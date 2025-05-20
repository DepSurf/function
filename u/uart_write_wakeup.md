# Function: <code>uart_write_wakeup</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void uart_write_wakeup(struct uart_port *port);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff81501100)
Location: drivers/tty/serial/serial_core.c:71
Inline: True
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
  - drivers/tty/serial/8250/8250_dma.c:__dma_tx_complete
  - drivers/tty/serial/max310x.c:max310x_handle_tx
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
```
**Symbols:**

```
ffffffff81501100-ffffffff81501125: uart_write_wakeup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void uart_write_wakeup(struct uart_port *port);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff81551b10)
Location: drivers/tty/serial/serial_core.c:106
Inline: True
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
  - drivers/tty/serial/8250/8250_dma.c:__dma_tx_complete
  - drivers/tty/serial/max310x.c:max310x_handle_tx
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
```
**Symbols:**

```
ffffffff81551b10-ffffffff81551b35: uart_write_wakeup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

```c
void uart_write_wakeup(struct uart_port *port);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff8157e690)
Location: drivers/tty/serial/serial_core.c:107
Inline: True
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
  - drivers/tty/serial/8250/8250_dma.c:__dma_tx_complete
  - drivers/tty/serial/max310x.c:max310x_handle_tx
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
```
**Symbols:**

```
ffffffff8157e690-ffffffff8157e69b: uart_write_wakeup.part.15 (STB_LOCAL)
ffffffff8157e6a0-ffffffff8157e6c1: uart_write_wakeup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
void uart_write_wakeup(struct uart_port *port);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff81592630)
Location: drivers/tty/serial/serial_core.c:108
Inline: True
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
  - drivers/tty/serial/8250/8250_dma.c:__dma_tx_complete
  - drivers/tty/serial/max310x.c:max310x_handle_tx
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
```
**Symbols:**

```
ffffffff81592630-ffffffff8159263b: uart_write_wakeup.part.13 (STB_LOCAL)
ffffffff81592640-ffffffff81592661: uart_write_wakeup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void uart_write_wakeup(struct uart_port *port);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff815f7190)
Location: drivers/tty/serial/serial_core.c:95
Inline: True
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
  - drivers/tty/serial/8250/8250_dma.c:__dma_tx_complete
  - drivers/tty/serial/max310x.c:max310x_handle_tx
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
```
**Symbols:**

```
ffffffff815f7190-ffffffff815f719b: uart_write_wakeup.part.18 (STB_LOCAL)
ffffffff815f71a0-ffffffff815f71c1: uart_write_wakeup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void uart_write_wakeup(struct uart_port *port);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff81630360)
Location: drivers/tty/serial/serial_core.c:95
Inline: True
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
  - drivers/tty/serial/8250/8250_dma.c:__dma_tx_complete
  - drivers/tty/serial/max310x.c:max310x_wq_proc
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
```
**Symbols:**

```
ffffffff81630360-ffffffff8163037e: uart_write_wakeup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void uart_write_wakeup(struct uart_port *port);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff8164e510)
Location: drivers/tty/serial/serial_core.c:95
Inline: True
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
  - drivers/tty/serial/8250/8250_dma.c:__dma_tx_complete
  - drivers/tty/serial/max310x.c:max310x_wq_proc
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
```
**Symbols:**

```
ffffffff8164e510-ffffffff8164e52e: uart_write_wakeup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
void uart_write_wakeup(struct uart_port *port);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff81683090)
Location: drivers/tty/serial/serial_core.c:95
Inline: True
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
  - drivers/tty/serial/8250/8250_dma.c:__dma_tx_complete
  - drivers/tty/serial/max310x.c:max310x_tx_proc
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
```
**Symbols:**

```
ffffffff81683090-ffffffff8168309b: uart_write_wakeup.part.0 (STB_LOCAL)
ffffffff816830a0-ffffffff816830c1: uart_write_wakeup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
void uart_write_wakeup(struct uart_port *port);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff816a5730)
Location: drivers/tty/serial/serial_core.c:96
Inline: True
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
  - drivers/tty/serial/8250/8250_dma.c:__dma_tx_complete
  - drivers/tty/serial/max310x.c:max310x_tx_proc
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
```
**Symbols:**

```
ffffffff816a5730-ffffffff816a573b: uart_write_wakeup.part.0 (STB_LOCAL)
ffffffff816a5740-ffffffff816a5761: uart_write_wakeup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void uart_write_wakeup(struct uart_port *port);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff81757d00)
Location: drivers/tty/serial/serial_core.c:97
Inline: True
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
  - drivers/tty/serial/8250/8250_dma.c:__dma_tx_complete
  - drivers/tty/serial/max310x.c:max310x_handle_tx
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_tx
```
**Symbols:**

