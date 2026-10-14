# SIT313 C1 – DEV@Deakin New Post Page

## Project Overview

This project extends the DEV@Deakin web application by implementing a New Post page using React. The page allows users to choose between creating a Question or an Article and enter the relevant information through a form.

## Features

- **Post Type Selection:** Choose between Question and Article.
- **Question Form:** Enter a title, describe a problem and add tags.
- **Article Form:** Enter a title, abstract, article text and tags.
- **Conditional Rendering:** Display different form fields based on the selected post type.
- **State Management:** Use React's `useState` hook to manage form inputs.
- **Form Validation:** Check required fields and limit tags to a maximum of three.
- **Submission Feedback:** Display alert messages for validation errors and successful submissions.
- **Navigation:** Access the New Post page through the Post button in the navigation bar.
- **Responsive Design:** Use CSS to provide a clean layout across different screen sizes.

## Technologies Used

- React
- JavaScript
- HTML
- CSS
- React Router
- Vite

## Project Structure

```text
src/
├── components/
│   ├── Header.jsx
│   ├── Footer.jsx
│   ├── FeaturedArticles.jsx
│   └── FeaturedTutorials.jsx
├── pages/
│   ├── login.jsx
│   ├── register.jsx
│   ├── NewPost.jsx
│   └── NewPost.css
├── App.jsx
├── App.css
├── main.jsx
└── firebase.js
```

*Note: The structure above represents the expected files. Adjust it if your actual project folders differ.*

## Installation and Setup

1. Clone the repository:

   ```bash
   git clone https://github.com/Shivamsingla-dev/SIT313-C1.git
   ```

2. Navigate to the project directory:

   ```bash
   cd SIT313-C1
   ```

3. Install the dependencies:

   ```bash
   npm install
   ```

4. Start the development server:

   ```bash
   npm run dev
   ```

5. Open the local URL displayed in the terminal, usually `http://localhost:5173`.

## How to Use

1. Open the DEV@Deakin application.
2. Click the **Post** button in the navigation bar.
3. Select either Question or Article.
4. Enter the required information in the displayed fields.
5. Add up to three tags, separated by commas.
6. Click **Post** to submit the form and view the corresponding alert message.

## Testing

The page can be tested by switching between Question and Article, checking that the correct fields appear, submitting incomplete forms, entering more than three tags and submitting completed forms.

## Current Limitations

The current implementation provides client-side form validation and submission feedback. Posts are not saved to a database or published for other users to view. Backend integration and persistent post storage are not included in this implementation.

## Learning Outcomes

This task helped develop my understanding of React hooks, conditional rendering, controlled form inputs, form validation, component organisation and routing within an existing React application.
