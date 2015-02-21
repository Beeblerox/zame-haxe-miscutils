# Firefox 35.0.1 on OsX

## Iteration only

### OldStringMap

```
10 | 740047 per 4009, 727971 per 4009, 897083 per 4001, 903965 per 4001, 908710 per 4001 | avg: 835555 per 4004
100 | 88261 per 4001, 89106 per 4001, 87687 per 4001, 88051 per 4001, 91741 per 4001 | avg: 88969 per 4001
1000 | 4922 per 4001, 6643 per 4001, 9754 per 4001, 10107 per 4001, 9971 per 4001 | avg: 8279 per 4001
10000 | 720 per 4002, 734 per 4002, 743 per 4004, 559 per 4006, 770 per 4003 | avg: 705 per 4003
100000 | 35 per 4060, 35 per 4043, 31 per 4116, 38 per 4026, 38 per 4010 | avg: 35 per 4051
```

### NewStringMap

```
10 | 484513 per 4001, 474990 per 4001, 467309 per 4001, 454900 per 4001, 462002 per 4001 | avg: 468743 per 4001
100 | 76374 per 4001, 77455 per 4001, 76534 per 4001, 78545 per 4001, 76215 per 4001 | avg: 77025 per 4001
1000 | 4862 per 4001, 4896 per 4001, 4869 per 4001, 4332 per 4001, 4888 per 4001 | avg: 4769 per 4001
10000 | 378 per 4008, 374 per 4008, 380 per 4009, 378 per 4005, 378 per 4005 | avg: 378 per 4007
100000 | 19 per 4128, 20 per 4196, 22 per 4142, 21 per 4153, 22 per 4136 | avg: 21 per 4151
```

### FastIteratingStringMap

```
10 | 1891331 per 4001, 1878924 per 4001, 1864361 per 4001, 1890813 per 4001, 2300093 per 4001 | avg: 1965104 per 4001
100 | 269190 per 4001, 269363 per 4001, 270411 per 4001, 270575 per 4001, 271381 per 4001 | avg: 270184 per 4001
1000 | 11383 per 4001, 11318 per 4001, 11293 per 4001, 11279 per 4001, 14422 per 4001 | avg: 11939 per 4001
10000 | 1080 per 4004, 1084 per 4003, 1093 per 4003, 1059 per 4004, 1075 per 4002 | avg: 1078 per 4003
100000 | 75 per 4050, 74 per 4027, 74 per 4018, 74 per 4022, 74 per 4024 | avg: 74 per 4028
```

## Without iteration

### OldStringMap

```
10 | 261074 per 4001, 309792 per 4001, 310279 per 4001, 311004 per 4001, 311466 per 4001 | avg: 300723 per 4001
100 | 25346 per 4001, 25872 per 4001, 23453 per 4001, 22791 per 4001, 24199 per 4001 | avg: 24332 per 4001
1000 | 2406 per 4001, 2162 per 4002, 2127 per 4001, 2162 per 4002, 2214 per 4001 | avg: 2214 per 4001
10000 | 205 per 4010, 205 per 4014, 199 per 4018, 206 per 4014, 203 per 4011 | avg: 204 per 4013
100000 | 16 per 4363, 16 per 4167, 16 per 4073, 16 per 4176, 15 per 4060 | avg: 16 per 4168
```

### NewStringMap

```
10 | 150287 per 4001, 149725 per 4001, 148833 per 4001, 150004 per 4001, 150091 per 4001 | avg: 149788 per 4001
100 | 15189 per 4001, 15197 per 4001, 15198 per 4001, 15207 per 4001, 15221 per 4001 | avg: 15202 per 4001
1000 | 1129 per 4001, 1033 per 4070, 1137 per 4004, 1148 per 4002, 1701 per 4002 | avg: 1230 per 4016
10000 | 155 per 4002, 156 per 4012, 156 per 4005, 156 per 4018, 155 per 4011 | avg: 156 per 4010
100000 | 13 per 4098, 14 per 4138, 14 per 4151, 14 per 4170, 14 per 4155 | avg: 14 per 4142
```

### FastIteratingStringMap

