# Formulas & Multipliers

## Multipliers by angle
| Angle | Multiplier | Shrink per inch of rise |
|-------|-----------|------------------------|
| 10°   | 5.76      | 0.03                   |
| 22.5° | 2.61      | 0.15                   |
| 30°   | 2.00      | 0.27                   |
| 45°   | 1.41      | 0.41                   |
| 60°   | 1.15      | 0.58                   |

## Offset
```
travel = depth / sin(angle)
spacing between bends = travel
```
Example: 4" obstruction, 30° bends → travel = 4 / 0.5 = 8".

## Saddle (3-bend)
- Center bend angle = 2 × side angle (e.g., 45°/90°/45° or 30°/60°/30°).
- For 45°/90°/45°: side mark offset = depth × 1.41; center mark at midpoint.
- For 30°/60°/30°: side mark offset = depth × 2.00.

## Rolling offset
```
true offset = sqrt(horizontal^2 + vertical^2)
travel = true offset / sin(angle)
```

## 90° stub-up with shrink
```
mark = stub_height + shrink
shrink ≈ 2 × (conduit OD)   (standard radius bender)
```
"