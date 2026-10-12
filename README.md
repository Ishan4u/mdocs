# Mdocs

A docs viewer and editor for Markdown files. Runs fully in your browser.

**Open it:** https://ishan4u.github.io/mdocs/

No install, no sign-up. You can also install it as an app (browser menu → _Install_).

---

## Open a local folder

1. Go to https://ishan4u.github.io/mdocs/
2. Click **Choose docs folder** (or drag the folder onto the page).
3. The sidebar is built from your folders and files.

## Connect a GitHub repo

### 1. Create a token

1. In Mdocs, click **Continue with GitHub** (or the branch icon in the top bar).
2. Click **Create token on GitHub**. A GitHub page opens.
3. Enter a name and an expiration date.
4. **Repository access** → pick only your docs repo.
5. **Permissions** → **Contents**:
   - _Read-only_ — to view
   - _Read and write_ — to save changes
   - Optional: **Pull requests: Read and write** — to open PRs
6. Click **Generate token** and copy it.

### 2. Connect

1. Paste the token into Mdocs.
2. Tick **Remember me** to keep it in this browser (optional).

> Public repos work without a token: type `owner/repo` in the search box. Read only.

### 3. Open the repo

1. Pick a repo from the list, or type `owner/repo`.
2. Pick a branch.
3. Click **Open**.

### 4. Edit and save

1. Click **Edit** on a section, or **New file** in the **Files** view.
2. Click **Save to GitHub** in the top bar.
3. Check the changes and the commit message.
4. Click **Commit**. All changes go in one commit.

Click **↻ Reload** to get the latest from GitHub.
Click **Disconnect** to remove the token.

---

Full guide is inside the app.

---

## Common errors

| Error                                 | Fix                                                                          |
| ------------------------------------- | ---------------------------------------------------------------------------- |
| Token cannot write to this repository | Make a token with **Contents: Read and write** for this repo                 |
| Not allowed to update the branch      | Branch is protected → **Commit to a new branch**, then **Open pull request** |
| Rate limit used up                    | Connect with a token, or wait                                                |

## Privacy

Your files and token stay in your browser. Mdocs talks only to GitHub.

## License

See [LICENSE](LICENSE).
