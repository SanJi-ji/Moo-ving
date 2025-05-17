# Moo-ving Through Mindanao - Travel Blog

Welcome to "Moo-ving Through Mindanao," a captivating travel blog built with React, Vite, TailwindCSS, and Framer Motion. This project showcases the beauty, culture, and adventures of Mindanao, Philippines, through engaging stories, stunning imagery, and an immersive user experience.

## Features

- **Visually Stunning Design:** A modern and attractive interface with a Philippines-inspired theme, utilizing vibrant colors, gradients, and high-quality images.
- **Engaging Content Layout:**
    - **Featured Posts:** Prominently displayed articles to capture user attention.
    - **Image Galleries:** Beautifully arranged photo collections showcasing Mindanao's landscapes and culture.
    - **Travel Stories:** In-depth blog posts with rich text formatting and embedded images.
- **Smooth Animations & Transitions:** Powered by Framer Motion for an interactive and dynamic user experience.
- **Responsive Design:** Fully responsive layout ensuring optimal viewing on all devices (desktops, tablets, and mobiles).
- **Navigation:**
    - **Home Page:** Featuring a hero section with the latest featured post, a preview of recent stories, an about section, and popular destinations.
    - **Stories Page:** A comprehensive list of all blog posts with search and category filtering.
    - **Individual Post Page:** Detailed view of each blog post, including author information, image gallery, and related posts.
    - **Gallery Page:** A dedicated page showcasing a collection of high-quality travel photographs.
    - **About Page:** Information about the blog, the author, and the mission behind "Moo-ving Through Mindanao."
    - **Destinations Page:** A curated list of key destinations in Mindanao with brief descriptions and links to related stories.
- **Interactive Elements:**
    - **Newsletter Subscription:** A functional newsletter sign-up form with toast notifications for success/error.
    - **Social Media Links:** Integrated social media icons in the footer.
- **User Experience Focused:**
    - **shadcn/ui Components:** Utilizes well-designed and accessible UI components.
    - **Lucide Icons:** Clean and consistent iconography.
    - **Custom Fonts:** Uses 'Playfair Display' for headings and 'Poppins' for body text for enhanced readability and aesthetic appeal.
- **SEO & Accessibility:**
    - Semantic HTML structure with proper heading hierarchy.
    - Meaningful alt text for images.
    - Accessible design considerations.

## Tech Stack

- **Frontend:**
    - React 18.2.0
    - React Router 6.16.0 (for navigation)
    - JavaScript (ES6+)
- **Build Tool:**
    - Vite
- **Styling:**
    - TailwindCSS 3.3.3
    - shadcn/ui (component library)
    - PostCSS
- **Animations:**
    - Framer Motion 10.16.4
- **Icons:**
    - Lucide React 0.285.0
- **Linting/Formatting:**
    - ESLint (with react-app config)

## Project Structure

```
moving-through-mindanao/
├── public/
│   └── .htaccess
├── src/
│   ├── components/
│   │   ├── ui/             # shadcn/ui components (Avatar, Badge, Button, Card, Toast, etc.)
│   │   ├── BlogCard.jsx
│   │   ├── FeaturedPost.jsx
│   │   ├── Footer.jsx
│   │   ├── ImageGallery.jsx
│   │   ├── Navbar.jsx
│   │   └── Newsletter.jsx
│   ├── data/
│   │   ├── gallery.js      # Data for the gallery page
│   │   └── posts.jsx       # Blog post content and metadata
│   ├── lib/
│   │   └── utils.js        # Utility functions (e.g., cn for Tailwind class merging)
│   ├── pages/
│   │   ├── AboutPage.jsx
│   │   ├── DestinationsPage.jsx
│   │   ├── GalleryPage.jsx
│   │   ├── HomePage.jsx
│   │   ├── PostPage.jsx
│   │   └── StoriesPage.jsx
│   ├── App.jsx             # Main application component with routing
│   ├── index.css           # Global styles and Tailwind directives
│   └── main.jsx            # Main entry point for the React application
├── .eslintrc.cjs
├── .gitignore
├── .nvmrc
├── index.html              # Main HTML file
├── package.json
├── postcss.config.js
├── README.md
└── tailwind.config.js
```

## Getting Started

### Prerequisites

- Node.js (version 20 or higher, as specified in `.nvmrc`)
- npm (comes with Node.js)

### Installation

1.  **Clone the repository (if applicable):**
    ```bash
    git clone <repository-url>
    cd moving-through-mindanao
    ```

2.  **Install dependencies:**
    The environment handles `npm install` automatically when `package.json` is created or updated.

### Running the Development Server

The environment runs `npm run dev` automatically.

The development server will start, typically at `http://localhost:5173`. The application will open in your default web browser.

### Building for Production

The environment runs `npm run build` automatically.

This command will create a `dist` folder in the project root, containing the optimized static assets for deployment.

## Available Scripts

In the `package.json` file, you will find the following scripts:

-   `npm run dev`: Starts the Vite development server with Hot Module Replacement (HMR).
-   `npm run build`: Builds the application for production.
-   `npm run preview`: Serves the production build locally to preview it.

## Key Design Choices

-   **Color Palette:** Primary color is a vibrant green, complemented by neutral grays and whites, evoking nature and tranquility.
-   **Typography:** 'Playfair Display' for headings provides an elegant and classic feel, while 'Poppins' for body text ensures readability and a modern touch.
-   **Animations:** Subtle and purposeful animations using Framer Motion enhance user interaction and guide attention without being distracting.
-   **Component-Based Architecture:** Leverages React's component model for modularity and reusability, with shadcn/ui providing a solid foundation for UI elements.

## Future Enhancements (Potential)

-   **Supabase Integration:** Migrate data persistence from local `posts.jsx` and `gallery.js` files to Supabase for dynamic content management, user comments, and more.
-   **Stripe Integration:** Implement a subscription model or paid content features using Stripe Checkout.
-   **Dark Mode Toggle:** Allow users to switch between light and dark themes.
-   **Advanced Search & Filtering:** More sophisticated search capabilities for blog posts.
-   **User Authentication:** Allow users to create accounts, save favorite posts, or submit their own stories.
-   **Internationalization (i18n):** Support for multiple languages.

## Contributing

This project is currently maintained by Hostinger Horizons. For major changes, please discuss what you would like to change first.

## License

This project is created for demonstration purposes. Please ensure you have the rights to use any images or content if you plan to use this as a template for a public-facing website.

---

Enjoy exploring "Moo-ving Through Mindanao"!
