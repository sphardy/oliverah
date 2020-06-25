---
#
# oliverah.com home page
#
# Simple memoji based splash page with gallery of links
#
# Header image adjusted to keep memoji being inapproriately cut based on page dimensions
#

title             : "Oliverah<br/>Consulting<br/>Services"
tagline           : |-
  Business Development & Project Management Services for the Technology Industry.

author            : Personal
read_time         : false

layout            : sph-splash

header:
  overlay_image   : /assets/images/OliverahClear.jpg
  overlay_filter  : rgba(185,144,117,0.15)
  position        : "81% 50%" #Shift image up
  #actions:
  #  - label       : About Me...
  #    url         : /about

permalink         : /

sctag             : Home #Statcounter Tag

gallery:
  # Oliverah Site Image
  - title         : "About Oliverah..."
    alt           : "About Oliverah"
    url           : /about
    image_path    : /assets/images/sph-oliverah.jpg

  # Contact Image
  - title         : "Contact Me Here..."
    alt           : "Contact Me"
    url           : /contact
    image_path    : /assets/images/sph-contact.jpg

  # File Upload Image
  - title         : "Send Stuff Here..."
    alt           : "File Upload"
    url           : /uploads
    image_path    : /assets/images/sph-upload.jpg

01234567890123456 : Align
---
<!--style>.page__hero--overlay {height: 100%;}</style-->
<style>
  .page__hero--overlay {min-height: 350px;}
</style>
{% include gallery %}
