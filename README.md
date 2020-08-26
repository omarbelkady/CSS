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