```
10 | 239269 per 4001, 237230 per 4001, 235141 per 4001, 240461 per 4001, 239481 per 4001 | avg: 238316 per 4001
100 | 24085 per 4001, 24070 per 4001, 24022 per 4001, 22449 per 4001, 22193 per 4001 | avg: 23364 per 4001
1000 | 1190 per 4002, 1350 per 4002, 1374 per 4002, 1385 per 4002, 1332 per 4001 | avg: 1326 per 4002
10000 | 117 per 4001, 118 per 4017, 117 per 4023, 118 per 4030, 117 per 4003 | avg: 117 per 4015
100000 | 11 per 4085, 11 per 4089, 11 per 4032, 11 per 4079, 10 per 4067 | avg: 11 per 4070
```

## Combined

### OldStringMap

```
10 | 567463 per 4001, 588454 per 4001, 550649 per 4001, 569126 per 4001, 576747 per 4001 | avg: 570488 per 4001
100 | 50075 per 4001, 67682 per 4001, 70030 per 4001, 70066 per 4001, 70276 per 4001 | avg: 65626 per 4001
1000 | 5390 per 4001, 5617 per 4001, 5514 per 4001, 4441 per 4001, 5563 per 4001 | avg: 5305 per 4001
10000 | 453 per 4008, 356 per 4008, 447 per 4004, 364 per 4006, 455 per 4009 | avg: 415 per 4007
100000 | 25 per 4216, 25 per 4085, 23 per 4004, 25 per 4091, 23 per 4087 | avg: 24 per 4097
```

### NewStringMap

```
10 | 323883 per 4001, 292893 per 4001, 316212 per 4001, 318973 per 4001, 316171 per 4001 | avg: 313626 per 4001
100 | 41473 per 4001, 41639 per 4001, 40607 per 4001, 39631 per 4001, 40174 per 4001 | avg: 40705 per 4001
1000 | 2430 per 4001, 2457 per 4001, 2283 per 4002, 2297 per 4002, 2382 per 4002 | avg: 2370 per 4002
10000 | 196 per 4015, 202 per 4009, 200 per 4002, 201 per 4016, 204 per 4017 | avg: 201 per 4012
100000 | 13 per 4230, 13 per 4229, 13 per 4273, 13 per 4225, 13 per 4252 | avg: 13 per 4242
```

### FastIteratingStringMap

```
10 | 608380 per 4001, 596787 per 4001, 603373 per 4001, 606332 per 4001, 608107 per 4001 | avg: 604596 per 4001
100 | 56310 per 4001, 56013 per 4001, 55974 per 4001, 54812 per 4001, 58892 per 4001 | avg: 56400 per 4001
1000 | 3565 per 4001, 3572 per 4001, 3591 per 4001, 3581 per 4001, 3597 per 4001 | avg: 3581 per 4001
10000 | 289 per 4011, 279 per 4011, 290 per 4013, 290 per 4008, 287 per 4005 | avg: 287 per 4010
100000 | 26 per 4146, 25 per 4018, 25 per 4025, 25 per 4054, 25 per 4017 | avg: 25 per 4052
```

# Done

# Chrome 40.0.2214.111 (64-bit) on OsX

## Iteration only

### OldStringMap

```
10 | 1010326 per 4001, 1018745 per 4001, 1029667 per 4001, 1031197 per 4001, 1023929 per 4001 | avg: 1022773 per 4001
100 | 42974 per 4001, 42900 per 4001, 43100 per 4001, 43071 per 4001, 43068 per 4001 | avg: 43023 per 4001
1000 | 3800 per 4001, 3814 per 4002, 3801 per 4001, 3807 per 4001, 3836 per 4001 | avg: 3812 per 4001
10000 | 335 per 4009, 332 per 4011, 340 per 4011, 333 per 4007, 342 per 4007 | avg: 336 per 4009
100000 | 22 per 4036, 22 per 4021, 22 per 4081, 22 per 4061, 22 per 4044 | avg: 22 per 4049
```

### NewStringMap

```
10 | 413721 per 4001, 417015 per 4001, 413690 per 4001, 408702 per 4001, 414576 per 4001 | avg: 413541 per 4001
100 | 48928 per 4001, 48945 per 4001, 48741 per 4001, 48407 per 4001, 49262 per 4001 | avg: 48857 per 4001
1000 | 4975 per 4001, 5051 per 4001, 5049 per 4001, 5032 per 4001, 5018 per 4001 | avg: 5025 per 4001
10000 | 498 per 4007, 509 per 4006, 513 per 4004, 518 per 4008, 515 per 4007 | avg: 511 per 4006
100000 | 31 per 4057, 30 per 4053, 30 per 4044, 30 per 4045, 30 per 4050 | avg: 30 per 4050
```

