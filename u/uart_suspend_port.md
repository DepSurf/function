# Function: <code>uart_suspend_port</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int uart_suspend_port(struct uart_driver *drv, struct uart_port *uport);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff81503d40)
Location: drivers/tty/serial/serial_core.c:2027
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_core.c:serial8250_suspend_port
  - drivers/tty/serial/8250/8250_core.c:serial8250_suspend
  - drivers/tty/serial/max310x.c:max310x_suspend
```
**Symbols:**

```
ffffffff81503d40-ffffffff81503fb6: uart_suspend_port (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int uart_suspend_port(struct uart_driver *drv, struct uart_port *uport);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff81555370)
Location: drivers/tty/serial/serial_core.c:2113
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_core.c:serial8250_suspend
  - drivers/tty/serial/8250/8250_core.c:serial8250_suspend_port
  - drivers/tty/serial/max310x.c:max310x_suspend
```
**Symbols:**

```
ffffffff81555370-ffffffff815555f4: uart_suspend_port (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int uart_suspend_port(struct uart_driver *drv, struct uart_port *uport);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff8157e340)
Location: drivers/tty/serial/serial_core.c:2075
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_core.c:serial8250_suspend
  - drivers/tty/serial/8250/8250_core.c:serial8250_suspend_port
  - drivers/tty/serial/max310x.c:max310x_suspend
```
**Symbols:**

```
ffffffff8157e340-ffffffff8157e5c9: uart_suspend_port (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int uart_suspend_port(struct uart_driver *drv, struct uart_port *uport);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff81595ed0)
Location: drivers/tty/serial/serial_core.c:2081
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_core.c:serial8250_suspend
  - drivers/tty/serial/8250/8250_core.c:serial8250_suspend_port
  - drivers/tty/serial/max310x.c:max310x_suspend
```
**Symbols:**

```
ffffffff81595ed0-ffffffff81596144: uart_suspend_port (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int uart_suspend_port(struct uart_driver *drv, struct uart_port *uport);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff815faaa0)
Location: drivers/tty/serial/serial_core.c:2087
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_core.c:serial8250_suspend
  - drivers/tty/serial/8250/8250_core.c:serial8250_suspend_port
  - drivers/tty/serial/max310x.c:max310x_suspend
```
**Symbols:**

```
ffffffff815faaa0-ffffffff815fad23: uart_suspend_port (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int uart_suspend_port(struct uart_driver *drv, struct uart_port *uport);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff81632bc0)
Location: drivers/tty/serial/serial_core.c:2084
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_core.c:serial8250_suspend
  - drivers/tty/serial/8250/8250_core.c:serial8250_suspend_port
  - drivers/tty/serial/max310x.c:max310x_suspend
```
**Symbols:**

```
ffffffff81632bc0-ffffffff81632e4a: uart_suspend_port (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int uart_suspend_port(struct uart_driver *drv, struct uart_port *uport);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffff81651b60)
Location: drivers/tty/serial/serial_core.c:2143
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_core.c:serial8250_suspend
  - drivers/tty/serial/8250/8250_core.c:serial8250_suspend_port
  - drivers/tty/serial/max310x.c:max310x_suspend
