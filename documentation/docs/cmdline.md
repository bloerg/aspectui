# Command line tools
[ASPECT](http://www.tls-tautenburg.de/TLS/fileadmin/forschung/meus/ASPECT/ASPECT.html) outputs html tables containing images for icon specs and hyperlinking to [SDSS Explorer sites](http://sdss3.org/FIXME) related to the icons.

The following command line tools are supposed to combine data created by ASPECT with spectra metadata from SDSS fits files.

## Commands

* `aspectui.py [dir-name]` - Creates a complete Map from an input file like full0_0.html including metadata files and downsized icon zoomlevels.
* `render_icons.py` - Basic nice and ugly icon rendering of spectra from fits files.
* `sdss_id_mapping.py` - Creates csv output of MJD-PLATEID-FIBERID to SOM x and y coordinates mapping from input file like full0_0.html

## Project layout

    mkdocs.yml    # The configuration file.
    docs/
        index.md  # The documentation homepage.
        ...       # Other markdown pages, images and other files.
