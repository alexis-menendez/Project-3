# InnerOrbit: *Mood Journal, Mood Tracker, & Reflective Social Space*

```md
⚠️ Work In Progress
This project is currently under active development and is not yet complete.
Expect bugs, missing features, and unpolished UI while construction is underway.
```

## **Description**

**InnerOrbit** is a full-stack, responsive, and interactive single-page application built using the MERN stack with GraphQL and JWT authentication. This application solves a real-world problem using real data and is designed with a smooth user experience and polished, professional UI in mind. 

**Problem Solved:** People struggle to understand emotional patterns and maintain consistent emotional routines. Traditional journals often lack visual feedback, encouragement, or the option to connect meaningfully with others without oversharing or losing privacy.

**Concept:** InnerOrbit is a social ritual app — a place where users occasionally share glimpses of their mood or thoughts into a public “galaxy” while still maintaining control, anonymity, and consent.

**App Overview**
* Mood Tracker: Calendar-based mood logging with color coding and editable daily entries.
* Mood Journal: Private journal visualized as constellations of stars, each representing an entry.
* Mood Nebulas: Optional public feed for anonymous, tagged reflections with light interaction.
* Constellation Cards: Weekly reflection prompts with the option to share responses anonymously.
* Orbits: Invite-only pods for sharing progress and encouragement with close friends.
* Self-Care Companion: Digital pet that reflects your real-world wellness habits.
* Privacy & Auth: Secure JWT authentication with private-first, consent-based sharing.
* Design & Deployment: Mobile-first calm UI, Tailwind CSS, and CI/CD deployment on Render.  
  
  
| **Key Features**                                  | **Technology Stack**                                                  |
| ------------------------------------------------- | --------------------------------------------------------------------- |
| Mobile-first, responsive design                   | **Languages:** JavaScript                                             |
| Component-based architecture                      | **Front-End:** React, Apollo Client, React Router                     |
| GraphQL for client-server communication           | **Back-End:** Node.js, Express.js, Apollo Server, GraphQL             |
| MongoDB integration with Mongoose ODM             | **Database:** MongoDB                                                 |
| Secure user authentication with JWT               | **Authentication:** JWT                                               |
| Protected routes and user sessions                | **Security:** bcrypt, dotenv                                          |
| GitHub Actions for CI/CD                          | **CI/CD:** GitHub Actions                                             |
| Styled with [chosen approach]                     | **Styling:** [styled-components / Chakra UI / Ant Design / Pure CSS]  |   
| Deployed on Render                                | **Deployment:** Render                                                |


## Table of Contents  **(DO NOT FORGET TO UPDATE THIS AND DELETE ANY SECTIONS YOU ARE NOT USING!)**

- [Screenshots](#screenshots)
- [Walkthrough Video](#walkthrough-video)
- [Live Demo](#live-demo)
- [Future Development](#future-development)
- [Tests](#tests)
- [Documentation](#documentation)
- [Acknowledgements](#acknowledgements)
- [Contact](#contact)

## Screenshots

![projectscreenshot](LINK-GOES-HERE!)  **(DO NOT FORGET TO UPDATE THIS!)**  

## Walkthrough Video

- currently unavailable

## Live Demo

- [Inner-Orbit Demo](https://inner-orbit.onrender.com/) 

## Database Schema **(DO NOT FORGET TO UPDATE THIS!)**  
Field     |  Type      |  Required  |  Description              |
| ------- | ---------- | ---------- | ------------------------- |
_id       |  ObjectId  |  Yes       |  Auto-generated unique ID |
username  |  String    |  Yes       |  User's display name      |
email     |  String	   |  Yes       |  Must be unique           |
password  |  String    |  Yes       |  Hashed password          |
logs      |  [Log]     |  No        |  Reference to user's logs |


## Future Development

 - Expand data model and relationships
 - Integrate additional APIs
 - Add user dashboard with analytics
 - Implement automated testing
 - Enhance accessibility and internationalization

## Tests

There are currently no automated tests for this project

## Documentation

> **Note:** INSERT ANY NOTES ABOUT DOCUMENTATION HERE, DELETE IF THERE ARE NONE!

- [Repository](https://github.com/YOUR-REPO-URL-GOES-HERE) **(DO NOT FORGET TO UPDATE THIS!)**  
- [Google Slides](https://docs.google.com/presentation/YOUR-SLIDES-URL-GOES-HERE) **(DO NOT FORGET TO UPDATE THIS!)**  
- [Google Doc](https://docs.google.com/document/YOUR-GOOGLE-DOC-URL-GOES-HERE) **(DO NOT FORGET TO UPDATE THIS!)**  

## Acknowledgements

1. (ANY OUTSIDE AID) **(DO NOT FORGET TO UPDATE THIS!)**  
2. Squid Sqrite by [Penzilla](https://penzilla.itch.io/)

## Contact

If you have any questions, feel free to contact the team:

#### Project Lead, UI/UX Designer: [**Alex Menendez**](https://alex-menendez.onrender.com/) – Full-Stack Developer with a focus on UI/UX and team collaboration.

- **Website**: [Crafted-By-Alex](https://alex-menendez.onrender.com/)
- **LinkedIn**: [in/alex-d-menendez](https://www.linkedin.com/in/alex-d-menendez/)
- **GitHub**: [alexis-menendez](https://github.com/alexis-menendez)
- **Email**: [alexis.menendez@austincc.edu](https://alex-menendez.onrender.com/contact)

#### Frontend Lead: [**Constance RobinE**](https://zomblic.netlify.app/) – Full stack Developer

- **Website**: [Portfolio](https://zomblic.netlify.app/)
- **LinkedIn**: [in/Constance](www.linkedin.com/in/constance-robin/)
- **GitHub**: [zomblic](https://github.com/zomblic)
- **Email**: [zomblic@hotmail.com](https://zomblic.netlify.app/contact)

#### Backend Lead: [**Blake Brittain**](https://blakenb-portfolio.netlify.app/) – Full stack Developer

- **Website**: [Blake's portfolio](https://blakenb-portfolio.netlify.app/)
- **LinkedIn**: [in/Blake Brittain](https://www.linkedin.com/in/blake-n-brittain/)
- **GitHub**: [Blake Brittin](https://github.com/Blakenb)
- **Email**: [Blakenb87@gmail.com](Blakenb87@gmail.com)

#### Backend Developer: [**BACKEND-DEVELOPER-NAME**](https://BACKEND-DEVELOPER-NAME.netlify.app/) – BLAH, BLAH, BLAH  

- **Website**: [Portfolio](https://BACKEND-DEVELOPER-NAME.onrender.com/)
- **LinkedIn**: [in/BACKEND-DEVELOPER-NAME](https://www.linkedin.com/in/BACKEND-DEVELOPER-NAME/)
- **GitHub**: [BACKEND-DEVELOPER-USERNAME](https://github.com/alexis-menendez)
- **Email**: [BACKEND-DEVELOPER-NAME@email.com](https://BACKEND-DEVELOPER-NAME.onrender.com/contact)

