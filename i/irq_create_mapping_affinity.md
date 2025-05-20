# Function: <code>irq_create_mapping_affinity</code>

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
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
unsigned int irq_create_mapping_affinity(struct irq_domain *domain, irq_hw_number_t hwirq, const struct irq_affinity_desc *affinity);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff81126720)
Location: kernel/irq/irqdomain.c:657
Inline: False
Direct callers:
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - drivers/gpio/gpiolib.c:gpiochip_to_irq
  - drivers/base/regmap/regmap-irq.c:regmap_irq_get_virq
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_init
  - drivers/mfd/mfd-core.c:mfd_add_device
  - drivers/mfd/tps6586x.c:tps6586x_irq_get_virq
  - drivers/i2c/i2c-core-base.c:i2c_device_probe
```
**Symbols:**

```
ffffffff81126720-ffffffff8112688f: irq_create_mapping_affinity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
unsigned int irq_create_mapping_affinity(struct irq_domain *domain, irq_hw_number_t hwirq, const struct irq_affinity_desc *affinity);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff81126740)
Location: kernel/irq/irqdomain.c:659
Inline: False
Direct callers:
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - drivers/gpio/gpiolib.c:gpiochip_to_irq
  - drivers/base/regmap/regmap-irq.c:regmap_irq_get_virq
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/arizona-irq.c:arizona_irq_init
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_init
  - drivers/mfd/mfd-core.c:mfd_add_device
  - drivers/mfd/tps6586x.c:tps6586x_irq_get_virq
  - drivers/i2c/i2c-core-base.c:i2c_device_probe
```
**Symbols:**

```
ffffffff81126740-ffffffff811268af: irq_create_mapping_affinity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
unsigned int irq_create_mapping_affinity(struct irq_domain *domain, irq_hw_number_t hwirq, const struct irq_affinity_desc *affinity);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff81146b20)
Location: kernel/irq/irqdomain.c:682
Inline: False
Direct callers:
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - drivers/gpio/gpiolib.c:gpiochip_to_irq
  - drivers/base/regmap/regmap-irq.c:regmap_irq_get_virq
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_init
  - drivers/mfd/mfd-core.c:mfd_add_device
  - drivers/mfd/tps6586x.c:tps6586x_irq_get_virq
  - drivers/i2c/i2c-core-base.c:i2c_device_probe
```
**Symbols:**

```
ffffffff81146b20-ffffffff81146ca8: irq_create_mapping_affinity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
unsigned int irq_create_mapping_affinity(struct irq_domain *domain, irq_hw_number_t hwirq, const struct irq_affinity_desc *affinity);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff8116aee0)
Location: kernel/irq/irqdomain.c:682
Inline: False
Direct callers:
  - kernel/irq/irqdomain.c:irq_create_fwspec_mapping
  - drivers/gpio/gpiolib.c:gpiochip_to_irq
  - drivers/base/regmap/regmap-irq.c:regmap_irq_get_virq
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_init
  - drivers/mfd/mfd-core.c:mfd_add_device
  - drivers/mfd/tps6586x.c:tps6586x_irq_get_virq
  - drivers/i2c/i2c-core-base.c:i2c_device_probe
```
**Symbols:**

```
ffffffff8116aee0-ffffffff8116b093: irq_create_mapping_affinity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
unsigned int irq_create_mapping_affinity(struct irq_domain *domain, irq_hw_number_t hwirq, const struct irq_affinity_desc *affinity);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff8119fab0)
Location: kernel/irq/irqdomain.c:748
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_to_irq
  - drivers/base/regmap/regmap-irq.c:regmap_irq_get_virq
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_init
  - drivers/mfd/mfd-core.c:mfd_add_device
  - drivers/mfd/tps6586x.c:tps6586x_irq_get_virq
  - drivers/i2c/i2c-core-base.c:i2c_device_probe
```
**Symbols:**

```
ffffffff8119fab0-ffffffff8119fba8: irq_create_mapping_affinity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
unsigned int irq_create_mapping_affinity(struct irq_domain *domain, irq_hw_number_t hwirq, const struct irq_affinity_desc *affinity);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff811b1610)
Location: kernel/irq/irqdomain.c:729
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_to_irq
  - drivers/base/regmap/regmap-irq.c:regmap_irq_get_virq
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_init
  - drivers/mfd/mfd-core.c:mfd_add_device
  - drivers/mfd/tps6586x.c:tps6586x_irq_get_virq
  - drivers/i2c/i2c-core-base.c:i2c_device_probe
```
**Symbols:**

```
ffffffff811b1610-ffffffff811b170a: irq_create_mapping_affinity (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
unsigned int irq_create_mapping_affinity(struct irq_domain *domain, irq_hw_number_t hwirq, const struct irq_affinity_desc *affinity);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff811c13c0)
Location: kernel/irq/irqdomain.c:729
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_to_irq
  - drivers/base/regmap/regmap-irq.c:regmap_irq_get_virq
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_init
  - drivers/mfd/mfd-core.c:mfd_add_device
  - drivers/mfd/tps6586x.c:tps6586x_irq_get_virq
  - drivers/i2c/i2c-core-base.c:i2c_device_probe
```
**Symbols:**

```
ffffffff811c13c0-ffffffff811c14ba: irq_create_mapping_affinity (STB_GLOBAL)
```
</details>
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
