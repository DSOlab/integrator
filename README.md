# integrator
Integrator for POD

## Installation

You will need:
 * the `datetime` library by [DSO](https://github.com/DSOlab/ggdatetime),
 * the `iers` library by [DSO](https://github.com/xanthospap/iers2010),
 * the `geodesy` library dy [DSO](https://github.com/DSOlab/ggeodesy),
 * the `sp3` library by [DSO](https://github.com/xanthospap/sp3),
 * the [yaml-cpp](https://github.com/jbeder/yaml-cpp) library for parsing `yaml` (configuration) files
 * the [cspice](https://naif.jpl.nasa.gov/naif/toolkit.html) library (if not already installed with `iers`). For instructions, see the [iers repository](https://github.com/xanthospap/iers2010)

Installation is performed via [cmake](https://cmake.org/):

```bash
cmake -S . -B build -DCMAKE_BUILD_TYPE=Release -DCMAKE_PREFIX_PATH=/usr/local/lib
cmake --build build --target all --config=Release -- -j4
cd build && sudo make install
```

## PREPARE Funding
>This study was funded under the project PREPARE (HFRI PN:15562) in the framework of H.F.R.I call “Basic research Financing (Horizontal support of all Sciences)” under the National Recovery and Resilience Plan “Greece 2.0” funded by the European Union – NextGenerationEU<br>
<img src="https://github.com/demanasta/prepare_web/blob/main/logos/prepare_logo.png" width="150"><img src="https://github.com/demanasta/prepare_web/blob/main/logos/ntua.png" width="150"><br>
<img src="https://github.com/demanasta/prepare_web/blob/main/logos/elidek_en.jpg" width="200">  <img src="https://github.com/demanasta/prepare_web/blob/main/logos/Gr20_en.jpg" width="380">

