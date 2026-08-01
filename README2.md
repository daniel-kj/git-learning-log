<img src="https://cdn.prod.website-files.com/677c400686e724409a5a7409/6790ad949cf622dc8dcd9fe4_nextwork-logo-leather.svg" alt="NextWork" width="300" />

# Git Undo, Recovery, and Debugging

**Project Link:** [View Project](https://nextwork.ai/projects/2a174c0b-492b-472c-b8de-11c58f71253a)

**Author:** Daniel  
**Email:** danieljrkagbenyo@gmail.com

---

![Image](https://nextwork.ai/lively_turquoise_clever_feijoa/uploads/2a174c0b-492b-472c-b8de-11c58f71253a_g4cvohgl)

## Project Overview: Mastering Git Recovery and Debugging

### What this project set out to achieve

In this project, I'm learning how to revert commits, recover branches and perfoming hotfixes so that I can undo public mistakes, rescue work after accidental reset and debug real-world workflows.

## Setting Up the Repository and Environment

### Goals for this setup step

In this step, I'm setting up my local Git repo in VS code editor so that I can practice undoing, recovering, and debugging with.

![Image](https://nextwork.ai/lively_turquoise_clever_feijoa/uploads/2a174c0b-492b-472c-b8de-11c58f71253a_g1082umq)

### Configuring Git for this project

I configured my local to chech that I'm on the main branch before perfoming a pull request because I needed to ensure both my local and remote repo are both the same before staging, commiting and push the newly created file

## Building a Meaningful Commit History

### Why a rich history matters for practice

In this step, I'm building 4 documentation sections to my practice file with each having its own commit so that I can push all to GitHub.

![Image](https://nextwork.ai/lively_turquoise_clever_feijoa/uploads/2a174c0b-492b-472c-b8de-11c58f71253a_rxiot185)

### The value of granular commits

I committed separately because tools like git reset, git revert and git bisect need work seperately so need different targets to operate on.

## Undoing Mistakes Safely with Reset and Revert

### Approach to undoing bad commits

In this step, I'm learning how to undo a local commit with git reset --soft and undo a pushed commit with git revert so that I can learn the differences between the two.

### Reset vs. revert: choosing the right tool

I would use git reset when I am working in my local repo, when local commits haven't been pushed yet and git revert when when working on commits have already been pushed because it undoes commits by creating a new history.

## Recovering Lost Commits with Git Reflog

### Simulating and recovering from data loss

In this step, I'm simulating loosing work using hard reset so that I can prove that git reflog can find lost commits.

![Image](https://nextwork.ai/lively_turquoise_clever_feijoa/uploads/2a174c0b-492b-472c-b8de-11c58f71253a_k4mtf1ce)

### How reflog sees what git log cannot

Git reflog can find the lost commit because it keeps a record of anything that happens in the repository localy only. This record allows anything committed to be almost always recovered.

![Image](https://nextwork.ai/lively_turquoise_clever_feijoa/uploads/2a174c0b-492b-472c-b8de-11c58f71253a_quljmadv)

## Cherry-Picking a Hotfix Across Branches

### Setting up the cherry-pick scenario

In this step, I'm setting up a feature branch with a mix of feature work and a bug fix so that I can cherry-pick the fix commit to main.

![Image](https://nextwork.ai/lively_turquoise_clever_feijoa/uploads/2a174c0b-492b-472c-b8de-11c58f71253a_glkgbt5x)

### When cherry-pick beats a full merge

I would use cherry-pick instead of merge because my main branch needs an urgent fix that is complete in a feture branch and doesn't require waiting to merge the entire branch when all other features are complete.

## Hunting Down a Bug with Git Bisect

### Binary search through commit history

In this step, I'm using a binary search to find, fix and clean up a hidden bug in a series of commits.

### Identifying the first bad commit

Git bisect identified the commit with message Add auth config This was hard to find manually because doing it that way will take too much time.

## Tagging a Release for CI/CD Readiness

![Image](https://nextwork.ai/lively_turquoise_clever_feijoa/uploads/2a174c0b-492b-472c-b8de-11c58f71253a_2r1c7yrq)

### Annotated vs. lightweight tags

In this project extension, I learned that annotated tags are for store tagger name, date, and a message,  while lightweight tags are for pointing to metadata.

## Reflections and Wrap-Up

### Key tools and concepts from this project

Key concepts I learnt include undoing local commits with git reset, undoing public commits with git revert, finding and recover commits that were lost using git reflog,  surgically applying a single commit in a branch with git cherry-pick, using a binary-search to find a commit that introduced a bug in the version history using git bisect and annotated tags that store tagger name, date, and a message (meant for releases) while lightweight tags are just pointers with no metadata (meant for private or temporary labels).

### Time and challenges

This project took me approximately 8 hours. The most challenging part was understanding how git bisect uses binary-searches find bad commits.

### Looking ahead

I did this project today to learn how to publish and collaborate with Git and GitHub. Another skill I want to learn is CI/CD

---

*Built with [NextWork](https://nextwork.ai) - [View this project](https://nextwork.ai/projects/2a174c0b-492b-472c-b8de-11c58f71253a)*