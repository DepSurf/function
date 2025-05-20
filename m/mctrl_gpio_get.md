# Function: <code>mctrl_gpio_get</code>

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
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
unsigned int mctrl_gpio_get(struct mctrl_gpios *gpios, unsigned int *mctrl);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/serial_mctrl_gpio.c (ffffffff8169575f)
Location: drivers/tty/serial/serial_mctrl_gpio.c:68
Inline: True
Inline callers:
  - drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_irq_handle
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_get_mctrl
  - drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_irq_handle
```
**Symbols:**

```
ffffffff816956a0-ffffffff8169570b: mctrl_gpio_get.part.0 (STB_LOCAL)
ffffffff81695710-ffffffff81695728: mctrl_gpio_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
unsigned int mctrl_gpio_get(struct mctrl_gpios *gpios, unsigned int *mctrl);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/serial_mctrl_gpio.c (ffffffff816b82ef)
Location: drivers/tty/serial/serial_mctrl_gpio.c:76
Inline: True
Inline callers:
  - drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_irq_handle
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_get_mctrl
  - drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_irq_handle
```
**Symbols:**

```
ffffffff816b8230-ffffffff816b829b: mctrl_gpio_get.part.0 (STB_LOCAL)
ffffffff816b82a0-ffffffff816b82b8: mctrl_gpio_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
unsigned int mctrl_gpio_get(struct mctrl_gpios *gpios, unsigned int *mctrl);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_mctrl_gpio.c (ffffffff8176c310)
Location: drivers/tty/serial/serial_mctrl_gpio.c:76
Inline: True
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_get_mctrl
  - drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_irq_handle
```
**Symbols:**

```
ffffffff8176c310-ffffffff8176c380: mctrl_gpio_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
unsigned int mctrl_gpio_get(struct mctrl_gpios *gpios, unsigned int *mctrl);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_mctrl_gpio.c (ffffffff81786e30)
Location: drivers/tty/serial/serial_mctrl_gpio.c:76
Inline: True
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_get_mctrl
  - drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_irq_handle
```
**Symbols:**

```
ffffffff81786e30-ffffffff81786ea0: mctrl_gpio_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
unsigned int mctrl_gpio_get(struct mctrl_gpios *gpios, unsigned int *mctrl);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_mctrl_gpio.c (ffffffff8176a790)
Location: drivers/tty/serial/serial_mctrl_gpio.c:76
Inline: True
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_get_mctrl
  - drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_irq_handle
```
**Symbols:**

```
ffffffff8176a790-ffffffff8176a7fc: mctrl_gpio_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
unsigned int mctrl_gpio_get(struct mctrl_gpios *gpios, unsigned int *mctrl);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_mctrl_gpio.c (ffffffff817efb40)
Location: drivers/tty/serial/serial_mctrl_gpio.c:76
Inline: True
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_get_mctrl
  - drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_irq_handle
```
**Symbols:**

```
ffffffff817efb40-ffffffff817efca6: mctrl_gpio_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
unsigned int mctrl_gpio_get(struct mctrl_gpios *gpios, unsigned int *mctrl);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_mctrl_gpio.c (ffffffff8192fd40)
Location: drivers/tty/serial/serial_mctrl_gpio.c:76
Inline: True
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_get_mctrl
  - drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_irq_handle
```
**Symbols:**

```
ffffffff8192fd40-ffffffff8192feba: mctrl_gpio_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
unsigned int mctrl_gpio_get(struct mctrl_gpios *gpios, unsigned int *mctrl);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_mctrl_gpio.c (ffffffff81a8e140)
Location: drivers/tty/serial/serial_mctrl_gpio.c:97
Inline: True
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_get_mctrl
  - drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_irq_handle
```
**Symbols:**

```
ffffffff81a8e140-ffffffff81a8e2ba: mctrl_gpio_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
unsigned int mctrl_gpio_get(struct mctrl_gpios *gpios, unsigned int *mctrl);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_mctrl_gpio.c (ffffffff81ad98f0)
Location: drivers/tty/serial/serial_mctrl_gpio.c:97
Inline: True
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_get_mctrl
  - drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_irq_handle
```
**Symbols:**

```
ffffffff81ad98f0-ffffffff81ad9a6a: mctrl_gpio_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
unsigned int mctrl_gpio_get(struct mctrl_gpios *gpios, unsigned int *mctrl);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/serial_mctrl_gpio.c (ffffffff81b2cbe0)
Location: drivers/tty/serial/serial_mctrl_gpio.c:97
Inline: True
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_get_mctrl
  - drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_irq_handle
