# Step 7: Open a Pull Request

**Previous step:** [Step 6 - Commit and Push](06-commit.md)
**Next step:** [Step 8 (Bonus) - Build and Publish Your Own Web Page](08-github-pages.md)

---

## What Is a Pull Request?

A **Pull Request** (PR) is a formal request to merge your branch into `main`. It is also a collaboration tool — teammates can look at your changes, leave comments, suggest improvements, and approve the work before it gets merged.

Even when working alone, PRs are useful because they:
- Create a permanent record of your work
- Let someone review your code before it becomes "official"
- Show the full diff (exactly what changed, line by line)

This is how virtually all professional software development works. Opening a PR is one of the most common things a developer does.

> **🤖 Ask Copilot:** Open Copilot Chat and ask: *"What makes a good pull request description?"* Keep its tips in mind when you fill out the PR below.

---

## What You Are Doing

You are requesting to merge your `add-about-me` branch into `main`. This brings your `exercises/about-me.md` file into the main branch.

Your instructor will review the PR. **Do not merge it yourself** — let the instructor do that.

---

## Your Task: Open a Pull Request

1. Go to your forked repository on **github.com** in a browser tab.
2. You should see a yellow banner near the top that says **"add-about-me had recent pushes — Compare & pull request"**. Click that button.
   - If you do not see the banner, click the **Pull requests** tab, then click **New pull request**.
3. On the "Comparing changes" page, confirm:
   - **Base branch:** `main` (the branch you are merging *into*)
   - **Compare branch:** `add-about-me` (your branch with the changes)
4. Click **Create pull request**.
5. The PR description is already filled in with a checklist — that is from the template file in this repo.
6. **Fill out the checklist:** Check the box next to each step you completed by clicking the checkboxes, or by changing `- [ ]` to `- [x]` in the text.
7. Fill in the "What I Learned" and "Questions or Stuck Points" sections.
8. Click **Create pull request**.

---

## The PR Checklist

Your PR description will be pre-filled with a checklist. It should look something like this when you are done:

```
- [x] I forked the repository (Step 1)
- [x] I launched a Codespace (Step 2)
- [x] I set up GitHub Copilot (Step 3)
- [x] I created a branch called `add-about-me` (Step 4)
- [x] I created `exercises/about-me.md` (Step 5)
- [x] I committed and pushed my file (Step 6)
- [x] I opened this Pull Request (Step 7)
```

---

## Automated Check

When you open the PR, the **Step 7 Check** workflow runs and verifies:
- Your `exercises/about-me.md` is included in the PR
- You checked at least one box in the checklist

Check the **Checks** section at the bottom of your PR page to see the result.

---

## What Happens Next?

1. Your instructor will see your Pull Request.
2. They may leave comments or suggestions — you can make more edits in your Codespace and commit again to respond.
3. When everything looks good, your instructor will **merge** the PR.
4. Your `about-me.md` file becomes part of the `main` branch.

**Congratulations — you have completed the core Tech Journey course!**

Want to keep going? **[Step 8 (Bonus)](08-github-pages.md)** is an open-ended challenge: build your own web page and publish it live to the internet with GitHub Pages, using Copilot to help you design it.

---

## What You Learned

| Skill | How You Did It |
|-------|---------------|
| Fork a repo | GitHub Fork button |
| Launch a cloud dev environment | Codespaces tab on the Code button |
| Use an AI coding assistant | GitHub Copilot suggestions and chat |
| Create a branch | Branch menu (or terminal) in the Codespace |
| Create and edit a file | Codespace file explorer |
| Stage changes | Source Control panel `+` |
| Commit and push | Source Control panel in the Codespace |
| Open a Pull Request | GitHub Pull Requests tab |

These are the core skills you will use in any software role. You now know the complete modern developer workflow — from a cloud dev environment and an AI assistant all the way to a Pull Request.
