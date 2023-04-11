# Python code to create the list of URLs for VLASS fits images
This Python code generates a list of URLs for VLASS fits images. It fetches the links to all VLASS files within a specified epoch of VLASS data contained in a given folder of tiles.

The resulting output of this code can be used as an input for running the CIRADA catalog generator available on GitHub at https://github.com/CIRADA-Tools/continuum_bdp_catalogue_generator. The CIRADA catalog generator will then use these links to download the files and run PyBDSF to do the source finding on these fits images.

The usage is as follows.
```python
python get_urls_from_nrao.py <URL> <mode>
```

Here, an example for URL is https://archive-new.nrao.edu/vlass/se_continuum_imaging/VLASS2.1 .
There are two modes, 'w' for write and 'a' for append.
