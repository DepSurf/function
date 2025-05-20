# Function: <code>mem_cgroup_iter</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct mem_cgroup *mem_cgroup_iter(struct mem_cgroup *root, struct mem_cgroup *prev, struct mem_cgroup_reclaim_cookie *reclaim);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff811fc800)
Location: mm/memcontrol.c:871
Inline: False
Direct callers:
  - mm/vmscan.c:drop_slab_node
  - mm/vmscan.c:shrink_zone
  - mm/vmscan.c:shrink_zone
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:tree_stat
  - mm/memcontrol.c:tree_stat
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:mem_cgroup_count_children
  - mm/memcontrol.c:mem_cgroup_count_children
  - mm/memcontrol.c:mem_cgroup_unmark_under_oom
  - mm/memcontrol.c:mem_cgroup_unmark_under_oom
  - mm/memcontrol.c:mem_cgroup_out_of_memory
  - mm/memcontrol.c:mem_cgroup_out_of_memory
  - mm/memcontrol.c:mem_cgroup_print_oom_info
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
```
**Symbols:**

```
ffffffff811fc800-ffffffff811fcb82: mem_cgroup_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct mem_cgroup *mem_cgroup_iter(struct mem_cgroup *root, struct mem_cgroup *prev, struct mem_cgroup_reclaim_cookie *reclaim);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81220450)
Location: mm/memcontrol.c:764
Inline: False
Direct callers:
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:drop_slab_node
  - mm/memcontrol.c:memory_stat_show
  - mm/memcontrol.c:memory_stat_show
  - mm/memcontrol.c:memory_stat_show
  - mm/memcontrol.c:memory_stat_show
  - mm/memcontrol.c:memory_stat_show
  - mm/memcontrol.c:memory_stat_show
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
  - mm/memcontrol.c:mem_cgroup_unmark_under_oom
  - mm/memcontrol.c:mem_cgroup_unmark_under_oom
  - mm/memcontrol.c:mem_cgroup_out_of_memory
  - mm/memcontrol.c:mem_cgroup_out_of_memory
  - mm/memcontrol.c:mem_cgroup_count_children
  - mm/memcontrol.c:mem_cgroup_count_children
  - mm/memcontrol.c:mem_cgroup_print_oom_info
  - mm/memcontrol.c:mem_cgroup_print_oom_info
```
**Symbols:**

```
ffffffff81220450-ffffffff8122071d: mem_cgroup_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct mem_cgroup *mem_cgroup_iter(struct mem_cgroup *root, struct mem_cgroup *prev, struct mem_cgroup_reclaim_cookie *reclaim);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81232bb0)
Location: mm/memcontrol.c:766
Inline: False
Direct callers:
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:drop_slab_node
  - mm/memcontrol.c:memory_stat_show
  - mm/memcontrol.c:memory_stat_show
  - mm/memcontrol.c:memory_stat_show
  - mm/memcontrol.c:memory_stat_show
  - mm/memcontrol.c:memory_stat_show
  - mm/memcontrol.c:memory_stat_show
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
  - mm/memcontrol.c:mem_cgroup_unmark_under_oom
  - mm/memcontrol.c:mem_cgroup_unmark_under_oom
  - mm/memcontrol.c:mem_cgroup_count_children
  - mm/memcontrol.c:mem_cgroup_count_children
  - mm/memcontrol.c:mem_cgroup_print_oom_info
  - mm/memcontrol.c:mem_cgroup_print_oom_info
  - mm/memcontrol.c:mem_cgroup_scan_tasks
  - mm/memcontrol.c:mem_cgroup_scan_tasks
```
**Symbols:**

```
ffffffff81232bb0-ffffffff81232ea5: mem_cgroup_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct mem_cgroup *mem_cgroup_iter(struct mem_cgroup *root, struct mem_cgroup *prev, struct mem_cgroup_reclaim_cookie *reclaim);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff8123e3d0)
Location: mm/memcontrol.c:736
Inline: False
Direct callers:
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:snapshot_refaults
  - mm/vmscan.c:snapshot_refaults
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:drop_slab_node
  - mm/memcontrol.c:memory_stat_show
  - mm/memcontrol.c:memory_stat_show
  - mm/memcontrol.c:memory_stat_show
  - mm/memcontrol.c:memory_stat_show
  - mm/memcontrol.c:memory_stat_show
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
  - mm/memcontrol.c:mem_cgroup_unmark_under_oom
  - mm/memcontrol.c:mem_cgroup_unmark_under_oom
  - mm/memcontrol.c:mem_cgroup_count_children
  - mm/memcontrol.c:mem_cgroup_count_children
  - mm/memcontrol.c:mem_cgroup_print_oom_info
  - mm/memcontrol.c:mem_cgroup_print_oom_info
  - mm/memcontrol.c:mem_cgroup_scan_tasks
  - mm/memcontrol.c:mem_cgroup_scan_tasks
