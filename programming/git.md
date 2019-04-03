# Git

I love Git and version control. And I use version control over any project I do. I follow a [series of rules](../focusing/rules.md#git) when dealing with Git.

## Notes

- Commit as often as you can. Ideally after each micro-iteration, when something new is working.
  - This way, at the end of the day you can just rebase the whole branch and squash all of the micro-commits in a whole commit implementing the whole new features.
- Good git workflow to make changes to new projects: clone, fork (`hub fork`), 'git checkout -b my-feature', work, commit, 'git push -u nikitavoloboev my-feature', work, commit, 'git push'.
- If you’re doing things right, there’s only two kinds of branches anyways, master and feature branches. Feature branches can be squashed and rebased off master (minimizing the issue of merge conflicts and making for easier management of the commit history) and merged to master from there without requiring further conflict resolution. ([Trunk-Based Development](https://paulhammant.com/2013/04/05/what-is-trunk-based-development/))
- A Git branch is just a pointer to a commit. Git commits, however, also contain the hash of the parent commit(s), so by referring to that commit you also refer too all ancestors.
- Squash + rebase (for feature branches) are good for PRs. No one cares that it took you 20 tries to get the feature right, what matters is what went into the pull request, which is usually one commit.

## Links

- [Git from the Bottom Up](https://jwiegley.github.io/git-from-the-bottom-up/)
- [Flight rules for git](https://github.com/k88hudson/git-flight-rules#readme)
- [Great Git workflow instructions](https://github.com/rvolosatovs/turtlitto/blob/master/CONTRIBUTING.md#readme)
- [GIT Conventions](https://medium.com/@tjholowaychuk/git-conventions-a940ee20862d)
- [Learn Git branching](https://learngitbranching.js.org/)
- [Gitbase](https://github.com/src-d/gitbase) - SQL interface to Git repositories.
- [Gitea](https://github.com/go-gitea/gitea) - Easiest, fastest, and most painless way of setting up a self-hosted Git service.
- [How to Write a Git Commit Message](https://chris.beams.io/posts/git-commit/)
- [How I Use Git](https://hugogiraudel.com/2018/02/17/how-i-use-git/)
- [clog-cli](https://github.com/clog-tool/clog-cli#readme) - Generate beautiful changelogs from your Git commit history.
- [git rebase for fame and power](http://www.charlesetc.com/rebase-for-fame/)
- [gitbatch](https://github.com/isacikgoz/gitbatch) - Manage your git repositories in one place.
- [Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0-beta.2/) - Specification for adding human and machine readable meaning to commit messages.
- [git absorb](https://github.com/tummychow/git-absorb) - Git commit --fixup, but automatic.
- [ghq](https://github.com/motemen/ghq) - Manage remote repository clones.
- [git-flow](https://github.com/nvie/gitflow) - Collection of Git extensions to provide high-level repository operations for Vincent Driessen's [branching model](http://nvie.com/git-model).
- [gitin](https://github.com/isacikgoz/gitin) - Commit/branch/status explorer for git.
- [Lab](https://github.com/zaquestion/lab) - Wraps Git or Hub, making it simple to clone, fork, and interact with repositories on GitLab.
- [Tips for a disciplined git workflow (2019)](https://drewdevault.com/2019/02/25/Using-git-with-discipline.html)
- [Git Town](https://github.com/Originate/git-town) - Generic, high-level Git workflow support.
- [libgit2](https://libgit2.org/) - Portable, pure C implementation of the Git core methods provided as a re-entrant linkable library.
- [git-delete-squashed](https://github.com/not-an-aardvark/git-delete-squashed) - Delete branches that have been squashed and merged into master.
- [rebase-editor](https://github.com/sjurba/rebase-editor) - Simple terminal based sequence editor for git interactive rebase.
- [git-standup](https://github.com/kamranahmedse/git-standup) - Recall what you did on the last working day. Psst! or be nosy and find what someone else in your team did.
- [git-rs](https://github.com/chrisdickinson/git-rs) - Implementing git in rust for fun and education.
