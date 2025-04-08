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
To keep the app convenient and accessible to as many users as possible, the development tools being used were chosen with cross-platform development in mind (supporting both Android and Apple phones). Flutter, a UI framework for the Dart language, was chosen since it requires little to no extra work to support a variety of target platforms. However, because the developer had zero prior experience with either the language or the framework, learning how to use these tools was an important part of the process. Completing coursework and prototype applications in Flutter was part of the risk management plan constructed in the beginning phases of the project, which enabled the smooth success of the project in later phases.

Android Studio was the IDE of choice for the project, due to its convenient integration of an Android emulator.

Additionally, the UI design of the application was developed from scratch. Wireframes, high-fidelity mockups, and navigational prototypes were thoroughly developed in Figma prior to the start of code development.

Technology | Justification
-|-
Android Studio Ladybug 2024.2.1 | IDE of choice
Dart 3.4.0 | Programming language of choice
Flutter 3.22.0 | UI framework for Dart
GitHub | Git platform
Jira | Project management platform
Figma | UI/UX design & prototyping

## Technical Approach
The FlyAZ Passport app is still in development, planning for completion over the course of at least three stages. With separation of concerns and abstraction in mind, stage one was designated to focus solely on the client application: a mobile app for both Android and iOS platforms. The goal was to develop a fully navigable front-end that looks and feels like the final product, only using mock data in place of integration with a back-end database for the time being.

Logical Design | Physical Design
-|-
![](/documents/LogicalDesign.png) Defines the various layers present in the client application, and a proposal for the design of the server application, using a REST API, which will be completed in a future stage. The client application consumes mock data until then. | ![](/documents/PhysicalDesign.png) Shows the relationship between the client, mock data, server, and database, including the specific devices and environment the client was tested on.

## Project Management
The project so far has followed the complete software development lifecycle (SDLC) process. Before the start of code development, a project proposal, risk management plan, technical & non-functional requirements, and througough design documentation were all carefully constructed to create as much clarity and direction for the project as possible. Thanks to this thorough planning, development has progressed smoothly since then in a sprint-based structure, using Jira to track user stories and generate progress reports. Weekly team meetings with the client and project mentors have been held throughout to provide updates, get feedback, and discuss the direction of the project. A test plan was maintained and performed throughout, to ensure the functionality of all features as development progressed. By the end of stage one, 118% of all initially defined project requirements were completed, including several features pulled in from out-of-scope.

Jira Backlog & Burndown Chart | Traceability Matrix & Test Cases
-|-
![](/documents/JiraBacklog.png) Backlog of user stories being tracked in Jira, to make sprints & project management easy. | ![](/documents/TraceabilityMatrix.png) Traceability matrix used to track the relationship between all user stories, documentation, code files, and test cases.
![](/documents/JiraBurndownChart.png) Example of a burndown chart generated in Jira based on the projected vs. completed user stories. | ![](/documents/TestCases.png) Test plan including test cases that correspond to every user story, ensuring all features function properly.

## Risks & Challenges
- Since the developer had no prior experience with Flutter (the framework), Dart (the language), Android Studio (the IDE), or even Figma (the UI/UX designer), choosing these tools was considered a major risk going into the project. To ensure this risk did not become an issue, a comprehensive risk management plan was put into place for it, including the completion of coursework on these tools and multiple test applications prior to the start of project development. This was completed smoothly and was what allowed the project to be as successful as it was, using the right tools for the job.
- Upon taking on this project, the developer did not initially expect to work solo. When the time came to plan it in further detail, the scope of the project had to be restructured, keeping in consideration what would be possible with only one developer, in the time allotted, and how it would make the most sense for the project to be divided, given the sole developer's skillset.

## Outstanding Issues
- Due to the developer's hardware limitations, the app was unable to be tested on any physical hardware, or on any iOS virtual devices. However, the app was tested on several Android virtual devices and on screens with the same resolution as the targeted iOS machines.
  - For the same reason, the flashlight feature in the QR code scanner was also unable to be tested.
- There are no other outstanding bugs or issues at this time, save for the fact that the application is not yet complete (only stage 1 having been finished).
