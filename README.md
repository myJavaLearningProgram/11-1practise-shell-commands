# 命令行练习：常用的Linux命令

请在如下文件中完成Linux命令挑战：

- `ls`命令练习 practise-ls/solution.sh
- `mv`命令练习 practise-mv/solution.sh
- `mv`命令练习 practise-rename/solution.sh
- `rm`命令练习 practise-remove/solution.sh
- `rm`命令练习 practise-remove-all/solution.sh
- `cp`命令练习 practise-cp/solution.sh
- `cp`命令练习 practise-cp-all/solution.sh
- `mkdir`命令练习 practise-mkdir/solution.sh
- 重定向练习 practise-append/solution.sh

# 请切记，只提交对`solution.sh`文件的修改，不要提交其他文件！！！！

运行`mvn clean verify`会对目录中的文件进行一些修改，请不要提交它们。欲丢弃这些修改，可执行：

```
git add '*solution.sh' && git commit -m 'Temp' && git add . && git reset --hard && git reset HEAD~
```

# 请注意，如果你使用的是Windows，请不要在IDEA或者cmd中运行`mvn clean verify`，而是在Git bash中运行！


在提交Pull Request之前，你应当在本地确保所有代码已经编译通过，并且通过了测试(`mvn clean verify`)

-----
注意！我们只允许你修改以下文件，对其他文件的修改会被拒绝：
- practise-ls/solution.sh
-  practise-mv/solution.sh
-  practise-rename/solution.sh
-  practise-remove/solution.sh
-  practise-remove-all/solution.sh
-  practise-cp/solution.sh
-  practise-cp-all/solution.sh
-  practise-mkdir/solution.sh
-----


