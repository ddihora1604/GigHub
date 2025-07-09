# GigHub - Freelancer Marketplace Platform

Prototype: https://youtu.be/cg60ysIn7EA?si=6CzJzzh4t_rupSa7

## Overview

GigHub is a comprehensive freelancer marketplace platform that connects clients with skilled professionals across various domains. The platform offers a streamlined experience for project posting, bidding, contract management, payment processing, and secure communication.

## Key Features

### Core Features
- **Dual Interface**: Separate, role-specific dashboards for clients and freelancers
- **Project Management**: End-to-end project lifecycle management
- **Secure Messaging**: Built-in communication with AI monitoring
- **Payment Processing**: Secure, milestone-based payment handling
- **Responsive Design**: Optimized for all devices

### For Clients
- **Project Posting**: Intuitive interface for new projects
- **Freelancer Discovery**: AI-powered professional matching
- **Milestone Approval**: Streamlined work review process
- **Secure Payments**: Escrow-based payment protection

### For Freelancers
- **Project Discovery**: Find relevant opportunities
- **Bid Management**: Submit and track proposals
- **Earnings Dashboard**: Monitor income and payments
- **Portfolio Showcase**: Highlight your best work

## Technology Stack

### Frontend
- **Languages**: HTML5, CSS3, JavaScript (ES6+)
- **Frameworks**: Tailwind CSS
- **Icons**: Font Awesome
- **Design**: Responsive, mobile-first approach

## Getting Started

### Prerequisites
- Modern web browser (Chrome, Firefox, Safari, or Edge)
- Optional: Local web server for development

### Quick Start
1. Clone the repository:
   ```bash
   git clone https://github.com/ddihora1604/GigHub.git
   cd GigHub
   ```

2. Open `login.html` in your browser to begin

### Local Development
For a better development experience, use a local server:
```bash
# Python 3
python -m http.server 8000

# Or with Node.js
npx http-server
```
Then visit `http://localhost:8000` in your browser.

## Project Structure

```
GigHub/
├── client/                     # Client-specific pages
│   ├── client-dashboard.html      # Dashboard overview
│   ├── client-messages.html       # Messaging interface
│   ├── client-pay.html           # Payment management
│   ├── client-profile.html       # Profile settings
│   ├── client-project-details.html # Project details
│   └── client-projects.html      # Projects listing
│
├── freelancer/                  # Freelancer-specific pages
│   ├── freelancer-dashboard.html  # Dashboard overview
│   ├── freelancer-messages.html   # Messaging interface
│   ├── freelancer-pay.html       # Earnings management
│   ├── freelancer-profile.html   # Professional profile
│   ├── freelancer-project-details.html # Project details
│   └── freelancer-projects.html  # Projects listing
│
├── shared/                      # Shared pages
│   ├── login.html               # Authentication
│   ├── post-project.html        # Project creation
│   └── project-search.html      # Project discovery
│
└── assets/                      # Static assets
    ├── css/
    │   └── style.css           # Global styles
    └── img/                    # Image assets
```

## Project Lifecycle

1. **Project Creation**
   - Client posts project with requirements
   - Sets budget and timeline

2. **Discovery & Bidding**
   - Freelancers discover and bid on projects
   - Client reviews proposals

3. **Project Execution**
   - Work begins after contract approval
   - Milestone-based progress tracking

4. **Completion**
   - Work submission and review
   - Secure payment release
   - Rating and feedback

## Responsive Design
GigHub is fully responsive and works seamlessly on:
- Desktop computers
- Laptops
- Tablets
- Mobile devices

## User Roles

### Client

Clients are businesses or individuals looking to hire freelancers for their projects. They can:
- Post new projects with detailed requirements
- Review freelancer applications and portfolios
- Manage active projects and approve milestones
- Process payments and provide reviews

### Freelancer

Freelancers are professionals offering their services. They can:
- Discover and apply to relevant projects
- Submit work and track progress through milestones
- Manage earnings and request withdrawals
- Build a portfolio and reputation through completed projects

