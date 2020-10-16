1. Installed a cli tool built for creating react apps (https://create-react-app.dev/)

```
npm install -g create-react-app
```

2. Create the react app

```
create-react-app --use-npm example-project
```

3. Install Cypress (https://docs.cypress.io/)

```
cd example-project
npm install cypress --save-dev
```

4. Manually add this to the package.json file under "scripts"

```
"cypress": "cypress open"
```

5. Run Cypress and the first time it runs it will configure itself.

```
npm run cypress
```
