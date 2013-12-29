# jQuery DevAnime
DevAnime is a jQuery plugin that scrolls content with css3 animation. You'll find all the documentation you need at [samimaxhuni.info](http://samimaxhuni.info).

```javascript
$(document).ready(function () {
	$(document).DevSolutionAnime({
		parent_class : '.animated-area',
        child_class  : '.animated',
        anime_attr   : 'data-devanime',
        delay_attr   : 'data-devanime-delay'
	});
```
In order for this to work you also need to include animate.css on your page.

Here's an example of how you would use it for loading raw HTML:

```javascript
<script>
$(document).DevSolutionsAnime({
	parent_class : '.animated-area',
        child_class  : '.animated',
        anime_attr   : 'data-devanime',
        delay_attr   : 'data-devanime-delay',
        anime_hide   : false
});
</script>

<div class="animated-area">
	<div class="animated" data-devanime="fadeInLeftBig" data-devanime-delay="0.6s">
		Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod
		tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam,
		quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo
		consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse
		cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non
		proident, sunt in culpa qui officia deserunt mollit anim id est laborum.
	</div>
	<div class="animated" data-devanime="fadeInRightBig" data-devanime-delay="0.6s">
		Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod
		tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam,
		quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo
		consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse
		cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non
		proident, sunt in culpa qui officia deserunt mollit anim id est laborum.
	</div>

</div>
```
