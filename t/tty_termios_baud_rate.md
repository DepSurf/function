# Function: <code>tty_termios_baud_rate</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
speed_t tty_termios_baud_rate(struct ktermios *termios);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ioctl.c (ffffffff814e8160)
Location: drivers/tty/tty_ioctl.c:314
Inline: True
Inline callers:
  - drivers/tty/tty_ioctl.c:tty_termios_input_baud_rate
Direct callers:
  - drivers/tty/tty_io.c:tty_init_termios
  - drivers/tty/tty_ldisc.c:tty_ldisc_hangup
  - drivers/tty/serial/serial_core.c:uart_get_baud_rate
  - drivers/tty/serial/serial_core.c:uart_get_baud_rate
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_pci.c:byt_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
```
**Symbols:**

```
ffffffff814e8160-ffffffff814e81a3: tty_termios_baud_rate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
speed_t tty_termios_baud_rate(struct ktermios *termios);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ioctl.c (ffffffff8153931b)
Location: drivers/tty/tty_ioctl.c:309
Inline: True
Inline callers:
  - drivers/tty/tty_ioctl.c:tty_termios_input_baud_rate
Direct callers:
  - drivers/tty/tty_io.c:tty_init_termios
  - drivers/tty/tty_ldisc.c:tty_ldisc_hangup
  - drivers/tty/serial/serial_core.c:uart_get_baud_rate
  - drivers/tty/serial/serial_core.c:uart_get_baud_rate
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_pci.c:byt_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
```
**Symbols:**

```
ffffffff815392c0-ffffffff815392ff: tty_termios_baud_rate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
speed_t tty_termios_baud_rate(struct ktermios *termios);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ioctl.c (ffffffff81565a2b)
Location: drivers/tty/tty_ioctl.c:309
Inline: True
Inline callers:
  - drivers/tty/tty_ioctl.c:tty_termios_input_baud_rate
Direct callers:
  - drivers/tty/tty_io.c:tty_init_termios
  - drivers/tty/tty_ldisc.c:tty_ldisc_hangup
  - drivers/tty/serial/serial_core.c:uart_get_baud_rate
  - drivers/tty/serial/serial_core.c:uart_get_baud_rate
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
```
**Symbols:**

```
ffffffff815659d0-ffffffff81565a0f: tty_termios_baud_rate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
speed_t tty_termios_baud_rate(struct ktermios *termios);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_baudrate.c (ffffffff8157ca9b)
Location: drivers/tty/tty_baudrate.c:60
Inline: True
Inline callers:
  - drivers/tty/tty_baudrate.c:tty_termios_input_baud_rate
Direct callers:
  - drivers/tty/tty_io.c:tty_init_termios
  - drivers/tty/tty_ldisc.c:tty_ldisc_hangup
  - drivers/tty/serial/serial_core.c:uart_get_baud_rate
  - drivers/tty/serial/serial_core.c:uart_get_baud_rate
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
```
**Symbols:**

```
ffffffff8157ca40-ffffffff8157ca7f: tty_termios_baud_rate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
speed_t tty_termios_baud_rate(struct ktermios *termios);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_baudrate.c (ffffffff815e15bb)
Location: drivers/tty/tty_baudrate.c:61
Inline: True
Inline callers:
  - drivers/tty/tty_baudrate.c:tty_termios_input_baud_rate
Direct callers:
  - drivers/tty/tty_io.c:tty_init_termios
  - drivers/tty/tty_ldisc.c:tty_ldisc_hangup
  - drivers/tty/serial/serial_core.c:uart_get_baud_rate
  - drivers/tty/serial/serial_core.c:uart_get_baud_rate
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
```
**Symbols:**

```
ffffffff815e1560-ffffffff815e159f: tty_termios_baud_rate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
speed_t tty_termios_baud_rate(struct ktermios *termios);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_baudrate.c (ffffffff8161a863)
Location: drivers/tty/tty_baudrate.c:61
Inline: True
Inline callers:
  - drivers/tty/tty_baudrate.c:tty_termios_input_baud_rate
