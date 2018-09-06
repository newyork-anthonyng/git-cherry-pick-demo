Hello World


How are you doing?

This is some more text.
THIS IS ANOTHER LINE.

# `git cherry-pick` demo
This shows an example of how `git cherry-pick` only replays the work done in the commit. You can lose work from other commits that you don't `cherry-pick`.

1. `git fetch --all`
1. `git checkout master`
1. `git cherry-pick 9ced45bd7329fe6d3a80b85bc3a5433b1a2b87da`
  1. This commit SHA is the last one from from the `new` branch.
1. Notice how there are differences between the `new` and `master` branch.
