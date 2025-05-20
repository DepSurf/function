# Function: <code>wait_for_xmitr</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Collision ⚠️</summary>

```c
void wait_for_xmitr(struct uart_8250_port *up, int bits);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffffffff815068b0)
Location: drivers/tty/serial/8250/8250_port.c:1717
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_putchar
  - drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char
  - drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
```
```
In drivers/tty/serial/8250/8250_early.c (ffffffff81fa758d)
Location: drivers/tty/serial/8250/8250_early.c:76
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_early.c:early_serial8250_write
  - drivers/tty/serial/8250/8250_early.c:serial_putc
```
**Symbols:**

```
ffffffff815068b0-ffffffff81506941: wait_for_xmitr (STB_LOCAL)
ffffffff81fa758d-ffffffff81fa75b1: wait_for_xmitr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void wait_for_xmitr(struct uart_8250_port *up, int bits);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffffffff81558080)
Location: drivers/tty/serial/8250/8250_port.c:1976
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_putchar
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char
  - drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char
```
**Symbols:**

```
ffffffff81558080-ffffffff81558111: wait_for_xmitr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void wait_for_xmitr(struct uart_8250_port *up, int bits);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffffffff81584890)
Location: drivers/tty/serial/8250/8250_port.c:1997
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_putchar
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char
  - drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char
```
**Symbols:**

```
ffffffff81584890-ffffffff81584926: wait_for_xmitr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void wait_for_xmitr(struct uart_8250_port *up, int bits);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffffffff815987b0)
Location: drivers/tty/serial/8250/8250_port.c:2009
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_putchar
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char
  - drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char
```
**Symbols:**

```
ffffffff815987b0-ffffffff81598850: wait_for_xmitr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void wait_for_xmitr(struct uart_8250_port *up, int bits);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffffffff815fd560)
Location: drivers/tty/serial/8250/8250_port.c:2040
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_putchar
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char
  - drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char
```
**Symbols:**

```
ffffffff815fd560-ffffffff815fd60c: wait_for_xmitr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void wait_for_xmitr(struct uart_8250_port *up, int bits);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffffffff81636f30)
Location: drivers/tty/serial/8250/8250_port.c:2023
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_putchar
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char
  - drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char
```
**Symbols:**

```
ffffffff81636f30-ffffffff81636fdc: wait_for_xmitr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void wait_for_xmitr(struct uart_8250_port *up, int bits);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffffffff81655440)
Location: drivers/tty/serial/8250/8250_port.c:2022
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_putchar
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char
  - drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char
```
**Symbols:**

```
ffffffff81655440-ffffffff816554ec: wait_for_xmitr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void wait_for_xmitr(struct uart_8250_port *up, int bits);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffffffff816895f0)
Location: drivers/tty/serial/8250/8250_port.c:2014
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_putchar
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char
  - drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char
```
**Symbols:**

```
ffffffff816895f0-ffffffff8168969b: wait_for_xmitr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void wait_for_xmitr(struct uart_8250_port *up, int bits);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffffffff816abd10)
Location: drivers/tty/serial/8250/8250_port.c:1963
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_putchar
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char
  - drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char
```
**Symbols:**

```
ffffffff816abd10-ffffffff816abdbb: wait_for_xmitr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void wait_for_xmitr(struct uart_8250_port *up, int bits);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffffffff8175e930)
Location: drivers/tty/serial/8250/8250_port.c:2054
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_putchar
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char
  - drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char
```
**Symbols:**

```
ffffffff8175e930-ffffffff8175e9db: wait_for_xmitr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void wait_for_xmitr(struct uart_8250_port *up, int bits);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffffffff817797b0)
Location: drivers/tty/serial/8250/8250_port.c:2055
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_putchar
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char
  - drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char
```
**Symbols:**

```
ffffffff817797b0-ffffffff8177985b: wait_for_xmitr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void wait_for_xmitr(struct uart_8250_port *up, int bits);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffffffff8175d0e0)
Location: drivers/tty/serial/8250/8250_port.c:2068
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_putchar
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char
  - drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char
```
**Symbols:**

```
ffffffff8175d0e0-ffffffff8175d18b: wait_for_xmitr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void wait_for_xmitr(struct uart_8250_port *up, int bits);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffffffff817e0f70)
Location: drivers/tty/serial/8250/8250_port.c:2062
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_putchar
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char
  - drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char
```
**Symbols:**

```
ffffffff817e0f70-ffffffff817e101b: wait_for_xmitr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void wait_for_xmitr(struct uart_8250_port *up, int bits);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffffffff81920430)
Location: drivers/tty/serial/8250/8250_port.c:2096
Inline: True
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_putchar
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char
  - drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char
```
**Symbols:**

