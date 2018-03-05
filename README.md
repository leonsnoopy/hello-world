# hello_git
learning how to use git
<pre>
簡單的幾個操作git的實用發法
建立git專案
方法1：
	如果要在一個資料夾下加入git管理，用console路徑到資料夾下 $ git init
	資料夾就會多出一個.git的檔案，往後的資料夾都可以用git來管理
方法2：
	或是直接再git web的網頁管理上建立一個新的repository

從遠端下載專案到本地端 $ git clone 網址

查看狀態 $ git status

add：  
	單一 $ git add 檔案
	全部 $ git add .

取消add：
	單一 $ git reset HEAD 檔案
	全部 $ git reset HEAD .

commit:
	單一 commit $ git commit 檔案 -m "文字"
	全部 commit $ git commit -m "文字"

上傳：
	git push
</pre>