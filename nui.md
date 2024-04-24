https://youtu.be/fmV3Pt-o4yg

https://www.hostinger.fr/tutoriels/commandes-git

npx astro add astro-icon

echo "# blog.tonybengue.fr" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/tonybengue/blog.tonybengue.fr.git
git push -u origin main


git checkout --orphan latest_branch
git add .
git commit -m "commit message"
git branch -D main # delete main branch
git branch -m main # rename current branch to main
git commit -m "commit message"

DNS
A 185.199.108.153
A 185.199.109.153
A 185.199.110.153
A 185.199.111.153
dig tonybengue.fr +noall +answer -t A

Verification google
TXT google-site-verification=CQbLRDN029oam6Jb-Nzgd0PrPTbRe33DGwORo5u56Fk