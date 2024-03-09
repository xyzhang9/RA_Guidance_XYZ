# Instructions on Git

## Why git?
- Versioning: no more files with name such as `assignment_version3a_draft_Feb2018.m`. Can easily go back to any past version of files
- Documented collaboration
- Project organization
- Convenient online and offline access
- Easier collaboration

## Git command (Git Bash or Git CMD)
[A very good guidance to Git](https://www.youtube.com/watch?v=SWYqp7iY_Tc)

### Getting started

1. Open an account on https://github.com/

2. Download git to your computer from https://git-scm.com/downloads

3. Set up Git's initial settings, so that it doesn't ask you for your details every time you pull and push.
	- [Link to OS-specific instructions](https://help.github.com/articles/caching-your-github-password-in-git/#platform-mac)
    - [A general guide for Git's initial settings](https://git-scm.com/book/en/v2/Getting-Started-First-Time-Git-Setup)
    - [Avoiding replaetedly typing in username and password](https://git-scm.com/docs/gitcredentials)

### Setting up a repository:

1. Create a repository on GitHub. Typically you would want the `readme.md` and `.gitignore` files.
2. Open Git bash (I prefer this) or Git CMD and locate to a directory where you'd like to store your local repository. 
3. Clone the repository into a local machine: `git clone https:\\github.com\emanMarcu\repo.git`

### Typical repeated workflow after creating up a repository:

1. Pull: `git pull`
1. Add: `git add .`
1. Commit (with message) `git commit -m "short message" -m "long message"`
    - Commit often
    - [Tips for useful commit messages](https://chris.beams.io/posts/git-commit/)
1. Push: `git push`

- Use **Issues** for assignment-specific communciation:
	1. Among team members.
	2. Between team members and instructors.
    
- Later in the course we may discuss **branching**. But for now, the aformentioned workflow is sufficient. But you can get an idea how it works from the video above.

### Conflicts
You may run into conflicts every now and then. The link below explains how to resolve conflicts in merges but it works for conflicts from pull request.

- [On Github](https://www.youtube.com/watch?v=JtIX3HJKwfo)
- [Using Git bash](https://www.youtube.com/watch?v=iRyUUGsNHrU)

## Github Desktop
Alternative to using Git bash or Git CMD, you could download Github Desktop.

[A nice guide to Github Desktop](https://www.youtube.com/watch?v=77W2JSL7-r8)
