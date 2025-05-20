# Function: <code>bgpio_init</code>

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
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int bgpio_init(struct gpio_chip *gc, struct device *dev, long unsigned int sz, void *dat, void *set, void *clr, void *dirout, void *dirin, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpio-mmio.c (0)
Location: drivers/gpio/gpio-mmio.c:599
Inline: False
Direct callers:
  - drivers/gpio/gpio-mmio.c:bgpio_pdev_probe
```
**Symbols:**

```
ffffffff81ea924a-ffffffff81ea926e: bgpio_init.cold (STB_LOCAL)
ffffffff817b1bd0-ffffffff817b1f84: bgpio_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int bgpio_init(struct gpio_chip *gc, struct device *dev, long unsigned int sz, void *dat, void *set, void *clr, void *dirout, void *dirin, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpio-mmio.c (ffffffff818cbb00)
Location: drivers/gpio/gpio-mmio.c:599
Inline: False
Direct callers:
  - drivers/gpio/gpio-mmio.c:bgpio_pdev_probe
```
**Symbols:**

```
ffffffff818cbb00-ffffffff818cbeba: bgpio_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int bgpio_init(struct gpio_chip *gc, struct device *dev, long unsigned int sz, void *dat, void *set, void *clr, void *dirout, void *dirin, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpio-mmio.c (ffffffff8190eb70)
Location: drivers/gpio/gpio-mmio.c:599
Inline: False
Direct callers:
  - drivers/gpio/gpio-mmio.c:bgpio_pdev_probe
```
**Symbols:**

```
ffffffff8190eb70-ffffffff8190ef26: bgpio_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int bgpio_init(struct gpio_chip *gc, struct device *dev, long unsigned int sz, void *dat, void *set, void *clr, void *dirout, void *dirin, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpio-mmio.c (0)
Location: drivers/gpio/gpio-mmio.c:598
Inline: False
Direct callers:
  - drivers/gpio/gpio-mmio.c:bgpio_pdev_probe
```
**Symbols:**

```
ffffffff821ec8a4-ffffffff821ec8f4: bgpio_init.cold (STB_LOCAL)
ffffffff819568e0-ffffffff81956d28: bgpio_init (STB_GLOBAL)
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
int bgpio_init(struct gpio_chip *gc, struct device *dev, long unsigned int sz, void *dat, void *set, void *clr, void *dirout, void *dirin, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpio-mmio.c (ffff8000106cc9c0)
Location: drivers/gpio/gpio-mmio.c:582
Inline: False
Direct callers:
  - drivers/gpio/gpio-mmio.c:bgpio_pdev_probe
  - drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_probe
  - drivers/gpio/gpio-mpc8xxx.c:mpc8xxx_probe
  - drivers/gpio/gpio-mpc8xxx.c:mpc8xxx_probe
  - drivers/gpio/gpio-mxc.c:mxc_gpio_probe
  - drivers/mfd/vexpress-sysreg.c:vexpress_sysreg_probe
```
**Symbols:**

```
ffff8000106cc9c0-ffff8000106ccd90: bgpio_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int bgpio_init(struct gpio_chip *gc, struct device *dev, long unsigned int sz, void *dat, void *set, void *clr, void *dirout, void *dirin, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpio-mmio.c (c0867b3c)
Location: drivers/gpio/gpio-mmio.c:582
Inline: False
Direct callers:
  - drivers/pinctrl/nuvoton/pinctrl-npcm7xx.c:npcm7xx_gpio_of
  - drivers/gpio/gpio-mmio.c:bgpio_pdev_probe
  - drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_probe
  - drivers/gpio/gpio-mpc8xxx.c:mpc8xxx_probe
  - drivers/gpio/gpio-mpc8xxx.c:mpc8xxx_probe
  - drivers/gpio/gpio-mxc.c:mxc_gpio_probe
  - drivers/mfd/vexpress-sysreg.c:vexpress_sysreg_probe
```
**Symbols:**

```
c0867b3c-c0867ecc: bgpio_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int bgpio_init(struct gpio_chip *gc, struct device *dev, long unsigned int sz, void *dat, void *set, void *clr, void *dirout, void *dirin, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpio-mmio.c (c0000000008489f0)
Location: drivers/gpio/gpio-mmio.c:582
Inline: False
Direct callers:
  - drivers/gpio/gpio-mmio.c:bgpio_pdev_probe
  - drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_probe
```
**Symbols:**

```
c0000000008489f0-c000000000848e7c: bgpio_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int bgpio_init(struct gpio_chip *gc, struct device *dev, long unsigned int sz, void *dat, void *set, void *clr, void *dirout, void *dirin, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpio-mmio.c (ffffffe0004adc5a)
Location: drivers/gpio/gpio-mmio.c:582
Inline: False
Direct callers:
  - drivers/gpio/gpio-mmio.c:bgpio_pdev_probe
  - drivers/gpio/gpio-ftgpio010.c:ftgpio_gpio_probe
```
**Symbols:**

```
ffffffe0004adc5a-ffffffe0004adf5e: bgpio_init (STB_GLOBAL)
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
int bgpio_init(struct gpio_chip *gc, struct device *dev, long unsigned int sz, void *dat, void *set, void *clr, void *dirout, void *dirin, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpio-mmio.c (0)
Location: drivers/gpio/gpio-mmio.c:582
Inline: False
Direct callers:
  - drivers/gpio/gpio-mmio.c:bgpio_pdev_probe
```
**Symbols:**

```
ffffffff8156aaaf-ffffffff8156aae1: bgpio_init.cold (STB_LOCAL)
ffffffff8156a300-ffffffff8156a6f9: bgpio_init (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
</ul>
<b>Flavor</b>
<ul>
</ul>
