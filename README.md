# Cocktails

A modern and stylish cocktail application built with React, Tailwind CSS, and GSAP for a smooth and engaging user experience.

## Key Features & Benefits

*   **Visually Appealing Design:** Utilizes Tailwind CSS for a clean and responsive design.
*   **Smooth Animations:** Leverages GSAP for fluid and eye-catching animations.
*   **React Components:** Modular architecture for maintainability and reusability.
*   **Responsive Layout:** Adapts seamlessly to different screen sizes.

## Prerequisites & Dependencies

Before you begin, ensure you have the following installed:

*   **Node.js:** (Recommended version: 18 or higher) - [https://nodejs.org/](https://nodejs.org/)
*   **npm** (Node Package Manager) or **Yarn** (Package Manager)

## Installation & Setup Instructions

Follow these steps to get the project up and running:

1.  **Clone the repository:**

    ```bash
    git clone https://github.com/a-man-yadav/Cocktails.git
    cd Cocktails
    ```

2.  **Install Dependencies:**

    Using npm:

    ```bash
    npm install
    ```

3.  **Start the Development Server:**

    Using npm:

    ```bash
    npm run dev
    ```

## Usage Examples & API Documentation

The application utilizes React components to structure the user interface. Key components include:

*   **Navigation:**  Defined using `navLinks` in `constants/index.js` to create the navigation bar.

    ```javascript
    const navLinks = [
        {
           id: "cocktails",
           title: "Cocktails",
        },
        {
           id: "about",
           title: "About Us",
        },
        {
           id: "work",
           title: "The Art",
        },
        {
           id: "contact",
           title: "Contact",
        },
    ];
    ```

*   **Cocktail Lists:** Data for cocktail items is located in `constants/index.js`.

    ```javascript
    const cocktailLists = [
        {
           name: "Chapel Hill Shiraz",
           country: "AU",
           detail: "Battle",
           price: "$10",
        },
        // ... more cocktail objects
    ];
    ```

## Configuration Options

The project is configured using the following files:

*   **`package.json`:** Contains project metadata, dependencies, and scripts.
*   **`vite.config.js` (Implied, not directly provided):** Configuration file for Vite.

## Contributing Guidelines

We welcome contributions! To contribute, please follow these steps:

1.  Fork the repository.
2.  Create a new branch for your feature or bug fix.
3.  Make your changes and commit them with descriptive commit messages.
4.  Push your changes to your fork.
5.  Submit a pull request to the main branch.

Please ensure your code adheres to the project's coding standards and includes relevant tests.

## License Information

This project has no specified license. All rights are reserved by the owner.

## Acknowledgments

*   This project utilizes the following open-source libraries:
    *   [React](https://reactjs.org/)
    *   [Tailwind CSS](https://tailwindcss.com/)
    *   [GSAP](https://greensock.com/gsap/)
    *   [Vite](https://vitejs.dev/)
