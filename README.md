# Git_Record



![git](https://user-images.githubusercontent.com/63569149/132827145-a19b649d-6978-44f4-898c-fe6defd85579.png)


# 看版本 git log
![image](https://user-images.githubusercontent.com/63569149/132827306-145d62c7-8e8f-451b-86ce-919b744bbc62.png)


# 退回版本 git reset --hard HEAD@{1}
![image](https://user-images.githubusercontent.com/63569149/132827419-a115aec9-6008-4ba3-896f-3baa0bcd280a.png)


# 退回后重新发送到remote， 需要 -f, 因为版本落后
![image](https://user-images.githubusercontent.com/63569149/132827514-77a49be1-66b3-4cd4-be92-22787422dedf.png)


# 手动在网页上，或者别人修改后，需要更新本地 git fetch, git branch -avv, 查看区别，然后git pull 拉到本地
![image](https://user-images.githubusercontent.com/63569149/132827784-c6136b12-ac7c-447c-891a-a48a2883223b.png)
![image](https://user-images.githubusercontent.com/63569149/132827900-d4f63e46-e9c0-4404-83a4-461ce01ef95f.png)
![image](https://user-images.githubusercontent.com/63569149/132828841-87b5667f-9b03-46e7-aca5-9ed100f040ed.png)


# 创建新的分支 git branch [分支名], git branch 查看分支， git checkout 切换分支
![image](https://user-images.githubusercontent.com/63569149/132830133-6dc008f8-c3a9-49d3-b9c4-a4df4e85ba86.png)

上传分支
执行 git push [主机名] [本地分支名]:[远程分支名] 即可将本地分支推送到远程仓库的分支中，通常冒号前后的分支名是相同的，如果是相同的，可以省略 :[远程分支名]，如果远程分支不存在，会自动创建：

git push origin dev1:dev1

![image](https://user-images.githubusercontent.com/63569149/132831612-e7c81c84-ec8a-43d6-95cb-4b97dedc72fa.png)

![image](https://user-images.githubusercontent.com/63569149/132831804-2c17b7d3-56a6-4000-beba-51f7abdfb55a.png)


更变默认push的 分支，原本一直是main，上传到main，传到分支需要 git push origin dev1:dev1 很麻烦
![image](https://user-images.githubusercontent.com/63569149/132832446-8b81fd61-1aec-4cdb-ad28-27fbbff51df6.png)


<<<<<<< HEAD
# 删除远程分支 branch
![image](https://user-images.githubusercontent.com/63569149/133038329-56173bf0-942a-4b91-83fd-92c483c77615.png)

=======
哈哈哈哈
>>>>>>> 408cca097da6340a0cc49f1ffca4b505e1c86f85


