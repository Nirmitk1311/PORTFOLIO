# Nirmit Kasodariya Portfolio

This is the personal portfolio website of Nirmit Kishor Kasodariya, an Artificial Intelligence and Data Science Engineer. The website showcases skills, projects, freelance services, and contact information in a modern, responsive, and visually appealing design.

## 🚀 Features
- Home, About, Skills, Freelance, Projects, and Connect sections
- Animated AI/Data Science themed background
- Responsive design for all devices
- Project links to GitHub repositories with detailed descriptions
- Social and contact links with icons
- Modern dark theme with glassmorphism effects
- Enhanced project showcase with images and comprehensive descriptions

## 🛠️ Technologies Used
- HTML5
- CSS3 (with custom animations and glassmorphism effects)
- JavaScript (for background animation and scroll effects)
- [Font Awesome](https://fontawesome.com/) for icons

## 📂 Folder Structure
```
PORTFOLIO/
├── assets/           # Images and skill icons
├── index.html        # Main HTML file
├── style.css         # Stylesheet
├── script.js         # JavaScript for animations
└── README.md         # Project documentation
```

## 🌐 Deployment
This site can be deployed on [Netlify](https://www.netlify.com/) or any static hosting provider.

### Deploy on Netlify
1. Push your code to GitHub.
2. Go to Netlify and select "Add new site" > "Import an existing project".
3. Connect your GitHub and select this repository.
4. Set the build command to `N/A` (for static sites) and the publish directory to `./`.
5. Click "Deploy site".

## 📞 Contact
- [LinkedIn](https://www.linkedin.com/in/nirmit-kasodariya-499aa7208)
- [GitHub](https://github.com/Nirmitk1311)
- [Instagram](https://www.instagram.com/nirmit_1311)
- [Facebook](https://www.facebook.com/share/18vtp7PJPJ/)
- Email: nirmit1311@gmail.com

---
© 2024 Nirmit Kasodariya. All rights reserved. 

/* Project Images */
.project-image {
    width: 80px;
    height: 80px;
    object-fit: contain;
    margin-bottom: 1rem;
    border-radius: 12px;
    background: rgba(255, 255, 255, 0.05);
    padding: 0.5rem;
    transition: all 0.3s ease;
    box-shadow: 0 4px 16px rgba(0, 168, 255, 0.1);
}

.project-item:hover .project-image {
    transform: scale(1.05);
    box-shadow: 0 8px 24px rgba(0, 168, 255, 0.2);
}

.project-item {
    background: rgba(35, 38, 58, 0.6);
    backdrop-filter: blur(8px);
    border: 1px solid rgba(255, 255, 255, 0.08);
    border-radius: 16px;
    padding: 2rem;
    margin-bottom: 2rem;
    transition: all 0.3s ease;
    text-align: center;
    display: flex;
    flex-direction: column;
    align-items: center;
}

.project-item:hover {
    transform: translateY(-4px);
    box-shadow: 0 12px 32px rgba(0, 0, 0, 0.3);
    border-color: rgba(0, 168, 255, 0.3);
}

.project-item h3 {
    color: #00a8ff;
    margin: 1rem 0;
    font-size: 1.4rem;
}

.project-item p {
    color: #b8c5d6;
    line-height: 1.6;
    margin-bottom: 1.5rem;
    text-align: center;
    max-width: 500px;
}

.project-item a {
    color: #00a8ff;
    text-decoration: none;
    font-weight: 600;
    padding: 0.75rem 1.5rem;
    border: 2px solid #00a8ff;
    border-radius: 8px;
    transition: all 0.3s ease;
    background: rgba(0, 168, 255, 0.1);
}

.project-item a:hover {
    background: #00a8ff;
    color: #181a20;
    transform: translateY(-2px);
    box-shadow: 0 6px 20px rgba(0, 168, 255, 0.3);
}

/* Responsive adjustments for project images */
@media (max-width: 900px) {
    .project-image {
        width: 70px;
        height: 70px;
    }
    
    .project-item {
        padding: 1.5rem;
    }
    
    .project-item h3 {
        font-size: 1.2rem;
    }
    
    .project-item p {
        font-size: 0.95rem;
    }
}

@media (max-width: 600px) {
    .project-image {
        width: 60px;
        height: 60px;
    }
    
    .project-item {
        padding: 1.2rem;
        margin-bottom: 1.5rem;
    }
    
    .project-item h3 {
        font-size: 1.1rem;
    }
    
    .project-item p {
        font-size: 0.9rem;
        line-height: 1.5;
    }
    
    .project-item a {
        padding: 0.6rem 1.2rem;
        font-size: 0.9rem;
    }
} 