# Task Tracker

A simple, client-side web application for tracking time spent on tasks, managing projects, setting goals, and generating reports. All data is stored locally in your browser.

## Features

* **Task Tracking:** Start and stop timers for tasks, with real-time duration display.
* **Project Organization:** Categorize tasks under different projects for better organization.
* **Goal Management:** Set time-based goals (daily, weekly, monthly) for specific projects or general work, with visual progress indicators.
* **Date Navigation:** Easily navigate through days to view past and current task entries.
* **Advanced Reporting:** Generate detailed reports based on projects and custom date ranges.
* **Local Data Persistence:** All your data (tasks, projects, goals) is automatically saved in your browser's local storage.
* **Data Export:** Export your tracked time entries, goals, or projects as CSV or JSON files.
* **Responsive UI:** Designed to work seamlessly across various devices (desktops, tablets, mobile phones).
* **Intuitive User Experience:** Custom modals for input and confirmation, and toast notifications for instant feedback.

## Technologies Used

* **HTML5:** Structure of the web application.
* **Tailwind CSS:** A utility-first CSS framework for rapid and responsive styling.
* **JavaScript (ES6+):** Core logic for task tracking, data management, and UI interactions.
* **Font Awesome:** For various icons used throughout the application.

## Getting Started

To run this application locally, simply follow these steps:

1.  **Clone the repository (or download the `timetrack.html` file):**

    ```bash
    git clone [https://github.com/your-username/task-tracker.git](https://github.com/your-username/task-tracker.git)
    cd task-tracker
    ```

2.  **Open `timetrack.html` in your web browser:**
    You can simply double-click the `timetrack.html` file, or open it via your browser's "File > Open File" menu.

That's it! The application runs entirely in your browser, and all your data will be saved locally.

## Usage

1.  **Start a Task:**
    * Enter a description in the "What are you working on?" input field.
    * (Optional) Select an existing project from the dropdown or create a new one.
    * Click the "Play" button (▶) to start the timer.
    * Click the "Pause" button (⏸) to stop the timer.

2.  **Manage Projects:**
    * Click the "plus" icon next to "Projects" to create a new project.
    * Edit or delete existing projects using the pencil and trash icons.

3.  **Set Goals:**
    * Click the "plus" icon next to "Goals" to set a new goal.
    * Define the goal name, target hours, frequency (daily, weekly, monthly), and an optional end date.
    * Goals can be linked to specific projects.
    * Edit or delete existing goals using the pencil and trash icons.

4.  **View Reports:**
    * Click the "Advanced Reports" button to open the reporting modal.
    * Filter reports by project and date range.
    * Click "Generate Report" to see a summary of your tracked time.

5.  **Export Data:**
    * Click the "Export Data" button.
    * Choose the type of data to export (Time Entries, Goals, or Projects).
    * Select the export format (CSV or JSON).
    * For time entries, you can choose to export all or filtered entries (based on the current report criteria).
