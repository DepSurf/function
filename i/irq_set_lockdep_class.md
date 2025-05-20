# Function: <code>irq_set_lockdep_class</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/irq/generic-chip.c (ffffffff810df421)
Location: include/linux/irqdesc.h:231
Inline: True
Inline callers:
  - kernel/irq/generic-chip.c:irq_map_generic_chip
  - kernel/irq/generic-chip.c:irq_setup_generic_chip
```
```
In drivers/gpio/gpiolib.c (ffffffff8142514e)
Location: include/linux/irqdesc.h:231
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/irq/generic-chip.c (ffffffff810e4ef9)
Location: include/linux/irqdesc.h:238
Inline: True
Inline callers:
  - kernel/irq/generic-chip.c:irq_setup_generic_chip
  - kernel/irq/generic-chip.c:irq_map_generic_chip
```
```
In drivers/gpio/gpiolib.c (ffffffff8146f04e)
Location: include/linux/irqdesc.h:238
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
```
```
In drivers/mfd/arizona-irq.c (ffffffff815d3657)
Location: include/linux/irqdesc.h:238
Inline: True
Inline callers:
  - drivers/mfd/arizona-irq.c:arizona_irq_map
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/irq/generic-chip.c (ffffffff810eb809)
Location: include/linux/irqdesc.h:241
Inline: True
Inline callers:
  - kernel/irq/generic-chip.c:irq_setup_generic_chip
  - kernel/irq/generic-chip.c:irq_map_generic_chip
```
```
In drivers/gpio/gpiolib.c (ffffffff8149106e)
Location: include/linux/irqdesc.h:241
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
```
```
In drivers/mfd/arizona-irq.c (ffffffff816003a7)
Location: include/linux/irqdesc.h:241
Inline: True
Inline callers:
  - drivers/mfd/arizona-irq.c:arizona_irq_map
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/irq/generic-chip.c (ffffffff810eb0b1)
Location: include/linux/irqdesc.h:248
Inline: True
Inline callers:
  - kernel/irq/generic-chip.c:irq_setup_generic_chip
  - kernel/irq/generic-chip.c:irq_map_generic_chip
```
```
In drivers/gpio/gpiolib.c (ffffffff8149ab2e)
Location: include/linux/irqdesc.h:248
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
```
```
In drivers/mfd/arizona-irq.c (ffffffff81614257)
Location: include/linux/irqdesc.h:248
Inline: True
Inline callers:
  - drivers/mfd/arizona-irq.c:arizona_irq_map
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/irq/generic-chip.c (ffffffff810f3611)
Location: include/linux/irqdesc.h:258
Inline: True
Inline callers:
  - kernel/irq/generic-chip.c:irq_setup_generic_chip
  - kernel/irq/generic-chip.c:irq_map_generic_chip
```
```
In drivers/gpio/gpiolib.c (ffffffff814d9039)
Location: include/linux/irqdesc.h:258
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
```
```
In drivers/mfd/arizona-irq.c (ffffffff8167c8f7)
Location: include/linux/irqdesc.h:258
Inline: True
Inline callers:
  - drivers/mfd/arizona-irq.c:arizona_irq_map
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/irq/generic-chip.c (ffffffff810fb8b1)
Location: include/linux/irqdesc.h:253
Inline: True
Inline callers:
  - kernel/irq/generic-chip.c:irq_setup_generic_chip
  - kernel/irq/generic-chip.c:irq_map_generic_chip
```
```
In drivers/gpio/gpiolib.c (ffffffff815081ac)
Location: include/linux/irqdesc.h:253
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
```
```
In drivers/mfd/arizona-irq.c (ffffffff816b8347)
Location: include/linux/irqdesc.h:253
Inline: True
Inline callers:
  - drivers/mfd/arizona-irq.c:arizona_irq_map
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/irq/generic-chip.c (ffffffff81107076)
Location: include/linux/irqdesc.h:253
Inline: True
Inline callers:
  - kernel/irq/generic-chip.c:irq_setup_generic_chip
  - kernel/irq/generic-chip.c:irq_map_generic_chip
```
```
In drivers/gpio/gpiolib.c (ffffffff8151caec)
Location: include/linux/irqdesc.h:253
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
```
```
In drivers/mfd/arizona-irq.c (ffffffff816d9587)
Location: include/linux/irqdesc.h:253
Inline: True
Inline callers:
  - drivers/mfd/arizona-irq.c:arizona_irq_map
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/irq/generic-chip.c (ffffffff81110664)
Location: include/linux/irqdesc.h:260
Inline: True
Inline callers:
  - kernel/irq/generic-chip.c:irq_setup_generic_chip
  - kernel/irq/generic-chip.c:irq_map_generic_chip
```
```
In drivers/gpio/gpiolib.c (ffffffff8154adaf)
Location: include/linux/irqdesc.h:260
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
```
```
In drivers/mfd/arizona-irq.c (ffffffff81714cca)
Location: include/linux/irqdesc.h:260
Inline: True
Inline callers:
  - drivers/mfd/arizona-irq.c:arizona_irq_map
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
In kernel/irq/generic-chip.c (ffffffff8111c8c4)
Location: include/linux/irqdesc.h:260
Inline: True
Inline callers:
  - kernel/irq/generic-chip.c:irq_setup_generic_chip
  - kernel/irq/generic-chip.c:irq_map_generic_chip
