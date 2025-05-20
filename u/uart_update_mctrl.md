# Function: <code>uart_update_mctrl</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff81501a2b)
Location: drivers/tty/serial/serial_core.c:114
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_tiocmset
  - drivers/tty/serial/serial_core.c:uart_dtr_rts
  - drivers/tty/serial/serial_core.c:uart_dtr_rts
  - drivers/tty/serial/serial_core.c:uart_throttle
  - drivers/tty/serial/serial_core.c:uart_unthrottle
  - drivers/tty/serial/serial_core.c:uart_shutdown
  - drivers/tty/serial/serial_core.c:uart_set_termios
  - drivers/tty/serial/serial_core.c:uart_set_termios
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void uart_update_mctrl(struct uart_port *port, unsigned int set, unsigned int clear);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff81550600)
Location: drivers/tty/serial/serial_core.c:150
Inline: False
Direct callers:
  - drivers/tty/serial/serial_core.c:uart_dtr_rts
  - drivers/tty/serial/serial_core.c:uart_dtr_rts
  - drivers/tty/serial/serial_core.c:uart_set_termios
  - drivers/tty/serial/serial_core.c:uart_set_termios
  - drivers/tty/serial/serial_core.c:uart_tiocmset
  - drivers/tty/serial/serial_core.c:uart_unthrottle
  - drivers/tty/serial/serial_core.c:uart_throttle
  - drivers/tty/serial/serial_core.c:uart_shutdown
  - drivers/tty/serial/serial_core.c:uart_startup
```
**Symbols:**

```
ffffffff81550600-ffffffff8155065f: uart_update_mctrl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void uart_update_mctrl(struct uart_port *port, unsigned int set, unsigned int clear);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff8157ce80)
Location: drivers/tty/serial/serial_core.c:151
Inline: False
Direct callers:
  - drivers/tty/serial/serial_core.c:uart_dtr_rts
  - drivers/tty/serial/serial_core.c:uart_dtr_rts
  - drivers/tty/serial/serial_core.c:uart_set_termios
  - drivers/tty/serial/serial_core.c:uart_set_termios
  - drivers/tty/serial/serial_core.c:uart_tiocmset
  - drivers/tty/serial/serial_core.c:uart_unthrottle
  - drivers/tty/serial/serial_core.c:uart_throttle
  - drivers/tty/serial/serial_core.c:uart_shutdown
```
**Symbols:**

```
ffffffff8157ce80-ffffffff8157cedf: uart_update_mctrl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void uart_update_mctrl(struct uart_port *port, unsigned int set, unsigned int clear);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff815910f0)
Location: drivers/tty/serial/serial_core.c:152
Inline: False
Direct callers:
  - drivers/tty/serial/serial_core.c:uart_dtr_rts
  - drivers/tty/serial/serial_core.c:uart_dtr_rts
  - drivers/tty/serial/serial_core.c:uart_set_termios
  - drivers/tty/serial/serial_core.c:uart_set_termios
  - drivers/tty/serial/serial_core.c:uart_tiocmset
  - drivers/tty/serial/serial_core.c:uart_unthrottle
  - drivers/tty/serial/serial_core.c:uart_throttle
  - drivers/tty/serial/serial_core.c:uart_shutdown
```
**Symbols:**

```
ffffffff815910f0-ffffffff8159114f: uart_update_mctrl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void uart_update_mctrl(struct uart_port *port, unsigned int set, unsigned int clear);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff815f5b80)
Location: drivers/tty/serial/serial_core.c:139
Inline: False
Direct callers:
  - drivers/tty/serial/serial_core.c:uart_set_termios
  - drivers/tty/serial/serial_core.c:uart_set_termios
  - drivers/tty/serial/serial_core.c:uart_tiocmset
  - drivers/tty/serial/serial_core.c:uart_unthrottle
  - drivers/tty/serial/serial_core.c:uart_throttle
