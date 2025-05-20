# Function: <code>cpumap_print_bitmask_to_buf</code>

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
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/topology.c (ffffffff81842212)
Location: include/linux/cpumask.h:1003
Inline: True
Inline callers:
  - drivers/base/topology.c:die_cpus_read
```
```
In drivers/base/node.c (ffffffff8185bb90)
Location: include/linux/cpumask.h:1003
Inline: True
Inline callers:
  - drivers/base/node.c:cpumap_read
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/topology.c (ffffffff819859c2)
Location: include/linux/cpumask.h:1029
Inline: True
Inline callers:
  - drivers/base/topology.c:die_cpus_read
  - drivers/base/topology.c:cluster_cpus_read
```
```
In drivers/base/node.c (ffffffff819a2c19)
Location: include/linux/cpumask.h:1029
Inline: True
Inline callers:
  - drivers/base/node.c:cpumap_read
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/topology.c (ffffffff81af3e52)
Location: include/linux/cpumask.h:1138
Inline: True
Inline callers:
  - drivers/base/topology.c:die_cpus_read
  - drivers/base/topology.c:cluster_cpus_read
```
```
In drivers/base/node.c (ffffffff81b14a6e)
Location: include/linux/cpumask.h:1138
Inline: True
Inline callers:
  - drivers/base/node.c:cpumap_read
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/topology.c (ffffffff81b42062)
Location: include/linux/cpumask.h:1190
Inline: True
Inline callers:
  - drivers/base/topology.c:die_cpus_read
  - drivers/base/topology.c:cluster_cpus_read
```
```
In drivers/base/node.c (ffffffff81b637de)
Location: include/linux/cpumask.h:1190
Inline: True
Inline callers:
  - drivers/base/node.c:cpumap_read
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/topology.c (ffffffff81b99f32)
Location: include/linux/cpumask.h:1212
Inline: True
Inline callers:
  - drivers/base/topology.c:die_cpus_read
  - drivers/base/topology.c:cluster_cpus_read
```
```
In drivers/base/node.c (ffffffff81bb72ee)
Location: include/linux/cpumask.h:1212
Inline: True
Inline callers:
  - drivers/base/node.c:cpumap_read
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
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
