## GIT

When you encounter the message indicating that you have divergent branches, it means that the state of your local branch and the remote branch (in this case, `origin/main`) have both progressed independently and now contain different commits that need to be reconciled.

To proceed, you must choose one of the mentioned strategies to handle the divergence. Here’s a quick guide on what each option does, so you can decide how to proceed:

1. **Merge (git config pull.rebase false)**:
   - This will create a merge commit in your local branch that combines the changes from both branches (local and remote).
- Run this command if you prefer to maintain a history that includes all changes and their context:

```bash
git pull --no-rebase
```

2. **Rebase (git config pull.rebase true)**:
- This will apply your local changes on top of the changes from the remote branch. The commit history will be linear.
- Run this if you prefer a cleaner history without merge commits:

```bash
git pull --rebase
```

3. **Fast-forward only (git config pull.ff only)**:
- This will move your local branch pointer forward only if it is a simple fast-forward
- operation, meaning no merge or rebase is required.
- This is useful if you want to strictly avoid merge commits and only update your branch if the remote branch is ahead.
- Use this command if you prefer this behavior:

```bash
git pull --ff-only
```

4. **Setting defaults globally**:
- If you always want to use a specific strategy, you can set a global default. For example, for merge:

```bash
git config --global pull.rebase false
```

- Or for rebase:

```bash
git config --global pull.rebase true
```

- Or for fast-forward only:

```bash
git config --global pull.ff only
```

Here's a one-liner example for each strategy to execute a pull command with the specified behavior:

- For merging:
```bash
git pull --no-rebase
```

- For rebasing:
```bash
git pull --rebase
```

- For fast-forward only:
```bash
git pull --ff-only
```

Choose the strategy that aligns with your workflow or organizational guidelines. Once specified, execute the command



Before you can proceed with a `git rebase`, you must ensure that your working directory is clean, meaning it should not have any unstaged or uncommitted changes. Here are the steps to resolve this issue:

1. **Review Your Changes**:
   - Check your current changes to see what modifications exist.
   
     ```bash
     git status
     ```

2. **Stage Your Changes**:
   - If you want to keep your changes and make them part of the next commit, you need to stage them:

     ```bash
     git add .
     ```

3. **Commit Your Changes**:
   - After staging, commit your changes:

     ```bash
     git commit -m "Describe your changes"
     ```

4. **Stash Your Changes**:
   - If you do not want to commit these changes yet and temporarily save them, you can stash them:

     ```bash
     git stash
     ```

   - This will store your uncommitted changes and leave your working directory clean.

5. **Rebase After Stashing**:
   - Once stashed, you can proceed with the rebase:

     ```bash
     git rebase
     ```

6. **Apply Your Stash (     - If you stashed your changes, you can reapply them after completing the rebase:

     ```bash
     git stash pop
     ```

Here's a step-by-step guide summarizing the process:

### If you decide to commit the changes:
1. **Stage your changes**:

   ```bash
   git add .
   ```

2. **Commit the changes**:

   ```bash
   git commit -m "Your commit message"
   ```

3. **Proceed with the rebase**:

   ```bash
   git pull --rebase
   ```

### If you decide to stash the changes:
1. **Stash your changes**:

   ```bash
   git stash
   ```

2. **Proceed with the rebase**:

   ```bash
   git pull --rebase
   ```

3. **Reapply your stashed changes**:

   ```bash
   git stash pop
   ```

Choose the approach that suits your workflow. If you opt to stash and there are conflicts when applying the stash, you might need to manually resolve those conflicts.