#Commitment_issues_ctf
- This challenge focuses on version control system (VCS)
- VCS helps us keep track of changes made in a file.
---



#Challenge description
- I accidentally wrote the flag down. Good thing I deleted it!
- You download the challenge files here:
- challenge.zip
---



#Environment
- Host Machine: Windows 10 with Oracle VirtualBox
- Guest: Ubuntu 20.04 LTS (CLI-based)
- Access: SSH via PuTTY
---


#Steps Taken
- Downloaded file from picoctf and extracted it
- Added the extracted folder to Oracle as a shared folder and moved it to a home directory
- Checked the file history with git log
- Used commit id to navigate through the .txt file history.
- Encountered stash error, and used git stash to make file changes in a separate branch.
- Read the .txt file again with cat, and found the flag
---


#Lessons Learned
- Version control system allows us to work separately  from the main branch.
- The git checkout <commit id> command is used to check the different types of changes made in a file.
- To confirm the file history and access previous commits, use: git log <file>
---


#Flag
- picoCTF{[REDACTED]}



---
