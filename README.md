# tinymvt-rs

[![codecov](https://codecov.io/gh/MIERUNE/tinymvt/graph/badge.svg?token=HSPd9MRmxC)](https://codecov.io/gh/MIERUNE/tinymvt)
![Crates.io Version](https://img.shields.io/crates/v/tinymvt)

A minimal Rust toolkit for serializing Mapbox Vector Tiles (MVT).

License: MIT

Includes the following utilities:

- Protobuf ([prost](https://github.com/tokio-rs/prost)) data types for MVT
- Geometry encoder
- Tags encoder
- Conversion between Web Mercator and geographic coordinates
- Conversion between linear tile IDs (PMTiles-compliant Hilbert IDs) and XYZ tile coordinates

