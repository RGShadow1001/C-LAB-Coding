# C-LAB-Coding 🚀
Welcome to our B.Tech CSE 1st Semester Team Repository! This space is created for collaborating on our C Programming laboratory assignments and group code modules.

## 📂 Repository Workspace Structure
To prevent merge conflicts and maintain clean tracking, we use a **Folder-per-Member** setup on the main branch. Please ensure you strictly build, edit, and update your files inside your personal folder workspace:
* `/Shaurya` —  Designated workspace folder for Shaurya.
* `/SAAD` — Designated workspace folder for Saad.
* `/Tushar` — Designated workspace folder for Tushar.

*Note: Shared architectural resources or shared utility files can be kept in the root folder after text discussion.*

---

## 🛠️ Team Daily Git Workflow
Follow this simple routine in your Codespace terminal every time you work to keep the project synchronized:

### 1. Start of the Session (Sync System)
Before writing any code, pull changes uploaded by other team members to stay updated:
```bash
git pull origin main
```

### 2. Write and Compile
* Work **exclusively** inside your personal folder.
* Press `Ctrl + S` to save files before compilation runs.
* Do not manually push compiled executable formats (like `a.out` or `.exe`). They are automatically blocked by our `.gitignore` configuration rule.

### 3. End of the Session (Upload Files)
Stage your target modifications, commit with a readable description, and upload to the cloud:
```bash
git add .
git commit -m "Added lab exercise solutions"
git push origin main
```

---

## 📝 Lab Viva Reminders
* Always declare your main function entry block standard layout as `int main()` or `void main()` according to the lab manual template.
* Include explicit string newline definitions using `\n` inside your `printf()` blocks, or use the `puts("Your Text")` system call to ensure clear, single-row console alignments automatically.
