# Function: <code>pinctrl_gpio_can_use_line</code>

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
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool pinctrl_gpio_can_use_line(unsigned int gpio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/core.c (ffffffff8155f180)
Location: drivers/pinctrl/core.c:739
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpio_ioctl
```
**Symbols:**

```
ffffffff8155f180-ffffffff8155f21a: pinctrl_gpio_can_use_line (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool pinctrl_gpio_can_use_line(unsigned int gpio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/core.c (ffffffff81601480)
Location: drivers/pinctrl/core.c:740
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpio_desc_to_lineinfo
```
**Symbols:**

```
ffffffff81601480-ffffffff8160151a: pinctrl_gpio_can_use_line (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool pinctrl_gpio_can_use_line(unsigned int gpio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/core.c (ffffffff816262e0)
Location: drivers/pinctrl/core.c:741
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-cdev.c:gpio_desc_to_lineinfo
```
**Symbols:**

```
ffffffff816262e0-ffffffff8162637a: pinctrl_gpio_can_use_line (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool pinctrl_gpio_can_use_line(unsigned int gpio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/core.c (ffffffff81609d80)
Location: drivers/pinctrl/core.c:741
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-cdev.c:gpio_desc_to_lineinfo
```
**Symbols:**

```
ffffffff81609d80-ffffffff81609e1c: pinctrl_gpio_can_use_line (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool pinctrl_gpio_can_use_line(unsigned int gpio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/core.c (ffffffff81678a00)
Location: drivers/pinctrl/core.c:741
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-cdev.c:gpio_desc_to_lineinfo
```
**Symbols:**

```
ffffffff81678a00-ffffffff81678a9c: pinctrl_gpio_can_use_line (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool pinctrl_gpio_can_use_line(unsigned int gpio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/core.c (ffffffff81793db0)
Location: drivers/pinctrl/core.c:741
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-cdev.c:gpio_desc_to_lineinfo
```
**Symbols:**

```
ffffffff81793db0-ffffffff81793e65: pinctrl_gpio_can_use_line (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool pinctrl_gpio_can_use_line(unsigned int gpio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/core.c (ffffffff818a8fe0)
Location: drivers/pinctrl/core.c:742
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-cdev.c:gpio_desc_to_lineinfo
```
**Symbols:**

```
ffffffff818a8fe0-ffffffff818a9095: pinctrl_gpio_can_use_line (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool pinctrl_gpio_can_use_line(unsigned int gpio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/core.c (ffffffff818ebed0)
Location: drivers/pinctrl/core.c:746
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-cdev.c:gpio_desc_to_lineinfo
```
**Symbols:**

```
ffffffff818ebed0-ffffffff818ebf85: pinctrl_gpio_can_use_line (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool pinctrl_gpio_can_use_line(struct gpio_chip *gc, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/core.c (ffffffff81933420)
Location: drivers/pinctrl/core.c:755
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-cdev.c:gpio_desc_to_lineinfo
```
**Symbols:**

```
ffffffff81933420-ffffffff819334e5: pinctrl_gpio_can_use_line (STB_GLOBAL)
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
bool pinctrl_gpio_can_use_line(unsigned int gpio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/core.c (ffff80001068b510)
Location: drivers/pinctrl/core.c:739
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpio_ioctl
```
**Symbols:**

```
ffff80001068b510-ffff80001068b5cc: pinctrl_gpio_can_use_line (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool pinctrl_gpio_can_use_line(unsigned int gpio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/core.c (c082d84c)
Location: drivers/pinctrl/core.c:739
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpio_ioctl
```
**Symbols:**

```
c082d84c-c082d900: pinctrl_gpio_can_use_line (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool pinctrl_gpio_can_use_line(unsigned int gpio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/core.c (c000000000823ed0)
Location: drivers/pinctrl/core.c:739
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpio_ioctl
```
**Symbols:**

```
c000000000823ed0-c000000000823fc8: pinctrl_gpio_can_use_line (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool pinctrl_gpio_can_use_line(unsigned int gpio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/core.c (ffffffe000497aee)
Location: drivers/pinctrl/core.c:739
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpio_ioctl
```
**Symbols:**

```
ffffffe000497aee-ffffffe000497b7a: pinctrl_gpio_can_use_line (STB_GLOBAL)
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
bool pinctrl_gpio_can_use_line(unsigned int gpio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/core.c (ffffffff81557770)
Location: drivers/pinctrl/core.c:739
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpio_ioctl
```
**Symbols:**

```
ffffffff81557770-ffffffff8155780a: pinctrl_gpio_can_use_line (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool pinctrl_gpio_can_use_line(unsigned int gpio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/core.c (ffffffff81547c30)
Location: drivers/pinctrl/core.c:739
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpio_ioctl
```
**Symbols:**

```
ffffffff81547c30-ffffffff81547cca: pinctrl_gpio_can_use_line (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool pinctrl_gpio_can_use_line(unsigned int gpio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/core.c (ffffffff815534b0)
Location: drivers/pinctrl/core.c:739
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpio_ioctl
```
**Symbols:**

```
ffffffff815534b0-ffffffff8155354a: pinctrl_gpio_can_use_line (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool pinctrl_gpio_can_use_line(unsigned int gpio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/core.c (ffffffff8156d340)
Location: drivers/pinctrl/core.c:739
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpio_ioctl
```
**Symbols:**

```
ffffffff8156d340-ffffffff8156d3da: pinctrl_gpio_can_use_line (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>6.5</code> and <code>6.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct gpio_chip *gc</code>
</li>
<li>
<b>Param added. </b>
<code>unsigned int offset</code>
</li>
<li>
<b>Param removed. </b>
<code>unsigned int gpio</code>
</li>
</ul>
</details>
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
