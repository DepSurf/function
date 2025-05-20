# Function: <code>mctrl_gpio_init</code>

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
In <code>5.0</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
struct mctrl_gpios *mctrl_gpio_init(struct uart_port *port, unsigned int idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/serial_mctrl_gpio.c (0)
Location: drivers/tty/serial/serial_mctrl_gpio.c:189
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_core.c:serial8250_register_8250_port
```
**Symbols:**

```
ffffffff816959ad-ffffffff81695a10: mctrl_gpio_init.cold (STB_LOCAL)
ffffffff81695530-ffffffff81695603: mctrl_gpio_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
struct mctrl_gpios *mctrl_gpio_init(struct uart_port *port, unsigned int idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/serial_mctrl_gpio.c (0)
Location: drivers/tty/serial/serial_mctrl_gpio.c:192
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_core.c:serial8250_register_8250_port
```
**Symbols:**

```
ffffffff816b853d-ffffffff816b85a0: mctrl_gpio_init.cold (STB_LOCAL)
ffffffff816b80c0-ffffffff816b8193: mctrl_gpio_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
struct mctrl_gpios *mctrl_gpio_init(struct uart_port *port, unsigned int idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/serial_mctrl_gpio.c (0)
Location: drivers/tty/serial/serial_mctrl_gpio.c:192
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_core.c:serial8250_register_8250_port
```
**Symbols:**

```
ffffffff8176c5fd-ffffffff8176c660: mctrl_gpio_init.cold (STB_LOCAL)
ffffffff8176c1a0-ffffffff8176c273: mctrl_gpio_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
struct mctrl_gpios *mctrl_gpio_init(struct uart_port *port, unsigned int idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/serial_mctrl_gpio.c (0)
Location: drivers/tty/serial/serial_mctrl_gpio.c:192
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_core.c:serial8250_register_8250_port
```
**Symbols:**

```
ffffffff81c082bd-ffffffff81c08320: mctrl_gpio_init.cold (STB_LOCAL)
ffffffff81786cc0-ffffffff81786d93: mctrl_gpio_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
struct mctrl_gpios *mctrl_gpio_init(struct uart_port *port, unsigned int idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/serial_mctrl_gpio.c (0)
Location: drivers/tty/serial/serial_mctrl_gpio.c:192
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_core.c:serial8250_register_8250_port
```
**Symbols:**

```
ffffffff81bf9e81-ffffffff81bf9ee4: mctrl_gpio_init.cold (STB_LOCAL)
ffffffff8176a620-ffffffff8176a6f3: mctrl_gpio_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct mctrl_gpios *mctrl_gpio_init(struct uart_port *port, unsigned int idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_mctrl_gpio.c (ffffffff817ef710)
Location: drivers/tty/serial/serial_mctrl_gpio.c:192
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_core.c:serial8250_register_8250_port
```
**Symbols:**

```
ffffffff817ef710-ffffffff817ef973: mctrl_gpio_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct mctrl_gpios *mctrl_gpio_init(struct uart_port *port, unsigned int idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_mctrl_gpio.c (ffffffff8192fad0)
Location: drivers/tty/serial/serial_mctrl_gpio.c:192
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_core.c:serial8250_register_8250_port
```
**Symbols:**

```
ffffffff8192fad0-ffffffff8192fd3f: mctrl_gpio_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct mctrl_gpios *mctrl_gpio_init(struct uart_port *port, unsigned int idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_mctrl_gpio.c (ffffffff81a8deb0)
Location: drivers/tty/serial/serial_mctrl_gpio.c:224
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_core.c:serial8250_register_8250_port
```
**Symbols:**

```
ffffffff81a8deb0-ffffffff81a8e126: mctrl_gpio_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct mctrl_gpios *mctrl_gpio_init(struct uart_port *port, unsigned int idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_mctrl_gpio.c (ffffffff81ad9660)
Location: drivers/tty/serial/serial_mctrl_gpio.c:224
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_core.c:serial8250_register_8250_port
```
**Symbols:**

```
ffffffff81ad9660-ffffffff81ad98d6: mctrl_gpio_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct mctrl_gpios *mctrl_gpio_init(struct uart_port *port, unsigned int idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_mctrl_gpio.c (ffffffff81b2c950)
Location: drivers/tty/serial/serial_mctrl_gpio.c:224
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_core.c:serial8250_register_8250_port
```
**Symbols:**

```
ffffffff81b2c950-ffffffff81b2cbc6: mctrl_gpio_init (STB_GLOBAL)
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
struct mctrl_gpios *mctrl_gpio_init(struct uart_port *port, unsigned int idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_mctrl_gpio.c (ffff8000108a78b0)
Location: drivers/tty/serial/serial_mctrl_gpio.c:192
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_core.c:serial8250_register_8250_port
  - drivers/tty/serial/imx.c:imx_uart_probe
```
**Symbols:**

```
ffff8000108a78b0-ffff8000108a7a08: mctrl_gpio_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct mctrl_gpios *mctrl_gpio_init(struct uart_port *port, unsigned int idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_mctrl_gpio.c (c09a44c8)
Location: drivers/tty/serial/serial_mctrl_gpio.c:192
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_core.c:serial8250_register_8250_port
  - drivers/tty/serial/imx.c:imx_uart_probe
```
**Symbols:**

```
c09a44c8-c09a4620: mctrl_gpio_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct mctrl_gpios *mctrl_gpio_init(struct uart_port *port, unsigned int idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_mctrl_gpio.c (c00000000093e3a0)
Location: drivers/tty/serial/serial_mctrl_gpio.c:192
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_core.c:serial8250_register_8250_port
```
**Symbols:**

```
c00000000093e3a0-c00000000093e56c: mctrl_gpio_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct mctrl_gpios *mctrl_gpio_init(struct uart_port *port, unsigned int idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_mctrl_gpio.c (ffffffe00055e1f8)
Location: drivers/tty/serial/serial_mctrl_gpio.c:192
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_core.c:serial8250_register_8250_port
```
**Symbols:**

```
ffffffe00055e1f8-ffffffe00055e32c: mctrl_gpio_init (STB_GLOBAL)
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
struct mctrl_gpios *mctrl_gpio_init(struct uart_port *port, unsigned int idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/serial_mctrl_gpio.c (0)
Location: drivers/tty/serial/serial_mctrl_gpio.c:192
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_core.c:serial8250_register_8250_port
```
**Symbols:**

```
ffffffff8167df9d-ffffffff8167e000: mctrl_gpio_init.cold (STB_LOCAL)
ffffffff8167db20-ffffffff8167dbf3: mctrl_gpio_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
struct mctrl_gpios *mctrl_gpio_init(struct uart_port *port, unsigned int idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/serial_mctrl_gpio.c (0)
Location: drivers/tty/serial/serial_mctrl_gpio.c:192
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_core.c:serial8250_register_8250_port
```
**Symbols:**

```
ffffffff8165d08d-ffffffff8165d0f0: mctrl_gpio_init.cold (STB_LOCAL)
ffffffff8165cc10-ffffffff8165cce3: mctrl_gpio_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
struct mctrl_gpios *mctrl_gpio_init(struct uart_port *port, unsigned int idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/serial_mctrl_gpio.c (0)
Location: drivers/tty/serial/serial_mctrl_gpio.c:192
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_core.c:serial8250_register_8250_port
```
**Symbols:**

```
ffffffff816ac37d-ffffffff816ac3e0: mctrl_gpio_init.cold (STB_LOCAL)
ffffffff816abf00-ffffffff816abfd3: mctrl_gpio_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
struct mctrl_gpios *mctrl_gpio_init(struct uart_port *port, unsigned int idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/serial_mctrl_gpio.c (0)
Location: drivers/tty/serial/serial_mctrl_gpio.c:192
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_core.c:serial8250_register_8250_port
```
**Symbols:**

```
ffffffff816c67dd-ffffffff816c6840: mctrl_gpio_init.cold (STB_LOCAL)
ffffffff816c6360-ffffffff816c6433: mctrl_gpio_init (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
