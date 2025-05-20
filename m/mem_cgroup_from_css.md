# Function: <code>mem_cgroup_from_css</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (0)
Location: include/linux/memcontrol.h:314
Inline: True
```
```
In mm/slab_common.c (0)
Location: include/linux/memcontrol.h:314
Inline: True
```
```
In mm/memcontrol.c (ffffffff811f9b48)
Location: include/linux/memcontrol.h:314
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_hierarchy_write
  - mm/memcontrol.c:mem_cgroup_css_online
  - mm/memcontrol.c:get_mem_cgroup_from_mm
  - mm/memcontrol.c:mem_cgroup_try_charge
  - mm/memcontrol.c:mem_cgroup_uncharge_swap
```
```
In mm/vmpressure.c (0)
Location: include/linux/memcontrol.h:314
Inline: True
```
```
In net/ipv4/tcp_memcontrol.c (0)
Location: include/linux/memcontrol.h:314
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (0)
Location: include/linux/memcontrol.h:358
Inline: True
```
```
In mm/slab_common.c (0)
Location: include/linux/memcontrol.h:358
Inline: True
```
```
In mm/memcontrol.c (ffffffff8121d709)
Location: include/linux/memcontrol.h:358
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_hierarchy_write
  - mm/memcontrol.c:get_mem_cgroup_from_mm
```
```
In mm/vmpressure.c (0)
Location: include/linux/memcontrol.h:358
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
In mm/backing-dev.c (0)
Location: include/linux/memcontrol.h:358
Inline: True
```
```
In mm/slab_common.c (0)
Location: include/linux/memcontrol.h:358
Inline: True
```
```
In mm/memcontrol.c (ffffffff8122fc79)
Location: include/linux/memcontrol.h:358
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_hierarchy_write
  - mm/memcontrol.c:get_mem_cgroup_from_mm
```
```
In mm/vmpressure.c (0)
Location: include/linux/memcontrol.h:358
Inline: True
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
In mm/backing-dev.c (0)
Location: include/linux/memcontrol.h:341
Inline: True
```
```
In mm/slab_common.c (0)
Location: include/linux/memcontrol.h:341
Inline: True
```
```
In mm/memcontrol.c (ffffffff8123b595)
Location: include/linux/memcontrol.h:341
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_hierarchy_write
  - mm/memcontrol.c:get_mem_cgroup_from_mm
```
```
In mm/vmpressure.c (0)
Location: include/linux/memcontrol.h:341
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
In mm/backing-dev.c (0)
Location: include/linux/memcontrol.h:341
Inline: True
```
```
In mm/slab_common.c (0)
Location: include/linux/memcontrol.h:341
Inline: True
```
```
In mm/memcontrol.c (ffffffff8125ae25)
Location: include/linux/memcontrol.h:341
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_hierarchy_write
  - mm/memcontrol.c:get_mem_cgroup_from_mm
```
```
In mm/vmpressure.c (0)
Location: include/linux/memcontrol.h:341
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
In mm/backing-dev.c (ffffffff81218d0e)
Location: include/linux/memcontrol.h:374
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_get_create
```
```
In mm/slab_common.c (ffffffff8121f214)
Location: include/linux/memcontrol.h:374
Inline: True
Inline callers:
  - mm/slab_common.c:memcg_slab_show
  - mm/slab_common.c:memcg_slab_next
  - mm/slab_common.c:memcg_slab_start
```
```
In mm/memcontrol.c (ffffffff8127e90c)
Location: include/linux/memcontrol.h:374
Inline: True
Inline callers:
  - mm/memcontrol.c:swap_events_show
  - mm/memcontrol.c:swap_max_write
  - mm/memcontrol.c:swap_max_show
  - mm/memcontrol.c:swap_current_read
  - mm/memcontrol.c:mem_cgroup_sk_alloc
  - mm/memcontrol.c:memory_stat_show
  - mm/memcontrol.c:memory_events_show
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:memory_max_show
  - mm/memcontrol.c:memory_high_write
  - mm/memcontrol.c:memory_high_show
  - mm/memcontrol.c:memory_low_write
  - mm/memcontrol.c:memory_low_show
  - mm/memcontrol.c:memory_min_write
  - mm/memcontrol.c:memory_min_show
  - mm/memcontrol.c:memory_current_read
  - mm/memcontrol.c:mem_cgroup_css_reset
  - mm/memcontrol.c:mem_cgroup_css_free
  - mm/memcontrol.c:mem_cgroup_css_released
  - mm/memcontrol.c:mem_cgroup_css_offline
  - mm/memcontrol.c:mem_cgroup_css_online
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:mem_cgroup_wb_stats
  - mm/memcontrol.c:mem_cgroup_wb_domain
  - mm/memcontrol.c:mem_cgroup_oom_control_write
  - mm/memcontrol.c:mem_cgroup_oom_control_read
  - mm/memcontrol.c:mem_cgroup_swappiness_write
  - mm/memcontrol.c:mem_cgroup_swappiness_read
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:mem_cgroup_move_charge_write
  - mm/memcontrol.c:mem_cgroup_move_charge_read
  - mm/memcontrol.c:mem_cgroup_reset
  - mm/memcontrol.c:mem_cgroup_write
  - mm/memcontrol.c:mem_cgroup_read_u64
  - mm/memcontrol.c:mem_cgroup_hierarchy_write
  - mm/memcontrol.c:mem_cgroup_hierarchy_write
  - mm/memcontrol.c:mem_cgroup_hierarchy_read
  - mm/memcontrol.c:mem_cgroup_force_empty_write
  - mm/memcontrol.c:task_in_mem_cgroup
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:get_mem_cgroup_from_mm
```
```
In mm/vmpressure.c (ffffffff812870c5)
Location: include/linux/memcontrol.h:374
Inline: True
Inline callers:
  - mm/vmpressure.c:vmpressure_work_fn
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
In mm/backing-dev.c (ffffffff8122bb5e)
Location: include/linux/memcontrol.h:403
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_get_create
```
```
In mm/slab_common.c (ffffffff81232204)
Location: include/linux/memcontrol.h:403
Inline: True
Inline callers:
  - mm/slab_common.c:memcg_slab_show
  - mm/slab_common.c:memcg_slab_next
  - mm/slab_common.c:memcg_slab_start
