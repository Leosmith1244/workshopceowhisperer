The CEO Whisperer: Personal Branding for the Ambitious Workshop Website
This repository contains the static website for "The CEO Whisperer: Personal Branding for the Ambitious" workshop, hosted by PR Pros Toastmasters. This site serves as a central hub for workshop information, agenda, speaker outlines, and valuable resources to help attendees elevate their personal brand and executive presence.
Project Overview
This website is designed to be a compelling and informative platform for a personal branding workshop series. It aims to:
Attract & Inform: Provide key details about the workshop, its benefits, and the engaging sessions.
Empower Attendees: Offer in-depth speaker outlines and a curated collection of resources and tools for continued learning.
Showcase PR Pros Toastmasters: Highlight the club's commitment to empowering professionals in communication and leadership.
Website Structure
The website consists of the following pages:
index.html: The main landing page, providing an overview of the workshop, testimonials, and a waitlist registration form.
agenda.html: A detailed timeline of the workshop sessions, including speeches and interactive activities.
speakers.html: A page dedicated to each speech, providing a fleshed-out outline following the AIDA model.
aida.html: An explanatory page detailing the AIDA (Attention, Interest, Desire, Action) model and its application in public speaking and personal branding, complete with real-life examples.
resources.html: A valuable page offering downloadable checklists, visual guides, templates, recommended reading, and links to further enhance personal branding efforts.
Features
Responsive Design: Optimized for viewing on desktops, tablets, and mobile devices.
Toastmasters Branding: Utilizes the specified Toastmasters brand colors for a cohesive look and feel.
Engaging Content: Detailed descriptions, compelling calls to action, and structured information.
Interactive Elements: Hover effects on cards, and a subtle fade-in animation on the agenda timeline.
Form Integration (Netlify): The waitlist form on index.html is set up to work with Netlify Forms for easy data collection.
Technologies Used
HTML5: For semantic structure.
CSS3: For styling, including responsive design. All CSS is embedded directly in each HTML file for self-containment.
JavaScript: For minor interactivity (e.g., form validation, agenda animations).
Font Awesome: For icons (<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">).
Google Fonts: Montserrat and Open Sans for typography (<link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@400;600;700&family=Open+Sans:wght@300;400;600&display=swap" rel="stylesheet">).
Setup and Deployment
This website is designed for easy deployment as a static site.
1. Clone the Repository
git clone <your-repository-url>
cd the-ceo-whisperer-workshop

2. Local Development (Optional)
You can open any of the .html files directly in your web browser to view the website locally. No special server setup is required.
open index.html # On macOS
start index.html # On Windows
xdg-open index.html # On Linux

3. Deployment with GitHub Pages / Netlify
This website is perfectly suited for deployment with services like GitHub Pages or Netlify.
Using Netlify (Recommended for Form Functionality):
Create a New Site: Log in to Netlify and click "Add new site" -> "Import an existing project."
Connect to Git Provider: Connect to your GitHub repository where this project is hosted.
Deployment Settings:
Branch to deploy: main (or your primary branch)
Build command: Leave empty (static site)
Publish directory: Leave empty (or /, as it's the root)
Deploy Site: Click "Deploy site." Netlify will automatically detect the HTML files and deploy your site.
For the waitlist form on index.html to work:
Ensure the form tag has the attributes data-netlify="true" and name="ceo-whisperer-waitlist".
Netlify automatically handles forms. You can view submissions in your Netlify dashboard under "Forms."
Using GitHub Pages:
Create Repository: Push this project to a new GitHub repository.
Go to Settings: In your GitHub repository, navigate to "Settings" -> "Pages."
Source: Under "Build and deployment," choose "Deploy from a branch." Select your primary branch (e.g., main) and the /(root) folder.
Save: Click "Save." GitHub Pages will then build and deploy your site, providing a URL (e.g., yourusername.github.io/your-repository-name).
Contributing
As this is a specific workshop website, direct contributions are not typically expected. However, if you find any issues or have suggestions for improvements, please open an issue in the GitHub repository.
Contact
For questions about the workshop or PR Pros Toastmasters, please visit our official website: https://prpros.toastmastersclubs.org/
