# テクノロジー（藤原） 10/4課題

- テキストエディタ（Visual Studio Codeなど）でREADME.mdを開きます
- 下の欄（` ``` `で挟まれている部分）に、ChromeデベロッパーツールのConsoleで実行したログを丸ごとコピー＆ペーストしてください

```
var str = "Hello";
undefined
var num = 123;
undefined
var flog = true;
undefined
const number = 1
undefined
const number = 1;
VM1877:1 Uncaught SyntaxError: Identifier 'number' has already been declared
    at <anonymous>:1:1
(anonymous) @ VM1877:1
console(num)
VM1904:1 Uncaught TypeError: console is not a function
    at <anonymous>:1:1
(anonymous) @ VM1904:1
console(num);
VM1908:1 Uncaught TypeError: console is not a function
    at <anonymous>:1:1
(anonymous) @ VM1908:1
console(str);
VM1930:1 Uncaught TypeError: console is not a function
    at <anonymous>:1:1
(anonymous) @ VM1930:1
console.log(str);
VM1943:1 Hello
undefined
window.outerWidth
1440
var prefList = ["北海道","青森","岩手　","宮城","秋田"];
undefined
console.log(prefList[0])
VM2095:1 北海道
undefined
console.log(prefList[3]);
VM2142:1 宮城
undefined
var prefHash = {"kanto":"関東地方","chubu":"中部地方","kinki":"近畿地方","chugoku","中国地方","shikoku","四国地方"};
VM2308:1 Uncaught SyntaxError: Unexpected token ,
var prefHash = {"kanto":"関東地方","chubu":"中部地方","kinki":"近畿地方","chugoku":"中国地方","shikoku":"四国地方"};
undefined
console.log(prefHash["kanto"]);
VM2370:1 関東地方
undefined
console.log(prefHash.kanto);
VM2427:1 関東地方
undefined
console.log(prefHash["kinki"]);
VM2486:1 近畿地方
undefined
console.log(prefHash.kinki);
VM2539:1 近畿地方
undefined
var prefHash1 = {"kanto":"関東地方","chubu":"中部地方"};
undefined
var prefHash2 = {kanto:"関東地方",chubu:"中部地方"};
undefined
var prefHash3 = {};
undefined
prefHash3["kanto"] = "関東地方";
"関東地方"
prefHash3["chubu"] = "中部地方";
"中部地方"
var prefHash4 = {};
undefined
prefHash4.kanto = "関東地方";
"関東地方"
prefHash4.chubu = "中部地方";
"中部地方"
var str = "Javaを始めよう!";
undefined
console.log(str.length);
VM3034:1 10
undefined
var date = new Date():
VM3071:1 Uncaught SyntaxError: Unexpected token :
var date = new Date();
undefined
console.log(date.toLocaleDateString());
VM3140:1 2018/10/5
undefined
var str = navigator.platform + "\n" + navigator.userAgent + "\n"
undefined
var str = navigator.platform + "\n" + navigator.userAgent + "\n";
undefined
window.alert(str);
undefined
```

## 例（下記の書き方をまねてください）

```
console.log('hello')
VM31:1 hello
undefined
```
