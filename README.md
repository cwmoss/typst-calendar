# 12 Page Month Calendar

This is an example typst template that creates a PDF with 12 page monthly calendar for a given year.

The month layout contains an image and a list of events.

## create the pdf

    // put your images in the images/ folder
    // create a list of paths to the images
    ls images/ > images.txt

    // edit events.txt for birthdays etc.

    // compile the pdf
    typst compile --font-path fonts/ calendar.typ

## font credits

fonts used: poppins & playwrite found on google fonts

## image credits

please look at `image-credits.html` for the list of demo images
