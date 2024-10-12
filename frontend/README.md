# AI-Resume-Builder

## Create Professional Resumes with AI Assistance

**AI-Resume-Builder** is an intuitive platform designed to help users create professional resumes with the power of AI. The application integrates React (Vite), Strapi, Clerk authentication, Postgres (via Vercel), and the Gemini AI model to generate high-quality resume suggestions tailored to user needs. Whether you're a job seeker or an experienced professional, AI-Resume-Builder simplifies the resume-building process, ensuring you stand out in today's competitive job market.

## Features

- **AI-Powered Resume Suggestions**: The Gemini AI model provides intelligent recommendations for resume sections.
- **User Authentication**: Powered by Clerk, providing a secure and seamless login/signup experience.
- **Responsive Design**: Built with Tailwind CSS, ensuring optimal user experience across all devices.
- **Real-time Data Management**: Utilizes Strapi for efficient content management and Postgres for secure data storage.
- **Rich Text Editing**: Includes a simple WYSIWYG editor for formatting resume content.
- **Shareability**: Easily share your resume through web-share functionalities.

## Technologies Used

- **Frontend**: React (Vite), Shadcn (UI Components), TailwindCSS, Radix-UI
- **Backend**: Strapi, Postgres (hosted on Vercel)
- **AI Model**: Gemini AI for generating resume content suggestions
- **Authentication**: Clerk for user management
- **State Management**: React Context
- **HTTP Requests**: Axios
- **Utilities**: nanoid, uuid, clsx

## Installation and Setup

To get started with AI-Resume-Builder on your local machine:

1. **Clone the repository**:
      ```bash
      git clone https://github.com/your-username/ai-resume-builder.git


2. **Navigate to the Project Directory:**
       ```bash
       cd AI-Resume-Builder

3. **Install Dependencies::**
     ```bash
     npm install
     
4. **Set up environment variables:**
   Create a .env file in the project root and add the necessary environment variables for Strapi, Postgres, Clerk, and other    integrations.
  
5. **Start the development server:** 
     ```bash
     npm run dev

6. **Build the project for production:**
     ```bash
     npm run build


## Usage Instructions
Sign Up / Log In: After deployment or running the project locally, users can sign up or log in through Clerk.
Generate Resume: Users can fill in their details (such as personal info, experience, education, and skills) and receive AI-powered suggestions.
Export and Share: After customizing the resume, users can export it or share it through the web-share feature.


## Contributing
We welcome contributions to improve AI-Resume-Builder! To get started:

1. **Fork the repository and clone it locally:**
    ```bash
    git clone https://github.com/your-username/ai-resume-builder.git

2.**Create a new feature branch:**
    ```bash
    git checkout -b feature/your-feature

3.**Commit your changes:**
    ```bash
    git commit -m "Add new feature"
    
4.**Push the branch to your forked repository:**
    ```bash
    git push origin feature/your-feature

5.**Create a Pull Request from your branch to the main branch of the original repository.**

## Contributor Guidelines
Ensure your code follows the ESLint configuration provided in the project.
Make sure to run npm run lint before submitting pull requests to fix any issues.
Contributions should include tests where applicable.

## License
This project is licensed under the MIT License. See the LICENSE file for more details.
