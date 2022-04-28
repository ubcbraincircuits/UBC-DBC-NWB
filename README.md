# UBC-DBC-NWB
The script, NWBMetadataScript.ipynb, is meant to demonstrate how to augment metadata to a Neurodata Without Borders (https://www.nwb.org) file format (a more standardized way of storing raw and processed neuroscience data). Executing this script will allow you to add metadata to an nwb file that has been generated with a data analysis/visualization tool.

You can use the following script assuming that you have done the steps below:
<br>
- Images have been recorded and scanned correctly with spatial calibration (with a two-photon microscope). <br>
- The .tiff format files have then been imported and analyzed with suite2p* which produces an NWB file.  <br>

Therefore, the NWB file created by suite2p can now be loaded and its corresponding metadata can be added by following the script below. <br>
*Additional note on using suite2p: If you are interested in using suite2p for calcium imaging analysis please refer to the link posted below which provides further documentation on the use of suite2p: <br>
https://suite2p.readthedocs.io/en/latest/_modules/suite2p/io/nwb.html

Please note that the ophys.nwb file is the one we used to run the script with.

