What I can do is this:

Make two branches and merge them to a single branch.  

What I would like to do is:

Make several branches when work pauses I would like to push the branch to
server.  Then, perhaps on another machine, pull all branches and continue work.  

Desired workflows below.

So from fresh machine:

* Pull all branches
* work on branches
* maybe make new branch
* Push all branches including new branch

From fresh machine

* Pull all branches
* work on branches
* merge two (or more) branches
* push everything and have the merge push too.  

In this case there will be fewer branches to push then pull.

An auxiliary project is pushing to keybase and a private git server.
I expect that I could make a script that would push to both.