```
**Symbols:**

```
ffffffff8123e3d0-ffffffff8123e6b3: mem_cgroup_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct mem_cgroup *mem_cgroup_iter(struct mem_cgroup *root, struct mem_cgroup *prev, struct mem_cgroup_reclaim_cookie *reclaim);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff8125df70)
Location: mm/memcontrol.c:750
Inline: False
Direct callers:
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:snapshot_refaults
  - mm/vmscan.c:snapshot_refaults
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:drop_slab_node
  - mm/memcontrol.c:memory_stat_show
  - mm/memcontrol.c:memory_stat_show
  - mm/memcontrol.c:memory_stat_show
  - mm/memcontrol.c:memory_stat_show
  - mm/memcontrol.c:memory_stat_show
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
  - mm/memcontrol.c:mem_cgroup_unmark_under_oom
  - mm/memcontrol.c:mem_cgroup_unmark_under_oom
  - mm/memcontrol.c:mem_cgroup_count_children
  - mm/memcontrol.c:mem_cgroup_count_children
  - mm/memcontrol.c:mem_cgroup_print_oom_info
  - mm/memcontrol.c:mem_cgroup_print_oom_info
  - mm/memcontrol.c:mem_cgroup_scan_tasks
  - mm/memcontrol.c:mem_cgroup_scan_tasks
```
**Symbols:**

```
ffffffff8125df70-ffffffff8125e25e: mem_cgroup_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct mem_cgroup *mem_cgroup_iter(struct mem_cgroup *root, struct mem_cgroup *prev, struct mem_cgroup_reclaim_cookie *reclaim);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81282200)
Location: mm/memcontrol.c:721
Inline: False
Direct callers:
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:snapshot_refaults
  - mm/vmscan.c:snapshot_refaults
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:drop_slab_node
  - mm/memcontrol.c:memory_stat_show
  - mm/memcontrol.c:memory_stat_show
  - mm/memcontrol.c:memory_stat_show
  - mm/memcontrol.c:memory_stat_show
  - mm/memcontrol.c:memory_stat_show
  - mm/memcontrol.c:memory_stat_show
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:memcg_hotplug_cpu_dead
  - mm/memcontrol.c:memcg_hotplug_cpu_dead
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
  - mm/memcontrol.c:mem_cgroup_unmark_under_oom
  - mm/memcontrol.c:mem_cgroup_unmark_under_oom
  - mm/memcontrol.c:mem_cgroup_print_oom_info
  - mm/memcontrol.c:mem_cgroup_print_oom_info
  - mm/memcontrol.c:mem_cgroup_scan_tasks
  - mm/memcontrol.c:mem_cgroup_scan_tasks
```
**Symbols:**

```
ffffffff81282200-ffffffff812824f2: mem_cgroup_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct mem_cgroup *mem_cgroup_iter(struct mem_cgroup *root, struct mem_cgroup *prev, struct mem_cgroup_reclaim_cookie *reclaim);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812963e0)
Location: mm/memcontrol.c:910
Inline: False
Direct callers:
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:snapshot_refaults
  - mm/vmscan.c:snapshot_refaults
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:drop_slab_node
  - mm/vmscan.c:drop_slab_node
  - mm/memcontrol.c:mem_cgroup_oom_notify
  - mm/memcontrol.c:mem_cgroup_oom_notify
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:accumulate_memcg_tree
  - mm/memcontrol.c:accumulate_memcg_tree
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:memcg_hotplug_cpu_dead
  - mm/memcontrol.c:memcg_hotplug_cpu_dead
  - mm/memcontrol.c:mem_cgroup_unmark_under_oom
  - mm/memcontrol.c:mem_cgroup_unmark_under_oom
  - mm/memcontrol.c:mem_cgroup_mark_under_oom
  - mm/memcontrol.c:mem_cgroup_mark_under_oom
  - mm/memcontrol.c:mem_cgroup_oom_unlock
  - mm/memcontrol.c:mem_cgroup_oom_unlock
  - mm/memcontrol.c:mem_cgroup_oom_trylock
  - mm/memcontrol.c:mem_cgroup_oom_trylock
  - mm/memcontrol.c:mem_cgroup_oom_trylock
  - mm/memcontrol.c:mem_cgroup_oom_trylock
  - mm/memcontrol.c:mem_cgroup_print_oom_meminfo
  - mm/memcontrol.c:mem_cgroup_print_oom_meminfo
  - mm/memcontrol.c:mem_cgroup_scan_tasks
  - mm/memcontrol.c:mem_cgroup_scan_tasks
  - mm/memcontrol.c:memcg_expand_shrinker_maps
  - mm/memcontrol.c:memcg_expand_shrinker_maps
