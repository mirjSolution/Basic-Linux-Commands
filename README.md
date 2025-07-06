# 🧰 Basic Linux Commands

This guide contains essential Linux terminal commands for navigating the file system, managing files and directories, viewing system info, and using superuser privileges. Perfect for DevOps, system administration, and daily terminal usage.

---

## 📁 Navigation

![Navigation](GIF/nav.gif)

### Show Current Directory

```bash
pwd
```

### List Contents

```bash
ls
```

### Change Directory

```bash
cd Documents
```

### Go Up One Level

```bash
cd ..
```

---

## 🛠 File & Folder Operations

![Navigation](GIF/FFOperations.gif)

### Create a Directory

```bash
mkdir test
```

### Create a File

```bash
touch test.txt
```

### Remove a File

```bash
rm test.txt
```

### Remove a Directory

```bash
rm -r test
```

---

## 🧭 Paths: Absolute vs Relative

![Navigation](GIF/Path.gif)

### Absolute Path

```bash
cd /etc/network
```

### Relative Path

```bash
cd Documents
```

---

## ⚡ Terminal Productivity Tips

![Productivity](GIF/productivity.gif)

- **Autocomplete:** Press `Tab`
- **Command History:** `history`
- **Reverse Search:** `Ctrl + R`
- **Cancel Command:** `Ctrl + C`
- **Paste in Terminal:** `Ctrl + Shift + V`

---

## 📄 Viewing File Contents

### View a Text File

```bash
cat filename.txt
```

### View Command History File

```bash
cat ~/.bash_history
```

---

## 📂 Hidden Files

### List All Files Including Hidden

```bash
ls -a
```

---

## 🔁 Rename or Move Files and Folders

### Rename Folder

```bash
mv old_folder new_folder
```

### Rename File

```bash
mv old_file.txt new_file.txt
```

---

## 📋 Copy Files and Folders

### Copy Folder Recursively

```bash
cp -r source_folder destination_folder
```

### Copy File

```bash
cp file1.txt file2.txt
```

---

## 💻 System Info Commands

### Kernel and System Info

```bash
uname -a
```

### OS Release Info

```bash
cat /etc/os-release
```

### CPU Info

```bash
cat /proc/cpuinfo
```

### Memory Info

```bash
cat /proc/meminfo
```

---

## 🔐 Superuser and Sudo

### Create User

```bash
sudo adduser test
```

### Switch User

```bash
su - test
```

### Delete User

```bash
sudo deluser test
```

### Create Group

```bash
sudo addgroup test
```

### Delete Group

```bash
sudo groupdel test
```

---

## ✅ Summary

These commands are foundational to working with Linux systems via the terminal. Whether managing files, navigating the system, or using sudo for admin tasks — these are the essential tools for everyday Linux usage.

---

🧑‍💻 _Created by Rico John Dato-on_
