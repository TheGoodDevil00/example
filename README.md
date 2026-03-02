Hello World This is Good.
today is Monday.


### 2) Clone your fork
```bash
git clone https://github.com/<your-username>/attendance.git
cd attendance
```

### 3) Switch to your department branch
Replace `<branch-name>` with your department branch (for example: `CS`, `IT`, `AI`).

```bash
git checkout <branch-name>
```

### 4) Pull the latest changes
```bash
git pull origin <branch-name>
```

### 5) Add your attendance entry
Edit `attendance.md` and add your:
- Name, Branch,Roll No, Div
- Short description of your understanding from lecture

### 6) Commit your changes
```bash
git add attendance.md
git commit -m "Add attendance: <your-name>"
```

### 7) Push to your fork
```bash
git push origin <branch-name>
```

### 8) Create a Pull Request
Create a PR from your fork’s `<branch-name>` branch to this repository’s `<branch-name>` branch.

### 9) Verification
After approval, check the website the next morning. If your name appears, your attendance is marked.