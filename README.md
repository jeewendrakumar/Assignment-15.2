# Assignment-15.2

Write a GraphQL query to fetch Books from 51 to 60.

{
  bookStore {
    books(after: "YXJyYXljb25uZWN0aW9uOjQ5", before: "YXJyYXljb25uZWN0aW9uOjYw") {
      edges {
        cursor
        node {
          id
          title
        }
      }
    }
  }
}
