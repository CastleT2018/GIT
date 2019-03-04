<h1>安裝 vue-cli</h1>
1.npm install -g @vue/cli      //安裝 vue-cli
2.vue --version                //確認版本
//-----------------------------------------------------
*src:工作區
*dist:編譯壓縮上線版
*package.json:plugin 配置版
建立 webpack 板型
1.vue init webpack myweb       //myweb--專案名稱
2.cd myweb 3.進入專案下 package.json 中，確認 vue 最終版如下：
  "dependencies": {
  "vue": "2.6.8",               //確認 vue 最終版(^去掉)
  "vue-router": "3.0.2"         //確認 vue-router 最終版(^去掉)
  },
3.npm run dev  or npm start     //編譯後，給網址           
4.npm run build                 //編譯壓縮後，dist檔下
//-----------------------------------------------------





npm install bootstrap --save --save-exact
