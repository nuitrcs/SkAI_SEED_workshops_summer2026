# Day 3 (June 17)

Instructor : Aaron Geller

Contents:
- loops and conditionals
- basic error handling
- files
- defining your own functions


## Data files

- `NEOComets.csv` : information about the comets subset of the Near Earth Objects from NASA JPL downloaded from [here](https://ssd.jpl.nasa.gov/tools/sbdb_query.html).  The columns contain:
    - **full_name**: The comet's official designation
    - **class**: Orbital class — `JFc` (Jupiter-family comet), `HTC` (Halley-type comet), `ETc` (Encke-type comet), and others
    - **diameter**: Nucleus diameter in kilometers
    - **e**: Orbital eccentricity (0 = circular, closer to 1 = more elongated)
    - **a**: Semi-major axis in AU (astronomical units; 1 AU = Earth–Sun distance)
    - **i**: Orbital inclination in degrees (tilt relative to Earth's orbital plane)
    - **per_y**: Orbital period in years
    - **first_obs** / **last_obs**: Dates of first and last observation
    - **condition_code**: Orbit quality rating (0 = best-determined, 9 = most uncertain)
- `wht20250414.txt` : observing log for the [WHT telescope](https://www.ing.iac.es/astronomy/telescopes/wht/) from April 14, 2025
- `wht20250414_trim.txt` : observing log for the [WHT telescope](https://www.ing.iac.es/astronomy/telescopes/wht/) from April 15, 2025, but trimmed to only include one table

Both observing logs were downloaded from the [Isaac Newton Group of Telescopes](https://www.ing.iac.es/astronomy/observing/inglogs.php).  More information about the observing log contents can be found [here](https://www.ing.iac.es/astronomy/observing/inglogs_help.html)
