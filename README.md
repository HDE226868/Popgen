
# Popgen
Popgen is a Python 3.x script to generate randomized zero-age main sequence (ZAMS) stellar populations. It uses initial mass functions (IMFs) from [Salpeter (1955)](http://adsabs.harvard.edu/abs/1955ApJ...121..161S) and [Kroupa (2002)](http://adsabs.harvard.edu/abs/2001MNRAS.322..231K) to generate an initial mass distribution, then uses fits from [Tout et al. (1996)](http://mnras.oxfordjournals.org/content/281/1/257.full.pdf) based on stellar models to determine the radii, luminosities, and surface temperatures of the stars. The basic model uses a metallicity reference point of Z = 0.02, close to the Sun's metallicity, but different metallicities can be accounted for.

Copyright 2016 HDE 226868

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License
