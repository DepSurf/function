# Function: <code>uart_get_baud_rate</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
unsigned int uart_get_baud_rate(struct uart_port *port, struct ktermios *termios, struct ktermios *old, unsigned int min, unsigned int max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff814ffdd0)
Location: drivers/tty/serial/serial_core.c:335
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/max310x.c:max310x_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
```
**Symbols:**

```
ffffffff814ffdd0-ffffffff814fff20: uart_get_baud_rate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
unsigned int uart_get_baud_rate(struct uart_port *port, struct ktermios *termios, struct ktermios *old, unsigned int min, unsigned int max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff815507c0)
Location: drivers/tty/serial/serial_core.c:373
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/max310x.c:max310x_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
```
**Symbols:**

```
ffffffff815507c0-ffffffff81550910: uart_get_baud_rate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
unsigned int uart_get_baud_rate(struct uart_port *port, struct ktermios *termios, struct ktermios *old, unsigned int min, unsigned int max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff8157d040)
Location: drivers/tty/serial/serial_core.c:365
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/max310x.c:max310x_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
```
**Symbols:**

```
ffffffff8157d040-ffffffff8157d190: uart_get_baud_rate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
unsigned int uart_get_baud_rate(struct uart_port *port, struct ktermios *termios, struct ktermios *old, unsigned int min, unsigned int max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff815912a0)
Location: drivers/tty/serial/serial_core.c:366
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/max310x.c:max310x_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
```
**Symbols:**

```
ffffffff815912a0-ffffffff815913d6: uart_get_baud_rate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
unsigned int uart_get_baud_rate(struct uart_port *port, struct ktermios *termios, struct ktermios *old, unsigned int min, unsigned int max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff815f5d60)
Location: drivers/tty/serial/serial_core.c:374
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/max310x.c:max310x_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
```
**Symbols:**

```
ffffffff815f5d60-ffffffff815f5e96: uart_get_baud_rate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
unsigned int uart_get_baud_rate(struct uart_port *port, struct ktermios *termios, struct ktermios *old, unsigned int min, unsigned int max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff8162ef50)
Location: drivers/tty/serial/serial_core.c:381
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/max310x.c:max310x_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
```
**Symbols:**

```
ffffffff8162ef50-ffffffff8162f084: uart_get_baud_rate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
unsigned int uart_get_baud_rate(struct uart_port *port, struct ktermios *termios, struct ktermios *old, unsigned int min, unsigned int max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff8164d0d0)
Location: drivers/tty/serial/serial_core.c:394
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/max310x.c:max310x_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
```
**Symbols:**

```
ffffffff8164d0d0-ffffffff8164d204: uart_get_baud_rate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
unsigned int uart_get_baud_rate(struct uart_port *port, struct ktermios *termios, struct ktermios *old, unsigned int min, unsigned int max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/serial_core.c (0)
Location: drivers/tty/serial/serial_core.c:391
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/max310x.c:max310x_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
```
**Symbols:**

```
ffffffff81686dc9-ffffffff81686dde: uart_get_baud_rate.cold (STB_LOCAL)
ffffffff81681c00-ffffffff81681d33: uart_get_baud_rate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
unsigned int uart_get_baud_rate(struct uart_port *port, struct ktermios *termios, struct ktermios *old, unsigned int min, unsigned int max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff816a42b0)
Location: drivers/tty/serial/serial_core.c:392
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/max310x.c:max310x_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
```
**Symbols:**

```
ffffffff816a42b0-ffffffff816a43ce: uart_get_baud_rate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
unsigned int uart_get_baud_rate(struct uart_port *port, struct ktermios *termios, struct ktermios *old, unsigned int min, unsigned int max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff81756b60)
Location: drivers/tty/serial/serial_core.c:393
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_restore
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/max310x.c:max310x_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
```
**Symbols:**

```
ffffffff81756b60-ffffffff81756c7e: uart_get_baud_rate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
unsigned int uart_get_baud_rate(struct uart_port *port, struct ktermios *termios, struct ktermios *old, unsigned int min, unsigned int max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff81771ce0)
Location: drivers/tty/serial/serial_core.c:394
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_restore
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_port.c:serial8250_update_uartclk
  - drivers/tty/serial/max310x.c:max310x_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
```
**Symbols:**

```
ffffffff81771ce0-ffffffff81771dfe: uart_get_baud_rate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
unsigned int uart_get_baud_rate(struct uart_port *port, struct ktermios *termios, struct ktermios *old, unsigned int min, unsigned int max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff817557a0)
Location: drivers/tty/serial/serial_core.c:394
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_port.c:serial8250_update_uartclk
  - drivers/tty/serial/max310x.c:max310x_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
```
**Symbols:**

```
ffffffff817557a0-ffffffff817558be: uart_get_baud_rate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
unsigned int uart_get_baud_rate(struct uart_port *port, struct ktermios *termios, struct ktermios *old, unsigned int min, unsigned int max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff817d8ec0)
Location: drivers/tty/serial/serial_core.c:377
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_port.c:serial8250_update_uartclk
  - drivers/tty/serial/max310x.c:max310x_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
```
**Symbols:**

```
ffffffff817d8ec0-ffffffff817d8fde: uart_get_baud_rate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
unsigned int uart_get_baud_rate(struct uart_port *port, struct ktermios *termios, struct ktermios *old, unsigned int min, unsigned int max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff819173a0)
Location: drivers/tty/serial/serial_core.c:377
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_port.c:serial8250_update_uartclk
  - drivers/tty/serial/max310x.c:max310x_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
```
**Symbols:**

```
ffffffff819173a0-ffffffff819174ea: uart_get_baud_rate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
unsigned int uart_get_baud_rate(struct uart_port *port, struct ktermios *termios, const struct ktermios *old, unsigned int min, unsigned int max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff81a72840)
Location: drivers/tty/serial/serial_core.c:377
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_port.c:serial8250_update_uartclk
  - drivers/tty/serial/max310x.c:max310x_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
```
**Symbols:**

```
ffffffff81a72840-ffffffff81a7299a: uart_get_baud_rate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
unsigned int uart_get_baud_rate(struct uart_port *port, struct ktermios *termios, const struct ktermios *old, unsigned int min, unsigned int max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff81abd100)
Location: drivers/tty/serial/serial_core.c:444
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_port.c:serial8250_update_uartclk
  - drivers/tty/serial/max310x.c:max310x_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
```
**Symbols:**

```
ffffffff81abd100-ffffffff81abd25d: uart_get_baud_rate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
unsigned int uart_get_baud_rate(struct uart_port *port, struct ktermios *termios, const struct ktermios *old, unsigned int min, unsigned int max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff81b0fef0)
Location: drivers/tty/serial/serial_core.c:442
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_port.c:serial8250_update_uartclk
  - drivers/tty/serial/max310x.c:max310x_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
```
**Symbols:**

```
ffffffff81b0fef0-ffffffff81b1004b: uart_get_baud_rate (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
unsigned int uart_get_baud_rate(struct uart_port *port, struct ktermios *termios, struct ktermios *old, unsigned int min, unsigned int max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffff80001087c6c0)
Location: drivers/tty/serial/serial_core.c:392
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_mtk.c:mtk8250_set_termios
  - drivers/tty/serial/amba-pl011.c:pl011_set_termios
  - drivers/tty/serial/max310x.c:max310x_set_termios
  - drivers/tty/serial/imx.c:imx_uart_set_termios
  - drivers/tty/serial/meson_uart.c:meson_uart_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/msm_serial.c:msm_set_termios
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_set_termios
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_set_termios
  - drivers/tty/serial/owl-uart.c:owl_uart_set_termios
```
**Symbols:**

```
ffff80001087c6c0-ffff80001087c838: uart_get_baud_rate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
unsigned int uart_get_baud_rate(struct uart_port *port, struct ktermios *termios, struct ktermios *old, unsigned int min, unsigned int max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (c097d514)
Location: drivers/tty/serial/serial_core.c:392
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_mtk.c:mtk8250_set_termios
  - drivers/tty/serial/amba-pl011.c:pl011_set_termios
  - drivers/tty/serial/max310x.c:max310x_set_termios
  - drivers/tty/serial/imx.c:imx_uart_set_termios
  - drivers/tty/serial/meson_uart.c:meson_uart_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/msm_serial.c:msm_set_termios
  - drivers/tty/serial/omap-serial.c:serial_omap_set_termios
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_set_termios
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_set_termios
  - drivers/tty/serial/owl-uart.c:owl_uart_set_termios
  - drivers/tty/serial/rda-uart.c:rda_uart_set_termios
```
**Symbols:**

```
c097d514-c097d674: uart_get_baud_rate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
unsigned int uart_get_baud_rate(struct uart_port *port, struct ktermios *termios, struct ktermios *old, unsigned int min, unsigned int max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (c000000000922c90)
Location: drivers/tty/serial/serial_core.c:392
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
```
**Symbols:**

```
c000000000922c90-c000000000922ebc: uart_get_baud_rate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
unsigned int uart_get_baud_rate(struct uart_port *port, struct ktermios *termios, struct ktermios *old, unsigned int min, unsigned int max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffe00054b39c)
Location: drivers/tty/serial/serial_core.c:392
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/max310x.c:max310x_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sifive.c:sifive_serial_set_termios
```
**Symbols:**

```
ffffffe00054b39c-ffffffe00054b4e2: uart_get_baud_rate (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
unsigned int uart_get_baud_rate(struct uart_port *port, struct ktermios *termios, struct ktermios *old, unsigned int min, unsigned int max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff81669d10)
Location: drivers/tty/serial/serial_core.c:392
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/max310x.c:max310x_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
```
**Symbols:**

```
ffffffff81669d10-ffffffff81669e2e: uart_get_baud_rate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
unsigned int uart_get_baud_rate(struct uart_port *port, struct ktermios *termios, struct ktermios *old, unsigned int min, unsigned int max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff81648e80)
Location: drivers/tty/serial/serial_core.c:392
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/max310x.c:max310x_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
```
**Symbols:**

```
ffffffff81648e80-ffffffff81648f9e: uart_get_baud_rate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
unsigned int uart_get_baud_rate(struct uart_port *port, struct ktermios *termios, struct ktermios *old, unsigned int min, unsigned int max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff816980f0)
Location: drivers/tty/serial/serial_core.c:392
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/max310x.c:max310x_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
```
**Symbols:**

```
ffffffff816980f0-ffffffff8169820e: uart_get_baud_rate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
unsigned int uart_get_baud_rate(struct uart_port *port, struct ktermios *termios, struct ktermios *old, unsigned int min, unsigned int max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff816b2670)
Location: drivers/tty/serial/serial_core.c:392
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/max310x.c:max310x_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
```
**Symbols:**

```
ffffffff816b2670-ffffffff816b278e: uart_get_baud_rate (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct ktermios *old</code> ➡️ <code>const struct ktermios *old</code>
</li>
</ul>
</details>
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