```
**Symbols:**

```
ffffffff812963e0-ffffffff812966a0: mem_cgroup_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct mem_cgroup *mem_cgroup_iter(struct mem_cgroup *root, struct mem_cgroup *prev, struct mem_cgroup_reclaim_cookie *reclaim);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812b2f20)
Location: mm/memcontrol.c:1027
Inline: False
Direct callers:
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:snapshot_refaults
  - mm/vmscan.c:snapshot_refaults
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:drop_slab_node
  - mm/vmscan.c:drop_slab_node
  - mm/memcontrol.c:mem_cgroup_oom_notify
  - mm/memcontrol.c:mem_cgroup_oom_notify
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:memcg_hotplug_cpu_dead
  - mm/memcontrol.c:memcg_hotplug_cpu_dead
  - mm/memcontrol.c:mem_cgroup_unmark_under_oom
  - mm/memcontrol.c:mem_cgroup_unmark_under_oom
  - mm/memcontrol.c:mem_cgroup_mark_under_oom
  - mm/memcontrol.c:mem_cgroup_mark_under_oom
  - mm/memcontrol.c:mem_cgroup_oom_unlock
  - mm/memcontrol.c:mem_cgroup_oom_unlock
  - mm/memcontrol.c:mem_cgroup_oom_trylock
  - mm/memcontrol.c:mem_cgroup_oom_trylock
  - mm/memcontrol.c:mem_cgroup_oom_trylock
  - mm/memcontrol.c:mem_cgroup_scan_tasks
  - mm/memcontrol.c:mem_cgroup_scan_tasks
  - mm/memcontrol.c:memcg_expand_shrinker_maps
  - mm/memcontrol.c:memcg_expand_shrinker_maps
```
**Symbols:**

```
ffffffff812b2f20-ffffffff812b31e9: mem_cgroup_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct mem_cgroup *mem_cgroup_iter(struct mem_cgroup *root, struct mem_cgroup *prev, struct mem_cgroup_reclaim_cookie *reclaim);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812c49f0)
Location: mm/memcontrol.c:1038
Inline: False
Direct callers:
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:snapshot_refaults
  - mm/vmscan.c:snapshot_refaults
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:drop_slab_node
  - mm/vmscan.c:drop_slab_node
  - mm/memcontrol.c:mem_cgroup_oom_notify
  - mm/memcontrol.c:mem_cgroup_oom_notify
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:memcg_hotplug_cpu_dead
  - mm/memcontrol.c:memcg_hotplug_cpu_dead
  - mm/memcontrol.c:mem_cgroup_unmark_under_oom
  - mm/memcontrol.c:mem_cgroup_unmark_under_oom
  - mm/memcontrol.c:mem_cgroup_mark_under_oom
  - mm/memcontrol.c:mem_cgroup_mark_under_oom
  - mm/memcontrol.c:mem_cgroup_oom_unlock
  - mm/memcontrol.c:mem_cgroup_oom_unlock
  - mm/memcontrol.c:mem_cgroup_oom_trylock
  - mm/memcontrol.c:mem_cgroup_oom_trylock
  - mm/memcontrol.c:mem_cgroup_oom_trylock
  - mm/memcontrol.c:mem_cgroup_scan_tasks
  - mm/memcontrol.c:mem_cgroup_scan_tasks
  - mm/memcontrol.c:memcg_expand_shrinker_maps
  - mm/memcontrol.c:memcg_expand_shrinker_maps
```
**Symbols:**

```
ffffffff812c49f0-ffffffff812c4cb3: mem_cgroup_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct mem_cgroup *mem_cgroup_iter(struct mem_cgroup *root, struct mem_cgroup *prev, struct mem_cgroup_reclaim_cookie *reclaim);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812fa6f0)
Location: mm/memcontrol.c:1003
Inline: False
Direct callers:
  - mm/vmscan.c:age_active_anon
  - mm/vmscan.c:age_active_anon
  - mm/vmscan.c:shrink_node_memcgs
  - mm/vmscan.c:shrink_node_memcgs
  - mm/vmscan.c:drop_slab_node
  - mm/vmscan.c:drop_slab_node
  - mm/memcontrol.c:mem_cgroup_oom_notify
  - mm/memcontrol.c:mem_cgroup_oom_notify
  - mm/memcontrol.c:memcg_hotplug_cpu_dead
  - mm/memcontrol.c:memcg_hotplug_cpu_dead
  - mm/memcontrol.c:mem_cgroup_unmark_under_oom
  - mm/memcontrol.c:mem_cgroup_unmark_under_oom
  - mm/memcontrol.c:mem_cgroup_mark_under_oom
  - mm/memcontrol.c:mem_cgroup_mark_under_oom
  - mm/memcontrol.c:mem_cgroup_oom_unlock
  - mm/memcontrol.c:mem_cgroup_oom_unlock
  - mm/memcontrol.c:mem_cgroup_oom_trylock
  - mm/memcontrol.c:mem_cgroup_oom_trylock
  - mm/memcontrol.c:mem_cgroup_oom_trylock
  - mm/memcontrol.c:mem_cgroup_scan_tasks
  - mm/memcontrol.c:mem_cgroup_scan_tasks
  - mm/memcontrol.c:memcg_expand_shrinker_maps
