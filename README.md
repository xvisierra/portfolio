# Developer Portfolio 

<p align="center">
<img src="https://raw.githubusercontent.com/PhantomScript/asset-container/b26b0ebaaa13bec7fac796ee0b8296676df6ee0b/developer-portfolio/website.svg" alt="" width="450px"/>
</p>

## This is a professional Developer portfolio made with react.js along with sheetdb . We can add the portfolio to our resume to cater the viewer into an interactive detailed view about the person . Its a great tool to showcase your skills and to make an impactful impression to the viewer.

<br />

## Table of Contents :scroll:
- [Sections](#sections-bookmark)
- [Demo](#demo-movie_camera)
- [Themes](#themes-art)
- [Installation](#installation-arrow_down)
- [Getting Started](#getting-started-dart)
- [Folder Structure](#folder-structure-open_file_folder)
- [Usage](#usage-joystick)
- [Hosting](#hosting-globe_with_meridians)
- [SEO](#seo-spider)
- [Packages Used](#packages-used-package)
- [APIs Used](#apis-used-world_map)
- [Fonts and Images](#fonts-and-images-performing_arts)
- [Upcoming Features](#upcoming-features-construction)
- [Contributors](#contributors-man_technologistwoman_technologist)

<br /><br />


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

# Demo :movie_camera:
![](https://i.imgur.com/SXIQUhi.png)
## View live demo [here](https://xvisierra.github.io/portfolio).

<br />

<br></br>


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
>#### Set website theme in [`src/data/themeData.js`](https://github.com/hhhrrrttt222111/developer-portfolio/blob/master/src/data/themeData.js) and choose your favourite font from [`src/App.css`](https://github.com/hhhrrrttt222111/developer-portfolio/blob/master/src/App.css)

> #### About You - [`src/data/aboutData.js`](https://github.com/hhhrrrttt222111/developer-portfolio/blob/master/src/data/aboutData.js)

> #### Education details - [`src/data/educationData.js`](https://github.com/hhhrrrttt222111/developer-portfolio/blob/master/src/data/educationData.js) 

> #### Enter your Projects - [`src/data/projectsData.js`](https://github.com/hhhrrrttt222111/developer-portfolio/blob/master/src/data/projectsData.js)

> #### Add your Skills - [`src/data/skillsData.js`](https://github.com/hhhrrrttt222111/developer-portfolio/blob/master/src/data/skillsData.js)

> #### Experience - [`src/data/experienceData.js`](https://github.com/hhhrrrttt222111/developer-portfolio/blob/master/src/data/experienceData.js)

> #### Achievements - [`src/data/achievementData.js`](https://github.com/hhhrrrttt222111/developer-portfolio/blob/master/src/data/achievementData.js)

> #### Services - [`src/data/servicesData.js`](https://github.com/hhhrrrttt222111/developer-portfolio/blob/master/src/data/servicesData.js)

> #### Testimonials - [`src/data/testimonialsData.js`](https://github.com/hhhrrrttt222111/developer-portfolio/blob/master/src/data/testimonialsData.js)

> #### Your Blogs and Articles - [`src/data/blogData.js`](https://github.com/hhhrrrttt222111/developer-portfolio/blob/master/src/data/blogData.js)

> #### Contact Details - [`src/data/contactsData.js`](https://github.com/hhhrrrttt222111/developer-portfolio/blob/master/src/data/contactsData.js)

> #### Social Media Profiles - [`src/data/contactsData.js`](https://github.com/hhhrrrttt222111/developer-portfolio/blob/master/src/data/socialsData.js)

```javascript
// EXAMPLE
export const educationData = [
    {
        id: 1,
        institution: '-- INSTITUTION NAME --',
        course: '-- COURSE NAME --',
        startYear: '2017',
        endYear: '2019'
    },
    //
]
```

### Instructions and format for each section can be found inside the data files.
<br></br>

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

<br />

# Refrences :man_technologist::woman_technologist:

<div>
    <table>
        <tr>
            <td align="center"><a href="https://reactjsexample.com/"><img src="https://logos-download.com/wp-content/uploads/2016/09/React_logo_logotype_emblem.png" width="135px;" height="135px;" alt=""/><br /><b>https://reactjsexample.com/</b></a></td>
        </tr>
    </table>
</div>
