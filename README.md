# Compass Volunteer Flow – Code Showcase

**A tool that makes helping others easier.**  
This is my frontend implementation of the Compass flow, developed for the non-profit organization noQ – a step-by-step guide that helps volunteers find the right support services for people in need.

---

## About the Project

Volunteers often face information overload – what services are available, who qualifies, how do you narrow things down?  
**Compass solves that with a structured flow:**  
**Start → Service Type → Age Group → Filter → Results.**

I built the entire frontend in React, including:
- Multi-step navigation (React Router v6)
- State management with Context API
- Dynamic filtering & text search
- API integration with query parameters

> Development started with mocked data to build and test logic. Once stable, I integrated the flow with noQ’s backend in production.

---

## Demo

📺 [Watch the walkthrough](https://www.youtube.com/watch?v=L4yjd7nKKBI)  
*Language: Swedish*  
A short video demo of the full user flow I built – from first click to final result.

---

## Features

- Multi-step page flow with persistent user input
- Filter results by tags, age group, and service type
- Text-based search across several fields
- Mocked vs. live API data toggle
- Clean, modular code structure

---

## Tech Stack

- **React**
- **React Router v6.3**
- **Context API**
- **JavaScript (ES6+)**
- **Tailwind CSS**
- **React Icons**
- **Vite** (development environment)

---

## Note

Some parts as `useLogin` reference noQ’s internal logic. These are included for structural accuracy but are not functional in this standalone showcase.

---

## Contact

Curious about this project or want to connect?

**Melissa Öström**  
Fullstack Development Student @ Nackademin 

Fullstack Developer (Pro bono) @ noQ

📧 melisa.ostrom@outlook.com  

[LinkedIn](https://www.linkedin.com/in/melissaostrom)

