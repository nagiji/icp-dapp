
### Interface
```
answer: (nat, text) -> (Bool);
ask: (text) -> (Bool);
upvote: (text, text) -> (Bool);
balanceOf: (principal) -> (Int) query;
queryAllQuestions: () -> (vec text) query;
```

## :package: Installation (development)

```bash
npm i
# Start the replica, running in the background
dfx start --background
# Deploy canisters to the replica
dfx deploy
# Start the development server
npm start
```

## :cloud: Deployment

```
dfx deploy --network ic
```