### FastIteratingStringMap

```
10 | 5587646 per 4001, 5594492 per 4001, 5553439 per 4001, 5603788 per 4001, 5587706 per 4001 | avg: 5585414 per 4001
100 | 892268 per 4001, 893865 per 4001, 891280 per 4001, 898082 per 4001, 896053 per 4001 | avg: 894310 per 4001
1000 | 95898 per 4001, 96304 per 4001, 95831 per 4001, 96799 per 4001, 95287 per 4001 | avg: 96024 per 4001
10000 | 9664 per 4001, 9645 per 4001, 9622 per 4001, 9649 per 4001, 9676 per 4001 | avg: 9651 per 4001
100000 | 946 per 4002, 949 per 4004, 943 per 4004, 950 per 4001, 955 per 4003 | avg: 949 per 4003
```

## Without iteration

### OldStringMap

```
10 | 286595 per 4001, 285562 per 4001, 285540 per 4001, 286806 per 4001, 284729 per 4001 | avg: 285846 per 4001
100 | 33525 per 4001, 33743 per 4001, 33735 per 4001, 33628 per 4001, 33715 per 4001 | avg: 33669 per 4001
1000 | 3164 per 4001, 3193 per 4001, 3203 per 4001, 3180 per 4001, 3192 per 4001 | avg: 3186 per 4001
10000 | 308 per 4011, 311 per 4011, 310 per 4008, 312 per 4002, 312 per 4008 | avg: 311 per 4008
100000 | 24 per 4155, 25 per 4123, 25 per 4155, 24 per 4074, 24 per 4002 | avg: 24 per 4102
```

### NewStringMap

```
10 | 371087 per 4001, 372149 per 4001, 375117 per 4001, 377640 per 4001, 375768 per 4001 | avg: 374352 per 4001
100 | 39189 per 4001, 39293 per 4001, 39205 per 4001, 39147 per 4001, 39431 per 4001 | avg: 39253 per 4001
1000 | 3960 per 4001, 3989 per 4001, 3825 per 4001, 3936 per 4001, 3970 per 4001 | avg: 3936 per 4001
10000 | 398 per 4010, 397 per 4006, 395 per 4007, 400 per 4006, 397 per 4008 | avg: 397 per 4007
100000 | 39 per 4011, 39 per 4019, 39 per 4049, 39 per 4023, 39 per 4017 | avg: 39 per 4024
```

### FastIteratingStringMap

```
10 | 270688 per 4001, 272670 per 4001, 273425 per 4001, 271849 per 4001, 272133 per 4001 | avg: 272153 per 4001
100 | 28671 per 4001, 28667 per 4001, 28752 per 4001, 28946 per 4001, 28814 per 4001 | avg: 28770 per 4001
1000 | 2871 per 4001, 2887 per 4002, 2894 per 4002, 2915 per 4001, 2919 per 4001 | avg: 2897 per 4001
10000 | 289 per 4012, 288 per 4003, 286 per 4002, 288 per 4005, 288 per 4010 | avg: 288 per 4006
100000 | 29 per 4100, 29 per 4075, 29 per 4097, 29 per 4093, 29 per 4085 | avg: 29 per 4090
```

## Combined

### OldStringMap

```
10 | 399666 per 4001, 396156 per 4001, 398290 per 4001, 395557 per 4001, 396206 per 4001 | avg: 397175 per 4001
100 | 32394 per 4001, 32501 per 4001, 32477 per 4001, 32654 per 4001, 32167 per 4001 | avg: 32439 per 4001
1000 | 2922 per 4001, 2982 per 4002, 2938 per 4001, 2976 per 4001, 2936 per 4001 | avg: 2951 per 4001
10000 | 263 per 4011, 263 per 4002, 264 per 4007, 263 per 4001, 264 per 4003 | avg: 263 per 4005
100000 | 18 per 4124, 18 per 4136, 18 per 4136, 18 per 4096, 18 per 4114 | avg: 18 per 4121
```

### NewStringMap

