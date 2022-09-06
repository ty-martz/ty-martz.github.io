---
layout: default
title: Emissions Calculator
---

<div class="post">
	<h1 class="pageTitle">Emissions Calculator</h1>
	<p class="intro">actions to calculate your emissions.</p>
	<br>
  <body>
    <h1>Download template file here to fill in and reupload</h1>
    <form method="GET" action="/artifacts/flights_template.csv">
      <button type="submit">Download Template</button>
    </form>
    <br>
    <h1>Upload your CSV file for your flight emissions</h1>
    <img src="./artifacts/paper_plane.png"/>
    <form method="POST" action="" enctype="multipart/form-data">
      <p><input type="file" name="flights_file"></p>
      <p><input type="submit" value="Submit"></p>
    </form>
  </body>
</div>
