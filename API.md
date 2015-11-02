# music.note.freq


<!-- START docme generated API please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN docme TO UPDATE -->

<div>
<div class="jsdoc-githubify">
<section>
<article>
<div class="container-overview">
<dl class="details">
</dl>
</div>
<dl>
<dt>
<h4 class="name" id="freq"><span class="type-signature"></span>freq<span class="signature">(tuning, note)</span><span class="type-signature"> &rarr; {Float}</span></h4>
</dt>
<dd>
<div class="description">
<p>Get the pitch frequency in herzs with custom concert tuning</p>
<p>This function is currified so it can be partially applied (see examples)</p>
</div>
<h5>Parameters:</h5>
<table class="params">
<thead>
<tr>
<th>Name</th>
<th>Type</th>
<th class="last">Description</th>
</tr>
</thead>
<tbody>
<tr>
<td class="name"><code>tuning</code></td>
<td class="type">
<span class="param-type">Float</span>
</td>
<td class="description last"><p>the frequency of A4 (null means 440)</p></td>
</tr>
<tr>
<td class="name"><code>note</code></td>
<td class="type">
<span class="param-type">String</span>
|
<span class="param-type">Array</span>
</td>
<td class="description last"><p>the note name</p></td>
</tr>
</tbody>
</table>
<dl class="details">
<dt class="tag-source">Source:</dt>
<dd class="tag-source"><ul class="dummy">
<li>
<a href="https://github.com/danigb/music.note.freq/blob/master/index.js">index.js</a>
<span>, </span>
<a href="https://github.com/danigb/music.note.freq/blob/master/index.js#L8">lineno 8</a>
</li>
</ul></dd>
</dl>
<h5>Returns:</h5>
<div class="param-desc">
<p>the frequency of the note</p>
</div>
<dl>
<dt>
Type
</dt>
<dd>
<span class="param-type">Float</span>
</dd>
</dl>
<h5>Examples</h5>
<pre class="prettyprint"><code>freq(null, 'A4') // => 440
freq(444, 'A4') // => 444</code></pre>
<pre class="prettyprint"><code>// partially applied
['A4', 'A#4', 'B5'].map(freq(440)) // => [440, ...]
var baroque = freq(415)
baroque('A3') // => 207.5</code></pre>
</dd>
</dl>
</article>
</section>
</div>

*generated with [docme](https://github.com/thlorenz/docme)*
</div>
<!-- END docme generated API please keep comment here to allow auto update -->
