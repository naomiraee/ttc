#ttc
# Postcard Maker

Postcard Maker is a simple, responsive web app where you can upload an image and it’ll be sent out as a postcard.

Images are uploaded via the Express backend, to the image host, cloudinary.com, via a Node module. You can resize and crop the original image to postcard size and then it’s sent to the dispatcher, lob.com, for print and delivery via another Node module. Stripe is used to process payments. 

![](https://cdn.hyperdev.com/70b0550f-da2e-4d0e-bb9b-c81436d7d8d4%2FpostcardMakerGIF.gif)

## Getting Started

See `setup.md` for an overview of how the code works.
