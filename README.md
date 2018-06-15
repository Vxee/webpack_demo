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