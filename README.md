## Tech Stack
### Frontend
 - **React.js** *for building the interface*
   - **Next.js** *for server-side rendering, routing, & tooling*
   - **Styled components** *for styling*
   - **React-Apollo** *for interfacing with Apollo Client*
 - **Apollo Client** *for data management*
   - Performing GraphQL mutations
   - Fetching GraphQL queries
   - Caching GraphQL data
   - Managing local state
   - Error and Loading UI states
   - Replaces the need for Redux + data fetching/caching libraries
### Backend
 - **GraphQL Yoga** *Express GraphQL server*
   - Implementing Query and Mutation Resolvers
   - Custom server-side logic
   - Charging credit cards
   - Sending email
   - Performing JWT authentication
   - Checking permissions
 - **Prisma** *GraphQL Database interface*
   - Provides GraphQL CRUD APIs for MySQL or Postgres database
   - Schema definition
   - Data relationships
   - Queried directly from GraphQL Yoga server
   - Self-hosted or as-a-service