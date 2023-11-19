# mock-wallet

In order to run the project, first fill out the variables in `src/env.js` file (This is not the most secure implementation, but will do for now):
```
const env = {
  BASE_URL: '<base_url>',
  PROVIDER_ID: '<provider_id>',
  CLIENT_API_KEY: '<client_api_key>',
  WEBHOOK_SECRET: '<webhook_secret>',
}
  
export { env };
```

Then run: 
```
yarn start
```


