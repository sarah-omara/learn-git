# learn-git
Repository for Practicing Git

## Setup
You can clone this repository using: `git clone`, cloning either with HTTP or SSH. To clone with HTTP, you can clone directly. To clone with SSH, you have additional steps:
- Generate an SSH Key:
```
ssh-keygen -t ed25519 -C “email”
```
- Copy the public part of they key:
```
pbcopy < ~/.ssh/id_ed25519.pub 
```
- Paste it on GitHub

## Update local config file
Ensure your git config (global, local) are what you want:
```
git config --global --list
```

Add your email and username to the local config if needed:
```
git config --local user.name "John Doe"
git config --local user.email YOUREMAIL
```
 