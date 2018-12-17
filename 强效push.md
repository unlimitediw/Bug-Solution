```git push -f origin master```

* 会完全更新远程repository
* 体会： 当删除.git 或者push -f origin master 导致remote repository的.git与local.git 无法对应时, 将会被限制同名文件无法merge. 导致 no fast forward 或unrelated histories的错误. 即使--allow-unrelated-hisotries允许merge,仍然不允许同名文件存在.
