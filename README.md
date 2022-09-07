# 👇👇看这里👇👇

## 教程

1. Fork这个地址的仓库

![image-20220907201110292](https://found-img-blog.oss-cn-hangzhou.aliyuncs.com/img/image-20220907201110292.png)

2. 复制SSH地址

![image-20220907201215711](https://found-img-blog.oss-cn-hangzhou.aliyuncs.com/img/image-20220907201215711.png)

3. 新建一个文件夹(建议英文)，打开git终端
4. 执行命令`git clone 你刚刚复制的地址`将代码克隆到本地
   - `git clone git@github.com:Found-404/Fl-UI.git `
5. 执行`yarn`下载所用到的第三方包
6. 修改组件的代码
7. ...
8. 执行命令`git status -s`检查修改的部分
9. `git add .`上传所有修改的文件到暂存区
10. `git commit -m "提交描述信息"`将暂存区文件上传到仓库
11. `git push origin main`上传仓库到远程仓库，注意此时远程仓库是没有实时更新你修改的代码的！
12. 在你拉取的仓库中点击Pull requests

![image-20220907215533644](https://found-img-blog.oss-cn-hangzhou.aliyuncs.com/img/image-20220907215533644.png)

13. 点击New pull request创建拉取请求

![image-20220907215612891](https://found-img-blog.oss-cn-hangzhou.aliyuncs.com/img/image-20220907215612891.png)

14. 左边为主组件仓库的分支选择，右边为你本地仓库分支选择
15. 写好注释
16. 点击蓝色提交
