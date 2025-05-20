# Function: <code>to_spi_device</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap-spi.c (0)
Location: include/linux/spi/spi.h:176
Inline: True
```
```
In drivers/spi/spi.c (ffffffff815e6e35)
Location: include/linux/spi/spi.h:176
Inline: True
Inline callers:
  - drivers/spi/spi.c:__unregister
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap-spi.c (0)
Location: include/linux/spi/spi.h:183
Inline: True
```
```
In drivers/spi/spi.c (0)
Location: include/linux/spi/spi.h:183
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap-spi.c (0)
Location: include/linux/spi/spi.h:183
Inline: True
```
```
In drivers/spi/spi.c (0)
Location: include/linux/spi/spi.h:183
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap-spi.c (0)
Location: include/linux/spi/spi.h:186
Inline: True
```
```
In drivers/spi/spi.c (0)
Location: include/linux/spi/spi.h:186
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap-spi.c (0)
Location: include/linux/spi/spi.h:186
Inline: True
```
```
In drivers/spi/spi.c (ffffffff816f4515)
Location: include/linux/spi/spi.h:186
Inline: True
Inline callers:
  - drivers/spi/spi.c:__unregister
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/max310x.c (ffffffff8163fa11)
Location: include/linux/spi/spi.h:186
Inline: True
```
```
In drivers/base/regmap/regmap-spi.c (ffffffff816a6c05)
Location: include/linux/spi/spi.h:186
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-spi.c:regmap_spi_read
  - drivers/base/regmap/regmap-spi.c:regmap_spi_async_write
  - drivers/base/regmap/regmap-spi.c:regmap_spi_gather_write
  - drivers/base/regmap/regmap-spi.c:regmap_spi_write
```
```
In drivers/spi/spi.c (ffffffff81730f75)
Location: include/linux/spi/spi.h:186
Inline: True
Inline callers:
  - drivers/spi/spi.c:__unregister
  - drivers/spi/spi.c:spi_dev_check
  - drivers/spi/spi.c:spi_drv_shutdown
  - drivers/spi/spi.c:spi_drv_remove
  - drivers/spi/spi.c:spi_drv_probe
  - drivers/spi/spi.c:spi_uevent
  - drivers/spi/spi.c:spi_match_device
  - drivers/spi/spi.c:spi_device_transfers_split_maxsize_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo16_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo15_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo14_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo13_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo12_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo11_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo10_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo9_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo8_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo7_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo6_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo5_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo4_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo3_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo2_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo1_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo0_show
  - drivers/spi/spi.c:spi_device_bytes_tx_show
  - drivers/spi/spi.c:spi_device_bytes_rx_show
  - drivers/spi/spi.c:spi_device_bytes_show
  - drivers/spi/spi.c:spi_device_spi_async_show
  - drivers/spi/spi.c:spi_device_spi_sync_immediate_show
  - drivers/spi/spi.c:spi_device_spi_sync_show
  - drivers/spi/spi.c:spi_device_timedout_show
  - drivers/spi/spi.c:spi_device_errors_show
  - drivers/spi/spi.c:spi_device_transfers_show
  - drivers/spi/spi.c:spi_device_messages_show
  - drivers/spi/spi.c:modalias_show
  - drivers/spi/spi.c:spidev_release
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/max310x.c (ffffffff8165dc21)
Location: include/linux/spi/spi.h:181
Inline: True
```
```
In drivers/base/regmap/regmap-spi.c (ffffffff816c7745)
Location: include/linux/spi/spi.h:181
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-spi.c:regmap_spi_read
  - drivers/base/regmap/regmap-spi.c:regmap_spi_async_write
  - drivers/base/regmap/regmap-spi.c:regmap_spi_gather_write
  - drivers/base/regmap/regmap-spi.c:regmap_spi_write
