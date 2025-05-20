# Function: <code>sum_zone_numa_event_state</code>

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
<summary>In <code>5.15</code>: ✅</summary>

```c
long unsigned int sum_zone_numa_event_state(int node, enum numa_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff812c4ed0)
Location: mm/vmstat.c:1008
Inline: False
Direct callers:
  - drivers/base/node.c:node_read_vmstat
  - drivers/base/node.c:node_read_numastat
  - drivers/base/node.c:node_read_numastat
  - drivers/base/node.c:node_read_numastat
  - drivers/base/node.c:node_read_numastat
  - drivers/base/node.c:node_read_numastat
  - drivers/base/node.c:node_read_numastat
```
**Symbols:**

```
ffffffff812c4ed0-ffffffff812c4f0e: sum_zone_numa_event_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long unsigned int sum_zone_numa_event_state(int node, enum numa_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff81322400)
Location: mm/vmstat.c:1009
Inline: False
Direct callers:
  - drivers/base/node.c:node_read_vmstat
  - drivers/base/node.c:node_read_numastat
  - drivers/base/node.c:node_read_numastat
  - drivers/base/node.c:node_read_numastat
  - drivers/base/node.c:node_read_numastat
  - drivers/base/node.c:node_read_numastat
  - drivers/base/node.c:node_read_numastat
```
**Symbols:**

```
ffffffff81322400-ffffffff81322449: sum_zone_numa_event_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long unsigned int sum_zone_numa_event_state(int node, enum numa_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff81396590)
Location: mm/vmstat.c:996
Inline: False
Direct callers:
  - drivers/base/node.c:node_read_vmstat
  - drivers/base/node.c:node_read_numastat
  - drivers/base/node.c:node_read_numastat
  - drivers/base/node.c:node_read_numastat
  - drivers/base/node.c:node_read_numastat
  - drivers/base/node.c:node_read_numastat
  - drivers/base/node.c:node_read_numastat
```
**Symbols:**

```
ffffffff81396590-ffffffff813965d9: sum_zone_numa_event_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long unsigned int sum_zone_numa_event_state(int node, enum numa_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff813c9490)
Location: mm/vmstat.c:997
Inline: False
Direct callers:
  - drivers/base/node.c:node_read_vmstat
  - drivers/base/node.c:node_read_numastat
  - drivers/base/node.c:node_read_numastat
  - drivers/base/node.c:node_read_numastat
  - drivers/base/node.c:node_read_numastat
  - drivers/base/node.c:node_read_numastat
  - drivers/base/node.c:node_read_numastat
```
**Symbols:**

```
ffffffff813c9490-ffffffff813c9508: sum_zone_numa_event_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long unsigned int sum_zone_numa_event_state(int node, enum numa_stat_item item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff813f3e20)
Location: mm/vmstat.c:1000
Inline: False
Direct callers:
  - drivers/base/node.c:node_read_vmstat
  - drivers/base/node.c:node_read_numastat
  - drivers/base/node.c:node_read_numastat
  - drivers/base/node.c:node_read_numastat
  - drivers/base/node.c:node_read_numastat
  - drivers/base/node.c:node_read_numastat
  - drivers/base/node.c:node_read_numastat
```
**Symbols:**

```
ffffffff813f3e20-ffffffff813f3e98: sum_zone_numa_event_state (STB_GLOBAL)
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
