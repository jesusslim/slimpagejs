# slimpagejs
javascript for pages | JS分页

##How to use
	
###1.Init | *初始化*

[*English*]

`SlimPage.init("body",5,20,100);`

The first param is the __dom__ where you want to add the page square.For example:".class" or "#id".

The second param is the __page now__.You can get it from the url,or get it by ajax,or set it when rendering the html template.

The third param is the __pagesize__.

The last param is __total__ of the pages.

[*Chinese*]

`SlimPage.init("body",5,20,100);`

第一个参数表示需要添加分页区域的元素 例如 ".class" or "#id"

第二个参数表示当前在第几页，可以通过url获取，或者ajax取数据时获取，或者渲染模板时获取等

第三个参数表示一页的数据条数

第四个参数表示总页数

###2.Show pages html | *显示分页区域*

`SlimPage.showPage();`

Of course you shoud init it before show page.

调用时请确保已进行初始化

###3.Aboun webpage-jumping | *关于分页*

When we click on the page num,the webpage will jump to the url: __baseurl?page=x__ .

点击页码后跳转到的url为：__当前的基本url(已除去参数)?page=x__

###4.How to add other params in url | *url跳转时传递其他参数*

`SlimPage.Params.cat = 5;`

We can add some params to SlimPage.Params,if we do this,when we click to jump,the url is: __baseurl?page=x&cat=5__ .

我们可以通过给SlimPage.Params对象添加其他需要传递的参数，这样我们点击页码跳转到的url为：__当前的基本url(已除去参数)?page=x&cat=5__

##Contact me

Jesus Slim

Email1:[755808379@qq.com]

Email2:[jesus.slim@yahoo.com]

[755808379@qq.com]:mailto:755808379@qq.com
[jesus.slim@yahoo.com]:mailto:jesus.slim@yahoo.com
