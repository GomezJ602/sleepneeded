# IronCore Fitness

## Project Description

IronCore Fitness is an AI-powered fitness and nutrition application designed to provide users with personalized workout routines, macro-nutrient guidance, progress tracking, and gamified reward incentives. The system uses user profile information, daily activity logs, body measurements, caloric intake, available equipment, workout schedule preferences, and fitness goals to generate customized fitness recommendations.

The application is built around a personalized coaching experience. Users complete an initial questionnaire that collects information such as desired physique, experience level, primary fitness goal, average caloric intake, daily activity level, workout availability, equipment access, height, weight, age, and gender. Based on this information, the system uses Grok's cloud-based AI engine to generate workout routines and nutrition recommendations. As users continue logging workouts, calories, weight, and completed activities, the system updates recommendations over time.

IronCore Fitness also includes nutrition tracking features, including UPC barcode scanning through the user's phone camera. This allows users to scan packaged foods and retrieve nutrition information more easily. Users may also manually add custom food items, including food name, brand, serving size, calories, and macro-nutrient details.

The system is intended to support a secure $15/month subscription model. User health data, account data, workout records, nutrition logs, and billing-related information are protected through Supabase authentication, encryption, and database services. The system also includes performance requirements, such as fast barcode scanning and responsive app interactions, to support a smooth user experience.

## Main Features

- Personalized AI-generated workout routines
- Initial fitness questionnaire and user profile setup
- Daily workout, calorie, weight, and nutrition tracking
- Macro-nutrient recommendation support
- UPC barcode scanning for food logging
- Custom food item entry
- Gamified points and reward system
- Progress tracking and personalized updates
- Subscription-based access model
- Secure authentication and encrypted data storage

## Repository Contents

This repository contains the planning, requirements, and design materials for the IronCore Fitness system. The included files document the system's purpose, requirements, architecture, and UML/design models used to guide development.

### Requirements Documentation

`System_Requirements_IronCore_Final.docx` contains the main system requirements document. It describes the purpose of the IronCore Fitness application, input requirements, process requirements, output requirements, performance requirements, and security requirements.

### UML and Design Diagrams

The repository is intended to include UML and system design diagrams for the project. These diagrams help explain how users, external systems, and internal components interact with IronCore Fitness. Design artifacts may include class diagrams, use case diagrams, use case scenarios, system sequence charts, and the system context diagram.

### System Context Diagram

The system context diagram shows IronCore Fitness as the central system and identifies the external actors and systems that interact with it. These include the fitness app user, system administrator, Grok AI engine, Supabase, payment gateway, mobile device camera, nutrition database, and notification service.

### Source Code and Future Implementation Files

As the project develops, this repository may also contain application source code, configuration files, database scripts, API integration files, testing files, and deployment documentation. These files will support the implementation of the features described in the requirements document.

## External Systems

IronCore Fitness is designed to interact with several external services:

- Grok AI Engine for personalized workout and macro recommendations
- Supabase for authentication, encryption, and database storage
- Payment Gateway for monthly subscription processing
- Mobile Device Camera for UPC barcode scanning
- Nutrition/Food Database for food item and macro lookup
- Notification Service for reminders, alerts, and reward updates

## Purpose of the Repository

The purpose of this repository is to organize all project materials for IronCore Fitness in one place. It serves as the foundation for planning, designing, developing, testing, and documenting the application. The repository helps team members and reviewers understand what the system does, what requirements it must satisfy, and what design models support the final application.

## Project Status

This project is currently in the requirements and design phase. The system requirements document and design diagrams define the planned functionality and structure of the application before full implementation.
