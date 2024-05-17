# The basic Git Workflow

This document covers all commands of a basic Git workflow, that we have learned in class, so far. It also contains a few additional explanations about the commands for a better understanding.

## Overview of Commands

The synthax to use a command is:
```console
git <command>
```
| Command | Explanation |
| :------ | :---------: |
| add . | add the whole content of the directory to the staging area |
| add \<filename\> | add a certain file to the staging area |
| diff | view the changes that COULD be added next to the staging area, but haven't been so far | 
| diff --cached | view the changes that are staged for the next commit relative to **HEAD** <br> (**staged** is a synonym for **cached**) |
| status | view the state of the working directory and the staging are<br>(which changes have been staged, which haven't,<br> and which files aren't being tracked by Git) |
|  commit -m "short, but meaningfull comment"| transer the changes to the local repository |
| log | show the commit history |
| log --pretty=oneline | easier to read commit history, because every commit is on 1 line |
| push | upload the changes to the remote repository |

## Overview of a basic Git Workflow

![git_workflow_overview](explained-git-basic-workflow.png)

## Further Information

Click on a link to get further information about the command [add](https://git-scm.com/docs/git-add), [diff](https://git-scm.com/docs/git-diff), [status](https://git-scm.com/docs/git-status), [commit](https://git-scm.com/docs/git-commit), [log](https://git-scm.com/docs/git-log) or [push](https://git-scm.com/docs/git-push).