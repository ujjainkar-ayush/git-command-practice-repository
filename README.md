# git-command-practice-repository


|  # | Category | Git Command         | Syntax                                                       | Description                                    |
| -: | -------- | ------------------- | ------------------------------------------------------------ | ---------------------------------------------- |
|  1 | Setup    | `git --version`     | `git --version`                                              | Displays the installed Git version.            |
|  2 | Setup    | `git config`        | `git config [--global \| --system \| --local] <key> <value>` | Reads and writes Git configuration settings.   |
|  3 | Setup    | `git help`          | `git help <command>`                                         | Shows the manual/help for a Git command.       |
|  4 | Setup    | `git credential`    | `git credential <action>`                                    | Manages Git credentials.                       |
|  5 | Basic    | `git init`          | `git init [<directory>]`                                     | Initializes a new Git repository.              |
|  6 | Basic    | `git clone`         | `git clone <url> [<directory>]`                              | Clones an existing repository.                 |
|  7 | Basic    | `git add`           | `git add <pathspec>`                                         | Stages changes for commit.                     |
|  8 | Basic    | `git status`        | `git status`                                                 | Shows repository status.                       |
|  9 | Basic    | `git diff`          | `git diff [<options>] [<commit>] [-- <path>]`                | Displays differences between versions.         |
| 10 | Basic    | `git commit`        | `git commit [<options>]`                                     | Records staged changes into history.           |
| 11 | Basic    | `git rm`            | `git rm [<options>] <file>`                                  | Removes tracked files.                         |
| 12 | Basic    | `git mv`            | `git mv <source> <destination>`                              | Renames or moves files.                        |
| 13 | Basic    | `git restore`       | `git restore [<options>] <pathspec>`                         | Restores files or unstages changes.            |
| 14 | Basic    | `git checkout`      | `git checkout [<options>] [<branch>] [-- <file>]`            | Switches branches or restores files.           |
| 15 | Basic    | `git reset`         | `git reset [<mode>] [<commit>]`                              | Resets commits, staging area, or working tree. |
| 16 | History  | `git log`           | `git log [<options>]`                                        | Displays commit history.                       |
| 17 | History  | `git show`          | `git show [<object>]`                                        | Shows details of commits or tags.              |
| 18 | History  | `git diff-tree`     | `git diff-tree <tree-ish>`                                   | Compares tree objects.                         |
| 19 | History  | `git blame`         | `git blame <file>`                                           | Shows who last modified each line.             |
| 20 | History  | `git grep`          | `git grep [<options>] <pattern>`                             | Searches tracked files.                        |
| 21 | History  | `git shortlog`      | `git shortlog [<options>]`                                   | Summarizes commits by author.                  |
| 22 | History  | `git describe`      | `git describe [<commit>]`                                    | Gives human-readable commit names.             |
| 23 | History  | `git reflog`        | `git reflog [<options>]`                                     | Shows local reference history.                 |
| 24 | History  | `git bisect`        | `git bisect <subcommand>`                                    | Finds the commit introducing a bug.            |
| 25 | History  | `git ls-files`      | `git ls-files [<options>]`                                   | Lists tracked files.                           |
| 26 | Branch   | `git branch`        | `git branch [<options>] [<branchname>]`                      | Creates, lists, or deletes branches.           |
| 27 | Branch   | `git merge`         | `git merge [<options>] <branch>`                             | Merges branches.                               |
| 28 | Branch   | `git mergetool`     | `git mergetool [<options>]`                                  | Launches a merge conflict tool.                |
| 29 | Branch   | `git rebase`        | `git rebase [<options>] [<upstream>]`                        | Rebases commits.                               |
| 30 | Branch   | `git cherry-pick`   | `git cherry-pick <commit>`                                   | Applies a specific commit.                     |
| 31 | Branch   | `git revert`        | `git revert <commit>`                                        | Creates a commit that undoes another commit.   |
| 32 | Branch   | `git stash`         | `git stash [<subcommand>]`                                   | Temporarily saves uncommitted changes.         |
| 33 | Branch   | `git merge-base`    | `git merge-base <commit1> <commit2>`                         | Finds common ancestor of branches.             |
| 34 | Branch   | `git merge-file`    | `git merge-file <current> <base> <other>`                    | Merges individual files.                       |
| 35 | Branch   | `git rerere`        | `git rerere`                                                 | Reuses previous conflict resolutions.          |
| 36 | Branch   | `git clean`         | `git clean [<options>]`                                      | Removes untracked files.                       |
| 37 | Remote   | `git remote`        | `git remote [<subcommand>]`                                  | Manages remote repositories.                   |
| 38 | Remote   | `git fetch`         | `git fetch [<remote>] [<refspec>]`                           | Downloads remote changes.                      |
| 39 | Remote   | `git pull`          | `git pull [<remote>] [<branch>]`                             | Fetches and merges remote changes.             |
| 40 | Remote   | `git push`          | `git push [<remote>] [<refspec>]`                            | Uploads commits to a remote repository.        |
| 41 | Remote   | `git ls-remote`     | `git ls-remote [<remote>]`                                   | Lists remote references.                       |
| 42 | Remote   | `git show-ref`      | `git show-ref`                                               | Lists local references.                        |
| 43 | Remote   | `git tag`           | `git tag [<options>] [<tagname>]`                            | Creates and manages tags.                      |
| 44 | Advanced | `git filter-branch` | `git filter-branch [<options>]`                              | Rewrites repository history.                   |
| 45 | Advanced | `git revert`        | `git revert <commit>`                                        | Safely undoes a commit.                        |
| 46 | Advanced | `git format-patch`  | `git format-patch [<options>] <since>`                       | Creates patch files.                           |
| 47 | Advanced | `git am`            | `git am [<options>] [<mbox>]`                                | Applies patches as commits.                    |
| 48 | Advanced | `git apply`         | `git apply [<options>] <patch>`                              | Applies a patch without committing.            |
| 49 | Advanced | `git request-pull`  | `git request-pull <start> <url> [<end>]`                     | Generates a pull request summary.              |
| 50 | Advanced | `git send-email`    | `git send-email [<options>] <file>`                          | Sends patches via email.                       |
| 51 | Advanced | `git instaweb`      | `git instaweb [--start \| --stop]`                           | Launches a local Git web interface.            |
| 52 | Advanced | `git daemon`        | `git daemon [<options>]`                                     | Runs a Git server.                             |
| 53 | Advanced | `git bundle`        | `git bundle <subcommand>`                                    | Creates portable Git bundles.                  |
| 54 | Advanced | `git archive`       | `git archive [<options>] <tree-ish>`                         | Exports repository as ZIP/TAR.                 |
| 55 | Advanced | `git submodule`     | `git submodule <subcommand>`                                 | Manages submodules.                            |
| 56 | Advanced | `git gc`            | `git gc [--auto]`                                            | Cleans and optimizes repository.               |
| 57 | Advanced | `git fsck`          | `git fsck [<options>]`                                       | Verifies repository integrity.                 |
| 58 | Advanced | `git prune`         | `git prune [<options>]`                                      | Removes unreachable objects.                   |
| 59 | Advanced | `git count-objects` | `git count-objects [<options>]`                              | Counts Git objects.                            |
| 60 | Advanced | `git verify-pack`   | `git verify-pack -v <pack-index>`                            | Verifies pack files.                           |
| 61 | Plumbing | `git hash-object`   | `git hash-object [<options>] <file>`                         | Computes object hashes.                        |
| 62 | Plumbing | `git cat-file`      | `git cat-file <type> <object>`                               | Displays Git object contents.                  |
| 63 | Plumbing | `git update-index`  | `git update-index [<options>] <file>`                        | Updates the Git index.                         |
| 64 | Plumbing | `git write-tree`    | `git write-tree`                                             | Creates a tree object.                         |
| 65 | Plumbing | `git read-tree`     | `git read-tree [<options>] <tree-ish>`                       | Reads a tree into the index.                   |
| 66 | Plumbing | `git commit-tree`   | `git commit-tree <tree> [-p <parent>] -m <msg>`              | Creates a commit object.                       |
| 67 | Plumbing | `git ls-tree`       | `git ls-tree [<options>] <tree-ish>`                         | Lists tree contents.                           |
| 68 | Plumbing | `git update-ref`    | `git update-ref <refname> <new-value>`                       | Updates references.                            |
| 69 | Plumbing | `git symbolic-ref`  | `git symbolic-ref HEAD [<ref>]`                              | Reads or sets symbolic refs.                   |
| 70 | Plumbing | `git rev-parse`     | `git rev-parse [<options>] <rev>`                            | Parses revision identifiers.                   |
| 71 | Plumbing | `git rev-list`      | `git rev-list [<options>] <commits>`                         | Lists commit hashes.                           |
| 72 | Plumbing | `git for-each-ref`  | `git for-each-ref [<options>] [<pattern>]`                   | Iterates over references.                      |
| 73 | Plumbing | `git replace`       | `git replace <object> <replacement>`                         | Replaces Git objects.                          |
| 74 | Plumbing | `git diff-tree`     | `git diff-tree <tree-ish>`                                   | Compares tree objects.                         |
| 75 | Advanced | `git svn`           | `git svn <subcommand>`                                       | Integrates Git with SVN.                       |
| 76 | Advanced | `git p4`            | `git p4 <subcommand>`                                        | Integrates Git with Perforce.                  |
| 77 | Advanced | `git reflog`        | `git reflog [<options>]`                                     | Tracks local HEAD and branch movements.        |
