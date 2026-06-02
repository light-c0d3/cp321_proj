<h1>📊 CP321 Project – Online Learning Trends in Ontario (2018–2022)</h1>

<h2>👥 Team Members</h2>
<ul>
  <li>Malika Sharma – 210479350</li>
  <li>Ruveyda Nur Kizmaz – 210960430</li>
</ul>

<hr>

<h2>🌱 Introduction</h2>
<p>
Education has been changing quite quickly in recent years, especially with the rise of online learning. 
What students choose to study is often linked to both their interests and the direction of future career opportunities.
</p>

<p>
In Ontario, secondary school students have increasingly used online courses to support or extend their learning. 
Looking at enrollment data from 2018 to 2022 gives us a way to understand these shifts more clearly.
</p>

<p>
This project explores how course enrollment patterns have changed over time and what these changes might suggest 
about student interests and future job market trends.
</p>

<hr>

<h2>🎯 Project Goal</h2>
<p><strong>How do online course enrollment trends among Ontario secondary school students from 2018 to 2022 reflect changing interests and possible shifts in future job market demands?</strong></p>

<hr>

<h2>📁 Dataset</h2>
<p>We used a publicly available dataset from the Ontario Data Catalogue:</p>

<p>
<a href="https://data.ontario.ca/dataset/online-learning-course-enrolment-totals-by-course/resource/df4278d2-4c00-42af-b58b-cfed40d6f6a3">
Ontario Online Learning Course Enrollment Dataset
</a>
</p>

<h3>What it includes:</h3>
<ul>
  <li>Course names and course codes</li>
  <li>Enrollment numbers for each year (2018–2022)</li>
  <li>Online learning enrollment totals across Ontario secondary schools</li>
</ul>

<hr>

<h2>⚙️ Data Processing</h2>
<ul>
  <li>Replaced missing or suppressed values (&lt;10) with a small numeric value</li>
  <li>Filled missing data with 0</li>
  <li>Converted enrollment columns into numeric format</li>
  <li>Removed “Provincial Total” rows to avoid duplication</li>
  <li>Reshaped data using <code>melt()</code> for trend analysis</li>
  <li>Grouped and aggregated data depending on the visualization</li>
</ul>

<p>
These steps helped clean the dataset and made it easier to compare trends across years.
</p>

<hr>

<h2>📈 Visualizations & Insights</h2>

<h3>📊 1. Grouped Bar Chart</h3>
<ul>
  <li>Shows the top 3 enrolled courses each year</li>
  <li>Mandatory courses like English and Civics consistently stay high</li>
  <li>Gives a baseline of overall online learning activity</li>
</ul>

<h3>🔥 2. Heatmap</h3>
<ul>
  <li>Displays enrollment intensity across top 15 courses</li>
  <li>Core subjects dominate the dataset</li>
  <li>Science electives like Biology, Chemistry, Physics stand out</li>
</ul>

<h3>📉 3. Line Chart</h3>
<ul>
  <li>Shows courses with declining enrollment trends</li>
  <li>Suggests shifting student preferences</li>
  <li>May reflect changes in career expectations</li>
</ul>

<h3>📦 4. Stacked Bar Chart</h3>
<ul>
  <li>Shows elective course enrollment distribution</li>
  <li>Business and Computer Science remain strong</li>
  <li>Science subjects stay consistently popular</li>
</ul>

<hr>

<h2>🧠 Key Findings</h2>
<ul>
  <li>Required courses remain consistently high in enrollment</li>
  <li>Technology and science-related electives maintain strong interest</li>
  <li>Some courses show declining engagement over time</li>
  <li>Students are increasingly choosing career-oriented subjects</li>
</ul>

<p>
Overall, the data suggests that students are becoming more intentional about course selection, especially in areas connected to future job opportunities.
</p>

<hr>

<h2>📌 Conclusion</h2>
<p>
Between 2018 and 2022, online learning in Ontario secondary schools became more than just an alternative — it became a key part of how students shape their education paths.
</p>

<p>
The patterns suggest a gradual shift toward technology and science-focused learning, alongside stable demand for foundational subjects.
</p>

<p>
These trends reflect how education and future workforce interests are evolving together.
</p>

<hr>

<h2>💻 How to Run the Code</h2>

<h3>Requirements</h3>
<pre>
pip install pandas
pip install matplotlib
pip install seaborn
pip install openpyxl
</pre>

<h3>Run</h3>
<ul>
  <li>Place dataset in: <code>data/onlinelearnenrolbycrs_1415-2021_en.xlsx</code></li>
  <li>Run Python scripts section by section</li>
</ul>
