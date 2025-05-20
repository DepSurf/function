# Function: <code>gic_mask_irq</code>

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
<summary>In <code>arm64</code>: Collision, Selective Inline ⚠️</summary>

```c
void gic_mask_irq(struct irq_data *d);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/irqchip/irq-gic.c (ffff80001066b738)
Location: drivers/irqchip/irq-gic.c:202
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic.c:gic_eoimode1_mask_irq
```
```
In drivers/irqchip/irq-gic-v3.c (ffff80001066f300)
Location: drivers/irqchip/irq-gic-v3.c:329
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic-v3.c:gic_set_affinity
  - drivers/irqchip/irq-gic-v3.c:gic_eoimode1_mask_irq
```
**Symbols:**

```
ffff80001066b6d0-ffff80001066b71c: gic_mask_irq (STB_LOCAL)
ffff80001066ea50-ffff80001066ea80: gic_mask_irq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Collision, Selective Inline ⚠️</summary>

```c
void gic_mask_irq(struct irq_data *d);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/irqchip/irq-gic.c (c0814914)
Location: drivers/irqchip/irq-gic.c:202
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic.c:gic_eoimode1_mask_irq
```
```
In drivers/irqchip/irq-gic-v3.c (c08180a4)
Location: drivers/irqchip/irq-gic-v3.c:329
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic-v3.c:gic_set_affinity
  - drivers/irqchip/irq-gic-v3.c:gic_eoimode1_mask_irq
```
**Symbols:**

```
c08148bc-c0814900: gic_mask_irq (STB_LOCAL)
c0816f30-c0816f50: gic_mask_irq (STB_LOCAL)
```
</details>
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
<b>Arch</b>
<ul>
</ul>
