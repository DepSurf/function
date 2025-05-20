# Function: <code>uart_console_write</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void uart_console_write(struct uart_port *port, const char *s, unsigned int count, void (*putchar)(struct uart_port *, int));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff814ffc60)
Location: drivers/tty/serial/serial_core.c:1777
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_write
  - drivers/tty/serial/sccnxp.c:sccnxp_console_write
```
**Symbols:**

```
ffffffff814ffc60-ffffffff814ffcc5: uart_console_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void uart_console_write(struct uart_port *port, const char *s, unsigned int count, void (*putchar)(struct uart_port *, int));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff81550710)
Location: drivers/tty/serial/serial_core.c:1889
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_write
  - drivers/tty/serial/sccnxp.c:sccnxp_console_write
```
**Symbols:**

```
ffffffff81550710-ffffffff81550775: uart_console_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void uart_console_write(struct uart_port *port, const char *s, unsigned int count, void (*putchar)(struct uart_port *, int));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff8157cf90)
Location: drivers/tty/serial/serial_core.c:1847
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_write
  - drivers/tty/serial/sccnxp.c:sccnxp_console_write
```
**Symbols:**

```
ffffffff8157cf90-ffffffff8157cff5: uart_console_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void uart_console_write(struct uart_port *port, const char *s, unsigned int count, void (*putchar)(struct uart_port *, int));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff81591200)
Location: drivers/tty/serial/serial_core.c:1853
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_write
  - drivers/tty/serial/sccnxp.c:sccnxp_console_write
```
**Symbols:**

```
ffffffff81591200-ffffffff81591258: uart_console_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void uart_console_write(struct uart_port *port, const char *s, unsigned int count, void (*putchar)(struct uart_port *, int));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff815f5ca0)
Location: drivers/tty/serial/serial_core.c:1859
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_write
  - drivers/tty/serial/sccnxp.c:sccnxp_console_write
```
**Symbols:**

```
ffffffff815f5ca0-ffffffff815f5cfc: uart_console_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void uart_console_write(struct uart_port *port, const char *s, unsigned int count, void (*putchar)(struct uart_port *, int));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff8162eeb0)
Location: drivers/tty/serial/serial_core.c:1855
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_write
  - drivers/tty/serial/sccnxp.c:sccnxp_console_write
```
**Symbols:**

```
ffffffff8162eeb0-ffffffff8162ef0a: uart_console_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void uart_console_write(struct uart_port *port, const char *s, unsigned int count, void (*putchar)(struct uart_port *, int));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff8164d030)
Location: drivers/tty/serial/serial_core.c:1914
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_write
  - drivers/tty/serial/sccnxp.c:sccnxp_console_write
```
**Symbols:**

```
ffffffff8164d030-ffffffff8164d08a: uart_console_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void uart_console_write(struct uart_port *port, const char *s, unsigned int count, void (*putchar)(struct uart_port *, int));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff81681b60)
Location: drivers/tty/serial/serial_core.c:1920
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_write
  - drivers/tty/serial/sccnxp.c:sccnxp_console_write
```
**Symbols:**

```
ffffffff81681b60-ffffffff81681bba: uart_console_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void uart_console_write(struct uart_port *port, const char *s, unsigned int count, void (*putchar)(struct uart_port *, int));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff816a4210)
Location: drivers/tty/serial/serial_core.c:1919
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_write
  - drivers/tty/serial/sccnxp.c:sccnxp_console_write
```
**Symbols:**

```
ffffffff816a4210-ffffffff816a426a: uart_console_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void uart_console_write(struct uart_port *port, const char *s, unsigned int count, void (*putchar)(struct uart_port *, int));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff81756a90)
Location: drivers/tty/serial/serial_core.c:1931
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_write
  - drivers/tty/serial/sccnxp.c:sccnxp_console_write
