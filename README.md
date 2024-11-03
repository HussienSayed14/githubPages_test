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
  <p><strong>Navigating the Generative AI Revolution:</strong> A Global Perspective</p>
  <p>Since late 2022, generative artificial intelligence has surged into the forefront of technological innovation, dramatically impacting industries across the globe...</p>
  <!-- Include the full content for Unit 1 here -->
</div>

<div id="Unit2" class="tabcontent">
  <h2>Unit 2</h2>
  <p><strong>Literature Review Outline:</strong> Usage of Large Language Models (LLMs) in Robotics</p>
  <p>Introduction Overview of LLMs in robotics, particularly for control systems, significance of models like GPT-3 and GPT-4 in robotics...</p>
  <!-- Include the full content for Unit 2 here -->
</div>

<div id="Unit3" class="tabcontent">
  <h2>Unit 3</h2>
  <p><strong>Selecting Appropriate Research Methods, Data Collection, and Required Skills for Evaluating Large Language Models in Robotics</strong></p>
  <p>The project focuses on evaluating the feasibility and accuracy of Large Language Models (LLMs) in performing kinematic calculations for humanoid robots...</p>
  <!-- Include the full content for Unit 3 here -->
</div>

<div id="Unit4" class="tabcontent">
  <h2>Unit 4</h2>
  <p><strong>Detailed Outline for Literature Review:</strong> Usage of Large Language Models (LLMs) in Robotics</p>
  <p>Introduction to LLM advancements and their transformative role across technology sectors, particularly robotics...</p>
  <!-- Include the full content for Unit 4 here -->
</div>

<div id="Unit5" class="tabcontent">
  <h2>Unit 5</h2>
  <p><strong>Case Study:</strong> Inappropriate Use of Surveys</p>
  <p>The 2018 Cambridge Analytica scandal highlighted the dangers of using seemingly harmless surveys on social media to harvest personal data for alternative purposes, particularly political and financial gain...</p>
  <!-- Include the full content for Unit 5 here -->
</div>

<div id="Unit6" class="tabcontent">
  <h2>Unit 6</h2>
  <p>6.1-8.1</p>
  <p><strong>The results for Diet B are as follows:</strong> Sample Size: 50, Sample Mean Weight Loss: 3.710 kg, Sample Standard Deviation: 2.769 kg...</p>
  <!-- Include the full content for Unit 6 here -->
</div>

<div id="Unit7" class="tabcontent">
  <h2>Unit 7</h2>
  <p><strong>Literature review:</strong> Usage of Large Language Models (LLMs) in Robotics</p>
  <p>In the literature review on the use of Large Language Models (LLMs) in robotics, I examined various aspects of how LLMs like GPT-3 and GPT-4 are applied to control robots...</p>
  <!-- Include the full content for Unit 7 here -->
</div>

<div id="Unit9" class="tabcontent">
  <h2>Unit 9</h2>
  <p>9.1 Interpretation: Area 1: The least preferred brand is Brand A, followed by Brand B, with the majority of respondents preferring other brands...</p>
  <!-- Include the full content for Unit 9 here -->
</div>

<div id="Unit10" class="tabcontent">
  <h2>Unit 10</h2>
  <p>In developing this presentation on evaluating Large Language Models (LLMs) for robotics, I delved deeply into both the technical potential and limitations of LLMs in robotics applications...</p>
  <!-- Include the full content for Unit 10 here -->
</div>

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
.tab button { padding: 10px; cursor: pointer; background-color: #f1f1f1; border: none; }
.tab button.active { background-color: #ddd; font-weight: bold; }
.tabcontent { display: none; padding: 20px; border: 1px solid #ccc; margin-top: 10px; }
</style>
