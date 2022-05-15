<nav>
        <ul>
            <li><a href="fastfoodrestuarants.html">Favorite Fast Food Restuarants</a></li>
            <li><a href="tempconverter.html">Temperature Converter</a></li>
            <li><a href="about.html">About Me</a></li>
        </ul>
</nav>

<p2>
Hello, my name is Kaden Helsel, and welcome to my website! I am currently a Freshman at Mount Aloysius studying IT. For my career, I want to become a Network and Computer Systems Administrator. I have always liked working with technology as a kid, always helping out someone to fix something that might not be working properly. As I got older, that's when I knew that going into IT would be the best thing for me. In creation of this website, I have added three pages. The first page is from one of my previous assignments where we had to talk about 4 of our favorite things, in which I chose fast food restuarants. The second page is from our Assignment 10, where we had to come up with something creative for this website we are building, which is a temperature converter. Lastly, my about page is pretty much a big background of things about me.
</p2>


<style>

.accordion {
  max-width: 650px;
  border: 3px solid #FFCC00;
  border-bottom: none;
}

.accordion:last-child {
  border-bottom: 3px solid #FFCC00;
}

.accordion-header {
  display: flex;
  padding: 16px;
  cursor: pointer;
  background-color: #000000;
}

.accordion-title {
  flex: 1;
}

.accordion-icon: {
  width: 16px;
}

.accordion-content {
  padding: 16px;
}

.accordion-content {
  display: none;
}

</style>

<section id="contact-me">

<h2>How To Contact Me / View My GitHub Page</h2>

<div class="accordion">
    <div class="accordion-header">
      <div class="accordion-title"><strong>GitHub</strong></div>
      <span class="accordion-icon">+</span>
    </div>
    <div class="accordion-content">
        https://github.com/klhst11
    </div>
</div>

<div class="accordion">
    <div class="accordion-header">
      <div class="accordion-title"><strong>Personal Email</strong></div>
      <span class="accordion-icon">+</span>
    </div>
    <div class="accordion-content">
        kadenhelsel@gmail.com
    </div>
</div>

<div class="accordion">
    <div class="accordion-header">
      <div class="accordion-title"><strong>School Email</strong></div>
      <span class="accordion-icon">+</span>
    </div>
    <div class="accordion-content">
        klhst11@student.mtaloy.edu
    </div>
</div>

</section>

<script>

// Runs the loop
const accordionHeaders = document.getElementsByClassName('accordion-header');
const accordionContents = document.getElementsByClassName('accordion-content');
const accordionIcons = document.getElementsByClassName('accordion-icon');

// Allows the user to click on and either show or hide the accordions contents 
for (let i = 0; i < accordionHeaders.length; i++) {
  accordionHeaders[i].addEventListener('click', () => {
    accordionContents[i].style.display = accordionContents[i].style.display == 'block' ? 'none' : 'block';
    accordionIcons[i].innerHTML = accordionContents[i].style.display == 'block' ? '-' : '+';
  });
}

</script>
