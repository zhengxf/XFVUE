<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js App"/>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'app',
  components: {
    HelloWorld
  }
}
</script>

<style>
	
	
	/* 
	计算属性
	
	vue—data中变量和字符串拼接
	https://www.cnblogs.com/baby-zuji/p/9825208.html
	当您的拖欠运费总额大于欠费信用额度${this.scoreStr}元，或拖欠时间超过${this.days}天时，将会对店铺造成影响。`
	
	
	Safari、火狐时间格式 不支持 -，需要写成/
	let startTime = nowDate.getFullYear() + '/' + nowDate.getMonth() + '/' + nowDate.getDate() + ' 00:00:00'
	
	
	js的日期操作：String转date日期格式、求日期差
	https://www.cnblogs.com/spll/p/9686689.html
	
	JavaScript中getMonth()输出月份比实际少1的原因
	http://www.dodoloo.com/js/10.html
	
	
	JavaScript toISOString() 方法
	https://www.runoob.com/jsref/jsref-toisostring.html
	
	
	命令行运行JS node xxx.js
	
	字符串在html中的页面中的换行 white-space: pre
	http://www.imooc.com/article/288241?block_id=tuijian_wz
	
	
	作者：流浪杭州
	链接：http://www.imooc.com/article/288241?block_id=tuijian_wz
	来源：慕课网
	
	
	<button>标签
	
	阻止时间传递，创建2个平级的view，遮罩，在同一个父view上
	
	v-if 的使用
	
	vue中ckeckbox(复选框)的使用，及对click事件和change的理解
	https://blog.csdn.net/MMryyy/article/details/95216247
	
	
	Cannot read property 'slice' of undefined
	https://blog.csdn.net/qq6759/article/details/90711604
	1.错误可能由于数组或对象未定义或为null 引起的，所以查看获取数据的接口是否请求到了数据。
	2.查看返回的数据格式是否和之前的数据格式一致。
	
	
	vue中过滤器filters的使用
	https://www.cnblogs.com/shenmissing/p/9039718.html
	
	js判断字符是否为空的方法
	https://www.cnblogs.com/shuilangyizu/p/7744111.html
	
	
	
	Unexpected token o in JSON at position 1
	https://blog.csdn.net/qq_41999617/article/details/83511002
	JSON.parse() 方法用于将一个 JSON 字符串转换为对象,如
	JSON.stringify() 方法是将一个JavaScript值(对象或者数组)转换为一个 JSON字符串，如
	
	console.log('-------' + printData)
	var s = JSON.stringify(printData);
	console.log('+++++++++' + s)
					
	var h = JSON.parse(s)
	console.log('*******' + h)

	
	
	promise未定义问题
	https://www.cnblogs.com/yuanxinru321/p/10551876.html
	
	
	iframe 去掉margin
	
	px、pt 转换：https://www.runoob.com/w3cnote/px-pt-em-convert-table.html
	
	JSON.stringify() json对象转字符串 保护\
	JSON.parse(string)
	https://www.cnblogs.com/echolun/p/9631836.html
	
	
	css font 加粗
	http://www.divcss5.com/rumen/r122.shtml
	font-family: SimSun; 宋体
	
	
	img 标签居中
	h5 img 不拉伸
	js 图片裁剪到指定尺寸
	js取整
	JS获取图片的原始宽度和高度
	js中image获取不到width和heigth的问题
	https://blog.csdn.net/u014581901/article/details/79661623
	
	div与span区别及用法:http://www.divcss5.com/rumen/r79.shtml
	div:div占用的位置是一行
	span:span占用的是内容有多宽就占用多宽的空间距离
	
	
	img标签在div中水平垂直居中--两种实现方式
	https://www.cnblogs.com/alinjj/p/6884132.html
	
	html table td中放图片注意事项
	https://dong-shuai22-126-com.iteye.com/blog/1707335
	
	vue js 获取某个元素的绝对位置 
	
	CSS绘制三角形和箭头，不用再用图片了
	http://www.divcss5.com/rumen/r50847.shtml
	https://segmentfault.com/a/1190000005715074
	
	margin和padding失效
	
	块状元素和行内元素的margin,padding的区别
	https://blog.csdn.net/Buddha_ITXiong/article/details/79528127
	
	pc mouse over 提示
	 鼠标mouseover
	 mouseenter 闪烁 
	 
	 UE鼠标移上去提示功能类似hover
	 https://www.cnblogs.com/banyuege/p/9344753.html
	
	文本换行：https://www.cnblogs.com/leegent/p/9274424.html
	
	文字垂直居中：http://www.divcss5.com/rumen/r363.shtml
	line-height: 
	
	旋转：https://www.cnblogs.com/langwo/p/7076616.html
	transform:rotate(30deg);
	
	MBPC
	//M
	right: 50%;
	
	//B
	设置边框
	border-width: 2px;
	border-style: solid;
	border-color: gray;
	
	// P
	
	
	// C
	max-width: 100%;
	
	标签置于顶层
	z-index：-1
	
	position: absolute;
	position: relative;
	
	// 不展示
	display：none;
	// span a 等行内元素
	display:flex
	display: block;
	display: inline-block;
	
	// 块元素
	
	
	vertical-align: middle;
	
	// 设置透明度
	
	
	// CSS 等分
	实现CSS等分布局的5种方式：https://www.cnblogs.com/xiaohuochai/p/5456695.html
	
	
	*/
#app {
	
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>









