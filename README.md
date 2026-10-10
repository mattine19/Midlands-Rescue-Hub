# Midlands-Rescue-Hub
# 🐾 Midlands Rescue Hub

### A Software Design & UML Architecture Project

Midlands Rescue Hub is a proposed software platform designed to help animal rescues, shelters, and veterinary clinics coordinate animal placement requests and identify suitable foster volunteers.

The project explores how software architecture and object-oriented design can help organize animal information, manage placement requests, rank potential volunteer matches, and coordinate outreach.

## 🎯 Project Goals

- Organize animal information and placement requests.
- Identify suitable foster volunteers based on compatibility, availability, and care requirements.
- Prioritize requests according to urgency.
- Support coordinated volunteer outreach and follow-up.
- Provide a structured system design that can serve as a foundation for future development.

## 🏗️ System Architecture

The UML class diagram outlines the proposed classes, their responsibilities, and the relationships between system components.

Key components include:

| Component | Responsibility |
|---|---|
| `Animal` | Represents an animal and its care requirements. |
| `Volunteer` | Stores foster preferences, capacity, availability, and relevant experience. |
| `PlacementRequest` | Represents an animal placement request, including urgency and status. |
| `MatchingEngine` | Ranks potential volunteers and calculates fit scores. |
| `VolunteerScore` | Represents a volunteer's match score and the reason for the match. |
| `DispatchService` | Coordinates outreach waves, SMS notification operations, and volunteer acceptance. |
| `Organization` | Represents participating rescues, shelters, and veterinary clinics. |
| `RescueHubFacade` | Provides a central interface for coordinating major system operations. |
| `DataLoader` / `DataWriter` | Handle planned data import and export operations. |
| `RequestList` / `VolunteerList` / `OrganizationList` | Manage collections of requests, volunteers, and organizations. |

The design also includes enumerations for animal types, request urgency, request status, and organization tiers.

## 🔄 Proposed Workflow

1. **Register:** An organization creates an animal placement request.
2. **Evaluate:** The system considers animal requirements and volunteer suitability.
3. **Match:** Potential foster volunteers are ranked using fit scores.
4. **Dispatch:** The design supports outreach to selected volunteers in waves.
5. **Record:** Volunteer responses are recorded as the request progresses toward fulfillment.

## 📁 Project Files

- `index.html` — Portfolio website showcasing the project concept and architecture.
- `Midlands-Rescue-Hub-UML.pdf` — UML class diagram exported from Lucidchart.

## 🛠️ Tools & Concepts

- **Lucidchart** — UML class diagram and system modeling.
- **HTML and CSS** — Portfolio website.
- **Object-oriented design** — Classes, attributes, methods, and responsibilities.
- **Software architecture** — Component organization and separation of responsibilities.
- **UML** — Modeling the proposed structure of the system.

## 📌 Project Status

This repository presents a software design concept and its UML architecture. The website is a static portfolio showcase, not a deployed animal rescue application.

The class diagram documents the proposed system structure. Live volunteer matching, database integration, authentication, and operational SMS notifications are not claimed to be implemented.

## 🌱 Future Development

Potential future work could include:

- Developing a working application from the UML design.
- Implementing volunteer registration and organization accounts.
- Connecting the system to a database.
- Building and testing the volunteer-matching logic.
- Integrating a notification service for volunteer outreach.
- Testing the workflow with animal rescue organizations.

---

**Midlands Rescue Hub**  
*Technology designed to help animal rescue organizations work together.*
