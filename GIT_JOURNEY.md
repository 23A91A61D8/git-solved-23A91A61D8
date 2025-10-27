# My Git Mastery Challenge Journey

## Student Information
- **Name:** Arepalli Venkata Lakshmi  
- **Student ID:** 23A91A61D8  
- **Repository:** [https://github.com/23A91A61D8/git-solved-23A91A61D8](https://github.com/23A91A61D8/git-solved-23A91A61D8)  
- **Date Started:** [26-10-2025]  
- **Date Completed:** [27-10-2025]  

---

## Task Summary
Cloned the instructor’s repository with pre-built conflicts and successfully resolved **all merge conflicts** across multiple branches using standard Git workflows. Practiced advanced commands like **stash**, **rebase**, **cherry-pick**, **reset**, and **tagging** to simulate real-world DevOps scenarios.

---

## Commands Used

| Command | Times Used | Purpose |
|----------|-------------|----------|
| git clone | 1 | Clone instructor's repository |
| git checkout | 20+ | Switch between branches |
| git branch | 10+ | View and manage branches |
| git merge | 2 | Merge dev and conflict-simulator into main |
| git add | 30+ | Stage resolved conflicts |
| git commit | 15+ | Commit resolved changes |
| git push | 10+ | Push to my repository |
| git fetch | 2 | Fetch updates from instructor |
| git pull | 1 | Pull updates |
| git stash | 2 | Save temporary work |
| git cherry-pick | 1 | Copy specific commit |
| git rebase | 1 | Rebase feature branch |
| git reset | 3 | Undo commits (soft/mixed/hard) |
| git revert | 1 | Safe undo |
| git tag | 2 | Create release tags |
| git status | 50+ | Check repository state |
| git log | 30+ | View history |
| git diff | 20+ | Compare changes |

---

## Conflicts Resolved

### Merge 1: main + dev (6 files)

#### Conflict 1: config/app-config.yaml
- **Issue:** Production used port 8080, development used 3000  
- **Resolution:** Unified config with environment-based settings  
- **Strategy:** Kept production as default; added dev override  
- **Difficulty:** Medium  
- **Time:** 15 minutes  

#### Conflict 2: config/database-config.json
- **Issue:** Different database hosts and SSL settings  
- **Resolution:** Added separate profiles for both environments  
- **Strategy:** Used structured JSON with environment keys  
- **Difficulty:** Medium  
- **Time:** 10 minutes  

#### Conflict 3: scripts/deploy.sh
- **Issue:** Conflicting deployment strategies (production vs docker)  
- **Resolution:** Added `DEPLOY_ENV` variable logic  
- **Strategy:** Made script dynamic for both modes  
- **Difficulty:** Hard  
- **Time:** 20 minutes  

#### Conflict 4: scripts/monitor.js
- **Issue:** Different monitoring intervals and log styles  
- **Resolution:** Used environment-based configuration object  
- **Strategy:** Used `process.env.NODE_ENV` for conditional behavior  
- **Difficulty:** Medium  
- **Time:** 15 minutes  

#### Conflict 5: docs/architecture.md
- **Issue:** Different architectural content  
- **Resolution:** Merged both into a single unified doc  
- **Strategy:** Created sections for each environment  
- **Difficulty:** Easy  
- **Time:** 10 minutes  

#### Conflict 6: README.md
- **Issue:** Different feature lists and versions  
- **Resolution:** Combined all features with clear environment labels  
- **Strategy:** Organized sections by Production, Development, and AI Experimental  
- **Difficulty:** Easy  
- **Time:** 10 minutes  

---

### Merge 2: main + conflict-simulator (6 files)
- **Similar conflict structure:** handled same as first merge  
- **Outcome:** All conflicts successfully merged and project stable  

---

## Most Challenging Parts

1. **Understanding Conflict Markers:**  
   Learned what `<<<<<<<`, `=======`, and `>>>>>>>` mean — the key to resolving correctly.  

2. **Choosing the Right Code:**  
   The hardest part was deciding what to keep; had to carefully read both sides.  

3. **Complex Script Conflicts:**  
   `deploy.sh` required combining two logics without breaking production.  

4. **Testing After Resolution:**  
   Ensured merged scripts executed properly after resolution.  

---

## Key Learnings

### 🧠 Technical Skills
- Mastered Git conflict resolution  
- Learned `git diff`, `rebase`, and `cherry-pick`  
- Understood Git reset and revert differences  
- Gained full workflow experience  

### 🧭 Best Practices
- Always read both sides before resolving  
- Test before committing  
- Commit frequently with clear messages  
- Use `git status` and `git log` often  

### ⚙️ Git Workflow Insights
- Conflicts are normal — not mistakes  
- Git keeps a full history (you can always recover!)  
- `git reflog` is a lifesaver  
- Document everything for traceability  

---

## Reflection
This Git Mastery Challenge made me truly confident in handling real-world Git operations.  
I now understand how to **analyze, resolve, and document conflicts**, and when to use commands like **rebase** or **reset**.  
Most importantly, I learned that Git is not just a tool — it’s a skill that builds **confidence, precision, and teamwork** in development.

---

