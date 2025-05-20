# Function: <code>mem_cgroup_flush_stats</code>

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
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void mem_cgroup_flush_stats();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff813538ec)
Location: mm/memcontrol.c:679
Inline: True
Inline callers:
  - mm/memcontrol.c:memory_numa_stat_show
  - mm/memcontrol.c:mem_cgroup_wb_stats
  - mm/memcontrol.c:__mem_cgroup_usage_unregister_event
  - mm/memcontrol.c:__mem_cgroup_usage_unregister_event
  - mm/memcontrol.c:__mem_cgroup_usage_register_event
  - mm/memcontrol.c:__mem_cgroup_usage_register_event
  - mm/memcontrol.c:__mem_cgroup_threshold
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:mem_cgroup_read_u64
  - mm/memcontrol.c:mem_cgroup_read_u64
  - mm/memcontrol.c:memory_stat_format
Direct callers:
  - mm/vmscan.c:shrink_node
  - mm/workingset.c:workingset_refault
```
**Symbols:**

```
ffffffff813563a0-ffffffff813563c1: mem_cgroup_flush_stats (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void mem_cgroup_flush_stats();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff813cb926)
Location: mm/memcontrol.c:647
Inline: True
Inline callers:
  - mm/memcontrol.c:memory_numa_stat_show
  - mm/memcontrol.c:mem_cgroup_wb_stats
  - mm/memcontrol.c:__mem_cgroup_usage_unregister_event
  - mm/memcontrol.c:__mem_cgroup_usage_unregister_event
  - mm/memcontrol.c:__mem_cgroup_usage_register_event
  - mm/memcontrol.c:__mem_cgroup_usage_register_event
  - mm/memcontrol.c:__mem_cgroup_threshold
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:mem_cgroup_read_u64
  - mm/memcontrol.c:mem_cgroup_read_u64
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:mem_cgroup_flush_stats_delayed
Direct callers:
  - mm/vmscan.c:shrink_node
```
**Symbols:**

```
ffffffff813cef70-ffffffff813cefa1: mem_cgroup_flush_stats (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void mem_cgroup_flush_stats();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81450636)
Location: mm/memcontrol.c:640
Inline: True
Inline callers:
  - mm/memcontrol.c:memory_numa_stat_show
  - mm/memcontrol.c:mem_cgroup_wb_stats
  - mm/memcontrol.c:__mem_cgroup_usage_unregister_event
  - mm/memcontrol.c:__mem_cgroup_threshold
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:mem_cgroup_flush_stats_delayed
Direct callers:
  - mm/vmscan.c:prepare_scan_count
```
**Symbols:**

```
ffffffff814540d0-ffffffff81454101: mem_cgroup_flush_stats (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void mem_cgroup_flush_stats();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81486096)
Location: mm/memcontrol.c:661
Inline: True
Inline callers:
  - mm/memcontrol.c:memory_numa_stat_show
  - mm/memcontrol.c:mem_cgroup_wb_stats
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:mem_cgroup_flush_stats_ratelimited
Direct callers:
  - mm/vmscan.c:prepare_scan_count
```
**Symbols:**

```
ffffffff81489e80-ffffffff81489eb1: mem_cgroup_flush_stats (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void mem_cgroup_flush_stats(struct mem_cgroup *memcg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/memcontrol.c (ffffffff814b4f65)
Location: mm/memcontrol.c:756
Inline: True
Inline callers:
  - mm/memcontrol.c:zswap_current_read
  - mm/memcontrol.c:memory_numa_stat_show
  - mm/memcontrol.c:mem_cgroup_wb_stats
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:mem_cgroup_flush_stats_ratelimited
Direct callers:
  - mm/vmscan.c:prepare_scan_control
  - mm/zswap.c:zswap_shrinker_count
  - mm/memcontrol.c:zswap_current_read
  - mm/memcontrol.c:memory_numa_stat_show
  - mm/memcontrol.c:mem_cgroup_wb_stats
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:mem_cgroup_flush_stats_ratelimited
```
**Symbols:**

```
ffffffff814b4140-ffffffff814b41c5: mem_cgroup_flush_stats.part.0 (STB_LOCAL)
ffffffff814b9650-ffffffff814b966f: mem_cgroup_flush_stats (STB_GLOBAL)
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
<details>
<summary>Changed between <code>6.5</code> and <code>6.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct mem_cgroup *memcg</code>
</li>
</ul>
</details>
</li>
</ul>
