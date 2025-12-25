**Git and GitHub Practice: Day 1 and Day 2**

You have watched the Git crash course video. Your focus for today is to apply those concepts practically using Git and GitHub. Please follow the steps below carefully and complete all of them.

This entire exercise must be done **using the terminal (command line)** and **not** using any Git buttons or UI shortcuts inside VS Code.

---

## 0. Important Ground Rules (Read Carefully)

* You must use **terminal commands** (`git clone`, `git add`, `git commit`, `git push`, etc.).
* Do **not** use VS Code Git UI buttons for commit, push, pull, or branch creation.
* You will use **VS Code only as a code editor**, not as a Git shortcut tool.
* **Be completely honest in your writing.**
  This repository is for learning and growth, not for looking perfect.
  **Write what you actually understood, what confused you, and what you struggled with.**

This honesty is very important and will be reviewed.

---

## 1. What Is Terminal / Command Line (Very Brief)

The terminal (also called command line) is a text-based way to interact with your computer.

Instead of clicking buttons, you type commands such as:

* `git status`
* `git commit`
* `git push`

Git is primarily designed to be used from the terminal. Learning this early will make you significantly stronger as a developer.

You will open the terminal:

* On Windows: Git Bash or VS Code integrated terminal

---

## 2. Create Your Personal GitHub Repository

1. Log in to your GitHub account.
2. Create a new repository named:
   **`daily-achievements`**
3. Check the option **“Initialize with README.md”**.

### What Is a `.md` File (Markdown)

A `.md` file is a **Markdown file**.

Markdown is a very simple text format used to write:

* Headings
* Bullet points
* Code blocks
* Lists

It is commonly used for documentation in software projects.

Example:

```md
# Heading
- Bullet point
- Another point
```

You will use Markdown for **all writing in this repository**.

---

## 3. What to Write in `README.md`

Open `README.md` and write:

* What this repository is for
* That it is your daily internship learning and achievement tracker
* That it will be updated **by you every single working day**

Example points to include:

* Purpose of the repository
* How it is structured (day-wise folders)
* A short note that this is a learning log

Keep it simple and clear.

---

## 4. Clone the Repository and Open It in VS Code

1. Clone the repository using terminal.
2. Open the folder in **VS Code**.
3. Make sure you understand:

   * Local repository (your machine)
   * Remote repository (GitHub)

---

## 5. Repository Structure (Mandatory)

Create the following structure:

```text
daily-achievements/
├── README.md
├── day-01/
│   ├── summary.md
│   └── notes.md
├── day-02/
│   ├── summary.md
│   └── notes.md
```

Rules:

* Each day has its own folder.
* All files must be written in **Markdown (`.md`)**.
* This repository will be updated **every working day**, without exception.

---

## 6. Write Content for Day 01 and Day 02

Since your internship started yesterday, you must write for **both days**.

### In `day-01/summary.md` and `day-02/summary.md`, write:

* What you did that day
* What Git concepts or commands you practiced
* What you understood well
* What did not fully make sense

### In `day-01/notes.md` and `day-02/notes.md`, write:

* Notes from the Git video
* Important commands
* Errors you encountered
* Questions you want to ask me

Again: **be honest and clear**. This is for learning.

---

## 7. Commit to Main Branch Using Terminal

From the repository root, use terminal commands to:

1. Check status
2. Stage files
3. Commit with a meaningful message
4. Push to `main`

Your commit message should clearly describe what you did.

---

## 8. Branching Exercise

Now practice working with branches.

1. Create a new branch named:
   **`day-02-improvements`**
2. Switch to this branch using terminal.
3. Improve any summary file:

   * Add one more learning
   * Improve formatting
4. Commit the changes.
5. Push the branch to GitHub.

---

## 9. Pull Request Exercise

1. Go to GitHub.
2. Open a Pull Request from `day-02-improvements` into `main`.
3. Add a short description of what you changed.
4. Do not merge it yet.

Important note:

* Sometimes I will ask you to create branches instead of committing directly to `main`.
* Sometimes I may open a Pull Request and ask you to **review it**.
* You should become comfortable with both creating and reviewing Pull Requests.

---

## What I Will Review

* Repository structure
* Markdown clarity
* Commit messages
* Branch usage
* Pull Request quality
* Honesty and reflection quality

---

## Final Step

Once you finish:

* Send me the GitHub repository link
* Send me the Pull Request link

Take your time. Read errors carefully. Experiment freely. Mistakes are expected and encouraged at this stage.