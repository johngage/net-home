---
widget: slider
headless: true  # This file represents a page section.
title: "Slider Test"
active: true

# ... Put Your Section Options Here (section position etc.) ...
weight: 10
# Slide interval.
# Use `false` to disable animation or enter a time in ms, e.g. `5000` (5s).
interval: false

# Minimum slide height.
# Specify a height to ensure a consistent height for each slide.
height: 300px

item:
  - title: "Hi,there, John"
    content: 'I am center aligned 😄'
    # Choose `center`, `left`, or `right` alignment.
    align: center
    # Overlay a color or image (optional).
    #   Deactivate an option by commenting out the line, prefixing it with `#`.
    overlay_color: '#666'  # An HTML color value.
    overlay_img: camp.jpg  # Image path relative to your `assets/media/` folder
    overlay_filter: 0.5  # Darken the image. Value in range 0-1.
    
    # Call to action button (optional).
    #   Activate the button by specifying a URL and button label below.
    #   Deactivate by commenting out parameters, prefixing lines with `#`.
    cta_label: Download my app
    cta_url: 'https://example.org'
    cta_icon_pack: fas
    cta_icon: graduation-cap
    
  - title: PHOTO-2021-02-10-16-58-20
    content: 'I am left aligned 😄'
    align: left
    overlay_color: '#555'
    overlay_img: 'PHOTO-2021-02-10-16-58-20.jpg'
    overlay_filter: 0.5
  - title: IMG_9305.png
    content: 'I am right aligned 😄'
    align: right
    overlay_color: '#333'
    overlay_img: 'IMG_9305.png'
    overlay_filter: 0.5
  - title: KTC.1 
    content: 'I am left aligned 😄'
    align: left
    overlay_color: '#555'
    overlay_img: 'KTCWaterTreatment.tiff'
    overlay_filter: 0.5
  - title: KTC.2 gif
    content: 'I am right aligned 😄'
    align: right
    overlay_color: '#333'
    overlay_img: 'Safaricom.gif'
    overlay_filter: 0.5
  - title: KTC.3 svg
    content: 'I am left aligned 😄'
    align: left
    overlay_color: '#555'
    overlay_img: 'JupyterConsole.svg'
    overlay_filter: 0.5
  - title: KTC.4
    content: 'I am right aligned 😄'
    align: right
    overlay_color: '#333'
    overlay_img: ''
    overlay_filter: 0.5
  - title: another jpg
    content: 'picture of Darfur'
    overlay_img: '2080627_065628.jpg'
    
---
