# 課題: HTML、CSS、JavaScriptの基本 / クリエイティブアカデミー

## 1. `day`という変数を作り、文字列"Monday"を代入してください

### A.
var day = "Monday";

## 2. `alert`または`console.log`で`day`の値を表示してください

### B.
console.log(day);


## 3. `getDay`という関数を作り、文字列"Friday"をリターンしてください
## 4. 以下のコードを改変し`console.log(day);`が`undefined`にならないようにしてください

	var setDay = function() { 
		var day = "Friday"; 
	}; 

	setDay(); 
	console.log(day); // undefined

### A.
var setDay = function(){
  var day = "Friday";
  return day;
};
var day = setDay();
alert(day);

#もしくは？

var day;
var setDay = function(){
	day = "Friday";
};
setDay();
alert(day);


## 5. `people`に"Bob"、"Sally"、"John"というアイテムを左記の順番どおりに配列として定義してください。

### A.
var people = ["Bob", "Sally", "John"];


## 6. 5の配列に対して`people[2]`としたら以下のうち、どの値になりますか？

1. Bob
2. Sally
3. John

### A.
###John

## 7. 以下のコードを改変し`anchor`の`style`を"red"にしてください

	var anchor = document.getElementById("myAnchor");

### A.
var anchor = document.getElementById("myAnchor");
anchor.style.cssText = 'background-color: red;';


## 8. 配列をループするのに利用できるのは以下のうちどれ

1. for
2. those
3. loop
4. eachOne

### A. 
### each


## 9. DOMツリーから特定のIDが付与された要素を検索するのに利用するのは次の空白を埋めてください。

	document.___________

### A.
document.getElementById("idname");

## 10. `box`と`id`が付与された要素をクリックした後、背景色をオレンジからグリーンに変更してください。

### A.
var box = document.getElementById("box");
box.addEventListener('click',function(){
	box.style.cssText = "background-color: green;";
});

