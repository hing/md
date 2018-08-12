# Meet md!

A static site generator that moves the "generator" part to the browser.
This site is pure text files with a single Javascript included on each page that renders
the theme and assets as needed.

Each page is written in markdown with a single `<script>` tag that includes md.js. Once you have created your pages then simply upload the system to your website and enjoy.

**md** includes an enhanced [Online Markdown Editor](https://hing.me/md/editor.html) you can use to write your posts using a live preview of the rendered markdown. It uses `localStorage` to persist your writings even if you lose power.

## [Visit the Demo](https://hing.me/md/)

## Getting Started

1. Download [md.js](https://hing.me/md/js/md.js)
2. Create an **filename.html** file and write in Markdown
3. Paste the following code at the bottom of the page:  
	<code><script src="md.js"></script></code>  
4. `git commit` the new article or (sad face) SFTP it up to your web host

...and you're done! Rinse and repeat.

## Degrading gracefully in the absence of JavaScript

If you want the MarkDown content to appear as human-readable MarkDown text in browsers without JavaScript (instead of as an undelimited blob), add a line like this at the top of your documents:

\[enable JavaScript to render MarkDown\]: \<pre\>

This is a MarkDown comment that will not be rendered, but HTML renderers will see the \<pre\> tag and act accordingly.

## Masthead Images

For those of you who like to include photo mastheads on your posts. Simply place a Markdown image tag at the top of your post (within the first 100 characters) and it will be displayed in the header.

	![masthead](http://example.com/image.jpg)

MIT License with ♡ from [David Pennington](http://davidpennington.me)

[Donate Stellar](https://www.stellar.org) to xeoncross
