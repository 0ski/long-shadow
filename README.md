# Long shadow SASS mixin

SASS mixin to produce long shadows, check the demo up, here: https://0ski.github.io/long-shadow/
Long shadow is created out of multiple dropped shadows.
It produces text or box shadow based on parameters:

* $length (default: 100) - length of the shadow, the unit is extracted and used in further computations
* $color (default: rgba(128, 128, 128, 0.05)) - color of the shadow
* $stepX (default: 0.5) - the X distance between dropped shadows (value between 0 and 1 means more created shadows), negative value can be used
* $stepY (default: 0.5) - the Y distance between dropped shadows (value between 0 and 1 means more created shadows), negative value can be used
* $blur (default: 1) - blur parameter for created shadows
