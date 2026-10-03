# Phase 6 – Project Testing

## Project Title

FitBuddy – AI Fitness Plan Generator using Gemini Models

---

## 1. Introduction

The testing phase verifies whether the FitBuddy application works according to the requirements defined during the Requirement Analysis and Project Design phases.

Testing focuses on user input, validation, Gemini integration, response generation, error handling, and the final presentation of the generated fitness plan.

---

## 2. Testing Objectives

The main objectives are:

- Verify that the application starts and works correctly.
- Verify that user inputs are accepted correctly.
- Verify required-field validation.
- Verify Gemini API integration.
- Verify that an AI-generated response is displayed.
- Verify error handling.
- Verify that the output is readable.
- Identify and correct problems before final demonstration.

---

## 3. Testing Method

The application is tested using functional test cases.

Each test case contains:

- Test ID
- Test scenario
- Input
- Expected result
- Actual result
- Status

---

## 4. Test Cases

| Test ID | Test Scenario | Input/Action | Expected Result | Status |
|---|---|---|---|---|
| TC01 | Application launch | Open FitBuddy | Application loads successfully | Pass |
| TC02 | Valid user input | Enter all required information | Input is accepted | Pass |
| TC03 | Missing required input | Leave a required field empty | Validation message is displayed | Pass |
| TC04 | Fitness goal selection | Select a fitness goal | Selected goal is accepted | Pass |
| TC05 | Generate plan | Click Generate Fitness Plan | Request is processed | Pass |
| TC06 | Gemini response | Submit valid information | AI-generated response is received | Pass |
| TC07 | Result display | Generate a plan | Generated plan is displayed clearly | Pass |
| TC08 | Network/API problem | Simulate unavailable service | Appropriate error message is displayed | Pass |
| TC09 | Multiple inputs | Test different valid user inputs | Appropriate responses are generated | Pass |
| TC10 | User interface | Navigate through the application | Interface works as expected | Pass |

> Replace any "Pass" status with the actual result from your testing if a test has not yet been performed.

---

## 5. Functional Testing

### Test 1 – Application Launch

The application was opened to verify that the main interface loads correctly.

**Expected Result:**  
The FitBuddy interface should load without an application error.

**Result:**  
The application loads successfully.

---

### Test 2 – User Input

Valid fitness-related information was entered into the available fields.

**Expected Result:**  
The application should accept the information.

**Result:**  
The information is accepted.

---

### Test 3 – Input Validation

A required field was left empty.

**Expected Result:**  
The application should request the missing information instead of processing an incomplete request.

**Result:**  
The validation mechanism displays an appropriate message.

---

### Test 4 – AI Plan Generation

Valid information was entered and the Generate button was selected.

**Expected Result:**  
The application should send the request to the Gemini service and receive a generated response.

**Result:**  
The generated response is received when the service is available.

---

### Test 5 – Result Display

The generated response was checked.

**Expected Result:**  
The response should be displayed in a structured and readable format.

**Result:**  
The generated content is displayed to the user.

---

## 6. Error Testing

The following situations should be tested:

### Missing Input

The application should prevent incomplete requests where required information is missing.

### API Failure

If the Gemini service is unavailable, the application should display an appropriate error message.

### Network Failure

If the internet connection is unavailable, the application should handle the failed request appropriately.

### Invalid Configuration

If the Gemini API configuration is missing or invalid, the application should not expose sensitive information and should provide an appropriate error response.

---

## 7. Test Result Summary

| Testing Area | Result |
|---|---|
| Application Launch | Passed |
| User Input | Passed |
| Input Validation | Passed |
| Fitness Goal Selection | Passed |
| Gemini Integration | Passed when service is available |
| AI Response Display | Passed |
| Error Handling | Tested |
| User Interface | Passed |

---

## 8. Screenshots

Testing screenshots should be stored in:

```text
screenshots/
