# Function: <code>gic_poke_irq</code>

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
void gic_poke_irq(struct irq_data *d, u32 offset);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/irqchip/irq-gic.c (ffff80001066b86c)
Location: drivers/irqchip/irq-gic.c:190
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic.c:gic_irq_set_irqchip_state
  - drivers/irqchip/irq-gic.c:gic_unmask_irq
  - drivers/irqchip/irq-gic.c:gic_eoimode1_mask_irq
  - drivers/irqchip/irq-gic.c:gic_eoimode1_mask_irq
```
```
In drivers/irqchip/irq-gic-v3.c (ffff80001066e8b8)
Location: drivers/irqchip/irq-gic-v3.c:308
Inline: False
Direct callers:
  - drivers/irqchip/irq-gic-v3.c:gic_set_affinity
  - drivers/irqchip/irq-gic-v3.c:gic_set_affinity
  - drivers/irqchip/irq-gic-v3.c:gic_irq_set_irqchip_state
  - drivers/irqchip/irq-gic-v3.c:gic_eoimode1_mask_irq
  - drivers/irqchip/irq-gic-v3.c:gic_eoimode1_mask_irq
```
**Symbols:**

```
ffff80001066e8b8-ffff80001066e994: gic_poke_irq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Collision, Selective Inline ⚠️</summary>

```c
void gic_poke_irq(struct irq_data *d, u32 offset);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/irqchip/irq-gic.c (c0814a0c)
Location: drivers/irqchip/irq-gic.c:190
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic.c:gic_irq_set_irqchip_state
  - drivers/irqchip/irq-gic.c:gic_unmask_irq
  - drivers/irqchip/irq-gic.c:gic_eoimode1_mask_irq
  - drivers/irqchip/irq-gic.c:gic_eoimode1_mask_irq
```
```
In drivers/irqchip/irq-gic-v3.c (c0816de0)
Location: drivers/irqchip/irq-gic-v3.c:308
Inline: False
Direct callers:
  - drivers/irqchip/irq-gic-v3.c:gic_set_affinity
  - drivers/irqchip/irq-gic-v3.c:gic_set_affinity
  - drivers/irqchip/irq-gic-v3.c:gic_irq_set_irqchip_state
  - drivers/irqchip/irq-gic-v3.c:gic_eoimode1_mask_irq
  - drivers/irqchip/irq-gic-v3.c:gic_eoimode1_mask_irq
```
**Symbols:**

```
c0816de0-c0816eb8: gic_poke_irq (STB_LOCAL)
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
