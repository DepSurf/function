# Function: <code>gic_irq_domain_map</code>

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
int gic_irq_domain_map(struct irq_domain *d, unsigned int irq, irq_hw_number_t hw);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/irqchip/irq-gic.c (ffff80001066bae8)
Location: drivers/irqchip/irq-gic.c:976
Inline: False
Direct callers:
  - drivers/irqchip/irq-gic.c:gic_irq_domain_alloc
```
```
In drivers/irqchip/irq-gic-v3.c (ffff80001066e534)
Location: drivers/irqchip/irq-gic-v3.c:1238
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic-v3.c:gic_irq_domain_alloc
```
**Symbols:**

```
ffff80001066bae8-ffff80001066bbd0: gic_irq_domain_map (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Collision, Selective Inline ⚠️</summary>

```c
int gic_irq_domain_map(struct irq_domain *d, unsigned int irq, irq_hw_number_t hw);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/irqchip/irq-gic.c (c0814db0)
Location: drivers/irqchip/irq-gic.c:976
Inline: False
Direct callers:
  - drivers/irqchip/irq-gic.c:gic_irq_domain_alloc
```
```
In drivers/irqchip/irq-gic-v3.c (c0817310)
Location: drivers/irqchip/irq-gic-v3.c:1238
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic-v3.c:gic_irq_domain_alloc
```
**Symbols:**

```
c0814db0-c0814e90: gic_irq_domain_map (STB_LOCAL)
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
