# Function: <code>parent_mem_cgroup</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
struct mem_cgroup *parent_mem_cgroup(struct mem_cgroup *memcg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff811f9650)
Location: mm/memcontrol.c:4213
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_css_released
  - mm/memcontrol.c:mem_cgroup_css_offline
  - mm/memcontrol.c:mem_cgroup_css_online
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:page_cgroup_ino
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:mem_cgroup_handle_over_high
  - mm/memcontrol.c:mem_cgroup_wb_stats
  - mm/memcontrol.c:mem_cgroup_low
Direct callers:
  - net/core/sock.c:__sk_mem_schedule
  - net/core/sock.c:__sk_mem_schedule
  - net/core/sock.c:sk_clone_lock
  - net/ipv4/tcp.c:tcp_init_sock
  - net/ipv4/tcp_ipv4.c:tcp_v4_destroy_sock
  - net/ipv4/tcp_memcontrol.c:tcp_init_cgroup
```
**Symbols:**

```
ffffffff811f9650-ffffffff811f9671: parent_mem_cgroup (STB_GLOBAL)
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
In mm/memcontrol.c (ffffffff81224c8e)
Location: include/linux/memcontrol.h:386
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_swap_full
  - mm/memcontrol.c:mem_cgroup_get_nr_swap_pages
  - mm/memcontrol.c:mem_cgroup_id_get_online
  - mm/memcontrol.c:mem_cgroup_low
  - mm/memcontrol.c:mem_cgroup_css_released
  - mm/memcontrol.c:mem_cgroup_wb_stats
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:page_cgroup_ino
```
```
In mm/vmpressure.c (ffffffff81224e25)
Location: include/linux/memcontrol.h:386
Inline: True
Inline callers:
  - mm/vmpressure.c:vmpressure_work_fn
```
```
In net/core/sock.c (ffffffff817681a0)
Location: include/linux/memcontrol.h:386
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_schedule
```
```
In net/ipv4/tcp.c (ffffffff817d58d7)
Location: include/linux/memcontrol.h:386
Inline: True
Inline callers:
  - net/ipv4/tcp.c:sk_stream_alloc_skb
```
```
In net/ipv4/tcp_input.c (ffffffff817dbdfc)
Location: include/linux/memcontrol.h:386
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_check_space
  - net/ipv4/tcp_input.c:tcp_try_rmem_schedule
  - net/ipv4/tcp_input.c:tcp_try_rmem_schedule
```
```
In net/ipv4/tcp_output.c (ffffffff817e634b)
Location: include/linux/memcontrol.h:386
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_output.c:__tcp_select_window
```
```
In net/ipv4/tcp_timer.c (ffffffff817e6fb5)
Location: include/linux/memcontrol.h:386
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
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
In mm/memcontrol.c (ffffffff8123727e)
Location: include/linux/memcontrol.h:388
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_swap_full
  - mm/memcontrol.c:mem_cgroup_get_nr_swap_pages
  - mm/memcontrol.c:mem_cgroup_id_get_online
  - mm/memcontrol.c:mem_cgroup_low
  - mm/memcontrol.c:mem_cgroup_css_released
  - mm/memcontrol.c:mem_cgroup_wb_stats
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:page_cgroup_ino
```
```
In mm/vmpressure.c (ffffffff81237415)
Location: include/linux/memcontrol.h:388
Inline: True
Inline callers:
  - mm/vmpressure.c:vmpressure_work_fn
```
```
In net/core/sock.c (ffffffff81795195)
Location: include/linux/memcontrol.h:388
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_raise_allocated
```
```
In net/ipv4/tcp.c (ffffffff81805901)
Location: include/linux/memcontrol.h:388
Inline: True
Inline callers:
  - net/ipv4/tcp.c:sk_stream_alloc_skb
```
```
In net/ipv4/tcp_input.c (ffffffff8180bed2)
Location: include/linux/memcontrol.h:388
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_check_space
  - net/ipv4/tcp_input.c:tcp_prune_ofo_queue
```
```
In net/ipv4/tcp_output.c (ffffffff81816a6b)
Location: include/linux/memcontrol.h:388
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_output.c:__tcp_select_window
```
```
In net/ipv4/tcp_timer.c (ffffffff818176fb)
Location: include/linux/memcontrol.h:388
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
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
In mm/memcontrol.c (ffffffff81242d3e)
Location: include/linux/memcontrol.h:382
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_swap_full
  - mm/memcontrol.c:mem_cgroup_get_nr_swap_pages
  - mm/memcontrol.c:mem_cgroup_id_get_online
  - mm/memcontrol.c:mem_cgroup_low
  - mm/memcontrol.c:mem_cgroup_css_released
  - mm/memcontrol.c:mem_cgroup_wb_stats
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:page_cgroup_ino
```
```
In mm/vmpressure.c (ffffffff81242f01)
Location: include/linux/memcontrol.h:382
Inline: True
Inline callers:
  - mm/vmpressure.c:vmpressure_work_fn
```
```
In net/core/sock.c (ffffffff817b38d1)
Location: include/linux/memcontrol.h:382
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_raise_allocated
```
```
In net/ipv4/tcp.c (ffffffff81825d44)
Location: include/linux/memcontrol.h:382
Inline: True
Inline callers:
  - net/ipv4/tcp.c:sk_stream_alloc_skb
```
```
In net/ipv4/tcp_input.c (ffffffff81828012)
Location: include/linux/memcontrol.h:382
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_check_space
```
```
In net/ipv4/tcp_output.c (ffffffff81836da9)
Location: include/linux/memcontrol.h:382
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_output.c:__tcp_select_window
```
```
In net/ipv4/tcp_timer.c (ffffffff81837ad3)
Location: include/linux/memcontrol.h:382
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
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
In mm/memcontrol.c (ffffffff81262b8e)
Location: include/linux/memcontrol.h:382
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_swap_full
  - mm/memcontrol.c:mem_cgroup_get_nr_swap_pages
  - mm/memcontrol.c:mem_cgroup_id_get_online
  - mm/memcontrol.c:mem_cgroup_low
  - mm/memcontrol.c:mem_cgroup_css_released
  - mm/memcontrol.c:mem_cgroup_wb_stats
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:page_cgroup_ino
```
```
In mm/vmpressure.c (ffffffff81262d51)
Location: include/linux/memcontrol.h:382
Inline: True
Inline callers:
  - mm/vmpressure.c:vmpressure_work_fn
```
```
In net/core/sock.c (ffffffff8182bcf7)
Location: include/linux/memcontrol.h:382
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_raise_allocated
```
```
In net/ipv4/tcp.c (ffffffff818a3e00)
Location: include/linux/memcontrol.h:382
Inline: True
Inline callers:
  - net/ipv4/tcp.c:sk_stream_alloc_skb
```
```
In net/ipv4/tcp_input.c (ffffffff818a752d)
Location: include/linux/memcontrol.h:382
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_check_space
```
```
In net/ipv4/tcp_output.c (ffffffff818b63c6)
Location: include/linux/memcontrol.h:382
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_output.c:__tcp_select_window
```
```
In net/ipv4/tcp_timer.c (ffffffff818b724f)
Location: include/linux/memcontrol.h:382
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
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
In mm/memcontrol.c (ffffffff81286d3e)
Location: include/linux/memcontrol.h:415
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_swap_full
  - mm/memcontrol.c:mem_cgroup_get_nr_swap_pages
  - mm/memcontrol.c:mem_cgroup_id_get_online
  - mm/memcontrol.c:mem_cgroup_protected
  - mm/memcontrol.c:mem_cgroup_css_released
  - mm/memcontrol.c:mem_cgroup_wb_stats
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:page_cgroup_ino
```
```
In mm/vmpressure.c (ffffffff812870cc)
Location: include/linux/memcontrol.h:415
Inline: True
Inline callers:
  - mm/vmpressure.c:vmpressure_work_fn
```
```
In net/core/sock.c (ffffffff81875856)
Location: include/linux/memcontrol.h:415
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_raise_allocated
```
```
In net/ipv4/tcp.c (ffffffff818f9b7b)
Location: include/linux/memcontrol.h:415
Inline: True
Inline callers:
  - net/ipv4/tcp.c:sk_stream_alloc_skb
