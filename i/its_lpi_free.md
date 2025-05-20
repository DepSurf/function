# Function: <code>its_lpi_free</code>

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
void its_lpi_free(long unsigned int *bitmap, u32 base, u32 nr_ids);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/irqchip/irq-gic-v3-its.c (ffff800010670f60)
Location: drivers/irqchip/irq-gic-v3-its.c:1622
Inline: False
Direct callers:
  - drivers/irqchip/irq-gic-v3-its.c:its_vpe_irq_domain_alloc
  - drivers/irqchip/irq-gic-v3-its.c:its_vpe_irq_domain_alloc
  - drivers/irqchip/irq-gic-v3-its.c:its_vpe_irq_domain_alloc
  - drivers/irqchip/irq-gic-v3-its.c:its_vpe_irq_domain_free
  - drivers/irqchip/irq-gic-v3-its.c:its_irq_domain_free
```
**Symbols:**

```
ffff800010670f60-ffff800010670fc8: its_lpi_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void its_lpi_free(long unsigned int *bitmap, u32 base, u32 nr_ids);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/irqchip/irq-gic-v3-its.c (c081aa4c)
Location: drivers/irqchip/irq-gic-v3-its.c:1622
Inline: False
Direct callers:
  - drivers/irqchip/irq-gic-v3-its.c:its_vpe_irq_domain_alloc
  - drivers/irqchip/irq-gic-v3-its.c:its_vpe_irq_domain_alloc
  - drivers/irqchip/irq-gic-v3-its.c:its_vpe_irq_domain_alloc
  - drivers/irqchip/irq-gic-v3-its.c:its_vpe_irq_domain_free
  - drivers/irqchip/irq-gic-v3-its.c:its_irq_domain_free
```
**Symbols:**

```
c081aa4c-c081aaa4: its_lpi_free (STB_LOCAL)
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
