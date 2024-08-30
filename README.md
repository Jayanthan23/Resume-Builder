# Resume Builder

A Django-based web application that allows users to create and download professional resumes. This project provides a user-friendly interface to input personal information, work experience, education, and skills, generating a well-formatted resume in PDF format.

## Features

- *User Authentication:* Secure user registration and login functionality.
- *Profile Management:* Users can create, edit, and delete their profiles.
- *Resume Creation:* Allows users to input their personal details, education, work experience, and skills.
- *PDF Generation:* Generates a downloadable PDF version of the resume based on the user's input.
- *Responsive Design:* Compatible with various devices for ease of use.

## Technologies Used

- *Frontend:* HTML, CSS, Bootstrap
- *Backend:* Django, Python
- *Database:* SQLite (default Django database)
- *PDF Generation:* WeasyPrint (or any other library you used)

## Installation

1. *Clone the repository:*

   bash
   git clone https://github.com/yourusername/resume-builder.git
   cd resume-builder
   

2. *Create a virtual environment:*

   bash
   python -m venv venv
   

3. *Activate the virtual environment:*

   - *Windows:*
     bash
     venv\Scripts\activate
     
   - *MacOS/Linux:*
     bash
     source venv/bin/activate
     

4. *Install the required dependencies:*

   bash
   pip install -r requirements.txt
   

5. *Apply migrations:*

   bash
   python manage.py migrate
   

6. *Run the development server:*

   bash
   python manage.py runserver
   

7. *Open the application:*

   Visit http://127.0.0.1:8000/ in your web browser.

## Usage

1. *Register* a new account or *log in* if you already have one.
2. Navigate to the *Profile* section to add or update your personal details.
3. Go to the *Resume Builder* section to input your education, work experience, skills, and other relevant details.
4. Click *Generate Resume* to create a PDF version of your resume, which you can download.

## Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository.
2. Create a new branch (git checkout -b feature-branch).
3. Commit your changes (git commit -m 'Add some feature').
4. Push to the branch (git push origin feature-branch).
5. Open a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Acknowledgments

- Thanks to the Django community for their excellent documentation and support.
- Inspiration for this project came from various online resources and tutorials.