```
```
In net/ipv4/tcp_input.c (ffffffff819003e3)
Location: include/linux/memcontrol.h:415
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_check_space
```
```
In net/ipv4/tcp_output.c (ffffffff8190bc06)
Location: include/linux/memcontrol.h:415
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_output.c:__tcp_select_window
```
```
In net/ipv4/tcp_timer.c (ffffffff8190cc86)
Location: include/linux/memcontrol.h:415
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
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
In mm/memcontrol.c (ffffffff8129bc4e)
Location: include/linux/memcontrol.h:450
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_swap_full
  - mm/memcontrol.c:mem_cgroup_get_nr_swap_pages
  - mm/memcontrol.c:mem_cgroup_id_get_online
  - mm/memcontrol.c:mem_cgroup_protected
  - mm/memcontrol.c:mem_cgroup_css_released
  - mm/memcontrol.c:mem_cgroup_wb_stats
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:mem_cgroup_get_oom_group
  - mm/memcontrol.c:page_cgroup_ino
```
```
In mm/vmpressure.c (ffffffff8129c01c)
Location: include/linux/memcontrol.h:450
Inline: True
Inline callers:
  - mm/vmpressure.c:vmpressure_work_fn
```
```
In net/core/sock.c (ffffffff8189618c)
Location: include/linux/memcontrol.h:450
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_raise_allocated
```
```
In net/ipv4/tcp.c (ffffffff81927aab)
Location: include/linux/memcontrol.h:450
Inline: True
Inline callers:
  - net/ipv4/tcp.c:sk_stream_alloc_skb
```
```
In net/ipv4/tcp_input.c (ffffffff8192a7f3)
Location: include/linux/memcontrol.h:450
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_check_space
```
```
In net/ipv4/tcp_output.c (ffffffff81939ed3)
Location: include/linux/memcontrol.h:450
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_output.c:__tcp_select_window
```
```
In net/ipv4/tcp_timer.c (ffffffff8193af95)
Location: include/linux/memcontrol.h:450
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
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
In mm/oom_kill.c (ffffffff8121c10c)
Location: include/linux/memcontrol.h:456
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
```
```
In mm/vmscan.c (ffffffff8122d7a1)
Location: include/linux/memcontrol.h:456
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_node
```
```
In mm/slub.c (ffffffff81294073)
Location: include/linux/memcontrol.h:456
Inline: True
Inline callers:
  - mm/slub.c:alloc_slab_page
```
```
In mm/memcontrol.c (ffffffff812b6e30)
Location: include/linux/memcontrol.h:456
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_swap_full
  - mm/memcontrol.c:mem_cgroup_get_nr_swap_pages
  - mm/memcontrol.c:mem_cgroup_try_charge_swap
  - mm/memcontrol.c:mem_cgroup_id_get_online
  - mm/memcontrol.c:mem_cgroup_protected
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:mem_cgroup_css_released
  - mm/memcontrol.c:mem_cgroup_wb_stats
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:memcg_flush_percpu_vmevents
  - mm/memcontrol.c:memcg_flush_percpu_vmstats
  - mm/memcontrol.c:memcg_flush_percpu_vmstats
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:memcg_hotplug_cpu_dead
  - mm/memcontrol.c:memcg_hotplug_cpu_dead
  - mm/memcontrol.c:memcg_hotplug_cpu_dead
  - mm/memcontrol.c:mem_cgroup_get_oom_group
  - mm/memcontrol.c:__count_memcg_events
  - mm/memcontrol.c:__mod_lruvec_state
  - mm/memcontrol.c:__mod_memcg_state
  - mm/memcontrol.c:page_cgroup_ino
```
```
In mm/vmpressure.c (ffffffff812b71b3)
Location: include/linux/memcontrol.h:456
Inline: True
Inline callers:
  - mm/vmpressure.c:vmpressure_work_fn
```
```
In net/core/sock.c (ffffffff818e0698)
Location: include/linux/memcontrol.h:456
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_raise_allocated
```
```
In net/ipv4/tcp.c (ffffffff8198a974)
Location: include/linux/memcontrol.h:456
Inline: True
Inline callers:
  - net/ipv4/tcp.c:sk_stream_alloc_skb
```
```
In net/ipv4/tcp_input.c (ffffffff8198da62)
Location: include/linux/memcontrol.h:456
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_check_space
```
```
In net/ipv4/tcp_output.c (ffffffff8199e18a)
Location: include/linux/memcontrol.h:456
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_output.c:__tcp_select_window
```
```
In net/ipv4/tcp_timer.c (ffffffff8199f296)
Location: include/linux/memcontrol.h:456
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
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
In mm/oom_kill.c (ffffffff81229a9e)
Location: include/linux/memcontrol.h:490
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
```
```
In mm/vmscan.c (ffffffff8123b983)
Location: include/linux/memcontrol.h:490
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_node
```
```
In mm/slub.c (ffffffff812a3de3)
Location: include/linux/memcontrol.h:490
Inline: True
Inline callers:
  - mm/slub.c:alloc_slab_page
```
```
In mm/memcontrol.c (ffffffff812c8d00)
Location: include/linux/memcontrol.h:490
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_swap_full
  - mm/memcontrol.c:mem_cgroup_get_nr_swap_pages
  - mm/memcontrol.c:mem_cgroup_try_charge_swap
  - mm/memcontrol.c:mem_cgroup_id_get_online
  - mm/memcontrol.c:mem_cgroup_protected
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:mem_cgroup_css_released
  - mm/memcontrol.c:mem_cgroup_wb_stats
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:memcg_flush_percpu_vmevents
  - mm/memcontrol.c:memcg_flush_percpu_vmstats
  - mm/memcontrol.c:memcg_flush_percpu_vmstats
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:mem_cgroup_handle_over_high
  - mm/memcontrol.c:memcg_hotplug_cpu_dead
  - mm/memcontrol.c:memcg_hotplug_cpu_dead
  - mm/memcontrol.c:memcg_hotplug_cpu_dead
  - mm/memcontrol.c:mem_cgroup_get_oom_group
  - mm/memcontrol.c:__count_memcg_events
  - mm/memcontrol.c:__mod_lruvec_state
  - mm/memcontrol.c:__mod_memcg_state
  - mm/memcontrol.c:page_cgroup_ino
```
```
In mm/vmpressure.c (ffffffff812c9083)
Location: include/linux/memcontrol.h:490
Inline: True
Inline callers:
  - mm/vmpressure.c:vmpressure_work_fn
```
```
In net/core/sock.c (ffffffff81912862)
Location: include/linux/memcontrol.h:490
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_raise_allocated
```
```
In net/ipv4/tcp.c (ffffffff819c1138)
Location: include/linux/memcontrol.h:490
Inline: True
```
```
In net/ipv4/tcp_input.c (ffffffff819c4614)
Location: include/linux/memcontrol.h:490
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_check_space
```
```
In net/ipv4/tcp_output.c (ffffffff819d4c54)
Location: include/linux/memcontrol.h:490
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_output.c:__tcp_select_window
```
```
In net/ipv4/tcp_timer.c (ffffffff819d5e48)
Location: include/linux/memcontrol.h:490
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
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
In mm/oom_kill.c (ffffffff812568db)
Location: include/linux/memcontrol.h:467
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
```
```
In mm/swap.c (ffffffff8125fc84)
Location: include/linux/memcontrol.h:467
Inline: True
Inline callers:
  - mm/swap.c:lru_note_cost
```
```
In mm/vmscan.c (ffffffff81268a32)
Location: include/linux/memcontrol.h:467
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_node_memcgs
```
```
In mm/workingset.c (ffffffff812869ff)
Location: include/linux/memcontrol.h:467
Inline: True
Inline callers:
  - mm/workingset.c:workingset_age_nonresident
```
```
In mm/slub.c (ffffffff812d98c9)
Location: include/linux/memcontrol.h:467
Inline: True
Inline callers:
  - mm/slub.c:alloc_slab_page
