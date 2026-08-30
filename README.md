
git clone https://github.com/gargibhardwaj24/gargibhardwaj24.git my-profile
cd my-profile
rm -rf 
git init && git branch -M main

rm -f assets/*.svg assets/jacket.png
pip install pillow
python scripts/dotify.py yourphoto.png -o assets/portrait --cols 100 --equalize --detail 0.5 --color
