# Function: <code>serial8250_get_divisor</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
unsigned int serial8250_get_divisor(struct uart_8250_port *up, unsigned int baud, unsigned int *frac);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffffffff81506980)
Location: drivers/tty/serial/8250/8250_port.c:2136
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
```
**Symbols:**

```
ffffffff81506980-ffffffff815069f9: serial8250_get_divisor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
unsigned int serial8250_get_divisor(struct uart_8250_port *up, unsigned int baud, unsigned int *frac);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffffffff81558150)
Location: drivers/tty/serial/8250/8250_port.c:2398
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
```
**Symbols:**

```
ffffffff81558150-ffffffff815581ca: serial8250_get_divisor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
unsigned int serial8250_get_divisor(struct uart_8250_port *up, unsigned int baud, unsigned int *frac);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffffffff81584960)
Location: drivers/tty/serial/8250/8250_port.c:2439
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
```
**Symbols:**

```
ffffffff81584960-ffffffff815849da: serial8250_get_divisor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
unsigned int serial8250_get_divisor(struct uart_8250_port *up, unsigned int baud, unsigned int *frac);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffffffff81598880)
Location: drivers/tty/serial/8250/8250_port.c:2468
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
```
**Symbols:**

```
ffffffff81598880-ffffffff815988fb: serial8250_get_divisor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
unsigned int serial8250_get_divisor(struct uart_8250_port *up, unsigned int baud, unsigned int *frac);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffffffff815fd650)
Location: drivers/tty/serial/8250/8250_port.c:2517
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
```
**Symbols:**

```
ffffffff815fd650-ffffffff815fd6eb: serial8250_get_divisor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
unsigned int serial8250_get_divisor(struct uart_8250_port *up, unsigned int baud, unsigned int *frac);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffffffff81637020)
Location: drivers/tty/serial/8250/8250_port.c:2500
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
```
**Symbols:**

```
ffffffff81637020-ffffffff816370ba: serial8250_get_divisor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
unsigned int serial8250_get_divisor(struct uart_port *port, unsigned int baud, unsigned int *frac);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffffffff81655530)
Location: drivers/tty/serial/8250/8250_port.c:2532
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
```
**Symbols:**

```
ffffffff81655530-ffffffff816555da: serial8250_get_divisor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
unsigned int serial8250_get_divisor(struct uart_port *port, unsigned int baud, unsigned int *frac);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffffffff816896e0)
Location: drivers/tty/serial/8250/8250_port.c:2524
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
```
**Symbols:**

```
ffffffff816896e0-ffffffff8168978e: serial8250_get_divisor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
unsigned int serial8250_get_divisor(struct uart_port *port, unsigned int baud, unsigned int *frac);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffffffff816ac880)
Location: drivers/tty/serial/8250/8250_port.c:2454
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
```
**Symbols:**

```
ffffffff816ac880-ffffffff816ac909: serial8250_get_divisor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
unsigned int serial8250_get_divisor(struct uart_port *port, unsigned int baud, unsigned int *frac);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffffffff8175ecf0)
Location: drivers/tty/serial/8250/8250_port.c:2536
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_restore
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
```
**Symbols:**

```
ffffffff8175ecf0-ffffffff8175ed75: serial8250_get_divisor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
unsigned int serial8250_get_divisor(struct uart_port *port, unsigned int baud, unsigned int *frac);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffffffff81779b70)
Location: drivers/tty/serial/8250/8250_port.c:2537
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_restore
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_port.c:serial8250_update_uartclk
```
**Symbols:**

```
ffffffff81779b70-ffffffff81779bf5: serial8250_get_divisor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
unsigned int serial8250_get_divisor(struct uart_port *port, unsigned int baud, unsigned int *frac);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffffffff8175d4a0)
Location: drivers/tty/serial/8250/8250_port.c:2550
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_port.c:serial8250_update_uartclk
```
**Symbols:**

```
ffffffff8175d4a0-ffffffff8175d525: serial8250_get_divisor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
unsigned int serial8250_get_divisor(struct uart_port *port, unsigned int baud, unsigned int *frac);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffffffff817e1260)
Location: drivers/tty/serial/8250/8250_port.c:2570
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_port.c:serial8250_update_uartclk
```
**Symbols:**

```
ffffffff817e1260-ffffffff817e12f9: serial8250_get_divisor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
unsigned int serial8250_get_divisor(struct uart_port *port, unsigned int baud, unsigned int *frac);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffffffff81920020)
Location: drivers/tty/serial/8250/8250_port.c:2592
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_port.c:serial8250_update_uartclk
```
**Symbols:**

```
ffffffff81920020-ffffffff819200dd: serial8250_get_divisor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
unsigned int serial8250_get_divisor(struct uart_port *port, unsigned int baud, unsigned int *frac);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffffffff81a7c6d0)
Location: drivers/tty/serial/8250/8250_port.c:2596
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_port.c:serial8250_update_uartclk
```
**Symbols:**

```
ffffffff81a7c6d0-ffffffff81a7c78d: serial8250_get_divisor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
unsigned int serial8250_get_divisor(struct uart_port *port, unsigned int baud, unsigned int *frac);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffffffff81ac7f80)
Location: drivers/tty/serial/8250/8250_port.c:2613
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_port.c:serial8250_update_uartclk
```
**Symbols:**

```
ffffffff81ac7f80-ffffffff81ac803d: serial8250_get_divisor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
unsigned int serial8250_get_divisor(struct uart_port *port, unsigned int baud, unsigned int *frac);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffffffff81b1b030)
Location: drivers/tty/serial/8250/8250_port.c:2615
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_port.c:serial8250_update_uartclk
```
**Symbols:**

```
ffffffff81b1b030-ffffffff81b1b0ed: serial8250_get_divisor (STB_LOCAL)
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
unsigned int serial8250_get_divisor(struct uart_port *port, unsigned int baud, unsigned int *frac);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffff800010887590)
Location: drivers/tty/serial/8250/8250_port.c:2454
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
```
**Symbols:**

```
ffff800010887590-ffff800010887654: serial8250_get_divisor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
unsigned int serial8250_get_divisor(struct uart_port *port, unsigned int baud, unsigned int *frac);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (c0985be8)
Location: drivers/tty/serial/8250/8250_port.c:2454
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
```
**Symbols:**

```
c0985be8-c0985c98: serial8250_get_divisor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
unsigned int serial8250_get_divisor(struct uart_port *port, unsigned int baud, unsigned int *frac);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (c00000000092ea00)
Location: drivers/tty/serial/8250/8250_port.c:2454
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
```
**Symbols:**

```
c00000000092ea00-c00000000092eb40: serial8250_get_divisor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
unsigned int serial8250_get_divisor(struct uart_port *port, unsigned int baud, unsigned int *frac);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffffffe00055241e)
Location: drivers/tty/serial/8250/8250_port.c:2454
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
```
**Symbols:**

```
ffffffe00055241e-ffffffe0005524c8: serial8250_get_divisor (STB_LOCAL)
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
unsigned int serial8250_get_divisor(struct uart_port *port, unsigned int baud, unsigned int *frac);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffffffff816722f0)
Location: drivers/tty/serial/8250/8250_port.c:2454
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
```
**Symbols:**

```
ffffffff816722f0-ffffffff81672379: serial8250_get_divisor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
unsigned int serial8250_get_divisor(struct uart_port *port, unsigned int baud, unsigned int *frac);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffffffff816513f0)
Location: drivers/tty/serial/8250/8250_port.c:2454
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
```
**Symbols:**

```
ffffffff816513f0-ffffffff81651479: serial8250_get_divisor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
unsigned int serial8250_get_divisor(struct uart_port *port, unsigned int baud, unsigned int *frac);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffffffff816a06c0)
Location: drivers/tty/serial/8250/8250_port.c:2454
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
```
**Symbols:**

```
ffffffff816a06c0-ffffffff816a0749: serial8250_get_divisor (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
unsigned int serial8250_get_divisor(struct uart_port *port, unsigned int baud, unsigned int *frac);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffffffff816bab80)
Location: drivers/tty/serial/8250/8250_port.c:2454
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
```
**Symbols:**

```
ffffffff816bab80-ffffffff816bac09: serial8250_get_divisor (STB_LOCAL)
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
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct uart_port *port</code>
</li>
<li>
<b>Param removed. </b>
<code>struct uart_8250_port *up</code>
</li>
</ul>
</details>
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
