<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Front-end Developer Job Form</title>
  <link rel="stylesheet" href="styles.css" />
</head>
<body>
  <header>
    <h1 id="title">Front-end developer job form</h1>
    <p id="description">Please fill out the application form to apply for the job</p>
  </header>

  <main>
    <form id="survey-form">
      <label for="name" id="name-label">Name</label>
      <input type="text" id="name" placeholder="Input full name here!" required />

      <label for="email" id="email-label">Email</label>
      <input type="email" id="email" placeholder="example@gmail.com" required />

      <label for="number" id="number-label">Work experience (years)</label>
      <input type="number" id="number" placeholder="3" min="3" max="120" />

      <label for="dropdown">Education</label>
      <select id="dropdown">
        <option disabled selected value="">Select Your Education</option>
        <option value="middle">Middle</option>
        <option value="matric">Matric</option>
        <option value="intermediate">Intermediate</option>
        <option value="bachelor's degree">Bachelor's Degree</option>
        <option value="master's degree">Master's Degree</option>
      </select>

      <p>Gender</p>
      <label for="male"><input class="inline" type="radio" id="male" name="gender" value="male" /> Male</label>
      <label for="female"><input class="inline" type="radio" id="female" name="gender" value="female" /> Female</label>
      <label for="other"><input class="inline" type="radio" id="other" name="gender" value="other" /> Rather not</label>

      <p>Which of the following do you have expertise in?</p>
      <label for="first"><input class="inline" type="checkbox" id="first" value="first" /> Front-end Projects</label>
      <label for="second"><input class="inline" type="checkbox" id="second" value="second" /> HTML, CSS, JavaScript Challenges</label>
      <label for="third"><input class="inline" type="checkbox" id="third" value="third" /> Git and Github Collaboration</label>
      <label for="fourth"><input class="inline" type="checkbox" id="fourth" value="fourth" /> Additional Courses</label>
      <label for="fifth"><input class="inline" type="checkbox" id="fifth" value="fifth" /> React Js Experience</label>

      <label for="textarea">Provide a bio</label>
      <textarea id="textarea" placeholder="Share your experience with us" rows="3" cols="30"></textarea>

      <input type="submit" id="submit" value="Submit" />
    </form>
  </main>
</body>
</html>
