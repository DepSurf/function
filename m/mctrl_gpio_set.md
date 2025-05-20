# Function: <code>mctrl_gpio_set</code>

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
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void mctrl_gpio_set(struct mctrl_gpios *gpios, unsigned int mctrl);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_mctrl_gpio.c (ffffffff81695610)
Location: drivers/tty/serial/serial_mctrl_gpio.c:40
Inline: True
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_mctrl
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
```
**Symbols:**

```
ffffffff81695610-ffffffff8169569d: mctrl_gpio_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void mctrl_gpio_set(struct mctrl_gpios *gpios, unsigned int mctrl);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_mctrl_gpio.c (ffffffff816b81a0)
Location: drivers/tty/serial/serial_mctrl_gpio.c:45
Inline: True
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_mctrl
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
```
**Symbols:**

```
ffffffff816b81a0-ffffffff816b822d: mctrl_gpio_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void mctrl_gpio_set(struct mctrl_gpios *gpios, unsigned int mctrl);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_mctrl_gpio.c (ffffffff8176c280)
Location: drivers/tty/serial/serial_mctrl_gpio.c:45
Inline: True
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_restore
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_mctrl
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_start_tx
  - drivers/tty/serial/8250/8250_port.c:autoconfig_irq
  - drivers/tty/serial/8250/8250_port.c:autoconfig_irq
  - drivers/tty/serial/8250/8250_port.c:autoconfig_irq
  - drivers/tty/serial/8250/8250_port.c:autoconfig_irq
  - drivers/tty/serial/8250/8250_port.c:autoconfig_irq
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
```
**Symbols:**

```
ffffffff8176c280-ffffffff8176c30f: mctrl_gpio_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void mctrl_gpio_set(struct mctrl_gpios *gpios, unsigned int mctrl);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_mctrl_gpio.c (ffffffff81786da0)
Location: drivers/tty/serial/serial_mctrl_gpio.c:45
Inline: True
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_restore
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_mctrl
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_start_tx
  - drivers/tty/serial/8250/8250_port.c:autoconfig_irq
  - drivers/tty/serial/8250/8250_port.c:autoconfig_irq
  - drivers/tty/serial/8250/8250_port.c:autoconfig_irq
  - drivers/tty/serial/8250/8250_port.c:autoconfig_irq
  - drivers/tty/serial/8250/8250_port.c:autoconfig_irq
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
```
**Symbols:**

```
ffffffff81786da0-ffffffff81786e2f: mctrl_gpio_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void mctrl_gpio_set(struct mctrl_gpios *gpios, unsigned int mctrl);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_mctrl_gpio.c (ffffffff8176a700)
Location: drivers/tty/serial/serial_mctrl_gpio.c:45
Inline: True
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_mctrl
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_start_tx
  - drivers/tty/serial/8250/8250_port.c:autoconfig_irq
  - drivers/tty/serial/8250/8250_port.c:autoconfig_irq
  - drivers/tty/serial/8250/8250_port.c:autoconfig_irq
  - drivers/tty/serial/8250/8250_port.c:autoconfig_irq
  - drivers/tty/serial/8250/8250_port.c:autoconfig_irq
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
```
**Symbols:**

```
ffffffff8176a700-ffffffff8176a78f: mctrl_gpio_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void mctrl_gpio_set(struct mctrl_gpios *gpios, unsigned int mctrl);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_mctrl_gpio.c (ffffffff817ef980)
Location: drivers/tty/serial/serial_mctrl_gpio.c:45
Inline: True
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_mctrl
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_start_tx
  - drivers/tty/serial/8250/8250_port.c:autoconfig_irq
  - drivers/tty/serial/8250/8250_port.c:autoconfig_irq
  - drivers/tty/serial/8250/8250_port.c:autoconfig_irq
  - drivers/tty/serial/8250/8250_port.c:autoconfig_irq
  - drivers/tty/serial/8250/8250_port.c:autoconfig_irq
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
```
**Symbols:**

```
ffffffff817ef980-ffffffff817efb32: mctrl_gpio_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void mctrl_gpio_set(struct mctrl_gpios *gpios, unsigned int mctrl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_mctrl_gpio.c (ffffffff8192f700)
Location: drivers/tty/serial/serial_mctrl_gpio.c:45
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_mctrl
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_start_tx
  - drivers/tty/serial/8250/8250_port.c:autoconfig_irq
  - drivers/tty/serial/8250/8250_port.c:autoconfig_irq
  - drivers/tty/serial/8250/8250_port.c:autoconfig_irq
  - drivers/tty/serial/8250/8250_port.c:autoconfig_irq
  - drivers/tty/serial/8250/8250_port.c:autoconfig_irq
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
```
**Symbols:**

```
ffffffff8192f700-ffffffff8192f8ec: mctrl_gpio_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void mctrl_gpio_set(struct mctrl_gpios *gpios, unsigned int mctrl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_mctrl_gpio.c (ffffffff81a8dac0)
Location: drivers/tty/serial/serial_mctrl_gpio.c:52
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_mctrl
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_start_tx
  - drivers/tty/serial/8250/8250_port.c:autoconfig_irq
  - drivers/tty/serial/8250/8250_port.c:autoconfig_irq
  - drivers/tty/serial/8250/8250_port.c:autoconfig_irq
  - drivers/tty/serial/8250/8250_port.c:autoconfig_irq
  - drivers/tty/serial/8250/8250_port.c:autoconfig_irq
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
```
**Symbols:**

```
ffffffff81a8dac0-ffffffff81a8dcac: mctrl_gpio_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void mctrl_gpio_set(struct mctrl_gpios *gpios, unsigned int mctrl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_mctrl_gpio.c (ffffffff81ad9270)
Location: drivers/tty/serial/serial_mctrl_gpio.c:52
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_mctrl
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_start_tx
  - drivers/tty/serial/8250/8250_port.c:autoconfig_irq
  - drivers/tty/serial/8250/8250_port.c:autoconfig_irq
  - drivers/tty/serial/8250/8250_port.c:autoconfig_irq
  - drivers/tty/serial/8250/8250_port.c:autoconfig_irq
  - drivers/tty/serial/8250/8250_port.c:autoconfig_irq
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
```
**Symbols:**

```
ffffffff81ad9270-ffffffff81ad945c: mctrl_gpio_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void mctrl_gpio_set(struct mctrl_gpios *gpios, unsigned int mctrl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_mctrl_gpio.c (ffffffff81b2c560)
Location: drivers/tty/serial/serial_mctrl_gpio.c:52
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_mctrl
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_start_tx
  - drivers/tty/serial/8250/8250_port.c:autoconfig_irq
  - drivers/tty/serial/8250/8250_port.c:autoconfig_irq
  - drivers/tty/serial/8250/8250_port.c:autoconfig_irq
  - drivers/tty/serial/8250/8250_port.c:autoconfig_irq
  - drivers/tty/serial/8250/8250_port.c:autoconfig_irq
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
```
**Symbols:**

```
ffffffff81b2c560-ffffffff81b2c74c: mctrl_gpio_set (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void mctrl_gpio_set(struct mctrl_gpios *gpios, unsigned int mctrl);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_mctrl_gpio.c (ffff8000108a7a08)
Location: drivers/tty/serial/serial_mctrl_gpio.c:45
Inline: True
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_mctrl
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/imx.c:imx_uart_rs485_config
  - drivers/tty/serial/imx.c:imx_uart_rs485_config
  - drivers/tty/serial/imx.c:imx_uart_set_termios
  - drivers/tty/serial/imx.c:imx_uart_set_termios
  - drivers/tty/serial/imx.c:imx_uart_set_mctrl
  - drivers/tty/serial/imx.c:imx_uart_start_tx
  - drivers/tty/serial/imx.c:imx_uart_start_tx
```
**Symbols:**

```
ffff8000108a7a08-ffff8000108a7afc: mctrl_gpio_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void mctrl_gpio_set(struct mctrl_gpios *gpios, unsigned int mctrl);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_mctrl_gpio.c (c09a4620)
Location: drivers/tty/serial/serial_mctrl_gpio.c:45
Inline: True
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_mctrl
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/imx.c:imx_uart_rs485_config
  - drivers/tty/serial/imx.c:imx_uart_set_termios
  - drivers/tty/serial/imx.c:imx_uart_set_mctrl
  - drivers/tty/serial/imx.c:imx_uart_start_tx
```
**Symbols:**

```
c09a4620-c09a4710: mctrl_gpio_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void mctrl_gpio_set(struct mctrl_gpios *gpios, unsigned int mctrl);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_mctrl_gpio.c (c00000000093e570)
Location: drivers/tty/serial/serial_mctrl_gpio.c:45
Inline: True
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_mctrl
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
```
**Symbols:**

```
c00000000093e570-c00000000093e684: mctrl_gpio_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void mctrl_gpio_set(struct mctrl_gpios *gpios, unsigned int mctrl);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_mctrl_gpio.c (ffffffe00055e32c)
Location: drivers/tty/serial/serial_mctrl_gpio.c:45
Inline: True
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_mctrl
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
```
**Symbols:**

```
ffffffe00055e32c-ffffffe00055e3f6: mctrl_gpio_set (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void mctrl_gpio_set(struct mctrl_gpios *gpios, unsigned int mctrl);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_mctrl_gpio.c (ffffffff8167dc00)
Location: drivers/tty/serial/serial_mctrl_gpio.c:45
Inline: True
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_mctrl
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
```
**Symbols:**

```
ffffffff8167dc00-ffffffff8167dc8d: mctrl_gpio_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void mctrl_gpio_set(struct mctrl_gpios *gpios, unsigned int mctrl);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_mctrl_gpio.c (ffffffff8165ccf0)
Location: drivers/tty/serial/serial_mctrl_gpio.c:45
Inline: True
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_mctrl
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
```
**Symbols:**

```
ffffffff8165ccf0-ffffffff8165cd7d: mctrl_gpio_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void mctrl_gpio_set(struct mctrl_gpios *gpios, unsigned int mctrl);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_mctrl_gpio.c (ffffffff816abfe0)
Location: drivers/tty/serial/serial_mctrl_gpio.c:45
Inline: True
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_mctrl
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
```
**Symbols:**

```
ffffffff816abfe0-ffffffff816ac06d: mctrl_gpio_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void mctrl_gpio_set(struct mctrl_gpios *gpios, unsigned int mctrl);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_mctrl_gpio.c (ffffffff816c6440)
Location: drivers/tty/serial/serial_mctrl_gpio.c:45
Inline: True
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_console_write
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_mctrl
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:size_fifo
  - drivers/tty/serial/8250/8250_port.c:size_fifo
```
**Symbols:**

```
ffffffff816c6440-ffffffff816c64cd: mctrl_gpio_set (STB_GLOBAL)
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
