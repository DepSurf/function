# Function: <code>spi_unregister_driver</code>

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
In drivers/tty/serial/max310x.c (ffffffff820afd15)
Location: include/linux/spi/spi.h:264
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_uart_driver_exit
```
```
In drivers/mfd/wm831x-spi.c (ffffffff820b00db)
Location: include/linux/spi/spi.h:264
Inline: True
Inline callers:
  - drivers/mfd/wm831x-spi.c:wm831x_spi_exit
```
```
In drivers/mfd/tps65912-spi.c (ffffffff820b0135)
Location: include/linux/spi/spi.h:264
Inline: True
Inline callers:
  - drivers/mfd/tps65912-spi.c:tps65912_spi_exit
```
```
In drivers/mfd/ezx-pcap.c (ffffffff820b018f)
Location: include/linux/spi/spi.h:264
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:ezx_pcap_exit
```
```
In drivers/mfd/da9052-spi.c (ffffffff820b01c5)
Location: include/linux/spi/spi.h:264
Inline: True
Inline callers:
  - drivers/mfd/da9052-spi.c:da9052_spi_exit
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
In drivers/tty/serial/max310x.c (ffffffff820e7846)
Location: include/linux/spi/spi.h:271
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_uart_exit
```
```
In drivers/mfd/wm831x-spi.c (ffffffff820e7c3d)
Location: include/linux/spi/spi.h:271
Inline: True
Inline callers:
  - drivers/mfd/wm831x-spi.c:wm831x_spi_exit
```
```
In drivers/mfd/tps65912-spi.c (ffffffff820e7c85)
Location: include/linux/spi/spi.h:271
Inline: True
Inline callers:
  - drivers/mfd/tps65912-spi.c:tps65912_spi_driver_exit
```
```
In drivers/mfd/ezx-pcap.c (ffffffff820e7cdf)
Location: include/linux/spi/spi.h:271
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:ezx_pcap_exit
```
```
In drivers/mfd/da9052-spi.c (ffffffff820e7d15)
Location: include/linux/spi/spi.h:271
Inline: True
Inline callers:
  - drivers/mfd/da9052-spi.c:da9052_spi_exit
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
In drivers/tty/serial/max310x.c (ffffffff821cd6fc)
Location: include/linux/spi/spi.h:271
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_uart_exit
```
```
In drivers/mfd/wm831x-spi.c (ffffffff821cda09)
Location: include/linux/spi/spi.h:271
Inline: True
Inline callers:
  - drivers/mfd/wm831x-spi.c:wm831x_spi_exit
```
```
In drivers/mfd/tps65912-spi.c (ffffffff821cda51)
Location: include/linux/spi/spi.h:271
Inline: True
Inline callers:
  - drivers/mfd/tps65912-spi.c:tps65912_spi_driver_exit
```
```
In drivers/mfd/ezx-pcap.c (ffffffff821cda99)
Location: include/linux/spi/spi.h:271
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:ezx_pcap_exit
```
```
In drivers/mfd/da9052-spi.c (ffffffff821cdabd)
Location: include/linux/spi/spi.h:271
Inline: True
Inline callers:
  - drivers/mfd/da9052-spi.c:da9052_spi_exit
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
In drivers/tty/serial/max310x.c (ffffffff822c28c8)
Location: include/linux/spi/spi.h:274
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_uart_exit
```
```
In drivers/mfd/wm831x-spi.c (ffffffff822c2bec)
Location: include/linux/spi/spi.h:274
Inline: True
Inline callers:
  - drivers/mfd/wm831x-spi.c:wm831x_spi_exit
```
```
In drivers/mfd/tps65912-spi.c (ffffffff822c2c34)
Location: include/linux/spi/spi.h:274
Inline: True
Inline callers:
  - drivers/mfd/tps65912-spi.c:tps65912_spi_driver_exit
