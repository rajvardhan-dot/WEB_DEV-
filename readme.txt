alt+shift+down arrow: copy content to down
alt press and select where u want cursor
h1 style: backgrounf color>: INLINE CSS h1 tag hain and style ek attribute hain
#TABLE
rowspan
colspa
thead, tfoot , tbody

video6:
SEO(SEARCH ENGINE OPTIMIZATION)
CORE WEB VITALS:
        CLS:CUMULATIVE LAYOUT shift, PAGE LOAD HOTE HOTE KITNA SHIFT HO RHA HAIN
        LCP:LARGEST CONTENT PAINT: render time of largest image in the web PAGE(best it should be 2.5sec)
        FID: first input delay:input kitni der me process ho rha hain(100sec is good)
* Lighthouse concept to check the performance of the page or any improvement required(check in inspect)

VIDEO7:

FORMS
    get and post rqst

INPUT TAGS

VIDEO8:

Inline: take required width(anchor tag)
block element: take complete  width(ex-> para)(puri width)

Video9:
id & classes

id will be unique
classs can be same
(.)-> use to access classs
(#)-> use to acces id 
id and classs are attributes

Video10;
video , audio , Media
preload important
svg:
pre
<iframe>: other websites ko embedd krne ke liye use hota hain

video14:
HTML Entities:enable u to display character that is reserverd like p tag body tag
&nbsp->space between words

quotation tag: blockquote , q TAGS 



@@@@CSS:

Element selector (p)
class selector ( using (.))
ID (# USING U CAN CHANGE ,ID IS UNIQUE)

pseudo-class selector:
a:hover{
    color: black
}

#multiple selector or grouping selector

universal selector
nested selector
attribute selector

#how to add styling to HTML

Inline (apply on opening tag) e.g para
internal(style tag)(head tag ke andar)
external(sheet link krte hain)

#specifity: jab color class krte hain toh specifity batayega konsa pick hoga konsa nhi
     #!important keyword(1)
     #Inline CSS(2)
     #ID(3)
     #class(4)
     #tag(5)
     
     
    parameters are used to select content of the web page 

****BOX MODEL IN CSS:***

Every element on page is rectangular box and may have width , height , borders , margin, padding
Margin: border ke outer part ko margin
padding: content and border ke beech ka part (TOP , RIGHT , BOTTOM , LEFT)
box-sizing- isse content size chhota ho jayega aur , padding dalne se box ka size change nahi hoga aur content ka size same rhega bs box inc hoga


*****Colors in CSS:
   #top 3 important
 Hexadecimal(#111111 0-f tk value staring 2 red , green , blue)
 RGB Colors(_,_,_ - red , green , blue)
 Predefined/cross-browser color names( )
 RGBA Colors
 HSL Colors
 HSLA Colors

*****Units in css:
 1 absolute Units(mm, cm , in ,px) fixed size everywhere , pixel density more means more clear pic and good pic , smooth
 2 percentage unit(width:10% , height:20%)
 3 relative unit
      1.relative to font size(em(relative to parent size, 1em*parent div size) , rem(relative to root, HTML config ke according)) 
      2.related to Document(relative to viewport- vw: width of viewport , vh: height of viewport)

  
iNTERVIEW QUESTION:
    DIFFERNECE BETWEEN 1% AND 1VW:
        ans: Use 1% when you need an element’s size to be a percentage of its parent element. This is typical in nested layouts where child elements need to resize based on their container.
             Use 1vw when you need an element’s size to be a percentage of the viewport width. This is typical for creating full-screen sections, responsive typography, and layouts that need to adapt to the viewport size directly.

Float tag is used to shift box left right top and bottom

*****CSS GRADIENTS:

(by default gradient top to bottom hota hain)
      css gradient let you display smooth transistion between two or more specified colors.
      linear gradient(goes down/up/left/right/diagonally)
      Radial gradient(defined by their center)
      conic gradient(rotated around a center point)
    * Linear Gradient:
    A linear gradient in CSS is a way to create a smooth transition between two or more specified colors along a straight line(to right , to left , to bottom , to up , to bottom left , to bottom right)
           *Default direction
           *specific direction
           *using angles
           *using transparency by giving 4 values in RGBA
           background image sbse last wali ki priority jada hoti hain

    * Radial gradient: 
          it is defined by its center.
    * conic gradient:
        gradient with color transistion rotated around a center point
     

******Shadow effect
Text-Shadow(text pe shadow apply krne ke liye)(A-Horizontal , B-vertical , C-blur , colors  )
spread radius:  ? 
Box-Shadow(box pe shadow apply krne ke liye)(text ka color sahdow ka color hota hain)(by giving negative value we can change the direction from bottom side to top side)

*******CSS DIMENSTION PROPERTIES:
    width
    height
    min-height
    min-width
    max-height(agar content min size se bada hain toh content ka size bhi badh jayega apne aap)
    max-width

*****Overflow Property:
    Visible(overflow content visible hoga)
    Hidden (content hidden hoga)
    Scroll(overflow content scroll hoga kr dikhega )
    Auto(chhote content me visible and bade content me scroll)
    overflow is the shorthand property of overflow.x and overflow.y

*****CSS Position property
     *Static(by default static  )
     *relative(relative to normal position) left right top bottom
     *fixed(will be fixed in one posi)
     *absolute(ancestor ke repect me, image overlap krne me use hota hain)
     *sticky(wil fix after scrolling) toggle between two position relative and fixed

     Display- inline block;  matlab box ko ek line me align  kara do

****CSS-2D transforms
     *translate()
     *rotate()
     *scaleX(ZOOM ke liye use hota hain) scale(2,3) - first will be horizontal and second will  be vertical 
     *scaleY()
     *skewX()
     *skewY()
     *skew(tilt ho jayega by some angle )
     *matrix( single property iska use krke top ki sari property apply kr skte hai aap)
     
****CSS flex Box:
    Layout model:  space distribution
                   align capability
    flex box is a type of container 
         parent container - > child/ flex items
         main axis -horizontal
         cross-vertical
        
        flex container property:

            flex-direction: box ki direction decide krta hain row , row-reverse , col , col-reverse

            flex-wrap: boxes ko squeeze krne ki jagah unko neeche shift kr dega (default value-no wrap , wrap-reverse , wrap)

            flex-flow(shorthand notaion, wrap and direction ek saath use kr skte hain =>  flex flow: row wrap)

            justify-content(Horizontal) main axis ke around 
                     -flex-start(start me Aa jayegi chile box)
                     -flex-end(end me chake jayegi sari boxes)
                     -center(all child box will be in the center)
                     -space-around(space ke saath distribute ho jayege boxes sare)
                     -space-evenly(equal space)
                     -space-between(proper spacing between items - 2 in corner rest in equal distribution)
                *gap:10px(shorthand notation -> row-gap , col-gap) ->to generate gap between boxes

            align-items(by default stretch hoti hain) vertical axis
                   -flex-start(vertical axis ke according element top pe rhege)
                   -flex-end(element end me rhege)
                   -center(element in center)
                   -stretch - box parent container ke barabar ho jayegi
                   -baseline(box ka content ek line pe hoga)

            align-content: iska use krke boxex ke beech ka gap remove jo jayega
                   -flex-start
                   -flex-end
                   -center
                   -space-between
                   -space around
                   -space-evenly



flex item property:
            order(child box ka order change krna chahta hu)
            flex-grow(by default value is 0 , flex-grow se box ka size increase ho jata hain )
            flex-shrink(by default value 1 hoti hain , responsive website ke liye isse ye pta chalega ki konsa box chhota hoga aur konsa nahi )
            flex-basis(Width dene ke liye use hota hain , width and flex-basis dono ka kaam same hota hain lagbhag but flex-basis se sara content visible hoga and sirf width se content cut ho jayega )
            flex(shirthand notation hain , upar ki 4 property handle kr skte ho)
            align-self(indivisual boxes ki property set krne ke liye use hota hain, align-self: stretch or flex-end )

    

*****CSS GRID*****
CSS grid(Two dimension layout , it keep content in the form of row and column with gap (row gap , and column gap)) ->flex box how content will flow, grid is simple Layout.
flex box is relative to content and grid is about simple layout creation
flex box is 1D , grid is 2D

line based placement:
grid-column-start
grid-column-end
grid-row-start
grid-row-end
shirthand PROPERTIES: grid-row , grid-column , grid area

***Some more PROPERTIES
   justify-content (start , end , center , sapce evenly , space around ,  space between)
   justify content
   justify self
   justify item

   align item 
   align self
   place self
   place item 

******Grids and responsiveness:
responsive desgin means different different device me website should be looks good  , adjustable in every screen 
grid area:row start/column start / row end / col end -> shorthand properties to include, grid-row-start-grid-col-start , grid-row-end , grid-col-end.

grid template area: grid template areas is the property used to name the rows and columns of a gridand to set the layout 

    Display: grid;
    grid-template-columns: 200px 400px;
    grid-template-rows: 30px 500px 30px;

    grid-template-areas: 
    "hd hd"
    "side main"
    "ft ft";

Advance grid concepts:
 (fraction unit) fr unit(1fr, 1fr , 1fr three equal size column) repeat(4 , 1fr)
      Repeat function: repeat(4, 1fr)
      Grid-auto-rows:minmax() -> when we have unknown number of rows , jab rows ka pta na ho toh Auto ka use krte hain , minmax batata hain minimum and maximum rows
      use grid auto rows to assign rows and col automatically according to the compactbility of website like facebook rows and cols will automatically will increase and decrease

    grid-auto-rows: minmax(100px , auto);
    grid-template-columns: repeat(4,1fr);

******Grid Properties:
    -justify-content(Horizontal axis ke along kaise data rakhte hain (start , end , center , sapce evenly , space around ,  space between))
    -Align-content(row ke beech ka spacing , space-between , space evenly , space-around  , )
    -justify-item ()
    -align-items(vertical axis, cross axis pe kaam krta hain)(start , end , baseline(start) , stretch )
    -justify-self(same like justify content but this is use for child component)
    -align-self(same like align item but this is use for child item) vertical axis ke along 
    -place-items(shorthand notation , justify and align property set krne ke liye  )
    -place-self(justify self and align self ke liye  )
place-content: center can be use in place of justify content and align-content to keep content in the center


justify-content is use to shift the box with from one position to other position without changeing the shape and size of the box
justify-item will change the width of the box according to the content
justify-self(particular box ke content me change lane ke liye use krte hain)

*************ALWAYS USE % , REM , EM , VW ,VH to set width and height********

********MEDIA Queries
 different different device pe using breakpoint apne layout kp handle krte hain 
 iska use krke hm different style use krte hai different device mein 
 
  It's like giving the website instructions to change its appearance or layout to be more user-friendly whether you're viewing it on a phone, tablet, or computer. 
  For example, a media query might tell the website to display a single-column layout on a small phone screen and a multi-column layout on a larger desktop screen.
- add media queries at the end in css file section 
-@media(contdition)
@media(max-width: 400px){ // if pixel will go below 400px then do changes in the container
    .container{
        grid-gap:100px;
    }
}

@media(max-width: 350px){
    .container{
        grid-template-rows: 30px 1fr 1fr 30px;
        grid-template-col: 1fr;

        grid-gap:2px;

        grid-template-areas:
        "hd"
        "side"
        "main"
        "ft";
    }
}


******Nested Grids:
nesting CSS grid is simple can be done simply using the display: grid rules for both a parent and child element
.container{
    display:grid;
    //...
}

#one{
    display: grid
}


****Always use universal selector to set margin=0 , padding=0 , box-sizing: border-box********

