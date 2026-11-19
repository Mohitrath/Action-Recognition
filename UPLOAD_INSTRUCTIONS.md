# Upload this project to GitHub

Destination: https://github.com/Mohitrath/Action-Recognition

1. Unzip `Group20_Ready_For_GitHub.zip`.
2. Open the extracted `Course_Project_Group_20` folder.
3. On Windows, double-click `PUSH_TO_GITHUB.bat`.
   On Linux/WSL, run `bash publish_to_github.sh`.
4. Git may open a sign-in window to authenticate your GitHub account.
5. Refresh the repository page after the script reports success.

The destination repository was initialized with a .gitignore file. The scripts fetch the current main branch before committing project files.
These scripts preserve existing files and upload the source code, app, research papers,
reports, poster, test assets and result files that are included in this package.
Git will not include ignored secrets or local environments.

If Git reports "Author identity unknown", run:
    git config --global user.name "Your Name"
    git config --global user.email "your-verified-github-email@example.com"
Then run the script again.

This public repository will expose its contents to anyone. Review included
third-party research PDFs and other source material for redistribution rights before pushing.
This ZIP does not contain the trained model checkpoint.
