# Function: <code>irq_set_probe</code>

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
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff815702ce)
Location: include/linux/irq.h:727
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_hierarchy_irq_domain_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8160d1d7)
Location: include/linux/irq.h:757
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_hierarchy_irq_domain_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81633fa7)
Location: include/linux/irq.h:770
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_hierarchy_irq_domain_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81617af7)
Location: include/linux/irq.h:772
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_hierarchy_irq_domain_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81686d77)
Location: include/linux/irq.h:774
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_hierarchy_irq_domain_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff817a3cac)
Location: include/linux/irq.h:778
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_hierarchy_irq_domain_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff818bb59c)
Location: include/linux/irq.h:780
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_hierarchy_irq_domain_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff818fe6b2)
Location: include/linux/irq.h:793
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_hierarchy_irq_domain_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81945ce2)
Location: include/linux/irq.h:775
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_hierarchy_irq_domain_alloc
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
In drivers/irqchip/irq-bcm2835.c (ffff80001147095c)
Location: include/linux/irq.h:727
Inline: True
```
```
In drivers/irqchip/irq-sun4i.c (ffff80001066b2a4)
Location: include/linux/irq.h:727
Inline: True
Inline callers:
  - drivers/irqchip/irq-sun4i.c:sun4i_irq_map
```
```
In drivers/irqchip/irq-gic.c (ffff80001066bb94)
Location: include/linux/irq.h:727
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic.c:gic_irq_domain_map
```
```
In drivers/irqchip/irq-gic-v3.c (ffff80001066e5c8)
Location: include/linux/irq.h:727
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic-v3.c:gic_irq_domain_alloc
```
```
In drivers/irqchip/irq-mvebu-pic.c (ffff80001067a084)
Location: include/linux/irq.h:727
Inline: True
Inline callers:
  - drivers/irqchip/irq-mvebu-pic.c:mvebu_pic_irq_map
```
```
In drivers/irqchip/irq-mvebu-sei.c (ffff80001067a57c)
Location: include/linux/irq.h:727
Inline: True
Inline callers:
  - drivers/irqchip/irq-mvebu-sei.c:mvebu_sei_ap_alloc
```
```
In drivers/gpio/gpiolib.c (ffff8000106be318)
Location: include/linux/irq.h:727
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_hierarchy_irq_domain_alloc
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
In drivers/irqchip/exynos-combiner.c (c081393c)
Location: include/linux/irq.h:727
Inline: True
Inline callers:
  - drivers/irqchip/exynos-combiner.c:combiner_irq_domain_map
```
```
In drivers/irqchip/irq-hip04.c (c0813de4)
Location: include/linux/irq.h:727
Inline: True
Inline callers:
  - drivers/irqchip/irq-hip04.c:hip04_irq_domain_map
```
```
In drivers/irqchip/irq-gic.c (c0814e5c)
Location: include/linux/irq.h:727
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic.c:gic_irq_domain_map
```
```
In drivers/irqchip/irq-gic-v3.c (c0817394)
Location: include/linux/irq.h:727
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic-v3.c:gic_irq_domain_alloc
```
```
In drivers/irqchip/irq-armada-370-xp.c (c081e98c)
Location: include/linux/irq.h:727
Inline: True
Inline callers:
  - drivers/irqchip/irq-armada-370-xp.c:armada_370_xp_mpic_irq_map
```
```
In drivers/irqchip/irq-rda-intc.c (c081ecdc)
Location: include/linux/irq.h:727
Inline: True
Inline callers:
  - drivers/irqchip/irq-rda-intc.c:rda_irq_map
```
```
In drivers/irqchip/irq-aspeed-vic.c (c0821c50)
Location: include/linux/irq.h:727
Inline: True
Inline callers:
  - drivers/irqchip/irq-aspeed-vic.c:avic_map
```
```
In drivers/gpio/gpiolib.c (c085e094)
Location: include/linux/irq.h:727
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_hierarchy_irq_domain_alloc
```
</details>
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffe0004a51e2)
Location: include/linux/irq.h:727
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_hierarchy_irq_domain_alloc
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81565a8e)
Location: include/linux/irq.h:727
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_hierarchy_irq_domain_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff815568de)
Location: include/linux/irq.h:727
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_hierarchy_irq_domain_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff815645fe)
Location: include/linux/irq.h:727
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_hierarchy_irq_domain_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8157e51e)
Location: include/linux/irq.h:727
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_hierarchy_irq_domain_alloc
```
</details>
</li>
</ul>

## Differences
