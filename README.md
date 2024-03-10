```
GraphQL Request
query{
  posts{
    title,
    content,
    author{
      id,
      name
    }
  }
}

GraphQL Response

{
	"data": {
		"posts": [
			{
				"title": "Intro To Graphql",
				"content": "Some Content",
				"author": {
					"id": "1",
					"name": "Krishna Sameer"
				}
			},
			{
				"title": "Intro to basic surgery",
				"content": "Some content",
				"author": {
					"id": "2",
					"name": "Keshav"
				}
			},
			{
				"title": "Test Post from GraphQL",
				"content": "Added From GraphiQL Interface",
				"author": {
					"id": "1",
					"name": "Krishna Sameer"
				}
			}
		]
	}
}
```