# Deepak Portfolio 
 <h1>deepakshowcase.netlify.app</h1>

# Sections :bookmark:
- HOME
- ABOUT
- RESUME
    - EDUCATION
    - SKILLS
    - EXPERIENCE
    - PROJECTS 
    - Achievements <br />
- SERVICES 
    - TESTIMONIALS <br />
- BLOG
- CONTACTS 

<br /><br />



### Install packages from the root directory
```
npm install
`
### Start the development server
```
npm start
```
<br />

# Folder Structure :open_file_folder:

```bash
├── LICENSE   
├── README.md        
├── package-lock.json
├── package.json     
├── public
│   ├── _redirects   
│   ├── favicon.ico  
│   ├── favicon.png
│   ├── favicon512.png
│   ├── index.html
│   ├── manifest.json
│   └── robots.txt
├── src
│   ├── App.css
│   ├── App.js
│   ├── assets
│   │   ├── fonts
│   │   │   └── Bestermind
│   │   │       └── BestermindRegular.ttf
│   │   ├── pdf
│   │   │   └── resume.pdf
│   │   └── svg
│   │       ├── about
│   │       ├── contacts
│   │       ├── education
│   │       ├── experience
│   │       ├── projects
│   │       ├── skills
│   │       ├── social
│   │       └── testimonials
│   ├── components
│   │   ├── About
│   │   │   ├── About.css
│   │   │   └── About.js
│   │   ├── Achievements
│   │   │   ├── Achievements.css
│   │   │   └── Achievements.js
│   │   │   └── AchievementCard.js
│   │   ├── BackToTop
│   │   │   ├── BackToTop.css
│   │   │   └── BackToTop.js
│   │   ├── Blog
│   │   │   ├── Blog.css
│   │   │   ├── Blog.js
│   │   │   └── SingleBlog
│   │   │       ├── SingleBlog.css
│   │   │       └── SingleBlog.js
│   │   ├── Contacts
│   │   │   ├── Contacts.css
│   │   │   └── Contacts.js
│   │   ├── Education
│   │   │   ├── Education.css
│   │   │   ├── Education.js
│   │   │   └── EducationCard.js
│   │   ├── Experience
│   │   │   ├── Experience.css
│   │   │   ├── Experience.js
│   │   │   └── ExperienceCard.js
│   │   ├── Footer
│   │   │   ├── Footer.css
│   │   │   └── Footer.js
│   │   ├── Landing
│   │   │   ├── Landing.css
│   │   │   └── Landing.js
│   │   ├── Navbar
│   │   │   ├── Navbar.css
│   │   │   └── Navbar.js
│   │   ├── Projects
│   │   │   ├── Projects.css
│   │   │   ├── Projects.js
│   │   │   └── SingleProject
│   │   │       ├── SingleProject.css
│   │   │       └── SingleProject.js
│   │   ├── Services
│   │   │   ├── Services.css
│   │   │   ├── Services.js
│   │   │   └── SingleService
│   │   │       ├── SingleService.css
│   │   │       └── SingleService.js
│   │   ├── Skills
│   │   │   ├── Skills.css
│   │   │   └── Skills.js
│   │   ├── Testimonials
│   │   │   ├── Testimonials.css
│   │   │   └── Testimonials.js
│   │   └── index.js
│   ├── contexts
│   │   └── ThemeContext.js
│   ├── data
│   │   ├── aboutData.js
│   │   ├── achievementData.js
│   │   ├── blogData.js
│   │   ├── contactsData.js
│   │   ├── educationData.js
│   │   ├── experienceData.js
│   │   ├── headerData.js
│   │   ├── projectsData.js
│   │   ├── servicesData.js
│   │   ├── skillsData.js
│   │   ├── socialsData.js
│   │   ├── testimonialsData.js
│   │   └── themeData.js
│   ├── index.css
│   ├── index.js
│   ├── pages
│   │   ├── Blog
│   │   │   ├── BlogPage.css
│   │   │   └── BlogPage.js
│   │   ├── Main
│   │   │   └── Main.js
│   │   ├── Project
│   │   │   ├── ProjectPage.css
│   │   │   └── ProjectPage.js
│   │   └── index.js
│   ├── reportWebVitals.js
│   ├── theme
│   │   ├── images.js
│   │   └── theme.js
│   └── utils
│       ├── ScrollToTop.js
│       └── skillsImage.js
└── yarn.lock
```
<br />


