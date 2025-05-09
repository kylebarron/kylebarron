### Hi there! I'm Kyle 👋

I'm a software engineer passionate about fast, interoperable geospatial data science.

I'm primarily developing the [Apache Arrow], [GeoArrow] and [GeoParquet] ecosystems to make that a reality.

**Python:**

| Project                  | Role   | Description                                                                                   |
| ------------------------ | ------ | --------------------------------------------------------------------------------------------- |
| [obstore]                | author | The simplest, highest-throughput Python interface to S3, GCS & Azure Storage.                 |
| [lonboard]               | author | Python library for fast, interactive geospatial vector data visualization in Jupyter.         |
| [arro3]                  | author | A minimal Python library to manage [Apache Arrow] data                                        |
| [geoarrow-rust]          | author | A Python library implementing the [GeoArrow] specification with efficient spatial operations. |
| [geopolars]              | author | Geospatial extensions for the [Polars] DataFrame library.                                     |
| [geoindex-rs]            | author | Fast, memory-efficient 2D spatial indexes for Python.                                         |
| [suncalc-py]             | author | A Python port of suncalc.js for calculating sun position and sunlight phases.                 |
| [pymartini]              | author | A Cython port of Martini for fast RTIN terrain mesh generation.                               |
| [pydelatin]              | author | Python bindings to `hmm` for fast terrain mesh generation.                                    |
| [quantized-mesh-encoder] | author | A fast Python [Quantized Mesh] encoder                                                        |
| [usgs-topo-tiler]        | author | Python package to read Web Mercator map tiles from USGS Historical Topographic Maps           |
| [keplergl_cli]           | author | One-line geospatial data visualization using Kepler.gl                                        |

**Rust:**

| Project             | Role             | Description                                                                                                                                   |
| ------------------- | ---------------- | --------------------------------------------------------------------------------------------------------------------------------------------- |
| [geoarrow-rs]       | author           | A Rust implementation of the [GeoArrow] specification and bindings to GeoRust algorithms for efficient spatial operations on GeoArrow memory. |
| [wkb]               | author           | Fast, pure-Rust reader and writer for Well-Known Binary geometries.                                                                           |
| [wkt]               | core contributor | Rust read/write support for well-known text (WKT)                                                                                             |
| [geo-index]         | author           | A Rust crate for packed, static, zero-copy spatial indexes.                                                                                   |
| [pyo3-arrow]        | author           | Lightweight [Apache Arrow] integration for [pyo3].                                                                                            |
| [pyo3-object_store] | author           | Integration between [object_store] and [pyo3].                                                                                                |
| [arrow-wasm]        | author           | Building block library for using Apache Arrow in Rust WebAssembly modules                                                                     |
| [geopolars]         | author           | Geospatial extensions for the [Polars] DataFrame library.                                                                                     |

**JavaScript:**

| Project                    | Role        | Description                                                                    |
| -------------------------- | ----------- | ------------------------------------------------------------------------------ |
| [parquet-wasm]             | author      | Rust-based WebAssembly bindings to read and write Apache [Parquet] data.       |
| [@geoarrow/deck.gl-layers] | author      | [deck.gl] layers for rendering [GeoArrow] data.                                |
| [geoarrow-wasm]            | author      | Efficient, vectorized geospatial operations in WebAssembly.                    |
| [arrow-js-ffi]             | author      | Zero-copy reading of Arrow data from WebAssembly.                              |
| [literate-flatbush]        | documenter  | Understanding [Flatbush]: a fast, elegant RTree implementation.                |
| [geoarrow-js]              | author      | TypeScript implementation of [GeoArrow].                                       |
| [deck.gl]                  | contributor | WebGL2 powered visualization framework.                                        |
| [deck.gl-raster]           | author      | [deck.gl] layers and WebGL modules for client-side satellite imagery analysis. |

**Specifications:**

