# QuickStay

A modern hotel booking platform that allows users to search, book rooms, make online payments, and manage reservations easily. Hotel owners can register, add rooms, and efficiently manage their properties and bookings.

## Features

- **User Authentication:** Secure login and registration using Clerk.
- **Room Search & Booking:** Search, filter, and book hotel rooms.
- **Online Payments:** Process payments securely via Stripe.
- **Email Notifications:** Receive booking confirmation emails.
- **Hotel Management:** Hotel owners can register, add rooms, and manage bookings.
- **Responsive Design:** Modern UI built with React and TailwindCSS.

## Technologies

- **Frontend:** React, Vite, TailwindCSS, React Router, Axios
- **Backend:** Node.js, Express, MongoDB (Mongoose)
- **Authentication:** Clerk
- **Payments:** Stripe
- **Image Upload:** Cloudinary
- **Email:** Nodemailer
- **Deployment:** Vercel

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/TranKienCuong2003/QuickStay_FullStack.git
   cd QuickStay
   ```

2. Install dependencies for both client and server:

   ```bash
   # Install client dependencies
   cd client
   npm install

   # Install server dependencies
   cd ../server
   npm install
   ```

3. Set up environment variables:

   - Create a `.env` file in the `client` directory with:
     ```
     VITE_API_URL=http://localhost:3000
     VITE_CLERK_PUBLISHABLE_KEY=your_clerk_publishable_key
     ```
   - Create a `.env` file in the `server` directory with:
     ```
     PORT=3000
     MONGODB_URI=your_mongodb_connection_string
     CLOUDINARY_CLOUD_NAME=your_cloudinary_cloud_name
     CLOUDINARY_API_KEY=your_cloudinary_api_key
     CLOUDINARY_API_SECRET=your_cloudinary_api_secret
     CLERK_SECRET_KEY=your_clerk_secret_key
     STRIPE_SECRET_KEY=your_stripe_secret_key
     STRIPE_WEBHOOK_SECRET=your_stripe_webhook_secret
     ```

4. Run the application:

   ```bash
   # Start the server
   cd server
   npm start

   # Start the client (in a new terminal)
   cd client
   npm run dev
   ```

## Usage

- **User:** Register, log in, search for rooms, book, and manage reservations.
- **Hotel Owner:** Register your hotel, add rooms, and manage bookings.

## License

This project is licensed under the [MIT License](LICENSE).

## Contact

For any questions or support, please reach out to [trankiencuong30072003@gmail.com](mailto:trankiencuong30072003@gmail.com).
