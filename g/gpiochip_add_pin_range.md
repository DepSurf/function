# Function: <code>gpiochip_add_pin_range</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int gpiochip_add_pin_range(struct gpio_chip *chip, const char *pinctl_name, unsigned int gpio_offset, unsigned int pin_offset, unsigned int npins);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81426960)
Location: drivers/gpio/gpiolib.c:829
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
```
**Symbols:**

```
ffffffff81426960-ffffffff81426a9d: gpiochip_add_pin_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int gpiochip_add_pin_range(struct gpio_chip *chip, const char *pinctl_name, unsigned int gpio_offset, unsigned int pin_offset, unsigned int npins);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff814705c0)
Location: drivers/gpio/gpiolib.c:1751
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
```
**Symbols:**

```
ffffffff814705c0-ffffffff8147070d: gpiochip_add_pin_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int gpiochip_add_pin_range(struct gpio_chip *chip, const char *pinctl_name, unsigned int gpio_offset, unsigned int pin_offset, unsigned int npins);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff814915c0)
Location: drivers/gpio/gpiolib.c:1938
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
```
**Symbols:**

```
ffffffff814915c0-ffffffff8149170d: gpiochip_add_pin_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int gpiochip_add_pin_range(struct gpio_chip *chip, const char *pinctl_name, unsigned int gpio_offset, unsigned int pin_offset, unsigned int npins);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8149b050)
Location: drivers/gpio/gpiolib.c:1939
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
```
**Symbols:**

```
ffffffff8149b050-ffffffff8149b194: gpiochip_add_pin_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int gpiochip_add_pin_range(struct gpio_chip *chip, const char *pinctl_name, unsigned int gpio_offset, unsigned int pin_offset, unsigned int npins);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff814d9590)
Location: drivers/gpio/gpiolib.c:2076
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_probe
```
**Symbols:**

```
ffffffff814d9590-ffffffff814d96d4: gpiochip_add_pin_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int gpiochip_add_pin_range(struct gpio_chip *chip, const char *pinctl_name, unsigned int gpio_offset, unsigned int pin_offset, unsigned int npins);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff815085b0)
Location: drivers/gpio/gpiolib.c:2193
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
```
**Symbols:**

```
ffffffff815085b0-ffffffff81508701: gpiochip_add_pin_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int gpiochip_add_pin_range(struct gpio_chip *chip, const char *pinctl_name, unsigned int gpio_offset, unsigned int pin_offset, unsigned int npins);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8151bd20)
Location: drivers/gpio/gpiolib.c:2208
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
```
**Symbols:**

```
ffffffff8151bd20-ffffffff8151be71: gpiochip_add_pin_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int gpiochip_add_pin_range(struct gpio_chip *chip, const char *pinctl_name, unsigned int gpio_offset, unsigned int pin_offset, unsigned int npins);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:2272
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_probe
```
**Symbols:**

```
ffffffff8154edcf-ffffffff8154ee1a: gpiochip_add_pin_range.cold (STB_LOCAL)
ffffffff8154a050-ffffffff8154a158: gpiochip_add_pin_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int gpiochip_add_pin_range(struct gpio_chip *chip, const char *pinctl_name, unsigned int gpio_offset, unsigned int pin_offset, unsigned int npins);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:2604
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
```
**Symbols:**

```
ffffffff81570397-ffffffff815703e2: gpiochip_add_pin_range.cold (STB_LOCAL)
ffffffff8156b1f0-ffffffff8156b2f8: gpiochip_add_pin_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int gpiochip_add_pin_range(struct gpio_chip *gc, const char *pinctl_name, unsigned int gpio_offset, unsigned int pin_offset, unsigned int npins);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:2971
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_add_pin_ranges
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_add_pin_ranges
```
**Symbols:**

```
ffffffff816143ca-ffffffff81614415: gpiochip_add_pin_range.cold (STB_LOCAL)
ffffffff8160e6d0-ffffffff8160e7d8: gpiochip_add_pin_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int gpiochip_add_pin_range(struct gpio_chip *gc, const char *pinctl_name, unsigned int gpio_offset, unsigned int pin_offset, unsigned int npins);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:1774
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_add_pin_ranges
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_add_pin_ranges
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_add_pin_ranges
```
**Symbols:**

```
ffffffff81bf5bca-ffffffff81bf5c15: gpiochip_add_pin_range.cold (STB_LOCAL)
ffffffff81634d00-ffffffff81634e08: gpiochip_add_pin_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int gpiochip_add_pin_range(struct gpio_chip *gc, const char *pinctl_name, unsigned int gpio_offset, unsigned int pin_offset, unsigned int npins);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:1751
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_add_pin_ranges
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_add_pin_ranges
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_add_pin_ranges
```
**Symbols:**

```
ffffffff81be7ab8-ffffffff81be7b03: gpiochip_add_pin_range.cold (STB_LOCAL)
ffffffff816189d0-ffffffff81618ad8: gpiochip_add_pin_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int gpiochip_add_pin_range(struct gpio_chip *gc, const char *pinctl_name, unsigned int gpio_offset, unsigned int pin_offset, unsigned int npins);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:1773
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_add_pin_ranges
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_add_pin_ranges
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_add_pin_ranges
```
**Symbols:**

```
ffffffff81ce15ad-ffffffff81ce15f8: gpiochip_add_pin_range.cold (STB_LOCAL)
ffffffff81687d40-ffffffff81687e45: gpiochip_add_pin_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int gpiochip_add_pin_range(struct gpio_chip *gc, const char *pinctl_name, unsigned int gpio_offset, unsigned int pin_offset, unsigned int npins);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:1834
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_add_pin_ranges
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_add_pin_ranges
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_add_pin_ranges
```
**Symbols:**

```
ffffffff81ea7f26-ffffffff81ea7f71: gpiochip_add_pin_range.cold (STB_LOCAL)
ffffffff817a5020-ffffffff817a512f: gpiochip_add_pin_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int gpiochip_add_pin_range(struct gpio_chip *gc, const char *pinctl_name, unsigned int gpio_offset, unsigned int pin_offset, unsigned int npins);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff818bcf80)
Location: drivers/gpio/gpiolib.c:1904
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_add_pin_ranges
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_add_pin_ranges
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_add_pin_ranges
```
**Symbols:**

```
ffffffff818bcf80-ffffffff818bd0c7: gpiochip_add_pin_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int gpiochip_add_pin_range(struct gpio_chip *gc, const char *pinctl_name, unsigned int gpio_offset, unsigned int pin_offset, unsigned int npins);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff819000a0)
Location: drivers/gpio/gpiolib.c:1943
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_add_pin_ranges
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_add_pin_ranges
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_add_pin_ranges
```
**Symbols:**

```
ffffffff819000a0-ffffffff819001e7: gpiochip_add_pin_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int gpiochip_add_pin_range(struct gpio_chip *gc, const char *pinctl_name, unsigned int gpio_offset, unsigned int pin_offset, unsigned int npins);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff819479d0)
Location: drivers/gpio/gpiolib.c:2126
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_add_pin_ranges
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_add_pin_ranges
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_gpio_add_pin_ranges
```
**Symbols:**

```
ffffffff819479d0-ffffffff81947b46: gpiochip_add_pin_range (STB_GLOBAL)
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
int gpiochip_add_pin_range(struct gpio_chip *chip, const char *pinctl_name, unsigned int gpio_offset, unsigned int pin_offset, unsigned int npins);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffff8000106beb48)
Location: drivers/gpio/gpiolib.c:2604
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-as3722.c:as3722_pinctrl_probe
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
  - drivers/pinctrl/qcom/pinctrl-msm.c:msm_pinctrl_probe
  - drivers/pinctrl/sunxi/pinctrl-sunxi.c:sunxi_pinctrl_init_with_variant
  - drivers/pinctrl/mediatek/pinctrl-mtk-common.c:mtk_pctrl_init
  - drivers/pinctrl/mediatek/pinctrl-mtk-common.c:mtk_pctrl_init
  - drivers/pinctrl/mediatek/pinctrl-moore.c:mtk_moore_pinctrl_probe
  - drivers/gpio/gpiolib-of.c:of_gpiochip_add
