Spring Security Application

This is a simple Spring Boot application demonstrating basic security configurations using Spring Security. The project restricts access to specific endpoints, allowing public access to some while securing others that require authentication.

📋 Project Overview

This project implements:

Role-based access control for secure endpoint handling.
Basic form login and HTTP Basic authentication.
A simple REST API with restricted and unrestricted access points.

🚀 Features

Public Endpoints: Open to everyone (no authentication required)
/contact - Displays contact information.
/updates - Provides the latest updates.
Protected Endpoints: Requires user authentication
/check - Returns balance details.
/transfer - Processes a fund transfer.
🛠️ Technology Stack

Java
Spring Boot
Spring Security

🔒 Security Configuration

The SecurityFilterChain in WebConfig.java defines the security settings.
/contact and /updates are publicly accessible.
/check and /transfer require user authentication.
Configures form-based login and HTTP Basic authentication for secure access.
