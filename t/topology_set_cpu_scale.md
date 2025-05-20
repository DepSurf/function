# Function: <code>topology_set_cpu_scale</code>

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
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void topology_set_cpu_scale(unsigned int cpu, long unsigned int capacity);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/arch_topology.c (ffff800010920230)
Location: drivers/base/arch_topology.c:40
Inline: True
Inline callers:
  - drivers/base/arch_topology.c:topology_normalize_cpu_scale
```
**Symbols:**

```
ffff800010920148-ffff800010920188: topology_set_cpu_scale (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void topology_set_cpu_scale(unsigned int cpu, long unsigned int capacity);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/arch_topology.c (c0a051f0)
Location: drivers/base/arch_topology.c:40
Inline: True
Inline callers:
  - drivers/base/arch_topology.c:topology_normalize_cpu_scale
Direct callers:
  - arch/arm/kernel/topology.c:store_cpu_topology
```
**Symbols:**

```
c0a05114-c0a05144: topology_set_cpu_scale (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void topology_set_cpu_scale(unsigned int cpu, long unsigned int capacity);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/arch_topology.c (ffffffe00059eed2)
Location: drivers/base/arch_topology.c:40
Inline: True
Inline callers:
  - drivers/base/arch_topology.c:topology_normalize_cpu_scale
```
**Symbols:**

```
ffffffe00059ee28-ffffffe00059ee6c: topology_set_cpu_scale (STB_GLOBAL)
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
