# NexusAI – Startup–Investor Matching Platform

NexusAI is a web-based platform designed to connect startup founders with potential investors. It combines startup growth assessment with investor compatibility ranking and provides an interface for investors to explore and evaluate startup profiles.

The project demonstrates how software engineering principles can be applied to develop an integrated startup–investor discovery platform.

## Features

### Startup Founder Dashboard
- Enter startup information, including sector, funding stage, location, funding requirements, revenue, growth rate and team size.
- Generate an indicative startup growth score.
- View a High or Low growth assessment.
- Receive six ranked investor recommendations.
- Open investor detail panels to explore investment preferences and matching factors.

### Investor Dashboard
- Explore 1,500 generated startup profiles.
- Browse recommended startups.
- Filter startups by sector, stage and location.
- Sort startups by match score, growth score and growth rate.
- Navigate through paginated startup listings.
- Open detailed startup profiles to view financial and operational information.

### Additional Features
- Interactive startup and investor detail drawers.
- Sector-specific fictional startup names.
- Dark and light theme support.
- Responsive web interface.

## Technology Stack

| Category | Technologies |
|---|---|
| Frontend | Next.js 16, React 19 |
| Programming Language | TypeScript |
| Styling | Tailwind CSS v4 |
| UI Components | shadcn/ui, Radix UI |
| Backend | Next.js API Routes |
| Data Handling | In-memory synthetic datasets |
| Deployment | Vercel |

## Scoring Mechanism

NexusAI currently uses rule-based scoring mechanisms rather than a trained machine-learning model.

- **Growth Assessment:** Uses submitted startup information to calculate an indicative growth score and classify the result as High or Low.
- **Investor Matching:** Ranks investors using sector alignment, funding-stage alignment and a growth-related bonus.

The displayed scores are illustrative and should not be interpreted as validated predictions or investment advice.

## Dataset

The investor dashboard uses a generated dataset containing:

- 1,500 synthetic startup profiles.
- 10 predefined investor profiles.
- Fictional company names and illustrative business information.

The current prototype maintains its data in memory and does not use a persistent database.

## Getting Started

### Prerequisites

- Node.js
- npm
- Git

### Installation

Clone the repository:

```bash
git clone https://github.com/zaidhussain2024-alt/web_programming_project.git
```

Navigate to the project directory:

```bash
cd web_programming_project
```

Install dependencies:

```bash
npm install
```

Start the development server:

```bash
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) in your browser.

### Production Build

```bash
npm run build
npm run start
```

## API Routes

| Endpoint | Description |
|---|---|
| `/api/predict` | Processes startup growth assessment requests. |
| `/api/match` | Generates investor compatibility rankings. |
| `/api/startups` | Retrieves startup records for investor-side browsing. |

## Project Links

- **GitHub Repository:** https://github.com/zaidhussain2024-alt/NexusAI-Software-Engineering
- **Live Application:** https://software-zaid-1236-project-alpha.vercel.app

## Project Information

**Project:** NexusAI – Startup–Investor Matching Platform

**Course:** Software Engineering (BCSE301L)

**Institution:** Vellore Institute of Technology, Chennai

**Developed by:**
- Zaid Hussain


---

*This project is an academic software prototype developed for educational and demonstration purposes. It uses synthetic data and illustrative rule-based scoring.*