```
```
In mm/memcontrol.c (ffffffff812fe338)
Location: include/linux/memcontrol.h:467
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_swap_full
  - mm/memcontrol.c:mem_cgroup_get_nr_swap_pages
  - mm/memcontrol.c:mem_cgroup_try_charge_swap
  - mm/memcontrol.c:mem_cgroup_id_get_online
  - mm/memcontrol.c:mem_cgroup_protected
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:mem_cgroup_css_released
  - mm/memcontrol.c:mem_cgroup_wb_stats
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:memcg_flush_percpu_vmevents
  - mm/memcontrol.c:memcg_flush_percpu_vmstats
  - mm/memcontrol.c:memcg_flush_percpu_vmstats
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:mem_cgroup_handle_over_high
  - mm/memcontrol.c:mem_cgroup_handle_over_high
  - mm/memcontrol.c:mem_cgroup_handle_over_high
  - mm/memcontrol.c:memcg_hotplug_cpu_dead
  - mm/memcontrol.c:memcg_hotplug_cpu_dead
  - mm/memcontrol.c:memcg_hotplug_cpu_dead
  - mm/memcontrol.c:mem_cgroup_get_oom_group
  - mm/memcontrol.c:__mod_lruvec_state
  - mm/memcontrol.c:mem_cgroup_update_tree
  - mm/memcontrol.c:page_cgroup_ino
```
```
In mm/vmpressure.c (ffffffff812fe6e0)
Location: include/linux/memcontrol.h:467
Inline: True
Inline callers:
  - mm/vmpressure.c:vmpressure_work_fn
```
```
In net/core/sock.c (ffffffff819e5b5d)
Location: include/linux/memcontrol.h:467
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_reduce_allocated
  - net/core/sock.c:__sk_mem_raise_allocated
```
```
In net/ipv4/tcp.c (ffffffff81aac861)
Location: include/linux/memcontrol.h:467
Inline: True
Inline callers:
  - net/ipv4/tcp.c:sk_stream_alloc_skb
```
```
In net/ipv4/tcp_input.c (ffffffff81ab334d)
Location: include/linux/memcontrol.h:467
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_check_space
  - net/ipv4/tcp_input.c:tcp_prune_queue
  - net/ipv4/tcp_input.c:tcp_prune_queue
  - net/ipv4/tcp_input.c:tcp_prune_ofo_queue
  - net/ipv4/tcp_input.c:tcp_grow_window
```
```
In net/ipv4/tcp_output.c (ffffffff81ac160d)
Location: include/linux/memcontrol.h:467
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_output.c:__tcp_select_window
```
```
In net/ipv4/tcp_timer.c (ffffffff81ac2d03)
Location: include/linux/memcontrol.h:467
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
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
In mm/oom_kill.c (ffffffff81261471)
Location: include/linux/memcontrol.h:787
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
```
```
In mm/swap.c (ffffffff8126a256)
Location: include/linux/memcontrol.h:787
Inline: True
Inline callers:
  - mm/swap.c:lru_note_cost
```
```
In mm/vmscan.c (ffffffff8127349f)
Location: include/linux/memcontrol.h:787
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_node_memcgs
```
```
In mm/workingset.c (ffffffff81290c4f)
Location: include/linux/memcontrol.h:787
Inline: True
Inline callers:
  - mm/workingset.c:workingset_age_nonresident
```
```
In mm/memcontrol.c (ffffffff8130a869)
Location: include/linux/memcontrol.h:787
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_swap_full
  - mm/memcontrol.c:mem_cgroup_get_nr_swap_pages
  - mm/memcontrol.c:mem_cgroup_try_charge_swap
  - mm/memcontrol.c:mem_cgroup_id_get_online
  - mm/memcontrol.c:mem_cgroup_calculate_protection
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:mem_cgroup_css_released
  - mm/memcontrol.c:mem_cgroup_wb_stats
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:memcg_flush_percpu_vmevents
  - mm/memcontrol.c:memcg_flush_percpu_vmstats
  - mm/memcontrol.c:memcg_flush_percpu_vmstats
  - mm/memcontrol.c:get_obj_cgroup_from_current
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:mem_cgroup_handle_over_high
  - mm/memcontrol.c:mem_cgroup_handle_over_high
  - mm/memcontrol.c:mem_cgroup_handle_over_high
  - mm/memcontrol.c:memcg_hotplug_cpu_dead
  - mm/memcontrol.c:memcg_hotplug_cpu_dead
  - mm/memcontrol.c:memcg_hotplug_cpu_dead
  - mm/memcontrol.c:mem_cgroup_get_oom_group
  - mm/memcontrol.c:__mod_memcg_lruvec_state
  - mm/memcontrol.c:mem_cgroup_update_tree
  - mm/memcontrol.c:page_cgroup_ino
```
```
In mm/vmpressure.c (ffffffff8130aa20)
Location: include/linux/memcontrol.h:787
Inline: True
Inline callers:
  - mm/vmpressure.c:vmpressure_work_fn
```
```
In net/core/sock.c (ffffffff819e562d)
Location: include/linux/memcontrol.h:787
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_reduce_allocated
  - net/core/sock.c:__sk_mem_raise_allocated
```
```
In net/ipv4/tcp.c (ffffffff81ab41b0)
Location: include/linux/memcontrol.h:787
Inline: True
Inline callers:
  - net/ipv4/tcp.c:sk_stream_alloc_skb
  - net/ipv4/tcp.c:tcp_poll
```
```
In net/ipv4/tcp_input.c (ffffffff81abe2a3)
Location: include/linux/memcontrol.h:787
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_check_space
  - net/ipv4/tcp_input.c:tcp_prune_queue
  - net/ipv4/tcp_input.c:tcp_prune_queue
  - net/ipv4/tcp_input.c:tcp_prune_ofo_queue
  - net/ipv4/tcp_input.c:tcp_data_ready
  - net/ipv4/tcp_input.c:tcp_grow_window
```
```
In net/ipv4/tcp_output.c (ffffffff81acd07d)
Location: include/linux/memcontrol.h:787
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_output.c:__tcp_select_window
```
```
In net/ipv4/tcp_timer.c (ffffffff81ace793)
Location: include/linux/memcontrol.h:787
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
```
```
In net/mptcp/protocol.c (ffffffff81bbeb84)
Location: include/linux/memcontrol.h:787
Inline: True
Inline callers:
  - net/mptcp/protocol.c:__mptcp_subflow_push_pending
  - net/mptcp/protocol.c:mptcp_alloc_tx_skb
  - net/mptcp/protocol.c:__mptcp_clean_una
  - net/mptcp/protocol.c:__mptcp_wmem_reserve
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
In mm/oom_kill.c (ffffffff81265cad)
Location: include/linux/memcontrol.h:866
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
```
```
In mm/swap.c (ffffffff8126f379)
Location: include/linux/memcontrol.h:866
Inline: True
Inline callers:
  - mm/swap.c:lru_note_cost
```
```
In mm/vmscan.c (ffffffff812787bf)
Location: include/linux/memcontrol.h:866
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_node_memcgs
  - mm/vmscan.c:reparent_shrinker_deferred
```
```
In mm/workingset.c (ffffffff812962af)
Location: include/linux/memcontrol.h:866
Inline: True
Inline callers:
  - mm/workingset.c:workingset_age_nonresident
```
```
In mm/memcontrol.c (ffffffff81310ec4)
Location: include/linux/memcontrol.h:866
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_swap_full
  - mm/memcontrol.c:mem_cgroup_get_nr_swap_pages
  - mm/memcontrol.c:mem_cgroup_try_charge_swap
  - mm/memcontrol.c:mem_cgroup_id_get_online
  - mm/memcontrol.c:mem_cgroup_calculate_protection
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:mem_cgroup_css_rstat_flush
  - mm/memcontrol.c:mem_cgroup_css_released
  - mm/memcontrol.c:mem_cgroup_wb_stats
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:__memcg_kmem_charge_page
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:mem_cgroup_handle_over_high
  - mm/memcontrol.c:mem_cgroup_handle_over_high
  - mm/memcontrol.c:mem_cgroup_handle_over_high
  - mm/memcontrol.c:memcg_flush_lruvec_page_state
  - mm/memcontrol.c:mem_cgroup_get_oom_group
  - mm/memcontrol.c:__mod_memcg_lruvec_state
  - mm/memcontrol.c:page_cgroup_ino
```
```
In mm/vmpressure.c (ffffffff81311080)
Location: include/linux/memcontrol.h:866
Inline: True
Inline callers:
  - mm/vmpressure.c:vmpressure_work_fn
