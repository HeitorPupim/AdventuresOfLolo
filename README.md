# Adventures Of Lolo

<em> Create a game similar to the old Adventures of Lolo (link below):</em>

<a href= "https://www.youtube.com/watch?v=xUU4Jfj9Gjs"> Original Adventures of Lolo Gameplay</a> 

<h4> Abs:</h4>

First Game dev. by me @USP while enrolled in OOP course. 
This game was made in Java (โ) while we learned some OOP topics such as hierarchy, classes, interfaces, Design Patterns and so on.
  
![startMenu](https://user-images.githubusercontent.com/50893051/192388877-91598752-2e62-422f-bea4-0ac3e86b7c80.png)


<h3> Game Consts: </h3>

<ul>
  <li> 11x11 Matrix Board game </li>
  <li> Frame Interval = 100 FPS</li>
</ul>



<h3> UML Diagram: </h3>
We also drew the UML diagram to represent the classes of our game. 

![UML Diagram](https://user-images.githubusercontent.com/50893051/192388185-caf8ed7c-dfe8-4d22-91b9-9cf28e7e4a57.png)

The <em> Elemento </e> is an <a href = "https://docs.oracle.com/javase/tutorial/java/IandI/abstract.html#:~:text=An%20abstract%20class%20is%20a,but%20they%20can%20be%20subclassed.&text=When%20an%20abstract%20class%20is,methods%20in%20its%20parent%20class."> Abstract Class </a>
Then, <em> Elemento Animado </em> and <em> Elemento Estatico </em> inherits all the methods and attributes of Elemento. 
In the hierarchy, we structured: 

Elemento Animado (moving objects):
<ul>
  <li> ๐ฆธ Lolo (the hero/main character)</li>
  <li> ๐พ Inimigo (enemy) </li>
    <ul>
      <li> ๐พ Tatu Cinza </li>
      <li> ๐พ Link (special character) </li>
  </ul>
 </ul>
 
 Elemento Estรกtico (static/movable object):
 <ul> 
  <li> Agua (๐ฆ - kills lolo on collision)</li>
  <li> Arvore (๐ณ obstacle object)</li>
  <li> Egg (๐ฅ Whenever lolo touches a Cat/Skull it turns into an ๐ฅ, which can be moved)</li>
  <li> Bloco Verde ( ๐ช purple block in  LVL3)</li>
  <li> Bau (๐ฐ After collecting all hearts and touching the chest, next level will be generated)</li>
  <li> Caveira (๐ Static element that also turns into ๐ฅ) -</li>
  <li> Coracao (โค๏ธ - Lolo needs to collect all 6 hearts)</li>
  <li> Minhoca (๐ฑ - Static element that also turns into ๐ฅ) </li>
  

</ul>

<h3> Gameplay Gif: </h3>

![Game Gif](https://user-images.githubusercontent.com/50893051/192387515-ff898e5c-c73a-4f51-bd91-56144791e92c.gif)