```
**Symbols:**

```
ffffffff815f5b80-ffffffff815f5be5: uart_update_mctrl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void uart_update_mctrl(struct uart_port *port, unsigned int set, unsigned int clear);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff8162ed90)
Location: drivers/tty/serial/serial_core.c:139
Inline: False
Direct callers:
  - drivers/tty/serial/serial_core.c:uart_set_termios
  - drivers/tty/serial/serial_core.c:uart_set_termios
  - drivers/tty/serial/serial_core.c:uart_tiocmset
  - drivers/tty/serial/serial_core.c:uart_unthrottle
  - drivers/tty/serial/serial_core.c:uart_throttle
```
**Symbols:**

```
ffffffff8162ed90-ffffffff8162edf5: uart_update_mctrl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void uart_update_mctrl(struct uart_port *port, unsigned int set, unsigned int clear);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff8164cf10)
Location: drivers/tty/serial/serial_core.c:142
Inline: False
Direct callers:
  - drivers/tty/serial/serial_core.c:uart_set_termios
  - drivers/tty/serial/serial_core.c:uart_set_termios
  - drivers/tty/serial/serial_core.c:uart_tiocmset
  - drivers/tty/serial/serial_core.c:uart_unthrottle
  - drivers/tty/serial/serial_core.c:uart_throttle
```
**Symbols:**

```
ffffffff8164cf10-ffffffff8164cf75: uart_update_mctrl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void uart_update_mctrl(struct uart_port *port, unsigned int set, unsigned int clear);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff81681a40)
Location: drivers/tty/serial/serial_core.c:139
Inline: False
Direct callers:
  - drivers/tty/serial/serial_core.c:uart_set_termios
  - drivers/tty/serial/serial_core.c:uart_set_termios
  - drivers/tty/serial/serial_core.c:uart_tiocmset
  - drivers/tty/serial/serial_core.c:uart_unthrottle
  - drivers/tty/serial/serial_core.c:uart_throttle
  - drivers/tty/serial/serial_core.c:uart_port_dtr_rts
  - drivers/tty/serial/serial_core.c:uart_port_dtr_rts
```
**Symbols:**

```
ffffffff81681a40-ffffffff81681aa5: uart_update_mctrl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void uart_update_mctrl(struct uart_port *port, unsigned int set, unsigned int clear);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff816a40f0)
Location: drivers/tty/serial/serial_core.c:140
Inline: False
Direct callers:
  - drivers/tty/serial/serial_core.c:uart_set_termios
  - drivers/tty/serial/serial_core.c:uart_set_termios
  - drivers/tty/serial/serial_core.c:uart_tiocmset
  - drivers/tty/serial/serial_core.c:uart_unthrottle
  - drivers/tty/serial/serial_core.c:uart_throttle
  - drivers/tty/serial/serial_core.c:uart_port_dtr_rts
  - drivers/tty/serial/serial_core.c:uart_port_dtr_rts
```
**Symbols:**

```
ffffffff816a40f0-ffffffff816a4155: uart_update_mctrl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void uart_update_mctrl(struct uart_port *port, unsigned int set, unsigned int clear);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff81759ec6)
Location: drivers/tty/serial/serial_core.c:141
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_set_termios
  - drivers/tty/serial/serial_core.c:uart_set_termios
  - drivers/tty/serial/serial_core.c:uart_unthrottle
  - drivers/tty/serial/serial_core.c:uart_throttle
  - drivers/tty/serial/serial_core.c:uart_port_dtr_rts
  - drivers/tty/serial/serial_core.c:uart_port_dtr_rts
  - drivers/tty/serial/serial_core.c:uart_port_dtr_rts
Direct callers:
  - drivers/tty/serial/serial_core.c:uart_tiocmset
  - drivers/tty/serial/serial_core.c:uart_port_dtr_rts
```
**Symbols:**

```
ffffffff81756970-ffffffff817569d5: uart_update_mctrl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void uart_update_mctrl(struct uart_port *port, unsigned int set, unsigned int clear);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff81774fa6)
Location: drivers/tty/serial/serial_core.c:142
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_set_termios
  - drivers/tty/serial/serial_core.c:uart_set_termios
  - drivers/tty/serial/serial_core.c:uart_unthrottle
  - drivers/tty/serial/serial_core.c:uart_throttle
  - drivers/tty/serial/serial_core.c:uart_port_dtr_rts
  - drivers/tty/serial/serial_core.c:uart_port_dtr_rts
  - drivers/tty/serial/serial_core.c:uart_port_dtr_rts
