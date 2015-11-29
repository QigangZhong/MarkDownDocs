#Header1
##Header2
### Header 3

#一. 引用块
> This is a blockquote.
> 
> This is the second paragraph in the blockquote.
>
> ## This is an H2 in a blockquote
>
>>嵌套引用

#二. 斜杠加粗
Some of these words *are emphasized*.
Some of these words _are emphasized also_.
Use two asterisks for **strong emphasis**.
Or, if you prefer, __use two underscores instead__.

#三. 列表
* Candy.
* Gum.
* Booze.
* 代码块
		`public class Sample(){}`

1. Red
2. Green
3. Blue

* A list item.
With multiple paragraphs.

* Another item in the list.

#四. 超链接
[example link](http://example.com/).
[example link](http://example.com/ "With a Title").

I get 10 times more traffic from [Google][1] than from
[Yahoo][2] or [MSN][3].

[1]: http://google.com/ "Google"
[2]: http://search.yahoo.com/ "Yahoo Search"
[3]: http://search.msn.com/ "MSN Search"

[The New York Times][NY Times].

[ny times]: http://www.nytimes.com/

#五. 图片
![alt text](/path/to/img.jpg "Title")

![alt text][id]

[id]: /path/to/img.jpg "Title"

#六. 代码

-----------------------------------------
<code>this is code</code>

<pre>
	<code>
		public class Sample()
		{
			public string Prop{get;set;}
		}
	</code>
</pre>

-----------------------------------------

`this is code`

`public class Sample()
{
	public string Prop{get;set;}
}`

```
public class Sample()
{
	public string Prop{get;set;}
}
```

-----------------------------------------



#七. 分割线
***
-----------------------------------------

#八. 表格
<table>
	<tr>
		<th>列1</th><th>列2</th>
	</tr>
    <tr>
        <td>Foo</td><td>bar</td>
    </tr>
</table>