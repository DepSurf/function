# Function: <code>irqd_set_forwarded_to_vcpu</code>

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
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/irqchip/irq-gic.c (ffff80001066b900)
Location: include/linux/irq.h:341
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic.c:gic_irq_set_vcpu_affinity
```
```
In drivers/irqchip/irq-gic-v3.c (0)
Location: include/linux/irq.h:341
Inline: True
```
```
In drivers/irqchip/irq-gic-v3-its.c (ffff800010673514)
Location: include/linux/irq.h:341
Inline: True
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
In drivers/irqchip/irq-gic.c (c0814a84)
Location: include/linux/irq.h:341
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic.c:gic_irq_set_vcpu_affinity
```
```
In drivers/irqchip/irq-gic-v3.c (c0817944)
Location: include/linux/irq.h:341
Inline: True
```
```
In drivers/irqchip/irq-gic-v3-its.c (c081c810)
Location: include/linux/irq.h:341
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic-v3-its.c:its_irq_set_vcpu_affinity
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
In arch/powerpc/sysdev/xive/common.c (c0000000000bdbec)
Location: include/linux/irq.h:341
Inline: True
Inline callers:
  - arch/powerpc/sysdev/xive/common.c:xive_irq_set_vcpu_affinity
```
</details>
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
