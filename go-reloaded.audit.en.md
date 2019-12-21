#### btreetransplant

##### Try with the arguments:
``` root =
01
└── 07
    ├── 12
    │   └── 10
    └── 05
        └── 02
            └── 03
, node = 12 and
repla =
55
├── 60
└── 33
    └── 12
        └── 15
```
```
01
└── 07
    ├── 55
    │   ├── 60
    │   └── 33
    │       └── 12
    │           └── 15
    └── 05
        └── 02
            └── 03
```
###### Does the function returns the value above?
##### Try with the arguments:
``` root =
33
├── 5
│   └── 52
└── 20
    ├── 31
    └── 13
        └── 11
, node = 20 and
repla =
55
├── 60
└── 33
    └── 12
        └── 15
```
```
33
├── 5
│   └── 52
└── 55
    ├── 60
    └── 33
        └── 12
            └── 15
```
###### Does the function returns the value above?
##### Try with the arguments:
``` root =
03
└── 39
    ├── 99
    │   └── 44
    └── 11
        └── 14
            └── 11
, node = 11 and
repla =
55
├── 60
└── 33
    └── 12
        └── 15
```

```
03
└── 39
    ├── 99
    │   └── 44
    └── 55
        ├── 60
        └── 33
            └── 12
                └── 15
```
###### Does the function returns the value above?
##### Try with the arguments:
``` root =
03
├── 03
│   └── 94
│       └── 19
│           ├── 24
│           └── 111
└── 01
, node = 19 and
repla =
55
├── 60
└── 33
    └── 12
        └── 15
```
```
03
├── 03
│   └── 94
│       └── 55
│           ├── 60
│           └── 33
│               └── 12
│                   └── 15
└── 01
```
###### Does the function returns the value above?
##### Try with the arguments:
``` root =
02
├── 03
│   └── 92
│       └── 19
│           ├── 22
│           └── 111
└── 01
, node = 92 and
repla =
55
├── 60
└── 33
    └── 12
        └── 15
```
```
02
├── 03
│   └── 55
│       ├── 60
│       └── 33
│           └── 12
│               └── 15
└── 01
```
###### Does the function returns the value above?
##### Try with the arguments:
```
root = 
00
└── 02
    └── 04
        └── 53
            ├── 66
            └── 23
                └── 21
, node = 21 and
repla =
55
├── 60
└── 33
    └── 12
        └── 15
```
```
00
└── 02
    └── 04
        └── 53
            ├── 66
            └── 23
                └── 55
                    ├── 60
                    └── 33
                        └── 12
                            └── 15
```
###### Does the function returns the value above?
##### Try with the arguments:
```
root = 
02
└── 03
    └── 06
        └── 09
            └── 83
                └── 28
                    └── 24
, node = 06 and
repla =
55
├── 60
└── 33
    └── 12
        └── 15
```
```
02
└── 03
    └── 55
        ├── 60
        └── 33
            └── 12
                └── 15
```
###### Does the function returns the value above?
##### Try with the arguments:
```
root = 
06
├── 07
│   └── 09
│       └── 83
│           └── 68
│               └── 64
└── 01
, node = 06 and
repla =
55
├── 60
└── 33
    └── 12
        └── 15
```
```
55
├── 60
└── 33
    └── 12
        └── 15
```
###### Does the function returns the value above?