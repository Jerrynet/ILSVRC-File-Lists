# ILSVRC 2012-2014 CLS-LOC File Lists

**Format:**
Each row is an image-label pair with the following format:
*filepath label*

**Labels**
- All labels were converted to numbers, starts from 1.
- The numbering follows the label order specified in ILSVRC-2014 devkit.

**Lists**
- *trainList.txt* All train images
- *trainList_noCMYK_noPNG* Train images, but not include files saved as CMYK color space or fake jpeg files (actually pngs)
- *valList* All validation images
- *valList_filtered.txt* Exclude CMYK images.


Please see [ilsvrc-cmyk-image-list](https://github.com/cytsai/ilsvrc-cmyk-image-list) for more information about these images.

**Note**
This is not an official ILSVRC release. Please check the official website: [ILSVRC Challenge](http://www.image-net.org/challenges/LSVRC/).