```
```
In drivers/gpio/gpiolib.c (ffffffff8156beef)
Location: include/linux/irqdesc.h:260
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
  - drivers/gpio/gpiolib.c:gpiochip_hierarchy_irq_domain_alloc
```
```
In drivers/mfd/arizona-irq.c (ffffffff81738fda)
Location: include/linux/irqdesc.h:260
Inline: True
Inline callers:
  - drivers/mfd/arizona-irq.c:arizona_irq_map
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
In kernel/irq/generic-chip.c (ffffffff811289d4)
Location: include/linux/irqdesc.h:260
Inline: True
Inline callers:
  - kernel/irq/generic-chip.c:irq_setup_generic_chip
  - kernel/irq/generic-chip.c:irq_map_generic_chip
```
```
In drivers/gpio/gpiolib.c (ffffffff816100f3)
Location: include/linux/irqdesc.h:260
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
  - drivers/gpio/gpiolib.c:gpiochip_hierarchy_irq_domain_alloc
```
```
In drivers/mfd/arizona-irq.c (ffffffff817f663a)
Location: include/linux/irqdesc.h:260
Inline: True
Inline callers:
  - drivers/mfd/arizona-irq.c:arizona_irq_map
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
In kernel/irq/generic-chip.c (0)
Location: include/linux/irqdesc.h:252
Inline: True
```
```
In drivers/gpio/gpiolib.c (0)
Location: include/linux/irqdesc.h:252
Inline: True
```
```
In drivers/mfd/arizona-irq.c (0)
Location: include/linux/irqdesc.h:252
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
In kernel/irq/generic-chip.c (0)
Location: include/linux/irqdesc.h:252
Inline: True
```
```
In drivers/gpio/gpiolib.c (0)
Location: include/linux/irqdesc.h:252
Inline: True
```
```
In drivers/mfd/arizona-irq.c (0)
Location: include/linux/irqdesc.h:252
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
In kernel/irq/generic-chip.c (0)
Location: include/linux/irqdesc.h:248
Inline: True
```
```
In drivers/gpio/gpiolib.c (0)
Location: include/linux/irqdesc.h:248
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
In kernel/irq/generic-chip.c (0)
Location: include/linux/irqdesc.h:242
Inline: True
```
```
In drivers/gpio/gpiolib.c (0)
Location: include/linux/irqdesc.h:242
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
In kernel/irq/generic-chip.c (0)
Location: include/linux/irqdesc.h:244
Inline: True
```
```
In drivers/gpio/gpiolib.c (0)
Location: include/linux/irqdesc.h:244
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
In kernel/irq/generic-chip.c (0)
Location: include/linux/irqdesc.h:247
Inline: True
```
```
In drivers/gpio/gpiolib.c (0)
Location: include/linux/irqdesc.h:247
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
In kernel/irq/generic-chip.c (0)
Location: include/linux/irqdesc.h:247
Inline: True
```
```
In drivers/gpio/gpiolib.c (0)
Location: include/linux/irqdesc.h:247
Inline: True
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
In kernel/irq/generic-chip.c (ffff800010181308)
Location: include/linux/irqdesc.h:260
Inline: True
Inline callers:
  - kernel/irq/generic-chip.c:irq_setup_generic_chip
  - kernel/irq/generic-chip.c:irq_map_generic_chip
```
```
In drivers/pinctrl/pinctrl-single.c (ffff80001069c520)
Location: include/linux/irqdesc.h:260
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-single.c:pcs_irqdomain_map
```
```
In drivers/gpio/gpiolib.c (ffff8000106bf220)
Location: include/linux/irqdesc.h:260
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
  - drivers/gpio/gpiolib.c:gpiochip_hierarchy_irq_domain_alloc
```
```
In drivers/mfd/arizona-irq.c (ffff800010933b90)
Location: include/linux/irqdesc.h:260
Inline: True
Inline callers:
  - drivers/mfd/arizona-irq.c:arizona_irq_map
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
In kernel/irq/generic-chip.c (c03d0dec)
Location: include/linux/irqdesc.h:260
Inline: True
Inline callers:
  - kernel/irq/generic-chip.c:irq_setup_generic_chip
  - kernel/irq/generic-chip.c:irq_map_generic_chip
```
```
In drivers/irqchip/irq-renesas-intc-irqpin.c (c081f9cc)
Location: include/linux/irqdesc.h:260
Inline: True
Inline callers:
  - drivers/irqchip/irq-renesas-intc-irqpin.c:intc_irqpin_irq_domain_map
```
```
In drivers/pinctrl/pinctrl-single.c (c083f2e8)
Location: include/linux/irqdesc.h:260
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-single.c:pcs_irqdomain_map
```
```
In drivers/gpio/gpiolib.c (c085f9d0)
Location: include/linux/irqdesc.h:260
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
  - drivers/gpio/gpiolib.c:gpiochip_hierarchy_irq_domain_alloc
