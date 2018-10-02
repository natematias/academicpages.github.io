---
creators:
- J. Nathan Matias
date: '2011-07-10'
excerpt: ""
filename: 2012-07-10-doctor-johnson
hosts:
- SwiftKey
image: http://natematias.com/portfolio/images/drjohnson_console.png
subtitle: 
tags:
- project
- nlp
- swiftkey
title: Doctor Johnson
uri: ''
---

<p>Dr. Johnson is a rapid prototyping framework for language predition applications in JRuby. It's loosely based on Rails and Django, but it's more generic than those web-focused frameworks.</p>
<p>I developed it while at <a href="http://www.touchtype-online.com/">TouchType</a>, as part of our initiative to:</p>
<ul><li> Develop quantitative measurements for what constitute good text predictions</li>
<li> Develop qualitative processes for cleaning bad text predictions</li>
<li>  Experiment with and test improvements to the Fluency prediction engine</li>

<li> Prototype web-based language interfaces</li></ul>
<p>I also used Dr. Johnson within the company to help train new employees in test-driven development. By pair programming new products or new features, we would run through small iterations of the larger development process we adopt within the company.</p>
<p>Here are some of the projects I developed using Dr. Johnson:</p>
<p><b>The Prediction Console:</b></p>
<p>A console for interacting with TouchType's <a href="http://www.touchtype-online.com/products/touchtype-fluency-prediction.htm">Fluency</a> library.</p>
<p><b>The Evaluator:</b></p>

<p>A system for generating quantitative scores of statistical language models:</p>
<img width="240" height="174" src="http://natematias.com/portfolio/images/word_prediction_score.png"/> <img width="168" src="http://natematias.com/portfolio/images/overall_prediction_score.png"/>
<p><b>The Generator:</b></p>
<p>A system for generating language models of specific corpora, whether serious (<i>medical language models</i>) or for fun (<i>famous poets, novelists, and performers</i>). The Console screenshot above shows an example of predictions based on William Gibson's novel <a href="http://en.wikipedia.org/wiki/Neuromancer">Neuromancer</a>. I am using these language models for an ongoing research project on famous literary styles. Gibson's work, for example, is famous for what is called an "Eyeball Kick," a term coined by <a href="http://www.allenginsberg.org/">Allen Ginnsberg</a>.</p>
<p><b>FluencyWeb:</b></p>

<p>In progress at the time of writing (Dec 2010), this project merges Dr. Johnson with Rails 3.0 to permit the rapid prototyping of HTML5 language-focused applications.</p>
<p><b>Colour Predictions:</b></p>
<p>This clever extention to Dr. Johnson was made by Douglas Orr, longtime friend and now coworker at TouchType. He modified Dr. Johnson's evaluator to output color-coded text, visually indicating how the library responds in varied language contexts. It's extremely useful for debugging.</p>
<img width="500" src="http://natematias.com/portfolio/images/orr_colour_output.png"/>
