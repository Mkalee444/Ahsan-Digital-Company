<!DOCTYPE html>
<html lang="en">
<head>
<style type="text/css">
body {
  font-family: Arial, sans-serif;
  background-color:  #cf9e62;
  margin: 0;
  padding: 0;
  
  justify-content: center;
  align-items: center;
  height: 100v
}
header{
  top: 0%;
  left: 50%;
  right: 50%;
  color: #cf9e62;
  background-color: #271a0b;
  text-align: end;
  justify-content: center;
  font-size: 20px;
  height: 1cm;
  

}

.img{
  width: 10%;
  top: 100% ;
  left: 100%;
  right:0%;
  height: 1.0cm;

}

.container {
  background: #271a0b;
  color:  #cf9e62;
  padding: 20px;
  border-radius: 48px;
  box-shadow: 0 0 10px black(0, 0, 0, 0.1);
  max-width: 400px;
  width: 100%;
  text-align: center;
}

h1 {
  margin-bottom: 20px;
}

form {
  display: flex;
  flex-direction: column;
}

label {
  margin-top: 10px;
}

input {
  padding: 10px;
  margin-top: 5px;
  border: 1px solid #ccc;
  border-radius: 4px;
}
span{
  margin-top: 50px;
}
 img {
  border-radius: 32px;
  height: 1cm;
  width: 10%;
  position: relative;
  size: 10px;

}

.btn {
  margin-top: 20px;
  padding: 10px;
  background:  #cf9e62;
  color: #271a0b;
  border: none;
  border-radius: 4px;
  cursor: pointer;
  text-decoration:dotted;
}

.btn:hover {
  background-color:  #cf9e62;

}

</style>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>FUDMA Recommender - Home</title>
  <link rel="stylesheet" href="styles.css">
</head>
<header>
   FEDERAL UNIVERSITY DUTSINMA 
  <img src="C:\Users\Umar Lawal\Pictures\images_2.jpeg" height="1.5cm"></img>
     
</header>
<br><br><br> 
  <br><br> <br><br>
  <center>
  <div class="container">
    <h1>Welcome to FUDMA Course Recommender</h1>
    <p>This system will help you find the best course based on your UTME scores and WAEC/NECO subjects.</p>
    <a href="Rec2.html" class="btn">Get Started</a>
  </div>
  <br><br><br>
  </center>
</body>
<script type="text/javascript">
  // A welcoming message
  alert("Welcome to Fudma Recommender System!")
// UTME Form Submission
document.getElementById('utme-form').addEventListener('submit', function (e) {
  e.preventDefault();
  // Store UTME data in localStorage
  const utmeData = {
    subject1: document.getElementById('subject1').value,
    score1: document.getElementById('score1').value,
    subject2: document.getElementById('subject2').value,
    score2: document.getElementById('score2').value,
    subject3: document.getElementById('subject3').value,
    score3: document.getElementById('score3').value,
    subject4: document.getElementById('subject4').value,
    score4: document.getElementById('score4').value,
  };
  localStorage.setItem('utmeData', JSON.stringify(utmeData));
  window.location.href = 'Rec3.html';
});

// WAEC/NECO Form Submission
document.getElementById('waec-neco-form').addEventListener('submit', function (e) {
  e.preventDefault();
  // Store WAEC/NECO data in localStorage
  const waecNecoData = {
    subject1: document.getElementById('subject1').value,
    subject2: document.getElementById('subject2').value,
    subject3: document.getElementById('subject3').value,
    subject4: document.getElementById('subject4').value,
    subject5: document.getElementById('subject5').value,
  };
  localStorage.setItem('waecNecoData', JSON.stringify(waecNecoData));
  window.location.href = 'recommendation.html';
});

    // Recommendation LogiccommendedCourse
