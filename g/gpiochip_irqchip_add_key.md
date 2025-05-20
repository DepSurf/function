# Function: <code>gpiochip_irqchip_add_key</code>

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
<summary>In <code>4.10</code>: ✅</summary>

```c
int gpiochip_irqchip_add_key(struct gpio_chip *gpiochip, struct irq_chip *irqchip, unsigned int first_irq, irq_flow_handler_t handler, unsigned int type, bool nested, struct lock_class_key *lock_key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81490350)
Location: drivers/gpio/gpiolib.c:1752
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_probe
```
**Symbols:**

```
ffffffff81490350-ffffffff81490578: gpiochip_irqchip_add_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int gpiochip_irqchip_add_key(struct gpio_chip *gpiochip, struct irq_chip *irqchip, unsigned int first_irq, irq_flow_handler_t handler, unsigned int type, bool nested, struct lock_class_key *lock_key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81499a60)
Location: drivers/gpio/gpiolib.c:1740
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_probe
```
**Symbols:**

```
ffffffff81499a60-ffffffff81499c62: gpiochip_irqchip_add_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int gpiochip_irqchip_add_key(struct gpio_chip *gpiochip, struct irq_chip *irqchip, unsigned int first_irq, irq_flow_handler_t handler, unsigned int type, bool threaded, struct lock_class_key *lock_key, struct lock_class_key *request_key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff814d7a00)
Location: drivers/gpio/gpiolib.c:1887
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-intel.c:intel_pinctrl_probe
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_probe
```
**Symbols:**

```
ffffffff814d7a00-ffffffff814d7bd2: gpiochip_irqchip_add_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int gpiochip_irqchip_add_key(struct gpio_chip *gpiochip, struct irq_chip *irqchip, unsigned int first_irq, irq_flow_handler_t handler, unsigned int type, bool threaded, struct lock_class_key *lock_key, struct lock_class_key *request_key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:1994
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_probe
```
**Symbols:**

```
ffffffff8150bda1-ffffffff8150bdb7: gpiochip_irqchip_add_key.cold.45 (STB_LOCAL)
ffffffff81506db0-ffffffff81506f6c: gpiochip_irqchip_add_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int gpiochip_irqchip_add_key(struct gpio_chip *gpiochip, struct irq_chip *irqchip, unsigned int first_irq, irq_flow_handler_t handler, unsigned int type, bool threaded, struct lock_class_key *lock_key, struct lock_class_key *request_key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:2017
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_probe
```
**Symbols:**

```
ffffffff81520c21-ffffffff81520c37: gpiochip_irqchip_add_key.cold.43 (STB_LOCAL)
ffffffff8151b440-ffffffff8151b5d4: gpiochip_irqchip_add_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int gpiochip_irqchip_add_key(struct gpio_chip *gpiochip, struct irq_chip *irqchip, unsigned int first_irq, irq_flow_handler_t handler, unsigned int type, bool threaded, struct lock_class_key *lock_key, struct lock_class_key *request_key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:2081
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_probe
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_gpio_probe
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_probe
```
**Symbols:**

```
ffffffff8154ed98-ffffffff8154edae: gpiochip_irqchip_add_key.cold (STB_LOCAL)
ffffffff81549720-ffffffff815498c5: gpiochip_irqchip_add_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int gpiochip_irqchip_add_key(struct gpio_chip *gpiochip, struct irq_chip *irqchip, unsigned int first_irq, irq_flow_handler_t handler, unsigned int type, bool threaded, struct lock_class_key *lock_key, struct lock_class_key *request_key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:2408
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
```
**Symbols:**

```
ffffffff815704c1-ffffffff815704d7: gpiochip_irqchip_add_key.cold (STB_LOCAL)
ffffffff8156bd10-ffffffff8156beb5: gpiochip_irqchip_add_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int gpiochip_irqchip_add_key(struct gpio_chip *gc, struct irq_chip *irqchip, unsigned int first_irq, irq_flow_handler_t handler, unsigned int type, bool threaded, struct lock_class_key *lock_key, struct lock_class_key *request_key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:2750
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
  - drivers/gpio/gpio-crystalcove.c:crystalcove_gpio_probe
```
**Symbols:**

```
ffffffff816142a0-ffffffff816142c2: gpiochip_irqchip_add_key.cold (STB_LOCAL)
ffffffff8160d3d0-ffffffff8160d575: gpiochip_irqchip_add_key (STB_GLOBAL)
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
int gpiochip_irqchip_add_key(struct gpio_chip *gpiochip, struct irq_chip *irqchip, unsigned int first_irq, irq_flow_handler_t handler, unsigned int type, bool threaded, struct lock_class_key *lock_key, struct lock_class_key *request_key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffff8000106bf038)
Location: drivers/gpio/gpiolib.c:2408
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
  - drivers/pinctrl/pinctrl-ocelot.c:ocelot_pinctrl_probe
  - drivers/pinctrl/mvebu/pinctrl-armada-37xx.c:armada_37xx_pinctrl_probe
  - drivers/gpio/gpio-stmpe.c:stmpe_gpio_probe
  - drivers/gpio/gpio-tc3589x.c:tc3589x_gpio_probe
```
**Symbols:**

