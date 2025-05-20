# Function: <code>uart_handle_sysrq_char</code>

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
In drivers/tty/serial/8250/8250_port.c (ffffffff8150806f)
Location: include/linux/serial_core.h:431
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_rx_chars
```
```
In drivers/tty/serial/sccnxp.c (ffffffff8150fc54)
Location: include/linux/serial_core.h:431
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
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
In drivers/tty/serial/8250/8250_port.c (ffffffff81559974)
Location: include/linux/serial_core.h:446
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_rx_chars
```
```
In drivers/tty/serial/sccnxp.c (ffffffff8156219c)
Location: include/linux/serial_core.h:446
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
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
In drivers/tty/serial/8250/8250_port.c (ffffffff81586184)
Location: include/linux/serial_core.h:455
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_rx_chars
```
```
In drivers/tty/serial/sccnxp.c (ffffffff8158e90c)
Location: include/linux/serial_core.h:455
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
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
In drivers/tty/serial/8250/8250_port.c (ffffffff815999c4)
Location: include/linux/serial_core.h:457
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_rx_chars
```
```
In drivers/tty/serial/sccnxp.c (ffffffff815a2bc5)
Location: include/linux/serial_core.h:457
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
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
In drivers/tty/serial/8250/8250_port.c (ffffffff815fe894)
Location: include/linux/serial_core.h:457
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_rx_chars
```
```
In drivers/tty/serial/sccnxp.c (ffffffff81607d75)
Location: include/linux/serial_core.h:457
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
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
In drivers/tty/serial/8250/8250_port.c (ffffffff816381b8)
Location: include/linux/serial_core.h:466
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_read_char
```
```
In drivers/tty/serial/sccnxp.c (ffffffff81641350)
Location: include/linux/serial_core.h:466
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/max310x.c (0)
Location: include/linux/serial_core.h:518
Inline: True
```
```
In drivers/tty/serial/sccnxp.c (ffffffff8165f583)
Location: include/linux/serial_core.h:478
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/max310x.c (0)
Location: include/linux/serial_core.h:505
Inline: True
```
```
In drivers/tty/serial/sccnxp.c (ffffffff81694ba3)
Location: include/linux/serial_core.h:465
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/max310x.c (0)
Location: include/linux/serial_core.h:505
Inline: True
```
```
In drivers/tty/serial/sccnxp.c (ffffffff816b7743)
Location: include/linux/serial_core.h:465
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
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
In drivers/tty/serial/max310x.c (ffffffff8176875d)
Location: include/linux/serial_core.h:471
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_handle_rx
```
```
In drivers/tty/serial/sccnxp.c (ffffffff8176b6dc)
Location: include/linux/serial_core.h:471
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_rx
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
In drivers/tty/serial/max310x.c (ffffffff817834fd)
Location: include/linux/serial_core.h:465
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_handle_rx
```
```
In drivers/tty/serial/sccnxp.c (ffffffff817862bc)
Location: include/linux/serial_core.h:465
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_rx
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
In drivers/tty/serial/max310x.c (ffffffff81766df6)
Location: include/linux/serial_core.h:465
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_handle_rx
```
```
In drivers/tty/serial/sccnxp.c (ffffffff81769c2c)
Location: include/linux/serial_core.h:465
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_rx
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
In drivers/tty/serial/max310x.c (ffffffff817eb7c6)
Location: include/linux/serial_core.h:466
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_handle_rx
```
```
In drivers/tty/serial/sccnxp.c (ffffffff817edb07)
Location: include/linux/serial_core.h:466
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_rx
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
In drivers/tty/serial/max310x.c (ffffffff8192c63e)
Location: include/linux/serial_core.h:475
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_handle_rx
```
```
In drivers/tty/serial/sccnxp.c (ffffffff8192dabf)
Location: include/linux/serial_core.h:475
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_rx
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
In drivers/tty/serial/max310x.c (ffffffff81a88fd8)
Location: include/linux/serial_core.h:914
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_handle_rx
```
```
In drivers/tty/serial/sccnxp.c (ffffffff81a8bd2f)
Location: include/linux/serial_core.h:914
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_rx
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
In drivers/tty/serial/max310x.c (ffffffff81ad46dc)
Location: include/linux/serial_core.h:916
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_handle_rx
```
```
In drivers/tty/serial/sccnxp.c (ffffffff81ad74ff)
Location: include/linux/serial_core.h:916
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_rx
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
In drivers/tty/serial/max310x.c (ffffffff81b27bb3)
Location: include/linux/serial_core.h:1017
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_handle_rx
```
```
In drivers/tty/serial/sccnxp.c (ffffffff81b2a7a9)
Location: include/linux/serial_core.h:1017
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_rx
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/amba-pl011.c (ffff80001089491c)
Location: include/linux/serial_core.h:465
Inline: True
Inline callers:
  - drivers/tty/serial/amba-pl011.c:pl011_fifo_to_tty
