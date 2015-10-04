# Armello.zh_TW
阿門羅王國中文化

基於目前只有簡中翻譯且翻譯品質低落而開啟的翻譯計劃

# 參考流程

以下直接是寫執行命令，如果是用其它工具的人，UI上應該會有對應的功能。

1. 點選 fork 將專案複製至自已的帳號底下，
2. 將你 fork 過去的專案，也就是你自己的專案 clone 到你的本地端
3. 在 clone 的專案下新建分支（branch），並切換到你的分支上，名稱可取為「帳號名-trans」，命令為`git branch 名稱-trans` + `git checkout 名稱-trans`
4. 執行 `git remote add neoremote https://github.com/codebayin/Armello.zh_TW.git` 將本庫加為遠端庫
5. 執行 `git remote update` 更新
6. 執行 `git fetch neoremote master` 拉取本庫更新到你的本地
7. 執行 `git rebase neoremote/master` 將更新內容整併到你的分支

以上為初始化流程，如果 neoremote 有更新請執行 5~7 即可，平時請在自己的分支上作業。
最後發 pull-request 將翻譯內容加回至本專案，每次發之前請務必確認是否同步了最新版。
（建議翻譯部份成果就可加回，太多可能導致重覆翻譯或衝突發生）
