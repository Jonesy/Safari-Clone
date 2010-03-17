# A good browser should be able to reproduce itself.

### This is Safari 4 built entirely with HTML and CSS3. No images used.

(Only works in Webkit Mac-based browsers, of course)

One thing I've always noticed working as a web developer on a Mac is that Webkit always seemed to have CSS3 features that allows one to recreate Aqua elements quite easily. Inspired by David DeSandro's Opera Logo made in CSS, I decided to take on Safari. I approached this with the goal of doing so with:

+ No images
+ No JavaScript
+ No Canvas

So there some features of Safari's default state that didn't make the cut, like tabs and a some icons and I didn't take any steps to make this experiment work in any other browser (it does work in Chrome for Mac though), I do want to take on FireFox 3.6 to see how far I can reproduce it with Mozilla's CSS3 implementation.

### Some notes:

The most surprising part was being able to recreate the Aqua window buttons with multiple CSS gradient backgrounds and not a whole lot of effort. I ended up having to add an extra <span> element so I could get the bevel in cleanly, but I almost could of got away with just one <div>.

I chose to go with <input type="search"> over styling a text input with -webkit-border-radius (which looks to jaggedy). Con is that the border colour is slightly off, but pro is it looks nicer and we gain the magnifying glass icon for free (keeping with the no images rules).

I chose fonts over <div>'s for the button labels, but with an extra bit of work I could switch them over in order to lose some of the fuzziness that comes with the anti-aliasing.

In the spirit of making the browser with no additional images, I opted to keep the Address Bar globe out, as well as the Refresh button, but with little work these can be slotted in. The source is available on Github, and if anyone wants to take on making the actually browser work, have at it!

Next up: Mobile Safari.