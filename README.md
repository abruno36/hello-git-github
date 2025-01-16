Heading
=======

Sub-heading
-----------

# Alternative heading

## Alternative sub-heading

Paragraphs are separated 
by a blank line.

Two spaces at the end of a line  
produce a line break.
</syntaxhighlight>
|
<syntaxhighlight lang="html">
<h1>Heading</h1>

<h2>Sub-heading</h2>

<h1>Alternative heading</h1>

<h2>Alternative sub-heading</h2>

<p>Paragraphs are separated
by a blank line.</p>

<p>Two spaces at the end of a line<br />
produce a line break.</p>
</syntaxhighlight>
|<div style="overflow: hidden; page-break-after: avoid;
font-size: 1.8em; font-family: Georgia,Times,serif; margin-top: 1em; margin-bottom: 0.25em; line-height: 1.3; padding: 0; border-bottom: 1px solid #AAAAAA;>Heading</div>

<div style="overflow: hidden; page-break-after: avoid;
font-size: 1.5em; font-family: Georgia,Times,serif; margin-top: 1em; margin-bottom: 0.25em; line-height: 1.3; padding: 0; border-bottom: 1px solid #AAAAAA;>Sub-heading</div>

<div style="overflow: hidden; page-break-after: avoid;
font-size: 1.8em; font-family: Georgia,Times,serif; margin-top: 1em; margin-bottom: 0.25em; line-height: 1.3; padding: 0; border-bottom: 1px solid #AAAAAA;>Alternative heading</div>

<div style="overflow: hidden; page-break-after: avoid;
font-size: 1.5em; font-family: Georgia,Times,serif; margin-top: 1em; margin-bottom: 0.25em; line-height: 1.3; padding: 0; border-bottom: 1px solid #AAAAAA;>Alternative sub-heading</div>

Paragraphs are separated
by a blank line.

Two spaces at the end of a line<br />
produce a line break.

|-
|<syntaxhighlight lang="md">Text attributes _italic_, **bold**, `monospace`.

Horizontal rule:

---

</syntaxhighlight>
|
<syntaxhighlight lang="html"><p>Text attributes <em>italic</em>, <strong>bold</strong>, <code>monospace</code>.</p>

<p>Horizontal rule:</p>

<hr />

</syntaxhighlight>
|Text attributes ''italic'', '''bold''', <code>monospace</code>.</p>

Horizontal rule:

<hr />

|-
|<syntaxhighlight lang="md">
Bullet lists nested within numbered list:

  1. fruits
     * apple
     * banana
  2. vegetables
     - carrot
     - broccoli ONE - normal
     - broccoli TWO - ninja
  
</syntaxhighlight>
|
<syntaxhighlight lang="html"><p>Bullet lists nested within numbered list:</p>

<ol>
  <li>fruits <ul>
      <li>apple</li>
      <li>banana</li>
  </ul></li>
  <li>vegetables <ul>
      <li>carrot</li>
      <li>broccoli</li>
  </ul></li>
</ol>

</syntaxhighlight>
|Bullet lists nested within numbered list:

# fruits
#* apple
#* banana
# vegetables
#* carrot
#* broccoli one

|-
|<syntaxhighlight lang="md">A [link](http://example.com).

![Image](Icon-pictures.png "icon")

> Markdown uses email-style
characters for blockquoting.
>
> Multiple paragraphs need to be prepended individually.

Most inline <abbr title="Hypertext Markup Language">HTML</abbr> tags are supported.
</syntaxhighlight>
|
<syntaxhighlight lang="html"><p>A <a href="http://example.com">link</a>.</p>

<p><img alt="Image" title="icon" src="Icon-pictures.png" /></p>

<blockquote>
<p>Markdown uses email-style characters for blockquoting.</p>
<p>Multiple paragraphs need to be prepended individually.</p>
</blockquote>

<p>Most inline <abbr title="Hypertext Markup Language">HTML</abbr> tags are supported.</p>

</syntaxhighlight>
|A [http://example.com/ link].

[[File:Icon-pictures.png|alt=Image|link=|icon]]

<blockquote>
Markdown uses email-style characters for blockquoting.

Multiple paragraphs need to be prepended individually.
</blockquote>

Most inline <abbr title="Hypertext Markup Language">HTML</abbr> tags are supported.

<!-- Spare row markup
|-
|<syntaxhighlight lang="md">m
</syntaxhighlight>
|
<syntaxhighlight lang="html">h
</syntaxhighlight>
|end
 -->
|}
