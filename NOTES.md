Microsoft Windows [Version 10.0.19043.1165]
(c) Microsoft Corporation. All rights reserved.


# F:\SkyEye>git init -b MainBranch
Initialized empty Git repository in F:/SkyEye/.git/

# F:\SkyEye>git add .

# F:\SkyEye>git commit -m "Initial on Git."
[MainBranch (root-commit) 518b20f] Initial on Git.
 2 files changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Brain Storming for BillyCam.docx
 create mode 100644 README.md

# F:\SkyEye>git remote add origin https://github.com/NemoAng/SkyEye.git

# F:\SkyEye>git push -f --set-upstream MainBranch MainBranch
fatal: 'MainBranch' does not appear to be a git repository
fatal: Could not read from remote repository.

Please make sure you have the correct access rights
and the repository exists.

F:\SkyEye>git push -f --set-upstream MainBranch
fatal: 'MainBranch' does not appear to be a git repository
fatal: Could not read from remote repository.

Please make sure you have the correct access rights
and the repository exists.

F:\SkyEye>git push -f origin MainBranch
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (4/4), 1.53 MiB | 113.00 KiB/s, done.
Total 4 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/NemoAng/SkyEye.git
 + f12e233...518b20f MainBranch -> MainBranch (forced update)

F:\SkyEye>code .