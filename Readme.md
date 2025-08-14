# ☀️ Sunrise Primary School Website

Welcome to the official website for Sunrise Primary School! This is a vibrant and playful one-page website designed to showcase our school's mission, curriculum, faculty, and events. It also includes a help desk and a contact form to engage with parents and the community.

## ✨ Features

- **Responsive Design:** The website is fully responsive and looks great on desktops, tablets, and mobile devices.
- **Vibrant Color Palette:** A cheerful color scheme is used to create a welcoming and engaging atmosphere.
- **Playful Animations:**
  - **Floating Elements:** Decorative shapes and buttons "float" gently to add a touch of magic.
  - **Bounce Animation:** The logo and hero text have a subtle bounce animation for a dynamic feel.
  - **Card Effects:** Cards lift and rotate slightly on hover to draw attention.
- **Dynamic Content Sections:**
  - **Hero Section:** A captivating introduction with a background image and animated text.
  - **About Section:** Information about the school's mission and history.
  - **Curriculum Section:** Highlights of our fun-filled educational program.
  - **Faculty Section:** Introduces our wonderful teachers with their expertise.
  - **Events Section:** Showcases exciting school events and activities.
  - **Help Desk:** A contact form for inquiries and support.
- **Form Integration:** Forms for the Help Desk and footer are integrated with a Google Apps Script to collect submissions.
- **Custom Notifications:** A custom notification system provides user feedback for form submissions.
- **Confetti Effect:** A fun confetti animation plays upon successful form submission.
- **Smooth Scrolling:** All navigation links use smooth scrolling to a seamless user experience.

## 🚀 Deployment

This project is deployed using **Vercel**. To deploy your own version of this website, follow these steps:

1.  **Clone this repository** from your version control system (e.g., GitHub).
2.  **Sign in to your Vercel account** or create a new one.
3.  On the Vercel dashboard, click **"Add New"** and then **"Project."**
4.  **Import your project** from your Git repository. Vercel will automatically detect the project and its configuration.
5.  Click **"Deploy."**

Vercel will build and deploy your project, providing you with a live URL. Any new commits to the main branch of your repository will automatically trigger a new deployment.

### Connecting to Google Apps Script

The website's forms are configured to send data to a Google Sheet using a **Google Apps Script**.

1.  **Create a Google Sheet:** Set up a new Google Sheet to store your form data. Create tabs named `HelpdeskContacts` and `FooterContacts`.
2.  **Create a Google Apps Script:**
    - In your Google Sheet, go to **Extensions > Apps Script**.
    - Paste the `WEB_APP_URL` from your `script.js` file into your Apps Script.
    - Deploy the script as a Web App to get a new `WEB_APP_URL`.
    - Replace the placeholder `WEB_APP_URL` in your `script.js` file with the URL from your Apps Script deployment.
3.  **Update the Script URL:**
    - In `script.js`, change `const WEB_APP_URL = "https://script.google.com/macros/s/YOUR_SCRIPT_ID/exec";` to your new URL.
4.  **Redeploy:** Push your changes to your Git repository, and Vercel will automatically redeploy the site with the updated script URL.

## 📁 Project Structure

The project is structured as a simple static website:
Of course. Here is a complete README.md file for your website, ready to be copied and pasted into your project. It includes all the relevant details for a Vercel deployment.

Markdown

# ☀️ Sunrise Primary School Website

Welcome to the official website for Sunrise Primary School! This is a vibrant and playful one-page website designed to showcase our school's mission, curriculum, faculty, and events. It also includes a help desk and a contact form to engage with parents and the community.

## ✨ Features

- **Responsive Design:** The website is fully responsive and looks great on desktops, tablets, and mobile devices.
- **Vibrant Color Palette:** A cheerful color scheme is used to create a welcoming and engaging atmosphere.
- **Playful Animations:**
  - **Floating Elements:** Decorative shapes and buttons "float" gently to add a touch of magic.
  - **Bounce Animation:** The logo and hero text have a subtle bounce animation for a dynamic feel.
  - **Card Effects:** Cards lift and rotate slightly on hover to draw attention.
- **Dynamic Content Sections:**
  - **Hero Section:** A captivating introduction with a background image and animated text.
  - **About Section:** Information about the school's mission and history.
  - **Curriculum Section:** Highlights of our fun-filled educational program.
  - **Faculty Section:** Introduces our wonderful teachers with their expertise.
  - **Events Section:** Showcases exciting school events and activities.
  - **Help Desk:** A contact form for inquiries and support.
- **Form Integration:** Forms for the Help Desk and footer are integrated with a Google Apps Script to collect submissions.
- **Custom Notifications:** A custom notification system provides user feedback for form submissions.
- **Confetti Effect:** A fun confetti animation plays upon successful form submission.
- **Smooth Scrolling:** All navigation links use smooth scrolling to a seamless user experience.

## 🚀 Deployment

This project is deployed using **Vercel**. To deploy your own version of this website, follow these steps:

1.  **Clone this repository** from your version control system (e.g., GitHub).
2.  **Sign in to your Vercel account** or create a new one.
3.  On the Vercel dashboard, click **"Add New"** and then **"Project."**
4.  **Import your project** from your Git repository. Vercel will automatically detect the project and its configuration.
5.  Click **"Deploy."**

Vercel will build and deploy your project, providing you with a live URL. Any new commits to the main branch of your repository will automatically trigger a new deployment.

### Connecting to Google Apps Script

The website's forms are configured to send data to a Google Sheet using a **Google Apps Script**.

1.  **Create a Google Sheet:** Set up a new Google Sheet to store your form data. Create tabs named `HelpdeskContacts` and `FooterContacts`.
2.  **Create a Google Apps Script:**
    - In your Google Sheet, go to **Extensions > Apps Script**.
    - Paste the `WEB_APP_URL` from your `script.js` file into your Apps Script.
    - Deploy the script as a Web App to get a new `WEB_APP_URL`.
    - Replace the placeholder `WEB_APP_URL` in your `script.js` file with the URL from your Apps Script deployment.
3.  **Update the Script URL:**
    - In `script.js`, change `const WEB_APP_URL = "https://script.google.com/macros/s/YOUR_SCRIPT_ID/exec";` to your new URL.
4.  **Redeploy:** Push your changes to your Git repository, and Vercel will automatically redeploy the site with the updated script URL.

## 📁 Project Structure

The project is structured as a simple static website:

/
├── index.html         # Main HTML file for the website structure.
├── style.css          # All the CSS for styling and animations.
├── script.js          # JavaScript for form handling, animations, and other dynamic features.
├── favicon.png        # Website favicon.
└── README.md          # This file.

## 📝 Technologies Used

-   **HTML5:** For the website structure.
-   **CSS3:** For styling, including Flexbox for layout and keyframe animations.
-   **JavaScript (ES6+):** For interactive features, form handling, and API integration.
-   **Google Apps Script:** For the backend form submissions to a Google Sheet.
-   **Vercel:** For deployment and hosting.