```
```
In drivers/spi/spi.c (ffffffff81753965)
Location: include/linux/spi/spi.h:181
Inline: True
Inline callers:
  - drivers/spi/spi.c:__unregister
  - drivers/spi/spi.c:spi_dev_check
  - drivers/spi/spi.c:spi_drv_shutdown
  - drivers/spi/spi.c:spi_drv_remove
  - drivers/spi/spi.c:spi_drv_probe
  - drivers/spi/spi.c:spi_uevent
  - drivers/spi/spi.c:spi_match_device
  - drivers/spi/spi.c:spi_device_transfers_split_maxsize_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo16_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo15_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo14_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo13_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo12_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo11_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo10_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo9_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo8_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo7_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo6_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo5_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo4_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo3_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo2_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo1_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo0_show
  - drivers/spi/spi.c:spi_device_bytes_tx_show
  - drivers/spi/spi.c:spi_device_bytes_rx_show
  - drivers/spi/spi.c:spi_device_bytes_show
  - drivers/spi/spi.c:spi_device_spi_async_show
  - drivers/spi/spi.c:spi_device_spi_sync_immediate_show
  - drivers/spi/spi.c:spi_device_spi_sync_show
  - drivers/spi/spi.c:spi_device_timedout_show
  - drivers/spi/spi.c:spi_device_errors_show
  - drivers/spi/spi.c:spi_device_transfers_show
  - drivers/spi/spi.c:spi_device_messages_show
  - drivers/spi/spi.c:driver_override_show
  - drivers/spi/spi.c:driver_override_store
  - drivers/spi/spi.c:modalias_show
  - drivers/spi/spi.c:spidev_release
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/max310x.c (ffffffff81692ae2)
Location: include/linux/spi/spi.h:191
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_batch_read
  - drivers/tty/serial/max310x.c:max310x_batch_write
```
```
In drivers/base/regmap/regmap-spi.c (ffffffff817029f5)
Location: include/linux/spi/spi.h:191
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-spi.c:regmap_spi_read
  - drivers/base/regmap/regmap-spi.c:regmap_spi_async_write
  - drivers/base/regmap/regmap-spi.c:regmap_spi_gather_write
  - drivers/base/regmap/regmap-spi.c:regmap_spi_write
```
```
In drivers/spi/spi.c (ffffffff8178f195)
Location: include/linux/spi/spi.h:191
Inline: True
Inline callers:
  - drivers/spi/spi.c:__unregister
  - drivers/spi/spi.c:spi_dev_check
  - drivers/spi/spi.c:spi_drv_shutdown
  - drivers/spi/spi.c:spi_drv_remove
  - drivers/spi/spi.c:spi_drv_probe
  - drivers/spi/spi.c:spi_uevent
  - drivers/spi/spi.c:spi_match_device
  - drivers/spi/spi.c:spi_device_transfers_split_maxsize_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo16_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo15_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo14_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo13_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo12_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo11_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo10_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo9_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo8_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo7_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo6_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo5_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo4_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo3_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo2_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo1_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo0_show
  - drivers/spi/spi.c:spi_device_bytes_tx_show
  - drivers/spi/spi.c:spi_device_bytes_rx_show
  - drivers/spi/spi.c:spi_device_bytes_show
  - drivers/spi/spi.c:spi_device_spi_async_show
  - drivers/spi/spi.c:spi_device_spi_sync_immediate_show
  - drivers/spi/spi.c:spi_device_spi_sync_show
  - drivers/spi/spi.c:spi_device_timedout_show
  - drivers/spi/spi.c:spi_device_errors_show
  - drivers/spi/spi.c:spi_device_transfers_show
  - drivers/spi/spi.c:spi_device_messages_show
  - drivers/spi/spi.c:driver_override_show
  - drivers/spi/spi.c:driver_override_store
  - drivers/spi/spi.c:modalias_show
  - drivers/spi/spi.c:spidev_release
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/max310x.c (ffffffff816b5682)
Location: include/linux/spi/spi.h:191
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_batch_read
  - drivers/tty/serial/max310x.c:max310x_batch_write
```
```
In drivers/base/regmap/regmap-spi.c (ffffffff81726d45)
Location: include/linux/spi/spi.h:191
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-spi.c:regmap_spi_read
  - drivers/base/regmap/regmap-spi.c:regmap_spi_async_write
  - drivers/base/regmap/regmap-spi.c:regmap_spi_gather_write
  - drivers/base/regmap/regmap-spi.c:regmap_spi_write
