# Earphones-3D
Responsive Carousel Slider with Detail View
This project is a fully functional and responsive carousel slider built using HTML, CSS, and vanilla JavaScript. It features a clean UI with smooth transitions and interactive controls for navigating through a series of items or cards. Designed with performance and user experience in mind, the carousel works seamlessly across modern browsers and devices.

Features
Next/Previous Navigation: Users can move through items with dedicated buttons.

Smooth Transitions: Animations are handled using CSS for a smooth visual experience.

Detail View: Each item includes a “See More” button that expands the item to show more information in a dedicated view.

Back Button: Allows users to exit the detail view and return to the main carousel.

Click Throttling: Disables navigation buttons temporarily during animation to prevent glitches from rapid clicking.

Clean DOM Manipulation: Items are dynamically re-ordered using appendChild and prepend without page reloads.

Minimal Dependencies: Built with pure JavaScript—no external libraries or frameworks required.


How It Works
When a user clicks the “Next” or “Prev” button, the first or last item in the carousel is moved accordingly using DOM methods, and the carousel's animation class (next or prev) is triggered. The “See More” button opens a detail view by adding a showDetail class, and the “Back” button removes it. Button throttling is managed via pointerEvents and setTimeout.


Use Cases
Perfect for product showcases, portfolios, testimonials, image galleries, or any scenario that benefits from compact content presentation with the option to view more.