```
```
In mm/memcontrol.c (ffffffff8129309c)
Location: include/linux/memcontrol.h:403
Inline: True
Inline callers:
  - mm/memcontrol.c:swap_events_show
  - mm/memcontrol.c:swap_max_write
  - mm/memcontrol.c:swap_max_show
  - mm/memcontrol.c:swap_current_read
  - mm/memcontrol.c:mem_cgroup_sk_alloc
  - mm/memcontrol.c:memory_oom_group_write
  - mm/memcontrol.c:memory_oom_group_show
  - mm/memcontrol.c:memory_stat_show
  - mm/memcontrol.c:memory_events_show
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:memory_max_show
  - mm/memcontrol.c:memory_high_write
  - mm/memcontrol.c:memory_high_show
  - mm/memcontrol.c:memory_low_write
  - mm/memcontrol.c:memory_low_show
  - mm/memcontrol.c:memory_min_write
  - mm/memcontrol.c:memory_min_show
  - mm/memcontrol.c:memory_current_read
  - mm/memcontrol.c:mem_cgroup_css_reset
  - mm/memcontrol.c:mem_cgroup_css_free
  - mm/memcontrol.c:mem_cgroup_css_released
  - mm/memcontrol.c:mem_cgroup_css_offline
  - mm/memcontrol.c:mem_cgroup_css_online
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:mem_cgroup_wb_stats
  - mm/memcontrol.c:mem_cgroup_wb_domain
  - mm/memcontrol.c:mem_cgroup_oom_control_write
  - mm/memcontrol.c:mem_cgroup_oom_control_read
  - mm/memcontrol.c:mem_cgroup_swappiness_write
  - mm/memcontrol.c:mem_cgroup_swappiness_read
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:mem_cgroup_move_charge_write
  - mm/memcontrol.c:mem_cgroup_move_charge_read
  - mm/memcontrol.c:mem_cgroup_reset
  - mm/memcontrol.c:mem_cgroup_write
  - mm/memcontrol.c:mem_cgroup_read_u64
  - mm/memcontrol.c:mem_cgroup_hierarchy_write
  - mm/memcontrol.c:mem_cgroup_hierarchy_write
  - mm/memcontrol.c:mem_cgroup_hierarchy_read
  - mm/memcontrol.c:mem_cgroup_force_empty_write
  - mm/memcontrol.c:mem_cgroup_get_oom_group
  - mm/memcontrol.c:task_in_mem_cgroup
  - mm/memcontrol.c:mem_cgroup_iter
```
```
In mm/vmpressure.c (ffffffff8129c015)
Location: include/linux/memcontrol.h:403
Inline: True
Inline callers:
  - mm/vmpressure.c:vmpressure_work_fn
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff8123b83a)
Location: include/linux/memcontrol.h:404
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_get_create
```
```
In mm/slab_common.c (ffffffff812426d4)
Location: include/linux/memcontrol.h:404
Inline: True
Inline callers:
  - mm/slab_common.c:memcg_slab_show
  - mm/slab_common.c:memcg_slab_next
  - mm/slab_common.c:memcg_slab_start
```
```
In mm/memcontrol.c (ffffffff812ad97c)
Location: include/linux/memcontrol.h:404
Inline: True
Inline callers:
  - mm/memcontrol.c:swap_events_show
  - mm/memcontrol.c:swap_max_write
  - mm/memcontrol.c:swap_max_show
  - mm/memcontrol.c:swap_current_read
  - mm/memcontrol.c:mem_cgroup_sk_alloc
  - mm/memcontrol.c:memory_oom_group_write
  - mm/memcontrol.c:memory_oom_group_show
  - mm/memcontrol.c:memory_stat_show
  - mm/memcontrol.c:memory_events_local_show
  - mm/memcontrol.c:memory_events_show
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:memory_max_show
  - mm/memcontrol.c:memory_high_write
  - mm/memcontrol.c:memory_high_show
  - mm/memcontrol.c:memory_low_write
  - mm/memcontrol.c:memory_low_show
  - mm/memcontrol.c:memory_min_write
  - mm/memcontrol.c:memory_min_show
  - mm/memcontrol.c:memory_current_read
  - mm/memcontrol.c:mem_cgroup_css_reset
  - mm/memcontrol.c:mem_cgroup_css_free
  - mm/memcontrol.c:mem_cgroup_css_released
  - mm/memcontrol.c:mem_cgroup_css_offline
  - mm/memcontrol.c:mem_cgroup_css_online
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:mem_cgroup_wb_stats
  - mm/memcontrol.c:mem_cgroup_wb_domain
  - mm/memcontrol.c:mem_cgroup_oom_control_write
  - mm/memcontrol.c:mem_cgroup_oom_control_read
  - mm/memcontrol.c:mem_cgroup_swappiness_write
  - mm/memcontrol.c:mem_cgroup_swappiness_read
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:mem_cgroup_move_charge_write
  - mm/memcontrol.c:mem_cgroup_move_charge_read
  - mm/memcontrol.c:mem_cgroup_reset
  - mm/memcontrol.c:mem_cgroup_write
  - mm/memcontrol.c:mem_cgroup_read_u64
  - mm/memcontrol.c:mem_cgroup_hierarchy_write
  - mm/memcontrol.c:mem_cgroup_hierarchy_write
  - mm/memcontrol.c:mem_cgroup_hierarchy_read
  - mm/memcontrol.c:mem_cgroup_force_empty_write
  - mm/memcontrol.c:memcg_kmem_get_cache
  - mm/memcontrol.c:mem_cgroup_get_oom_group
  - mm/memcontrol.c:mem_cgroup_iter
```
```
In mm/vmpressure.c (ffffffff812b71ac)
Location: include/linux/memcontrol.h:404
Inline: True
Inline callers:
  - mm/vmpressure.c:vmpressure_work_fn
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff81249ccb)
Location: include/linux/memcontrol.h:438
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_get_create
```
```
In mm/slab_common.c (ffffffff81250bf4)
Location: include/linux/memcontrol.h:438
Inline: True
Inline callers:
  - mm/slab_common.c:memcg_slab_show
  - mm/slab_common.c:memcg_slab_next
  - mm/slab_common.c:memcg_slab_start
```
```
In mm/memcontrol.c (ffffffff812bf4cc)
Location: include/linux/memcontrol.h:438
Inline: True
Inline callers:
  - mm/memcontrol.c:swap_events_show
  - mm/memcontrol.c:swap_max_write
  - mm/memcontrol.c:swap_max_show
  - mm/memcontrol.c:swap_current_read
  - mm/memcontrol.c:mem_cgroup_sk_alloc
  - mm/memcontrol.c:memory_oom_group_write
  - mm/memcontrol.c:memory_oom_group_show
  - mm/memcontrol.c:memory_stat_show
  - mm/memcontrol.c:memory_events_local_show
  - mm/memcontrol.c:memory_events_show
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:memory_max_show
  - mm/memcontrol.c:memory_high_write
  - mm/memcontrol.c:memory_high_show
  - mm/memcontrol.c:memory_low_write
  - mm/memcontrol.c:memory_low_show
  - mm/memcontrol.c:memory_min_write
  - mm/memcontrol.c:memory_min_show
  - mm/memcontrol.c:memory_current_read
  - mm/memcontrol.c:mem_cgroup_css_reset
  - mm/memcontrol.c:mem_cgroup_css_free
  - mm/memcontrol.c:mem_cgroup_css_released
  - mm/memcontrol.c:mem_cgroup_css_offline
  - mm/memcontrol.c:mem_cgroup_css_online
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:mem_cgroup_flush_foreign
  - mm/memcontrol.c:mem_cgroup_wb_stats
  - mm/memcontrol.c:mem_cgroup_wb_domain
  - mm/memcontrol.c:mem_cgroup_oom_control_write
  - mm/memcontrol.c:mem_cgroup_oom_control_read
  - mm/memcontrol.c:mem_cgroup_swappiness_write
  - mm/memcontrol.c:mem_cgroup_swappiness_read
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:mem_cgroup_move_charge_write
  - mm/memcontrol.c:mem_cgroup_move_charge_read
  - mm/memcontrol.c:mem_cgroup_reset
  - mm/memcontrol.c:mem_cgroup_write
  - mm/memcontrol.c:mem_cgroup_read_u64
  - mm/memcontrol.c:mem_cgroup_hierarchy_write
  - mm/memcontrol.c:mem_cgroup_hierarchy_write
  - mm/memcontrol.c:mem_cgroup_hierarchy_read
  - mm/memcontrol.c:mem_cgroup_force_empty_write
  - mm/memcontrol.c:memcg_kmem_get_cache
  - mm/memcontrol.c:mem_cgroup_get_oom_group
  - mm/memcontrol.c:mem_cgroup_iter
