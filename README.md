# sass-project

## Install node-sass
To install node-sass run the following command in your terminal: npm install node-sass

## To compile from Sass to Css
Add the below lines in package.json
"scripts": {
  "test": "echo \"Error: no test specified\" && exit 1",
  "scss": "node-sass --watch scss -o css"
}

When we run this script it will watch every .scss file in the scss/ folder, 
then save the compiled css in css/ folder every time we change a .scss file.

## To compile and watch the SASS files
To execute our one-line script, we need to run the following command in the terminal: npm run scss

