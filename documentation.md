# Documentation

Here is a documentation of what have been tried to get to the solution.

## Image Search

For the image search two google searches where performed. The searched term was in both cases `harvard`. Then the two `URL`s have been compare. The idea was to look for criteria like:

- key/value pair that is consistent for all cases
- probably no number because they are likely to change with each search
- other key than "q"

For example here are two `URL`s:

- https://www.google.com/search?q=harvard&sca_esv=579077719&hl=en&tbm=isch&source=hp&biw=1512&bih=856&ei=aahEZbbbGcqWseMPieuBmA8&iflsig=AO6bgOgAAAAAZUS2eaDOGmwMjZa_SrukyWPfdWm4dFuD&ved=0ahUKEwj2s4qWrqeCAxVKS2wGHYl1APMQ4dUDCAc&uact=5&oq=harvard&gs_lp=EgNpbWciB2hhcnZhcmQyCBAAGIAEGLEDMggQABiABBixAzIIEAAYgAQYsQMyCBAAGIAEGLEDMggQABiABBixAzILEAAYgAQYsQMYgwEyCxAAGIAEGLEDGIMBMgUQABiABDIFEAAYgAQyBRAAGIAESOcLUABY5QlwAHgAkAEAmAFKoAHRA6oBATe4AQPIAQD4AQGKAgtnd3Mtd2l6LWltZ8ICCxAAGIoFGLEDGIMBwgIIEAAYigUYsQM&sclient=img
- https://www.google.com/search?q=harvard&tbm=isch&ved=2ahUKEwjHycyXrqeCAxU8TWwGHXKTDB0Q2-cCegQIABAA&oq=harvard&gs_lcp=CgNpbWcQAzIKCAAQigUQsQMQQzIHCAAQigUQQzIHCAAQigUQQzIKCAAQigUQsQMQQzIHCAAQigUQQzIHCAAQigUQQzIHCAAQigUQQzIHCAAQigUQQzIHCAAQigUQQzIHCAAQigUQQ1AAWABg4gJoAHAAeACAAUaIAUaSAQExmAEAqgELZ3dzLXdpei1pbWfAAQE&sclient=img&ei=bKhEZcfjJLyaseMP8qay6AE&bih=856&biw=1512&hl=en

Over try and error the right key/value pair was identified as `tbm=isch`

This property was then implemented into `html/image.html` (see `id="img_in2"`).