```
ffffffff81757d00-ffffffff81757d1e: uart_write_wakeup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void uart_write_wakeup(struct uart_port *port);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff81772dc0)
Location: drivers/tty/serial/serial_core.c:98
Inline: True
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
  - drivers/tty/serial/8250/8250_dma.c:__dma_tx_complete
  - drivers/tty/serial/max310x.c:max310x_handle_tx
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_tx
```
**Symbols:**

```
ffffffff81772dc0-ffffffff81772dde: uart_write_wakeup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void uart_write_wakeup(struct uart_port *port);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff81756830)
Location: drivers/tty/serial/serial_core.c:98
Inline: True
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
  - drivers/tty/serial/8250/8250_dma.c:__dma_tx_complete
  - drivers/tty/serial/max310x.c:max310x_handle_tx
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_tx
```
**Symbols:**

```
ffffffff81756830-ffffffff8175684e: uart_write_wakeup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void uart_write_wakeup(struct uart_port *port);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff817d8e60)
Location: drivers/tty/serial/serial_core.c:98
Inline: True
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
  - drivers/tty/serial/8250/8250_dma.c:__dma_tx_complete
  - drivers/tty/serial/max310x.c:max310x_handle_tx
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_tx
```
**Symbols:**

```
ffffffff817d8e60-ffffffff817d8e7e: uart_write_wakeup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void uart_write_wakeup(struct uart_port *port);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff81917300)
Location: drivers/tty/serial/serial_core.c:104
Inline: True
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
  - drivers/tty/serial/8250/8250_dma.c:__dma_tx_complete
  - drivers/tty/serial/max310x.c:max310x_handle_tx
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_tx
```
**Symbols:**

```
ffffffff81917300-ffffffff81917324: uart_write_wakeup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void uart_write_wakeup(struct uart_port *port);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff81a727a0)
Location: drivers/tty/serial/serial_core.c:111
Inline: True
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
  - drivers/tty/serial/8250/8250_dma.c:__dma_tx_complete
  - drivers/tty/serial/max310x.c:max310x_handle_tx
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_tx
```
**Symbols:**

```
ffffffff81a727a0-ffffffff81a727c4: uart_write_wakeup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void uart_write_wakeup(struct uart_port *port);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff81abd060)
Location: drivers/tty/serial/serial_core.c:112
Inline: True
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
  - drivers/tty/serial/8250/8250_dma.c:__dma_tx_complete
  - drivers/tty/serial/max310x.c:max310x_handle_tx
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_tx
```
**Symbols:**

```
ffffffff81abd060-ffffffff81abd084: uart_write_wakeup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void uart_write_wakeup(struct uart_port *port);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff81b0fe50)
Location: drivers/tty/serial/serial_core.c:112
Inline: True
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
  - drivers/tty/serial/8250/8250_dma.c:__dma_tx_complete
  - drivers/tty/serial/max310x.c:max310x_handle_tx
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_tx
```
**Symbols:**

```
ffffffff81b0fe50-ffffffff81b0fe74: uart_write_wakeup (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

```c
void uart_write_wakeup(struct uart_port *port);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffff80001087da58)
Location: drivers/tty/serial/serial_core.c:96
Inline: True
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
  - drivers/tty/serial/8250/8250_dma.c:__dma_tx_complete
  - drivers/tty/serial/amba-pl011.c:pl011_tx_chars
  - drivers/tty/serial/amba-pl011.c:pl011_dma_tx_refill
  - drivers/tty/serial/max310x.c:max310x_tx_proc
  - drivers/tty/serial/imx.c:imx_uart_int
  - drivers/tty/serial/imx.c:imx_uart_txint
  - drivers/tty/serial/imx.c:imx_uart_dma_tx_callback
  - drivers/tty/serial/meson_uart.c:meson_uart_start_tx
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
  - drivers/tty/serial/msm_serial.c:msm_handle_tx_pio
  - drivers/tty/serial/msm_serial.c:msm_complete_tx_dma
  - drivers/tty/serial/owl-uart.c:owl_uart_irq
```
**Symbols:**

```
ffff80001087da58-ffff80001087da6c: uart_write_wakeup.part.0 (STB_LOCAL)
ffff80001087da70-ffff80001087daa4: uart_write_wakeup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

