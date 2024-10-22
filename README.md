echo "# capstone-foundation-level2-10-07-24" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/Chanty1988/capstone-foundation-level2-10-07-24.git
curl -sS https://webi.sh/gh | sh
gh auth login
git push -u origin main

