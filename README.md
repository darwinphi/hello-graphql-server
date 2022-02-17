# 🍡 hello-graphql-server
A simple demo using Apollo GraphQL on Vercel

<img src="https://upload.wikimedia.org/wikipedia/commons/1/17/GraphQL_Logo.svg" width=120 /> <img src="https://logovtor.com/wp-content/uploads/2020/10/vercel-inc-logo-vector.png" height=150/> 

## Demo

```
curl --request POST \
  --header 'content-type: application/json' \
  --url 'https://hello-graphql-server.vercel.app/graphql' \
  --data '{"query":"query { hello }"}'
```
