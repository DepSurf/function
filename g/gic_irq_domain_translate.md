# Function: <code>gic_irq_domain_translate</code>

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
<summary>In <code>arm64</code>: Collision ⚠️</summary>

```c
int gic_irq_domain_translate(struct irq_domain *d, struct irq_fwspec *fwspec, long unsigned int *hwirq, unsigned int *type);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/irqchip/irq-gic.c (ffff80001066b950)
Location: drivers/irqchip/irq-gic.c:999
Inline: False
Direct callers:
  - drivers/irqchip/irq-gic.c:gic_irq_domain_alloc
```
```
In drivers/irqchip/irq-gic-v3.c (ffff80001066dc60)
Location: drivers/irqchip/irq-gic-v3.c:1279
Inline: False
Direct callers:
  - drivers/irqchip/irq-gic-v3.c:gic_irq_domain_alloc
```
**Symbols:**

```
ffff80001066b950-ffff80001066ba40: gic_irq_domain_translate (STB_LOCAL)
ffff80001066dc60-ffff80001066ddec: gic_irq_domain_translate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Collision ⚠️</summary>

```c
int gic_irq_domain_translate(struct irq_domain *d, struct irq_fwspec *fwspec, long unsigned int *hwirq, unsigned int *type);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/irqchip/irq-gic.c (c0814c10)
Location: drivers/irqchip/irq-gic.c:999
Inline: False
Direct callers:
  - drivers/irqchip/irq-gic.c:gic_irq_domain_alloc
```
```
In drivers/irqchip/irq-gic-v3.c (c0816a44)
Location: drivers/irqchip/irq-gic-v3.c:1279
Inline: False
Direct callers:
  - drivers/irqchip/irq-gic-v3.c:gic_irq_domain_alloc
```
**Symbols:**

```
c0814c10-c0814d0c: gic_irq_domain_translate (STB_LOCAL)
c0816a44-c0816be0: gic_irq_domain_translate (STB_LOCAL)
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
