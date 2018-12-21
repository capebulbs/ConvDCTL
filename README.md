# ConvDCTL
Enable convolution in DaVinci Resolve by DCTL (DaVinci Color Transform Language)

How to use:

Copy the file to the DaVinci Resolve LUT directory:
/Library/Application Support/Blackmagic Design/DaVinci Resolve/LUT (for Mac)
C:\ProgramData\Blackmagic Design\DaVinci Resolve\Support\LUT (for Windows)
/home/resolve/LUT (for Linux)

In Color Page of DaVinci Resolve, Apply "DCTL" in ResolveFX Color to the selected node, and choose "Conv.dctl" in DCTL List, then tweak the kernel values and the Coefficient. The default kernel values are Laplace operator.
