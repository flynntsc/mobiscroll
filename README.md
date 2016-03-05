# mobiscroll

Script:

```
<script src="http://code.jquery.com/jquery-1.9.1.min.js"></script>
<link href="css/mobiscroll.custom-2.6.2.min.css" rel="stylesheet" type="text/css" />
<script src="js/mobiscroll.custom-2.6.2.min.js" type="text/javascript"></script>
```

Html:

```
<input type="text" id="flyn">
```

Js:

```
$("#flyn").mobiscroll({
	preset: 'date',
	theme: 'android-ics light',
	lang: 'zh',
	mode: 'scroller',
});
```

Options:

```
{
	preset: 'date', // datetime,time,tree_list,image_text,select
	theme: 'ios', //皮肤【android-ics light】【android-ics】【ios】【jqm】...
	mode: "scroller",//操作方式【scroller】【clickpick】【mixed】
	lang: 'zh', // hu,de,es,fr,it,no,pt-BR,nl,tr,ja
	display: 'modal', //显示方【modal】【inline】【bubble】【top】【bottom】
	dateFormat: 'yyyy-mm-dd',
	setText: '确定',
	cancelText: '清空',
	dateOrder: 'yymmdd',
	dayText: '日', 
	monthText: '月',
	yearText: '年', 
	startYear: (new Date()).getFullYear(), 
	endYear: (new Date()).getFullYear() + 9, 
	showNow: true,
	nowText: "明天",
	showOnFocus: false,
	height: 45,
	width: 90,
	rows: 3
}
```
