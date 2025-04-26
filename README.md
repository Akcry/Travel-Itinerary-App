# Travel-Itinerary-App
Project Overview The Travel Itinerary App is a responsive web application built using React. It demonstrates converting Figma designs into functional components while following best practices in React development. The app includes a sidebar for itineraries, a main content area for details, and a dynamically toggleable third pane

Project Structure
travel_itinerary_app/
├── public/
│   └── index.html          # Main HTML file
├── src/
│   ├── components/
│   │   ├── Sidebar.jsx     # Sidebar component
│   │   ├── Content.jsx     # Main content with toggleable third pane
│   ├── styles/
│   │   └── index.css       # TailwindCSS styles
│   ├── App.jsx             # Main App component
│   ├── index.js            # React entry point
├── tailwind.config.js      # TailwindCSS configuration
└── package.json            # Project dependencies and scripts

Component Hierarchy
App:
Parent component containing the overall layout.
Sidebar:
Displays a list of itineraries.
Built for reusability with customizable list items.
Content:
Displays itinerary details.
Includes a button to toggle a third pane.
Third Pane (part of Content):
Dynamically appears with additional details when triggered.

Challenges Faced
Responsive Design:
Adjusting layouts and typography to ensure consistency across screen sizes was challenging but resolved using TailwindCSS's responsive utilities.
Third Pane Functionality:
Implementing a dynamic layout that toggles seamlessly between two and three panes required careful state management.
Mock Integration:
Simulating integrations (e.g., API calls) while maintaining a clear and organized codebase was an insightful experience.

