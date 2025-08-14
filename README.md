What is a Pull Request (PR)?

A pull request is basically you saying:

“Hey, I made some changes in my branch. Can we merge them into your branch (usually main or develop)?”

It’s a way to propose changes, discuss them, and review code before actually merging them into the main project.

When Do You Use a Pull Request?

You made changes in a separate branch or fork.

You want someone (or yourself) to review before merging.

You want to keep a record of what changed and why.

How It Works in GitHub

You create a branch (say feature/login-system) from the main branch.

Make changes → commit → push your branch to GitHub.

Open a pull request from your branch → target branch (e.g., main).

Discuss & review

Other developers can comment, suggest changes, or approve.

Merge the PR once approved.

Delete branch (optional, but keeps repo clean).

Example Flow

Clone the repo and create a branch:

git checkout -b feature/add-search


Make changes → commit → push:

git add .
git commit -m "Added search feature"
git push origin feature/add-search


Go to GitHub → Click "Compare & Pull Request".

Fill PR details:

Title: Short summary (Add search feature).

Description: What, why, and any testing steps.

Assign reviewers → Wait for feedback.

Click "Merge" (once approved).

Why PRs are Important

Code Review → Spot bugs before they hit main.

Documentation → PR discussion keeps a history of decisions.

Collaboration → Team can track changes & reasoning.

💡 Tip: In open-source projects, PRs are also how outsiders contribute — they don’t directly push to your repo; they fork it, make changes, and send a PR for you to merge.
