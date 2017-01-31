##Build Command

kernel:

> ./mk -o=TARGET_BUILD_VARIANT=user htc_816g n k

boot.img:

> ./pack_bootimage.sh

lk.bin:

> ./mk -o=TARGET_BUILD_VARIANT=user htc_816g n lk

## Known information
| Subsystem | Driver name | Availability | Working |
|-----------|-------------|--------------|---------|
| LCM driver #1 | `hx8394d_hd720_dsi_vdo_truly` | Yes | ? |
| LCM driver #2 | `hx8394d_hd720_dsi_vdo_yushun` | yes | ? |
| Modem | `MOLY.WR8.W1315.MD.WG.MP.V34.P21` | ? | ? |
| Touch panel | `mtk-tpd (i2c 0-0048)` | ? | ? |
| GPU | `Mali-450 MP` | YES | ? |
| PMIC #1 | `fan53555 (i2c 4-0060)` | ? | ? |
| PMIC #2 | `ncp6335 (i2c 1-001c)` | YES | ? |
| PMIC #3 | `mt6333 (i2c 1-006b)` | YES | ? |
| PMIC #4 | `tps6128 (i2c 1-0075)` | ? | ? |
| MMC | `emmc` | ? | ? |
| Camera #1 | `ov13850_mipi_raw` | ? | ? |
| Camera #2 | `s5k3l2xx_mipi_raw` | ? | ? |
| Camera #3 | `s5k5e2ya_mipi_raw` | YES | ? |
| Camera #4 | `hi551mipi_raw` | ? | ? |
| Accelerometer | `bma2xx (i2c 2-0018)` | YES | ? |
| ALS/PS | `EPL2182 (i2c 2-0049)` | YES | ? |
| Magnetometer | `mmc6416x (i2c 2-0030)` | ? | ? |
| Charger | `bq24158 (i2c 1-006a)` | YES | ? |
| Flash | `Q7XSAB` | ? | ? |
| Gyroscope | `MPU3050c` | YES | ? |
| Lens #1 | `DW9714AF (i2c 1-0027)` | YES | ? |
| Lens #2 | `DW9761BAF (i2c 1-0018)` | ? | ? |
| Other #1 | `CAM_CAL_DRV (i2c 1-0027)` | ? | ? |
| Other #2 | `kd_camera_hw (i2c 1-007f)` | ? | ? |
| Other #3 | `dummy_eeprom (i2c 1-0050)` | ? | ? |
| RAM | `1 GB LPDDR3` | ? | ? |
| USB | `?` | ? | ? |
| Vibrator | `?` | ? | ? |
| NAND | `?` | ? | ? |
| RTC | `?` | ? | ? |
| Audio | `?` | ? | ? |
| LED | `?` | ? | ? |
| Thermal | `?` | ? | ? |
| Bluetooth | `?` | ? | ? |
| WiFi | `?` | ? | ? |