```
```
In drivers/spi/spi.c (ffffffff817b2d55)
Location: include/linux/spi/spi.h:191
Inline: True
Inline callers:
  - drivers/spi/spi.c:__unregister
  - drivers/spi/spi.c:spi_dev_check
  - drivers/spi/spi.c:spi_drv_shutdown
  - drivers/spi/spi.c:spi_drv_remove
  - drivers/spi/spi.c:spi_drv_probe
  - drivers/spi/spi.c:spi_uevent
  - drivers/spi/spi.c:spi_match_device
  - drivers/spi/spi.c:spi_device_transfers_split_maxsize_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo16_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo15_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo14_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo13_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo12_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo11_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo10_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo9_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo8_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo7_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo6_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo5_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo4_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo3_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo2_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo1_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo0_show
  - drivers/spi/spi.c:spi_device_bytes_tx_show
  - drivers/spi/spi.c:spi_device_bytes_rx_show
  - drivers/spi/spi.c:spi_device_bytes_show
  - drivers/spi/spi.c:spi_device_spi_async_show
  - drivers/spi/spi.c:spi_device_spi_sync_immediate_show
  - drivers/spi/spi.c:spi_device_spi_sync_show
  - drivers/spi/spi.c:spi_device_timedout_show
  - drivers/spi/spi.c:spi_device_errors_show
  - drivers/spi/spi.c:spi_device_transfers_show
  - drivers/spi/spi.c:spi_device_messages_show
  - drivers/spi/spi.c:driver_override_show
  - drivers/spi/spi.c:driver_override_store
  - drivers/spi/spi.c:modalias_show
  - drivers/spi/spi.c:spidev_release
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/max310x.c (ffffffff817681f8)
Location: include/linux/spi/spi.h:210
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_batch_read
  - drivers/tty/serial/max310x.c:max310x_batch_write
```
```
In drivers/base/regmap/regmap-spi.c (ffffffff817e3315)
Location: include/linux/spi/spi.h:210
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-spi.c:regmap_spi_read
  - drivers/base/regmap/regmap-spi.c:regmap_spi_async_write
  - drivers/base/regmap/regmap-spi.c:regmap_spi_gather_write
  - drivers/base/regmap/regmap-spi.c:regmap_spi_write
```
```
In drivers/spi/spi.c (ffffffff81878715)
Location: include/linux/spi/spi.h:210
Inline: True
Inline callers:
  - drivers/spi/spi.c:__unregister
  - drivers/spi/spi.c:spi_dev_check
  - drivers/spi/spi.c:spi_drv_shutdown
  - drivers/spi/spi.c:spi_drv_remove
  - drivers/spi/spi.c:spi_drv_probe
  - drivers/spi/spi.c:spi_uevent
  - drivers/spi/spi.c:spi_match_device
  - drivers/spi/spi.c:spi_device_transfers_split_maxsize_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo16_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo15_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo14_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo13_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo12_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo11_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo10_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo9_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo8_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo7_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo6_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo5_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo4_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo3_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo2_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo1_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo0_show
  - drivers/spi/spi.c:spi_device_bytes_tx_show
  - drivers/spi/spi.c:spi_device_bytes_rx_show
  - drivers/spi/spi.c:spi_device_bytes_show
  - drivers/spi/spi.c:spi_device_spi_async_show
  - drivers/spi/spi.c:spi_device_spi_sync_immediate_show
  - drivers/spi/spi.c:spi_device_spi_sync_show
  - drivers/spi/spi.c:spi_device_timedout_show
  - drivers/spi/spi.c:spi_device_errors_show
  - drivers/spi/spi.c:spi_device_transfers_show
  - drivers/spi/spi.c:spi_device_messages_show
  - drivers/spi/spi.c:driver_override_show
  - drivers/spi/spi.c:driver_override_store
  - drivers/spi/spi.c:modalias_show
  - drivers/spi/spi.c:spidev_release
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/max310x.c (ffffffff8178303b)
Location: include/linux/spi/spi.h:211
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_batch_read
  - drivers/tty/serial/max310x.c:max310x_batch_write
```
```
In drivers/base/regmap/regmap-spi.c (ffffffff817f7f75)
Location: include/linux/spi/spi.h:211
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-spi.c:regmap_spi_read
  - drivers/base/regmap/regmap-spi.c:regmap_spi_async_write
  - drivers/base/regmap/regmap-spi.c:regmap_spi_gather_write
  - drivers/base/regmap/regmap-spi.c:regmap_spi_write
