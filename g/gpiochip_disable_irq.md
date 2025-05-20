# Function: <code>gpiochip_disable_irq</code>

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
void gpiochip_disable_irq(struct gpio_chip *chip, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8151a9f0)
Location: drivers/gpio/gpiolib.c:3501
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_irq_disable
```
**Symbols:**

```
ffffffff8151a9f0-ffffffff8151aa31: gpiochip_disable_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void gpiochip_disable_irq(struct gpio_chip *chip, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:3590
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_irq_disable
```
**Symbols:**

```
ffffffff8154ed2d-ffffffff8154ed40: gpiochip_disable_irq.cold (STB_LOCAL)
ffffffff81549280-ffffffff815492c1: gpiochip_disable_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void gpiochip_disable_irq(struct gpio_chip *chip, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8156a160)
Location: drivers/gpio/gpiolib.c:3944
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_irq_disable
```
**Symbols:**

```
ffffffff8156a160-ffffffff8156a1a0: gpiochip_disable_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void gpiochip_disable_irq(struct gpio_chip *gc, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8160e340)
Location: drivers/gpio/gpiolib.c:4352
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_irq_disable
  - drivers/gpio/gpiolib.c:gpiochip_irq_mask
```
**Symbols:**

```
ffffffff8160e340-ffffffff8160e382: gpiochip_disable_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void gpiochip_disable_irq(struct gpio_chip *gc, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81634e10)
Location: drivers/gpio/gpiolib.c:3176
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_irq_disable
  - drivers/gpio/gpiolib.c:gpiochip_irq_mask
```
**Symbols:**

```
ffffffff81634e10-ffffffff81634e55: gpiochip_disable_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void gpiochip_disable_irq(struct gpio_chip *gc, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff816186f0)
Location: drivers/gpio/gpiolib.c:3153
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_irq_disable
  - drivers/gpio/gpiolib.c:gpiochip_irq_mask
```
**Symbols:**

```
ffffffff816186f0-ffffffff81618735: gpiochip_disable_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void gpiochip_disable_irq(struct gpio_chip *gc, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81687990)
Location: drivers/gpio/gpiolib.c:3212
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_irq_disable
  - drivers/gpio/gpiolib.c:gpiochip_irq_mask
```
**Symbols:**

```
ffffffff81687990-ffffffff816879d5: gpiochip_disable_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void gpiochip_disable_irq(struct gpio_chip *gc, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff817a30d0)
Location: drivers/gpio/gpiolib.c:3333
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_disable
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_mask
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_mask
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_irq_mask
  - drivers/gpio/gpiolib.c:gpiochip_irq_disable
  - drivers/gpio/gpiolib.c:gpiochip_irq_mask
  - drivers/gpio/gpio-crystalcove.c:crystalcove_irq_mask
```
**Symbols:**

```
ffffffff817a30d0-ffffffff817a312d: gpiochip_disable_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void gpiochip_disable_irq(struct gpio_chip *gc, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff818ba540)
Location: drivers/gpio/gpiolib.c:3403
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_disable
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_mask
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_mask
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_irq_mask
  - drivers/gpio/gpiolib.c:gpiochip_irq_disable
  - drivers/gpio/gpiolib.c:gpiochip_irq_mask
  - drivers/gpio/gpio-crystalcove.c:crystalcove_irq_mask
```
**Symbols:**

```
ffffffff818ba540-ffffffff818ba59d: gpiochip_disable_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void gpiochip_disable_irq(struct gpio_chip *gc, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff818fd640)
Location: drivers/gpio/gpiolib.c:3444
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_disable
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_mask
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_mask
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_mask
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_irq_mask
  - drivers/gpio/gpiolib.c:gpiochip_irq_disable
  - drivers/gpio/gpiolib.c:gpiochip_irq_mask
  - drivers/gpio/gpio-crystalcove.c:crystalcove_irq_mask
```
**Symbols:**

```
ffffffff818fd640-ffffffff818fd69d: gpiochip_disable_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void gpiochip_disable_irq(struct gpio_chip *gc, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81944bd0)
Location: drivers/gpio/gpiolib.c:3637
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_irq_disable
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_irq_mask
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_irq_mask
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_irq_mask
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_irq_mask
  - drivers/gpio/gpiolib.c:gpiochip_irq_disable
  - drivers/gpio/gpiolib.c:gpiochip_irq_mask
  - drivers/gpio/gpio-crystalcove.c:crystalcove_irq_mask
```
**Symbols:**

```
ffffffff81944bd0-ffffffff81944c34: gpiochip_disable_irq (STB_GLOBAL)
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
void gpiochip_disable_irq(struct gpio_chip *chip, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffff8000106c02b8)
Location: drivers/gpio/gpiolib.c:3944
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_irq_disable
```
**Symbols:**

```
ffff8000106c02b8-ffff8000106c0348: gpiochip_disable_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void gpiochip_disable_irq(struct gpio_chip *chip, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (c085d538)
Location: drivers/gpio/gpiolib.c:3944
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_irq_disable
```
**Symbols:**

```
c085d538-c085d5ac: gpiochip_disable_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void gpiochip_disable_irq(struct gpio_chip *chip, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (c000000000839ac0)
Location: drivers/gpio/gpiolib.c:3944
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_irq_disable
```
**Symbols:**

```
c000000000839ac0-c000000000839b2c: gpiochip_disable_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void gpiochip_disable_irq(struct gpio_chip *chip, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffe0004a463c)
Location: drivers/gpio/gpiolib.c:3944
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_irq_disable
```
**Symbols:**

```
ffffffe0004a463c-ffffffe0004a469a: gpiochip_disable_irq (STB_GLOBAL)
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
void gpiochip_disable_irq(struct gpio_chip *chip, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8155f920)
Location: drivers/gpio/gpiolib.c:3944
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_irq_disable
```
**Symbols:**

```
ffffffff8155f920-ffffffff8155f960: gpiochip_disable_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void gpiochip_disable_irq(struct gpio_chip *chip, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81550770)
Location: drivers/gpio/gpiolib.c:3944
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_irq_disable
```
**Symbols:**

```
ffffffff81550770-ffffffff815507b0: gpiochip_disable_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void gpiochip_disable_irq(struct gpio_chip *chip, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8155e490)
Location: drivers/gpio/gpiolib.c:3944
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_irq_disable
```
**Symbols:**

```
ffffffff8155e490-ffffffff8155e4d0: gpiochip_disable_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void gpiochip_disable_irq(struct gpio_chip *chip, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81578320)
Location: drivers/gpio/gpiolib.c:3944
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_irq_disable
```
**Symbols:**

```
ffffffff81578320-ffffffff81578360: gpiochip_disable_irq (STB_GLOBAL)
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
