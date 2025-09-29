#Astronomical App using NASA API – Astronomy Picture of the Day (APOD)

![NASA APOD Banner](./img/banner.png)

---

## Project Overview

The **Astronomical App using NASA API** is a modern web application that allows users to explore the **Astronomy Picture of the Day (APOD)** provided by NASA. The app fetches daily space images or videos, along with descriptions and copyright information, allowing users to immerse themselves in the wonders of the universe.

This project is ideal for astronomy enthusiasts, students, educators, and anyone passionate about exploring space.

### Key Objectives

- Display NASA’s APOD dynamically.  
- Allow users to select a specific date to view images/videos.  
- Provide a **random APOD feature** to explore interesting astronomical content.  
- Include a **download button** for images.  
- Offer an **immersive UI** with background space video and a modern 3D card layout.  

---

## Live Demo

You can try the live version of this project here:  
[**View Live Demo**](https://yourdomain.com) *(Replace with your actual hosted URL)*

---

## Features

### Core Features

- **Daily APOD Fetching:** Loads the Astronomy Picture of the Day automatically.  
- **Date Picker:** Users can select any date and view the APOD of that day.  
- **Random APOD:** Click a button to view a random space image or video.  
- **Download Option:** Easily download HD images with one click.  
- **Responsive Layout:** Works perfectly on desktop, tablet, and mobile devices.  
- **Background Video:** Adds an immersive space-themed background video with subtle dark overlay.  
- **3D UI Card:** The information card has a 3D glassmorphic effect for better visual appeal.  
- **Video Support:** Supports embedded videos (e.g., YouTube APOD videos) and image content.  
- **Error Handling:** Displays alerts when API requests fail.  

---

## Technologies Used

- **Frontend:** HTML5, CSS3, JavaScript  
- **UI Frameworks:** [MDBootstrap](https://mdbootstrap.com/), Font Awesome icons  
- **Date Picker:** [Flatpickr](https://flatpickr.js.org/)  
- **API:** [NASA Astronomy Picture of the Day (APOD)](https://api.nasa.gov/)  
- **Hosting:** Can be hosted on GitHub Pages, Vercel, or Netlify  

---

## How It Works

1. The app makes a request to the NASA APOD API using a secure API key.  
2. The API responds with JSON containing image/video URL, title, explanation, copyright, and HD URL.  
3. The app dynamically displays the content in a responsive card layout.  
4. Users can pick a specific date, click **Random**, or view **today's APOD**.  
5. If the APOD is a video, it embeds the video directly; if it’s an image, it displays it with a download option.  

---

## Installation & Setup

To run this project locally:

1. **Clone the repository:**
   ```bash
   git clone https://github.com/YourUsername/Astronomical-app-using-NASA-API-showing-Astronomy-Picture-of-the-Day.git
   cd Astronomical-app-using-NASA-API-showing-Astronomy-Picture-of-the-Day
