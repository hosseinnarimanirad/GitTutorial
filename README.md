# Git Tutorial

## File/Change States

![circle](https://user-images.githubusercontent.com/7770893/204490406-c9deb570-6a5a-41ed-9312-8a24297d0c24.png)


- **untracked:** new files in a directory that has not been tracked (excluding ignored files)
- **unstaged:** new changes on tracked files that have not been staged or stashed
- **staged (new file):** staged new files that does not exists in local or remote repository (e.g. using `git add` command)
- **staged:** staged changes (excluding new files) (e.g. using `git add` command)
- **committed:** new files or changes that have been committed (e.g. using `git commit` command)
- **published:** pushed commits (using `git push` command)
 
 
### How git commands affect files in git 
Follow the colors to see how you can traverse between different states.

## Example 1
Using `git restore .` discards changes on unstaged changes and does not affect untracked or staged, or committed changes.

## Example 2
`git reset --mixed HEAD~1` causes newly added files that have been staged to be untracked and also unstage all commited or staged changes

![image](https://user-images.githubusercontent.com/7770893/201478926-e8d03f6e-ad0e-420f-9456-87f871f7d4fe.png)

### Full Version

![image](https://user-images.githubusercontent.com/7770893/201986211-09869338-b2f4-4686-85ff-20ee06e23382.png) 

