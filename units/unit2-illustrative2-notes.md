<!DOCTYPE html>
<html>

<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>unit2-illustrative2-notes</title>
  <link rel="stylesheet" href="https://stackedit.io/style.css" />
</head>

<body class="stackedit">
  <div class="stackedit__left">
    <div class="stackedit__toc">
      
<ul>
<li>
<ul>
<li><a href="#notes-for-unit-2---illustrative-programs">Notes for Unit 2 - Illustrative programs</a></li>
<li><a href="#program-listing">Program Listing</a></li>
<li><a href="#sample-output">Sample Output</a></li>
<li><a href="#documentation">Documentation</a></li>
<li><a href="#cyberdojo-link">CyberDojo link</a></li>
<li><a href="#ppt-presentation">PPT presentation</a></li>
</ul>
</li>
</ul>

    </div>
  </div>
  <div class="stackedit__right">
    <div class="stackedit__html">
      <h2 id="notes-for-unit-2---illustrative-programs">Notes for Unit 2 - Illustrative programs</h2>

<table>
<thead>
<tr>
<th>Question</th>
<th>Answer</th>
</tr>
</thead>
<tbody>
<tr>
<td><p><strong>Coordinate Geometry Terms</strong></p><p><br></p><p>Coordinate Geometry Definition - It is one of the branches of geometry where the position of a point is defined using coordinates.</p><p><br></p><p>What are the Coordinates?	</p><p><br></p></td>
<td><p><span>What are the Coordinates?</span></p><p><br></p><p><span><span class="ql-cursor">﻿</span>Coordinates are a set of values which helps to show the exact position of a point in the coordinate plane.</span></p></td>
</tr>
<tr>
<td><p>Coordinate Plane Meaning	- A coordinate plane is a 2D plane which is formed by the intersection of two perpendicular lines known as the x-axis and y-axis.</p><p><br></p><p>What is the <strong>Distance Formula</strong>?</p></td>
<td><p><span>What is the </span><span>Distance Formula</span><span>?</span></p><p><br></p><p><span><span class="ql-cursor">﻿</span></span>It is used to find the distance between two points situated in <strong>A(x1,y1)</strong> and <strong>B(x2,y2)</strong></p><p><br></p></td>
</tr>
<tr>
<td><p>What is the most logical way to represent a cartesian point in Python?</p><p><br></p><p>A. Use two variables, for e.g.  x1 and y1  or x2 and y2 </p><p>B. Use a single tuple variable</p><p>C. <strong>None</strong> of the above</p></td>
<td><p><strong>Choice B. </strong></p><p><strong>Tuple</strong> is the logical way of representing a point in Python.</p></td>
</tr>
<tr>
<td><p>What is the <a href="https://en.wikipedia.org/wiki/Syntax_(programming_languages)" rel="noopener noreferrer" target="_blank">syntax</a> for defining a point <code>(3, 4)</code> as a tuple in Python? </p><p><br></p><p>A. <code>(3, 4)</code></p><p>B. <code>tuple(3, 4)</code></p><p>C. Both the above are valid</p></td>
<td><p><strong>Choice C. </strong></p><p><br></p><p><strong>﻿(3, 4) </strong>and<strong> tuple(3, 4) </strong>are equivalent to each other.</p><p><br></p></td>
</tr>
<tr>
<td><p>How can you deconstruct a <strong>tuple</strong> that represents a point?</p><p><br></p></td>
<td><p>How do you deconstruct a tuple? </p><p><br></p><p>If</p><p><code>pointA = (6, 8) # construction</code></p><p><br></p><p>then</p><p><code>x1, y1 = pointA # deconstruction</code></p><p><code>print(x1, y1)   # 6, 8 </code></p></td>
</tr>
<tr>
<td><p><code>x1, y1, x2, y2 = (1, 2, 3, 4)</code></p><p><br></p><p>What is the value of <code>x1</code> and <code>y2</code>?</p></td>
<td><pre class="ql-syntax">1 and 4. </pre></td>
</tr>
<tr>
<td><p>What is the distance between (4, 0) and (0, 0)?</p><p><br></p><p><img src="https://memcode-production.s3.us-west-2.amazonaws.com/1585923947937" width="230"></p></td>
<td><p><strong>4</strong></p><p><br></p><p><code class="ql-font-monospace">d = (x1 - x2)</code></p><p><code class="ql-font-monospace">  = 4 - 0 </code></p><p><code class="ql-font-monospace">  = 4 </code></p></td>
</tr>
<tr>
<td><p>What is the distance between (4, 3) and (4, 0)?</p><p><br></p><p><br></p><p><img src="https://memcode-production.s3.us-west-2.amazonaws.com/1585924803590" width="238"></p></td>
<td><p><strong>3</strong></p><p><br></p><p><code>d = (x1 - x2) + (y1 - y2) </code></p><p><code>  = (4 - 4) + (3 - 0) </code></p><p><code>  = 0 + 3</code></p><p><code>  = 3</code></p></td>
</tr>
<tr>
<td><p>What is the distance between (4, 3) and (0, 0)?</p><p><br></p><p><img src="https://memcode-production.s3.us-west-2.amazonaws.com/1585924993650" width="248"></p></td>
<td><p>Using previous formula, we get </p><p><br></p><p><code>d = (x1 - x2) + (y1 - y2) </code></p><p><code>  = (4 - 0) + (3 - 0) </code></p><p><code>  = 4 + 3</code></p><p><code>  = 7</code></p><p><br></p><p>But we know from <a href="https://www.mathsisfun.com/algebra/distance-2-points.html" rel="noopener noreferrer" target="_blank">https://www.mathsisfun.com/algebra/distance-2-points.html</a> </p><p><br></p><p><img src="https://memcode-production.s3.us-west-2.amazonaws.com/1585925436666" width="290"></p><p><br></p></td>
</tr>
<tr>
<td><p>If (x1 - x2) + (y1 - y2) is giving a higher value than what is correct,</p><p><br></p><p>What can the <strong>distance formula</strong> be? </p></td>
<td><p>Why not square the x component and square the y component, and then reduce it down by using square root?</p><p><br></p><p>The distance formula is as follows:</p><p><br></p><p><img src="https://memcode-production.s3.us-west-2.amazonaws.com/1585939313392"></p></td>
</tr>
<tr>
<td><p>What is the distance between <strong>(2, -1)</strong> and <strong>(5, 3)</strong>?</p></td>
<td><p><img src="https://memcode-production.s3.us-west-2.amazonaws.com/1585926241096" width="276"></p></td>
</tr>
<tr>
<td><p>Are you confident of writing the code for <strong>Distance between Two Points? </strong></p><p><br></p><p><strong><span class="ql-cursor">﻿</span></strong></p></td>
<td><p>Test yourself at <a href="http://j.mp/twoPoints" rel="noopener noreferrer" target="_blank">http://j.mp/twoPointsCC</a></p></td>
</tr>
</tbody>
</table><h2 id="program-listing">Program Listing</h2>
<pre class=" language-python"><code class="prism  language-python"><span class="token keyword">from</span> math <span class="token keyword">import</span> sqrt


