# Function: <code>gpiochip_unlock_as_irq</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
void gpiochip_unlock_as_irq(struct gpio_chip *chip, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81424e30)
Location: drivers/gpio/gpiolib.c:1643
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_irq_relres
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_irq_relres
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_free_irq
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_free_interrupts
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupt
```
**Symbols:**

```
ffffffff81424e30-ffffffff81424e4d: gpiochip_unlock_as_irq.part.14 (STB_LOCAL)
ffffffff81424e50-ffffffff81424e6c: gpiochip_unlock_as_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void gpiochip_unlock_as_irq(struct gpio_chip *chip, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8146ec42)
Location: drivers/gpio/gpiolib.c:2627
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_irq_relres
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_irq_relres
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_free_irq
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_free_interrupts
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupt
```
**Symbols:**

```
ffffffff8146ebe0-ffffffff8146ec01: gpiochip_unlock_as_irq.part.18 (STB_LOCAL)
ffffffff8146ec10-ffffffff8146ec2c: gpiochip_unlock_as_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void gpiochip_unlock_as_irq(struct gpio_chip *chip, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8148fef0)
Location: drivers/gpio/gpiolib.c:2829
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_irq_relres
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_free_irq
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_free_interrupts
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupt
```
**Symbols:**

```
ffffffff8148fef0-ffffffff8148ff44: gpiochip_unlock_as_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void gpiochip_unlock_as_irq(struct gpio_chip *chip, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff814996a0)
Location: drivers/gpio/gpiolib.c:2826
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_irq_relres
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_free_irq
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_free_interrupts
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupt
```
**Symbols:**

```
ffffffff814996a0-ffffffff814996f4: gpiochip_unlock_as_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void gpiochip_unlock_as_irq(struct gpio_chip *chip, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff814d79a0)
Location: drivers/gpio/gpiolib.c:3097
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_irq_relres
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_free_irq
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_free_interrupts
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupt
```
**Symbols:**

```
ffffffff814d79a0-ffffffff814d79f5: gpiochip_unlock_as_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void gpiochip_unlock_as_irq(struct gpio_chip *chip, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81506d50)
Location: drivers/gpio/gpiolib.c:3289
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_irq_relres
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_free_irq
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_free_interrupts
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_request_interrupt
```
**Symbols:**

```
ffffffff81506d50-ffffffff81506dad: gpiochip_unlock_as_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void gpiochip_unlock_as_irq(struct gpio_chip *chip, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8151b2f0)
Location: drivers/gpio/gpiolib.c:3484
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_irq_relres
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_free_irq
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_free_interrupts
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event
```
**Symbols:**

```
ffffffff8151b2f0-ffffffff8151b352: gpiochip_unlock_as_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void gpiochip_unlock_as_irq(struct gpio_chip *chip, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff815494a0)
Location: drivers/gpio/gpiolib.c:3573
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_irq_relres
  - drivers/gpio/gpiolib.c:gpiochip_irq_domain_deactivate
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_free_irq
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_free_interrupts
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event
```
**Symbols:**

```
ffffffff815494a0-ffffffff81549501: gpiochip_unlock_as_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void gpiochip_unlock_as_irq(struct gpio_chip *chip, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8156a770)
Location: drivers/gpio/gpiolib.c:3927
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_irq_relres
  - drivers/gpio/gpiolib.c:gpiochip_irq_domain_deactivate
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_free_irq
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_free_interrupts
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event
```
**Symbols:**

```
ffffffff8156a770-ffffffff8156a7d1: gpiochip_unlock_as_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void gpiochip_unlock_as_irq(struct gpio_chip *gc, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8160e540)
Location: drivers/gpio/gpiolib.c:4335
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_irq_relres
  - drivers/gpio/gpiolib.c:gpiochip_irq_domain_deactivate
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_free_interrupts
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event
```
**Symbols:**

```
ffffffff8160e540-ffffffff8160e5a2: gpiochip_unlock_as_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void gpiochip_unlock_as_irq(struct gpio_chip *gc, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81634ee0)
Location: drivers/gpio/gpiolib.c:3159
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_irq_relres
  - drivers/gpio/gpiolib.c:gpiochip_irq_domain_deactivate
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_free_interrupts
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event
```
**Symbols:**

```
ffffffff81634ee0-ffffffff81634f46: gpiochip_unlock_as_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void gpiochip_unlock_as_irq(struct gpio_chip *gc, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff816187b0)
Location: drivers/gpio/gpiolib.c:3136
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_irq_relres
  - drivers/gpio/gpiolib.c:gpiochip_irq_domain_deactivate
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_free_interrupts
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event
```
**Symbols:**

```
ffffffff816187b0-ffffffff81618815: gpiochip_unlock_as_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void gpiochip_unlock_as_irq(struct gpio_chip *gc, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81687a50)
Location: drivers/gpio/gpiolib.c:3195
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_irq_relres
  - drivers/gpio/gpiolib.c:gpiochip_irq_domain_deactivate
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_free_interrupts
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event
```
**Symbols:**

```
ffffffff81687a50-ffffffff81687ab5: gpiochip_unlock_as_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void gpiochip_unlock_as_irq(struct gpio_chip *gc, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff817a3940)
Location: drivers/gpio/gpiolib.c:3316
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_irq_relres
  - drivers/gpio/gpiolib.c:gpiochip_irq_domain_deactivate
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_free_interrupts
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event
```
**Symbols:**

```
ffffffff817a3940-ffffffff817a39bd: gpiochip_unlock_as_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void gpiochip_unlock_as_irq(struct gpio_chip *gc, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff818bb1c0)
Location: drivers/gpio/gpiolib.c:3386
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_irq_relres
  - drivers/gpio/gpiolib.c:gpiochip_irq_domain_deactivate
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_free_interrupts
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event
```
**Symbols:**

```
ffffffff818bb1c0-ffffffff818bb23d: gpiochip_unlock_as_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void gpiochip_unlock_as_irq(struct gpio_chip *gc, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff818fe2c0)
Location: drivers/gpio/gpiolib.c:3427
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_irq_relres
  - drivers/gpio/gpiolib.c:gpiochip_irq_domain_deactivate
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_free_interrupts
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event
```
**Symbols:**

```
ffffffff818fe2c0-ffffffff818fe33d: gpiochip_unlock_as_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void gpiochip_unlock_as_irq(struct gpio_chip *gc, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff819458f0)
Location: drivers/gpio/gpiolib.c:3620
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_irq_relres
  - drivers/gpio/gpiolib.c:gpiochip_irq_domain_deactivate
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_free_interrupts
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event
```
**Symbols:**

```
ffffffff819458f0-ffffffff81945973: gpiochip_unlock_as_irq (STB_GLOBAL)
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
void gpiochip_unlock_as_irq(struct gpio_chip *chip, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffff8000106c0140)
Location: drivers/gpio/gpiolib.c:3927
Inline: False
Direct callers:
  - drivers/pinctrl/qcom/pinctrl-msm.c:msm_gpio_irq_relres
  - drivers/pinctrl/sunxi/pinctrl-sunxi.c:sunxi_pinctrl_irq_release_resources
  - drivers/pinctrl/mediatek/mtk-eint.c:mtk_eint_irq_release_resources
  - drivers/gpio/gpiolib.c:gpiochip_irq_relres
  - drivers/gpio/gpiolib.c:gpiochip_irq_domain_deactivate
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_free_irq
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_free_interrupts
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event
```
**Symbols:**

```
ffff8000106c0140-ffff8000106c01fc: gpiochip_unlock_as_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void gpiochip_unlock_as_irq(struct gpio_chip *chip, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (c085db88)
Location: drivers/gpio/gpiolib.c:3927
Inline: False
Direct callers:
  - drivers/pinctrl/qcom/pinctrl-msm.c:msm_gpio_irq_relres
  - drivers/pinctrl/samsung/pinctrl-exynos.c:exynos_irq_release_resources
  - drivers/pinctrl/mediatek/mtk-eint.c:mtk_eint_irq_release_resources
  - drivers/gpio/gpiolib.c:gpiochip_irq_relres
  - drivers/gpio/gpiolib.c:gpiochip_irq_domain_deactivate
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_free_irq
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq
  - drivers/gpio/gpio-tegra.c:tegra_gpio_irq_shutdown
```
**Symbols:**

```
c085db88-c085dc04: gpiochip_unlock_as_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void gpiochip_unlock_as_irq(struct gpio_chip *chip, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (c00000000083a710)
Location: drivers/gpio/gpiolib.c:3927
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_irq_relres
  - drivers/gpio/gpiolib.c:gpiochip_irq_domain_deactivate
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_free_irq
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq
```
**Symbols:**

```
c00000000083a710-c00000000083a8fc: gpiochip_unlock_as_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void gpiochip_unlock_as_irq(struct gpio_chip *chip, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffe0004a4d82)
Location: drivers/gpio/gpiolib.c:3927
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_irq_relres
  - drivers/gpio/gpiolib.c:gpiochip_irq_domain_deactivate
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_free_irq
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq
```
**Symbols:**

```
ffffffe0004a4d82-ffffffe0004a4df6: gpiochip_unlock_as_irq (STB_GLOBAL)
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
void gpiochip_unlock_as_irq(struct gpio_chip *chip, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8155ff30)
Location: drivers/gpio/gpiolib.c:3927
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_irq_relres
  - drivers/gpio/gpiolib.c:gpiochip_irq_domain_deactivate
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_free_irq
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_free_interrupts
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event
```
**Symbols:**

```
ffffffff8155ff30-ffffffff8155ff91: gpiochip_unlock_as_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void gpiochip_unlock_as_irq(struct gpio_chip *chip, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81550d80)
Location: drivers/gpio/gpiolib.c:3927
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_irq_relres
  - drivers/gpio/gpiolib.c:gpiochip_irq_domain_deactivate
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_free_irq
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_free_interrupts
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event
```
**Symbols:**

```
ffffffff81550d80-ffffffff81550de1: gpiochip_unlock_as_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void gpiochip_unlock_as_irq(struct gpio_chip *chip, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8155eaa0)
Location: drivers/gpio/gpiolib.c:3927
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_irq_relres
  - drivers/gpio/gpiolib.c:gpiochip_irq_domain_deactivate
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_free_irq
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_free_interrupts
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event
```
**Symbols:**

```
ffffffff8155eaa0-ffffffff8155eb01: gpiochip_unlock_as_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void gpiochip_unlock_as_irq(struct gpio_chip *chip, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81578930)
Location: drivers/gpio/gpiolib.c:3927
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_irq_relres
  - drivers/gpio/gpiolib.c:gpiochip_irq_domain_deactivate
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_free_irq
  - drivers/gpio/gpiolib-sysfs.c:gpio_sysfs_request_irq
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_free_interrupts
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event
```
**Symbols:**

```
ffffffff81578930-ffffffff81578991: gpiochip_unlock_as_irq (STB_GLOBAL)
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
