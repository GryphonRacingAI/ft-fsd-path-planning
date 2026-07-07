# MPPI track demo JSON variants

Progressive SLAM-style demos for `python -m fsd_path_planning.demo`, scoped from the start grid through cone pair 16 (16 frames).

## Files

| File | Colors | Width |
|------|--------|-------|
| `mppi_track_canonical_w3m_start_16.json` | Blue=left, yellow=right (planner-correct) | 3 m |
| `mppi_track_canonical_w6m_start_16.json` | Blue=left, yellow=right | 6 m |
| `mppi_track_inverted_w6m_start_16.json` | Yellow=left, blue=right (swapped labels) | 6 m |
| `mppi_track_inverted_w3m_start_16.json` | Yellow=left, blue=right | 3 m |

## Run

```bash
python -m fsd_path_planning.demo -i fsd_path_planning/demo/mppi_track/mppi_track_inverted_w6m_start_16.json
```