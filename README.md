# Card Api Coil XML Example

It's some simple CardView using Picasso lib for deserializing and loading an image.

There are 3 cards:
1) The URL is ok and has no delay
2) The URL is ok but has a 5s delay - async
3) The URL is ok but has a 5s delay - sync
4) The URL is broken
   
I also reuse the card layout inside the main layout using xml include

The image with delayed code has some distortion using Coil, but I still don't know the reason