```
```
In net/core/sock.c (ffffffff819cb73d)
Location: include/linux/memcontrol.h:866
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_reduce_allocated
  - net/core/sock.c:__sk_mem_raise_allocated
```
```
In net/ipv4/tcp.c (ffffffff81a9f320)
Location: include/linux/memcontrol.h:866
Inline: True
Inline callers:
  - net/ipv4/tcp.c:sk_stream_alloc_skb
  - net/ipv4/tcp.c:tcp_poll
```
```
In net/ipv4/tcp_input.c (ffffffff81aa9383)
Location: include/linux/memcontrol.h:866
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_check_space
  - net/ipv4/tcp_input.c:tcp_prune_ofo_queue
  - net/ipv4/tcp_input.c:tcp_data_ready
  - net/ipv4/tcp_input.c:tcp_grow_window
```
```
In net/ipv4/tcp_output.c (ffffffff81ab824d)
Location: include/linux/memcontrol.h:866
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_output.c:__tcp_select_window
```
```
In net/ipv4/tcp_timer.c (ffffffff81ab9933)
Location: include/linux/memcontrol.h:866
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
```
```
In net/mptcp/protocol.c (ffffffff81bafb44)
Location: include/linux/memcontrol.h:866
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_sendmsg
  - net/mptcp/protocol.c:mptcp_sendmsg
  - net/mptcp/protocol.c:__mptcp_subflow_push_pending
  - net/mptcp/protocol.c:mptcp_alloc_tx_skb
  - net/mptcp/protocol.c:__mptcp_clean_una
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
In mm/oom_kill.c (ffffffff812a24d7)
Location: include/linux/memcontrol.h:862
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
```
```
In mm/swap.c (ffffffff812ac4cf)
Location: include/linux/memcontrol.h:862
Inline: True
Inline callers:
  - mm/swap.c:lru_note_cost
```
```
In mm/vmscan.c (ffffffff812b6516)
Location: include/linux/memcontrol.h:862
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_node_memcgs
  - mm/vmscan.c:reparent_shrinker_deferred
```
```
In mm/workingset.c (ffffffff812d6a3c)
Location: include/linux/memcontrol.h:862
Inline: True
Inline callers:
  - mm/workingset.c:workingset_age_nonresident
```
```
In mm/memcontrol.c (ffffffff8135c1a8)
Location: include/linux/memcontrol.h:862
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_swap_full
  - mm/memcontrol.c:mem_cgroup_get_nr_swap_pages
  - mm/memcontrol.c:__mem_cgroup_try_charge_swap
  - mm/memcontrol.c:mem_cgroup_id_get_online
  - mm/memcontrol.c:mem_cgroup_calculate_protection
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:mem_cgroup_css_rstat_flush
  - mm/memcontrol.c:mem_cgroup_css_released
  - mm/memcontrol.c:mem_cgroup_wb_stats
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:__memcg_kmem_charge_page
  - mm/memcontrol.c:try_charge_memcg
  - mm/memcontrol.c:try_charge_memcg
  - mm/memcontrol.c:mem_cgroup_handle_over_high
  - mm/memcontrol.c:mem_cgroup_handle_over_high
  - mm/memcontrol.c:mem_cgroup_handle_over_high
  - mm/memcontrol.c:mem_cgroup_get_oom_group
  - mm/memcontrol.c:page_cgroup_ino
```
```
In mm/vmpressure.c (ffffffff8135c370)
Location: include/linux/memcontrol.h:862
Inline: True
Inline callers:
  - mm/vmpressure.c:vmpressure_work_fn
```
```
In net/core/sock.c (ffffffff81a7adc4)
Location: include/linux/memcontrol.h:862
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_reduce_allocated
  - net/core/sock.c:__sk_mem_raise_allocated
```
```
In net/ipv4/tcp.c (ffffffff81b5b0d0)
Location: include/linux/memcontrol.h:862
Inline: True
Inline callers:
  - net/ipv4/tcp.c:sk_stream_alloc_skb
  - net/ipv4/tcp.c:tcp_poll
```
```
In net/ipv4/tcp_input.c (ffffffff81b65270)
Location: include/linux/memcontrol.h:862
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_check_space
  - net/ipv4/tcp_input.c:tcp_prune_ofo_queue
  - net/ipv4/tcp_input.c:tcp_data_ready
  - net/ipv4/tcp_input.c:tcp_grow_window
```
```
In net/ipv4/tcp_output.c (ffffffff81b75437)
Location: include/linux/memcontrol.h:862
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_output.c:__tcp_select_window
```
```
In net/ipv4/tcp_timer.c (ffffffff81b76d69)
Location: include/linux/memcontrol.h:862
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
```
```
In net/mptcp/protocol.c (ffffffff81c7d6b4)
Location: include/linux/memcontrol.h:862
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_sendmsg
  - net/mptcp/protocol.c:mptcp_alloc_tx_skb
  - net/mptcp/protocol.c:__mptcp_clean_una
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
In mm/oom_kill.c (ffffffff812fa427)
Location: include/linux/memcontrol.h:863
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
```
```
In mm/swap.c (ffffffff8130662d)
Location: include/linux/memcontrol.h:863
Inline: True
Inline callers:
  - mm/swap.c:lru_note_cost
```
```
In mm/vmscan.c (ffffffff81311997)
Location: include/linux/memcontrol.h:863
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_node_memcgs
  - mm/vmscan.c:reparent_shrinker_deferred
```
```
In mm/list_lru.c (ffffffff81335ad6)
Location: include/linux/memcontrol.h:863
Inline: True
Inline callers:
  - mm/list_lru.c:memcg_list_lru_alloc
```
```
In mm/workingset.c (ffffffff8133616c)
Location: include/linux/memcontrol.h:863
Inline: True
Inline callers:
  - mm/workingset.c:workingset_age_nonresident
```
```
In mm/memcontrol.c (ffffffff813d5c4e)
Location: include/linux/memcontrol.h:863
Inline: True
Inline callers:
  - mm/memcontrol.c:obj_cgroup_may_zswap
  - mm/memcontrol.c:mem_cgroup_swap_full
  - mm/memcontrol.c:mem_cgroup_get_nr_swap_pages
  - mm/memcontrol.c:__mem_cgroup_try_charge_swap
  - mm/memcontrol.c:mem_cgroup_id_get_online
  - mm/memcontrol.c:mem_cgroup_calculate_protection
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:mem_cgroup_css_rstat_flush
  - mm/memcontrol.c:mem_cgroup_css_released
  - mm/memcontrol.c:mem_cgroup_wb_stats
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:__get_obj_cgroup_from_memcg
  - mm/memcontrol.c:try_charge_memcg
  - mm/memcontrol.c:try_charge_memcg
  - mm/memcontrol.c:try_charge_memcg
  - mm/memcontrol.c:mem_cgroup_handle_over_high
  - mm/memcontrol.c:mem_cgroup_handle_over_high
  - mm/memcontrol.c:mem_cgroup_handle_over_high
  - mm/memcontrol.c:mem_cgroup_get_oom_group
  - mm/memcontrol.c:page_cgroup_ino
```
```
In mm/vmpressure.c (ffffffff813d5f81)
Location: include/linux/memcontrol.h:863
Inline: True
Inline callers:
  - mm/vmpressure.c:vmpressure_work_fn
```
```
In net/core/sock.c (ffffffff81beecd3)
Location: include/linux/memcontrol.h:863
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_reduce_allocated
  - net/core/sock.c:__sk_mem_raise_allocated
```
```
In net/ipv4/tcp.c (ffffffff81ce9b2d)
Location: include/linux/memcontrol.h:863
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_stream_alloc_skb
  - net/ipv4/tcp.c:tcp_poll
```
```
In net/ipv4/tcp_input.c (ffffffff81cf35d7)
Location: include/linux/memcontrol.h:863
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_prune_ofo_queue
  - net/ipv4/tcp_input.c:tcp_data_ready
  - net/ipv4/tcp_input.c:tcp_try_rmem_schedule
  - net/ipv4/tcp_input.c:tcp_try_rmem_schedule
  - net/ipv4/tcp_input.c:tcp_grow_window
