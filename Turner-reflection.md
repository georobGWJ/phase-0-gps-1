# Guided Pairing Session 1.1 Reflection

**What Git concepts were you struggling with prior to the GPS session?**
I was confused how versioning worked once you had multiple local branches going in addition to the GitHub branch. Specifically, I was confused about why you could create a branch, update files, add and commit those files and push the update back to the Master branch of GitHub but the local Master branch doesn't mirror those changes until you update it separately. It seemed counter-intuitive that the local Master and GitHub master wouldn't try and auto-sync. In hindsight it makes sense that those wouldn't auto-sync since that would remove some control from the programmer and could be _very_ bad if you had separately updated the local Master and planned on merging it later.

**What concepts were clarified during the GPS?**
I gained more insight on reasons to branch other than to create safe places to implement new features or to have multiple coders working on different parts of the code.

I also gained a better understanding of how branches behave both locally and on GitHub and know now to be more careful and pay attention to keeping different branches merged. More specifically, it's important to remember to keep your branches in check via merging, lest you end up with a dense and confusing mess of branches.

Finally, it was satisfying to create and resolve a merge conflict. It was pleasantly straight-forward.

**What questions did you ask your pair and the guide?**
I asked about where to find the code to review for a pull request, about how and when ```git diff``` works and why the ```git pull``` command when run in a freshly created branch wasn't downloading changes that had been committed and merged to the GitHub project. I couldn't figure out that last one and ended up doing a ```git merge master``` when I had the new branch checked out. 

We also briefly discussed absolute versus relative filepaths and I am going to do some independent research to ensure I understand them.

**What still confuses you about Git?**
I understand how to use the basic commands and do a small amount of troubleshooting but when things go completely sideways, I don't know how to address the problem outside of Googling. I haven't had anything break that badly in the repos I've created but have seen my cohort-mates struggling with some bigger issues and wish I knew enough to help. And I still need to figure out why my ```git pull``` wasn't working in my new branch (as mentioned above.)

**How was your first experience of pairing in a GPS?**
I had only a guide, Peter. He was very friendly and helpful but I had no cohort-mates to pair with. Tomorrow I will be pairing with a cohort-mate for Challenge 2.2, so I'll know then!