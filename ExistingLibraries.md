# Existing Libraries

Here's a partial listing of some of the existing libraries in julia that you can use for working with geospatial data. Not all of them are listed under the JuliaGeo organization, but some of them might get moved over.

## Wrappers for C Libraries
- [LibGEOS.jl](https://github.com/JuliaGeo/LibGEOS.jl) is a wrapper to GEOS for performing geospatial operations on vector geometries
- [Proj4.jl](https://github.com/JuliaGeo/Proj4.jl) is a wrapper to PROJ.4 for performing cartographic projections
- [GDAL.jl](https://github.com/visr/GDAL.jl) is a wrapper to GDAL (Geospatial Data Abstraction Library) for reading and writing raster and vector datasets; [ArchGDAL.jl](https://github.com/yeesian/ArchGDAL.jl) builds on top of GDAL.jl for a more julian user experience.
- [NetCDF.jl](https://github.com/JuliaGeo/NetCDF.jl) and [NCDatasets.jl](https://github.com/Alexander-Barth/NCDatasets.jl) provides a high-level and a medium-level interface for writing and reading netcdf files.
- [GMT.jl](https://github.com/joa-quim/GMT.jl) provides a wrapper for working with the [G]eneric [M]apping [T]ools (GMT) library in julia.

## Native Julia libraries
- [Geodesy.jl](https://github.com/JuliaGeo/Geodesy.jl) -- is a julia package for working with points defined in different coordinate systems, with support for LLA/ENU/ECEF currently.
- [Shapefile.jl](https://github.com/JuliaGeo/Shapefile.jl) is a julia package that parses in ESRI Shapefiles.
- [GeoJSON.jl](https://github.com/JuliaGeo/GeoJSON.jl) is a julia package that provides utilities for encoding and decoding GeoJSON formatted data.

## Other Projects
- [OpenStreetMap.jl](https://github.com/tedsteiner/OpenStreetMap.jl) and [OpenStreetMap2.jl](https://github.com/yeesian/OpenStreetMap2.jl) provides basic functionality for parsing, viewing, and working with OpenStreetMap map data.
- [LibSpatialIndex.jl](https://github.com/yeesian/LibSpatialIndex.jl) provides functionality for spatially indexing kD bounding box data (based on [libspatialindex](https://github.com/libspatialindex/libspatialindex))
