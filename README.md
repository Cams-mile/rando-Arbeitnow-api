
## Table of Contents

<details>

   <summary>Contents</summary>

1. [👤 Author Information](#-author-information)
1. [🌐 API Information](#-api-information)
   1. [API Name](#api-name)
   1. [Base URL](#base-url)
   1. [Authentication](#authentication)
1. [📦 Sample JSON Response](#-sample-json-response)

</details>


## Table of Contents

<details>

   <summary>Contents</summary>

1. [👤 Author Information](#-author-information)
1. [🌐 API Information](#-api-information)
   1. [API Name](#api-name)
   1. [Base URL](#base-url)

</details>
# 💼 Job Finder Web Application

A responsive web-based **Job Finder application** built using **HTML, CSS, and JavaScript**.  
This project uses a **public Job Board API** to fetch and display a large list of job openings, allowing users to browse and search jobs easily.

---

## 👤 Author Information
- **Name:** Camile Caragay
- **GitHub Username:** Cams-mile
- **Course & Section:** BSIT
- **Subject:** Elective / API Integration

---

## 🌐 API Information

### API Name
**Arbeitnow Job Board API**

### Base URL
https://arbeitnow.com/api

/job-board-api

### Authentication
✔ None  
❌ API Key  
❌ OAuth  

---

## 📦 Sample JSON Response
*(Only the fields used in the project)*

```json
{
  "data": [
    {
      "title": "Frontend Developer",
      "company_name": "Example Company",
      "location": "Berlin",
      "url": "https://example.com/job"
    }
  ]
}

```
✨ Features

Automatically loads many job listings on page load

Search jobs by title, company, or location

Load More Jobs button to display more results

Loading indicator while fetching data

Error handling for no results and failed API requests

Responsive and clean card-based UI

----
🛠 Technologies Used

HTML – Structure of the application

CSS – Styling, layout, and responsiveness

JavaScript – Fetch API, DOM manipulation, filtering logic

Arbeitnow Job Board API – Job data source

----
📁 File Structure
rando-Arbeitnow-api/
│
├── index.html
├── style.css
└── script.js

----
⚙️ Installation

Follow the steps below to run the project locally.

1️⃣ Clone the Repository

Open your terminal or command prompt and run:

git clone 
```bash
https://github.com/Cams-mile/rando-Arbeitnow-api.git

```

2️⃣ Navigate to the Project Folder
```bash
cd rando-Arbeitnow-api

```
3️⃣ Open the Project

Open the index.html file in any modern web browser
(or right-click → Open with Live Server if using VS Code).

---
▶ How to Use

Wait for the job listings to load

Use the search bar to filter jobs (optional)

Click Load More Jobs to display more listings

Click View Job to open the job posting

---
🧪 Error Handling Implemented

Empty search input

No matching results

Failed API request

Loading state feedback
