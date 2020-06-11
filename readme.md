
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
<div id="magazine">
	<div><span class="text">Page 1</span></div>
	<div><span class="text">Page 2</span></div>
	<div><span class="text">Page 3</span></div>
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
