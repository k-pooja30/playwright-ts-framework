# Project Name



![Tests](https://github.com/[username]/[repo]/actions/workflows/[workflow].yml/badge.svg)



One line on what this project tests, e.g. "End-to-end UI tests for the SauceDemo e-commerce site."

## Tech stack
Playwright · TypeScript · GitHub Actions

## What's covered
- Login (valid and invalid)
- Add to cart and checkout
- Negative and edge cases

## Project structure

tests/      # test specs
pages/      # page objects
fixtures/   # custom fixtures
test-data/  # input data


## Getting started

git clone [repo-url]
cd [repo]
npm install
npx playwright install
npx playwright test


## Reports
Run npx playwright show-report to open the HTML report.



![Report screenshot](docs/report.png)



## Highlights
- Page Object Model for maintainable tests
- Runs in parallel across Chromium, Firefox, and WebKit
- Automated on every push via GitHub Actions
