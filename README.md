# vue-3-text-isvisible
Using Vue 3 text in div visible (not) visible,

I wanted to encourage myself to document some information in using Vue 3.

In this case, to use a click event directive to toggle a div text content as visible or not.

In addition, I like to keep the responsive part of the business correct.

I use Firefox InspectQ (Responsive Design Mode) toggle to resize page width for cell phone size render.

Note that there is an unwanted text overflow in the second box due to the 2em font size.

As a corollary, 

this text overflow observation maybe considered as a method of testing to sort-out visual anomalies; thus, reasons for code revisions.

![text-in-box](https://user-images.githubusercontent.com/89032071/167033672-8abaf112-8619-4055-a1f1-d070184b6007.png)

The image was created with a screenshot of cell phone size.

I attached the two CSS properties for viewing the render.

The point to remember is that changes can take place on a page, and a larger font size might overflow the width definition of div property.

Therefore,

use caution when defining the best way to render text that will not produce an overflow condition.





