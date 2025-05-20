# Function: <code>of_irq_to_resource_table</code>

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
int of_irq_to_resource_table(struct device_node *dev, struct resource *res, int nr_irqs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/irq.c (ffff800010b751e8)
Location: drivers/of/irq.c:452
Inline: False
Direct callers:
  - drivers/of/platform.c:of_device_alloc
```
**Symbols:**

```
ffff800010b751e8-ffff800010b75258: of_irq_to_resource_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int of_irq_to_resource_table(struct device_node *dev, struct resource *res, int nr_irqs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/irq.c (c0c57694)
Location: drivers/of/irq.c:452
Inline: False
Direct callers:
  - drivers/of/platform.c:of_device_alloc
```
**Symbols:**

```
c0c57694-c0c576f0: of_irq_to_resource_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int of_irq_to_resource_table(struct device_node *dev, struct resource *res, int nr_irqs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/irq.c (c000000000c52680)
Location: drivers/of/irq.c:452
Inline: False
Direct callers:
  - arch/powerpc/platforms/powernv/opal-irqchip.c:opal_event_init
  - drivers/of/platform.c:of_device_alloc
```
**Symbols:**

```
c000000000c52680-c000000000c52728: of_irq_to_resource_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int of_irq_to_resource_table(struct device_node *dev, struct resource *res, int nr_irqs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/irq.c (ffffffe000728a10)
Location: drivers/of/irq.c:452
Inline: False
Direct callers:
  - drivers/of/platform.c:of_device_alloc
```
**Symbols:**

```
ffffffe000728a10-ffffffe000728a66: of_irq_to_resource_table (STB_GLOBAL)
```
</details>
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
