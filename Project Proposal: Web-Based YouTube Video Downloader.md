1. Project Planning & Management

Project Overview

This project aims to develop a web-based tool that allows users to download YouTube videos by entering a video URL. The system will fetch the best resolution and store the downloaded video inside a mounted volume within a containerized environment.

Objectives

•	Develop a user-friendly web interface for downloading YouTube videos.
•	Ensure high-quality video resolution selection.
•	Implement a secure and efficient storage mechanism inside a container.
•	Deploy the system using Docker for portability and scalability.

Scope

•	Users can input a YouTube URL and receive a downloadable file.
•	The system will fetch the highest available resolution.
•	Videos will be stored inside a mounted volume in a container.
•	The solution will be web-based and accessible via a browser.

Project Plan

Timeline (Gantt Chart)

1.	Week 1: Requirement Gathering & Literature Review
2.	Week 2: System Design & Architecture
3.	Week 3: Development & Implementation
4.	Week 4: Testing & Optimization
5.	Week 5: Deployment & Documentation

Milestones

•	Requirement Analysis Completion
•	Prototype Development
•	Backend Integration
•	System Testing
•	Final Deployment

Deliverables

•	Requirement Specification Document
•	Web Application (Frontend & Backend)
•	Testing Report
•	Deployment Guide

Resource Allocation

•	Developer(s) – System development & testing
•	UI/UX Designer – Interface design
•	Project Manager – Coordination & risk assessment
•	DevOps Engineer – Deployment & containerization

Task Assignment & Roles

•	Frontend Development: Responsible for user interface creation.
•	Backend Development: Handles video processing and storage.
•	Testing & QA: Ensures system functionality and reliability.
•	DevOps: Manages containerization and deployment.

Risk Assessment & Mitigation Plan
Risk	Likelihood	Impact	Mitigation Strategy
API Restrictions	High	High	Use proxy methods or alternative solutions
Storage Overflow	Medium	High	Implement auto-cleaning mechanisms
Legal Issues	High	High	Ensure compliance with YouTube policies
Performance Issues	Medium	Medium	Optimize video fetching and storage

KPIs (Key Performance Indicators)

•	System Response Time: < 3 seconds
•	Uptime: 99.9%
•	User Adoption Rate: > 80% retention rate
•	Download Success Rate: > 95%


2. Literature Review

Feedback & Evaluation

•	The project will be assessed based on functionality, security, and user experience.
•	Lecturer will provide periodic feedback on project progress.

Suggested Improvements

•	Introduce batch downloading.
•	Implement user authentication for personalized experiences.
•	Optimize storage with auto-deletion policies.

Final Grading Criteria

Criteria	Weight (%)
Documentation	20%
Implementation	40%
Testing	20%
Presentation	20%

3. Requirements Gathering

Stakeholder Analysis
Stakeholder	Role	Needs
Users	End-Users	Easy-to-use interface, high-quality downloads
Developers	System Builders	Clear API documentation, scalable architecture
Legal Team	Compliance	Ensure adherence to policies

User Stories & Use Cases

User Stories:

1.	As a user, I want to enter a YouTube URL and download the best quality video.
2.	As an admin, I want to manage storage and delete old videos.

Use Case Example:

Title: Download YouTube Video Actors: User, System Precondition: User has a YouTube video URL. Steps:

1.	User inputs URL
2.	System fetches video metadata
3.	System processes and stores video
4.	User downloads the video

Functional Requirements

•	Input field for video URL.
•	Automatic fetching of highest resolution.
•	Download button with storage integration.
•	Error handling for invalid URLs.

Non-Functional Requirements

•	Performance: Must process videos within 3 seconds.
•	Security: Secure data handling & prevent unauthorized access.
•	Usability: Intuitive and accessible user interface.
•	Reliability: Ensure system uptime of 99.9%.







