
### 1. **Initialize Gitflow**  
```bash
git flow init
```

### 2. **Start a Feature Branch**  
```bash
git flow feature start feature-name
```

### 3. **Work on the Feature**  
Make changes and commit them:  
```bash
git add .
git commit -m "Commit message"
```

### 4. **Finish the Feature**  
```bash
git flow feature finish feature-name
```

### 5. **Start a Release**  
```bash
git flow release start release-name
```

### 6. **Finalize the Release**  
```bash
git flow release finish release-name
```

### 7. **Start a Hotfix (for urgent fixes)**  
```bash
git flow hotfix start hotfix-name
```

### 8. **Finish the Hotfix**  
```bash
git flow hotfix finish hotfix-name
```

### 9. **Merge and Push Changes**  
After finishing features, releases, or hotfixes:  
```bash
git push origin --all
git push origin --tags
```