Direct callers:
  - drivers/tty/tty_io.c:tty_init_termios
  - drivers/tty/tty_ldisc.c:tty_ldisc_hangup
  - drivers/tty/serial/serial_core.c:uart_get_baud_rate
  - drivers/tty/serial/serial_core.c:uart_get_baud_rate
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
```
**Symbols:**

```
ffffffff8161a7e0-ffffffff8161a81f: tty_termios_baud_rate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
speed_t tty_termios_baud_rate(struct ktermios *termios);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_baudrate.c (ffffffff81637a40)
Location: drivers/tty/tty_baudrate.c:61
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_init_termios
  - drivers/tty/tty_ldisc.c:tty_ldisc_hangup
  - drivers/tty/tty_baudrate.c:tty_termios_input_baud_rate
  - drivers/tty/serial/serial_core.c:uart_get_baud_rate
  - drivers/tty/serial/serial_core.c:uart_get_baud_rate
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
```
**Symbols:**

```
ffffffff81637a40-ffffffff81637a93: tty_termios_baud_rate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
speed_t tty_termios_baud_rate(struct ktermios *termios);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_baudrate.c (ffffffff8166bd00)
Location: drivers/tty/tty_baudrate.c:61
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_init_termios
  - drivers/tty/tty_ldisc.c:tty_ldisc_hangup
  - drivers/tty/tty_baudrate.c:tty_termios_input_baud_rate
  - drivers/tty/serial/serial_core.c:uart_get_baud_rate
  - drivers/tty/serial/serial_core.c:uart_get_baud_rate
  - drivers/tty/serial/serial_core.c:uart_get_baud_rate
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
```
**Symbols:**

```
ffffffff8166bd00-ffffffff8166bd63: tty_termios_baud_rate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
speed_t tty_termios_baud_rate(struct ktermios *termios);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_baudrate.c (ffffffff8168e370)
Location: drivers/tty/tty_baudrate.c:61
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_init_termios
  - drivers/tty/tty_ldisc.c:tty_ldisc_hangup
  - drivers/tty/tty_baudrate.c:tty_termios_input_baud_rate
  - drivers/tty/serial/serial_core.c:uart_get_baud_rate
  - drivers/tty/serial/serial_core.c:uart_get_baud_rate
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
```
**Symbols:**

```
ffffffff8168e370-ffffffff8168e3d3: tty_termios_baud_rate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
speed_t tty_termios_baud_rate(struct ktermios *termios);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_baudrate.c (ffffffff81740630)
Location: drivers/tty/tty_baudrate.c:57
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_init_termios
  - drivers/tty/tty_ldisc.c:tty_ldisc_hangup
  - drivers/tty/tty_baudrate.c:tty_termios_input_baud_rate
  - drivers/tty/serial/serial_core.c:uart_get_baud_rate
  - drivers/tty/serial/serial_core.c:uart_get_baud_rate
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
```
**Symbols:**

```
ffffffff81740630-ffffffff8174069a: tty_termios_baud_rate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
speed_t tty_termios_baud_rate(struct ktermios *termios);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_baudrate.c (ffffffff8175c560)
Location: drivers/tty/tty_baudrate.c:57
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_init_termios
  - drivers/tty/tty_ldisc.c:tty_ldisc_hangup
  - drivers/tty/tty_baudrate.c:tty_termios_input_baud_rate
  - drivers/tty/serial/serial_core.c:uart_get_baud_rate
  - drivers/tty/serial/serial_core.c:uart_get_baud_rate
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
```
**Symbols:**

```
ffffffff8175c560-ffffffff8175c5ca: tty_termios_baud_rate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
speed_t tty_termios_baud_rate(struct ktermios *termios);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_baudrate.c (ffffffff81740400)
Location: drivers/tty/tty_baudrate.c:58
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_init_termios
  - drivers/tty/tty_ldisc.c:tty_ldisc_hangup
  - drivers/tty/tty_baudrate.c:tty_termios_input_baud_rate
  - drivers/tty/serial/serial_core.c:uart_get_baud_rate
  - drivers/tty/serial/serial_core.c:uart_get_baud_rate
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
```
**Symbols:**

```
ffffffff81740400-ffffffff8174046a: tty_termios_baud_rate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
speed_t tty_termios_baud_rate(struct ktermios *termios);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_baudrate.c (ffffffff817c0be0)
Location: drivers/tty/tty_baudrate.c:58
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_init_termios
  - drivers/tty/tty_ldisc.c:tty_ldisc_hangup
  - drivers/tty/tty_baudrate.c:tty_termios_input_baud_rate
  - drivers/tty/serial/serial_core.c:uart_get_baud_rate
  - drivers/tty/serial/serial_core.c:uart_get_baud_rate
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
```
**Symbols:**

```
ffffffff817c0be0-ffffffff817c0c60: tty_termios_baud_rate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
speed_t tty_termios_baud_rate(struct ktermios *termios);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_baudrate.c (ffffffff818fd4e0)
Location: drivers/tty/tty_baudrate.c:58
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_init_termios
  - drivers/tty/tty_ioctl.c:set_termios
  - drivers/tty/tty_ldisc.c:tty_ldisc_hangup
  - drivers/tty/tty_port.c:tty_port_close_start
  - drivers/tty/tty_baudrate.c:tty_termios_input_baud_rate
  - drivers/tty/serial/serial_core.c:uart_get_baud_rate
  - drivers/tty/serial/serial_core.c:uart_get_baud_rate
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
```
**Symbols:**

```
ffffffff818fd4e0-ffffffff818fd589: tty_termios_baud_rate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
speed_t tty_termios_baud_rate(const struct ktermios *termios);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_baudrate.c (ffffffff81a5712b)
Location: drivers/tty/tty_baudrate.c:58
Inline: True
Inline callers:
  - drivers/tty/tty_baudrate.c:tty_termios_input_baud_rate
