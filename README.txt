拉取Git项目到本地
1. 打开终端，cd到自己想要存放项目的文件夹
$ cd /Users/ioskaifa/Desktop
2. 输入git clone url,url为你要拉取的项目地址
$ git clone https://github.com/...


提交本地代码到Git仓库
1. git add 你改动后的文件,如果想要全部上传 git add .
$ git add .
2. 执行git commit -m “添加注释”
$ git commit -m "注释"
3. git push 上传，可能会让你输入github账号和密码按提示输入即可
$ git remote add origin https://github.com/yuanzhihao812/YYY.git
