# CosmoQuest
Space Tourism Website
Overview
This project is a Space Tourism website built using Angular and TypeScript to provide a visually engaging and interactive experience for users interested in space travel. It was developed as part of the Frontend Mentor challenge, leveraging modern front-end technologies and best practices for web development.

Features
Responsive Design: The website is designed to work seamlessly across all screen sizes, with a focus on a mobile-first workflow.
Smooth Animations: The router animation effect creates a dynamic user experience when transitioning between different pages.
Interactive Components: Includes multiple pages such as destinations, crew, and technology, with a navigation bar and visually appealing layouts.
Technologies Used
Angular: The front-end framework used to build the application, enabling dynamic routing, modular architecture, and reusable components.
TypeScript: TypeScript was used for type-safe, object-oriented programming to enhance code quality and maintainability.
CSS (SASS): SASS was utilized as the CSS preprocessor for easier management of styles with variables, mixins, and nesting.
Flexbox: Employed Flexbox for creating flexible layouts that adjust based on screen size, ensuring responsive design.
Semantic HTML5: Semantic HTML5 tags were used for accessibility and better SEO optimization.
Key Features & Benefits
Custom Router Animation: Implemented custom page transition animations using Angular's router. Referenced official Angular documentation for effective implementation.
Mobile-First Workflow: The website is optimized for mobile devices first, ensuring fast load times and an engaging mobile experience before scaling up to larger screens.
Reusable Components: Leveraged Angular’s component-based architecture to create reusable and maintainable UI elements like navigation bars, buttons, and cards.
SASS for Scalability: Using SASS allowed for a scalable and organized stylesheet structure, ensuring easier maintenance and future updates.
Project Structure
app.component.ts: Main entry component with routing logic and custom animations.
app.module.ts: The main Angular module, managing imports, declarations, and bootstrapping of the application.
app-routing.module.ts: Handles routing between different pages (Destinations, Crew, Technology, etc.) and page-specific transitions.
components/navbar/navbar.component.ts: The navigation bar component, offering seamless navigation between sections.
pages/home/home.component.ts: The home page of the website.
pages/destinations/destinations.component.ts: Page showcasing various space travel destinations.
pages/crew/crew.component.ts: Page introducing the crew behind the space missions.
pages/technology/technology.component.ts: Page displaying cutting-edge technologies used for space exploration.
Setup Instructions
To run the project locally:

Clone the repository:


git clone https://github.com/your-username/space-tourism-website.git
cd space-tourism-website
Install dependencies:


npm install
Run the application:

ng serve
Visit http://localhost:4200/ in your browser.

Useful Resources
Angular Official Documentation: https://angular.io/docs
Used the documentation to implement the router animations and ensure best practices for routing.
Frontend Mentor Challenge: Space Tourism Website Challenge