```
```
In drivers/tty/serial/max310x.c (0)
Location: include/linux/serial_core.h:505
Inline: True
```
```
In drivers/tty/serial/imx.c (ffff80001089a52c)
Location: include/linux/serial_core.h:465
Inline: True
```
```
In drivers/tty/serial/meson_uart.c (ffff80001089f390)
Location: include/linux/serial_core.h:465
Inline: True
Inline callers:
  - drivers/tty/serial/meson_uart.c:meson_uart_interrupt
```
```
In drivers/tty/serial/sccnxp.c (ffff80001089fde0)
Location: include/linux/serial_core.h:465
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
```
```
In drivers/tty/serial/msm_serial.c (ffff8000108a4058)
Location: include/linux/serial_core.h:465
Inline: True
Inline callers:
  - drivers/tty/serial/msm_serial.c:msm_uart_irq
  - drivers/tty/serial/msm_serial.c:msm_uart_irq
  - drivers/tty/serial/msm_serial.c:msm_complete_rx_dma
```
```
In drivers/tty/serial/mvebu-uart.c (0)
Location: include/linux/serial_core.h:505
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/amba-pl011.c (c098fdbc)
Location: include/linux/serial_core.h:465
Inline: True
Inline callers:
  - drivers/tty/serial/amba-pl011.c:pl011_fifo_to_tty
```
```
In drivers/tty/serial/max310x.c (0)
Location: include/linux/serial_core.h:505
Inline: True
```
```
In drivers/tty/serial/imx.c (c0996218)
Location: include/linux/serial_core.h:465
Inline: True
```
```
In drivers/tty/serial/meson_uart.c (c0998e0c)
Location: include/linux/serial_core.h:465
Inline: True
Inline callers:
  - drivers/tty/serial/meson_uart.c:meson_uart_interrupt
```
```
In drivers/tty/serial/sccnxp.c (c099aaf0)
Location: include/linux/serial_core.h:465
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
```
```
In drivers/tty/serial/msm_serial.c (c099d5cc)
Location: include/linux/serial_core.h:465
Inline: True
Inline callers:
  - drivers/tty/serial/msm_serial.c:msm_uart_irq
  - drivers/tty/serial/msm_serial.c:msm_uart_irq
  - drivers/tty/serial/msm_serial.c:msm_complete_rx_dma
```
```
In drivers/tty/serial/omap-serial.c (c09a09b8)
Location: include/linux/serial_core.h:465
Inline: True
Inline callers:
  - drivers/tty/serial/omap-serial.c:serial_omap_irq
```
```
In drivers/tty/serial/mvebu-uart.c (0)
Location: include/linux/serial_core.h:505
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/max310x.c (0)
Location: include/linux/serial_core.h:505
Inline: True
```
```
In drivers/tty/serial/sccnxp.c (c00000000093d050)
Location: include/linux/serial_core.h:465
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/max310x.c (0)
Location: include/linux/serial_core.h:505
Inline: True
```
```
In drivers/tty/serial/sccnxp.c (ffffffe00055c6e8)
Location: include/linux/serial_core.h:465
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/max310x.c (0)
Location: include/linux/serial_core.h:505
Inline: True
```
```
In drivers/tty/serial/sccnxp.c (ffffffff8167d1a3)
Location: include/linux/serial_core.h:465
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/max310x.c (0)
Location: include/linux/serial_core.h:505
Inline: True
```
```
In drivers/tty/serial/sccnxp.c (ffffffff8165c293)
Location: include/linux/serial_core.h:465
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/max310x.c (0)
Location: include/linux/serial_core.h:505
Inline: True
```
```
In drivers/tty/serial/sccnxp.c (ffffffff816ab583)
Location: include/linux/serial_core.h:465
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/max310x.c (0)
Location: include/linux/serial_core.h:505
Inline: True
```
```
In drivers/tty/serial/sccnxp.c (ffffffff816c59e3)
Location: include/linux/serial_core.h:465
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
```
</details>
</li>
</ul>

## Differences
