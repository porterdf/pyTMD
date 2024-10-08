pyTMD
=====

``pyTMD`` is a Python-based tidal prediction software that reads OTIS, GOT and FES
formatted tidal solutions for predicting ocean and load tides and can use IERS
conventions for calculating radial pole tide displacements.

.. toctree::
    :maxdepth: 2
    :caption: Getting Started

    getting_started/Overview.rst
    getting_started/Install.rst
    getting_started/Getting-Started.rst
    getting_started/Contributing.rst
    getting_started/Resources.rst
    getting_started/Citations.rst

.. toctree::
    :maxdepth: 1
    :hidden:
    :caption: User Guide

    user_guide/Examples.rst

.. toctree::
    :maxdepth: 1
    :hidden:
    :caption: API Reference

    api_reference/bilinear_interp.rst
    api_reference/calc_astrol_longitudes.rst
    api_reference/calc_delta_time.rst
    api_reference/check_tide_points.rst
    api_reference/compute_equilibrium_tide.rst
    api_reference/compute_tide_corrections.rst
    api_reference/convert_ll_xy.rst
    api_reference/eop.rst
    api_reference/iers_mean_pole.rst
    api_reference/infer_minor_corrections.rst
    api_reference/load_constituent.rst
    api_reference/load_nodal_corrections.rst
    api_reference/model.rst
    api_reference/nearest_extrap.rst
    api_reference/output_otis_tides.rst
    api_reference/predict_tidal_ts.rst
    api_reference/predict_tide_drift.rst
    api_reference/predict_tide.rst
    api_reference/read_FES_model.rst
    api_reference/read_GOT_model.rst
    api_reference/read_iers_EOP.rst
    api_reference/read_netcdf_model.rst
    api_reference/read_ocean_pole_tide.rst
    api_reference/read_tide_model.rst
    api_reference/spatial.rst
    api_reference/tidal_ellipse.rst
    api_reference/time.rst
    api_reference/utilities.rst

.. toctree::
    :maxdepth: 1
    :hidden:
    :caption: Utilities

    api_reference/arcticdata_tides.rst
    api_reference/aviso_fes_tides.rst
    api_reference/reduce_OTIS_files.rst
    api_reference/usap_cats_tides.rst
    api_reference/verify_box_tpxo.rst

.. toctree::
    :maxdepth: 1
    :hidden:
    :caption: Use Cases

    api_reference/compute_LPET_elevations.rst
    api_reference/compute_LPT_displacements.rst
    api_reference/compute_OPT_displacements.rst
    api_reference/compute_tidal_currents.rst
    api_reference/compute_tidal_elevations.rst