```
**Symbols:**

```
ffffffff81756a90-ffffffff81756ae8: uart_console_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void uart_console_write(struct uart_port *port, const char *s, unsigned int count, void (*putchar)(struct uart_port *, int));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff81771c10)
Location: drivers/tty/serial/serial_core.c:1937
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_write
  - drivers/tty/serial/sccnxp.c:sccnxp_console_write
```
**Symbols:**

```
ffffffff81771c10-ffffffff81771c68: uart_console_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void uart_console_write(struct uart_port *port, const char *s, unsigned int count, void (*putchar)(struct uart_port *, int));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff817556d0)
Location: drivers/tty/serial/serial_core.c:1934
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_write
  - drivers/tty/serial/sccnxp.c:sccnxp_console_write
```
**Symbols:**

```
ffffffff817556d0-ffffffff81755728: uart_console_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void uart_console_write(struct uart_port *port, const char *s, unsigned int count, void (*putchar)(struct uart_port *, int));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff817d8d90)
Location: drivers/tty/serial/serial_core.c:1933
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_write
  - drivers/tty/serial/sccnxp.c:sccnxp_console_write
```
**Symbols:**

```
ffffffff817d8d90-ffffffff817d8de8: uart_console_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void uart_console_write(struct uart_port *port, const char *s, unsigned int count, void (*putchar)(struct uart_port *, unsigned char));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff81917200)
Location: drivers/tty/serial/serial_core.c:1958
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_write
  - drivers/tty/serial/sccnxp.c:sccnxp_console_write
```
**Symbols:**

```
ffffffff81917200-ffffffff81917264: uart_console_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void uart_console_write(struct uart_port *port, const char *s, unsigned int count, void (*putchar)(struct uart_port *, unsigned char));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff81a72660)
Location: drivers/tty/serial/serial_core.c:2075
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_write
  - drivers/tty/serial/sccnxp.c:sccnxp_console_write
```
**Symbols:**

```
ffffffff81a72660-ffffffff81a726c4: uart_console_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void uart_console_write(struct uart_port *port, const char *s, unsigned int count, void (*putchar)(struct uart_port *, unsigned char));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff81abcf20)
Location: drivers/tty/serial/serial_core.c:2095
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_write
  - drivers/tty/serial/8250/8250_rt288x.c:au_early_serial8250_write
  - drivers/tty/serial/sccnxp.c:sccnxp_console_write
```
**Symbols:**

```
ffffffff81abcf20-ffffffff81abcf84: uart_console_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void uart_console_write(struct uart_port *port, const char *s, unsigned int count, void (*putchar)(struct uart_port *, unsigned char));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff81b0fd10)
Location: drivers/tty/serial/serial_core.c:2131
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_write
  - drivers/tty/serial/8250/8250_rt288x.c:au_early_serial8250_write
  - drivers/tty/serial/sccnxp.c:sccnxp_console_write
```
**Symbols:**

```
ffffffff81b0fd10-ffffffff81b0fd74: uart_console_write (STB_GLOBAL)
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
void uart_console_write(struct uart_port *port, const char *s, unsigned int count, void (*putchar)(struct uart_port *, int));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffff80001087c5f8)
Location: drivers/tty/serial/serial_core.c:1919
Inline: False
Direct callers:
  - drivers/tty/serial/earlycon-arm-semihost.c:smh_write
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_write
  - drivers/tty/serial/amba-pl011.c:pl011_early_write
  - drivers/tty/serial/amba-pl011.c:qdf2400_e44_early_write
  - drivers/tty/serial/amba-pl011.c:pl011_console_write
  - drivers/tty/serial/imx.c:imx_uart_console_early_write
  - drivers/tty/serial/imx.c:imx_uart_console_write
  - drivers/tty/serial/meson_uart.c:meson_serial_port_write
  - drivers/tty/serial/sccnxp.c:sccnxp_console_write
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_console_write
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_putc_early_write
  - drivers/tty/serial/owl-uart.c:owl_uart_port_write
