jquery.easydrag
===============

Make a dom element draggable

###How to use:
```javascript
$('.draggable-element').dragdrop({
  eventsuffix : '.dragdrop',
	anchor: '',
	bound : 'window',
	dragstart: function() {
	},
	dragmove: function(d) {
	},
	dragend: function() {
	}
});

```
###settings
```javascript
//eventsuffix: string, default to '.dragdrop', a jquery event namespace

//anchor: drag trigger of the selected draggable element, default to element itself.

//bound: selector string, default to window

```
