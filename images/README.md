# README

## Sources

## How the UCSF HPC logo was created
The UCSF HPC logo was created using
[paint.net](http://www.getpaint.net/index.html):

 1. Import
    [`ucsf_logo_K_OTL_9,1200dpi,000000,transparent.png`](https://github.com/UCSF-CBC/UCSF-logo/)
 2. Resize canvas to 3099x1522 px to 3099x3099 px
 3. Resize image to 1136x1136px
 4. Use Tool 'Magick Wand' to select white background and delete
    (this will turn it into transparent background).
 5. Set text font to 'Courier New' with size '448 pt' and 'bold' style.
 6. Set primary color to 990000 (153,00,00), which is red.
 7. Add text `HPC`.
 8. Select UCSF + HPC text.
 9. Choose Tools 'Move Selected Pixels'
10. Shift selected image downward to center vertically (keyboard works
    here) and press ENTER.
11. Save as 'UCSF-HPC-logo,000000_990000,transparent,1136x1136.png'
   

This above was done by Henrik Bengtsson on 2016-01-24.


## How the favicon was created
The favicon was created from the UCSF HPC logo as:
```sh
convert images/UCSF-HPC-logo,000000_990000,transparent,1136x1136.png -geometry 128x128 -define icon:auto-resize=64,48,32,16 ico/favicon.ico
```
using [ImageMagick](http://www.imagemagick.org/).



## REFERENCES:
* [1] https://github.com/ucsf-web-services/ucsf_identity_web_banner_templates
