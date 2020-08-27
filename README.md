### align-content
```
where to align a flexible containers items within the flex container


basic possible vals: start, center, space-between, space-around, end
normal val: norml
baseline aligning vals: baseline, first baseline, last baseline
distributed aligning vals: stretch, space-evenly
overflow aligning vals: safe center, unsafe center
global vals: inherit, initial, unset
```

### align-items
```
default alignment or items within the flex container
```

### align-self
```
alignment for selected items within the flex container
```

### animation
```
specify the keyframe-based animation
```

### animation-delay
```
when should the animation start
```

### animation-direction
```
whether or not to play the animation in reverse or no
```

### animation-duration
```
how long to play one cycle of anim val should in s or ms
```

### animation-fill-mode: style of the element when animation is not playing
```css
/* none: no styles applied before or after animation plays
* forwards: apply the style of the last keyframe if forwards then 100% if backwards then 0%
* backwards: apply the style of the first keyframe if forwards then 0% if backwards then 100%
* both: animation will follow the rules of both backwards and forwards
*/
```

### example animation
```css
@keyframes myanim{
0%{background-color: red;}
25%{background-color: green;}
50%{background-color: blue;}
100%{background-color: orange;}
}
/*Remember the 100% or the animation will only display from 0 to 50 and not loop*/

```


### animation-iteration-count
```
how many times to play the animation before stop
```

### animation-name
```
name given to @keyframes defined anim that should be applied to an element
```

### animation-play-state
```
run or pause the anim
```

### backface-visibility
```
do/do not display backside of a tranformed element when facing user
```

### Have multiple background images with specific size and specific repeat
```css
#nelan1{
	background: url(alan_loves2.gif) left top no-repeat, url(alan_loves_compilers.gif) right bottom no-repeat, url(pintos.gif) left top repeat;
	background size: 50px, 130px, auto
}
```

### background-attachment
```
whether the bg image is fixed in the viewport or scroll
```

### background-repeat
```
how the background image is tiled
```

### border-bottom-color
```
color of the bottom border of an element
```

### border-radius
```
how to make an element circular
```

### box-shadow
```
give a container a shadow
```

### flex-direction
```
direction of the flexible items
```

### float example 3 images aligned side by side (width) and place space between them (padding)
```css
.img-container
{
	float: left;
	width: 33.33% /*3 containers use 25% for four, 20% for five ..*/
	padding: 5px;
}
```

## Links
### link styling a ... possible styling of link, hover, visite and active
```css
a:link{
	color: red; /*styling an unvisited link*/
}

a:visited{
	color: purple; /*styling a visted link*/
}

a:hover{
	color: green; /*When I hover my mouse over the link the hyperlink will turn green*/
}

a: active{
	color: blue; /*The color the hyperlink changes to the moment I press it*/
}
```




## Lists Props
### list-style: display style for a list and list element(li)
```css
ul{
	list-style: /*list-style-type list-style-position:positionofmarker list-style-image*/
	list-style: disc inside url("images/alan568372.png");
}
```

### margin: space surrounding element use when move an element u,d,l,r and if width: fixed
to center
```css
width: fixed;
/*to center element horizontally assign the margin value to auto*/
```

### opacity: how transparent do you want the element 0: fully transparent 1: fully opaque
```css
img{
	opacity: 0.25;
}
```

## Video Sizing
### Take up all the available space
```css
video{
	width: 100%;/*Take up all the available space*/
	height: auto;
}
```

### Scale to size
```css
video{
	max-width: 100%;
	height: auto;
}
```



### padding: space in between an element, edge of the container, border
```css
padding: top, right bottom left;
padding: top, rightleft, bottom;
padding: topbottom, rightlef;
padding-bottom: ; 
padding-top: ;
padding-left: ;
padding-right ;
```


### Text-Styling

#### Direction: right to left(rtl), left to right(ltr), initial, inherit
```css
p{
	direction: rtl;
}
```

#### Tab-Size: length of tab character ..... integer(#of spaces) | length(width of tab) | initial(default) | inherit
```css
A5265683S2{
	-moz-tab-size: 3; /*Firefox*/
	-o-tab-size: 3; /*Opera*/
	tab-size: 3; /*Any other browser*/
}
```

### Text-decoration: none, underline, overline, line-through, blink, 2 or more vals, iniial, inherit
```css
a{
	text-decoration: overline;
}
```

### Word-Break: normal, break-all, keep-all, initial, inherit ... how to break lines within words
```css
p{
	width: 150px;
	word-break: break-all;
}
```

### Display: box and effect on layout content takes effect on formatted structure
```
Display vals: inline|block|contents|flex|flow|flow-root|grid|inline-block
| inline-flex| inline-grid | inline-table | list-item | run-in | table | table-caption |
table-column-group| table-header-group | table-footer-group | table-row-group | table-cell|
|table-column | table-row | none| initial | inherit|
```

```css
h1{
display: flex;
}
```

### Word Spacing: length | normal | initial inherit ... set space between words in text
possible vals:
```css
	/*possible vals: length(integer), normal, initial inherit*/
	word-spacing: 50px;

```


![p1](https://user-images.githubusercontent.com/31806568/90336834-5927d700-dfd6-11ea-86ed-835a669ec813.png)

![p2](https://user-images.githubusercontent.com/31806568/90336837-5c22c780-dfd6-11ea-817a-8ab2729bd7ff.png)

![p3](https://user-images.githubusercontent.com/31806568/90336839-5f1db800-dfd6-11ea-8ae3-40211434513a.png)

![p4](https://user-images.githubusercontent.com/31806568/90336843-61801200-dfd6-11ea-9826-d08f08e820a3.png)
