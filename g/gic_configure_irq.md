# Function: <code>gic_configure_irq</code>

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
int gic_configure_irq(unsigned int irq, unsigned int type, void *base, void (*sync_access)());
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/irqchip/irq-gic-common.c (ffff80001066ced8)
Location: drivers/irqchip/irq-gic-common.c:54
Inline: False
Direct callers:
  - drivers/irqchip/irq-gic.c:gic_set_type
  - drivers/irqchip/irq-gic.c:gic_set_type
  - drivers/irqchip/irq-gic-v3.c:gic_set_type
```
**Symbols:**

```
ffff80001066ced8-ffff80001066d034: gic_configure_irq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int gic_configure_irq(unsigned int irq, unsigned int type, void *base, void (*sync_access)());
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/irqchip/irq-gic-common.c (c0816124)
Location: drivers/irqchip/irq-gic-common.c:54
Inline: False
Direct callers:
  - drivers/irqchip/irq-hip04.c:hip04_irq_set_type
  - drivers/irqchip/irq-hip04.c:hip04_irq_set_type
  - drivers/irqchip/irq-gic.c:gic_set_type
  - drivers/irqchip/irq-gic.c:gic_set_type
  - drivers/irqchip/irq-gic-v3.c:gic_set_type
```
**Symbols:**

```
c0816124-c08161d8: gic_configure_irq (STB_GLOBAL)
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
