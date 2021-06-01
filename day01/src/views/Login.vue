<!--  -->
<template>
    
  <div data-v-1a2158ee="" class="login-container">
    <form data-v-1a2158ee="" class="el-form login-form">
      <h2 data-v-1a2158ee="" class="login-title">梦学谷会员管理系统</h2>
      <div data-v-1a2158ee="" class="el-form-item is-required">
        <label for="username" class="el-form-item__label" style="width: 80px"
          >帐号</label
        >
        <div class="el-form-item__content" style="margin-left: 80px">
          <div data-v-1a2158ee="" class="el-input">
            <!----><input
              type="text"
              autocomplete="off"
              class="el-input__inner"
            /><!----><!----><!----><!---->
          </div>
          <!---->
        </div>
      </div>
      <div data-v-1a2158ee="" class="el-form-item is-required">
        <label for="password" class="el-form-item__label" style="width: 80px"
          >密码</label
        >
        <div class="el-form-item__content" style="margin-left: 80px">
          <div data-v-1a2158ee="" class="el-input">
            <!----><input
              type="password"
              autocomplete="off"
              class="el-input__inner"
            /><!----><!----><!----><!---->
          </div>
          <!---->
        </div>
      </div>
      <div data-v-1a2158ee="" class="el-form-item">
        <!---->
        <div class="el-form-item__content" style="margin-left: 80px">
          <button
            data-v-1a2158ee=""
            type="button"
            class="el-button el-button--primary"
          >
            <!----><!----><span>登录</span></button
          ><!---->
        </div>
      </div>
    </form>
  </div>
</template>

<script>
export default {
  name: "",
  data() {
    return {};
  },
  mounted() {}, //安装
  methods: {}, //方法
  computed: {}, //计算
  watch: {}, //监听
  filters: {}, //过滤器
};
</script>
<style>
body {
  font-family: "\5FAE\8F6F\96C5\9ED1";
  margin: 0 auto;
}
.login-form[data-v-1a2158ee] {
  width: 350px;
  margin: 160px auto;
  background-color: hsla(0, 0%, 100%, 0.8);
  padding: 28px;
  border-radius: 20px;
}
.login-container[data-v-1a2158ee] {
  position: absolute;
  width: 100%;
  height: 100%;
  background: url(https://pics6.baidu.com/feed/b03533fa828ba61e7a094db99b2fc20d314e5960.jpeg?token=e9791a74e390d7dff8fe60bbbeec9314);
}
.login-title[data-v-1a2158ee] {
  color: #303133;
  text-align: center;
}
.logo[data-v-abbf0c46] {
  vertical-align: middle;
  padding: 0 10px 0 40px;
}
.company[data-v-abbf0c46] {
  position: absolute;
  color: #fff;
}
.el-dropdown[data-v-abbf0c46] {
  float: right;
  margin-right: 40px;
}
.el-dropdown-link[data-v-abbf0c46] {
  color: #fff;
  cursor: pointer;
}
.el-menu[data-v-4e6e2095] {
  border-right: none;
}
.el-breadcrumb[data-v-1874e3ef] {
  height: 10px;
  padding: 20px;
  border-radius: 4px;
  -webkit-box-shadow: 0 2px 12px 0 rgba(0, 0, 0, 0.1);
  box-shadow: 0 2px 12px 0 rgba(0, 0, 0, 0.1);
}
.line[data-v-1874e3ef] {
  border-left: 3px solid #31c17b;
  padding-left: 10px;
}
.header[data-v-7d092518] {
  position: absolute;
  line-height: 50px;
  top: 0;
  left: 0;
  right: 0;
  background-color: #2d3a4b;
}
.navbar[data-v-7d092518] {
  width: 230px;
  left: 0;
  background-color: #545c64;
}
.main[data-v-7d092518],
.navbar[data-v-7d092518] {
  position: absolute;
  top: 50px;
  bottom: 0;
  overflow-y: auto;
}
.main[data-v-7d092518] {
  left: 230px;
  right: 0;
  padding: 10px;
}
div[data-v-59f00986] {
  text-align: center;
}
</style>