Direct callers:
  - drivers/tty/serial/serial_core.c:uart_tiocmset
  - drivers/tty/serial/serial_core.c:uart_port_dtr_rts
```
**Symbols:**

```
ffffffff81771af0-ffffffff81771b55: uart_update_mctrl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void uart_update_mctrl(struct uart_port *port, unsigned int set, unsigned int clear);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff81758456)
Location: drivers/tty/serial/serial_core.c:142
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_set_termios
  - drivers/tty/serial/serial_core.c:uart_set_termios
  - drivers/tty/serial/serial_core.c:uart_unthrottle
  - drivers/tty/serial/serial_core.c:uart_throttle
  - drivers/tty/serial/serial_core.c:uart_port_dtr_rts
  - drivers/tty/serial/serial_core.c:uart_port_dtr_rts
  - drivers/tty/serial/serial_core.c:uart_port_dtr_rts
Direct callers:
  - drivers/tty/serial/serial_core.c:uart_tiocmset
  - drivers/tty/serial/serial_core.c:uart_port_dtr_rts
```
**Symbols:**

```
ffffffff817555b0-ffffffff81755615: uart_update_mctrl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void uart_update_mctrl(struct uart_port *port, unsigned int set, unsigned int clear);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff817dbcf6)
Location: drivers/tty/serial/serial_core.c:142
Inline: True
Inline callers:
  - drivers/tty/serial/serial_core.c:uart_set_termios
  - drivers/tty/serial/serial_core.c:uart_set_termios
  - drivers/tty/serial/serial_core.c:uart_unthrottle
  - drivers/tty/serial/serial_core.c:uart_throttle
  - drivers/tty/serial/serial_core.c:uart_port_dtr_rts
  - drivers/tty/serial/serial_core.c:uart_port_dtr_rts
  - drivers/tty/serial/serial_core.c:uart_port_dtr_rts
Direct callers:
  - drivers/tty/serial/serial_core.c:uart_tiocmset
  - drivers/tty/serial/serial_core.c:uart_port_dtr_rts
```
**Symbols:**

```
ffffffff817d8ce0-ffffffff817d8d45: uart_update_mctrl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void uart_update_mctrl(struct uart_port *port, unsigned int set, unsigned int clear);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff819170e0)
Location: drivers/tty/serial/serial_core.c:149
Inline: False
Direct callers:
  - drivers/tty/serial/serial_core.c:uart_dtr_rts
  - drivers/tty/serial/serial_core.c:uart_dtr_rts
  - drivers/tty/serial/serial_core.c:uart_set_termios
  - drivers/tty/serial/serial_core.c:uart_set_termios
  - drivers/tty/serial/serial_core.c:uart_tiocmset
  - drivers/tty/serial/serial_core.c:uart_unthrottle
  - drivers/tty/serial/serial_core.c:uart_throttle
  - drivers/tty/serial/serial_core.c:uart_shutdown
  - drivers/tty/serial/serial_core.c:uart_port_startup
```
**Symbols:**

```
ffffffff819170e0-ffffffff81917164: uart_update_mctrl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void uart_update_mctrl(struct uart_port *port, unsigned int set, unsigned int clear);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff81a72510)
Location: drivers/tty/serial/serial_core.c:156
Inline: False
Direct callers:
  - drivers/tty/serial/serial_core.c:uart_dtr_rts
  - drivers/tty/serial/serial_core.c:uart_dtr_rts
  - drivers/tty/serial/serial_core.c:uart_set_termios
  - drivers/tty/serial/serial_core.c:uart_set_termios
  - drivers/tty/serial/serial_core.c:uart_tiocmset
  - drivers/tty/serial/serial_core.c:uart_unthrottle
  - drivers/tty/serial/serial_core.c:uart_throttle
  - drivers/tty/serial/serial_core.c:uart_shutdown
  - drivers/tty/serial/serial_core.c:uart_port_startup
