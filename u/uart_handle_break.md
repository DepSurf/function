# Function: <code>uart_handle_break</code>

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
In drivers/tty/serial/8250/8250_port.c (ffffffff8150817f)
Location: include/linux/serial_core.h:450
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_rx_chars
```
```
In drivers/tty/serial/max310x.c (ffffffff8150d75f)
Location: include/linux/serial_core.h:450
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_port_irq
```
```
In drivers/tty/serial/sccnxp.c (ffffffff8150ffa5)
Location: include/linux/serial_core.h:450
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
In drivers/tty/serial/8250/8250_port.c (ffffffff81559a96)
Location: include/linux/serial_core.h:465
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_rx_chars
```
```
In drivers/tty/serial/max310x.c (ffffffff8155f9cb)
Location: include/linux/serial_core.h:465
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_port_irq
```
```
In drivers/tty/serial/sccnxp.c (ffffffff81562504)
Location: include/linux/serial_core.h:465
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
In drivers/tty/serial/8250/8250_port.c (ffffffff815862a6)
Location: include/linux/serial_core.h:474
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_rx_chars
```
```
In drivers/tty/serial/max310x.c (ffffffff8158c122)
Location: include/linux/serial_core.h:474
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_port_irq
```
```
In drivers/tty/serial/sccnxp.c (ffffffff8158ec79)
Location: include/linux/serial_core.h:474
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
In drivers/tty/serial/8250/8250_port.c (ffffffff81599aff)
Location: include/linux/serial_core.h:476
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_rx_chars
```
```
In drivers/tty/serial/max310x.c (ffffffff815a026a)
Location: include/linux/serial_core.h:476
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_port_irq
```
```
In drivers/tty/serial/sccnxp.c (ffffffff815a2d0a)
Location: include/linux/serial_core.h:476
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
In drivers/tty/serial/8250/8250_port.c (ffffffff815fe9df)
Location: include/linux/serial_core.h:476
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_rx_chars
```
```
In drivers/tty/serial/max310x.c (ffffffff8160599a)
Location: include/linux/serial_core.h:476
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_port_irq
```
```
In drivers/tty/serial/sccnxp.c (ffffffff81607eba)
Location: include/linux/serial_core.h:476
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
In drivers/tty/serial/8250/8250_port.c (ffffffff81638299)
Location: include/linux/serial_core.h:485
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_read_char
```
```
In drivers/tty/serial/max310x.c (ffffffff8163fe41)
Location: include/linux/serial_core.h:485
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_handle_rx
```
```
In drivers/tty/serial/sccnxp.c (ffffffff81641573)
Location: include/linux/serial_core.h:485
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
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
In drivers/tty/serial/8250/8250_port.c (ffffffff81654943)
Location: include/linux/serial_core.h:531
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_read_char
```
```
In drivers/tty/serial/max310x.c (ffffffff8165e054)
Location: include/linux/serial_core.h:531
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_handle_rx
```
```
In drivers/tty/serial/sccnxp.c (ffffffff8165f6eb)
Location: include/linux/serial_core.h:531
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
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
In drivers/tty/serial/8250/8250_port.c (ffffffff81689337)
Location: include/linux/serial_core.h:518
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_read_char
```
```
In drivers/tty/serial/max310x.c (ffffffff81692d7a)
Location: include/linux/serial_core.h:518
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_port_irq
```
```
In drivers/tty/serial/sccnxp.c (ffffffff81694d08)
Location: include/linux/serial_core.h:518
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
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
In drivers/tty/serial/8250/8250_port.c (ffffffff816aba57)
Location: include/linux/serial_core.h:518
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_read_char
```
```
In drivers/tty/serial/max310x.c (ffffffff816b591a)
Location: include/linux/serial_core.h:518
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_port_irq
```
```
In drivers/tty/serial/sccnxp.c (ffffffff816b78a8)
Location: include/linux/serial_core.h:518
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
In drivers/tty/serial/8250/8250_port.c (ffffffff8175e6ec)
Location: include/linux/serial_core.h:544
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_read_char
```
```
In drivers/tty/serial/max310x.c (ffffffff81768867)
Location: include/linux/serial_core.h:544
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_handle_rx
```
```
In drivers/tty/serial/sccnxp.c (ffffffff8176b83d)
Location: include/linux/serial_core.h:544
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
In drivers/tty/serial/8250/8250_port.c (ffffffff8177956c)
Location: include/linux/serial_core.h:538
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_read_char
```
```
In drivers/tty/serial/max310x.c (ffffffff81783607)
Location: include/linux/serial_core.h:538
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_handle_rx
```
```
In drivers/tty/serial/sccnxp.c (ffffffff8178641d)
Location: include/linux/serial_core.h:538
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
In drivers/tty/serial/8250/8250_port.c (ffffffff8175ce2c)
Location: include/linux/serial_core.h:562
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_read_char
```
```
In drivers/tty/serial/max310x.c (ffffffff81766ef1)
Location: include/linux/serial_core.h:562
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_handle_rx
```
```
In drivers/tty/serial/sccnxp.c (ffffffff81769d7c)
Location: include/linux/serial_core.h:562
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
In drivers/tty/serial/8250/8250_port.c (ffffffff817e0c8c)
Location: include/linux/serial_core.h:563
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_read_char
```
```
In drivers/tty/serial/max310x.c (ffffffff817eb8c1)
Location: include/linux/serial_core.h:563
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_handle_rx
```
```
In drivers/tty/serial/sccnxp.c (ffffffff817edc35)
Location: include/linux/serial_core.h:563
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
In drivers/tty/serial/8250/8250_port.c (ffffffff8191faac)
Location: include/linux/serial_core.h:572
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_read_char
```
```
In drivers/tty/serial/max310x.c (ffffffff8192c749)
Location: include/linux/serial_core.h:572
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_handle_rx
```
```
In drivers/tty/serial/sccnxp.c (ffffffff8192dc14)
Location: include/linux/serial_core.h:572
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
In drivers/tty/serial/8250/8250_port.c (ffffffff81a7c060)
Location: include/linux/serial_core.h:1011
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_read_char
```
```
In drivers/tty/serial/max310x.c (ffffffff81a890d4)
Location: include/linux/serial_core.h:1011
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_handle_rx
```
```
In drivers/tty/serial/sccnxp.c (ffffffff81a8be84)
Location: include/linux/serial_core.h:1011
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
In drivers/tty/serial/8250/8250_port.c (ffffffff81ac735f)
Location: include/linux/serial_core.h:1013
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_read_char
```
```
In drivers/tty/serial/max310x.c (ffffffff81ad47cb)
Location: include/linux/serial_core.h:1013
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_handle_rx
```
```
In drivers/tty/serial/sccnxp.c (ffffffff81ad7666)
Location: include/linux/serial_core.h:1013
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
In drivers/tty/serial/8250/8250_port.c (ffffffff81b1a7e6)
Location: include/linux/serial_core.h:1114
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_read_char
```
```
In drivers/tty/serial/max310x.c (ffffffff81b27ca4)
Location: include/linux/serial_core.h:1114
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_handle_rx
```
```
In drivers/tty/serial/sccnxp.c (ffffffff81b2a92e)
Location: include/linux/serial_core.h:1114
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
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffff800010886598)
Location: include/linux/serial_core.h:518
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_read_char
```
```
In drivers/tty/serial/amba-pl011.c (ffff8000108949f0)
Location: include/linux/serial_core.h:518
Inline: True
Inline callers:
  - drivers/tty/serial/amba-pl011.c:pl011_fifo_to_tty