```
```
In net/ipv4/tcp_output.c (ffffffff81d04ca6)
Location: include/linux/memcontrol.h:863
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_output.c:__tcp_select_window
```
```
In net/ipv4/tcp_timer.c (ffffffff81d06622)
Location: include/linux/memcontrol.h:863
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
```
```
In net/mptcp/protocol.c (ffffffff81e1f23c)
Location: include/linux/memcontrol.h:863
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_sendmsg_frag
  - net/mptcp/protocol.c:__mptcp_clean_una
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
In mm/oom_kill.c (ffffffff81364b97)
Location: include/linux/memcontrol.h:854
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
```
```
In mm/swap.c (ffffffff813706e6)
Location: include/linux/memcontrol.h:854
Inline: True
Inline callers:
  - mm/swap.c:lru_note_cost
```
```
In mm/vmscan.c (ffffffff81384fc2)
Location: include/linux/memcontrol.h:854
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_node_memcgs
  - mm/vmscan.c:reparent_shrinker_deferred
```
```
In mm/list_lru.c (ffffffff813ac896)
Location: include/linux/memcontrol.h:854
Inline: True
Inline callers:
  - mm/list_lru.c:memcg_list_lru_alloc
```
```
In mm/workingset.c (ffffffff813ad3ec)
Location: include/linux/memcontrol.h:854
Inline: True
Inline callers:
  - mm/workingset.c:workingset_age_nonresident
```
```
In mm/memcontrol.c (ffffffff8145b635)
Location: include/linux/memcontrol.h:854
Inline: True
Inline callers:
  - mm/memcontrol.c:obj_cgroup_may_zswap
  - mm/memcontrol.c:mem_cgroup_swap_full
  - mm/memcontrol.c:mem_cgroup_get_nr_swap_pages
  - mm/memcontrol.c:__mem_cgroup_try_charge_swap
  - mm/memcontrol.c:mem_cgroup_id_get_online
  - mm/memcontrol.c:mem_cgroup_calculate_protection
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:mem_cgroup_css_rstat_flush
  - mm/memcontrol.c:mem_cgroup_css_released
  - mm/memcontrol.c:mem_cgroup_css_offline
  - mm/memcontrol.c:mem_cgroup_css_online
  - mm/memcontrol.c:mem_cgroup_wb_stats
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:__get_obj_cgroup_from_memcg
  - mm/memcontrol.c:try_charge_memcg
  - mm/memcontrol.c:try_charge_memcg
  - mm/memcontrol.c:try_charge_memcg
  - mm/memcontrol.c:try_charge_memcg
  - mm/memcontrol.c:mem_cgroup_handle_over_high
  - mm/memcontrol.c:mem_cgroup_handle_over_high
  - mm/memcontrol.c:mem_cgroup_handle_over_high
  - mm/memcontrol.c:mem_cgroup_get_oom_group
  - mm/memcontrol.c:page_cgroup_ino
```
```
In mm/vmpressure.c (ffffffff8145b9a1)
Location: include/linux/memcontrol.h:854
Inline: True
Inline callers:
  - mm/vmpressure.c:vmpressure_work_fn
```
```
In net/core/sock.c (ffffffff81d9e422)
Location: include/linux/memcontrol.h:854
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_reduce_allocated
  - net/core/sock.c:__sk_mem_raise_allocated
```
```
In net/ipv4/tcp.c (ffffffff81ead3e7)
Location: include/linux/memcontrol.h:854
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_poll
```
```
In net/ipv4/tcp_input.c (ffffffff81eb7bfa)
Location: include/linux/memcontrol.h:854
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_prune_ofo_queue
  - net/ipv4/tcp_input.c:tcp_data_ready
  - net/ipv4/tcp_input.c:tcp_try_rmem_schedule
  - net/ipv4/tcp_input.c:tcp_try_rmem_schedule
  - net/ipv4/tcp_input.c:tcp_grow_window
```
```
In net/ipv4/tcp_output.c (ffffffff81ec9cf6)
Location: include/linux/memcontrol.h:854
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_output.c:__tcp_select_window
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
In mm/oom_kill.c (ffffffff81397057)
Location: include/linux/memcontrol.h:872
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
```
```
In mm/swap.c (ffffffff813a2896)
Location: include/linux/memcontrol.h:872
Inline: True
Inline callers:
  - mm/swap.c:lru_note_cost
```
```
In mm/vmscan.c (ffffffff813b6b22)
Location: include/linux/memcontrol.h:872
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_node_memcgs
  - mm/vmscan.c:shrink_one
  - mm/vmscan.c:reparent_shrinker_deferred
```
```
In mm/list_lru.c (ffffffff813e0c36)
Location: include/linux/memcontrol.h:872
Inline: True
Inline callers:
  - mm/list_lru.c:memcg_list_lru_alloc
```
```
In mm/workingset.c (ffffffff813e17dc)
Location: include/linux/memcontrol.h:872
Inline: True
Inline callers:
  - mm/workingset.c:workingset_age_nonresident
```
```
In mm/memcontrol.c (ffffffff814912a5)
Location: include/linux/memcontrol.h:872
Inline: True
Inline callers:
  - mm/memcontrol.c:obj_cgroup_may_zswap
  - mm/memcontrol.c:mem_cgroup_swap_full
  - mm/memcontrol.c:mem_cgroup_get_nr_swap_pages
  - mm/memcontrol.c:__mem_cgroup_try_charge_swap
  - mm/memcontrol.c:mem_cgroup_id_get_online
  - mm/memcontrol.c:mem_cgroup_calculate_protection
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:mem_cgroup_css_rstat_flush
  - mm/memcontrol.c:mem_cgroup_css_released
  - mm/memcontrol.c:mem_cgroup_css_offline
  - mm/memcontrol.c:mem_cgroup_css_online
  - mm/memcontrol.c:mem_cgroup_wb_stats
  - mm/memcontrol.c:__get_obj_cgroup_from_memcg
  - mm/memcontrol.c:try_charge_memcg
  - mm/memcontrol.c:try_charge_memcg
  - mm/memcontrol.c:try_charge_memcg
  - mm/memcontrol.c:try_charge_memcg
  - mm/memcontrol.c:mem_cgroup_handle_over_high
  - mm/memcontrol.c:mem_cgroup_handle_over_high
  - mm/memcontrol.c:mem_cgroup_handle_over_high
  - mm/memcontrol.c:mem_cgroup_get_oom_group
  - mm/memcontrol.c:memcg_check_events
  - mm/memcontrol.c:memcg_check_events
  - mm/memcontrol.c:page_cgroup_ino
```
```
In mm/vmpressure.c (ffffffff81491620)
Location: include/linux/memcontrol.h:872
Inline: True
Inline callers:
  - mm/vmpressure.c:vmpressure_work_fn
```
```
In net/core/sock.c (ffffffff81e0c7a8)
Location: include/linux/memcontrol.h:872
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_raise_allocated
```
```
In net/ipv4/tcp.c (ffffffff81f0baf6)
Location: include/linux/memcontrol.h:872
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_poll
```
```
In net/ipv4/tcp_input.c (ffffffff81f15a2a)
Location: include/linux/memcontrol.h:872
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_prune_ofo_queue
  - net/ipv4/tcp_input.c:tcp_data_ready
  - net/ipv4/tcp_input.c:tcp_try_rmem_schedule
  - net/ipv4/tcp_input.c:tcp_try_rmem_schedule
  - net/ipv4/tcp_input.c:tcp_grow_window
```
```
In net/ipv4/tcp_output.c (ffffffff81f28846)
Location: include/linux/memcontrol.h:872
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_output.c:__tcp_select_window
  - net/ipv4/tcp_output.c:__tcp_select_window
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
In mm/oom_kill.c (ffffffff813c0dcb)
Location: include/linux/memcontrol.h:891
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
```
```
In mm/swap.c (ffffffff813cc516)
Location: include/linux/memcontrol.h:891
Inline: True
Inline callers:
  - mm/swap.c:lru_note_cost
```
```
In mm/vmscan.c (ffffffff813df9e2)
Location: include/linux/memcontrol.h:891
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_node_memcgs
  - mm/vmscan.c:shrink_one