```
```
In mm/vmpressure.c (ffffffff812c907c)
Location: include/linux/memcontrol.h:438
Inline: True
Inline callers:
  - mm/vmpressure.c:vmpressure_work_fn
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff81277ed5)
Location: include/linux/memcontrol.h:415
Inline: True
Inline callers:
  - mm/backing-dev.c:cgwb_create
```
```
In mm/slab_common.c (ffffffff8127f264)
Location: include/linux/memcontrol.h:415
Inline: True
Inline callers:
  - mm/slab_common.c:memcg_slab_show
  - mm/slab_common.c:memcg_slab_next
  - mm/slab_common.c:memcg_slab_start
```
```
In mm/memcontrol.c (ffffffff812f47cc)
Location: include/linux/memcontrol.h:415
Inline: True
Inline callers:
  - mm/memcontrol.c:swap_events_show
  - mm/memcontrol.c:swap_max_write
  - mm/memcontrol.c:swap_max_show
  - mm/memcontrol.c:swap_high_write
  - mm/memcontrol.c:swap_high_show
  - mm/memcontrol.c:swap_current_read
  - mm/memcontrol.c:mem_cgroup_sk_alloc
  - mm/memcontrol.c:memory_oom_group_write
  - mm/memcontrol.c:memory_oom_group_show
  - mm/memcontrol.c:memory_stat_show
  - mm/memcontrol.c:memory_events_local_show
  - mm/memcontrol.c:memory_events_show
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:memory_max_show
  - mm/memcontrol.c:memory_high_write
  - mm/memcontrol.c:memory_high_show
  - mm/memcontrol.c:memory_low_write
  - mm/memcontrol.c:memory_low_show
  - mm/memcontrol.c:memory_min_write
  - mm/memcontrol.c:memory_min_show
  - mm/memcontrol.c:memory_current_read
  - mm/memcontrol.c:mem_cgroup_css_reset
  - mm/memcontrol.c:mem_cgroup_css_free
  - mm/memcontrol.c:mem_cgroup_css_released
  - mm/memcontrol.c:mem_cgroup_css_offline
  - mm/memcontrol.c:mem_cgroup_css_online
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:mem_cgroup_flush_foreign
  - mm/memcontrol.c:mem_cgroup_wb_stats
  - mm/memcontrol.c:mem_cgroup_wb_domain
  - mm/memcontrol.c:mem_cgroup_oom_control_write
  - mm/memcontrol.c:mem_cgroup_oom_control_read
  - mm/memcontrol.c:mem_cgroup_swappiness_write
  - mm/memcontrol.c:mem_cgroup_swappiness_read
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:mem_cgroup_move_charge_write
  - mm/memcontrol.c:mem_cgroup_move_charge_read
  - mm/memcontrol.c:mem_cgroup_reset
  - mm/memcontrol.c:mem_cgroup_write
  - mm/memcontrol.c:mem_cgroup_read_u64
  - mm/memcontrol.c:mem_cgroup_hierarchy_write
  - mm/memcontrol.c:mem_cgroup_hierarchy_write
  - mm/memcontrol.c:mem_cgroup_hierarchy_read
  - mm/memcontrol.c:mem_cgroup_force_empty_write
  - mm/memcontrol.c:memcg_kmem_get_cache
  - mm/memcontrol.c:mem_cgroup_get_oom_group
  - mm/memcontrol.c:mem_cgroup_iter
```
```
In mm/vmpressure.c (ffffffff812fe6e0)
Location: include/linux/memcontrol.h:415
Inline: True
Inline callers:
  - mm/vmpressure.c:vmpressure_work_fn
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
In mm/backing-dev.c (ffffffff81282665)
Location: include/linux/memcontrol.h:708
Inline: True
Inline callers:
  - mm/backing-dev.c:cgwb_create
```
```
In mm/memcontrol.c (ffffffff813000ac)
Location: include/linux/memcontrol.h:708
Inline: True
Inline callers:
  - mm/memcontrol.c:swap_events_show
  - mm/memcontrol.c:swap_max_write
  - mm/memcontrol.c:swap_max_show
  - mm/memcontrol.c:swap_high_write
  - mm/memcontrol.c:swap_high_show
  - mm/memcontrol.c:swap_current_read
  - mm/memcontrol.c:mem_cgroup_sk_alloc
  - mm/memcontrol.c:memory_oom_group_write
  - mm/memcontrol.c:memory_oom_group_show
  - mm/memcontrol.c:memory_numa_stat_show
  - mm/memcontrol.c:memory_stat_show
  - mm/memcontrol.c:memory_events_local_show
  - mm/memcontrol.c:memory_events_show
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:memory_max_show
  - mm/memcontrol.c:memory_high_write
  - mm/memcontrol.c:memory_high_show
  - mm/memcontrol.c:memory_low_write
  - mm/memcontrol.c:memory_low_show
  - mm/memcontrol.c:memory_min_write
  - mm/memcontrol.c:memory_min_show
  - mm/memcontrol.c:memory_current_read
  - mm/memcontrol.c:mem_cgroup_css_reset
  - mm/memcontrol.c:mem_cgroup_css_free
  - mm/memcontrol.c:mem_cgroup_css_released
  - mm/memcontrol.c:mem_cgroup_css_offline
  - mm/memcontrol.c:mem_cgroup_css_online
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:mem_cgroup_flush_foreign
  - mm/memcontrol.c:mem_cgroup_wb_stats
  - mm/memcontrol.c:mem_cgroup_wb_domain
  - mm/memcontrol.c:mem_cgroup_oom_control_write
  - mm/memcontrol.c:mem_cgroup_oom_control_read
  - mm/memcontrol.c:mem_cgroup_swappiness_write
  - mm/memcontrol.c:mem_cgroup_swappiness_read
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:mem_cgroup_move_charge_write
  - mm/memcontrol.c:mem_cgroup_move_charge_read
  - mm/memcontrol.c:mem_cgroup_reset
  - mm/memcontrol.c:mem_cgroup_write
  - mm/memcontrol.c:mem_cgroup_read_u64
  - mm/memcontrol.c:mem_cgroup_force_empty_write
  - mm/memcontrol.c:get_obj_cgroup_from_current
  - mm/memcontrol.c:mem_cgroup_get_oom_group
  - mm/memcontrol.c:mem_cgroup_iter
