# Jest CI Demo

![CI](https://github.com/Jfoose89/jest-ci-demo/actions/workflows/test.yml/badge.svg)
![codecov](https://codecov.io/gh/Jfoose89/jest-ci-demo/branch/main/graph/badge.svg)

En enkel miniräknare med Jest-tester och CI via GitHub Actions.

## Scripts

- `npm test` – kör Jest-tester
- `npm run test:coverage` – kör tester med kodtäckning

## CI

- Körs på push och pull request mot `main` och `develop`
- Testar mot Node 18 och 20
- Laddar upp coverage till Codecov
