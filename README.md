# git

## Warm-Up
- how to start a repo from scratch? 
    - `git init` local method
    - on GitHub `git clone` and either `git push --force` or `git pull` methods
- how to *undo* mistakes?
    - `git revert` vs. …
    - `git reset` vs. …
    - `git reset --hard`vs. …
    - `git restore` (experimental command!) 
- `rebase`:
    - reparenting (Changing the parent (starting) commit upon which a series of commits is built)
    - history modification (fixing or deleting broken commits or changing the order in which commits are applied)
- `rebase` vs. `merge`
- how to go to a specific point in history?
    - `git checkout SHA` ⟶ `DETACHED HEAD` problem
    - interaction with branches
- `git gui`: building commits along the way interactively (for the *mess around* type of workflows)

## The Open Source model
- remotes: `pull`, `push`, `fetch`, `merge`
- GitHub: forks, branches and PRs
- strategies for keeping your fork up-to-date: `rebase` or `merge`
- talking about PRs: what about CI? Some concepts
- a more thorough and deailed explanation can be found on the [Numpy Contributor's Guide](https://docs.scipy.org/doc/numpy/dev/gitwash/index.html). This guide can be adapted to your own needs, see [gitwash](https://github.com/matthew-brett/gitwash).
