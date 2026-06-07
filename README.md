# TDEE Calculator

A target-weight TDEE calculator.

Enter target weight, height, age, sex, and activity level to estimate daily maintenance calories, BMR, activity add-on, and simple fat-loss targets.

## Why

Maintenance calories are easier to reason about when the first answer is plain:

> what would this target weight probably burn in a day?

This tool is for quick planning, macro math, and sanity-checking calorie targets without opening a full tracker.

## Features

- Target weight input with lb / kg toggle
- Height input with inches / feet plus inches toggle
- Age, sex, and activity-level controls
- Estimated TDEE and BMR readouts
- BMR baseline, activity add-on, daily maintenance, moderate fat-loss, and fast fat-loss rows
- Copyable calorie math
- Single HTML file, no build step

## Formula

This mirrors the linked reference calculator's Harris-Benedict-style imperial equations:

- Male BMR: `66 + (6.23 * weight_lb) + (12.7 * height_in) - (6.8 * age)`
- Female BMR: `655 + (4.35 * weight_lb) + (4.7 * height_in) - (4.7 * age)`

TDEE is `BMR * activity multiplier`.

Fat-loss rows are simple daily deficits:

- Moderate fat loss: `TDEE - 250`
- Fast fat loss: `TDEE - 500`

## Notes

This is an estimate, not medical advice. Real maintenance can vary with body composition, hormones, medications, sleep, training load, adaptive metabolism, and tracking accuracy.