```
**Symbols:**

```
ffff8000106beb48-ffff8000106bec98: gpiochip_add_pin_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int gpiochip_add_pin_range(struct gpio_chip *chip, const char *pinctl_name, unsigned int gpio_offset, unsigned int pin_offset, unsigned int npins);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (c085e8f0)
Location: drivers/gpio/gpiolib.c:2604
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-as3722.c:as3722_pinctrl_probe
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
  - drivers/pinctrl/nuvoton/pinctrl-npcm7xx.c:npcm7xx_pinctrl_probe
  - drivers/pinctrl/qcom/pinctrl-msm.c:msm_pinctrl_probe
  - drivers/pinctrl/mediatek/pinctrl-mtk-common.c:mtk_pctrl_init
  - drivers/pinctrl/mediatek/pinctrl-moore.c:mtk_moore_pinctrl_probe
  - drivers/gpio/gpiolib-of.c:of_gpiochip_add
```
**Symbols:**

```
c085e8f0-c085ea44: gpiochip_add_pin_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int gpiochip_add_pin_range(struct gpio_chip *chip, const char *pinctl_name, unsigned int gpio_offset, unsigned int pin_offset, unsigned int npins);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (c00000000083e9d0)
Location: drivers/gpio/gpiolib.c:2604
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-as3722.c:as3722_pinctrl_probe
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
  - drivers/gpio/gpiolib-of.c:of_gpiochip_add
