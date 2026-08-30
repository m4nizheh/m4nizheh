# grab it, then immediately detach it from my history
git clone https://github.com/gargibhardwaj24/gargibhardwaj24.git my-profile
cd my-profile
rm -rf .git
git init && git branch -M main
# my face and my charts are not your face and your charts
rm -f assets/*.svg assets/jacket.png
pip install pillow
