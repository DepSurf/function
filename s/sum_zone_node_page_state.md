# Function: <code>sum_zone_node_page_state</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
long unsigned int sum_zone_node_page_state(int node, enum zone_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff811c70a0)
Location: mm/vmstat.c:791
Inline: False
Direct callers:
  - mm/page_alloc.c:si_meminfo_node
  - mm/vmscan.c:node_reclaim
  - mm/vmscan.c:shrink_node_memcg
  - drivers/base/node.c:node_read_vmstat
  - drivers/base/node.c:node_read_numastat
  - drivers/base/node.c:node_read_numastat
  - drivers/base/node.c:node_read_numastat
  - drivers/base/node.c:node_read_numastat
  - drivers/base/node.c:node_read_numastat
  - drivers/base/node.c:node_read_numastat
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
```
**Symbols:**

```
ffffffff811c70a0-ffffffff811c70e9: sum_zone_node_page_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
long unsigned int sum_zone_node_page_state(int node, enum zone_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff811d71c0)
Location: mm/vmstat.c:791
Inline: False
Direct callers:
  - mm/page_alloc.c:si_meminfo_node
  - mm/vmscan.c:node_reclaim
  - mm/vmscan.c:shrink_node_memcg
  - drivers/base/node.c:node_read_vmstat
  - drivers/base/node.c:node_read_numastat
  - drivers/base/node.c:node_read_numastat
  - drivers/base/node.c:node_read_numastat
  - drivers/base/node.c:node_read_numastat
  - drivers/base/node.c:node_read_numastat
  - drivers/base/node.c:node_read_numastat
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
```
**Symbols:**

```
ffffffff811d71c0-ffffffff811d7209: sum_zone_node_page_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
long unsigned int sum_zone_node_page_state(int node, enum zone_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff811e0020)
Location: mm/vmstat.c:791
Inline: False
Direct callers:
  - mm/page_alloc.c:si_meminfo_node
  - mm/vmscan.c:shrink_node_memcg
  - drivers/base/node.c:node_read_vmstat
  - drivers/base/node.c:node_read_numastat
  - drivers/base/node.c:node_read_numastat
  - drivers/base/node.c:node_read_numastat
  - drivers/base/node.c:node_read_numastat
  - drivers/base/node.c:node_read_numastat
  - drivers/base/node.c:node_read_numastat
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
```
**Symbols:**

```
ffffffff811e0020-ffffffff811e0069: sum_zone_node_page_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
long unsigned int sum_zone_node_page_state(int node, enum zone_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff811f5f10)
Location: mm/vmstat.c:958
Inline: False
Direct callers:
  - mm/page_alloc.c:si_meminfo_node
  - mm/vmscan.c:shrink_node_memcg
  - drivers/base/node.c:node_read_vmstat
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
```
**Symbols:**

```
ffffffff811f5f10-ffffffff811f5f59: sum_zone_node_page_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
long unsigned int sum_zone_node_page_state(int node, enum zone_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff81217190)
Location: mm/vmstat.c:958
Inline: False
Direct callers:
  - mm/page_alloc.c:si_meminfo_node
  - mm/vmscan.c:shrink_node_memcg
  - drivers/base/node.c:node_read_vmstat
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
```
**Symbols:**

```
ffffffff81217190-ffffffff812171d4: sum_zone_node_page_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
long unsigned int sum_zone_node_page_state(int node, enum zone_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff8122a0a0)
Location: mm/vmstat.c:958
Inline: False
Direct callers:
  - mm/page_alloc.c:si_meminfo_node
  - mm/vmscan.c:shrink_node_memcg
  - drivers/base/node.c:node_read_vmstat
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
```
**Symbols:**

```
ffffffff8122a0a0-ffffffff8122a0e4: sum_zone_node_page_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
long unsigned int sum_zone_node_page_state(int node, enum zone_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff81239d40)
Location: mm/vmstat.c:959
Inline: False
Direct callers:
  - mm/vmscan.c:get_scan_count
  - mm/page_alloc.c:si_meminfo_node
  - drivers/base/node.c:node_read_vmstat
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
```
**Symbols:**

```
ffffffff81239d40-ffffffff81239d88: sum_zone_node_page_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long unsigned int sum_zone_node_page_state(int node, enum zone_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff81248040)
Location: mm/vmstat.c:959
Inline: False
Direct callers:
  - mm/vmscan.c:get_scan_count
  - mm/page_alloc.c:si_meminfo_node
  - drivers/base/node.c:node_read_vmstat
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
```
**Symbols:**

```
ffffffff81248040-ffffffff81248088: sum_zone_node_page_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long unsigned int sum_zone_node_page_state(int node, enum zone_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff812761b0)
Location: mm/vmstat.c:959
Inline: False
Direct callers:
  - mm/vmscan.c:shrink_node
  - mm/page_alloc.c:si_meminfo_node
  - drivers/base/node.c:node_read_vmstat
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
```
**Symbols:**

```
ffffffff812761b0-ffffffff812761f8: sum_zone_node_page_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long unsigned int sum_zone_node_page_state(int node, enum zone_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff81280ab0)
Location: mm/vmstat.c:973
Inline: False
Direct callers:
  - mm/vmscan.c:shrink_node
  - mm/page_alloc.c:si_meminfo_node
  - drivers/base/node.c:node_read_vmstat
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
```
**Symbols:**

```
ffffffff81280ab0-ffffffff81280af8: sum_zone_node_page_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long unsigned int sum_zone_node_page_state(int node, enum zone_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff81285bb0)
Location: mm/vmstat.c:985
Inline: False
Direct callers:
  - mm/vmscan.c:shrink_node
  - mm/page_alloc.c:si_meminfo_node
  - drivers/base/node.c:node_read_vmstat
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
```
**Symbols:**

```
ffffffff81285bb0-ffffffff81285bf8: sum_zone_node_page_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long unsigned int sum_zone_node_page_state(int node, enum zone_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff812c4e50)
Location: mm/vmstat.c:994
Inline: False
Direct callers:
  - mm/vmscan.c:shrink_node
  - mm/page_alloc.c:si_meminfo_node
  - drivers/base/node.c:node_read_vmstat
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
```
**Symbols:**

```
ffffffff812c4e50-ffffffff812c4ec6: sum_zone_node_page_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long unsigned int sum_zone_node_page_state(int node, enum zone_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff81322380)
Location: mm/vmstat.c:995
Inline: False
Direct callers:
  - mm/vmscan.c:shrink_node
  - mm/page_alloc.c:si_meminfo_node
  - drivers/base/node.c:node_read_vmstat
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
```
**Symbols:**

```
ffffffff81322380-ffffffff81322400: sum_zone_node_page_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long unsigned int sum_zone_node_page_state(int node, enum zone_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff81396500)
Location: mm/vmstat.c:982
Inline: False
Direct callers:
  - mm/vmscan.c:prepare_scan_count
  - mm/page_alloc.c:si_meminfo_node
  - drivers/base/node.c:node_read_vmstat
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
```
**Symbols:**

```
ffffffff81396500-ffffffff81396580: sum_zone_node_page_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long unsigned int sum_zone_node_page_state(int node, enum zone_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff813c93f0)
Location: mm/vmstat.c:983
Inline: False
Direct callers:
  - mm/vmscan.c:prepare_scan_count
  - mm/show_mem.c:si_meminfo_node
  - drivers/base/node.c:node_read_vmstat
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
```
**Symbols:**

```
ffffffff813c93f0-ffffffff813c9471: sum_zone_node_page_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long unsigned int sum_zone_node_page_state(int node, enum zone_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff813f3d80)
Location: mm/vmstat.c:986
Inline: False
Direct callers:
  - mm/vmscan.c:prepare_scan_control
  - mm/show_mem.c:si_meminfo_node
  - drivers/base/node.c:node_read_vmstat
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
```
**Symbols:**

```
ffffffff813f3d80-ffffffff813f3e01: sum_zone_node_page_state (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
long unsigned int sum_zone_node_page_state(int node, enum zone_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffff8000102dca08)
Location: mm/vmstat.c:959
Inline: False
Direct callers:
  - mm/vmscan.c:get_scan_count
  - mm/page_alloc.c:si_meminfo_node
  - drivers/base/node.c:node_read_vmstat
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
```
**Symbols:**

```
ffff8000102dca08-ffff8000102dca78: sum_zone_node_page_state (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long unsigned int sum_zone_node_page_state(int node, enum zone_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (c00000000039c5e0)
Location: mm/vmstat.c:959
Inline: False
Direct callers:
  - mm/vmscan.c:get_scan_count
  - mm/page_alloc.c:si_meminfo_node
  - drivers/base/node.c:node_read_vmstat
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
```
**Symbols:**

```
c00000000039c5e0-c00000000039c648: sum_zone_node_page_state (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
long unsigned int sum_zone_node_page_state(int node, enum zone_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff81240690)
Location: mm/vmstat.c:959
Inline: False
Direct callers:
  - mm/vmscan.c:get_scan_count
  - mm/page_alloc.c:si_meminfo_node
  - drivers/base/node.c:node_read_vmstat
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
```
**Symbols:**

```
ffffffff81240690-ffffffff812406d8: sum_zone_node_page_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long unsigned int sum_zone_node_page_state(int node, enum zone_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff81233690)
Location: mm/vmstat.c:959
Inline: False
Direct callers:
  - mm/vmscan.c:get_scan_count
  - mm/page_alloc.c:si_meminfo_node
  - drivers/base/node.c:node_read_vmstat
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
```
**Symbols:**

```
ffffffff81233690-ffffffff812336d8: sum_zone_node_page_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long unsigned int sum_zone_node_page_state(int node, enum zone_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff8123e430)
Location: mm/vmstat.c:959
Inline: False
Direct callers:
  - mm/vmscan.c:get_scan_count
  - mm/page_alloc.c:si_meminfo_node
  - drivers/base/node.c:node_read_vmstat
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
```
**Symbols:**

```
ffffffff8123e430-ffffffff8123e478: sum_zone_node_page_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long unsigned int sum_zone_node_page_state(int node, enum zone_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff8124db60)
Location: mm/vmstat.c:959
Inline: False
Direct callers:
  - mm/vmscan.c:get_scan_count
  - mm/page_alloc.c:si_meminfo_node
  - drivers/base/node.c:node_read_vmstat
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
  - drivers/base/node.c:node_read_meminfo
```
**Symbols:**

```
ffffffff8124db60-ffffffff8124dba8: sum_zone_node_page_state (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
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
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
