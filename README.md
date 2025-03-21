# coding-project-template

npm install gh-pages --save-dev

package.json
"predeploy": "npm run build",
"deploy": "gh-pages -d dist",


When making a change do:
npm run deploy
