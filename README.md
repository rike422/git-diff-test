# git-diff-test

この状態でmasterで最新のコミットであるe54330c241f9a0f9f51ca1e5eb7ea07ee0b412f8と現状の差分を取る

```
_(master)_ >#> git diff --name-status e54330c241f9a0f9f51ca1e5eb7ea07ee0b412f8
A       20201022_0010.txt
A       20201022_0011.txt
A       b.txt
A       e.txt
A       old.txt
A       old2.txt
```

プルリクエスト側でe54330c241f9a0f9f51ca1e5eb7ea07ee0b412f8以前に追加されたファイルのdiffも取れる
