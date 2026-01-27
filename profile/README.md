# SnakeAid
[![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://python.org) [![YOLO](https://img.shields.io/badge/YOLO-v12-blue.svg?style=for-the-badge)](https://github.com/ultralytics) [![Flutter](https://img.shields.io/badge/Flutter-02569B?style=for-the-badge&logo=flutter&logoColor=white)](https://flutter.dev) [![.NET](https://img.shields.io/badge/.NET-512BD4?style=for-the-badge&logo=dotnet&logoColor=white)](https://dotnet.microsoft.com/) [![Next JS](https://img.shields.io/badge/Next-black?style=for-the-badge&logo=next.js&logoColor=white)](https://nextjs.org/) [![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)](https://www.docker.com/)

**AI-Powered Platform for Snakebite First Aid and Rescue Support**
*Nền tảng hỗ trợ sơ cứu & cứu hộ rắn cắn ứng dụng AI*

<br />

## About The Project

SnakeAid revolutionizes the response to snakebite incidents by connecting patients, rescuers, experts, and administrators in a unified ecosystem. Our mission is to minimize fatalities through timely first aid guidance, accurate AI-driven identification, and rapid rescue coordination.

### What It Does
The platform integrates **Computer Vision**, **Real-time Geolocation**, and **Expert Consultation** to:
1.  **Identify** snake species instantly from images to determine venom risks.
2.  **Guide** patients with correct first-aid procedures and prohibited actions.
3.  **Coordinate** rescue teams and connect patients to the nearest antivenom facilities.
4.  **Digitize** the workflow for snake experts and administrators to manage data and insights.

### Key Capabilities
*   **Patient Assistance**: Instant emergency support with AI-powered snake identification. Patients receive step-by-step first aid instructions while the system automatically broadcasts SOS signals with GPS coordinates to nearby rescuers.
*   **Rescue Coordination**: Dedicated tools for rescue teams to receive real-time alerts, navigate to incident locations, and manage transport logistics.
*   **Expert Consultation**: A platform for herpetologists and medical experts to verify species, provide remote treatment consultation, and update the central knowledge base.
*   **Administrative Control**: Comprehensive dashboard for managing users, monitoring system-wide analytics, and issuing community safety alerts for high-risk areas.

## The Ecosystem

Our platform is engineered as a distributed system of specialized components.

| Module | Purpose | Core Technology |
| :--- | :--- | :--- |
| **[SnakeAid.Docs](https://github.com/Snake-AID/SnakeAid.Docs)** | Architecture, Functional Specs, Research | Docsify, Markdown |
| **[SnakeAI.ComputerVision](https://github.com/Snake-AID/SnakeAI.ComputerVision)** | Model Training Pipeline & Experiments | Roboflow, ClearML |
| **[SnakeAI.ModelEndpoint](https://github.com/Snake-AID/SnakeAI.ModelEndpoint)** | Inference Service & API | FastAPI, ONNX |
| **[SnakeAid.Backend](https://github.com/Snake-AID/SnakeAid.Backend)** | Core Business Logic & Data Layer | .NET 8, PostgreSQL |
| **[SnakeAid.Frontend](https://github.com/Snake-AID/SnakeAid.Frontend)** | Administration & Management Portal | Next.js, TailwindCSS |
| **[SnakeAid.Mobile](https://github.com/Snake-AID/SnakeAid.Mobile)** | Patient & Rescuer Applications | Flutter, Dart |


<br>

## Documentation ([SnakeAid.Docs](https://github.com/Snake-AID/SnakeAid.Docs))
![Docsify](https://img.shields.io/badge/Docsify-42b883?style=flat-square&logo=docsify&logoColor=white) ![Markdown](https://img.shields.io/badge/Markdown-000000?style=flat-square&logo=markdown&logoColor=white)

![SnakeAid Docs Banner](https://placehold.co/800x200?text=SnakeAid+Docs+Banner)

The central knowledge hub containing detailed functional specifications, system architecture, research papers, and localized documentation for all platform components.

<br>

## Computer Vision ([SnakeAI.ComputerVision](https://github.com/Snake-AID/SnakeAI.ComputerVision))
![Roboflow](https://img.shields.io/badge/Roboflow-6706CE?style=flat-square&logo=roboflow&logoColor=white) ![Ultralytics](https://img.shields.io/badge/Ultralytics_YOLO-0086FF?style=flat-square&logo=ultralytics&logoColor=white) ![Google Colab](https://img.shields.io/badge/Google_Colab-F9AB00?style=flat-square&logo=googlecolab&logoColor=white) ![Amazon SageMaker](https://img.shields.io/badge/Amazon_SageMaker-232F3E?style=flat-square&logo=amazon&logoColor=white) ![ClearML](https://img.shields.io/badge/ClearML-182335?style=flat-square&logo=clearml&logoColor=white) ![Neural Magic](https://img.shields.io/badge/Neural_Magic-162846?style=flat-square) ![Ngrok](https://img.shields.io/badge/Ngrok-1F1E38?style=flat-square&logo=ngrok&logoColor=white) ![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)

![Computer Vision Banner](https://placehold.co/800x200?text=Computer+Vision+Banner)

The complete AI training pipeline. From raw dataset management with Roboflow to model training experiments with YOLOv12 and ClearML tracking.

<br>

## AI Inference ([SnakeAI.ModelEndpoint](https://github.com/Snake-AID/SnakeAI.ModelEndpoint))
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white) ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white) ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white) ![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white) ![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white) ![Pydantic](https://img.shields.io/badge/Pydantic-E92063?style=flat-square&logo=pydantic&logoColor=white)

![Model Endpoint Banner](https://placehold.co/800x200?text=Model+Endpoint+Banner)

High-performance, containerized inference service. Serves the trained YOLO models via a robust FastAPI interface, optimized for rapid snake identification.

<br>

## Backend Services ([SnakeAid.Backend](https://github.com/Snake-AID/SnakeAid.Backend))
![.NET 8](https://img.shields.io/badge/.NET_8-512BD4?style=flat-square&logo=dotnet&logoColor=white) ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white) ![EF Core](https://img.shields.io/badge/EF_Core-512BD4?style=flat-square&logo=dotnet&logoColor=white) ![Mapster](https://img.shields.io/badge/Mapster-000000?style=flat-square&logo=nuget&logoColor=white) ![Carter](https://img.shields.io/badge/Carter-3C873A?style=flat-square&logo=nuget&logoColor=white) ![Serilog](https://img.shields.io/badge/Serilog-9A334E?style=flat-square&logo=nuget&logoColor=white) ![YARP](https://img.shields.io/badge/YARP-512BD4?style=flat-square&logo=dotnet&logoColor=white) ![Cloudinary](https://img.shields.io/badge/Cloudinary-3448C5?style=flat-square&logo=cloudinary&logoColor=white) ![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=flat-square&logo=firebase&logoColor=black) ![Swagger](https://img.shields.io/badge/Swagger-85EA2D?style=flat-square&logo=swagger&logoColor=black)

![Backend Banner](https://placehold.co/800x200?text=Backend+Banner)

The core logic engine. Manages user authentication, rescue coordination, expert consultations, and database transactions with security and scalability in mind.

<br>

## Web Portal ([SnakeAid.Frontend](https://github.com/Snake-AID/SnakeAid.Frontend))
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=next.js&logoColor=white) ![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB) ![TailwindCSS](https://img.shields.io/badge/TailwindCSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white) ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white) ![DrizzleORM](https://img.shields.io/badge/Drizzle_ORM-C5F74F?style=flat-square&logo=drizzle&logoColor=black) ![Clerk](https://img.shields.io/badge/Clerk-6C47FF?style=flat-square&logo=clerk&logoColor=white) ![Sentry](https://img.shields.io/badge/Sentry-362D59?style=flat-square&logo=sentry&logoColor=white) ![PostHog](https://img.shields.io/badge/PostHog-000000?style=flat-square&logo=posthog&logoColor=white) ![Storybook](https://img.shields.io/badge/Storybook-FF4785?style=flat-square&logo=storybook&logoColor=white) ![Vitest](https://img.shields.io/badge/Vitest-6E9F18?style=flat-square&logo=vitest&logoColor=white) ![Playwright](https://img.shields.io/badge/Playwright-45BA4B?style=flat-square&logo=playwright&logoColor=white) ![Zod](https://img.shields.io/badge/Zod-3E67B1?style=flat-square&logo=zod&logoColor=white)

![Frontend Banner](https://placehold.co/800x200?text=Frontend+Banner)

A modern, responsive administrative and user portal. Provides dashboards for system oversight, content management, and detailed analytics.

<br>

## Mobile App ([SnakeAid.Mobile](https://github.com/Snake-AID/SnakeAid.Mobile))
![Flutter](https://img.shields.io/badge/Flutter-02569B?style=flat-square&logo=flutter&logoColor=white) ![Dart](https://img.shields.io/badge/Dart-0175C2?style=flat-square&logo=dart&logoColor=white) ![Riverpod](https://img.shields.io/badge/Riverpod-2D3748?style=flat-square&logo=riverpod&logoColor=white) ![Google Maps](https://img.shields.io/badge/Google_Maps-4285F4?style=flat-square&logo=googlemaps&logoColor=white) ![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=flat-square&logo=firebase&logoColor=black) ![Dio](https://img.shields.io/badge/Dio-000000?style=flat-square&logo=network&logoColor=white) ![GoRouter](https://img.shields.io/badge/GoRouter-20232A?style=flat-square&logo=flutter&logoColor=white) ![JsonSerializable](https://img.shields.io/badge/JsonSerializable-0175C2?style=flat-square&logo=dart&logoColor=white)

![Mobile App Banner](https://placehold.co/800x200?text=Mobile+App+Banner)

The primary interface for Patients, Rescuers, and Experts. Features SOS signaling, real-time rescue tracking, and on-the-go AI identification.

<br>

<div align="center">
  <sub>SnakeAid Organization © 2026</sub>
</div>
