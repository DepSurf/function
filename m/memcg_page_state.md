# Function: <code>memcg_page_state</code>

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
<details>
<summary>In <code>4.13</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/vmscan.c (ffffffff811cfee7)
Location: include/linux/memcontrol.h:491
Inline: True
Inline callers:
  - mm/vmscan.c:snapshot_refaults
  - mm/vmscan.c:inactive_list_is_low
```
```
In mm/memcontrol.c (ffffffff8124047e)
Location: include/linux/memcontrol.h:491
Inline: True
Inline callers:
  - mm/memcontrol.c:memory_stat_show
  - mm/memcontrol.c:mem_cgroup_wb_stats
  - mm/memcontrol.c:mem_cgroup_wb_stats
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:memcg_stat_show
Direct callers:
  - mm/memcontrol.c:mem_cgroup_print_oom_info
```
**Symbols:**

```
ffffffff8123bc60-ffffffff8123bccf: memcg_page_state.isra.23 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/vmscan.c (ffffffff811e538d)
Location: include/linux/memcontrol.h:492
Inline: True
Inline callers:
  - mm/vmscan.c:snapshot_refaults
  - mm/vmscan.c:inactive_list_is_low
```
```
In mm/memcontrol.c (ffffffff812601b1)
Location: include/linux/memcontrol.h:492
Inline: True
Inline callers:
  - mm/memcontrol.c:memory_stat_show
  - mm/memcontrol.c:mem_cgroup_wb_stats
  - mm/memcontrol.c:mem_cgroup_wb_stats
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:memcg_stat_show
Direct callers:
  - mm/memcontrol.c:mem_cgroup_print_oom_info
```
**Symbols:**

```
ffffffff8125b580-ffffffff8125b5e3: memcg_page_state.isra.26 (STB_LOCAL)
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
In mm/vmscan.c (ffffffff81205ff5)
Location: include/linux/memcontrol.h:525
Inline: True
Inline callers:
  - mm/vmscan.c:snapshot_refaults
  - mm/vmscan.c:inactive_list_is_low
```
```
In mm/memcontrol.c (ffffffff81284240)
Location: include/linux/memcontrol.h:525
Inline: True
Inline callers:
  - mm/memcontrol.c:memory_stat_show
  - mm/memcontrol.c:mem_cgroup_wb_stats
  - mm/memcontrol.c:mem_cgroup_wb_stats
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:mem_cgroup_print_oom_info
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
In mm/vmscan.c (ffffffff812189c5)
Location: include/linux/memcontrol.h:565
Inline: True
Inline callers:
  - mm/vmscan.c:snapshot_refaults
  - mm/vmscan.c:inactive_list_is_low
