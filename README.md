# Global_Configuration
Used for personal customization and configuration 

##  AWS CLI Configuration

```css
vim ~/.bashrc
```
input the following

```
alias aws='aws --output text'
alias del-volume='aws ec2 delete-volume --volume-id'
alias instance='aws ec2 run-instances --image-id' 
alias instances='aws ec2 describe-instances'
alias term-instances='aws ec2 terminate-instances --instance-ids' 
alias start-fedora='instance ami-0187f76b --instance-type t1.micro' 
alias start-freebsd='instance ami-d0b520b8 --instance-type t1.micro' 
alias start-netbsd='instance ami-569ed93c --instance-type t1.micro' 
alias start-omnios='instance ami-50ecc847 --instance-type t1.micro' 
alias start-ubuntu='instance ami-6de0dd04 --instance-type t1.micro' 
alias start-amazonlinux='instance ami-0b33d91d --instance-type t2.micro'
alias securitygroups='aws ec2 describe-security-groups'

alias volumes='aws ec2 describe-volumes' 

```

restart bashrc
```css
. ~/.bashrc
```
