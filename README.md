# Natural System Models

Synthetic sedimentary models of natural depositional systems, in SedArch `.vvm`
format, for review and validation. Each file holds the time-stepped evolution of
a basin: the top surface, sea level and sediment fractions at every time step.

## Models

| File | System | Grid (nodes) | Cell size | Time steps | Time span |
|------|--------|--------------|-----------|------------|-----------|
| `delta_synthetic.vvm`                | Delta, sea level −25 m        | 61 × 41  | 50 m    | 101  | 2 ka |
| `delta_synthetic_sealevel0.vvm`      | Delta, sea level 0 m          | 61 × 41  | 50 m    | 101  | 2 ka |
| `delta_synthetic_standard2ka.vvm`    | Delta, standard 2 ka run      | 61 × 41  | 50 m    | 101  | 2 ka |
| `carbonate_synthetic.vvm`            | Carbonate platform            | 61 × 41  | 100 m   | 101  | 2 ka |
| `carbonate_large_area_synthetic.vvm` | Carbonate platform, large area | 241 × 121 | 4000 m | 101  | 2 ka |
| `carbonate_large_area_corrected.vvm` | Carbonate platform, large area, corrected | 241 × 121 | 4000 m | 101 | 2 ka |
| `bengal_fan_synthetic.vvm`           | Submarine fan (Bengal Fan)    | 61 × 41  | 100 m   | 101  | 2 ka |
| `mississippi_delta_1ma_1kyr.vvm`     | Mississippi Delta, last 1 Ma  | 61 × 41  | 2000 m  | 1001 | 1 Ma (1 kyr steps) |

All models use four sediment classes (diameters 20, 10, 5 and 1).

Two large-area models, `bengal_fan_large_area_synthetic.vvm` and
`large_area_Missisipi_1Ma.vvm`, are over GitHub's 100 MB file limit and are not
included in this repository.

## Viewing

The models can be opened in [SAView](https://github.com/pdhoteg/SAView_v1) and
processed with [SedCompanion](https://github.com/pdhoteg/sedCompanion_v1).

## License

GNU General Public License v3.0 — see [LICENSE](LICENSE).