## Navigation

### Common Navigation Elements

- **Top Navigation Bar**: Contains the GigHub logo, user name, and notifications
- **Sidebar**: Primary navigation menu with role-specific options
- **Breadcrumbs**: Available on detail pages for easy backward navigation

### Client Navigation

- **Dashboard**: Overview of active projects, recommendations, and stats
- **My Projects**: List and manage all client projects
- **Post New Project**: Form to create and publish new project listings
- **Messages**: Communication center for all project-related conversations
- **Profile**: Personal and business information management
- **Payments**: Payment history, methods, and processing

### Freelancer Navigation

- **Dashboard**: Overview of active projects, earnings, and stats
- **Find Projects**: Search and discover new project opportunities
- **My Projects**: Manage current and past freelancer projects
- **Messages**: Communication with clients
- **Profile**: Professional profile and portfolio management
- **Payments**: Earnings tracking, history, and withdrawal requests

## Pages Overview

### Authentication

- **Login Page**: Entry point with role selection (client/freelancer)

### Client Pages

- **Client Dashboard**: Key metrics, project snapshots, and freelancer recommendations
- **Client Projects**: List view of all projects with filtering options
- **Project Details**: Comprehensive view of a specific project with tabs for:
  - Contract details
  - Project overview
  - Freelancer information
  - Files and deliverables
  - Milestones and tasks
- **Post Project**: Multi-step form for creating new projects
- **Client Messages**: Chat interface for communicating with freelancers
- **Client Profile**: Personal/business information management
- **Client Payments**: Payment processing, history, and method management

### Freelancer Pages

- **Freelancer Dashboard**: Earnings metrics, active projects, and recommended opportunities
- **Project Search**: Discovery tool for finding new projects
- **Freelancer Projects**: Management view of current and past projects
- **Project Details**: Detailed view of a specific project with:
  - Project overview
  - Milestone tracking
  - File management
  - Communication options
- **Freelancer Messages**: Communication center for client interactions
- **Freelancer Profile**: Professional profile management with portfolio
- **Freelancer Payments**: Earnings tracking, history, and withdrawal requests

The platform features a comprehensive contract approval system:

1. Client receives contract proposal from freelancer
2. Client reviews contract details, including:
   - Project scope and deliverables
   - Milestone breakdown and payment schedule
   - Timeline and deadlines
3. Client can preview the project mockup with key features
4. Client approves the contract or requests revisions
5. Upon approval, the project status is updated and work can begin

### Payment System

GigHub uses a milestone-based payment system:

1. Client deposits funds into escrow at project start
2. Funds are released upon milestone completion approval
3. Freelancers can track earnings and request withdrawals
4. Payment history is maintained for financial record-keeping

## Future Enhancements

Planned features for future releases:

- **Time Tracking**: Built-in time tracking for hourly projects
- **Mobile App**: Native applications for iOS and Android
- **Advanced Analytics**: Detailed performance metrics for users
- **Team Collaboration**: Support for team-based project execution
- **API Integration**: Connections with popular project management tools
- **Subscription Plans**: Premium features for power users
- **Dispute Resolution**: Enhanced system for handling conflicts

## Usage Instructions

### For Clients

1. **Register/Login**: Create an account or log in as a client
2. **Post a Project**: Create a detailed project description with requirements
3. **Review Applicants**: Evaluate freelancers who apply to your project
4. **Manage Projects**: Track progress, approve milestones, and communicate with freelancers
5. **Process Payments**: Release funds upon satisfactory completion of milestones

### For Freelancers

1. **Register/Login**: Create an account or log in as a freelancer
2. **Complete Profile**: Add skills, portfolio, and set your rates
3. **Find Projects**: Search for relevant projects matching your skills
4. **Submit Proposals**: Apply to projects with personalized proposals
5. **Deliver Work**: Complete milestones and submit for client approval
6. **Receive Payments**: Track earnings and withdraw funds 