# Asteroid Detector 3000

## Team Information

**Team Number:** 16-4

**Team Name:** Woodwinds in Space

**Team Members:**
- Kelsea Hall      -  keha5124       -  keha5124@colorado.edu 
- Mark Worster     -  mawo2024       -  mawo2024@colorado.edu 
- Reed Colloton    -  reed-colloton  -  reco9501@colorado.edu 
- Zachary McGuire  -  ZackMcGuire    -  zamc6801@colorado.edu 

## Project Description

The main page provides a list of asteroids most likely to hit Earth in the next several thousand years, and how much damage they could do. Other features would allow users to be given more data about a chosen asteroid, and charts that explain details about asteroids.

## Vision Statement

Raising awareness about dangerous asteroids in a kid-friendly manner

## Technology Stack

- **Frontend:** HTML, CSS, JavaScript
- **Backend:** Node.js, Express
- **Database:** PostgreSQL
- **External API:** NASA Near-Earth Object (NEO) API
- **Containerization:** Docker
- **Version Control:** Git/GitHub

## Prerequisites

- Docker and Docker Compose installed
- Git installed
- Node.js (for local development)

## Installation & Setup

1. Clone the repository:
```bash
git clone https://github.com/CU-CSCI3308-Fall2025/group-project-reed-colloton
cd group-project-reed-colloton
```

2. Navigate to the project source code:
```bash
cd ProjectSourceCode
```

3. Build and run the application using Docker:
```bash
docker-compose up -d
```

4. Access the application at `http://localhost:3000`

## Project Structure

```
.
├── TeamMeetingLogs/          # Weekly meeting minutes with TA
├── MilestoneSubmissions/     # Course deliverables and documentation
├── ProjectSourceCode/        # Application source code
│   ├── src/                  # Source files
│   ├── public/               # Static assets
│   ├── docker-compose.yaml   # Docker configuration
│   └── .gitignore           # Git ignore rules
└── README.md                 # This file
```


## Development Methodology

Scrum meetings and Kanban boards.

## Communication

We have a text chat, and plan to meet weekly over Zoom

**TA Meetings:** Friday at 11-11:15 on zoom


This project is created for educational purposes as part of CSCI 3308 at CU Boulder.

## Five Potential Risks

1. If the website isn't intuitive to use. This could prevent some people from using it, but this could be mitigated with icons and putting all links in the nav bar.
2. If the external API we're using changes or goes down. This would completely brick our website, so we'll make a backup database copy just in case
3. If our calculations end up being completely wrong. This wouldn't make the application stop working, but providing misleading or incorrect estimates about asteroid risk wouldn't be ideal. At the very least, we'll check a few calculations with what scientists have made to make sure we're in the right ballpark.
4. If we get rate-limited by the external API. This could cause our website to slow down or stop working completely, so we'd need to figure out what that limit is, and slow down requests if we get close to it.
5. If we get caught up in scope creep. This would hurt our ability to get out a working, complete project by the deadline, so we'll need to make sure to have a minimum viable product with plenty of time to spare.
