# My Portfolio Website

This is my personal portfolio website hosted for free using **GitHub Pages**.  
It’s a simple **HTML + CSS** static site that showcases my profile and projects.

---

## 🌐 Live Website
[View Website](https://<yourusername>.github.io)

*(Replace `<yourusername>` with your GitHub username)*

---

## 📂 Project Structure
├── index.html # Main HTML file
├── style.css # Stylesheet for the website

-
---

## 🚀 How to Deploy on GitHub Pages
1. Create a GitHub repository named:
<yourusername>.github.io
git add .
git commit -m "Initial website upload"
git push origin main
Go to GitHub → Settings → Pages

Source: main branch

Folder: / (root)

Click Save

Wait 1–2 minutes and visit:
https://<yourusername>.github.io
Features

Simple, clean HTML + CSS

Free hosting with GitHub Pages

Easy to update — just push new commits

Works on all modern browsers

🛠️ Technologies Used

HTML5

CSS3

Git & GitHub Pages


**INTERVIEW QUESTION:**

**1. What is Git and why use it?**
Git is a distributed version control system used to track changes in code, collaborate with others, and maintain a history of revisions.
We use it to:

Keep a history of project changes

Revert to previous versions if needed

Work in parallel with a team without overwriting each other’s work

**2. How do you push code to GitHub?**
   git add .                  # Stage changes
git commit -m "Message"    # Commit changes
git push origin main       # Push to the 'main' branch
**
****3. What is GitHub Pages?**
GitHub Pages is a free hosting service by GitHub that lets you host static websites directly from a repository.

**4. Difference between static and dynamic websites?**

Static Website: Content is fixed, created with HTML/CSS/JS, and looks the same for all users.

Dynamic Website: Content changes based on user interaction or backend logic (e.g., PHP, Node.js, databases).

**5. How do you revert commits in Git?**

To undo the last commit but keep changes:
GitHub Pages is a free hosting service by GitHub that lets you host static websites directly from a repository.
*To undo the last commit but keep changes:
git reset --soft HEAD~1
*To undo and discard changes:
git reset --hard HEAD~1
*To revert a specific commit:
git revert <commit-hash>

**6. What is branching in Git?**
Branching allows you to create a separate line of development in a project.
Example:

main branch for production code

feature-x branch for new features
Branches help in working independently without affecting main code until merged.

**7. Explain pull requests.**
A pull request (PR) is a request to merge changes from one branch into another.
It’s commonly used in collaborative projects for code review before merging.

**8. How to resolve merge conflicts?**

Open the conflicting file(s)

Look for conflict markers:
<<<<<<< HEAD
Current branch changes
=======
Incoming branch changes
>>>>>>> branch-name

**9. How to host a website for free?**

GitHub Pages – for static websites

Netlify – supports static and JAMstack sites

Vercel – great for Next.js and React projects

Firebase Hosting – for static and dynamic content
GitHub Pages is the easiest for plain HTML/CSS/JS.

**10. What is continuous deployment?**
Continuous deployment is the practice of automatically deploying code changes to production after passing automated tests, without manual approval.
It ensures faster delivery and constant updates.


