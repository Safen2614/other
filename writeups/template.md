# Process Writeup

## Name: Safe Nasher 
## Course: sep 10
## Period: 3 
## Concept: Basic HTML 
### Context
Im learning HTML in the SEP program we are learning how to put context on your page. I think that coding is annoying as of right now but thats because Im in the learning zone and it will be better the longer I keep coding. The first code I ever saw when I was a young lad and I did inspect and delated some code to see what would happen. At the end I just deleted everything.  

### Process 

In my SEP class I am learning how to make websites. I learned about a elements herf and more. But sometimes I get stuck like the FreeCodeCamp. I think I was stuck on the "Link to External Pages with Anchor Elements" I kept on looking at one line of code but when I just look at all of the code because looking at one might not even be the problem and theres somehting you did at some other line of code that you messed up. The mistake was that I copy it on top and I forgot about it. also when they just told as to nest it without showing it to us that was hard. When I made it to class and val went up and coded when she did nested then I understand it better on how to do nest. When I took the check in I got this question wrong "Which is the correct syntax for making an image a clickable link? (assume "#" refers to proper URLs)" I put 
```<img href="#"><a src="#"></img>``` which was wrong the right one was ```<a href="#"><img src="#"></a>```
My other moment was when I was on "Nest an Anchor Element within a Paragraph" what I had to do was to remove the ```target```the mistake was that I also didnt delte the other actor elemt and forgot the closing tag. I even tried to look up why ti wasn't working and it still didnt see it. I need to work on look at EVERYTHING in my code I keep being fixed on one thing and not step back and look at everything. this was my code before 
~~~<h2>CatPhotoApp</h2>
<main>

  <a href="https://www.freecatphotoapp.com" target="_blank">cat photos</a>

  <img src="https://cdn.freecodecamp.org/curriculum/cat-photo-app/relaxing-cat.jpg" alt="A cute orange cat lying on its back.">
<p>View more
  <a href="https://www.freecatphotoapp.com" target="_blank">cat photos<a>
  </p>
  <p>Kitty ipsum dolor sit amet, shed everywhere shed everywhere stretching attack your ankles chase the red dot, hairball run catnip eat the grass sniff.</p>
  <p>Purr jump eat the grass rip the couch scratched sunbathe, shed everywhere rip the couch sleep in the sink fluffy fur catnip scratched.</p>
</main>
~~~
This is when I fixed it 
~~~
<h2>CatPhotoApp</h2>
<main>


  <img src="https://cdn.freecodecamp.org/curriculum/cat-photo-app/relaxing-cat.jpg" alt="A cute orange cat lying on its back.">
<p>View more
  <a href="https://www.freecatphotoapp.com" target="_blank">cat photos</a>
  </p>
  <p>Kitty ipsum dolor sit amet, shed everywhere shed everywhere stretching attack your ankles chase the red dot, hairball run catnip eat the grass sniff.</p>
  <p>Purr jump eat the grass rip the couch scratched sunbathe, shed everywhere rip the couch sleep in the sink fluffy fur catnip scratched.</p>
</main>
~~~
### explaining the code
the a element is being the used as the arcter element is the strt to making a link. the p is to add text before the a element (view more) href is to be used in the a element to put a link to another website. the target element is used for where to open the link. then add the text cat photos for free code camp then add the closing tags /a and /p.

* Tip if you get stuck read the reread the WHOLE CODE.
* To create an internal link, you assign a links href attribute to a hash symbol # plus the value of the id attribute for the element that you want to internally link to, usually farther down the page. You then need to add the same id attribute to the element you are linking to. An id is an attribute that uniquely describes an element. 

*To make a word a link do this  
```<p> im a paragraph <a href=#>im a link to nowhere</p></a>```
*A (anchor) elements can also be used to create internal links to jump to different sections within a webpage.
### example
~~~<h2>CatPhotoApp</h2>
<main>

  <a href="#footer">Jump to Bottom</a>

  <img src="https://cdn.freecodecamp.org/curriculum/cat-photo-app/relaxing-cat.jpg" alt="A cute orange cat lying on its back.">

  <p>Kitty ipsum dolor sit amet, shed everywhere shed everywhere stretching attack your ankles chase the red dot, hairball run catnip eat the grass sniff. Purr jump eat the grass rip the couch scratched sunbathe, shed everywhere rip the couch sleep in the sink fluffy fur catnip scratched. Kitty ipsum dolor sit amet, shed everywhere shed everywhere stretching attack your ankles chase the red dot, hairball run catnip eat the grass sniff.</p>
  <p>Purr jump eat the grass rip the couch scratched sunbathe, shed everywhere rip the couch sleep in the sink fluffy fur catnip scratched. Kitty ipsum dolor sit amet, shed everywhere shed everywhere stretching attack your ankles chase the red dot, hairball run catnip eat the grass sniff. Purr jump eat the grass rip the couch scratched sunbathe, shed everywhere rip the couch sleep in the sink fluffy fur catnip scratched.</p>
  <p>Meowwww loved it, hated it, loved it, hated it yet spill litter box, scratch at owner, destroy all furniture, especially couch or lay on arms while you're using the keyboard. Missing until dinner time toy mouse squeak roll over. With tail in the air lounge in doorway. Man running from cops stops to pet cats, goes to jail.</p>
  <p>Intently stare at the same spot poop in the plant pot but kitten is playing with dead mouse. Get video posted to internet for chasing red dot leave fur on owners clothes meow to be let out and mesmerizing birds leave fur on owners clothes or favor packaging over toy so purr for no reason. Meow to be let out play time intently sniff hand run outside as soon as door open yet destroy couch.</p>

</main>

<footer id="footer">Copyright Cat Photo App</footer>
~~~
### Tips
use dashes - and lower case letters
use ipsum lorem for filler text so it takes up space and to see how your website will look with text. 





---

NOTE: to see the raw code for this file, click [here](https://raw.githubusercontent.com/hstatsep/other/main/writeups/template.md)
