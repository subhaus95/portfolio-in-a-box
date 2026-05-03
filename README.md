# Portfolio-in-a-Box
### A tiered guide to building your public presence — for students in any discipline

> **The problem:** Most of your work during a degree lives inside a learning management system you'll lose access to the day you graduate. What survives is a transcript and a GPA. In a world drowning in AI-generated output, that's not enough. This guide gives you a path from zero to a professional public portfolio — at whatever level of effort you can commit to today.

---

## Before you start — set up your GitHub account properly

Everything in this guide is built on GitHub. Five minutes here will pay off across all three tiers.

### 1. Create your account

Go to [github.com](https://github.com) and sign up. **Your username becomes part of your public URL** — `github.com/yourusername` and `yourusername.github.io` — so it will appear on your CV, your LinkedIn profile, and in front of every hiring manager who clicks your link.

**Pick something you'd say out loud in a job interview.** The test is simple: imagine reading it aloud to a recruiter. If you'd hesitate, change it.

Good patterns:
 For our student, Tamara Curtains Urania, we might choose:
 
- `firstname-lastname` → `tamara-urania`
- `firstnamelastname` → `tamaraurania`
- `initial-lastname` → `t-urania`

Avoid:
- Nicknames, gaming handles, or anything from your 2015 Xbox account
- Numbers that look like birth years (`tamaraurania72`)
- Underscores (they break some URL parsers and look informal)
- Anything with humour that doesn't age well — you'll be using this for years

If your name is common and taken, add your field: `tamara-urania-meche` is better than `tamara-urania-2027`.

> Already have an account with a username you'd rather not put on a CV? You can change it under **Settings → Account → Change username**. Existing links redirect automatically, but update anything you've shared publicly before changing it.

### 2. Claim the GitHub Student Developer Pack

This is free and most students never do it.

1. Go to [education.github.com/pack](https://education.github.com/pack)
2. Click **Get student benefits**
3. Verify with your university email address
4. GitHub will give your account a **Pro badge** and unlock free access to a stack of developer tools — Copilot, custom domains, hosting credits, and more

The Pro badge is a small but visible signal on your profile. Do it now, before you forget.

### 3. Fill out your profile basics

Go to your profile (click your avatar → **Your profile**) and fill in:

- **Name** — your real name, not your username
- **Bio** — one sentence: your degree, university, and focus area. E.g. *Chemical Engineering · University of Calgary · Process simulation and sustainability*
- **Location** — city is fine
- **Website** — leave blank for now; you'll add your `yourname.github.io` URL after Tier 2

A profile photo isn't mandatory but it helps. A clear headshot or a professional-looking avatar — the same one you use on LinkedIn.

---

## Pick your starting tier

| | Tier 1 | Tier 2 | Tier 3 |
|---|---|---|---|
| **Name** | Profile README | Live Site | Full Portfolio |
| **Time** | ~10 minutes | ~30 minutes | ~2 hours |
| **Technical skill** | None | None | Low |
| **What you get** | A professional GitHub landing page | A real URL: `yourname.github.io` | Multi-page site with project cards, PDF embeds, formula rendering |
| **Best for** | Anyone starting today | Anyone who wants a URL on their CV | STEM students — ChemE, MechE, Biology, CS — with reports, code, and structured project work |
| **Editable via** | GitHub web interface | GitHub web interface | GitHub web interface |
| **Cost** | Free | Free | Free |

Start at Tier 1. Upgrade when you're ready. **All three tiers use GitHub and are completely free.**

---

## Tier 1 — The Profile README (10 minutes)

GitHub has a feature most students never find: if you create a **public repository with exactly the same name as your username**, whatever you put in its `README.md` appears at the top of your GitHub profile page.

No web hosting. No code. If you can write an email, you can do this.

### Steps

1. Go to [github.com](https://github.com) and sign in
2. Click **+** → **New repository**
3. Name it **exactly** your GitHub username — letter for letter, same capitalisation. GitHub will show a green tick and the message *"You found a secret!"* when you get it right
4. Set it to **Public** and check **Add a README file**
5. Click **Create repository**
6. Click the pencil icon to edit the README — or paste the template below directly

> If the repository name doesn't match your username exactly, it just becomes a normal repository. Nothing breaks — it won't appear on your profile. Rename it under **Settings → Repository name** until you see the green tick.

### What to put in it

Use this template — fill in your own details:

```markdown
## Hi, I'm [Your Name]

[Your degree], [Your University] · Class of [Year]

I'm studying [your discipline] with a focus on [your area of interest].
Currently working on [what you're building or learning right now].

### What I'm working on
- [Project or course work — describe it in one sentence]
- [Another project]

### Skills & tools
[MATLAB] [Python] [Aspen Plus] [HYSYS] [SolidWorks] [R] [AutoCAD] — replace with yours

### Find me
- LinkedIn: [linkedin.com/in/yourname](https://linkedin.com/in/yourname)
- Email: your@email.com
```

### Speed it up

[GitHub Profile README Generator](https://rahuldkjain.github.io/gh-profile-readme-generator/) — fill in a form, get Markdown you can paste directly into your README. Done.

---

## Tier 2 — The Live Site (30 minutes)

A live website at `yourname.github.io` is a real URL you can put on a CV, a business card, or a LinkedIn headline. GitHub Pages hosts it for free, directly from your repository — no subscription, no third-party platform.

**The site itself is part of the signal.** It shows you shipped something to the public web.

### Steps

1. Go to any repository (your Tier 1 README repository works perfectly)
2. Click **Settings** → **Pages** (left sidebar)
3. Under **Source**, select your `main` branch
4. Click **Save**
5. Under **Theme Chooser**, pick a theme (Cayman and Architect are clean and professional)
6. GitHub turns your `README.md` into a mobile-responsive website

Your site will be live at `https://yourusername.github.io` within a few minutes.

### Add your site URL to LinkedIn

1. Go to your LinkedIn profile → Edit intro
2. Add your `yourname.github.io` URL to the **Website** field
3. In the **Featured** section, add a link to your site

That URL on your LinkedIn profile is now clickable by every recruiter who views your profile.

---

## Tier 3 — The Full Portfolio (2 hours)

For students who want structured project pages, PDF embeds for lab reports, formula rendering for engineering and science work, and skills badges — mature Jekyll templates exist that do all of this, edited entirely through Markdown files in GitHub's browser interface.

**No CSS. No JavaScript. No local install required.**

### Choose a template

#### [al-folio](https://github.com/alshedivat/al-folio) — recommended for STEM and research students
- 12,000+ forks; used by academics across every discipline worldwide
- Supports MathJax (render equations like $\Delta G = \Delta H - T\Delta S$ or $\dot{m} = \rho A v$ in your project pages)
- Project cards, publications list, auto-generated CV, PDF download link
- Skills badges generated from project tags

#### [Academic Pages](https://academicpages.github.io) — simpler alternative
- Based on Minimal Mistakes Jekyll theme
- Publications, talks, teaching portfolio, blog — editable entirely in GitHub's web interface
- Better for students who want something up quickly with less configuration

### Setup (same process for both)

1. Go to the template repository and click **"Use this template"** → **"Create a new repository"**

   > ⚠️ **Use "Use this template" — not "Fork."** A template gives you a clean commit history. Your portfolio looks like your original work from day one. A fork carries a "forked from" label.

2. Name your new repository `yourusername.github.io`
3. Set it to **Public**
4. Click **Create repository**
5. Go to **Settings** → **Pages** → set source to `gh-pages` branch
6. Edit `_config.yml` with your name, institution, and links
7. Your site is live at `https://yourusername.github.io`

### Adding a project

Create a new file in the `_projects/` folder. Name it anything (e.g. `distillation-design.md`). Use this structure:

```markdown
---
layout: page
title: Distillation Column Design — Ethanol-Water Separation
description: >
  Process simulation and economic optimisation of a distillation column
  using Aspen Plus and Python, completed as part of ENGG 4410.
img: assets/img/distillation-thumb.jpg
importance: 1
category: coursework
---

## The problem

[One paragraph: what was the engineering or process challenge?]

## What I built

[One paragraph: what did you simulate, design, or optimise?]

## What I learned

[One paragraph: what would you do differently? What surprised you?]

## Tools used

Aspen Plus · Python (pandas, matplotlib) · HYSYS
```

GitHub Pages rebuilds your site automatically every time you commit a change. No commands to run.

---

## The STAR template for project descriptions

Whether you're writing a project page (Tier 3) or a LinkedIn post about your work, use this structure. It's the format that hiring managers actually read.

```
Situation:  What was the context or problem? (1–2 sentences)
Task:       What were you specifically responsible for? (1–2 sentences)
Action:     What did you build, model, analyse, or design? (2–3 sentences)
Result:     What was the outcome? What did you learn? (1–2 sentences)
```

### Example — Mechanical Engineering

> **Computational Fluid Dynamics of a Heat Exchanger**
>
> A third-year thermodynamics course required us to model fluid flow in a shell-and-tube heat exchanger. I was responsible for the CFD simulation and validation against experimental data. Using ANSYS Fluent, I built a parametric model and ran simulations across five flow-rate conditions, validating results against lab measurements to within 4%. I learned that mesh refinement decisions have a larger effect on accuracy than solver settings — something no textbook made clear until I saw it in my own output.

### Example — Chemical Engineering

> **Distillation Column Design for an Ethanol-Water Separation**
>
> A process design course required us to specify a distillation column capable of producing 99.5% ethanol from a fermentation feed. I was responsible for the simulation and economic optimisation. Using Aspen Plus, I modelled the column across a range of reflux ratios and feed tray positions, then wrote a Python script to pull the results and plot the cost surface — finding an operating point 12% cheaper than the textbook shortcut method suggested. I put the simulation files, the Python script, and a plain-English walkthrough on GitHub so future students in the course could use it as a reference without starting from scratch.

---

## Image guide

A photo of a physical project — a prototype, a model, a lab setup — is powerful evidence. Here's how to include one without breaking your site.

1. **Compress first.** Phone photos are 4–8 MB. Aim for under 500 KB. Use [Squoosh](https://squoosh.app) — free, browser-based, no install.
2. **Rename descriptively.** `IMG_4821.jpg` tells a visitor nothing. `distillation-column-lab.jpg` does.
3. **Upload to `assets/img/`** in your repository via the GitHub web interface (drag and drop).
4. **Reference it in your project Markdown** using the `img:` field in the front matter.

---

## Connect GitHub to LinkedIn

Your GitHub profile and your LinkedIn profile should point at each other. Here's how:

**On GitHub:**
- Add your LinkedIn URL to your profile (Edit profile → Website)
- Pin your 3–5 strongest repositories to the top of your profile

**On LinkedIn:**
- Add your `yourname.github.io` URL to your profile header (Website field)
- Use the **Featured** section to link to your portfolio site or your strongest project page
- For each significant project, write a **post** — one paragraph using the STAR format above. Tag it to your education entry.

**On LinkedIn, write in English, not in terminal output.** Recruiters are not reading your code. They are reading your explanation of what the code does and why it mattered.

---

## What makes a strong README for an individual project

Every pinned repository should have a README that answers these questions:

1. **What does this do?** — one sentence
2. **Why does it exist?** — what problem does it solve?
3. **What did you use?** — tools, languages, frameworks
4. **How do you run it?** — even if it's just "open in MATLAB"
5. **What did you learn?** — this is the one most students skip; it's the most important one for a recruiter

A README that explains your thinking is worth more than the code itself to someone deciding whether to call you.

---

## Resources

| Resource | What it's for |
|---|---|
| [GitHub Pages](https://pages.github.com) | Free hosting — the official guide |
| [GitHub Student Developer Pack](https://education.github.com/pack) | Free Pro badge + tools — verify with your university email |
| [GitHub Profile README Generator](https://rahuldkjain.github.io/gh-profile-readme-generator/) | Tier 1 setup in minutes |
| [al-folio template](https://github.com/alshedivat/al-folio) | Tier 3 — STEM-focused, MathJax, project cards |
| [Academic Pages template](https://academicpages.github.io) | Tier 3 — simpler alternative |
| [Squoosh](https://squoosh.app) | Compress images before uploading |
| [UNC CS: GitHub & LinkedIn Guide](https://cs.unc.edu/student-life/career/guide-to-github-and-linkedin/) | The four Cs of a strong GitHub profile |
| [Shields.io](https://shields.io) | Generate skills/tools badges for your README |

---

## The point

The degree is the credential. The portfolio is the proof.

These are not interchangeable. The transcript tells someone you completed the curriculum. A portfolio tells them how you think, what you care about, and whether you can ship. In a job market where everyone has a degree and AI can produce passable output on demand, the thing that stands out is the person who can point at something real and say: I made that.

There's no substitute for showing your work. There never was. Start at whichever tier you'll actually finish today.

---

*Assembled taking input from the MRU Computer Science Advisory Board. Contributions welcome — open a PR.*
