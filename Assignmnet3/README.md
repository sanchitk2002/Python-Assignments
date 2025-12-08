# Flask Web Server with MongoDB Atlas Integration

This project is a Flask-based web application developed to fulfill the given assignment requirements. It demonstrates backend API development, file-based data handling, frontend form submission, and cloud database integration using MongoDB Atlas.

---

## Project Description

The application consists of two main features:

### 1. REST API (`/api` Route)

A REST API endpoint is created using Flask.  
When the `/api` route is accessed, the server:

- Reads data from a backend JSON file.
- Converts the file content into a JSON list.
- Returns the JSON data as an API response.

This feature demonstrates how data can be served from a backend file through an API.

---

### 2. Frontend Form with MongoDB Atlas

A simple HTML form is created that allows users to:

- Enter their name and email.
- Submit the form to the Flask backend.

On form submission:

- The data is stored in **MongoDB Atlas**.
- On **successful submission**, the user is redirected to a page showing:

> ✅ **"Data submitted successfully"**

- If there is an error:
  - The error message is displayed on the same page without redirection.

This ensures proper validation and user feedback.

---

## Screenshots of the Working Project

### Home Page (Form Page)

![Form Page](screenshots/form_page.png)

---

### Validation Error (Empty Field Check)

![Validation Error](screenshots/validation_error.png)

---

### Success Page After Submission

![Success Page](screenshots/success_page.png)

---

### API JSON Response (`/api`)

![API Response](screenshots/api_response.png)

---

### Data Stored in MongoDB Atlas

![MongoDB Data](screenshots/mongodb_data.png)

---

## Conclusion

This project successfully demonstrates:

- Flask REST API functionality
- Reading and serving data from a backend file
- Frontend form submission
- MongoDB Atlas dat