```
**Symbols:**

```
ffffffff812fa6f0-ffffffff812fa989: mem_cgroup_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct mem_cgroup *mem_cgroup_iter(struct mem_cgroup *root, struct mem_cgroup *prev, struct mem_cgroup_reclaim_cookie *reclaim);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81306690)
Location: mm/memcontrol.c:1135
Inline: False
Direct callers:
  - mm/vmscan.c:age_active_anon
  - mm/vmscan.c:age_active_anon
  - mm/vmscan.c:shrink_node_memcgs
  - mm/vmscan.c:shrink_node_memcgs
  - mm/vmscan.c:drop_slab_node
  - mm/vmscan.c:drop_slab_node
  - mm/memcontrol.c:mem_cgroup_oom_notify
  - mm/memcontrol.c:mem_cgroup_oom_notify
  - mm/memcontrol.c:memcg_hotplug_cpu_dead
  - mm/memcontrol.c:memcg_hotplug_cpu_dead
  - mm/memcontrol.c:mem_cgroup_unmark_under_oom
  - mm/memcontrol.c:mem_cgroup_unmark_under_oom
  - mm/memcontrol.c:mem_cgroup_mark_under_oom
  - mm/memcontrol.c:mem_cgroup_mark_under_oom
  - mm/memcontrol.c:mem_cgroup_oom_unlock
  - mm/memcontrol.c:mem_cgroup_oom_unlock
  - mm/memcontrol.c:mem_cgroup_oom_trylock
  - mm/memcontrol.c:mem_cgroup_oom_trylock
  - mm/memcontrol.c:mem_cgroup_oom_trylock
  - mm/memcontrol.c:mem_cgroup_scan_tasks
  - mm/memcontrol.c:mem_cgroup_scan_tasks
  - mm/memcontrol.c:memcg_expand_shrinker_maps
```
**Symbols:**

```
ffffffff81306690-ffffffff81306937: mem_cgroup_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct mem_cgroup *mem_cgroup_iter(struct mem_cgroup *root, struct mem_cgroup *prev, struct mem_cgroup_reclaim_cookie *reclaim);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff8130ceb0)
Location: mm/memcontrol.c:962
Inline: False
Direct callers:
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:shrink_node_memcgs
  - mm/vmscan.c:shrink_node_memcgs
  - mm/vmscan.c:drop_slab_node
  - mm/vmscan.c:drop_slab_node
  - mm/vmscan.c:prealloc_shrinker
  - mm/vmscan.c:prealloc_shrinker
  - mm/memcontrol.c:mem_cgroup_oom_notify
  - mm/memcontrol.c:mem_cgroup_oom_notify
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:memcg_hotplug_cpu_dead
  - mm/memcontrol.c:memcg_hotplug_cpu_dead
  - mm/memcontrol.c:mem_cgroup_unmark_under_oom
  - mm/memcontrol.c:mem_cgroup_unmark_under_oom
  - mm/memcontrol.c:mem_cgroup_mark_under_oom
  - mm/memcontrol.c:mem_cgroup_mark_under_oom
  - mm/memcontrol.c:mem_cgroup_oom_unlock
  - mm/memcontrol.c:mem_cgroup_oom_unlock
  - mm/memcontrol.c:mem_cgroup_oom_trylock
  - mm/memcontrol.c:mem_cgroup_oom_trylock
  - mm/memcontrol.c:mem_cgroup_oom_trylock
  - mm/memcontrol.c:mem_cgroup_scan_tasks
  - mm/memcontrol.c:mem_cgroup_scan_tasks
```
**Symbols:**

```
ffffffff8130ceb0-ffffffff8130d15f: mem_cgroup_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct mem_cgroup *mem_cgroup_iter(struct mem_cgroup *root, struct mem_cgroup *prev, struct mem_cgroup_reclaim_cookie *reclaim);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81357d60)
Location: mm/memcontrol.c:1017
Inline: False
Direct callers:
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:shrink_node_memcgs
  - mm/vmscan.c:shrink_node_memcgs
  - mm/vmscan.c:drop_slab_node
  - mm/vmscan.c:drop_slab_node
  - mm/vmscan.c:prealloc_shrinker
  - mm/vmscan.c:prealloc_shrinker
  - mm/memcontrol.c:mem_cgroup_oom_notify
  - mm/memcontrol.c:mem_cgroup_oom_notify
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:mem_cgroup_unmark_under_oom
  - mm/memcontrol.c:mem_cgroup_unmark_under_oom
  - mm/memcontrol.c:mem_cgroup_mark_under_oom
  - mm/memcontrol.c:mem_cgroup_mark_under_oom
  - mm/memcontrol.c:mem_cgroup_oom_unlock
  - mm/memcontrol.c:mem_cgroup_oom_unlock
  - mm/memcontrol.c:mem_cgroup_oom_trylock
  - mm/memcontrol.c:mem_cgroup_oom_trylock
  - mm/memcontrol.c:mem_cgroup_oom_trylock
  - mm/memcontrol.c:mem_cgroup_scan_tasks
  - mm/memcontrol.c:mem_cgroup_scan_tasks
```
**Symbols:**

```
ffffffff81357d60-ffffffff8135800f: mem_cgroup_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct mem_cgroup *mem_cgroup_iter(struct mem_cgroup *root, struct mem_cgroup *prev, struct mem_cgroup_reclaim_cookie *reclaim);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff813d0e60)
Location: mm/memcontrol.c:999
Inline: False
Direct callers:
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:shrink_node_memcgs
  - mm/vmscan.c:shrink_node_memcgs
  - mm/vmscan.c:drop_slab
  - mm/vmscan.c:drop_slab
  - mm/vmscan.c:prealloc_shrinker
  - mm/vmscan.c:prealloc_shrinker
  - mm/memcontrol.c:mem_cgroup_oom_notify
  - mm/memcontrol.c:mem_cgroup_oom_notify
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:mem_cgroup_unmark_under_oom
  - mm/memcontrol.c:mem_cgroup_unmark_under_oom
  - mm/memcontrol.c:mem_cgroup_mark_under_oom
  - mm/memcontrol.c:mem_cgroup_mark_under_oom
  - mm/memcontrol.c:mem_cgroup_oom_unlock
  - mm/memcontrol.c:mem_cgroup_oom_unlock
  - mm/memcontrol.c:mem_cgroup_oom_trylock
  - mm/memcontrol.c:mem_cgroup_oom_trylock
  - mm/memcontrol.c:mem_cgroup_oom_trylock
  - mm/memcontrol.c:mem_cgroup_scan_tasks
  - mm/memcontrol.c:mem_cgroup_scan_tasks
