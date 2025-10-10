# arbazali.github.io

This is a GitHub Pages repository for hosting your personal website.

## How to Upload Your Code to This Repository

There are several ways to upload your code from your local device to this repository. Choose the method that works best for you:

### Method 1: Using Git Command Line (Recommended)

This is the most common and powerful method used by developers.

#### Prerequisites
- Install Git on your computer: [Download Git](https://git-scm.com/downloads)
- Have a GitHub account and access to this repository

#### Steps

1. **Clone the repository** (first time only):
   ```bash
   git clone https://github.com/arbazali72660/arbazali.github.io.git
   cd arbazali.github.io
   ```

2. **Make your changes**:
   - Edit existing files (index.html, style.css, script.js)
   - Add new files or folders as needed

3. **Check what files have changed**:
   ```bash
   git status
   ```

4. **Stage your changes**:
   ```bash
   # Stage all changes
   git add .
   
   # Or stage specific files
   git add index.html style.css
   ```

5. **Commit your changes**:
   ```bash
   git commit -m "Describe your changes here"
   ```

6. **Push to GitHub**:
   ```bash
   git push origin main
   ```

#### Updating Your Local Copy

If you've already cloned the repository and want to get the latest changes:

```bash
cd arbazali.github.io
git pull origin main
```

### Method 2: Using GitHub Web Interface

This method is easiest for small changes and doesn't require installing Git.

#### Steps

1. Go to [https://github.com/arbazali72660/arbazali.github.io](https://github.com/arbazali72660/arbazali.github.io)
2. Navigate to the file you want to edit
3. Click the pencil icon (✏️) to edit the file
4. Make your changes
5. Scroll down and add a commit message
6. Click "Commit changes"

#### To Upload New Files via Web Interface:

1. Go to the repository page
2. Click "Add file" → "Upload files"
3. Drag and drop your files or click "choose your files"
4. Add a commit message
5. Click "Commit changes"

### Method 3: Using GitHub Desktop

GitHub Desktop provides a graphical interface for Git operations.

#### Prerequisites
- Download and install [GitHub Desktop](https://desktop.github.com/)

#### Steps

1. **Clone the repository**:
   - Open GitHub Desktop
   - Click "File" → "Clone repository"
   - Select "arbazali72660/arbazali.github.io" or enter the URL
   - Choose where to save it on your computer
   - Click "Clone"

2. **Make your changes**:
   - Edit files using your favorite code editor
   - GitHub Desktop will automatically detect changes

3. **Commit your changes**:
   - In GitHub Desktop, you'll see all changed files
   - Write a summary of your changes in the "Summary" field
   - Optionally add a description
   - Click "Commit to main"

4. **Push to GitHub**:
   - Click "Push origin" in the top bar

## Common Git Commands

Here are some useful Git commands for managing your code:

```bash
# Check status of your files
git status

# View recent commits
git log

# Undo changes to a file (before staging)
git checkout -- filename

# Undo staged changes
git reset HEAD filename

# View differences in your changes
git diff

# Create a new branch
git checkout -b new-branch-name

# Switch between branches
git checkout branch-name

# List all branches
git branch -a
```

## Repository Structure

```
arbazali.github.io/
├── index.html    # Main HTML file for your website
├── style.css     # CSS styles for your website
├── script.js     # JavaScript functionality
└── README.md     # This file
```

## Viewing Your Website

After pushing changes to GitHub, your website will be available at:
- **Main site**: https://arbazali72660.github.io

GitHub Pages typically updates within a few minutes after you push changes.

## Troubleshooting

### Authentication Issues

If you encounter authentication issues when pushing:

1. **Using HTTPS**: You may need to use a Personal Access Token instead of your password
   - Generate a token at: https://github.com/settings/tokens
   - Use the token as your password when prompted

2. **Using SSH**: Set up SSH keys for easier authentication
   - Follow the guide: https://docs.github.com/en/authentication/connecting-to-github-with-ssh

### Merge Conflicts

If you get a merge conflict:

1. Pull the latest changes first:
   ```bash
   git pull origin main
   ```

2. If conflicts occur, open the conflicting files and resolve them manually
3. Stage the resolved files:
   ```bash
   git add filename
   ```

4. Complete the merge:
   ```bash
   git commit -m "Resolved merge conflicts"
   ```

5. Push your changes:
   ```bash
   git push origin main
   ```

### Can't Push Changes

If `git push` fails:

1. Make sure you have the latest changes:
   ```bash
   git pull origin main
   ```

2. Try pushing again:
   ```bash
   git push origin main
   ```

## Additional Resources

- [Git Documentation](https://git-scm.com/doc)
- [GitHub Guides](https://guides.github.com/)
- [GitHub Pages Documentation](https://docs.github.com/en/pages)
- [Markdown Guide](https://www.markdownguide.org/) (for editing this README)

## Contributing

Feel free to update this README if you find ways to improve the instructions or add helpful information!

---

**Need help?** Open an issue in this repository or consult the [GitHub Community Forum](https://github.community/).
