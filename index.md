## Welcome to GitHub Pages
<html>
  <head>
    Add two numbers
    <title>Add two numbers</title>
  </head>
  <body>
    <form>
      <input type ="text" id="box1"><br>
        <input type ="text" id="box2"><br>
        <input type ="text" id="+">
        <input type ="button" value="+" onclick="calcSum()">
    </form>
    
    <script>
      function calcSum() {
      let box1 = documents.getElemntsByID("box1")[0].value;
        let box2 = documents.getElemntsByID("box2")[0].value;
      let sum = Number(box1) + Number(box2);
      documents.getElementsByID("+")[0].VALUE = SUM;
      }
      </script>
  </body>
  </html>
      
