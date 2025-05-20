# Function: <code>gpiochip_set_chained_irqchip</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void gpiochip_set_chained_irqchip(struct gpio_chip *gpiochip, struct irq_chip *irqchip, int parent_irq, irq_flow_handler_t parent_handler);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81425090)
Location: drivers/gpio/gpiolib.c:494
Inline: True
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_probe
  - drivers/gpio/gpio-intel-mid.c:intel_gpio_probe
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_probe
  - drivers/gpio/gpio-zx.c:zx_gpio_probe
```
**Symbols:**

```
ffffffff81425090-ffffffff81425129: gpiochip_set_chained_irqchip (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void gpiochip_set_chained_irqchip(struct gpio_chip *gpiochip, struct irq_chip *irqchip, int parent_irq, irq_flow_handler_t parent_handler);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8146ef80)
Location: drivers/gpio/gpiolib.c:1414
Inline: True
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_probe
  - drivers/gpio/gpio-zx.c:zx_gpio_probe
```
**Symbols:**

```
ffffffff8146ef80-ffffffff8146f02e: gpiochip_set_chained_irqchip (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void gpiochip_set_chained_irqchip(struct gpio_chip *gpiochip, struct irq_chip *irqchip, int parent_irq, irq_flow_handler_t parent_handler);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81490fc0)
Location: drivers/gpio/gpiolib.c:1574
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_probe
```
**Symbols:**

```
ffffffff81490fc0-ffffffff81491048: gpiochip_set_chained_irqchip (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void gpiochip_set_chained_irqchip(struct gpio_chip *gpiochip, struct irq_chip *irqchip, unsigned int parent_irq, irq_flow_handler_t parent_handler);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8149aa80)
Location: drivers/gpio/gpiolib.c:1562
Inline: False
Direct callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_probe
```
**Symbols:**

```
ffffffff8149aa80-ffffffff8149ab0b: gpiochip_set_chained_irqchip (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void gpiochip_set_chained_irqchip(struct gpio_chip *gpiochip, struct irq_chip *irqchip, unsigned int parent_irq, irq_flow_handler_t parent_handler);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff814d8f00)
Location: drivers/gpio/gpiolib.c:1594
Inline: True
Direct callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_probe
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_probe
```
**Symbols:**

```
ffffffff814d8f00-ffffffff814d8fdb: gpiochip_set_chained_irqchip (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void gpiochip_set_chained_irqchip(struct gpio_chip *gpiochip, struct irq_chip *irqchip, unsigned int parent_irq, irq_flow_handler_t parent_handler);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81508110)
Location: drivers/gpio/gpiolib.c:1701
Inline: True
Direct callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_probe
```
**Symbols:**

```
ffffffff81508110-ffffffff8150814a: gpiochip_set_chained_irqchip (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void gpiochip_set_chained_irqchip(struct gpio_chip *gpiochip, struct irq_chip *irqchip, unsigned int parent_irq, irq_flow_handler_t parent_handler);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8151ca00)
Location: drivers/gpio/gpiolib.c:1688
Inline: True
Direct callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_probe
```
**Symbols:**

```
ffffffff8151ca00-ffffffff8151cabd: gpiochip_set_chained_irqchip (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
void gpiochip_set_chained_irqchip(struct gpio_chip *gpiochip, struct irq_chip *irqchip, unsigned int parent_irq, irq_flow_handler_t parent_handler);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8154ef2f)
Location: drivers/gpio/gpiolib.c:1715
Inline: True
Direct callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_probe
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_probe
```
**Symbols:**

```
ffffffff8154ef2f-ffffffff8154ef93: gpiochip_set_chained_irqchip.cold (STB_LOCAL)
ffffffff8154ace0-ffffffff8154ad77: gpiochip_set_chained_irqchip (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
void gpiochip_set_chained_irqchip(struct gpio_chip *gpiochip, struct irq_chip *irqchip, unsigned int parent_irq, irq_flow_handler_t parent_handler);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff815704d7)
Location: drivers/gpio/gpiolib.c:1738
Inline: True
Direct callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
```
**Symbols:**

```
ffffffff815704d7-ffffffff8157053b: gpiochip_set_chained_irqchip.cold (STB_LOCAL)
ffffffff8156bf70-ffffffff8156c007: gpiochip_set_chained_irqchip (STB_GLOBAL)
```
</details>
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
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void gpiochip_set_chained_irqchip(struct gpio_chip *gpiochip, struct irq_chip *irqchip, unsigned int parent_irq, irq_flow_handler_t parent_handler);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffff8000106bf2f0)
Location: drivers/gpio/gpiolib.c:1738
Inline: True
Direct callers:
  - drivers/pinctrl/pinctrl-ocelot.c:ocelot_pinctrl_probe
  - drivers/pinctrl/mvebu/pinctrl-armada-37xx.c:armada_37xx_pinctrl_probe
```
**Symbols:**

