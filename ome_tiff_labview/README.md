A set of VIs for writing OME-TIFF files in Labview.  This is not a general solution for writing OME-TIFF,
because the OME-XML is handled in a very basic manner.  However, if you need to save stacks of images in an
OME-TIFF format and need a quick solution, this could do the trick.

The included DLL is built for 32-bit Windows.  For other architectures, rebuild Libtiff as necessary (Zlib etc. also required).
