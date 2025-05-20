# Function: <code>serial8250_do_set_divisor</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void serial8250_do_set_divisor(struct uart_port *port, unsigned int baud, unsigned int quot, unsigned int quot_frac);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffffffff816558c0)
Location: drivers/tty/serial/8250/8250_port.c:2580
Inline: True
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_divisor
```
**Symbols:**

```
ffffffff816558c0-ffffffff8165595a: serial8250_do_set_divisor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void serial8250_do_set_divisor(struct uart_port *port, unsigned int baud, unsigned int quot, unsigned int quot_frac);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffffffff81689a70)
Location: drivers/tty/serial/8250/8250_port.c:2572
Inline: True
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_divisor
  - drivers/tty/serial/8250/8250_pci.c:pericom_do_set_divisor
```
**Symbols:**

```
ffffffff81689a70-ffffffff81689b0d: serial8250_do_set_divisor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void serial8250_do_set_divisor(struct uart_port *port, unsigned int baud, unsigned int quot, unsigned int quot_frac);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffffffff816ab6e0)
Location: drivers/tty/serial/8250/8250_port.c:2502
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_divisor
  - drivers/tty/serial/8250/8250_dwlib.c:dw8250_set_divisor
  - drivers/tty/serial/8250/8250_pci.c:pericom_do_set_divisor
```
**Symbols:**

```
ffffffff816ab6e0-ffffffff816ab741: serial8250_do_set_divisor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void serial8250_do_set_divisor(struct uart_port *port, unsigned int baud, unsigned int quot, unsigned int quot_frac);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffffffff8175e380)
Location: drivers/tty/serial/8250/8250_port.c:2584
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_restore
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_dwlib.c:dw8250_set_divisor
  - drivers/tty/serial/8250/8250_pci.c:pericom_do_set_divisor
```
**Symbols:**

```
ffffffff8175e380-ffffffff8175e3e1: serial8250_do_set_divisor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void serial8250_do_set_divisor(struct uart_port *port, unsigned int baud, unsigned int quot, unsigned int quot_frac);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffffffff81779200)
Location: drivers/tty/serial/8250/8250_port.c:2585
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_restore
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_port.c:serial8250_update_uartclk
  - drivers/tty/serial/8250/8250_dwlib.c:dw8250_set_divisor
  - drivers/tty/serial/8250/8250_pci.c:pericom_do_set_divisor
```
**Symbols:**

```
ffffffff81779200-ffffffff81779261: serial8250_do_set_divisor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void serial8250_do_set_divisor(struct uart_port *port, unsigned int baud, unsigned int quot, unsigned int quot_frac);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffffffff8175cb60)
Location: drivers/tty/serial/8250/8250_port.c:2598
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_port.c:serial8250_update_uartclk
  - drivers/tty/serial/8250/8250_dwlib.c:dw8250_set_divisor
  - drivers/tty/serial/8250/8250_pci.c:pericom_do_set_divisor
```
**Symbols:**

```
ffffffff8175cb60-ffffffff8175cbc1: serial8250_do_set_divisor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void serial8250_do_set_divisor(struct uart_port *port, unsigned int baud, unsigned int quot, unsigned int quot_frac);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffffffff817e0630)
Location: drivers/tty/serial/8250/8250_port.c:2618
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_port.c:serial8250_update_uartclk
  - drivers/tty/serial/8250/8250_dwlib.c:dw8250_set_divisor
```
**Symbols:**

```
ffffffff817e0630-ffffffff817e0691: serial8250_do_set_divisor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void serial8250_do_set_divisor(struct uart_port *port, unsigned int baud, unsigned int quot, unsigned int quot_frac);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffffffff8191f390)
Location: drivers/tty/serial/8250/8250_port.c:2624
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_port.c:serial8250_update_uartclk
  - drivers/tty/serial/8250/8250_dwlib.c:dw8250_set_divisor
  - drivers/tty/serial/8250/8250_pci.c:pci_oxsemi_tornado_set_divisor
```
**Symbols:**

```
ffffffff8191f390-ffffffff8191f3fa: serial8250_do_set_divisor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void serial8250_do_set_divisor(struct uart_port *port, unsigned int baud, unsigned int quot, unsigned int quot_frac);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffffffff81a7b830)
Location: drivers/tty/serial/8250/8250_port.c:2628
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_port.c:serial8250_update_uartclk
  - drivers/tty/serial/8250/8250_dwlib.c:dw8250_set_divisor
  - drivers/tty/serial/8250/8250_pci.c:pci_oxsemi_tornado_set_divisor
```
**Symbols:**

```
ffffffff81a7b830-ffffffff81a7b89a: serial8250_do_set_divisor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void serial8250_do_set_divisor(struct uart_port *port, unsigned int baud, unsigned int quot, unsigned int quot_frac);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffffffff81ac6fa0)
Location: drivers/tty/serial/8250/8250_port.c:2642
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_port.c:serial8250_update_uartclk
  - drivers/tty/serial/8250/8250_dwlib.c:dw8250_set_divisor
  - drivers/tty/serial/8250/8250_pci.c:pci_oxsemi_tornado_set_divisor
