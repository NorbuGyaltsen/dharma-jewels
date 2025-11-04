# Setup Repo Inside Local Folder

(when setting up a new windows iteration, delete the current .git folder and do this once before running dharmajewels.exe)

`git config --global core.autocrlf input`
`git config --global core.safecrlf false`
`cd "C:\path\to\folder"`
`git init -b main` (or `git init` then `git branch -M main`)
`git remote add origin https://github.com/NorbuGyaltsen/dharma-jewels.git`
`git add .`
`git commit -m "Initial commit"`
`git push -u origin main --force`
