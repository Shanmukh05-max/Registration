# Registration Form

A simple and responsive **Registration Form** created using **HTML, CSS, and JavaScript**.  
This project collects user details such as name, roll number, phone number, email, and gender with basic form validation.

## Features

- User-friendly registration interface
- Input fields for:
  - First Name
  - Last Name
  - Roll Number
  - Phone Number
  - Email Address
  - Gender Selection
- HTML5 form validation
- Phone number validation using pattern matching
- Required field validation
- Submit and Reset buttons
- Success alert message after submission
- Simple and clean CSS styling

## Technologies Used

- **HTML5** – Structure of the registration form
- **CSS3** – Styling and layout design
- **JavaScript** – Form submission handling

## Project Structure

```
Registration-Form/
│
├── index.html
└── README.md
```

## How to Run the Project

1. Download or clone this repository.

2. Open the project folder.

3. Open `index.html` in any web browser.

4. Fill in the registration details and click the **Submit** button.

## Form Validation

The form includes:
- Mandatory field checking using `required`
- Email format validation using `type="email"`
- 10-digit phone number validation using:
  ```
  pattern="[0-9]{10}"
  ```

## Output

The form displays a registration interface where users can enter their details.  
After successful submission, a confirmation message appears:

```
Registration Successful!
```

## Future Improvements

- Add backend integration for storing user data
- Connect with a database
- Add password field and authentication
- Improve responsive design for mobile devices
- Add advanced JavaScript validation

## Author

Your Name

## License

This project is open-source and available for learning purposes.
