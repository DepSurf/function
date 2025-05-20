# Function: <code>uart_get_rs485_mode</code>

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
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void uart_get_rs485_mode(struct device *dev, struct serial_rs485 *rs485conf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff81630160)
Location: drivers/tty/serial/serial_core.c:3030
Inline: False
```
**Symbols:**

```
ffffffff81630160-ffffffff81630220: uart_get_rs485_mode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void uart_get_rs485_mode(struct device *dev, struct serial_rs485 *rs485conf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff8164e310)
Location: drivers/tty/serial/serial_core.c:3091
Inline: False
```
**Symbols:**

```
ffffffff8164e310-ffffffff8164e3d0: uart_get_rs485_mode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void uart_get_rs485_mode(struct device *dev, struct serial_rs485 *rs485conf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff81682e70)
Location: drivers/tty/serial/serial_core.c:3098
Inline: False
```
**Symbols:**

```
ffffffff81682e70-ffffffff81682f30: uart_get_rs485_mode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void uart_get_rs485_mode(struct device *dev, struct serial_rs485 *rs485conf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff816a5510)
Location: drivers/tty/serial/serial_core.c:3100
Inline: False
```
**Symbols:**

```
ffffffff816a5510-ffffffff816a55d0: uart_get_rs485_mode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int uart_get_rs485_mode(struct uart_port *port);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/serial_core.c (0)
Location: drivers/tty/serial/serial_core.c:3213
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_core.c:serial8250_register_8250_port
```
**Symbols:**

```
ffffffff8175c0b9-ffffffff8175c0cd: uart_get_rs485_mode.cold (STB_LOCAL)
ffffffff81757b40-ffffffff81757c73: uart_get_rs485_mode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int uart_get_rs485_mode(struct uart_port *port);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff81772c00)
Location: drivers/tty/serial/serial_core.c:3220
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_core.c:serial8250_register_8250_port
```
**Symbols:**

```
ffffffff81772c00-ffffffff81772d36: uart_get_rs485_mode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int uart_get_rs485_mode(struct uart_port *port);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff81756670)
Location: drivers/tty/serial/serial_core.c:3217
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_core.c:serial8250_register_8250_port
```
**Symbols:**

```
ffffffff81756670-ffffffff817567ae: uart_get_rs485_mode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int uart_get_rs485_mode(struct uart_port *port);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff817d9da0)
Location: drivers/tty/serial/serial_core.c:3234
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_core.c:serial8250_register_8250_port
```
**Symbols:**

```
ffffffff817d9da0-ffffffff817d9ede: uart_get_rs485_mode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int uart_get_rs485_mode(struct uart_port *port);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff81918820)
Location: drivers/tty/serial/serial_core.c:3275
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_core.c:serial8250_register_8250_port
```
**Symbols:**

```
ffffffff81918820-ffffffff81918967: uart_get_rs485_mode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int uart_get_rs485_mode(struct uart_port *port);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff81a74270)
Location: drivers/tty/serial/serial_core.c:3412
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_core.c:serial8250_register_8250_port
```
**Symbols:**

```
ffffffff81a74270-ffffffff81a743d5: uart_get_rs485_mode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int uart_get_rs485_mode(struct uart_port *port);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff81abe8f0)
Location: drivers/tty/serial/serial_core.c:3564
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_core.c:serial8250_register_8250_port
```
**Symbols:**

```
ffffffff81abe8f0-ffffffff81abeaab: uart_get_rs485_mode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int uart_get_rs485_mode(struct uart_port *port);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff81b11670)
Location: drivers/tty/serial/serial_core.c:3601
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_core.c:serial8250_register_8250_port
```
**Symbols:**

```
ffffffff81b11670-ffffffff81b11830: uart_get_rs485_mode (STB_GLOBAL)
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
void uart_get_rs485_mode(struct device *dev, struct serial_rs485 *rs485conf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffff80001087d838)
Location: drivers/tty/serial/serial_core.c:3100
Inline: False
Direct callers:
  - drivers/tty/serial/imx.c:imx_uart_probe
```
**Symbols:**

```
ffff80001087d838-ffff80001087d940: uart_get_rs485_mode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void uart_get_rs485_mode(struct device *dev, struct serial_rs485 *rs485conf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (c097f430)
Location: drivers/tty/serial/serial_core.c:3100
Inline: False
Direct callers:
  - drivers/tty/serial/imx.c:imx_uart_probe
  - drivers/tty/serial/omap-serial.c:serial_omap_probe
```
**Symbols:**

```
c097f430-c097f528: uart_get_rs485_mode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void uart_get_rs485_mode(struct device *dev, struct serial_rs485 *rs485conf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (c000000000924820)
Location: drivers/tty/serial/serial_core.c:3100
Inline: False
```
**Symbols:**

```
c000000000924820-c000000000924954: uart_get_rs485_mode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void uart_get_rs485_mode(struct device *dev, struct serial_rs485 *rs485conf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffe00054c296)
Location: drivers/tty/serial/serial_core.c:3100
Inline: False
```
**Symbols:**

```
ffffffe00054c296-ffffffe00054c34c: uart_get_rs485_mode (STB_GLOBAL)
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
void uart_get_rs485_mode(struct device *dev, struct serial_rs485 *rs485conf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff8166af70)
Location: drivers/tty/serial/serial_core.c:3100
Inline: False
```
**Symbols:**

```
ffffffff8166af70-ffffffff8166b030: uart_get_rs485_mode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void uart_get_rs485_mode(struct device *dev, struct serial_rs485 *rs485conf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff8164a0e0)
Location: drivers/tty/serial/serial_core.c:3100
Inline: False
```
**Symbols:**

```
ffffffff8164a0e0-ffffffff8164a1a0: uart_get_rs485_mode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void uart_get_rs485_mode(struct device *dev, struct serial_rs485 *rs485conf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff81699350)
Location: drivers/tty/serial/serial_core.c:3100
Inline: False
```
**Symbols:**

```
ffffffff81699350-ffffffff81699410: uart_get_rs485_mode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void uart_get_rs485_mode(struct device *dev, struct serial_rs485 *rs485conf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff816b3a00)
Location: drivers/tty/serial/serial_core.c:3100
Inline: False
```
**Symbols:**

```
ffffffff816b3a00-ffffffff816b3ac0: uart_get_rs485_mode (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct uart_port *port</code>
</li>
<li>
<b>Param removed. </b>
<code>struct device *dev</code>
</li>
<li>
<b>Param removed. </b>
<code>struct serial_rs485 *rs485conf</code>
</li>
<li>
<b>Return type changed. </b>
<code>void</code> ➡️ <code>int</code>
</li>
</ul>
</details>
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
