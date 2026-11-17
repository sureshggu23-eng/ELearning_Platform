# Skillora – free e-learning platform

Skillora is a responsive e-learning website with student registration, course enrolment, lesson progress, quizzes, certificates and an admin course-management dashboard.

## Run with Node.js (recommended)

1. Install Node.js 18 or newer.
2. Open a terminal in the `skillora` folder.
3. Run `npm install`.
4. Run `npm start`.
5. Open http://localhost:3000.

The server stores shared users, courses and progress in `data.json`.

## Admin access

- Open **Admin sign in**.
- Email: `admin@skillora.com`
- Password: `admin123`

The admin dashboard supports adding, editing and deleting courses and managing student accounts. When adding a course, enter its title, category, level, description, lesson topics and detailed explanations. Every course must have exactly 10 quiz questions, each with four distinct options and a selected correct answer.

## Student access

Students can create an account, browse courses, enrol for free, complete lessons, track progress, take the 10-question final quiz and earn a certificate by reaching the course pass mark.

## Catalogue

The starter catalogue contains eight expanded courses across web development, JavaScript, UI/UX design, full-stack development, Python data science, digital marketing, Python programming and graphic design. Each starter course includes six detailed lessons and ten quiz questions.

## Browser demo mode

Opening `public/index.html` directly uses browser-local demo storage. For shared accounts and server-backed data, use the Node.js instructions above.
