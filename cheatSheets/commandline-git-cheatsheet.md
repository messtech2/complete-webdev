# 🖥️ Command Line Essentials Cheat Sheet

## Basic Navigation
| Command          | Description                          |
|------------------|--------------------------------------|
| `cd folder`      | Change directory                     |
| `cd ..`          | Move up one directory                |
| `ls`             | List files/folders (Linux/Mac)       |
| `dir`            | List files/folders (Windows)         |
| `pwd`            | Show current directory path          |
| `mkdir folder`   | Create new folder                    |
| `touch file.txt` | Create new file (Linux/Mac)          |
| `echo > file.txt`| Create new file (Windows)            |

## Git Integration
| Command                | Description                          |
|------------------------|--------------------------------------|
| `git init`             | Initialize Git repo                 |
| `git status`           | Check changes                       |
| `git add .`            | Stage all files                     |
| `git commit -m "msg"`  | Commit changes                      |
| `git push`             | Upload to GitHub                    |

---
# 📦 GitHub & Vercel Cheat Sheet

## 🔑 GitHub Basics
| Command | Description |
|---------|-------------|
| `git init` | Initialize a new Git repo |
| `git status` | Check changed files |
| `git add .` | Stage all files |
| `git commit -m "message"` | Commit changes |
| `git branch` | List branches |
| `git checkout -b new-branch` | Create & switch to new branch |

## 🔄 Remote Repositories
| Command | Description |
|---------|-------------|
| `git remote add origin [URL]` | Connect local repo to GitHub |
| `git push -u origin main` | First push to GitHub |
| `git clone [URL]` | Download a GitHub repo |
| `git pull` | Fetch + merge remote changes |

## 🚀 Vercel Deployment
### Method 1: Drag & Drop
1. Go to [vercel.com](https://vercel.com)
2. Drag your project folder into Vercel
3. Automatic deployment!

### Method 2: GitHub Integration
1. Connect GitHub account to Vercel
2. Select repository
3. Auto-deploys on every `git push`

## 🛠️ Troubleshooting
| Issue | Solution |
|-------|----------|
| "Repository not found" | Check remote URL with `git remote -v` |
| Deployment failed | Check Vercel logs for errors |
| Can't push to GitHub | `git pull` first to merge changes |

## 💡 Pro Tips
- Use `.gitignore` for files/folders to exclude
- Vercel automatically detects frameworks (React, Next.js etc.)
- Custom domains available in Vercel dashboard

