# Function: <code>mem_cgroup_get_lru_size</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff811a04be)
Location: include/linux/memcontrol.h:378
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff811b871a)
Location: include/linux/memcontrol.h:439
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff811c8d5b)
Location: include/linux/memcontrol.h:441
Inline: True
Inline callers:
  - mm/vmscan.c:lruvec_lru_size
```
```
In mm/memcontrol.c (ffffffff81232ae6)
Location: include/linux/memcontrol.h:441
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_node_nr_lru_pages
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff811d168a)
Location: include/linux/memcontrol.h:435
Inline: True
Inline callers:
  - mm/vmscan.c:lruvec_lru_size
```
```
In mm/memcontrol.c (0)
Location: include/linux/memcontrol.h:435
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff811e6b2a)
Location: include/linux/memcontrol.h:435
Inline: True
Inline callers:
  - mm/vmscan.c:lruvec_lru_size
```
```
In mm/memcontrol.c (0)
Location: include/linux/memcontrol.h:435
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff81207eec)
Location: include/linux/memcontrol.h:468
Inline: True
Inline callers:
  - mm/vmscan.c:lruvec_lru_size
```
```
In mm/memcontrol.c (ffffffff81282124)
Location: include/linux/memcontrol.h:468
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_node_nr_lru_pages
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff8121aa6c)
Location: include/linux/memcontrol.h:503
Inline: True
Inline callers:
  - mm/vmscan.c:lruvec_lru_size
```
```
In mm/memcontrol.c (ffffffff81296304)
Location: include/linux/memcontrol.h:503
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_node_nr_lru_pages
```
</details>
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
