# Function: <code>gic_irq</code>

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
<summary>In <code>arm64</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/irqchip/irq-gic.c (ffff80001066c350)
Location: drivers/irqchip/irq-gic.c:171
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic.c:gic_set_affinity
  - drivers/irqchip/irq-gic.c:gic_set_type
  - drivers/irqchip/irq-gic.c:gic_irq_set_irqchip_state
  - drivers/irqchip/irq-gic.c:gic_eoi_irq
  - drivers/irqchip/irq-gic.c:gic_unmask_irq
  - drivers/irqchip/irq-gic.c:gic_eoimode1_mask_irq
  - drivers/irqchip/irq-gic.c:gic_peek_irq
```
```
In drivers/irqchip/irq-gic-v3.c (ffff80001066efd8)
Location: drivers/irqchip/irq-gic-v3.c:136
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic-v3.c:gic_set_type
  - drivers/irqchip/irq-gic-v3.c:gic_eoimode1_eoi_irq
  - drivers/irqchip/irq-gic-v3.c:gic_irq_nmi_teardown
  - drivers/irqchip/irq-gic-v3.c:gic_irq_nmi_setup
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/irqchip/irq-gic.c (c08156a8)
Location: drivers/irqchip/irq-gic.c:171
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic.c:gic_set_affinity
  - drivers/irqchip/irq-gic.c:gic_set_type
  - drivers/irqchip/irq-gic.c:gic_irq_set_irqchip_state
  - drivers/irqchip/irq-gic.c:gic_eoi_irq
  - drivers/irqchip/irq-gic.c:gic_unmask_irq
  - drivers/irqchip/irq-gic.c:gic_eoimode1_mask_irq
```
```
In drivers/irqchip/irq-gic-v3.c (c0817120)
Location: drivers/irqchip/irq-gic-v3.c:136
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic-v3.c:gic_set_type
  - drivers/irqchip/irq-gic-v3.c:gic_eoimode1_eoi_irq
  - drivers/irqchip/irq-gic-v3.c:gic_eoi_irq
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