```
```
In drivers/mfd/ezx-pcap.c (ffffffff822c2c7c)
Location: include/linux/spi/spi.h:274
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:ezx_pcap_exit
```
```
In drivers/mfd/da9052-spi.c (ffffffff822c2ca0)
Location: include/linux/spi/spi.h:274
Inline: True
Inline callers:
  - drivers/mfd/da9052-spi.c:da9052_spi_exit
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
In drivers/tty/serial/max310x.c (ffffffff828d5ae3)
Location: include/linux/spi/spi.h:274
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_uart_exit
```
```
In drivers/mfd/wm831x-spi.c (ffffffff828d5e04)
Location: include/linux/spi/spi.h:274
Inline: True
Inline callers:
  - drivers/mfd/wm831x-spi.c:wm831x_spi_exit
```
```
In drivers/mfd/tps65912-spi.c (ffffffff828d5e4c)
Location: include/linux/spi/spi.h:274
Inline: True
Inline callers:
  - drivers/mfd/tps65912-spi.c:tps65912_spi_driver_exit
```
```
In drivers/mfd/ezx-pcap.c (ffffffff828d5e94)
Location: include/linux/spi/spi.h:274
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:ezx_pcap_exit
```
```
In drivers/mfd/da9052-spi.c (ffffffff828d5eb8)
Location: include/linux/spi/spi.h:274
Inline: True
Inline callers:
  - drivers/mfd/da9052-spi.c:da9052_spi_exit
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
In drivers/tty/serial/max310x.c (ffffffff829073ef)
Location: include/linux/spi/spi.h:274
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_uart_exit
```
```
In drivers/mfd/wm831x-spi.c (ffffffff82907722)
Location: include/linux/spi/spi.h:274
Inline: True
Inline callers:
  - drivers/mfd/wm831x-spi.c:wm831x_spi_exit
```
```
In drivers/mfd/tps65912-spi.c (ffffffff8290776a)
Location: include/linux/spi/spi.h:274
Inline: True
Inline callers:
  - drivers/mfd/tps65912-spi.c:tps65912_spi_driver_exit
```
```
In drivers/mfd/ezx-pcap.c (ffffffff829077b2)
Location: include/linux/spi/spi.h:274
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:ezx_pcap_exit
```
```
In drivers/mfd/da9052-spi.c (ffffffff829077d6)
Location: include/linux/spi/spi.h:274
Inline: True
Inline callers:
  - drivers/mfd/da9052-spi.c:da9052_spi_exit
```
```
In drivers/spi/spi-mem.c (ffffffff81733dc5)
Location: include/linux/spi/spi.h:274
Inline: True
Inline callers:
  - drivers/spi/spi-mem.c:spi_mem_driver_unregister
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
In drivers/tty/serial/max310x.c (ffffffff82adf191)
Location: include/linux/spi/spi.h:269
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_uart_exit
```
```
In drivers/mfd/wm831x-spi.c (ffffffff82adf528)
Location: include/linux/spi/spi.h:269
Inline: True
Inline callers:
  - drivers/mfd/wm831x-spi.c:wm831x_spi_exit
```
```
In drivers/mfd/tps65912-spi.c (ffffffff82adf570)
Location: include/linux/spi/spi.h:269
Inline: True
Inline callers:
  - drivers/mfd/tps65912-spi.c:tps65912_spi_driver_exit
```
```
In drivers/mfd/ezx-pcap.c (ffffffff82adf5b8)
Location: include/linux/spi/spi.h:269
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:ezx_pcap_exit
```
```
In drivers/mfd/da9052-spi.c (ffffffff82adf5dc)
Location: include/linux/spi/spi.h:269
Inline: True
Inline callers:
  - drivers/mfd/da9052-spi.c:da9052_spi_exit
```
```
In drivers/spi/spi-mem.c (ffffffff81756995)
Location: include/linux/spi/spi.h:269
Inline: True
Inline callers:
  - drivers/spi/spi-mem.c:spi_mem_driver_unregister
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
In drivers/tty/serial/max310x.c (ffffffff82b042ce)
Location: include/linux/spi/spi.h:279
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_uart_exit
```
```
In drivers/mfd/tps65912-spi.c (ffffffff82b04638)
Location: include/linux/spi/spi.h:279
Inline: True
Inline callers:
  - drivers/mfd/tps65912-spi.c:tps65912_spi_driver_exit
