
# Invoices Dashboard

This project is a web-based invoices dashboard application that provides an interface for managing and viewing invoices. The application includes a sidebar for navigation, a main content area displaying invoice details, and functionalities for filtering and sorting invoices.

## Features

- **Sidebar Navigation:** The sidebar allows users to navigate between different sections like Dashboard, Sales, Purchase, Cash, Stock, Accounting, and Reports.
- **Invoice Management:** Users can view and manage invoices, including features like sorting by date, status, and amount.
- **Filtering:** Invoices can be filtered based on vessel name, status, priority, and date.
- **Search Functionality:** The search bar allows users to search for specific invoices.
- **Pagination:** Users can navigate through multiple pages of invoices.
- **Responsive Design:** The layout adjusts according to the screen size, making it accessible on both desktop and mobile devices.

## Technologies Used

- **HTML/CSS:** For structuring and styling the application.
- **JavaScript:** For interactivity, including sorting, filtering, and toggling the sidebar.
- **Google Fonts:** The application uses the 'Inter' font from Google Fonts.
- **jsPDF and jsPDF-AutoTable:** For generating PDF files from the invoices data.

## Project Structure

- **index.html:** The main HTML file that includes the structure of the dashboard.
- **styles/:** Contains the minified CSS files for global, sidebar, and main content styling.
- **script.min.js:** The minified JavaScript file that handles the interactivity of the dashboard.

## Usage

1. Clone the repository or download the project files.
2. Open `index.html` in your web browser to view the dashboard.
3. Interact with the dashboard using the sidebar, tabs, filters, and search functionalities.

## Sidebar Functionality

The sidebar can be toggled between an open and close state. When the screen width is less than 900px, the sidebar automatically collapses. The arrow button on the sidebar allows the user to manually open or close the sidebar.

## Tabs and Filters

- **Tabs:** The tabs allow users to switch between different invoice categories such as All Invoices, Overdue, In Progress, and Waiting.
- **Filters:** Users can filter invoices based on vessel name, status, priority, and date. The filter state is maintained and indicated with a notification badge.

## Sorting

The table can be sorted by clicking on the column headers. Sorting is available for the Details, Date, Status, and Amount columns.

## Search

The search functionality allows users to search for invoices by typing keywords into the search bar. The table dynamically updates to show matching results.

## License

This project is licensed under the MIT License.