```
```
In drivers/spi/spi.c (ffffffff81886f85)
Location: include/linux/spi/spi.h:211
Inline: True
Inline callers:
  - drivers/spi/spi.c:__unregister
  - drivers/spi/spi.c:spi_dev_check
  - drivers/spi/spi.c:spi_shutdown
  - drivers/spi/spi.c:spi_remove
  - drivers/spi/spi.c:spi_probe
  - drivers/spi/spi.c:spi_uevent
  - drivers/spi/spi.c:spi_match_device
  - drivers/spi/spi.c:spi_device_transfers_split_maxsize_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo16_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo15_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo14_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo13_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo12_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo11_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo10_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo9_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo8_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo7_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo6_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo5_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo4_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo3_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo2_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo1_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo0_show
  - drivers/spi/spi.c:spi_device_bytes_tx_show
  - drivers/spi/spi.c:spi_device_bytes_rx_show
  - drivers/spi/spi.c:spi_device_bytes_show
  - drivers/spi/spi.c:spi_device_spi_async_show
  - drivers/spi/spi.c:spi_device_spi_sync_immediate_show
  - drivers/spi/spi.c:spi_device_spi_sync_show
  - drivers/spi/spi.c:spi_device_timedout_show
  - drivers/spi/spi.c:spi_device_errors_show
  - drivers/spi/spi.c:spi_device_transfers_show
  - drivers/spi/spi.c:spi_device_messages_show
  - drivers/spi/spi.c:driver_override_show
  - drivers/spi/spi.c:driver_override_store
  - drivers/spi/spi.c:modalias_show
  - drivers/spi/spi.c:spidev_release
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/max310x.c (ffffffff81766932)
Location: include/linux/spi/spi.h:209
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_batch_read
  - drivers/tty/serial/max310x.c:max310x_batch_write
```
```
In drivers/base/regmap/regmap-spi.c (ffffffff817dc705)
Location: include/linux/spi/spi.h:209
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-spi.c:regmap_spi_read
  - drivers/base/regmap/regmap-spi.c:regmap_spi_async_write
  - drivers/base/regmap/regmap-spi.c:regmap_spi_gather_write
  - drivers/base/regmap/regmap-spi.c:regmap_spi_write
```
```
In drivers/spi/spi.c (ffffffff818697e5)
Location: include/linux/spi/spi.h:209
Inline: True
Inline callers:
  - drivers/spi/spi.c:__unregister
  - drivers/spi/spi.c:spi_dev_check
  - drivers/spi/spi.c:spi_shutdown
  - drivers/spi/spi.c:spi_remove
  - drivers/spi/spi.c:spi_probe
  - drivers/spi/spi.c:spi_uevent
  - drivers/spi/spi.c:spi_match_device
  - drivers/spi/spi.c:spi_device_transfers_split_maxsize_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo16_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo15_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo14_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo13_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo12_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo11_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo10_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo9_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo8_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo7_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo6_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo5_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo4_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo3_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo2_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo1_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo0_show
  - drivers/spi/spi.c:spi_device_bytes_tx_show
  - drivers/spi/spi.c:spi_device_bytes_rx_show
  - drivers/spi/spi.c:spi_device_bytes_show
  - drivers/spi/spi.c:spi_device_spi_async_show
  - drivers/spi/spi.c:spi_device_spi_sync_immediate_show
  - drivers/spi/spi.c:spi_device_spi_sync_show
  - drivers/spi/spi.c:spi_device_timedout_show
  - drivers/spi/spi.c:spi_device_errors_show
  - drivers/spi/spi.c:spi_device_transfers_show
  - drivers/spi/spi.c:spi_device_messages_show
  - drivers/spi/spi.c:driver_override_show
  - drivers/spi/spi.c:driver_override_store
  - drivers/spi/spi.c:modalias_show
  - drivers/spi/spi.c:spidev_release
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/max310x.c (ffffffff817eb302)
Location: include/linux/spi/spi.h:217
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_batch_read
  - drivers/tty/serial/max310x.c:max310x_batch_write
```
```
In drivers/base/regmap/regmap-spi.c (ffffffff81868105)
Location: include/linux/spi/spi.h:217
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-spi.c:regmap_spi_read
  - drivers/base/regmap/regmap-spi.c:regmap_spi_async_write
  - drivers/base/regmap/regmap-spi.c:regmap_spi_gather_write
  - drivers/base/regmap/regmap-spi.c:regmap_spi_write
