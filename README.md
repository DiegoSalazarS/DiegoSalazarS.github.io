# Diegoverse Portfolio Website

Welcome to the **Diegoverse** personal portfolio. This site showcases Diego Salazar’s background, education, work, volunteer experience, passions, and upcoming projects. It’s designed to be clean, engaging, and fully accessible, with a consistent dark theme and Montserrat typography.

---

## Table of Contents

1. [Features](#features)  
2. [Folder Structure](#folder-structure)  
3. [Nielsen’s 10 Usability Heuristics Compliance](#nielsens-10-usability-heuristics-compliance)  
4. [Credits](#credits)

---

## Features

- **Global Navbar** with clear branding and a Download-Resume button  
- **Responsive Layouts** for Home, Education, Work, Volunteer, Passions, and Projects pages  
- **Dark Theme** using Montserrat font for readability and style  
- **Animated “Coming Soon”** effect on the Projects page  
- **Accessible Imagery** with meaningful alt text on all `<img>` elements  
- **Footer** with social links and additional resources  
- **External CSS per page** for maintainability  

---

## Folder Structure

```
/assets
  /css
    styles_home.css
    styles_education.css
    styles_work.css
    styles_volunteer.css
    styles_passions.css
    styles_projects.css
  /img
    favicon.ico
    (all images with alt text)
  /docs
    diego-salazar-resume.pdf
index.html
education.html
work.html
volunteer.html
passions.html
projects.html
README.md
```

---

## Nielsen’s 10 Usability Heuristics Compliance

1. **Visibility of System Status**  
   - Animated loading (“Coming Soon”) and button hover effects provide instant feedback.  
   - Active navigation link underlines show the current page.

2. **Match Between System and the Real World**  
   - Clear, human-readable labels (Home, Education, Work, etc.) mirror real-world concepts.  
   - Icons (🎓, 💼, 🤝) reinforce meaning.

3. **User Control and Freedom**  
   - “Download Resume” button is always available in the navbar.  
   - Persistent navigation lets users jump between pages without dead ends.

4. **Consistency and Standards**  
   - Uniform layout structure, typography, and color palette across all pages.  
   - Standard link hover/active states and button behaviors.

5. **Error Prevention**  
   - External links use `rel="noopener noreferrer"` to prevent tab-nabbing.  
   - All links and assets are validated before deployment.

6. **Recognition Rather Than Recall**  
   - Persistent navbar and footer present context on every page.  
   - Clear section headings and icons minimize cognitive load.

7. **Flexibility and Efficiency of Use**  
   - Responsive design adapts to mobile and desktop automatically.  
   - External CSS per page keeps payload small and speeds up loading.

8. **Aesthetic and Minimalist Design**  
   - Dark theme with high-contrast text for readability.  
   - Clean layouts without unnecessary decoration; focus on content.

9. **Help Users Recognize, Diagnose, and Recover from Errors**  
   - Missing images display descriptive alt text rather than broken icons.  
   - Can add a custom 404 page to redirect users back to Home.

10. **Help and Documentation**  
    - This README provides clear setup, structure, and design rationale.  
    - Alt text and PR history document changes for future maintainers.

---

## Credits

- **Design Inspiration:** Uiverse.io, CSS Buttons, Neumorphism.io  
- **Icons & SVGs:** Bootstrap Icons  
- **Fonts:** Google Fonts – Montserrat  
- **Built by:** Diego Salazar (diegosala2004@gmail.com)

