# HTML & CSS + GitHub Practical Assignment

Welcome to your first collaborative GitHub assignment! 

## Purpose

The main goal of this practical is to get comfortable with the daily Git and GitHub workflow used in real teams while practicing the HTML and CSS skills you have learned so far. 

Through this assignment, you will practice:
- Working with Git branches
- Writing clean, meaningful commits
- Pushing your local code to GitHub
- Opening and documenting a Pull Request (PR)
- Applying basic collaborative development habits
- Building clean, semantic HTML and plain CSS components

---

## Assigned Tasks

| Student | Assigned Folder | Assignment |
| :--- | :--- | :--- |
| **Krishna** | [`krishna/`](file:///d:/Incubation/Learnings/html-css-github-practice/krishna/README.md) | Personal Profile Card |
| **Astha** | [`astha/`](file:///d:/Incubation/Learnings/html-css-github-practice/astha/README.md) | Product Card |
| **Vibhakar** | [`vibhakar/`](file:///d:/Incubation/Learnings/html-css-github-practice/vibhakar/README.md) | Login Form |
| **Vivek** | [`vivek/`](file:///d:/Incubation/Learnings/html-css-github-practice/vivek/README.md) | Food Card |
| **Obama** | [`obama/`](file:///d:/Incubation/Learnings/html-css-github-practice/obama/README.md) | Movie/Book Card |

---

## Assignment Workflow & Rules

Follow these steps carefully from start to finish:

1. **Clone the repository** to your local machine:
   ```bash
   git clone <repository-url>
   cd html-css-github-practice
   ```

2. **Never work directly on the `main` branch.** Always make sure `main` stays clean.

3. **Create and switch to your own feature branch** before writing any code:
   ```bash
   git checkout -b feature/krishna-profile-card
   ```
   *(Replace with your assigned folder name and task, e.g., `feature/astha-product-card`).*

4. **Work only inside your assigned folder** (e.g., `krishna/`). Do not touch or modify other folders.

5. **Create your files** inside your member folder (for example, `index.html` and `style.css`).

6. **Stage and commit your changes** with clear, meaningful commit messages:
   ```bash
   git add krishna/
   git commit -m "Add initial HTML structure for profile card"
   ```

7. **Push your branch** to GitHub:
   ```bash
   git push -u origin feature/krishna-profile-card
   ```

8. **Open a Pull Request (PR)** on GitHub from your branch to `main`.

9. **Add a clear PR title and a short description** explaining what you built and any design choices you made.

10. **Check for review feedback.** If feedback or improvements are suggested, make the changes in your folder, commit them, and push again—the PR will update automatically.

11. **Do not merge your own Pull Request.** An instructor or lead will review and merge it.

---

## Submission Requirements

Your assignment is considered submitted once you have:
- Completed your assigned HTML and CSS task inside your folder.
- Pushed your feature branch to GitHub.
- Opened a Pull Request targeted at the `main` branch.
- Provided a clear PR title and brief description.
- Addressed any review comments or requested changes.

> **Note:** Do not directly push your final work to `main`. The Pull Request is the submission.

---

## Important Rules

- **HTML and CSS only:** Pure HTML and vanilla CSS. Do not use Bootstrap, Tailwind, React, or any other UI libraries/frameworks.
- **Keep it simple and clean:** Focus on good structure, readability, and tidy indentation.
- **Meaningful naming:** Use descriptive file names and semantic class names (e.g., `profile-card`, `btn-contact`).
- **Respect folder boundaries:** Only add or edit files inside your designated folder.
- **Preserve repository files:** Do not delete or edit the global `README.md` file or other members' folders.
- **Original work:** Do not copy another member's markup or styling. Build your own version!

---

## Need Help?

If you run into Git issues (like branch detached states or merge conflicts), ask your peers or mentor before running force commands. Happy coding!
