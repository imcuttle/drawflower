# DrawFlower

[Demo](http://moyuyc.github.io/2016/04/26/canvas绘制平面花瓣/)

How To Play?

1.`<script src='drawflower.js'></script>`
2.`canvas.drawFlower(option);`

```
//default option
{
	animate:false,
	rotate:90,  
	randomSize:true,
	randomColor:true,
	randomPetals: true,
	pos:{
		x:this.width/2,
		y:this.height/2
	}
}
```
or
```
{
	animate:true,
	rotate:-20,  
	randomSize:false,
	size:10,
	randomColor:false,
	color:[100,100,100],
	randomPetals: false,
	petals:6,
	pos:{
		x:0,
		y:0
	}
}
```