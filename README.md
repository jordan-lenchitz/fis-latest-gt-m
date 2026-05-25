all software in this package is part of fis gtm which is copyright 2026 fidelity information services inc and provided to you under the terms of a license if there is a copying file included in this package it contains the terms of the license under which the package is provided to you if there is not a copying file in the package you must ensure that your use of fis gtm complies with the license under which it is provided if you are unsure as to the terms of your license please consult with the entity that provided you with the package

gtm relies on cmake to generate the makefiles

to build gtm from source sudo the following after meeting the prereqs

`$ mkdir <fis-gtm-build>`

`$ cd <fis-gtm-build>`

`$ cmake -d cmake_install_prefixpath=$pwd/package <path to>/fis-gtm-v71-011`

`$ make`

`$ make install`

`$ cd package/lib/fis-gtm/v71-011_x86_64`

`# now you are ready to install gtm one recommended installation path is /opt/fis-gtm/v71-011_x86_64`

`$ ./configure`

`$ make clean`
