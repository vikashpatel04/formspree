# Simple HTML Project with Tailwind CSS and Formspree

This is a simple project using a basic HTML file styled with Tailwind CSS via CDN, and includes a contact form powered by Formspree for handling form submissions.

---

### In hurry..!

Go stright to [Usage](#usage) to use this code


## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Setup](#setup)
- [Usage](#usage)
- [Contributing](#contributing)

## Introduction

This project demonstrates how to use Tailwind CSS via CDN in a simple HTML file and integrate a contact form that submits data to Formspree. It's perfect for small projects, landing pages, or static websites that need quick styling and form handling.

## Features

- **Tailwind CSS via CDN**: Easily style your HTML with Tailwind CSS without any build tools.
- **Formspree Integration**: Handle form submissions without needing a backend.

## Setup

Integrate Formspree into your HTML form with these steps:

1. **Sign up or Log in to Formspree**:
   - Go to [Formspree](https://formspree.io/) and create an account or log in.

2. **Create a New Form**:
   - Click "Create a New Form", enter a name, and click "Create".

3. **Get Formspree Endpoint**:
   - Copy the provided Formspree endpoint URL (`https://formspree.io/f/your-form-id`).

4. **Update Your HTML Form**:
   - Set the `action` attribute of your `<form>` tag to the Formspree endpoint.

     ```html
     <form action="https://formspree.io/f/your-form-id" method="POST">
         <!-- Your form fields -->
     </form>
     ```

5. **Customize and Deploy**:
   - Customize your form and deploy your HTML file with the integrated Formspree form.

6. **Manage Submissions**:
   - Log in to Formspree to view and manage form submissions.

This setup allows handling form submissions securely without backend setup, ideal for static websites.


## Usage

To use this project, simply clone the repository and open the `index.html` file in your web browser.

```bash
git clone https://github.com/vikashpatel04/formspree.git

cd formspree
```

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any improvements or bug fixes.