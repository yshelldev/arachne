Arachnate experiments with frontend state by prioritizing performance over TypeScript type safety.

## Design Choice
Uses plain objects and manual event dispatches instead of typed proxies, cutting overhead for faster execution. State updates stay explicit and lightweight.

## Best Scenarios
Suits vanilla JS/TS projects where runtime speed matters more than strict typing. Developers handle shapes via docs/examples, embracing direct control.

## Balance Note
Offers flexibility for perf-focused apps; add JSDoc or schemas for guidance where types would help.