# My Cydia Repository

This is a custom Cydia/Sileo repository containing iOS packages.

## Repository Contents

- **Blank White App** - A simple blank white iOS app for iPhone 6 running iOS 12.5.7

## Repository Structure

```
repo/
├── debs/
│   └── com.example.blankwhiteapp_1.0.0_iphoneos-arm.deb
├── Packages
├── Packages.gz
├── Release
└── README.md
```

## Setting Up as a Git Repository

1. Initialize Git repository:
   ```bash
   git init
   ```

2. Add all files:
   ```bash
   git add .
   ```

3. Create initial commit:
   ```bash
   git commit -m "Initial repository setup"
   ```

4. Create a GitHub repository and push:
   ```bash
   git remote add origin https://github.com/yourusername/your-repo-name.git
   git branch -M main
   git push -u origin main
   ```

## Adding to Sileo/Cydia

Once your repository is hosted on GitHub Pages or another web server, add it to Sileo:

1. Open Sileo
2. Go to Sources tab
3. Tap the "+" button
4. Add your repository URL: `https://yourusername.github.io/your-repo-name/`
5. Tap "Add Source"
6. Refresh sources

## Repository URL Format

For GitHub Pages, your repository URL should be:
`https://yourusername.github.io/your-repo-name/`

Make sure to enable GitHub Pages in your repository settings and point it to the main branch.

## Package Information

- **Package ID:** com.example.blankwhiteapp
- **Version:** 1.0.0
- **Architecture:** iphoneos-arm
- **Description:** A simple blank white iOS app for iPhone 6 running iOS 12.5.7
- **Compatibility:** iOS 12.0+
