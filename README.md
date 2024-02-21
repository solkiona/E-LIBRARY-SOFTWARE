
---

# E-Read Library

![Project Logo](static/assets/images/EreadLogo.png)

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Deployment](#deployment)
- [Contributing](#contributing)
- [License](#license)

## Introduction

The E-Read Library is a web application designed to provide a user-friendly platform for managing and organizing your e-book collection. With features such as user authentication, a dashboard for book management, and an intuitive interface, this app is tailored for book enthusiasts and collectors.

## Features

- **User Authentication:** Secure user accounts with login functionality.
- **Dashboard:** An interactive dashboard for managing your e-book collection.
- **Book Details:** View detailed information about each book, including title, author, and cover image.
- **Favorites:** Mark and organize your favorite books for quick access.
- **Search and Filter:** Easily find books using the search functionality and filter options.
- **File Upload:** Upload and associate e-book files with corresponding entries.

## Installation

To run the E-Read Library locally, follow these steps:

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/E-Read-Library.git
   ```

2. Install dependencies:

   ```bash
   cd E-Read-Library
   pip install -r requirements.txt
   ```

3. Set up environment variables:

   Create a `.env` file in the project root with the following content:

   ```env
   SECRET_KEY=your_secret_key
   ```

   Replace `your_secret_key` with a secure secret key for Flask.

4. Run the application:

   ```bash
   python3 app.py
   ```

   Open your browser and navigate to [http://localhost:5000](http://localhost:5000).

## Usage

1. **Register/Login:**
   - Create an account or log in with existing credentials.

2. **Dashboard:**
   - Explore your personalized dashboard with book listings.

3. **Book Management:**
   - Add, edit, or delete books from your collection.

4. **Favorites:**
   - Mark books as favorites for quick access.

5. **Search and Filter:**
   - Use the search bar and filter options to find specific books.

6. **File Upload:**
   - Upload e-book files and associate them with relevant book entries.

## Deployment

This project is ready for deployment on platforms like Render. Ensure that you have Gunicorn installed and update the `requirements.txt` file accordingly. Use the following command to start the server:

```bash
gunicorn -w 4 -b 0.0.0.0:5000 app:app
```

## Contributing

Contributions are welcome! Feel free to open issues, submit pull requests, or provide feedback.

## License

This project is licensed under the [MIT License](LICENSE).

---

Project Developed by:
**ADULE SOLOMON ONWUKWE**
_solkiona@gmail.com_