```
```
In drivers/tty/serial/max310x.c (ffff8000108990fc)
Location: include/linux/serial_core.h:518
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_port_irq
```
```
In drivers/tty/serial/imx.c (ffff80001089dc68)
Location: include/linux/serial_core.h:518
Inline: True
Inline callers:
  - drivers/tty/serial/imx.c:imx_uart_dma_rx_callback
```
```
In drivers/tty/serial/meson_uart.c (ffff80001089f540)
Location: include/linux/serial_core.h:518
Inline: True
Inline callers:
  - drivers/tty/serial/meson_uart.c:meson_uart_interrupt
```
```
In drivers/tty/serial/sccnxp.c (ffff80001089ff28)
Location: include/linux/serial_core.h:518
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
```
```
In drivers/tty/serial/msm_serial.c (ffff8000108a4280)
Location: include/linux/serial_core.h:518
Inline: True
Inline callers:
  - drivers/tty/serial/msm_serial.c:msm_uart_irq
  - drivers/tty/serial/msm_serial.c:msm_uart_irq
  - drivers/tty/serial/msm_serial.c:msm_complete_rx_dma
```
```
In drivers/tty/serial/mvebu-uart.c (ffff8000108a53b4)
Location: include/linux/serial_core.h:518
Inline: True
Inline callers:
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_rx_chars
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
In drivers/tty/serial/8250/8250_port.c (c0984ad0)
Location: include/linux/serial_core.h:518
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_read_char
```
```
In drivers/tty/serial/amba-pl011.c (c098fee8)
Location: include/linux/serial_core.h:518
Inline: True
Inline callers:
  - drivers/tty/serial/amba-pl011.c:pl011_fifo_to_tty
