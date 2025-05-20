# Function: <code>cpumap_print_list_to_buf</code>

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
In drivers/base/topology.c (ffffffff81842092)
Location: include/linux/cpumask.h:1018
Inline: True
Inline callers:
  - drivers/base/topology.c:die_cpus_list_read
```
```
In drivers/base/node.c (ffffffff8185b920)
Location: include/linux/cpumask.h:1018
Inline: True
Inline callers:
  - drivers/base/node.c:cpulist_read
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
In drivers/base/topology.c (ffffffff81985812)
Location: include/linux/cpumask.h:1044
Inline: True
Inline callers:
  - drivers/base/topology.c:die_cpus_list_read
  - drivers/base/topology.c:cluster_cpus_list_read
```
```
In drivers/base/node.c (ffffffff819a2929)
Location: include/linux/cpumask.h:1044
Inline: True
Inline callers:
  - drivers/base/node.c:cpulist_read
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
In drivers/base/topology.c (ffffffff81af3c72)
Location: include/linux/cpumask.h:1153
Inline: True
Inline callers:
  - drivers/base/topology.c:die_cpus_list_read
  - drivers/base/topology.c:cluster_cpus_list_read
```
```
In drivers/base/node.c (ffffffff81b148de)
Location: include/linux/cpumask.h:1153
Inline: True
Inline callers:
  - drivers/base/node.c:cpulist_read
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
In drivers/base/topology.c (ffffffff81b41e82)
Location: include/linux/cpumask.h:1209
Inline: True
Inline callers:
  - drivers/base/topology.c:die_cpus_list_read
  - drivers/base/topology.c:cluster_cpus_list_read
```
```
In drivers/base/node.c (ffffffff81b6364e)
Location: include/linux/cpumask.h:1209
Inline: True
Inline callers:
  - drivers/base/node.c:cpulist_read
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
In drivers/base/topology.c (ffffffff81b99d52)
Location: include/linux/cpumask.h:1234
Inline: True
Inline callers:
  - drivers/base/topology.c:die_cpus_list_read
  - drivers/base/topology.c:cluster_cpus_list_read
```
```
In drivers/base/node.c (ffffffff81bb715e)
Location: include/linux/cpumask.h:1234
Inline: True
Inline callers:
  - drivers/base/node.c:cpulist_read
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
