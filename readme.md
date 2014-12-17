#What is it for ?
This is for making clean menu markup and without touching main css (menu.css) customizing menu from additional css file. Like if you want to make top menu if you created top-menu.css for extending definitions in menu.css

```html
<ul class="menu top">
	<li><a href="#">Home</a>
		<ul>
			<li><a href="#">News</a></li>
			<li><a href="#">Weather</a></li>
			<li><a href="#">Blog</a>
				<ul>
					<li><a href="#">About Blog</a></li>
					<li><a href="#">New Posts</a></li>
					<li><a href="#">Our bloggers</a></li>
				</ul>
			</li>
		</ul>
	</li>
	<li><a href="#">About</a></li>
	<li><a href="#">Services</a>
		<ul>
			<li><a href="#">Another Sub 1</a></li>
			<li><a href="#">Another Sub 2</a></li>
			<li><a href="#">Another Sub 3</a>
		</ul>
	</li>
	<li><a href="#">Contact</a></li>
</ul>
```

![](/images/menu1.png)