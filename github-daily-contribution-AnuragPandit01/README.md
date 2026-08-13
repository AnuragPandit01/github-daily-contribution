# GitHub Daily Contribution

**GitHub profile:** https://github.com/AnuragPandit01

This repository contains a GitHub Actions workflow that automatically creates
one contribution commit every day.

## Schedule

The workflow runs daily at **12:00 UTC (5:30 PM IST)** and can also be started
manually from the GitHub Actions tab.

## Setup

1. Create a public repository on **AnuragPandit01's GitHub account**.
2. Upload the contents of this project.
3. Go to **Settings → Secrets and variables → Actions**.
4. Create a repository secret named:

   `GH_COMMIT_EMAIL`

5. Set its value to the exact GitHub-associated commit email or GitHub-provided
   `noreply` email shown in your GitHub email settings.
6. Go to **Actions → Daily Contribution → Run workflow** to test it.

Using an email associated with the GitHub account is important because GitHub
uses the commit email to attribute commits to the account's contribution graph.
