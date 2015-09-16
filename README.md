## git-hooks

個人的通用 git hooks 設定

## 功能
commit 之前
- 如果 PHP 語法有問題會擋下來不給 commit
- 如果有 XXX 或是 `print_r()` `var_dump()` 之類的東西會顯示 warning 然後停五秒鐘

## 安裝

- 先 check out，放到某個你想要的地方，例如 `~\tool-repo\git-hooks`
- `cd {專案目錄}\.git\`
- `rm -rf hooks`
- `ln -s ~\tool-repo\git-hooks hooks`
