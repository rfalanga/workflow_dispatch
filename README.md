# workflow_dispatch

I've known about GitHub Actions workflow_dispatch for over a year and have used it successfully. I want to mention that GitHub workflow_dispatch must be in a workflow in the default branch, or else it will not work!

Just yesterday I've learned that it is possible to use workflow_display with input parameters to the workflow. This is extremely handy, as that can be used to provide guidance to how to workflow works, without putting in lots of conditional logic in conjunction with GitHub Action variables. I've found a tutorial on this topic. This repo is my following along on tutorial [Add Inputs to GitHub Actions Workflows - GitHub Actions Tutorial](https://youtu.be/Sb_zLeHEVqQ?si=7hLDA9VrVoGMHnpP) by goobar.

(Taking from the video tutorial)

Fleible Workflows

- Enter tag names
- Select deployment environments
- Configure as needed
