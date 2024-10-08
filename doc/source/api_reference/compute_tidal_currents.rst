=========================
compute_tidal_currents.py
=========================

- Calculates tidal currents for an input file (ascii, netCDF4, HDF5, geotiff)
- For netCDF4 and HDF5 files, can extract the time units from attributes
- Can use OTIS format tidal solutions provided by Ohio State University and ESR
- Can use Finite Element Solution (FES) models provided by AVISO

`Source code`__

.. __: https://github.com/tsutterley/pyTMD/blob/main/scripts/compute_tidal_currents.py

.. argparse::
    :filename: ../../scripts/compute_tidal_currents.py
    :func: arguments
    :prog: compute_tidal_currents.py
    :nodescription:
    :nodefault:

    --variables : @after
        * for csv files: the order of the columns within the file
        * for HDF5 and netCDF4 files: time, y, x and data variable names

    --type -t : @after
        * ``'drift'``: drift buoys or satellite/airborne altimetry (time per data point)
        * ``'grid'``: spatial grids or images (single time for all data points)

    --epoch -e : @after
        * ``'days since 1858-11-17T00:00:00'`` (default Modified Julian Days)

    --deltatime -d : @after
        * can be set to ``0`` to use exact calendar date from epoch

    --standard -s : @after
        * ``'UTC'``: Coordinate Universal Time
        * ``'GPS'``: GPS Time
        * ``'LORAN'``: Long Range Navigator Time
        * ``'TAI'``: International Atomic Time
        * ``'datetime'``: formatted datetime string in UTC

    --projection : @after
        * ``4326``: latitude and longitude coordinates on WGS84 reference ellipsoid

    --cutoff -c : @after
        * set to ``'inf'`` to extrapolate for all points