```
**Symbols:**

```
ffffffff81ac6fa0-ffffffff81ac700a: serial8250_do_set_divisor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void serial8250_do_set_divisor(struct uart_port *port, unsigned int baud, unsigned int quot, unsigned int quot_frac);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffffffff81b1a040)
Location: drivers/tty/serial/8250/8250_port.c:2644
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_termios
  - drivers/tty/serial/8250/8250_port.c:serial8250_update_uartclk
  - drivers/tty/serial/8250/8250_dwlib.c:dw8250_set_divisor
  - drivers/tty/serial/8250/8250_pci.c:pci_oxsemi_tornado_set_divisor
```
**Symbols:**

```
ffffffff81b1a040-ffffffff81b1a0aa: serial8250_do_set_divisor (STB_GLOBAL)
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
void serial8250_do_set_divisor(struct uart_port *port, unsigned int baud, unsigned int quot, unsigned int quot_frac);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffff8000108860d8)
Location: drivers/tty/serial/8250/8250_port.c:2502
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_divisor
  - drivers/tty/serial/8250/8250_dwlib.c:dw8250_set_divisor
  - drivers/tty/serial/8250/8250_pci.c:pericom_do_set_divisor
```
**Symbols:**

```
ffff8000108860d8-ffff80001088615c: serial8250_do_set_divisor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void serial8250_do_set_divisor(struct uart_port *port, unsigned int baud, unsigned int quot, unsigned int quot_frac);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (c09846cc)
Location: drivers/tty/serial/8250/8250_port.c:2502
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_divisor
  - drivers/tty/serial/8250/8250_dwlib.c:dw8250_set_divisor
  - drivers/tty/serial/8250/8250_pci.c:pericom_do_set_divisor
```
**Symbols:**

```
c09846cc-c0984720: serial8250_do_set_divisor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void serial8250_do_set_divisor(struct uart_port *port, unsigned int baud, unsigned int quot, unsigned int quot_frac);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (c00000000092cc50)
Location: drivers/tty/serial/8250/8250_port.c:2502
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_divisor
  - drivers/tty/serial/8250/8250_dwlib.c:dw8250_set_divisor
  - drivers/tty/serial/8250/8250_dwlib.c:dw8250_set_divisor
  - drivers/tty/serial/8250/8250_pci.c:pericom_do_set_divisor
```
**Symbols:**

```
c00000000092cc50-c00000000092cd28: serial8250_do_set_divisor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void serial8250_do_set_divisor(struct uart_port *port, unsigned int baud, unsigned int quot, unsigned int quot_frac);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffffffe0005513c4)
Location: drivers/tty/serial/8250/8250_port.c:2502
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_divisor
  - drivers/tty/serial/8250/8250_dwlib.c:dw8250_set_divisor
  - drivers/tty/serial/8250/8250_pci.c:pericom_do_set_divisor
```
**Symbols:**

```
ffffffe0005513c4-ffffffe000551418: serial8250_do_set_divisor (STB_GLOBAL)
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
void serial8250_do_set_divisor(struct uart_port *port, unsigned int baud, unsigned int quot, unsigned int quot_frac);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffffffff81671150)
Location: drivers/tty/serial/8250/8250_port.c:2502
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_divisor
  - drivers/tty/serial/8250/8250_dwlib.c:dw8250_set_divisor
  - drivers/tty/serial/8250/8250_pci.c:pericom_do_set_divisor
```
**Symbols:**

```
ffffffff81671150-ffffffff816711b1: serial8250_do_set_divisor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void serial8250_do_set_divisor(struct uart_port *port, unsigned int baud, unsigned int quot, unsigned int quot_frac);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffffffff81650250)
Location: drivers/tty/serial/8250/8250_port.c:2502
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_divisor
  - drivers/tty/serial/8250/8250_dwlib.c:dw8250_set_divisor
  - drivers/tty/serial/8250/8250_pci.c:pericom_do_set_divisor
```
**Symbols:**

```
ffffffff81650250-ffffffff816502b1: serial8250_do_set_divisor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void serial8250_do_set_divisor(struct uart_port *port, unsigned int baud, unsigned int quot, unsigned int quot_frac);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffffffff8169f520)
Location: drivers/tty/serial/8250/8250_port.c:2502
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_divisor
  - drivers/tty/serial/8250/8250_dwlib.c:dw8250_set_divisor
  - drivers/tty/serial/8250/8250_pci.c:pericom_do_set_divisor
```
**Symbols:**

```
ffffffff8169f520-ffffffff8169f581: serial8250_do_set_divisor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void serial8250_do_set_divisor(struct uart_port *port, unsigned int baud, unsigned int quot, unsigned int quot_frac);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_port.c (ffffffff816b99e0)
Location: drivers/tty/serial/8250/8250_port.c:2502
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_set_divisor
  - drivers/tty/serial/8250/8250_dwlib.c:dw8250_set_divisor
  - drivers/tty/serial/8250/8250_pci.c:pericom_do_set_divisor
```
**Symbols:**

```
ffffffff816b99e0-ffffffff816b9a41: serial8250_do_set_divisor (STB_GLOBAL)
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
