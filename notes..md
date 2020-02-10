1. add apollo on Index.js
   npm i graphql react-router-dom apollo-boot react-apollo

const client = new ApolloClient({
uri: "localhost:4000/graphql"
});

2. add
   import { BrowserRouter as Router } from "react-router-dom";
