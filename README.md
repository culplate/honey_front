# Bee and Hornet

**Bee and Hornet** is a single-page application (SPA) designed as a demo version of an online store that sells honey and honey-based products. This store is part of a family business. While the API keys and functionality related to feedback, messages, and sales are disabled or removed for this demo, the entire application logic is still present, giving a full sense of how the store operates.

## Key Features

- **React & Redux Toolkit**: The app uses React for the UI and Redux Toolkit for state management, ensuring efficient and scalable state handling.
- **Axios**: HTTP client used for making API requests (logic is present but disabled for demo purposes).
- **Formik & Yup**: Form management and validation are handled using Formik, with Yup providing schema-based form validation.
- **Swiper**: A modern slider component used to showcase honey products in a visually appealing way.
- **React-Toastify**: Provides smooth notifications for various events within the app.
- **Responsive Design**: Using `react-responsive` to ensure the app looks great on all screen sizes.
- **SCSS (Sass)**: For modular and clean styling of components.

## Build and Development Tools

- **Vite**: Fast and efficient build tool for development and production.
- **ESLint & Prettier**: Ensures code quality and consistent formatting, with linting enforced via Husky on pre-commit.
- **Husky & Lint-staged**: Pre-commit hooks to ensure code linting and formatting are followed before any commits are made.

## How to Use

1. Clone the repository:
     ```bash
     git clone https://github.com/culplate/honey-front.git
     ```

2. Install dependencies:
     ```bash
     npm install
     ```
4. Run the development server:
     ```bash
     npm start
     ```
6. Build for production:
     ```bash
     npm run build
     ```

## Notes
This is a demo version, and no real transactions, feedback, or messaging are available.
All the core logic for the store is still in place, providing a full example of how the store operates.

## License
This project is licensed under the MIT License.
