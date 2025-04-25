一个协同工作的git仓库测试用例

先切换自己的分支,然后编辑代码.

git checkout -b 自己的分支(假设dev)
git add .
git commit -m "......"
git push origin dev(创建的分支)

这样远程仓库就有了一个dev分支,及其代码.


git checkout main
git pull
git merge dev
就完成了主分支合并dev分支.