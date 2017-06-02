## Build Setup

``` bash
# install cordova
npm i cordova -g

# run your code (optional argument stands for live-reload)
cordova (run|emulate) [android|ios|browser] [-- --lr]

# build for production
cordova build --release
```

## Project Structure

src - Source files are here. Mostly your target is this directory.
src/assets/static - Your static assets like images, css, fonts, json, js, sass is here.
src/assets/static/css - put custom app CSS styles here. Don't forget to import them in main.js
src/assets/vue/pages - app .vue pages
src/assets/vue/components - folder with custom .vue components
src/main.js - main app file where you include/import all required libs and init app
src/routes.js - app routes
src/main.vue - main app structure/component

More details - https://framework7.io/vue/templates.html