| Project      | Role             | Description                                                                           |
| ------------ | ---------------- | ------------------------------------------------------------------------------------- |
| [GeoArrow]   | core contributor | Specification for storing geospatial data in Apache Arrow.                            |
| [GeoParquet] | core contributor | Specification for storing geospatial vector data (point, line, polygon) in [Parquet]. |

**Other:**

| Project                        | Role   | Description                                                                                                                                                                                                                                                      |
| ------------------------------ | ------ | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [National Scenic Trails Guide] | author | A [website](https://nst.guide) and [data tools](https://github.com/nst-guide) for exploring and navigating the [Pacific Crest Trail]. After hiking the PCT, this project was the core of my effort to transition to a career in geospatial software engineering. |
| [all-transit]                  | author | Visualization of all transit routes in continental U.S.                                                                                                                                                                                                          |
| [vscode-jupyter-python]        | author | Run automatically-inferred Python code blocks in the VS Code Jupyter extension                                                                                                                                                                                   |

[@geoarrow/deck.gl-layers]: https://github.com/geoarrow/deck.gl-layers
[all-transit]: https://github.com/kylebarron/all-transit
[Apache Arrow]: https://arrow.apache.org/
[arro3]: https://github.com/kylebarron/arro3
[arrow-js-ffi]: https://github.com/kylebarron/arrow-js-ffi
[arrow-wasm]: https://github.com/kylebarron/arrow-wasm
[deck.gl-raster]: https://github.com/kylebarron/deck.gl-raster/
[deck.gl]: https://github.com/visgl/deck.gl
[flatbush]: https://github.com/mourner/flatbush
[geo-index]: https://github.com/kylebarron/geo-index
[geoarrow-js]: https://github.com/geoarrow/geoarrow-js
[geoarrow-rs]: https://github.com/geoarrow/geoarrow-rs
[geoarrow-rust]: https://geoarrow.org/geoarrow-rs/python/latest/
[geoarrow-wasm]: https://github.com/geoarrow/geoarrow-rs/tree/main/js#readme
[geoarrow]: https://github.com/geoarrow/geoarrow
[geoindex-rs]: https://github.com/kylebarron/geo-index/tree/main/python
[geoparquet]: https://github.com/opengeospatial/geoparquet
[geopolars]: https://github.com/geopolars/geopolars
[keplergl_cli]: https://github.com/kylebarron/keplergl_cli
[literate-flatbush]: https://github.com/kylebarron/literate-flatbush
[lonboard]: https://github.com/developmentseed/lonboard
[National Scenic Trails Guide]: https://nst.guide/
[object_store]: https://crates.io/crates/object_store
[obstore]: https://github.com/developmentseed/obstore
[Pacific Crest Trail]: https://en.wikipedia.org/wiki/Pacific_Crest_Trail
[parquet-wasm]: https://github.com/kylebarron/parquet-wasm
[Parquet]: https://parquet.apache.org/
[Polars]: https://github.com/pola-rs/polars
[pydelatin]: https://github.com/kylebarron/pydelatin
[pymartini]: https://github.com/kylebarron/pymartini
[pyo3-arrow]: https://github.com/kylebarron/arro3/tree/main/pyo3-arrow
[pyo3-object_store]: https://github.com/developmentseed/obstore/tree/main/pyo3-object_store
[pyo3]: https://github.com/PyO3/pyo3
[Quantized Mesh]: https://github.com/CesiumGS/quantized-mesh
[quantized-mesh-encoder]: https://github.com/kylebarron/quantized-mesh-encoder
[suncalc-py]: https://github.com/kylebarron/suncalc-py
[usgs-topo-tiler]: https://github.com/kylebarron/usgs-topo-tiler
[vscode-jupyter-python]: https://github.com/kylebarron/vscode-jupyter-python
[wkb]: https://github.com/georust/wkb
[wkt]: https://github.com/georust/wkt

<!--
**kylebarron/kylebarron** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
