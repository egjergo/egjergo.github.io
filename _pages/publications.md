---
layout: page3
title: Publications
---

<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
* {
  box-sizing: border-box;
}

/* Add a gray background color with some padding */
body {
  padding: 0px;
  background: #f1f1f1;
}

/* Header/Blog Title */
.header {
  padding: 3px;
  font-size: 30px;
  text-align: center;
  background: white;
}

/* Create two unequal columns that floats next to each other */
/* Left column */
.leftcolumn {   
  float: left;
  width: 50%;
}

/* Right column */
.rightcolumn {
  float: left;
  width: 50%;
  padding-left: 10px;
}

/* Fake image */
.fakeimg {
  background-color: #aaa;
  width: 100%;
  padding: 20px;
}

/* Add a card effect for articles */
.card {
   background-color: white;
   padding: 20px;
   margin-top: 20px;
}

/* Clear floats after the columns */
.row:after {
  content: "";
  display: table;
  clear: both;
}

/* Footer */
.footer {
  padding: 20px;
  text-align: center;
  background: #ddd;
  margin-top: 20px;
}

/* Responsive layout - when the screen is less than 800px wide, make the two columns stack on top of each other instead of next to each other */
@media screen and (max-width: 1200px) {
  .leftcolumn, .rightcolumn {   
    width: 100%;
    padding: 0;
  }
}
</style>
</head>
<body>

<div class="header">

For an up-to-date list of publications, please visit <a target="_blank" href="https://ui.adsabs.harvard.edu/search/q=author%3A%22gjergo%2C%20e%22&sort=date%20desc%2C%20bibcode%20desc&p_=0">my ADS search results</a>

<a
id="cy-effective-orcid-url"
class="underline"
  href="https://orcid.org/0000-0002-7440-1080"
  target="orcid.widget"
  rel="me noopener noreferrer"
  style="vertical-align: top">
  <img
    src="https://orcid.org/sites/default/files/images/orcid_16x16.png"
    style="width: 1em; margin-inline-start: 0.5em"
    alt="ORCID iD icon"/>
  https://orcid.org/0000-0002-7440-1080
</a>

</div>

<div class="row">
  <div class="leftcolumn">
    <div class="card">
      <h5>Type Ia supernovae selection and forecast of cosmology constraints for the Dark Energy Survey</h5>
      <h6>Title description, Dec 7, 2017</h6>
      <p>Gjergo Eda, Duggan Jefferson, Cunningham John, Kuhlmann Stephen, Biswas Rahul, Kovacs Eve, Bernstein Joseph, Spinka Harold.</p>
      <p>Argonne National Laboratory, Illinois Institute of Technology, Loyola University Chicago.</p>
      <p><a target="_blank" href="https://ui.adsabs.harvard.edu/abs/2013APh....42...52G/abstract">Astroparticle Physics, 2013, Volume 42, p. 52-61.</a></p>
    </div>
    <!--<div class="card">
      <h2>TITLE HEADING</h2>
      <h5>Title description, Sep 2, 2017</h5>
      <div class="fakeimg" style="height:200px;">Image</div>
      <p>Some text..</p>
      <p>Sunt in culpa qui officia deserunt mollit anim id est laborum consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco.</p>
    </div>-->
  </div>

  <div class="rightcolumn">
    <div class="card">
      <h2>About Me</h2>
      <div class="fakeimg" style="height:100px;">Image</div>
      <p>Some text about me in culpa qui officia deserunt mollit anim..</p>
    </div>
    <div class="card">
      <h3>Popular Post</h3>
      <div class="fakeimg">Image</div><br>
      <div class="fakeimg">Image</div><br>
      <div class="fakeimg">Image</div>
    </div>
    <div class="card">
      <h3>Follow Me</h3>
      <p>Some text..</p>
    </div>
  </div>
</div>

<div class="footer">
  <h2>Footer</h2>
</div>

</body>
</html>