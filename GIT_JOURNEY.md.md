

 Student Information

� Name: Nethala Vinay

� Student ID: 24A95A0513

� Repository: https://github.com/vinay-nethala/git-solved-24A95A0513

� Date Started: 25-10-2025

� Date Completed: 28-10-2025


� Task Summary

� Cloned the instructor�s repository containing multiple pre-built merge conflicts across branches (main, dev, and conflict-simulator).
� Resolved all conflicts manually using correct Git workflows.
� Practiced and mastered almost every major Git command through hands-on execution.



� Commands Used

+-------------------+-------------+-----------------------------------------------+
| Command           | Times Used  | Purpose                                       |
+-------------------+-------------+-----------------------------------------------+
| git clone         | 1           | Clone instructor�s repository                 |
| git checkout      | 20+         | Switch between branches                       |
| git branch        | 10+         | View and manage branches                      |
| git merge         | 2           | Merge 'dev' and 'conflict-simulator' into main|
| git add           | 30+         | Stage resolved conflicts                      |
| git commit        | 15+         | Commit resolved changes                       |
| git push          | 10+         | Push updates to remote repository             |
| git fetch         | 2           | Fetch updates from instructor                 |
| git pull          | 1           | Pull latest changes                           |
| git stash         | 2           | Save temporary work                           |
| git cherry-pick   | 1           | Apply specific commit                         |
| git rebase        | 1           | Rebase feature branch                         |
| git reset         | 3           | Undo commits (soft/mixed/hard)                |
| git revert        | 1           | Safe undo of a commit                         |
| git tag           | 2           | Create release tags                           |
| git status        | 50+         | Check repository status                       |
| git log           | 30+         | View commit history                           |
| git diff          | 20+         | Compare changes between versions              |
+-------------------+-------------+-----------------------------------------------+


---

� Conflicts Resolved

� Merge 1: main + dev (6 Files)

1. config/app-config.yaml

� Issue: Port mismatch (Production: 8080, Development: 3000)
� Resolution: Unified config supporting environment-based ports
� Strategy: Default to production, add optional development mode
� Difficulty: Medium
� Time: 15 minutes

2. config/database-config.json

� Issue: Different DB hosts and SSL modes
� Resolution: Created separate profiles for both environments
� Strategy: Structured JSON with �production� and �development� keys
� Difficulty: Medium
� Time: 10 minutes

3. scripts/deploy.sh

� Issue: Conflicting deployment methods (production vs Docker)
� Resolution: Added conditional logic based on DEPLOY_ENV
� Strategy: Dynamic script handling both environments
� Difficulty: Hard
� Time: 20 minutes

4. scripts/monitor.js

� Issue: Different log formats and intervals
� Resolution: Environment-based configuration object
� Strategy: Used process.env.NODE_ENV for behavior selection
� Difficulty: Medium
� Time: 15 minutes

5. docs/architecture.md

� Issue: Different architectural explanations
� Resolution: Merged both into a detailed combined section
� Strategy: Created environment-specific subsections
� Difficulty: Easy
� Time: 10 minutes

6. README.md

� Issue: Conflicting feature lists and version info
� Resolution: Combined all with clear category grouping
� Strategy: Organized features by �Core�, �Dev�, and �Prod�
� Difficulty: Easy
� Time: 10 minutes


---

� Merge 2: main + conflict-simulator (6 Files)

1. config/security.yaml

� Issue: Conflicting authentication methods
� Resolution: Combined both by allowing JWT and OAuth modes
� Strategy: Used environment variable to toggle between modes
� Difficulty: Medium
� Time: 15 minutes

2. src/api/userController.js

� Issue: Different error handling logic
� Resolution: Merged with improved try-catch and logging
� Strategy: Integrated best parts from both sides
� Difficulty: Hard
� Time: 20 minutes

3. src/api/productController.js

� Issue: Conflicting response formats
� Resolution: Standardized JSON response structure
� Strategy: Followed REST API best practices
� Difficulty: Medium
� Time: 15 minutes

4. utils/logger.js

� Issue: Different log levels and formatting
� Resolution: Created universal logger with configurable levels
� Strategy: Used NODE_ENV to adjust verbosity
� Difficulty: Medium
� Time: 10 minutes

5. tests/app.test.js

� Issue: Different test cases for same module
� Resolution: Combined both test sets after validation
� Strategy: Retained all passing tests
� Difficulty: Easy
� Time: 10 minutes

6. README.md

� Issue: Overlapping merge notes
� Resolution: Cleaned and documented final conflict resolution
� Strategy: Added �Final Merge Notes� section
� Difficulty: Easy
� Time: 5 minutes


---

� Most Challenging Parts

1. � Understanding Conflict Markers
� Initially confused by <<<<<<<, =======, and >>>>>>>.
� Learned that HEAD represents the current branch and the other side is the incoming branch.


2. � Choosing What to Keep
� Reading both versions fully helped in making better merge decisions.


3. � Complex Script Conflicts
� Some files had totally different logic � had to study both approaches before merging.


4. � Testing After Resolution
� Tested after each merge to ensure the code still worked properly.




---

� Key Learnings

� Technical Skills

� Learned to resolve merge conflicts confidently.
� Understood how conflict markers work.
� Mastered git diff, git log, and git reflog.
� Gained confidence with advanced commands like rebase, revert, and cherry-pick.

� Best Practices

� Always read both sides before resolving.
� Test code after every merge.
� Write meaningful commit messages.
� Use git status regularly.
� Commit small and logical changes.

� Workflow Insights

� Conflicts are normal � not errors.
� Stay calm and analyze both changes carefully.
� When unsure, document and seek clarification.
� Back up your work before merging (stash or new branch).


---

� Reflection

� This challenge completely changed how I view Git.
� Merge conflicts are not problems � they�re opportunities to make better decisions.
� Now, I feel confident handling conflicts and collaborating on real projects.

I Learned:

The difference between merge and rebase

How to undo changes safely using git revert or git reflog

How to maintain a clean and reliable Git workflow


> Final Thought:
�Conflicts don�t break your project � they build your problem-solving skills.�
