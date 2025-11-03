# Krish S. Mistry - Portfolio Website

A responsive personal portfolio website built with HTML, CSS, and vanilla JavaScript.

## Description

This portfolio website showcases Krish S. Mistry's skills, projects, and professional experience. The website is designed to be responsive, accessible, and user-friendly across all devices.

## Features

- Responsive design (mobile-first approach)
- Clean and modern UI with smooth animations
- Contact form with mailto functionality
- Project showcase section
- Skills and experience display
- Resume download option
- Social media integration

## File Structure

```
KrishMistry_PortfolioWebsite/
│
├── index.html                  # Main HTML file
├── assets/
│   ├── css/
│   │   └── styles.css          # Main stylesheet
│   ├── js/
│   │   └── app.js              # JavaScript functionality
│   ├── images/                 # Image assets
│   │   ├── profile.jpg         # Profile picture
│   │   ├── project1.jpg        # Project thumbnails
│   │   ├── project2.jpg
│   │   ├── project3.jpg
│   │   └── favicon.png         # Website favicon
│   └── documents/
│       └── resume.pdf          # Downloadable resume
└── README.md                   # This file
```

## Setup Instructions

### Local Development

1. **Clone the repository**

   ```bash
   git clone https://github.com/yourusername/KrishMistry_PortfolioWebsite.git
   cd KrishMistry_PortfolioWebsite
   ```

2. **Open with Visual Studio Code Live Server**

   If you have Visual Studio Code with the Live Server extension installed:
   - Open the project folder in VS Code
   - Right-click on `index.html`
   - Select "Open with Live Server"

   OR

3. **Use Python's built-in HTTP server**

   ```bash
   # Navigate to the project directory
   cd KrishMistry_PortfolioWebsite
   
   # Start the server
   python -m http.server
   ```

   Then open your browser and go to `http://localhost:8000`

## Deployment to GitHub Pages

1. **Create a GitHub repository**

   Create a new repository on GitHub named `yourusername.github.io` or any other name of your choice.

2. **Initialize Git and push to GitHub**

   ```bash
   git init
   git add .
   git commit -m "Initial commit"
   git branch -M main
   git remote add origin https://github.com/yourusername/KrishMistry_PortfolioWebsite.git
   git push -u origin main
   ```

3. **Enable GitHub Pages**

   - Go to your repository on GitHub
   - Click on "Settings"
   - Scroll down to the "GitHub Pages" section
   - Select the branch you want to deploy (usually `main`)
   - Click "Save"
   - Your site will be published at `https://yourusername.github.io/KrishMistry_PortfolioWebsite/`

## Customization

1. **Replace placeholder images**
   - Replace `profile.jpg` with your own profile picture
   - Replace project images in the `assets/images` folder
   - Update the favicon

2. **Update personal information**
   - Edit the content in `index.html` to reflect your personal information
   - Update links to your social media profiles
   - Replace `resume.pdf` with your actual resume

3. **Modify styling**
   - Customize colors and styling in `assets/css/styles.css`

## Technologies Used

- HTML5
- CSS3
- JavaScript (ES6+)
- Font Awesome (for icons)
- Google Fonts

## License

This project is open source and available under the [MIT License](LICENSE).

## Contact

Krish S. Mistry - krishmistry076@gmail.com