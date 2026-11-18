# comp120_assignment3
COMP120_versioncontrol

# comp120_assignment3

COMP120_versioncontrol: a simple task manager used to practice version control with Git and GitHub (repositories, milestones, issues, branches, pull requests and collaboration).

## Features

- Add a task (Issue #1)
- Mark a task as complete (Issue #3)
- View all tasks
- Basic usage documentation (Issue #2)

## Project Structure

```
comp120_assignment3/
├── src/
│   └── app.py          # Main application code
├── docs/
│   └── notes.md        # Project notes and workflow documentation
├── .gitignore          # Files Git should ignore
└── README.md           # Project overview and usage instructions
```

## Getting Started

### Prerequisites

- Git installed ([git-scm.com](https://git-scm.com))
- Python 3.10 or later

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/hiffy247/comp120_assignment3.git
   ```
2. Move into the project folder:
   ```bash
   cd comp120_assignment3
   ```
3. Run the application:
   ```bash
   python src/app.py
   ```

## Usage

| Action | How to do it |
|--------|--------------|
| Add a task | Choose **Add task** from the menu and type the task description |
| View tasks | Choose **View tasks** to list all tasks with their status |
| Complete a task | Choose **Complete task** and enter the task number |
| Exit | Choose **Quit** |

Example session:
```
1. Add task
2. View tasks
3. Complete task
4. Quit
> 1
Enter task: Submit Assignment 3
Task added.
```

## Development Workflow

This project follows a branch-based workflow:

1. Pick an issue from the **v1.0 Release** milestone.
2. Create a branch named after the work, e.g. `feature/add-task` or `docs/readme-usage`.
3. Commit changes with clear messages that reference the issue (e.g. `closes #2`).
4. Push the branch and open a **Pull Request**.
5. Have a collaborator review it, then merge into `main`.

## Milestone

**Ifeoluwa_v1.0 Release** (due November 23, 2026): the first working version of the task app.

## Contributors

- [@hiffy247](https://github.com/hiffy247): repository owner
- [@quack-pixel](https://github.com/quack-pixel): collaborator

## Course

COMP120, Centennial College, Software Engineering Technology