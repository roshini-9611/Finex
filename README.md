# Finex
Finance management web app with ml models
# Before using this repository:
## Follow these steps:
1. Check if your database follows er diagram structure
(the ai commands shared are weird)
2. Create a file in path: /backend/critical.js locally. Add an object containing database details.
Use the syntax:

```
const <obj-name> = {
    host:<host-address>,
    user:<user-name>,
    password:<password>,
    database:<db-name>,
    port:<port-number>,
};
export { <obj-name> };
```

## To run:
1. Frontend react app: Go to /frontend/dbc and type 'npm start'
2. Backend server: Go to /backend and type 'node index.js'

If you have issues while running 'npm start', 
delete frontend/node_modules/ dir and run 'npm install'

## Goals:
1. Functioning Update feature   ✔️
    - Bug fixed: Date UTC conflict
2. User Interface design

Tips:
- Use cd '/dir-name' to change directories
- You can use either VS Code terminal 
(since you can use multiple terminals by clicking on plus sign) 
- OR you can use cmd prompt

Have fun guys 👍
