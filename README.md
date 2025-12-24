# Hands-On Version Control Using Git Bash and GitHub

## Project Overview
This project was created to demonstrate practical understanding of **Git version control**.  
It covers repository initialization, branching, committing, merging, merge conflict creation, and conflict resolution using real Git commands.

The project represents a basic web application structure for a Disaster Preparedness system.

---

## Project Structure
- `index.html` — Homepage
- `login.html` — Login page
- `signup.html` — Signup page
- `quiz.html` — Quiz page
- `style.css` — CSS styling
- `app.js` — JavaScript file
- `README.md` — Documentation

---

## Branches Used
The following branches were created and used:

- **master** — Main branch
- **b1** — Feature update branch
- **b2** — Testing branch
- **b3** — Bugfix branch
- **b4** — Experiment branch

---

## Git Commands Practiced
The assignment demonstrates usage of:

- `git init`
- `git status`
- `git add`
- `git commit`
- `git branch`
- `git checkout`
- `git merge`
- `git config`
- `git remote`
- `git push`

---

## Merging Workflow
- Branch `b1` was merged into `master` using fast-forward merge.
- Branch `b2` was merged using the ORT merge strategy.
- Branches `b3` and `b4` caused merge conflicts due to changes in the same file.

---

## Merge Conflict Demonstration

### File Involved
`index.html`

### Reason for Conflict
The same file was modified differently in:
- `master` branch
- `b3` and `b4` branches

This resulted in Git being unable to automatically merge the changes.

---

### Conflict Example
```html
<<<<<<< HEAD
<h1>Homepage</h1>
=======
<h1>HomePage - b3 version</h1>
>>>>>>> b3

Challenges Faced
- Remote repository not configured initially (origin missing).
- Branch name mismatch while pushing branches.
- Authentication and permission errors with GitHub.
- Merge conflicts due to changes in the same file.
- Manual conflict resolution using conflict markers.
- Understanding merge strategies (fast-forward vs conflict merge).
- Initial difficulty with Git commands in the terminal.

Learning Outcomes
- Learned how to manage multiple branches.
- Understood Git merge workflows.
- Gained experience resolving merge conflicts manually.
- Improved command-line and GitHub usage skills.
- Learned best practices for commits and repository management.


## ScreenShots
<img width="1440" height="900" alt="Screenshot 2025-12-18 at 1 14 22 PM" src="https://github.com/user-attachments/assets/4f02f4e2-3054-42e1-8c47-f98dbe2ded3c" />
<img width="1440" height="900" alt="Screenshot 2025-12-18 at 1 20 37 PM" src="https://github.com/user-attachments/assets/9e1b7d73-97a1-406f
<img width="1440" height="900" alt="Screenshot 2025-12-18 at 1 20 48 PM" src="https://github.com/user-attachments/assets/be2fa52a-4fb0-49c0-aa91-84de4c56c9f7" />
-9d94-cee20e4e27de" />
<img width="1440" height="900" alt="Screenshot 2025-12-18 at 1 21 01 PM" src="https://github.com/user-attachments/assets/885411bb-7a99-43f2-8f1c-5857235f3ad1" />
<img width="1440" height="900" alt="Screenshot 2025-12-18 at 1 21 47 PM" src="https://github.com/user-attachments/assets/9cf88d83-2a0a-4375-a916-c246168cfeff" />
<img width="1440" height="900" alt="Screenshot 2025-12-18 at 1 24 27 PM" src="https://github.com/user-attachments/assets/561721a1-d1b8-45d0-b2f0-f77eb0565e08" />
<img width="1440" height="900" alt="Screenshot 2025-12-18 at 1 42 29 PM" src="https://github.com/user-attachments/assets/f2470df2-debd-403f-9bf3-c1632c036251" />
<img width="1440" height="900" alt="Screenshot 2025-12-18 at 1 42 39 PM" src="https://github.com/user-attachments/assets/72288c07-bdfb-4ddf-a17c-edbb6296fe5e" />
<img width="1440" height="900" alt="Screenshot 2025-12-18 at 1 45 41 PM" src="https://github.com/user-attachments/assets/432bc6de-2f92-473a-afb7-54ffc56b0f28" />
<img width="1440" height="900" alt="Screenshot 2025-12-18 at 1 48 52 PM" src="https://github.com/user-attachments/assets/ac5de57a-700c-43aa-bf96-e42d28b7228b" />
<img width="1440" height="900" alt="Screenshot 2025-12-18 at 1 49 34 PM" src="https://github.com/user-attachments/assets/91f45d42-d5df-40be-8cc0-9a13be4098bd" />
<img width="1440" height="900" alt="Screenshot 2025-12-18 at 1 52 17 PM" src="https://github.com/user-attachments/assets/21e68657-93de-4900-824e-1c92c15c7de1" />
<img width="1440" height="900" alt="Screenshot 2025-12-18 at 1 55 15 PM" src="https://github.com/user-attachments/assets/e6ce98d3-0bf6-43f4-9b59-7869d31650d9" />
