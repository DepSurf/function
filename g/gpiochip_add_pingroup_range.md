# Function: <code>gpiochip_add_pingroup_range</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int gpiochip_add_pingroup_range(struct gpio_chip *chip, struct pinctrl_dev *pctldev, unsigned int gpio_offset, const char *pin_group);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81426aa0)
Location: drivers/gpio/gpiolib.c:780
Inline: False
```
**Symbols:**

```
ffffffff81426aa0-ffffffff81426bce: gpiochip_add_pingroup_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int gpiochip_add_pingroup_range(struct gpio_chip *chip, struct pinctrl_dev *pctldev, unsigned int gpio_offset, const char *pin_group);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81470470)
Location: drivers/gpio/gpiolib.c:1701
Inline: False
```
**Symbols:**

```
ffffffff81470470-ffffffff814705b7: gpiochip_add_pingroup_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int gpiochip_add_pingroup_range(struct gpio_chip *chip, struct pinctrl_dev *pctldev, unsigned int gpio_offset, const char *pin_group);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81491470)
Location: drivers/gpio/gpiolib.c:1888
Inline: False
```
**Symbols:**

```
ffffffff81491470-ffffffff814915b7: gpiochip_add_pingroup_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int gpiochip_add_pingroup_range(struct gpio_chip *chip, struct pinctrl_dev *pctldev, unsigned int gpio_offset, const char *pin_group);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8149af10)
Location: drivers/gpio/gpiolib.c:1889
Inline: False
```
**Symbols:**

```
ffffffff8149af10-ffffffff8149b04f: gpiochip_add_pingroup_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int gpiochip_add_pingroup_range(struct gpio_chip *chip, struct pinctrl_dev *pctldev, unsigned int gpio_offset, const char *pin_group);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff814d9450)
Location: drivers/gpio/gpiolib.c:2023
Inline: False
```
**Symbols:**

```
ffffffff814d9450-ffffffff814d958f: gpiochip_add_pingroup_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int gpiochip_add_pingroup_range(struct gpio_chip *chip, struct pinctrl_dev *pctldev, unsigned int gpio_offset, const char *pin_group);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81508710)
Location: drivers/gpio/gpiolib.c:2135
Inline: False
```
**Symbols:**

```
ffffffff81508710-ffffffff8150884f: gpiochip_add_pingroup_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int gpiochip_add_pingroup_range(struct gpio_chip *chip, struct pinctrl_dev *pctldev, unsigned int gpio_offset, const char *pin_group);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8151bbe0)
Location: drivers/gpio/gpiolib.c:2150
Inline: False
```
**Symbols:**

```
ffffffff8151bbe0-ffffffff8151bd1f: gpiochip_add_pingroup_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int gpiochip_add_pingroup_range(struct gpio_chip *chip, struct pinctrl_dev *pctldev, unsigned int gpio_offset, const char *pin_group);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:2214
Inline: False
```
**Symbols:**

```
ffffffff8154edae-ffffffff8154edcf: gpiochip_add_pingroup_range.cold (STB_LOCAL)
ffffffff81549f20-ffffffff8154a043: gpiochip_add_pingroup_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int gpiochip_add_pingroup_range(struct gpio_chip *chip, struct pinctrl_dev *pctldev, unsigned int gpio_offset, const char *pin_group);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:2546
Inline: False
```
**Symbols:**

```
ffffffff81570376-ffffffff81570397: gpiochip_add_pingroup_range.cold (STB_LOCAL)
ffffffff8156b0c0-ffffffff8156b1e3: gpiochip_add_pingroup_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int gpiochip_add_pingroup_range(struct gpio_chip *gc, struct pinctrl_dev *pctldev, unsigned int gpio_offset, const char *pin_group);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:2913
Inline: False
```
**Symbols:**

```
ffffffff816143a9-ffffffff816143ca: gpiochip_add_pingroup_range.cold (STB_LOCAL)
ffffffff8160e410-ffffffff8160e533: gpiochip_add_pingroup_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int gpiochip_add_pingroup_range(struct gpio_chip *gc, struct pinctrl_dev *pctldev, unsigned int gpio_offset, const char *pin_group);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:1716
Inline: False
```
**Symbols:**

```
ffffffff81bf5ba9-ffffffff81bf5bca: gpiochip_add_pingroup_range.cold (STB_LOCAL)
ffffffff81634bd0-ffffffff81634cf3: gpiochip_add_pingroup_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int gpiochip_add_pingroup_range(struct gpio_chip *gc, struct pinctrl_dev *pctldev, unsigned int gpio_offset, const char *pin_group);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:1693
Inline: False
```
**Symbols:**

```
ffffffff81be7a97-ffffffff81be7ab8: gpiochip_add_pingroup_range.cold (STB_LOCAL)
ffffffff816188a0-ffffffff816189c3: gpiochip_add_pingroup_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int gpiochip_add_pingroup_range(struct gpio_chip *gc, struct pinctrl_dev *pctldev, unsigned int gpio_offset, const char *pin_group);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:1715
Inline: False
```
**Symbols:**

```
ffffffff81ce158c-ffffffff81ce15ad: gpiochip_add_pingroup_range.cold (STB_LOCAL)
ffffffff81687b40-ffffffff81687c60: gpiochip_add_pingroup_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int gpiochip_add_pingroup_range(struct gpio_chip *gc, struct pinctrl_dev *pctldev, unsigned int gpio_offset, const char *pin_group);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:1776
Inline: False
```
**Symbols:**

```
ffffffff81ea7f05-ffffffff81ea7f26: gpiochip_add_pingroup_range.cold (STB_LOCAL)
ffffffff817a4ee0-ffffffff817a501f: gpiochip_add_pingroup_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int gpiochip_add_pingroup_range(struct gpio_chip *gc, struct pinctrl_dev *pctldev, unsigned int gpio_offset, const char *pin_group);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff818bce10)
Location: drivers/gpio/gpiolib.c:1846
Inline: False
```
**Symbols:**

```
ffffffff818bce10-ffffffff818bcf68: gpiochip_add_pingroup_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int gpiochip_add_pingroup_range(struct gpio_chip *gc, struct pinctrl_dev *pctldev, unsigned int gpio_offset, const char *pin_group);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff818fff30)
Location: drivers/gpio/gpiolib.c:1885
Inline: False
```
**Symbols:**

```
ffffffff818fff30-ffffffff81900088: gpiochip_add_pingroup_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int gpiochip_add_pingroup_range(struct gpio_chip *gc, struct pinctrl_dev *pctldev, unsigned int gpio_offset, const char *pin_group);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81947830)
Location: drivers/gpio/gpiolib.c:2068
Inline: False
```
**Symbols:**

```
ffffffff81947830-ffffffff819479b7: gpiochip_add_pingroup_range (STB_GLOBAL)
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
int gpiochip_add_pingroup_range(struct gpio_chip *chip, struct pinctrl_dev *pctldev, unsigned int gpio_offset, const char *pin_group);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffff8000106be9e0)
Location: drivers/gpio/gpiolib.c:2546
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-of.c:of_gpiochip_add
```
**Symbols:**

```
ffff8000106be9e0-ffff8000106beb44: gpiochip_add_pingroup_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int gpiochip_add_pingroup_range(struct gpio_chip *chip, struct pinctrl_dev *pctldev, unsigned int gpio_offset, const char *pin_group);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (c085e798)
Location: drivers/gpio/gpiolib.c:2546
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-of.c:of_gpiochip_add
```
**Symbols:**

```
c085e798-c085e8f0: gpiochip_add_pingroup_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int gpiochip_add_pingroup_range(struct gpio_chip *chip, struct pinctrl_dev *pctldev, unsigned int gpio_offset, const char *pin_group);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (c00000000083e7e0)
Location: drivers/gpio/gpiolib.c:2546
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-of.c:of_gpiochip_add
```
**Symbols:**

```
c00000000083e7e0-c00000000083e9d0: gpiochip_add_pingroup_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int gpiochip_add_pingroup_range(struct gpio_chip *chip, struct pinctrl_dev *pctldev, unsigned int gpio_offset, const char *pin_group);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffe0004a58bc)
Location: drivers/gpio/gpiolib.c:2546
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-of.c:of_gpiochip_add
```
**Symbols:**

```
ffffffe0004a58bc-ffffffe0004a59fa: gpiochip_add_pingroup_range (STB_GLOBAL)
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
int gpiochip_add_pingroup_range(struct gpio_chip *chip, struct pinctrl_dev *pctldev, unsigned int gpio_offset, const char *pin_group);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:2546
Inline: False
```
**Symbols:**

```
ffffffff81565b36-ffffffff81565b57: gpiochip_add_pingroup_range.cold (STB_LOCAL)
ffffffff81560880-ffffffff815609a3: gpiochip_add_pingroup_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int gpiochip_add_pingroup_range(struct gpio_chip *chip, struct pinctrl_dev *pctldev, unsigned int gpio_offset, const char *pin_group);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:2546
Inline: False
```
**Symbols:**

```
ffffffff81556986-ffffffff815569a7: gpiochip_add_pingroup_range.cold (STB_LOCAL)
ffffffff815516d0-ffffffff815517f3: gpiochip_add_pingroup_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int gpiochip_add_pingroup_range(struct gpio_chip *chip, struct pinctrl_dev *pctldev, unsigned int gpio_offset, const char *pin_group);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:2546
Inline: False
```
**Symbols:**

```
ffffffff815646a6-ffffffff815646c7: gpiochip_add_pingroup_range.cold (STB_LOCAL)
ffffffff8155f3f0-ffffffff8155f513: gpiochip_add_pingroup_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int gpiochip_add_pingroup_range(struct gpio_chip *chip, struct pinctrl_dev *pctldev, unsigned int gpio_offset, const char *pin_group);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:2546
Inline: False
```
**Symbols:**

```
ffffffff8157e5c6-ffffffff8157e5e7: gpiochip_add_pingroup_range.cold (STB_LOCAL)
ffffffff81579270-ffffffff81579393: gpiochip_add_pingroup_range (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct gpio_chip *gc</code>
</li>
<li>
<b>Param removed. </b>
<code>struct gpio_chip *chip</code>
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
