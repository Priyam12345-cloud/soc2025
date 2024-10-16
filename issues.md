# Issues: 
### 1.Render Projects from Backend CSV

**Description:**
Projects tab should load and display all projects from a backend CSV file with accurate details and in the correct order.

**Steps:**
1. Create a backend API to serve project data from the CSV.
2. Fetch the data on the frontend when loading the Projects tab.
3. Display each project with correct details (title, description, etc.).
4. Ensure projects are sorted correctly (e.g., by date or status).
5. Add error handling for empty or invalid CSV data.

### 2.Image Not Showing Up on the Project Page

**Description:**
Images in the project are not rendering or appearing on the frontend. This could be due to incorrect file paths, missing images, or issues with the image component on the frontend.

**Steps to Reproduce:**
1. Visit the relevant page where the image should appear.
2. Check the image tag and inspect the source using the browser’s Developer Tools (Inspect > Network tab).

### 3.Missing "Forgot Password" Option for Account Recovery

**Description:**
There is no "Forgot Password" or "Forgot Username" option available, preventing users from recovering their accounts if they forget their login credentials.

**Steps to Reproduce:**
1. Attempt to log in to the website.
2. Observe that there is no "Forgot Password" or "Forgot Username" option for account recovery.


### 4.Form Validation Not Triggering

**Description:**
Form validation errors are not displayed when submitting invalid data, leading to unhandled errors and poor user experience.

**Steps to Reproduce:**
1. Visit any form page (e.g., registration or login).
2. Submit the form with invalid or empty fields.
3. Observe that no validation feedback is shown to the user.
