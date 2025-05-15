# Compass Volunteer Flow – Code Showcase

This repository showcases my personal implementation of the Compass flow developed for the non-profit organization noQ. The purpose of the flow is to guide volunteers through a step-by-step interface to find the most relevant services for people in need.

This is a code-only version and is not intended to run as a standalone application.

---

## About the Project

The Compass flow allows volunteers to select the type of service, define a target age group, apply filters, and search among available resources. I was responsible for building the entire frontend flow using React, including navigation, state management, and data filtering.

Development started with mocked data to design and test functionality. Once the frontend logic was complete, the flow was integrated with noQ’s backend API and query parameters were used to fetch relevant data based on user input.

---

## Demo

A short walkthrough of the Compass volunteer flow I built at noQ.

[Watch the video here](https://youtu.be/L4yjd7nKKBI)  
*Language: Swedish*

---

## Key Features

- Multi-step page flow: Start → Service Type → Age Group → Result Page
- Context API to store and share user selections across steps
- Resource filtering by tags, age, and service type
- Text-based search across multiple fields
- Mocked data used during development
- API integration implemented in production

---

## Technologies Used

- React
- React Router v6.3
- Context API
- JavaScript (ES6+)
- React Icons
- Tailwind CSS
- Vite (used during development)

---

## Notes

Some files reference internal logic from the original noQ codebase (for example, `useLogin`). These are included only to preserve the original structure and are not functional in this standalone version. 

---

## Contact

Feel free to reach out if you want to know more about the project or my work!

**Melissa Öström**  
Fullstack Development Student | Volunteer Developer  
melisa.ostrom@outlook.com  
[LinkedIn](https://www.linkedin.com/in/melissaostrom)

