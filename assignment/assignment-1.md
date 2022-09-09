### Question 1

~---> Before start, Make sure you are in your branch. If not, `git checkout -b {your-name-and-lastname}`,

==> `cd ~` to navigate root folder\
==> Create a folder called m922-git\
==> Navigate into the m922-git folder\
==> Create a file called third.txt\
==> Initialize an empty git repository\
==> Add third.txt to the staging area\
==> Commit with the message "adding third.txt"\
==> Check out your commit with git log\
==> Create another file called fourth.txt\
==> Add fourth.txt to the staging area\
==> Commit with the message "adding fourth.txt"\
==> Remove the third.txt file\
==> Add this change to the staging area\
==> Commit with the message "removing third.txt"\
==> Check out your commits using git log\
==> Write the command to list all of the global configurations for git on your machine. You can type git config --global to find out how to do this.

### Answer 1

~---> When you done, put `assignment-1.md` file on staged are, then commit it in your branch.\
~---> Please write your commands under this line.\
~---> `git push -u origin {your-name-and-lastname}` once you commit ...

1. cd ~
2. mkdir m922-git
3. cd m922-git
4. "" > third.txt
5. git init
6. git add .
7. git commit -m "adding third.txt"
8. git log
9. "" > fourth.txt
10. git add .
11. git commit -m "adding fourth.txt"
12. rm third.txt
13. git add .
14. git commit -m "removing third.txt"
15. git log
16. git config --global --list