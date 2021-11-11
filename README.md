# Blended-Data
Testing version control and we will be adding to it
Nov 11/21 I seem to have screwed up my SSH Key after moving directories around.  I didn't like that Git Bash was putting new folders (i.e. blended for example) directly in my user account so I created a folder C:\Users\Greg\Carleton and then used the mv command in Git Bash to move blended under Carleton.  I then created a new folder under Carleton called class_repository that I was going to add files to.  The clone failed:
Greg@Greg-ThinkPad MINGW64 /c/users/greg/carleton/class_repository
$ git clone git@carleton.bootcampcontent.com:carleton-university/CARL-VIRT-DATA-PT-11-2021-U-B.git
Cloning into 'CARL-VIRT-DATA-PT-11-2021-U-B'...
The authenticity of host 'carleton.bootcampcontent.com (67.205.184.193)' can't be established.
ED25519 key fingerprint is SHA256:PTbbcqU8ot5BxH05Zd2A/OkeOuHz9WiX+4cLNoNi2HQ.
This key is not known by any other names
Are you sure you want to continue connecting (yes/no/[fingerprint])? yes
Warning: Permanently added 'carleton.bootcampcontent.com' (ED25519) to the list of known hosts.
git@carleton.bootcampcontent.com: Permission denied (publickey).
fatal: Could not read from remote repository.

Please make sure you have the correct access rights
and the repository exists.

I then created a new key for while in the class_repository directory and tried again:

$ git clone git@carleton.bootcampcontent.com:carleton-university/CARL-VIRT-DATA-PT-11-2021-U-B.git
Cloning into 'CARL-VIRT-DATA-PT-11-2021-U-B'...
git@carleton.bootcampcontent.com: Permission denied (publickey).
fatal: Could not read from remote repository.

I have made these changes to the readme.md file to see if I can push them to my account
