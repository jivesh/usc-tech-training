# Git Exercise for USC Tech
For this tutorial, let's try to do a few things with Git. 
_Note: Git CLI is preferred but it's ok if you want to start with the Github app_

1. Clone this repository to your device.
2. Create a branch and switch to that branch (try to figure out how to do that; find hints [here](https://git-scm.com/book/en/v2/Git-Branching-Basic-Branching-and-Merging))
3. Open the `names.py` file with your editor of choice and add a print statement with your name there.
4. Save the changed file.
5. Add your file to the local repository (Google how to add files, or use `git help`!)
6. Commit your change (i.e. the addition of the file) to your new branch,
7. Push your branch (which is currently local) to the remote (i.e. the online repository)
8. Go to the link for the repo [here](https://github.com/jivesh/usc-tech-training) and create a pull request
9. You're done! Do approach any of your leads or directors if you have issues at any point in this execise

Doing this exercise will also get you 1 Hacktoberfest PR: you'll be 25% on the way to getting that free t-shirt!

## Appendix: Handling merge conflicts
If your PR is approved, you would want to merge it. However, you may be blocked from merging it due to a _merge conflict_.  
[Read up on what merge conflicts are.](https://www.git-tower.com/learn/git/ebook/en/command-line/advanced-topics/merge-conflicts/)(The parts about the Git CLI may not be relevant for this exercise - the merge conflict you'll encounter here can be resolved via the web editor)
### After you've read that article
You may resolve this merge conflict via the web editor. For this situation, merge conflicts will likely occur when 2 people add their name on the same line. Resolving a merge conflict means deciding which branch's code you want. In this case, you want both branches' code i.e. both people's names. To resolve this, simply delete the markers that Git has included (for instance `<<<<<<< HEAD` and `=======`)
