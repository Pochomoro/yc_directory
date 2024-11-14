
# NextJS 15 Blog App for Startups (yc_directory)

A project created following a tutorial by JavaScript Mastery, building a blog application using the latest Next.js 15, with added error management via Sentry and database management via Sanity. This app allows users to post, filter, and explore articles related to startups, featuring a GitHub OAuth login for user authentication and data storage in Sanity.

## Project Overview

This app is designed to manage and display articles about startups, enabling users to:
- Post new articles
- Filter articles by various parameters
- Explore articles through a user-friendly interface

### Key Features

- **Next.js 15**: Utilized Next.js’s newest features, including Partial Pre-rendering (PPR) and server components to enhance performance.
- **Sentry**: Integrated for robust error monitoring and management, providing seamless tracking and reporting of errors in both development and production environments.
- **Sanity**: Used as the content management system (CMS) and database, storing and structuring article and user data.
- **GitHub OAuth Authentication**: Leveraged GitHub OAuth to securely authenticate users, with authenticated data saved in Sanity for easy management.
- **Partial Pre-Rendering (PPR)**: Implemented to improve load times and SEO by rendering critical content on the server side.
- **Server Components**: Used `use server` and `use client` to handle components more efficiently in a hybrid server-client model.

## Technologies Used

- **Framework**: [Next.js 15](https://nextjs.org/)
- **Error Monitoring**: [Sentry](https://sentry.io/)
- **Content Management & Database**: [Sanity](https://www.sanity.io/)
- **Authentication**: GitHub OAuth for secure user authentication
- **Frontend**: Tailwind CSS for responsive and modern UI
- **Deployment**: Hosted on Vercel for streamlined CI/CD

## How It Works

- **Authentication**: Users can log in via GitHub OAuth, and their information is stored in Sanity.
- **Error Handling**: Sentry tracks errors across both the client and server, helping monitor issues in real time.
- **Content Management**: Articles and user data are stored in Sanity, allowing easy retrieval and management.
- **Rendering**: Uses PPR to render critical content on the server, improving load times and SEO. `use server` and `use client` components handle rendering efficiently between server and client environments.

## Learning Highlights

- Gained practical experience with the new **Next.js 15 features** like PPR and server components.
- Learned how to integrate and configure **Sentry for error management**.
- Set up and managed a **Sanity CMS** for structured content storage and retrieval.
- Gained knowledge in **OAuth authentication** using GitHub, ensuring secure and seamless user login.

## Acknowledgements

Special thanks to [JavaScript Mastery](https://www.youtube.com/c/javascriptmastery) for the tutorial that served as the foundation for this project.

