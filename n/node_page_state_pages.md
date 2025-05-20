# Function: <code>node_page_state_pages</code>

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
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
long unsigned int node_page_state_pages(struct pglist_data *pgdat, enum node_stat_item item);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff8127ee08)
Location: mm/vmstat.c:1006
Inline: True
Inline callers:
  - mm/vmstat.c:zoneinfo_show_print
  - mm/vmstat.c:node_page_state
Direct callers:
  - mm/vmscan.c:node_reclaim
  - drivers/base/node.c:node_read_vmstat
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
```
**Symbols:**

```
ffffffff81280bb0-ffffffff81280bd4: node_page_state_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
long unsigned int node_page_state_pages(struct pglist_data *pgdat, enum node_stat_item item);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff81283fcb)
Location: mm/vmstat.c:1018
Inline: True
Inline callers:
  - mm/vmstat.c:zoneinfo_show_print
  - mm/vmstat.c:node_page_state
Direct callers:
  - mm/vmscan.c:node_reclaim
  - drivers/base/node.c:node_read_vmstat
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
```
**Symbols:**

```
ffffffff81285cb0-ffffffff81285cd1: node_page_state_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
long unsigned int node_page_state_pages(struct pglist_data *pgdat, enum node_stat_item item);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff812c26c9)
Location: mm/vmstat.c:1024
Inline: True
Inline callers:
  - mm/vmstat.c:zoneinfo_show_print
  - mm/vmstat.c:node_page_state
Direct callers:
  - mm/vmscan.c:node_reclaim
  - drivers/base/node.c:node_read_vmstat
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
```
**Symbols:**

```
ffffffff812c4f10-ffffffff812c4f31: node_page_state_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
long unsigned int node_page_state_pages(struct pglist_data *pgdat, enum node_stat_item item);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff8131f790)
Location: mm/vmstat.c:1025
Inline: True
Inline callers:
  - mm/vmstat.c:zoneinfo_show_print
  - mm/vmstat.c:node_page_state
Direct callers:
  - mm/vmscan.c:node_reclaim
  - mm/vmscan.c:__node_reclaim
  - drivers/base/node.c:node_read_vmstat
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
```
**Symbols:**

```
ffffffff81322450-ffffffff8132247b: node_page_state_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
long unsigned int node_page_state_pages(struct pglist_data *pgdat, enum node_stat_item item);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff813932fa)
Location: mm/vmstat.c:1012
Inline: True
Inline callers:
  - mm/vmstat.c:zoneinfo_show_print
  - mm/vmstat.c:node_page_state
Direct callers:
  - mm/vmscan.c:node_reclaim
  - mm/vmscan.c:__node_reclaim
  - drivers/base/node.c:node_read_vmstat
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
```
**Symbols:**

```
ffffffff813965f0-ffffffff8139663b: node_page_state_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
long unsigned int node_page_state_pages(struct pglist_data *pgdat, enum node_stat_item item);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff813c5c48)
Location: mm/vmstat.c:1013
Inline: True
Inline callers:
  - mm/vmstat.c:zoneinfo_show_print
  - mm/vmstat.c:node_page_state
Direct callers:
  - mm/vmscan.c:node_reclaim
  - mm/vmscan.c:__node_reclaim
  - drivers/base/node.c:node_read_vmstat
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
```
**Symbols:**

```
ffffffff813c9520-ffffffff813c956b: node_page_state_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
long unsigned int node_page_state_pages(struct pglist_data *pgdat, enum node_stat_item item);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff813f0648)
Location: mm/vmstat.c:1016
Inline: True
Inline callers:
  - mm/vmstat.c:zoneinfo_show_print
  - mm/vmstat.c:node_page_state
Direct callers:
  - mm/vmscan.c:node_reclaim
  - mm/vmscan.c:__node_reclaim
  - drivers/base/node.c:node_read_vmstat
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
```
**Symbols:**

```
ffffffff813f3eb0-ffffffff813f3efb: node_page_state_pages (STB_GLOBAL)
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
<b>Regular</b>
<ul>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
