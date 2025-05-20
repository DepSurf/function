# Function: <code>gic_set_affinity</code>

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
int gic_set_affinity(struct irq_data *d, const struct cpumask *mask_val, bool force);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/irqchip/irq-gic.c (ffff80001066c320)
Location: drivers/irqchip/irq-gic.c:329
Inline: False
```
```
In drivers/irqchip/irq-gic-v3.c (ffff80001066f128)
Location: drivers/irqchip/irq-gic-v3.c:1128
Inline: False
```
**Symbols:**

```
ffff80001066c320-ffff80001066c418: gic_set_affinity (STB_LOCAL)
ffff80001066f128-ffff80001066f31c: gic_set_affinity (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Collision ⚠️</summary>

```c
int gic_set_affinity(struct irq_data *d, const struct cpumask *mask_val, bool force);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/irqchip/irq-gic.c (c0815694)
Location: drivers/irqchip/irq-gic.c:329
Inline: False
```
```
In drivers/irqchip/irq-gic-v3.c (c0817ee0)
Location: drivers/irqchip/irq-gic-v3.c:1128
Inline: False
```
**Symbols:**

```
c0815694-c081577c: gic_set_affinity (STB_LOCAL)
c0817ee0-c08180b8: gic_set_affinity (STB_LOCAL)
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
