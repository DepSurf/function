# Function: <code>gic_cpu_init</code>

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
<summary>In <code>arm64</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
int gic_cpu_init(struct gic_chip_data *gic);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/irqchip/irq-gic.c (ffff80001066c100)
Location: drivers/irqchip/irq-gic.c:514
Inline: False
Direct callers:
  - drivers/irqchip/irq-gic.c:gic_init_bases
  - drivers/irqchip/irq-gic.c:gic_starting_cpu
```
```
In drivers/irqchip/irq-gic-v3.c (ffff8000114730a4)
Location: drivers/irqchip/irq-gic-v3.c:1006
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic-v3.c:gic_init_bases
  - drivers/irqchip/irq-gic-v3.c:gic_starting_cpu
Direct callers:
  - drivers/irqchip/irq-gic-v3.c:gic_init_bases
  - drivers/irqchip/irq-gic-v3.c:gic_starting_cpu
```
**Symbols:**

```
ffff80001066c100-ffff80001066c210: gic_cpu_init (STB_LOCAL)
ffff80001066f618-ffff80001066f738: gic_cpu_init.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
int gic_cpu_init(struct gic_chip_data *gic);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/irqchip/irq-gic.c (c08152fc)
Location: drivers/irqchip/irq-gic.c:514
Inline: False
Direct callers:
  - drivers/irqchip/irq-gic.c:gic_init_bases
  - drivers/irqchip/irq-gic.c:gic_starting_cpu
```
```
In drivers/irqchip/irq-gic-v3.c (c154bc2c)
Location: drivers/irqchip/irq-gic-v3.c:1006
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic-v3.c:gic_init_bases
Direct callers:
  - drivers/irqchip/irq-gic-v3.c:gic_init_bases
```
**Symbols:**

```
c08152fc-c08153cc: gic_cpu_init (STB_LOCAL)
c0817d7c-c0817e84: gic_cpu_init.part.0 (STB_LOCAL)
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
