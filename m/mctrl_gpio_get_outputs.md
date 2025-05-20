# Function: <code>mctrl_gpio_get_outputs</code>

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
unsigned int mctrl_gpio_get_outputs(struct mctrl_gpios *gpios, unsigned int *mctrl);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_mctrl_gpio.c (ffffffff81695840)
Location: drivers/tty/serial/serial_mctrl_gpio.c:89
Inline: True
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:size_fifo
```
**Symbols:**

```
ffffffff81695840-ffffffff816958b0: mctrl_gpio_get_outputs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
unsigned int mctrl_gpio_get_outputs(struct mctrl_gpios *gpios, unsigned int *mctrl);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_mctrl_gpio.c (ffffffff816b83d0)
Location: drivers/tty/serial/serial_mctrl_gpio.c:97
Inline: True
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:size_fifo
```
**Symbols:**

```
ffffffff816b83d0-ffffffff816b8440: mctrl_gpio_get_outputs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
unsigned int mctrl_gpio_get_outputs(struct mctrl_gpios *gpios, unsigned int *mctrl);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_mctrl_gpio.c (ffffffff8176c490)
Location: drivers/tty/serial/serial_mctrl_gpio.c:97
Inline: True
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_mctrl
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_start_tx
  - drivers/tty/serial/8250/8250_port.c:autoconfig_irq
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:size_fifo
```
**Symbols:**

```
ffffffff8176c490-ffffffff8176c500: mctrl_gpio_get_outputs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
unsigned int mctrl_gpio_get_outputs(struct mctrl_gpios *gpios, unsigned int *mctrl);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_mctrl_gpio.c (ffffffff81786fb0)
Location: drivers/tty/serial/serial_mctrl_gpio.c:97
Inline: True
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_mctrl
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_start_tx
  - drivers/tty/serial/8250/8250_port.c:autoconfig_irq
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:size_fifo
```
**Symbols:**

```
ffffffff81786fb0-ffffffff81787020: mctrl_gpio_get_outputs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
unsigned int mctrl_gpio_get_outputs(struct mctrl_gpios *gpios, unsigned int *mctrl);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_mctrl_gpio.c (ffffffff8176a920)
Location: drivers/tty/serial/serial_mctrl_gpio.c:97
Inline: True
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_set_mctrl
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_start_tx
  - drivers/tty/serial/8250/8250_port.c:autoconfig_irq
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:size_fifo
```
**Symbols:**

```
ffffffff8176a920-ffffffff8176a98c: mctrl_gpio_get_outputs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
unsigned int mctrl_gpio_get_outputs(struct mctrl_gpios *gpios, unsigned int *mctrl);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_mctrl_gpio.c (ffffffff817efdd0)
Location: drivers/tty/serial/serial_mctrl_gpio.c:97
Inline: True
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_start_tx
  - drivers/tty/serial/8250/8250_port.c:autoconfig_irq
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:size_fifo
```
**Symbols:**

```
ffffffff817efdd0-ffffffff817eff36: mctrl_gpio_get_outputs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
unsigned int mctrl_gpio_get_outputs(struct mctrl_gpios *gpios, unsigned int *mctrl);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_mctrl_gpio.c (ffffffff8192fff0)
Location: drivers/tty/serial/serial_mctrl_gpio.c:97
Inline: True
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_start_tx
  - drivers/tty/serial/8250/8250_port.c:autoconfig_irq
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:size_fifo
```
**Symbols:**

```
ffffffff8192fff0-ffffffff8193016a: mctrl_gpio_get_outputs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
unsigned int mctrl_gpio_get_outputs(struct mctrl_gpios *gpios, unsigned int *mctrl);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_mctrl_gpio.c (ffffffff81a8e410)
Location: drivers/tty/serial/serial_mctrl_gpio.c:118
Inline: True
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_start_tx
  - drivers/tty/serial/8250/8250_port.c:autoconfig_irq
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:size_fifo
```
**Symbols:**

```
ffffffff81a8e410-ffffffff81a8e58a: mctrl_gpio_get_outputs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
unsigned int mctrl_gpio_get_outputs(struct mctrl_gpios *gpios, unsigned int *mctrl);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_mctrl_gpio.c (ffffffff81ad9bc0)
Location: drivers/tty/serial/serial_mctrl_gpio.c:118
Inline: True
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_start_tx
  - drivers/tty/serial/8250/8250_port.c:autoconfig_irq
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:size_fifo
```
**Symbols:**

```
ffffffff81ad9bc0-ffffffff81ad9d3a: mctrl_gpio_get_outputs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
unsigned int mctrl_gpio_get_outputs(struct mctrl_gpios *gpios, unsigned int *mctrl);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_mctrl_gpio.c (ffffffff81b2ceb0)
Location: drivers/tty/serial/serial_mctrl_gpio.c:118
Inline: True
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_start_tx
  - drivers/tty/serial/8250/8250_port.c:autoconfig_irq
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:size_fifo
```
**Symbols:**

```
ffffffff81b2ceb0-ffffffff81b2d02a: mctrl_gpio_get_outputs (STB_GLOBAL)
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
unsigned int mctrl_gpio_get_outputs(struct mctrl_gpios *gpios, unsigned int *mctrl);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_mctrl_gpio.c (ffff8000108a7be8)
Location: drivers/tty/serial/serial_mctrl_gpio.c:97
Inline: True
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:size_fifo
```
**Symbols:**

```
ffff8000108a7be8-ffff8000108a7c9c: mctrl_gpio_get_outputs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
unsigned int mctrl_gpio_get_outputs(struct mctrl_gpios *gpios, unsigned int *mctrl);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_mctrl_gpio.c (c09a48e4)
Location: drivers/tty/serial/serial_mctrl_gpio.c:97
Inline: True
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:size_fifo
```
**Symbols:**

```
c09a48e4-c09a496c: mctrl_gpio_get_outputs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
unsigned int mctrl_gpio_get_outputs(struct mctrl_gpios *gpios, unsigned int *mctrl);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_mctrl_gpio.c (c00000000093e930)
Location: drivers/tty/serial/serial_mctrl_gpio.c:97
Inline: True
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:size_fifo
```
**Symbols:**

```
c00000000093e930-c00000000093ea24: mctrl_gpio_get_outputs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
unsigned int mctrl_gpio_get_outputs(struct mctrl_gpios *gpios, unsigned int *mctrl);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_mctrl_gpio.c (ffffffe00055e5a8)
Location: drivers/tty/serial/serial_mctrl_gpio.c:97
Inline: True
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:size_fifo
```
**Symbols:**

```
ffffffe00055e5a8-ffffffe00055e630: mctrl_gpio_get_outputs (STB_GLOBAL)
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
unsigned int mctrl_gpio_get_outputs(struct mctrl_gpios *gpios, unsigned int *mctrl);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_mctrl_gpio.c (ffffffff8167de30)
Location: drivers/tty/serial/serial_mctrl_gpio.c:97
Inline: True
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:size_fifo
```
**Symbols:**

```
ffffffff8167de30-ffffffff8167dea0: mctrl_gpio_get_outputs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
unsigned int mctrl_gpio_get_outputs(struct mctrl_gpios *gpios, unsigned int *mctrl);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_mctrl_gpio.c (ffffffff8165cf20)
Location: drivers/tty/serial/serial_mctrl_gpio.c:97
Inline: True
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:size_fifo
```
**Symbols:**

```
ffffffff8165cf20-ffffffff8165cf90: mctrl_gpio_get_outputs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
unsigned int mctrl_gpio_get_outputs(struct mctrl_gpios *gpios, unsigned int *mctrl);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_mctrl_gpio.c (ffffffff816ac210)
Location: drivers/tty/serial/serial_mctrl_gpio.c:97
Inline: True
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:size_fifo
```
**Symbols:**

```
ffffffff816ac210-ffffffff816ac280: mctrl_gpio_get_outputs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
unsigned int mctrl_gpio_get_outputs(struct mctrl_gpios *gpios, unsigned int *mctrl);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_mctrl_gpio.c (ffffffff816c6670)
Location: drivers/tty/serial/serial_mctrl_gpio.c:97
Inline: True
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_config_port
  - drivers/tty/serial/8250/8250_port.c:serial8250_start_tx
  - drivers/tty/serial/8250/8250_port.c:autoconfig
  - drivers/tty/serial/8250/8250_port.c:autoconfig_16550a
  - drivers/tty/serial/8250/8250_port.c:size_fifo
```
**Symbols:**

```
ffffffff816c6670-ffffffff816c66e0: mctrl_gpio_get_outputs (STB_GLOBAL)
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