```
```
In mm/vmpressure.c (ffffffff8130aa20)
Location: include/linux/memcontrol.h:708
Inline: True
Inline callers:
  - mm/vmpressure.c:vmpressure_work_fn
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
In mm/backing-dev.c (ffffffff81287775)
Location: include/linux/memcontrol.h:793
Inline: True
Inline callers:
  - mm/backing-dev.c:cgwb_create
```
```
In mm/memcontrol.c (ffffffff81306eec)
Location: include/linux/memcontrol.h:793
Inline: True
Inline callers:
  - mm/memcontrol.c:swap_events_show
  - mm/memcontrol.c:swap_max_write
  - mm/memcontrol.c:swap_max_show
  - mm/memcontrol.c:swap_high_write
  - mm/memcontrol.c:swap_high_show
  - mm/memcontrol.c:swap_current_read
  - mm/memcontrol.c:mem_cgroup_sk_alloc
  - mm/memcontrol.c:memory_oom_group_write
  - mm/memcontrol.c:memory_oom_group_show
  - mm/memcontrol.c:memory_numa_stat_show
  - mm/memcontrol.c:memory_stat_show
  - mm/memcontrol.c:memory_events_local_show
  - mm/memcontrol.c:memory_events_show
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:memory_max_show
  - mm/memcontrol.c:memory_high_write
  - mm/memcontrol.c:memory_high_show
  - mm/memcontrol.c:memory_low_write
  - mm/memcontrol.c:memory_low_show
  - mm/memcontrol.c:memory_min_write
  - mm/memcontrol.c:memory_min_show
  - mm/memcontrol.c:memory_current_read
  - mm/memcontrol.c:mem_cgroup_css_rstat_flush
  - mm/memcontrol.c:mem_cgroup_css_reset
  - mm/memcontrol.c:mem_cgroup_css_free
  - mm/memcontrol.c:mem_cgroup_css_released
  - mm/memcontrol.c:mem_cgroup_css_offline
  - mm/memcontrol.c:mem_cgroup_css_online
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:mem_cgroup_flush_foreign
  - mm/memcontrol.c:mem_cgroup_wb_stats
  - mm/memcontrol.c:mem_cgroup_wb_domain
  - mm/memcontrol.c:mem_cgroup_oom_control_write
  - mm/memcontrol.c:mem_cgroup_oom_control_read
  - mm/memcontrol.c:mem_cgroup_swappiness_write
  - mm/memcontrol.c:mem_cgroup_swappiness_read
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:mem_cgroup_move_charge_write
  - mm/memcontrol.c:mem_cgroup_move_charge_read
  - mm/memcontrol.c:mem_cgroup_reset
  - mm/memcontrol.c:mem_cgroup_write
  - mm/memcontrol.c:mem_cgroup_read_u64
  - mm/memcontrol.c:mem_cgroup_force_empty_write
  - mm/memcontrol.c:__memcg_kmem_charge_page
  - mm/memcontrol.c:mem_cgroup_get_oom_group
  - mm/memcontrol.c:mem_cgroup_iter
```
```
In mm/vmpressure.c (ffffffff81311080)
Location: include/linux/memcontrol.h:793
Inline: True
Inline callers:
  - mm/vmpressure.c:vmpressure_work_fn
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
In mm/backing-dev.c (ffffffff812c6ed5)
Location: include/linux/memcontrol.h:789
Inline: True
Inline callers:
  - mm/backing-dev.c:cgwb_create
```
```
In mm/memcontrol.c (ffffffff81350bac)
Location: include/linux/memcontrol.h:789
Inline: True
Inline callers:
  - mm/memcontrol.c:swap_events_show
  - mm/memcontrol.c:swap_max_write
  - mm/memcontrol.c:swap_max_show
  - mm/memcontrol.c:swap_high_write
  - mm/memcontrol.c:swap_high_show
  - mm/memcontrol.c:swap_current_read
  - mm/memcontrol.c:mem_cgroup_sk_alloc
  - mm/memcontrol.c:memory_oom_group_write
  - mm/memcontrol.c:memory_oom_group_show
  - mm/memcontrol.c:memory_numa_stat_show
  - mm/memcontrol.c:memory_stat_show
  - mm/memcontrol.c:memory_events_local_show
  - mm/memcontrol.c:memory_events_show
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:memory_max_show
  - mm/memcontrol.c:memory_high_write
  - mm/memcontrol.c:memory_high_show
  - mm/memcontrol.c:memory_low_write
  - mm/memcontrol.c:memory_low_show
  - mm/memcontrol.c:memory_min_write
  - mm/memcontrol.c:memory_min_show
  - mm/memcontrol.c:memory_current_read
  - mm/memcontrol.c:mem_cgroup_css_rstat_flush
  - mm/memcontrol.c:mem_cgroup_css_reset
  - mm/memcontrol.c:mem_cgroup_css_free
  - mm/memcontrol.c:mem_cgroup_css_released
  - mm/memcontrol.c:mem_cgroup_css_offline
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:mem_cgroup_flush_foreign
  - mm/memcontrol.c:mem_cgroup_wb_stats
  - mm/memcontrol.c:mem_cgroup_wb_domain
  - mm/memcontrol.c:mem_cgroup_oom_control_write
  - mm/memcontrol.c:mem_cgroup_oom_control_read
  - mm/memcontrol.c:mem_cgroup_swappiness_write
  - mm/memcontrol.c:mem_cgroup_swappiness_read
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:mem_cgroup_move_charge_write
  - mm/memcontrol.c:mem_cgroup_move_charge_read
  - mm/memcontrol.c:mem_cgroup_reset
  - mm/memcontrol.c:mem_cgroup_write
  - mm/memcontrol.c:mem_cgroup_read_u64
  - mm/memcontrol.c:mem_cgroup_force_empty_write
  - mm/memcontrol.c:__memcg_kmem_charge_page
  - mm/memcontrol.c:mem_cgroup_get_oom_group
  - mm/memcontrol.c:mem_cgroup_iter
  - mm/memcontrol.c:get_mem_cgroup_from_mm
```
```
In fs/fs-writeback.c (ffffffff813b0768)
Location: include/linux/memcontrol.h:789
Inline: True
Inline callers:
  - fs/fs-writeback.c:cgroup_writeback_by_id