```
```
In drivers/mfd/ezx-pcap.c (ffffffff82b0466e)
Location: include/linux/spi/spi.h:279
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:ezx_pcap_exit
```
```
In drivers/mfd/da9052-spi.c (ffffffff82b04692)
Location: include/linux/spi/spi.h:279
Inline: True
Inline callers:
  - drivers/mfd/da9052-spi.c:da9052_spi_exit
```
```
In drivers/spi/spi-mem.c (ffffffff81792f55)
Location: include/linux/spi/spi.h:279
Inline: True
Inline callers:
  - drivers/spi/spi-mem.c:spi_mem_driver_unregister
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
In drivers/tty/serial/max310x.c (ffffffff82b131a9)
Location: include/linux/spi/spi.h:279
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_uart_exit
```
```
In drivers/mfd/tps65912-spi.c (ffffffff82b13513)
Location: include/linux/spi/spi.h:279
Inline: True
Inline callers:
  - drivers/mfd/tps65912-spi.c:tps65912_spi_driver_exit
```
```
In drivers/mfd/ezx-pcap.c (ffffffff82b13549)
Location: include/linux/spi/spi.h:279
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:ezx_pcap_exit
```
```
In drivers/mfd/da9052-spi.c (ffffffff82b1356d)
Location: include/linux/spi/spi.h:279
Inline: True
Inline callers:
  - drivers/mfd/da9052-spi.c:da9052_spi_exit
```
```
In drivers/spi/spi-mem.c (ffffffff817b6aa5)
Location: include/linux/spi/spi.h:279
Inline: True
Inline callers:
  - drivers/spi/spi-mem.c:spi_mem_driver_unregister
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
In drivers/tty/serial/max310x.c (ffffffff82f24c42)
Location: include/linux/spi/spi.h:298
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_uart_exit
```
```
In drivers/mfd/tps65912-spi.c (ffffffff82f24fc4)
Location: include/linux/spi/spi.h:298
Inline: True
Inline callers:
  - drivers/mfd/tps65912-spi.c:tps65912_spi_driver_exit
```
```
In drivers/mfd/ezx-pcap.c (ffffffff82f24ffa)
Location: include/linux/spi/spi.h:298
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:ezx_pcap_exit
```
```
In drivers/mfd/da9052-spi.c (ffffffff82f2501e)
Location: include/linux/spi/spi.h:298
Inline: True
Inline callers:
  - drivers/mfd/da9052-spi.c:da9052_spi_exit
```
```
In drivers/spi/spi-mem.c (ffffffff8187d8b5)
Location: include/linux/spi/spi.h:298
Inline: True
Inline callers:
  - drivers/spi/spi-mem.c:spi_mem_driver_unregister
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
In drivers/tty/serial/max310x.c (ffffffff8321d1e2)
Location: include/linux/spi/spi.h:299
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_uart_exit
```
```
In drivers/mfd/tps65912-spi.c (ffffffff8321d538)
Location: include/linux/spi/spi.h:299
Inline: True
Inline callers:
  - drivers/mfd/tps65912-spi.c:tps65912_spi_driver_exit
```
```
In drivers/mfd/ezx-pcap.c (ffffffff8321d56e)
Location: include/linux/spi/spi.h:299
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:ezx_pcap_exit
```
```
In drivers/mfd/da9052-spi.c (ffffffff8321d592)
Location: include/linux/spi/spi.h:299
Inline: True
Inline callers:
  - drivers/mfd/da9052-spi.c:da9052_spi_exit