```
```
In drivers/spi/spi.c (ffffffff818f92f5)
Location: include/linux/spi/spi.h:217
Inline: True
Inline callers:
  - drivers/spi/spi.c:__unregister
  - drivers/spi/spi.c:spi_dev_check
  - drivers/spi/spi.c:spi_shutdown
  - drivers/spi/spi.c:spi_remove
  - drivers/spi/spi.c:spi_probe
  - drivers/spi/spi.c:spi_uevent
  - drivers/spi/spi.c:spi_match_device
  - drivers/spi/spi.c:spi_device_transfers_split_maxsize_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo16_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo15_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo14_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo13_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo12_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo11_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo10_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo9_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo8_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo7_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo6_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo5_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo4_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo3_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo2_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo1_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo0_show
  - drivers/spi/spi.c:spi_device_bytes_tx_show
  - drivers/spi/spi.c:spi_device_bytes_rx_show
  - drivers/spi/spi.c:spi_device_bytes_show
  - drivers/spi/spi.c:spi_device_spi_async_show
  - drivers/spi/spi.c:spi_device_spi_sync_immediate_show
  - drivers/spi/spi.c:spi_device_spi_sync_show
  - drivers/spi/spi.c:spi_device_timedout_show
  - drivers/spi/spi.c:spi_device_errors_show
  - drivers/spi/spi.c:spi_device_transfers_show
  - drivers/spi/spi.c:spi_device_messages_show
  - drivers/spi/spi.c:driver_override_show
  - drivers/spi/spi.c:driver_override_store
  - drivers/spi/spi.c:modalias_show
  - drivers/spi/spi.c:spidev_release
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/max310x.c (0)
Location: include/linux/spi/spi.h:213
Inline: True
```
```
In drivers/base/regmap/regmap-spi.c (0)
Location: include/linux/spi/spi.h:213
Inline: True
```
```
In drivers/spi/spi.c (0)
Location: include/linux/spi/spi.h:213
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap-spi.c (0)
Location: include/linux/spi/spi.h:226
Inline: True
```
```
In drivers/spi/spi.c (0)
Location: include/linux/spi/spi.h:226
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap-spi.c (0)
Location: include/linux/spi/spi.h:239
Inline: True
```
```
In drivers/spi/spi.c (0)
Location: include/linux/spi/spi.h:239
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regmap-spi.c (0)
Location: include/linux/spi/spi.h:252
Inline: True
```
```
In drivers/spi/spi.c (0)
Location: include/linux/spi/spi.h:252
Inline: True
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/max310x.c (ffff800010898e9c)
Location: include/linux/spi/spi.h:191
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_batch_read
  - drivers/tty/serial/max310x.c:max310x_batch_write
```
```
In drivers/base/regmap/regmap-spi.c (ffff80001091bf78)
Location: include/linux/spi/spi.h:191
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-spi.c:regmap_spi_read
  - drivers/base/regmap/regmap-spi.c:regmap_spi_async_write
  - drivers/base/regmap/regmap-spi.c:regmap_spi_gather_write
  - drivers/base/regmap/regmap-spi.c:regmap_spi_write
```
```
In drivers/spi/spi.c (ffff8000109c40b0)
Location: include/linux/spi/spi.h:191
Inline: True
Inline callers:
  - drivers/spi/spi.c:__unregister
  - drivers/spi/spi.c:spi_dev_check
  - drivers/spi/spi.c:spi_drv_shutdown
  - drivers/spi/spi.c:spi_drv_remove
  - drivers/spi/spi.c:spi_drv_probe
  - drivers/spi/spi.c:spi_uevent
  - drivers/spi/spi.c:spi_match_device
  - drivers/spi/spi.c:spi_device_transfers_split_maxsize_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo16_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo15_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo14_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo13_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo12_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo11_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo10_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo9_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo8_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo7_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo6_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo5_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo4_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo3_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo2_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo1_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo0_show
  - drivers/spi/spi.c:spi_device_bytes_tx_show
  - drivers/spi/spi.c:spi_device_bytes_rx_show
  - drivers/spi/spi.c:spi_device_bytes_show
  - drivers/spi/spi.c:spi_device_spi_async_show
  - drivers/spi/spi.c:spi_device_spi_sync_immediate_show
  - drivers/spi/spi.c:spi_device_spi_sync_show
  - drivers/spi/spi.c:spi_device_timedout_show
  - drivers/spi/spi.c:spi_device_errors_show
  - drivers/spi/spi.c:spi_device_transfers_show
  - drivers/spi/spi.c:spi_device_messages_show
  - drivers/spi/spi.c:driver_override_show
  - drivers/spi/spi.c:driver_override_store
  - drivers/spi/spi.c:modalias_show
  - drivers/spi/spi.c:spidev_release
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/max310x.c (c0994424)
Location: include/linux/spi/spi.h:191
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_batch_read
  - drivers/tty/serial/max310x.c:max310x_batch_write
```
```
In drivers/base/regmap/regmap-spi.c (c0a017a8)
Location: include/linux/spi/spi.h:191
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-spi.c:regmap_spi_read
  - drivers/base/regmap/regmap-spi.c:regmap_spi_async_write
  - drivers/base/regmap/regmap-spi.c:regmap_spi_gather_write
  - drivers/base/regmap/regmap-spi.c:regmap_spi_write
