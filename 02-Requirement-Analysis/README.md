# Phase 2 – Requirement Analysis

## Project Title
FitBuddy – AI Fitness Plan Generator using Gemini Models

## 1. Introduction

Requirement analysis identifies the functional, non-functional, technical, and user requirements needed to develop the FitBuddy application.

FitBuddy is an AI-assisted fitness planning application that uses Gemini Models to generate structured general fitness suggestions based on information provided by the user.

---

## 2. Functional Requirements

The system should provide the following functions:

### FR01 – User Input
The application should allow users to enter relevant information such as:
- Fitness goal
- Activity level
- Workout preferences
- Available workout time
- Other optional information required by the application

### FR02 – Input Validation
The system should check that required information has been entered before generating a plan.

### FR03 – Fitness Goal Selection
The user should be able to select a general fitness goal.

### FR04 – AI Plan Generation
The application should send the relevant user information to the Gemini Model and request a structured fitness plan.

### FR05 – Display Generated Plan
The application should display the generated plan in a clear and readable format.

### FR06 – Error Handling
The system should provide an appropriate message when an invalid input, network problem, or API-related problem occurs.

### FR07 – User-Friendly Interface
The application should provide simple navigation and understandable input fields.

---

## 3. Non-Functional Requirements

### Performance
The application should provide the generated response within a reasonable time, depending on network and API response conditions.

### Usability
The interface should be simple and easy to understand.

### Reliability
The application should handle invalid input and API/network errors appropriately.

### Security
Sensitive information such as API keys must not be exposed in the public GitHub repository.

### Maintainability
The source code should be organized into understandable files and modules.

### Scalability
The application should be designed so that additional fitness-related features can be added later.

---

## 4. User Requirements

The user should be able to:

1. Open the FitBuddy application.
2. Enter the required fitness information.
3. Select a fitness goal.
4. Submit the information.
5. Request an AI-generated fitness plan.
6. View the generated result.
7. Understand the generated plan easily.

---

## 5. Software Requirements

The project may use the following software and technologies:

- Python
- Gemini API / Gemini Models
- HTML
- CSS
- JavaScript
- Visual Studio Code
- GitHub
- Web Browser
- Internet Connection

The exact technologies depend on the final implementation of the application.

---

## 6. Hardware Requirements

Recommended hardware requirements:

- Laptop or desktop computer
- Minimum 4 GB RAM
- Internet connection
- Keyboard and mouse/touchpad
- Modern web browser

---

## 7. Technology Requirements

### Generative AI
Gemini Models are used to process user information and generate structured fitness-plan content.

### Programming Language
Python or another suitable programming language may be used for application development.

### Frontend
HTML, CSS, JavaScript, or a suitable UI framework can be used to create the user interface.

### Version Control
GitHub is used to store and manage the project source code and phase-wise documentation.

---

## 8. API Requirements

The application requires access to a suitable Gemini API service for AI-generated responses.

The API key must be stored securely using environment variables or another secure configuration method.

The API key must NOT be uploaded to the public GitHub repository.

---

## 9. Input Requirements

Example inputs include:

| Input | Description |
|---|---|
| Fitness Goal | General goal selected by the user |
| Activity Level | Current activity level |
| Workout Preference | Preferred type of activity |
| Available Time | Approximate time available |
| Additional Information | Optional information used by the application |

---

## 10. Output Requirements

The system should provide a structured AI-generated response that may include:

- Suggested weekly schedule
- General workout suggestions
- Activity recommendations
- Rest and recovery suggestions
- General lifestyle suggestions
- Safety considerations

The output should be clearly formatted and easy to understand.

---

## 11. Constraints

The project has the following constraints:

- Requires an internet connection for API-based AI generation.
- Gemini API availability may affect application functionality.
- AI-generated information may require human review.
- The application is intended for general fitness planning and is not a medical diagnostic system.

---

## 12. Assumptions

The project assumes that:

- The user provides reasonably accurate information.
- The user has access to an internet connection.
- The Gemini API is available.
- The application has valid API configuration.
- Users understand that generated fitness suggestions are general information.

---

## 13. Requirement Summary

The main requirement of FitBuddy is to provide a simple interface through which users can provide fitness-related information and receive an AI-generated, structured general fitness plan using Gemini Models.

The system combines a user-friendly interface, application logic, and generative AI to demonstrate a practical use case of Gemini technology.

---

## 14. Safety Consideration

FitBuddy is designed for general informational and planning purposes. Generated content should not be considered medical advice, diagnosis, or individualized treatment. Users with health conditions, injuries, or other concerns should consult an appropriately qualified professional.
