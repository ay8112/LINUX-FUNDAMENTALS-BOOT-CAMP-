📄 README.md
# 🐧 Linux Fundamentals Project – Tech Diary

This project is part of the **Linux Fundamentals** hands-on bootcamp.  
It demonstrates basic Linux commands, file handling, and version control practices by creating a **structured Tech Diary**.  

---

## 📂 Project Structure



linux_project/
│── profile.txt # Contains personal details (Name & Roll No)
│── commands.txt # 5 favorite Linux commands with purpose
│── log.txt # 5 executed commands from history
│── tech_diary.txt # Final merged file with ASCII art & motivational quote


---

## 📝 Steps Followed

1. **Create Project Directory**
   ```bash
   mkdir linux_project
   cd linux_project


Create Files

touch profile.txt commands.txt log.txt


Add Content

profile.txt → Name & Roll Number

commands.txt → 5 favorite Linux commands + explanation

log.txt → 5 executed commands (from history)

Format Files Using nano

nano profile.txt
nano commands.txt
nano log.txt


Merge Files into Final Tech Diary

cat profile.txt commands.txt log.txt > tech_diary.txt


Decorate Tech Diary

Added ASCII art

Added motivational quote

Compress Project

zip linux_project.zip *.txt


Upload to GitHub

git init
git add .
git commit -m "Linux Fundamentals Project Submission"
git remote add origin <your-repo-link>
git push -u origin master

🚀 Commands Practiced

mkdir, cd, touch, echo, cat, nano/vim, history, zip, git

🎨 Final Output (Sample Preview)
====================== My Linux Tech Diary ======================

👤 Profile
-----------------------------------------------------------
Name     : Aman Singh Yadav
Roll No  : BBDNIT-2025-CS-117

🖥️ Favorite Linux Commands
-----------------------------------------------------------
1. ls        → Lists files and directories in the current location
2. pwd       → Prints the current working directory
3. cat       → Displays the contents of a file
4. nano      → Opens a file in the nano text editor
5. zip       → Compresses files into a .zip archive

📜 Logbook (Recent Commands from History)
-----------------------------------------------------------
$ ls
$ mkdir linux_project
$ cd linux_project
$ touch profile.txt
$ echo "Hello Linux World!" >> profile.txt

✨ Motivation

“Every command you learn makes you stronger.
Keep coding, keep growing 🌱.”

📌 Submission Details

Name: Aman Singh Yadav

Roll No: BBDNIT-2025-CS



