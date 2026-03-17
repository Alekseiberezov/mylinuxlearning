---
typora-root-url: ./jichu
---

# 本篇来讲两个命令-which和-find命令

## which

which命令被用来查找命令的存储文件

which 参数1

![](/which.png)

## find

find是用来查找指定文件的命令

find 起始路径 -name "被查找文件名"

(su - root切换管理员账户)

![](/findname.png)

通过文件名找到了ceshi.txt文件

此命令能配合第五篇学习的通配符使用（通配符需在""中使用）

![](/testtongpei.png)



如果将-name改成-size即为按文件大小查找

find 起始路径 -size +|-n[kmg]

+，-大于小于

n表示大小数字

kmg表示大小单位

![](/find-size.png)