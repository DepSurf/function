# Function: <code>get_intid_range</code>

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
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/irqchip/irq-gic-v3.c (ffff80001066f188)
Location: drivers/irqchip/irq-gic-v3.c:131
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic-v3.c:gic_set_affinity
  - drivers/irqchip/irq-gic-v3.c:gic_set_affinity
  - drivers/irqchip/irq-gic-v3.c:gic_set_type
  - drivers/irqchip/irq-gic-v3.c:gic_set_type
  - drivers/irqchip/irq-gic-v3.c:gic_irq_nmi_teardown
  - drivers/irqchip/irq-gic-v3.c:gic_irq_nmi_setup
  - drivers/irqchip/irq-gic-v3.c:gic_get_ppi_index
  - drivers/irqchip/irq-gic-v3.c:gic_irq_set_prio
  - drivers/irqchip/irq-gic-v3.c:gic_poke_irq
  - drivers/irqchip/irq-gic-v3.c:gic_peek_irq
  - drivers/irqchip/irq-gic-v3.c:convert_offset_index
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/irqchip/irq-gic-v3.c (c0817f3c)
Location: drivers/irqchip/irq-gic-v3.c:131
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic-v3.c:gic_set_affinity
  - drivers/irqchip/irq-gic-v3.c:gic_set_affinity
  - drivers/irqchip/irq-gic-v3.c:gic_set_type
  - drivers/irqchip/irq-gic-v3.c:gic_set_type
  - drivers/irqchip/irq-gic-v3.c:gic_poke_irq
  - drivers/irqchip/irq-gic-v3.c:gic_peek_irq
  - drivers/irqchip/irq-gic-v3.c:convert_offset_index
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
