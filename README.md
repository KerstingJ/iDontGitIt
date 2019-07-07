## Adventures in Git

In a world far far away... not too far away, but still fairly far away. It's your first day on the space force as a VCS cadet, you walk briskly towards the control center to report to your new commander. You open the door to a frantic scene, sirens are blaring, lights flashing. No one even notices you are there. You overhear two controllers talking in hushed voices, they can't believe Captain Git has been captured.

A grumpy looking senior officer walks up to you.

> "You must be the new recruit. One hell of a day to start. What can we call you?"

**_create a new branch, open the intro.txt file and enter your name save it, then add, commit, and push your changes, then pull from the branch `part2`_**

```javascript --this looks nicer than no format
git checkout -b branchName
// this command creates and checks out a branch with the given name

echo "myName=yourName" > intro.txt
// overwrite intro.txt with the given string

git add intro.txt
// add intro.txt to staging area

git commit -m "Added my name to intro.txt"
// commit your changes with a helpful message

git push -u origin branchName
// push your local changes to your remote repository and add the new branch

git pull origin part2
// pulls the commits made on branch "part2" into your current working branch
```
