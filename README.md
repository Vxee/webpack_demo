# webpack_demo
This is a simple demos of Webpack.  

### Use  
##### 01_entry_file
`$ npm i -g webpack webpack-dev-server`  
use `webpack-dev-server` can create a local server  

`$ npm run dev` launch the server,visit http://127.0.0.1:8080

##### 02_multiple_entry_files  
allow multiple entry files  
to fix repeat use webpack-command will create many bundle.js so we use a plugin to delete old files automatically.  

##### 04_css_loader  
allow include CSS in JS file.use css-loader to read css file,style-loader to insert `<style>` into html  

##### 05_image_loader  
allow include img in JS file.use image-loader and file-loader.  

##### 07_uglify_js_plugin  
allow to minified js  

##### 08_html_webpack_plugin and browser_webpack_plugin  
html_webpack_plugin can create `index.html` for you ,open-browser-webpack-plugin can open a new browser tab when webpack loads.
