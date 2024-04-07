<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Document</title>
    <link rel="stylesheet" href="AA.css">

  </head>
  <body>
    <form action="empid">
      <fieldset>
        <h1>Employee Details</h1>
        <legend class="container">Employee Application Form</legend>
        Employee ID : <input type="text" placeholder="Employee ID" required/>
        <p>First Name : <input type="text" placeholder="Firstname" required/></p>
        <p>Last Name : <input type="text" placeholder="Lastname" required/></p>
        <p>Date Of Birth: <input type="date" /></p>
        <p>
          Gender : <input type="radio" name="#" required/>Male
          <input type="radio" name="#" required/>Female
        </p>
        <p>E-mail : <input type="email" placeholder="Enter the email" required/></p>
        <p>
          Mobile No :
          <input type="text" name="" id="" placeholder="Enter the numberr" required />
        </p>
        <p>Designation : <input type="text" placeholder="Designation" required/></p>
        
        <p><input type="file" name="" id="" required />(Less then 50kb)</p>

        Address :
        <p>
          <textarea
            name=""
            id=""
            cols="30"
            rows="10"
            placeholder="Enter the Address........"
          required></textarea>
        </p>

        <button>Submit</button>
      </fieldset>
    </form>
  </body>
</html>



-----------------------------------------------------------------------------------------------------
CSS




/* Apply general styles */
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f4f4f4;
  }
  
  form {
    width: 70%; /* Decreased width */
    margin: 20px auto;
    background-color: #fff;
    padding: 15px; /* Decreased padding */
    border-radius: 5px;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
  }
  
  h1 {
    text-align: center;
  }
  
  fieldset {
    border: none;
  }
  
  legend {
    font-size: 1.2em;
    font-weight: bold;
  }
  
  input[type="text"],
  input[type="email"],
  input[type="date"],
  input[type="file"],
  textarea {
    width: calc(100% - 22px); /* Adjusted width to accommodate padding and border */
    padding: 8px; /* Decreased padding */
    margin-bottom: 10px;
    border: 1px solid #ccc;
    border-radius: 5px;
    box-sizing: border-box;
  }
  
  input[type="radio"] {
    margin-right: 8px; /* Decreased margin */
  }
  
  button {
    background-color: #007bff;
    color: #fff;
    border: none;
    padding: 10px 15px; /* Decreased padding */
    border-radius: 5px;
    cursor: pointer;
  }
  
  button:hover {
    background-color: #0056b3;
  }
  
  /* Responsive styles */
  @media screen and (max-width: 600px) {
    form {
      width: 90%;
    }
  }
  
