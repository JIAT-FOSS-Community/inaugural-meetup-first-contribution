# 🪄 Contributing to Your First Open Source Project

Welcome, Sorcerer! ✨ This is your guide to making your **very first open-source contribution** at the JIAT FOSS Inaugural Meetup.

By following these steps, you'll learn the complete open-source contribution workflow: **Fork → Clone → Branch → Edit → Commit → Push → Pull Request**

---

## 📜 Prerequisites

Before you begin, make sure you have:

- [x] A **GitHub account** — [Sign up here](https://github.com)
- [x] **Git installed** — Verify with `git --version`
- [x] **SSH key set up** — Verify with `ssh -T git@github.com`

---

## 🌿 Step-by-Step Contribution Guide

### Step 1: Fork this Repository 🍴

Click the **"Fork"** button at the top-right corner of this repository page on GitHub.

> **Why fork?** A fork is YOUR personal copy of this repository on YOUR GitHub account. You can make changes freely without affecting the original project.

### Step 2: Clone Your Fork 📥

```bash
git clone git@github.com:YOUR-USERNAME/inaugural-meetup-first-contribution.git
cd inaugural-meetup-first-contribution
```

> **Why clone?** Cloning downloads your fork to your local machine so you can work on it.

### Step 3: Create a New Branch 🌿

```bash
git checkout -b add-participant-YOUR-NUMBER
```

Replace `YOUR-NUMBER` with the number you were assigned (e.g., `add-participant-005`).

> **Why branch?** A branch lets you work on changes without affecting the `main` branch. Professional developers NEVER commit directly to main.

### Step 4: Add Your Details 📝

1. **Copy the template:**
```bash
cp participants/template.json participants/YOUR-NUMBER.json
```
Replace `YOUR-NUMBER` with your assigned 3-digit number (e.g., `002`, `015`, `042`).

2. **Edit your JSON file** with your actual details:
```json
{
  "number": 2,
  "name": "Your Full Name",
  "branch": "GAMPAHA",
  "batch": "YOUR BATCH",
  "image": "assets/images/002.jpg",
  "github": "your-github-username"
}
```

**Valid branch values:** `GAMPAHA`, `COLOMBO`, `KANDY`, `KURUNEGALA`, `MATARA`

3. **Add your photo** (optional but encouraged!):
   - Place your photo in the `assets/images/` folder
   - Name it with your number: `YOUR-NUMBER.jpg` (e.g., `002.jpg`)
   - Recommended: Square image, at least 200x200px

### Step 5: Stage & Commit 📦

```bash
git add .
git status
c
```

> **Why commit?** A commit is a permanent snapshot of your changes. The message describes what you did.

### Step 6: Push to Your Fork 🚀

```bash
git push origin add-participant-YOUR-NUMBER
```

> **Why push?** Pushing uploads your local commits to your fork on GitHub.

### Step 7: Create a Pull Request 📬

1. Go to your fork on GitHub
2. You'll see a banner: **"Compare & pull request"** — click it!
3. Add a title: `feat: add participant YOUR-NUMBER - Your Name`
4. Add a brief description if you want
5. Click **"Create pull request"**

> **Why a Pull Request?** A PR is your proposal to merge your changes into the original project. The maintainer will review and accept it.

### Step 8: Wait for the Merge ✅

The maintainer (Charaka) will review your PR and merge it. Once merged, your card will appear on the live participants page!

---

## ⚠️ Why We Use Numbered Files

Each participant edits a **different** file (`001.json`, `002.json`, etc.). This is a deliberate design choice to **prevent merge conflicts**.

**What are merge conflicts?** They happen when two people edit the **same part of the same file**. Git can't decide which version to keep, so it asks YOU to resolve it manually.

By giving each participant their own file, we ensure everyone's changes are independent — no conflicts, smooth merging! This is a pattern real open-source maintainers use.

---

## ❓ Need Help?

If you get stuck at any point:
- 🙋 Raise your hand — we'll come help you!
- 💬 Drop your question in the WhatsApp community
- 🔗 Open an **Issue** on this repository

---

## 🧙‍♂️ Commit Message Format

We use **Conventional Commits** for this project:

```
feat: add participant 005 - Jane Doe
```

| Prefix | Usage |
|--------|-------|
| `feat:` | Adding your participant file |
| `fix:` | Fixing a typo or error in your file |
| `docs:` | Updating documentation |

---

*Made with ❤️ by the JIAT FOSS Community — Open Sourcery since 2026*

#JIATFOSS #OpenSourcery #FOSS #OpenSource #FOSSLK #JavaInstitute #TechCommunity
