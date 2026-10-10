# AttendanceFlow (AttendPro)

A student attendance management system built with React + Tailwind CSS on Vite, backed by the Base44 platform (auth, database, backend functions).

## Setup

1. Install dependencies with your package manager.
2. Configure a Base44 app (https://base44.com), then point the SDK client at it (src/api/base44Client.js).
3. Start the dev server.

## Structure

- src/pages/ - Dashboard, Students, Subjects, Mark Attendance, Reports, GitHub view, auth pages
- src/components/ - Layout, ProtectedRoute, and UI primitives (shadcn/ui)
- base44/entities/ - Student, Subject, AttendanceRecord schemas
- base44/functions/ - Backend functions (githubOverview)

## Features

- Student and subject management
- Roster-based attendance marking
- Attendance reports with CSV export
- GitHub repository and commit overview
