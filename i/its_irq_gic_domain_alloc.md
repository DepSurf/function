# Function: <code>its_irq_gic_domain_alloc</code>

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
int its_irq_gic_domain_alloc(struct irq_domain *domain, unsigned int virq, irq_hw_number_t hwirq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/irqchip/irq-gic-v3-its.c (ffff800010670a18)
Location: drivers/irqchip/irq-gic-v3-its.c:2554
Inline: False
Direct callers:
  - drivers/irqchip/irq-gic-v3-its.c:its_vpe_irq_domain_alloc
  - drivers/irqchip/irq-gic-v3-its.c:its_irq_domain_alloc
```
**Symbols:**

```
ffff800010670a18-ffff800010670b00: its_irq_gic_domain_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int its_irq_gic_domain_alloc(struct irq_domain *domain, unsigned int virq, irq_hw_number_t hwirq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/irqchip/irq-gic-v3-its.c (c0819f8c)
Location: drivers/irqchip/irq-gic-v3-its.c:2554
Inline: False
Direct callers:
  - drivers/irqchip/irq-gic-v3-its.c:its_vpe_irq_domain_alloc
  - drivers/irqchip/irq-gic-v3-its.c:its_irq_domain_alloc
```
**Symbols:**

```
c0819f8c-c081a070: its_irq_gic_domain_alloc (STB_LOCAL)
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
