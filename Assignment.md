Personal Portfolio Project – Assignment Submission

Student Name: Benjamin Tait
Admission Number: 150250
Project Title: Benjamin Tait Portfolio
Live Site: https://ben-tait.github.io/portfolio-BenjaminTait/
## 1. Project Overview

This project is a Personal Portfolio Website built using HTML, CSS, and JavaScript, and managed fully through GitHub using proper software engineering workflows. The goal of the assignment was to:

Practice GitHub project management

Use milestones, issues, and a project board

Implement clean branching strategies

Follow conventional commits

Use feature branches

Create pull requests

Simulate and resolve a merge conflict

Deploy the website using GitHub Pages

The final result is a fully deployed, working personal portfolio site showcasing experience, skills, and projects.

## 2. Milestones

I defined milestones to break the website into major development phases.

Milestone List
Milestone	Description	Link
Landing Page Structure	Build the hero section and base layout for the site.
About Section	Add details about my background, skills, and education.	
Projects Section	Display projects and tech stacks used.	
Deployment & Documentation	Prepare docs, deploy site, and write Assignment.md.	
Merge Conflict Simulation	Create and resolve a real merge conflict.	
## 3. Issues

Each milestone was broken down into smaller tasks and tracked as issues.

Example Issues 

#2 – Build Hero Section → Part of Landing Page Milestone

#4 – Create About Me Section → Part of About Section Milestone

#5 – Add Projects Section → Part of Projects Milestone

#6 – Add Project Details → Part of Projects Milestone

#7 – Deployment Preparation → Deployment Milestone

#10 – Simulate Merge Conflict → Merge Conflict Milestone

![Issues](./docs/images/Issues(2).png)

## 4. GitHub Project Board

I created and used a Kanban-style board with these columns:

To Do

In Progress

Done

Every issue was added to the board and moved across stages as I worked.

Screenshot Placeholder

![Project Board](./docs/images/project-board.png)

## 5. Git Workflow
### Branching Strategy

Every issue had its own feature branch using this naming format:

feature/<issue-number>-short-description


Examples:

feature/2-hero-section

feature/4-about-me

feature/6-project-details
![Branches](./docs/images/Branches.png)
### Pull Requests (PRs)

Each branch had a PR opened, linked to its issue, reviewed (self-review), and merged into main.

### Commit Conventions

I used conventional commits, with at least 6 commit types, including:

feat: – new feature

fix: – bug fix

docs: – documentation update

style: – formatting changes

chore: – non-code tasks

test: – testing-related additions

ci: – (optional) workflow config

refactor: – code restructuring

Examples from the project

feat(hero): add hero section with CTA

chore(repo): initial project structure

fix(conflict): resolve merge conflict in conflict-demo.txt

docs(assignment): update Assignment.md


## 6. Pull Requests

Each issue produced a PR.

Example PRs
Branch	Purpose
feature/2-hero-section	Added hero section
feature/4-about-me	Added about section
feature/6-project-details	Project cards + details
feature/conflict-B	Merge conflict simulation
Screenshot Placeholder

![Pull Requests](./docs/images/pull-requests.png)

## 7. Merge Conflict Simulation (Required Task)

This was a major part of the assignment. I successfully simulated and resolved a merge conflict using branches A and B.

Steps Followed

Created file conflict-demo.txt.

Created two branches:

feature/conflict-A

feature/conflict-B

Modified the same line differently in both branches.

Merged branch A into main.

Opened PR for branch B → GitHub detected a conflict:

“This branch has conflicts that must be resolved.”

Pulled main into branch B locally:

git pull origin main


Resolved conflict manually in VS Code.

Committed resolution:

fix(conflict): resolve merge conflict in conflict-demo.txt


Pushed the resolved branch:

git push


GitHub updated PR → no conflict → merged.

Screenshot Placeholders

![Merge Conflict](./docs/images/Merge_Conflict.png)
![Merge Conflict Resolved](./docs/images/Merge_Conflict_Resolved.png)


## 8. Deployment

The portfolio was deployed using GitHub Pages.

Steps:

Created a docs/ folder with index.html.

Pushed updates to main.

Went to Settings → Pages → Source → main /docs

GitHub generated the live URL.

Live URL:

(https://ben-tait.github.io/portfolio-BenjaminTait/)

Screenshot Placeholder


## 9. Final Checklist
Requirement	Completed
Milestones created	✔️
Issues created and linked	✔️
Project board organized	✔️
Feature branches used	✔️
Conventional commits (6+ types)	✔️
Pull requests opened & merged	✔️
Merge conflict simulated	✔️
Merge conflict resolved manually	✔️
GitHub Pages deployed	✔️
Assignment.md completed	✔️
## 10. Conclusion

This assignment allowed me to practice real-world software development workflows, including version control, issue tracking, project planning, PR management, and conflict resolution. I completed a fully functioning personal portfolio while applying industry-standard Git and GitHub practices.