<span class="token keyword">def</span> <span class="token function">distance_between</span><span class="token punctuation">(</span>pointA<span class="token punctuation">,</span> pointB<span class="token punctuation">)</span><span class="token punctuation">:</span>
    <span class="token triple-quoted-string string">"""Computes the distance between two Point objects.
    
    """</span>
    x1<span class="token punctuation">,</span> y1 <span class="token operator">=</span> pointA
    x2<span class="token punctuation">,</span> y2 <span class="token operator">=</span> pointB

    distx <span class="token operator">=</span> x1 <span class="token operator">-</span> x2
    disty <span class="token operator">=</span> y1 <span class="token operator">-</span> y2

    <span class="token keyword">return</span> sqrt<span class="token punctuation">(</span>distx<span class="token operator">**</span><span class="token number">2</span> <span class="token operator">+</span> disty<span class="token operator">**</span><span class="token number">2</span><span class="token punctuation">)</span>


<span class="token comment"># main program</span>

<span class="token comment"># tuple packing allows for assigning</span>
<span class="token comment"># multiple inputs in one statement</span>

pointA <span class="token operator">=</span> <span class="token builtin">int</span><span class="token punctuation">(</span><span class="token builtin">input</span><span class="token punctuation">(</span><span class="token string">"Enter xcordinate for PointA "</span><span class="token punctuation">)</span><span class="token punctuation">)</span><span class="token punctuation">,</span> \
    <span class="token builtin">int</span><span class="token punctuation">(</span><span class="token builtin">input</span><span class="token punctuation">(</span><span class="token string">"Enter ycordinate for PointA "</span><span class="token punctuation">)</span><span class="token punctuation">)</span>

pointB <span class="token operator">=</span> <span class="token builtin">int</span><span class="token punctuation">(</span><span class="token builtin">input</span><span class="token punctuation">(</span><span class="token string">"Enter xcordinate for PointB "</span><span class="token punctuation">)</span><span class="token punctuation">)</span><span class="token punctuation">,</span> \
    <span class="token builtin">int</span><span class="token punctuation">(</span><span class="token builtin">input</span><span class="token punctuation">(</span><span class="token string">"Enter ycordinate for PointB "</span><span class="token punctuation">)</span><span class="token punctuation">)</span>

<span class="token keyword">print</span><span class="token punctuation">(</span><span class="token string">"distance between points"</span><span class="token punctuation">,</span> 
	distance_between<span class="token punctuation">(</span>pointA<span class="token punctuation">,</span> pointB<span class="token punctuation">)</span>
	<span class="token punctuation">)</span>
</code></pre>
<h2 id="sample-output">Sample Output</h2>
<p><img src="https://i.imgur.com/H5xRUay.jpg" alt="out"></p>
<h2 id="documentation">Documentation</h2>
<p><a href="https://github.com/kgisl/pythonFDP/blob/master/docs/README.md#distance_between">distance_between</a> doctstring documentation</p>
<h2 id="cyberdojo-link">CyberDojo link</h2>
<p><a href="http://cyberdojo1.kgfsl.com/kata/edit/Tx2Vqt">http://cyberdojo1.kgfsl.com/kata/edit/Tx2Vqt</a></p>
<h2 id="ppt-presentation">PPT presentation</h2>
<p><a href="%5Bhttps://github.com/kgisl/pythonFDP/blob/master/files/Unit%202%20-%20illustrative%20programs.pdf%5D(https://github.com/kgisl/pythonFDP/blob/master/files/Unit%202%20-%20illustrative%20programs.pdf)">PDF version</a></p>

    </div>
  </div>
</body>

</html>