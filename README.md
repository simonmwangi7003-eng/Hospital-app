# MedFlow Hospital Management System

A responsive frontend-only hospital operations demo built with React, Vite, React Router, Recharts and Lucide React.

## Requirements
- Node.js 18 or newer
- npm

## Setup
1. Extract `medflow-hospital.zip`.
2. Open the extracted `medflow-hospital` folder in VS Code.
3. Open the integrated terminal.
4. Install dependencies:
   ```bash
   npm install
   ```
5. Start the development server:
   ```bash
   npm run dev
   ```
6. Open the local URL printed by Vite (normally `http://localhost:5173`).

To create a production build:
```bash
npm run build
npm run preview
```

## Demo login
- Email: `admin@medflow.test`
- Password: `medflow123`
- Choose a role from the role selector to preview role-specific navigation.
- Any valid email and password of at least six characters are accepted by this simulated login.

## Included
- Dashboard cards and interactive Recharts visualizations
- Patient, staff, appointment, consultation, laboratory, pharmacy, billing and bed modules
- Add/edit/delete workflows, search, status filters and pagination
- Appointment double-booking validation
- Medication stock validation and dispensing
- Invoice payment tracking and outstanding balances
- Lab completion creates a billing record
- Bed admission and discharge actions
- Reports, notifications, light/dark theme and responsive navigation
- Seeded demo records and browser localStorage persistence

## Important limitations
This is a frontend demonstration, not a production clinical information system. Data is stored in the current browser and is not synchronized across devices. Authentication is simulated; passwords are not securely stored or verified. There is no server-side authorization, audit trail, encryption, real payment gateway, pharmacy regulatory workflow, or medical-device integration. Do not enter real patient or other sensitive health information. Production deployment requires a secure backend, database, access controls, audit logging, backups and compliance review.
