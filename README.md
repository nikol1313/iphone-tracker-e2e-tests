# iphone-tracker-e2e-tests

iphone-tracker-e2e/
├── pages/
│   ├── BasePage.ts
│   ├── HomePage.ts          # search box, list of tracked models
│   ├── ProductPage.ts       # current price, price history, "track" button
│   └── AlertsPage.ts        # price-drop alerts (if you have them)
├── fixtures/
│   ├── pageFixtures.ts
│   └── mockData/prices.json # fake prices for page.route()
├── tests/
│   ├── search.spec.ts
│   ├── product.spec.ts
│   └── alerts.spec.ts
├── .env.example             
├── playwright.config.ts
└── .github/workflows/playwright.yml