```
```
In mm/memcontrol.c (ffffffff8129a90d)
Location: include/linux/memcontrol.h:565
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_wb_stats
  - mm/memcontrol.c:mem_cgroup_wb_stats
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:accumulate_memcg_tree
  - mm/memcontrol.c:mem_cgroup_print_oom_meminfo
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812afd75)
Location: include/linux/memcontrol.h:558
Inline: True
Inline callers:
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812c17e5)
Location: include/linux/memcontrol.h:594
Inline: True
Inline callers:
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812f700f)
Location: include/linux/memcontrol.h:571
Inline: True
Inline callers:
  - mm/memcontrol.c:__mem_cgroup_usage_unregister_event
  - mm/memcontrol.c:__mem_cgroup_usage_unregister_event
  - mm/memcontrol.c:__mem_cgroup_usage_unregister_event
  - mm/memcontrol.c:__mem_cgroup_usage_unregister_event
  - mm/memcontrol.c:__mem_cgroup_usage_unregister_event
  - mm/memcontrol.c:__mem_cgroup_usage_register_event
  - mm/memcontrol.c:__mem_cgroup_usage_register_event
  - mm/memcontrol.c:__mem_cgroup_usage_register_event
  - mm/memcontrol.c:__mem_cgroup_usage_register_event
  - mm/memcontrol.c:__mem_cgroup_usage_register_event
  - mm/memcontrol.c:__mem_cgroup_threshold
  - mm/memcontrol.c:__mem_cgroup_threshold
  - mm/memcontrol.c:__mem_cgroup_threshold
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:mem_cgroup_read_u64
  - mm/memcontrol.c:mem_cgroup_read_u64
  - mm/memcontrol.c:mem_cgroup_read_u64
  - mm/memcontrol.c:mem_cgroup_read_u64
  - mm/memcontrol.c:mem_cgroup_read_u64
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff8130246f)
Location: include/linux/memcontrol.h:889
Inline: True
Inline callers:
  - mm/memcontrol.c:__mem_cgroup_usage_unregister_event
  - mm/memcontrol.c:__mem_cgroup_usage_unregister_event
  - mm/memcontrol.c:__mem_cgroup_usage_unregister_event
  - mm/memcontrol.c:__mem_cgroup_usage_unregister_event
  - mm/memcontrol.c:__mem_cgroup_usage_unregister_event
  - mm/memcontrol.c:__mem_cgroup_usage_register_event
  - mm/memcontrol.c:__mem_cgroup_usage_register_event
  - mm/memcontrol.c:__mem_cgroup_usage_register_event
  - mm/memcontrol.c:__mem_cgroup_usage_register_event
  - mm/memcontrol.c:__mem_cgroup_usage_register_event
  - mm/memcontrol.c:__mem_cgroup_threshold
  - mm/memcontrol.c:__mem_cgroup_threshold
  - mm/memcontrol.c:__mem_cgroup_threshold
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:mem_cgroup_read_u64
  - mm/memcontrol.c:mem_cgroup_read_u64
  - mm/memcontrol.c:mem_cgroup_read_u64
  - mm/memcontrol.c:mem_cgroup_read_u64
  - mm/memcontrol.c:mem_cgroup_read_u64
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff8130fd9d)
Location: mm/memcontrol.c:650
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_wb_stats
  - mm/memcontrol.c:mem_cgroup_wb_stats
  - mm/memcontrol.c:mem_cgroup_wb_stats
  - mm/memcontrol.c:mem_cgroup_wb_stats
  - mm/memcontrol.c:__mem_cgroup_usage_unregister_event
  - mm/memcontrol.c:__mem_cgroup_usage_unregister_event
  - mm/memcontrol.c:__mem_cgroup_usage_unregister_event
  - mm/memcontrol.c:__mem_cgroup_usage_unregister_event
  - mm/memcontrol.c:__mem_cgroup_usage_unregister_event
  - mm/memcontrol.c:__mem_cgroup_usage_register_event
  - mm/memcontrol.c:__mem_cgroup_usage_register_event
  - mm/memcontrol.c:__mem_cgroup_usage_register_event
  - mm/memcontrol.c:__mem_cgroup_usage_register_event
  - mm/memcontrol.c:__mem_cgroup_usage_register_event
  - mm/memcontrol.c:__mem_cgroup_threshold
  - mm/memcontrol.c:__mem_cgroup_threshold
  - mm/memcontrol.c:__mem_cgroup_threshold
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:mem_cgroup_read_u64
  - mm/memcontrol.c:mem_cgroup_read_u64
  - mm/memcontrol.c:mem_cgroup_read_u64
  - mm/memcontrol.c:mem_cgroup_read_u64
  - mm/memcontrol.c:mem_cgroup_read_u64
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
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
In mm/memcontrol.c (ffffffff8135b059)
Location: include/linux/memcontrol.h:967
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_wb_stats
  - mm/memcontrol.c:mem_cgroup_wb_stats
  - mm/memcontrol.c:mem_cgroup_wb_stats
  - mm/memcontrol.c:mem_cgroup_wb_stats
  - mm/memcontrol.c:__mem_cgroup_usage_unregister_event
  - mm/memcontrol.c:__mem_cgroup_usage_unregister_event
  - mm/memcontrol.c:__mem_cgroup_usage_unregister_event
  - mm/memcontrol.c:__mem_cgroup_usage_unregister_event
  - mm/memcontrol.c:__mem_cgroup_usage_unregister_event
  - mm/memcontrol.c:__mem_cgroup_usage_register_event
  - mm/memcontrol.c:__mem_cgroup_usage_register_event
  - mm/memcontrol.c:__mem_cgroup_usage_register_event
  - mm/memcontrol.c:__mem_cgroup_usage_register_event
  - mm/memcontrol.c:__mem_cgroup_usage_register_event
  - mm/memcontrol.c:__mem_cgroup_threshold
  - mm/memcontrol.c:__mem_cgroup_threshold
  - mm/memcontrol.c:__mem_cgroup_threshold
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:mem_cgroup_read_u64
  - mm/memcontrol.c:mem_cgroup_read_u64
  - mm/memcontrol.c:mem_cgroup_read_u64
  - mm/memcontrol.c:mem_cgroup_read_u64
  - mm/memcontrol.c:mem_cgroup_read_u64
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
```
```
In fs/fs-writeback.c (ffffffff813b0768)
Location: include/linux/memcontrol.h:967
Inline: True
Inline callers:
  - fs/fs-writeback.c:cgroup_writeback_by_id
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
In mm/memcontrol.c (ffffffff813c98e5)
Location: include/linux/memcontrol.h:979
Inline: True
Inline callers:
  - mm/memcontrol.c:zswap_current_read
  - mm/memcontrol.c:obj_cgroup_may_zswap
  - mm/memcontrol.c:mem_cgroup_wb_stats
  - mm/memcontrol.c:mem_cgroup_wb_stats
  - mm/memcontrol.c:mem_cgroup_wb_stats
  - mm/memcontrol.c:mem_cgroup_wb_stats
  - mm/memcontrol.c:__mem_cgroup_usage_unregister_event
  - mm/memcontrol.c:__mem_cgroup_usage_unregister_event
  - mm/memcontrol.c:__mem_cgroup_usage_unregister_event
  - mm/memcontrol.c:__mem_cgroup_usage_unregister_event
  - mm/memcontrol.c:__mem_cgroup_usage_unregister_event
  - mm/memcontrol.c:__mem_cgroup_usage_register_event
  - mm/memcontrol.c:__mem_cgroup_usage_register_event
  - mm/memcontrol.c:__mem_cgroup_usage_register_event
  - mm/memcontrol.c:__mem_cgroup_usage_register_event
  - mm/memcontrol.c:__mem_cgroup_usage_register_event
  - mm/memcontrol.c:__mem_cgroup_threshold
  - mm/memcontrol.c:__mem_cgroup_threshold
  - mm/memcontrol.c:__mem_cgroup_threshold
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:mem_cgroup_read_u64
  - mm/memcontrol.c:mem_cgroup_read_u64
  - mm/memcontrol.c:mem_cgroup_read_u64
  - mm/memcontrol.c:mem_cgroup_read_u64
  - mm/memcontrol.c:mem_cgroup_read_u64
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
```
```
In fs/fs-writeback.c (ffffffff8143555a)
Location: include/linux/memcontrol.h:979
Inline: True
Inline callers:
  - fs/fs-writeback.c:cgroup_writeback_by_id
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
long unsigned int memcg_page_state(struct mem_cgroup *memcg, int idx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff8144eef5)
Location: mm/memcontrol.c:725
Inline: True
Inline callers:
  - mm/memcontrol.c:zswap_current_read
  - mm/memcontrol.c:obj_cgroup_may_zswap
  - mm/memcontrol.c:mem_cgroup_wb_stats
  - mm/memcontrol.c:mem_cgroup_wb_stats
  - mm/memcontrol.c:mem_cgroup_wb_stats
  - mm/memcontrol.c:mem_cgroup_wb_stats
  - mm/memcontrol.c:__mem_cgroup_usage_unregister_event
  - mm/memcontrol.c:__mem_cgroup_usage_unregister_event
  - mm/memcontrol.c:__mem_cgroup_usage_unregister_event
  - mm/memcontrol.c:__mem_cgroup_threshold
  - mm/memcontrol.c:__mem_cgroup_threshold
  - mm/memcontrol.c:__mem_cgroup_threshold
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:memcg_numa_stat_show
Direct callers:
  - fs/fs-writeback.c:cgroup_writeback_by_id
