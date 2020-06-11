# VTEX Recommendation GraphQL

This app exports a GraphQL schema for recommendation shelves on VTEX stores.

## Usage

To use it in your app, declare it on your manifest file:

```
"dependencies": {
  "vtex.recommendation-graphql": "0.x"
}
```

You need to have an app that implements the schema declared in this app, such as [vtex.recommendation-resolver](https://github.com/vtex-apps/recommendation-resolver).
