# FCC-Project-1-1
Responsive Web Design Projects - Build a Tribute Page
<!DOCTYPE html>
<html>
<style>
body {
  background-color: white;
  font-family: verdana, tahoma, bookman ;
  font-size: 10;
  line-height: 2;
  text-align: center;
  color: #500;
  margin: 0;
  text-align: center;
  justify-content: center;
}
#main {
  background-color: beige;
  padding: 5px;
}
#img-div {
  background-color: #a67a56;
  border-radius: 10px;
  padding: 15px;
}
img {
  max-width: 300px;
  width: 100%;
  display: block;
  height: auto;
  margin: auto;
}
#headline {
  margin: 50px 0;
  text-align: center;
}
#tribute-text{
  max-width: 1000px;
  margin: 0 auto 10px auto;
  text-align: center;
  line-height: 1;
  padding: 5px;
}
ul {
  max-width: 500px;
  margin: 0 auto 50px auto;
  text-align: left;
  line-height: 2;
}
li {
  margin: 20px 0;
}
</style>

<script src="https://cdn.freecodecamp.org/testable-projects-fcc/v1/bundle.js"></script>

<! –– I've tried my best to make this work my own. I've used information from FCC's curriculum, W3Schools and other open forums and guides to make my own pages. If there has been any sort of infringement, feel free to contact me and I'll try and fix it. Contact info: shaak@live.nl ––>

  <main id="main">
  <h1 id="title"> William the Silent </h1>
      <p> Prince and first ruler of the United Netherlands </p>
      <figure id="img-div">
        <img id="image" src="https://upload.wikimedia.org/wikipedia/commons/3/35/Philip_II_of_Spain_berating_William_the_Silent_Prince_of_Orange_by_Cornelis_Kruseman.jpg" alt="A painting showing Philip the second of Spain berating William the Silent Prince of Orange"/>
        <figcaption id="img-caption"> Philip the 2<sup>nd</sup> of Spain berating William the Silent Prince of Orange by Cornelis Kruseman.</figcaption>
        </figure>
  
  <section id="tribute-info">
  <h3><strong>Here's a time line of William the Silent's life:</strong></h3>
    <p id="tribute-text">
      William was the leader of the revolt against Spanish rule of the Netherlands. This revolt started what is now known as the Eighty Years' War where the Netherlands fought for its independence from Spain and the Catholic church. William was born into nobility and was raised by Spanish nobility. After becoming more dissatisfied he turned against his former masters and used his resources and influence to do so. After many battles, successes and failures, William was eventually shot aged 51. His legacy inspired the Dutch to fight for their indepence which was eventually achieved in 1648. The Dutch royal family is from the same bloodline as William.
    </p>
        <ul>
  <li>
    <strong>1533</strong> - Born in Hessen, Germany</li>
  <li>
    <strong>1544</strong> - Aged 11, William is bestowed his cousin's heritage including the kingdom of Orange in France. The 11-year old William is known henceforth as 'Prince of Orange'</li>
  <li>
    <strong>1551</strong> - Marries Anna van Egmont. Through this marriage his influence and posessions grew in the Netherlands. Their first son, Filips Willem van Oranje was born in 1554</li>
  <li>
    <strong>1555</strong> - Philip the 2<sup>nd</sup> acquires leadership of the Netherlands. A devout Catholic who wanted to create one kingdom where the online religion was Catholicism. In this time William receives his education from Charles the 5<sup>th</sup> and proves himself to be a worthy leader.</li>
  <li>
    <strong>1559</strong> - William is appointed 'Stadhouder', governor of the main Dutch provinces an greatly increases his power. It is then he started to grow increasingly aggitated by Spain's treatment of the Dutch citizens.</li>
  <li>
    <strong>1568</strong> - After increasing tensions in the Netherlands William attacks the Spanish army. This coincides with the start of the 80-year war between the Netherlands and Spain.</li>
  <li>
    <strong>1581</strong> - The Netherlands declares official independency from Spain, electing William as the new leader.</li>
  <li>
    <strong>1584</strong> - Dies after being shot by Balthasar Gerards, a devout Catholic who supported the Spanish.</li>
  </ul>
    
  <p id="quote"><em>"Mon Dieu, ayez pitié de mon âme; mon Dieu, ayez pitié de ce pauvre peuple. (My God, have pity on my soul; my God, have pity on this poor people)."
<br>
    <br>
    -- William's last words after being shot</em></p>
  
    <h3><strong>If you have time, you should read more about William's life on his <a id="tribute-link" href="https://en.wikipedia.org/wiki/William_the_Silent" target="_blank">Wikipedia entry.</a></strong></h3>
    </section>
    </main>
<footer>
  <p>
  This page is created <a id="tribute-link" href="https://github.com/HaakSan" target="_blank">HaakSan</a> for <a id0"fcc-link" href="https://www.freecodecamp.org/""_blank">FreeCodeCamp</a> - 2021</p>
  </footer>
</html>
