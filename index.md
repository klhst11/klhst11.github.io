<nav>
        <ul>
            <li><a href="fastfoodrestuarants.html">Favorite Fast Food Restuarants</a></li>
            <li><a href="tempconverter.html">Temperature Converter</a></li>
            <li><a href="about.html">About Me</a></li>
        </ul>
</nav>

<body>
      <div id="header">
        <nav>
          <ul>
            <li class="fork"><a href="https://github.com/klhst11/klhst11.github.io">View On GitHub</a></li>
            
          </ul>
        </nav>
      </div><!-- end header -->

    <div class="wrapper">

      <section>
        <div id="title">
          <h1>Kadens Porfolio Website</h1>
          <p></p>
          <hr>
          <span class="credits left">Project maintained by <a href="https://github.com/klhst11">klhst11</a></span>
          <span class="credits right">Hosted on GitHub Pages — Theme by <a href="https://twitter.com/mattgraham">mattgraham</a></span>
        </div>

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


<section id="home">

<div class="accordion">
    <div class="accordion-header">
      <div class="accordion-title">Hello, my name is Kaden Helsel, and welcome to my website! I am currently a Freshman at Mount Aloysius studying IT. For my career, I want to become a Network and Computer Systems Administrator. I have always liked working with technology as a kid, always helping out someone to fix something that might not be working properly. As I got older, that's when I knew that going into IT would be the best thing for me. In creation of this website, I have added three pages. The first page is from one of my previous assignments where we had to talk about 4 of our favorite things, in which I chose fast food restuarants. The second page is from our Assignment 10, where we had to come up with something creative for this website we are building, which is a temperature converter. Lastly, my about page is pretty much a big background of things about me.</div>
    </div>
</div>

</section>


<section id="contact">

<h2>How To Contact Me</h2>

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

<section id="jobs">

<h2>Possible IT Jobs That I May Pursue</h2>

<div class="accordion">
    <div class="accordion-header">
      <div class="accordion-title"><strong>Network & Computer Systems Administrator</strong></div>
    </div>
</div>

<div class="accordion">
    <div class="accordion-header">
      <div class="accordion-title"><strong>Computer Systems Analyst</strong></div>
    </div>
</div>
    
<div class="accordion">
    <div class="accordion-header">
      <div class="accordion-title"><strong>Database Administrator</strong></div>
    </div>
</div>
    
<div class="accordion">
    <div class="accordion-header">
      <div class="accordion-title"><strong>Information Technology Architect</strong></div>
    </div>
</div>    
 
</section>          
          
<script>

const accordionHeaders = document.getElementsByClassName('accordion-header');
const accordionContents = document.getElementsByClassName('accordion-content');
const accordionIcons = document.getElementsByClassName('accordion-icon');

for (let i = 0; i < accordionHeaders.length; i++) {
  accordionHeaders[i].addEventListener('click', () => {
    accordionContents[i].style.display = accordionContents[i].style.display == 'block' ? 'none' : 'block';
    accordionIcons[i].innerHTML = accordionContents[i].style.display == 'block' ? '-' : '+';
  });
}

</script>

</section>

</div>
  
</body>