```
ffff8000106bf2f0-ffff8000106bf3e0: gpiochip_set_chained_irqchip (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void gpiochip_set_chained_irqchip(struct gpio_chip *gpiochip, struct irq_chip *irqchip, unsigned int parent_irq, irq_flow_handler_t parent_handler);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (c085fa8c)
Location: drivers/gpio/gpiolib.c:1738
Inline: True
Direct callers:
  - drivers/pinctrl/pinctrl-ocelot.c:ocelot_pinctrl_probe
  - drivers/pinctrl/nuvoton/pinctrl-npcm7xx.c:npcm7xx_pinctrl_probe
```
**Symbols:**

```
c085fa8c-c085fb7c: gpiochip_set_chained_irqchip (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void gpiochip_set_chained_irqchip(struct gpio_chip *gpiochip, struct irq_chip *irqchip, unsigned int parent_irq, irq_flow_handler_t parent_handler);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (c00000000083ccb0)
Location: drivers/gpio/gpiolib.c:1738
Inline: True
Direct callers:
  - drivers/pinctrl/pinctrl-ocelot.c:ocelot_pinctrl_probe
```
**Symbols:**

```
c00000000083ccb0-c00000000083ce3c: gpiochip_set_chained_irqchip (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void gpiochip_set_chained_irqchip(struct gpio_chip *gpiochip, struct irq_chip *irqchip, unsigned int parent_irq, irq_flow_handler_t parent_handler);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffe0004a68aa)
Location: drivers/gpio/gpiolib.c:1738
Inline: True
Direct callers:
  - drivers/pinctrl/pinctrl-ocelot.c:ocelot_pinctrl_probe
```
**Symbols:**

```
ffffffe0004a68aa-ffffffe0004a697c: gpiochip_set_chained_irqchip (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
void gpiochip_set_chained_irqchip(struct gpio_chip *gpiochip, struct irq_chip *irqchip, unsigned int parent_irq, irq_flow_handler_t parent_handler);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81565c97)
Location: drivers/gpio/gpiolib.c:1738
Inline: True
Direct callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
```
**Symbols:**

```
ffffffff81565c97-ffffffff81565cfb: gpiochip_set_chained_irqchip.cold (STB_LOCAL)
ffffffff81561730-ffffffff815617c7: gpiochip_set_chained_irqchip (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
void gpiochip_set_chained_irqchip(struct gpio_chip *gpiochip, struct irq_chip *irqchip, unsigned int parent_irq, irq_flow_handler_t parent_handler);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81556ae7)
Location: drivers/gpio/gpiolib.c:1738
Inline: True
Direct callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
```
**Symbols:**

```
ffffffff81556ae7-ffffffff81556b4b: gpiochip_set_chained_irqchip.cold (STB_LOCAL)
ffffffff81552580-ffffffff81552617: gpiochip_set_chained_irqchip (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
void gpiochip_set_chained_irqchip(struct gpio_chip *gpiochip, struct irq_chip *irqchip, unsigned int parent_irq, irq_flow_handler_t parent_handler);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81564807)
Location: drivers/gpio/gpiolib.c:1738
Inline: True
Direct callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
```
**Symbols:**

```
ffffffff81564807-ffffffff8156486b: gpiochip_set_chained_irqchip.cold (STB_LOCAL)
ffffffff815602a0-ffffffff81560337: gpiochip_set_chained_irqchip (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
void gpiochip_set_chained_irqchip(struct gpio_chip *gpiochip, struct irq_chip *irqchip, unsigned int parent_irq, irq_flow_handler_t parent_handler);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8157e727)
Location: drivers/gpio/gpiolib.c:1738
Inline: True
Direct callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
```
**Symbols:**

```
ffffffff8157e727-ffffffff8157e78b: gpiochip_set_chained_irqchip.cold (STB_LOCAL)
ffffffff8157a110-ffffffff8157a1a7: gpiochip_set_chained_irqchip (STB_GLOBAL)
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
