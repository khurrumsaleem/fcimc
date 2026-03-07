# TODO

## High-value improvements

- [ ] Add unit tests for core Python modules (imc_source.py, imc_track.py, etc.)
- [ ] Add type hints to the Python modules
- [x] Remove or integrate main.py
- [ ] Make hardcoded values configurable (RNG seed, -j 4 parallelism, comparison tolerances)
- [ ] Add Python implementation documentation (comparable to ford.md for Fortran)

## From ford.md "Notes for extension"

- [ ] Implement the reserved `-d, --debug` flag
- [ ] Refactor global modules to derived types, coordinating across all subroutines
- [ ] Extend `imc_track` beyond 1D slab geometry assumption
- [ ] Make plot times configurable in `imc_opcon` instead of hardcoded three snapshots