```
**Symbols:**

```
ffffffff81a72510-ffffffff81a7258c: uart_update_mctrl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void uart_update_mctrl(struct uart_port *port, unsigned int set, unsigned int clear);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff81abcdd0)
Location: drivers/tty/serial/serial_core.c:178
Inline: False
Direct callers:
  - drivers/tty/serial/serial_core.c:uart_dtr_rts
  - drivers/tty/serial/serial_core.c:uart_dtr_rts
  - drivers/tty/serial/serial_core.c:uart_set_termios
  - drivers/tty/serial/serial_core.c:uart_set_termios
  - drivers/tty/serial/serial_core.c:uart_tiocmset
  - drivers/tty/serial/serial_core.c:uart_unthrottle
  - drivers/tty/serial/serial_core.c:uart_throttle
  - drivers/tty/serial/serial_core.c:uart_shutdown
  - drivers/tty/serial/serial_core.c:uart_port_startup
```
**Symbols:**

```
ffffffff81abcdd0-ffffffff81abce4c: uart_update_mctrl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void uart_update_mctrl(struct uart_port *port, unsigned int set, unsigned int clear);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff81b0fbc0)
Location: drivers/tty/serial/serial_core.c:177
Inline: False
Direct callers:
  - drivers/tty/serial/serial_core.c:uart_dtr_rts
  - drivers/tty/serial/serial_core.c:uart_dtr_rts
  - drivers/tty/serial/serial_core.c:uart_set_termios
  - drivers/tty/serial/serial_core.c:uart_set_termios
  - drivers/tty/serial/serial_core.c:uart_tiocmset
  - drivers/tty/serial/serial_core.c:uart_unthrottle
  - drivers/tty/serial/serial_core.c:uart_throttle
  - drivers/tty/serial/serial_core.c:uart_shutdown
  - drivers/tty/serial/serial_core.c:uart_port_startup
```
**Symbols:**

```
ffffffff81b0fbc0-ffffffff81b0fc3c: uart_update_mctrl (STB_LOCAL)
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
void uart_update_mctrl(struct uart_port *port, unsigned int set, unsigned int clear);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffff80001087e7b0)
Location: drivers/tty/serial/serial_core.c:140
Inline: False
Direct callers:
  - drivers/tty/serial/serial_core.c:uart_set_termios
  - drivers/tty/serial/serial_core.c:uart_set_termios
  - drivers/tty/serial/serial_core.c:uart_tiocmset
  - drivers/tty/serial/serial_core.c:uart_unthrottle
  - drivers/tty/serial/serial_core.c:uart_throttle
  - drivers/tty/serial/serial_core.c:uart_port_dtr_rts
```
**Symbols:**

```
ffff80001087e7b0-ffff80001087e878: uart_update_mctrl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void uart_update_mctrl(struct uart_port *port, unsigned int set, unsigned int clear);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (c097d250)
Location: drivers/tty/serial/serial_core.c:140
Inline: False
Direct callers:
  - drivers/tty/serial/serial_core.c:uart_set_termios
  - drivers/tty/serial/serial_core.c:uart_set_termios
  - drivers/tty/serial/serial_core.c:uart_tiocmset
  - drivers/tty/serial/serial_core.c:uart_unthrottle
  - drivers/tty/serial/serial_core.c:uart_throttle
  - drivers/tty/serial/serial_core.c:uart_port_dtr_rts
```
**Symbols:**

```
c097d250-c097d2b0: uart_update_mctrl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void uart_update_mctrl(struct uart_port *port, unsigned int set, unsigned int clear);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (c0000000009229c0)
Location: drivers/tty/serial/serial_core.c:140
Inline: False
Direct callers:
  - drivers/tty/serial/serial_core.c:uart_set_termios
  - drivers/tty/serial/serial_core.c:uart_set_termios
  - drivers/tty/serial/serial_core.c:uart_tiocmset
  - drivers/tty/serial/serial_core.c:uart_unthrottle
  - drivers/tty/serial/serial_core.c:uart_throttle
  - drivers/tty/serial/serial_core.c:uart_port_dtr_rts
  - drivers/tty/serial/serial_core.c:uart_port_dtr_rts
