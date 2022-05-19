# yavta
 Yet Another V4L2 Test Application
 Fork of yavta from git://git.ideasonboard.org/yavta.git
 
# Modified content

Add 4 types FourCC on Jetson XAVIER and TX2
- Xavier

| Depth | Bit order (X is undefined) | FourCC |
| --- | --- | --- |
| 10 | 0 B9 B8 B7 B6 B5 B4 B3 B2 B1 B0 X X X X X | XY10 |
| 12 | 0 B11 B10 B9 B8 B7 B6 B5 B4 B3 B2 B1 B0 X X X | XY12 |

- TX2

| Depth | Bit order (X is undefined) | FourCC |
| --- | --- | --- |
| 10 | 0 0 B9 B8 B7 B6 B5 B4 B3 B2 B1 B0 X X X X | TY10 |
| 12 | 0 0 B11 B10 B9 B8 B7 B6 B5 B4 B3 B2 B1 B0 X X | TY12 |

