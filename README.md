# StudyNotion EdTech Website

![Logo-Full-Light](https://github.com/subham-paul/StudyNotion-EdTech/assets/52645265/4ddcf361-9776-49c0-b833-51fe5e382abe)


StudyNotion is an innovative EdTech platform where instructors can upload their courses and track their progress through visually appealing pie charts created using the Chart.js npm package. The website is built on ReactJS, TailwindCSS, and Express, with backend support provided by NodeJS and MongoDB. For payment processing, StudyNotion utilizes Razorpay. The website's frontend is hosted on Vercel, and course data is securely stored on Cloudinary servers. Additionally, the website integrates Dicebear's API to automatically generate unique profile pictures for users.

## Features

- **Instructor Dashboard**: Instructors can log in and access their personalized dashboard to upload and manage their courses. They can monitor the progress of enrolled students through informative pie charts created with Chart.js.

- **Student Dashboard**: Students can access their dashboard after registering for courses. They can view their enrolled courses, track their learning progress, and interact with the course material.

- **Admin Dashboard**: Administrators have access to the administrative dashboard to manage users, courses, and ensure the smooth functioning of the platform.

- **Payment Integration**: StudyNotion incorporates Razorpay for secure and seamless payment processing for course enrollments and other transactions.

- **Profile Picture Generation**: Users' profile pictures are automatically generated using Dicebear's API, creating unique and personalized avatars for each user.

## Technologies Used

- Frontend: ReactJS, TailwindCSS
- Backend: Express, NodeJS, MongoDB
- Payment Processing: Razorpay
- Frontend Hosting: Vercel
- Backend Hosting: Render
- Course Data Storage: Cloudinary
- Profile Picture Generation: Dicebear API

## Getting Started

1. Clone the repository:

```bash
git clone https://github.com/subham-paul/StudyNotion-EdTech.git
```

2. Install dependencies:

```bash
cd StudyNotion-EdTech
npm install
```

3. Set up environment variables:

   - Create a `.env` file in the root directory.
   - Add the necessary environment variables for MongoDB connection, Razorpay integration, Dicebear API key, etc.

4. Run the development server:

```bash
npm run dev
```

5. Access the website locally at `http://localhost:3000`.

## Deployment

- Frontend is hosted on Vercel: [https://vercel.com/](https://vercel.com/)
- Backend is hosted on Render: [https://render.com/](https://render.com/)

## Contributions

Contributions to StudyNotion are welcome! If you encounter any issues or have ideas for improvements, feel free to create pull requests or submit issues.

## License

The StudyNotion EdTech Website is open-source software licensed under the [MIT license](LICENSE).

## Acknowledgments

- The StudyNotion team would like to express gratitude to the open-source community, without which this project wouldn't have been possible.
- Thanks to Chart.js, Razorpay, Cloudinary, Dicebear, and all the other tools and libraries that contributed to this project's success.
