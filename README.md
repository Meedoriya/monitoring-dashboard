# IT Monitoring Dashboard

## Overview
This project is an interactive, multi-page web application designed to monitor the state of IT infrastructure. It provides a user-friendly interface for tracking server statuses, viewing detailed server information, and submitting feedback. Built with HTML, CSS, and Bootstrap, the application is fully responsive and incorporates modern design practices.

## Features
### Completed Features:
1. **Multi-page Structure**:
   - **Home Page**: Displays overall infrastructure status with dynamic status cards.
   - **Details Page**: Provides a detailed view of server statuses in a table format with hover effects and pop-up modals.
   - **Contact Page**: Allows users to send feedback via a contact form with a loading animation.

2. **Interactive and Engaging Elements**:
   - Dynamic status updates using a loading spinner.
   - Hover effects for better user interaction.
   - Pop-up modal windows for detailed server information.

3. **Responsive Design**:
   - Adapts seamlessly to various screen sizes using Bootstrap's grid system and responsive utilities.

### Upcoming Enhancements:
2. **Enhanced Design and Visual Appeal**:
   - **Custom Themes**: Utilize Bootstrap’s SCSS variables to create a corporate or modern aesthetic theme.
   - **Icons and Images**: Add professional icons, illustrations, or background images.
   - **Dark Mode**: Implement a toggle for dark mode.

3. **Extended Features**:
   - **Search and Sort**: Add search and sorting functionality for the server table.
   - **Filtering**: Allow filtering servers by status (e.g., "All," "OK," "Error").
   - **Export Options**: Enable exporting the server table to CSV format.

4. **Integration and Real-World Simulation**:
   - **Data Fetching**: Connect the app to a mock API for dynamic data retrieval.
   - **Feedback Storage**: Simulate storing contact form submissions in localStorage or sending to an API.

5. **Additional Pages and Content**:
   - **About Page**: Explain the application's purpose and features.
   - **User Guide**: Add a step-by-step guide with screenshots.
   - **Analytics Dashboard**: Visualize server trends using charts (e.g., bar, pie, line).

6. **Advanced Interactivity**:
   - **Real-Time Notifications**: Notify users of server status changes.
   - **Live Chat**: Add a chat widget for support.
   - **Form Feedback Animation**: Enhance form submission feedback with animations.

7. **Usability and Accessibility**:
   - **Mobile-First Design**: Ensure every element is optimized for smaller screens.
   - **Accessibility Improvements**: Add ARIA roles, keyboard navigation, and focus management.
   - **Language Switcher**: Allow toggling between multiple languages.

8. **Deployment**:
   - Deploy the application using Netlify or GitHub Pages.
   - Use a custom domain for a professional look.

## Project Structure
```
/project-folder
├── index.html         # Home Page
├── details.html       # Details Page
├── contact.html       # Contact Page
├── css/
│   └── style.css      # Custom styles
└── assets/            # Images and additional assets (if needed)
```

## How to Use
1. Clone the repository and open the project in your preferred text editor or IDE.
2. Open the `index.html` file in a browser to view the Home Page.
3. Navigate to the other pages using the navbar links.
4. Interact with the dynamic elements such as cards, table rows, and contact form.

## Technologies Used
- **HTML**: For structuring the web pages.
- **CSS**: For styling and custom designs.
- **Bootstrap 5**: For responsive design and interactive components.
- **Font Awesome**: For icons used in status indicators.
- **JavaScript**: For interactive elements such as modals, spinners, and form submission.

## Pages Overview
### 1. Home Page (`index.html`)
- Displays the current status of the IT infrastructure.
- Includes two cards:
  - **General Status (Green)**: Indicates systems are fine.
  - **Critical Errors (Red)**: Highlights systems with issues.
- Hover effects for better user interaction.

### 2. Details Page (`details.html`)
- Provides a table of server statuses with columns:
  - Server Name
  - IP Address
  - Status (with icons).
- Includes:
  - Loading spinner when the table is being fetched.
  - Hover effects on table rows.
  - Modal pop-ups with detailed server information.

### 3. Contact Page (`contact.html`)
- Features a feedback form with fields for:
  - Name
  - Email
  - Message.
- Displays a loading spinner upon form submission.
- Alerts the user upon successful submission.

## How to Contribute
1. Fork the repository.
2. Create a feature branch (`git checkout -b feature-name`).
3. Commit your changes (`git commit -m 'Add feature'`).
4. Push to the branch (`git push origin feature-name`).
5. Open a Pull Request.

---
**Author**: Moldabayev Alibi
