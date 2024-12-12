# css-fundamentals-lab
git config --global user.name "Wanwisa"
git config --global user.email "66160263@go.buu.ac.th"
git clone https://github.com/66160263/css-fundamentals-lab
git add Readme.md
git add .
git commit -m "init project "
git push
git checkout -b feature/main
git add .
git commit -m “create main page"
git checkout -b feature/css
git add .
git commit -m “add basic CSS selectors”
git add .
git commit -m "add box model styles"
git add .
git commit -m "add flexbox layouts"
git checkout main
git merge  feature/main
git merge  feature/css
git push origin main
