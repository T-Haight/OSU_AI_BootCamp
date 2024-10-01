## Git Commands
- git diff

  diff of what is changed but not staged
- git add [file]

  add a file as it looks now to your next commit (stage) 
- git reset [file]

  unstage a file while retaining the changes in working directory
- git diff --staged

  diff of what is staged but not yet committed
- git commit -m “[descriptive message]”

  commit your staged content as a new commit snapshot
- git status

  show modified files in working directory, staged for your next commit
- git branch

  list your branches. a * will appear next to the currently active branch
- git branch [branch-name]

  create a new branch at the current commit
- git checkout [branch-name]

  switch to another branch and check it out into your working directory
- git merge [branch_name] 

  Join specified [branch_name] branch into your current branch (the one you are on currently).
- git branch -d [branch_name]

  Remove selected branch, if it is already merged into any other. -D instead of -d forces deletion.
- git push origin [branch-name]

  push your commit to the branch
- git fetch 

  Fetch changes from the remote, but not update tracking branches.
- git pull

  Fetch changes from the remote and merge current branch with its upstream.

## Linux Commands
- ls 

  list files and directories (-l: long format, -a: includes hidden files, -h: human readable file sizes, -lhtr: size date info.)
- cd [path] or cd ~ or cd ..

  change current directory to specified path, home directory for user, or up one directory level
- pwd

  print current working directory
- mkdir [directory]

  create a new directory
- rm [file] or rm -r [directory]

  remove files and directories (-f to force removal)
- cp [file] [destination] or cp -r [directory] [destination]

  copy files and directories to a specified destination
- mv [file] [new_file] or mv [file] [directory]

  rename file or move file to the specified directory
- touch [file]

  create an empty file
- echo "text" > [file]

  adds line of text into file (add another > to add text to second line, etc.)
- cat [file]

  view the contents of a file
- head [file] or head -n [n] [file]

  view the first 10 lines or n lines of a file
- tail [file] or tail -n [n] [file]

  view the last 10 lines or n lines of a file
- explorer [file] or explorer .

  opens a file or opens file explorer in the current directory

## VIM Commands
- Esc :w

  save
- Esc :x

  quit
