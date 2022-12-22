# 0xkeivin.github.io
## Hugo setup
```bash
brew install hugo
# clone a theme 
git clone https://github.com/apvarun/digital-garden-hugo-theme.git themes/digitalgarden
# copy css file 
cp themes/digitalgarden/static/css/main.css static/main.css
# generate site without cache
hugo server --noHTTPCache
# create an about page
hugo new about.md
```