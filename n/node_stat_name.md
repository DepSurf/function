# Function: <code>node_stat_name</code>

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
In mm/vmstat.c (ffffffff812745c6)
Location: include/linux/vmstat.h:405
Inline: True
Inline callers:
  - mm/vmstat.c:zoneinfo_show_print
```
```
In mm/memcontrol.c (ffffffff812f84a2)
Location: include/linux/vmstat.h:405
Inline: True
Inline callers:
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:memory_stat_format
```
```
In drivers/base/node.c (ffffffff817d76a7)
Location: include/linux/vmstat.h:405
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
In mm/vmstat.c (ffffffff8127ee19)
Location: include/linux/vmstat.h:422
Inline: True
Inline callers:
  - mm/vmstat.c:zoneinfo_show_print
```
```
In mm/memcontrol.c (ffffffff81303f4f)
Location: include/linux/vmstat.h:422
Inline: True
Inline callers:
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:memcg_stat_show
```
```
In drivers/base/node.c (ffffffff817ec0f2)
Location: include/linux/vmstat.h:422
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
In mm/vmstat.c (ffffffff81bd8d26)
Location: include/linux/vmstat.h:428
Inline: True
Inline callers:
  - mm/vmstat.c:vmstat_refresh
  - mm/vmstat.c:zoneinfo_show_print
```
```
In mm/memcontrol.c (ffffffff8130a0fb)
Location: include/linux/vmstat.h:428
Inline: True
Inline callers:
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:memcg_stat_show
```
```
In drivers/base/node.c (ffffffff817d090a)
Location: include/linux/vmstat.h:428
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
In mm/vmstat.c (ffffffff81cbab8a)
Location: include/linux/vmstat.h:441
Inline: True
Inline callers:
  - mm/vmstat.c:vmstat_refresh
  - mm/vmstat.c:zoneinfo_show_print
```
```
In mm/memcontrol.c (ffffffff813544ec)
Location: include/linux/vmstat.h:441
Inline: True
Inline callers:
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:memcg_stat_show
```
```
In drivers/base/node.c (ffffffff8185b29f)
Location: include/linux/vmstat.h:441
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
In mm/vmstat.c (ffffffff81e6c4a4)
Location: include/linux/vmstat.h:513
Inline: True
Inline callers:
  - mm/vmstat.c:vmstat_refresh
  - mm/vmstat.c:zoneinfo_show_print
```
```
In mm/memcontrol.c (ffffffff813cc1c6)
Location: include/linux/vmstat.h:513
Inline: True
Inline callers:
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:memcg_stat_show
```
```
In drivers/base/node.c (ffffffff819a2272)
Location: include/linux/vmstat.h:513
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
In mm/vmstat.c (ffffffff813968e6)
Location: include/linux/vmstat.h:507
Inline: True
Inline callers:
  - mm/vmstat.c:vmstat_refresh
  - mm/vmstat.c:zoneinfo_show_print
```
```
In mm/memcontrol.c (ffffffff81452883)
Location: include/linux/vmstat.h:507
Inline: True
Inline callers:
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:memcg_stat_show
```
```
In drivers/base/node.c (ffffffff81b14212)
Location: include/linux/vmstat.h:507
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
In mm/vmstat.c (ffffffff813c97f3)
Location: include/linux/vmstat.h:513
Inline: True
Inline callers:
  - mm/vmstat.c:vmstat_refresh
  - mm/vmstat.c:zoneinfo_show_print
```
```
In mm/memcontrol.c (ffffffff8148838e)
Location: include/linux/vmstat.h:513
Inline: True
```
```
In drivers/base/node.c (ffffffff81b62f3a)
Location: include/linux/vmstat.h:513
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
In mm/vmstat.c (ffffffff813f4181)
Location: include/linux/vmstat.h:513
Inline: True
Inline callers:
  - mm/vmstat.c:vmstat_refresh
  - mm/vmstat.c:zoneinfo_show_print
```
```
In mm/memcontrol.c (ffffffff814b64ec)
Location: include/linux/vmstat.h:513
Inline: True
```
```
In drivers/base/node.c (ffffffff81bb6a4a)
Location: include/linux/vmstat.h:513
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
