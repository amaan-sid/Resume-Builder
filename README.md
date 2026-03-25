# Resume Builder

A modern, full-stack Resume Builder application built with Next.js that allows users to create, customize, and export professional resumes.

---

## Features

* Create and edit resume sections (Education, Experience, Skills, etc.)
* Live preview of resume
* Export resume as PDF
* User authentication (login/signup)
* Save resumes to database
* Clean and responsive UI
* Fast performance with server-side rendering

---

## Tech Stack

**Frontend**

* Next.js (App Router)
* React
* Tailwind CSS

**Backend**

* Next.js API Routes

**Database**

* MongoDB

---

## Installation

1. Clone the repository:

```bash
git clone https://github.com/your-username/resume-builder.git
```

2. Navigate into the project:

```bash
cd resume-builder
```

3. Install dependencies:

```bash
npm install
```

4. Setup environment variables:

Create a `.env` file and add:

NEXTAUTH_SECRET=your_generated_secret 
NEXTAUTH_URL=http://localhost:3000 

MONGODB_URI=your_mongodb_connection_string

5. Run the development server:

```bash
npm run dev
```

6. Open in browser:

```
http://localhost:3000
```

---

## Environment Variables

| Variable    | Description                   |
| ----------- | ----------------------------- |
| MONGODB_URI | MongoDB connection string     |
| JWT_SECRET  | Secret key for authentication |

---

## Future Improvements

* AI-based resume suggestions
* Multiple resume templates
* Public resume sharing link
* ATS-friendly optimization
* Recruiter dashboard

---

