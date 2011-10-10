# JoshuaRJones.me Resume Layout

JoshuaRJones.me strives to be a clean, semantic and responsive resume-like site layout. Largely inspired from [Bold - CV / Resume Template](http://themeforest.net/item/bold-cv-resume-template-minimal-smart/210069?ref=QBKL) by [Nathan McMillan](http://nathanmcmillan.com).

I desired a responsive resume layout without extra `div`s with a class of `.clear` to make the layout work. It's a slow work in progress, mostly because I'm busy with numerous other projects, but it should be a solid semantic resume layout when it's completed.

**Themes:** To get a different theme, there are really only two areas that need tweaking. The body's background color:

`body {
	background: -> #9ebf75 <- url( ../images/grid-bg.png);
	}`
	
And if you want to keep the unified feel, you'll need to edit the colors for the progress meters:

`.meter span {
	background-color: #acd27c;
	background-image: -webkit-gradient(linear, left top, left bottom, from(#acd27c), to(#7aa04b));
	background-image: -webkit-linear-gradient(top, #acd27c 0%, #7aa04b 100% );
	background-image:    -moz-linear-gradient(top, #acd27c 0%, #7aa04b 100% );
	background-image:     -ms-linear-gradient(top, #acd27c 0%, #7aa04b 100% );
	background-image:      -o-linear-gradient(top, #acd27c 0%, #7aa04b 100% );
	background-image:         linear-gradient(top, #acd27c 0%, #7aa04b 100% );
	display: block;
	overflow: hidden;
	}`

## Skillset Region

The progress bars in the skillset region are inspired from [Chris Coyier's](http://css-tricks.com/) progress bars article, updated and cleaned up a bit.

The `span` element inside the `div` with the class `.meter` has an inline style attribute to declare the width in a percentage. This spans out the bar inside of the `div`, giving the appearance of a progress bar.

More here: [http://css-tricks.com/8518-css3-progress-bars/](http://css-tricks.com/8518-css3-progress-bars/)

## To-Do

* JavaScript trigger that slides down brief explanation when a skillset is clicked on.
* CSS opacity hover effects on social icons and gallery thumbs

### Bugs

If you find a bug playing with the layout, please create an issue here on GitHub.

[https://github.com/JoshuaJones/JoshuaRJones.me/issues](https://github.com/JoshuaJones/JoshuaRJones.me/issues)