```
```
In drivers/block/loop.c (ffffffff81870022)
Location: include/linux/memcontrol.h:789
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_process_work
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
In mm/oom_kill.c (0)
Location: include/linux/memcontrol.h:790
Inline: True
```
```
In mm/swap.c (0)
Location: include/linux/memcontrol.h:790
Inline: True
```
```
In mm/vmscan.c (0)
Location: include/linux/memcontrol.h:790
Inline: True
```
```
In mm/backing-dev.c (0)
Location: include/linux/memcontrol.h:790
Inline: True
```
```
In mm/list_lru.c (0)
Location: include/linux/memcontrol.h:790
Inline: True
```
```
In mm/workingset.c (0)
Location: include/linux/memcontrol.h:790
Inline: True
```
```
In mm/memcontrol.c (0)
Location: include/linux/memcontrol.h:790
Inline: True
```
```
In mm/vmpressure.c (0)
Location: include/linux/memcontrol.h:790
Inline: True
```
```
In fs/fs-writeback.c (0)
Location: include/linux/memcontrol.h:790
Inline: True
```
```
In drivers/block/loop.c (0)
Location: include/linux/memcontrol.h:790
Inline: True
```
```
In net/core/sock.c (0)
Location: include/linux/memcontrol.h:790
Inline: True
```
```
In net/ipv4/tcp.c (0)
Location: include/linux/memcontrol.h:790
Inline: True
```
```
In net/ipv4/tcp_input.c (0)
Location: include/linux/memcontrol.h:790
Inline: True
```
```
In net/ipv4/tcp_output.c (0)
Location: include/linux/memcontrol.h:790
Inline: True
```
```
In net/ipv4/tcp_timer.c (0)
Location: include/linux/memcontrol.h:790
Inline: True
```
```
In net/mptcp/protocol.c (0)
Location: include/linux/memcontrol.h:790
Inline: True
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
In mm/oom_kill.c (0)
Location: include/linux/memcontrol.h:772
Inline: True
```
```
In mm/swap.c (0)
Location: include/linux/memcontrol.h:772
Inline: True
```
```
In mm/vmscan.c (0)
Location: include/linux/memcontrol.h:772
Inline: True
```
```
In mm/backing-dev.c (0)
Location: include/linux/memcontrol.h:772
Inline: True
```
```
In mm/list_lru.c (0)
Location: include/linux/memcontrol.h:772
Inline: True
```
```
In mm/workingset.c (0)
Location: include/linux/memcontrol.h:772
Inline: True
```
```
In mm/memcontrol.c (0)
Location: include/linux/memcontrol.h:772
Inline: True
```
```
In mm/vmpressure.c (0)
Location: include/linux/memcontrol.h:772
Inline: True
```
```
In fs/fs-writeback.c (0)
Location: include/linux/memcontrol.h:772
Inline: True
```
```
In drivers/block/loop.c (0)
Location: include/linux/memcontrol.h:772
Inline: True
```
```
In net/core/sock.c (0)
Location: include/linux/memcontrol.h:772
Inline: True
```
```
In net/ipv4/tcp.c (0)
Location: include/linux/memcontrol.h:772
Inline: True
```
```
In net/ipv4/tcp_input.c (0)
Location: include/linux/memcontrol.h:772
Inline: True
```
```
In net/ipv4/tcp_output.c (0)
Location: include/linux/memcontrol.h:772
Inline: True
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
In mm/oom_kill.c (0)
Location: include/linux/memcontrol.h:785
Inline: True
```
```
In mm/swap.c (0)
Location: include/linux/memcontrol.h:785
Inline: True
```
```
In mm/vmscan.c (0)
Location: include/linux/memcontrol.h:785
Inline: True
```
```
In mm/backing-dev.c (0)
Location: include/linux/memcontrol.h:785
Inline: True
```
```
In mm/list_lru.c (0)
Location: include/linux/memcontrol.h:785
Inline: True
```
```
In mm/workingset.c (0)
Location: include/linux/memcontrol.h:785
Inline: True
```
```
In mm/memcontrol.c (0)
Location: include/linux/memcontrol.h:785
Inline: True
```
```
In mm/vmpressure.c (0)
Location: include/linux/memcontrol.h:785
Inline: True
```
```
In fs/fs-writeback.c (0)
Location: include/linux/memcontrol.h:785
Inline: True
```
```
In drivers/block/loop.c (0)
Location: include/linux/memcontrol.h:785
Inline: True
```
```
In net/core/sock.c (0)
Location: include/linux/memcontrol.h:785
Inline: True
```
```
In net/ipv4/tcp.c (0)
Location: include/linux/memcontrol.h:785
Inline: True
```
```
In net/ipv4/tcp_input.c (0)
Location: include/linux/memcontrol.h:785
Inline: True
```
```
In net/ipv4/tcp_output.c (0)
Location: include/linux/memcontrol.h:785
Inline: True
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
In mm/oom_kill.c (0)
Location: include/linux/memcontrol.h:800
Inline: True
```
```
In mm/swap.c (0)
Location: include/linux/memcontrol.h:800
Inline: True
```
```
In mm/vmscan.c (0)
Location: include/linux/memcontrol.h:800
Inline: True
```
```
In mm/shrinker.c (0)
Location: include/linux/memcontrol.h:800
Inline: True
```
```
In mm/backing-dev.c (0)
Location: include/linux/memcontrol.h:800
Inline: True
```
```
In mm/list_lru.c (0)
Location: include/linux/memcontrol.h:800
Inline: True
```
```
In mm/workingset.c (0)
Location: include/linux/memcontrol.h:800
Inline: True
```
```
In mm/memcontrol.c (0)
Location: include/linux/memcontrol.h:800
Inline: True
```
```
In mm/vmpressure.c (0)
Location: include/linux/memcontrol.h:800
Inline: True
```
```
In fs/fs-writeback.c (0)
Location: include/linux/memcontrol.h:800
Inline: True
```
```
In drivers/block/loop.c (0)
Location: include/linux/memcontrol.h:800
Inline: True
```
```
In net/ipv4/tcp.c (0)
Location: include/linux/memcontrol.h:800
Inline: True
```
```
In net/ipv4/tcp_input.c (0)
Location: include/linux/memcontrol.h:800
Inline: True
```
```
In net/ipv4/tcp_output.c (0)
Location: include/linux/memcontrol.h:800
Inline: True
```
```
In net/mptcp/protocol.c (0)
Location: include/linux/memcontrol.h:800
Inline: True
```
```
In net/mptcp/sockopt.c (0)
Location: include/linux/memcontrol.h:800
Inline: True
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffff8000102df45c)
Location: include/linux/memcontrol.h:438
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_get_create
```
```
In mm/slab_common.c (ffff8000102e7e5c)
Location: include/linux/memcontrol.h:438
Inline: True
Inline callers:
  - mm/slab_common.c:memcg_slab_show
  - mm/slab_common.c:memcg_slab_next
  - mm/slab_common.c:memcg_slab_start