```
**Symbols:**

```
ffffffff81b2cbe0-ffffffff81b2cd5a: mctrl_gpio_get (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

```c
unsigned int mctrl_gpio_get(struct mctrl_gpios *gpios, unsigned int *mctrl);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/serial_mctrl_gpio.c (ffff8000108a7e38)
Location: drivers/tty/serial/serial_mctrl_gpio.c:76
Inline: True
Inline callers:
  - drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_irq_handle
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_get_mctrl
  - drivers/tty/serial/imx.c:imx_uart_get_mctrl
  - drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_irq_handle
```
**Symbols:**

```
ffff8000108a7b00-ffff8000108a7ba0: mctrl_gpio_get.part.0 (STB_LOCAL)
ffff8000108a7ba0-ffff8000108a7be8: mctrl_gpio_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

```c
unsigned int mctrl_gpio_get(struct mctrl_gpios *gpios, unsigned int *mctrl);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/serial_mctrl_gpio.c (c09a47fc)
Location: drivers/tty/serial/serial_mctrl_gpio.c:76
Inline: True
Inline callers:
  - drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_irq_handle
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_get_mctrl
  - drivers/tty/serial/imx.c:imx_uart_get_mctrl
  - drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_irq_handle
```
**Symbols:**

```
c09a4710-c09a4790: mctrl_gpio_get.part.0 (STB_LOCAL)
c09a4790-c09a47bc: mctrl_gpio_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

```c
unsigned int mctrl_gpio_get(struct mctrl_gpios *gpios, unsigned int *mctrl);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/serial_mctrl_gpio.c (c00000000093e7ec)
Location: drivers/tty/serial/serial_mctrl_gpio.c:76
Inline: True
Inline callers:
  - drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_irq_handle
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_get_mctrl
  - drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_irq_handle
```
**Symbols:**

```
c00000000093e690-c00000000093e76c: mctrl_gpio_get.part.0 (STB_LOCAL)
c00000000093e770-c00000000093e798: mctrl_gpio_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

```c
unsigned int mctrl_gpio_get(struct mctrl_gpios *gpios, unsigned int *mctrl);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/serial_mctrl_gpio.c (ffffffe00055e4e4)
Location: drivers/tty/serial/serial_mctrl_gpio.c:76
Inline: True
Inline callers:
  - drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_irq_handle
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_get_mctrl
  - drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_irq_handle
```
**Symbols:**

```
ffffffe00055e3f6-ffffffe00055e47a: mctrl_gpio_get.part.0 (STB_LOCAL)
ffffffe00055e47a-ffffffe00055e4c0: mctrl_gpio_get (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
unsigned int mctrl_gpio_get(struct mctrl_gpios *gpios, unsigned int *mctrl);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/serial_mctrl_gpio.c (ffffffff8167dd4f)
Location: drivers/tty/serial/serial_mctrl_gpio.c:76
Inline: True
Inline callers:
  - drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_irq_handle
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_get_mctrl
  - drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_irq_handle
```
**Symbols:**

```
ffffffff8167dc90-ffffffff8167dcfb: mctrl_gpio_get.part.0 (STB_LOCAL)
ffffffff8167dd00-ffffffff8167dd18: mctrl_gpio_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
unsigned int mctrl_gpio_get(struct mctrl_gpios *gpios, unsigned int *mctrl);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/serial_mctrl_gpio.c (ffffffff8165ce3f)
Location: drivers/tty/serial/serial_mctrl_gpio.c:76
Inline: True
Inline callers:
  - drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_irq_handle
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_get_mctrl
  - drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_irq_handle
```
**Symbols:**

```
ffffffff8165cd80-ffffffff8165cdeb: mctrl_gpio_get.part.0 (STB_LOCAL)
ffffffff8165cdf0-ffffffff8165ce08: mctrl_gpio_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
unsigned int mctrl_gpio_get(struct mctrl_gpios *gpios, unsigned int *mctrl);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/serial_mctrl_gpio.c (ffffffff816ac12f)
Location: drivers/tty/serial/serial_mctrl_gpio.c:76
Inline: True
Inline callers:
  - drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_irq_handle
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_get_mctrl
  - drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_irq_handle
```
**Symbols:**

```
ffffffff816ac070-ffffffff816ac0db: mctrl_gpio_get.part.0 (STB_LOCAL)
ffffffff816ac0e0-ffffffff816ac0f8: mctrl_gpio_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
unsigned int mctrl_gpio_get(struct mctrl_gpios *gpios, unsigned int *mctrl);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/serial_mctrl_gpio.c (ffffffff816c658f)
Location: drivers/tty/serial/serial_mctrl_gpio.c:76
Inline: True
Inline callers:
  - drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_irq_handle
Direct callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_do_get_mctrl
  - drivers/tty/serial/serial_mctrl_gpio.c:mctrl_gpio_irq_handle
```
**Symbols:**

```
ffffffff816c64d0-ffffffff816c653b: mctrl_gpio_get.part.0 (STB_LOCAL)
ffffffff816c6540-ffffffff816c6558: mctrl_gpio_get (STB_GLOBAL)
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
