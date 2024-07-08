# coding-tasks
# Sticky Notes Project

## Description

The Sticky Notes project is a web application built using Django that allows users to create, view, edit, and delete notes. This project is a practical exercise in learning Django, a popular web framework for Python. It covers key aspects such as URL routing, views, templates, and models. Understanding these concepts is crucial for developing web applications efficiently.

## Table of Contents

- [Description](#description)
- [Installation](#installation)
- [Usage](#usage)
- [Features](#features)
- [Contributing](#contributing)
- [License](#license)

## Installation

To set up the Sticky Notes project on your local machine, follow these steps:

1. **Clone the repository:**
    ```bash
    git clone https://github.com/your-username/sticky_notes.git
    cd sticky_notes
    ```

2. **Create and activate a virtual environment:**
    ```bash
    python -m venv venv
    source venv/bin/activate # On Windows use `venv\Scripts\activate`
    ```

3. **Install dependencies:**
    ```bash
    pip install -r requirements.txt
    ```

4. **Apply migrations:**
    ```bash
    python manage.py migrate
    ```

5. **Run the development server:**
    ```bash
    python manage.py runserver
    ```

6. **Access the application:**
    Open your web browser and navigate to `http://127.0.0.1:8000`.

## Usage

### Creating a Note
1. Navigate to the home page.
2. Click on "Create Note".
3. Fill in the note details and click "Save".

### Viewing Notes
1. Navigate to the home page.
2. All notes are listed with options to view, edit, or delete.

### Editing a Note
1. Click on the "Edit" button next to the note you want to edit.
2. Update the note details and click "Save".

### Deleting a Note
1. Click on the "Delete" button next to the note you want to delete.
2. Confirm the deletion.

## Features

- **User Authentication:** Secure login and registration system.
- **CRUD Operations:** Create, read, update, and delete notes.
- **Responsive Design:** Mobile-friendly interface.
- **Search Functionality:** Quickly find notes.

## Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes.
4. Commit your changes (`git commit -m 'Add some feature'`).
5. Push to the branch (`git push origin feature-branch`).
6. Open a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more information.
