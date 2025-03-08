# Basic Streamlit Setup & Authentication

Welcome to the **Basic Streamlit Setup & Authentication** module for the **Performance Management System**. This document explains how to set up a basic Streamlit application and implement authentication with role-based access using Streamlit-Authenticator.

---

## Overview

The purpose of this module is to lay the groundwork for our Performance Management System by:
- **Setting up a basic Streamlit app** that serves as the foundation for our project.
- **Implementing user authentication** using Streamlit-Authenticator.
- **Supporting role-based access** for three distinct roles: Management, Leads, and Employees.
- **Preparing the project structure** for open-source collaboration on GitHub.

---

## Prerequisites

Before you begin, ensure you have:
- **Python 3.8+** installed.
- **pip** for managing Python packages.
- Basic familiarity with Python and Streamlit.
- A GitHub account for hosting the project and documentation.

---

## Step-by-Step Instructions

### 1. Create a New GitHub Repository
- Create a new repository on GitHub (e.g., `performance-management-system`).
- Clone the repository to your local machine.

### 2. Organize Your Project Structure
Set up the directory structure as follows:

pms/ ├── docs/ │ └── AuthenticationModule.md # (This documentation file) ├── app.py ├── requirements.txt └── README.md


### 3. Set Up a Virtual Environment
- Create and activate a Python virtual environment.
- This isolates your project's dependencies.

### 4. Install Required Packages
- Install Streamlit and Streamlit-Authenticator via pip.
- Update your `requirements.txt` to include these packages.

### 5. Implement Basic Authentication
- Use Streamlit-Authenticator to create a login interface.
- Define user roles (Management, Lead, Employee) and set up role-based UI rendering.
- Ensure proper session management for secure authentication.

### 6. Run the Application Locally
- Launch your app using Streamlit.
- Verify that the login page and role display function as expected.

---

## What’s Next?

After successfully setting up authentication:
- We will extend the system to include KRA management.
- Role-based feedback forms will be created for self-assessment and evaluation.
- Finally, we’ll integrate LangChain and an LLM for AI-powered appraisal analysis.

---

## Contribution & Further Enhancements

As an open-source project, contributions are welcome! We encourage developers to extend this module with features such as:
- Enhanced security (e.g., password hashing, secure cookie management).
- Improved user interface designs.
- Integration with external identity providers.


---