```
```
In drivers/spi/spi-mem.c (ffffffff8188bde5)
Location: include/linux/spi/spi.h:299
Inline: True
Inline callers:
  - drivers/spi/spi-mem.c:spi_mem_driver_unregister
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
In drivers/tty/serial/max310x.c (ffffffff83451191)
Location: include/linux/spi/spi.h:296
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_uart_exit
```
```
In drivers/mfd/tps65912-spi.c (ffffffff834514f1)
Location: include/linux/spi/spi.h:296
Inline: True
Inline callers:
  - drivers/mfd/tps65912-spi.c:tps65912_spi_driver_exit
```
```
In drivers/mfd/ezx-pcap.c (ffffffff83451527)
Location: include/linux/spi/spi.h:296
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:ezx_pcap_exit
```
```
In drivers/mfd/da9052-spi.c (ffffffff8345154b)
Location: include/linux/spi/spi.h:296
Inline: True
Inline callers:
  - drivers/mfd/da9052-spi.c:da9052_spi_exit
```
```
In drivers/spi/spi-mem.c (ffffffff8186e745)
Location: include/linux/spi/spi.h:296
Inline: True
Inline callers:
  - drivers/spi/spi-mem.c:spi_mem_driver_unregister
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
In drivers/tty/serial/max310x.c (ffffffff8354478b)
Location: include/linux/spi/spi.h:304
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_uart_exit
```
```
In drivers/mfd/tps65912-spi.c (ffffffff83544b20)
Location: include/linux/spi/spi.h:304
Inline: True
Inline callers:
  - drivers/mfd/tps65912-spi.c:tps65912_spi_driver_exit
```
```
In drivers/mfd/ezx-pcap.c (ffffffff83544b56)
Location: include/linux/spi/spi.h:304
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:ezx_pcap_exit
```
```
In drivers/mfd/da9052-spi.c (ffffffff83544b7a)
Location: include/linux/spi/spi.h:304
Inline: True
Inline callers:
  - drivers/mfd/da9052-spi.c:da9052_spi_exit
```
```
In drivers/spi/spi-mem.c (ffffffff818fe7e5)
Location: include/linux/spi/spi.h:304
Inline: True
Inline callers:
  - drivers/spi/spi-mem.c:spi_mem_driver_unregister
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
In drivers/tty/serial/max310x.c (ffffffff837229ce)
Location: include/linux/spi/spi.h:300
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_uart_exit
```
```
In drivers/mfd/tps65912-spi.c (ffffffff83722e36)
Location: include/linux/spi/spi.h:300
Inline: True
Inline callers:
  - drivers/mfd/tps65912-spi.c:tps65912_spi_driver_exit
```
```
In drivers/mfd/ezx-pcap.c (ffffffff83722e7e)
Location: include/linux/spi/spi.h:300
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:ezx_pcap_exit
```
```
In drivers/mfd/da9052-spi.c (ffffffff83722eae)
Location: include/linux/spi/spi.h:300
Inline: True
Inline callers:
  - drivers/mfd/da9052-spi.c:da9052_spi_exit
```
```
In drivers/spi/spi-mem.c (ffffffff81a500e5)
Location: include/linux/spi/spi.h:300
Inline: True
Inline callers:
  - drivers/spi/spi-mem.c:spi_mem_driver_unregister
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
In drivers/tty/serial/max310x.c (ffffffff842b0e80)
Location: include/linux/spi/spi.h:313
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_uart_exit
  - drivers/tty/serial/max310x.c:max310x_uart_init
```
```
In drivers/mfd/tps65912-spi.c (ffffffff842b1580)
Location: include/linux/spi/spi.h:313
Inline: True
Inline callers:
  - drivers/mfd/tps65912-spi.c:tps65912_spi_driver_exit
```
```
In drivers/mfd/ezx-pcap.c (ffffffff842b1610)
Location: include/linux/spi/spi.h:313
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:ezx_pcap_exit
```
```
In drivers/mfd/da9052-spi.c (ffffffff842b1670)
Location: include/linux/spi/spi.h:313
Inline: True
Inline callers:
  - drivers/mfd/da9052-spi.c:da9052_spi_exit
