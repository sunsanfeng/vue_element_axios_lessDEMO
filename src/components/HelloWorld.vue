<template>
  <div class="hello">
    <i class="el-icon-edit"></i>
		<i class="el-icon-share"></i>
		<i class="el-icon-delete"></i>
		<div class="ls">
			<p class="txt">近日，一则寻人启事在网络平台上热传。2月24日凌晨，刘卉（化名）在和室友李菲聊完天后，便离开了住所，至北青报记者发稿时仍未归来。家人和朋友都十分着急，便在网上发布寻人启事。2月27日，刘卉的母亲告诉北京青年报记者，刘卉的室友已经报警，刘卉父母也已经来到了北京，现在每天都在外面寻找女儿，打算找到女儿再回家。</p>
		</div>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  },
  methods:{
  	open2() {
	    this.$message({
	      message: '恭喜你，这是一条成功消息',
	      type: 'success'
	    });
	  },
  },
  created:function(){
  	this.open2();
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="less">
.ls{
	border: 1px solid red;
	.txt{
		text-indent: 2rem;
	}
}
</style>
