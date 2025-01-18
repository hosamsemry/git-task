## delete branch locally
git branch -d localBranchName

## delete branch remotely
git push origin --delete remoteBranchName

-------------------------------------------

Annotated tags store extra meta data such as: the tagger name, email, and date. This is important data for a public release.
Lightweight tags are essentially 'bookmarks' to a commit, they are just a name and a pointer to a commit, useful for creating quick links to relevant commits.

-------------------------------------------

1. When you want to avoid unnecessary merge commits and maintain a cleaner, linear commit history.

2. When the main branch (or any upstream branch) has progressed, and you want your branch to include those changes before continuing your work.

3. When you want to clean up messy commit history (e.g., squash multiple commits into one) before merging into the main branch.

4. When merging frequently would create merge commits that clutter history, or when multiple developers are working on the same feature 

5. When working with a forked repository and keeping your fork's main branch up to date with the upstream repository without creating merge commits.

6. When a branch is branched off the wrong base, and you need to move it to a different starting point.

7. When collaborating with others and you want to share a clean, logically organized commit history.

-----------------------------------------------

git tag 

-----------------------------------------------

locally git tag -d v1.0
remotely git push origin --delete v1.0

-----------------------------------------------

![image](template.png)