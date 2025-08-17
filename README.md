# Setup of anion-exchange membrane (AEM) composed of TMA-PF and Cl-
This repository distributes the force field parameters of trimethylammonium-substituted polyfluorene (TMA-PF) and the initial structures of anion-exchange membranes (AEM) composed of TMA-PF (10mer), Cl ions, at different water content lambda (# of water molecules/ion exchange group).
General Amber force field 2 (GAFF2), TIP4P-Ew, and Joung-Chetham parameters were used for TMA-PF, water, and Cl ions, respectively.


## Force field parameters of TMA-PF 
* [TPF.lib](./TMA-PF/TPF.lib) : Amber library file for setup
* [TPF.frcmod](./TMA-PF/TPF.frcmod) : Amber parameter modification file
* [TPF.pdb](./TMA-PF/TPF.pdb) : PDB-formatted coordinate file of TMA-PF
* [TPF_monomer.mol2](./TMA-PF/TPF_monomer.mol2) : MOL2-formatted monomer structure of TMA-PF with its point charges.

TPF.lib, TPF.frcmod, and TPF.pdb are required to setup the AEM systems with Amber ``tleap`` program.
Atom labels and charges of monomer are listed below.

| Atom index | Atom Label  | Charge (\|e\|) | 
|:------|:------------|:-------------|
|     1 |  C1         |  -0.129690   |  
|     2 |  C2         |   0.037570   |  
|     3 |  C3         |  -0.170740   |  
|     4 |  C4         |  -0.138640   |  
|     5 |  C5         |  -0.059580   |  
|     6 |  C6         |   0.128480   |  
|     7 |  H1         |   0.097120   |  
|     8 |  H2         |   0.136700   |  
|     9 |  H3         |   0.138560   |  
|    10 |  C7         |   0.026600   |  
|    11 |  C8         |   0.221390   |  
|    12 |  C9         |  -0.037550   |  
|    13 |  C10        |  -0.185860   |  
|    14 |  C11        |  -0.143310   |  
|    15 |  C12        |  -0.137530   |  
|    16 |  H4         |   0.121040   |  
|    17 |  C13        |  -0.135550   |  
|    18 |  H5         |   0.135810   |  
|    19 |  H6         |   0.000000   |  
|    20 |  H7         |   0.135930   |  
|    21 |  C14        |   0.011750   |  
|    22 |  C15        |  -0.130070   |  
|    23 |  C16        |  -0.173430   |  
|    24 |  C17        |   0.139320   |  
|    25 |  H8         |   0.101650   |  
|    26 |  C18        |  -0.145850   |  
|    27 |  H9         |   0.118830   |  
|    28 |  C19        |   0.077910   |  
|    29 |  C20        |  -0.028570   |  
|    30 |  H10        |   0.134110   |  
|    31 |  C21        |   0.205000   |  
|    32 |  C22        |  -0.053730   |  
|    33 |  C23        |  -0.163660   |  
|    34 |  C24        |  -0.141300   |  
|    35 |  C25        |  -0.133920   |  
|    36 |  H11        |   0.122970   |  
|    37 |  C26        |  -0.132830   |  
|    38 |  H12        |   0.129270   |  
|    39 |  H13        |   0.000000   |  
|    40 |  H14        |   0.132540   |  
|    41 |  C27        |  -0.277420   |  
|    42 |  C28        |   0.056470   |  
|    43 |  H15        |   0.088800   |  
|    44 |  H16        |   0.088800   |  
|    45 |  C29        |  -0.047350   |  
|    46 |  H17        |   0.006060   |  
|    47 |  H18        |   0.006060   |  
|    48 |  C30        |   0.001760   |  
|    49 |  H19        |   0.027550   |  
|    50 |  H20        |   0.027550   |  
|    51 |  H21        |   0.028060   |  
|    52 |  H22        |   0.028060   |  
|    53 |  C31        |   0.029400   |  
|    54 |  H23        |   0.024970   |  
|    55 |  H24        |   0.024970   |  
|    56 |  C32        |  -0.112910   |  
|    57 |  H25        |   0.099700   |  
|    58 |  H26        |   0.099700   |  
|    59 |  N1         |   0.223030   |  
|    60 |  C33        |  -0.408830   |  
|    61 |  C34        |  -0.408830   |  
|    62 |  C35        |  -0.408830   |  
|    63 |  H27        |   0.195500   |  
|    64 |  H28        |   0.195500   |  
|    65 |  H29        |   0.195500   |  
|    66 |  H30        |   0.195500   |  
|    67 |  H31        |   0.195500   |  
|    68 |  H32        |   0.195500   |  
|    69 |  H33        |   0.195500   |  
|    70 |  H34        |   0.195500   |  
|    71 |  H35        |   0.195500   |  
|    72 |  C36        |  -0.277420   |  
|    73 |  C37        |   0.056470   |  
|    74 |  H36        |   0.088800   |  
|    75 |  H37        |   0.088800   |  
|    76 |  C38        |  -0.047350   |  
|    77 |  H38        |   0.006060   |  
|    78 |  H39        |   0.006060   |  
|    79 |  C39        |   0.001760   |  
|    80 |  H40        |   0.027550   |  
|    81 |  H41        |   0.027550   |  
|    82 |  H42        |   0.028060   |  
|    83 |  H43        |   0.028060   |  
|    84 |  C40        |   0.029400   |  
|    85 |  H44        |   0.024970   |  
|    86 |  H45        |   0.024970   |  
|    87 |  C41        |  -0.112910   |  
|    88 |  H46        |   0.099700   |  
|    89 |  H47        |   0.099700   |  
|    90 |  N2         |   0.223030   |  
|    91 |  C42        |  -0.408830   |  
|    92 |  C43        |  -0.408830   |  
|    93 |  C44        |  -0.408830   |  
|    94 |  H48        |   0.195500   |  
|    95 |  H49        |   0.195500   |  
|    96 |  H50        |   0.195500   |  
|    97 |  H51        |   0.195500   |  
|    98 |  H52        |   0.195500   |  
|    99 |  H53        |   0.195500   |  
|   100 |  H54        |   0.195500   |  
|   101 |  H55        |   0.195500   |  
|   102 |  H56        |   0.195500   |  
|   103 |  C45        |  -0.171020   |  
|   104 |  H57        |   0.050800   |  
|   105 |  H58        |   0.050800   |  
|   106 |  C46        |  -0.012120   |  
|   107 |  H59        |  -0.001520   |  
|   108 |  H60        |  -0.001520   |  
|   109 |  C47        |   0.015900   |  
|   110 |  H61        |   0.009300   |  
|   111 |  H62        |   0.009300   |  
|   112 |  C48        |   0.025510   |  
|   113 |  H63        |   0.004420   |  
|   114 |  H64        |   0.004420   |  
|   115 |  C49        |  -0.056020   |  
|   116 |  H65        |   0.007350   |  
|   117 |  H66        |   0.007350   |  
|   118 |  C50        |   0.000390   |  
|   119 |  H67        |  -0.003370   |  
|   120 |  H68        |  -0.003370   |  
|   121 |  C51        |   0.189110   |  
|   122 |  H69        |  -0.025010   |  
|   123 |  H70        |  -0.025010   |  
|   124 |  C52        |  -0.171020   |  
|   125 |  H71        |   0.050800   |  
|   126 |  H72        |   0.050800   |  
|   127 |  C53        |  -0.012120   |  
|   128 |  H73        |  -0.001520   |  
|   129 |  H74        |  -0.001520   |  
|   130 |  C54        |   0.015900   |  
|   131 |  H75        |   0.009300   |  
|   132 |  H76        |   0.009300   |  
|   133 |  C55        |   0.025510   |  
|   134 |  H77        |   0.004420   |  
|   135 |  H78        |   0.004420   |  
|   136 |  C56        |  -0.056020   |  
|   137 |  H79        |   0.007350   |  
|   138 |  H80        |   0.007350   |  
|   139 |  C57        |   0.000390   |  
|   140 |  H81        |  -0.003370   |  
|   141 |  H82        |  -0.003370   |  
|   142 |  C58        |   0.189110   |  
|   143 |  H83        |  -0.025010   |  
|   144 |  H84        |  -0.025010   |  
|   145 |  C59        |  -0.321120   |  
|   146 |  H85        |   0.077930   |  
|   147 |  H86        |   0.077930   |  
|   148 |  H87        |   0.077930   |  
|   149 |  C60        |  -0.321120   |  
|   150 |  H88        |   0.077930   |  
|   151 |  H89        |   0.077930   |  
|   152 |  H90        |   0.077930   |  

## Initial structures and parameters of AEM systems at different lambda
* [Lambda = 0](./Initial_structures/l_00)
* [Lambda = 1](./Initial_structures/l_01)
* [Lambda = 2](./Initial_structures/l_02)
* [Lambda = 3](./Initial_structures/l_03)
* [Lambda = 4](./Initial_structures/l_04)
* [Lambda = 5](./Initial_structures/l_05)
* [Lambda = 6](./Initial_structures/l_06)
* [Lambda = 7](./Initial_structures/l_07)
* [Lambda = 8](./Initial_structures/l_08)
* [Lambda = 9](./Initial_structures/l_09)
* [Lambda = 10](./Initial_structures/l_10)

At each lambda, 
* XX.inpcrd (XX=00, 01, ..., 05) : Amber RST7-formatted coordinate file
* XX.pdb (XX=00, 01, ..., 05) : PDB-formatted coordinate file
* complex.prmtop (XX=00, 01, ..., 05) :  Amber PARM7-formatted parameter file

are contained. XX signifies different initial structures. Note that the initial box length is 300 angs. x 300 angs. x 300 angs. for all the structures.

## Reference
Y. Nara, K. Kasahara*, K. Yagi, K. KIm, N. Matubayasi, H. Kawakami, and M. Tanaka*, under revision.

