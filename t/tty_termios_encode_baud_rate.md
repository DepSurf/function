# Function: <code>tty_termios_encode_baud_rate</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void tty_termios_encode_baud_rate(struct ktermios *termios, speed_t ibaud, speed_t obaud);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ioctl.c (ffffffff814e8230)
Location: drivers/tty/tty_ioctl.c:398
Inline: False
Direct callers:
  - drivers/tty/tty_ioctl.c:tty_encode_baud_rate
  - drivers/tty/serial/serial_core.c:uart_get_baud_rate
  - drivers/tty/serial/serial_core.c:uart_get_baud_rate
  - drivers/tty/serial/serial_core.c:uart_get_baud_rate
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/kgdb_nmi.c:kgdb_register_nmi_console
```
**Symbols:**

```
ffffffff814e8230-ffffffff814e837e: tty_termios_encode_baud_rate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void tty_termios_encode_baud_rate(struct ktermios *termios, speed_t ibaud, speed_t obaud);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ioctl.c (ffffffff81539380)
Location: drivers/tty/tty_ioctl.c:393
Inline: False
Direct callers:
  - drivers/tty/tty_ioctl.c:tty_encode_baud_rate
  - drivers/tty/serial/serial_core.c:uart_set_options
  - drivers/tty/serial/serial_core.c:uart_get_baud_rate
  - drivers/tty/serial/serial_core.c:uart_get_baud_rate
  - drivers/tty/serial/serial_core.c:uart_get_baud_rate
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/kgdb_nmi.c:kgdb_register_nmi_console
```
**Symbols:**

```
ffffffff81539380-ffffffff815394ca: tty_termios_encode_baud_rate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void tty_termios_encode_baud_rate(struct ktermios *termios, speed_t ibaud, speed_t obaud);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ioctl.c (ffffffff81565a90)
Location: drivers/tty/tty_ioctl.c:393
Inline: False
Direct callers:
  - drivers/tty/tty_ioctl.c:tty_encode_baud_rate
  - drivers/tty/serial/serial_core.c:uart_set_options
  - drivers/tty/serial/serial_core.c:uart_get_baud_rate
  - drivers/tty/serial/serial_core.c:uart_get_baud_rate
  - drivers/tty/serial/serial_core.c:uart_get_baud_rate
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/kgdb_nmi.c:kgdb_register_nmi_console
```
**Symbols:**

```
ffffffff81565a90-ffffffff81565bda: tty_termios_encode_baud_rate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void tty_termios_encode_baud_rate(struct ktermios *termios, speed_t ibaud, speed_t obaud);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_baudrate.c (ffffffff8157cb00)
Location: drivers/tty/tty_baudrate.c:144
Inline: False
Direct callers:
  - drivers/tty/tty_baudrate.c:tty_encode_baud_rate
  - drivers/tty/serial/serial_core.c:uart_set_options
  - drivers/tty/serial/serial_core.c:uart_get_baud_rate
  - drivers/tty/serial/serial_core.c:uart_get_baud_rate
  - drivers/tty/serial/serial_core.c:uart_get_baud_rate
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
```
**Symbols:**

```
ffffffff8157cb00-ffffffff8157cc56: tty_termios_encode_baud_rate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void tty_termios_encode_baud_rate(struct ktermios *termios, speed_t ibaud, speed_t obaud);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_baudrate.c (ffffffff815e1620)
Location: drivers/tty/tty_baudrate.c:145
Inline: False
Direct callers:
  - drivers/tty/tty_baudrate.c:tty_encode_baud_rate
  - drivers/tty/serial/serial_core.c:uart_set_options
  - drivers/tty/serial/serial_core.c:uart_get_baud_rate
  - drivers/tty/serial/serial_core.c:uart_get_baud_rate
  - drivers/tty/serial/serial_core.c:uart_get_baud_rate
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_set_baudrate
```
**Symbols:**

```
ffffffff815e1620-ffffffff815e1776: tty_termios_encode_baud_rate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void tty_termios_encode_baud_rate(struct ktermios *termios, speed_t ibaud, speed_t obaud);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_baudrate.c (ffffffff8161a8a0)
Location: drivers/tty/tty_baudrate.c:145
Inline: False
Direct callers:
  - drivers/tty/tty_baudrate.c:tty_encode_baud_rate
  - drivers/tty/serial/serial_core.c:uart_set_options
  - drivers/tty/serial/serial_core.c:uart_get_baud_rate
  - drivers/tty/serial/serial_core.c:uart_get_baud_rate
  - drivers/tty/serial/serial_core.c:uart_get_baud_rate
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_set_baudrate
```
**Symbols:**

```
ffffffff8161a8a0-ffffffff8161aa21: tty_termios_encode_baud_rate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void tty_termios_encode_baud_rate(struct ktermios *termios, speed_t ibaud, speed_t obaud);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_baudrate.c (ffffffff81637b10)
Location: drivers/tty/tty_baudrate.c:145
Inline: False
Direct callers:
  - drivers/tty/tty_baudrate.c:tty_encode_baud_rate
  - drivers/tty/serial/serial_core.c:uart_set_options
  - drivers/tty/serial/serial_core.c:uart_get_baud_rate
  - drivers/tty/serial/serial_core.c:uart_get_baud_rate
  - drivers/tty/serial/serial_core.c:uart_get_baud_rate
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_set_baudrate
```
**Symbols:**

```
ffffffff81637b10-ffffffff81637c91: tty_termios_encode_baud_rate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void tty_termios_encode_baud_rate(struct ktermios *termios, speed_t ibaud, speed_t obaud);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_baudrate.c (ffffffff8166bde0)
Location: drivers/tty/tty_baudrate.c:145
Inline: False
Direct callers:
  - drivers/tty/tty_baudrate.c:tty_encode_baud_rate
  - drivers/tty/serial/serial_core.c:uart_set_options
  - drivers/tty/serial/serial_core.c:uart_get_baud_rate
  - drivers/tty/serial/serial_core.c:uart_get_baud_rate
  - drivers/tty/serial/serial_core.c:uart_get_baud_rate
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_set_baudrate
```
**Symbols:**

```
ffffffff8166bde0-ffffffff8166bf87: tty_termios_encode_baud_rate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void tty_termios_encode_baud_rate(struct ktermios *termios, speed_t ibaud, speed_t obaud);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_baudrate.c (ffffffff8168e450)
Location: drivers/tty/tty_baudrate.c:145
Inline: False
Direct callers:
  - drivers/tty/tty_baudrate.c:tty_encode_baud_rate
  - drivers/tty/serial/serial_core.c:uart_set_options
  - drivers/tty/serial/serial_core.c:uart_get_baud_rate
  - drivers/tty/serial/serial_core.c:uart_get_baud_rate
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_set_baudrate
```
**Symbols:**

```
ffffffff8168e450-ffffffff8168e5f7: tty_termios_encode_baud_rate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void tty_termios_encode_baud_rate(struct ktermios *termios, speed_t ibaud, speed_t obaud);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_baudrate.c (ffffffff81740720)
Location: drivers/tty/tty_baudrate.c:141
Inline: False
Direct callers:
  - drivers/tty/tty_baudrate.c:tty_encode_baud_rate
  - drivers/tty/serial/serial_core.c:uart_set_options
  - drivers/tty/serial/serial_core.c:uart_get_baud_rate
  - drivers/tty/serial/serial_core.c:uart_get_baud_rate
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_set_baudrate
```
**Symbols:**

```
ffffffff81740720-ffffffff817408ab: tty_termios_encode_baud_rate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void tty_termios_encode_baud_rate(struct ktermios *termios, speed_t ibaud, speed_t obaud);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_baudrate.c (ffffffff8175c650)
Location: drivers/tty/tty_baudrate.c:141
Inline: False
Direct callers:
  - drivers/tty/tty_baudrate.c:tty_encode_baud_rate
  - drivers/tty/serial/serial_core.c:uart_set_options
  - drivers/tty/serial/serial_core.c:uart_get_baud_rate
  - drivers/tty/serial/serial_core.c:uart_get_baud_rate
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_set_baudrate
```
**Symbols:**

```
ffffffff8175c650-ffffffff8175c7db: tty_termios_encode_baud_rate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void tty_termios_encode_baud_rate(struct ktermios *termios, speed_t ibaud, speed_t obaud);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_baudrate.c (ffffffff817404e0)
Location: drivers/tty/tty_baudrate.c:142
Inline: False
Direct callers:
  - drivers/tty/tty_baudrate.c:tty_encode_baud_rate
  - drivers/tty/serial/serial_core.c:uart_set_options
  - drivers/tty/serial/serial_core.c:uart_get_baud_rate
  - drivers/tty/serial/serial_core.c:uart_get_baud_rate
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_set_baudrate
```
**Symbols:**

```
ffffffff817404e0-ffffffff8174066b: tty_termios_encode_baud_rate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void tty_termios_encode_baud_rate(struct ktermios *termios, speed_t ibaud, speed_t obaud);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_baudrate.c (ffffffff817c0cf0)
Location: drivers/tty/tty_baudrate.c:142
Inline: False
Direct callers:
  - drivers/tty/tty_baudrate.c:tty_encode_baud_rate
  - drivers/tty/serial/serial_core.c:uart_set_options
  - drivers/tty/serial/serial_core.c:uart_get_baud_rate
  - drivers/tty/serial/serial_core.c:uart_get_baud_rate
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_set_baudrate
```
**Symbols:**

```
ffffffff817c0cf0-ffffffff817c1099: tty_termios_encode_baud_rate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void tty_termios_encode_baud_rate(struct ktermios *termios, speed_t ibaud, speed_t obaud);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_baudrate.c (ffffffff818fd650)
Location: drivers/tty/tty_baudrate.c:137
Inline: False
Direct callers:
  - drivers/tty/tty_baudrate.c:tty_encode_baud_rate
  - drivers/tty/serial/serial_core.c:uart_set_options
  - drivers/tty/serial/serial_core.c:uart_get_baud_rate
  - drivers/tty/serial/serial_core.c:uart_get_baud_rate
  - drivers/tty/serial/serial_core.c:uart_get_baud_rate
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/kgdb_nmi.c:kgdb_register_nmi_console
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_set_baudrate
```
**Symbols:**

```
ffffffff818fd650-ffffffff818fda1c: tty_termios_encode_baud_rate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void tty_termios_encode_baud_rate(struct ktermios *termios, speed_t ibaud, speed_t obaud);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_baudrate.c (ffffffff81a56ca0)
Location: drivers/tty/tty_baudrate.c:129
Inline: False
Direct callers:
  - drivers/tty/tty_baudrate.c:tty_encode_baud_rate
  - drivers/tty/serial/serial_core.c:uart_set_options
  - drivers/tty/serial/serial_core.c:uart_get_baud_rate
  - drivers/tty/serial/serial_core.c:uart_get_baud_rate
  - drivers/tty/serial/serial_core.c:uart_get_baud_rate
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/kgdb_nmi.c:kgdb_register_nmi_console
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_set_baudrate
```
**Symbols:**

```
ffffffff81a56ca0-ffffffff81a5706c: tty_termios_encode_baud_rate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void tty_termios_encode_baud_rate(struct ktermios *termios, speed_t ibaud, speed_t obaud);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_baudrate.c (ffffffff81aa1280)
Location: drivers/tty/tty_baudrate.c:129
Inline: False
Direct callers:
  - drivers/tty/tty_baudrate.c:tty_encode_baud_rate
  - drivers/tty/serial/serial_core.c:uart_set_options
  - drivers/tty/serial/serial_core.c:uart_get_baud_rate
  - drivers/tty/serial/serial_core.c:uart_get_baud_rate
  - drivers/tty/serial/serial_core.c:uart_get_baud_rate
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/kgdb_nmi.c:kgdb_register_nmi_console
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_set_baudrate
```
**Symbols:**

```
ffffffff81aa1280-ffffffff81aa1649: tty_termios_encode_baud_rate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void tty_termios_encode_baud_rate(struct ktermios *termios, speed_t ibaud, speed_t obaud);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_baudrate.c (ffffffff81af3ce0)
Location: drivers/tty/tty_baudrate.c:129
Inline: False
Direct callers:
  - drivers/tty/tty_baudrate.c:tty_encode_baud_rate
  - drivers/tty/serial/serial_core.c:uart_set_options
  - drivers/tty/serial/serial_core.c:uart_get_baud_rate
  - drivers/tty/serial/serial_core.c:uart_get_baud_rate
  - drivers/tty/serial/serial_core.c:uart_get_baud_rate
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/kgdb_nmi.c:kgdb_register_nmi_console
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_set_baudrate
```
**Symbols:**

```
ffffffff81af3ce0-ffffffff81af40a9: tty_termios_encode_baud_rate (STB_GLOBAL)
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
void tty_termios_encode_baud_rate(struct ktermios *termios, speed_t ibaud, speed_t obaud);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_baudrate.c (ffff80001085f9d0)
Location: drivers/tty/tty_baudrate.c:145
Inline: False
Direct callers:
  - drivers/tty/tty_baudrate.c:tty_encode_baud_rate
  - drivers/tty/serial/serial_core.c:uart_set_options
  - drivers/tty/serial/serial_core.c:uart_get_baud_rate
  - drivers/tty/serial/serial_core.c:uart_get_baud_rate
  - drivers/tty/serial/serial_core.c:uart_get_baud_rate
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios
  - drivers/tty/serial/8250/8250_mtk.c:mtk8250_set_termios
  - drivers/tty/serial/amba-pl011.c:sbsa_uart_set_termios
  - drivers/tty/serial/imx.c:imx_uart_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/msm_serial.c:msm_set_termios
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_set_termios
  - drivers/tty/serial/owl-uart.c:owl_uart_set_termios
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_set_baudrate
```
**Symbols:**

```
ffff80001085f9d0-ffff80001085fb98: tty_termios_encode_baud_rate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void tty_termios_encode_baud_rate(struct ktermios *termios, speed_t ibaud, speed_t obaud);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_baudrate.c (c0966c88)
Location: drivers/tty/tty_baudrate.c:145
Inline: False
Direct callers:
  - drivers/tty/tty_baudrate.c:tty_encode_baud_rate
  - drivers/tty/serial/serial_core.c:uart_set_options
  - drivers/tty/serial/serial_core.c:uart_get_baud_rate
  - drivers/tty/serial/serial_core.c:uart_get_baud_rate
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_mtk.c:mtk8250_set_termios
  - drivers/tty/serial/amba-pl011.c:sbsa_uart_set_termios
  - drivers/tty/serial/imx.c:imx_uart_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/msm_serial.c:msm_set_termios
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_set_termios
  - drivers/tty/serial/owl-uart.c:owl_uart_set_termios
  - drivers/tty/serial/rda-uart.c:rda_uart_set_termios
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_set_baudrate
```
**Symbols:**

```
c0966c88-c0966e30: tty_termios_encode_baud_rate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void tty_termios_encode_baud_rate(struct ktermios *termios, speed_t ibaud, speed_t obaud);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_baudrate.c (c0000000008fee10)
Location: drivers/tty/tty_baudrate.c:145
Inline: False
Direct callers:
  - drivers/tty/tty_ioctl.c:tty_mode_ioctl
  - drivers/tty/tty_baudrate.c:tty_encode_baud_rate
  - drivers/tty/serial/serial_core.c:uart_set_options
  - drivers/tty/serial/serial_core.c:uart_get_baud_rate
  - drivers/tty/serial/serial_core.c:uart_get_baud_rate
  - drivers/tty/serial/serial_core.c:uart_get_baud_rate
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_set_baudrate
```
**Symbols:**

```
c0000000008fee10-c0000000008ff06c: tty_termios_encode_baud_rate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void tty_termios_encode_baud_rate(struct ktermios *termios, speed_t ibaud, speed_t obaud);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_baudrate.c (ffffffe000537c6c)
Location: drivers/tty/tty_baudrate.c:145
Inline: False
Direct callers:
  - drivers/tty/tty_baudrate.c:tty_encode_baud_rate
  - drivers/tty/serial/serial_core.c:uart_set_options
  - drivers/tty/serial/serial_core.c:uart_get_baud_rate
  - drivers/tty/serial/serial_core.c:uart_get_baud_rate
  - drivers/tty/serial/serial_core.c:uart_get_baud_rate
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_set_baudrate
```
**Symbols:**

```
ffffffe000537c6c-ffffffe000537dca: tty_termios_encode_baud_rate (STB_GLOBAL)
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
void tty_termios_encode_baud_rate(struct ktermios *termios, speed_t ibaud, speed_t obaud);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_baudrate.c (ffffffff81653ed0)
Location: drivers/tty/tty_baudrate.c:145
Inline: False
Direct callers:
  - drivers/tty/tty_baudrate.c:tty_encode_baud_rate
  - drivers/tty/serial/serial_core.c:uart_set_options
  - drivers/tty/serial/serial_core.c:uart_get_baud_rate
  - drivers/tty/serial/serial_core.c:uart_get_baud_rate
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_set_baudrate
```
**Symbols:**

```
ffffffff81653ed0-ffffffff81654077: tty_termios_encode_baud_rate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void tty_termios_encode_baud_rate(struct ktermios *termios, speed_t ibaud, speed_t obaud);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_baudrate.c (ffffffff816342b0)
Location: drivers/tty/tty_baudrate.c:145
Inline: False
Direct callers:
  - drivers/tty/tty_baudrate.c:tty_encode_baud_rate
  - drivers/tty/serial/serial_core.c:uart_set_options
  - drivers/tty/serial/serial_core.c:uart_get_baud_rate
  - drivers/tty/serial/serial_core.c:uart_get_baud_rate
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
```
**Symbols:**

```
ffffffff816342b0-ffffffff81634457: tty_termios_encode_baud_rate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void tty_termios_encode_baud_rate(struct ktermios *termios, speed_t ibaud, speed_t obaud);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_baudrate.c (ffffffff81682290)
Location: drivers/tty/tty_baudrate.c:145
Inline: False
Direct callers:
  - drivers/tty/tty_baudrate.c:tty_encode_baud_rate
  - drivers/tty/serial/serial_core.c:uart_set_options
  - drivers/tty/serial/serial_core.c:uart_get_baud_rate
  - drivers/tty/serial/serial_core.c:uart_get_baud_rate
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_set_baudrate
```
**Symbols:**

```
ffffffff81682290-ffffffff81682437: tty_termios_encode_baud_rate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void tty_termios_encode_baud_rate(struct ktermios *termios, speed_t ibaud, speed_t obaud);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_baudrate.c (ffffffff8169c8d0)
Location: drivers/tty/tty_baudrate.c:145
Inline: False
Direct callers:
  - drivers/tty/tty_baudrate.c:tty_encode_baud_rate
  - drivers/tty/serial/serial_core.c:uart_set_options
  - drivers/tty/serial/serial_core.c:uart_get_baud_rate
  - drivers/tty/serial/serial_core.c:uart_get_baud_rate
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_set_baudrate
```
**Symbols:**

```
ffffffff8169c8d0-ffffffff8169ca77: tty_termios_encode_baud_rate (STB_GLOBAL)
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
