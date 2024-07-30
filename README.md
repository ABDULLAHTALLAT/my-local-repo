# my-local-rep
● Tell me how to remove them locally and remotely.

Remove Local Branches:


git branch -d dev
git branch -d test


Remove Remote Branches:

git push origin --delete dev
git push origin --delete test


● Tell me how to checkout another branch without commit
changes Stash Changes:

git stash
Checkout Another Branch:

git checkout <dev>
git checkout <test>
Apply Stashed Changes (if needed):

git stash apply