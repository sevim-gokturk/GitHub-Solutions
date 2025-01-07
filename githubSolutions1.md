### Authentication:
```bash
git config --global user.name "Your Name"
git config --global user.email "your-email@example.com"
```

### First Push:
- Go to GitHub and create New Repository then:
```bash
git init
git add .
git commit -m "Initial commit"
git remote add origin <repository-URL>
git branch -M main
git push -u origin main
```

### Push Error:
```bash
git push -u origin main --force
```

### Remove `.git` Folder:
```bash
Remove-Item -Recurse -Force .git
```

### Fix `.gitignore` Issues:
- Issue : When I saw a file on my GitHub but that is already in gitignore. An example for configuration.properties file.
```bash
git rm --cached configuration.properties
git commit -m "Stop tracking configuration.properties"
git push
```

---

