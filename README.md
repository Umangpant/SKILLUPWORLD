# SKILLUPWORLD
🚀 Overview

SkillUp is a modern education platform crafted to improve public speaking, confidence, and communication skills.
It provides structured lessons, self-assessment tools, and a seamless booking flow for live demo sessions.

The platform helps learners at every level — from school students to working professionals.


🧩 Features

These are your original features, now formatted professionally:

🎓 Interactive Courses

Structured modules that guide users through essential public speaking techniques.

🧠 Self-Assessment Quiz

Learners can evaluate their current skills and receive personalized improvement paths.

🎨 Modern Responsive Design

Clean, premium, and fully accessible UI built with Tailwind CSS — works on all devices.

🔐 User Authentication

Secure login through Supabase Auth (Google OAuth)
Smooth session management for both localhost and production domain.

📅 Demo Class Booking

Multi-step animated booking modal

Timezone detection

Google Meet integration

Works for guest users and logged-in users

💌 Email Automation

HTML emails for users & admin

Confirmation, alerts, and booking details

Background email sending (non-blocking & fast)


🛠 Tech Stack
<p align="center"> <img src="https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=next.js&logoColor=white"/> <img src="https://img.shields.io/badge/React%20(Inside%20Next.js)-61DAFB?style=for-the-badge&logo=react&logoColor=black"/> <img src="https://img.shields.io/badge/Supabase-3ECF8E?style=for-the-badge&logo=supabase&logoColor=white"/> <img src="https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white"/> <img src="https://img.shields.io/badge/Tailwind%20CSS-38B2AC?style=for-the-badge&logo=tailwindcss&logoColor=white"/> <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white"/> <img src="https://img.shields.io/badge/Nodemailer-009B2D?style=for-the-badge&logo=mail.ru&logoColor=white"/> <img src="https://img.shields.io/badge/Brevo%20SMTP-0066CC?style=for-the-badge"/> <img src="https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white"/> </p>
🧱 System Architecture

SkillUp uses a robust full-stack setup:

Frontend

Next.js App Router (React-based components)

Tailwind CSS styling

Multi-step animated UI

Client components for booking flow

Backend API

Hosted on Vercel serverless functions:

Booking management (/api/book-class)

Email automation

Error logging

Background async tasks

Database + Auth (Supabase)

PostgreSQL database

Google OAuth login

Insert policies for guest bookings

RLS & service role integration for production

Email System

Nodemailer + Brevo SMTP

Dynamic HTML templates

Sends confirmation to user + alert to admin


👨‍💻 Contribution (Your Role)

I contributed as a full-stack developer to SkillUp:

Developed the booking flow logic

Implemented email automation system (user + admin)

Integrated Supabase authentication and session handling

Built responsive UI components using React + Tailwind

Configured Vercel deployment & production environment

Handled domain DNS, SMTP authentication & Brevo setup

Ensured both guest bookings and logged-in bookings work flawlessly 



🔗 Live Demo

👉 https://skillupworld.org
