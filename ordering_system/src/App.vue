<template>
  <div id="app">
    <router-view/>
  </div>
</template>

<script>
export default {
  name: 'App'
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  height: calc(100vh - 16px);
}

/* 消除边距 */
* {
  margin: 0;
  padding: 0;
}

body,hr, dl, dt, dd, ul, ol, li, h1, h2, h3, h4, h5, h6, pre, form, fieldset, input, textarea, blockquote, p {
  padding: 0;
  margin: 0;
}

/*列表样式消除*/
ol, ul, li {
  list-style: none;
}

/* a标签样式重置 */
a {
  text-decoration: none;
}

/*盒模型默认使用内边框*/
* {
  -webkit-box-sizing: border-box;
  -moz-box-sizing: border-box;
  box-sizing: border-box;
}

img {
  max-width: 100%;
}

::-webkit-scrollbar {
  width: 5px;
  height: 8px;
  background-color: rgba(210, 210, 210, 0.48);
  -webkit-border-radius: 4px;
  -moz-border-radius: 4px;
  border-radius: 0;
}

::-webkit-scrollbar-thumb {
  background-color: #838383;
  -webkit-border-radius: 4px;
  -moz-border-radius: 4px;
  border-radius: 2px;
}

html,body{overflow-x:hidden;overflow-y:hidden;}

/*清除浮动*/

.clearfix:before,
.clearfix:after {
  content: "";
  display: table;
}

.clearfix:after {
  clear: both;
}

/* Hides from IE-mac */
* html .clearfix {
  height: 1%;
}

.clearfix {
  display: block;
}

/* End hide from IE-mac */
* + html .clearfix {
  min-height: 1%;
}

/* IE7 */

/* 添加浮动 */
.left {
  float: left;
}

.right {
  float: right;
}


/*合并表格边框*/

table, td, tr, th {
  border-collapse: collapse;
}


/*img在盒子中有下边距*/

img {
  /*IE7*/
  border: none;
  vertical-align: middle;
}

/*全局设置*/

body {
  font-family: Helvetica, Tahoma, Arial, STXihei, '华文细黑', Microsoft YaHei, '微软雅黑', SimSun, '宋体', Heiti, '黑体', sans-serif;
  font-size: 16px;
  color: #333333;
}

/* 响应式字体设置：默认1rem=100px */
html {
  font-size: 625%;
}


/* 多行文本超出隐藏并显示省略 */
.overFlow-1 {
  overflow: hidden;
  text-overflow: ellipsis;
  display: -webkit-box;
  -webkit-line-clamp: 1;
  -webkit-box-orient: vertical;
}

.overFlow-5 {
  overflow: hidden;
  text-overflow: ellipsis;
  display: -webkit-box;
  -webkit-line-clamp: 5;
  -webkit-box-orient: vertical;
}

.overFlow-2 {
  overflow: hidden;
  text-overflow: ellipsis;
  display: -webkit-box;
  -webkit-line-clamp: 2;
  -webkit-box-orient: vertical;
}

.overFlow-3 {
  overflow: hidden;
  text-overflow: ellipsis;
  display: -webkit-box;
  -webkit-line-clamp: 3;
  -webkit-box-orient: vertical;
}

.overFlow-4 {
  overflow: hidden;
  text-overflow: ellipsis;
  display: -webkit-box;
  -webkit-line-clamp: 4;
  -webkit-box-orient: vertical;
}

.overFlow-6 {
  overflow: hidden;
  text-overflow: ellipsis;
  display: -webkit-box;
  -webkit-line-clamp: 6;
  -webkit-box-orient: vertical;
}


.fs24 {
  font-size: 24px;
}

.fs22 {
  font-size: 22px;
}

.fs20 {
  font-size: 20px;
}

.fs18 {
  font-size: 18px;
}

.fs16 {
  font-size: 16px;
}

.fs14 {
  font-size: 14px;
}

.fs12 {
  font-size: 12px;
}

.fs10 {
  font-size: 10px;
}

.text-indet0 {
  text-indent: 0 !important;
}
</style>
