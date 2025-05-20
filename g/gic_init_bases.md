# Function: <code>gic_init_bases</code>

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
int gic_init_bases(struct gic_chip_data *gic, struct fwnode_handle *handle);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/irqchip/irq-gic.c (ffff80001066c418)
Location: drivers/irqchip/irq-gic.c:1097
Inline: False
Direct callers:
  - drivers/irqchip/irq-gic.c:gic_of_init_child
  - drivers/irqchip/irq-gic.c:__gic_init_bases
```
```
In drivers/irqchip/irq-gic-v3.c (ffff800011472c84)
Location: drivers/irqchip/irq-gic-v3.c:1513
Inline: False
Direct callers:
  - drivers/irqchip/irq-gic-v3.c:gic_acpi_init
  - drivers/irqchip/irq-gic-v3.c:gic_of_init
```
**Symbols:**

```
ffff80001066c418-ffff80001066c650: gic_init_bases (STB_LOCAL)
ffff800011472c84-ffff8000114731a4: gic_init_bases (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Collision ⚠️</summary>

```c
int gic_init_bases(struct gic_chip_data *gic, struct fwnode_handle *handle);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/irqchip/irq-gic.c (c08153f4)
Location: drivers/irqchip/irq-gic.c:1097
Inline: False
Direct callers:
  - drivers/irqchip/irq-gic.c:gic_of_init_child
  - drivers/irqchip/irq-gic.c:__gic_init_bases
```
```
In drivers/irqchip/irq-gic-v3.c (c154b758)
Location: drivers/irqchip/irq-gic-v3.c:1513
Inline: False
Direct callers:
  - drivers/irqchip/irq-gic-v3.c:gic_of_init
```
**Symbols:**

```
c08153f4-c0815694: gic_init_bases (STB_LOCAL)
c154b758-c154bcb0: gic_init_bases (STB_LOCAL)
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