```
```
In mm/shrinker.c (ffffffff813e4b95)
Location: include/linux/memcontrol.h:891
Inline: True
Inline callers:
  - mm/shrinker.c:reparent_shrinker_deferred
```
```
In mm/list_lru.c (ffffffff8140b506)
Location: include/linux/memcontrol.h:891
Inline: True
Inline callers:
  - mm/list_lru.c:memcg_list_lru_alloc
```
```
In mm/workingset.c (ffffffff8140bf1c)
Location: include/linux/memcontrol.h:891
Inline: True
Inline callers:
  - mm/workingset.c:workingset_age_nonresident
```
```
In mm/memcontrol.c (ffffffff814c0c15)
Location: include/linux/memcontrol.h:891
Inline: True
Inline callers:
  - mm/memcontrol.c:obj_cgroup_may_zswap
  - mm/memcontrol.c:mem_cgroup_swap_full
  - mm/memcontrol.c:mem_cgroup_get_nr_swap_pages
  - mm/memcontrol.c:__mem_cgroup_try_charge_swap
  - mm/memcontrol.c:mem_cgroup_id_get_online
  - mm/memcontrol.c:mem_cgroup_calculate_protection
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:mem_cgroup_css_rstat_flush
  - mm/memcontrol.c:mem_cgroup_css_released
  - mm/memcontrol.c:mem_cgroup_css_offline
  - mm/memcontrol.c:mem_cgroup_css_online
  - mm/memcontrol.c:mem_cgroup_wb_stats
  - mm/memcontrol.c:__memcg_kmem_charge_page
  - mm/memcontrol.c:get_obj_cgroup_from_folio
  - mm/memcontrol.c:current_objcg_update
  - mm/memcontrol.c:try_charge_memcg
  - mm/memcontrol.c:try_charge_memcg
  - mm/memcontrol.c:try_charge_memcg
  - mm/memcontrol.c:try_charge_memcg
  - mm/memcontrol.c:mem_cgroup_handle_over_high
  - mm/memcontrol.c:mem_cgroup_handle_over_high
  - mm/memcontrol.c:mem_cgroup_handle_over_high
  - mm/memcontrol.c:reclaim_high
  - mm/memcontrol.c:reclaim_high
  - mm/memcontrol.c:mem_cgroup_get_oom_group
  - mm/memcontrol.c:memcg_check_events
  - mm/memcontrol.c:memcg_check_events
  - mm/memcontrol.c:page_cgroup_ino
```
```
In mm/vmpressure.c (ffffffff814c0ffd)
Location: include/linux/memcontrol.h:891
Inline: True
Inline callers:
  - mm/vmpressure.c:vmpressure_work_fn
```
```
In net/ipv4/tcp.c (ffffffff81fcfbab)
Location: include/linux/memcontrol.h:891
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_poll
```
```
In net/ipv4/tcp_input.c (ffffffff81fda6aa)
Location: include/linux/memcontrol.h:891
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_prune_ofo_queue
  - net/ipv4/tcp_input.c:tcp_data_ready
  - net/ipv4/tcp_input.c:tcp_try_rmem_schedule
  - net/ipv4/tcp_input.c:tcp_try_rmem_schedule
  - net/ipv4/tcp_input.c:tcp_grow_window
```
```
In net/ipv4/tcp_output.c (ffffffff81fed2de)
Location: include/linux/memcontrol.h:891
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_output.c:__tcp_select_window
  - net/ipv4/tcp_output.c:__tcp_select_window
```
```
In net/mptcp/protocol.c (ffffffff8214574a)
Location: include/linux/memcontrol.h:891
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_poll
  - net/mptcp/protocol.c:mptcp_data_ready
```
```
In net/mptcp/sockopt.c (ffffffff821602cc)
Location: include/linux/memcontrol.h:891
Inline: True
Inline callers:
  - net/mptcp/sockopt.c:mptcp_set_rcvlowat
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
In mm/oom_kill.c (ffff8000102b7898)
Location: include/linux/memcontrol.h:490
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
```
```
In mm/vmscan.c (ffff8000102ccba4)
Location: include/linux/memcontrol.h:490
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_node
```
```
In mm/slub.c (ffff800010345b38)
Location: include/linux/memcontrol.h:490
Inline: True
Inline callers:
  - mm/slub.c:alloc_slab_page
```
```
In mm/memcontrol.c (ffff80001036bbcc)
Location: include/linux/memcontrol.h:490
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_swap_full
  - mm/memcontrol.c:mem_cgroup_get_nr_swap_pages
  - mm/memcontrol.c:mem_cgroup_id_get_online
  - mm/memcontrol.c:mem_cgroup_protected
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:mem_cgroup_css_released
  - mm/memcontrol.c:mem_cgroup_wb_stats
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:memcg_flush_percpu_vmevents
  - mm/memcontrol.c:memcg_flush_percpu_vmstats
  - mm/memcontrol.c:memcg_flush_percpu_vmstats
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:mem_cgroup_handle_over_high
  - mm/memcontrol.c:memcg_hotplug_cpu_dead
  - mm/memcontrol.c:memcg_hotplug_cpu_dead
  - mm/memcontrol.c:memcg_hotplug_cpu_dead
  - mm/memcontrol.c:mem_cgroup_get_oom_group
  - mm/memcontrol.c:__count_memcg_events
  - mm/memcontrol.c:__mod_lruvec_state
  - mm/memcontrol.c:__mod_memcg_state
  - mm/memcontrol.c:page_cgroup_ino
```
```
In mm/vmpressure.c (ffff80001036c53c)
Location: include/linux/memcontrol.h:490
Inline: True
Inline callers:
  - mm/vmpressure.c:vmpressure_work_fn
```
```
In net/core/sock.c (ffff800010baceb8)
Location: include/linux/memcontrol.h:490
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_raise_allocated
```
```
In net/ipv4/tcp.c (ffff800010c7405c)
Location: include/linux/memcontrol.h:490
Inline: True
Inline callers:
  - net/ipv4/tcp.c:sk_stream_alloc_skb
```
```
In net/ipv4/tcp_input.c (ffff800010c77038)
Location: include/linux/memcontrol.h:490
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_check_space
```
```
In net/ipv4/tcp_output.c (ffff800010c87898)
Location: include/linux/memcontrol.h:490
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_output.c:__tcp_select_window
```
```
In net/ipv4/tcp_timer.c (ffff800010c88da0)
Location: include/linux/memcontrol.h:490
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
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
In mm/oom_kill.c (c04e44ec)
Location: include/linux/memcontrol.h:490
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
```
```
In mm/vmscan.c (c04f6820)
Location: include/linux/memcontrol.h:490
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_node
```
```
In mm/slub.c (c05498c4)
Location: include/linux/memcontrol.h:490
Inline: True
Inline callers:
  - mm/slub.c:alloc_slab_page
```
```
In mm/memcontrol.c (c055d274)
Location: include/linux/memcontrol.h:490
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_swap_full
  - mm/memcontrol.c:mem_cgroup_get_nr_swap_pages
  - mm/memcontrol.c:mem_cgroup_try_charge_swap
  - mm/memcontrol.c:mem_cgroup_id_get_online
  - mm/memcontrol.c:mem_cgroup_protected
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:mem_cgroup_css_released
  - mm/memcontrol.c:mem_cgroup_wb_stats
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:memcg_flush_percpu_vmevents
  - mm/memcontrol.c:memcg_flush_percpu_vmstats
  - mm/memcontrol.c:memcg_flush_percpu_vmstats
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:mem_cgroup_handle_over_high
  - mm/memcontrol.c:memcg_hotplug_cpu_dead
  - mm/memcontrol.c:memcg_hotplug_cpu_dead
  - mm/memcontrol.c:memcg_hotplug_cpu_dead
  - mm/memcontrol.c:mem_cgroup_get_oom_group
  - mm/memcontrol.c:__count_memcg_events
  - mm/memcontrol.c:__mod_lruvec_state
  - mm/memcontrol.c:__mod_memcg_state
  - mm/memcontrol.c:page_cgroup_ino
```
```
In mm/vmpressure.c (c055d630)
Location: include/linux/memcontrol.h:490
Inline: True
Inline callers:
  - mm/vmpressure.c:vmpressure_work_fn
