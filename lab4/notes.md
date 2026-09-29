**Question 1**
The `--global` flag applies your name and email to all Git repositories on your computer under your user account. If you left it out, the configuration would only apply locally to the specific repository you are currently working in.

**Question 2**
The `.git` directory appeared in the list. This hidden folder contains the entire history, tracking data, and internal metadata that Git uses to manage your repository.

**Question 3**
Git was offering to track hundreds or thousands of files. The vast majority of these were files from the `.venv/` directory, which contains third-party Python libraries that I did not write.

**Question 4**
The `.venv/` folder and any other files matching the patterns in the `.gitignore` file (like `__pycache__/`) disappeared from the list of untracked files. 

**Question 5**
The `.gitignore` file should be committed, not ignored. It needs to be part of the repository's history so that anyone else working on the project (or yourself on a different computer) will automatically ignore the exact same files.

**Question 6**
`README.md` moved from "Untracked files" to "Changes to be committed". In the three-places model, it moved out of the Working Directory and into the Staging Area.

**Question 7**
Git printed the branch name, a short unique commit hash, the commit message, and a summary of what changed. It also stated exactly how many files were changed and the number of insertions/deletions.

**Question 8**
The first seven characters are called the commit hash (or SHA-1 hash). They act as a unique identifier for that specific snapshot in your repository's history so you can always refer back to it. 

**Question 9**
The four steps are: 
1. Work on your files (Working Directory).
2. Check the current state using `git status`.
3. Add the files you want to save using `git add` (moves to Staging Area).
4. Save the snapshot permanently using `git commit -m "message"` (moves to Repository).

**Question 10**
`README.md` gets a special name because platforms like GitHub automatically look for it and display it on the front page of the repository. It serves as the immediate introduction and documentation for anyone visiting the project.

**Question 11**
`gh auth login` securely connected your terminal to your GitHub account using a web browser and saved an authentication token on your machine. Git uses this secure token to verify who you are, bypassing the need to type a password every time you push.

**Question 12**
The formatted contents of `README.md` are showing on the front page. GitHub automatically renders this file to give visitors a quick, easy-to-read overview of what the repository contains.

**Question 13**
No, pushing did not change your local history at all. It simply copied your local commit history and uploaded it to the remote repository on GitHub to keep the two synchronized.

**Question 14**
A private repository exists securely on GitHub's cloud servers and can be viewed by you and anyone you explicitly invite. A repository that does not exist on GitHub at all only lives locally on your laptop's hard drive and cannot be shared or backed up online.
