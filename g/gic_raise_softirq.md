# Function: <code>gic_raise_softirq</code>

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
void gic_raise_softirq(const struct cpumask *mask, unsigned int irq);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/irqchip/irq-gic.c (ffff80001066be00)
Location: drivers/irqchip/irq-gic.c:806
Inline: True
```
```
In drivers/irqchip/irq-gic-v3.c (ffff80001066dec0)
Location: drivers/irqchip/irq-gic-v3.c:1095
Inline: False
```
**Symbols:**

```
ffff80001066be00-ffff80001066beb8: gic_raise_softirq (STB_LOCAL)
ffff80001066dec0-ffff80001066e008: gic_raise_softirq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Collision, Selective Inline ⚠️</summary>

```c
void gic_raise_softirq(const struct cpumask *mask, unsigned int irq);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/irqchip/irq-gic.c (c08151d4)
Location: drivers/irqchip/irq-gic.c:806
Inline: True
```
```
In drivers/irqchip/irq-gic-v3.c (c08174a4)
Location: drivers/irqchip/irq-gic-v3.c:1095
Inline: False
```
**Symbols:**

```
c08151d4-c0815280: gic_raise_softirq (STB_LOCAL)
c08174a4-c08175f8: gic_raise_softirq (STB_LOCAL)
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
