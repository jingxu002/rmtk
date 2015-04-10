Risk Modeller's Toolkit (rmtk)
==============================

This is the web repository of the Risk Modeller's Toolkit (rmtk). 
The rmtk is a suite of tools developed by scientists working at the 
GEM (i.e. Global Earthquake Model) Model Facility. The main purpouse
of the rmtk is to provide a suite of tools for the creation of seismic
risk input models.

The toolkit contains the following functionalities for constructing 
seismic risk input models (please refer to the documentation and
tutorial for more information):


VULNERABILITY TOOLS:

* Nonlinear Static Methods:
    - ''R–μ–T'' relation (Dolšek and Fajfar, 2004)
    - ''SPO2IDA'' (Vamvatsikos and Cornell, 2006)
    - ''CR–μ–T'' (Ruiz-García and Miranda, 2007)

* Nonlinear Dynamic Methods:
    - Incremental Dynamic Analysis (Vamvatsikos and Cornell, 2002)
    - Multiple Stripe Analysis (Jalayer and Cornell, 2009)
    - Damage Probability Matrix Method


Dependencies
------------

The main dependencies of this library are the following:
* csv
* numpy
* python-decorator
* risklib (this is part of the OpenQuake suite)

For the libraries part of the OpenQuake suite the reader can refer to 
http://github.com/gem


License
-------

The Risk Modeller's Toolkit is free software: you can redistribute 
it and/or modify it under the terms of the GNU Affero General Public 
License as published by the Free Software Foundation, either version 
3 of the License, or (at your option) any later version.

Copyright © 2014-2015, GEM Foundation, Chiara Casotto, Anirudh Rao,
Vitor Silva.


Disclaimer
----------

The software Risk Modeller's Toolkit (rmtk) provided herein 
is released as a prototype implementation on behalf of 
scientists and engineers working within the GEM Foundation (Global 
Earthquake Model). 

It is distributed for the purpose of open collaboration and in the 
hope that it will be useful to the scientific, engineering, disaster
risk and software design communities. 

The software is NOT distributed as part of GEM’s OpenQuake suite 
(http://www.globalquakemodel.org/openquake) and must be considered as a 
separate entity. The software provided herein is designed and implemented 
by scientific staff. It is not developed to the design standards, nor 
subject to same level of critical review by professional software 
developers, as GEM’s OpenQuake software suite.  

Feedback and contribution to the software is welcome, and can be 
directed to the risk scientific staff of the GEM Model Facility 
(risk@globalquakemodel.org). 

The Risk Modeller's Toolkit (rmtk) is therefore distributed WITHOUT 
ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or 
FITNESS FOR A PARTICULAR PURPOSE. See the GNU General Public License 
for more details.

The GEM Foundation, and the authors of the software, assume no 
liability for use of the software.