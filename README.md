# git-demo

Some Content Added!

This Repo is all about learning Git Version Control!

## Generating pair of SSH Key

This key is used to securely authincate your machine to your github account

1. "ssh-keygen -t rsa –C "[your email address]"

> Reminder This command will generate 2 files, you must open one file ending with .pub extension. after that copy everything there and go in your account Settings -> SSH and GPG keys -> New SSH key -> Enter Name in first fild and paste your copied key in second field -> Add SSH Key. That's it!

2. For Credententials

   git config --global user.name “[Your Name]“

   git config --global user.email “[Your Email]"
