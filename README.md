@@ -0,0 +1,14 @@
<!DOCTYPE html>
<html lang="en" dir="ltr">
  <head>
    <meta charset="utf-8">
    <title>Hobbies</title>
  </head>
  <body>
<h3>My Hobbies</h3>
<ol type="I">
  <li>Cricket</li>
  <li>Hockey</li>
  <li>Football</li>
  </body>
</html>
 27  
contact-me.html
@@ -0,0 +1,27 @@
<!DOCTYPE html>
<html lang="en" dir="ltr">

<head>
  <meta charset="utf-8">
  <title>Contact Me</title>
</head>

<body>
  <h1>My Contact Details</h1>
  <p>My Fictional Address: <strong>Main City Kasur</strong></p>
  <p>Mobile: <b>03225932678</b></p>
  <p>Email: <strong><u>ahmad481988@gmail.com</u></strong></p>
<hr>
  <!--Form-->
  <form action="mailto:ahmad481988@gmail.com" method="post" enctype="text/plain">
    <label>Your Name:</label>
    <input type="text" name="Your Name" value=""><br>
    <label>Email:</label>
    <input type="email" name="Your Email" value=""><br>
    <label>Your Messege</label><br>
    <textarea name="Your Messege" rows="10" cols="30"></textarea><br>
    <input type="submit">
  </form>
</body>

</html>
 106  
mysite.html
@@ -0,0 +1,106 @@
<!DOCTYPE html>
<html lang="en" dir="ltr">

<head>
  <meta charset="utf-8">
  <title>Ahmad's Personal Site</title>

</head>

<body>
  <table cellspacing="30">
    <tr>
      <td><img src="D:\University\Web Notes\Images\profile1.jpg" alt="Ahmad's profile picture">
      <!--To change shape of Images use CSS-->
      <!-- <p align=center>  <img src="D:\University\Web Notes\Images\profile1.jpg" height =50% width=80% alt="Ahmad's profile picture" >
    -->
</td>
<td>  <h1>Muhammad Ahmad</h1>

<p><em>BSCS student of 5th semester in <strong>GCU</strong>. I 💗 coffee. I also 💖 Programming.</em> </p>
<p>I am <a href="https://www.facebook.com/profile.php?id=100044538727552"> Muhammad Ahmad</a> from Kasur, Pakisan.
  I am 21 years old. I study BSCS(Bachelor of Science in computer science) from <a href="https://gcu.edu.pk">GCU( Government College University, Lahore)</a>.
  Now I'm free after 4th semester finals and started to learn about WordPress, HTML, CSS and JavaScript.
  I want to become a web designer of top ranking. I hope that I will learn soon.
</p>
</td>
    </tr>
  </table>

  <hr>
  <h3>Books and Teaching</h3>
  <ul>
    <li>C++</li>
    <li>Java</li>
    <li>C# </li>
    <li>Web Development</li>
    <li>  <a download href="https://web.stanford.edu/group/csp/cs21/htmlcheatsheet.pdf">Download htmlcheatsheet</a></li>
  </ul>
  <hr>
  <!-- HTML Tables -->
  <h3>Educational Experience</h3>
  <table border="1" >
    <thead>
      <!--thead means table head like columns-->
      <tr>
        <th>Dates</th>
        <!--th means thable head cell which may be coumn name and column names are written in bold th is bold-->
        <th>Orgarnizations</th>
      </tr>
    </thead>
    <tbody>  <!--tbody Contains table body-->
      <tr>
        <!--tr represents table row and td represents table data like cell data (columns)-->
        <td>2009-2012</td>
        <td>Al-Sharif Model School Kasur</td>
      </tr>
      <tr>
        <td>2013-2018</td>
        <td>Govt. Islamia High School Kasur</td>
      </tr>
      <tr>
        <td>2019-2020</td>
        <td>Govt. Islamia College Kasur</td>
      </tr>
      <tr>
        <td>2020</td>
        <td>GCU Lahore</td>
      </tr>
    </tbody>
    <tfoot>
      <!--tfoot contains table footer-->
    </tfoot>
  </table>

<hr>

  <h3><a href="Hobbies.html">My Hobbies</a></h3>
  <!--<h3><a href="Hobbies.html" target="#">My Hobbies</a></h3>-->

  <h3><a href="contact-me.html">Contact Me</a></h3>
  <h3>My Desires</h3>
  <ol type="1">
    <li>Web Development</li>
    <li>App Development</li>
    <li>Game Development</li>
    <li>Algorithms</li>
  </ol>
<h3>Skills</h3>
<table>
  <tr>
    <td>HTML</td>
    <td>⭐⭐⭐⭐</td>
  </tr>
  <tr>
    <td>Java</td>
    <td>⭐⭐⭐</td>
  </tr>
  <tr>
    <td>C++</td>
    <td>⭐⭐⭐</td>
  </tr>
</table>

</body>

</html>
 BIN +29.1 KB 
profile1.jpg
