# Organization Management System in Python

## Project Overview

This project is a console-based **Organization Management System** developed in Python. It allows users to manage staff records within three types of organizations: **Hospital**, **School**, and **Company**. The system supports viewing staff information, modifying their departments, and searching for staff by name, all through an intuitive menu-driven interface.

## Features

- View staff members and their departments by organization
- Modify a staff member’s department
- Search for a staff member by name (case-insensitive)
- User-friendly main menu navigation
- Graceful handling of invalid input

## Technologies Used

- Python 3
- Adherence to [PEP 8](https://peps.python.org/pep-0008/) standards for code quality and readability

## How It Works

The system is built using modular functions:

- `display_staff(organization)`: Displays staff information for the selected organization.
- `modify_staff_department(organization)`: Allows updating the department of a staff member.
- `search_staff_by_name(organization)`: Searches for staff by name and displays their details.
- `main_menu()`: Handles user navigation across tasks.

## Error Handling

- Invalid menu options are caught and prompt the user to retry.
- Staff searches and modifications display clear messages when names are not found.
- Case-insensitive name matching improves user experience.

## User Experience

- Clear instructions and prompts at each step
- Informative error messages
- Automatic return to the main menu after each action

## Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/organization-management-system.git
   cd organization-management-system
