# Git & GitHub Introduction Workshop

Welcome to the COD Computer Science Club's Git & GitHub Introduction Workshop!

This activity is designed to give you hands-on experience with the fundamentals of Git and GitHub.

## What You'll Learn

By the end of this activity, you should understand how to:

* Create and work with a Git repository
* Track changes with Git
* Stage and commit changes
* View your commit history
* Connect a local repository to GitHub
* Push changes to GitHub
* Pull changes from GitHub
* Create and work with branches
* Create a Pull Request
* Merge changes
* Resolve a merge conflict
* Use a `.gitignore` file

---

# Part 1 — Get the Repository

Start by creating your own copy of this repository.

If you are working from the COD Computer Science Club's GitHub repository, **fork the repository** to your own GitHub account.

Then clone your fork to your computer.

Once you have cloned the repository, open the project folder in your code editor or terminal.

---

# Part 2 — Explore the Repository

Take a look at the files in this repository.

You should see:

```text
cod-cs-club-git-intro/
├── README.md
├── about-me.txt
└── projects.txt

---

# Part 3 — Check Your Git Status

Open your terminal in the repository folder.

Use Git to check the current status of your project.

Your goal is to determine:

* What branch are you currently on?
* Are there any files Git is currently tracking?
* Are there any untracked or modified files?

Record what you discover.

---

# Part 4 — Make Your First Change

Open `about-me.txt`.

Add your information to the file.

For example:

```text
Name: Your Name
Major: Your Major
Favorite Programming Language: Python
Why I am learning Git: I want to learn how developers collaborate on projects.
```

You may add additional information if you want.

After making your change, check the status of your repository.

Then inspect the difference between your current version and the previous version.

---

# Part 5 — Stage and Commit Your Change

Stage your changes and create your first commit.

Your commit message should clearly describe what you changed.

Example:

```text
Add personal information
```

After committing, check your Git history.

You should now be able to see your new commit.

### Checkpoint

At this point, you should understand:

```text
Working Directory
        ↓
     Staging
        ↓
      Commit
```

---

# Part 6 — Push Your Changes to GitHub

Your commit currently exists in your local Git repository.

Now send your changes to GitHub.

After pushing your changes, refresh your GitHub repository.

You should see your updated `about-me.txt`.

### Question

What is the difference between:

* A local repository
* A GitHub repository?

---

# Part 7 — Create a Branch

Now practice working on a separate feature.

Create a new branch called:

```text
add-projects
```

Switch to your new branch.

Verify that you are working on the correct branch.

---

# Part 8 — Add Your Project Ideas

Open `projects.txt`.

Add at least **three projects** that you would like to build.

For example:

```text
Projects I Want to Build

1. Python Data Analysis Project
2. Machine Learning Project
3. Web Application
```

You can replace these with your own ideas.

Stage and commit your changes.

Use a descriptive commit message.

---

# Part 9 — Push Your Branch

Push your new branch to GitHub.

Go to your GitHub repository and find your new branch.

Your `main` branch should not contain your new project ideas yet.

Your `add-projects` branch should contain them.

This demonstrates why branches are useful.

---

# Part 10 — Create a Pull Request

Create a Pull Request on GitHub.

Your Pull Request should request:

```text
add-projects → main
```

In your Pull Request description, explain:

* What you changed
* Why you made the change
* What files you modified

Review your changes and then merge the Pull Request.

---

# Part 11 — Update Your Local Repository

After merging the Pull Request on GitHub, return to your local repository.

Switch back to `main`.

Then retrieve the latest version of the project from GitHub.

Check your files.

Your `projects.txt` changes should now be present on your local `main` branch.

---

# Git Commands Reference

Here are some of the commands you will use during this activity:

```bash
git status
git add
git commit -m
git log
git diff
git push
git pull
git branch
git switch
git merge
```

If you get stuck, start with:

```bash
git status
```

Git will often give you useful information about what is happening.

---

# Final Takeaways

Remember these five concepts:

**Git** tracks changes to your project.

**A commit** is a saved snapshot of your project.

**A branch** allows you to work separately from another version of your project.

**GitHub** hosts your Git repositories online.

**A Pull Request** allows changes to be reviewed and merged into another branch.

Happy coding!
