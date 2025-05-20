# Function: <code>gic_irq_set_vcpu_affinity</code>

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
int gic_irq_set_vcpu_affinity(struct irq_data *d, void *vcpu);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/irqchip/irq-gic.c (ffff80001066b8d0)
Location: drivers/irqchip/irq-gic.c:315
Inline: False
```
```
In drivers/irqchip/irq-gic-v3.c (ffff80001066e0a0)
Location: drivers/irqchip/irq-gic-v3.c:563
Inline: True
```
**Symbols:**

```
ffff80001066b8d0-ffff80001066b938: gic_irq_set_vcpu_affinity (STB_LOCAL)
ffff80001066e0a0-ffff80001066e0e8: gic_irq_set_vcpu_affinity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Collision, Selective Inline ⚠️</summary>

```c
int gic_irq_set_vcpu_affinity(struct irq_data *d, void *vcpu);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/irqchip/irq-gic.c (c0814a5c)
Location: drivers/irqchip/irq-gic.c:315
Inline: False
```
```
In drivers/irqchip/irq-gic-v3.c (c0817920)
Location: drivers/irqchip/irq-gic-v3.c:563
Inline: True
```
**Symbols:**

```
c0814a5c-c0814aa4: gic_irq_set_vcpu_affinity (STB_LOCAL)
c0817920-c0817954: gic_irq_set_vcpu_affinity (STB_LOCAL)
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
