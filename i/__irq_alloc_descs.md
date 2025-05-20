# Function: <code>__irq_alloc_descs</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int __irq_alloc_descs(int irq, unsigned int from, unsigned int cnt, int node, struct module *owner);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff81818e10)
Location: kernel/irq/irqdesc.c:430
Inline: False
Direct callers:
  - kernel/irq/irqdomain.c:irq_create_strict_mappings
  - kernel/irq/irqdomain.c:irq_create_direct_mapping
  - kernel/irq/irqdomain.c:irq_domain_add_simple
  - drivers/xen/events/events_base.c:xen_allocate_irqs_dynamic
  - drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip
  - drivers/mfd/88pm860x-core.c:device_8607_init
  - drivers/mfd/wm831x-irq.c:wm831x_irq_init
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
```
**Symbols:**

```
ffffffff81818e10-ffffffff81819006: __irq_alloc_descs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int __irq_alloc_descs(int irq, unsigned int from, unsigned int cnt, int node, struct module *owner, const struct cpumask *affinity);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff81892a60)
Location: kernel/irq/irqdesc.c:491
Inline: False
Direct callers:
  - kernel/irq/irqdomain.c:irq_create_strict_mappings
  - kernel/irq/irqdomain.c:irq_create_direct_mapping
  - kernel/irq/irqdomain.c:irq_domain_add_simple
  - drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq
  - drivers/xen/events/events_base.c:xen_allocate_irqs_dynamic
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip
  - drivers/mfd/88pm860x-core.c:device_8607_init
  - drivers/mfd/wm831x-irq.c:wm831x_irq_init
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
```
**Symbols:**

```
ffffffff81892a60-ffffffff81892d10: __irq_alloc_descs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int __irq_alloc_descs(int irq, unsigned int from, unsigned int cnt, int node, struct module *owner, const struct cpumask *affinity);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff818c7360)
Location: kernel/irq/irqdesc.c:679
Inline: False
Direct callers:
  - kernel/irq/irqdomain.c:irq_create_strict_mappings
  - kernel/irq/irqdomain.c:irq_create_direct_mapping
  - kernel/irq/irqdomain.c:irq_domain_add_simple
  - drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq
  - drivers/xen/events/events_base.c:xen_allocate_irqs_dynamic
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip
  - drivers/mfd/88pm860x-core.c:device_8607_init
  - drivers/mfd/wm831x-irq.c:wm831x_irq_init
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
```
**Symbols:**

```
ffffffff818c7360-ffffffff818c75f4: __irq_alloc_descs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int __irq_alloc_descs(int irq, unsigned int from, unsigned int cnt, int node, struct module *owner, const struct cpumask *affinity);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff818feab0)
Location: kernel/irq/irqdesc.c:696
Inline: False
Direct callers:
  - kernel/irq/devres.c:__devm_irq_alloc_descs
  - kernel/irq/irqdomain.c:irq_create_strict_mappings
  - kernel/irq/irqdomain.c:irq_create_direct_mapping
  - kernel/irq/irqdomain.c:irq_domain_add_simple
  - drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq
  - drivers/xen/events/events_base.c:xen_allocate_irqs_dynamic
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip
  - drivers/mfd/88pm860x-core.c:device_8607_init
  - drivers/mfd/wm831x-irq.c:wm831x_irq_init
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
```
**Symbols:**

```
ffffffff818feab0-ffffffff818fed42: __irq_alloc_descs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int __irq_alloc_descs(int irq, unsigned int from, unsigned int cnt, int node, struct module *owner, const struct cpumask *affinity);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff81988cf0)
Location: kernel/irq/irqdesc.c:689
Inline: False
Direct callers:
  - kernel/irq/devres.c:__devm_irq_alloc_descs
  - kernel/irq/irqdomain.c:irq_create_strict_mappings
  - kernel/irq/irqdomain.c:irq_create_direct_mapping
  - kernel/irq/irqdomain.c:irq_domain_add_simple
  - drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq
  - drivers/xen/events/events_base.c:xen_allocate_irqs_dynamic
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip
  - drivers/mfd/88pm860x-core.c:device_8607_init
  - drivers/mfd/wm831x-irq.c:wm831x_irq_init
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
```
**Symbols:**

```
ffffffff81988cf0-ffffffff81988f24: __irq_alloc_descs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int __irq_alloc_descs(int irq, unsigned int from, unsigned int cnt, int node, struct module *owner, const struct cpumask *affinity);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff819e5630)
Location: kernel/irq/irqdesc.c:706
Inline: False
Direct callers:
  - kernel/irq/devres.c:__devm_irq_alloc_descs
  - kernel/irq/irqdomain.c:irq_create_strict_mappings
  - kernel/irq/irqdomain.c:irq_create_direct_mapping
  - kernel/irq/irqdomain.c:irq_domain_add_simple
  - drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq
  - drivers/xen/events/events_base.c:xen_allocate_irqs_dynamic
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip
  - drivers/mfd/88pm860x-core.c:device_8607_init
  - drivers/mfd/wm831x-irq.c:wm831x_irq_init
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
```
**Symbols:**

```
ffffffff819e5630-ffffffff819e5888: __irq_alloc_descs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int __irq_alloc_descs(int irq, unsigned int from, unsigned int cnt, int node, struct module *owner, const struct irq_affinity_desc *affinity);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff81a20840)
Location: kernel/irq/irqdesc.c:711
Inline: False
Direct callers:
  - kernel/irq/devres.c:__devm_irq_alloc_descs
  - kernel/irq/irqdomain.c:irq_create_strict_mappings
  - kernel/irq/irqdomain.c:irq_create_direct_mapping
  - kernel/irq/irqdomain.c:irq_domain_add_simple
  - drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq
  - drivers/xen/events/events_base.c:xen_allocate_irqs_dynamic
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip
  - drivers/mfd/88pm860x-core.c:device_8607_init
  - drivers/mfd/wm831x-irq.c:wm831x_irq_init
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
```
**Symbols:**

```
ffffffff81a20840-ffffffff81a20a81: __irq_alloc_descs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int __irq_alloc_descs(int irq, unsigned int from, unsigned int cnt, int node, struct module *owner, const struct irq_affinity_desc *affinity);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff81a90d70)
Location: kernel/irq/irqdesc.c:766
Inline: False
Direct callers:
  - kernel/irq/devres.c:__devm_irq_alloc_descs
  - kernel/irq/irqdomain.c:irq_create_strict_mappings
  - kernel/irq/irqdomain.c:irq_create_direct_mapping
  - kernel/irq/irqdomain.c:irq_domain_add_simple
  - drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq
  - drivers/xen/events/events_base.c:xen_allocate_irqs_dynamic
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip
  - drivers/mfd/88pm860x-core.c:device_8607_init
  - drivers/mfd/wm831x-irq.c:wm831x_irq_init
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
```
**Symbols:**

```
ffffffff81a90d70-ffffffff81a90fc4: __irq_alloc_descs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int __irq_alloc_descs(int irq, unsigned int from, unsigned int cnt, int node, struct module *owner, const struct irq_affinity_desc *affinity);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff81ac80b0)
Location: kernel/irq/irqdesc.c:766
Inline: False
Direct callers:
  - kernel/irq/devres.c:__devm_irq_alloc_descs
  - kernel/irq/irqdomain.c:irq_create_strict_mappings
  - kernel/irq/irqdomain.c:irq_create_direct_mapping
  - kernel/irq/irqdomain.c:irq_domain_add_simple
  - drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq
  - drivers/xen/events/events_base.c:xen_allocate_irqs_dynamic
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip
  - drivers/mfd/88pm860x-core.c:device_8607_init
  - drivers/mfd/wm831x-irq.c:wm831x_irq_init
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
```
**Symbols:**

```
ffffffff81ac80b0-ffffffff81ac8304: __irq_alloc_descs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __irq_alloc_descs(int irq, unsigned int from, unsigned int cnt, int node, struct module *owner, const struct irq_affinity_desc *affinity);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff81bc0be0)
Location: kernel/irq/irqdesc.c:772
Inline: False
Direct callers:
  - kernel/irq/devres.c:__devm_irq_alloc_descs
  - kernel/irq/irqdomain.c:__irq_domain_alloc_irqs
  - kernel/irq/irqdomain.c:irq_create_strict_mappings
  - kernel/irq/irqdomain.c:irq_create_direct_mapping
  - kernel/irq/irqdomain.c:irq_domain_add_simple
  - drivers/xen/events/events_base.c:bind_virq_to_irq
  - drivers/xen/events/events_base.c:bind_ipi_to_irq
  - drivers/xen/events/events_base.c:bind_evtchn_to_irq
  - drivers/xen/events/events_base.c:xen_bind_pirq_msi_to_irq
  - drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq
  - drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip_np
  - drivers/mfd/88pm860x-core.c:device_irq_init
  - drivers/mfd/wm831x-irq.c:wm831x_irq_init
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/tps6586x.c:tps6586x_irq_init
```
**Symbols:**

```
ffffffff81bc0be0-ffffffff81bc0d0c: __irq_alloc_descs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __irq_alloc_descs(int irq, unsigned int from, unsigned int cnt, int node, struct module *owner, const struct irq_affinity_desc *affinity);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff81c39c70)
Location: kernel/irq/irqdesc.c:774
Inline: False
Direct callers:
  - kernel/irq/devres.c:__devm_irq_alloc_descs
  - kernel/irq/irqdomain.c:__irq_domain_alloc_irqs
  - kernel/irq/irqdomain.c:irq_create_strict_mappings
  - kernel/irq/irqdomain.c:irq_create_direct_mapping
  - kernel/irq/irqdomain.c:irq_domain_add_simple
  - drivers/xen/events/events_base.c:bind_virq_to_irq
  - drivers/xen/events/events_base.c:bind_ipi_to_irq
  - drivers/xen/events/events_base.c:bind_evtchn_to_irq_chip
  - drivers/xen/events/events_base.c:xen_bind_pirq_msi_to_irq
  - drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq
  - drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip_fwnode
  - drivers/mfd/88pm860x-core.c:device_irq_init
  - drivers/mfd/wm831x-irq.c:wm831x_irq_init
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/tps6586x.c:tps6586x_irq_init
```
**Symbols:**

```
ffffffff81c39c70-ffffffff81c39d9c: __irq_alloc_descs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __irq_alloc_descs(int irq, unsigned int from, unsigned int cnt, int node, struct module *owner, const struct irq_affinity_desc *affinity);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff81c2c240)
Location: kernel/irq/irqdesc.c:774
Inline: False
Direct callers:
  - kernel/irq/devres.c:__devm_irq_alloc_descs
  - kernel/irq/irqdomain.c:__irq_domain_alloc_irqs
  - kernel/irq/irqdomain.c:irq_create_direct_mapping
  - kernel/irq/irqdomain.c:irq_domain_create_simple
  - drivers/xen/events/events_base.c:bind_ipi_to_irqhandler
  - drivers/xen/events/events_base.c:bind_virq_to_irq
  - drivers/xen/events/events_base.c:bind_evtchn_to_irq_chip
  - drivers/xen/events/events_base.c:xen_bind_pirq_msi_to_irq
  - drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq
  - drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip_fwnode
  - drivers/mfd/88pm860x-core.c:device_irq_init
  - drivers/mfd/wm831x-irq.c:wm831x_irq_init
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
```
**Symbols:**

```
ffffffff81c2c240-ffffffff81c2c368: __irq_alloc_descs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __irq_alloc_descs(int irq, unsigned int from, unsigned int cnt, int node, struct module *owner, const struct irq_affinity_desc *affinity);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff81d4a930)
Location: kernel/irq/irqdesc.c:786
Inline: False
Direct callers:
  - kernel/irq/devres.c:__devm_irq_alloc_descs
  - kernel/irq/irqdomain.c:__irq_domain_alloc_irqs
  - kernel/irq/irqdomain.c:irq_domain_create_simple
  - drivers/xen/events/events_base.c:bind_ipi_to_irqhandler
  - drivers/xen/events/events_base.c:bind_virq_to_irq
  - drivers/xen/events/events_base.c:bind_evtchn_to_irq_chip
  - drivers/xen/events/events_base.c:xen_bind_pirq_msi_to_irq
  - drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq
  - drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip_fwnode
  - drivers/mfd/88pm860x-core.c:device_irq_init
  - drivers/mfd/wm831x-irq.c:wm831x_irq_init
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
```
**Symbols:**

```
ffffffff81d4a930-ffffffff81d4aa58: __irq_alloc_descs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __irq_alloc_descs(int irq, unsigned int from, unsigned int cnt, int node, struct module *owner, const struct irq_affinity_desc *affinity);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff81f19fd0)
Location: kernel/irq/irqdesc.c:763
Inline: False
Direct callers:
  - kernel/irq/devres.c:__devm_irq_alloc_descs
  - kernel/irq/irqdomain.c:__irq_domain_alloc_irqs
  - kernel/irq/irqdomain.c:irq_domain_create_simple
  - drivers/xen/events/events_base.c:bind_ipi_to_irqhandler
  - drivers/xen/events/events_base.c:bind_virq_to_irq
  - drivers/xen/events/events_base.c:bind_evtchn_to_irq_chip
  - drivers/xen/events/events_base.c:xen_bind_pirq_msi_to_irq
  - drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq
  - drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip_fwnode
  - drivers/mfd/88pm860x-core.c:device_irq_init
  - drivers/mfd/wm831x-irq.c:wm831x_irq_init
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
```
**Symbols:**

```
ffffffff81f19fd0-ffffffff81f1a0f9: __irq_alloc_descs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __irq_alloc_descs(int irq, unsigned int from, unsigned int cnt, int node, struct module *owner, const struct irq_affinity_desc *affinity);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff820c1c00)
Location: kernel/irq/irqdesc.c:790
Inline: False
Direct callers:
  - kernel/irq/devres.c:__devm_irq_alloc_descs
  - kernel/irq/irqdomain.c:irq_domain_alloc_irqs_locked
  - kernel/irq/irqdomain.c:irq_domain_create_simple
  - drivers/xen/events/events_base.c:bind_ipi_to_irqhandler
  - drivers/xen/events/events_base.c:bind_virq_to_irq
  - drivers/xen/events/events_base.c:bind_evtchn_to_irq_chip
  - drivers/xen/events/events_base.c:xen_bind_pirq_msi_to_irq
  - drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq
  - drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip_fwnode
  - drivers/mfd/88pm860x-core.c:device_irq_init
  - drivers/mfd/wm831x-irq.c:wm831x_irq_init
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/tps6586x.c:tps6586x_irq_init
```
**Symbols:**

```
ffffffff820c1c00-ffffffff820c1d29: __irq_alloc_descs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __irq_alloc_descs(int irq, unsigned int from, unsigned int cnt, int node, struct module *owner, const struct irq_affinity_desc *affinity);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff821458d0)
Location: kernel/irq/irqdesc.c:810
Inline: False
Direct callers:
  - kernel/irq/devres.c:__devm_irq_alloc_descs
  - kernel/irq/irqdomain.c:irq_domain_alloc_irqs_locked
  - kernel/irq/irqdomain.c:irq_domain_create_simple
  - drivers/xen/events/events_base.c:bind_ipi_to_irqhandler
  - drivers/xen/events/events_base.c:bind_virq_to_irq
  - drivers/xen/events/events_base.c:bind_evtchn_to_irq_chip
  - drivers/xen/events/events_base.c:xen_bind_pirq_msi_to_irq
  - drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq
  - drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip_fwnode
  - drivers/mfd/88pm860x-core.c:device_irq_init
  - drivers/mfd/wm831x-irq.c:wm831x_irq_init
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/tps6586x.c:tps6586x_irq_init
```
**Symbols:**

```
ffffffff821458d0-ffffffff82145a70: __irq_alloc_descs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __irq_alloc_descs(int irq, unsigned int from, unsigned int cnt, int node, struct module *owner, const struct irq_affinity_desc *affinity);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff82227ff0)
Location: kernel/irq/irqdesc.c:810
Inline: False
Direct callers:
  - kernel/irq/devres.c:__devm_irq_alloc_descs
  - kernel/irq/irqdomain.c:irq_domain_alloc_irqs_locked
  - kernel/irq/irqdomain.c:irq_domain_create_simple
  - drivers/xen/events/events_base.c:xen_bind_pirq_msi_to_irq
  - drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq
  - drivers/xen/events/events_base.c:xen_allocate_irq_dynamic
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip_fwnode
  - drivers/mfd/88pm860x-core.c:device_irq_init
  - drivers/mfd/wm831x-irq.c:wm831x_irq_init
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/tps6586x.c:tps6586x_irq_init
```
**Symbols:**

```
ffffffff82227ff0-ffffffff8222818e: __irq_alloc_descs (STB_GLOBAL)
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
int __irq_alloc_descs(int irq, unsigned int from, unsigned int cnt, int node, struct module *owner, const struct irq_affinity_desc *affinity);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffff800010d9bf08)
Location: kernel/irq/irqdesc.c:766
Inline: False
Direct callers:
  - kernel/irq/devres.c:__devm_irq_alloc_descs
  - kernel/irq/irqdomain.c:irq_create_strict_mappings
  - kernel/irq/irqdomain.c:irq_create_direct_mapping
  - kernel/irq/irqdomain.c:irq_domain_add_simple
  - drivers/irqchip/irq-gic.c:gic_init_bases
  - drivers/dma/ipu/ipu_irq.c:ipu_irq_attach_irq
  - drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq
  - drivers/xen/events/events_base.c:xen_allocate_irqs_dynamic
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip
  - drivers/mfd/88pm860x-core.c:device_8607_init
  - drivers/mfd/wm831x-irq.c:wm831x_irq_init
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
```
**Symbols:**

```
ffff800010d9bf08-ffff800010d9c1a4: __irq_alloc_descs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __irq_alloc_descs(int irq, unsigned int from, unsigned int cnt, int node, struct module *owner, const struct irq_affinity_desc *affinity);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (c0e985a8)
Location: kernel/irq/irqdesc.c:766
Inline: False
Direct callers:
  - arch/arm/mach-imx/tzic.c:tzic_init_dt
  - arch/arm/mach-omap2/prm_common.c:omap_prcm_register_chain_handler
  - kernel/irq/devres.c:__devm_irq_alloc_descs
  - kernel/irq/irqdomain.c:irq_create_strict_mappings
  - kernel/irq/irqdomain.c:irq_create_direct_mapping
  - kernel/irq/irqdomain.c:irq_domain_add_simple
  - drivers/irqchip/irq-hip04.c:hip04_of_init
  - drivers/irqchip/irq-omap-intc.c:omap_init_irq_legacy
  - drivers/irqchip/irq-gic.c:gic_init_bases
  - drivers/dma/ipu/ipu_irq.c:ipu_irq_attach_irq
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip
  - drivers/mfd/88pm860x-core.c:device_8607_init
  - drivers/mfd/wm831x-irq.c:wm831x_irq_init
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
```
**Symbols:**

```
c0e985a8-c0e987d4: __irq_alloc_descs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __irq_alloc_descs(int irq, unsigned int from, unsigned int cnt, int node, struct module *owner, const struct irq_affinity_desc *affinity);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (c0000000001d1e30)
Location: kernel/irq/irqdesc.c:766
Inline: False
Direct callers:
  - kernel/irq/devres.c:__devm_irq_alloc_descs
  - kernel/irq/irqdomain.c:irq_create_strict_mappings
  - kernel/irq/irqdomain.c:irq_create_direct_mapping
  - kernel/irq/irqdomain.c:irq_domain_add_simple
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip
  - drivers/mfd/88pm860x-core.c:device_8607_init
  - drivers/mfd/wm831x-irq.c:wm831x_irq_init
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
```
**Symbols:**

```
c0000000001d1e30-c0000000001d21f0: __irq_alloc_descs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int __irq_alloc_descs(int irq, unsigned int from, unsigned int cnt, int node, struct module *owner, const struct irq_affinity_desc *affinity);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffe0008c419c)
Location: kernel/irq/irqdesc.c:766
Inline: False
Direct callers:
  - kernel/irq/devres.c:__devm_irq_alloc_descs
  - kernel/irq/irqdomain.c:irq_create_strict_mappings
  - kernel/irq/irqdomain.c:irq_create_direct_mapping
  - kernel/irq/irqdomain.c:irq_domain_add_simple
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip
  - drivers/mfd/88pm860x-core.c:device_8607_init
  - drivers/mfd/wm831x-irq.c:wm831x_irq_init
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
```
**Symbols:**

```
ffffffe0008c419c-ffffffe0008c437e: __irq_alloc_descs (STB_GLOBAL)
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
int __irq_alloc_descs(int irq, unsigned int from, unsigned int cnt, int node, struct module *owner, const struct irq_affinity_desc *affinity);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff81a66f20)
Location: kernel/irq/irqdesc.c:766
Inline: False
Direct callers:
  - kernel/irq/devres.c:__devm_irq_alloc_descs
  - kernel/irq/irqdomain.c:irq_create_strict_mappings
  - kernel/irq/irqdomain.c:irq_create_direct_mapping
  - kernel/irq/irqdomain.c:irq_domain_add_simple
  - drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq
  - drivers/xen/events/events_base.c:xen_allocate_irqs_dynamic
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip
  - drivers/mfd/wm831x-irq.c:wm831x_irq_init