```
```
In drivers/spi/spi-mem.c (ffffffff81bd9225)
Location: include/linux/spi/spi.h:313
Inline: True
Inline callers:
  - drivers/spi/spi-mem.c:spi_mem_driver_unregister
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
In drivers/tty/serial/max310x.c (ffffffff83af3a70)
Location: include/linux/spi/spi.h:344
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_uart_exit
  - drivers/tty/serial/max310x.c:max310x_uart_init
```
```
In drivers/mfd/tps65912-spi.c (ffffffff83af41c0)
Location: include/linux/spi/spi.h:344
Inline: True
Inline callers:
  - drivers/mfd/tps65912-spi.c:tps65912_spi_driver_exit
```
```
In drivers/mfd/ezx-pcap.c (ffffffff83af4250)
Location: include/linux/spi/spi.h:344
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:ezx_pcap_exit
```
```
In drivers/mfd/da9052-spi.c (ffffffff83af42b0)
Location: include/linux/spi/spi.h:344
Inline: True
Inline callers:
  - drivers/mfd/da9052-spi.c:da9052_spi_exit
```
```
In drivers/spi/spi-mem.c (ffffffff81c2fc25)
Location: include/linux/spi/spi.h:344
Inline: True
Inline callers:
  - drivers/spi/spi-mem.c:spi_mem_driver_unregister
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
In drivers/tty/serial/max310x.c (ffffffff83d4f7d0)
Location: include/linux/spi/spi.h:368
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_uart_exit
  - drivers/tty/serial/max310x.c:max310x_uart_init
```
```
In drivers/mfd/tps65912-spi.c (ffffffff83d4fef0)
Location: include/linux/spi/spi.h:368
Inline: True
Inline callers:
  - drivers/mfd/tps65912-spi.c:tps65912_spi_driver_exit
```
```
In drivers/mfd/ezx-pcap.c (ffffffff83d4ff80)
Location: include/linux/spi/spi.h:368
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:ezx_pcap_exit
```
```
In drivers/mfd/da9052-spi.c (ffffffff83d4ffe0)
Location: include/linux/spi/spi.h:368
Inline: True
Inline callers:
  - drivers/mfd/da9052-spi.c:da9052_spi_exit
```
```
In drivers/spi/spi-mem.c (ffffffff81ce2ae5)
Location: include/linux/spi/spi.h:368
Inline: True
Inline callers:
  - drivers/spi/spi-mem.c:spi_mem_driver_unregister
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
In drivers/tty/serial/max310x.c (ffff8000114b982c)
Location: include/linux/spi/spi.h:279
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_uart_exit
```
```
In drivers/mfd/stmpe-spi.c (ffff8000114b9d64)
Location: include/linux/spi/spi.h:279
Inline: True
Inline callers:
  - drivers/mfd/stmpe-spi.c:stmpe_exit
```
```
In drivers/mfd/tps65912-spi.c (ffff8000114b9dbc)
Location: include/linux/spi/spi.h:279
Inline: True
Inline callers:
  - drivers/mfd/tps65912-spi.c:tps65912_spi_driver_exit
```
```
In drivers/mfd/ezx-pcap.c (ffff8000114b9e14)
Location: include/linux/spi/spi.h:279
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:ezx_pcap_exit
```
```
In drivers/mfd/da9052-spi.c (ffff8000114b9e50)
Location: include/linux/spi/spi.h:279
Inline: True
Inline callers:
  - drivers/mfd/da9052-spi.c:da9052_spi_exit
```
```
In drivers/spi/spi-mem.c (ffff8000109ca728)
Location: include/linux/spi/spi.h:279
Inline: True
Inline callers:
  - drivers/spi/spi-mem.c:spi_mem_driver_unregister
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
In drivers/tty/serial/max310x.c (c15bf948)
Location: include/linux/spi/spi.h:279
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_uart_exit
```
```
In drivers/mfd/stmpe-spi.c (c15bfdec)
Location: include/linux/spi/spi.h:279
Inline: True
Inline callers:
  - drivers/mfd/stmpe-spi.c:stmpe_exit
