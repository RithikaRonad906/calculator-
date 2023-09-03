**Student Registration Form HTML Program**

**Description:**
This HTML program creates a simple student registration form with various input fields for capturing the student's information. The form includes fields for the student's first name, last name, address, date of birth (DOB), gender, standard, and subjects of interest. The form also includes a submit button to submit the data.

**Readme File for Student Registration Form:**

**1. HTML File:**
- The main HTML file is named `index.html`.
- The file uses the `<!DOCTYPE html>` declaration to specify the HTML version.
- The page is in English, as indicated by the `lang="en"` attribute in the `<html>` tag.
- The character set is set to UTF-8 (`<meta charset="UTF-8">`) to support various characters.

**2. Viewport Settings:**
- The viewport meta tag (`<meta name="viewport" content="width=device-width, initial-scale=1.0">`) is included to ensure the page scales correctly on different devices.

**3. Title:**
- The title of the page is set to "Student Registration Form" (`<title>Student Registration Form</title>`).

**4. Styling:**
- The background color of the page is set to light green using inline CSS (`<body style="background-color: lightgreen;">`).

**5. Heading:**
- The page includes an `<h1>` heading that says "Student Registration Form." The heading is centered and underlined (`<h1 align="center"><u>Student Registration Form</u></h1>`).

**6. Form Elements:**
- The form is enclosed within the `<form>` tag (`<form> ... </form>`).
- The form includes the following input fields:
  - First Name: `<input type="text" placeholder="First name">`
  - Last Name: `<input type="text" placeholder="Last name">`
  - Address: `<textarea rows="2" cols="50" name="comment" form="usrform">Enter text here...</textarea>`
  - Date of Birth (DOB): `<input type="date" name="DOB">`
  - Gender: Radio buttons for Male, Female, and Other.
  - Select Standard: A drop-down list (`<select>`) with options for different standards (1st to 5th).
  - Select Subject: Checkboxes for various subjects (Maths, English, Science, History, Geography, and French).

**7. Form Submission:**
- The form includes a submit button (`<input type="submit" value="submit">`) that users can click to submit the data.

**Note:**
- This is a static HTML form, and it does not have any server-side processing to handle form submissions or store data.
- If you want to handle form submissions, you'll need to use a server-side script (e.g., PHP, Python, etc.) to process the form data and store it in a database or perform any other required actions.

**Instructions:**
1. Download the `index.html` file.
2. Open the `index.html` file using any modern web browser.
3. Fill in the student's information in the form fields.
4. Select the appropriate options for gender, standard, and subjects of interest.
5. Click the "submit" button to submit the form (Note: This won't perform any actual submission since there is no server-side handling in this static example).

Remember that this is just a basic HTML form template and may require further enhancements and server-side integration for practical use in a real-world scenario.