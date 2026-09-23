# Personal Portfolio Website

## Project Description

This project is a responsive personal portfolio website created for INFR3120 – Web and Scripting Programming. The purpose of the website is to present information about me, my technical skills, and some of the projects I have completed.

The website contains four separate pages:

- Home
- About Me
- Projects
- Contact Me

The website was developed using HTML5 and CSS3 and is designed to work across mobile, tablet, and laptop screen sizes.

---

## Responsive Design

The website uses separate CSS files and media queries to support different screen sizes. The layout changes depending on the width of the user's device.

### Mobile

The mobile layout is used for screens up to 767px wide.

```css
@media screen and (max-width: 767px)
```

This range was selected for smaller devices such as smartphones. On mobile screens, the navigation links are displayed vertically and the main content uses more of the available screen width.

### Tablet

The tablet layout is used for screens between 768px and 1023px wide.

```css
@media screen and (min-width: 768px) and (max-width: 1023px)
```

This range was selected for medium-sized devices such as tablets. The layout provides more space than the mobile version while keeping images, videos, forms, and other content appropriately sized.

### Laptop

The laptop layout is used for screens 1024px wide and larger.

```css
@media screen and (min-width: 1024px)
```

This range was selected for laptops and larger displays. A maximum width is used for the main content to prevent text and other elements from becoming too wide on large screens.

---

## Color Scheme

The website uses a blue-based color scheme selected using Adobe Color. The colors were chosen to create a professional, clean, and consistent appearance throughout the portfolio.

The main colors used are:

- Dark Blue: `#1D3557`
- Purple: `#4C3E96`
- Light Cream: `#F1FAEE`
- Light Gray: `#F4F4F4`
- Dark Text: `#222222`
- White: `#FFFFFF`

The blue colors are mainly used for the header, footer, headings, borders, buttons, and hover effects. The lighter colors are used for backgrounds and contrast, while the darker color is used to keep normal text readable.

---

## Gradients

The website uses two different linear gradient styles.

### Angle Linear Gradient

The header uses an angle linear gradient:

```css
background: linear-gradient(135deg, #1D2342, #4C3E96);
```

The `135deg` value creates a diagonal transition between the dark blue and medium blue colors.

### Directional Linear Gradient

The footer uses a directional linear gradient:

```css
background: linear-gradient(to right, #1D2342, #4C3E96);
```

The `to right` direction creates a horizontal color transition from the left side of the footer to the right side.

---

## Accessibility

Accessibility was considered while developing the website.

The website includes:

- Alternative text for images
- Labels associated with contact form inputs
- Semantic HTML elements such as `header`, `nav`, `main`, `section`, `article`, and `footer`
- Clear and consistent navigation
- Readable text and background contrast
- HTML5 video controls
- Responsive layouts for different screen sizes

---

## Contact Form Validation

The Contact Me page uses HTML validation to help ensure that users enter appropriate information before submitting the form.

The name, email, cell number, and comments fields are required.

The email field uses:

```html
<input type="email">
```

This allows the browser to check whether the entered information follows an email format.

The cell number field uses:

```html
pattern="[0-9]{10}"
```

This requires the user to enter a 10-digit phone number.

---

## About Me Media

The About Me page includes a personal image and a short introduction video.

The video uses the HTML5 `video` element and includes playback controls. A poster image is also displayed before the video begins playing.

The introduction video is approximately 45–60 seconds long.

---

## Project Page

The Projects page presents five projects that demonstrate skills in networking, data analytics, statistical analysis, business technology, and data visualization.

The projects include:

- Cisco Network Design & Configuration
- Data Analytics & Visualization
- SAS Data Analysis
- SAP ERP Business Simulation
- Student Performance Data Analysis

Semantic `article` elements are used to separate each project into its own self-contained section.

---

## Technologies Used

The technologies used to develop this portfolio include:

- HTML5
- CSS3
- Git
- GitHub
- GitHub Pages

No Flexbox was used in the development of the website. Responsive layouts were created using CSS media queries and fluid sizing.

---

## Testing

The website was tested using the following tools:

- W3C HTML Validator
- W3C CSS Validator
- W3C Link Checker
- Spell checking
- WAVE Web Accessibility Evaluation Tool

---

## Version Control

Git and GitHub are used for version control throughout the development of the portfolio.

Regular commits are made at different stages of development to document the progress of the website.

The final website was deployed publicly using GitHub Pages.

---

## Author

**Jeffery Nnabuife**

Technology Management Student  
Ontario Tech University  
Email: nnabuife202@gmail.com