```
**Symbols:**

```
ffffffff813d0e60-ffffffff813d114e: mem_cgroup_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct mem_cgroup *mem_cgroup_iter(struct mem_cgroup *root, struct mem_cgroup *prev, struct mem_cgroup_reclaim_cookie *reclaim);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81456250)
Location: mm/memcontrol.c:1079
Inline: False
Direct callers:
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:shrink_node_memcgs
  - mm/vmscan.c:shrink_node_memcgs
  - mm/vmscan.c:lru_gen_seq_next
  - mm/vmscan.c:lru_gen_seq_start
  - mm/vmscan.c:lru_gen_seq_start
  - mm/vmscan.c:lru_gen_change_state
  - mm/vmscan.c:lru_gen_change_state
  - mm/vmscan.c:lru_gen_age_node
  - mm/vmscan.c:lru_gen_age_node
  - mm/vmscan.c:drop_slab
  - mm/vmscan.c:drop_slab
  - mm/vmscan.c:__prealloc_shrinker
  - mm/vmscan.c:__prealloc_shrinker
  - mm/memcontrol.c:mem_cgroup_oom_notify
  - mm/memcontrol.c:mem_cgroup_oom_notify
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:mem_cgroup_unmark_under_oom
  - mm/memcontrol.c:mem_cgroup_unmark_under_oom
  - mm/memcontrol.c:mem_cgroup_mark_under_oom
  - mm/memcontrol.c:mem_cgroup_mark_under_oom
  - mm/memcontrol.c:mem_cgroup_oom_unlock
  - mm/memcontrol.c:mem_cgroup_oom_unlock
  - mm/memcontrol.c:mem_cgroup_oom_trylock
  - mm/memcontrol.c:mem_cgroup_oom_trylock
  - mm/memcontrol.c:mem_cgroup_oom_trylock
  - mm/memcontrol.c:mem_cgroup_scan_tasks
  - mm/memcontrol.c:mem_cgroup_scan_tasks
```
**Symbols:**

```
ffffffff81456250-ffffffff8145653e: mem_cgroup_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct mem_cgroup *mem_cgroup_iter(struct mem_cgroup *root, struct mem_cgroup *prev, struct mem_cgroup_reclaim_cookie *reclaim);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff8148bb30)
Location: mm/memcontrol.c:1104
Inline: False
Direct callers:
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:shrink_node_memcgs
  - mm/vmscan.c:shrink_node_memcgs
  - mm/vmscan.c:lru_gen_seq_next
  - mm/vmscan.c:lru_gen_seq_start
  - mm/vmscan.c:lru_gen_seq_start
  - mm/vmscan.c:lru_gen_change_state
  - mm/vmscan.c:lru_gen_change_state
  - mm/vmscan.c:lru_gen_age_node
  - mm/vmscan.c:lru_gen_age_node
  - mm/vmscan.c:drop_slab
  - mm/vmscan.c:drop_slab
  - mm/vmscan.c:__prealloc_shrinker
  - mm/vmscan.c:__prealloc_shrinker
  - mm/memcontrol.c:mem_cgroup_oom_notify
  - mm/memcontrol.c:mem_cgroup_oom_notify
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:mem_cgroup_unmark_under_oom
  - mm/memcontrol.c:mem_cgroup_unmark_under_oom
  - mm/memcontrol.c:mem_cgroup_mark_under_oom
  - mm/memcontrol.c:mem_cgroup_mark_under_oom
  - mm/memcontrol.c:mem_cgroup_oom_unlock
  - mm/memcontrol.c:mem_cgroup_oom_unlock
  - mm/memcontrol.c:mem_cgroup_oom_trylock
  - mm/memcontrol.c:mem_cgroup_oom_trylock
  - mm/memcontrol.c:mem_cgroup_oom_trylock
  - mm/memcontrol.c:mem_cgroup_scan_tasks
  - mm/memcontrol.c:mem_cgroup_scan_tasks
