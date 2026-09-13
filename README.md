# 💼 JobFinder – Job Portal Website

## 📌 Introduction

**JobFinder** is a responsive and interactive **Job Portal Website** developed using **HTML, CSS, and JavaScript**.

The website allows users to search for jobs using keywords and filter available jobs according to **location** and **job category**.

It is a beginner-friendly frontend project created to practice **HTML structure, CSS styling, JavaScript functions, DOM manipulation, events, arrays, conditions, and responsive web design**.

---

## 🚀 Features

* 🔎 Search jobs by job title or keyword
* 📍 Filter jobs by location
* 🏷️ Filter jobs by category
* 💼 Display job information in cards
* 💰 Show salary information
* 💻 Show employment type
* 📊 Dynamic job counter
* ❌ No Jobs Found message
* 🚀 Apply Now button
* 📱 Responsive design
* 🎨 Modern and clean user interface
* ⚡ Interactive JavaScript functionality

---

## 🛠️ Technologies Used

* **HTML5**
* **CSS3**
* **JavaScript**

---

## 🔎 Search & Filter System

The website provides three main search options:

### 1. Job Search

Users can enter a job title or keyword such as:

* Frontend Developer
* Python Developer
* Java Developer
* Web Developer

### 2. Location Filter

Available locations include:

* Delhi
* Noida
* Bangalore
* Mumbai

### 3. Category Filter

Available categories include:

* Web Development
* Python
* Java
* Design

The search system combines these filters to display only matching jobs.

---

## 💼 Job Listings

The project contains six sample job listings:

| Job                | Location  | Category        |
| ------------------ | --------- | --------------- |
| Frontend Developer | Noida     | Web Development |
| Python Developer   | Delhi     | Python          |
| Java Developer     | Bangalore | Java            |
| UI/UX Designer     | Mumbai    | Design          |
| Web Developer      | Delhi     | Web Development |
| Python Intern      | Noida     | Python          |

The job cards also display company name, salary, employment type, and category.

---

## ⚙️ JavaScript Functionality

### `searchJobs()`

This function handles the job search and filtering system.

It:

1. Gets the search keyword.
2. Gets the selected location.
3. Gets the selected category.
4. Selects all job cards.
5. Checks each job against the filters.
6. Shows matching jobs.
7. Hides non-matching jobs.
8. Updates the number of jobs found.
9. Displays a message when no jobs match.

The project uses JavaScript methods such as:

* `getElementById()`
* `querySelectorAll()`
* `getAttribute()`
* `includes()`
* `forEach()`

---

### `applyJob()`

The `applyJob()` function displays an application-success message when the user clicks **Apply Now**.

This is currently a frontend demonstration and does not submit an application to a real backend.

---

## 🔄 Project Workflow

```text
                 ┌─────────────────┐
                 │   Open Website  │
                 └────────┬────────┘
                          │
                          ▼
                 ┌─────────────────┐
                 │ View Job Cards  │
                 └────────┬────────┘
                          │
                          ▼
                 ┌─────────────────┐
                 │ Enter Keyword   │
                 │ Select Location │
                 │ Select Category │
                 └────────┬────────┘
                          │
                          ▼
                 ┌─────────────────┐
                 │ Search & Filter │
                 │     Jobs        │
                 └────────┬────────┘
                          │
                ┌─────────┴─────────┐
                ▼                   ▼
        ┌──────────────┐     ┌──────────────┐
        │ Jobs Found   │     │ No Jobs Found│
        └──────┬───────┘     └──────────────┘
               │
               ▼
        ┌──────────────┐
        │ Apply Now    │
        └──────┬───────┘
               │
               ▼
        ┌──────────────────┐
        │ Application Demo │
        └──────────────────┘
```

---

## 📱 Responsive Design

The website is designed to work on different screen sizes.

### Desktop

Three job cards are displayed in a row.

### Tablet

Two job cards are displayed in a row.

### Mobile

One job card is displayed per row.

The navigation and search section also adjust for smaller screens.

---

## 📂 Project Structure

```text
JobFinder/
│
└── index.html
```

The complete project is currently contained in a single HTML file with:

* HTML structure
* CSS styling
* JavaScript functionality

---

## 🎯 Learning Objectives

This project helps practice:

* HTML5 page structure
* CSS Flexbox
* CSS Grid
* CSS Media Queries
* JavaScript functions
* JavaScript conditions
* DOM manipulation
* Event listeners
* `forEach()`
* `includes()`
* `getAttribute()`
* Search and filtering logic
* Responsive web design

---

## 🔮 Future Improvements

The project can be expanded by adding:

* 👤 User Login & Registration
* 📝 Real Job Application Form
* 🏢 Company Registration
* 💾 Database Integration
* 🔐 User Authentication
* ❤️ Save/Favorite Jobs
* 📄 Resume Upload
* 🔔 Job Notifications
* 🌐 Backend API
* 🔎 Advanced Search
* 🌓 Dark/Light Mode

---

## 📸 Project Preview

Add your project screenshot here:

```text
![JobFinder Preview](screenshot.png)
```

---

## ⭐ Project Highlights

* Beginner-friendly frontend project
* Interactive job search
* Multiple filtering options
* Dynamic job counter
* Responsive layout
* Clean user interface
* JavaScript DOM manipulation
* Easy to understand code

---

## 💖 Made With

**💖 & 💻 HTML + CSS + JavaScript**

**🟢 Beginner-Friendly**

---

## ⭐ Visit Repository

[🐙 ⭐ VISIT REPOSITORY](YOUR_GITHUB_REPOSITORY_LINK)

---

## 📄 License

This project is created for **educational and portfolio purposes**.
# Job-Portal-Website
A responsive job portal website built with HTML, CSS and JavaScript featuring job search, location and category filters, job listings and an interactive Apply Now system.
