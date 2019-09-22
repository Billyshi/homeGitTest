Git is a version control system.
Git is free.
test 

dev modify
dev modify002
20190922
other modify
shixin add.
other modify 02
other modify 17:26
billy在本地进行了修改 17：38，此时实际上其他人以修改并提交了东西到服务器上，查看会导致什么结果

测试：其他人已提交新文件到远程，此时本地修改了另一个文件，尝试是否能直接 git pull.
测试：远程分支修改了，在本地尝试 pull --rebase.
测试：远程和本地修改了同一个文件，执行 git pull --rebase
测试：本地此时修改了相同文件，尝试 rebase

测试：git diff

master modify night;
dev modify night