```
10 | 309074 per 4001, 310939 per 4001, 311018 per 4001, 311783 per 4001, 311465 per 4001 | avg: 310856 per 4001
100 | 35960 per 4001, 36159 per 4001, 36102 per 4001, 36256 per 4001, 36086 per 4001 | avg: 36113 per 4001
1000 | 3651 per 4001, 3687 per 4001, 3669 per 4001, 3710 per 4001, 3614 per 4001 | avg: 3666 per 4001
10000 | 364 per 4001, 371 per 4004, 371 per 4009, 371 per 4009, 371 per 4010 | avg: 370 per 4007
100000 | 25 per 4048, 25 per 4030, 25 per 4006, 25 per 4021, 25 per 4041 | avg: 25 per 4029
```

### FastIteratingStringMap

```
10 | 915467 per 4001, 925161 per 4001, 914723 per 4001, 915599 per 4001, 922113 per 4001 | avg: 918613 per 4001
100 | 98905 per 4001, 98302 per 4001, 99406 per 4001, 99002 per 4001, 99677 per 4001 | avg: 99058 per 4001
1000 | 9922 per 4001, 10018 per 4001, 10064 per 4001, 10052 per 4001, 9998 per 4001 | avg: 10011 per 4001
10000 | 1001 per 4003, 998 per 4004, 999 per 4004, 1001 per 4001, 1002 per 4003 | avg: 1000 per 4003
100000 | 98 per 4022, 99 per 4012, 99 per 4024, 99 per 4033, 99 per 4036 | avg: 99 per 4025
```

# Done

# Safari 8.0.3 on OsX

## Iteration only

### OldStringMap

```
10 | 588938 per 4001, 634579 per 4001, 631419 per 4001, 614492 per 4001, 631127 per 4001 | avg: 620111 per 4001
100 | 37009 per 4001, 38254 per 4001, 38331 per 4001, 37674 per 4001, 37605 per 4001 | avg: 37775 per 4001
1000 | 3662 per 4001, 3590 per 4001, 3564 per 4001, 3414 per 4001, 3436 per 4001 | avg: 3533 per 4001
10000 | 252 per 4012, 249 per 4007, 249 per 4011, 247 per 4001, 255 per 4012 | avg: 250 per 4009
100000 | 19 per 4011, 19 per 4049, 20 per 4176, 20 per 4184, 19 per 4099 | avg: 19 per 4104
```

### NewStringMap

```
10 | 399540 per 4001, 420937 per 4001, 432366 per 4001, 419593 per 4001, 423607 per 4001 | avg: 419209 per 4001
100 | 44341 per 4001, 43626 per 4001, 44671 per 4001, 44505 per 4001, 44572 per 4001 | avg: 44343 per 4001
1000 | 3666 per 4001, 3596 per 4001, 3527 per 4001, 3674 per 4001, 3709 per 4001 | avg: 3634 per 4001
10000 | 304 per 4009, 304 per 4006, 300 per 4010, 305 per 4007, 307 per 4003 | avg: 304 per 4007
100000 | 24 per 4024, 24 per 4026, 24 per 4017, 24 per 4083, 24 per 4095 | avg: 24 per 4049
```

### FastIteratingStringMap

```
10 | 1468369 per 4001, 1398653 per 4001, 1266476 per 4001, 1695254 per 4001, 1669696 per 4001 | avg: 1499690 per 4001
100 | 157813 per 4001, 198687 per 4001, 199920 per 4001, 211109 per 4001, 200298 per 4001 | avg: 193565 per 4001
1000 | 22986 per 4001, 22724 per 4001, 22925 per 4001, 22619 per 4001, 22737 per 4001 | avg: 22798 per 4001
10000 | 2271 per 4001, 2283 per 4002, 2277 per 4001, 2261 per 4001, 2276 per 4001 | avg: 2274 per 4001
100000 | 226 per 4008, 207 per 4003, 210 per 4008, 209 per 4013, 208 per 4014 | avg: 212 per 4009
```

## Without iteration

### OldStringMap

