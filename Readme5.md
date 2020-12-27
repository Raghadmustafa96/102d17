**The  color  property allows you to specify the color of text inside an element**

You can specify any color in CSS in one of three ways : 

1. rgb values 
These express colors in terms of how much red, green and blue are used to make it up. For example:  rgb(100,100,90)  


1. hex  Codes 
These are six-digit codes that represent the amount of red, green and blue in a color, preceded by a pound or hash # sign.
 For example:  #ee3e80

1. Color names 
There are 147 predefined color names that are recognized by browsers. For example: DarkCyan 



## background-color
CSS treats each HTML element as if it appears in a box, and the background-color property sets the color of the background for that box. 
You can specify your choice of background color in the same three ways you can specify foreground colors: 
*RGB values
*hex code
*color names 

If you do not specify a background color, then the background is transparent. 

`body { background-color: rgb(200,200,200);} h1 { background-color: DarkCyan;}
`

Every color on a computer screen is created by mixing amounts of red, green, and blue. 

Computer monitors are made up of thousands of tiny squares called pixels. 

When the screen is not turned on, it's black because it's not emitting any light. When it's on, each pixel can be a different color, creating a picture. The color of every pixel on the screen is expressed in terms of a mix of red, green, and blue. 


## Contrast


1. high Contrast
Text is easier to read when there is higher contrast between background and however,  then too much contrast can make it harder to read,too


1. low Contrast 
Text is harder to read when there is low contrast between background and foreground colors. A lack of contrast is particularly a problem for those with visual impairments and color blindness. It also affects those with poor monitors and sunlight on their screens. 


1. medium Contrast
 For long spans of text, reducing the contrast a little bit improves readability. You can reduce contrast by using dark gray text on a white background or an off-white text on a dark background.


#### opacity

CSS3 introduces the  opacity property, which allows you to specify  the  opacity  of  an  element and any of its child elements. 
The value is a number between 0.0  and  1.0