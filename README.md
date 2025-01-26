# Next Meet - Video Meeting Application

Next Meet is a modern video meeting application built using **Next.js**, **Clerk**, and **Stream Video**. It provides features like instant meetings, scheduled meetings, meeting invitations, and more.

## Features

- **Instant Meetings**: Start a meeting instantly.
- **Scheduled Meetings**: Schedule a meeting for a later time.
- **Meeting Invitation**: Share meeting links with participants.
- **Meeting Management**: Join or start meetings via the interface.
- **Clerk Authentication**: Secure user sign-up/sign-in using Clerk.
- **Stream Video Integration**: Real-time video calls with Stream API.

## Technologies

- **Next.js** (React framework)
- **Clerk** (Authentication & Authorization)
- **Stream Video** (Real-time video calls)
- **Tailwind CSS** (Styling)
- **React-Toastify** (Toast notifications)
- **React-datepicker** (Date picker)
- **TypeScript** (Static typing)
- **Node.js** (Backend support)

## Prerequisites

Before running the project locally, ensure you have the following installed:

- Node.js (v14 or later)
- npm or yarn
- A Clerk account (for authentication)
- A Stream account (for video functionality)

## Setup

### 1. Clone the Repository

Clone the repository to your local machine:

```bash
git clone https://github.com/Satyam-Mishra-1/next-meet.git

```

### 2. Install Dependencies
Navigate to the project folder and install the dependencies:

```bash 
cd next-meet
npm install
```

### 3. Configure Environment Variables
```bash
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=your_clerk_publishable_key
CLERK_SECRET_KEY=your_clerk_secret_key

NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up

NEXT_PUBLIC_STREAM_API_KEY=your_stream_api_key
STREAM_SECRET_KEY=your_stream_secret_key

NEXT_PUBLIC_BASE_URL=http://localhost:3000

```

### 4. Run the Project Locally
```bash
npm run dev
``` 
