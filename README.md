# What I Learned About GitHub


This repository was created as part of a GitHub familiarization task. I made this to get hands-on experience with GitHub by actually using its core features rather than just reading about them. Below I have documented everything I did and what I learned along the way.

---

## What I Did

### 1. Created a Public Repository

I started by creating a new public repository named **github_practice_thanujsilla** on GitHub. I initialized it with a README file directly from the GitHub web interface. This was my first time setting up a repo from scratch and I got to understand what a repository actually is — a place where all your project files and their history are stored.

---

### 2. Created 3 GitHub Issues

After creating the repo, I opened the Issues tab and created three issues to track the tasks I needed to complete:

- **Issue #1 — Add project documentation:** To remind myself to write proper documentation for the project.
- **Issue #2 — Learn Git branching:** To explore how branches work in Git and GitHub.
- **Issue #3 — Explore GitHub Actions:** To look into how automated workflows are set up.

Creating issues helped me understand how teams track work and bugs in a structured way. Each issue gets its own number and a comment thread where discussion can happen.

---

### 3. Created the Project Structure

I added two folders to the repository — `docs/` and `notes/`. One thing I learned here is that GitHub does not allow empty folders, so I created a `README.md` file inside each folder to make them appear.

I did this by clicking **Add file → Create new file** and typing `docs/README.md` in the filename — the moment I typed the `/`, GitHub automatically converted it into a folder. I repeated the same for `notes/README.md`.

The final structure looks like this:

```
github_practice_thanujsilla/
│
├── README.md
├── docs/
│    └── index.html
└── notes/
     └── 
```

---

## What I Learned About GitHub

### Repositories
A repository is essentially a project folder that lives on GitHub. It stores all the files of a project along with the complete history of every change made to them. Repositories can be public (visible to everyone) or private (visible only to you and invited collaborators).

### Issues
Issues are GitHub's way of tracking tasks, bugs, and ideas within a project. Every issue has a title, a description, and a unique number. You can assign issues to people, add labels to categorize them, and have discussions in the comment section. I found issues very useful for staying organized — even for a solo project like this one.

### Pull Requests
A Pull Request (PR) is how you propose changes to a repository. When I finish working on a separate branch, I can open a PR to request that my changes be reviewed and merged into the main branch. PRs are the core of collaboration on GitHub — they allow teammates to review code, leave comments, and approve changes before anything gets merged.

### Branches
A branch is an independent copy of the repository where I can work on something without affecting the main code. The default branch is called `main`. The idea is that I create a new branch for each feature or fix, work on it separately, and then merge it back into `main` once it's ready. This keeps the main codebase stable at all times.

### Forks
A fork is a personal copy of someone else's repository. If I want to contribute to an open-source project, I fork it first — this gives me my own copy where I can freely make changes. Once I'm done, I can open a Pull Request to suggest my changes to the original repository. Forking is what makes open-source contribution possible on GitHub.

### GitHub Projects
GitHub Projects is a built-in project management board that comes with every repository. I can add my issues and pull requests to a board and organize them into columns like **To Do**, **In Progress**, and **Done**. It works similarly to tools like Trello and helps track the overall progress of a project at a glance.

---

## Reflections

This task gave me a solid practical foundation in GitHub. Before this, I had only a surface-level idea of what these features were. Actually creating issues, setting up folders, and exploring the interface made everything much clearer. I now feel comfortable navigating a GitHub repository and understanding the purpose of each feature.
