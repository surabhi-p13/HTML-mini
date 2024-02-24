# HTML-mini
A mini project of creating registration form using HTML
      <!DOCTYPE html>
<html>
  <head>
    <title>Hello, World!</title>
    <link rel="stylesheet" href="styles.css" />
  </head>
  <body>
      <h4>Registration Form</h4>
      <br>
      <form>
      <input type="text"placeholder="Enter your full name">
      <br>
      <br>
      <input type="password"placeholder="Password">
      <br>
      <br>
      <input type="text"placeholder="Contact info">
      <br>
      <br>
      <input type="text"placeholder="Email ID">
      <br>
      <br>
      <select name="City"id="City">
        <option value="Select">Select</option> 
        <option value="Delhi">Delhi</option>
        <option value="Goa">Goa</option>
        <option value="Mumbai">Mumbai</option>
        <option value="Bangalore">Bangalore</option>
        <option value="Kerala">Kerala</option>
      </select>
      <br>
      <br>
      <select name="Country"id="Country">
        <option value="Select">Select</option>
        <option value="America">America</option>
        <option value="Brazil">Brazil</option>
        <option value="Canada">Canada</option>
        <option value="Isreal">Isreal</option>
        <option value="India">India</option>
      </select>
      <br>
      <br>
      <h4>Type of course</h4>
      <label for="100">
        <input type="radio" value="Basic/Beginner" name=class id="100">Basic/Beginner
      </label>
      <br>
      <label for="101">
        <input type="radio"value="Intermediate"name="class" id="101">Intermediate
      </label>
      <br>
      <label for="102">
        <input type="radio"value="Professional"name="Professional" id="102">Professional
      </label>
      <br>
      <br>
      <h4>Courses list</h4>

      <label for="111">
        <input type="checkbox"value="Java"name="list" id="111">Java
      </label>
      <br>
      <label for="112">
        <input type="checkbox"value="AI"name="list" id="112">AI
      </label>
      <br>
      <label for="113">
        <input type="checkbox"value="Cloud Computing"name="list" id="113">Cloud Computing
      </label>
      <br>
      <label for="114">
        <input type="checkbox"value="MySQL"name="list" id="114">MySQL
      </label>
      <br>
      <br>
      <br>
      <h4>Feedback Form</h4>
      <textarea name="Feedback"id="1111"placeholder="Please provide your feedback" rows=7></textarea>
      <br>
      <br>
      <br>
      <input type="Submit"value="Submit">
      </form>
      
  </body>
</html>
