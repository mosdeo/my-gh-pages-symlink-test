嘗試復現以下 repo 的 symlink 效果  
<https://github.com/s4y/gh-pages-symlink-test>

並測試自己要的效果

驗證頁面：

1. link: https://mosdeo.github.io/my-gh-pages-symlink-test/link/ OK
2. cycle link: https://mosdeo.github.io/my-gh-pages-symlink-test/cyclelink/target/ Failed
3. 回上一層: https://mosdeo.github.io/my-gh-pages-symlink-test/folder/linkToPervLevel Failed
4. 連結到下一層檔案 https://mosdeo.github.io/my-gh-pages-symlink-test/linkToNextLevel.html