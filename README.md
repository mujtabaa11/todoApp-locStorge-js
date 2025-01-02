# Task Manager

## Overview

This project is a task manager that allows users to add, update, and delete tasks. Tasks are saved to `localStorage`, so they persist even after the page is refreshed. The task management interface provides forms for creating and editing tasks, and a display area for viewing and interacting with the tasks.

## Features

- **Add New Task**: Users can add a new task by filling out a form with the title, date, and description.
- **Edit Existing Task**: Users can edit an existing task by clicking the "Edit" button next to it.
- **Delete Task**: Users can delete a task by clicking the "Delete" button.
- **Confirm Close**: If the user tries to close the form with unsaved changes, they are prompted with a confirmation dialog.

## Technologies Used

- **HTML**: Structure and form for task input and task list display.
- **CSS**: Styling for the task form and task list.
- **JavaScript**: Manages the task data, task interactions (add, update, delete), and handles form validation and state persistence via `localStorage`.

## Project Structure

1. **HTML (`index.html`)**: Contains the structure of the task form, task list, and confirmation dialog.
2. **CSS (`styles.css`)**: Provides styling for the task form and task list layout.
3. **JavaScript (`script.js`)**: Manages the logic for adding, editing, deleting tasks, and interacting with `localStorage`.

## Installation

### Prerequisites

- A browser to view and interact with the task manager.

### Steps

1. **Clone the Repository** (or download the files):
    ```bash
    git clone <repository_url>
    ```

2. **Open the Project**:
    - Open the `index.html` file in your browser.

---

## How It Works

1. **Task Form**: 
   - The form allows users to input the title, date, and description for the task. Upon form submission, a task is either added or updated, and the task list is updated accordingly.
   - When a user tries to close the form with unsaved changes, a confirmation dialog is shown to ensure they don't lose their data.

2. **Task List**: 
   - Each task is displayed with its title, date, and description. The user can edit or delete each task.
   - Tasks are stored in `localStorage`, and the page is updated each time a change is made.

3. **Task Edit**:
   - When a task is edited, the form is populated with the existing task data. The "Add Task" button changes to "Update Task" to reflect the editing process.

4. **Task Deletion**:
   - When a task is deleted, the task is removed from both the DOM and `localStorage`.

---

## Features in Detail

- **Task Management**: Add new tasks or update existing tasks with a title, date, and description.
- **Form Handling**: The form is hidden or shown based on user interactions. The user is prompted with a confirmation dialog if they try to close the form with unsaved changes.
- **Persistence**: All tasks are saved in `localStorage` and persist across page reloads.
- **Responsive Design**: The application is designed to be responsive and works well on various screen sizes.

---

## License

This project is open-source and available under the [MIT License](./LICENSE).

---

## Future Enhancements

- **Due Date Notifications**: Add notifications or alerts for upcoming due dates.
- **Priority Levels**: Implement priority levels for tasks (e.g., High, Medium, Low).
- **Task Categories**: Add the ability to categorize tasks (e.g., Work, Personal, etc.).

---

Feel free to reach out if you have any questions or suggestions!
