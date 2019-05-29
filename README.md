# webpack-static-web
使用node-sass自动编译css，使用browser-sync实现保存动态刷新。方便静态网站开发。
## 使用
```
$ git clone https://github.com/zane626/webpack-static-web.git
$ cd webpack-static-web.git
$ npm i
$ npm start || npm run serve
```
## sass说明
> 在`src/scss/`目录下创建的`scss`文件，会在`src/css/`目录下创建同名`css`文件，请在html中直接引用css文件