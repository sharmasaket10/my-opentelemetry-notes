# My OpenTelemetry Notes

**Your personal repo.** You are the owner. There is no remote—nothing is shared with anyone.

- **OpenTelemetry-Learning-Handbook.md** — Step-by-step learning guide (Docker, demo, data model, scenarios).
- Add more files and folders as you like. Commit on `main` whenever you want.

## Commands you’ll use

```powershell
cd "c:\Users\hroch\Documents\BannerHealth\oPEN tELEMETRY\my-opentelemetry-notes"

# See status
git status

# Add and commit (you own this repo)
git add .
git commit -m "Your message"
```

---

## Publish to GitHub (free)

1. **Create a GitHub account** (if you don’t have one): https://github.com/join — free.

2. **Create a new repo on GitHub:**
   - Go to https://github.com/new
   - **Repository name:** e.g. `my-opentelemetry-notes` (or any name you like)
   - **Public** = anyone can see it; **Private** = only you (both are free)
   - Leave “Add a README” **unchecked** (you already have one locally)
   - Click **Create repository**

3. **Connect your local repo and push** (replace `YOUR_USERNAME` and `YOUR_REPO_NAME` with your GitHub username and the repo name you chose):

   ```powershell
   cd "c:\Users\hroch\Documents\BannerHealth\oPEN tELEMETRY\my-opentelemetry-notes"

   git remote add origin https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git
   git push -u origin main
   ```

4. When prompted for credentials, use your **GitHub username** and a **Personal Access Token** (not your GitHub password). To create a token: GitHub → Settings → Developer settings → Personal access tokens → Generate new token; give it “repo” scope.

After this, your repo is published. Use `git push` anytime to update it.
