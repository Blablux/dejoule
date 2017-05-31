# dejoule

dejoule is a collection of vector files intendend for laser cutting, tracing and
etching.

Currently, files are saved at different states and have not yet been tested on
real material (but dimensions have been checked on print).

Here are the three different states available :

+ __BW__: simple black and white template
+ __colors__: Colors are added to differenciate etching, tracing and cutting.
Unless there's a need for different level of etching, colors are as follow :
    + Black (#000): etching
    + Red (#F00): cutting
    + Green (#0F0): tracing
+ __colors-width__: tracing and etching border-width is set to 0,001pt which is the
width detected by the cutter I use.

## Projects list

+ __Samples__: a small pattern used to calibrate the machine depending on the
material. It contains elements to be cut, traced or etched. There's a black and
white version, a color verion, and a version with gradient in case you need to
test greyscale.
+ __XwingTMG__: Templates from the
[FFG game](https://www.fantasyflightgames.com/en/products/x-wing/). Tokens have
a different shape than in the game as I found it easier to stack. Other
templates are supposed to be similar to the ones used in the game. Also include
a generic template file with common used images.

## Side Note

DeJoule is the guardian of the pillar of _Energy_ and a NPC from the video
games serie [Legacy of Kain](https://en.wikipedia.org/wiki/Legacy_of_Kain).
