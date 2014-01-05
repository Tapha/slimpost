##SŁIMPØST / Minimal theme for Ghost

###Overview
**Slimpost** is clean, minimal and responsive theme for Ghost.

**Demo**: [http://slimpost-ghost.infinitum.me](http://slimpost-ghost.infinitum.me)

####Features
- Clean and minimal design
- Responsive HTML5/CSS3 layout
- Fullscreen image viewer (using Darkbox)
- Disqus integration
- Social links block (using Font Awesome Icons)
- FitVids for embedded videos
- Smooth page scrolling
- Using Type Rendering Mix JS
- Custom fonts

###Installation
1. Copy theme folder into your **Ghost** installation folder: <code>/content/themes</code>.
2. Restart **Ghost** instance.
3. Sign in to **Admin panel**, go to **Settings → General** and select **slimpost** in themes list.

###Configuration

####Social links
You can change links to your social profiles in <code>partials/social-links.hbs</code> file.  
It's possible to add another social icons if you want because theme uses **Font Awesome** icons. You can check out all social icons here: <a href="http://fontawesome.io/icons/#brand" target="_blank">http://fontawesome.io/icons/#brand</a>

####Disqus comments
If you would like to use **Disqus** comments just change your shortname in <code>partials/disqus-shortname.hbs</code>:  
<pre><code>{{! Disqus shortname }}
var disqus_shortname = 'example';</code></pre>

###Theme preview

![Desktop view](https://raw.github.com/bzhnyau/slimpost/master/screenshots/preview.png)

![Mobile view #1](https://raw.github.com/bzhnyau/slimpost/master/screenshots/S31028-205539.jpg)

![Mobile view #2](https://raw.github.com/bzhnyau/slimpost/master/screenshots/S31028-205607.jpg)