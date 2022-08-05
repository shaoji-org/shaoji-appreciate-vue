<template>
  <div class="post-video">
    <el-row>
      <el-col :span="8" v-for="(o, index) in 2" :key="o" :offset="index > 0 ? 2 : 0">
        <el-card :body-style="{ padding: '0px'}">
          <img src="https://images.unsplash.com/photo-1656444273949-fefcbb060f7c?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxlZGl0b3JpYWwtZmVlZHwyMTB8fHxlbnwwfHx8fA%3D%3D&auto=format&fit=crop&w=800&q=60" class="image">
          <div style="padding: 14px;">
            <span class="shaoji_info">Something</span>
              <el-button v-if="true" icon="el-icon-star-off" class="button" circle></el-button>
              <el-button v-else type="info" icon="el-icon-star-on" class="button" circle></el-button>
          </div>
        </el-card>
      </el-col>
    </el-row>
  </div>
</template>

<script>
export default {
  name: "ShaoJi",
}
</script>

<style scoped>

.button {
  padding: 0;
  float: right;
  margin-top: -10px;
}
.image {
  display: block;
  width: 300px;
  height: 400px;
  object-fit: cover;
  margin: 0 auto ;
}
</style>