Direct callers:
  - drivers/tty/tty_io.c:tty_init_termios
  - drivers/tty/tty_ioctl.c:set_termios
  - drivers/tty/tty_ldisc.c:tty_ldisc_hangup
  - drivers/tty/tty_port.c:tty_port_close_start
  - drivers/tty/serial/serial_core.c:uart_get_baud_rate
  - drivers/tty/serial/serial_core.c:uart_get_baud_rate
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios
  - drivers/tty/serial/8250/8250_mid.c:mid8250_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
```
**Symbols:**

```
ffffffff81a56bf0-ffffffff81a56c8b: tty_termios_baud_rate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
speed_t tty_termios_baud_rate(const struct ktermios *termios);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_baudrate.c (ffffffff81aa170b)
Location: drivers/tty/tty_baudrate.c:58
Inline: True
Inline callers:
  - drivers/tty/tty_baudrate.c:tty_termios_input_baud_rate
Direct callers:
  - drivers/tty/tty_io.c:tty_init_termios
  - drivers/tty/tty_ioctl.c:set_termios
  - drivers/tty/tty_ldisc.c:tty_ldisc_hangup
  - drivers/tty/tty_port.c:tty_port_close_start
  - drivers/tty/serial/serial_core.c:uart_get_baud_rate
  - drivers/tty/serial/serial_core.c:uart_get_baud_rate
  - drivers/tty/serial/serial_core.c:uart_get_baud_rate
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios
  - drivers/tty/serial/8250/8250_mid.c:mid8250_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
```
**Symbols:**

```
ffffffff81aa11d0-ffffffff81aa126b: tty_termios_baud_rate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
speed_t tty_termios_baud_rate(const struct ktermios *termios);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_baudrate.c (ffffffff81af416b)
Location: drivers/tty/tty_baudrate.c:58
Inline: True
Inline callers:
  - drivers/tty/tty_baudrate.c:tty_termios_input_baud_rate
Direct callers:
  - drivers/tty/tty_io.c:tty_init_termios
  - drivers/tty/tty_ioctl.c:set_termios
  - drivers/tty/tty_ldisc.c:tty_ldisc_hangup
  - drivers/tty/tty_port.c:tty_port_close_start
  - drivers/tty/serial/serial_core.c:uart_get_baud_rate
  - drivers/tty/serial/serial_core.c:uart_get_baud_rate
  - drivers/tty/serial/serial_core.c:uart_get_baud_rate
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios
  - drivers/tty/serial/8250/8250_mid.c:mid8250_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
```
**Symbols:**

```
ffffffff81af3c30-ffffffff81af3ccb: tty_termios_baud_rate (STB_GLOBAL)
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
speed_t tty_termios_baud_rate(struct ktermios *termios);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_baudrate.c (ffff80001085f870)
Location: drivers/tty/tty_baudrate.c:61
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_init_termios
  - drivers/tty/tty_ldisc.c:tty_ldisc_hangup
  - drivers/tty/tty_baudrate.c:tty_termios_input_baud_rate
  - drivers/tty/serial/serial_core.c:uart_get_baud_rate
  - drivers/tty/serial/serial_core.c:uart_get_baud_rate
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios
  - drivers/tty/serial/8250/8250_dw.c:dw8250_set_termios
  - drivers/tty/serial/8250/8250_mtk.c:mtk8250_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/msm_serial.c:msm_set_termios
  - drivers/tty/serial/owl-uart.c:owl_uart_set_termios
```
**Symbols:**

```
ffff80001085f870-ffff80001085f910: tty_termios_baud_rate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
speed_t tty_termios_baud_rate(struct ktermios *termios);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_baudrate.c (c0966b98)
Location: drivers/tty/tty_baudrate.c:61
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_init_termios
  - drivers/tty/tty_ldisc.c:tty_ldisc_hangup
  - drivers/tty/tty_baudrate.c:tty_termios_input_baud_rate
  - drivers/tty/serial/serial_core.c:uart_get_baud_rate
  - drivers/tty/serial/serial_core.c:uart_get_baud_rate
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_mtk.c:mtk8250_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/msm_serial.c:msm_set_termios
  - drivers/tty/serial/msm_serial.c:msm_set_termios
  - drivers/tty/serial/owl-uart.c:owl_uart_set_termios
  - drivers/tty/serial/rda-uart.c:rda_uart_set_termios
