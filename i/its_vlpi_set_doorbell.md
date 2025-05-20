# Function: <code>its_vlpi_set_doorbell</code>

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
<summary>In <code>arm64</code>: ✅</summary>

```c
void its_vlpi_set_doorbell(struct irq_data *d, bool enable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/irqchip/irq-gic-v3-its.c (ffff800010671af0)
Location: drivers/irqchip/irq-gic-v3-its.c:1101
Inline: False
Direct callers:
  - drivers/irqchip/irq-gic-v3-its.c:its_unmask_irq
  - drivers/irqchip/irq-gic-v3-its.c:its_mask_irq
```
**Symbols:**

```
ffff800010671af0-ffff800010671b48: its_vlpi_set_doorbell (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void its_vlpi_set_doorbell(struct irq_data *d, bool enable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/irqchip/irq-gic-v3-its.c (c0819d00)
Location: drivers/irqchip/irq-gic-v3-its.c:1101
Inline: False
Direct callers:
  - drivers/irqchip/irq-gic-v3-its.c:its_irq_set_vcpu_affinity
  - drivers/irqchip/irq-gic-v3-its.c:its_unmask_irq
  - drivers/irqchip/irq-gic-v3-its.c:its_mask_irq
```
**Symbols:**

```
c0819d00-c0819d4c: its_vlpi_set_doorbell (STB_LOCAL)
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
