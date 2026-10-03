# Phase 3 – Project Design

## Project Title

FitBuddy – AI Fitness Plan Generator using Gemini Models

---

## 1. Introduction

The Project Design phase describes the overall architecture, workflow, modules, inputs, processing, and outputs of the FitBuddy application.

FitBuddy accepts fitness-related information from the user, processes the information through the application, sends an appropriate prompt to the Gemini Model, and displays the generated general fitness plan to the user.

---

## 2. System Architecture

The overall system architecture consists of the following components:

```text
+----------------------+
|        User          |
+----------+-----------+
           |
           v
+----------------------+
|  FitBuddy Interface  |
+----------+-----------+
           |
           v
+----------------------+
|   User Input Data    |
+----------+-----------+
           |
           v
+----------------------+
| Application Logic    |
+----------+-----------+
           |
           v
+----------------------+
|    Prompt Builder    |
+----------+-----------+
           |
           v
+----------------------+
|      Gemini API      |
+----------+-----------+
           |
           v
+----------------------+
|  AI Generated Plan   |
+----------+-----------+
           |
           v
+----------------------+
|   Result Display     |
+----------+-----------+
           |
           v
+----------------------+
|        User          |
+----------------------+