```
**Symbols:**

```
ffffffff81454180-ffffffff814541d1: memcg_page_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
long unsigned int memcg_page_state(struct mem_cgroup *memcg, int idx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81484925)
Location: mm/memcontrol.c:750
Inline: True
Inline callers:
  - mm/memcontrol.c:zswap_current_read
  - mm/memcontrol.c:obj_cgroup_may_zswap
  - mm/memcontrol.c:mem_cgroup_wb_stats
  - mm/memcontrol.c:mem_cgroup_wb_stats
  - mm/memcontrol.c:mem_cgroup_wb_stats
  - mm/memcontrol.c:mem_cgroup_wb_stats
  - mm/memcontrol.c:memcg_numa_stat_show
Direct callers:
  - fs/fs-writeback.c:cgroup_writeback_by_id
```
**Symbols:**

```
ffffffff81489f30-ffffffff81489f81: memcg_page_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
long unsigned int memcg_page_state(struct mem_cgroup *memcg, int idx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff814b4f74)
Location: mm/memcontrol.c:785
Inline: True
Inline callers:
  - mm/memcontrol.c:zswap_current_read
  - mm/memcontrol.c:obj_cgroup_may_zswap
  - mm/memcontrol.c:mem_cgroup_wb_stats
  - mm/memcontrol.c:mem_cgroup_wb_stats
  - mm/memcontrol.c:mem_cgroup_wb_stats
  - mm/memcontrol.c:mem_cgroup_wb_stats
  - mm/memcontrol.c:memcg_numa_stat_show
