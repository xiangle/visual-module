<template>
   <div class="main">
      <div class="filesMenu">
         <ul>
            <li>admin.js</li>
            <li>test.js</li>
            <li>user.js</li>
         </ul>
      </div>
      <!-- <div class="fileController">
                                    <ul>
                                       <li>test.js</li>
                                       <li>test控制器</li>
                                       <li>xx</li>
                                    </ul>
                                 </div> -->
      <div class="body">
         <ul class="topMenu">
            <li>test.js</li>
            <li>test控制器</li>
            <li>xx</li>
         </ul>
         <ul>
            <li>user 用户名称</li>
            <li>password 密码</li>
            <li>type 项目类型</li>
         </ul>
         <ul>
            <li>
               <ul>
                  <li>
                     <ul>
                        <li>a</li>
                        <li>b</li>
                        <li>c</li>
                     </ul>
                  </li>
                  <li>b</li>
                  <li>
                     <ul>
                        <li>a</li>
                        <li>b</li>
                        <li>c</li>
                     </ul>

                  </li>
               </ul>
            </li>
            <li>b</li>
            <li>
               <ul>
                  <li>a</li>
                  <li>b</li>
                  <li>c</li>
               </ul>
            </li>
         </ul>
      </div>
   </div>
</template>

<script>
export default {
   name: 'main',
   data() {
      return {
         msg: 'Welcome to Your Vue.js App'
      }
   }
}
</script>

<style scoped>
.main,
.filesMenu,
.fileController,
.body {
   height: 100%;
}

.filesMenu {
   width: 11%;
   float: left;
}

.filesMenu ul {
   height: 100%;
   background-color: #666;
   color: #eee;
   font-size: 13px;
}

.filesMenu ul li {
   padding: 6px 6px;
}


/* .fileController {
   width: 8%;
   float: left;
}

.fileController ul {
   padding-top: 5px;
   height: 100%;
   border-right: 1px solid rgba(0, 0, 0, .1);
}

.fileController ul li {
   float: left;
   padding: 12px 0;
   width: 100%;
   text-align: center;
} */

.body {
   width: 89%;
   float: left;
}

.body .topMenu {
   padding: 0;
   border-bottom: 1px solid rgba(0, 0, 0, 0.1);
   height: 50px;
}

.body .topMenu li {
   float: left;
   width: 100px;
   padding: 6px;
}

.body ul {
   padding: 10px;
}

.body ul li {
   padding: 15px;
   border: 1px solid rgba(0, 0, 0, .1);
   margin: 10px 0;
   border-radius: 3px;
}


/* .body>ul>li {
   padding: 18px 26px;
} */
</style>
