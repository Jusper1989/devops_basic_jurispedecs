## Otrais MD, 14.punkts

# Vienādiem failiem ir vienāds hash
Zemāk atradu 2 veidus kā to salīdzināt, pirmais ir ar git log --raw komandu
Otrais ir ar git ls-files komandu konkrētam failam

commit cf117fadc1f90df0305a4731134c9bc508f485cb
Author: Juris Pedecs <juris.pedecs@gmail.com>
Date:   Sun May 1 18:56:04 2022 +0300

    md septitais punkts, pievienoju failus

:000000 100644 0000000 8c5e001 A        module_1/README.md
:000000 100644 0000000 7e30a41 A        module_1/git_md.JPG
:000000 100644 0000000 9223905 A        module_1/hello_world.JPG


commit efd4b3a5bc526421a1dd1705cec22b62a259fa43 (HEAD -> main, origin/main, origin/HEAD)
Author: Juris Pedecs <juris.pedecs@gmail.com>
Date:   Sun May 1 20:13:19 2022 +0300

    md 2, uzdevums 12

:000000 100644 0000000 e69de29 A        module_2/README.md
:000000 100644 0000000 7e30a41 A        module_2/git_md.JPG
:000000 100644 0000000 9223905 A        module_2/hello_world.JPG



Juris@JURIS-PC MINGW64 ~/Documents/LU_DevOPS/git_repos/devops_basic_jurispedecs/module_2 (main)
$ git ls-files -s git_md.JPG
100644 7e30a41ee0378fcd1768cc38b2e5bbbd02803e24 0       git_md.JPG

Juris@JURIS-PC MINGW64 ~/Documents/LU_DevOPS/git_repos/devops_basic_jurispedecs/module_2 (main)
$ cd ../module_1

Juris@JURIS-PC MINGW64 ~/Documents/LU_DevOPS/git_repos/devops_basic_jurispedecs/module_1 (main)
$ git ls-files -s git_md.JPG
100644 7e30a41ee0378fcd1768cc38b2e5bbbd02803e24 0       git_md.JPG
