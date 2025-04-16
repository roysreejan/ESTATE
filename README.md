# ESTATE

Estate is a modern real estate web application designed to showcase properties, customer testimonials, and company information. Built with React, TailwindCSS, and Vite, it provides a responsive and visually appealing user experience.

## Features

- **Header**: A visually striking hero section with navigation links and call-to-action buttons.
- **About Section**: Highlights the company's achievements and mission.
- **Projects Section**: Displays a portfolio of completed projects with a responsive slider.
- **Testimonials Section**: Showcases customer feedback with ratings and profiles.
- **Contact Form**: Allows users to send inquiries via a form integrated with Web3Forms.
- **Footer**: Includes company links, a newsletter subscription form, and copyright information.

## Tech Stack

- **Frontend**: React, TailwindCSS, Framer Motion
- **Build Tool**: Vite
- **Linting**: ESLint
- **Form Handling**: Web3Forms
- **Notifications**: React Toastify

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/roysreejan/ESTATE
   ```

2. Navigate to the project directory:
   ```bash
   cd estate
   ```

3. Install dependencies:
   ```bash
   npm install
   ```

4. Start the development server:
   ```bash
   npm run dev
   ```

5. Open the application in your browser at 
   ```
   http://localhost:5173
   ```

## Scripts

- `npm run dev`: Start the development server.
- `npm run build`: Build the project for production.
- `npm run preview`: Preview the production build.
- `npm run lint`: Run ESLint to check for code issues.

## Folder Structure

```
estate/
├── public/               # Static assets
│   └── favicon.ico       # Favicon for the application
├── src/                  # Source code
│   ├── assets/           # Images and assets
│   ├── components/       # React components
│   │   ├── Header.jsx    # Header component
│   │   ├── Footer.jsx    # Footer component
│   │   ├── About.jsx     # About section component
│   │   ├── Projects.jsx  # Projects section component
│   │   ├── Testimonials.jsx # Testimonials section component
│   │   └── ContactForm.jsx  # Contact form component
│   ├── App.jsx           # Main application component
│   ├── main.jsx          # Entry point
│   └── index.css         # Global styles
├── .vscode/              # VS Code settings
│   └── settings.json     # Editor-specific settings
├── node_modules/         # Installed dependencies
├── package.json          # Project metadata and dependencies
├── vite.config.js        # Vite configuration
├── eslint.config.js      # ESLint configuration
├── vercel.json           # Vercel deployment configuration
└── README.md             # Project documentation
```

## Dependencies

- **React**: UI library for building components.
- **TailwindCSS**: Utility-first CSS framework.
- **Framer Motion**: Animation library for React.
- **React Toastify**: Notifications for React.
- **Web3Forms**: Form submission API.

## Deployment

This project is configured for deployment on [Vercel](https://vercel.com). The `vercel.json` file ensures that all routes are rewritten to `index.html` for a single-page application.
The live project is available at: `https://estate-property.vercel.app/`

To deploy:

1. Install the Vercel CLI:
   ```bash
   npm install -g vercel
   ```

2. Deploy the project:
   ```bash
   vercel
   ```

## Acknowledgments

- Built with ❤️ using React and TailwindCSS.
- Icons and images sourced from the project's assets folder.