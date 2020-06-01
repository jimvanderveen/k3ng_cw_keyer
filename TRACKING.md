# Keeping my fork up-to-date

My plan is to keep my *master* branch tracking K3NG's *master*.
My repository is labeled *mine*, K3NG's is *upstream*.

This is intended to allow me to work on my own keyer (adding hardware,
using various Arduino's, etc.), while still keeping up with K3NG's
development.

** This assumes that I am _not_ contributing to K3NG's project! **

1. Save uncommitted changes, e.g. git stash
1. Verify: `git status -vv` doesn't list anything
1. Switch to my fork's master: `git fetch mine && git checkout master`
1. Pull updates from K3NG: `git fetch upstream`
1. Save to my repo: `git merge upstream/master master`