```
**Symbols:**

```
ffffffff81a66f20-ffffffff81a67174: __irq_alloc_descs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int __irq_alloc_descs(int irq, unsigned int from, unsigned int cnt, int node, struct module *owner, const struct irq_affinity_desc *affinity);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff81a239e0)
Location: kernel/irq/irqdesc.c:766
Inline: False
Direct callers:
  - kernel/irq/devres.c:__devm_irq_alloc_descs
  - kernel/irq/irqdomain.c:irq_create_strict_mappings
  - kernel/irq/irqdomain.c:irq_create_direct_mapping
  - kernel/irq/irqdomain.c:irq_domain_add_simple
  - kernel/irq/irq_sim.c:irq_sim_init
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip
  - drivers/mfd/wm831x-irq.c:wm831x_irq_init
```
**Symbols:**

```
ffffffff81a239e0-ffffffff81a23c34: __irq_alloc_descs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int __irq_alloc_descs(int irq, unsigned int from, unsigned int cnt, int node, struct module *owner, const struct irq_affinity_desc *affinity);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff81ad3330)
Location: kernel/irq/irqdesc.c:766
Inline: False
Direct callers:
  - kernel/irq/devres.c:__devm_irq_alloc_descs
  - kernel/irq/irqdomain.c:irq_create_strict_mappings
  - kernel/irq/irqdomain.c:irq_create_direct_mapping
  - kernel/irq/irqdomain.c:irq_domain_add_simple
  - drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq
  - drivers/xen/events/events_base.c:xen_allocate_irqs_dynamic
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip
  - drivers/mfd/88pm860x-core.c:device_8607_init
  - drivers/mfd/wm831x-irq.c:wm831x_irq_init
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
```
**Symbols:**

```
ffffffff81ad3330-ffffffff81ad3584: __irq_alloc_descs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int __irq_alloc_descs(int irq, unsigned int from, unsigned int cnt, int node, struct module *owner, const struct irq_affinity_desc *affinity);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdesc.c (ffffffff81adf830)
Location: kernel/irq/irqdesc.c:766
Inline: False
Direct callers:
  - kernel/irq/devres.c:__devm_irq_alloc_descs
  - kernel/irq/irqdomain.c:irq_create_strict_mappings
  - kernel/irq/irqdomain.c:irq_create_direct_mapping
  - kernel/irq/irqdomain.c:irq_domain_add_simple
  - drivers/xen/events/events_base.c:xen_bind_pirq_gsi_to_irq
  - drivers/xen/events/events_base.c:xen_allocate_irqs_dynamic
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip
  - drivers/mfd/88pm860x-core.c:device_8607_init
  - drivers/mfd/wm831x-irq.c:wm831x_irq_init
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
  - drivers/mfd/wm8350-irq.c:wm8350_irq_init
  - drivers/mfd/twl4030-irq.c:twl4030_init_irq
  - drivers/mfd/max8925-core.c:max8925_device_init
  - drivers/mfd/tps6586x.c:tps6586x_i2c_probe
```
**Symbols:**

```
ffffffff81adf830-ffffffff81adfa84: __irq_alloc_descs (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>const struct cpumask *affinity</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>const struct cpumask *affinity</code> ➡️ <code>const struct irq_affinity_desc *affinity</code>
</li>
</ul>
</details>
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