```
10 | 285091 per 4001, 289354 per 4001, 293540 per 4001, 291603 per 4001, 291471 per 4001 | avg: 290212 per 4001
100 | 27584 per 4001, 27436 per 4001, 27417 per 4001, 27367 per 4001, 27356 per 4001 | avg: 27432 per 4001
1000 | 2608 per 4001, 2612 per 4001, 2536 per 4002, 2338 per 4001, 2494 per 4002 | avg: 2518 per 4001
10000 | 207 per 4003, 210 per 4012, 207 per 4012, 208 per 4012, 207 per 4018 | avg: 208 per 4011
100000 | 18 per 4075, 18 per 4011, 19 per 4217, 19 per 4200, 18 per 4053 | avg: 18 per 4111
```

### NewStringMap

```
10 | 409856 per 4001, 408020 per 4001, 409802 per 4001, 413224 per 4001, 415406 per 4001 | avg: 411262 per 4001
100 | 42865 per 4001, 38110 per 4001, 37573 per 4001, 38344 per 4001, 38154 per 4001 | avg: 39009 per 4001
1000 | 4281 per 4001, 2569 per 4001, 2611 per 4001, 2569 per 4001, 4388 per 4001 | avg: 3284 per 4001
10000 | 383 per 4003, 380 per 4001, 256 per 4010, 249 per 4005, 246 per 4008 | avg: 303 per 4005
100000 | 39 per 4024, 39 per 4014, 39 per 4069, 39 per 4017, 40 per 4083 | avg: 39 per 4041
```

### FastIteratingStringMap

```
10 | 244888 per 4001, 243173 per 4001, 246919 per 4001, 246811 per 4001, 246486 per 4001 | avg: 245655 per 4001
100 | 24854 per 4001, 22214 per 4001, 22265 per 4001, 22411 per 4001, 22403 per 4001 | avg: 22829 per 4001
1000 | 2480 per 4002, 1541 per 4001, 1527 per 4004, 1524 per 4001, 2492 per 4001 | avg: 1913 per 4002
10000 | 218 per 4017, 217 per 4012, 149 per 4026, 148 per 4016, 214 per 4016 | avg: 189 per 4017
100000 | 23 per 4113, 23 per 4140, 23 per 4099, 23 per 4123, 23 per 4153 | avg: 23 per 4126
```

## Combined

### OldStringMap

```
10 | 376490 per 4001, 378600 per 4001, 380655 per 4001, 379791 per 4001, 377336 per 4001 | avg: 378574 per 4001
100 | 26378 per 4001, 26307 per 4001, 25587 per 4001, 25754 per 4001, 25297 per 4001 | avg: 25865 per 4001
1000 | 2401 per 4001, 2357 per 4001, 2285 per 4002, 2276 per 4001, 2281 per 4001 | avg: 2320 per 4001
10000 | 184 per 4015, 179 per 4015, 176 per 4013, 173 per 4014, 173 per 4023 | avg: 177 per 4016
100000 | 14 per 4197, 14 per 4186, 14 per 4294, 14 per 4233, 14 per 4104 | avg: 14 per 4203
```

### NewStringMap

```
10 | 278011 per 4001, 289563 per 4001, 288411 per 4001, 304403 per 4001, 309020 per 4001 | avg: 293882 per 4001
100 | 31021 per 4001, 30994 per 4001, 29731 per 4001, 29990 per 4001, 29606 per 4001 | avg: 30268 per 4001
1000 | 2718 per 4001, 2694 per 4001, 2763 per 4001, 2746 per 4001, 2741 per 4001 | avg: 2732 per 4001
10000 | 231 per 4014, 233 per 4009, 233 per 4002, 228 per 4005, 230 per 4012 | avg: 231 per 4008
100000 | 19 per 4102, 19 per 4198, 18 per 4109, 18 per 4028, 19 per 4090 | avg: 19 per 4105
```

### FastIteratingStringMap

```
10 | 573134 per 4001, 604753 per 4001, 519704 per 4001, 605582 per 4001, 612634 per 4001 | avg: 583161 per 4001
100 | 55706 per 4001, 64822 per 4001, 59960 per 4001, 60370 per 4001, 59362 per 4001 | avg: 60044 per 4001
1000 | 6770 per 4001, 6721 per 4001, 6659 per 4001, 6698 per 4001, 6761 per 4001 | avg: 6722 per 4001
10000 | 671 per 4002, 674 per 4005, 672 per 4001, 656 per 4006, 636 per 4005 | avg: 662 per 4004
100000 | 60 per 4016, 61 per 4005, 61 per 4010, 61 per 4022, 61 per 4007 | avg: 61 per 4012
```

# Done