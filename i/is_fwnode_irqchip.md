# Function: <code>is_fwnode_irqchip</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff810e0086)
Location: include/linux/irqdomain.h:214
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_free_fwnode
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff810e5a46)
Location: include/linux/irqdomain.h:229
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_free_fwnode
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff810ec3b6)
Location: include/linux/irqdomain.h:236
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_free_fwnode
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff810ec687)
Location: include/linux/irqdomain.h:268
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:__irq_domain_add
  - kernel/irq/irqdomain.c:irq_domain_free_fwnode
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff810f4ed2)
Location: include/linux/irqdomain.h:277
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:__irq_domain_add
  - kernel/irq/irqdomain.c:irq_domain_free_fwnode
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff810fd2b2)
Location: include/linux/irqdomain.h:277
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:__irq_domain_add
  - kernel/irq/irqdomain.c:irq_domain_free_fwnode
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff81108d52)
Location: include/linux/irqdomain.h:279
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:__irq_domain_add
  - kernel/irq/irqdomain.c:irq_domain_free_fwnode
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff81112332)
Location: include/linux/irqdomain.h:281
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:__irq_domain_add
  - kernel/irq/irqdomain.c:irq_domain_free_fwnode
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff8111e5c2)
Location: include/linux/irqdomain.h:288
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:__irq_domain_add
  - kernel/irq/irqdomain.c:irq_domain_free_fwnode
```
```
In drivers/gpio/gpiolib.c (ffffffff8156fb3a)
Location: include/linux/irqdomain.h:288
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff81129d04)
Location: include/linux/irqdomain.h:289
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:__irq_domain_add
  - kernel/irq/irqdomain.c:irq_domain_free_fwnode
```
```
In drivers/gpio/gpiolib.c (ffffffff8160dce7)
Location: include/linux/irqdomain.h:289
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/apic/vector.c (ffffffff8106ff70)
Location: include/linux/irqdomain.h:296
Inline: True
```
```
In kernel/irq/irqdomain.c (ffffffff811256bb)
Location: include/linux/irqdomain.h:296
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:__irq_domain_add
  - kernel/irq/irqdomain.c:irq_domain_free_fwnode
```
```
In drivers/gpio/gpiolib.c (ffffffff81634547)
Location: include/linux/irqdomain.h:296
Inline: True
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
In arch/x86/kernel/apic/vector.c (ffffffff81070ac2)
Location: include/linux/irqdomain.h:292
Inline: True
```
```
In kernel/irq/irqdomain.c (ffffffff8112598f)
Location: include/linux/irqdomain.h:292
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:__irq_domain_add
  - kernel/irq/irqdomain.c:irq_domain_free_fwnode
```
```
In drivers/gpio/gpiolib.c (ffffffff81617ffc)
Location: include/linux/irqdomain.h:292
Inline: True
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
In arch/x86/kernel/apic/vector.c (ffffffff8107c742)
Location: include/linux/irqdomain.h:291
Inline: True
```
```
In kernel/irq/irqdomain.c (ffffffff81146131)
Location: include/linux/irqdomain.h:291
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:__irq_domain_add
  - kernel/irq/irqdomain.c:irq_domain_free_fwnode
```
```
In drivers/gpio/gpiolib.c (ffffffff8168727c)
Location: include/linux/irqdomain.h:291
Inline: True
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
In arch/x86/kernel/apic/vector.c (ffffffff8108bb02)
Location: include/linux/irqdomain.h:305
Inline: True
```
```
In kernel/irq/irqdomain.c (ffffffff8116a3d4)
Location: include/linux/irqdomain.h:305
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:__irq_domain_add
  - kernel/irq/irqdomain.c:irq_domain_free_fwnode
```
```
In drivers/gpio/gpiolib.c (ffffffff817a4523)
Location: include/linux/irqdomain.h:305
Inline: True
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
In arch/x86/kernel/apic/vector.c (ffffffff8109ff92)
Location: include/linux/irqdomain.h:293
Inline: True
```
```
In kernel/irq/irqdomain.c (ffffffff8119ef64)
Location: include/linux/irqdomain.h:293
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:__irq_domain_create
  - kernel/irq/irqdomain.c:irq_domain_free_fwnode
```
```
In drivers/gpio/gpiolib.c (ffffffff818bc086)
Location: include/linux/irqdomain.h:293
Inline: True
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
In arch/x86/kernel/apic/vector.c (ffffffff810a2f12)
Location: include/linux/irqdomain.h:296
Inline: True
```
```
In kernel/irq/irqdomain.c (ffffffff811b0e44)
Location: include/linux/irqdomain.h:296
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:__irq_domain_create
  - kernel/irq/irqdomain.c:irq_domain_free_fwnode