```
**Symbols:**

```
ffffffff81651b60-ffffffff81651dea: uart_suspend_port (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int uart_suspend_port(struct uart_driver *drv, struct uart_port *uport);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/serial_core.c (0)
Location: drivers/tty/serial/serial_core.c:2149
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_core.c:serial8250_suspend
  - drivers/tty/serial/8250/8250_core.c:serial8250_suspend_port
  - drivers/tty/serial/max310x.c:max310x_suspend
```
**Symbols:**

```
ffffffff81687038-ffffffff81687059: uart_suspend_port.cold (STB_LOCAL)
ffffffff816867e0-ffffffff81686a5a: uart_suspend_port (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int uart_suspend_port(struct uart_driver *drv, struct uart_port *uport);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/serial_core.c (0)
Location: drivers/tty/serial/serial_core.c:2150
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_core.c:serial8250_suspend
  - drivers/tty/serial/8250/8250_core.c:serial8250_suspend_port
  - drivers/tty/serial/max310x.c:max310x_suspend
```
**Symbols:**

```
ffffffff816a96e2-ffffffff816a9703: uart_suspend_port.cold (STB_LOCAL)
ffffffff816a8ef0-ffffffff816a916a: uart_suspend_port (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int uart_suspend_port(struct uart_driver *drv, struct uart_port *uport);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/serial_core.c (0)
Location: drivers/tty/serial/serial_core.c:2161
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_core.c:serial8250_suspend
  - drivers/tty/serial/8250/8250_core.c:serial8250_suspend_port
  - drivers/tty/serial/max310x.c:max310x_suspend
```
**Symbols:**

```
ffffffff8175c0cd-ffffffff8175c0ee: uart_suspend_port.cold (STB_LOCAL)
ffffffff817597c0-ffffffff81759a3a: uart_suspend_port (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int uart_suspend_port(struct uart_driver *drv, struct uart_port *uport);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/serial_core.c (0)
Location: drivers/tty/serial/serial_core.c:2167
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_core.c:serial8250_suspend
  - drivers/tty/serial/8250/8250_core.c:serial8250_suspend_port
  - drivers/tty/serial/max310x.c:max310x_suspend
```
**Symbols:**

```
ffffffff81c07c4e-ffffffff81c07c6f: uart_suspend_port.cold (STB_LOCAL)
ffffffff81774730-ffffffff817749aa: uart_suspend_port (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int uart_suspend_port(struct uart_driver *drv, struct uart_port *uport);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/serial_core.c (0)
Location: drivers/tty/serial/serial_core.c:2164
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_core.c:serial8250_suspend
  - drivers/tty/serial/8250/8250_core.c:serial8250_suspend_port
  - drivers/tty/serial/max310x.c:max310x_suspend
```
**Symbols:**

```
ffffffff81bf99a5-ffffffff81bf99c6: uart_suspend_port.cold (STB_LOCAL)
ffffffff81759df0-ffffffff8175a06a: uart_suspend_port (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int uart_suspend_port(struct uart_driver *drv, struct uart_port *uport);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/serial_core.c (0)
Location: drivers/tty/serial/serial_core.c:2166
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_core.c:serial8250_suspend
  - drivers/tty/serial/8250/8250_core.c:serial8250_suspend_port
  - drivers/tty/serial/max310x.c:max310x_suspend
```
**Symbols:**

```
ffffffff81cf9b24-ffffffff81cf9b5a: uart_suspend_port.cold (STB_LOCAL)
ffffffff817dd320-ffffffff817dd5a9: uart_suspend_port (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int uart_suspend_port(struct uart_driver *drv, struct uart_port *uport);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/serial_core.c (0)
Location: drivers/tty/serial/serial_core.c:2191
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_core.c:serial8250_suspend
  - drivers/tty/serial/8250/8250_core.c:serial8250_suspend_port
  - drivers/tty/serial/max310x.c:max310x_suspend
```
**Symbols:**

```
ffffffff81ec1da5-ffffffff81ec1dd9: uart_suspend_port.cold (STB_LOCAL)
ffffffff8191a880-ffffffff8191ab46: uart_suspend_port (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int uart_suspend_port(struct uart_driver *drv, struct uart_port *uport);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/serial_core.c (0)
Location: drivers/tty/serial/serial_core.c:2315
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_core.c:serial8250_suspend
  - drivers/tty/serial/8250/8250_core.c:serial8250_suspend_port
  - drivers/tty/serial/max310x.c:max310x_suspend
```
**Symbols:**

```
ffffffff82095ce6-ffffffff82095cfb: uart_suspend_port.cold (STB_LOCAL)
ffffffff81a762d0-ffffffff81a765be: uart_suspend_port (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int uart_suspend_port(struct uart_driver *drv, struct uart_port *uport);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/serial_core.c (0)
Location: drivers/tty/serial/serial_core.c:2335
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_core.c:serial8250_suspend
  - drivers/tty/serial/8250/8250_core.c:serial8250_suspend_port
  - drivers/tty/serial/max310x.c:max310x_suspend
```
**Symbols:**

```
ffffffff82116b6b-ffffffff82116b80: uart_suspend_port.cold (STB_LOCAL)
ffffffff81ac1080-ffffffff81ac137c: uart_suspend_port (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int uart_suspend_port(struct uart_driver *drv, struct uart_port *uport);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/serial_core.c (0)
Location: drivers/tty/serial/serial_core.c:2371
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_core.c:serial8250_suspend
  - drivers/tty/serial/8250/8250_core.c:serial8250_suspend_port
  - drivers/tty/serial/max310x.c:max310x_suspend
```
**Symbols:**

```
ffffffff821f48c5-ffffffff821f48da: uart_suspend_port.cold (STB_LOCAL)
ffffffff81b13ec0-ffffffff81b141bc: uart_suspend_port (STB_GLOBAL)
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
int uart_suspend_port(struct uart_driver *drv, struct uart_port *uport);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffff800010880080)
Location: drivers/tty/serial/serial_core.c:2150
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_core.c:serial8250_suspend
  - drivers/tty/serial/8250/8250_core.c:serial8250_suspend_port
  - drivers/tty/serial/amba-pl011.c:pl011_suspend
  - drivers/tty/serial/max310x.c:max310x_suspend
  - drivers/tty/serial/imx.c:imx_uart_freeze
  - drivers/tty/serial/imx.c:imx_uart_suspend
  - drivers/tty/serial/msm_serial.c:msm_serial_suspend
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_suspend
```
**Symbols:**

```
ffff800010880080-ffff800010880334: uart_suspend_port (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int uart_suspend_port(struct uart_driver *drv, struct uart_port *uport);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (c097de40)
Location: drivers/tty/serial/serial_core.c:2150
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_core.c:serial8250_suspend
  - drivers/tty/serial/8250/8250_core.c:serial8250_suspend_port
  - drivers/tty/serial/amba-pl011.c:pl011_suspend
  - drivers/tty/serial/max310x.c:max310x_suspend
  - drivers/tty/serial/imx.c:imx_uart_freeze
  - drivers/tty/serial/imx.c:imx_uart_suspend
  - drivers/tty/serial/msm_serial.c:msm_serial_suspend
  - drivers/tty/serial/omap-serial.c:serial_omap_suspend
  - drivers/tty/serial/mvebu-uart.c:mvebu_uart_suspend
```
**Symbols:**

```
c097de40-c097e08c: uart_suspend_port (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int uart_suspend_port(struct uart_driver *drv, struct uart_port *uport);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (c0000000009298c0)
Location: drivers/tty/serial/serial_core.c:2150
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_core.c:serial8250_suspend
  - drivers/tty/serial/8250/8250_core.c:serial8250_suspend_port
  - drivers/tty/serial/max310x.c:max310x_suspend
```
**Symbols:**

```
c0000000009298c0-c000000000929c38: uart_suspend_port (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int uart_suspend_port(struct uart_driver *drv, struct uart_port *uport);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_core.c (ffffffe00054f214)
Location: drivers/tty/serial/serial_core.c:2150
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_core.c:serial8250_suspend
  - drivers/tty/serial/8250/8250_core.c:serial8250_suspend_port
```
**Symbols:**

```
ffffffe00054f214-ffffffe00054f426: uart_suspend_port (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int uart_suspend_port(struct uart_driver *drv, struct uart_port *uport);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/serial_core.c (0)
Location: drivers/tty/serial/serial_core.c:2150
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_core.c:serial8250_suspend
  - drivers/tty/serial/8250/8250_core.c:serial8250_suspend_port
  - drivers/tty/serial/max310x.c:max310x_suspend
```
**Symbols:**

```
ffffffff8166f142-ffffffff8166f163: uart_suspend_port.cold (STB_LOCAL)
ffffffff8166e950-ffffffff8166ebca: uart_suspend_port (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int uart_suspend_port(struct uart_driver *drv, struct uart_port *uport);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/serial_core.c (0)
Location: drivers/tty/serial/serial_core.c:2150
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_core.c:serial8250_suspend
  - drivers/tty/serial/8250/8250_core.c:serial8250_suspend_port
  - drivers/tty/serial/max310x.c:max310x_suspend
```
**Symbols:**

```
ffffffff8164e272-ffffffff8164e293: uart_suspend_port.cold (STB_LOCAL)
ffffffff8164ca50-ffffffff8164ccc4: uart_suspend_port (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int uart_suspend_port(struct uart_driver *drv, struct uart_port *uport);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/serial_core.c (0)
Location: drivers/tty/serial/serial_core.c:2150
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_core.c:serial8250_suspend
  - drivers/tty/serial/8250/8250_core.c:serial8250_suspend_port
  - drivers/tty/serial/max310x.c:max310x_suspend
```
**Symbols:**

```
ffffffff8169d522-ffffffff8169d543: uart_suspend_port.cold (STB_LOCAL)
ffffffff8169cd30-ffffffff8169cfaa: uart_suspend_port (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int uart_suspend_port(struct uart_driver *drv, struct uart_port *uport);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/serial_core.c (0)
Location: drivers/tty/serial/serial_core.c:2150
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_core.c:serial8250_suspend
  - drivers/tty/serial/8250/8250_core.c:serial8250_suspend_port
  - drivers/tty/serial/max310x.c:max310x_suspend
```
**Symbols:**

```
ffffffff816b7810-ffffffff816b782f: uart_suspend_port.cold (STB_LOCAL)
ffffffff816b3ac0-ffffffff816b3d2e: uart_suspend_port (STB_GLOBAL)
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