```
```
In drivers/tty/serial/max310x.c (c09946e0)
Location: include/linux/serial_core.h:518
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_port_irq
```
```
In drivers/tty/serial/imx.c (c0995f70)
Location: include/linux/serial_core.h:518
Inline: True
Inline callers:
  - drivers/tty/serial/imx.c:imx_uart_dma_rx_callback
```
```
In drivers/tty/serial/meson_uart.c (c0998f34)
Location: include/linux/serial_core.h:518
Inline: True
Inline callers:
  - drivers/tty/serial/meson_uart.c:meson_uart_interrupt
```
```
In drivers/tty/serial/sccnxp.c (c099ac64)
Location: include/linux/serial_core.h:518
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
```
```
In drivers/tty/serial/msm_serial.c (c099d830)
Location: include/linux/serial_core.h:518
Inline: True
Inline callers:
  - drivers/tty/serial/msm_serial.c:msm_uart_irq
  - drivers/tty/serial/msm_serial.c:msm_uart_irq
  - drivers/tty/serial/msm_serial.c:msm_complete_rx_dma
```
```
In drivers/tty/serial/omap-serial.c (c09a0af0)
Location: include/linux/serial_core.h:518
Inline: True
Inline callers:
  - drivers/tty/serial/omap-serial.c:serial_omap_irq
```
```
In drivers/tty/serial/mvebu-uart.c (c09a2320)
Location: include/linux/serial_core.h:518
Inline: True
Inline callers:
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_rx_chars
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
In drivers/tty/serial/8250/8250_port.c (c00000000092d1c0)
Location: include/linux/serial_core.h:518
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_read_char
```
```
In drivers/tty/serial/max310x.c (0)
Location: include/linux/serial_core.h:518
Inline: False
```
```
In drivers/tty/serial/sccnxp.c (c00000000093d21c)
Location: include/linux/serial_core.h:518
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
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
In drivers/tty/serial/8250/8250_port.c (ffffffe000551808)
Location: include/linux/serial_core.h:518
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_read_char
```
```
In drivers/tty/serial/max310x.c (ffffffe00055bad6)
Location: include/linux/serial_core.h:518
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_port_irq
```
```
In drivers/tty/serial/sccnxp.c (ffffffe00055c9a2)
Location: include/linux/serial_core.h:518
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
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffffffff816714c7)
Location: include/linux/serial_core.h:518
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_read_char
```
```
In drivers/tty/serial/max310x.c (ffffffff8167b37a)
Location: include/linux/serial_core.h:518
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_port_irq
```
```
In drivers/tty/serial/sccnxp.c (ffffffff8167d308)
Location: include/linux/serial_core.h:518
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
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
In drivers/tty/serial/8250/8250_port.c (ffffffff816505c7)
Location: include/linux/serial_core.h:518
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_read_char
```
```
In drivers/tty/serial/max310x.c (ffffffff8165a46a)
Location: include/linux/serial_core.h:518
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_port_irq
```
```
In drivers/tty/serial/sccnxp.c (ffffffff8165c3f8)
Location: include/linux/serial_core.h:518
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
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
In drivers/tty/serial/8250/8250_port.c (ffffffff8169f897)
Location: include/linux/serial_core.h:518
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_read_char
```
```
In drivers/tty/serial/max310x.c (ffffffff816a975a)
Location: include/linux/serial_core.h:518
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_port_irq
```
```
In drivers/tty/serial/sccnxp.c (ffffffff816ab6e8)
Location: include/linux/serial_core.h:518
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
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
In drivers/tty/serial/8250/8250_port.c (ffffffff816b9d57)
Location: include/linux/serial_core.h:518
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_read_char
```
```
In drivers/tty/serial/max310x.c (ffffffff816c3bba)
Location: include/linux/serial_core.h:518
Inline: True
Inline callers:
  - drivers/tty/serial/max310x.c:max310x_port_irq
```
```
In drivers/tty/serial/sccnxp.c (ffffffff816c5b48)
Location: include/linux/serial_core.h:518
Inline: True
Inline callers:
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
```
</details>
</li>
</ul>

## Differences