```
```
In drivers/spi/spi.c (c0aaf464)
Location: include/linux/spi/spi.h:191
Inline: True
Inline callers:
  - drivers/spi/spi.c:__unregister
  - drivers/spi/spi.c:slave_show
  - drivers/spi/spi.c:spi_dev_check
  - drivers/spi/spi.c:spi_drv_shutdown
  - drivers/spi/spi.c:spi_drv_remove
  - drivers/spi/spi.c:spi_drv_probe
  - drivers/spi/spi.c:spi_uevent
  - drivers/spi/spi.c:spi_match_device
  - drivers/spi/spi.c:spi_device_transfers_split_maxsize_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo16_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo15_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo14_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo13_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo12_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo11_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo10_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo9_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo8_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo7_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo6_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo5_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo4_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo3_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo2_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo1_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo0_show
  - drivers/spi/spi.c:spi_device_bytes_tx_show
  - drivers/spi/spi.c:spi_device_bytes_rx_show
  - drivers/spi/spi.c:spi_device_bytes_show
  - drivers/spi/spi.c:spi_device_spi_async_show
  - drivers/spi/spi.c:spi_device_spi_sync_immediate_show
  - drivers/spi/spi.c:spi_device_spi_sync_show
  - drivers/spi/spi.c:spi_device_timedout_show
  - drivers/spi/spi.c:spi_device_errors_show
  - drivers/spi/spi.c:spi_device_transfers_show
  - drivers/spi/spi.c:spi_device_messages_show
  - drivers/spi/spi.c:driver_override_show
  - drivers/spi/spi.c:driver_override_store
  - drivers/spi/spi.c:modalias_show
  - drivers/spi/spi.c:spidev_release
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/max310x.c (0)
Location: include/linux/spi/spi.h:191
Inline: True
```
```
In drivers/base/regmap/regmap-spi.c (c0000000009c06fc)
Location: include/linux/spi/spi.h:191
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-spi.c:regmap_spi_read
  - drivers/base/regmap/regmap-spi.c:regmap_spi_async_write
  - drivers/base/regmap/regmap-spi.c:regmap_spi_gather_write
  - drivers/base/regmap/regmap-spi.c:regmap_spi_write
```
```
In drivers/spi/spi.c (c000000000a85d7c)
Location: include/linux/spi/spi.h:191
Inline: True
Inline callers:
  - drivers/spi/spi.c:__unregister
  - drivers/spi/spi.c:slave_show
  - drivers/spi/spi.c:spi_dev_check
  - drivers/spi/spi.c:spi_drv_shutdown
  - drivers/spi/spi.c:spi_drv_remove
  - drivers/spi/spi.c:spi_drv_probe
  - drivers/spi/spi.c:spi_uevent
  - drivers/spi/spi.c:spi_match_device
  - drivers/spi/spi.c:spi_device_transfers_split_maxsize_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo16_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo15_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo14_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo13_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo12_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo11_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo10_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo9_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo8_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo7_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo6_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo5_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo4_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo3_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo2_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo1_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo0_show
  - drivers/spi/spi.c:spi_device_bytes_tx_show
  - drivers/spi/spi.c:spi_device_bytes_rx_show
  - drivers/spi/spi.c:spi_device_bytes_show
  - drivers/spi/spi.c:spi_device_spi_async_show
  - drivers/spi/spi.c:spi_device_spi_sync_immediate_show
  - drivers/spi/spi.c:spi_device_spi_sync_show
  - drivers/spi/spi.c:spi_device_timedout_show
  - drivers/spi/spi.c:spi_device_errors_show
  - drivers/spi/spi.c:spi_device_transfers_show
  - drivers/spi/spi.c:spi_device_messages_show
  - drivers/spi/spi.c:driver_override_show
  - drivers/spi/spi.c:driver_override_store
  - drivers/spi/spi.c:modalias_show
  - drivers/spi/spi.c:spidev_release
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/max310x.c (0)
Location: include/linux/spi/spi.h:191
Inline: True
```
```
In drivers/base/regmap/regmap-spi.c (0)
Location: include/linux/spi/spi.h:191
Inline: True
```
```
In drivers/spi/spi.c (0)
Location: include/linux/spi/spi.h:191
Inline: True
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/max310x.c (ffffffff8167b0e2)
Location: include/linux/spi/spi.h:191
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_batch_read
  - drivers/tty/serial/max310x.c:max310x_batch_write
