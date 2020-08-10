BootStrap CSS Flexbox grid layout System
Course-1 Week-1
npm scripts part1
install parallelshell@3.0.1 3.0.2not working else use npm run scripts;

in json:
"start": "npm run dev",
"watch:scss": "onchange \"css/*.scss\" -- npm run scss ",
    "dev": "npm-run-all -p watch:scss lite"

npm scripts part2
npm install --save-dev rimraf@2.6.2
"clean": "rimraf dist",
npm -g install copyfiles@2.0.0
"copyfonts": "copyfiles -f node_modules/font-awesome/fonts/* dist/fonts",
npm -g install imagemin-cli@3.0.0
sudo npm install -g imagemin-cli@3.0.0 --unsafe-perm=true --allow-root
"imagemin": "imagemin img/* --out-dir='dist/img'",