```
```
In net/core/sock.c (c0cc8a70)
Location: include/linux/memcontrol.h:490
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_raise_allocated
```
```
In net/ipv4/tcp.c (c0d826ec)
Location: include/linux/memcontrol.h:490
Inline: True
Inline callers:
  - net/ipv4/tcp.c:sk_stream_alloc_skb
```
```
In net/ipv4/tcp_input.c (c0d855c0)
Location: include/linux/memcontrol.h:490
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_check_space
  - net/ipv4/tcp_input.c:tcp_grow_window
```
```
In net/ipv4/tcp_output.c (c0d96c60)
Location: include/linux/memcontrol.h:490
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_output.c:__tcp_select_window
```
```
In net/ipv4/tcp_timer.c (c0d97f54)
Location: include/linux/memcontrol.h:490
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
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
In mm/oom_kill.c (c00000000036f694)
Location: include/linux/memcontrol.h:490
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
```
```
In mm/vmscan.c (c00000000038a3b8)
Location: include/linux/memcontrol.h:490
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_node
```
```
In mm/slub.c (c0000000004221f0)
Location: include/linux/memcontrol.h:490
Inline: True
Inline callers:
  - mm/slub.c:alloc_slab_page
```
```
In mm/memcontrol.c (c00000000045b894)
Location: include/linux/memcontrol.h:490
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_swap_full
  - mm/memcontrol.c:mem_cgroup_get_nr_swap_pages
  - mm/memcontrol.c:mem_cgroup_try_charge_swap
  - mm/memcontrol.c:mem_cgroup_id_get_online
  - mm/memcontrol.c:mem_cgroup_protected
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:mem_cgroup_css_released
  - mm/memcontrol.c:mem_cgroup_wb_stats
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:memcg_flush_percpu_vmevents
  - mm/memcontrol.c:memcg_flush_percpu_vmstats
  - mm/memcontrol.c:memcg_flush_percpu_vmstats
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:mem_cgroup_handle_over_high
  - mm/memcontrol.c:memcg_hotplug_cpu_dead
  - mm/memcontrol.c:memcg_hotplug_cpu_dead
  - mm/memcontrol.c:memcg_hotplug_cpu_dead
  - mm/memcontrol.c:mem_cgroup_get_oom_group
  - mm/memcontrol.c:__count_memcg_events
  - mm/memcontrol.c:__mod_lruvec_state
  - mm/memcontrol.c:__mod_memcg_state
  - mm/memcontrol.c:page_cgroup_ino
```
```
In mm/vmpressure.c (c00000000045c2a4)
Location: include/linux/memcontrol.h:490
Inline: True
Inline callers:
  - mm/vmpressure.c:vmpressure_work_fn
```
```
In net/core/sock.c (c000000000c7fd44)
Location: include/linux/memcontrol.h:490
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_raise_allocated
```
```
In net/ipv4/tcp.c (c000000000d7b038)
Location: include/linux/memcontrol.h:490
Inline: True
Inline callers:
  - net/ipv4/tcp.c:sk_stream_alloc_skb
```
```
In net/ipv4/tcp_input.c (c000000000d7f2f8)
Location: include/linux/memcontrol.h:490
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_check_space
```
```
In net/ipv4/tcp_output.c (c000000000d94468)
Location: include/linux/memcontrol.h:490
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_output.c:__tcp_select_window
```
```
In net/ipv4/tcp_timer.c (c000000000d95ee8)
Location: include/linux/memcontrol.h:490
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
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
In mm/oom_kill.c (ffffffe0001dbb7e)
Location: include/linux/memcontrol.h:490
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
```
```
In mm/vmscan.c (ffffffe0001eb57a)
Location: include/linux/memcontrol.h:490
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_node
```
```
In mm/slub.c (ffffffe000238306)
Location: include/linux/memcontrol.h:490
Inline: True
Inline callers:
  - mm/slub.c:alloc_slab_page
```
```
In mm/memcontrol.c (ffffffe000249198)
Location: include/linux/memcontrol.h:490
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_swap_full
  - mm/memcontrol.c:mem_cgroup_get_nr_swap_pages
  - mm/memcontrol.c:mem_cgroup_try_charge_swap
  - mm/memcontrol.c:mem_cgroup_id_get_online
  - mm/memcontrol.c:mem_cgroup_protected
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:mem_cgroup_css_released
  - mm/memcontrol.c:mem_cgroup_wb_stats
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:memcg_flush_percpu_vmevents
  - mm/memcontrol.c:memcg_flush_percpu_vmstats
  - mm/memcontrol.c:memcg_flush_percpu_vmstats
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:mem_cgroup_handle_over_high
  - mm/memcontrol.c:memcg_hotplug_cpu_dead
  - mm/memcontrol.c:memcg_hotplug_cpu_dead
  - mm/memcontrol.c:memcg_hotplug_cpu_dead
  - mm/memcontrol.c:mem_cgroup_get_oom_group
  - mm/memcontrol.c:__count_memcg_events
  - mm/memcontrol.c:__mod_lruvec_state
  - mm/memcontrol.c:__mod_memcg_state
  - mm/memcontrol.c:page_cgroup_ino
```
```
In mm/vmpressure.c (ffffffe0002494e2)
Location: include/linux/memcontrol.h:490
Inline: True
Inline callers:
  - mm/vmpressure.c:vmpressure_work_fn
```
```
In net/core/sock.c (ffffffe00073d792)
Location: include/linux/memcontrol.h:490
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_raise_allocated
```
```
In net/ipv4/tcp.c (ffffffe0007d763c)
Location: include/linux/memcontrol.h:490
Inline: True
```
```
In net/ipv4/tcp_input.c (ffffffe0007da286)
Location: include/linux/memcontrol.h:490
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_check_space
```
```
In net/ipv4/tcp_output.c (ffffffe0007e8c56)
Location: include/linux/memcontrol.h:490
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_output.c:__tcp_select_window
```
```
In net/ipv4/tcp_timer.c (ffffffe0007e9e58)
Location: include/linux/memcontrol.h:490
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
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
In mm/oom_kill.c (ffffffff812220ee)
Location: include/linux/memcontrol.h:490
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
```
```
In mm/vmscan.c (ffffffff81233fd3)
Location: include/linux/memcontrol.h:490
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_node
```
```
In mm/slub.c (ffffffff8129c3c3)
Location: include/linux/memcontrol.h:490
Inline: True
Inline callers:
  - mm/slub.c:alloc_slab_page
```
```
In mm/memcontrol.c (ffffffff812c12e0)
Location: include/linux/memcontrol.h:490
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_swap_full
  - mm/memcontrol.c:mem_cgroup_get_nr_swap_pages
  - mm/memcontrol.c:mem_cgroup_try_charge_swap
  - mm/memcontrol.c:mem_cgroup_id_get_online
  - mm/memcontrol.c:mem_cgroup_protected
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:mem_cgroup_css_released
  - mm/memcontrol.c:mem_cgroup_wb_stats
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:memcg_flush_percpu_vmevents
  - mm/memcontrol.c:memcg_flush_percpu_vmstats
  - mm/memcontrol.c:memcg_flush_percpu_vmstats
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:mem_cgroup_handle_over_high
  - mm/memcontrol.c:memcg_hotplug_cpu_dead
  - mm/memcontrol.c:memcg_hotplug_cpu_dead
  - mm/memcontrol.c:memcg_hotplug_cpu_dead
  - mm/memcontrol.c:mem_cgroup_get_oom_group
  - mm/memcontrol.c:__count_memcg_events
  - mm/memcontrol.c:__mod_lruvec_state
  - mm/memcontrol.c:__mod_memcg_state
  - mm/memcontrol.c:page_cgroup_ino
```
```
In mm/vmpressure.c (ffffffff812c1663)
Location: include/linux/memcontrol.h:490
Inline: True
Inline callers:
  - mm/vmpressure.c:vmpressure_work_fn
