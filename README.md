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

<button onclick="printContent()" style="margin-top: 10px;">Print Current Section</button>

<!-- Unit Content Sections -->
<div id="Unit1" class="tabcontent">
  <h2>Unit 1</h2>
  <p><strong>Navigating the Generative AI Revolution:</strong> A Global Perspective...</p>
  <p>Since late 2022, generative artificial intelligence has surged...</p>
  <!-- Full content of Unit 1 -->
</div>

<div id="Unit2" class="tabcontent">
  <h2>Unit 2</h2>
  <p><strong>Literature Review Outline:</strong> Usage of Large Language Models (LLMs) in Robotics...</p>
  <p>Introduction Overview of LLMs in robotics, particularly for control systems...</p>
  <!-- Full content of Unit 2 -->
</div>

<div id="Unit3" class="tabcontent">
  <h2>Unit 3</h2>
  <p><strong>Selecting Appropriate Research Methods, Data Collection, and Required Skills for Evaluating Large Language Models in Robotics</strong>...</p>
  <p>The project focuses on evaluating the feasibility and accuracy of Large Language Models (LLMs)...</p>
  <!-- Full content of Unit 3 -->
</div>

<!-- Continue adding div sections for Units 4-10 with full content as provided -->

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

function printContent() {
  var activeContent = document.querySelector('.tabcontent[style*="display: block"]');
  var newWin = window.open("");
  newWin.document.write(activeContent.outerHTML);
  newWin.print();
  newWin.close();
}

// Show the first tab by default
document.addEventListener("DOMContentLoaded", function() {
  document.querySelector('.tablinks').click();
});
</script>

<style>
.tab { display: flex; gap: 10px; }
.tab button { padding: 10px; cursor: pointer; background-color: #f1f1f1; border: none; }
.tab button.active { background-color: #ddd; font-weight: bold; }
.tabcontent { display: none; padding: 20px; border: 1px solid #ccc; margin-top: 10px; }
</style>
