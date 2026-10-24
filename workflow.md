# Activity 4: Git Workflow (CMD / VS Code terminal)

## Leader (Neil)
1. Create a **public** repository on GitHub, with README initialized.
2. Add collaborators: Camara, Camua-ty, Deocampo, Tababa, and `madzamador` (use their actual GitHub usernames).
3. Clone: `git clone https://github.com/LEADER_USERNAME/REPOSITORY.git`
4. Copy the starter files into the cloned folder; do not copy a ZIP over `.git`.
5. Stage and commit initial scaffold: `git add .` then `git commit -m "Add initial project scaffold"` and `git push origin main`.
6. Create five GitHub Issues matching the assigned work.

## Each member
1. `git clone https://github.com/LEADER_USERNAME/REPOSITORY.git`
2. `cd REPOSITORY`
3. `git checkout -b task/YOUR-ASSIGNED-BRANCH`
4. Edit assigned file(s), making a genuine contribution.
5. `git add .`
6. `git commit -m "Describe your contribution"`
7. `git push -u origin task/YOUR-ASSIGNED-BRANCH`
8. On GitHub, open a pull request targeting `main`, referencing the corresponding Issue.

## Leader integration
Review and merge pull requests one by one on GitHub. If using the command line instead, first run `git checkout main`, `git pull origin main`, `git merge origin/task/BRANCH-NAME`, and `git push origin main` for each branch after fetching. Do not merge a branch twice.

## Evidence
Capture screenshots of public repo, collaborators, Issues, branch list, each member's commits, pull requests, final `main`, and repository link. Only the leader submits the group output on MS Teams.