# Function: <code>gpiochip_lock_as_irq</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int gpiochip_lock_as_irq(struct gpio_chip *chip, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81424fc0)
Location: drivers/gpio/gpiolib.c:1618
Inline: True
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_irq_reqres
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupt
```
**Symbols:**

```
ffffffff81424fc0-ffffffff81425014: gpiochip_lock_as_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int gpiochip_lock_as_irq(struct gpio_chip *chip, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8146ddd0)
Location: drivers/gpio/gpiolib.c:2589
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_irq_reqres
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupt
```
**Symbols:**

```
ffffffff8146ddd0-ffffffff8146de63: gpiochip_lock_as_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int gpiochip_lock_as_irq(struct gpio_chip *chip, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8148fc90)
Location: drivers/gpio/gpiolib.c:2779
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_irq_reqres
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupt
```
**Symbols:**

```
ffffffff8148fc90-ffffffff8148fd3f: gpiochip_lock_as_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int gpiochip_lock_as_irq(struct gpio_chip *chip, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81499550)
Location: drivers/gpio/gpiolib.c:2776
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_irq_reqres
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupt
```
**Symbols:**

```
ffffffff81499550-ffffffff814995fc: gpiochip_lock_as_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int gpiochip_lock_as_irq(struct gpio_chip *chip, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff814d7850)
Location: drivers/gpio/gpiolib.c:3047
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_irq_reqres
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupt
```
**Symbols:**

```
ffffffff814d7850-ffffffff814d78ff: gpiochip_lock_as_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int gpiochip_lock_as_irq(struct gpio_chip *chip, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81506a70)
Location: drivers/gpio/gpiolib.c:3239
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_irq_reqres
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupt
```
**Symbols:**

```
ffffffff81506a70-ffffffff81506b23: gpiochip_lock_as_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int gpiochip_lock_as_irq(struct gpio_chip *chip, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8151c5e0)
Location: drivers/gpio/gpiolib.c:3432
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_reqres_irq
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event
```
**Symbols:**

```
ffffffff8151c5e0-ffffffff8151c6cc: gpiochip_lock_as_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int gpiochip_lock_as_irq(struct gpio_chip *chip, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:3521
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_reqres_irq
  - drivers/gpio/gpiolib.c:gpiochip_irq_domain_activate
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event
```
**Symbols:**

```
ffffffff8154ee1a-ffffffff8154ee6f: gpiochip_lock_as_irq.cold (STB_LOCAL)
ffffffff8154a8e0-ffffffff8154a97b: gpiochip_lock_as_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int gpiochip_lock_as_irq(struct gpio_chip *chip, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:3875
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_reqres_irq
  - drivers/gpio/gpiolib.c:gpiochip_irq_domain_activate
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event
```
**Symbols:**

```
ffffffff8157018a-ffffffff815701df: gpiochip_lock_as_irq.cold (STB_LOCAL)
ffffffff8156a290-ffffffff8156a32b: gpiochip_lock_as_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int gpiochip_lock_as_irq(struct gpio_chip *gc, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:4281
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_irq_reqres
  - drivers/gpio/gpiolib.c:gpiochip_irq_domain_activate
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event
```
**Symbols:**

```
ffffffff816144ff-ffffffff81614554: gpiochip_lock_as_irq.cold (STB_LOCAL)
ffffffff8160f6b0-ffffffff8160f754: gpiochip_lock_as_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int gpiochip_lock_as_irq(struct gpio_chip *gc, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:3105
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_irq_reqres
  - drivers/gpio/gpiolib.c:gpiochip_irq_domain_activate
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event
```
**Symbols:**

```
ffffffff81bf5c15-ffffffff81bf5c6a: gpiochip_lock_as_irq.cold (STB_LOCAL)
ffffffff81635270-ffffffff81635318: gpiochip_lock_as_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int gpiochip_lock_as_irq(struct gpio_chip *gc, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:3082
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_irq_reqres
  - drivers/gpio/gpiolib.c:gpiochip_irq_domain_activate
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event
```
**Symbols:**

```
ffffffff81be7b03-ffffffff81be7b58: gpiochip_lock_as_irq.cold (STB_LOCAL)
ffffffff81618d10-ffffffff81618db8: gpiochip_lock_as_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int gpiochip_lock_as_irq(struct gpio_chip *gc, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:3141
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_irq_reqres
  - drivers/gpio/gpiolib.c:gpiochip_irq_domain_activate
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event
```
**Symbols:**

```
ffffffff81ce160d-ffffffff81ce1677: gpiochip_lock_as_irq.cold (STB_LOCAL)
ffffffff81688250-ffffffff81688312: gpiochip_lock_as_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int gpiochip_lock_as_irq(struct gpio_chip *gc, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:3262
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_irq_reqres
  - drivers/gpio/gpiolib.c:gpiochip_irq_domain_activate
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event
```
**Symbols:**

```
ffffffff81ea7c3f-ffffffff81ea7ca9: gpiochip_lock_as_irq.cold (STB_LOCAL)
ffffffff817a3f90-ffffffff817a4064: gpiochip_lock_as_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int gpiochip_lock_as_irq(struct gpio_chip *gc, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:3332
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_reqres_irq
  - drivers/gpio/gpiolib.c:gpiochip_irq_domain_activate
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event
```
**Symbols:**

```
ffffffff8208e4d7-ffffffff8208e4ec: gpiochip_lock_as_irq.cold (STB_LOCAL)
ffffffff818bb920-ffffffff818bba33: gpiochip_lock_as_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int gpiochip_lock_as_irq(struct gpio_chip *gc, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:3373
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_reqres_irq
  - drivers/gpio/gpiolib.c:gpiochip_irq_domain_activate
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event
```
**Symbols:**

```
ffffffff8210e7ac-ffffffff8210e7c1: gpiochip_lock_as_irq.cold (STB_LOCAL)
ffffffff818feb40-ffffffff818fec53: gpiochip_lock_as_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int gpiochip_lock_as_irq(struct gpio_chip *gc, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:3566
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_reqres_irq
  - drivers/gpio/gpiolib.c:gpiochip_irq_domain_activate
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event
```
**Symbols:**

```
ffffffff821ec3f1-ffffffff821ec406: gpiochip_lock_as_irq.cold (STB_LOCAL)
ffffffff819461e0-ffffffff81946315: gpiochip_lock_as_irq (STB_GLOBAL)
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
int gpiochip_lock_as_irq(struct gpio_chip *chip, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffff8000106c1e40)
Location: drivers/gpio/gpiolib.c:3875
Inline: False
Direct callers:
  - drivers/pinctrl/qcom/pinctrl-msm.c:msm_gpio_irq_reqres
  - drivers/pinctrl/sunxi/pinctrl-sunxi.c:sunxi_pinctrl_irq_request_resources
  - drivers/pinctrl/mediatek/mtk-eint.c:mtk_eint_irq_request_resources
  - drivers/gpio/gpiolib.c:gpiochip_reqres_irq
  - drivers/gpio/gpiolib.c:gpiochip_irq_domain_activate
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event
```
**Symbols:**

```
ffff8000106c1e40-ffff8000106c1f88: gpiochip_lock_as_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int gpiochip_lock_as_irq(struct gpio_chip *chip, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (c085d79c)
Location: drivers/gpio/gpiolib.c:3875
Inline: False
Direct callers:
  - drivers/pinctrl/qcom/pinctrl-msm.c:msm_gpio_irq_reqres
  - drivers/pinctrl/samsung/pinctrl-exynos.c:exynos_irq_request_resources
  - drivers/pinctrl/mediatek/mtk-eint.c:mtk_eint_irq_request_resources
  - drivers/gpio/gpiolib.c:gpiochip_reqres_irq
  - drivers/gpio/gpiolib.c:gpiochip_irq_domain_activate
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq
  - drivers/gpio/gpio-tegra.c:tegra_gpio_irq_set_type
```
**Symbols:**

```
c085d79c-c085d8a0: gpiochip_lock_as_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int gpiochip_lock_as_irq(struct gpio_chip *chip, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (c000000000839ce0)
Location: drivers/gpio/gpiolib.c:3875
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_reqres_irq
  - drivers/gpio/gpiolib.c:gpiochip_irq_domain_activate
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq
```
**Symbols:**

```
c000000000839ce0-c000000000839e70: gpiochip_lock_as_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int gpiochip_lock_as_irq(struct gpio_chip *chip, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffe0004a47a0)
Location: drivers/gpio/gpiolib.c:3875
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_reqres_irq
  - drivers/gpio/gpiolib.c:gpiochip_irq_domain_activate
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq
```
**Symbols:**

```
ffffffe0004a47a0-ffffffe0004a489a: gpiochip_lock_as_irq (STB_GLOBAL)
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
int gpiochip_lock_as_irq(struct gpio_chip *chip, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:3875
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_reqres_irq
  - drivers/gpio/gpiolib.c:gpiochip_irq_domain_activate
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event
```
**Symbols:**

```
ffffffff8156594a-ffffffff8156599f: gpiochip_lock_as_irq.cold (STB_LOCAL)
ffffffff8155fa50-ffffffff8155faeb: gpiochip_lock_as_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int gpiochip_lock_as_irq(struct gpio_chip *chip, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:3875
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_reqres_irq
  - drivers/gpio/gpiolib.c:gpiochip_irq_domain_activate
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event
```
**Symbols:**

```
ffffffff8155679a-ffffffff815567ef: gpiochip_lock_as_irq.cold (STB_LOCAL)
ffffffff815508a0-ffffffff8155093b: gpiochip_lock_as_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int gpiochip_lock_as_irq(struct gpio_chip *chip, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:3875
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_reqres_irq
  - drivers/gpio/gpiolib.c:gpiochip_irq_domain_activate
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event
```
**Symbols:**

```
ffffffff815644ba-ffffffff8156450f: gpiochip_lock_as_irq.cold (STB_LOCAL)
ffffffff8155e5c0-ffffffff8155e65b: gpiochip_lock_as_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int gpiochip_lock_as_irq(struct gpio_chip *chip, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:3875
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_reqres_irq
  - drivers/gpio/gpiolib.c:gpiochip_irq_domain_activate
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event
```
**Symbols:**

```
ffffffff8157e3da-ffffffff8157e42f: gpiochip_lock_as_irq.cold (STB_LOCAL)
ffffffff81578450-ffffffff815784eb: gpiochip_lock_as_irq (STB_GLOBAL)
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
