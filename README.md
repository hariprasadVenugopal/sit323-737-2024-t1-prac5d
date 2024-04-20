<b>SIT323/SIT737- Cloud Native Application Development</b>

<b>5.2D: Dockerization- Publishing the microservice into the cloud</b>

<ul>
      <li>Clone the repository.</li>
      <li>Run the command <b>docker compose up</b></li>
      <li>3 applications will be there, 3000, 3040, 3080 these are the exposed ports.</li>
      <li>Once the applications are ready try http://localhost:3080/crash to crash the application.</li>
      <li>Check the logs to verify application restart.</li>
</ul>

URL's

<ul>
      <li>For addition use http://localhost:3080/addTwoNumber?num1=100&num2=100 .</li>
      <li>For subtraction use http://localhost:3080/subTwoNumber?num1=100&num2=100 .</li> 
      <li>For multiplication use http://localhost:3080/mulTwoNumber?num1=100&num2=100 .</li> 
      <li>For division use http://localhost:3080/divTwoNumber?num1=100&num2=100 .</li>
      <li>For exponentiation use http://localhost:3080/expTwoNumber?num1=100&num2=100 .</li>
      <li>For square root use http://localhost:3080/sqTwoNumber?num1=100 .</li>
      <li>For modulo use http://localhost:3080/modTwoNumber?num1=100&num2=100 .</li>
      <li>For application crash use http://localhost:3080/crash .</li>
</ul>
