# Function: <code>gpiochip_set_nested_irqchip</code>

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
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void gpiochip_set_nested_irqchip(struct gpio_chip *gpiochip, struct irq_chip *irqchip, int parent_irq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81491350)
Location: drivers/gpio/gpiolib.c:1591
Inline: True
Direct callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
```
**Symbols:**

```
ffffffff81491350-ffffffff814913b2: gpiochip_set_nested_irqchip (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void gpiochip_set_nested_irqchip(struct gpio_chip *gpiochip, struct irq_chip *irqchip, unsigned int parent_irq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8149adf0)
Location: drivers/gpio/gpiolib.c:1579
Inline: True
Direct callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
```
**Symbols:**

```
ffffffff8149adf0-ffffffff8149ae52: gpiochip_set_nested_irqchip (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void gpiochip_set_nested_irqchip(struct gpio_chip *gpiochip, struct irq_chip *irqchip, unsigned int parent_irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff814d9360)
Location: drivers/gpio/gpiolib.c:1616
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
```
**Symbols:**

```
ffffffff814d9360-ffffffff814d939d: gpiochip_set_nested_irqchip (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void gpiochip_set_nested_irqchip(struct gpio_chip *gpiochip, struct irq_chip *irqchip, unsigned int parent_irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff815080f0)
Location: drivers/gpio/gpiolib.c:1723
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
```
**Symbols:**

```
ffffffff815080f0-ffffffff81508104: gpiochip_set_nested_irqchip (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void gpiochip_set_nested_irqchip(struct gpio_chip *gpiochip, struct irq_chip *irqchip, unsigned int parent_irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8151d070)
Location: drivers/gpio/gpiolib.c:1709
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
```
**Symbols:**

```
ffffffff8151d070-ffffffff8151d0a7: gpiochip_set_nested_irqchip (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void gpiochip_set_nested_irqchip(struct gpio_chip *gpiochip, struct irq_chip *irqchip, unsigned int parent_irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:1736
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
```
**Symbols:**

```
ffffffff8154efa7-ffffffff8154efcd: gpiochip_set_nested_irqchip.cold (STB_LOCAL)
ffffffff8154b180-ffffffff8154b199: gpiochip_set_nested_irqchip (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void gpiochip_set_nested_irqchip(struct gpio_chip *gpiochip, struct irq_chip *irqchip, unsigned int parent_irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:1759
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
```
**Symbols:**

```
ffffffff8157054f-ffffffff81570575: gpiochip_set_nested_irqchip.cold (STB_LOCAL)
ffffffff8156c360-ffffffff8156c379: gpiochip_set_nested_irqchip (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void gpiochip_set_nested_irqchip(struct gpio_chip *gc, struct irq_chip *irqchip, unsigned int parent_irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:2065
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_probe
```
**Symbols:**

```
ffffffff816142c2-ffffffff816142e8: gpiochip_set_nested_irqchip.cold (STB_LOCAL)
ffffffff8160dca0-ffffffff8160dcb9: gpiochip_set_nested_irqchip (STB_GLOBAL)
```
</details>
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
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void gpiochip_set_nested_irqchip(struct gpio_chip *gpiochip, struct irq_chip *irqchip, unsigned int parent_irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffff8000106bf688)
Location: drivers/gpio/gpiolib.c:1759
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
  - drivers/gpio/gpio-stmpe.c:stmpe_gpio_probe
  - drivers/gpio/gpio-tc3589x.c:tc3589x_gpio_probe
```
**Symbols:**

```
ffff8000106bf688-ffff8000106bf6d8: gpiochip_set_nested_irqchip (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void gpiochip_set_nested_irqchip(struct gpio_chip *gpiochip, struct irq_chip *irqchip, unsigned int parent_irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (c085fd64)
Location: drivers/gpio/gpiolib.c:1759
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
  - drivers/gpio/gpio-stmpe.c:stmpe_gpio_probe
  - drivers/gpio/gpio-tc3589x.c:tc3589x_gpio_probe
```
**Symbols:**

```
c085fd64-c085fda8: gpiochip_set_nested_irqchip (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void gpiochip_set_nested_irqchip(struct gpio_chip *gpiochip, struct irq_chip *irqchip, unsigned int parent_irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (c00000000083d2f0)
Location: drivers/gpio/gpiolib.c:1759
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
  - drivers/gpio/gpio-stmpe.c:stmpe_gpio_probe
  - drivers/gpio/gpio-tc3589x.c:tc3589x_gpio_probe
```
**Symbols:**

```
c00000000083d2f0-c00000000083d34c: gpiochip_set_nested_irqchip (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void gpiochip_set_nested_irqchip(struct gpio_chip *gpiochip, struct irq_chip *irqchip, unsigned int parent_irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffe0004a6b80)
Location: drivers/gpio/gpiolib.c:1759
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
  - drivers/gpio/gpio-stmpe.c:stmpe_gpio_probe
  - drivers/gpio/gpio-tc3589x.c:tc3589x_gpio_probe
```
**Symbols:**

```
ffffffe0004a6b80-ffffffe0004a6bc6: gpiochip_set_nested_irqchip (STB_GLOBAL)
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
void gpiochip_set_nested_irqchip(struct gpio_chip *gpiochip, struct irq_chip *irqchip, unsigned int parent_irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:1759
Inline: False
```
**Symbols:**

```
ffffffff81565d0f-ffffffff81565d35: gpiochip_set_nested_irqchip.cold (STB_LOCAL)
ffffffff81561b20-ffffffff81561b39: gpiochip_set_nested_irqchip (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void gpiochip_set_nested_irqchip(struct gpio_chip *gpiochip, struct irq_chip *irqchip, unsigned int parent_irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:1759
Inline: False
```
**Symbols:**

```
ffffffff81556b5f-ffffffff81556b85: gpiochip_set_nested_irqchip.cold (STB_LOCAL)
ffffffff81552970-ffffffff81552989: gpiochip_set_nested_irqchip (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void gpiochip_set_nested_irqchip(struct gpio_chip *gpiochip, struct irq_chip *irqchip, unsigned int parent_irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:1759
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
```
**Symbols:**

```
ffffffff8156487f-ffffffff815648a5: gpiochip_set_nested_irqchip.cold (STB_LOCAL)
ffffffff81560690-ffffffff815606a9: gpiochip_set_nested_irqchip (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void gpiochip_set_nested_irqchip(struct gpio_chip *gpiochip, struct irq_chip *irqchip, unsigned int parent_irq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:1759
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
```
**Symbols:**

```
ffffffff8157e79f-ffffffff8157e7c5: gpiochip_set_nested_irqchip.cold (STB_LOCAL)
ffffffff8157a500-ffffffff8157a519: gpiochip_set_nested_irqchip (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>int parent_irq</code> ➡️ <code>unsigned int parent_irq</code>
</li>
</ul>
</details>
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
<code>struct gpio_chip *gpiochip</code>
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
