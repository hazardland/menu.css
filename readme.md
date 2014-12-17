#What is it for ?
This is for making clean menu markup and without touching main css (menu.css) customizing menu from additional css files.

Like if you want to make a top menu and if you created top-menu.css for extending definitions in menu.css. So there is main .menu class and you extend like .menu.top for menu called .top.

The only thing you need from this mess to work is menu.css. Other files in this repo are for testing and demonstration purposes and on the fly I am learning github markdown cool features.

Here is how your markup looks like:
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
While it will show up as even hovered:

![](/images/menu1.png)

But if browser width reduced:

![](/images/menu2.png)

Than if that button clicked:

![](/images/menu3.png)

Than if submenu parent clicked:

![](/images/menu4.png)

See index.html to get how this was done using menu.css and 4 lines of javascript code for click handling.