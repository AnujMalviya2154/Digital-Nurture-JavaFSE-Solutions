# Submission Guide

Per the DN 5.0 handbook: organize solutions week-wise, push to a **public** GitHub repo on
your personal account, and share the URL with your POC.

## 1. One-time Git identity (skip if already set)

```bash
git config --global user.name  "Your Name"
git config --global user.email "your-github-email@example.com"
```

## 2. Create a public repo on GitHub

Go to https://github.com/new → name it e.g. `Digital-Nurture-JavaFSE-Solutions`
→ set **Public** → **Create repository** (don't add a README, we already have one).

## 3. Push this folder

From inside the `DN5-DeepSkilling` folder:

```bash
git init
git add .
git commit -m "DN 5.0 Deep Skilling - Week 1 & Week 2 mandatory hands-on"
git branch -M main
git remote add origin https://github.com/<your-username>/Digital-Nurture-JavaFSE-Solutions.git
git push -u origin main
```

> `_source/` (the downloaded exercise statements) and build output are already ignored via `.gitignore`.

## 4. Share

Copy the repo URL (e.g. `https://github.com/<your-username>/Digital-Nurture-JavaFSE-Solutions`)
and send it to your college POC as proof of progress through Week 2.

## What's included

- **Week 1:** Design Patterns (Singleton, Factory Method), DSA (Search, Recursion),
  PL/SQL (Control Structures, Stored Procedures), JUnit + Mockito + SLF4J.
- **Week 2:** Spring Core & Maven (LibraryManagement), Spring Data JPA + Hibernate (orm-learn).

Every mandatory exercise from `DN - Java FSE Mandatory hands-on detail.xlsx` for Weeks 1–2 is covered.
