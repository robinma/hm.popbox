hm.popbox
=========

public popbox

hm.popbox 实例

hm.alert({title:'标题',text:'弹出框信息。'})

params

noTitle : true, //是否显示标题

text : '请输入提示信息', //内容文

height : 'auto', //高度字

width : 210,//宽度

confirm:'确定',

enhance:false,

icontype:'ok' //ok||notice
				
demo

hm.confirm({title:'标题',text:'弹出框信息。'},fn1,fn2)
demo2.click(function(){
	hm.confirm({title:'标题',text:'弹出框信息。'},function(){
		hm.alert({text:'这个是确定按钮'});
	},function(){
		hm.alert({text:'这个是取消按钮'});
	});
});
				
demo
hm.toast({text:''})

hm.popbox({text:'',html:'',callBack:fn})

callBack : null, //返回函数

noTitle : false, //是否显示标题栏

timeout : 0, //设置等待关闭时间，为0为不关闭

arrow:false,

direction:'top',//top|right|bottom|left

skewing:'20',

link : null, //链接地址

requestType : null, //iframe,ajax,img

title : '标题', //标题

drag : true, //是否拖动，当此值为true时，如果noTitle为false，也不可以拖动

width : 400, //内容区的宽度

height : 'auto', //内容的高度

html : '',//popBox的内容

style:"",//目前针对iframe设置

scrolling:"auto",//目前针对iframe使用

noMask:false,

noClose:false,

positionStyle:'auto',//auto|define

top:null,left:null,right:null,bottom:null,

closeFn:null

		
