# CGD-stata-scheme
A Stata scheme for CGD graphs

This is a scheme which goes someway towards implementing CGD's [branding and data viz guidelines](https://centerforglobaldevelop.sharepoint.com/:b:/r/sites/fileshare/Shared%20Documents/NDrive/Communications/CGD%20Branding%20Materials/CGD-Data-Viz-Style-Guide.pdf?csf=1&web=1&e=H081DY) on Stata graphs. It is a useful default which will likely still need to be modified by the user. There are other versions of this script floating around, but the point of this repository is to serve as the canonical version. If you have a change or improvement to the script (very welcome!) please submit a pull request, if you have your own Github account, or contact Jeremy Gaines (jgaines@cgdev.org) to get the direct login info.

*An R script which implements the branding and data viz guide is available [here](https://github.com/Center-for-Global-Development/CGDRtheme).*

## Instructions

1. Either clone the repository or download the relevant file directly [here](https://github.com/Center-for-Global-Development/CGD-stata-scheme/blob/main/scheme-cgd.scheme).
2. Type “adopath” in Stata to find where to save the new scheme
3. Save a copy of the file below as “scheme-cgd.scheme” in “Stata/ado/plus/s/” or “Stata/ado/personal/s/”
4. Type “set scheme cgd, permanently” in Stata
5. You may need to restart Stata
