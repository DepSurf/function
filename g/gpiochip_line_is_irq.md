# Function: <code>gpiochip_line_is_irq</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
bool gpiochip_line_is_irq(struct gpio_chip *chip, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8146ec70)
Location: drivers/gpio/gpiolib.c:2636
Inline: True
```
**Symbols:**

```
ffffffff8146ec70-ffffffff8146eca4: gpiochip_line_is_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
bool gpiochip_line_is_irq(struct gpio_chip *chip, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81490c40)
Location: drivers/gpio/gpiolib.c:2845
Inline: True
```
**Symbols:**

```
ffffffff81490c40-ffffffff81490c74: gpiochip_line_is_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
bool gpiochip_line_is_irq(struct gpio_chip *chip, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8149a5b0)
Location: drivers/gpio/gpiolib.c:2842
Inline: True
```
**Symbols:**

```
ffffffff8149a5b0-ffffffff8149a5e1: gpiochip_line_is_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
bool gpiochip_line_is_irq(struct gpio_chip *chip, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff814d88c0)
Location: drivers/gpio/gpiolib.c:3113
Inline: True
```
**Symbols:**

```
ffffffff814d88c0-ffffffff814d88f4: gpiochip_line_is_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
bool gpiochip_line_is_irq(struct gpio_chip *chip, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81507e10)
Location: drivers/gpio/gpiolib.c:3305
Inline: True
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_should_save
```
**Symbols:**

```
ffffffff81507e10-ffffffff81507e44: gpiochip_line_is_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
bool gpiochip_line_is_irq(struct gpio_chip *chip, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8151c780)
Location: drivers/gpio/gpiolib.c:3523
Inline: True
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_should_save
```
**Symbols:**

```
ffffffff8151c780-ffffffff8151c7b4: gpiochip_line_is_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
bool gpiochip_line_is_irq(struct gpio_chip *chip, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8154aa10)
Location: drivers/gpio/gpiolib.c:3612
Inline: True
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_should_save
```
**Symbols:**

```
ffffffff8154aa10-ffffffff8154aa44: gpiochip_line_is_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
bool gpiochip_line_is_irq(struct gpio_chip *chip, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8156b900)
Location: drivers/gpio/gpiolib.c:3966
Inline: True
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_should_save
```
**Symbols:**

```
ffffffff8156b900-ffffffff8156b934: gpiochip_line_is_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
bool gpiochip_line_is_irq(struct gpio_chip *gc, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8160e120)
Location: drivers/gpio/gpiolib.c:4379
Inline: True
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_resume
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_suspend
```
**Symbols:**

```
ffffffff8160e120-ffffffff8160e154: gpiochip_line_is_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
bool gpiochip_line_is_irq(struct gpio_chip *gc, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff816349e0)
Location: drivers/gpio/gpiolib.c:3203
Inline: True
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_resume
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_suspend
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_should_save
```
**Symbols:**

```
ffffffff816349e0-ffffffff81634a18: gpiochip_line_is_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
bool gpiochip_line_is_irq(struct gpio_chip *gc, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81618460)
Location: drivers/gpio/gpiolib.c:3180
Inline: True
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_resume
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_suspend
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_should_save
```
**Symbols:**

```
ffffffff81618460-ffffffff81618498: gpiochip_line_is_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
bool gpiochip_line_is_irq(struct gpio_chip *gc, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff816876f0)
Location: drivers/gpio/gpiolib.c:3239
Inline: True
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_resume
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_suspend
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_should_save
```
**Symbols:**

```
ffffffff816876f0-ffffffff81687728: gpiochip_line_is_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
bool gpiochip_line_is_irq(struct gpio_chip *gc, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff817a4950)
Location: drivers/gpio/gpiolib.c:3360
Inline: True
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_should_save
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_should_save
```
**Symbols:**

```
ffffffff817a4950-ffffffff817a4992: gpiochip_line_is_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
bool gpiochip_line_is_irq(struct gpio_chip *gc, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff818bc6e0)
Location: drivers/gpio/gpiolib.c:3430
Inline: True
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_should_save
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_should_save
```
**Symbols:**

```
ffffffff818bc6e0-ffffffff818bc722: gpiochip_line_is_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
bool gpiochip_line_is_irq(struct gpio_chip *gc, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff818ff050)
Location: drivers/gpio/gpiolib.c:3471
Inline: True
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_should_save
  - drivers/pinctrl/pinctrl-amd.c:do_amd_gpio_irq_handler
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_should_save
```
**Symbols:**

```
ffffffff818ff050-ffffffff818ff092: gpiochip_line_is_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
bool gpiochip_line_is_irq(struct gpio_chip *gc, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81946950)
Location: drivers/gpio/gpiolib.c:3664
Inline: True
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_should_save
  - drivers/pinctrl/pinctrl-amd.c:do_amd_gpio_irq_handler
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_should_save
```
**Symbols:**

```
ffffffff81946950-ffffffff8194698e: gpiochip_line_is_irq (STB_GLOBAL)
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
bool gpiochip_line_is_irq(struct gpio_chip *chip, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffff8000106bee48)
Location: drivers/gpio/gpiolib.c:3966
Inline: True
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_should_save
  - drivers/pinctrl/sunxi/pinctrl-sunxi.c:sunxi_pinctrl_gpio_get
```
**Symbols:**

```
ffff8000106bee48-ffff8000106beea4: gpiochip_line_is_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
bool gpiochip_line_is_irq(struct gpio_chip *chip, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (c085f428)
Location: drivers/gpio/gpiolib.c:3966
Inline: True
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_should_save
```
**Symbols:**

```
c085f428-c085f460: gpiochip_line_is_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
bool gpiochip_line_is_irq(struct gpio_chip *chip, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (c00000000083c7f0)
Location: drivers/gpio/gpiolib.c:3966
Inline: True
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_should_save
```
**Symbols:**

```
c00000000083c7f0-c00000000083c828: gpiochip_line_is_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
bool gpiochip_line_is_irq(struct gpio_chip *chip, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffe0004a62c6)
Location: drivers/gpio/gpiolib.c:3966
Inline: True
```
**Symbols:**

```
ffffffe0004a62c6-ffffffe0004a630a: gpiochip_line_is_irq (STB_GLOBAL)
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
bool gpiochip_line_is_irq(struct gpio_chip *chip, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff815610c0)
Location: drivers/gpio/gpiolib.c:3966
Inline: True
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_should_save
```
**Symbols:**

```
ffffffff815610c0-ffffffff815610f4: gpiochip_line_is_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
bool gpiochip_line_is_irq(struct gpio_chip *chip, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81551f10)
Location: drivers/gpio/gpiolib.c:3966
Inline: True
```
**Symbols:**

```
ffffffff81551f10-ffffffff81551f44: gpiochip_line_is_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
bool gpiochip_line_is_irq(struct gpio_chip *chip, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8155fc30)
Location: drivers/gpio/gpiolib.c:3966
Inline: True
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_should_save
```
**Symbols:**

```
ffffffff8155fc30-ffffffff8155fc64: gpiochip_line_is_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
bool gpiochip_line_is_irq(struct gpio_chip *chip, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81579a90)
Location: drivers/gpio/gpiolib.c:3966
Inline: True
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_should_save
```
**Symbols:**

```
ffffffff81579a90-ffffffff81579ac4: gpiochip_line_is_irq (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
