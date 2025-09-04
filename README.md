
# Project Title
Configo-Login Page

This project is a responsive login page design for Configo, built using HTML5 and CSS. The layout replicates a login screen with a split design:

Left side: login form, branding.

Right side: marketing message with background gradient and branding graphic.



## Technologies used
HTML5 – Page structure.
CSS – Styling and responsive layout.
Google Fonts (Poppins) – Font family
## Style Overview
a) Main Styles (style.css)

Flexbox Layout: Used to divide the page into left and right halves.

Left Section: Contains logo, signup button, login form, and terms.

Right Section: Gradient background with overlay logo graphic and marketing message.

Form Styling: Inputs, labels, and buttons styled with hover/focus states.

Tooltip: Signup button shows a hover tooltip (Sign up only via Invitation).

Extras: Subtle hover effects for links and inputs.

b) Utilities (utilities.css)

Utility classes to quickly apply common properties:

.d-flex → Display flex

.d-flex-col → Flex column layout

.justify-content-center → Horizontal centering

.align-items-center → Vertical centering

.text-black, .text-white, .text-muted → Text color helpers

.text-decoration-none → Removes underline from links
## Section Breakdown

1.Header Bar
Logo on the left
Signup button with hover tooltip on the right

2.Login Card
Title + short instruction
Email and password input fields
Submit button ("Continue to Login")
Forgot password link

3.Terms Section
Privacy Policy and Terms of Use links

4.Right Section
Gradient background (blue shades)
Semi-transparent logo watermark
Marketing text ("For teams that want to go live yesterday!")
## Responsiveness

The design is fully responsive using media queries:

A) < 600px (Small Phones):           
Vertical stacking (login form above, marketing below).  
Smaller font sizes and buttons.   

B) 600px – 768px (Small Devices):  
Vertical stacking with adjusted spacing.  
Slightly larger text and form inputs.

C) 769px – 990px (Tablets):  
Horizontal split (50% each side).

D) 991px – 1200px (Large Devices):
Full horizontal split with balanced content.

E) > 1200px (Extra Large Screens):   
Layout optimized for desktops with larger marketing section.
## How To Run?

Clone or download this repository.

Place all files in the same folder:  
index.html  
style.css  
utilities.css  
static/ folder with logo and assets  
Open index.html in your browser.

Link to Git Public Repository: https://github.com/gerejakajal207/Configo-Login-Page.git

Live Link : https://gerejakajal207.github.io/Configo-Login-Page/
