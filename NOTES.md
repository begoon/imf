# Cross-check: this calculator vs. the official IMF calculator

Comparison of this calculator against the official companion calculator
on bodyrecomposition.com (available to book buyers) and against the book
*Intermittent Modified Fasting* (Lyle McDonald, 2026).

Method: identical inputs were run through both calculators in a browser
(four full profiles plus boundary and multiplier probes), and the disputed
values were checked against the book's charts. Performed 2026-08-14.

## Values that agree in both calculators and the book

- Protein targets (category × training type × LBM), identical to the gram
  in all tested cases
- BMR by category: 10 / 9 / 8 cal/lb for Category 1 / 2 / 3
- All six exercise multipliers (per hour): low aerobic 0.2, medium
  aerobic 0.3, high aerobic 0.4, HIIT 0.3, moderate weight training 0.1,
  high-intensity weight training 0.2, scaled by minutes/60
- TDEE formula: bodyweight × BMR × (activity multiplier + exercise
  multiplier)
- EPA/DHA dose: 1.8 g below 175 lb, 3 g at or above

## Differences

### Daily activity multipliers

| Level | Book chart | This calculator | Official calculator |
| --- | --- | --- | --- |
| Inactive | 1.1 (≤5,000 steps) | 1.1 (<5k steps) | 1.2 (<5,000 steps) |
| Light | 1.2 (5,000–10,000) | 1.2 (5–10k) | 1.3 (10,000–15,000) |
| Moderate | 1.3 (10,000–20,000) | 1.3 (10–20k) | 1.4 (15,000–20,000) |
| High | 1.5 (20,000+) | 1.5 (20k+) | 1.6 (20,000+) |

The book's worked example ("Joe is 200 lbs and 22% Bodyfat/Category 2,
Moderate Activity Level = 1.3 multiplier") uses the chart values.
Observed effect: for a 200 lb Category 2 input, maintenance calories are
2,700 here vs. 2,880 on the official calculator.

### Vegetable amount on RFL days

- Book: "a maximum of 3-4 cups (225-325 g) steamed vegetables per day"
- This calculator: 3–4 cups (225–325 g)
- Official calculator: 3–4 cups (120–180 grams)

### Category boundaries

Book chart ("Older Methods" column): men Category 1 = "15% or lower",
Category 2 = 16–25%, Category 3 = 26%+; women Category 1 = "24% or
lower", Category 2 = 25–34%, Category 3 = 35%+.

- At exactly 15.0% (men) / 24.0% (women): this calculator assigns
  Category 1; the official calculator assigns Category 2.
- Fractional values between boundaries: the official calculator truncates
  BF% to an integer, so a man at 25.1–25.9% is Category 2 there and
  becomes Category 3 at 26.0%. This calculator switches to Category 3
  above 25.0%. The book chart is stated in whole percentages and does not
  specify fractional handling.
- The book additionally recommends that people on the cusp choose the
  leaner category ("a man at 26% bodyfat would put themselves in
  Category 2"). Neither calculator implements this rule.

### Features present in only one calculator

- DEXA correction for BF%: present here (bounds derived from the book's
  DEXA ranges); not offered by the official calculator.
- "Up to 25% of total protein intake can come from protein powder" note
  on RFL days: shown by the official calculator; not shown here.

## Note

The book's second worked TDEE example ("Sue: One hour weight training =
0.3") does not match the book's own exercise multiplier chart (weight
training 0.1–0.2). Both calculators follow the chart.
