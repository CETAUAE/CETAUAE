# Alumni Registration Form

This project is a simple web-based Alumni Registration Form designed to collect personal and professional details, along with skill sets and areas of interest, from alumni. The form includes email verification using an OTP (One-Time Password) to ensure valid submissions.

## Features

- **Personal Details Collection**: Collects personal information such as name, date of birth, and gender.
- **Professional Details**: Captures professional information like current job title, company, and years of experience.
- **Skill Set and Area of Interest**: Allows users to input their skills and areas they are interested in.
- **Email Verification**: Implements OTP verification to ensure the authenticity of the provided email address.
- **Responsive Design**: The form is styled using basic CSS to be user-friendly and responsive.

## Technologies Used

- **HTML/CSS**: For creating the structure and styling of the form.
- **JavaScript**: For client-side interactivity, including sending OTP requests.
- **PHP**: Server-side scripting for handling OTP generation, email sending, and form submission.
- **GitHub Pages**: Hosting static files (HTML/CSS/JS).
- **SMTP Server**: For sending OTP emails (requires proper email configuration).

## Getting Started

To get a local copy up and running follow these simple steps.

### Prerequisites

- A web server with PHP support (e.g., [XAMPP](https://www.apachefriends.org/index.html), [WAMP](https://www.wampserver.com/en/), or [MAMP](https://www.mamp.info/en/)).
- Basic knowledge of web development and PHP.
- A GitHub account to use GitHub Pages for static hosting.

### Installation

1. **Clone the repository**:
    ```bash
    git clone https://github.com/your-username/alumni-registration-form.git
    ```
2. **Navigate to the project directory**:
    ```bash
    cd alumni-registration-form
    ```

3. **Set up a local server**:
    - Use XAMPP/WAMP/MAMP to run a local server.
    - Place the project files inside the `htdocs` folder (for XAMPP) or the equivalent for other servers.
    - Start the local server.

4. **Access the form**:
    - Open a web browser and navigate to `http://localhost/alumni-registration-form/alumni_registration.html`.

### Usage

1. **Fill in the Alumni Registration Form**: Enter your personal, professional, and other relevant details.
2. **Verify Email**: Click the "Send OTP" button to receive a One-Time Password on your email.
3. **Enter OTP**: Input the received OTP in the form to verify your email address.
4. **Submit**: Click the "Submit" button to complete the registration.

### Deployment

To deploy the static HTML, CSS, and JavaScript files online:

1. **Upload to GitHub Pages**:
    - Push the repository to GitHub.
    - In the repository settings, enable GitHub Pages.
    - Choose the `main` branch and set the source to the root directory.
    - Your site will be available at `https://your-username.github.io/alumni-registration-form/`.

2. **PHP Functionality**:
    - GitHub Pages only hosts static content. To use PHP (OTP verification), you need a PHP-supported hosting service (e.g., InfinityFree, Heroku, or any web hosting service that supports PHP).
    - Upload your files to the hosting service following their deployment instructions.

### Folder Structure

```plaintext
alumni-registration-form/
│
├── logo.png                    # Logo for the form header
├── alumni_registration.html    # Main HTML file for the form
├── send_otp.php                # PHP script to handle OTP generation and sending
├── submit_form.php             # PHP script to handle OTP verification and form submission
├── README.md                   # This README file