```
ffff8000106bf038-ffff8000106bf1d4: gpiochip_irqchip_add_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int gpiochip_irqchip_add_key(struct gpio_chip *gpiochip, struct irq_chip *irqchip, unsigned int first_irq, irq_flow_handler_t handler, unsigned int type, bool threaded, struct lock_class_key *lock_key, struct lock_class_key *request_key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (c085f864)
Location: drivers/gpio/gpiolib.c:2408
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
  - drivers/pinctrl/pinctrl-ocelot.c:ocelot_pinctrl_probe
  - drivers/pinctrl/nuvoton/pinctrl-npcm7xx.c:npcm7xx_pinctrl_probe
  - drivers/gpio/gpio-stmpe.c:stmpe_gpio_probe
  - drivers/gpio/gpio-tc3589x.c:tc3589x_gpio_probe
```
**Symbols:**

```
c085f864-c085f990: gpiochip_irqchip_add_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int gpiochip_irqchip_add_key(struct gpio_chip *gpiochip, struct irq_chip *irqchip, unsigned int first_irq, irq_flow_handler_t handler, unsigned int type, bool threaded, struct lock_class_key *lock_key, struct lock_class_key *request_key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (c00000000083aed0)
Location: drivers/gpio/gpiolib.c:2408
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
  - drivers/pinctrl/pinctrl-ocelot.c:ocelot_pinctrl_probe
  - drivers/gpio/gpio-stmpe.c:stmpe_gpio_probe
  - drivers/gpio/gpio-tc3589x.c:tc3589x_gpio_probe
```
**Symbols:**

```
c00000000083aed0-c00000000083b068: gpiochip_irqchip_add_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int gpiochip_irqchip_add_key(struct gpio_chip *gpiochip, struct irq_chip *irqchip, unsigned int first_irq, irq_flow_handler_t handler, unsigned int type, bool threaded, struct lock_class_key *lock_key, struct lock_class_key *request_key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffe0004a66e2)
Location: drivers/gpio/gpiolib.c:2408
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
  - drivers/pinctrl/pinctrl-ocelot.c:ocelot_pinctrl_probe
  - drivers/gpio/gpio-stmpe.c:stmpe_gpio_probe
  - drivers/gpio/gpio-tc3589x.c:tc3589x_gpio_probe
```
**Symbols:**

```
ffffffe0004a66e2-ffffffe0004a67dc: gpiochip_irqchip_add_key (STB_GLOBAL)
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
int gpiochip_irqchip_add_key(struct gpio_chip *gpiochip, struct irq_chip *irqchip, unsigned int first_irq, irq_flow_handler_t handler, unsigned int type, bool threaded, struct lock_class_key *lock_key, struct lock_class_key *request_key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:2408
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
```
**Symbols:**

```
ffffffff81565c81-ffffffff81565c97: gpiochip_irqchip_add_key.cold (STB_LOCAL)
ffffffff815614d0-ffffffff81561675: gpiochip_irqchip_add_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int gpiochip_irqchip_add_key(struct gpio_chip *gpiochip, struct irq_chip *irqchip, unsigned int first_irq, irq_flow_handler_t handler, unsigned int type, bool threaded, struct lock_class_key *lock_key, struct lock_class_key *request_key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:2408
Inline: False
Direct callers:
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
```
**Symbols:**

```
ffffffff81556ad1-ffffffff81556ae7: gpiochip_irqchip_add_key.cold (STB_LOCAL)
ffffffff81552320-ffffffff815524c5: gpiochip_irqchip_add_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int gpiochip_irqchip_add_key(struct gpio_chip *gpiochip, struct irq_chip *irqchip, unsigned int first_irq, irq_flow_handler_t handler, unsigned int type, bool threaded, struct lock_class_key *lock_key, struct lock_class_key *request_key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:2408
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
```
**Symbols:**

```
ffffffff815647f1-ffffffff81564807: gpiochip_irqchip_add_key.cold (STB_LOCAL)
ffffffff81560040-ffffffff815601e5: gpiochip_irqchip_add_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int gpiochip_irqchip_add_key(struct gpio_chip *gpiochip, struct irq_chip *irqchip, unsigned int first_irq, irq_flow_handler_t handler, unsigned int type, bool threaded, struct lock_class_key *lock_key, struct lock_class_key *request_key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:2408
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
  - drivers/pinctrl/pinctrl-sx150x.c:sx150x_probe
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
  - drivers/pinctrl/intel/pinctrl-cherryview.c:chv_pinctrl_probe
```
**Symbols:**

```
ffffffff8157e711-ffffffff8157e727: gpiochip_irqchip_add_key.cold (STB_LOCAL)
ffffffff81579eb0-ffffffff8157a055: gpiochip_irqchip_add_key (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.13</code> and <code>4.15</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool threaded</code>
</li>
<li>
<b>Param added. </b>
<code>struct lock_class_key *request_key</code>
</li>
<li>
<b>Param removed. </b>
<code>bool nested</code>
</li>
</ul>
</details>
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
