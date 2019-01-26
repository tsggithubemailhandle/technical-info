# GLOSSARY OF TECHNICAL TERMS

### <a id="hook_box">Hook Box</a>
A <a href="#hook_box">**Hook Box**</a> is a special input box within the Administrative portion of the website that is spawned by the <a href="#dynamik-gen_theme_and_plugin">**Dynamik-Gen Theme and Plugin**</a>. Code is put into these Hook Boxes by the designer modularly, creating modules of code in the website that execute under certain conditions. These conditions are orchestrated as visually selectable options around the Hook Box input area. The term <a href="#hook_box">**Hook Box**</a> can also refer to the executing code itself or the results that the Hook Box produces. Most often, the result of the Hook Box is content on the website that couldn't be created using the capabilities of our current graphical content creation tools, such as <a href="#thrive">**Thrive**</a>.

### <a id="dynamik-gen_theme_and_plugin">Dynamik-Gen Theme and Plugin</a>
The <a href="#dynamik-gen_theme_and_plugin">**Dynamik-Gen Theme and Plugin**</a> is a special plugin that alters both the *public* parts of the website and the *private, administrative* parts of the website so that a designer can more easily *generate dynamic content*. It is installed as a <a href="#plugin">**Plugin**</a> which, in turn, alters the administrative part of the website to reveal a new <a href="#theme">**Theme**</a> and new administrative menus specifically for altering that theme. The Dynamik-Gen Theme then must be activated as the website's theme in order to see the changes take effect.

TopSpeedGolf uses this theme, ultimately controlled by the plugin, to give a majority of structure to the website.

### <a id="plugin">Plugin</a>
A <a href="#plugin">**Plugin**</a> is special folder with code files in it that can be uploaded to another special folder, the **Plugin Folder** of the website. The website treats code in the **Plugin Folder** as part of the website's code with the added condition that the designer flags the previously uploaded plugin folder as *activated*. Summarily, that is to say that the designer *uploads the plugin*, then *activates the plugin* in the administrative panel.

Plugins are generally designed to provide specific functionality to the designer of the website.

### <a id="theme">Theme</a>
A <a href="#theme">**Theme**</a> is a special folder with codes files in it that can be uploaded to another special folder, the **Theme Folder** of the website. The website treats code in the **Theme Folder** as part of the website's code with the added condition that the designer flags the previously uploaded theme folder as *activated*. Summarily, that is to say that the designer *uploads the theme*, then *activates the theme* in the administrative panel.

Themes are generally designed to give appearance to the website. Very often, themes will go beyond appearance and involve themselves in plugin-like functionality. This is the case with TopSpeedGolf's <a href="#dynamik-gen_theme_and_plugin">**Dynamik-Gen Theme and Plugin**</a>.

### <a id="thrive">Thrive</a>
<a href="#thrive">**Thrive**</a> is a <a href="#plugim">**Plugin**</a> that exposes alternative, improved menus for graphical content creation. Thrive content tends to be contained within the control of the <a href="#dynamik-gen_theme_and_plugin">**Dynamik-Gen Theme and Plugin**</a>, serving as a supplementary means of managing content within the website. For instance, the top navigation bar of TopSpeedGolf is controlled entirely by Dynamik, but many landing pages are controlled entirely by Thrive.

TopSpeedGolf uses Thrive for grahical content creation, in lieu of the standard WordPress Editor.

### <a id="code">Code</a>
<a href="#code">**Code**</a> refers to any text or content on the website's server that does not load into the browser in an obviously understood way -- lending itself instead to different specialized semantics. The term <a href="#code">**Code**</a> generalizes <a href="#html">**HTML**</a>, <a href="#css">**CSS**</a>, <a href="#javascript">**JavaScript**</a>, and <a href="#php">**PHP**</a> 

### <a id="html">HTML</a>
<a href="#html">**HTML**</a> is **H**yper**T**ext **M**arkup **L**anguage made of tags (hypertext) with text in them which resemble:
```
<b>Hello World!</b>
```
or:


**Hello World!**

as you would see in the Browser. The `<b>` hypertext tags tell the browser to **bold** the text.


### <a id="javascript">JavaScript</a>
<a href="#javascript">**JavaScript**</a> is code that is loaded as content along with a page and then interpreted by the browser to interact with the page, the user, or both. JavaScript appears inside of <a href="#html">**HTML**</a> tags containing text which is interpreted as JavaScript:

```
<script>
  console.log( 'Hello World!!' );
</script>
```
or the tag can take an address which will serve up the text to be interpreted:
```
<script src="https://www.someotherserver.com/resources/scripts/remote_script.js"></script>
```
Almost always, JavaScript is altering the user's experience by manipulating the page. JavaScript can:
- Change any part of the page, text or HTML tags. Obvious examples are pop-up modals and alert dialog boxes. JavaScript can go as far as adding more JavaScript to the page!
- Call and communicate with other resources in the background over the network. Most often, the JavaScript is either pulling something from or reporting something to our server. Sometimes, JavaScript will leverage other websites to outsource page processing/resources. For instance, Drip regularly gives us JavaScript snippets to place around various website pages that allow set-and-forget user tracking. This is JavaScript programming in the background of each user's browser communicating with Drip's servers over the network.
- Learn about the user implicitly or explicitly, by directing the user or by simply recording what they do.

### <a id="css">CSS</a>

### <a id="php">PHP</a>
