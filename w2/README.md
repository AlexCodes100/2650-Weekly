# Week 2

## Question 1

### Git Local

![Git_local](Git_local.png)

### Git Remote

![Git_remote](Git_remote.png)

### Answers to questions

#### A Mixed Bag - Grabbing just 1 commit

This exercise teaches the command git cherry-pick commit. What it does is that it lets us choose 1 or more commit and move them below wherever the HEAD is pointing. It's a great command to move different revisions or fixes into a single branch after.

#### A Mixed Bag - Juggling commits

This exercise teaches us the command git rebase -i HEAD~ which is like using the rebase command but it lets you choose which commits you want to move, if you want to reorder them or if you want to choose some but not others. It's great for merging feature branches but with specific commits.

#### A Mixed Bag - Juggling commits 2

This exercise was like the one before except we used the git cherry-pick command. In my opinion this one is a better command used in smaller developments.

#### Push & Pull -- Git Remotes - 7. Diverged History

This exercise shows one of the most common situations when working with a remote repository. It tells us that we need to have the most updated version of the remote repository in our local before pushing our changes. For this we see different combinations of fetch with merge or rebase and how git pull combines these options.