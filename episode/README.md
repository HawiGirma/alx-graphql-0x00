# alx-graphql-0x00
# Episode Query by ID

This task retrieves details for a specific episode using its ID from the Rick and Morty GraphQL API.

## Files
- `episode-id-1.graphql` → Query for episode ID 1
- `episode-id-1-output.json` → Output for episode ID 1

## Endpoint
[https://rickandmortyapi.com/graphql](https://rickandmortyapi.com/graphql)

## Example Query
```graphql
query {
  episode(id: 1) {
    id
    name
    air_date
    episode
  }
}
