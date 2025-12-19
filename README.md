# DisasterPrep Git Assignment 🚨

## 📌 Project Overview
This project was created to demonstrate practical understanding of **Git version control**.  
It covers repository initialization, branching, committing, merging, merge conflict creation, and conflict resolution using real Git commands.

The project represents a basic web application structure for a Disaster Preparedness system.

---

## 📂 Project Structure
- `index.html` — Homepage
- `login.html` — Login page
- `signup.html` — Signup page
- `quiz.html` — Quiz page
- `style.css` — CSS styling
- `app.js` — JavaScript file
- `README.md` — Documentation

---

## 🌿 Branches Used
The following branches were created and used:

- **master** — Main branch
- **b1** — Feature update branch
- **b2** — Testing branch
- **b3** — Bugfix branch
- **b4** — Experiment branch

---

## 🔧 Git Commands Practiced
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

## 🔀 Merging Workflow
- Branch `b1` was merged into `master` using fast-forward merge.
- Branch `b2` was merged using the ORT merge strategy.
- Branches `b3` and `b4` caused merge conflicts due to changes in the same file.

---

## ⚠️ Merge Conflict Demonstration

### 📄 File Involved
`index.html`

### 🔥 Reason for Conflict
The same file was modified differently in:
- `master` branch
- `b3` and `b4` branches

This resulted in Git being unable to automatically merge the changes.

---

### ❌ Conflict Example
```html
<<<<<<< HEAD
<h1>Homepage</h1>
=======
<h1>HomePage - b3 version</h1>
>>>>>>> b3

⚠️ Challenges Faced
- Remote repository not configured initially (origin missing).
- Branch name mismatch while pushing branches.
- Authentication and permission errors with GitHub.
- Merge conflicts due to changes in the same file.
- Manual conflict resolution using conflict markers.
- Understanding merge strategies (fast-forward vs conflict merge).
- Initial difficulty with Git commands in the terminal.

🧠 Learning Outcomes
- Learned how to manage multiple branches.
- Understood Git merge workflows.
- Gained experience resolving merge conflicts manually.
- Improved command-line and GitHub usage skills.
- Learned best practices for commits and repository management.

###ScreenShots
<img width="1440" height="900" alt="Screenshot 2025-12-18 at 1 14 22 PM" src="https://github.com/user-attachments/assets/52ed2b69-f85d-4fe0-84ba-f109843ef7c5" />
<img width="1440" height="900" alt="Screenshot 2025-12-18 at 1 42 29 PM" src="https://github.com/user-attachments/assets/fe3c2fb2-05c9-4414-a18f-23ac34b85f1c" />
<img width="1440" height="900" alt="Screenshot 2025-12-18 at 1 14 22 PM" src="https://github.com/user-attachments/assets/c152b8f5-9dcb-4bad-a4ca-5ba9411f85a1" />

