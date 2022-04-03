
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


<section id="work-experience">

<h2>Work Experience</h2>

<div class="accordion">
    <div class="accordion-header">
      <div class="accordion-title"><strong>NPC:</strong> September 2019 - Current</div>
      <span class="accordion-icon">+</span>
    </div>
    <div class="accordion-content">
        For my current job, I am a Digital Print Operator. We use big commercial size printers to print anything from documents to booklets. Their is a lot of thought process when it comes to this job since you need to know what paper to use, where to pull the files from, and how to complete the job correctly for shipping or to be taken somewhere else in the plant for further completion.
    </div>
</div>

<div class="accordion">
    <div class="accordion-header">
      <div class="accordion-title"><strong>Holiday Retirement:</strong> September 2018 - May 2019</div>
      <span class="accordion-icon">+</span>
    </div>
    <div class="accordion-content">
        For this job, I was a Dining Room Server. This job consisted of serving the retired folks food and drinks. We started by giving light refreshments before their meal, then eventually when it was dinner time, we went out and took their orders. After dinner was done, we then had to go out and bus all of the tables, then reset them for the next meal.
    </div>
</div>

</section>


<section id="contact">

<h2>How To Contact Me</h2>

<div class="accordion">
    <div class="accordion-header">
      <div class="accordion-title"><strong>Email</strong></div>
      <span class="accordion-icon">+</span>
    </div>
    <div class="accordion-content">
        kadenhelsel@gmail.com
    </div>
</div>

<div class="accordion">
    <div class="accordion-header">
      <div class="accordion-title"><strong>Phone Number</strong></div>
      <span class="accordion-icon">+</span>
    </div>
    <div class="accordion-content">
        814-932-3909
    </div>
</div>

<div class="accordion">
    <div class="accordion-header">
      <div class="accordion-title"><strong>Instagram</strong></div>
      <span class="accordion-icon">+</span>
    </div>
    <div class="accordion-content">
        kaden__helsel
    </div>
</div>

<div class="accordion">
    <div class="accordion-header">
      <div class="accordion-title"><strong>Facebook</strong></div>
      <span class="accordion-icon">+</span>
    </div>
    <div class="accordion-content">
        Kaden Helsel
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
