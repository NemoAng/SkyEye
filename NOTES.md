Microsoft Windows [Version 10.0.19043.1165]
(c) Microsoft Corporation. All rights reserved.

## F:\SkyEye>git init -b MainBranch

Initialized empty Git repository in F:/SkyEye/.git/

## F:\SkyEye>git add .

## F:\SkyEye>git commit -m "Initial on Git."

[MainBranch (root-commit) 3b34fe1] Initial on Git.
3 files changed, 42 insertions(+)
create mode 100644 Brain Storming for BillyCam.docx
create mode 100644 NOTES.md
create mode 100644 README.md

## F:\SkyEye>git remote add origin https://github.com/NemoAng/SkyEye.git

## F:\SkyEye>git push -f origin MainBranch

Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 4 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (5/5), 1.53 MiB | 112.00 KiB/s, done.
Total 5 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/NemoAng/SkyEye.git

- 28b90c2...3b34fe1 MainBranch -> MainBranch (forced update)

## F:\SkyEye>code .
