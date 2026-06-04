---
Before Day-5
---
I already knew the basics of making commits, handling simple pushes, and organizing project code across repositories. I also had experience managing local repositories for my previous software and web development projects.

---
## Day-5 Checklist
- [x] I have set up the basic Git configuration using `git config --global user.name "Your Name"`, `git config --global user.email "your.email@example.com"`, and set the default branch as main using `git config --global init.defaultBranch main`
- [x] I know GitHub allows only one user account per person, so I have merged my accounts (IITM and personal) into a single unified account
- [x] I understand the three states of a file in Git: working tree → staging → committed
- [x] I can run the daily workflow commands `git status`, `git diff`, and `git log` and know what each shows
- [x] I know how `.gitignore` works and how to use it to ignore files and folders that should not be pushed to the remote repository (e.g., `venv`, `__pycache__`, `.env`)
- [x] I can make a commit: `git add` → `git commit -m "message"` → `git push`
- [x] I know what `origin` and `main` are and can explain them in one sentence each
- [x] I can set up SSH key authentication and push to GitHub without entering a password
- [x] I can create an annotated tag (`git tag -a v0.1.0`) and push it to GitHub
- [x] I can write a meaningful commit message (not "fixed stuff" or "final.py")

---
After Day-5
---
I learned these things as well, apart from the checklist:
* Structuring clean release versioning locally and pushing annotated release points using `git push origin --tags`.
* Navigating Git's precise internal lifecycle stages (working directory vs. index/staging vs. HEAD history tracking) to better manage complex file modifications.

------
Feedback (Suggestions for the TDS Team)
---
The instruction regarding unifying academic and personal GitHub accounts is highly practical advice for maintaining a clean, lifelong professional portfolio without losing student-verified project records.

---------
### Personal Notes
* **Origin:** The default shorthand alias pointing to the remote repository URL hosted on GitHub.
* **Main:** The default primary development branch containing the production-ready source history.
* Quick command to push a specific tag: `git push origin v0.1.0`
* Always configure `.gitignore` *before* staging files, because tracking existing files requires clearing them out of the cache with `git rm --cached`.
