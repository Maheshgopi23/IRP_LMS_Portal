# IRP LMS – Learning Management System

## 📌 Project Overview

**IRP LMS (Learning Management System)** is a web-based learning platform designed to provide students with a structured learning experience. The platform helps students explore technical courses, watch video tutorials, and understand the step-by-step journey from learning new skills to preparing for placements.

The website provides a clean, user-friendly interface with dedicated sections for the home page, available courses, and contacting the support team.

## 🎯 Project Objectives

- Provide a centralized platform for exploring technical courses.
- Enable students to learn through embedded video tutorials.
- Present a structured learning journey for career development.
- Provide an easy way for students to contact the support team.
- Create a simple, responsive, and user-friendly interface.

## ✨ Features

### 1. Home Page
- Displays the IRP LMS branding and navigation bar.
- Attractive hero section introducing the learning platform.
- Explore Courses button for course navigation.
- Learning Journey section explaining the five stages of career development:
  1. Learn
  2. Practice
  3. Build Projects
  4. Prepare
  5. Get Placed

### 2. Courses Page
- Displays available technical courses in a grid layout.
- Embedded YouTube video tutorials for learning.
- Each course includes a title and short description.
- Currently includes the following courses:
  - HTML
  - CSS
  - JavaScript
  - React
  - Python
  - Java
  - Spring Boot
  - Hibernate
  - Django
- Includes an Explore More Courses section to encourage students to discover additional learning opportunities.

### 3. Contact Us Page
- Displays contact information for the support team.
- Includes email address, phone number, and office address.
- Provides a contact form with the following fields:
  - Full Name
  - Email Address
  - Subject
  - Message
- Includes HTML form validation using required attributes and email input validation.
- Provides a Send Message button.

### 4. Navigation Bar
- Consistent navigation across all three pages.
- Navigation links for Home, Courses, and Contact Us.
- Active navigation link highlighting to indicate the current page.
- Sign In button in the header.

### 5. Responsive Design
- CSS media queries for different screen sizes.
- Responsive grid layout for course cards and learning journey cards.
- Flexible layouts for the contact section.
- Mobile-friendly spacing and typography adjustments.

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| HTML5 | Website structure and content |
| CSS3 | Styling, layouts, and responsive design |
| Google Fonts | Poppins typography |
| CSS Flexbox | Header and content alignment |
| CSS Grid | Course and learning journey layouts |
| YouTube Embed | Displaying video tutorials |
| Cloudinary | Hosting website images and assets |

## 📂 Project Structure

```text
IRP-LMS/
│
├── index.html          # Home page
├── courses.html        # Courses and video tutorials page
├── contact.html        # Contact us page
│
├── styles.css          # Common stylesheet for all pages
│
└── README.md           # Project documentation
```

## 🎨 UI Design and Styling

The website uses a consistent design system to maintain visual consistency across all pages.

### Color Palette

| Color | Hex Code | Usage |
|---|---|---|
| Navy Blue | `#0B2F66` | Headings and primary text |
| Orange | `#FE781E` | Buttons, highlights, and active links |
| Light Blue | `#F5F9FE` | Main background |
| Soft Blue | `#E8F1FC` | Hero section background |
| White | `#FFFFFF` | Cards and navigation background |
| Secondary Blue | `#5A7DB5` | Descriptions and supporting text |

### Typography
- Font Family: Poppins
- Font Weights: 400, 500, 600, 700, 800

### Layout Techniques
- Flexbox for navigation and horizontal alignment.
- CSS Grid for card-based layouts.
- Media queries for responsive layouts.
- Background images for hero sections.
- Consistent padding, margins, borders, and border-radius values.

## ⚙️ Installation and Setup

Follow these steps to run the project locally.

**Step 1: Clone the repository**

```bash
git clone <repository-url>
```

**Step 2: Navigate to the project directory**

```bash
cd IRP-LMS
```

**Step 3: Open the project**

Open `index.html` in your browser.

Alternatively, use the Live Server extension in Visual Studio Code.

**Step 4: Explore the website**

Navigate between the following pages:

- `index.html` – Home
- `courses.html` – Courses
- `contact.html` – Contact Us

## 📸 Website Pages

### Home Page
Introduces the IRP LMS platform and displays the five-step learning journey.

### Courses Page
Displays technical courses with embedded YouTube video tutorials.

### Contact Us Page
Provides support information and a contact form for student enquiries.

## 🚀 Future Enhancements

The following features can be implemented to make the platform more functional:

- User registration and login authentication.
- Student and administrator dashboards.
- Course enrollment functionality.
- Search and filter courses.
- Integration with a backend to manage course information.
- Database integration to store student details and enquiries.
- Functional contact form with backend email integration.
- Student progress tracking.
- Course completion certificates.
- Placement preparation resources and mock interview modules.

## ⚠️ Current Project Limitations

- The project currently focuses on frontend development using HTML and CSS.
- Sign In and Explore Courses buttons are currently UI elements without implemented navigation functionality.
- The contact form does not currently submit data to a backend.
- Course videos are embedded using YouTube iframes.
- Course information is currently maintained directly in HTML.

## 👨‍💻 Developer

**Project Name:** IRP LMS – Learning Management System

**Project Type:** Frontend Web Development

**Technologies:** HTML5, CSS3

---

⭐ **If you find this project useful, feel free to explore and improve it!**
