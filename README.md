## 線上課程平台
- [git 使用](#git使用)
- [檔案架構](#檔案架構)

### git使用
- [git手冊](https://w3c.hexschool.com/git/b9be5b1e)
- [git notion筆記](https://jagged-veil-0e3.notion.site/git-216c171d3a774b3485baa0932aa46b40?pvs=4)

1.下載[Git - Downloads (git-scm.com)](https://git-scm.com/downloads)

2.clone專案，建立通道，之後都可以直接傳到github(自己的先備份一下，之前都有被覆蓋的經驗QQ)

```Bash
git clone git@github.com:CARRYUU/sscs-frontend.git
```
3.解衝突，把跟自己衝突到的程式碼修整一下
4.準備push程式碼上去
看程式碼的狀態
```Bash
git status
```
將程式碼添加
```Bash
git add .
```
將程式碼註解
```Bash
git commit -m 'feat: rewrite Readme'
```

將github檔案拉下來解衝突
```Bash
git pull origin main
```
解完衝突推上去
```Bash
git pull origin main
```
### 相關git commit 指令
- 註解規範
    - feat: 新增/修改功能 (feature)。
    - fix: 修補 bug (bug fix)。
    - docs: 文件 (documentation)。
    - style: 格式 (不影響程式碼運行的變動 white-space, formatting, missing semi colons, etc)。
    - refactor: 重構 (既不是新增功能，也不是修補 bug 的程式碼變動)。
    - perf: 改善效能 (A code change that improves performance)。
    - test: 增加測試 (when adding missing tests)。
    - chore: 建構程序或輔助工具的變動 (maintain)。
    - revert: 撤銷回覆先前的 commit 例如：revert: type(scope): subject (回覆版本：xxxx)。
### 檔案架構
```Bash
├─page
│      AddNewChapter.html
│      AddNewCourse.html
│      CourseContent.html
│      ManageChapter.html
│      SearchCourse.html
│      StudentCourse.html
│      StudentInfo.html
│      test.html
│      test1.html
│      tingtest.html
│      validcourse.html
│
├─public
│      132.png
│      133.png
│
└─style
        global.css
```