Direct callers:
  - mm/zswap.c:zswap_shrinker_count
  - mm/zswap.c:zswap_shrinker_count
  - fs/fs-writeback.c:cgroup_writeback_by_id
```
**Symbols:**

```
ffffffff814b96d0-ffffffff814b9721: memcg_page_state (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffff800010362a08)
Location: include/linux/memcontrol.h:594
Inline: True
Inline callers:
  - mm/memcontrol.c:__mem_cgroup_usage_unregister_event
  - mm/memcontrol.c:__mem_cgroup_usage_unregister_event
  - mm/memcontrol.c:__mem_cgroup_usage_register_event
  - mm/memcontrol.c:__mem_cgroup_usage_register_event
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:mem_cgroup_read_u64
  - mm/memcontrol.c:mem_cgroup_read_u64
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (c05551b8)
Location: include/linux/memcontrol.h:594
Inline: True
Inline callers:
  - mm/memcontrol.c:__mem_cgroup_usage_unregister_event
  - mm/memcontrol.c:__mem_cgroup_usage_unregister_event
  - mm/memcontrol.c:__mem_cgroup_usage_register_event
  - mm/memcontrol.c:__mem_cgroup_usage_register_event
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:mem_cgroup_read_u64
  - mm/memcontrol.c:mem_cgroup_read_u64
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (c00000000045008c)
Location: include/linux/memcontrol.h:594
Inline: True
Inline callers:
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffe0002422dc)
Location: include/linux/memcontrol.h:594
Inline: True
Inline callers:
  - mm/memcontrol.c:__mem_cgroup_usage_unregister_event
  - mm/memcontrol.c:__mem_cgroup_usage_unregister_event
  - mm/memcontrol.c:__mem_cgroup_usage_register_event
  - mm/memcontrol.c:__mem_cgroup_usage_register_event
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:mem_cgroup_read_u64
  - mm/memcontrol.c:mem_cgroup_read_u64
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812b9dc5)
Location: include/linux/memcontrol.h:594
Inline: True
Inline callers:
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812ab055)
Location: include/linux/memcontrol.h:594
Inline: True
Inline callers:
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812b7bd5)
Location: include/linux/memcontrol.h:594
Inline: True
Inline callers:
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812c84c5)
Location: include/linux/memcontrol.h:594
Inline: True
Inline callers:
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
  - mm/memcontrol.c:memory_stat_format
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
