<h1>A.安裝 vue-cli</h1>
<h2>1.npm install -g @vue/cli      //安裝 vue-cli<h2>
<h2>2.vue --version                //確認版本<h2>
//-----------------------------------------------------
<h3>*src:工作區</h3>
<h3>*dist:編譯壓縮上線版</h3>
<h3>*package.json:plugin 配置版</h3>
<h1>B.建立 webpack 板型</h1>
<h2>1.vue init webpack myweb       //myweb--專案名稱</h2>
<h2>2.cd myweb 3.進入專案下 package.json 中，確認 vue 最終版如下：</h2>
  <h2>"dependencies": {</h2>
  <h2>"vue": "2.6.8",               //確認 vue 最終版(^去掉)</h2>
  <h2>"vue-router": "3.0.2"         //確認 vue-router 最終版(^去掉)</h2>
  <h2>},</h2>
<h2>3.npm run dev  or npm start     //編譯後，給網址</h2>           
<h2>4.npm run build                 //編譯壓縮後，dist檔下</h2>
//-----------------------------------------------------
<h1>C.導入Bootstrap</h1>
<h2>1.cd 專案名稱</h2>
<h2>2.npm install bootstrap --save --save-exact  //--save-exact：最終版</h2>
<h2>3.main.js                         //編譯src檔下main.js</h2> 
<h2>4.import 'bootstrap/dist/css/bootstrap.min.css'  //導入
<h2>5.App.vue                         //編譯src檔下App.vue
<h2>6.<button class="btn btn-primary">OK<button> //導入至template內</h2>
<h2>7.npm start   //編譯後，給網址</h2>
//-----------------------------------------------------





