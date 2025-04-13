# CSS-Assignment-1
HTML Code (index.html)
<!DOCTYPE html>
<html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    
    <title>Advanced HTML5 Elements and Forms</title>
    
    <meta name="description" content="An example of advanced HTML5 elements and forms">
    
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CSS Example</title>
  <link rel="stylesheet" href="style.css">
  </head>  
<body>
  <h1 class="header">My CSS Webpage Example</h1>
    <p id="paragraph">This space is for any Text Paragraph.</p>
     <img src="https://images.pexels.com/photos/3184289/pexels-photo-3184289.jpeg?auto=compress&cs=tinysrgb&dpr=2&h=750&w=1260" alt="Example Image">
  <div class="container">
    <p>This is a container where texts are kept</p>
  </div>
       <ol type="I">
      <li>Item 1</li>
      <li>Item 2</li>
      <li>Item 3</li>
    </ol>
    <table>
      <caption>Contacts</caption>
      <thead>
        <tr>
          <th>Name</th>
          <th>Address</th>
          <th>Mobile</th>
          <th>Email</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td>Gabriel king</td>
          <td>2 jeth St</td>
          <td>+234-501-4430</td>
          <td>gabkg@ppp.com</td>
        </tr>
        <tr>
          <td>Mary Moses</td>
          <td>91 jum St</td>
          <td>+254-087-8774</td>
          <td>marses@uuu.com</td>
        </tr>
        <tr>
          <td>Knot Jessy</td>
          <td>6 gri St</td>
          <td>+233-651-0893</td>
          <td>jekot.smith@cdr.com</td>
        </tr>
        <tr>
          <td>Paul Henry</td>
          <td>231 hop St</td>
          <td>+234-986-0222</td>
          <td>phenry@dgg.com</td>
        </tr>
        <tr>
          <td>Floral ken</td>
          <td>7 mop St</td>
          <td>+254-528-0988</td>
          <td>kenflo@htr.com</td>
        </tr>
      </tbody>
    </table>
    
     <form>
      <h2>Registration Form</h2>
      <label for="name">Name:</label>
      <input type="text" id="name" name="name" required placeholder="Enter your name">
      
      <label for="email">Email:</label>
      <input type="email" id="email" name="email" required placeholder="Enter your email">
      
      <label for="password">Password:</label>
      <input type="password" id="password" name="password" required placeholder="Enter your password">
      
      <label for="date">Date:</label>
      <input type="date" id="date" name="date" required>
      
      <label for="country">Country:</label>
      <select id="country" name="country">
        <option value="">Select a country</option>
        <option value="Kenya">Kenya</option>
        <option value="Nigeria">Nigeria</option>
        <option value="Ghana">Ghana</option>
      </select>
      
      <label for="gender">Gender:</label>
      <input type="radio" id="male" name="gender" value="male">
      <label for="male">Male</label>
      <input type="radio" id="female" name="gender" value="female">
      <label for="female">Female</label>
      
      <label for="hobbies">Hobbies:</label>
      <input type="checkbox" id="reading" name="hobbies" value="reading">
      <label for="reading">Reading</label>
      <input type="checkbox" id="writing" name="hobbies" value="writing">
      <label for="writing">Writing</label>
      <input type="checkbox" id="coding" name="hobbies" value="coding">
      <label for="coding">Traveling</label>
       <button class="button">Register</button>
      <footer class="footer">
    <p>&copy; 2025 Alaba webpage</p>
</footer>
    </form>
</body>
</html>

CSS Code (style.css)
.header {
  color: #00698f;
  font-family: Arial, sans-serif;
  font-size: 36px;
  margin-bottom: 20px;
}
#paragraph {
  color: #666;
  font-family: Georgia, serif;
  font-size: 18px;
  line-height: 1.5;
}
.image {
  width: 100%;
  height: auto;
  margin: 20px 0;
  border: 1px solid #ddd;2
  padding: 10px;
}
1.container {
  background-color: #f0f0f0;
  padding: 20px;
  border: 1px solid #ddd;
  margin-bottom: 20px;
}
.list {
  list-style: none;
  padding: 0;
  margin: 0;
}
.list li {
  padding: 10px;
  border-bottom: 1px solid #ddd;
}
.list li:last-child {
  border-bottom: none;
}
.button {
  background-color: #00698f;
  color: #fff;
  padding: 10px 20px;
  border: none;
  border-radius: 5px;
  cursor: pointer;
}

.button:hover {
  background-color: #004c6b;
}
.footer {
  background-color: #333;
  color: #fff;
  padding: 10px;
  text-align: center;
  clear: both;
}
body {
  font-family: Arial, sans-serif;
  margin: 0;
  padding: 0;
}

h1, h2, h3 {
  font-weight: bold;
  margin-bottom: 10px;
}
a {
  text-decoration: none;
  color: #00698f;
}

a:hover {
  color: #004c6b;
}


