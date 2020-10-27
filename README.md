# ABUHB User Interface Design Standards
Updated: 27/10/2020 - JJ
<p>If you want to add all css and scripts please see <a href="#kitchen-sink">Kitchen Sink</a>.

<h2>Bootstrap</h2>
<p>Bootstrap is our preffered CSS framework for front end.  V4.5.3 is the production version as of 27/10/20.</p>
<p>Add this line of code <b>inside</b> your <code>&lt;head&gt;</code> tag;</p>
<p><code>&lt;link rel=&quot;stylesheet&quot; href=&quot;https://abuhb.github.io/ui/bootstrap-4.5.3-dist/css/bootstrap.css&quot;&gt;</code></p>
<p>Add this script <b>just above</b> <code>&lt;/body&gt;</code> tag.  NOTE: Includes jQuery.</p>
<p><code>&lt;script src=&quot;https://abuhb.github.io/ui/bootstrap-4.5.3-dist/js/bootstrap.bundle.min.js&quot;&gt;&lt;/script&gt;</code></p>
<ul>
<li><a href="https://getbootstrap.com/docs/4.5/layout/overview/">Bootstrap Documentation</a></li>
</ul>
<hr>

<h2>NHS Colours</h2>
<p>NHS Colours are a design standard that we use alongside Bootstrap.</p>
<p>Add this line of code <b>inside</b> your <code>&lt;head&gt;</code> tag;</p>
<code>&lt;link rel=&quot;stylesheet&quot; href=&quot;https://abuhb.github.io/ui/nhs-colours.css&quot;&gt;</code>
<ul>
<li><a href="https://www.england.nhs.uk/nhsidentity/identity-guidelines/colours/">Colour Usage Guidance</a></li>
</ul>
<hr>

<h2>Font Awesome</h2>
<p>Font Awesome provides an excellent range of icons.</p>
<p>Add this script <b>just above</b> <code>&lt;/body&gt;</code> tag.</p>
<code>&lt;script defer src=&quot;https://abuhb.github.io/ui/fontawesome/js/all.js&quot;&gt;&lt;/script&gt;</code>
<ul>
<li><a href="https://fontawesome.com/cheatsheet">FontAwesome Cheatsheet</a></li>
</ul>
<hr>

<h2>Kitchen Sink</h2>
<p>This will add Bootstrap, FontAwesome and NHS Colours to your site;</p>
<h3>Inside &lt;head&gt;</h3>
<code>&lt;link rel=&quot;stylesheet&quot; href=&quot;https://abuhb.github.io/ui/bootstrap-4.5.3-dist/css/bootstrap.css&quot;&gt;<br />
&lt;link rel=&quot;stylesheet&quot; href=&quot;https://abuhb.github.io/ui/nhs-colours.css&quot;&gt;</code>
<h3>Above &lt;/body&gt;</h3>
<p>
<code>&lt;script defer src=&quot;https://abuhb.github.io/ui/fontawesome/js/all.js&quot;&gt;&lt;/script&gt;<br />

&lt;script src=&quot;https://abuhb.github.io/ui/bootstrap-4.5.3-dist/js/bootstrap.bundle.min.js&quot;&gt;&lt;/script&gt;<br />
<br />
</code></p>