```
```
In drivers/base/regmap/regmap-spi.c (ffffffff816ecb25)
Location: include/linux/spi/spi.h:191
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-spi.c:regmap_spi_read
  - drivers/base/regmap/regmap-spi.c:regmap_spi_async_write
  - drivers/base/regmap/regmap-spi.c:regmap_spi_gather_write
  - drivers/base/regmap/regmap-spi.c:regmap_spi_write
```
```
In drivers/spi/spi.c (ffffffff81777835)
Location: include/linux/spi/spi.h:191
Inline: True
Inline callers:
  - drivers/spi/spi.c:__unregister
  - drivers/spi/spi.c:spi_dev_check
  - drivers/spi/spi.c:spi_drv_shutdown
  - drivers/spi/spi.c:spi_drv_remove
  - drivers/spi/spi.c:spi_drv_probe
  - drivers/spi/spi.c:spi_uevent
  - drivers/spi/spi.c:spi_match_device
  - drivers/spi/spi.c:spi_device_transfers_split_maxsize_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo16_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo15_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo14_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo13_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo12_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo11_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo10_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo9_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo8_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo7_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo6_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo5_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo4_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo3_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo2_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo1_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo0_show
  - drivers/spi/spi.c:spi_device_bytes_tx_show
  - drivers/spi/spi.c:spi_device_bytes_rx_show
  - drivers/spi/spi.c:spi_device_bytes_show
  - drivers/spi/spi.c:spi_device_spi_async_show
  - drivers/spi/spi.c:spi_device_spi_sync_immediate_show
  - drivers/spi/spi.c:spi_device_spi_sync_show
  - drivers/spi/spi.c:spi_device_timedout_show
  - drivers/spi/spi.c:spi_device_errors_show
  - drivers/spi/spi.c:spi_device_transfers_show
  - drivers/spi/spi.c:spi_device_messages_show
  - drivers/spi/spi.c:driver_override_show
  - drivers/spi/spi.c:driver_override_store
  - drivers/spi/spi.c:modalias_show
  - drivers/spi/spi.c:spidev_release
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/max310x.c (ffffffff8165a1d2)
Location: include/linux/spi/spi.h:191
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_batch_read
  - drivers/tty/serial/max310x.c:max310x_batch_write
```
```
In drivers/base/regmap/regmap-spi.c (ffffffff816c7165)
Location: include/linux/spi/spi.h:191
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-spi.c:regmap_spi_read
  - drivers/base/regmap/regmap-spi.c:regmap_spi_async_write
  - drivers/base/regmap/regmap-spi.c:regmap_spi_gather_write
  - drivers/base/regmap/regmap-spi.c:regmap_spi_write
```
```
In drivers/spi/spi.c (ffffffff817575e5)
Location: include/linux/spi/spi.h:191
Inline: True
Inline callers:
  - drivers/spi/spi.c:__unregister
  - drivers/spi/spi.c:spi_dev_check
  - drivers/spi/spi.c:spi_drv_shutdown
  - drivers/spi/spi.c:spi_drv_remove
  - drivers/spi/spi.c:spi_drv_probe
  - drivers/spi/spi.c:spi_uevent
  - drivers/spi/spi.c:spi_match_device
  - drivers/spi/spi.c:spi_device_transfers_split_maxsize_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo16_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo15_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo14_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo13_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo12_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo11_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo10_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo9_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo8_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo7_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo6_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo5_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo4_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo3_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo2_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo1_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo0_show
  - drivers/spi/spi.c:spi_device_bytes_tx_show
  - drivers/spi/spi.c:spi_device_bytes_rx_show
  - drivers/spi/spi.c:spi_device_bytes_show
  - drivers/spi/spi.c:spi_device_spi_async_show
  - drivers/spi/spi.c:spi_device_spi_sync_immediate_show
  - drivers/spi/spi.c:spi_device_spi_sync_show
  - drivers/spi/spi.c:spi_device_timedout_show
  - drivers/spi/spi.c:spi_device_errors_show
  - drivers/spi/spi.c:spi_device_transfers_show
  - drivers/spi/spi.c:spi_device_messages_show
  - drivers/spi/spi.c:driver_override_show
  - drivers/spi/spi.c:driver_override_store
  - drivers/spi/spi.c:modalias_show
  - drivers/spi/spi.c:spidev_release
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/max310x.c (ffffffff816a94c2)
Location: include/linux/spi/spi.h:191
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_batch_read
  - drivers/tty/serial/max310x.c:max310x_batch_write