```
```
In drivers/mfd/tps65912-spi.c (c15bfeb0)
Location: include/linux/spi/spi.h:279
Inline: True
Inline callers:
  - drivers/mfd/tps65912-spi.c:tps65912_spi_driver_exit
```
```
In drivers/mfd/ezx-pcap.c (c15bff20)
Location: include/linux/spi/spi.h:279
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:ezx_pcap_exit
```
```
In drivers/mfd/da9052-spi.c (c15bff58)
Location: include/linux/spi/spi.h:279
Inline: True
Inline callers:
  - drivers/mfd/da9052-spi.c:da9052_spi_exit
```
```
In drivers/spi/spi-mem.c (c0ab3d2c)
Location: include/linux/spi/spi.h:279
Inline: True
Inline callers:
  - drivers/spi/spi-mem.c:spi_mem_driver_unregister
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
In drivers/tty/serial/max310x.c (c0000000013cc9f8)
Location: include/linux/spi/spi.h:279
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_uart_exit
```
```
In drivers/mfd/stmpe-spi.c (c0000000013cd100)
Location: include/linux/spi/spi.h:279
Inline: True
Inline callers:
  - drivers/mfd/stmpe-spi.c:stmpe_exit
```
```
In drivers/mfd/tps65912-spi.c (c0000000013cd19c)
Location: include/linux/spi/spi.h:279
Inline: True
Inline callers:
  - drivers/mfd/tps65912-spi.c:tps65912_spi_driver_exit
```
```
In drivers/mfd/ezx-pcap.c (c0000000013cd238)
Location: include/linux/spi/spi.h:279
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:ezx_pcap_exit
```
```
In drivers/mfd/da9052-spi.c (c0000000013cd2a0)
Location: include/linux/spi/spi.h:279
Inline: True
Inline callers:
  - drivers/mfd/da9052-spi.c:da9052_spi_exit
```
```
In drivers/spi/spi-mem.c (c000000000a8c090)
Location: include/linux/spi/spi.h:279
Inline: True
Inline callers:
  - drivers/spi/spi-mem.c:spi_mem_driver_unregister
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
In drivers/tty/serial/max310x.c (ffffffe0000a141a)
Location: include/linux/spi/spi.h:279
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_uart_exit
```
```
In drivers/mfd/stmpe-spi.c (ffffffe0000a183c)
Location: include/linux/spi/spi.h:279
Inline: True
Inline callers:
  - drivers/mfd/stmpe-spi.c:stmpe_exit
```
```
In drivers/mfd/tps65912-spi.c (ffffffe0000a189c)
Location: include/linux/spi/spi.h:279
Inline: True
Inline callers:
  - drivers/mfd/tps65912-spi.c:tps65912_spi_driver_exit
```
```
In drivers/mfd/ezx-pcap.c (ffffffe0000a18fc)
Location: include/linux/spi/spi.h:279
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:ezx_pcap_exit
```
```
In drivers/mfd/da9052-spi.c (ffffffe0000a193c)
Location: include/linux/spi/spi.h:279
Inline: True
Inline callers:
  - drivers/mfd/da9052-spi.c:da9052_spi_exit
```
```
In drivers/spi/spi-mem.c (ffffffe00061a0e4)
Location: include/linux/spi/spi.h:279
Inline: True
Inline callers:
  - drivers/spi/spi-mem.c:spi_mem_driver_unregister
```
```
In drivers/mmc/host/mmc_spi.c (ffffffe0000a2a16)
Location: include/linux/spi/spi.h:279
Inline: True
Inline callers:
  - drivers/mmc/host/mmc_spi.c:mmc_spi_driver_exit
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
In drivers/tty/serial/max310x.c (ffffffff82af3298)
Location: include/linux/spi/spi.h:279
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_uart_exit
```
```
In drivers/mfd/tps65912-spi.c (ffffffff82af35de)
Location: include/linux/spi/spi.h:279
Inline: True
Inline callers:
  - drivers/mfd/tps65912-spi.c:tps65912_spi_driver_exit
