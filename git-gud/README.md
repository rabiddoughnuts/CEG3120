# Git-Gud Guide

- [Command Line](#Command-Line)
- [Files & Folders](#Files-&-Folders)
- [GitHub](#GitHub)

## Command Line

- Status  : Displays differences between index file and current commit.  
- Clone  :  Clone a repository into a new directory.  
- Add  :  Add file contents to index.  
- RM  :  Remove files from working tree and index.  
- Commit  :  Record changes to repository.  
- Push  :  Update remote references and associated objects.  
- Fetch  :  Download objects and references from another repository.  
- Merge  :  Join two or more development histories.  
- Pull  :  Fetch from and integrate with another repository.  
- Branch  :  List, create or delete branches.  
- Checkout  :  Switch branches or restore working tree files.  
- Init  :  Create empty repository or reinitialize and existing one.  
- Remote  :  Manage set of tracked repositories.  
 

```
# Markdown Guide
## Headers
### Bulleted
```

## Files & Folders

- .git Folder  :  this contains all the setup and tools for Git and tracks all changes, commits etc for the repository.  
- .gitignore File  :  Tells Git to ignore files containing whatever patterns listed in this file.  
- .git/hooks  :  Sample scripts that can help you change Git behaviour.

Put two spaces after this line followed by `Enter` to start new line.  

Just hitting the enter key doesn't work  
   
## GitHub

- Pull Request  :  `Git pull` will pull and copy all info from remote repository, generally GitHub, for whichever working tree I am currently on.  
- SSH authentication to repositories  :  `ssh -i privkey remoteuser@host` remoteuser@host is under `<>Code` button on github, but would be username and ip address for a repo I made on, aws, for instance.  

