# 7-lab
<p></p>

<h2 align="center">ФЕДЕРАЛЬНОЕ ГОСУДАРСТВЕННОЕ БЮДЖЕТНОЕ ОБРАЗОВАТЕЛЬНОЕ УЧРЕЖДЕНИЕ ВЫСШЕГО ПРОФЕССИОНАЛЬНОГО ОБРАЗОВАНИЯ <br> «САХАЛИНСКИЙ ГОСУДАРСТВЕННЫЙ УНИВЕРСИТЕТ» <br> КАФЕДРА ИНФОРМАТИКИ </h2>
<p align="center">Лабораторная работа №7 <br>
по предмету «Web-технологии, языки и средства создания web-приложений» 

<p align="center"><b>"Java Script"</b><p>
<p align="right"><b>Выполнил: </b> студент 231 группы Хорошко Илья Алексеевич</p>
<p  align="right"><b>Проверил: </b> Соболев Е. И., старший преподователь</p>
<br>
<br>
<br>
<p align="center">Южно-Сахалинск <br> СахГУ <br> 2023</p>
<h2> Введение </h2>
<p>Лабораторные работы по дисциплине «Web-технологии, языки и средства создания web-приложений» предназначены для освоения полученных теоретических знаний на практике. <br>
<h2>Цель:</h2>
  <p>Повторить по образцу, то есть сделать такой же макет используя материалы из архива lab7.zip</p>
  <h2 align="center">Решение</h2>
  
  index.html:
  
  ```html

  <!DOCTYPE html>
<html lang="en">
<head>
	<meta charset="UTF-8">
	<link href="http://fonts.googleapis.com/css?family=Arvo:400,700|Cookie" rel="stylesheet" type="text/css" />
	<link rel="stylesheet" href="style.css">
</head>
<body>
	<header>
		<div class="center">
			<a href="#" class="logo">Elysa4t</a>
			<nav>
				<ul>
					<li class="active"><a href="">Home</a></li>
					<li><a href="">Archives</a></li>
					<li><a href="">Gallery</a></li>
					<li><a href="">About</a></li>
					<li><a href="">Contact</a></li>
				</ul>
			</nav>
		</div>
	</header>

		<section class="banner">
			<div class="center">
				<div class="the-banner">
					<h2>Magna sed phasellus consequat lorem ipsum dolor</h2>
				</div>
			</div>
		</section>

		<main>
			<div class="center">
				<div class="post">
					<div class="posted">Posted by <a href="#">Someone</a> on April 14, 2012</div>
					<div class="entry">
						<h2 class="title">Lorem ipsum sed veroeros amet</h2>
						<a href="#" class="post-pic"></a>
						<p>
							Nam vestibulum hendrerit orci, sed pharetra elit elementum in. Donec in eros sed odio varius tempus. Vestibulum quis quam et velit rutrum ornare nec a massa. Curabitur malesuada ullamcorper nunc in suscipit. Donec semper venenatis dui sed facilisis. Morbi congue facilisis ante in feugiat. Mauris consectetur magna eu enim sagittis et bibendum lacus imperdiet. Maecenas semper massa ac odio ornare sodales. Nunc rhoncus vulputate nisi sed malesuada. Fusce ac mauris dui, id luctus ligula. Integer hendrerit.
						</p>
						<div class="meta">
						<p><span class="tags">Posted in <a href="#">News</a>, <a href="#">Design</a>, <a href="#">Other</a></span><span class="comments"><a href="#">235 Comments</a></span></p>
						</div>
					</div>
				</div>

				<aside>
					<div class="bg-top"></div>
					<div class="content-bg">
						<div>
							<div class="posted">About Elysa4t</div>
							<p>Mauris consectetur magna eu enim sagittis et bibendum lacus imperdiet. Maecenas semper massa amet et odio mauris dui, id luctus amet ligula.</p>
						</div>
						<div>
							<div class="posted">Recent Post</div>
							<ul>
								<li class="first"><a href="#">Hendrerit orci sed pharetra elit</a></li>
								<li><a href="#">Donec in eros odio varius tempus</a></li>
								<li><a href="#">Vestibulum quis quam et velit</a></li>
								<li><a href="#">Rutrum ornare nec sed curabitur</a></li>
								<li><a href="#">Malesuada ullamcorper nunc</a></li>
							</ul>
						</div>
						<div>
							<div class="posted">Something Else</div>
							<p>Mauris consectetur magna eu enim sagittis et bibendum lacus imperdiet. Maecenas semper massa amet et odio mauris dui, id luctus amet ligula.</p>
						</div>
					</div>
					<div class="bg-btm"></div>
				</aside>
			</div>
		</main>

	<footer>
		<div class="content">
			<div class="center">
				<div class="box-style">
					<div class="bg-top"></div>
					<div class="content-bg">
						<h2>Just another widget</h2>
						<p>Mauris consectetur magna tempus enim sagittis et bibendum lacus et imperdiet. Maecenas semper et massa amet et odio mauris dui, id luctus amet ligula.</p>
					</div>
					<div class="bg-btm"></div>
				</div>

				<div class="box-style">
					<div class="bg-top"></div>
					<div class="content-bg">
						<h2>Just another widget</h2>
						<p>Mauris consectetur magna tempus enim sagittis et bibendum lacus et imperdiet. Maecenas semper et massa amet et odio mauris dui, id luctus amet ligula.</p>
					</div>
					<div class="bg-btm"></div>
				</div>

				<div class="box-style">
					<div class="bg-top"></div>
					<div class="content-bg">
						<h2>Just another widget</h2>
						<p>Mauris consectetur magna tempus enim sagittis et bibendum lacus et imperdiet. Maecenas semper et massa amet et odio mauris dui, id luctus amet ligula.</p>
					</div>
					<div class="bg-btm"></div>
				</div>
			</div>
		</div>

		<section class="footer">
			<div class="center"><p>© Your Website Name  |  Elysa4T by <a href="">4Templates</a> |  Photos by <a href="">Fotogrph</a></p></div>
		</section>
	</footer>
</body>
</html>
```
style.css:

