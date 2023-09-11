# 2023-09-11-git_history

git commands
 - 'add <FILENAME>': adding the FILENAME to staging area
 - 'commit -m "MESSAGE': commit everything with a message to the staging area
 - 'push <WHERE> <WHAT>: pushes the history/commits to the remote (where) using the commits from the specified branch (what)
 - 'pull <WHERE> <WHAT>: pull (updates) the local repo with contents in the remote using the information in the specified branch (what)
 - 'log'
    -  'log - oneline' will help to pull one line of log
    - This may open a terminal program called 'less' that lets you scroll. Use 'q' to quit out of less.

- 'diff': will identify the changes in the local repo that is not added to git knowledge yet. This is comparing to the latest info that git knows about (added to staging area)
- 'diff -- staged': compare staged to committed. 
- "restore --staged <file>...": un-added the file from the staging area.
