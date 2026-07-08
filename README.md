# Tech Journey: Learn Git, Copilot, and GitHub

Git and GitHub are used by every professional software developer in the world. In this course, you will learn to use them too — working in a real cloud development environment with an AI assistant, all the way to opening a real Pull Request on GitHub.

---

## Before You Start

**You need two things:**

1. **A GitHub account** — Create a free one at [github.com](https://github.com) if you do not have one yet.
2. **A computer** — Any operating system works: Mac, Windows, or Linux/Chromebook.

**No prior experience required.** Everything runs in your browser — no software to install.

---

## How This Course Works

1. **Fork this repo** (Step 1 explains how) to create your own personal copy on GitHub.
2. **Launch a Codespace** — a full development environment that runs in your browser (Step 2).
3. **Set up GitHub Copilot**, your free AI assistant, and use it throughout the course (Step 3).
4. **Work through each step** in order, at your own pace.
5. **GitHub Actions automatically checks your work** when you push — you will see a green checkmark or a red X with hints in the Actions tab.
6. **Open a Pull Request** at the end so your instructor can review your work.

> **Why a Codespace?** GitHub also has a lightweight browser editor (github.dev, opened by pressing `.`), but it cannot run code or use Copilot. A **Codespace** is a full development environment in the cloud — and it is what lets you use **Copilot for free**. Both the Codespace and Copilot have generous free allowances for personal accounts.

> If you get stuck: re-read the step, ask **Copilot**, try Googling the exact error message, ask a classmate, or raise your hand for your instructor.

---

## Curriculum Steps

| Step | Topic | What You Will Do |
|------|-------|-----------------|
| [Step 1](steps/01-fork.md) | Fork the Repo | Make your own copy on GitHub |
| [Step 2](steps/02-codespace.md) | Launch a Codespace | Open a full cloud dev environment in your browser |
| [Step 3](steps/03-copilot.md) | Set Up GitHub Copilot | Turn on your free AI coding assistant |
| [Step 4](steps/04-branch.md) | Create a Branch | Start a safe working copy |
| [Step 5](steps/05-create-file.md) | Create Your File | Add and stage your about-me file |
| [Step 6](steps/06-commit.md) | Commit and Push | Save a snapshot and send it to GitHub |
| [Step 7](steps/07-pull-request.md) | Open a Pull Request | Request a review |
| [Step 8](steps/08-github-pages.md) | Publish a Web Page *(bonus)* | Build and deploy your own live site with GitHub Pages |

**Start here: [Step 1 - Fork the Repo](steps/01-fork.md)**

> **Step 8 is an open-ended bonus.** Steps 1–7 are the core course. Step 8 is for students who want to keep experimenting with Copilot and put a real, shareable website on the internet — great for fast finishers, and a fun challenge for everyone.

---

## How Validation Works

Every time you push code to GitHub, automated checks run in the background. To see your results:

1. Click the **Actions** tab at the top of your forked repository page.
2. Find the most recent workflow run.
3. A **green checkmark** means you passed. A **red X** means something needs fixing — click into the run to see a helpful error message explaining what to do.

> **Important:** When you first fork this repo, GitHub may ask you to enable Actions. Look for a yellow banner on the Actions tab and click **"I understand my workflows, go ahead and enable them."** You must do this before the checks will run.

---

## Git Quick Reference

These are the core git concepts you will learn:

| Concept | What It Means |
|---------|--------------|
| Repository (repo) | A folder tracked by git |
| Fork | Your personal copy of someone else's repo |
| Branch | A parallel timeline of your code |
| Staging | Marking which changes to include in the next commit |
| Commit | A labeled snapshot saved in git's history |
| Push | Sending your commits to GitHub |
| Pull Request | A request to merge your branch into `main` |
| Codespace | A full development environment that runs in the cloud |
| Copilot | An AI assistant that suggests and explains code |
| GitHub Pages | Free hosting that turns your files into a live website |

**Optional: CLI commands (for the curious)**

| Command | What It Does |
|---------|-------------|
| `git clone <url>` | Download a repository to your computer |
| `git status` | Show what has changed |
| `git checkout -b <name>` | Create and switch to a new branch |
| `git add <file>` | Stage a file |
| `git commit -m "message"` | Save a snapshot with a label |
| `git push origin <branch>` | Send your branch to GitHub |
| `git log --oneline` | See a compact commit history |

---

## For Instructors

<details>
<summary>Click to expand instructor notes</summary>

### Setting Up Your Class Copy

1. Fork or use this repo as a template under your organization.
2. Share your repo URL with students and have them fork from yours, not the original.

### A Note on Codespaces and Copilot Cost

Both tools are free for students within GitHub's monthly allowances:
- **Codespaces:** personal accounts include a free monthly quota (at the time of writing, ~120 core-hours and 15 GB storage). Remind students to **stop** their Codespace at [github.com/codespaces](https://github.com/codespaces) when done so they do not burn hours idling.
- **Copilot:** **Copilot Free** works for any account with no payment. Students can also verify through [GitHub Education](https://education.github.com/pack) for the full **Copilot Pro** at no cost. If your school uses a GitHub organization, you can alternatively grant Copilot seats to members.

### Reviewing Student Work

Students will open Pull Requests from `add-about-me` to `main` on their own forks. You can:
- Navigate to their fork and review the PR there.
- Ask students to share their fork URL with you.
- Have students add you as a collaborator on their fork if you want to leave inline comments.

### Customization Ideas

- Add more steps (merge conflicts, rebasing, issues) for advanced students.
- Change the exercise file (e.g., a `hello-world.py` script instead of `about-me.md`) to tie into another class.
- Add a step requiring students to resolve a merge conflict by pre-creating a conflicting file in the repo.

</details>

---

*Built for the Tech Journey STEM program.*
