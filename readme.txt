How to update lab website on Mac:

Go to terminal 

First update the content using jekyll with the following code 
cd Dropbox 
cd UBC\ Quant\ Lab\ Website/
jekyll serve

then push the changes to git and github with the following code
cd _site
git init 
git add --all
git commit -m “comment"
git push origin master 