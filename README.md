# -abdullah-dev-portfolio
Interactive, event-driven web application featuring dynamic DOM manipulation and responsive UI elements. 
Interactive Hiring Proposal 

​This project is a web-based, interactive job application tool designed to engage recruiters through dynamic UI elements rather than traditional application methods.

## Live Demo
Check out the live project here: [https://abdullah4229.github.io/-abdullah-dev-portfolio/](https://abdullah4229.github.io/-abdullah-dev-portfolio/)

​Technical Overview 

​The project is built using HTML5, CSS3, and Vanilla JavaScript. It is designed to be lightweight, fast, and responsive across devices without any external dependencies or frameworks.

​Key Features & Mechanics ​State Management: The application uses simple JavaScript functions to toggle visibility between the main interaction screen and the success screen. ​Dynamic DOM Manipulation: The primary interaction involves a decision-based interface where the UI reacts to user input in real-time. ​The "Escape" Logic 

​The interactive "No" button uses a specific event-driven approach to enhance user engagement:

​Event Listener: The button listens for the onmouseover event. ​Dynamic Positioning: Every time the cursor approaches the button, the JavaScript function triggers a random calculation for the button's top and left CSS properties (fixed positioning). ​Randomization: Using Math.random(), the function generates new coordinates within the viewport (vh and vw units), causing the button to instantly reposition itself, effectively "escaping" the cursor's interaction. ​Technologies ​HTML5: Semantic structure for the UI. ​CSS3: Flexbox for alignment, transitions for smooth interactions, and fixed positioning for dynamic elements. ​JavaScript: Logic handling for DOM event listeners and coordinate randomization. 
