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
    <tr>
      <th >5</th>
      <td><a href="#que5">Explain the let variable?</a></td>
    </tr>
     <tr>
      <th >6</th>
      <td><a href="#que6">Explain the const variable?</a></td>
    </tr>
     <tr>
      <th >7</th>
      <td><a href="#que7">Different Data types in Javascript?</a></td>
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
  <b>Syntax</b><br/>
  <span>var "variableName";</span><br/>
  <span>var "variableName" = "value"</span><br/><br/>
  <b>Multiple variable declare</b><br/>
  <span> var one = 1, two = 2, three = 3 ;</span><br/>
  <br/>
    <span>Before declare we can use var variable is called <b>hoisting</b></span><br/>
  <span>Hoisting example below :</span>
  
  ```
    a = 10;
    console.log("value "+a)
    var a = 10
  ```
  ``` 
  OutPut :
  value 10
  ```
</div>
<div class="common" id="que5" >
  <h3>5. Explain the let variable?</h3>
  <ul>
    <li>let variable was introduced in 2015.</li>
    <li>let variable is a Block scope.</li>
    <li>Declare the let variable before you use it.</li>
  </ul>
 <b>Syntax</b><br/>
  <span>let "variableName";</span><br/>
  <span>let "variableName" = "value"</span><br/><br/>
  <b>Multiple variable declare</b><br/>
  <span> let one = 1, two = 2, three = 3 ;</span><br/>
  <br/>
    <span>If use let variable before declaring it gives a error <b>"Cannot access 'variableName' before initialization"</b></span><br/>
  <span>Example below :</span>
  
  ```
    a = 10;
    console.log("value "+a)
    let a = 10
  ```
  ``` 
  OutPut :
  "ReferenceError: Cannot access 'a' before initialization"
  ```
</div>
<div class="common" id="que6" >
  <h3>6. Explain the const variable?</h3>
  <ul>
    <li>const variable was introduced in 2015.</li>
    <li>const variable is a Block scope.</li>
    <li>The const variable value can't changed</li>
  </ul>
 <b>Syntax</b><br/>
  <span>const "variableName";</span><br/>
  <span>const "variableName" = "value"</span><br/><br/>
  <b>Multiple variable declare</b><br/>
  <span> const one = 1, two = 2, three = 3 ;</span><br/>
  <br/>
    <span>If we try to change the const variable value it gives a error <b>"TypeError: Assignment to constant variable."</b></span><br/>
  <span>Example below :</span>
  
  ```
    const name = "suraj"
    name = "vijay"
  ```
  ``` 
  OutPut :
  "TypeError: Assignment to constant variable."
  ```
</div>
<div class="common" id="que7" >
  <h3>7. Different Data types in Javascript?</h3>
  <br/>
  <b>Primitive data type</b><br/>
  1. Number 
2. String 
3. Boolean
4. Undefined
5. Null

</div>
