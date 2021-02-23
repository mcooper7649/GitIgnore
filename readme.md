### Git | gitignore
---

1. Why do we want gitignore?
    - With public repos we want to hide certain files from being uploaded to git.

2. This prevents hackers from finding Passwords, API Keys, or other sensitive information.

3. Utilities Files or Local Settings are commonly added to gitignore
    - .DS_STORE files are common files to see added to gitignore

4. To create a gitignore, we need to create a hiddle file called .gitignore   // Case Sensitive

5. files added to .gitignore are case sensitive and need to be on their own line.



### Git | Gitignore Challenge
---

1. Create a directory called project
2. Create 4 files, file1, file2, file3, and secrets.txt
3. Create gitignore
4. git add all the files
5. git rm --cached -r   to remove what we added, so we can add our ignore preferences.
6. git status again to confirm we  have nothing added
7. add each filename to a new line // Case matters
8. 