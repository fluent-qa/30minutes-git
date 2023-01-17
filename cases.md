# Git Cases
- [ohshitgit](https://ohshitgit.com/)
  
## 我去,我提交错了

```sh
git reflog
# you will see a list of every thing you've
# done in git, across all branches!
# each one has an index HEAD@{index}
# find the one before you broke everything
git reset HEAD@{index}
# magic time machine

```

## 信息提交错了

```sh
git add . # or add individual files
git commit --amend --no-edit
```