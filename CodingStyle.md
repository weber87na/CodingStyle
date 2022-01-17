### CSharp 命名
主要[參考這篇](https://www.c-sharpcorner.com/UploadFile/8a67c0/C-Sharp-coding-standards-and-naming-conventions/)

`Camel Case` 或稱 `Lower Camel Case` 通常指小寫駝峰 , 字首小寫 , 第二個字大寫 , 通常長這樣 `addValues` `updateValues`

`Pascal Case` 或稱 `Upper Camel Case` 通常指大寫駝峰 , 每個字都大寫開頭 , 通常長這樣 `FirstName` `LastName`

`Underscore Prefix` 通常在 csharp 會看到 , 其他語言好像沒見過? 反正會在 `Camel Case` 的變數前加上底線 , 長這樣 `_age` `_name` , 用在私有變數

`private field` => `_lowerCamelCase` => 指 `私有變數` or `欄位` , 依照微軟官方其實私有變數不加底線 , 可是實際上一堆老外微軟工程師也用這樣命名 , 所以就用這樣吧

`public field` => `UpperCamelCase` => `欄位`

`Protected field` => `UpperCamelCase` => `欄位`

`Internal field` => `UpperCamelCase` => `欄位`

`Property` => `UpperCamelCase` => `屬性`

`Method or Function` => `UpperCamelCase` => 方法 or 函數 (這個在 java , js 裡面是小寫開頭容易搞錯)

`Class` => `UpperCamelCase` => `類別`

`Interface` => `IUpperCamelCase` => `介面`

`Local Variable` => `lowerCamelCase` => 這個通常指在 function 裡面的變數 , 在下面範例裡面的 `y`

`Parameter` => `lowerCamelCase` => `參數` 通常指在 function 裡面的參數列表
```
//x 為 Parameter
AddValue(int x)
{
	//這個就是 Local Variable
	int y = 0;
	return y + x;
}
```

`Enum` => `UpperCamelCase`
```
enum Number
{
  One ,
  Two ,
}
```

`Namespace` => `UpperCamelCase` 

範例 `LaDiSai.Domain` or `LaDiSai.Repositories`

正常會長這樣 `專案.資料夾.資料夾.資料夾` , 建議讓 visual studio 自己長 , 不要自己手改 , 造成最後自己都找不到檔案

### html css 命名
這個我多半都 `一律使用小寫` , 並且使用 `kebab-case` , 看到會用大寫的通常都是寫 `.net` 的工程師

`kebab-case` => 骨式命名法 也有人稱 `Train-Case` 火車命名法 , 通常長這樣 `btn-red` `btn-large` `btn-small`

### javascript 命名
主要[參考這篇](https://www.30secondsofcode.org/articles/s/javascript-naming-conventions) 即可
詳細可以看 [google](https://google.github.io/styleguide/jsguide.html)

### typescript
請參考[這份](https://github.com/basarat/typescript-book/blob/master/docs/styleguide/styleguide.md#filename)

### git commit 格式
請參考[angular](https://github.com/angular/angular/blob/master/CONTRIBUTING.md#-commit-message-format)風格