```
**Symbols:**

```
ffff80001087c5f8-ffff80001087c670: uart_console_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void uart_console_write(struct uart_port *port, const char *s, unsigned int count, void (*putchar)(struct uart_port *, int));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (c097d46c)
Location: drivers/tty/serial/serial_core.c:1919
Inline: False
Direct callers:
  - drivers/tty/serial/earlycon-arm-semihost.c:smh_write
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_write
  - drivers/tty/serial/amba-pl011.c:pl011_early_write
  - drivers/tty/serial/amba-pl011.c:qdf2400_e44_early_write
  - drivers/tty/serial/amba-pl011.c:pl011_console_write
  - drivers/tty/serial/imx.c:imx_uart_console_early_write
  - drivers/tty/serial/imx.c:imx_uart_console_write
  - drivers/tty/serial/meson_uart.c:meson_serial_port_write
  - drivers/tty/serial/sccnxp.c:sccnxp_console_write
  - drivers/tty/serial/omap-serial.c:serial_omap_console_write
  - drivers/tty/serial/omap-serial.c:early_omap_serial_write
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_console_write
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_putc_early_write
  - drivers/tty/serial/owl-uart.c:owl_uart_port_write
  - drivers/tty/serial/rda-uart.c:rda_uart_port_write
```
**Symbols:**

```
c097d46c-c097d4cc: uart_console_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void uart_console_write(struct uart_port *port, const char *s, unsigned int count, void (*putchar)(struct uart_port *, int));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (c000000000922b40)
Location: drivers/tty/serial/serial_core.c:1919
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_write
  - drivers/tty/serial/sccnxp.c:sccnxp_console_write
```
**Symbols:**

```
c000000000922b40-c000000000922bf4: uart_console_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void uart_console_write(struct uart_port *port, const char *s, unsigned int count, void (*putchar)(struct uart_port *, int));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffe00054b2f2)
Location: drivers/tty/serial/serial_core.c:1919
Inline: False
Direct callers:
  - drivers/tty/serial/earlycon-riscv-sbi.c:sbi_console_write
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_write
  - drivers/tty/serial/sccnxp.c:sccnxp_console_write
  - drivers/tty/serial/sifive.c:sifive_serial_console_write
  - drivers/tty/serial/sifive.c:early_sifive_serial_write
```
**Symbols:**

```
ffffffe00054b2f2-ffffffe00054b356: uart_console_write (STB_GLOBAL)
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
void uart_console_write(struct uart_port *port, const char *s, unsigned int count, void (*putchar)(struct uart_port *, int));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff81669c70)
Location: drivers/tty/serial/serial_core.c:1919
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_write
  - drivers/tty/serial/sccnxp.c:sccnxp_console_write
```
**Symbols:**

```
ffffffff81669c70-ffffffff81669cca: uart_console_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void uart_console_write(struct uart_port *port, const char *s, unsigned int count, void (*putchar)(struct uart_port *, int));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff81648de0)
Location: drivers/tty/serial/serial_core.c:1919
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_write
  - drivers/tty/serial/sccnxp.c:sccnxp_console_write
```
**Symbols:**

```
ffffffff81648de0-ffffffff81648e3a: uart_console_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void uart_console_write(struct uart_port *port, const char *s, unsigned int count, void (*putchar)(struct uart_port *, int));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff81698050)
Location: drivers/tty/serial/serial_core.c:1919
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_write
  - drivers/tty/serial/sccnxp.c:sccnxp_console_write
```
**Symbols:**

```
ffffffff81698050-ffffffff816980aa: uart_console_write (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void uart_console_write(struct uart_port *port, const char *s, unsigned int count, void (*putchar)(struct uart_port *, int));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff816b25d0)
Location: drivers/tty/serial/serial_core.c:1919
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_write
  - drivers/tty/serial/sccnxp.c:sccnxp_console_write
```
**Symbols:**

```
ffffffff816b25d0-ffffffff816b262a: uart_console_write (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>void (*putchar)(struct uart_port *, int)</code> ➡️ <code>void (*putchar)(struct uart_port *, unsigned char)</code>
</li>
</ul>
</details>
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
