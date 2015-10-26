# code-challenge-two
#### Litmus Newsletter Recreation

This email project mirrors the layout and styles from this <a href="https://dribbble.com/shots/897840-December-Newsletter/attachments/97970" target="_blank">Litmus Email Newsletter</a> with different iconography. This design features modular table segments that create each colored section and a 2 to 1 column responsive layout. The latter is accomplished with dynamically stacking elements that display 2-up or 1-up depending on the available viewing area. It does not rely on CSS media queries which would not be supported in Gmail. 

<s>I had trouble pushing my Litmus screenshots to this repository, so I hosted them <a href="https://www.dropbox.com/sh/y2erihslguvq0j2/AACfKbOcHbU4RsvC5DtuyB-Ta?dl=0&s=so" target="_blank">here on Dropbox</a>.</s>

Update: 10/26</br>
You can view the latest Litmus screenshots <a href="https://github.com/Chuabacca/code-challenge-two/tree/master/litmus-screenshots" target="_blank">here</a>.

#### The following are the highlights of this hand-coded design.
<ul>
<li>Responsive design with dynamically stacking elements.</li>
<li>Modular table layout - each section is not nested in a containing table.</li>
<li>Header section with logo, preview text, Twitter and mail icons.</li>
<li>HTML buttons that render well in Outlook tests without the use of button generators and Vector Markup Language.</li>
<li>Progressive enhancement with rounded corners displayed when supported.</li>
</ul>

#### Unresolved issues
<ul>
<li>Displaying as one-column design on the iPad. Need to do more research on the way iOS handles table widths.</li>
<li><s>Layout spacing issues in the Chewbacca segment in Outlook. May be caused by the way the headline text is nested in top section. Possible solution is to separate the headline text into its own discrete table module.</s></li>
<li>Update: 10/26
  <ul>
    <li>I was able to fix the issue with the header not being centered in some versions of Outlook by nesting it in its own table.</li> 
    <li>I was able to fix the spacing isues by moving the padding to the individual column elements instead of placing it in the colum  container. Outlook renders this better.</li>
  </ul>
</li>
<li>I was unable to achieve the uneven columns (elements containing text are wider than elements containing images) and still keep things aligned when the elements stacked in a single column. More experimentation is needed with stacking and centering table elements.</li>
</ul>

