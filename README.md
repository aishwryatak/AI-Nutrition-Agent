# AI-Powered Nutrition Agent

## Overview

The **AI-Powered Nutrition Agent** is designed as an intelligent nutrition-assistance system that combines **Agentic AI, Retrieval-Augmented Generation (RAG), personalization, and nutrition tracking**.

The proposed architecture uses specialized agents to handle different nutrition tasks while coordinating their work to provide personalized and context-aware guidance.

## Problem Statement

People often face difficulties with meal planning, portion control, nutritional tracking, and finding reliable information about healthy diets and disease-specific nutrition.

The project aims to provide personalized dietary insights, nutritional analysis, preventive-health guidance, and progress tracking through an intelligent Nutrition Agent.

## Key Features

- Personalized diet planning
- Nutrition information retrieval using RAG
- Food logging and nutritional feedback
- Preventive-health dietary guidance
- Multi-agent architecture
- Daily nutrition and goal tracking
- BMI, BMR and TDEE calculations
- Calorie, protein, carbohydrate and fat tracking
- Water-intake tracking
- Daily health score
- Nutrition tips
- Responsive dashboard interface

## Multi-Agent Architecture

The proposed system contains four specialized agents:

### 1. Nutrition Knowledge Agent
Retrieves relevant nutritional information from trusted knowledge sources and provides concise nutrition-related information.

### 2. Diet Recommendation Agent
Creates personalized meal recommendations using user requirements such as age, dietary preferences, health conditions, and fitness goals.

### 3. Health Advisory Agent
Provides preventive-health and disease-specific dietary guidance, such as diabetes-friendly and heart-healthy approaches.

### 4. Food Log & Feedback Agent
Processes food logs and provides nutritional analysis and feedback based on the user's recorded meals.

## RAG Pipeline

The proposed RAG workflow is:

**Trusted Nutrition Sources → Data Processing → Embeddings → Vector Database → Retrieval → Granite Model → Nutrition Response**

The RAG approach is intended to ground nutrition-related responses in reliable source information and reduce unsupported recommendations.

## Technology Stack

- IBM watsonx.ai
- IBM Granite Models
- IBM Langflow / IBM Orchestrate
- Retrieval-Augmented Generation (RAG)
- HTML
- CSS
- JavaScript
- Local browser storage for the current dashboard prototype

> **Note:** The current repository contains the supplied NutriTrack frontend prototype. IBM agent/orchestration files should be added to the `IBM-Agent/` and `RAG/` folders when the actual IBM Cloud / IBM Langflow / IBM Orchestrate project exports are available. No fabricated agent files are included.

## Current Dashboard Prototype

The supplied frontend is a NutriTrack dashboard that includes:

- Personal profile
- Goal calculation
- Food logging
- Macro tracking
- BMI calculation
- BMR calculation
- TDEE estimation
- Water intake
- Daily goals
- Daily health score
- Nutrition tips
- Dark mode

## Repository Structure

```text
AI-Nutrition-Agent/
│
├── README.md
│
├── frontend/
│   └── nutritrack.html
│
├── IBM-Agent/
│   └── (add actual IBM agent/orchestration files here)
│
├── RAG/
│   └── (add actual RAG/data files here)
│
├── documentation/
│   └── problemstatement.pdf
│
└── presentation/
    └── projectpresentation.pptx
```

## How to Run the Current Frontend

1. Open the `frontend` folder.
2. Double-click `nutritrack.html`.
3. The NutriTrack dashboard will open in a web browser.
4. Enter profile information and use the dashboard features.

## Project Goals

The overall goal is to develop a **smart, adaptive, and proactive digital nutritionist** that can support users with personalized dietary insights, nutritional feedback, and preventive-health guidance.

## Disclaimer

This project is intended for educational and demonstration purposes. Nutrition and health recommendations should not replace advice from qualified healthcare or nutrition professionals.
