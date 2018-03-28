# git使用ssh密钥
---
参考网址：https://www.cnblogs.com/superGG1990/p/6844952.html

步骤：
* cd ~/.ssh
* cat ~/.ssh/id_rsa/pub
* 复制密钥
* 登陆你的github帐户。点击你的头像，然后 Settings -> 左栏点击 SSH and GPG keys -点击 New SSH key
* 然后你复制上面的公钥内容，粘贴进“Key”文本域内。 title域，自己随便起个名字
* 点击 Add key。
* $ ssh -T git@github.com
* 登陆你的github，就像本文开头的图例，你在上面可以看到你的ssh协议相应的url，复制
* git remote set-url origin git@github.com:someaccount/someproject.git
* 再用git remote -v 查看一下
