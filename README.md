# makereal-lab-git-test

## Task 01

把自己的名字加到最底下的簽名區

然後開一個 Pull Request。

## Task 02

建立一個新的分支(名字隨意)，在專案根目錄下新增一個檔案 `hello.md`

完成後提交並推送這個分支，然後也開一個 Pull Request。

## Reference

- [Git 官網](https://git-scm.com/)
- [doggy8088/Learn-Git-in-30-days](https://github.com/doggy8088/Learn-Git-in-30-days/tree/master/zh-tw) (介面有點舊 但應該沒差?)

<details>
  <summary>走投無路時服用</summary>
  
## 教學 By ChatGPT

### ✅ Task 01 – 修改現有檔案（不需新分支）

1. Fork 本倉庫到你的 GitHub 帳號

2. Clone 到本地端

   ```bash
   git clone https://github.com/YOUR_USERNAME/makereal-lab-git-test.git
   cd git-test
   ```

3. 編輯 `README.md`，在「簽名區」最後一行加上你的名字

4. 提交並推送

   ```bash
   git add .
   git commit -m "完成 Task 01：加入簽名"
   git push origin main
   ```

5. 到 GitHub 開 Pull Request（從你的 fork 的 `main` 到原始倉庫的 `main`）

---

### 🚀 Task 02 – 建立分支與新增檔案

1. 建立並切換新分支（名稱自訂）

   ```bash
   git checkout -b task-02
   ```

2. 在專案根目錄新增 `hello.md`，寫點內容（例如 "Hello GitHub!"）

3. 提交並推送該分支

   ```bash
   git add .
   git commit -m "完成 Task 02：新增 hello.md"
   git push origin task-02
   ```

4. 到 GitHub 開 PR（從 `task-02` 分支對原始倉庫的 `main`）
</details>

## 簽名區


