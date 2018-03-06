# hello_git
learning how to use git
這個是用來記錄自己慣用的git方法

<pre>
將專案加入git控制，或是建立git專案
方法1
	新增一個全新的git專案 $ git init 檔案 
	幫一個資料夾加入git，到資料夾路徑下 $ git init
	資料夾就會多出一個.git的檔案，這樣之後的資料夾都可以用git來管理
方法2
	直接再git的網頁上(GitHub or GitLab)建立一個新的repository

從遠端下載到本地端 $ git clone 網址

查看git狀態 $ git status

add
	單一 $ git add 檔案
	全部 $ git add .

取消add
	單一 $ git reset HEAD 檔案
	全部 $ git reset HEAD .

commit
	單一 commit $ git commit 檔案 -m "文字"
	全部 commit $ git commit . -m "文字"
		commit $ git commit -am "文字"

上傳到遠端
	$ git push

從遠端下載到本地端
	$ git pull

自己開發方便密技
	修改的話就直接不管add與commit直接下 $ git commit . -m "文字" 之後就能push上去了
	但是如果有新增檔案的話必須要add後才可以，因為新的檔案git沒辦法抓到
</pre>

<pre>
團隊開發會遇到的事情

	push時如果沒辦法push表示遠端的檔案跟本地端的不一樣，會無法push
	解決辦法必須要先pull下來做比對
	修改好後，再次commit
</pre>
	

