# DESTinY website

Requirements
* hugo 
* node + npm

Using theme:    
https://themes.gohugo.io/themes/hugo-product-launch/


## Initial setup
```bash
hugo new site website
cd website
git init
git submodule add https://github.com/janraasch/hugo-product-launch.git themes/hugo-product-launch
echo "theme = 'hugo-product-launch'" >> hugo.toml
cp themes/hugo-product-launch/exampleSite/config.toml .
npm install ./themes/hugo-product-launch
hugo server --buildDrafts
```