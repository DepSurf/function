# Function: <code>numa_stat_name</code>

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
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff812764c1)
Location: include/linux/vmstat.h:398
Inline: True
Inline callers:
  - mm/vmstat.c:vmstat_refresh
  - mm/vmstat.c:zoneinfo_show_print
```
```
In drivers/base/node.c (ffffffff817d7671)
Location: include/linux/vmstat.h:398
Inline: True
Inline callers:
  - drivers/base/node.c:node_read_vmstat
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff81be6f6c)
Location: include/linux/vmstat.h:415
Inline: True
Inline callers:
  - mm/vmstat.c:vmstat_refresh
  - mm/vmstat.c:zoneinfo_show_print
```
```
In drivers/base/node.c (ffffffff817ec0bc)
Location: include/linux/vmstat.h:415
Inline: True
Inline callers:
  - drivers/base/node.c:node_read_vmstat
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff81283e7b)
Location: include/linux/vmstat.h:421
Inline: True
Inline callers:
  - mm/vmstat.c:zoneinfo_show_print
```
```
In drivers/base/node.c (ffffffff817d08dc)
Location: include/linux/vmstat.h:421
Inline: True
Inline callers:
  - drivers/base/node.c:node_read_vmstat
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff812c2582)
Location: include/linux/vmstat.h:434
Inline: True
Inline callers:
  - mm/vmstat.c:zoneinfo_show_print
```
```
In drivers/base/node.c (ffffffff8185b271)
Location: include/linux/vmstat.h:434
Inline: True
Inline callers:
  - drivers/base/node.c:node_read_vmstat
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
In mm/vmstat.c (ffffffff8131f654)
Location: include/linux/vmstat.h:506
Inline: True
Inline callers:
  - mm/vmstat.c:zoneinfo_show_print
```
```
In drivers/base/node.c (ffffffff819a2221)
Location: include/linux/vmstat.h:506
Inline: True
Inline callers:
  - drivers/base/node.c:node_read_vmstat
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
In mm/vmstat.c (ffffffff813931b4)
Location: include/linux/vmstat.h:500
Inline: True
Inline callers:
  - mm/vmstat.c:zoneinfo_show_print
```
```
In drivers/base/node.c (ffffffff81b141c1)
Location: include/linux/vmstat.h:500
Inline: True
Inline callers:
  - drivers/base/node.c:node_read_vmstat
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
In mm/vmstat.c (ffffffff813c5aef)
Location: include/linux/vmstat.h:506
Inline: True
Inline callers:
  - mm/vmstat.c:zoneinfo_show_print
```
```
In drivers/base/node.c (ffffffff81b62ef1)
Location: include/linux/vmstat.h:506
Inline: True
Inline callers:
  - drivers/base/node.c:node_read_vmstat
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
In mm/vmstat.c (ffffffff813f04ef)
Location: include/linux/vmstat.h:506
Inline: True
Inline callers:
  - mm/vmstat.c:zoneinfo_show_print
```
```
In drivers/base/node.c (ffffffff81bb6a01)
Location: include/linux/vmstat.h:506
Inline: True
Inline callers:
  - drivers/base/node.c:node_read_vmstat
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