```
**Symbols:**

```
c00000000083e9d0-c00000000083eb80: gpiochip_add_pin_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int gpiochip_add_pin_range(struct gpio_chip *chip, const char *pinctl_name, unsigned int gpio_offset, unsigned int pin_offset, unsigned int npins);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffe0004a59fa)
Location: drivers/gpio/gpiolib.c:2604
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-as3722.c:as3722_pinctrl_probe
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
  - drivers/gpio/gpiolib-of.c:of_gpiochip_add
```
**Symbols:**

```
ffffffe0004a59fa-ffffffe0004a5b3a: gpiochip_add_pin_range (STB_GLOBAL)
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
int gpiochip_add_pin_range(struct gpio_chip *chip, const char *pinctl_name, unsigned int gpio_offset, unsigned int pin_offset, unsigned int npins);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:2604
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
```
**Symbols:**

```
ffffffff81565b57-ffffffff81565ba2: gpiochip_add_pin_range.cold (STB_LOCAL)
ffffffff815609b0-ffffffff81560ab8: gpiochip_add_pin_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int gpiochip_add_pin_range(struct gpio_chip *chip, const char *pinctl_name, unsigned int gpio_offset, unsigned int pin_offset, unsigned int npins);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:2604
Inline: False
Direct callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
```
**Symbols:**

```
ffffffff815569a7-ffffffff815569f2: gpiochip_add_pin_range.cold (STB_LOCAL)
ffffffff81551800-ffffffff81551908: gpiochip_add_pin_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int gpiochip_add_pin_range(struct gpio_chip *chip, const char *pinctl_name, unsigned int gpio_offset, unsigned int pin_offset, unsigned int npins);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:2604
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
```
**Symbols:**

```
ffffffff815646c7-ffffffff81564712: gpiochip_add_pin_range.cold (STB_LOCAL)
ffffffff8155f520-ffffffff8155f628: gpiochip_add_pin_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int gpiochip_add_pin_range(struct gpio_chip *chip, const char *pinctl_name, unsigned int gpio_offset, unsigned int pin_offset, unsigned int npins);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:2604
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
```
**Symbols:**

```
ffffffff8157e5e7-ffffffff8157e632: gpiochip_add_pin_range.cold (STB_LOCAL)
ffffffff815793a0-ffffffff815794a8: gpiochip_add_pin_range (STB_GLOBAL)
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
