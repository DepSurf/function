# Function: <code>irq_domain_add_simple</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct irq_domain *irq_domain_add_simple(struct device_node *of_node, unsigned int size, unsigned int first_irq, const struct irq_domain_ops *ops, void *host_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff810e0c40)
Location: kernel/irq/irqdomain.c:186
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:_gpiochip_irqchip_add
  - drivers/mfd/max8998-irq.c:max8998_irq_init
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
```
**Symbols:**

```
ffffffff810e0c40-ffffffff810e0ccd: irq_domain_add_simple (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct irq_domain *irq_domain_add_simple(struct device_node *of_node, unsigned int size, unsigned int first_irq, const struct irq_domain_ops *ops, void *host_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff810e6510)
Location: kernel/irq/irqdomain.c:179
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:_gpiochip_irqchip_add
  - drivers/mfd/max8998-irq.c:max8998_irq_init
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
```
**Symbols:**

```
ffffffff810e6510-ffffffff810e659f: irq_domain_add_simple (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct irq_domain *irq_domain_add_simple(struct device_node *of_node, unsigned int size, unsigned int first_irq, const struct irq_domain_ops *ops, void *host_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff810ecf00)
Location: kernel/irq/irqdomain.c:177
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_irqchip_add_key
  - drivers/mfd/max8998-irq.c:max8998_irq_init
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
```
**Symbols:**

```
ffffffff810ecf00-ffffffff810ecf8f: irq_domain_add_simple (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct irq_domain *irq_domain_add_simple(struct device_node *of_node, unsigned int size, unsigned int first_irq, const struct irq_domain_ops *ops, void *host_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff810ec8a0)
Location: kernel/irq/irqdomain.c:313
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_irqchip_add_key
  - drivers/mfd/max8998-irq.c:max8998_irq_init
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
```
**Symbols:**

```
ffffffff810ec8a0-ffffffff810ec92f: irq_domain_add_simple (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct irq_domain *irq_domain_add_simple(struct device_node *of_node, unsigned int size, unsigned int first_irq, const struct irq_domain_ops *ops, void *host_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff810f5110)
Location: kernel/irq/irqdomain.c:314
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_irqchip_add_key
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/mfd/max8998-irq.c:max8998_irq_init
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
```
**Symbols:**

```
ffffffff810f5110-ffffffff810f519f: irq_domain_add_simple (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
struct irq_domain *irq_domain_add_simple(struct device_node *of_node, unsigned int size, unsigned int first_irq, const struct irq_domain_ops *ops, void *host_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/irq/irqdomain.c (0)
Location: kernel/irq/irqdomain.c:316
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_irqchip_add_key
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/mfd/max8998-irq.c:max8998_irq_init
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
```
**Symbols:**

```
ffffffff810fe4f8-ffffffff810fe50c: irq_domain_add_simple.cold.28 (STB_LOCAL)
ffffffff810fd4e0-ffffffff810fd562: irq_domain_add_simple (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
struct irq_domain *irq_domain_add_simple(struct device_node *of_node, unsigned int size, unsigned int first_irq, const struct irq_domain_ops *ops, void *host_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/irq/irqdomain.c (0)
Location: kernel/irq/irqdomain.c:316
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_irqchip_add_key
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/mfd/max8998-irq.c:max8998_irq_init
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
```
**Symbols:**

```
ffffffff81109cc8-ffffffff81109cdc: irq_domain_add_simple.cold.27 (STB_LOCAL)
ffffffff81108f90-ffffffff8110900d: irq_domain_add_simple (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
struct irq_domain *irq_domain_add_simple(struct device_node *of_node, unsigned int size, unsigned int first_irq, const struct irq_domain_ops *ops, void *host_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/irq/irqdomain.c (0)
Location: kernel/irq/irqdomain.c:316
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_irqchip_add_key
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/mfd/max8998-irq.c:max8998_irq_init
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
```
**Symbols:**

```
ffffffff8111338d-ffffffff811133a1: irq_domain_add_simple.cold (STB_LOCAL)
ffffffff81112560-ffffffff811125e3: irq_domain_add_simple (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
struct irq_domain *irq_domain_add_simple(struct device_node *of_node, unsigned int size, unsigned int first_irq, const struct irq_domain_ops *ops, void *host_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/irq/irqdomain.c (0)
Location: kernel/irq/irqdomain.c:318
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_irqchip_add_key
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/mfd/max8998-irq.c:max8998_irq_init
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
```
**Symbols:**

```
ffffffff8111f53b-ffffffff8111f54f: irq_domain_add_simple.cold (STB_LOCAL)
ffffffff8111e7f0-ffffffff8111e873: irq_domain_add_simple (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
struct irq_domain *irq_domain_add_simple(struct device_node *of_node, unsigned int size, unsigned int first_irq, const struct irq_domain_ops *ops, void *host_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/irq/irqdomain.c (0)
Location: kernel/irq/irqdomain.c:303
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_irqchip_add_key
  - drivers/gpio/gpiolib.c:gpiochip_add_irqchip
  - drivers/mfd/max8998-irq.c:max8998_irq_init
  - drivers/mfd/tps6586x.c:tps6586x_irq_init
```
**Symbols:**

```
ffffffff8112ba59-ffffffff8112ba6d: irq_domain_add_simple.cold (STB_LOCAL)
ffffffff8112a4a0-ffffffff8112a523: irq_domain_add_simple (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
struct irq_domain *irq_domain_add_simple(struct device_node *of_node, unsigned int size, unsigned int first_irq, const struct irq_domain_ops *ops, void *host_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/irq/irqdomain.c (0)
Location: kernel/irq/irqdomain.c:313
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_add_irqchip
  - drivers/mfd/max8998-irq.c:max8998_irq_init
  - drivers/mfd/tps6586x.c:tps6586x_irq_init
```
**Symbols:**

```
ffffffff81be1bff-ffffffff81be1c13: irq_domain_add_simple.cold (STB_LOCAL)
ffffffff81125f70-ffffffff81125ff3: irq_domain_add_simple (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mfd/max8998-irq.c (ffffffff817fd505)
Location: include/linux/irqdomain.h:328
Inline: True
Inline callers:
  - drivers/mfd/max8998-irq.c:max8998_irq_init
```
```
In drivers/mfd/tps6586x.c (ffffffff81c06e09)
Location: include/linux/irqdomain.h:328
Inline: True
Inline callers:
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mfd/max8998-irq.c (ffffffff81887277)
Location: include/linux/irqdomain.h:327
Inline: True
Inline callers:
  - drivers/mfd/max8998-irq.c:max8998_irq_init
```
```
In drivers/mfd/tps6586x.c (ffffffff81d0a407)
Location: include/linux/irqdomain.h:327
Inline: True
Inline callers:
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mfd/max8998-irq.c (ffffffff819d01d9)
Location: include/linux/irqdomain.h:341
Inline: True
Inline callers:
  - drivers/mfd/max8998-irq.c:max8998_irq_init
```
```
In drivers/mfd/tps6586x.c (ffffffff81ed287b)
Location: include/linux/irqdomain.h:341
Inline: True
Inline callers:
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mfd/max8998-irq.c (ffffffff81b49219)
Location: include/linux/irqdomain.h:329
Inline: True
Inline callers:
  - drivers/mfd/max8998-irq.c:max8998_irq_init
```
```
In drivers/mfd/tps6586x.c (ffffffff81b4a60b)
Location: include/linux/irqdomain.h:329
Inline: True
Inline callers:
  - drivers/mfd/tps6586x.c:tps6586x_irq_init
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mfd/max8998-irq.c (ffffffff81b9c669)
Location: include/linux/irqdomain.h:332
Inline: True
Inline callers:
  - drivers/mfd/max8998-irq.c:max8998_irq_init
```
```
In drivers/mfd/tps6586x.c (ffffffff81b9da4b)
Location: include/linux/irqdomain.h:332
Inline: True
Inline callers:
  - drivers/mfd/tps6586x.c:tps6586x_irq_init
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mfd/max8998-irq.c (ffffffff81bf0659)
Location: include/linux/irqdomain.h:332
Inline: True
Inline callers:
  - drivers/mfd/max8998-irq.c:max8998_irq_init
```
```
In drivers/mfd/tps6586x.c (ffffffff81bf1a3b)
Location: include/linux/irqdomain.h:332
Inline: True
Inline callers:
  - drivers/mfd/tps6586x.c:tps6586x_irq_init
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
struct irq_domain *irq_domain_add_simple(struct device_node *of_node, unsigned int size, unsigned int first_irq, const struct irq_domain_ops *ops, void *host_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffff8000101840c8)
Location: kernel/irq/irqdomain.c:318
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-single.c:pcs_probe
  - drivers/gpio/gpiolib.c:gpiochip_irqchip_add_key
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/mfd/stmpe.c:stmpe_probe
  - drivers/mfd/tc3589x.c:tc3589x_probe
  - drivers/mfd/max8998-irq.c:max8998_irq_init
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
```
**Symbols:**

```
ffff8000101840c8-ffff8000101841a8: irq_domain_add_simple (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct irq_domain *irq_domain_add_simple(struct device_node *of_node, unsigned int size, unsigned int first_irq, const struct irq_domain_ops *ops, void *host_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (c03d324c)
Location: kernel/irq/irqdomain.c:318
Inline: False
Direct callers:
  - drivers/irqchip/irq-renesas-intc-irqpin.c:intc_irqpin_probe
  - drivers/irqchip/irq-aspeed-vic.c:avic_of_init
  - drivers/pinctrl/pinctrl-single.c:pcs_probe
  - drivers/gpio/gpiolib.c:gpiochip_irqchip_add_key
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/mfd/stmpe.c:stmpe_probe
  - drivers/mfd/tc3589x.c:tc3589x_probe
  - drivers/mfd/max8998-irq.c:max8998_irq_init
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
```
**Symbols:**

```
c03d324c-c03d3304: irq_domain_add_simple (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct irq_domain *irq_domain_add_simple(struct device_node *of_node, unsigned int size, unsigned int first_irq, const struct irq_domain_ops *ops, void *host_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (c0000000001de6f0)
Location: kernel/irq/irqdomain.c:318
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-single.c:pcs_probe
  - drivers/gpio/gpiolib.c:gpiochip_irqchip_add_key
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/mfd/stmpe.c:stmpe_probe
  - drivers/mfd/tc3589x.c:tc3589x_probe
  - drivers/mfd/max8998-irq.c:max8998_irq_init
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
```
**Symbols:**

```
c0000000001de6f0-c0000000001de820: irq_domain_add_simple (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct irq_domain *irq_domain_add_simple(struct device_node *of_node, unsigned int size, unsigned int first_irq, const struct irq_domain_ops *ops, void *host_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffe00011b190)
Location: kernel/irq/irqdomain.c:318
Inline: False
Direct callers:
  - drivers/pinctrl/pinctrl-single.c:pcs_probe
  - drivers/gpio/gpiolib.c:gpiochip_irqchip_add_key
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/mfd/stmpe.c:stmpe_probe
  - drivers/mfd/tc3589x.c:tc3589x_probe
  - drivers/mfd/max8998-irq.c:max8998_irq_init
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
```
**Symbols:**

```
ffffffe00011b190-ffffffe00011b234: irq_domain_add_simple (STB_GLOBAL)
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
struct irq_domain *irq_domain_add_simple(struct device_node *of_node, unsigned int size, unsigned int first_irq, const struct irq_domain_ops *ops, void *host_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/irq/irqdomain.c (0)
Location: kernel/irq/irqdomain.c:318
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_irqchip_add_key
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
```
**Symbols:**

```
ffffffff81117b1b-ffffffff81117b2f: irq_domain_add_simple.cold (STB_LOCAL)
ffffffff81116dd0-ffffffff81116e53: irq_domain_add_simple (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
struct irq_domain *irq_domain_add_simple(struct device_node *of_node, unsigned int size, unsigned int first_irq, const struct irq_domain_ops *ops, void *host_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/irq/irqdomain.c (0)
Location: kernel/irq/irqdomain.c:318
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_irqchip_add_key
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
```
**Symbols:**

```
ffffffff8110880b-ffffffff8110881f: irq_domain_add_simple.cold (STB_LOCAL)
ffffffff81107ac0-ffffffff81107b43: irq_domain_add_simple (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
struct irq_domain *irq_domain_add_simple(struct device_node *of_node, unsigned int size, unsigned int first_irq, const struct irq_domain_ops *ops, void *host_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/irq/irqdomain.c (0)
Location: kernel/irq/irqdomain.c:318
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_irqchip_add_key
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/mfd/max8998-irq.c:max8998_irq_init
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
```
**Symbols:**

```
ffffffff81115a0b-ffffffff81115a1f: irq_domain_add_simple.cold (STB_LOCAL)
ffffffff81114cc0-ffffffff81114d43: irq_domain_add_simple (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
struct irq_domain *irq_domain_add_simple(struct device_node *of_node, unsigned int size, unsigned int first_irq, const struct irq_domain_ops *ops, void *host_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/irq/irqdomain.c (0)
Location: kernel/irq/irqdomain.c:318
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_irqchip_add_key
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/mfd/max8998-irq.c:max8998_irq_init
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
```
**Symbols:**

```
ffffffff8112103b-ffffffff8112104f: irq_domain_add_simple.cold (STB_LOCAL)
ffffffff811202f0-ffffffff81120373: irq_domain_add_simple (STB_GLOBAL)
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
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
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
