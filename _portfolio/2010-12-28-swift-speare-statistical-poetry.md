---
creators:
- J. Nathan Matias
date: '2010-12-28'
excerpt: Shakespeare with fewer Monkeys and Typewriters
filename: 2010-12-28-swift-speare-statistical-poetry
hosts:
- SwiftKey
image: http://farm6.staticflickr.com/5261/5644317701_c3ff461fb8_n.jpg
subtitle: Shakespeare with fewer Monkeys and Typewriters
tags:
- project
title: Swift-Speare Statistical Poetry
uri: http://www.swiftkey.net/en/blog/learning-to-write-like-shakespeare/
---

<p>Inspired partly by JM Coetzee's statistical work on Beckett's writing style, Swift-Speare is a set of experiments in machine-learning-assisted poetry composition using the <a href="../Business/DrJohnsonARapidPrototypi.html">Dr. Johnson</a> prototyping framework I designed for <a href="http://swiftkey.net">SwiftKey</a>.</p>
<p>I am currently compiling a collection of poetry in the style of Shakesepeare, Milton, Longfellow, and others with very distinctive styles. I am also applying these methods to novelists with distinctive styles, such as Joseph Conrad, William Gibson, Russell Hoban, and James Joyce.s</p>
<p><b>Step one</b>: create a statistical model of the sonnets.</p>
<p><b>Step two</b>: apply our predictive text algorithm interactively as I compose new writings in the style of famous writers.</p>

<p>Here is the beginning of a poem, based on a statistical model of Shakespeare's sonnets (showing the associated predictions):</p>
<pre>
  Let base clouds stir the world's enshrouded tears
  Which have no astronomy to be assail'd
  Thus in thy fair appearance lay thy buried fears
  Whose uncovering gaze my fond perception failed
  &gt; And in <b>|</b>
      [<b>my</b>, 0.000261165812844411]
      [<b>quest</b>, 0.000130582906422205]
      [<b>their</b>, 0.000130582906422205]
      [<b>possession</b>, 0.000130582906422205]
      [<b>hue</b>, 0.000130582906422205]
      [<b>the</b>, 2.94613328151172e-05]
</pre>

<p><a href="http://en.wikipedia.org/wiki/Beowulf"><b>Beowulf</b></a>:</p>
<pre>
  Sing sweetly of battle-borne ages
  of fell foes infernal, and the king
  whose woe endured hailing rage
  and the death of exiled heroes.
</pre>

<p><a href="http://en.wikipedia.org/wiki/An_Essay_on_Criticism"><b>Denham and Waller Combined</b></a>:</p>
<pre>  
  Since nature gave the world to all our hopes
  and beauty gives to us the youthful pleasures still;
  No weariness I'll yield to all man's gain
  Nor would I tell those powers above to rage.
  The wise counsels of age shall have the spoil
  of art, and elephant, and crown above
  &gt; when I have seen the <b>|</b>
      [<b>Muses</b>, 5.35540220880648e-06]
      [<b>Earl</b>, 4.53149414170184e-06]
      [<b>Queen</b>, 3.70758630197088e-06]
      [<b>Greeks</b>, 3.29563226841856e-06]
      [<b>British</b>, 3.29563226841856e-06]
      [<b>English</b>, 2.88367823486624e-06]
</pre>

<p><b>Justin Bieber</b>:</p>
<pre>
  I need somebody to be reality
  The only thing that makes me crazy is your breath
  and no matter what we've done whatever it could be
  once in a star, once in my heart
  &gt; Dancing close, baby <b>|</b>
      [<b>,</b>, 4.57498754258268e-05]
      [<b>oooh</b>, 1.71562023751903e-05]
      [<b>nooo</b>, 8.57810118759517e-06]
      [<b>doll</b>, 2.85936721411417e-06]
      [<b>know</b>, 2.85936721411417e-06]
      [<b>yeah</b>, 1.42968360705709e-06]

  yeah girl
  yeah girl
  girl I swear
  girl I know
  yeah yeah this beat rocks
  yeah girl
</pre>