# Function: <code>gpiochip_enable_irq</code>

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
<summary>In <code>5.0</code>: ✅</summary>

```c
void gpiochip_enable_irq(struct gpio_chip *chip, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8151aa90)
Location: drivers/gpio/gpiolib.c:3511
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_irq_enable
```
**Symbols:**

```
ffffffff8151aa90-ffffffff8151aade: gpiochip_enable_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void gpiochip_enable_irq(struct gpio_chip *chip, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:3600
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_irq_enable
```
**Symbols:**

```
ffffffff8154ed40-ffffffff8154ed66: gpiochip_enable_irq.cold (STB_LOCAL)
ffffffff81549320-ffffffff81549371: gpiochip_enable_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void gpiochip_enable_irq(struct gpio_chip *chip, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8156a1f0)
Location: drivers/gpio/gpiolib.c:3954
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_irq_enable
```
**Symbols:**

```
ffffffff8156a1f0-ffffffff8156a23d: gpiochip_enable_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void gpiochip_enable_irq(struct gpio_chip *gc, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8160e7e0)
Location: drivers/gpio/gpiolib.c:4362
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_irq_enable
  - drivers/gpio/gpiolib.c:gpiochip_irq_unmask
```
**Symbols:**

```
ffffffff8160e7e0-ffffffff8160e834: gpiochip_enable_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void gpiochip_enable_irq(struct gpio_chip *gc, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81635070)
Location: drivers/gpio/gpiolib.c:3186
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_irq_enable
  - drivers/gpio/gpiolib.c:gpiochip_irq_unmask
```
**Symbols:**

```
ffffffff81635070-ffffffff816350c8: gpiochip_enable_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void gpiochip_enable_irq(struct gpio_chip *gc, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81618ae0)
Location: drivers/gpio/gpiolib.c:3163
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_irq_enable
  - drivers/gpio/gpiolib.c:gpiochip_irq_unmask
```
**Symbols:**

```
ffffffff81618ae0-ffffffff81618b38: gpiochip_enable_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void gpiochip_enable_irq(struct gpio_chip *gc, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81687c60)
Location: drivers/gpio/gpiolib.c:3222
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_irq_enable
  - drivers/gpio/gpiolib.c:gpiochip_irq_unmask
```
**Symbols:**

```
ffffffff81687c60-ffffffff81687cb8: gpiochip_enable_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void gpiochip_enable_irq(struct gpio_chip *gc, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff817a31b0)
Location: drivers/gpio/gpiolib.c:3343
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_enable
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_unmask
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_startup
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_irq_unmask
  - drivers/gpio/gpiolib.c:gpiochip_irq_enable
  - drivers/gpio/gpiolib.c:gpiochip_irq_unmask
  - drivers/gpio/gpio-crystalcove.c:crystalcove_irq_unmask
```
**Symbols:**

```
ffffffff817a31b0-ffffffff817a3220: gpiochip_enable_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void gpiochip_enable_irq(struct gpio_chip *gc, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff818ba650)
Location: drivers/gpio/gpiolib.c:3413
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_enable
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_unmask
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_startup
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_irq_unmask
  - drivers/gpio/gpiolib.c:gpiochip_irq_enable
  - drivers/gpio/gpiolib.c:gpiochip_irq_unmask
  - drivers/gpio/gpio-crystalcove.c:crystalcove_irq_unmask
```
**Symbols:**

```
ffffffff818ba650-ffffffff818ba6c0: gpiochip_enable_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void gpiochip_enable_irq(struct gpio_chip *gc, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff818fd750)
Location: drivers/gpio/gpiolib.c:3454
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_enable
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_unmask
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_unmask
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_startup
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_irq_unmask
  - drivers/gpio/gpiolib.c:gpiochip_irq_enable
  - drivers/gpio/gpiolib.c:gpiochip_irq_unmask
  - drivers/gpio/gpio-crystalcove.c:crystalcove_irq_unmask
```
**Symbols:**

```
ffffffff818fd750-ffffffff818fd7c0: gpiochip_enable_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void gpiochip_enable_irq(struct gpio_chip *gc, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81944cf0)
Location: drivers/gpio/gpiolib.c:3647
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_enable
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_unmask
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_unmask
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_irq_unmask
  - drivers/gpio/gpiolib.c:gpiochip_irq_enable
  - drivers/gpio/gpiolib.c:gpiochip_irq_unmask
  - drivers/gpio/gpio-crystalcove.c:crystalcove_irq_unmask
```
**Symbols:**

```
ffffffff81944cf0-ffffffff81944d66: gpiochip_enable_irq (STB_GLOBAL)
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
void gpiochip_enable_irq(struct gpio_chip *chip, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffff8000106c04c8)
Location: drivers/gpio/gpiolib.c:3954
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_irq_enable
```
**Symbols:**

```
ffff8000106c04c8-ffff8000106c0560: gpiochip_enable_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void gpiochip_enable_irq(struct gpio_chip *chip, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (c085d6b8)
Location: drivers/gpio/gpiolib.c:3954
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_irq_enable
```
**Symbols:**

```
c085d6b8-c085d754: gpiochip_enable_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void gpiochip_enable_irq(struct gpio_chip *chip, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (c000000000839bc0)
Location: drivers/gpio/gpiolib.c:3954
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_irq_enable
```
**Symbols:**

```
c000000000839bc0-c000000000839c38: gpiochip_enable_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void gpiochip_enable_irq(struct gpio_chip *chip, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffe0004a46e2)
Location: drivers/gpio/gpiolib.c:3954
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_irq_enable
```
**Symbols:**

```
ffffffe0004a46e2-ffffffe0004a474c: gpiochip_enable_irq (STB_GLOBAL)
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
void gpiochip_enable_irq(struct gpio_chip *chip, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8155f9b0)
Location: drivers/gpio/gpiolib.c:3954
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_irq_enable
```
**Symbols:**

```
ffffffff8155f9b0-ffffffff8155f9fd: gpiochip_enable_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void gpiochip_enable_irq(struct gpio_chip *chip, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81550800)
Location: drivers/gpio/gpiolib.c:3954
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_irq_enable
```
**Symbols:**

```
ffffffff81550800-ffffffff8155084d: gpiochip_enable_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void gpiochip_enable_irq(struct gpio_chip *chip, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8155e520)
Location: drivers/gpio/gpiolib.c:3954
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_irq_enable
```
**Symbols:**

```
ffffffff8155e520-ffffffff8155e56d: gpiochip_enable_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void gpiochip_enable_irq(struct gpio_chip *chip, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff815783b0)
Location: drivers/gpio/gpiolib.c:3954
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_irq_enable
```
**Symbols:**

```
ffffffff815783b0-ffffffff815783fd: gpiochip_enable_irq (STB_GLOBAL)
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
