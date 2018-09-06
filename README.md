Hello World


How are you doing?

This is some more text.
This is another line.

# `git cherry-pick` demo
This shows an example of how `git cherry-pick` only replays the work done in the commit. You can lose work from other commits that you don't `cherry-pick`.

1. `git fetch --all`
1. `git checkout master`
1. `git cherry-pick a1a372a126a503aef6152ba6e99d41376eb1bb91`
  1. This commit SHA is the last one from from the `new` branch.
1. Notice how there are differences between the `new` and `master` branch.
