# 一、ekf2文件夹文件---->launch文件夹文件

## 端口值对应表

| :------------- | :------------- | :------------- |
| ---            |      |      |
|  | `SITL_UDP_PRT-value` | `mavlink_udp_port-value` |
| typhoon_h480_1 | 14560 | 14560 |
| typhoon_h480_2 | 14562 | 14562 |
| typhoon_h480_3 | 14563 | 14563 |
| typhoon_h480_4 | 14564 | 14564 |
|                | `The first mavlink start` | `mavlink stream port` |
| typhoon_h480_1 | 14556 | 14556 |
| typhoon_h480_2 | 14557 | 14547 |
| typhoon_h480_3 | 14550 | 14550 |
| typhoon_h480_4 | 14553 | 14553 |
|                | `The second mavlink start` | `fcu_url arg` |
| typhoon_h480_1 | 14557 | 14557 |
| typhoon_h480_2 | 12548 | 14558 |
| typhoon_h480_3 | 14551 | 14551 |
| typhoon_h480_4 | 14554 | 14554 |

# 二、typhoon_h480 启动launch文件名

```
typhoon_h480_mavros_posix_sitl.launch
```

