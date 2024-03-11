# *Guidelines for Research Assistants* <!-- omit from toc --> 

Welcome to the guidelines for research assistants and research managers. This document will help you understand the expectations and responsibilities of your role, as well as some tips and best practices to make your work more efficient and effective. This includes guidelines on organization and dealing with regular administrative tasks, keeping files organized, coding best practices, and conducting surveys. 

One of the most important things to keep in mind when working with professors is that they are extremely busy. They have many competing demands on their time and attention, such as teaching, traveling, presenting at seminars and conferences, meeting, applying for grants, managing research and teaching assistants, advising, overseeing projects, recruiting, reviewing, serving as discussant, writing papers, and more. These activities require a lot of time, energy, and focus. They also involve a lot of coordination, communication, and collaboration with other people. Follow this guide as closely as possible to help create a smooth workflow in the project, and always remember to be proactive with research tasks and communication.

Contents:
1. [Administrative tasks](#1-administrative-tasks)
    1. [Managing meetings](#i-managing-meetings)
    1. [Timesheet and recap backup](#ii-Timesheet-and-recap-backup)
    1. [Presenting results to PIs](#iii-presenting-results-to-pis)
2. [General project organization](#2-general-project-organization)
    1. [GitHub](#i-github)
    1. [Dropbox](#ii-dropbox)
    1. [Overleaf](#iii-overleaf)
3. [Acknowledgments](#3-acknowledgments)

# 1. Administrative tasks
## i. Managing meetings
1. **Send meeting agendas before meetings.** 
    - Send a meeting agenda **between one and two hours before each meeting** with detailed items to discuss in the meeting and attaching all content relevant to the meeting. This timing works well for PIs to be reminded about the call and have enough time to look at the agenda.
    - An easy way to remember to send meeting agendas is to set a calendar event with an email reminder for the agenda a couple of hours before each regular meeting.
    - You can keep track of content for each meeting.

2. **Send meeting recaps after meetings.**

    These recaps should have (1) detailed notes, with (2) actionable tasks, (3) tasks and conclusions posted in GitHub Issues and (4) be backed up in a Google Docs:
    1. **Detailed notes**. Send a meeting recap after each meeting with detailed notes about what was discussed in each meeting. You can take notes during meetings and record more complicated or important meetings that you might want to review afterwards. Send this recap as soon as possible after the meeting.
    2. **Organizing recaps**. Each item should have a discussion and tasks section. In the discussion section, write comments when possible as problem + potential solution. Here is an example of a recent recap:
    
        <img src="https://github.com/skhiggins/ra_guide/blob/main/pictures/meetings/meeting_1.png" align="center" height="60%" width="60%">

    4. **Create GitHub Issues for tasks and conclusions**. Immediately create GitHub Issues for the tasks discussed, and post a summary of the discussion under GitHub Issues. 

    5. **Back up to Google Docs**. Upload summaries to a Google Docs document, and include this link in all recap emails.

    If you use Apple Mail, you can create email templates for meeting agendas and recaps that are easy to fill out. You can find a guide for this [here](https://www.ericleeclark.com/create-email-templates-in-apple-mail-mojave/) and an example below:

   <img src="https://github.com/skhiggins/ra_guide/blob/main/pictures/meetings/meeting_3.png" align="center" height="40%" width="40%">

## ii. Timesheet and recap backup

The timesheets and recaps should be saved in a separate **Google Drive folder**. Specifically:

- Create a Google Sheet to write the timesheet for each week. You can find a template [here](https://docs.google.com/spreadsheets/d/1p3uaH4eAx_NmvJYl7v-tFmFRr55drqjfjRiFAG7Ut70/edit#gid=0).
- Create a Google Doc to save *all* the weekly recaps. See examples [below](#examples-of-the-weekly-recaps).
- Create a folder in Google Drive that contains the Google Sheet of the timesheet and the Google Doc of the weekly recaps.

Please share the Google Sheet of the timesheet and the Google Doc of the meeting recaps with me. You do **NOT** need to email them to me. 

> **Tips on Google Sheet shortcuts:** Click `Ctrl+;` to enter the current date, and `Ctrl+Shift+;` to enter the current time.

## iii. Presenting results to PIs

### Comments in GitHub Issue
Below are some key rule of thumbs but please also read [Best Practices for GitHub Issues Management](https://tilburgsciencehub.com/topics/automation/version-control/start-git/write-good-issues/) for detailed instructions and demonstrations.
1. Give context – what was the last decision made on how to do the task? What specific functions did you accomplish?
2. Be concise, but offer sufficient detail to understand both the problem and the solution.
    a. If there is detailed documentation that you want your PI to look at, link it in your comment.
3. Always propose potential solutions (ideally, more than one). Include enough information about the solutions for someone who hasn’t done the research to understand pros/cons, trade-offs and make a decision.
4. Avoid open-ended questions. Try to always be as specific as possible when making a question.
5. It is OK to follow-up if this is important and you have not received an answer.
6. When posting results you should describe the main findings. 

### Reports
1. When creating a report that include regressions, plots of the questions, descriptive statistics, etc, make sure that every variable is labeled correctly. A variable named q2_58 is not descriptive enough. You should provide the meaning of that variable, and if any clarification is necessary you should include it as a footnote. 
2. Make the information easily available. You can include hyperlinks to the sections or to each result. 
3. Any additional information that the PI's should know relevant to the report should be included in it. 

### Tables and figures
1. Your tables and figures should be correctly labeled. You should include descriptive names, relevant footnotes, labeled axes, etc.
2. Before presenting your results, you should always review your results to catch any error. You should check the number of observations, the size of the coefficients, etc. In general, think about it as your research. Do not only produce what you are told to, try to understand if your results make sense. 
3. Check for outliers and understand the sample that is being used in each regression table/figure.

# 2. General project organization
In academic projects, it's essential to keep reports, codes, results, data well organized and maintain a clean and well-documented track of progress. This helps other collaborators, both RAs and PIs, to stay updated and facilitate smooth collaboration. It also helps yourselves to keep track of progress when you work on multiple projects simultaneously. We accomplish this with the help of Dropbox, GitHub, and Overleaf (or other local latex compiler when you don't need collaboration when creating LaTex files).

- Each GitHub repository should be linked to a a Dropbox folder.
- Each GitHub issue should have a corresponding Dropbox folder within the corresponding repository folder. Each issue should contain links to relevant GitHub repository folders and files.
- Dropbox folder stores data and all the files you create for the project.
- The GitHub repository stores the structured folder but no **data**. Strutured folders are those corresponding to GitHub issues and is well organized so that it is clear what are the codes to solve the issue, what are the results, and what is the report.

## i. GitHub
GitHub is used to help facilitate sharing results and scripts with PIs and other research assistants, ensuring reproducibility of code, and having an up-to-date backup of current work, along with version control. Below are some of the key commands we will need for GitHub. Please click [here](https://github.com/xyzhang9/RA_Guidance_XYZ/blob/main/git.md) for more details on how to get started with GitHub (and Git which is mechine behind GitHub).

### Setting up a new repo on GitHub and cloning locally
1. Create new repo on GitHub, including a template `.gitignore` file (use corresponding Python, R or Stata template). The `.gitignore` file determines which files and folders will be ignored in every update. You should include the folders `data` and `proc` in the `.gitignore`. Additionally, there might be some file types you want to ignore (for example, auxiliary LaTeX files). The set of files to ignore will change depending on the project. 

2. Type the following commands in terminal:
    1. Change to directory where repo will be cloned 
        ```sh
        cd work
        ``` 
    2. Clone repo
        ```sh
        git clone https://github.com/user123/myproject
        ```
        
#### Creating a local repository:
Type the following commands in the terminal:
1. Change to directory where repo will be cloned 
    ```sh
    cd work
    ``` 
2. Clone repo
    ```sh
    git clone https://github.com/user123/myproject
    ```

### Updating the GitHub repo
First, modify files locally. Then, type the following commands in the terminal:
1. Change directory to project folder
    ```sh
    cd work/myrepo
    ``` 
2. Add new and modified files
    ```sh
    git add .
    ``` 
3. Review added files
    ```sh
    git status
    ``` 
4. Commit files and add a message
    ```sh
    git commit -m “This message describes what was changed in the current commit"
    ``` 
5. Get most up to date code from remote repo.
    ```sh
    git pull
    ```
6. Push changes to remote repo
    ```sh
    git push
    ```

### Creating a fork of a repo and making a pull request    
To make changes in repos where you are not the collaborator, you need to fork (create your own version of) the repo, make changes, and make a *pull request* to merge these changes back into the original repo. Follow these steps to fork a repo and create a pull request:

1. Install the [GitHub Command Line Interface (CLI)](https://cli.github.com/). If you have [Homebrew](https://brew.sh/) installed (on Mac OS X), you can install by typing on the command line `brew install gh`.
2. [Fork the repo](https://docs.github.com/en/get-started/quickstart/fork-a-repo)
    ```sh
    gh repo fork https://github.com/otheruser/repo_a
    ``` 
3. Clone forked repo
    ```sh
    git clone https://github.com/myuser/repo_a
    ``` 
4. Change directory to local folder
    ```sh
    cd repo_a
    ``` 
5. Make changes to files locally 
6. Add, commit and push changes. This updates files on your own fork of the repo.
7. Change directory to local folder
    ```sh
    git add .
    git commit -m “Add a message here”
    git push
    ```   
8. Create [pull request](https://cli.github.com/manual/gh_pr_create). Add title, insert details in body (if necessary) and submit pull request. Select other user’s repo as base repo.
    ```sh
    gh pr create
    ```   

## ii. Dropbox
Please sign up [here](https://www.dropbox.com/dropbox) if you don't have a Dropbox account. A free Dropbox account should give you 2 GB of cloud storage. It should be enough for our purpose.

## iii. Overleaf
Please sign up [here](https://www.overleaf.com/register) if you don't have an Overleaf account. When you don't need to collaborate with other people when creating reports, you can use other local latex compiler such as Tex Maker. However, it is recommended to use Overleaf if you have no/little experience with LaTex.

# 3. Acknowledgments
This guide is inspired by and adapted from Sean Higgins GitHub Repository [ra_guide](https://github.com/skhiggins/ra_guide).
