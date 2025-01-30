# Meet With Artist Application

![License](https://img.shields.io/badge/license-MIT-blue.svg)
![Version](https://img.shields.io/badge/version-1.0.0-brightgreen.svg)
![Build Status](https://img.shields.io/badge/build-passing-brightgreen.svg)
![GitHub Issues](https://img.shields.io/github/issues/yourusername/meet-with-artist-application.svg)
![GitHub Pull Requests](https://img.shields.io/github/issues-pr/yourusername/meet-with-artist-application.svg)

![BMLG Logo](https://www.bigmachinelabelgroup.com/files/2022/09/logo-600x82.png)

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Live Demo](#live-demo)
- [Installation](#installation)
- [Usage](#usage)
- [Deployment](#deployment)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)
- [Acknowledgements](#acknowledgements)

## Overview

The **Meet With Artist Application** is a secure, multi-step web form developed by [Big Machine Label Group (BMLG)](https://www.bigmachinelabelgroup.com). This application enables fans to apply for exclusive meetings with their favorite artists under the BMLG umbrella. The form ensures data integrity and security by incorporating digital signature capture and photo verification, culminating in a downloadable PDF of the completed application.

## Features

- **Multi-Step Form:** Guides users through four essential steps:
  1. **Basic Information:** Collects personal details and artist/label selection.
  2. **Address Information:** Gathers user's residential address.
  3. **Signature Capture:** Allows users to digitally sign the application.
  4. **Face Capture:** Enables users to capture a photo for identity verification.

- **Enhanced Security:**
  - **SSL Encryption:** Ensures secure data transmission.
  - **End-to-End Data Protection:** Safeguards user information throughout the application process.
  - **Data Security Icons:** Visual indicators reassure users of data protection measures.

- **Client-Side PDF Generation:** Utilizes [jsPDF](https://github.com/parallax/jsPDF) to compile user inputs, signature, and photo into a downloadable PDF document.

- **Responsive Design:** Optimized for various devices and screen sizes, ensuring a seamless user experience across desktops, tablets, and mobile devices.

- **Elegant Styling:** Incorporates custom fonts (Montserrat, Playfair Display, Lora, Spectral) and dynamic animations for an engaging and professional appearance.

- **Interactive Elements:**
  - **Digital Signature Canvas:** Users can draw their signatures using mouse, touch, or stylus inputs.
  - **Camera Integration:** Allows users to capture and upload their photos directly within the form.

- **User Feedback:** Implements [SweetAlert2](https://sweetalert2.github.io/) for enhanced alert messages and notifications.

## Technologies Used

### Frontend

- **HTML5**
- **CSS3**
  - **Bootstrap 5.3.0** for responsive layout and styling.
  - **Font Awesome 6.4.0** for icons.
  - **Animate.css 4.1.1** for animations.
  - **Google Fonts:** Montserrat, Playfair Display, Lora, Spectral.
- **JavaScript (ES6)**
  - **jQuery 3.7.0** for DOM manipulation.
  - **SweetAlert2 11.7.12** for alert dialogs.
  - **Face API.js 0.22.2** for face detection and verification.
  - **jsPDF 2.5.1** for PDF generation.
  - **Lottie Files:** For engaging animations via Lottie Web Player.

### Deployment

- **Surge.sh:** Static site hosting platform for easy and fast deployment.

## Live Demo

Experience the application live at: [https://your-project.surge.sh](https://your-project.surge.sh)

## Installation

To run this project locally, follow these steps:

### Prerequisites

- **Node.js** and **npm** installed on your machine. You can download them from [here](https://nodejs.org/).

### Steps

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/yourusername/meet-with-artist-application.git
   cd meet-with-artist-application
