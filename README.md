# Javascript-Question-answers
<table class="table">
  <thead>
    <tr>
      <th>NO</th>
      <th>Questions</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th >1</th>
      <td><a href="#que1">What is Javascript?</a></td>
    </tr>
    <tr>
      <th >2</th>
      <td><a href="#que2">Brief history of Javascript?</a></td>
    </tr>
     <tr>
      <th >3</th>
      <td><a href="#que3">What is variable and rules of variables?</a></td>
    </tr>
    <tr>
      <th >4</th>
      <td><a href="#que4">Explain the var variable?</a></td>
    </tr>
    </tbody>
</table>
<div class="common" id="que1" >
  <h3>1. What is Javascript?</h3>
  <ul>
    <li>Javascript (JS) is a scripting language</li>
    <li>It is used to enhance HTML pages</li>
    <li>It is commonly used in web development.</li>
    <li>It is lightweight</li>
  </ul>
</div>
<div class="common" id="que2" >
  <h3>2. Brief history of Javascript?</h3>
  <ul>
    <li>Javascript was invented in 1995.</li>
    <li> Invented by Brendan Eich.</li>
    <li> It was developed for Netscape 2.</li>
    <li>Javascript was first known as LiveScript after Netscape changed to javascript./li>
    <li>In 1997 JavaScript became an ECMA standard.</li>
    <li>The full form of ECMA is European Computer Manufacturer's Association</li>
    <li>ECMA is a Standard scripting language, and java script is most popular one.</li>
  </ul>
  <p>List of ECMA version</p>
  <table>
     <thead>
    <tr>
      <th>Year</th>
      <th>ECMA Version</th>
    </tr>
  </thead>
     <tbody>
    <tr>
      <th >1997	</th>
      <td>ES1</td>
    </tr>
    <tr>
      <th >1998	</th>
      <td>ES2</td>
    </tr>
    <tr>
      <th >1999	</th>
      <td>ES3</td>
    </tr>
     <tr>
      <th >2008</th>
      <td>ES4</td>
    </tr>   
     <tr>
      <th >2009</th>
      <td>ES5</td>
    </tr>
     <tr>
      <th >2015</th>
      <td>ES6</td>
    </tr>
    <tr>
      <th >2016</th>
      <td>ES7</td>
    </tr>
    <tr>
      <th >2017</th>
      <td>ES8</td>
    </tr>
    <tr>
      <th >2018</th>
      <td>ES9</td>
    </tr>
    </tbody>
  </table>
</div>
<div class="common" id="que3" >
  <h3>3. What is variable and rules of variables?</h3>
  <ul>
    <li>Varialbe used to store data value</li>
    <li>we can change data value.</li>
    <li>javascript variables are flexible we can store string, number, decimal numbers</li>
  </ul>
  <p>Rules of javascript variable </p>
  <ol>
    <li>Variable name start with a letter, or underscore(_), or doller($).</li>
    <li>Variable names cannot contain spaces.</li>
    <li>Declare JavaScript variables with var,let, or const.</li>
  </ol>
</div>
<div class="common" id="que4" >
  <h3>4. Explain the var variable?</h3>
  <ul>
    <li>var variable is used to store number, string or decimal number.</li>
    <li>var variable declares a function-scoped or globally-scoped.</li>
  </ul>
  <p>Syntax</p>
  <span>var "variableName";</span><br/>
  <span>var "variableName" = "value"</span>
  <p>Multiple variable declare</p>
  <span> var one = 1, two = 2, three = 3 ;
  <p>Example : </P>
  
  ```
    //Goble Scope
    var studentAge = 25;
    function GetAge(){
      //Function scope
      var studentAge = 20;
      console.log("FunctionScope "+studentAge)
    }
    GetAge()
    console.log("GobleScope "+studentAge)
  ```
  ``` 
  OutPut :
  FunctionScope 20
  GobleScope 25
  ```
</div>