```
ffffffff81920430-ffffffff819204a0: wait_for_xmitr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void wait_for_xmitr(struct uart_8250_port *up, int bits);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffffffff81a7cb70)
Location: drivers/tty/serial/8250/8250_port.c:2100
Inline: True
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_putchar
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char
  - drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char
```
**Symbols:**

```
ffffffff81a7cb70-ffffffff81a7cbe0: wait_for_xmitr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void wait_for_xmitr(struct uart_8250_port *up, int bits);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffffffff81ac82c0)
Location: drivers/tty/serial/8250/8250_port.c:2093
Inline: True
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_putchar
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char
  - drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char
```
**Symbols:**

```
ffffffff81ac82c0-ffffffff81ac8330: wait_for_xmitr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void wait_for_xmitr(struct uart_8250_port *up, int bits);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffffffff81b1b370)
Location: drivers/tty/serial/8250/8250_port.c:2095
Inline: True
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_putchar
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char
  - drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char
```
**Symbols:**

```
ffffffff81b1b370-ffffffff81b1b3e0: wait_for_xmitr (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Collision ⚠️</summary>

```c
void wait_for_xmitr(struct uart_8250_port *up, int bits);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffff800010886930)
Location: drivers/tty/serial/8250/8250_port.c:1963
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_putchar
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char
  - drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char
```
```
In drivers/tty/serial/mvebu-uart.c (ffff8000108a5820)
Location: drivers/tty/serial/mvebu-uart.c:643
Inline: False
Direct callers:
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_console_write
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_console_putchar
```
**Symbols:**

```
ffff800010886930-ffff8000108869f8: wait_for_xmitr (STB_LOCAL)
ffff8000108a5820-ffff8000108a58b4: wait_for_xmitr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Collision, Selective Inline ⚠️</summary>

```c
void wait_for_xmitr(struct uart_8250_port *up, int bits);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (c0984f38)
Location: drivers/tty/serial/8250/8250_port.c:1963
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_putchar
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char
  - drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char
```
```
In drivers/tty/serial/omap-serial.c (c09a03f0)
Location: drivers/tty/serial/omap-serial.c:1164
Inline: True
Direct callers:
  - drivers/tty/serial/omap-serial.c:serial_omap_console_write
  - drivers/tty/serial/omap-serial.c:serial_omap_console_putchar
  - drivers/tty/serial/omap-serial.c:serial_omap_poll_put_char
```
```
In drivers/tty/serial/mvebu-uart.c (c09a141c)
Location: drivers/tty/serial/mvebu-uart.c:643
Inline: False
Direct callers:
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_console_write
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_console_putchar
```
**Symbols:**

```
c0984f38-c098501c: wait_for_xmitr (STB_LOCAL)
c09a03f0-c09a04d4: wait_for_xmitr (STB_LOCAL)
c09a141c-c09a14d4: wait_for_xmitr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void wait_for_xmitr(struct uart_8250_port *up, int bits);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (c00000000092d7f0)
Location: drivers/tty/serial/8250/8250_port.c:1963
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_putchar
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char
  - drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char
```
**Symbols:**

```
c00000000092d7f0-c00000000092d928: wait_for_xmitr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void wait_for_xmitr(struct uart_8250_port *up, int bits);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffffffe000551a00)
Location: drivers/tty/serial/8250/8250_port.c:1963
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_putchar
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
```
**Symbols:**

```
ffffffe000551a00-ffffffe000551ab6: wait_for_xmitr (STB_LOCAL)
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
void wait_for_xmitr(struct uart_8250_port *up, int bits);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffffffff81671780)
Location: drivers/tty/serial/8250/8250_port.c:1963
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_putchar
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char
  - drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char
```
**Symbols:**

```
ffffffff81671780-ffffffff8167182b: wait_for_xmitr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void wait_for_xmitr(struct uart_8250_port *up, int bits);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffffffff81650880)
Location: drivers/tty/serial/8250/8250_port.c:1963
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_putchar
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char
  - drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char
```
**Symbols:**

```
ffffffff81650880-ffffffff8165092b: wait_for_xmitr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void wait_for_xmitr(struct uart_8250_port *up, int bits);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffffffff8169fb50)
Location: drivers/tty/serial/8250/8250_port.c:1963
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_putchar
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char
  - drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char
```
**Symbols:**

```
ffffffff8169fb50-ffffffff8169fbfb: wait_for_xmitr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void wait_for_xmitr(struct uart_8250_port *up, int bits);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffffffff816ba010)
Location: drivers/tty/serial/8250/8250_port.c:1963
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_putchar
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_startup
  - drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char
  - drivers/tty/serial/8250/8250_port.c:serial8250_put_poll_char
```
**Symbols:**

```
ffffffff816ba010-ffffffff816ba0bb: wait_for_xmitr (STB_LOCAL)
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
