FastPay
=======
      FastPay高度封装并集成了Android 端的支付宝支付、微信支付和银联支付。使用此库，可以简单高效的实现支付功能，节省了开发者看官方文档的时间
      
      FastPay拥有良好的扩展性，可以由用户自己集成其他支付方式，支付类实现FastMethod接口，支付的信息类实现FastPayInfo接口，在具体传到FastPay中。具体步骤参照示例代码。
      
Usage(使用)
---------------------------
step1<br>在gradle中直接引用<br>#在你项目根目录的build.gradle中添加<br>
```
allprojects {
		repositories {
			...
			maven { url 'https://jitpack.io' }
		}
	}
