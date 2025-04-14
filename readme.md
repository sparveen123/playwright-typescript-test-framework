# Playwrright testing framework

### pre-requisit
NodeJS

### install dependencies
```
npm install
```

### install browser
```
npx playwright install --with-deps chromium
```
for more details check official playwright document: https://playwright.dev/docs/browsers

### run command
```
npx playwright test --project=chrome (for headless run)
npx playwright test --project=chrome --headed (for headed run)
```