# OverTheWire Bandit — Level 0

## Objective
Connect to a remote server via SSH and find 
a password stored in a readme file.

## Tools Used
- SSH client
- Linux terminal (WSL on Windows)

## Steps Taken

Step 1: Connected to remote server
ssh bandit0@bandit.labs.overthewire.org -p 2220

Step 2: Listed files in directory
ls
Result: readme file found

Step 3: Read the file contents
cat readme
Result: Password retrieved successfully

## What I Learned
- How SSH connects to remote servers
- Basic Linux navigation with ls and cat
- How hidden files work in Linux

## Real World Application
SOC analysts SSH into remote servers daily 
to investigate incidents. These exact commands 
are used in real investigations.
