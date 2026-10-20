# Bread Calculator — React Starter

Initial React scaffold for a planned bread-ingredient calculator.

**Current status:** the checked-in application still renders the Create React App starter screen. Recipe inputs, scaling calculations, and a calculator interface have not been implemented in this snapshot.

## Run locally

```bash
git clone https://github.com/CristianEstrada/bread_calculator.git
cd bread_calculator
npm ci
npm start
```

## Existing scripts

- `npm start`: start the development server.
- `npm test`: run the current starter test in watch mode.
- `CI=true npm test -- --watchAll=false`: run tests once.
- `npm run build`: create the production bundle in `build/`.

The starter uses React and Create React App, as defined in `package.json`. The existing test checks the starter's “Learn React” link; it does not verify recipe calculations.

## Intended next steps

1. Define recipe quantities, units, yield, and scaling rules.
2. Implement the calculator interface and validation.
3. Add tests covering the actual scaling behavior.
4. Review the build toolchain before extending the starter.

For the separate recipe API prototype, see [FoodCalc Backend](https://github.com/CristianEstrada/food-calculator_backend). The two repositories are not currently wired together.
