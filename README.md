# Job Application Tracker

A modern, lightweight, and responsive web application designed to help job seekers organize their job search. This tool provides a centralized dashboard to track applications, monitor statuses (Interviewing, Offer, Rejected), and visualize success metrics with real-time statistics.

## Features

* **Visual Dashboard:** View key metrics at a glance, including Total Applications, Interview Count, Response Rate, and Success Rate.
* **Advanced Analytics:**
    * **Salary Insights:** Tracks average expected vs. offered salaries and total potential income.
    * **Timeline:** Tracks applications per week/month and days since the last application.
    * **Location Analysis:** Automatically groups applications by location.
* **Application Management:**
    * Add detailed entries (Company, Job Title, Salary Range, Link, Notes).
    * Update statuses (Applied ➝ Interviewing ➝ Offer ➝ Accepted/Rejected).
    * Log specific salary offers when statuses are updated.
* **Search & Filter:** Instantly filter applications by status or search by keyword (Company, Title, Location).
* **Bulk Actions:** Delete multiple selected applications at once.
* **Modern UI:** Built with a "Glassmorphism" design aesthetic using CSS variables, gradients, and backdrop filters.
* **Responsive:** Fully functional on desktop and mobile devices.

##  Getting Started

Since this project is built with JavaScript, HTML, and CSS, there are no build steps or complex dependencies required.

### Prerequisites
* A modern web browser (Chrome, Firefox, Safari, Edge).

### Installation
1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/yourusername/job-application-tracker.git](https://github.com/yourusername/job-application-tracker.git)
    ```
2.  **Navigate to the project folder:**
    ```bash
    cd job-application-tracker
    ```
3.  **Launch the App:**
    Simply open the `index.html` file in your web browser.

## echnologies Used

* **HTML5:** Semantic structure.
* **CSS3:** Flexbox, Grid, Linear Gradients, and Backdrop Filters for styling.
* **JavaScript (ES6+):** DOM manipulation, array filtering/mapping for statistics, and event handling.

## Project Structure

```text
/
├── index.html      # Main HTML structure
├── styles.css      # Styling, animations, and responsive design
└── app.js          # Logic for state management, rendering, and calculations
