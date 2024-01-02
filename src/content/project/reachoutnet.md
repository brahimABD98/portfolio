---
title: "ReachOutNet"
description: "A Web Application Advancing United Nation SDG 17"
pubDate: "31 Jun 2023"
tags: ['React', 'GraphQL', 'Apollo', 'tailwindcss']
---

## Overview:
As part of our annual project, our team of five is dedicated to creating a web application aligned with the United Nations Sustainable Development Goal (SDG) 17, known as "Partnerships for the Goals." The result of our efforts is ReachOutNet, a platform designed to connect volunteers with individuals interested in getting involved with local organizations. Leveraging React on the frontend and Apollo Server on the backend, our goal is to foster collaboration and community engagement.
<div class="flex flex-col items-center justify-center">

![Application Architecture](/reachoutnet/architecture.png)
<p>
Application Architecture
<p>
</div>

### Special Requirement
This year also marked a new requirement integrating some  AI capabilities, and we addressed this by utilizing the ChatGPT API. This integration allows us to filter user-generated content, ensuring a safe and respectful environment by preventing the sharing of prohibited content on the platform.

## My Contributions:
1. **Initial Project Setup:**
   - Established GitHub repositories and prepared initial projects for collaborative development.
   - Set up Apollo Server to connect with MongoDB, implemented ESLint & Prettier for code consistency.

2. **First Feature: Two-Factor Authentication (2FA)**
   For our initial sprint focused on user and user management, I was task with implementing 2FA:
   - Set up a GraphQL schema for OTP (one-time password) authentication.
   - Utilized the [speakeasy](https://www.npmjs.com/package/speakeasy) library for OTP generation.
   - Implemented frontend pages for security settings, activation, and validation.
   - Backoffice features for admin visibility and management of 2FA status for each user.

   *Conclusion:* Developing 2FA was a complex yet enlightening experience, with challenges on the frontend that I plan to share in a future blog post.

3. **Other Features:**
   Beyond 2FA, my contributions extended to:
   - Associations Management (CRUD)
   - password management
   - Geolocation search using Leaflet
   - Backend mailing service
   - File upload functionality
   - CI/CD workflow with GitHub Actions and Docker image building and publishing to DockerHub.

## Final Words:
Working with GraphQL using Apollo Server for the backend and Apollo Client on the frontend provided a unique and new experience. While it offered out-of-the-box features like caching and auto-documentation, refactoring posed challenges due to tight coupling of types in the schema. This project was an opportunity for me to delve into and understand the intricacies of GraphQL.

