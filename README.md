# HNG_track_0_profileCard
My first HNG Internship Project

A modern, accessible, and responsive profile card built with vanilla HTML, CSS, and JavaScript for the HNG Internship Stage 0 task.
Show Image
🌟 Features

Modern Glassmorphism Design - Dark theme with frosted glass effects and animated gradients
Fully Accessible - WCAG compliant with ARIA labels, keyboard navigation, and screen reader support
Responsive Layout - Optimized for mobile, tablet, and desktop devices
Interactive Tooltip - Hover over timestamp to see ISO local date/time
Real-time Updates - Timestamp updates every second
Smooth Animations - Subtle hover effects and transitions throughout

🎯 Task Requirements
This project fulfills all HNG Stage 0 requirements:
Required Elements (with exact data-testid attributes)

✅ Profile card container - test-profile-card
✅ User name - test-user-name
✅ Biography - test-user-bio
✅ Current time (milliseconds) - test-user-time
✅ Avatar image - test-user-avatar
✅ Social links container - test-user-social-links
✅ Individual social links - test-user-social-{network}
✅ Hobbies list - test-user-hobbies
✅ Dislikes list - test-user-dislikes

Technical Requirements

✅ Semantic HTML5 (<article>, <header>, <nav>, <section>, <figure>)
✅ Keyboard accessible with visible focus states
✅ Responsive design (mobile-first approach)
✅ Modern CSS (Flexbox & Grid)
✅ Time displayed in milliseconds using Date.now()
✅ Social links open in new tab with security attributes
✅ Proper alt text for images

🚀 Live Demo
Live Site: [Your Deployment URL Here]

📦 Installation & Local Development
Prerequisites

A modern web browser (Chrome, Firefox, Safari, Edge)
No build tools or dependencies required!

Running Locally

Clone the repository

bash   git clone https://github.com/yourusername/hng-profile-card.git
   cd hng-profile-card

Open the file

Simply open index.html in your browser
Or use a local server:

Using Python:

   # Python 3
   python -m http.server 8000
   
   # Python 2
   python -m SimpleHTTPServer 8000
Then visit http://localhost:8000

Using Node.js (with npx):

   # Node.js
   npx serve
   
Using VS Code:

   # VS Code

   Install "Live Server" extension
   Right-click index.html → "Open with Live Server"

🎨 Customization
Update Your Information

Personal Details (Lines 350-365)

html   <h1>Your Name</h1>
   <p class="bio">Your bio here...</p>

Avatar Image (Line 343)

html   <img src="your-image-url.jpg" alt="Your name and description">

Social Links (Lines 381-415)

html   <a href="https://github.com/yourusername">GitHub</a>

Hobbies & Dislikes (Lines 420-448)

html   <li>Your hobby here</li>
Color Scheme
Main colors used:

Primary Purple: #7877c6
Light Purple: #a3a3ff
Coral Orange: #ff8a65
Sky Blue: #63b3ed
Dark Background: #0a0a0a
Card Background: rgba(20, 20, 30, 0.7)

♿ Accessibility Features

Semantic HTML - Proper use of landmarks and heading hierarchy
ARIA Labels - Descriptive labels for screen readers
Keyboard Navigation - All interactive elements accessible via keyboard
Focus Indicators - Visible focus states for all focusable elements
Skip Link - Skip to main content for keyboard users
Alt Text - Descriptive alternative text for images
Color Contrast - WCAG AA compliant contrast ratios
Motion Preferences - Respects prefers-reduced-motion
High Contrast Mode - Support for high contrast display settings

🧪 Testing
Manual Testing Checklist

 All data-testid attributes present and correct
 Timestamp displays current time in milliseconds
 Timestamp tooltip shows ISO local time on hover
 Avatar image loads with proper alt text
 All social links open in new tab
 Keyboard navigation works (Tab, Enter, Shift+Tab)
 Focus indicators visible on all interactive elements
 Responsive on mobile (< 768px)
 Responsive on tablet (768px - 1024px)
 Responsive on desktop (> 1024px)
 Skip link appears on Tab press
 Screen reader announces all content correctly

Browser Testing
Tested and working on:

✅ Chrome/Edge (latest)
✅ Firefox (latest)
✅ Safari (latest)
✅ Mobile browsers (iOS Safari, Chrome Mobile)

📱 Responsive Breakpoints

Mobile: width <= 767px - Stacked layout
Desktop: width >= 768px - Side-by-side layout

🛠️ Technologies Used

HTML5 - Semantic markup
CSS3 - Modern styling with Flexbox, Grid, and animations
Vanilla JavaScript - No frameworks or libraries
No build tools - Pure client-side code