```
**Symbols:**

```
c0966b98-c0966c08: tty_termios_baud_rate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
speed_t tty_termios_baud_rate(struct ktermios *termios);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_baudrate.c (c0000000008fedb0)
Location: drivers/tty/tty_baudrate.c:61
Inline: True
Inline callers:
  - drivers/tty/tty_baudrate.c:tty_termios_input_baud_rate
Direct callers:
  - drivers/tty/tty_io.c:tty_init_termios
  - drivers/tty/tty_io.c:tty_init_termios
  - drivers/tty/tty_ldisc.c:tty_ldisc_hangup
  - drivers/tty/serial/serial_core.c:uart_get_baud_rate
  - drivers/tty/serial/serial_core.c:uart_get_baud_rate
  - drivers/tty/serial/serial_core.c:uart_get_baud_rate
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
```
**Symbols:**

```
c0000000008fecf0-c0000000008fed48: tty_termios_baud_rate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
speed_t tty_termios_baud_rate(struct ktermios *termios);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_baudrate.c (ffffffe000537b3a)
Location: drivers/tty/tty_baudrate.c:61
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_init_termios
  - drivers/tty/tty_ldisc.c:tty_ldisc_hangup
  - drivers/tty/tty_baudrate.c:tty_termios_input_baud_rate
  - drivers/tty/serial/serial_core.c:uart_get_baud_rate
  - drivers/tty/serial/serial_core.c:uart_get_baud_rate
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
```
**Symbols:**

```
ffffffe000537b3a-ffffffe000537bc4: tty_termios_baud_rate (STB_GLOBAL)
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
speed_t tty_termios_baud_rate(struct ktermios *termios);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_baudrate.c (ffffffff81653df0)
Location: drivers/tty/tty_baudrate.c:61
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_init_termios
  - drivers/tty/tty_ldisc.c:tty_ldisc_hangup
  - drivers/tty/tty_baudrate.c:tty_termios_input_baud_rate
  - drivers/tty/serial/serial_core.c:uart_get_baud_rate
  - drivers/tty/serial/serial_core.c:uart_get_baud_rate
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
```
**Symbols:**

```
ffffffff81653df0-ffffffff81653e53: tty_termios_baud_rate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
speed_t tty_termios_baud_rate(struct ktermios *termios);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_baudrate.c (ffffffff816341d0)
Location: drivers/tty/tty_baudrate.c:61
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_init_termios
  - drivers/tty/tty_ldisc.c:tty_ldisc_hangup
  - drivers/tty/tty_baudrate.c:tty_termios_input_baud_rate
  - drivers/tty/serial/serial_core.c:uart_get_baud_rate
  - drivers/tty/serial/serial_core.c:uart_get_baud_rate
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
```
**Symbols:**

```
ffffffff816341d0-ffffffff81634233: tty_termios_baud_rate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
speed_t tty_termios_baud_rate(struct ktermios *termios);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_baudrate.c (ffffffff816821b0)
Location: drivers/tty/tty_baudrate.c:61
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_init_termios
  - drivers/tty/tty_ldisc.c:tty_ldisc_hangup
  - drivers/tty/tty_baudrate.c:tty_termios_input_baud_rate
  - drivers/tty/serial/serial_core.c:uart_get_baud_rate
  - drivers/tty/serial/serial_core.c:uart_get_baud_rate
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
```
**Symbols:**

```
ffffffff816821b0-ffffffff81682213: tty_termios_baud_rate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
speed_t tty_termios_baud_rate(struct ktermios *termios);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_baudrate.c (ffffffff8169c7f0)
Location: drivers/tty/tty_baudrate.c:61
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_init_termios
  - drivers/tty/tty_ldisc.c:tty_ldisc_hangup
  - drivers/tty/tty_baudrate.c:tty_termios_input_baud_rate
  - drivers/tty/serial/serial_core.c:uart_get_baud_rate
  - drivers/tty/serial/serial_core.c:uart_get_baud_rate
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios
  - drivers/tty/serial/8250/8250_fintek.c:fintek_8250_set_termios
  - drivers/tty/serial/sccnxp.c:sccnxp_set_termios
```
**Symbols:**

```
ffffffff8169c7f0-ffffffff8169c853: tty_termios_baud_rate (STB_GLOBAL)
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
<code>struct ktermios *termios</code> ➡️ <code>const struct ktermios *termios</code>
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