```
```
In mm/memcontrol.c (ffff8000103612ec)
Location: include/linux/memcontrol.h:438
Inline: True
Inline callers:
  - mm/memcontrol.c:swap_events_show
  - mm/memcontrol.c:swap_max_write
  - mm/memcontrol.c:swap_max_show
  - mm/memcontrol.c:swap_current_read
  - mm/memcontrol.c:mem_cgroup_sk_alloc
  - mm/memcontrol.c:memory_oom_group_write
  - mm/memcontrol.c:memory_oom_group_show
  - mm/memcontrol.c:memory_stat_show
  - mm/memcontrol.c:memory_events_local_show
  - mm/memcontrol.c:memory_events_show
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:memory_max_show
  - mm/memcontrol.c:memory_high_write
  - mm/memcontrol.c:memory_high_show
  - mm/memcontrol.c:memory_low_write
  - mm/memcontrol.c:memory_low_show
  - mm/memcontrol.c:memory_min_write
  - mm/memcontrol.c:memory_min_show
  - mm/memcontrol.c:memory_current_read
  - mm/memcontrol.c:mem_cgroup_css_reset
  - mm/memcontrol.c:mem_cgroup_css_free
  - mm/memcontrol.c:mem_cgroup_css_released
  - mm/memcontrol.c:mem_cgroup_css_offline
  - mm/memcontrol.c:mem_cgroup_css_online
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:mem_cgroup_flush_foreign
  - mm/memcontrol.c:mem_cgroup_wb_stats
  - mm/memcontrol.c:mem_cgroup_wb_domain
  - mm/memcontrol.c:mem_cgroup_oom_control_write
  - mm/memcontrol.c:mem_cgroup_oom_control_read
  - mm/memcontrol.c:mem_cgroup_swappiness_write
  - mm/memcontrol.c:mem_cgroup_swappiness_read
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:mem_cgroup_move_charge_write
  - mm/memcontrol.c:mem_cgroup_move_charge_read
  - mm/memcontrol.c:mem_cgroup_reset
  - mm/memcontrol.c:mem_cgroup_write
  - mm/memcontrol.c:mem_cgroup_read_u64
  - mm/memcontrol.c:mem_cgroup_hierarchy_write
  - mm/memcontrol.c:mem_cgroup_hierarchy_write
  - mm/memcontrol.c:mem_cgroup_hierarchy_read
  - mm/memcontrol.c:mem_cgroup_force_empty_write
  - mm/memcontrol.c:memcg_kmem_get_cache
  - mm/memcontrol.c:mem_cgroup_get_oom_group
  - mm/memcontrol.c:mem_cgroup_iter
```
```
In mm/vmpressure.c (ffff80001036c538)
Location: include/linux/memcontrol.h:438
Inline: True
Inline callers:
  - mm/vmpressure.c:vmpressure_work_fn
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (c05042dc)
Location: include/linux/memcontrol.h:438
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_get_create
```
```
In mm/slab_common.c (c050bf10)
Location: include/linux/memcontrol.h:438
Inline: True
Inline callers:
  - mm/slab_common.c:memcg_slab_show
  - mm/slab_common.c:memcg_slab_next
  - mm/slab_common.c:memcg_slab_start
```
```
In mm/memcontrol.c (c05538bc)
Location: include/linux/memcontrol.h:438
Inline: True
Inline callers:
  - mm/memcontrol.c:swap_events_show
  - mm/memcontrol.c:swap_max_write
  - mm/memcontrol.c:swap_max_show
  - mm/memcontrol.c:swap_current_read
  - mm/memcontrol.c:mem_cgroup_sk_alloc
  - mm/memcontrol.c:memory_oom_group_write
  - mm/memcontrol.c:memory_oom_group_show
  - mm/memcontrol.c:memory_stat_show
  - mm/memcontrol.c:memory_events_local_show
  - mm/memcontrol.c:memory_events_show
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:memory_max_show
  - mm/memcontrol.c:memory_high_write
  - mm/memcontrol.c:memory_high_show
  - mm/memcontrol.c:memory_low_write
  - mm/memcontrol.c:memory_low_show
  - mm/memcontrol.c:memory_min_write
  - mm/memcontrol.c:memory_min_show
  - mm/memcontrol.c:memory_current_read
  - mm/memcontrol.c:mem_cgroup_css_reset
  - mm/memcontrol.c:mem_cgroup_css_free
  - mm/memcontrol.c:mem_cgroup_css_released
  - mm/memcontrol.c:mem_cgroup_css_offline
  - mm/memcontrol.c:mem_cgroup_css_online
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:mem_cgroup_flush_foreign
  - mm/memcontrol.c:mem_cgroup_wb_stats
  - mm/memcontrol.c:mem_cgroup_wb_domain
  - mm/memcontrol.c:mem_cgroup_oom_control_write
  - mm/memcontrol.c:mem_cgroup_oom_control_read
  - mm/memcontrol.c:mem_cgroup_swappiness_write
  - mm/memcontrol.c:mem_cgroup_swappiness_read
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:mem_cgroup_move_charge_write
  - mm/memcontrol.c:mem_cgroup_move_charge_read
  - mm/memcontrol.c:mem_cgroup_reset
  - mm/memcontrol.c:mem_cgroup_write
  - mm/memcontrol.c:mem_cgroup_read_u64
  - mm/memcontrol.c:mem_cgroup_hierarchy_write
  - mm/memcontrol.c:mem_cgroup_hierarchy_write
  - mm/memcontrol.c:mem_cgroup_hierarchy_read
  - mm/memcontrol.c:mem_cgroup_force_empty_write
  - mm/memcontrol.c:memcg_kmem_get_cache
  - mm/memcontrol.c:mem_cgroup_get_oom_group
  - mm/memcontrol.c:mem_cgroup_iter
```
```
In mm/vmpressure.c (c055d630)
Location: include/linux/memcontrol.h:438
Inline: True
Inline callers:
  - mm/vmpressure.c:vmpressure_work_fn
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (c00000000039efbc)
Location: include/linux/memcontrol.h:438
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_get_create
```
```
In mm/slab_common.c (c0000000003a9e40)
Location: include/linux/memcontrol.h:438
Inline: True
Inline callers:
  - mm/slab_common.c:memcg_slab_show
  - mm/slab_common.c:memcg_slab_next
  - mm/slab_common.c:memcg_slab_start
```
```
In mm/memcontrol.c (c00000000044c6d8)
Location: include/linux/memcontrol.h:438
Inline: True
Inline callers:
  - mm/memcontrol.c:swap_events_show
  - mm/memcontrol.c:swap_max_write
  - mm/memcontrol.c:swap_max_show
  - mm/memcontrol.c:swap_current_read
  - mm/memcontrol.c:mem_cgroup_sk_alloc
  - mm/memcontrol.c:memory_oom_group_write
  - mm/memcontrol.c:memory_oom_group_show
  - mm/memcontrol.c:memory_stat_show
  - mm/memcontrol.c:memory_events_local_show
  - mm/memcontrol.c:memory_events_show
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:memory_max_show
  - mm/memcontrol.c:memory_high_write
  - mm/memcontrol.c:memory_high_show
  - mm/memcontrol.c:memory_low_write
  - mm/memcontrol.c:memory_low_show
  - mm/memcontrol.c:memory_min_write
  - mm/memcontrol.c:memory_min_show
  - mm/memcontrol.c:memory_current_read
  - mm/memcontrol.c:mem_cgroup_css_reset
  - mm/memcontrol.c:mem_cgroup_css_free
  - mm/memcontrol.c:mem_cgroup_css_released
  - mm/memcontrol.c:mem_cgroup_css_offline
  - mm/memcontrol.c:mem_cgroup_css_online
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:mem_cgroup_flush_foreign
  - mm/memcontrol.c:mem_cgroup_wb_stats
  - mm/memcontrol.c:mem_cgroup_wb_domain
  - mm/memcontrol.c:mem_cgroup_oom_control_write
  - mm/memcontrol.c:mem_cgroup_oom_control_read
  - mm/memcontrol.c:mem_cgroup_swappiness_write
  - mm/memcontrol.c:mem_cgroup_swappiness_read
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:mem_cgroup_move_charge_write
  - mm/memcontrol.c:mem_cgroup_move_charge_read
  - mm/memcontrol.c:mem_cgroup_reset
  - mm/memcontrol.c:mem_cgroup_write
  - mm/memcontrol.c:mem_cgroup_read_u64
  - mm/memcontrol.c:mem_cgroup_hierarchy_write
  - mm/memcontrol.c:mem_cgroup_hierarchy_write
  - mm/memcontrol.c:mem_cgroup_hierarchy_read
  - mm/memcontrol.c:mem_cgroup_force_empty_write
  - mm/memcontrol.c:memcg_kmem_get_cache
  - mm/memcontrol.c:mem_cgroup_get_oom_group
  - mm/memcontrol.c:mem_cgroup_iter