```c
void uart_write_wakeup(struct uart_port *port);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/serial_core.c (c097f668)
Location: drivers/tty/serial/serial_core.c:96
Inline: True
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
  - drivers/tty/serial/8250/8250_dma.c:__dma_tx_complete
  - drivers/tty/serial/amba-pl011.c:pl011_tx_chars
  - drivers/tty/serial/amba-pl011.c:pl011_dma_tx_refill
  - drivers/tty/serial/max310x.c:max310x_tx_proc
  - drivers/tty/serial/imx.c:imx_uart_int
  - drivers/tty/serial/imx.c:imx_uart_txint
  - drivers/tty/serial/imx.c:imx_uart_dma_tx_callback
  - drivers/tty/serial/meson_uart.c:meson_uart_start_tx
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
  - drivers/tty/serial/msm_serial.c:msm_handle_tx_pio
  - drivers/tty/serial/msm_serial.c:msm_complete_tx_dma
  - drivers/tty/serial/omap-serial.c:serial_omap_irq
  - drivers/tty/serial/owl-uart.c:owl_uart_irq
  - drivers/tty/serial/rda-uart.c:rda_interrupt
```
**Symbols:**

```
c097f668-c097f680: uart_write_wakeup.part.0 (STB_LOCAL)
c097f680-c097f6ac: uart_write_wakeup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void uart_write_wakeup(struct uart_port *port);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (c000000000922c40)
Location: drivers/tty/serial/serial_core.c:96
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
  - drivers/tty/serial/8250/8250_dma.c:__dma_tx_complete
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
```
**Symbols:**

```
c000000000922c40-c000000000922c84: uart_write_wakeup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

```c
void uart_write_wakeup(struct uart_port *port);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffe00054c474)
Location: drivers/tty/serial/serial_core.c:96
Inline: True
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
  - drivers/tty/serial/8250/8250_dma.c:__dma_tx_complete
  - drivers/tty/serial/max310x.c:max310x_tx_proc
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
  - drivers/tty/serial/sifive.c:sifive_serial_irq
```
**Symbols:**

```
ffffffe00054c474-ffffffe00054c488: uart_write_wakeup.part.0 (STB_LOCAL)
ffffffe00054c488-ffffffe00054c4bc: uart_write_wakeup (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
void uart_write_wakeup(struct uart_port *port);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff8166b190)
Location: drivers/tty/serial/serial_core.c:96
Inline: True
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
  - drivers/tty/serial/8250/8250_dma.c:__dma_tx_complete
  - drivers/tty/serial/max310x.c:max310x_tx_proc
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
```
**Symbols:**

```
ffffffff8166b190-ffffffff8166b19b: uart_write_wakeup.part.0 (STB_LOCAL)
ffffffff8166b1a0-ffffffff8166b1c1: uart_write_wakeup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
void uart_write_wakeup(struct uart_port *port);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff8164a300)
Location: drivers/tty/serial/serial_core.c:96
Inline: True
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
  - drivers/tty/serial/8250/8250_dma.c:__dma_tx_complete
  - drivers/tty/serial/max310x.c:max310x_tx_proc
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
```
**Symbols:**

```
ffffffff8164a300-ffffffff8164a30b: uart_write_wakeup.part.0 (STB_LOCAL)
ffffffff8164a310-ffffffff8164a331: uart_write_wakeup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
void uart_write_wakeup(struct uart_port *port);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff81699570)
Location: drivers/tty/serial/serial_core.c:96
Inline: True
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
  - drivers/tty/serial/8250/8250_dma.c:__dma_tx_complete
  - drivers/tty/serial/max310x.c:max310x_tx_proc
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
```
**Symbols:**

```
ffffffff81699570-ffffffff8169957b: uart_write_wakeup.part.0 (STB_LOCAL)
ffffffff81699580-ffffffff816995a1: uart_write_wakeup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
void uart_write_wakeup(struct uart_port *port);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff816b40f0)
Location: drivers/tty/serial/serial_core.c:96
Inline: True
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_tx_chars
  - drivers/tty/serial/8250/8250_dma.c:__dma_tx_complete
  - drivers/tty/serial/max310x.c:max310x_tx_proc
  - drivers/tty/serial/sccnxp.c:sccnxp_handle_events
```
**Symbols:**

```
ffffffff816b40f0-ffffffff816b40fb: uart_write_wakeup.part.0 (STB_LOCAL)
ffffffff816b4100-ffffffff816b4121: uart_write_wakeup (STB_GLOBAL)
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
