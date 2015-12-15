# git-show-branching-commits

A git subcommand to show commits from which branches are branched.

## Setup

Download git-show-branching-commits to a directory in the PATH.

## Usage

Run `git show-branching-commits -h` in one of your local git repositories to show the help of this command.

## Example

http://cgit.freedesktop.org/cairo/

<pre>
$ git show-branching-commits -r origin/master
showing logs to origin/master
db8a7f1 1.15.2 release
  -> origin/HEAD
     origin/master
e7acf4b pattern: allow for a floating one pixel rounded difference.
  -> origin/color-emoji
f6fd372 pattern: Restore dropped inclusion of cairoint.h
  -> origin/1.14
59e2a93 Post-release version bump
  -> origin/1.12
c84730d version: Post release version bump
  -> origin/1.10
de7270c [cairo] Describe the restrictions upon cairo_set_tolerance()
  -> origin/1.8
44e6cdd Increment version to 1.6.5 after the 1.6.4 release
  -> origin/1.6
107a748 Increment cairo version to 1.4.10 (and libtool versioning to 13:5:11)
  -> origin/1.4
a5f068e [test] Add 128 to any diff component such that differences are visible
  -> origin/1.2
568ce86 Increment CAIRO_VERSION to 1.1.1 after making branch tag BRANCH_1_0.
  -> origin/1.0
</pre>