```
```
In mm/vmpressure.c (c00000000045c2a4)
Location: include/linux/memcontrol.h:438
Inline: True
Inline callers:
  - mm/vmpressure.c:vmpressure_work_fn
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (0)
Location: include/linux/memcontrol.h:438
Inline: True
```
```
In mm/slab_common.c (0)
Location: include/linux/memcontrol.h:438
Inline: True
```
```
In mm/memcontrol.c (ffffffe000248798)
Location: include/linux/memcontrol.h:438
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_sk_alloc
  - mm/memcontrol.c:mem_cgroup_hierarchy_write
  - mm/memcontrol.c:memcg_kmem_get_cache
```
```
In mm/vmpressure.c (0)
Location: include/linux/memcontrol.h:438
Inline: True
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff8124231b)
Location: include/linux/memcontrol.h:438
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_get_create
```
```
In mm/slab_common.c (ffffffff81249244)
Location: include/linux/memcontrol.h:438
Inline: True
Inline callers:
  - mm/slab_common.c:memcg_slab_show
  - mm/slab_common.c:memcg_slab_next
  - mm/slab_common.c:memcg_slab_start
```
```
In mm/memcontrol.c (ffffffff812b7aac)
Location: include/linux/memcontrol.h:438
Inline: True
Inline callers:
  - mm/memcontrol.c:swap_events_show
  - mm/memcontrol.c:swap_max_write
  - mm/memcontrol.c:swap_max_show
  - mm/memcontrol.c:swap_current_read
  - mm/memcontrol.c:mem_cgroup_sk_alloc
  - mm/memcontrol.c:memory_oom_group_write
  - mm/memcontrol.c:memory_oom_group_show
  - mm/memcontrol.c:memory_stat_show
  - mm/memcontrol.c:memory_events_local_show
  - mm/memcontrol.c:memory_events_show
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:memory_max_show
  - mm/memcontrol.c:memory_high_write
  - mm/memcontrol.c:memory_high_show
  - mm/memcontrol.c:memory_low_write
  - mm/memcontrol.c:memory_low_show
  - mm/memcontrol.c:memory_min_write
  - mm/memcontrol.c:memory_min_show
  - mm/memcontrol.c:memory_current_read
  - mm/memcontrol.c:mem_cgroup_css_reset
  - mm/memcontrol.c:mem_cgroup_css_free
  - mm/memcontrol.c:mem_cgroup_css_released
  - mm/memcontrol.c:mem_cgroup_css_offline
  - mm/memcontrol.c:mem_cgroup_css_online
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:mem_cgroup_flush_foreign
  - mm/memcontrol.c:mem_cgroup_wb_stats
  - mm/memcontrol.c:mem_cgroup_wb_domain
  - mm/memcontrol.c:mem_cgroup_oom_control_write
  - mm/memcontrol.c:mem_cgroup_oom_control_read
  - mm/memcontrol.c:mem_cgroup_swappiness_write
  - mm/memcontrol.c:mem_cgroup_swappiness_read
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:mem_cgroup_move_charge_write
  - mm/memcontrol.c:mem_cgroup_move_charge_read
  - mm/memcontrol.c:mem_cgroup_reset
  - mm/memcontrol.c:mem_cgroup_write
  - mm/memcontrol.c:mem_cgroup_read_u64
  - mm/memcontrol.c:mem_cgroup_hierarchy_write
  - mm/memcontrol.c:mem_cgroup_hierarchy_write
  - mm/memcontrol.c:mem_cgroup_hierarchy_read
  - mm/memcontrol.c:mem_cgroup_force_empty_write
  - mm/memcontrol.c:memcg_kmem_get_cache
  - mm/memcontrol.c:mem_cgroup_get_oom_group
  - mm/memcontrol.c:mem_cgroup_iter
```
```
In mm/vmpressure.c (ffffffff812c165c)
Location: include/linux/memcontrol.h:438
Inline: True
Inline callers:
  - mm/vmpressure.c:vmpressure_work_fn
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff812352eb)
Location: include/linux/memcontrol.h:438
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_get_create
```
```
In mm/slab_common.c (ffffffff8123c1f4)
Location: include/linux/memcontrol.h:438
Inline: True
Inline callers:
  - mm/slab_common.c:memcg_slab_show
  - mm/slab_common.c:memcg_slab_next
  - mm/slab_common.c:memcg_slab_start
```
```
In mm/memcontrol.c (ffffffff812a8c7c)
Location: include/linux/memcontrol.h:438
Inline: True
Inline callers:
  - mm/memcontrol.c:swap_events_show
  - mm/memcontrol.c:swap_max_write
  - mm/memcontrol.c:swap_max_show
  - mm/memcontrol.c:swap_current_read
  - mm/memcontrol.c:mem_cgroup_sk_alloc
  - mm/memcontrol.c:memory_oom_group_write
  - mm/memcontrol.c:memory_oom_group_show
  - mm/memcontrol.c:memory_stat_show
  - mm/memcontrol.c:memory_events_local_show
  - mm/memcontrol.c:memory_events_show
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:memory_max_show
  - mm/memcontrol.c:memory_high_write
  - mm/memcontrol.c:memory_high_show
  - mm/memcontrol.c:memory_low_write
  - mm/memcontrol.c:memory_low_show
  - mm/memcontrol.c:memory_min_write
  - mm/memcontrol.c:memory_min_show
  - mm/memcontrol.c:memory_current_read
  - mm/memcontrol.c:mem_cgroup_css_reset
  - mm/memcontrol.c:mem_cgroup_css_free
  - mm/memcontrol.c:mem_cgroup_css_released
  - mm/memcontrol.c:mem_cgroup_css_offline
  - mm/memcontrol.c:mem_cgroup_css_online
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:mem_cgroup_flush_foreign
  - mm/memcontrol.c:mem_cgroup_wb_stats
  - mm/memcontrol.c:mem_cgroup_wb_domain
  - mm/memcontrol.c:mem_cgroup_oom_control_write
  - mm/memcontrol.c:mem_cgroup_oom_control_read
  - mm/memcontrol.c:mem_cgroup_swappiness_write
  - mm/memcontrol.c:mem_cgroup_swappiness_read
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:mem_cgroup_move_charge_write
  - mm/memcontrol.c:mem_cgroup_move_charge_read
  - mm/memcontrol.c:mem_cgroup_reset
  - mm/memcontrol.c:mem_cgroup_write
  - mm/memcontrol.c:mem_cgroup_read_u64
  - mm/memcontrol.c:mem_cgroup_hierarchy_write
  - mm/memcontrol.c:mem_cgroup_hierarchy_write
  - mm/memcontrol.c:mem_cgroup_hierarchy_read
  - mm/memcontrol.c:mem_cgroup_force_empty_write
  - mm/memcontrol.c:memcg_kmem_get_cache
  - mm/memcontrol.c:mem_cgroup_get_oom_group
  - mm/memcontrol.c:mem_cgroup_iter