```
**Symbols:**

```
ffffffff8148bb30-ffffffff8148bdcd: mem_cgroup_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct mem_cgroup *mem_cgroup_iter(struct mem_cgroup *root, struct mem_cgroup *prev, struct mem_cgroup_reclaim_cookie *reclaim);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff814bb480)
Location: mm/memcontrol.c:1155
Inline: False
Direct callers:
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:shrink_node_memcgs
  - mm/vmscan.c:shrink_node_memcgs
  - mm/vmscan.c:lru_gen_seq_next
  - mm/vmscan.c:lru_gen_seq_start
  - mm/vmscan.c:lru_gen_seq_start
  - mm/vmscan.c:lru_gen_change_state
  - mm/vmscan.c:lru_gen_change_state
  - mm/vmscan.c:lru_gen_age_node
  - mm/vmscan.c:lru_gen_age_node
  - mm/vmscan.c:drop_slab
  - mm/vmscan.c:drop_slab
  - mm/shrinker.c:shrinker_alloc
  - mm/shrinker.c:shrinker_alloc
  - mm/zswap.c:shrink_worker
  - mm/zswap.c:zswap_memcg_offline_cleanup
  - mm/memcontrol.c:mem_cgroup_oom_notify
  - mm/memcontrol.c:mem_cgroup_oom_notify
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:mem_cgroup_unmark_under_oom
  - mm/memcontrol.c:mem_cgroup_unmark_under_oom
  - mm/memcontrol.c:mem_cgroup_mark_under_oom
  - mm/memcontrol.c:mem_cgroup_mark_under_oom
  - mm/memcontrol.c:mem_cgroup_oom_unlock
  - mm/memcontrol.c:mem_cgroup_oom_unlock
  - mm/memcontrol.c:mem_cgroup_oom_trylock
  - mm/memcontrol.c:mem_cgroup_oom_trylock
  - mm/memcontrol.c:mem_cgroup_oom_trylock
  - mm/memcontrol.c:mem_cgroup_scan_tasks
  - mm/memcontrol.c:mem_cgroup_scan_tasks
```
**Symbols:**

```
ffffffff814bb480-ffffffff814bb71d: mem_cgroup_iter (STB_GLOBAL)
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
struct mem_cgroup *mem_cgroup_iter(struct mem_cgroup *root, struct mem_cgroup *prev, struct mem_cgroup_reclaim_cookie *reclaim);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffff800010367648)
Location: mm/memcontrol.c:1038
Inline: False
Direct callers:
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:snapshot_refaults
  - mm/vmscan.c:snapshot_refaults
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:drop_slab_node
  - mm/vmscan.c:drop_slab_node
  - mm/memcontrol.c:mem_cgroup_oom_notify
  - mm/memcontrol.c:mem_cgroup_oom_notify
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:memcg_hotplug_cpu_dead
  - mm/memcontrol.c:memcg_hotplug_cpu_dead
  - mm/memcontrol.c:mem_cgroup_unmark_under_oom
  - mm/memcontrol.c:mem_cgroup_unmark_under_oom
  - mm/memcontrol.c:mem_cgroup_mark_under_oom
  - mm/memcontrol.c:mem_cgroup_mark_under_oom
  - mm/memcontrol.c:mem_cgroup_oom_unlock
  - mm/memcontrol.c:mem_cgroup_oom_unlock
  - mm/memcontrol.c:mem_cgroup_oom_trylock
  - mm/memcontrol.c:mem_cgroup_oom_trylock
  - mm/memcontrol.c:mem_cgroup_oom_trylock
  - mm/memcontrol.c:mem_cgroup_oom_trylock
  - mm/memcontrol.c:mem_cgroup_scan_tasks
  - mm/memcontrol.c:mem_cgroup_scan_tasks
  - mm/memcontrol.c:memcg_expand_shrinker_maps
  - mm/memcontrol.c:memcg_expand_shrinker_maps
```
**Symbols:**

```
ffff800010367648-ffff8000103678ac: mem_cgroup_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct mem_cgroup *mem_cgroup_iter(struct mem_cgroup *root, struct mem_cgroup *prev, struct mem_cgroup_reclaim_cookie *reclaim);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (c0558d8c)
Location: mm/memcontrol.c:1038
Inline: False
Direct callers:
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:snapshot_refaults
  - mm/vmscan.c:snapshot_refaults
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:drop_slab_node
  - mm/vmscan.c:drop_slab_node
  - mm/memcontrol.c:mem_cgroup_oom_notify
  - mm/memcontrol.c:mem_cgroup_oom_notify
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:memcg_hotplug_cpu_dead
  - mm/memcontrol.c:memcg_hotplug_cpu_dead
  - mm/memcontrol.c:mem_cgroup_unmark_under_oom
  - mm/memcontrol.c:mem_cgroup_mark_under_oom
  - mm/memcontrol.c:mem_cgroup_mark_under_oom
  - mm/memcontrol.c:mem_cgroup_oom_unlock
  - mm/memcontrol.c:mem_cgroup_oom_unlock
  - mm/memcontrol.c:mem_cgroup_oom_trylock
  - mm/memcontrol.c:mem_cgroup_oom_trylock
  - mm/memcontrol.c:mem_cgroup_oom_trylock
  - mm/memcontrol.c:mem_cgroup_oom_trylock
  - mm/memcontrol.c:mem_cgroup_scan_tasks
  - mm/memcontrol.c:mem_cgroup_scan_tasks
  - mm/memcontrol.c:memcg_expand_shrinker_maps
  - mm/memcontrol.c:memcg_expand_shrinker_maps
