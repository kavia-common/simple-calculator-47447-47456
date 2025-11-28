# Simple Calculator (Svelte)

A modern, Ocean Professional-themed calculator UI built with SvelteKit. It supports basic arithmetic, percent, continuous equals, and full keyboard shortcuts.

## Run locally

- Install dependencies: `npm install`
- Start dev server (port 3000): `npm run dev`
- Build: `npm run build`
- Preview production build: `npm run preview`

The app runs on http://localhost:3000 by default (configured in vite.config.ts).

## Features

- Operations: add, subtract, multiply, divide
- Percent: current entry becomes percent of previous when an operator is active; otherwise divides current by 100
- Decimal input with validation (no multiple decimals)
- Clear (C), Backspace (CE), Toggle sign (±)
- Immediate execution on operator press (simple calculator behavior)
- Continuous equals: pressing = repeatedly repeats the last operation
- Error handling: divide-by-zero shows "Error"; press C to reset
- Responsive layout and accessible buttons (roles, aria-labels, status live region)
- Keyboard support

## Keyboard shortcuts

- Digits: 0–9
- Decimal: . or ,
- Operators: +, -, *, /
- Percent: %
- Equals: = or Enter/Return
- Backspace: CE (delete last digit)
- Escape: C (clear)
- Toggle Sign: click ± button

## Environment

The app does not require any backend or external services. It respects VITE_* variables if present but does not depend on them.
