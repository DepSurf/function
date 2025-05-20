# Function: <code>do_SAK</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void do_SAK(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff814dfaa0)
Location: drivers/tty/tty_io.c:3106
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_rx_chars
  - drivers/tty/serial/max310x.c:max310x_port_irq
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
```
**Symbols:**

```
ffffffff814dfaa0-ffffffff814dfac9: do_SAK (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void do_SAK(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81530a60)
Location: drivers/tty/tty_io.c:3115
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_rx_chars
  - drivers/tty/serial/max310x.c:max310x_port_irq
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
```
**Symbols:**

```
ffffffff81530a60-ffffffff81530a89: do_SAK (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void do_SAK(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff8155d1b0)
Location: drivers/tty/tty_io.c:3115
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_rx_chars
  - drivers/tty/serial/max310x.c:max310x_port_irq
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
```
**Symbols:**

```
ffffffff8155d1b0-ffffffff8155d1d9: do_SAK (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void do_SAK(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81572da0)
Location: drivers/tty/tty_io.c:2662
Inline: True
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_rx_chars
  - drivers/tty/serial/max310x.c:max310x_port_irq
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
```
**Symbols:**

```
ffffffff81572da0-ffffffff81572dca: do_SAK (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void do_SAK(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff815d7120)
Location: drivers/tty/tty_io.c:2769
Inline: True
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_rx_chars
  - drivers/tty/serial/max310x.c:max310x_port_irq
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
```
**Symbols:**

```
ffffffff815d7120-ffffffff815d714a: do_SAK (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void do_SAK(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff816100a0)
Location: drivers/tty/tty_io.c:2787
Inline: True
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_read_char
  - drivers/tty/serial/max310x.c:max310x_handle_rx
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
```
**Symbols:**

```
ffffffff816100a0-ffffffff816100c9: do_SAK (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void do_SAK(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff8162cea0)
Location: drivers/tty/tty_io.c:2942
Inline: True
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_read_char
  - drivers/tty/serial/max310x.c:max310x_handle_rx
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
```
**Symbols:**

```
ffffffff8162cea0-ffffffff8162cec9: do_SAK (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void do_SAK(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81660b10)
Location: drivers/tty/tty_io.c:2946
Inline: True
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_read_char
  - drivers/tty/serial/max310x.c:max310x_port_irq
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
```
**Symbols:**

```
ffffffff81660b10-ffffffff81660b39: do_SAK (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void do_SAK(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81683160)
Location: drivers/tty/tty_io.c:2948
Inline: True
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_read_char
  - drivers/tty/serial/max310x.c:max310x_port_irq
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
```
**Symbols:**

```
ffffffff81683160-ffffffff81683189: do_SAK (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void do_SAK(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff817344f0)
Location: drivers/tty/tty_io.c:2951
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_read_char
  - drivers/tty/serial/max310x.c:max310x_handle_rx
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_rx
```
**Symbols:**

```
ffffffff817344f0-ffffffff81734519: do_SAK (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void do_SAK(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81750640)
Location: drivers/tty/tty_io.c:3044
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_read_char
  - drivers/tty/serial/max310x.c:max310x_handle_rx
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_rx
```
**Symbols:**

```
ffffffff81750640-ffffffff81750669: do_SAK (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void do_SAK(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff817344c0)
Location: drivers/tty/tty_io.c:3093
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_read_char
  - drivers/tty/serial/max310x.c:max310x_handle_rx
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_rx
```
**Symbols:**

```
ffffffff817344c0-ffffffff817344e9: do_SAK (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void do_SAK(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff817b4e20)
Location: drivers/tty/tty_io.c:3093
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_read_char
  - drivers/tty/serial/max310x.c:max310x_handle_rx
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_rx
```
**Symbols:**

```
ffffffff817b4e20-ffffffff817b4e49: do_SAK (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void do_SAK(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff818f0d00)
Location: drivers/tty/tty_io.c:3061
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_read_char
  - drivers/tty/serial/max310x.c:max310x_handle_rx
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_rx
```
**Symbols:**

```
ffffffff818f0d00-ffffffff818f0d41: do_SAK (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void do_SAK(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81a48e20)
Location: drivers/tty/tty_io.c:3060
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_read_char
  - drivers/tty/serial/max310x.c:max310x_handle_rx
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_rx
```
**Symbols:**

```
ffffffff81a48e20-ffffffff81a48e61: do_SAK (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void do_SAK(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81a93060)
Location: drivers/tty/tty_io.c:3069
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_read_char
  - drivers/tty/serial/max310x.c:max310x_handle_rx
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_rx
```
**Symbols:**

```
ffffffff81a93060-ffffffff81a930a1: do_SAK (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void do_SAK(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81ae5ab0)
Location: drivers/tty/tty_io.c:3086
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_read_char
  - drivers/tty/serial/max310x.c:max310x_handle_rx
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_rx
```
**Symbols:**

```
ffffffff81ae5ab0-ffffffff81ae5af1: do_SAK (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void do_SAK(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffff80001084f2a0)
Location: drivers/tty/tty_io.c:2948
Inline: True
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_read_char
  - drivers/tty/serial/amba-pl011.c:pl011_fifo_to_tty
  - drivers/tty/serial/max310x.c:max310x_port_irq
  - drivers/tty/serial/imx.c:imx_uart_dma_rx_callback
  - drivers/tty/serial/meson_uart.c:meson_uart_interrupt
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
  - drivers/tty/serial/msm_serial.c:msm_uart_irq
  - drivers/tty/serial/msm_serial.c:msm_uart_irq
  - drivers/tty/serial/msm_serial.c:msm_complete_rx_dma
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_rx_chars
```
**Symbols:**

```
ffff80001084f2a0-ffff80001084f2dc: do_SAK (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void do_SAK(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (c095b5a0)
Location: drivers/tty/tty_io.c:2948
Inline: True
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_read_char
  - drivers/tty/serial/amba-pl011.c:pl011_fifo_to_tty
  - drivers/tty/serial/max310x.c:max310x_port_irq
  - drivers/tty/serial/imx.c:imx_uart_dma_rx_callback
  - drivers/tty/serial/meson_uart.c:meson_uart_interrupt
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
  - drivers/tty/serial/msm_serial.c:msm_uart_irq
  - drivers/tty/serial/msm_serial.c:msm_uart_irq
  - drivers/tty/serial/msm_serial.c:msm_complete_rx_dma
  - drivers/tty/serial/omap-serial.c:serial_omap_irq
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_rx_chars
```
**Symbols:**

```
c095b5a0-c095b5d8: do_SAK (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void do_SAK(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (c0000000008ef6d0)
Location: drivers/tty/tty_io.c:2948
Inline: True
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_read_char
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
```
**Symbols:**

```
c0000000008ef6d0-c0000000008ef720: do_SAK (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void do_SAK(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffe00052dbc2)
Location: drivers/tty/tty_io.c:2948
Inline: True
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_read_char
  - drivers/tty/serial/max310x.c:max310x_port_irq
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
```
**Symbols:**

```
ffffffe00052dbc2-ffffffe00052dbfa: do_SAK (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void do_SAK(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81648be0)
Location: drivers/tty/tty_io.c:2948
Inline: True
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_read_char
  - drivers/tty/serial/max310x.c:max310x_port_irq
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
```
**Symbols:**

```
ffffffff81648be0-ffffffff81648c09: do_SAK (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void do_SAK(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81629040)
Location: drivers/tty/tty_io.c:2948
Inline: True
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_read_char
  - drivers/tty/serial/max310x.c:max310x_port_irq
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
```
**Symbols:**

```
ffffffff81629040-ffffffff81629069: do_SAK (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void do_SAK(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81676fa0)
Location: drivers/tty/tty_io.c:2948
Inline: True
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_read_char
  - drivers/tty/serial/max310x.c:max310x_port_irq
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
```
**Symbols:**

```
ffffffff81676fa0-ffffffff81676fc9: do_SAK (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void do_SAK(struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff816916c0)
Location: drivers/tty/tty_io.c:2948
Inline: True
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_read_char
  - drivers/tty/serial/max310x.c:max310x_port_irq
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
```
**Symbols:**

```
ffffffff816916c0-ffffffff816916e9: do_SAK (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
