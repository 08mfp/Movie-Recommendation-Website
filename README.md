# Movie Recommendation Website

This project is a movie recommendation website that was developed as part of our First Year Team Project at University. The website allows users to answer 5 questions to receive personalized movie recommendations. Based on your answers, the site provides 5 movies that we believe will be perfect for you to watch.

## Prerequisites

Before running this program, ensure you have the following:

- Node.js and npm installed on your computer.
- A modern web browser (e.g., Chrome, Firefox, Edge).

## Getting Started

### 1. Clone the Repository

1. Clone the project repository from your version control system.

### 2. Install Dependencies

1. Open your terminal and navigate to the project directory.
2. Run the following command to install all necessary dependencies:

   ```bash
   npm install
3. Run the Program
Start the development server and the Node.js server by running:
bash
Copy code
npm run dev
Open http://localhost:3000 in your web browser to view the website.
Answer the 5 questions to receive your personalized movie recommendations.
Explanation of the Code

## Project Structure:
The project is built using React.js, with components organized to manage different parts of the user interface and functionality.
CSS is used for styling, and an external API is used to fetch movie data.

### React Components:
- The main components include a question form, movie recommendation display, and navigation.
- State management is used to track user responses and update the movie recommendations dynamically.

### API Integration:
The website uses an API to access an extensive movie catalog, ensuring that the recommendations are diverse and up-to-date.

### Development Tools:
The project was bootstrapped with Create React App, which provides a robust development environment with useful scripts.
Notes

## Customization:
- You can customize the questions and movie recommendation logic by modifying the relevant React components.
- If you need more control over the build process or want to integrate additional tools, consider using the npm run eject command.
  
## Troubleshooting

### Server Not Starting:
- Ensure that Node.js and npm are installed correctly.
- Check the terminal for error messages and resolve any missing dependencies or configuration issues.

### Page Not Loading:
- Make sure the development server is running.
- Verify that you are accessing the correct URL: http://localhost:3000.

### API Issues:
- If the API fails to fetch data, check your internet connection.
- Inspect the console for any error messages related to the API request.
References
