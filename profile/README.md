# Sprint

Sprint is a powerful desktop application built using Electron and React, designed to enhance the onboarding process for software teams. It operates locally on your machine, seamlessly connecting to a FastAPI API hosted on Google Cloud Platform (GCP). Furthermore, Sprint leverages MongoDB as its robust database system. It offers two main features that are aimed at enhancing the onboarding experience for both managers and team members:

## Technology Stack Recommendation Engine
Sprint has implemented a cutting-edge technology stack recommendation engine that leverages state-of-the-art natural language processing techniques. This engine is powered by a fine-tuned BERT transformer model, which is capable of understanding project descriptions with remarkable accuracy. By analyzing project descriptions, it provides intelligent and context-aware technology stack suggestions.

Additionally, Sprint enhances its technology stack recommendations using K-means clustering in the popular scikit-learn library. This clustering process helps group similar project descriptions and refines the technology suggestions even further, ensuring that teams receive tailored recommendations that align with their specific project needs.

## Docker-Based Package Manager
Sprint has also developed and deployed a Docker-based package manager, integrated seamlessly with SSH and Ansible. This package manager automates the installation of remote technology stacks, significantly reducing the manual effort required for setting up development environments. It simplifies the process by allowing managers to initiate the installation remotely, ensuring that team members have the required tools and dependencies readily available.

## Process for Installation Technologies
To make the most of Sprint's capabilities, follow these steps:

1. **Manager Creates a Team:**
   - The manager initiates the onboarding process by creating a team within Sprint.

2. **Manager Installs Technology Stacks:**
   - Using Sprint's intuitive interface, the manager selects and installs the necessary technology stacks for the team. The recommendation engine can assist in this process by suggesting the most suitable stacks based on project descriptions.

3. **Team Member Participation:**
   - Team members receive notifications about the installed technology stacks and are prompted to complete any necessary setup steps on their end. Sprint provides clear instructions and guidance to ensure a smooth installation process.

4. **Team Member Installations:**
   - Team members follow the provided instructions to install the required technologies on their local development environments, ensuring they have everything they need to contribute effectively to the project.

5. **Manager Oversight:**
   - The manager can monitor the progress of technology stack installations for team members, ensuring that everyone is set up and ready to work efficiently.

## Demo
Explore Sprint's functionality through these informative demo videos:

### Video of Manager Creating a Team and Inviting Member
[Watch Here](https://github.com/TheSprintTeam/.github/assets/90528127/54a43953-5123-4968-9daf-46d7f151d30f)

### Video of Team Member Joining the Team
[Watch Here](https://github.com/TheSprintTeam/.github/assets/90528127/1c70a733-88bc-49dc-8e0d-590a6e679533)

### Video of Installation Prompt on Team Member
[Watch Here](https://github.com/TheSprintTeam/.github/assets/72236623/c3e0d802-c897-4c08-80c5-09ef4a3463bb)

### Video of Manager View for Team Member Installations
[Watch Here](https://github.com/TheSprintTeam/.github/assets/90528127/a50544d8-e50f-4bfc-a1e2-80a2b32771ea)

Sprint revolutionizes the onboarding process for software teams, making it more efficient and user-friendly. With its technology stack recommendation engine and Docker-based package manager, it empowers teams to focus on what matters most: delivering exceptional software solutions.
