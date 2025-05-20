# Function: <code>of_cpu_node_to_id</code>

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
int of_cpu_node_to_id(struct device_node *cpu_node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/base.c (ffff800010b6b1a0)
Location: drivers/of/base.c:462
Inline: False
Direct callers:
  - drivers/irqchip/irq-gic-v3.c:gic_populate_ppi_partitions
  - drivers/base/arch_topology.c:get_cpu_for_node
  - drivers/perf/arm_pmu_platform.c:pmu_parse_irqs
```
**Symbols:**

```
ffff800010b6b1a0-ffff800010b6b26c: of_cpu_node_to_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int of_cpu_node_to_id(struct device_node *cpu_node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/base.c (c0c4e5a0)
Location: drivers/of/base.c:462
Inline: False
Direct callers:
  - drivers/irqchip/irq-gic-v3.c:gic_populate_ppi_partitions
  - drivers/perf/arm_pmu_platform.c:arm_pmu_device_probe
```
**Symbols:**

```
c0c4e5a0-c0c4e644: of_cpu_node_to_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int of_cpu_node_to_id(struct device_node *cpu_node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/base.c (c000000000c44d10)
Location: drivers/of/base.c:462
Inline: False
```
**Symbols:**

```
c000000000c44d10-c000000000c44e2c: of_cpu_node_to_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int of_cpu_node_to_id(struct device_node *cpu_node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/base.c (ffffffe000720712)
Location: drivers/of/base.c:462
Inline: False
Direct callers:
  - drivers/base/arch_topology.c:get_cpu_for_node
```
**Symbols:**

```
ffffffe000720712-ffffffe0007207b6: of_cpu_node_to_id (STB_GLOBAL)
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
