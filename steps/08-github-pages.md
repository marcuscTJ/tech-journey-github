# Step 8 (Bonus): Build and Publish Your Own Web Page

**Previous step:** [Step 7 - Open a Pull Request](07-pull-request.md)
**Next step:** This is the finish line — go as far as you want!

---

## You Made It — Now Let's Show It Off

You have learned the complete developer workflow. This bonus step is different from the others: it is **open-ended**. There is no automated check and no single "right" answer. Your goal is to build something that is truly *yours* and put it on the real internet — a web page you can send to your friends and family.

Finished the earlier steps quickly? Perfect — spend your extra time here experimenting. Still catching up? That is completely fine; save this for when you are ready.

This is where you get to play. Use **Copilot** as much as you can.

---

## What Is GitHub Pages?

**GitHub Pages** is a free feature that turns files in your repository into a live website. You do not need a server, a domain, or any payment. You give GitHub an `index.html` file, flip a switch, and GitHub hosts it for the world at a web address like:

```
https://YOUR-USERNAME.github.io/tech-journey-github/
```

Your repo already contains a starter page: the **`index.html`** file in the main folder. `index.html` is the special name browsers look for — it is the "front door" of any website. Right now it is a starter template. By the end of this step it will be *your* page, live online.

> **🤖 Ask Copilot:** Open Copilot Chat and ask: *"What is an HTML file and what does the `index.html` file do on a website?"*

### Your page comes with a toolkit

To help you build cool things fast, your `index.html` already loads four popular web tools. You do **not** need to learn them — just know they are there, because **Copilot knows all of them** and can use them when you ask.

| Tool | What it gives you |
|------|-------------------|
| **Tailwind CSS** | Style anything by adding short `class` names (colors, spacing, shadows) — no separate stylesheet needed |
| **Font Awesome** | Thousands of icons, like `<i class="fa-solid fa-heart"></i>` |
| **Google Fonts** | A nice font (Poppins) already applied to the whole page |
| **Alpine.js** | Simple interactivity — buttons that count, toggles, show/hide — with just a little markup |

The starter page already uses all four (look at the "Wave at me" button near the bottom — that is Alpine.js and Font Awesome working together). When you ask Copilot for changes, it will reach for these automatically.

---

## Part 1: Publish the Starter Page (Get It Live First)

Before you change anything, let's get the starter page online. Seeing it work first makes editing way more fun.

1. Go to your forked repository on **github.com**.
2. Click the **Settings** tab (top of the repo page).
3. In the left sidebar, click **Pages**.
4. Under **Build and deployment → Source**, choose **Deploy from a branch**.
5. Under **Branch**, pick **`main`** and the **`/ (root)`** folder, then click **Save**.

GitHub now starts building your site. This takes **1–2 minutes** the first time.

6. Wait a minute, then **refresh** the Settings → Pages screen. When it is ready, you will see a message: *"Your site is live at ..."* with a link.
7. Click that link. 🎉 **Your starter page is on the real internet!**

> If you see a 404 error, do not panic — it usually just means the build has not finished yet. Wait another minute and refresh.

---

## Part 2: Make It Yours (Edit and Redeploy)

Now the fun part. You will edit `index.html` in your Codespace, and every time you push a change, GitHub Pages will automatically update your live site.

### Open the file

1. Go back to your **Codespace** (or launch one again from the **Code** button if you stopped it).
2. In the file explorer on the left, click **`index.html`** to open it.
3. Read through it. The page has helpful comments (the lines inside `<!-- ... -->`) showing you exactly where to start editing.

### Change it

Look for the section marked `▼▼▼ START EDITING HERE ▼▼▼` and make it about *you*:

- Replace **[Your Name]** with your actual name.
- Rewrite the **About Me** paragraph.
- Change the **Things I'm Into** list to your real interests.
- Change the colors! On the `<body>` tag, the `from-indigo-500 to-purple-600` classes control the background gradient — swap in other colors (try `from-pink-500 to-orange-400`).

> **🤖 Ask Copilot — this is the whole point of this step.** Your page has Tailwind, icons, and Alpine.js ready to go, so Copilot can do a lot. Try asking Chat for real changes:
> - *"Change my background to a sunset gradient."*
> - *"Add a 'My Projects' section with three cards, each with an icon."*
> - *"Add a button that toggles the page between light and dark mode using Alpine.js."*
> - *"Give my heading a fun animated hover effect."*
> - *"Add Font Awesome icons next to each of my interests."*
>
> Accept the parts you like, tweak them, and keep experimenting. This is exactly how developers use Copilot to build real things.

### Publish your changes

Every change you make follows the same save-it-to-GitHub rhythm you already learned:

1. **Save** the file (`Ctrl+S` / `Cmd+S`).
2. Open the **Source Control** panel on the left (the branch-looking icon).
3. **Stage** your change (the `+` next to `index.html`).
4. Write a commit message like `Personalize my showcase page` and **Commit**.
5. **Sync / Push** it to GitHub.

> **Note:** For this bonus page you are working directly on the `main` branch of *your own fork* — that is on purpose. GitHub Pages publishes from `main`, so pushing there is what updates your live site. (Your graded `about-me.md` work still lives on its own branch and Pull Request from the earlier steps.)

6. Wait about a minute, then **refresh your live page**. Your changes are online! 🚀

Repeat as much as you want: edit → commit → push → refresh. That loop is web development.

---

## Ideas to Keep Going

If you are on a roll, try adding:

- A photo or an emoji banner
- A list of links to things you like (use the `<a href="...">` tag — ask Copilot how!)
- A "projects" section describing what you built today
- A dark mode, an animation, or a custom font

There is no limit. Ask Copilot, try things, break things, fix them. That is how you learn.

---

## Share It

Copy your live URL:

```
https://YOUR-USERNAME.github.io/tech-journey-github/
```

Send it to a friend, a parent, or your instructor. You built a real website and published it to the internet — something the vast majority of people have never done.

---

## What You Learned in This Step

| Skill | How You Did It |
|-------|---------------|
| Host a live website | Enabled GitHub Pages on your fork |
| Edit HTML and CSS | Changed `index.html` in your Codespace |
| Use AI to build, not just fix | Asked Copilot to add real features |
| Ship changes continuously | Commit + push → site auto-updates |

---

**🎉 That's a wrap!** You forked a repo, worked in a cloud editor, paired with an AI, branched, committed, opened a Pull Request, *and* published a live website. That is the real modern developer workflow — start to finish. Be proud.
