# makereal-lab-git-test

## Task

Fork 此 repo 到你自己的 GitHub 帳號

Clone 你的 fork 到本地端

從本地建立一個 branch，命名格式為 `feature/<yourname>`

建立一個新資料夾：`names/`（如果已存在可共用）

在資料夾中建立一個 `<你的名字>.md`，內容隨意

回到 GitHub，開一個 Pull Request，目標分支為本 repo 的 `push_to_here`

## Reference

- [Git 官網](https://git-scm.com/)
- [doggy8088/Learn-Git-in-30-days](https://github.com/doggy8088/Learn-Git-in-30-days/tree/master/zh-tw) (介面有點舊 但應該沒差?)

<details>
  <summary>走投無路時服用</summary>
  
## 教學 By ChatGPT

這裡是一個完整範例，假設你的名字是 **Alice Wang**。

---

### ✅ 步驟一：Fork 專案

1. 前往這個 repo 頁面（你現在看到的這個）
2. 點右上角的 **"Fork"** 按鈕
3. 選擇你自己的帳號，GitHub 就會幫你建立一個副本

---

### ✅ 步驟二：Clone 到本地端

在你自己的 GitHub 帳號下，找到剛剛 fork 出來的 repo，點選 `Code` → `Copy HTTPS` 或 `SSH` 連結。

```bash
git clone <Git link>
cd makereal-lab-git-test
```

---

### ✅ 步驟三：建立新分支

```bash
git checkout -b feature/alice-wang
```

---

### ✅ 步驟四：新增檔案

建立 `names/` 資料夾（如果尚未存在）並新增檔案：

```bash
mkdir -p names
nano names/alice-wang.md
```

檔案內容範例：

```markdown
# Hello from Alice Wang

我正在學習 Git！  
今天我完成了一次 Fork + Branch + Pull Request 的流程。
```

儲存後結束編輯。

---

### ✅ 步驟五：加入 Git 並提交

```bash
git add names/alice-wang.md
git commit -m "add name for Alice Wang"
```

---

### ✅ 步驟六：推送到 GitHub

```bash
git push origin feature/alice-wang
```

---

### ✅ 步驟七：建立 Pull Request

1. 到你的 GitHub 上找到 fork 出來的 repo
2. 你會看到提示 `Compare & pull request`，點它
3. 確保：

   * **From**: your-username/feature/intro-alice-wang
   * **To**: original-repo/push_to_here
4. 留下簡單訊息後，送出 PR！

---

### 🎉 你完成了！

等待 repo 擁有者 review 和 merge，你就成功參與了一次 Git 協作流程！
</details>
