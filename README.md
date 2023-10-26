# The Wild Oasis

"The Wild Oasis" is a comprehensive web application template designed to facilitate the management of bookings, stays, cabins, and guest information within a serene and picturesque oasis. Built on a foundation of modern technologies, this project leverages the power of Supabase for secure data storage and React for a seamless user interface.

## Tech Stack

1. **Frontend:**

   - **React (v18.2.0)**
   - **React Router (v6.16.0)**
   - **React Query (v4.35.7):** A library for managing and caching asynchronous data fetching.
   - **Recharts (v2.9.0):** A composable charting library for building interactive data visualizations.
   - **Styled Components (v6.0.8):** A CSS-in-JS library for styling components.
   - **React Icons (v4.11.0):** A set of popular icon libraries for React components.
   - **React Hook Form (v7.46.2):** A library for managing forms and form validation in React applications.
   - **React Hot Toast (v2.4.1):** A toast notification library for displaying non-intrusive notifications.
   - **React Error Boundary (v4.0.11):** A component for handling errors gracefully within the application.

2. **Backend:**

   - **Supabase (via @supabase/supabase-js v2.37.0):** An open-source Firebase alternative for building, deploying, and scaling web and mobile applications. Used for data storage and retrieval.

3. **Date Manipulation:**

   - **date-fns (v2.30.0):** A library for manipulating and formatting dates in JavaScript.

4. **Development Tools:**

   - **Vite (v4.4.5):** A fast and opinionated build tool that aims to provide the best developer experience.
   - **Vite Plugins:** Including `@vitejs/plugin-react` for React support and `vite-plugin-eslint` for linting.

5. **Linting and Code Style:**
   - **ESLint (v8.45.0):** A pluggable and configurable linter tool for identifying and fixing problems in the code.
   - **eslint-config-react-app (v7.0.1):** A configuration for ESLint that is used in Create React App projects.

## Features

1. **User-friendly Interface:**

   - The application provides a clean and intuitive user interface, making it easy for administrators to navigate and perform tasks.

2. **Cabin Management:**

   - Administrators can maintain a list of available cabins, including details
     like cabin name, pricing, and discounts.

3. **Users Management:**

   - Administrators can add other users to have access to the application and
     this is the only way to sign up new users.

4. **Dynamic Pricing:**

   - The application calculates booking prices based on the selected cabin, the length of stay, and optional extras such as breakfast.

5. **Booking Validation:**

   - Users receive real-time validation feedback, ensuring that bookings adhere to rules like minimum and maximum booking lengths and start date restrictions.

6. **Payment Handling:**

   - Administrators can mark bookings as paid, while the application offers options to track paid and unpaid reservations.

7. **Data Visualizations:**

   - The system provides insightful data visualizations using Recharts, offering a summary of booking durations, sales charts, and more.

8. **Flexible Configuration:**

   - Administrators can configure settings such as minimum and maximum booking lengths and maximum guests per booking.

9. **Dark Mode Support:**

   - The application supports both light and dark modes to accommodate different user preferences.

10. **Toasts and Notifications:**

- Real-time notifications and toasts keep users informed of important actions and updates.

11. **Data Persistence:**

    - Data is securely stored and managed using Supabase, an open-source alternative to Firebase, ensuring data integrity and accessibility.

12. **Filtering:**

    - Users can filter bookings and cabins based on various criteria, enhancing the efficiency of data retrieval.

13. **Error Handling:**

    - The application incorporates error boundaries and gracefully handles errors to ensure a smooth user experience.

14. **Admin Dashboard:**
    - Administrators have access to a dashboard that provides an overview of bookings, sales, occupancy rates, and more.

## Improvements

**Future Features:**

1. **Booking Management:**
   - Users can create, edit, and manage bookings with detailed information, including start and end dates, number of guests, selected cabin, and special requests.
2. **Guest Management:**
   - The system allows for the management of guest information, enabling administrators to keep a record of guests' details and preferences.

## Demo

### Use these credentials to access the app

- Email: test@test.com
- Password: password1

<https://the-wild-oasis-hotels.vercel.app>

## Acknowledgements

- This is a demonestration of the last project of Jonas Schmedtmann's React course on Udemy.
