This is a [Next.js](https://nextjs.org) project bootstrapped with [`create-next-app`](https://nextjs.org/docs/app/api-reference/cli/create-next-app).

.

# User Management Dashboard

A modern, responsive user management dashboard built with Next.js, TypeScript, and Tailwind CSS. Features a multi-step form for adding users, dark mode support, animations, and real-time notifications.

## Features

### User List
- Fetches and displays user data from JSONPlaceholder API
- Responsive grid layout with user cards
- Search functionality by name or city
- Loading and error state handling
- Smooth animations using Framer Motion

### Multi-step Add User Form
- Step 1: Basic Information (name, email, phone)
- Step 2: Address Details
- Step 3: Review and Submit
- Form progress indicator
- Data persistence using localStorage
- Form validation
- Success/error notifications

### UI/UX Features
- Dark/Light mode toggle with system preference support
- Smooth transitions and animations
- Toast notifications for user feedback
- Responsive design for all screen sizes
- Modern and clean interface

## Technology Stack

- **Framework**: Next.js with TypeScript
- **Styling**: Tailwind CSS
- **Animations**: Framer Motion
- **State Management**: React Hooks
- **Form Handling**: Custom validation
- **API Integration**: Fetch API
- **Notifications**: React Hot Toast
- **Icons**: Heroicons

## Getting Started

1. Clone the repository
2. Install dependencies:
   ```bash
   npm install
   ```
3. Start the development server:
   ```bash
   npm run dev
   ```
4. Open [http://localhost:3000](http://localhost:3000) in your browser

## Project Structure

```
├── src/
│   ├── app/
│   │   ├── dashboard/     # Dashboard and Add User pages
│   │   ├── layout.tsx     # Root layout with providers
│   │   └── page.tsx       # Root page with redirect
│   ├── context/
│   │   └── ThemeContext.tsx  # Dark mode context
│   └── types/
│       └── user.ts        # TypeScript interfaces
└── public/                # Static assets
```

## Contributing

Feel free to submit issues and enhancement requests.

## License

MIT
