# GitHub Upload Steps

Suggested repository name:

```text
sevenbound-chimera-islands
```

Suggested owner/account:

```text
xatusbetazx17
```

## Option 1: Upload from the GitHub website

1. Go to GitHub.
2. Click **New repository**.
3. Name it `sevenbound-chimera-islands`.
4. Choose **Public** or **Private**.
5. Do **not** check “Add a README file” because this package already includes one.
6. Create the repository.
7. Unzip this package.
8. Open the `sevenbound-chimera-islands` folder.
9. Drag all files and folders into the GitHub upload page.
10. Commit the upload.

## Option 2: Upload with Git command line

From inside the unzipped `sevenbound-chimera-islands` folder:

```bash
git init
git branch -M main
git add .
git commit -m "Initial Sevenbound Chimera Islands prototype"
git remote add origin https://github.com/xatusbetazx17/sevenbound-chimera-islands.git
git push -u origin main
```

## Option 3: Upload with GitHub CLI

If you have `gh` installed and logged in:

```bash
gh repo create xatusbetazx17/sevenbound-chimera-islands --public --source=. --remote=origin --push
```

Use `--private` instead of `--public` if you want the project private.

## Enable GitHub Pages

This repo already includes a GitHub Pages workflow in `.github/workflows/pages.yml`.

After pushing:

1. Open the repository on GitHub.
2. Go to **Settings → Pages**.
3. Set Source to **GitHub Actions**.
4. Push to `main` or manually run the workflow.
