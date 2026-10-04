# Retro Calculator

A 1970s-style desk calculator in a single HTML file: seven-segment display, chunky keys, and a paper tape that prints every step.

**▶ Play it: https://parththakkar106.github.io/retro-calculator/**

## How it calculates

- **Left to right, no precedence.** Each operator computes immediately, so `2 + 3 × 4 = 20`.
- **Repeat equals.** Press `=` again to re-apply the last operation to the new total (`2 + 3 × 4 =` → 20, `=` → 80, `=` → 320).
- **New number, then `=`** applies the last operation to that number.
- Extras: `%`, `√`, `+/−`, `CE`, backspace.

## Keyboard

Digits and `+ - * /`, `Enter` or `=` for equals, `Esc` to clear, `Delete` for CE, `Backspace` to delete a digit.

## Run it

Open `index.html` in any browser. No build step, no dependencies.
