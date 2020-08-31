# helm-repo-example
helm-repo-example

```
helm package mychart
helm repo index .
```

```
git clone https://github.com/FeynmanZhou/helm-repo-example

# 拉取分支
git fetch
git checkout app/mychart

# 初始化
helm init --client-only

# 打包
helm package mychart

# 更新索引
helm repo index .

# 提交
git commit -a -m "[CI Build] Upload App"
git push origin HEAD:app/mychart

# Merge PR（人工或自动）
```
