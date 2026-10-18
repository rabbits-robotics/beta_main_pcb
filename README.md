# beta_main_pcb

## 役割

Nucleo F303K8 を 1 枚載せる制御基板。CAN 1 系統で首・車輪モータを制御し、射出 ESC、装填モータ、IMU を接続する。

## 主要部品

| 部品 | 型番 | 用途 |
|---|---|---|
| マイコンボード | NUCLEO-F303K8 | 制御 |
| CAN トランシーバ | MCP2562-E/P | CAN 1 系統 |
| モータドライバ | DRV8835 | 装填モータ |
| IMU | BNO055 | 姿勢 |
| 電源コネクタ | AMASS XT30PW-M / XT30PW-F | 外部 DCDC への往復 |
| 6P コネクタ | JST PH × 3 | 電源入力、Yaw モータ、Pitch モータ |
| 射出 ESC | JST PH 2P × 2、XH 2P × 2 | 信号と電源 |
| CAN 終端抵抗 | 120 Ω | |

回路図は [beta_main.pdf](./beta_main.pdf)、部品表は [bom.csv](./bom.csv)、3D は [beta_main.step](./beta_main.step)。

## ライセンス

© Rabbits Robotics、[CERN-OHL-P-2.0](./LICENSE)。
