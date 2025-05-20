# Function: <code>serial8250_set_divisor</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffffffff81507590)
Location: drivers/tty/serial/8250/8250_port.c:2206
Inline: True
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
```
**Symbols:**

```
ffffffff81507590-ffffffff81507605: serial8250_set_divisor.isra.10 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffffffff81558da0)
Location: drivers/tty/serial/8250/8250_port.c:2468
Inline: True
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
```
**Symbols:**

```
ffffffff81558da0-ffffffff81558e15: serial8250_set_divisor.isra.10 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffffffff815855b0)
Location: drivers/tty/serial/8250/8250_port.c:2509
Inline: True
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
```
**Symbols:**

```
ffffffff815855b0-ffffffff81585625: serial8250_set_divisor.isra.11 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffffffff81599420)
Location: drivers/tty/serial/8250/8250_port.c:2538
Inline: True
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
```
**Symbols:**

```
ffffffff81599420-ffffffff81599490: serial8250_set_divisor.isra.18 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffffffff815fe2a0)
Location: drivers/tty/serial/8250/8250_port.c:2589
Inline: True
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
```
**Symbols:**

```
ffffffff815fe2a0-ffffffff815fe33a: serial8250_set_divisor.isra.18 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffffffff81637bc0)
Location: drivers/tty/serial/8250/8250_port.c:2572
Inline: True
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
```
**Symbols:**

```
ffffffff81637bc0-ffffffff81637c5a: serial8250_set_divisor.isra.18 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void serial8250_set_divisor(struct uart_port *port, unsigned int baud, unsigned int quot, unsigned int quot_frac);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffffffff81655960)
Location: drivers/tty/serial/8250/8250_port.c:2614
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
```
**Symbols:**

```
ffffffff81655960-ffffffff81655980: serial8250_set_divisor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void serial8250_set_divisor(struct uart_port *port, unsigned int baud, unsigned int quot, unsigned int quot_frac);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffffffff81689b10)
Location: drivers/tty/serial/8250/8250_port.c:2606
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
```
**Symbols:**

```
ffffffff81689b10-ffffffff81689b30: serial8250_set_divisor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void serial8250_set_divisor(struct uart_port *port, unsigned int baud, unsigned int quot, unsigned int quot_frac);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffffffff816ab750)
Location: drivers/tty/serial/8250/8250_port.c:2529
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
```
**Symbols:**

```
ffffffff816ab750-ffffffff816ab770: serial8250_set_divisor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffffffff8175fa11)
Location: drivers/tty/serial/8250/8250_port.c:2611
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_restore
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffffffff8177a7e1)
Location: drivers/tty/serial/8250/8250_port.c:2612
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_restore
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_port.c:serial8250_update_uartclk
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffffffff81761ca9)
Location: drivers/tty/serial/8250/8250_port.c:2625
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_port.c:serial8250_update_uartclk
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffffffff817e5d09)
Location: drivers/tty/serial/8250/8250_port.c:2645
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_port.c:serial8250_update_uartclk
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffffffff81925139)
Location: drivers/tty/serial/8250/8250_port.c:2651
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_port.c:serial8250_update_uartclk
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffffffff81a81a5a)
Location: drivers/tty/serial/8250/8250_port.c:2655
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_port.c:serial8250_update_uartclk
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffffffff81acd04a)
Location: drivers/tty/serial/8250/8250_port.c:2669
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_port.c:serial8250_update_uartclk
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffffffff81b2011f)
Location: drivers/tty/serial/8250/8250_port.c:2671
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_port.c:serial8250_update_uartclk
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
void serial8250_set_divisor(struct uart_port *port, unsigned int baud, unsigned int quot, unsigned int quot_frac);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffff800010886160)
Location: drivers/tty/serial/8250/8250_port.c:2529
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
```
**Symbols:**

```
ffff800010886160-ffff8000108861c8: serial8250_set_divisor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void serial8250_set_divisor(struct uart_port *port, unsigned int baud, unsigned int quot, unsigned int quot_frac);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (c0984720)
Location: drivers/tty/serial/8250/8250_port.c:2529
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
```
**Symbols:**

```
c0984720-c0984750: serial8250_set_divisor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void serial8250_set_divisor(struct uart_port *port, unsigned int baud, unsigned int quot, unsigned int quot_frac);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (c00000000092cd30)
Location: drivers/tty/serial/8250/8250_port.c:2529
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
```
**Symbols:**

```
c00000000092cd30-c00000000092cd84: serial8250_set_divisor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void serial8250_set_divisor(struct uart_port *port, unsigned int baud, unsigned int quot, unsigned int quot_frac);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffffffe000551418)
Location: drivers/tty/serial/8250/8250_port.c:2529
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
```
**Symbols:**

```
ffffffe000551418-ffffffe000551470: serial8250_set_divisor (STB_LOCAL)
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
void serial8250_set_divisor(struct uart_port *port, unsigned int baud, unsigned int quot, unsigned int quot_frac);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffffffff816711c0)
Location: drivers/tty/serial/8250/8250_port.c:2529
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
```
**Symbols:**

```
ffffffff816711c0-ffffffff816711e0: serial8250_set_divisor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void serial8250_set_divisor(struct uart_port *port, unsigned int baud, unsigned int quot, unsigned int quot_frac);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffffffff816502c0)
Location: drivers/tty/serial/8250/8250_port.c:2529
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
```
**Symbols:**

```
ffffffff816502c0-ffffffff816502e0: serial8250_set_divisor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void serial8250_set_divisor(struct uart_port *port, unsigned int baud, unsigned int quot, unsigned int quot_frac);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffffffff8169f590)
Location: drivers/tty/serial/8250/8250_port.c:2529
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
```
**Symbols:**

```
ffffffff8169f590-ffffffff8169f5b0: serial8250_set_divisor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void serial8250_set_divisor(struct uart_port *port, unsigned int baud, unsigned int quot, unsigned int quot_frac);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffffffff816b9a50)
Location: drivers/tty/serial/8250/8250_port.c:2529
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
```
**Symbols:**

```
ffffffff816b9a50-ffffffff816b9a70: serial8250_set_divisor (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
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
