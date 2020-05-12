====================================
|| Technical Documentation Page
====================================

------------
Design
------------

I got the idea for the colors from the music video for the song 'RITMO'...there is a scene
where the backdrops is a cool sunset, though with a lot of blue shades on the perimeter, as well
as some yellow-oranges and purples...

Seeing as how I chose three.js for this project, I want to add a cool hover animation
for the sidebar menu. That, and I will use this section to create some 3D animations.




---------------
Log
---------------

Learned about using <article> elements for 'repeated' pieces of composition on a page that are
intended to be reusable.

I found that to display HTML as plain text you can just replace the '<' and '>' with '&lt;'
and '&gt;' respectively. Tedious, though it gets the job done.

-04/27/2020

'padding: 0' on '#navbar ul' got rid of the problem I had where the sidebar was offset to the right by a significant
amount.

-04/29/2020

Hmm, I'm literally 'untabbing' the code samples in order to get them to line up properly on the page...though I know I saw something about 'tab'
in either the official three.js website code and/or the fCC example page code...was it some CSS attribute that adjusted how the spaces of 'tabbing' behave?
Perhaps there is something here that makes it so that I don't have to 'unindent' the code samples and have it be out of the natural 'indent order'
in the HTML...

-05/02/2020

Hah! I finally figured out how to get the 'navheader' to be sticky while the nav UL scrolls! I was a combo
of position, width, and margin! And z-index and background color. I just needed to account for the spacing of the 
elements...now that I've written this out, it seems silly that I didn't think of this earlier! But alas, 
we live and we learn.

I commented out all of the <pre> elements in order for 'white-space: pre-wrap' to actually work when applied to the
<code> elements.

So far, I haven't found a solution that works in indenting text that 'wraps'. Specifically, I'm trying to target the text
inside of the <code> elements. At smaller screen sizes, the lines breaks and the indentation gets lost.

-05/11/2020