```
```
In drivers/base/regmap/regmap-spi.c (ffffffff8171a205)
Location: include/linux/spi/spi.h:191
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-spi.c:regmap_spi_read
  - drivers/base/regmap/regmap-spi.c:regmap_spi_async_write
  - drivers/base/regmap/regmap-spi.c:regmap_spi_gather_write
  - drivers/base/regmap/regmap-spi.c:regmap_spi_write
```
```
In drivers/spi/spi.c (ffffffff817a7bd5)
Location: include/linux/spi/spi.h:191
Inline: True
Inline callers:
  - drivers/spi/spi.c:__unregister
  - drivers/spi/spi.c:spi_dev_check
  - drivers/spi/spi.c:spi_drv_shutdown
  - drivers/spi/spi.c:spi_drv_remove
  - drivers/spi/spi.c:spi_drv_probe
  - drivers/spi/spi.c:spi_uevent
  - drivers/spi/spi.c:spi_match_device
  - drivers/spi/spi.c:spi_device_transfers_split_maxsize_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo16_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo15_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo14_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo13_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo12_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo11_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo10_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo9_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo8_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo7_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo6_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo5_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo4_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo3_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo2_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo1_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo0_show
  - drivers/spi/spi.c:spi_device_bytes_tx_show
  - drivers/spi/spi.c:spi_device_bytes_rx_show
  - drivers/spi/spi.c:spi_device_bytes_show
  - drivers/spi/spi.c:spi_device_spi_async_show
  - drivers/spi/spi.c:spi_device_spi_sync_immediate_show
  - drivers/spi/spi.c:spi_device_spi_sync_show
  - drivers/spi/spi.c:spi_device_timedout_show
  - drivers/spi/spi.c:spi_device_errors_show
  - drivers/spi/spi.c:spi_device_transfers_show
  - drivers/spi/spi.c:spi_device_messages_show
  - drivers/spi/spi.c:driver_override_show
  - drivers/spi/spi.c:driver_override_store
  - drivers/spi/spi.c:modalias_show
  - drivers/spi/spi.c:spidev_release
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/max310x.c (ffffffff816c3922)
Location: include/linux/spi/spi.h:191
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_batch_read
  - drivers/tty/serial/max310x.c:max310x_batch_write
```
```
In drivers/base/regmap/regmap-spi.c (ffffffff81735565)
Location: include/linux/spi/spi.h:191
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-spi.c:regmap_spi_read
  - drivers/base/regmap/regmap-spi.c:regmap_spi_async_write
  - drivers/base/regmap/regmap-spi.c:regmap_spi_gather_write
  - drivers/base/regmap/regmap-spi.c:regmap_spi_write
```
```
In drivers/spi/spi.c (ffffffff817c1a55)
Location: include/linux/spi/spi.h:191
Inline: True
Inline callers:
  - drivers/spi/spi.c:__unregister
  - drivers/spi/spi.c:spi_dev_check
  - drivers/spi/spi.c:spi_drv_shutdown
  - drivers/spi/spi.c:spi_drv_remove
  - drivers/spi/spi.c:spi_drv_probe
  - drivers/spi/spi.c:spi_uevent
  - drivers/spi/spi.c:spi_match_device
  - drivers/spi/spi.c:spi_device_transfers_split_maxsize_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo16_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo15_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo14_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo13_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo12_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo11_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo10_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo9_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo8_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo7_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo6_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo5_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo4_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo3_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo2_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo1_show
  - drivers/spi/spi.c:spi_device_transfer_bytes_histo0_show
  - drivers/spi/spi.c:spi_device_bytes_tx_show
  - drivers/spi/spi.c:spi_device_bytes_rx_show
  - drivers/spi/spi.c:spi_device_bytes_show
  - drivers/spi/spi.c:spi_device_spi_async_show
  - drivers/spi/spi.c:spi_device_spi_sync_immediate_show
  - drivers/spi/spi.c:spi_device_spi_sync_show
  - drivers/spi/spi.c:spi_device_timedout_show
  - drivers/spi/spi.c:spi_device_errors_show
  - drivers/spi/spi.c:spi_device_transfers_show
  - drivers/spi/spi.c:spi_device_messages_show
  - drivers/spi/spi.c:driver_override_show
  - drivers/spi/spi.c:driver_override_store
  - drivers/spi/spi.c:modalias_show
  - drivers/spi/spi.c:spidev_release
```
</details>
</li>
</ul>

## Differences
