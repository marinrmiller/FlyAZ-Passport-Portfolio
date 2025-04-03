# FlyAZ Passport: Stage One
![Several screenshots of the FlyAZ Passport app. In order, the home, progress, location, and leaderboard pages are shown.](/screenshots/all.png)

Across all of Arizona, there are 65 public-use airstrips and airports. As a pilot, what better way is there to practice flight planning and landing than visiting a variety of airports across your home state? This was the goal in the minds of the AZ Pilots Association that spawned the FlyAZ Passport program, which encourages pilots to fly into as many different airport environments as they can, using one convenient mobile app to quickly scan and track their progress as they go.

Intended to promote discovery, education, and safe flight planning, the FlyAZ Passport app is intended provide a milestone-based tourism program for pilots of Arizona to participate in at their leisure. Users will be able to log their visits to registered locations, track their progress, and compare scores with fellow users on a leaderboard.

## Functional Requirements
- In-app QR code scanning to register location visits
- Login, registration, update account, & password reset
- Uncluttered home page to summarize progress at a glance
- Progress tracker listing all locations, their visitation status, and completion percent toward the next milestone
- Detailed location info viewer for all locations
- Opt-in leaderboard, displaying users with the furthest progress to promote friendly competition
- Sleek, modern, and easy-to-navigate user interface throughout

## Non-Functional Requirements
- Compliance with the following WCAG 2.2 standards:
  - Success Criterion 1.4.1 Use of Color
  - Success Criterion 1.4.3 Contrast (Minimum)
  - Success Criterion 1.4.11 Non-text Contrast
- Testing for layout responsiveness on the following devices:
  - Pixel 6, Pixel 6 Pro, Pixel 7, Pixel 7 Pro, Pixel 8, & Pixel 8 Pro virtual machines
  - iPhone 13, iPhone 13 Pro Max, iPhone 14, iPhone 14 Pro Max, iPhone 15, iPhone 15 Pro Max, iPhone 16, & iPhone 16 Pro Max screen sizes
  - iPad 10th Generation, iPad Pro 11-in, & iPad Pro 13-in screen sizes

## Technologies Used
To keep the app convenient and accessible to as many users as possible, the development tools being used were chosen with cross-platform development in mind (supporting both Android and Apple phones). Flutter, a UI framework for the Dart language, makes this easy. Android Studio was the IDE of choice for its convenient integration of an Android emulator.

Additionally, the UI design of the application was developed from scratch. Wireframes, high-fidelity mockups, and navigational prototypes were thoroughly developed in Figma prior to the start of code development.

Technology | Justification
-|-
Android Studio Ladybug 2024.2.1 | IDE of choice
Dart 3.4.0 | Programming language of choice
Flutter 3.22.0 | UI framework for Dart
GitHub | Git platform
Jira | Project management platform
Figma | UI/UX design & prototyping

## Technical Approach & Project Management
The FlyAZ Passport app is still in development, planning for completion over the course of at least three stages. With separation of concerns and abstraction in mind, stage one was designated to focus solely on the client application: a mobile app for both Android and iOS platforms. The goal was to develop a fully navigable front-end that looks and feels like the final product, only using mock data in place of integration with a back-end database for the time being.

The project so far has followed the complete software development lifecycle (SDLC) process. Before the start of code development, a project proposal, risk management plan, technical & non-functional requirements, and througough design documentation were all carefully constructed to create as much clarity and direction for the project as possible. Thanks to this thorough planning, development has progressed smoothly since then in a sprint-based structure, using Jira to track user stories and generate progress reports. Weekly team meetings with the client and project mentors have been held throughout to provide updates, get feedback, and discuss the direction of the project. By the end of stage one, 118% of all initially defined project requirements were completed, including several features pulled in from out-of-scope.

Logical Design | Physical Design
:-:|:-:
![](/documents/LogicalDesign.png) | ![](/documents/PhysicalDesign.png)

**UML Diagram**
![](/documents/UMLDiagram.png)

## Risks & Challenges
wip

## Outstanding Issues
wip