```
```
In drivers/mfd/ezx-pcap.c (ffffffff82af35f0)
Location: include/linux/spi/spi.h:279
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:ezx_pcap_exit
```
```
In drivers/mfd/da9052-spi.c (ffffffff82af3602)
Location: include/linux/spi/spi.h:279
Inline: True
Inline callers:
  - drivers/mfd/da9052-spi.c:da9052_spi_exit
```
```
In drivers/spi/spi-mem.c (ffffffff8177b585)
Location: include/linux/spi/spi.h:279
Inline: True
Inline callers:
  - drivers/spi/spi-mem.c:spi_mem_driver_unregister
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
In drivers/tty/serial/max310x.c (ffffffff82ac365d)
Location: include/linux/spi/spi.h:279
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_uart_exit
```
```
In drivers/mfd/tps65912-spi.c (ffffffff82ac3921)
Location: include/linux/spi/spi.h:279
Inline: True
Inline callers:
  - drivers/mfd/tps65912-spi.c:tps65912_spi_driver_exit
```
```
In drivers/mfd/ezx-pcap.c (ffffffff82ac3933)
Location: include/linux/spi/spi.h:279
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:ezx_pcap_exit
```
```
In drivers/mfd/da9052-spi.c (ffffffff82ac3945)
Location: include/linux/spi/spi.h:279
Inline: True
Inline callers:
  - drivers/mfd/da9052-spi.c:da9052_spi_exit
```
```
In drivers/spi/spi-mem.c (ffffffff8175b335)
Location: include/linux/spi/spi.h:279
Inline: True
Inline callers:
  - drivers/spi/spi-mem.c:spi_mem_driver_unregister
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
In drivers/tty/serial/max310x.c (ffffffff82b0e495)
Location: include/linux/spi/spi.h:279
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_uart_exit
```
```
In drivers/mfd/tps65912-spi.c (ffffffff82b0e7ff)
Location: include/linux/spi/spi.h:279
Inline: True
Inline callers:
  - drivers/mfd/tps65912-spi.c:tps65912_spi_driver_exit
```
```
In drivers/mfd/ezx-pcap.c (ffffffff82b0e835)
Location: include/linux/spi/spi.h:279
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:ezx_pcap_exit
```
```
In drivers/mfd/da9052-spi.c (ffffffff82b0e859)
Location: include/linux/spi/spi.h:279
Inline: True
Inline callers:
  - drivers/mfd/da9052-spi.c:da9052_spi_exit
```
```
In drivers/spi/spi-mem.c (ffffffff817ab925)
Location: include/linux/spi/spi.h:279
Inline: True
Inline callers:
  - drivers/spi/spi-mem.c:spi_mem_driver_unregister
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
In drivers/tty/serial/max310x.c (ffffffff82b02fe1)
Location: include/linux/spi/spi.h:279
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_uart_exit
```
```
In drivers/mfd/tps65912-spi.c (ffffffff82b0334b)
Location: include/linux/spi/spi.h:279
Inline: True
Inline callers:
  - drivers/mfd/tps65912-spi.c:tps65912_spi_driver_exit
```
```
In drivers/mfd/ezx-pcap.c (ffffffff82b03381)
Location: include/linux/spi/spi.h:279
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:ezx_pcap_exit
```
```
In drivers/mfd/da9052-spi.c (ffffffff82b033a5)
Location: include/linux/spi/spi.h:279
Inline: True
Inline callers:
  - drivers/mfd/da9052-spi.c:da9052_spi_exit
```
```
In drivers/spi/spi-mem.c (ffffffff817c58b5)
Location: include/linux/spi/spi.h:279
Inline: True
Inline callers:
  - drivers/spi/spi-mem.c:spi_mem_driver_unregister
```
</details>
</li>
</ul>

## Differences
