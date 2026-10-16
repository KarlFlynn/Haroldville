Haroldville Tour - standalone website
=====================================

Upload everything in this folder (keep the folder layout as it is) to any
static web host. The page must be served over https:// for the VR button
to work; all the hosts below do that automatically.

Easiest: Netlify Drop
  1. Unzip this file on your PC.
  2. Go to https://app.netlify.com/drop and sign up (free).
  3. Drag the unzipped "haroldville-tour" folder onto the page.
  4. You get a link like https://something.netlify.app - you can rename
     it in the site's settings, e.g. haroldville-tour.netlify.app.

Other free options: GitHub Pages, Cloudflare Pages.

Files:
  index.html     the tour page
  aframe.min.js  A-Frame 1.7.0 (MIT licence), the VR engine
  photos/        full-size 360 photos (computers and headsets)
  lite/          4K copies (phones)
  thumbs/        small previews for the "All rooms" grid

Don't open index.html by double-clicking it: browsers block the photos
from loading off your own disk. It needs to be on a web host.
