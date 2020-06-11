
![Bilby Stampede](http://turnjs.com/pics/small-turnjs-letters.png)

**Get the turn.js 4th release on [turnjs.com](http://www.turnjs.com/)**


### What's new?

- Added option `flipalign`

- Added method `translateCoordinate`

- Modify method `eventMove`

- Modify method `cornerActivated`

- Modify method `center`

- Modify method `makeFlip`

* * *

#### Usage

**CSS code:**
```css
.rotate img{
  transform: rotate(-90deg);
  overflow: hidden;
}
```

**HTML code:**
```html
<div id="flipbook">
	<div class="page-wrapper">
		<div class="page rotate"> <img src="web/img/9c2ceddeafec3b7fc8dc9e8c45c9d186.jpg"/> </div>
	</div>
	<div class="page-wrapper">
		<div class="page rotate"> <img src="web/img/9c2ceddeafec3b7fc8dc9e8c45c9d186.jpg"/> </div>
	</div>
	<div class="page-wrapper">
		<div class="page rotate"> <img src="web/img/9c2ceddeafec3b7fc8dc9e8c45c9d186.jpg"/> </div>
	</div>
	<div class="page-wrapper">
		<div class="page rotate"> <img src="web/img/9c2ceddeafec3b7fc8dc9e8c45c9d186.jpg"/> </div>
	</div>
	<div class="page-wrapper">
		<div class="page rotate"> <img src="web/img/9c2ceddeafec3b7fc8dc9e8c45c9d186.jpg"/> </div>
	</div>
	<div class="page-wrapper">
		<div class="page rotate"> <img src="web/img/9c2ceddeafec3b7fc8dc9e8c45c9d186.jpg"/> </div>
	</div>
	<div class="page-wrapper">
		<div class="page rotate"> <img src="web/img/9c2ceddeafec3b7fc8dc9e8c45c9d186.jpg"/> </div>
	</div>
	<div class="page-wrapper">
		<div class="page rotate"> <img src="web/img/9c2ceddeafec3b7fc8dc9e8c45c9d186.jpg"/> </div>
	</div>
</div>
```

**JavaScript code:**
```javascript
$("#flipbook").css('transform', `translate3d(0px, 0px, 0px) rotate(90deg)`);
```

#### Requirements

jQuery 1.7 or later

#### Browser support
* Chrome 12, Safari 5, Firefox 10, IE 9

#### License
Released under a non-commercial BSD license

[Full documentation](https://github.com/blasten/turn.js/wiki/Reference)

* * *

[turnjs.com](http://www.turnjs.com/)
