🧑‍🎓 Student Information

Name: Nethala Vinay

Student ID: 24A95A0513

Repository: https://github.com/vinay-nethala/git-solved-24A95A0513

Date Started: 25-10-2025

Date Completed: 28-10-2025



---

📘 Task Summary

Cloned the instructor’s repository containing multiple pre-built merge conflicts across branches (main, dev, and conflict-simulator).

Resolved all conflicts manually using proper Git workflows.

Practiced and mastered almost every major Git command through hands-on execution.



---

🧮 Commands Used

Command	Times Used	Purpose

git clone	1	Clone instructor’s repository
git checkout 20+	Switch between branches
git branch	10+	View and manage branches
git merge	2	Merge 'dev' and 'conflict-simulator' into main
git add	    30+	Stage resolved conflicts
git commit	15+	Commit resolved changes
git push	10+	Push updates to remote repository
git fetch	2	Fetch updates from instructor
git pull	1	Pull latest changes
git stash	2	Save temporary work
git cherry-
pick	    1   Apply a specific commit
git rebase	1	Rebase a feature branch
git reset	3	Undo commits (soft/mixed/hard)
git revert	1	Safely undo a commit
git tag	    2	Create release tags
git status	50+	Check repository status
git log	    30+	View commit history
git diff	20+	Compare changes between versions



---

🔧 Conflicts Resolved

🔹 Merge 1: main + dev (6 Files)

1. config/app-config.yaml

Issue: Port mismatch (8080 vs 3000)

Resolution: Unified config supporting environment-based ports

Strategy: Defaulted to production, added optional dev mode

Difficulty: Medium | Time: 15 min



2. config/database-config.json

Issue: Different DB hosts and SSL modes

Resolution: Separate profiles for both environments

Strategy: Structured JSON with production and development keys

Difficulty: Medium | Time: 10 min



3. scripts/deploy.sh

Issue: Conflicting deployment methods

Resolution: Conditional logic based on DEPLOY_ENV

Strategy: One script for both prod and dev

Difficulty: Hard | Time: 20 min



4. scripts/monitor.js

Issue: Different log formats and intervals

Resolution: Environment-based configuration object

Strategy: Used process.env.NODE_ENV

Difficulty: Medium | Time: 15 min



5. docs/architecture.md

Issue: Different architectural explanations

Resolution: Combined both into a detailed unified section

Difficulty: Easy | Time: 10 min



6. README.md

Issue: Conflicting feature lists and version info

Resolution: Combined all with clear category grouping

Strategy: Organized by Core, Dev, and Prod features

Difficulty: Easy | Time: 10 min





---

🔹 Merge 2: main + conflict-simulator (6 Files)

1. config/security.yaml

Issue: Conflicting authentication methods

Resolution: Combined JWT and OAuth modes

Strategy: Used environment variable toggle

Difficulty: Medium | Time: 15 min



2. src/api/userController.js

Issue: Different error handling logic

Resolution: Unified with improved try-catch and logging

Difficulty: Hard | Time: 20 min



3. src/api/productController.js

Issue: Conflicting response formats

Resolution: Standardized JSON response structure

Difficulty: Medium | Time: 15 min



4. utils/logger.js

Issue: Different log levels and formatting

Resolution: Created a universal logger with configurable levels

Difficulty: Medium | Time: 10 min



5. tests/app.test.js

Issue: Different test cases

Resolution: Combined both sets after validation

Difficulty: Easy | Time: 10 min



6. README.md

Issue: Overlapping merge notes

Resolution: Cleaned and documented final conflict resolution

Difficulty: Easy | Time: 5 min





---

💪 Most Challenging Parts

Understanding conflict markers (<<<<<<<, =======, >>>>>>>)

Deciding which version to keep after comparison

Handling totally different logic in scripts

Testing after every merge to ensure project stability



---

🧠 Key Learnings

🔸 Technical Skills

Learned to resolve merge conflicts confidently

Understood how conflict markers work

Mastered git diff, git log, and git reflog

Practiced advanced commands like rebase, revert, and cherry-pick


🔸 Best Practices

Always read both sides before resolving

Test code after each merge

Write meaningful commit messages

Use git status frequently

Commit small and logical changes


🔸 Workflow Insights

Conflicts are normal, not errors

Stay calm and analyze before choosing

Document resolutions when unsure

Back up work before merging (using stash or branch)



---

💭 Reflection

This challenge completely changed how I view Git.
Merge conflicts are not problems — they are opportunities to make better decisions.
Now, I feel confident handling conflicts and collaborating on real-world projects.


---

🏁 I Learned:

The difference between merge and rebase

How to undo changes safely using git revert and git reflog

How to maintain a clean and reliable Git workflow



---

🌟 Final Thought

> “Conflicts don’t break your project — they build your problem-solving skills.”
