# CGPA Management System

A ReactJS application that implements a routing mechanism for managing and displaying student CGPA details with PDF download functionality.

## Features

- **Add CGPA**: Allows users to input student details and CGPA information
- **View CGPA**: Displays student CGPA information in a user-friendly interface
- **PDF Download**: Generate and download PDF reports of student CGPA data
- **Responsive Design**: Works seamlessly on desktop and mobile devices
- **Local Storage**: Data persistence using browser's localStorage

## Project Structure

```
src/
├── components/
│   ├── AddCGPA.jsx
│   └── ViewCGPA.jsx
├── App.jsx
├── App.css
├── index.css
└── main.jsx
```

## Components

### AddCGPA Component
- Form for entering student details (Name, ID, Semester)
- Dynamic subject management (Add/Remove subjects)
- Grade selection with automatic CGPA calculation
- Data validation and form submission
- Automatic navigation to View CGPA page after successful submission

### ViewCGPA Component
- Display list of all students with their CGPA data
- Detailed view of selected student's information
- Subject-wise grade breakdown in table format
- PDF generation and download functionality
- Delete student records functionality

## Technologies Used

- **React 19.1.1**: Frontend framework
- **React Router DOM**: Client-side routing
- **jsPDF**: PDF generation library
- **CSS3**: Styling with modern design patterns
- **LocalStorage**: Data persistence

## Installation & Setup

1. Navigate to the project directory:
   ```bash
   cd cpgacal
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Start the development server:
   ```bash
   npm run dev
   ```

4. Open your browser and navigate to `http://localhost:5173`

## Usage

### Adding CGPA Data
1. Click on "Add CGPA" in the navigation
2. Fill in student details (Name, ID, Semester)
3. Add subjects with their credits and grades
4. Click "Calculate CGPA" to see the calculated CGPA
5. Click "Save CGPA Data" to store the information

### Viewing CGPA Data
1. Click on "View CGPA" in the navigation
2. Select a student from the list to view their details
3. View subject-wise breakdown and overall CGPA
4. Click "Download PDF" to generate a PDF report

## Grade System

The application uses a 10-point grading system:
- A+: 10 points
- A: 9 points
- B+: 8 points
- B: 7 points
- C+: 6 points
- C: 5 points
- D: 4 points
- F: 0 points

## Features

- **Responsive Design**: Optimized for both desktop and mobile devices
- **Modern UI**: Clean and intuitive user interface
- **Data Validation**: Form validation to ensure data integrity
- **PDF Export**: Professional PDF reports with student details
- **Local Storage**: Data persists between browser sessions
- **Dynamic Forms**: Add/remove subjects as needed
- **Real-time Calculation**: Automatic CGPA calculation

## Browser Compatibility

- Chrome (recommended)
- Firefox
- Safari
- Edge

## Development

The application is built using Vite for fast development and hot module replacement. All components are functional components using React hooks for state management.

## License

This project is created for educational purposes as part of FEDF (Frontend Development Fundamentals) coursework.