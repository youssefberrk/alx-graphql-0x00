# GraphQL Rick and Morty API Explorer

## Description
This project explores GraphQL implementation using the Rick and Morty API. It includes a series of tasks focused on writing GraphQL queries and building a React application to display character and episode information from the Rick and Morty universe.

## Project Structure
The project is divided into multiple parts:

### Part 1: Basic GraphQL Queries (alx-graphql-0x00)
- Writing queries to fetch specific character information by ID
- Retrieving paginated lists of characters
- Fetching episode details

### Part 2: React Implementation (alx-graphql-0x01)
- Setting up a Next.js project with TypeScript
- Implementing Apollo Client
- Creating basic GraphQL queries

### Part 3: Advanced Implementation (alx-graphql-0x02)
- Building a complete Rick and Morty episode explorer
- Implementing pagination
- Creating reusable components

## Tasks Overview

### Task 0: Character Query by ID
- Write GraphQL queries to fetch character details using specific IDs
- Required fields: id, name, status, species, type, gender
- Implementation for characters with IDs 1-4

### Task 1: Characters List Query
- Create queries to fetch paginated lists of characters
- Implementation for pages 1-4
- Fields include: id, name, status, and image

### Task 2: Episode Query
- Fetch episode details using GraphQL
- Required fields: id, name, air_date, episode

### Task 3: React Application Setup
- Initialize Next.js project with TypeScript
- Install and configure Apollo Client
- Set up GraphQL queries structure

### Task 4: Episode Explorer Implementation
- Create interfaces for TypeScript
- Implement episode listing with pagination
- Build reusable components

## Technologies Used
- GraphQL
- React/Next.js
- TypeScript
- Apollo Client
- Tailwind CSS
- ESLint

## Setup Instructions

1. Clone the repository:
```bash
git clone https://github.com/youssefberrk/alx-graphql-0x00.git
```

2. Install dependencies:
```bash
cd alx-rick-and-morty-app
npm install
```

3. Run the development server:
```bash
npm run dev
```

4. Access the application at `http://localhost:3000`

## File Structure
```
alx-graphql-0x00/
├── character/
│   ├── character-id-1.graphql
│   ├── character-id-1-output.json
│   └── [other character files]
└── episode/
    ├── episode-page-1.graphql
    └── [other episode files]

alx-graphql-0x01/
└── alx-rick-and-morty-app/
    ├── graphql/
    │   ├── apolloClient.ts
    │   └── queries.ts
    └── pages/
        └── _app.tsx

alx-graphql-0x02/
└── alx-rick-and-morty-app/
    ├── components/
    │   └── common/
    │       └── EpisodeCard.tsx
    ├── interfaces/
    │   └── index.ts
    └── pages/
        └── index.tsx
```

## API Reference
This project uses the Rick and Morty GraphQL API: `https://rickandmortyapi.com/graphql`

## Contributors
- Youssef Berrakouan

## License
This project is part of the ALX Software Engineering program.

## Acknowledgments
- Rick and Morty API
- ALX Software Engineering Program