```
**Symbols:**

```
c0000000009229c0-c000000000922a6c: uart_update_mctrl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void uart_update_mctrl(struct uart_port *port, unsigned int set, unsigned int clear);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffe00054b1b2)
Location: drivers/tty/serial/serial_core.c:140
Inline: False
Direct callers:
  - drivers/tty/serial/serial_core.c:uart_set_termios
  - drivers/tty/serial/serial_core.c:uart_set_termios
  - drivers/tty/serial/serial_core.c:uart_tiocmset
  - drivers/tty/serial/serial_core.c:uart_unthrottle
  - drivers/tty/serial/serial_core.c:uart_throttle
  - drivers/tty/serial/serial_core.c:uart_port_dtr_rts
```
**Symbols:**

```
ffffffe00054b1b2-ffffffe00054b21a: uart_update_mctrl (STB_LOCAL)
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
void uart_update_mctrl(struct uart_port *port, unsigned int set, unsigned int clear);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff81669b50)
Location: drivers/tty/serial/serial_core.c:140
Inline: False
Direct callers:
  - drivers/tty/serial/serial_core.c:uart_set_termios
  - drivers/tty/serial/serial_core.c:uart_set_termios
  - drivers/tty/serial/serial_core.c:uart_tiocmset
  - drivers/tty/serial/serial_core.c:uart_unthrottle
  - drivers/tty/serial/serial_core.c:uart_throttle
  - drivers/tty/serial/serial_core.c:uart_port_dtr_rts
  - drivers/tty/serial/serial_core.c:uart_port_dtr_rts
```
**Symbols:**

```
ffffffff81669b50-ffffffff81669bb5: uart_update_mctrl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void uart_update_mctrl(struct uart_port *port, unsigned int set, unsigned int clear);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff81648cc0)
Location: drivers/tty/serial/serial_core.c:140
Inline: False
Direct callers:
  - drivers/tty/serial/serial_core.c:uart_set_termios
  - drivers/tty/serial/serial_core.c:uart_set_termios
  - drivers/tty/serial/serial_core.c:uart_tiocmset
  - drivers/tty/serial/serial_core.c:uart_unthrottle
  - drivers/tty/serial/serial_core.c:uart_throttle
  - drivers/tty/serial/serial_core.c:uart_port_dtr_rts
  - drivers/tty/serial/serial_core.c:uart_port_dtr_rts
```
**Symbols:**

```
ffffffff81648cc0-ffffffff81648d25: uart_update_mctrl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void uart_update_mctrl(struct uart_port *port, unsigned int set, unsigned int clear);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff81697f30)
Location: drivers/tty/serial/serial_core.c:140
Inline: False
Direct callers:
  - drivers/tty/serial/serial_core.c:uart_set_termios
  - drivers/tty/serial/serial_core.c:uart_set_termios
  - drivers/tty/serial/serial_core.c:uart_tiocmset
  - drivers/tty/serial/serial_core.c:uart_unthrottle
  - drivers/tty/serial/serial_core.c:uart_throttle
  - drivers/tty/serial/serial_core.c:uart_port_dtr_rts
  - drivers/tty/serial/serial_core.c:uart_port_dtr_rts
```
**Symbols:**

```
ffffffff81697f30-ffffffff81697f95: uart_update_mctrl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void uart_update_mctrl(struct uart_port *port, unsigned int set, unsigned int clear);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff816b24b0)
Location: drivers/tty/serial/serial_core.c:140
Inline: False
Direct callers:
  - drivers/tty/serial/serial_core.c:uart_set_termios
  - drivers/tty/serial/serial_core.c:uart_set_termios
  - drivers/tty/serial/serial_core.c:uart_tiocmset
  - drivers/tty/serial/serial_core.c:uart_unthrottle
  - drivers/tty/serial/serial_core.c:uart_throttle
  - drivers/tty/serial/serial_core.c:uart_port_dtr_rts
  - drivers/tty/serial/serial_core.c:uart_port_dtr_rts
```
**Symbols:**

```
ffffffff816b24b0-ffffffff816b2515: uart_update_mctrl (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
