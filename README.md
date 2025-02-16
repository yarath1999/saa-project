# 🔬 Testing Branch (`testing`)
---
## 🚀 Hello Team!
Welcome to the `testing` branch! This is where all new updates, features, and bug fixes are first tested before moving forward.

### 🛠 Why This Branch Exists
- This branch serves as a **safe testing environment** for new changes.
- The team will push their individual updates here before they are reviewed.

### 🔥 Rules for This Branch
✅ All developers should push their changes to `testing` first.
✅ This branch **is not stable** and may contain bugs.
✅ Only after passing tests, changes will be merged into `master`.

### 🔄 How We Work with `testing`
1. Developers create new features or bug fixes and push to `testing`.
2. The team reviews, tests, and debugs the changes.
3. If successful, updates are merged into `master`.

### 🚀 Commands for Using `testing`
To push changes to `testing`, run:
```bash
git checkout testing
git pull origin testing
git add .
git commit -m "Added new feature/bug fix"
git push origin testing
```

To merge `testing` into `master`, run:
```bash
git checkout master
git merge testing
git push origin master
```
---