```css
* {
    margin: 0px;
    padding: 0px;
}

body {
    background: #361C16 url(img/wrapper-bg.png) repeat;
    font-family: "Trebuchet MS", Arial, Helvetica, sans-serif;
    font-size: 13px;
    color: #333;
}

a, a:focus, a:active {
    text-decoration: none;
    color: #fff;
}

p {
    line-height: 170%;
}

ul {
    list-style: none;
}

.center {
    width: 1000px;
    margin: 0 auto;
}





.posted {
    height: 38px;
    padding: 0px 0px 0px 30px;
    background: url(img/post-posted-bg.png) no-repeat left top;
    line-height: 38px;
    letter-spacing: -1px;
    font-family: 'Arvo', serif;
    font-size: 16px;
    color: #FFFFFF;
}

aside .posted {
    background: url(img/sidebar-title-bg.png) no-repeat right top;
    font-weight: 400;
    margin: 20px 0;
    width: 295px;
}

.posted a {
    text-decoration: underline;
}


/*HEADER
======================*/
header {
    height: 187px;
    background: url(img/header-wrapper-bg.png) left top;
    display: flex;
    align-items: center;
}

    header .center {
        display: flex;
        flex-direction: row;
        align-items: center;
        justify-content: space-between;
    }

.logo {
    display: block;
    width: 221px;
    height: 110px;
    background: url(img/logo-bg.png) no-repeat left top;
    line-height: 110px;
    text-align: center;
    text-decoration: none;
    font-family: 'Cookie', cursive;
    font-size: 60px;
    font-weight: 400;
    color: #FFFFFF;
}

header ul {
    display: flex;
    letter-spacing: -1px;
    font-family: 'Arvo', serif;
    font-size: 16px;
}

nav li {
    height: 30px;
    margin-right: 40px;
}

    nav li:last-child {
        margin-right: 135px;
    }

nav a {
    color: #fff;
    line-height: 30px;
    padding: 5px 5px;
}

.active {
    background: #881D1D;
    border-radius: 5px;
    box-shadow: 0 0 10px rgba(255, 255, 255, 0.3);
}

    .active a {
        padding: 5px 15px;
    }


/*BANNER
======================*/
.banner {
    background: url(img/banner-wrapper-bg.png) repeat;
    padding: 32px 0;
}

.the-banner {
    margin: 0 auto;
    width: 960px;
    height: 278px;
    background: url(img/banner-image.jpg);
    background-size: cover;
    display: flex;
    text-align: center;
    border-radius: 9px;
}

    .the-banner h2 {
        width: 100%;
        padding: 15px 0;
        background: url(img/banner-caption-bg.png) no-repeat left bottom;
        align-self: flex-end;
        border-radius: 0 0 8px 8px;
        font-weight: normal;
        font-family: 'Cookie', cursive;
        font-size: 35px;
        color: #FFFFFF;
    }


/*PAGE
======================*/
main {
    padding: 30px 0px;
    background: url(img/page-wrapper-bg.png) repeat;
}

    main .center {
        display: flex;
        flex-direction: row;
        justify-content: space-between;
        align-items: flex-start;
    }

/*LEFT SIDE OF PAGE
*/
.post {
    width: 630px;
    padding: 30px 0px;
    background-color: #FFFFFF;
    border: 1px solid #E5D0D0;
    border-radius: 5px;
}

.entry {
    padding: 30px 30px 0px 30px;
}

.title {
    display: block;
    padding: 0px 0px 20px 0px;
    letter-spacing: -2px;
    font-family: 'Arvo', serif;
    font-size: 34px;
    color: #4E2B22;
    font-weight: 400;
}

.post-pic {
    display: block;
    width: 570px;
    height: 196px;
    background: url(img/pics01.jpg) no-repeat;
    background-size: cover;
    border-radius: 5px;
}

.post p {
    margin-top: 25px;
}

.post .meta {
    display: block;
    height: 66px;
    margin-top: 30px;
    padding: 0px 25px;
    background: url(img/posted-meta-bg.png) no-repeat left top;
    font-family: 'Arvo', serif;
    font-size: 16px;
    font-weight: normal;
    color: #572F26;
}

.meta a {
    text-decoration: underline;
    color: inherit;
}

    .meta a:hover {
        text-decoration: none;
    }

.tags {
    float: left;
    line-height: 66px;
}

.comments {
    float: right;
    line-height: 66px;
}


/*RIGHT SIDE OF PAGE
*/
main aside {
    width: 330px;
    border-radius: 5px;
    color: #E1C9C4;
}

.bg-top {
    height: 12px;
    background: url(img/sidebar-bg-01.png) no-repeat left top;
}

.bg-btm {
    height: 15px;
    background: url(img/sidebar-bg-03.png) no-repeat left top;
}

aside p {
    padding: 0px 60px 0px 30px;
    text-shadow: 1px 1px 0px rgba(54,29,24,1);
}

aside ul li {
    border-top: 1px solid #371E18;
    margin: 0px 60px 0px 30px;
    padding: 10px 0px 10px 0px;
}

    aside ul li:first-child {
        border-top: none;
    }

aside p:last-child {
    padding-bottom: 10px;
}

aside .content-bg {
    overflow: hidden;
    background: url(img/sidebar-bg-02.png) repeat-y left top;
}


/*FOOTER
======================*/
footer {
    background: url(img/footer-content-bg-01.png) repeat;
}

    footer .content {
        padding: 40px 0px 30px 0px;
        background: url(img/footer-content-bg-02.png) repeat-x left top;
    }

        footer .content .center {
            display: flex;
            flex-direction: row;
            justify-content: space-between;
        }

    footer .box-style {
        width: 300px;
        margin-right: 30px;
    }

        footer .box-style h2 {
            padding: 0px 0px 20px 0px;
            font-family: 'Arvo', serif;
            font-size: 13px;
            font-weight: 400;
            color: #FFFFFF;
        }

        footer .box-style p {
            text-shadow: 1px 1px 1px rgba(57, 27, 22, 1);
            color: #E1C9C4;
        }

    footer .bg-top {
        background: url(img/box-widget-bg-01.png) no-repeat left top;
    }

    footer .bg-btm {
        background: url(img/box-widget-bg-03.png) no-repeat left top;
    }

    footer .content-bg {
        padding: 20px 30px 10px 30px;
        background: url(img/box-widget-bg-02.png) repeat left top;
        ;
    }

.footer {
    height: 155px;
    background: url(img/footer-bg.png) repeat-x left top;
}

    .footer p {
        margin: 0px;
        padding: 40px 0px 0px 0px;
        text-shadow: 1px 1px 2px rgba(39, 20, 17, 1);
        text-align: center;
        color: #784F45;
    }

    .footer a {
        text-decoration: underline;
        color: inherit;
    }

        .footer a:hover {
            text-decoration: none;
        }
```

<h2 align="center">Вывод</h2>
Закрепил полученные навыки верстки сайта.
