# alx-graphql-0x00
# Character Query by ID

This project retrieves specific character information from the GraphQL API using their ID.

## Files
- `character-id-1.graphql` → Query for character ID 1
- `character-id-1-output.json` → Output for ID 1
- `character-id-2.graphql` → Query for character ID 2
- `character-id-2-output.json` → Output for ID 2
- `character-id-3.graphql` → Query for character ID 3
- `character-id-3-output.json` → Output for ID 3
- `character-id-4.graphql` → Query for character ID 4
- `character-id-4-output.json` → Output for ID 4

## Endpoint
[https://rickandmortyapi.com/graphql](https://rickandmortyapi.com/graphql)

## Example Query
```graphql
query {
  character(id: 1) {
    id
    name
    status
    species
    type
    gender
  }
}
```

# Paginated Character List

This project retrieves paginated character lists from the Rick and Morty GraphQL API.

## Files
- `characters-page-1.graphql` → Query for page 1
- `characters-page-1-output.json` → Output for page 1
- `characters-page-2.graphql` → Query for page 2
- `characters-page-2-output.json` → Output for page 2
- `characters-page-3.graphql` → Query for page 3
- `characters-page-3-output.json` → Output for page 3
- `characters-page-4.graphql` → Query for page 4
- `characters-page-4-output.json` → Output for page 4

## Endpoint
[https://rickandmortyapi.com/graphql](https://rickandmortyapi.com/graphql)

## Example Query
```graphql
query {
  characters(page: 1) {
    results {
      id
      name
      status
      image
    }
  }
}
