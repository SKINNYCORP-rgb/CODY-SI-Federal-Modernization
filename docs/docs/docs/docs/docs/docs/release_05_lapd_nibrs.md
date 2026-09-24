# 🚨 RELEASE 05 — MUNICIPAL NIBRS MODERNIZATION
**Core Engine Lane:** Los Angeles Police Department (LAPD) Crime Registry

## 📊 Legacy Metadata (Unmodernized Staging)
* Legacy RMS data logged under old Uniform Crime Reporting (UCR) parameters containing broken geospatial points `(0°, 0°)` and nearest-hundred-block strings.

## 🧠 Modernized Schema Index (`snake_case` Standard)
* `si_lapd_legacy_core` — `lapd_crime_historical_data`
* `si_nibrs_offenses` — `lapd_nibrs_offenses_dataset`
* `si_nibrs_victims` — `lapd_nibrs_victims_dataset`