```
```
In mm/vmpressure.c (ffffffff812b26ac)
Location: include/linux/memcontrol.h:438
Inline: True
Inline callers:
  - mm/vmpressure.c:vmpressure_work_fn
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff812400bb)
Location: include/linux/memcontrol.h:438
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_get_create
```
```
In mm/slab_common.c (ffffffff81246fe4)
Location: include/linux/memcontrol.h:438
Inline: True
Inline callers:
  - mm/slab_common.c:memcg_slab_show
  - mm/slab_common.c:memcg_slab_next
  - mm/slab_common.c:memcg_slab_start
```
```
In mm/memcontrol.c (ffffffff812b58bc)
Location: include/linux/memcontrol.h:438
Inline: True
Inline callers:
  - mm/memcontrol.c:swap_events_show
  - mm/memcontrol.c:swap_max_write
  - mm/memcontrol.c:swap_max_show
  - mm/memcontrol.c:swap_current_read
  - mm/memcontrol.c:mem_cgroup_sk_alloc
  - mm/memcontrol.c:memory_oom_group_write
  - mm/memcontrol.c:memory_oom_group_show
  - mm/memcontrol.c:memory_stat_show
  - mm/memcontrol.c:memory_events_local_show
  - mm/memcontrol.c:memory_events_show
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:memory_max_show
  - mm/memcontrol.c:memory_high_write
  - mm/memcontrol.c:memory_high_show
  - mm/memcontrol.c:memory_low_write
  - mm/memcontrol.c:memory_low_show
  - mm/memcontrol.c:memory_min_write
  - mm/memcontrol.c:memory_min_show
  - mm/memcontrol.c:memory_current_read
  - mm/memcontrol.c:mem_cgroup_css_reset
  - mm/memcontrol.c:mem_cgroup_css_free
  - mm/memcontrol.c:mem_cgroup_css_released
  - mm/memcontrol.c:mem_cgroup_css_offline
  - mm/memcontrol.c:mem_cgroup_css_online
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:mem_cgroup_flush_foreign
  - mm/memcontrol.c:mem_cgroup_wb_stats
  - mm/memcontrol.c:mem_cgroup_wb_domain
  - mm/memcontrol.c:mem_cgroup_oom_control_write
  - mm/memcontrol.c:mem_cgroup_oom_control_read
  - mm/memcontrol.c:mem_cgroup_swappiness_write
  - mm/memcontrol.c:mem_cgroup_swappiness_read
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:mem_cgroup_move_charge_write
  - mm/memcontrol.c:mem_cgroup_move_charge_read
  - mm/memcontrol.c:mem_cgroup_reset
  - mm/memcontrol.c:mem_cgroup_write
  - mm/memcontrol.c:mem_cgroup_read_u64
  - mm/memcontrol.c:mem_cgroup_hierarchy_write
  - mm/memcontrol.c:mem_cgroup_hierarchy_write
  - mm/memcontrol.c:mem_cgroup_hierarchy_read
  - mm/memcontrol.c:mem_cgroup_force_empty_write
  - mm/memcontrol.c:memcg_kmem_get_cache
  - mm/memcontrol.c:mem_cgroup_get_oom_group
  - mm/memcontrol.c:mem_cgroup_iter
```
```
In mm/vmpressure.c (ffffffff812bf46c)
Location: include/linux/memcontrol.h:438
Inline: True
Inline callers:
  - mm/vmpressure.c:vmpressure_work_fn
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff8124f80c)
Location: include/linux/memcontrol.h:438
Inline: True
Inline callers:
  - mm/backing-dev.c:wb_get_create
```
```
In mm/slab_common.c (ffffffff81256814)
Location: include/linux/memcontrol.h:438
Inline: True
Inline callers:
  - mm/slab_common.c:memcg_slab_show
  - mm/slab_common.c:memcg_slab_next
  - mm/slab_common.c:memcg_slab_start
```
```
In mm/memcontrol.c (ffffffff812c5ddc)
Location: include/linux/memcontrol.h:438
Inline: True
Inline callers:
  - mm/memcontrol.c:swap_events_show
  - mm/memcontrol.c:swap_max_write
  - mm/memcontrol.c:swap_max_show
  - mm/memcontrol.c:swap_current_read
  - mm/memcontrol.c:mem_cgroup_sk_alloc
  - mm/memcontrol.c:memory_oom_group_write
  - mm/memcontrol.c:memory_oom_group_show
  - mm/memcontrol.c:memory_stat_show
  - mm/memcontrol.c:memory_events_local_show
  - mm/memcontrol.c:memory_events_show
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:memory_max_show
  - mm/memcontrol.c:memory_high_write
  - mm/memcontrol.c:memory_high_show
  - mm/memcontrol.c:memory_low_write
  - mm/memcontrol.c:memory_low_show
  - mm/memcontrol.c:memory_min_write
  - mm/memcontrol.c:memory_min_show
  - mm/memcontrol.c:memory_current_read
  - mm/memcontrol.c:mem_cgroup_css_reset
  - mm/memcontrol.c:mem_cgroup_css_free
  - mm/memcontrol.c:mem_cgroup_css_released
  - mm/memcontrol.c:mem_cgroup_css_offline
  - mm/memcontrol.c:mem_cgroup_css_online
  - mm/memcontrol.c:mem_cgroup_css_alloc
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:mem_cgroup_flush_foreign
  - mm/memcontrol.c:mem_cgroup_wb_stats
  - mm/memcontrol.c:mem_cgroup_wb_domain
  - mm/memcontrol.c:mem_cgroup_oom_control_write
  - mm/memcontrol.c:mem_cgroup_oom_control_read
  - mm/memcontrol.c:mem_cgroup_swappiness_write
  - mm/memcontrol.c:mem_cgroup_swappiness_read
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:memcg_numa_stat_show
  - mm/memcontrol.c:mem_cgroup_move_charge_write
  - mm/memcontrol.c:mem_cgroup_move_charge_read
  - mm/memcontrol.c:mem_cgroup_reset
  - mm/memcontrol.c:mem_cgroup_write
  - mm/memcontrol.c:mem_cgroup_read_u64
  - mm/memcontrol.c:mem_cgroup_hierarchy_write
  - mm/memcontrol.c:mem_cgroup_hierarchy_write
  - mm/memcontrol.c:mem_cgroup_hierarchy_read
  - mm/memcontrol.c:mem_cgroup_force_empty_write
  - mm/memcontrol.c:memcg_kmem_get_cache
  - mm/memcontrol.c:mem_cgroup_get_oom_group
  - mm/memcontrol.c:mem_cgroup_iter
```
```
In mm/vmpressure.c (ffffffff812cfecd)
Location: include/linux/memcontrol.h:438
Inline: True
Inline callers:
  - mm/vmpressure.c:vmpressure_work_fn
```
</details>
</li>
</ul>

## Differences
