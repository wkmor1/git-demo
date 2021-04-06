# Intro to Git

## 1: Reasons to use Git/GitHub

1. Backing-up your work
2. Tracking changes
3. Collaborating on work with others
4. Making work public

## 2: What is a git repository?
  
A directory containing:

1. The files being tracked
2. A subdirectory called `.git` containing:
    1. The data needed to move back (and forward) through the tracked changes.
    2. The data needed to move between branches (alternate histories of the tracked files)
    3. Configuration data (username, location of a remote version of the repository, etc.)

## 3: What is git?

Software to manage a git repository and syncronise local and remote copies.

## 4: What is GitHub

1. An place to store remote copies of git repositories.
2. A suite of tools to manage remote repositories and collaborate with others on them.
3. More tools to do things with the contents of remote repositories (github actions, github pages, etc.) 

Other alternatives include GitLab, Bitbucket etal.

## 5: Installing Git

[Install Git](https://github.com/git-guides/install-git)

## 6: Essential git commands

1. git clone
2. git add
3. git commit -m
4. git push
5. git pull 

## 7: A typical git/Rstudio workflow

1. Have some work to start tracking with git.
2. Create a new repo on GitHub.
3. Start a new project in Rstudio.
4. Move files to new folder.
5. Commit files.
6. Push the changes.

## 8: Writing good git commit messages

  1. Title + description (optional).
  2. Use active future tense for title.
  3. Start title and description with uppercase letter.
  4. Don't end the title with a full stop (do end the description with one though).
  5. Use a title with 50 characters or less.
  6. Blank line after title.
  6. Use hard line endings at 50 characters or less for the description

### Example commit message
```
Add a new README file

Have added a new README file that describes how
one can use git/GitHub. The README includes an
example of making a commit message.
```

## 9: Next steps

  1. [Using git branches](https://www.atlassian.com/git/tutorials/using-branchesgith)
  2. [Issues](https://docs.github.com/en/github/managing-your-work-on-github/about-issues)
  3. [Pull Requests](https://docs.github.com/en/github/collaborating-with-issues-and-pull-requests/about-pull-requests)
  4. [GitHub Actions](https://github.com/r-lib/actions)
  5. [GitHub Pages](https://guides.github.com/features/pages/)
