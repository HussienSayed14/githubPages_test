# Course Content

<div id="tab-navigation" class="tab">
  <button class="tablinks" onclick="openUnit(event, 'Unit1')">Unit 1</button>
  <button class="tablinks" onclick="openUnit(event, 'Unit2')">Unit 2</button>
  <button class="tablinks" onclick="openUnit(event, 'Unit3')">Unit 3</button>
  <button class="tablinks" onclick="openUnit(event, 'Unit4')">Unit 4</button>
  <button class="tablinks" onclick="openUnit(event, 'Unit5')">Unit 5</button>
  <button class="tablinks" onclick="openUnit(event, 'Unit6')">Unit 6</button>
  <button class="tablinks" onclick="openUnit(event, 'Unit7')">Unit 7</button>
  <button class="tablinks" onclick="openUnit(event, 'Unit9')">Unit 9</button>
  <button class="tablinks" onclick="openUnit(event, 'Unit10')">Unit 10</button>
</div>

<!-- Unit Content Sections -->
<div id="Unit1" class="tabcontent">
  <h2>Unit 1</h2>
  <p>**Navigating the Generative AI Revolution:** A Global Perspective...</p>
  <!-- (Add the remaining content for Unit 1 here) -->
</div>

<div id="Unit2" class="tabcontent">
  <h2>Unit 2</h2>
  <p>**Literature Review Outline:** Usage of Large Language Models (LLMs) in Robotics...</p>
  <!-- (Add the remaining content for Unit 2 here) -->
</div>

<div id="Unit3" class="tabcontent">
  <h2>Unit 3</h2>
  <p>**Selecting Appropriate Research Methods, Data Collection, and Required Skills for Evaluating Large Language Models in Robotics**...</p>
  <!-- (Add the remaining content for Unit 3 here) -->
</div>

<!-- Continue adding div sections for Units 4-10 -->

<script>
function openUnit(evt, unitName) {
  // Hide all tab content
  var tabcontent = document.getElementsByClassName("tabcontent");
  for (var i = 0; i < tabcontent.length; i++) {
    tabcontent[i].style.display = "none";
  }

  // Remove "active" class from all tab buttons
  var tablinks = document.getElementsByClassName("tablinks");
  for (var i = 0; i < tablinks.length; i++) {
    tablinks[i].className = tablinks[i].className.replace(" active", "");
  }

  // Show the selected tab and add "active" class to the button
  document.getElementById(unitName).style.display = "block";
  evt.currentTarget.className += " active";
}

// Show the first tab by default
document.addEventListener("DOMContentLoaded", function() {
  document.querySelector('.tablinks').click();
});
</script>

<style>
.tab { display: flex; gap: 10px; }
.tab button { padding: 10px; cursor: pointer; }
.tab button.active { background-color: #ddd; }
.tabcontent { display: none; padding: 20px; border: 1px solid #ccc; margin-top: 10px; }
</style>
