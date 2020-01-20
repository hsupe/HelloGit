# HelloGit
Learn and experiment with Git

```bash
newBranch='Feature5'; change=$newBranch

git checkout master && git pull && git checkout -b $newBranch && echo "$change" >> Application1.txt && git add . && git commit -m "$change" && git push --set-upstream origin $newBranch && git checkout master && git branch -d $newBranch

change='RequirementChange' && sed -i "$ s/$/ $change/" Application1.txt && git add . && git commit -m "$change"
```
