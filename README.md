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





lab2
● Tell me how to list tags.

to List Tags:
git tag



● Tell me how to delete tag locally and remotely
Delete a Tag Locally:

git tag -d v1.7
Delete a Tag Remotely:

git push origin --delete tag v1.7



add image 
![Alt Text](https://github.com/ABDULLAHTALLAT/my-local-repo/blob/main/images%20(1).jpg)
