# Material Definition

## Simplified Compositions

| Material | Density (g/cc) | Composition     | Atomic Mass (u)    |
|----------|----------------|-----------------|--------------------|
| UZrH     | 7.2            | U-235           | 235.04393013100002 |
| SS304    | 8.0            | Fe-56           | 55.934936326       |
| Zr       | 6.5            | Zr-92           | 91.905034675       |
| Water    | 1.0            | H-1  (67 at.%)  | 18.01056468403     |
|          |                | O-16  (33 at.%) |                    |
| Graphite | 1.7            | C (elemental)   | 12.01073589673525  |
| B4C      | 2.52           | B-11            | 11.009305355       |
| Boral    | 2.53           | B-11 (50 at.%)  | 37.990843886       |
|          |                | Al-27 (50 at.%) |                    |
| Aluminum | 2.7            | Al-27           | 26.981538530999998 |


## Derived Material Input Data

| Material | Material Number  | Isotopes | Mass Fraction (wt.%) | Atom Density (/barn-cm) |
|----------|------------------|----------|----------------------|-------------------------|
| UZrH     | 1190A0B*         | 92235    | 100                  | 1.8447368020026703e-02  |
| SS304    | 1190A99*, 50002  | 26056    | 100                  | 8.61306638827906e-02    |
| Zr       | 20000            | 40092    | 100                  | 4.343444808841109e-02   |
| Water    | 30000            | 1001     | 11.191487328808077   | 6.687343351693846e-02   |
|          |                  | 8016     | 88.80851267119192    | 3.343671675846923e-02   |
| Graphite | 30001            | 6000     | 100                  | 8.523741291141694e-02   |
| B4C      | 40001            | 5011     | 100                  | 1.3784517815293171e-01  |
| Boral    | 40002            | 5011     | 28.978838659219774   | 4.010444737873965e-02   |
|          |                  | 13027    | 71.02116134078023    | 4.010444737873965e-02   |
| Aluminum | 50001            | 13027    | 100                  | 6.02626200552596e-02    |

\* A: 1 ~ 7, B: 0 ~ 2

## Temperature

All materials are defined at a temperature of 293.6 K.

## Nuclear Data

Use ENDF/B-VII.0 library as it is the most up-to-date library available for Serpent.
