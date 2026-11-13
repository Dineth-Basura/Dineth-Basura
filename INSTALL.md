# FIXED GitHub profile README — upload all 4 files

The previous images were broken because README.md referenced files that had not been uploaded alongside it. GitHub cannot display files that do not exist in the repository.

## Easiest method (GitHub website)

1. Extract the ZIP on your computer. **Do not upload the ZIP file.**
2. Open your GitHub profile repository: https://github.com/Dineth-Basura/Dineth-Basura
3. Click **Add file → Upload files**.
4. Select these four extracted files *at the same time*:
   - `README.md`
   - `hero.gif`
   - `typing.gif`
   - `workflow.gif`
5. Commit the changes directly to the default branch.
6. Reload your GitHub profile. The banner, typing line, and security workflow should all animate.

**Important:** The GIFs go in the **same folder as `README.md`** (repository root), not into an `assets` folder.

Expected file list:

    Dineth-Basura (repository root)
    ├── README.md
    ├── hero.gif
    ├── typing.gif
    └── workflow.gif

## Confirm each uploaded file works

The following links should display animated GIFs after you upload (replace `main` with your repository's default branch if different):

- https://github.com/Dineth-Basura/Dineth-Basura/blob/main/hero.gif
- https://github.com/Dineth-Basura/Dineth-Basura/blob/main/typing.gif
- https://github.com/Dineth-Basura/Dineth-Basura/blob/main/workflow.gif

## Why this version is more reliable

The three core animations are real GIF files stored in your own repository, rather than dynamically served by third parties. The external shields.io tool badges may depend on that service, but the animated header, text, and workflow do not.
