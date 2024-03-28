# BeeU-UI

## Necessary Items to Run
### Node.js Installation
To see if Node is installed, run `node --version`. If nothing pops up, [download here](https://nodejs.org/en).

### Node-sass Installation
After it is downloaded, run `npm install node-sass`.
Then `npm i sass --save`.
Create two folders, "sass" and "css"
Create file: style.scss in sass folder.
Enter following script into pacakge.json
```
 "scripts": { 
    "sass": "sass --watch sass/style.scss:css/style.css"
  },
```
Run sass to configure scss with css styles: `npm run sass`.
style.css should now be in the css folder.

### Notes:
Do not upload node_modules nor package-lock.json right now, as they are too large.
CTRL + C then Y to terminate.
