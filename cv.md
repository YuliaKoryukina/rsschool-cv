# Iuliia Koriukina

## Contact Information
* City: Belgrade, Serbia
* Email: koryuckina.yu@yandex.ru
* GitHub: https://github.com/YuliaKoryukina
* LinkedIn: https://www.linkedin.com/in/koryukina-yulia/
* Portfolio website: https://yuliakoryukina.website/
* Discord: silence_julia0019 

## About Me
Junior frontend developer and UI/UX designer. I am learning to create modern interfaces and clean code. I strive to combine visual aesthetics with technical implementation. Currently I am doing an internship where I create landing pages and work with WordPress. I am looking for an opportunity to continue developing in this field and learn from more experienced colleagues. I am a quick learner, attentive to details and responsible.

## Skills
* HTML5: semantic markup, accessibility, modern tags
* CSS3: Flexbox, Grid, responsive design
* JavaScript: actively learning, ES6+ syntax
* CMS: WordPress (theme customization, template modification)
* Tools: Git, GitHub, VS Code
* Design: Figma (prototyping, layouts, components), basic Photoshop
UI/UX: user flow design, typography, composition, color

## Work Experience
Frontend Developer Intern | Internship, January 2026 — present
* Develop and customize landing pages under the guidance of a mentor.
* Create pages using HTML/CSS, add styles and scripts.
* Work with WordPress: theme customization, modification of existing templates.

## Code Examples
**Palindrome check function:**
   ```javascript
   function palindrom(yourtext) {
     let sumSymbol = yourtext.length;
     console.log("Number of characters: " + sumSymbol);
     
     let countWords = (yourtext) => yourtext.trim().split(/\s+/).length;
     console.log("Number of words: " + countWords(yourtext));
     
     if (yourtext.includes(" ")) {
       let textWithoutSpaces = yourtext.replaceAll(" ", "");
       console.log("Text without spaces: " + textWithoutSpaces);
     } else {
       console.log("No spaces in text");
     }
     
     let sentences = yourtext.match(/[^.!?]+[.!?]+/g) || [];
     console.log("Number of sentences: " + sentences.length);
     
     let toLowerText = yourtext.toLowerCase();
     let reversText = toLowerText.split("").reverse().join("");
     if (toLowerText === reversText) {
       console.log("This is a palindrome");
     } else {
       console.log("This is not a palindrome");
     }
     
     let reverseText = yourtext.split("").reverse().join("");
     console.log("Reversed version: " + reverseText);
   }
   palindrom("Шалаш");

## Education
Saratov State Law Academy
Bachelor's degree, 2021
### Courses:
* Web development for beginners: HTML and CSS (Stepik)
* Web technologies: entry level
* FRONTEND: HTML CSS JS
* JavaScript for beginners

## English Language
* Level: Elementary (A2)