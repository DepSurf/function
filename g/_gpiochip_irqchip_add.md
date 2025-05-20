# Function: <code>_gpiochip_irqchip_add</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int _gpiochip_irqchip_add(struct gpio_chip *gpiochip, struct irq_chip *irqchip, unsigned int first_irq, irq_flow_handler_t handler, unsigned int type, struct lock_class_key *lock_key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81424750)
Location: drivers/gpio/gpiolib.c:672
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_gpio_probe
  - drivers/gpio/gpio-intel-mid.c:intel_gpio_probe
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_probe
  - drivers/gpio/gpio-sx150x.c:sx150x_probe
  - drivers/gpio/gpio-zx.c:zx_gpio_probe
```
**Symbols:**

```
ffffffff81424750-ffffffff81424876: _gpiochip_irqchip_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int _gpiochip_irqchip_add(struct gpio_chip *gpiochip, struct irq_chip *irqchip, unsigned int first_irq, irq_flow_handler_t handler, unsigned int type, struct lock_class_key *lock_key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8146e420)
Location: drivers/gpio/gpiolib.c:1592
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-amd.c:amd_gpio_probe
  - drivers/pinctrl/intel/pinctrl-baytrail.c:byt_pinctrl_probe
  - drivers/gpio/gpio-lynxpoint.c:lp_gpio_probe
  - drivers/gpio/gpio-sx150x.c:sx150x_probe
  - drivers/gpio/gpio-zx.c:zx_gpio_probe
```
**Symbols:**

```
ffffffff8146e420-ffffffff8146e546: _gpiochip_irqchip_add (STB_GLOBAL)
```
</details>
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
In <code>5.4</code>: Absent ⚠️
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
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
</ul>
