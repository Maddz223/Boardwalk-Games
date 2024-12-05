# My Static Website

This is a personal static website built using HTML, CSS, and JavaScript. The website serves as a portfolio to showcase my work and provide basic contact information.

## Table of Contents

- [Project Overview](#project-overview)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Deployment](#deployment)
- [Troubleshooting](#troubleshooting)
- [Contributing](#contributing)
- [License](#license)

## Project Overview

The website is designed to be a simple, fast-loading static site with the following features:

- A homepage with a brief introduction.
- A portfolio section showcasing past projects.
- A contact form for potential clients to reach out (static form, no backend).
- A responsive design optimized for both mobile and desktop screens.

## Technologies Used

This project uses the following technologies:

- **HTML**: For creating the basic structure of the website.
- **CSS**: For styling the website and making it responsive.
- **JavaScript**: For adding interactivity (e.g., smooth scroll, form validation).
- **Font Awesome**: For icons and vector images.
- **Google Fonts**: For custom fonts.

## Installation

To run this website locally on your machine, follow these steps:

1. **Clone the repository:**
   ```bash
   git clone https://github.com/yourusername/my-static-website.git
Navigate to the project directory:

bash
Copy code
cd my-static-website
Open the index.html file: Simply double-click on the index.html file, and it will open in your default browser. Alternatively, use a live server to preview the site.

Optional - Start a Local Server: If you prefer to run a local server, you can use tools like VS Code Live Server Extension or any other simple HTTP server:

Using Python:

bash
Copy code
python -m http.server 8000
Now open the browser and visit http://localhost:8000.

## Usage
To customize this static website, follow these instructions:

Homepage: Edit the index.html file to update the homepage content, including the introduction and main section.
Portfolio: Modify the portfolio.html file to showcase your projects. Add or remove sections as needed.
Contact Form: The contact form is currently a static form, but you can link it to a backend service (like Formspree or Google Forms) to handle submissions. For now, it does not send emails directly.
Styling: Customize the website's appearance by editing the styles.css file. Modify colors, fonts, and layout to suit your preferences.

## Deployment
You can deploy this website on any platform that supports static websites, such as GitHub Pages, Netlify, or Vercel. Here's how to deploy it on GitHub Pages:

Push your changes to your GitHub repository.
Go to the repository on GitHub and click on the Settings tab.
Scroll down to the GitHub Pages section.
Under Source, select main branch and root folder.
GitHub will provide you with a URL to access your deployed website.
Alternatively, you can deploy the site on Netlify by following these steps:

Go to Netlify and create an account.
Connect your GitHub repository to Netlify.
Select the repository and click Deploy Site.
Netlify will automatically deploy your website and provide a custom domain.

## Troubleshooting
Here are a few common issues and solutions:

Website not showing up correctly: If images or styles are not loading, make sure all files (images, CSS, JS) are in the correct folder and have the correct paths.
Contact form not working: The form is currently static and does not submit. To enable form submission, you can link it to an email service like Formspree or use a backend service.
Responsive issues: If the website looks weird on some screen sizes, ensure you have correctly set up media queries in styles.css for mobile responsiveness.

## Contributing
Contributions are welcome! To contribute to this project:

Fork the repository.
Create a new branch (git checkout -b feature-branch).
Make your changes.
Commit your changes (git commit -am 'Add feature').
Push to your forked branch (git push origin feature-branch).
Open a pull request.
## License
This project is licensed under the MIT License. Feel free to use and modify it for your own projects.
