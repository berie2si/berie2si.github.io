## Website Performance Optimization portfolio project

Your challenge, if you wish to accept it (and we sure hope you will), is to optimize this online portfolio for speed! In particular, optimize the critical rendering path and make this page render as quickly as possible by applying the techniques you've picked up in the [Critical Rendering Path course](https://www.udacity.com/course/ud884).

<br>
<i>Project result can be found : 
minified - http://berie-si.github.io/views/pizza.html
development - http://berie2si.github.io/views/pizza.html</i>
<br>
<i>Page speed score can be tested on : https://developers.google.com/speed/pagespeed/insights/</i>
<br>
<i>GitHub: 
minified - https://github.com/berie-si/berie-si.github.io
development - https://github.com/berie2si/berie2si.github.io
README -  https://github.com/berie2si/berie2si.github.io/blob/master/README.md</i>
<br>

## Notes
1. I inlined CSS into Pizza.html page
2. Google Analytics script has been async'd
3. Resized Images and added version for mobile
4. Followed PSI suggestions to make page more friendly and optimize
5. Reduced pizzas number
6. Caching document.body.scroolTop
7. Caching phase (always 5 values for same scrtop)
8. Caching changePizzaSizes(size) 
9. Caching - move var pizzasDiv out of loop
10. Minified HTML/CSS/JS - http://berie-si.github.io/views/pizza.html
10. pizza.html - adding to .mover 
     -webkit-backface-visibility: hidden;
     -webkit-perspective: 1000; 
11. Minified index.html; inlined CSS into index.html; resized images for index.html


References:
- reading the Piazza forum for P4 and applying steps suggested on the Piazza forum
- applying steps suggested by Google PSI
- applying steps learnt in Udacity course
- studying githubs of following Udacity students:
    Ben Halperin, cch5ng, dawoonC, haopei, kevdonk, uncleoptimus, bennythejudge, cynthia_o_donnel