```
```
In drivers/mfd/arizona-irq.c (c0a16b84)
Location: include/linux/irqdesc.h:260
Inline: True
Inline callers:
  - drivers/mfd/arizona-irq.c:arizona_irq_map
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/irq/generic-chip.c (c0000000001dc0b0)
Location: include/linux/irqdesc.h:260
Inline: True
Inline callers:
  - kernel/irq/generic-chip.c:irq_setup_generic_chip
  - kernel/irq/generic-chip.c:irq_map_generic_chip
```
```
In drivers/pinctrl/pinctrl-single.c (c000000000833d6c)
Location: include/linux/irqdesc.h:260
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-single.c:pcs_irqdomain_map
```
```
In drivers/gpio/gpiolib.c (c00000000083ce98)
Location: include/linux/irqdesc.h:260
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
```
```
In drivers/mfd/arizona-irq.c (c0000000009d4b64)
Location: include/linux/irqdesc.h:260
Inline: True
Inline callers:
  - drivers/mfd/arizona-irq.c:arizona_irq_map
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
In kernel/irq/generic-chip.c (ffffffe000119084)
Location: include/linux/irqdesc.h:260
Inline: True
Inline callers:
  - kernel/irq/generic-chip.c:irq_setup_generic_chip
  - kernel/irq/generic-chip.c:irq_map_generic_chip
```
```
In drivers/pinctrl/pinctrl-single.c (ffffffe0004a076e)
Location: include/linux/irqdesc.h:260
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-single.c:pcs_irqdomain_map
```
```
In drivers/gpio/gpiolib.c (ffffffe0004a681a)
Location: include/linux/irqdesc.h:260
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
  - drivers/gpio/gpiolib.c:gpiochip_hierarchy_irq_domain_alloc
```
```
In drivers/mfd/arizona-irq.c (ffffffe0005a99e8)
Location: include/linux/irqdesc.h:260
Inline: True
Inline callers:
  - drivers/mfd/arizona-irq.c:arizona_irq_map
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
In kernel/irq/generic-chip.c (ffffffff81114ea4)
Location: include/linux/irqdesc.h:260
Inline: True
Inline callers:
  - kernel/irq/generic-chip.c:irq_setup_generic_chip
  - kernel/irq/generic-chip.c:irq_map_generic_chip
```
```
In drivers/gpio/gpiolib.c (ffffffff815616af)
Location: include/linux/irqdesc.h:260
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
  - drivers/gpio/gpiolib.c:gpiochip_hierarchy_irq_domain_alloc
```
```
In drivers/mfd/arizona-irq.c (ffffffff816fcd3a)
Location: include/linux/irqdesc.h:260
Inline: True
Inline callers:
  - drivers/mfd/arizona-irq.c:arizona_irq_map
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
In kernel/irq/generic-chip.c (ffffffff81105bb4)
Location: include/linux/irqdesc.h:260
Inline: True
Inline callers:
  - kernel/irq/generic-chip.c:irq_setup_generic_chip
  - kernel/irq/generic-chip.c:irq_map_generic_chip
```
```
In drivers/gpio/gpiolib.c (ffffffff815524ff)
Location: include/linux/irqdesc.h:260
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
  - drivers/gpio/gpiolib.c:gpiochip_hierarchy_irq_domain_alloc
```
```
In drivers/mfd/arizona-irq.c (ffffffff816d0b4a)
Location: include/linux/irqdesc.h:260
Inline: True
Inline callers:
  - drivers/mfd/arizona-irq.c:arizona_irq_map
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
In kernel/irq/generic-chip.c (ffffffff81112d94)
Location: include/linux/irqdesc.h:260
Inline: True
Inline callers:
  - kernel/irq/generic-chip.c:irq_setup_generic_chip
  - kernel/irq/generic-chip.c:irq_map_generic_chip
```
```
In drivers/gpio/gpiolib.c (ffffffff8156021f)
Location: include/linux/irqdesc.h:260
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
  - drivers/gpio/gpiolib.c:gpiochip_hierarchy_irq_domain_alloc
```
```
In drivers/mfd/arizona-irq.c (ffffffff8172c49a)
Location: include/linux/irqdesc.h:260
Inline: True
Inline callers:
  - drivers/mfd/arizona-irq.c:arizona_irq_map
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
In kernel/irq/generic-chip.c (ffffffff8111e522)
Location: include/linux/irqdesc.h:260
Inline: True
Inline callers:
  - kernel/irq/generic-chip.c:irq_setup_generic_chip
  - kernel/irq/generic-chip.c:irq_map_generic_chip
```
```
In drivers/gpio/gpiolib.c (ffffffff8157a08f)
Location: include/linux/irqdesc.h:260
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_irq_map
  - drivers/gpio/gpiolib.c:gpiochip_hierarchy_irq_domain_alloc
```
```
In drivers/mfd/arizona-irq.c (ffffffff817478da)
Location: include/linux/irqdesc.h:260
Inline: True
Inline callers:
  - drivers/mfd/arizona-irq.c:arizona_irq_map
```
</details>
</li>
</ul>

## Differences
