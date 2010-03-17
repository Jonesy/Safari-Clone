# A good browser should be able to reproduce itself.

### This is Safari 4 built entirely with HTML and CSS3. No images used.

(Only works in Webkit Mac-based browsers, of course)

Being a web developer who works on a Mac, I've noticed that Apple's implementation of CSS3 to Webkit and Safari always felt like they were extending OS X GUI elements to the web, even going so far as to make the iTunes store mostly out of Webkit. With that in mind and being inspired by David DeSandro's Opera Logo made in CSS, I decided to take on Safari. I approached this with the goal of doing so with:

+ Only CSS
+ No images
+ No JavaScript
+ No Canvas

With those limits there of course were some of Safari's default state that didn't make the cut for now — most obviously the tabs and various icons. I also didn't take any steps to make this experiment work in any other browser (it does work in Chrome for Mac however). Eventually I'd like to perform the same experiment with FireFox 3.6, and perhaps others down the road if CSS3 advancements become available.

### Some notes:

* The most surprising part was being able to recreate with little effort the Aqua window buttons with multiple CSS gradient backgrounds. I ended up having to add an extra &lt;span&gt; element so I could get the bevel in cleanly, but I almost could of got away with just one &lt;div&gt;.
* I chose to go with &lt;input type="search"&gt; over styling a text input with -webkit-border-radius (which looks too jagged). Con is that the border colour is slightly off, but pro is it looks nicer and we gain the magnifying glass icon for free (keeping with the no images rule).
* I went with fonts over skewed and rotated &lt;div&gt;'s for the button labels, but with an extra bit of work I could switch them over in order to lose some of the fuzziness that comes with Safari's font anti-aliasing.
* In the spirit of making the browser with no additional images, I opted to keep the Address Bar globe out, as well as the Refresh button, but with little work they can be slotted in. The source is available on Github, and if anyone wants to take on making the browser actually work, have at it!

Next up: Mobile Safari.