```
```
In drivers/gpio/gpiolib.c (ffffffff818fef65)
Location: include/linux/irqdomain.h:296
Inline: True
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
In arch/x86/kernel/apic/vector.c (ffffffff810a9e52)
Location: include/linux/irqdomain.h:296
Inline: True
```
```
In kernel/irq/irqdomain.c (ffffffff811c0bc4)
Location: include/linux/irqdomain.h:296
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:__irq_domain_create
  - kernel/irq/irqdomain.c:irq_domain_free_fwnode
```
```
In drivers/gpio/gpiolib.c (ffffffff81946aec)
Location: include/linux/irqdomain.h:296
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_add_irqchip
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffff800010183d70)
Location: include/linux/irqdomain.h:288
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:__irq_domain_add
  - kernel/irq/irqdomain.c:irq_domain_free_fwnode
```
```
In drivers/irqchip/irq-gic.c (ffff80001066b998)
Location: include/linux/irqdomain.h:288
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic.c:gic_irq_domain_translate
```
```
In drivers/irqchip/irq-gic-v2m.c (ffff80001066d928)
Location: include/linux/irqdomain.h:288
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic-v2m.c:gicv2m_teardown
  - drivers/irqchip/irq-gic-v2m.c:gicv2m_irq_domain_alloc
```
```
In drivers/irqchip/irq-gic-v3.c (ffff80001066dca8)
Location: include/linux/irqdomain.h:288
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic-v3.c:gic_irq_domain_translate
```
```
In drivers/irqchip/irq-gic-v3-its.c (ffff800010670a74)
Location: include/linux/irqdomain.h:288
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic-v3-its.c:its_irq_gic_domain_alloc
```
```
In drivers/gpio/gpiolib.c (ffff8000106be164)
Location: include/linux/irqdomain.h:288
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_hierarchy_irq_domain_translate
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (c03d2fbc)
Location: include/linux/irqdomain.h:288
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:__irq_domain_add
  - kernel/irq/irqdomain.c:irq_domain_free_fwnode
```
```
In drivers/irqchip/irq-gic.c (c0814c4c)
Location: include/linux/irqdomain.h:288
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic.c:gic_irq_domain_translate
```
```
In drivers/irqchip/irq-gic-v2m.c (c154b608)
Location: include/linux/irqdomain.h:288
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic-v2m.c:gicv2m_of_init
  - drivers/irqchip/irq-gic-v2m.c:gicv2m_irq_domain_alloc
```
```
In drivers/irqchip/irq-gic-v3.c (c0816a80)
Location: include/linux/irqdomain.h:288
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic-v3.c:gic_irq_domain_translate
```
```
In drivers/irqchip/irq-gic-v3-its.c (c0819fe4)
Location: include/linux/irqdomain.h:288
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic-v3-its.c:its_irq_gic_domain_alloc
```
```
In drivers/gpio/gpiolib.c (c085dec4)
Location: include/linux/irqdomain.h:288
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_hierarchy_irq_domain_translate
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (c0000000001de3d4)
Location: include/linux/irqdomain.h:288
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:__irq_domain_add
  - kernel/irq/irqdomain.c:irq_domain_free_fwnode
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffe00011af46)
Location: include/linux/irqdomain.h:288
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:__irq_domain_add
  - kernel/irq/irqdomain.c:irq_domain_free_fwnode
```
```
In drivers/gpio/gpiolib.c (ffffffe0004a509a)
Location: include/linux/irqdomain.h:288
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_hierarchy_irq_domain_translate
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff81116ba2)
Location: include/linux/irqdomain.h:288
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:__irq_domain_add
  - kernel/irq/irqdomain.c:irq_domain_free_fwnode
```
```
In drivers/gpio/gpiolib.c (ffffffff815652fa)
Location: include/linux/irqdomain.h:288
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff81107892)
Location: include/linux/irqdomain.h:288
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:__irq_domain_add
  - kernel/irq/irqdomain.c:irq_domain_free_fwnode
```
```
In drivers/gpio/gpiolib.c (ffffffff8155614a)
Location: include/linux/irqdomain.h:288
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff81114a92)
Location: include/linux/irqdomain.h:288
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:__irq_domain_add
  - kernel/irq/irqdomain.c:irq_domain_free_fwnode
```
```
In drivers/gpio/gpiolib.c (ffffffff81563e6a)
Location: include/linux/irqdomain.h:288
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/irq/irqdomain.c (ffffffff811200c2)
Location: include/linux/irqdomain.h:288
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:__irq_domain_add
  - kernel/irq/irqdomain.c:irq_domain_free_fwnode
```
```
In drivers/gpio/gpiolib.c (ffffffff8157dd8a)
Location: include/linux/irqdomain.h:288
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
```
</details>
</li>
</ul>

## Differences
