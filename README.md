# again
Scripts for repeatability while developing and debugging

Ever have something almost working, change it a bit and break it, then
try to go back to when it was almost working, and you're sure you've
put the code back to the way it was, but it doesn't work the same?

This repo is to help with situations like that.  Its main command
records the state of your code as a git commit, runs a test command,
and saves the output into a directory named for the git commit.

Other commands let you mark the latest such commit as a checkpoint,
and squash non-checkpoint commits.
