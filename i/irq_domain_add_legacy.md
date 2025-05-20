# Function: <code>irq_domain_add_legacy</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct irq_domain *irq_domain_add_legacy(struct device_node *of_node, unsigned int size, unsigned int first_irq, irq_hw_number_t first_hwirq, const struct irq_domain_ops *ops, void *host_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff810e0cd0)
Location: kernel/irq/irqdomain.c:229
Inline: False
Direct callers:
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip
  - drivers/mfd/88pm860x-core.c:device_8607_init
  - drivers/mfd/wm831x-irq.c:wm831x_irq_init
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/max8925-core.c:max8925_device_init
```
**Symbols:**

```
ffffffff810e0cd0-ffffffff810e0d2a: irq_domain_add_legacy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct irq_domain *irq_domain_add_legacy(struct device_node *of_node, unsigned int size, unsigned int first_irq, irq_hw_number_t first_hwirq, const struct irq_domain_ops *ops, void *host_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff810e65a0)
Location: kernel/irq/irqdomain.c:222
Inline: False
Direct callers:
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip
  - drivers/mfd/88pm860x-core.c:device_8607_init
  - drivers/mfd/wm831x-irq.c:wm831x_irq_init
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/max8925-core.c:max8925_device_init
```
**Symbols:**

```
ffffffff810e65a0-ffffffff810e65fa: irq_domain_add_legacy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct irq_domain *irq_domain_add_legacy(struct device_node *of_node, unsigned int size, unsigned int first_irq, irq_hw_number_t first_hwirq, const struct irq_domain_ops *ops, void *host_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff810ecf90)
Location: kernel/irq/irqdomain.c:220
Inline: False
Direct callers:
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip
  - drivers/mfd/88pm860x-core.c:device_8607_init
  - drivers/mfd/wm831x-irq.c:wm831x_irq_init
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/max8925-core.c:max8925_device_init
```
**Symbols:**

```
ffffffff810ecf90-ffffffff810ecfea: irq_domain_add_legacy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct irq_domain *irq_domain_add_legacy(struct device_node *of_node, unsigned int size, unsigned int first_irq, irq_hw_number_t first_hwirq, const struct irq_domain_ops *ops, void *host_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff810ec930)
Location: kernel/irq/irqdomain.c:356
Inline: False
Direct callers:
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip
  - drivers/mfd/88pm860x-core.c:device_8607_init
  - drivers/mfd/wm831x-irq.c:wm831x_irq_init
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/max8925-core.c:max8925_device_init
```
**Symbols:**

```
ffffffff810ec930-ffffffff810ec990: irq_domain_add_legacy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct irq_domain *irq_domain_add_legacy(struct device_node *of_node, unsigned int size, unsigned int first_irq, irq_hw_number_t first_hwirq, const struct irq_domain_ops *ops, void *host_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff810f51a0)
Location: kernel/irq/irqdomain.c:357
Inline: False
Direct callers:
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip
  - drivers/mfd/88pm860x-core.c:device_8607_init
  - drivers/mfd/wm831x-irq.c:wm831x_irq_init
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/max8925-core.c:max8925_device_init
```
**Symbols:**

```
ffffffff810f51a0-ffffffff810f5200: irq_domain_add_legacy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct irq_domain *irq_domain_add_legacy(struct device_node *of_node, unsigned int size, unsigned int first_irq, irq_hw_number_t first_hwirq, const struct irq_domain_ops *ops, void *host_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff810fd570)
Location: kernel/irq/irqdomain.c:359
Inline: False
Direct callers:
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip
  - drivers/mfd/88pm860x-core.c:device_8607_init
  - drivers/mfd/wm831x-irq.c:wm831x_irq_init
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/max8925-core.c:max8925_device_init
```
**Symbols:**

```
ffffffff810fd570-ffffffff810fd5ca: irq_domain_add_legacy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct irq_domain *irq_domain_add_legacy(struct device_node *of_node, unsigned int size, unsigned int first_irq, irq_hw_number_t first_hwirq, const struct irq_domain_ops *ops, void *host_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff81109010)
Location: kernel/irq/irqdomain.c:359
Inline: False
Direct callers:
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip
  - drivers/mfd/88pm860x-core.c:device_8607_init
  - drivers/mfd/wm831x-irq.c:wm831x_irq_init
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/max8925-core.c:max8925_device_init
```
**Symbols:**

```
ffffffff81109010-ffffffff81109067: irq_domain_add_legacy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct irq_domain *irq_domain_add_legacy(struct device_node *of_node, unsigned int size, unsigned int first_irq, irq_hw_number_t first_hwirq, const struct irq_domain_ops *ops, void *host_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff811125f0)
Location: kernel/irq/irqdomain.c:359
Inline: False
Direct callers:
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip
  - drivers/mfd/88pm860x-core.c:device_8607_init
  - drivers/mfd/wm831x-irq.c:wm831x_irq_init
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/max8925-core.c:max8925_device_init
```
**Symbols:**

```
ffffffff811125f0-ffffffff81112649: irq_domain_add_legacy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct irq_domain *irq_domain_add_legacy(struct device_node *of_node, unsigned int size, unsigned int first_irq, irq_hw_number_t first_hwirq, const struct irq_domain_ops *ops, void *host_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff8111e880)
Location: kernel/irq/irqdomain.c:361
Inline: False
Direct callers:
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip
  - drivers/mfd/88pm860x-core.c:device_8607_init
  - drivers/mfd/wm831x-irq.c:wm831x_irq_init
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/max8925-core.c:max8925_device_init
```
**Symbols:**

```
ffffffff8111e880-ffffffff8111e8d9: irq_domain_add_legacy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct irq_domain *irq_domain_add_legacy(struct device_node *of_node, unsigned int size, unsigned int first_irq, irq_hw_number_t first_hwirq, const struct irq_domain_ops *ops, void *host_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff8112a530)
Location: kernel/irq/irqdomain.c:346
Inline: False
Direct callers:
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip_np
  - drivers/mfd/88pm860x-core.c:device_irq_init
  - drivers/mfd/wm831x-irq.c:wm831x_irq_init
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
```
**Symbols:**

```
ffffffff8112a530-ffffffff8112a589: irq_domain_add_legacy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct irq_domain *irq_domain_add_legacy(struct device_node *of_node, unsigned int size, unsigned int first_irq, irq_hw_number_t first_hwirq, const struct irq_domain_ops *ops, void *host_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff81126180)
Location: kernel/irq/irqdomain.c:356
Inline: False
Direct callers:
  - drivers/mfd/88pm860x-core.c:device_irq_init
  - drivers/mfd/wm831x-irq.c:wm831x_irq_init
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
```
**Symbols:**

```
ffffffff81126180-ffffffff811261d9: irq_domain_add_legacy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct irq_domain *irq_domain_add_legacy(struct device_node *of_node, unsigned int size, unsigned int first_irq, irq_hw_number_t first_hwirq, const struct irq_domain_ops *ops, void *host_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff81126210)
Location: kernel/irq/irqdomain.c:358
Inline: False
Direct callers:
  - drivers/mfd/88pm860x-core.c:device_irq_init
  - drivers/mfd/wm831x-irq.c:wm831x_irq_init
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
```
**Symbols:**

```
ffffffff81126210-ffffffff81126269: irq_domain_add_legacy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct irq_domain *irq_domain_add_legacy(struct device_node *of_node, unsigned int size, unsigned int first_irq, irq_hw_number_t first_hwirq, const struct irq_domain_ops *ops, void *host_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff81146ac0)
Location: kernel/irq/irqdomain.c:368
Inline: False
Direct callers:
  - drivers/mfd/88pm860x-core.c:device_irq_init
  - drivers/mfd/wm831x-irq.c:wm831x_irq_init
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
```
**Symbols:**

```
ffffffff81146ac0-ffffffff81146b19: irq_domain_add_legacy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct irq_domain *irq_domain_add_legacy(struct device_node *of_node, unsigned int size, unsigned int first_irq, irq_hw_number_t first_hwirq, const struct irq_domain_ops *ops, void *host_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff8116ae70)
Location: kernel/irq/irqdomain.c:368
Inline: False
Direct callers:
  - drivers/mfd/88pm860x-core.c:device_irq_init
  - drivers/mfd/wm831x-irq.c:wm831x_irq_init
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
```
**Symbols:**

```
ffffffff8116ae70-ffffffff8116aed9: irq_domain_add_legacy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct irq_domain *irq_domain_add_legacy(struct device_node *of_node, unsigned int size, unsigned int first_irq, irq_hw_number_t first_hwirq, const struct irq_domain_ops *ops, void *host_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff8119fdc0)
Location: kernel/irq/irqdomain.c:392
Inline: False
Direct callers:
  - drivers/mfd/88pm860x-core.c:device_irq_init
  - drivers/mfd/wm831x-irq.c:wm831x_irq_init
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
```
**Symbols:**

```
ffffffff8119fdc0-ffffffff8119fe31: irq_domain_add_legacy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct irq_domain *irq_domain_add_legacy(struct device_node *of_node, unsigned int size, unsigned int first_irq, irq_hw_number_t first_hwirq, const struct irq_domain_ops *ops, void *host_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff811b1ad0)
Location: kernel/irq/irqdomain.c:399
Inline: False
Direct callers:
  - drivers/mfd/88pm860x-core.c:device_irq_init
  - drivers/mfd/wm831x-irq.c:wm831x_irq_init
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
```
**Symbols:**

```
ffffffff811b1ad0-ffffffff811b1b41: irq_domain_add_legacy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct irq_domain *irq_domain_add_legacy(struct device_node *of_node, unsigned int size, unsigned int first_irq, irq_hw_number_t first_hwirq, const struct irq_domain_ops *ops, void *host_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff811c1880)
Location: kernel/irq/irqdomain.c:399
Inline: False
Direct callers:
  - drivers/mfd/88pm860x-core.c:device_irq_init
  - drivers/mfd/wm831x-irq.c:wm831x_irq_init
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
```
**Symbols:**

```
ffffffff811c1880-ffffffff811c18f1: irq_domain_add_legacy (STB_GLOBAL)
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
struct irq_domain *irq_domain_add_legacy(struct device_node *of_node, unsigned int size, unsigned int first_irq, irq_hw_number_t first_hwirq, const struct irq_domain_ops *ops, void *host_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffff8000101841a8)
Location: kernel/irq/irqdomain.c:361
Inline: False
Direct callers:
  - drivers/irqchip/irq-gic.c:gic_init_bases
  - drivers/gpio/gpio-davinci.c:davinci_gpio_irq_setup
  - drivers/gpio/gpio-mxc.c:mxc_gpio_probe
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip
  - drivers/mfd/88pm860x-core.c:device_8607_init
  - drivers/mfd/wm831x-irq.c:wm831x_irq_init
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/max8925-core.c:max8925_device_init
```
**Symbols:**

```
ffff8000101841a8-ffff800010184230: irq_domain_add_legacy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct irq_domain *irq_domain_add_legacy(struct device_node *of_node, unsigned int size, unsigned int first_irq, irq_hw_number_t first_hwirq, const struct irq_domain_ops *ops, void *host_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (c03d3304)
Location: kernel/irq/irqdomain.c:361
Inline: False
Direct callers:
  - arch/arm/mach-imx/tzic.c:tzic_init_dt
  - drivers/irqchip/irq-hip04.c:hip04_of_init
  - drivers/irqchip/irq-omap-intc.c:omap_init_irq_legacy
  - drivers/irqchip/irq-gic.c:gic_init_bases
  - drivers/gpio/gpio-mxc.c:mxc_gpio_probe
  - drivers/gpio/gpio-twl4030.c:gpio_twl4030_probe
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip
  - drivers/mfd/88pm860x-core.c:device_8607_init
  - drivers/mfd/wm831x-irq.c:wm831x_irq_init
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/max8925-core.c:max8925_device_init
```
**Symbols:**

```
c03d3304-c03d3374: irq_domain_add_legacy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct irq_domain *irq_domain_add_legacy(struct device_node *of_node, unsigned int size, unsigned int first_irq, irq_hw_number_t first_hwirq, const struct irq_domain_ops *ops, void *host_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (c0000000001de820)
Location: kernel/irq/irqdomain.c:361
Inline: False
Direct callers:
  - arch/powerpc/sysdev/i8259.c:i8259_init
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip
  - drivers/mfd/88pm860x-core.c:device_8607_init
  - drivers/mfd/wm831x-irq.c:wm831x_irq_init
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/max8925-core.c:max8925_device_init
```
**Symbols:**

```
c0000000001de820-c0000000001de8b4: irq_domain_add_legacy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct irq_domain *irq_domain_add_legacy(struct device_node *of_node, unsigned int size, unsigned int first_irq, irq_hw_number_t first_hwirq, const struct irq_domain_ops *ops, void *host_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffe00011b234)
Location: kernel/irq/irqdomain.c:361
Inline: False
Direct callers:
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip
  - drivers/mfd/88pm860x-core.c:device_8607_init
  - drivers/mfd/wm831x-irq.c:wm831x_irq_init
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/max8925-core.c:max8925_device_init
```
**Symbols:**

```
ffffffe00011b234-ffffffe00011b2a6: irq_domain_add_legacy (STB_GLOBAL)
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
struct irq_domain *irq_domain_add_legacy(struct device_node *of_node, unsigned int size, unsigned int first_irq, irq_hw_number_t first_hwirq, const struct irq_domain_ops *ops, void *host_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff81116e60)
Location: kernel/irq/irqdomain.c:361
Inline: False
Direct callers:
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip
  - drivers/mfd/wm831x-irq.c:wm831x_irq_init
```
**Symbols:**

```
ffffffff81116e60-ffffffff81116eb9: irq_domain_add_legacy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct irq_domain *irq_domain_add_legacy(struct device_node *of_node, unsigned int size, unsigned int first_irq, irq_hw_number_t first_hwirq, const struct irq_domain_ops *ops, void *host_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff81107b50)
Location: kernel/irq/irqdomain.c:361
Inline: False
Direct callers:
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip
  - drivers/mfd/wm831x-irq.c:wm831x_irq_init
```
**Symbols:**

```
ffffffff81107b50-ffffffff81107ba9: irq_domain_add_legacy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct irq_domain *irq_domain_add_legacy(struct device_node *of_node, unsigned int size, unsigned int first_irq, irq_hw_number_t first_hwirq, const struct irq_domain_ops *ops, void *host_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff81114d50)
Location: kernel/irq/irqdomain.c:361
Inline: False
Direct callers:
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip
  - drivers/mfd/88pm860x-core.c:device_8607_init
  - drivers/mfd/wm831x-irq.c:wm831x_irq_init
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/max8925-core.c:max8925_device_init
```
**Symbols:**

```
ffffffff81114d50-ffffffff81114da9: irq_domain_add_legacy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct irq_domain *irq_domain_add_legacy(struct device_node *of_node, unsigned int size, unsigned int first_irq, irq_hw_number_t first_hwirq, const struct irq_domain_ops *ops, void *host_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff81120380)
Location: kernel/irq/irqdomain.c:361
Inline: False
Direct callers:
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip
  - drivers/mfd/88pm860x-core.c:device_8607_init
  - drivers/mfd/wm831x-irq.c:wm831x_irq_init
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/max8925-core.c:max8925_device_init
```
**Symbols:**

```
ffffffff81120380-ffffffff811203d9: irq_domain_add_legacy (STB_GLOBAL)
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
