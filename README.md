# KustomizeTest
用来测试kustomize与argo协作

# 工作流程
1.根据工作负载类型创建新patch.ymal文件到对应目录
2.根据工作负载类型更新latest目录下的软连接
3.提交更改到仓库，argocd同步更新资源