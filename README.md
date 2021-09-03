# opencore_dell_latitude_5290
Opencore for latitude 5290 (non 2 in 1)


Notes :

------------------------------------
BIOS Latitude_5X90_1.17.0 :

0x3F323 		One Of: CFG Lock, VarStoreInfo (VarOffset/VarName): 0x52D, VarStore: 0x1, QuestionId: 0x30F, Size: 1, Min: 0x0, Max 0x1, Step: 0x0 {05 91 13 03 14 03 0F 03 01 00 2D 05 10 10 00 01 00}
0x3F334 			One Of Option: Disabled, Value (8 bit): 0x0 {09 07 04 00 00 00 00}
0x3F33B 			One Of Option: Enabled, Value (8 bit): 0x1 (default) {09 07 03 00 30 00 01}
0x3F342 		End One Of {29 02}

0x3F344 		One Of: Overclocking Lock, VarStoreInfo (VarOffset/VarName): 0x5DC, VarStore: 0x1, QuestionId: 0x310, Size: 1, Min: 0x0, Max 0x1, Step: 0x0 {05 91 0F 03 10 03 10 03 01 00 DC 05 10 10 00 01 00}
0x3F355 			One Of Option: Disabled, Value (8 bit): 0x0 {09 07 04 00 00 00 00}
0x3F35C 			One Of Option: Enabled, Value (8 bit): 0x1 (default) {09 07 03 00 30 00 01}
0x3F363 		End One Of {29 02}


0x46F39 			One Of: DVMT Pre-Allocated, VarStoreInfo (VarOffset/VarName): 0x804, VarStore: 0x1, QuestionId: 0x273A, Size: 1, Min: 0x0, Max 0xFE, Step: 0x0 {05 91 36 05 49 05 3A 27 01 00 04 08 14 10 00 FE 00}
0x46F4A 				One Of Option: 0M, Value (8 bit): 0x0 {09 07 37 05 00 00 00}
0x46F51 				One Of Option: 32M, Value (8 bit): 0x1 (default) {09 07 38 05 30 00 01}
0x46F58 				One Of Option: 64M, Value (8 bit): 0x2 {09 07 39 05 00 00 02}
0x46F5F 				One Of Option: 4M, Value (8 bit): 0xF0 {09 07 3A 05 00 00 F0}
0x46F66 				One Of Option: 8M, Value (8 bit): 0xF1 {09 07 3B 05 00 00 F1}
0x46F6D 				One Of Option: 12M, Value (8 bit): 0xF2 {09 07 3C 05 00 00 F2}
0x46F74 				One Of Option: 16M, Value (8 bit): 0xF3 {09 07 3D 05 00 00 F3}
0x46F7B 				One Of Option: 20M, Value (8 bit): 0xF4 {09 07 3E 05 00 00 F4}
0x46F82 				One Of Option: 24M, Value (8 bit): 0xF5 {09 07 3F 05 00 00 F5}
0x46F89 				One Of Option: 28M, Value (8 bit): 0xF6 {09 07 40 05 00 00 F6}
0x46F90 				One Of Option: 32M/F7, Value (8 bit): 0xF7 {09 07 41 05 00 00 F7}
0x46F97 				One Of Option: 36M, Value (8 bit): 0xF8 {09 07 42 05 00 00 F8}
0x46F9E 				One Of Option: 40M, Value (8 bit): 0xF9 {09 07 43 05 00 00 F9}
0x46FA5 				One Of Option: 44M, Value (8 bit): 0xFA {09 07 44 05 00 00 FA}
0x46FAC 				One Of Option: 48M, Value (8 bit): 0xFB {09 07 45 05 00 00 FB}
0x46FB3 				One Of Option: 52M, Value (8 bit): 0xFC {09 07 46 05 00 00 FC}
0x46FBA 				One Of Option: 56M, Value (8 bit): 0xFD {09 07 47 05 00 00 FD}
0x46FC1 				One Of Option: 60M, Value (8 bit): 0xFE {09 07 48 05 00 00 FE}
0x46FC8 			End One Of {29 02}
0x46FCA 		End If {29 02}
0x46FCC 		One Of: DVMT Total Gfx Mem, VarStoreInfo (VarOffset/VarName): 0x805, VarStore: 0x1, QuestionId: 0x59E, Size: 1, Min: 0x1, Max 0x3, Step: 0x0 {05 91 4A 05 4B 05 9E 05 01 00 05 08 10 10 01 03 00}
0x46FDD 			One Of Option: 256M, Value (8 bit): 0x2 (default) {09 07 4D 05 30 00 02}
0x46FE4 			One Of Option: 128M, Value (8 bit): 0x1 {09 07 4C 05 00 00 01}
0x46FEB 			One Of Option: MAX, Value (8 bit): 0x3 {09 07 4E 05 00 00 03}
0x46F
------------------------------------
BIOS Latitude_5X90_1.16.0 :

0x3F323 		One Of: CFG Lock, VarStoreInfo (VarOffset/VarName): 0x52D,
0x3F344 		One Of: Overclocking Lock, VarStoreInfo (VarOffset/VarName): 0x5DC


https://github.com/jaromeyer/XPS9570-Catalina/issues/44
