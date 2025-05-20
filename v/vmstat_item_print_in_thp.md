# Function: <code>vmstat_item_print_in_thp</code>

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
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (0)
Location: include/linux/mmzone.h:220
Inline: True
```
```
In drivers/base/node.c (0)
Location: include/linux/mmzone.h:220
Inline: True
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
In mm/vmstat.c (0)
Location: include/linux/mmzone.h:221
Inline: True
```
```
In drivers/base/node.c (0)
Location: include/linux/mmzone.h:221
Inline: True
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
In mm/vmstat.c (ffffffff8132130a)
Location: include/linux/mmzone.h:233
Inline: True
Inline callers:
  - mm/vmstat.c:vmstat_start
  - mm/vmstat.c:zoneinfo_show_print
```
```
In drivers/base/node.c (ffffffff819a2257)
Location: include/linux/mmzone.h:233
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
In mm/vmstat.c (ffffffff813952ca)
Location: include/linux/mmzone.h:221
Inline: True
Inline callers:
  - mm/vmstat.c:vmstat_start
  - mm/vmstat.c:zoneinfo_show_print
```
```
In drivers/base/node.c (ffffffff81b141f7)
Location: include/linux/mmzone.h:221
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
In mm/vmstat.c (ffffffff813c7eea)
Location: include/linux/mmzone.h:218
Inline: True
Inline callers:
  - mm/vmstat.c:vmstat_start
  - mm/vmstat.c:zoneinfo_show_print
```
```
In drivers/base/node.c (ffffffff81b62f32)
Location: include/linux/mmzone.h:218
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
In mm/vmstat.c (ffffffff813f28f9)
Location: include/linux/mmzone.h:225
Inline: True
Inline callers:
  - mm/vmstat.c:vmstat_start
  - mm/vmstat.c:zoneinfo_show_print
```
```
In drivers/base/node.c (ffffffff81bb6a42)
Location: include/linux/mmzone.h:225
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
