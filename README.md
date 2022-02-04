<p align="center">
<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/1/17/GraphQL_Logo.svg/512px-GraphQL_Logo.svg.png" width="100" alt="graphql logo"/>
<img src="https://i.imgur.com/migo24P.png" width="100" alt="moon highway logo"/>
</p>

# GraphQL Clients Workshop

Welcome! We're really glad you're here! Below you'll find all of the resources that we'll use throughout this course. If you're looking for slides, samples, links, etc., this is the place to look.

## Instructor Info

- **Eve Porcello**: [Twitter](https://twitter.com/eveporcello) | [Email](mailto:eve@moonhighway.com)
- **Alex Banks**: [Twitter](https://twitter.com/moontahoe) | [Email](mailto:alex@moonhighway.com)
- **Moon Highway Training**: [Moon Highway Website](https://www.moonhighway.com) | [Mailing List](http://bit.ly/moonhighway) | [Articles](https://www.moonhighway.com/articles)

#### Simple Requests

- curl Request

```sh
curl -X POST \
     -H "Content-Type: application/json" \
     --data '{ "query": "{allLifts{name}}" }' \
     http://snowtooth.moonhighway.com
```

- [Fetch Sample](https://codesandbox.io/s/n3jro0o4n0)
- [graphql-request](https://codesandbox.io/s/4qzq5z2vz0)
- [Snowtooth UI Start Files](https://github.com/graphqlworkshop/snowtooth-ui)

#### Apollo Link Examples

- [HTTP Link](https://codesandbox.io/s/koj24j5l07)
- [Concatenating Links](https://codesandbox.io/s/ql4jlz54yq)
- [Terminating Link: Start](https://codesandbox.io/s/objective-dawn-36rzq)
- [Terminating Link: Finish](https://codesandbox.io/s/mutable-smoke-qkvgc)
- [Apollo Client](https://codesandbox.io/s/oo3z008kzy?file=/src/index.js)

### Apollo & React

- [Snowtooth UI Start Files](https://github.com/graphqlworkshop/snowtooth-ui)
- [Snowtooth UI Finished Files](https://github.com/graphqlworkshop/snowtooth-ui/tree/complete)
- [Lab](https://slides.com/moonhighway/client-lab/)

### Caching

- [Caching, Client Side Schema](https://github.com/eveporcello/pet-library-client)

### Defer and Stream

- [Defer and Stream Slides](https://slides.com/moonhighway/defer-stream)
- [GraphQL Bleeding Edge Playground](https://github.com/n1ru4l/graphql-bleeding-edge-playground)
- [express-graphql, defer-stream branch](https://github.com/graphql/express-graphql/tree/defer-stream)
- [graphql-js, defer-stream branch](https://github.com/graphql/graphql-js/tree/defer-stream)

### Tutorials and Resources

- [Apollo Odyssey](https://odyssey.apollographql.com/)
- [How to GraphQL](https://howtographql.com)
- [GraphQL.org](https://graphql.org)