```
```
In net/core/sock.c (ffffffff818b2862)
Location: include/linux/memcontrol.h:490
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_raise_allocated
```
```
In net/ipv4/tcp.c (ffffffff81960fa8)
Location: include/linux/memcontrol.h:490
Inline: True
```
```
In net/ipv4/tcp_input.c (ffffffff81964484)
Location: include/linux/memcontrol.h:490
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_check_space
```
```
In net/ipv4/tcp_output.c (ffffffff81974ac4)
Location: include/linux/memcontrol.h:490
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_output.c:__tcp_select_window
```
```
In net/ipv4/tcp_timer.c (ffffffff81975cb8)
Location: include/linux/memcontrol.h:490
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
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
In mm/oom_kill.c (ffffffff8121529e)
Location: include/linux/memcontrol.h:490
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
```
```
In mm/vmscan.c (ffffffff81227043)
Location: include/linux/memcontrol.h:490
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_node
```
```
In mm/slub.c (ffffffff8128df74)
Location: include/linux/memcontrol.h:490
Inline: True
Inline callers:
  - mm/slub.c:alloc_slab_page
```
```
In mm/memcontrol.c (ffffffff812b2330)
Location: include/linux/memcontrol.h:490
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_swap_full
  - mm/memcontrol.c:mem_cgroup_get_nr_swap_pages
  - mm/memcontrol.c:mem_cgroup_try_charge_swap
  - mm/memcontrol.c:mem_cgroup_id_get_online
  - mm/memcontrol.c:mem_cgroup_protected
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:mem_cgroup_css_released
  - mm/memcontrol.c:mem_cgroup_wb_stats
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:memcg_flush_percpu_vmevents
  - mm/memcontrol.c:memcg_flush_percpu_vmstats
  - mm/memcontrol.c:memcg_flush_percpu_vmstats
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:mem_cgroup_handle_over_high
  - mm/memcontrol.c:memcg_hotplug_cpu_dead
  - mm/memcontrol.c:memcg_hotplug_cpu_dead
  - mm/memcontrol.c:memcg_hotplug_cpu_dead
  - mm/memcontrol.c:mem_cgroup_get_oom_group
  - mm/memcontrol.c:__count_memcg_events
  - mm/memcontrol.c:__mod_lruvec_state
  - mm/memcontrol.c:__mod_memcg_state
  - mm/memcontrol.c:page_cgroup_ino
```
```
In mm/vmpressure.c (ffffffff812b26b3)
Location: include/linux/memcontrol.h:490
Inline: True
Inline callers:
  - mm/vmpressure.c:vmpressure_work_fn
```
```
In net/core/sock.c (ffffffff8186c7b2)
Location: include/linux/memcontrol.h:490
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_raise_allocated
```
```
In net/ipv4/tcp.c (ffffffff8191aa98)
Location: include/linux/memcontrol.h:490
Inline: True
```
```
In net/ipv4/tcp_input.c (ffffffff8191df74)
Location: include/linux/memcontrol.h:490
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_check_space
```
```
In net/ipv4/tcp_output.c (ffffffff8192e584)
Location: include/linux/memcontrol.h:490
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_output.c:__tcp_select_window
```
```
In net/ipv4/tcp_timer.c (ffffffff8192f778)
Location: include/linux/memcontrol.h:490
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
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
In mm/oom_kill.c (ffffffff8121fe8e)
Location: include/linux/memcontrol.h:490
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
```
```
In mm/vmscan.c (ffffffff81231d73)
Location: include/linux/memcontrol.h:490
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_node
```
```
In mm/slub.c (ffffffff8129a1d3)
Location: include/linux/memcontrol.h:490
Inline: True
Inline callers:
  - mm/slub.c:alloc_slab_page
```
```
In mm/memcontrol.c (ffffffff812bf0f0)
Location: include/linux/memcontrol.h:490
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_swap_full
  - mm/memcontrol.c:mem_cgroup_get_nr_swap_pages
  - mm/memcontrol.c:mem_cgroup_try_charge_swap
  - mm/memcontrol.c:mem_cgroup_id_get_online
  - mm/memcontrol.c:mem_cgroup_protected
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:mem_cgroup_css_released
  - mm/memcontrol.c:mem_cgroup_wb_stats
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:memcg_flush_percpu_vmevents
  - mm/memcontrol.c:memcg_flush_percpu_vmstats
  - mm/memcontrol.c:memcg_flush_percpu_vmstats
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:mem_cgroup_handle_over_high
  - mm/memcontrol.c:memcg_hotplug_cpu_dead
  - mm/memcontrol.c:memcg_hotplug_cpu_dead
  - mm/memcontrol.c:memcg_hotplug_cpu_dead
  - mm/memcontrol.c:mem_cgroup_get_oom_group
  - mm/memcontrol.c:__count_memcg_events
  - mm/memcontrol.c:__mod_lruvec_state
  - mm/memcontrol.c:__mod_memcg_state
  - mm/memcontrol.c:page_cgroup_ino
```
```
In mm/vmpressure.c (ffffffff812bf473)
Location: include/linux/memcontrol.h:490
Inline: True
Inline callers:
  - mm/vmpressure.c:vmpressure_work_fn
```
```
In net/core/sock.c (ffffffff81903862)
Location: include/linux/memcontrol.h:490
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_raise_allocated
```
```
In net/ipv4/tcp.c (ffffffff819cb778)
Location: include/linux/memcontrol.h:490
Inline: True
```
```
In net/ipv4/tcp_input.c (ffffffff819cec54)
Location: include/linux/memcontrol.h:490
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_check_space
```
```
In net/ipv4/tcp_output.c (ffffffff819df294)
Location: include/linux/memcontrol.h:490
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_output.c:__tcp_select_window
```
```
In net/ipv4/tcp_timer.c (ffffffff819e0488)
Location: include/linux/memcontrol.h:490
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
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
In mm/oom_kill.c (ffffffff8122ef73)
Location: include/linux/memcontrol.h:490
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
```
```
In mm/vmscan.c (ffffffff812411d3)
Location: include/linux/memcontrol.h:490
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_node
```
```
In mm/slub.c (ffffffff812a9fe0)
Location: include/linux/memcontrol.h:490
Inline: True
Inline callers:
  - mm/slub.c:alloc_slab_page
```
```
In mm/memcontrol.c (ffffffff812cfb60)
Location: include/linux/memcontrol.h:490
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_swap_full
  - mm/memcontrol.c:mem_cgroup_get_nr_swap_pages
  - mm/memcontrol.c:mem_cgroup_try_charge_swap
  - mm/memcontrol.c:mem_cgroup_id_get_online
  - mm/memcontrol.c:mem_cgroup_protected
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:mem_cgroup_css_released
  - mm/memcontrol.c:mem_cgroup_wb_stats
  - mm/memcontrol.c:memcg_stat_show
  - mm/memcontrol.c:memcg_flush_percpu_vmevents
  - mm/memcontrol.c:memcg_flush_percpu_vmstats
  - mm/memcontrol.c:memcg_flush_percpu_vmstats
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:mem_cgroup_handle_over_high
  - mm/memcontrol.c:memcg_hotplug_cpu_dead
  - mm/memcontrol.c:memcg_hotplug_cpu_dead
  - mm/memcontrol.c:memcg_hotplug_cpu_dead
  - mm/memcontrol.c:mem_cgroup_get_oom_group
  - mm/memcontrol.c:__count_memcg_events
  - mm/memcontrol.c:__mod_lruvec_state
  - mm/memcontrol.c:__mod_memcg_state
  - mm/memcontrol.c:page_cgroup_ino
```
```
In mm/vmpressure.c (ffffffff812cfed4)
Location: include/linux/memcontrol.h:490
Inline: True
Inline callers:
  - mm/vmpressure.c:vmpressure_work_fn
```
```
In net/core/sock.c (ffffffff81924856)
Location: include/linux/memcontrol.h:490
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_raise_allocated
```
```
In net/ipv4/tcp.c (ffffffff819d5308)
Location: include/linux/memcontrol.h:490
Inline: True
```
```
In net/ipv4/tcp_input.c (ffffffff819d87e4)
Location: include/linux/memcontrol.h:490
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_check_space
```
```
In net/ipv4/tcp_output.c (ffffffff819e8f34)
Location: include/linux/memcontrol.h:490
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_fin
  - net/ipv4/tcp_output.c:__tcp_select_window
```
```
In net/ipv4/tcp_timer.c (ffffffff819ea148)
Location: include/linux/memcontrol.h:490
Inline: True
Inline callers:
  - net/ipv4/tcp_timer.c:tcp_delack_timer_handler
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