```
**Symbols:**

```
c0558d8c-c055916c: mem_cgroup_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct mem_cgroup *mem_cgroup_iter(struct mem_cgroup *root, struct mem_cgroup *prev, struct mem_cgroup_reclaim_cookie *reclaim);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (c000000000454cb0)
Location: mm/memcontrol.c:1038
Inline: False
Direct callers:
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:snapshot_refaults
  - mm/vmscan.c:snapshot_refaults
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:drop_slab_node
  - mm/vmscan.c:drop_slab_node
  - mm/memcontrol.c:mem_cgroup_oom_notify
  - mm/memcontrol.c:mem_cgroup_oom_notify
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:memcg_hotplug_cpu_dead
  - mm/memcontrol.c:memcg_hotplug_cpu_dead
  - mm/memcontrol.c:mem_cgroup_unmark_under_oom
  - mm/memcontrol.c:mem_cgroup_unmark_under_oom
  - mm/memcontrol.c:mem_cgroup_mark_under_oom
  - mm/memcontrol.c:mem_cgroup_mark_under_oom
  - mm/memcontrol.c:mem_cgroup_oom_unlock
  - mm/memcontrol.c:mem_cgroup_oom_unlock
  - mm/memcontrol.c:mem_cgroup_oom_trylock
  - mm/memcontrol.c:mem_cgroup_oom_trylock
  - mm/memcontrol.c:mem_cgroup_oom_trylock
  - mm/memcontrol.c:mem_cgroup_oom_trylock
  - mm/memcontrol.c:mem_cgroup_scan_tasks
  - mm/memcontrol.c:mem_cgroup_scan_tasks
  - mm/memcontrol.c:memcg_expand_shrinker_maps
  - mm/memcontrol.c:memcg_expand_shrinker_maps
```
**Symbols:**

```
c000000000454cb0-c0000000004551f8: mem_cgroup_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct mem_cgroup *mem_cgroup_iter(struct mem_cgroup *root, struct mem_cgroup *prev, struct mem_cgroup_reclaim_cookie *reclaim);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffe0002457bc)
Location: mm/memcontrol.c:1038
Inline: False
Direct callers:
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:snapshot_refaults
  - mm/vmscan.c:snapshot_refaults
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:drop_slab_node
  - mm/vmscan.c:drop_slab_node
  - mm/memcontrol.c:mem_cgroup_oom_notify
  - mm/memcontrol.c:mem_cgroup_oom_notify
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:memcg_hotplug_cpu_dead
  - mm/memcontrol.c:memcg_hotplug_cpu_dead
  - mm/memcontrol.c:mem_cgroup_unmark_under_oom
  - mm/memcontrol.c:mem_cgroup_unmark_under_oom
  - mm/memcontrol.c:mem_cgroup_mark_under_oom
  - mm/memcontrol.c:mem_cgroup_mark_under_oom
  - mm/memcontrol.c:mem_cgroup_oom_unlock
  - mm/memcontrol.c:mem_cgroup_oom_unlock
  - mm/memcontrol.c:mem_cgroup_oom_trylock
  - mm/memcontrol.c:mem_cgroup_oom_trylock
  - mm/memcontrol.c:mem_cgroup_oom_trylock
  - mm/memcontrol.c:mem_cgroup_oom_trylock
  - mm/memcontrol.c:mem_cgroup_scan_tasks
  - mm/memcontrol.c:mem_cgroup_scan_tasks
  - mm/memcontrol.c:memcg_expand_shrinker_maps
  - mm/memcontrol.c:memcg_expand_shrinker_maps
```
**Symbols:**

```
ffffffe0002457bc-ffffffe000245a80: mem_cgroup_iter (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
struct mem_cgroup *mem_cgroup_iter(struct mem_cgroup *root, struct mem_cgroup *prev, struct mem_cgroup_reclaim_cookie *reclaim);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812bcfd0)
Location: mm/memcontrol.c:1038
Inline: False
Direct callers:
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:snapshot_refaults
  - mm/vmscan.c:snapshot_refaults
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:drop_slab_node
  - mm/vmscan.c:drop_slab_node
  - mm/memcontrol.c:mem_cgroup_oom_notify
  - mm/memcontrol.c:mem_cgroup_oom_notify
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:memcg_hotplug_cpu_dead
  - mm/memcontrol.c:memcg_hotplug_cpu_dead
  - mm/memcontrol.c:mem_cgroup_unmark_under_oom
  - mm/memcontrol.c:mem_cgroup_unmark_under_oom
  - mm/memcontrol.c:mem_cgroup_mark_under_oom
  - mm/memcontrol.c:mem_cgroup_mark_under_oom
  - mm/memcontrol.c:mem_cgroup_oom_unlock
  - mm/memcontrol.c:mem_cgroup_oom_unlock
  - mm/memcontrol.c:mem_cgroup_oom_trylock
  - mm/memcontrol.c:mem_cgroup_oom_trylock
  - mm/memcontrol.c:mem_cgroup_oom_trylock
  - mm/memcontrol.c:mem_cgroup_scan_tasks
  - mm/memcontrol.c:mem_cgroup_scan_tasks
  - mm/memcontrol.c:memcg_expand_shrinker_maps
  - mm/memcontrol.c:memcg_expand_shrinker_maps
