<template>
  <div class="hello">
    <div style="height: 1000px;background-color: transparent;">
      <div class="message">
        <span style="font-size: 80px;font-family:cursive;color: black;font-weight: 1000;">Kig</span>
        <div style="text-align: center;margin-top: 30px;">
          <div style="display:inline-block ;border-radius: 50px;padding: 20px;width: fit-content;background-color: rgba(1, 1, 1, 0.5);border-radius: 40px;">
            <span style="font-size: 60px;font-family:'幼圆';font-weight: 1000;color: white;">专业小程序开发团队</span>
          </div>
        </div>
        <div style="text-align: center;margin-top: 40vh;">
          <div style="display: inline-block;">
            <el-button style="font-size: 30px;padding: 20px;height: max-content;border-radius: 30px;color: white;background-color: red;">联系我们</el-button>
          </div>
            
          </div>
      </div>
      
    </div>
    <div style="padding: 0;margin: 0;height: 700px;background-color: white;">
      <!-- <el-image :src="item.url" fit="contain"/> -->
       <span style="font-size: 80px;font-weight: 1000;">你来写这里</span>
    </div>
    
  </div>
  
</template>

<script lang="ts" setup>
// import { ref } from 'vue'
// import image from '../assets/image.png'
// import image2 from '../assets/image2.png'
// const items = ref([
//   {url:image2},
//   {url:image},
// ])
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.el-carousel__item h3 {
  color: #475669;
  opacity: 0.75;
  line-height: 200px;
  margin: 0;
  text-align: center;
}

.el-carousel__item:nth-child(2n) {
  background-color: #99a9bf;
}

.el-carousel__item:nth-child(2n + 1) {
  background-color: #d3dce6;
}
.hello{
  padding: 0;
  margin: 0;
  background-attachment: fixed;
  background-image: url('../assets/bg2.png');
  background-repeat: no-repeat;
  background-size: cover;
}
.message{
  text-align: left;
  padding: 20px;
}
</style>
