cbrewer2
========

This package makes Cynthia Brewer's
[ColorBrewer schemes](http://colorbrewer2.org/)
available in MATLAB, with a user-friendly interface.

Schemes can be interpolated to include more colours.
By default, this is done using cubic interpolation in the almost-perceptually
uniform CIELAB colour space to prevent inflection points arising and distorting
the scheme.


Requirements
------------

To interpolate the colour schemes in CIELab space, the FEX package
[colorspace](https://www.mathworks.com/matlabcentral/fileexchange/28790-colorspace-transformations)
is required.


Licensing
---------

Copyright (c) 2016 Scott Lowe

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
