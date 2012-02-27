<link href="http://icaker.github.com/markdown.css" rel="stylesheet"></link>

step 1:注册帐号；
step 2:按照官方的帮助文档设置环境，个人感觉2.Backup and remove existing SSH keys不用做，我按照这个步骤弄了，后来在test的时候提示路径错误：(不知道为何。。
step 3:建立仓库，用于存放代码；
step 4:fork一个仓库内的东西来，例如 $ git clone git@github.com:icaker/icaker.github.com.git USERNAME.github.com;
       （由于作者@icaker学术不精，也不知道哪些文件是完全无用的- -）
step 5：修改主要内容，主要index.md 或者index.html
       （在我看来，markdown比html语言简单，所以每次生成html时都是这么来的 $ markdown xxx.md > xxx.html）
	   $ cd USERNAME.github.com
	   $ git remote set-url origin git@github.com:USERNAME/USERNAME.github.com.git //设置二级域名?
	   $ git add index.md
	   然后用不同的编辑器进行修改，之后
	   $ git commit -m 'make a commitment descriping what you have done:)'
	   提交上去
	   $ git push origin master
step 6:可以登录浏览器看看效果了。http://USERNAME.github.com





