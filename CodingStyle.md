### CSharp 命名
主要[參考這篇](https://www.c-sharpcorner.com/UploadFile/8a67c0/C-Sharp-coding-standards-and-naming-conventions/)
`Camel Case` 或稱 `Lower Camel Case` 通常指小寫駝峰 , 字首小寫 , 第二個字大寫 , 通常長這樣 `addValues` `updateValues`
`Pascal Case` 或稱 `Upper Camel Case` 通常指小寫駝峰 , 每個字都大寫開頭 , 通常長這樣 `FirstName` `LastName`
`Underscore Prefix` 通常在 csharp 會看到 , 其他語言好像沒見過? 反正會在 `Camel Case` 的變數前加上底線 , 長這樣 `_age` `_name`

`private field` => `_lowerCamelCase` => 指 `私有變數` or `欄位`
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

### html css 命名
這個我多半都 `一律使用小寫` , 並且使用 `kebab-case` , 看到會用大寫的通常都是寫 `.net` 的工程師
`kebab-case` => 骨式命名法 也有人稱 `Train-Case` 火車命名法 , 通常長這樣 `btn-red` `btn-large` `btn-small`

### javascript 命名
主要[參考這篇](https://www.30secondsofcode.org/articles/s/javascript-naming-conventions) 即可
詳細可以看 [google](https://google.github.io/styleguide/jsguide.html)