#### Data for each component is divided into respective files.

> #### About You

> #### Education details

> #### Enter your Projects 

> #### Add your Skills

> #### Experience 

> #### Achievements 

> #### Services 

> #### Your Blogs and Articles 

> #### Contact Details 

> #### Social Media Profiles 



# SEO :spider:
### Search engine optimization (SEO) is the process of improving the quality and quantity of website traffic to a website or a web page from search engines. 
### Add the below code snippet to `public/index.html` with your site info. This step is not mandatory

<br />

```html
    <meta name="description" content="--- SITE DESCRIPTION ---" />
    <meta property="og:image" content="--- YOUR IMAGE ---">
    <meta property="og:site_name" content="--- YOUR NAME ---"/>
    <meta property="og:title" content="--- YOUR NAME ---"/>
    <meta property="og:url" content="--- YOUR SITE URL ---"/>
    <meta property="og:type" content="website"/>
    <meta property="og:description" content="--- SITE DESCRIPTION ---"/>
    <meta property="og:locale" content="---  ---">
    <meta property="og:image" content="--- YOUR IMAGE ---"/>
    <meta property="og:image:width" content="1200">
    <meta property="og:image:height" content="630">
    
    <meta itemprop="name" content="--- YOUR NAME ---"/>
    <meta itemprop="url" content="--- YOUR SITE URL ---"/>
    <meta itemprop="description" content="--- SITE DESCRIPTION ---"/>
    <meta itemprop="thumbnailUrl" content=""/>
    <link rel="image_src" href="--- YOUR IMAGE ---"/>
    <meta itemprop="image" content="--- YOUR IMAGE ---"/>
    
    <meta name="twitter:site" content="@--- YOUR TWITTER USERNAME ---">
    <meta name="twitter:creator" content="@--- YOUR TWITTER USERNAME ---">
    <meta name="twitter:url" content="--- YOUR SITE URL ---"/>
    <meta name="twitter:title" content="--- YOUR NAME ---">
    <meta name="twitter:description" content="--- SITE DESCRIPTION ---">
    <meta name="twitter:image" content="--- YOUR IMAGE ---">
    <meta name="twitter:card" content="summary"/>

```

<br />

# Packages Used :package:

| Client Side Packages  |
| :-------------: |
| @material-ui/core  |
| @material-ui/icons  |
| axios |
| react-fast-marquee |
| react-helmet  |
| react-icons  |
| react-reveal |
| react-router-dom  |
| react-router-hash-link  |
| react-slick  |
| slick-carousel |
| validator |


<br />

# APIs Used :world_map:
- [SheetDB](https://sheetdb.io/)


<br />

# Fonts and Images :performing_arts:

## Illustrations
- [Icons8](https://icons8.com/illustrations/styles)
- [SVG Porn](https://svgporn.com/)

## Icons
- [Material Icons](https://material-ui.com/components/material-icons/)
- [React Icons](https://react-icons.github.io/react-icons/)

## Fonts
- [Poppins](https://fonts.google.com/specimen/Poppins)
- [Montserrat](https://fonts.google.com/specimen/Montserrat)
- [Raleway](https://fonts.google.com/specimen/Raleway)
- [Big Shoulders Text](https://fonts.google.com/specimen/Big+Shoulders+Text)
- [Bestermind](https://www.dafont.com/bestermind.font)
- [Roboto](https://fonts.google.com/specimen/Roboto)
