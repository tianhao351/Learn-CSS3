# css secrets

## 1.background-clip
### I.example
1. [background-clip](http://www.w3school.com.cn/cssref/pr_background-clip.asp)
2. [example](C:/Users/DELOVEPER---1/Desktop/css%20secrets/01.html)

### II.key point
1. background-clip
```
background-clip determines the background painting area, which determines the area within which the background is painted. The syntax of the property is given with


‘border-box’
The background is painted within (clipped to) the border box.
‘padding-box’
The background is painted within (clipped to) the padding box.
‘content-box’
The background is painted within (clipped to) the content box.

```








---
## 2. Striped-background
### I.Example
[striped-background](http://dabblet.com/gist/119dbf7f0c76dba7b7ee/)

[vertical](http://dabblet.com/gist/1b4983062fd2b4d7e60e)


[degre-stripes](http://dabblet.com/gist/5646121210b0c99c94a7)


[subtle-stripes](http://dabblet.com/gist/aa50d296a8ec07cf7334)



### II.Keypoints
1.[Gradients](http://www.runoob.com/css3/css3-gradients.html/)

```
    "%" is using to point where the color stop
```
2.45 degree and 4 stripes
```
background: linear-gradient(45deg, 
              #fb3 25%, #58a 0, #58a 50%,
              #fb3 0, #fb3 75%, #58a 0);
background-size: 50px 50px;
```

3.[css gradient](http://www.cnblogs.com/lhb25/archive/2013/01/30/css3-linear-gradient.html)

### III. CSS Standard
1. “If a color stop has a position that is less than the specified position of any color stop before it in the list, set its position to be equal to the largest specified position of any color stop before it.” — CSS Images Level 3(w3.org/TR/css3-images)

2. “If multiple color stops have the same position, they produce an infinites- imal transition from the one specified first in the rule to the one specified last. In effect, the color suddenly changes at that position rather than smoothly transitioning.” — CSS Image Values Level3(w3.org/TR/css3-images)




---
# 3. parallelogram

## I.Example
[button](http://dabblet.com/gist/e1f72639c34a5578dda3)

## II.Key Points
1. [position ](http://www.w3school.com.cn/cssref/pr_class_position.asp)

2. [display ](http://www.w3school.com.cn/cssref/pr_class_display.asp)

3. pseudo-element ：
we can use a pseudo-element to apply all styling to (back- grounds, borders, etc.), and then transform that . Because our content is not contained in the pseudo-element, it is not affected by the transforma- tion. Let’s try to use this technique to style a link in the same way as in the previous section. We need our pseudo-element box to remain flexible and automatically inherit the dimensions of its parent, even when they are determined by its contents. An easy way to do that is to apply position: relative to the parent, position: absolute to the generated content, and set all off- sets to zero so that it stretches horizontally and vertically to the size of its parent.




---
## 4.Diamond images
### I.Examples
[link](http://dabblet.com/gist/c62456fed36a524b8273)

### II.Key Points
[css3:clip-path](http://www.w3cplus.com/css3/using-making-sense-of-clip-path.html)


---
## 5.Cutout corners
### I.Example
[link](http://dabblet.com/gist/2937c990d6bfad274740)
[link](http://dabblet.com/gist/24484257bc6cf7076a8e)

---

## 6.filter
### Key Points
#### 1.box-shadow/drop-shadow
[compare](http://www.w3cplus.com/css3/ten-effects-with-css3-filter)
#### 2.filter
[filter](http://www.w3cplus.com/css3/ten-effects-with-css3-filter)
- grayscale灰度
- sepia褐色（求专业指点翻译）
- saturate饱和度
- hue-rotate色相旋转
- invert反色
- opacity透明度
- brightness亮度
- contrast对比度
- blur模糊
- drop-shadow阴影
### Example
[link](http://dabblet.com/gist/b338c9940a31b727b7a9)

[background-blend-mode](http://www.w3cplus.com/css3/basics-css-blend-modes.html)