# Mission 0 - Create your GitHub workspace

## 1. Task / objective
Create a public repository with the required name and a separate folder for each mission.

## 2. Work completed
The project folder and repository are both named `digital-detective-8545`.
All nine mission folders, their README files, the converter placeholder, a root
README and an evidence folder were created. The root README links to all missions.

## 3. Commands / tools used
| Tool or operation | Purpose | Observed version |
| --- | --- | --- |
| `python3 --version` | Check Python availability | Python 3.14.7 |
| `git --version` | Check Git availability | git version 2.54.0 (Apple Git-157) |
| `mkdir -p` | Make the assignment folder | Not applicable |
| Python `pathlib` | Create required folders and initial text files | Python 3.14.7 |
| GitHub in Safari | Create the public repository | Web application |
| `git init`, `git add`, `git commit`, `git push` | Start version control, record and publish setup | Git |

## 4. My understanding
A repository stores project files and their version history. Mission folders keep
evidence and explanations for each topic together, making progress easier to review.
Git tracks files; a directory appears on GitHub when it contains a tracked file.

## 5. Difficulties faced
The connected GitHub account and Safari account differed. A Terminal push failed with "Could not resolve host: github.com". An initial staging attempt used a glob from the parent folder and matched no files. The first in-app browser
attempt failed. The login shell also reported a missing Homebrew executable.

## 6. How I resolved them
The student selected the already signed-in Safari account for this assignment.
After checking Git status, staging was rerun from inside the repository. The student ultimately requested browser control. Safari was used for repository creation and publishing; the restricted Terminal could not reach GitHub. Browser commits are real GitHub commits, but do not establish that a command-line push succeeded. Subsequent command checks used a non-login
shell, without modifying any shell settings or installing software.

## 7. Evidence / files
- [Root README](../README.md): introduction, mission index and disclosure.
- [Evidence index](../evidence/README.md): evidence privacy policy.
- Version checks above are actual Terminal outputs.
- The setup commit contains all required mission directories and placeholders.

## 8. Commit details
Commit message: `Set up Digital Detective mission structure`.
The local setup commit exists. The same setup is being published through GitHub in Safari before Mission 1 begins. Command-line push remains blocked; this workflow exception must be reviewed with the instructor.
