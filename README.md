# Selector Master
+ `div:first-child`[first child](templates/1.html)
+ `div:last-child`[last child](templates/2.html)
+ `#home li:nth-child(1)`[nth child(1)](templates/3.html)
+ `#home li:nth-child(5)`[nth child(5)](templates/4.html)
+ `#app::before`[before](templates/5.html)
+ `#app::after`[after](templates/6.html)
+ `.list nav ul li ul li a span`[multiple ascendants](templates/7.html)
+ `.list > li > span`[child element](templates/8.html)
+ `nav ~ p`[p element preceded by nav](templates/9.html)
+ `footer *`[all elements inside](templates/10.html)
+ `p:first-of-type`[first element of given type in a container](templates/11.html)
+ `a:link`[non visited](templates/12.html)
+ `a:hover`[hover over](templates/19.html)
+ `li:not(.active)`[every li except active class](templates/13.html)
+ `li:nth-last-of-type(3)`[last 3 li](templates/14.html)
+ `li:nth-of-type(2)`[first 2 li](templates/15.html)
+ `a[href="http://www.google.pl"]`[specific value attribute selector](templates/16.html)
+ `a[title]`[just an atribute selector](templates/17.html)
+ `p + p` [adjacent sibling](templates/18.html)
+ `p::first-line`[first line in paragraph](templates/20.html)
+ `a:visited`[visited anchors](templates/21.html)
+ `a:active`[very short behaviour after clicked anchor](templates/22.html)
+ `p::first-letter`[first letter of paragraphs](templates/23.html)
+ `::selection`[selected for whole document](templates/24.html)
+ `div !> div#abc`[div parent of id abc div](templates/25.html)
+ `input[type=checkbox]:checked + label`[targeting label after checkbox when checked](templates/26.html)
+ `a:hover`[hover over](templates/19.html)
+ `:required`[any element with required attribute](templates/27.html)
+ `*` [literally all elements, mostly used to reset/normalize](templates/28.html)
+ `div * p`[paragraph that has div ancestor, but not direct parent](templates/29.html)
+ `div:empty`[divs that are empty and we want to hide they could interefere with layout](templates/30.html)