```
**Symbols:**

```
ffffffff812bcfd0-ffffffff812bd293: mem_cgroup_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct mem_cgroup *mem_cgroup_iter(struct mem_cgroup *root, struct mem_cgroup *prev, struct mem_cgroup_reclaim_cookie *reclaim);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812ae110)
Location: mm/memcontrol.c:1038
Inline: False
Direct callers:
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:snapshot_refaults
  - mm/vmscan.c:snapshot_refaults
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:drop_slab_node
  - mm/vmscan.c:drop_slab_node
  - mm/memcontrol.c:mem_cgroup_oom_notify
  - mm/memcontrol.c:mem_cgroup_oom_notify
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:memcg_hotplug_cpu_dead
  - mm/memcontrol.c:memcg_hotplug_cpu_dead
  - mm/memcontrol.c:mem_cgroup_unmark_under_oom
  - mm/memcontrol.c:mem_cgroup_unmark_under_oom
  - mm/memcontrol.c:mem_cgroup_mark_under_oom
  - mm/memcontrol.c:mem_cgroup_mark_under_oom
  - mm/memcontrol.c:mem_cgroup_oom_unlock
  - mm/memcontrol.c:mem_cgroup_oom_unlock
  - mm/memcontrol.c:mem_cgroup_oom_trylock
  - mm/memcontrol.c:mem_cgroup_oom_trylock
  - mm/memcontrol.c:mem_cgroup_oom_trylock
  - mm/memcontrol.c:mem_cgroup_scan_tasks
  - mm/memcontrol.c:mem_cgroup_scan_tasks
  - mm/memcontrol.c:memcg_expand_shrinker_maps
  - mm/memcontrol.c:memcg_expand_shrinker_maps
```
**Symbols:**

```
ffffffff812ae110-ffffffff812ae3d3: mem_cgroup_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct mem_cgroup *mem_cgroup_iter(struct mem_cgroup *root, struct mem_cgroup *prev, struct mem_cgroup_reclaim_cookie *reclaim);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812bade0)
Location: mm/memcontrol.c:1038
Inline: False
Direct callers:
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:snapshot_refaults
  - mm/vmscan.c:snapshot_refaults
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:drop_slab_node
  - mm/vmscan.c:drop_slab_node
  - mm/memcontrol.c:mem_cgroup_oom_notify
  - mm/memcontrol.c:mem_cgroup_oom_notify
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:memcg_hotplug_cpu_dead
  - mm/memcontrol.c:memcg_hotplug_cpu_dead
  - mm/memcontrol.c:mem_cgroup_unmark_under_oom
  - mm/memcontrol.c:mem_cgroup_unmark_under_oom
  - mm/memcontrol.c:mem_cgroup_mark_under_oom
  - mm/memcontrol.c:mem_cgroup_mark_under_oom
  - mm/memcontrol.c:mem_cgroup_oom_unlock
  - mm/memcontrol.c:mem_cgroup_oom_unlock
  - mm/memcontrol.c:mem_cgroup_oom_trylock
  - mm/memcontrol.c:mem_cgroup_oom_trylock
  - mm/memcontrol.c:mem_cgroup_oom_trylock
  - mm/memcontrol.c:mem_cgroup_scan_tasks
  - mm/memcontrol.c:mem_cgroup_scan_tasks
  - mm/memcontrol.c:memcg_expand_shrinker_maps
  - mm/memcontrol.c:memcg_expand_shrinker_maps
```
**Symbols:**

```
ffffffff812bade0-ffffffff812bb0a3: mem_cgroup_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct mem_cgroup *mem_cgroup_iter(struct mem_cgroup *root, struct mem_cgroup *prev, struct mem_cgroup_reclaim_cookie *reclaim);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812cb530)
Location: mm/memcontrol.c:1038
Inline: False
Direct callers:
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:balance_pgdat
  - mm/vmscan.c:snapshot_refaults
  - mm/vmscan.c:snapshot_refaults
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:shrink_node
  - mm/vmscan.c:drop_slab_node
  - mm/vmscan.c:drop_slab_node
  - mm/memcontrol.c:mem_cgroup_oom_notify
  - mm/memcontrol.c:mem_cgroup_oom_notify
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:memcg_hotplug_cpu_dead
  - mm/memcontrol.c:memcg_hotplug_cpu_dead
  - mm/memcontrol.c:mem_cgroup_unmark_under_oom
  - mm/memcontrol.c:mem_cgroup_unmark_under_oom
  - mm/memcontrol.c:mem_cgroup_mark_under_oom
  - mm/memcontrol.c:mem_cgroup_mark_under_oom
  - mm/memcontrol.c:mem_cgroup_oom_unlock
  - mm/memcontrol.c:mem_cgroup_oom_unlock
  - mm/memcontrol.c:mem_cgroup_oom_trylock
  - mm/memcontrol.c:mem_cgroup_oom_trylock
  - mm/memcontrol.c:mem_cgroup_oom_trylock
  - mm/memcontrol.c:mem_cgroup_scan_tasks
  - mm/memcontrol.c:mem_cgroup_scan_tasks
  - mm/memcontrol.c:memcg_expand_shrinker_maps
  - mm/memcontrol.c:memcg_expand_shrinker_maps
```
**Symbols:**

```
ffffffff812cb530-ffffffff812cb85f: mem_cgroup_iter (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
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
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
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
