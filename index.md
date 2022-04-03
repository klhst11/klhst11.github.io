
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
      <div class="accordion-title">NPC - <strong>2019 - Current</strong></div>
      <span class="accordion-icon">+</span>
    </div>
    <div class="accordion-content">
        For my current job, I am a Digital Print Operator. We use big commercial size printers to print anything from documents to booklets. Their is a lot of thought process when it comes to this job since you need to know what paper to use, where to pull the files from, and how to complete the job correctly for shipping or to somewhere else in the plant.
    </div>
</div>

<div class="accordion">
    <div class="accordion-header">
      <div class="accordion-title">Second Volunteer Opportunity</div>
      <span class="accordion-icon">+</span>
    </div>
    <div class="accordion-content">
        Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.
    </div>
</div>

<div class="accordion">
    <div class="accordion-header">
      <div class="accordion-title">Third Volunteer Opportunity</div>
      <span class="accordion-icon">+</span>
    </div>
    <div class="accordion-content">
        Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.
    </div>
</div>

<div class="accordion">
    <div class="accordion-header">
      <div class="accordion-title">Fourth Volunteer Opportunity</div>
      <span class="accordion-icon">+</span>
    </div>
    <div class="accordion-content">
        Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.
    </div>
</div>

<div class="accordion">
    <div class="accordion-header">
      <div class="accordion-title">Fifth Volunteer Opportunity</div>
      <span class="accordion-icon">+</span>
    </div>
    <div class="accordion-content">
        Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.
    </div>
</div>


</section>


<section id="education">

<h2>Education</h2>

<div class="accordion">
    <div class="accordion-header">
      <div class="accordion-title">Bachelor's Degree - <strong>2014</strong></div>
      <span class="accordion-icon">+</span>
    </div>
    <div class="accordion-content">
        Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.
        <ul>
          <li>First task I completed</li>

        </ul>
    </div>
</div>

<div class="accordion">
    <div class="accordion-header">
      <div class="accordion-title">Second Volunteer Opportunity</div>
      <span class="accordion-icon">+</span>
    </div>
    <div class="accordion-content">
        Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.
    </div>
</div>

<div class="accordion">
    <div class="accordion-header">
      <div class="accordion-title">Third Volunteer Opportunity</div>
      <span class="accordion-icon">+</span>
    </div>
    <div class="accordion-content">
        Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.
    </div>
</div>

<div class="accordion">
    <div class="accordion-header">
      <div class="accordion-title">Fourth Volunteer Opportunity</div>
      <span class="accordion-icon">+</span>
    </div>
    <div class="accordion-content">
        Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.
    </div>
</div>

<div class="accordion">
    <div class="accordion-header">
      <div class="accordion-title">Fifth Volunteer Opportunity</div>
      <span class="accordion-icon">+</span>
    </div>
    <div class="accordion-content">
        Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.
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
