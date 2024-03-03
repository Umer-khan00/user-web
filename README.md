# Photo Tiles E-Commerce Website

Welcome to Photo Tiles, your premier destination for beautifully crafted frames. Explore and purchase frames from various categories, including Photo frames, Abstract, Islamic, Kids frames, and more. This website is built using HTML, CSS, and JavaScript, with Firebase Authentication for secure login and signup functionality.

## Web Images

![sample text](![image](https://github.com/NAWSHERWAN-ALI/JS-practice/assets/153446332/8e0d8b17-6a1b-4344-aad5-e83dc3d5b9ed)
)

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [Firebase Authentication](#firebase-authentication)
- [Contributing](#contributing)
- [License](#license)

## Introduction

Photo Tiles is an e-commerce platform dedicated to providing users with high-quality frames to preserve and showcase their cherished memories. The website is designed to be user-friendly, allowing seamless navigation through different frame categories.

## Features

- **Categories:** Explore frames in various categories, including Photo frames, Abstract, Islamic, Kids frames, and more.
- **Secure Authentication:** Utilize Firebase Authentication for a secure and reliable login and signup process.
- **User-Friendly Design:** The website is designed with a focus on user experience, making it easy for users to browse, select, and purchase frames.

## Getting Started

To get started with Photo Tiles on your local machine, follow these steps
[Photo Tiles website](https://user-web-chi.vercel.app/index.html)
Open the project in your preferred code editor.
Launch the index.html file in your browser.


## Usage

Once the website is up and running, users can:

- Browse frames in different categories.
- Create an account or log in using Firebase Authentication.
- Add frames to their cart and proceed to checkout.

## Firebase Authentication

Photo Tiles uses Firebase Authentication to ensure a secure and reliable user authentication process. To integrate Firebase Authentication into your project, follow these steps:

1. Set up a Firebase project and enable Authentication.
2. Obtain your Firebase configuration details.
3. Replace the placeholder Firebase configuration in `app.js` with your actual configuration.

```javascript
// Replace this with your Firebase configuration
const firebaseConfig = {
  apiKey: "YOUR_API_KEY",
  authDomain: "your-project.firebaseapp.com",
  // ... other configuration details
};

// Initialize Firebase
firebase.initializeApp(firebaseConfig);


