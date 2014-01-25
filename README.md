# Colorbox Skins
Colorbox Skins is a small collection of UI treatments applied to the popular jQuery plugin, [Colorbox](http://jacklmoore.com/colorbox/), by Jack Moore.

## About the Skins
The Colorbox plugin "ships" with a group of UI treatments, numbered Example 1 through 5 respectively, that demonstrate different ways to display content presented by ColorBox. The five UI treatments provide a basis for understanding how to modify the display.

While changing the display isn't difficult, some people want the ease of a theme (or skin) to bring about a different look and feel
to their content. Here are a few:

## Example 5, Inverted
This simple skin repositions the main title bar used by the plugin in its included skin, Example 5.

### Screenshots
Here is the original Example 5 shipped with the Colorbox plugin:

![Colorbox Example 5](http://www.cssian.com/colorbox/skins/example5.png "Original Example 5")

Here is the inverted version contained in this project:

![Colorbox Example 5 Inverted](http://www.cssian.com/colorbox/skins/example5-inverted.png "Inverted Example 5 skin")

### Background: Question 10456680 on StackOverflow
Awhile back Nuri Akman posed a [question on SO](http://stackoverflow.com/questions/10456680/moving-colorboxs-captions-to-top-of-box) about tweaking the position of Colorbox's main image line.  I posted an answer that was accepted and ended up writing code that was useful to the questioner.

That code was stored on another public file-sharing system and downloaded many times.

### New Home
As of now, the so-called "Example 5 (Inverted)" is moved here, as part of this project.

### Files and Diff
There are no changes to the example's index.html file, and only minimal changes to the plugin's CSS file, colorbox.css.

A simple diff of the plugin's CSS file and this skin's is included for convenience. It's just for quick reference and isn't necessary to use this skin. Find it in the _addl_ folder.

Also in the _addl_ folder are two images that depict the impact of the CSS.

### Use and Testing
Install the CSS file from this project into the folder where you store Colorbox's original CSS file. Be sure to make a copy of the original file before doing so. You are *on your own* as to testing in the browsers of interest to you.

## Sheer
This simple skin adds a semi-transparent background to the caption (title) text. The text is separately styled so that it is not subject
to the CSS *opacity* rule that results in the transparency.

###Screenshot
Here is a shot of the skin applied to Colorbox content, using the default Colorbox CSS file (also known as Example 1):

![Colorbox Sheer](http://www.cssian.com/colorbox/skins/sheer.png "Sheer skin")

### Changes Made to the Plugin
To bring about the separate styling of the title text, both the CSS and JS of the plugin have been modified slightly. A simple diff of'the changes is included on the _addl_ folder. The diff is just for quick reference and isn't necessary to use this skin.

Also in the _addl_ folder is an image that depicts the Sheer skin as applied to Colorbox's original Example 1 theme.

### Use and Testing
Install the CSS file from this project into the folder where you store Colorbox's original CSS file. Be sure to make a copy of the original file before doing so. You are *on your own* as to testing in the browsers of interest to you.

Additionally, you probably don't want to use this skin on some of the more advanced Colorbox examples, as the results are wonky.
For example, the skin incorrectly overlays the main window when used with the inline video examples.  Perhaps a fix is coming. :)


