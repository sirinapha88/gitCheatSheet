### Cheat Sheet

Whenever you're confused about git, come read this cheat sheet. Remember that all git commands can be run with the `--help` option. For example:

`$ git branch --help` or `$git log --help`

### Essential Git Commands

####Create a new git repository
`$ git init` - Create a new, local repository

#### Repo Status
`$ git status` - Check the status of your current repository and see which files have changed.

`$ git diff` - Show changes between commits, commit and working tree, etc.
#### Repo History
`$ git log` - Show commit logs

`$ git log --oneline --decorate --color --graph --all` - oneline shows the commit information on a single line making it easier to browse through commits at-a-glance. —decorate adds the names of branches or tags of the commits that are shown. —graph flag that will draw a text based graph of the commits on the left hand side of the commit messages

`$ git log -p [filename]` Display the patch representing each commit. This shows the full diff of each commit, which is the most detailed view you can have of your project history.

#### Stage files to commit
`$ git add <filename>` -  Add file contents to the index


`$ git add -A` -  - Tell the command to automatically stage files that have been modified and deleted, but new files you have not told Git about are not affected.


#### Commit changes in staged files
`$ git commit -m "<commit message>"` -- Record changes to the repository


#### Branching
`$ git branch <branch name>` - create branches

`$ git branch` -  List, create, or delete branches

`$ git checkout <branch name>` - Checkout a branch or paths to the working tree

#### Merging

`$ git merge <branch name>` - Join two or more development histories together


### Git Aliases
`$ git config --global alias.co checkout
`$ git config --global alias.br branch
`$ git config --global alias.ci commit
`$ git config --global alias.st status
