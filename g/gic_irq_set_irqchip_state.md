# Function: <code>gic_irq_set_irqchip_state</code>

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
int gic_irq_set_irqchip_state(struct irq_data *d, enum irqchip_irq_state which, bool val);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/irqchip/irq-gic.c (ffff80001066b810)
Location: drivers/irqchip/irq-gic.c:241
Inline: False
```
```
In drivers/irqchip/irq-gic-v3.c (ffff80001066e998)
Location: drivers/irqchip/irq-gic-v3.c:360
Inline: False
```
**Symbols:**

```
ffff80001066b810-ffff80001066b8d0: gic_irq_set_irqchip_state (STB_LOCAL)
ffff80001066e998-ffff80001066ea50: gic_irq_set_irqchip_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Collision ⚠️</summary>

```c
int gic_irq_set_irqchip_state(struct irq_data *d, enum irqchip_irq_state which, bool val);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/irqchip/irq-gic.c (c08149cc)
Location: drivers/irqchip/irq-gic.c:241
Inline: False
```
```
In drivers/irqchip/irq-gic-v3.c (c0816eb8)
Location: drivers/irqchip/irq-gic-v3.c:360
Inline: False
```
**Symbols:**

```
c08149cc-c0814a5c: gic_irq_set_irqchip_state (STB_LOCAL)
c0816eb8-c0816f30: gic_irq_set_irqchip_state (STB_LOCAL)
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
