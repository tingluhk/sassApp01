*SASS simple app
- to run the sass "sass --watch app.scss:app.css"



- installation in npm

        npm init
        // --save -dev means "devDependencies" in package.json
        npm install node-sass --save-dev
        // --save means "dependencies" in package.json
        npm install jquery --save

- // if you need to uninstall a package use "npm uninstall jquery --save"

- compile SASS

        npm run compile:sass

        add watch to script
        "scripts": {
                "compile:sass": "node-sass sass/app.scss css/app.css -w"
                },


- Auto Reload the page after compile 

        along with the npm run compil:sass in one terminal, open another terminal and watch for any changes auto reload.
        
        npm package = sudo npm install -g live-server
        then type "live-server --port=4040" in terminal





