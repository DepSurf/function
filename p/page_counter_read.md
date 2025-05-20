# Function: <code>page_counter_read</code>

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
In mm/memcontrol.c (ffffffff811f96b5)
Location: include/linux/page_counter.h:32
Inline: True
Inline callers:
  - mm/memcontrol.c:memory_current_read
  - mm/memcontrol.c:mem_cgroup_force_empty_write
  - mm/memcontrol.c:mem_cgroup_css_free
  - mm/memcontrol.c:__mem_cgroup_largest_soft_limit_node
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:__mem_cgroup_threshold
  - mm/memcontrol.c:__mem_cgroup_threshold
  - mm/memcontrol.c:__mem_cgroup_usage_unregister_event
  - mm/memcontrol.c:__mem_cgroup_usage_unregister_event
  - mm/memcontrol.c:__mem_cgroup_usage_register_event
  - mm/memcontrol.c:__mem_cgroup_usage_register_event
  - mm/memcontrol.c:mem_cgroup_read_u64
  - mm/memcontrol.c:mem_cgroup_read_u64
  - mm/memcontrol.c:mem_cgroup_read_u64
  - mm/memcontrol.c:mem_cgroup_resize_limit
  - mm/memcontrol.c:mem_cgroup_resize_limit
  - mm/memcontrol.c:mem_cgroup_resize_memsw_limit
  - mm/memcontrol.c:mem_cgroup_resize_memsw_limit
  - mm/memcontrol.c:mem_cgroup_print_oom_info
  - mm/memcontrol.c:mem_cgroup_print_oom_info
  - mm/memcontrol.c:mem_cgroup_print_oom_info
  - mm/memcontrol.c:mem_cgroup_handle_over_high
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:mem_cgroup_wb_stats
  - mm/memcontrol.c:mem_cgroup_low
  - mm/memcontrol.c:mem_cgroup_low
```
```
In mm/hugetlb_cgroup.c (ffffffff81200e50)
Location: include/linux/page_counter.h:32
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_reset
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline
```
```
In net/core/sock.c (ffffffff81702aad)
Location: include/linux/page_counter.h:32
Inline: True
Inline callers:
  - net/core/sock.c:__sk_mem_schedule
  - net/core/sock.c:__sk_mem_schedule
```
```
In net/ipv4/tcp.c (0)
Location: include/linux/page_counter.h:32
Inline: True
```
```
In net/ipv4/tcp_input.c (0)
Location: include/linux/page_counter.h:32
Inline: True
```
```
In net/ipv4/tcp_output.c (ffffffff81778f9f)
Location: include/linux/page_counter.h:32
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:sk_forced_mem_schedule
  - net/ipv4/tcp_output.c:sk_forced_mem_schedule
```
```
In net/ipv4/tcp_memcontrol.c (ffffffff817acf1c)
Location: include/linux/page_counter.h:32
Inline: True
Inline callers:
  - net/ipv4/tcp_memcontrol.c:tcp_cgroup_reset
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
In mm/memcontrol.c (ffffffff8121d215)
Location: include/linux/page_counter.h:32
Inline: True
Inline callers:
  - mm/memcontrol.c:swap_current_read
  - mm/memcontrol.c:mem_cgroup_swap_full
  - mm/memcontrol.c:mem_cgroup_get_nr_swap_pages
  - mm/memcontrol.c:mem_cgroup_low
  - mm/memcontrol.c:mem_cgroup_low
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:memory_high_write
  - mm/memcontrol.c:memory_current_read
  - mm/memcontrol.c:mem_cgroup_css_free
  - mm/memcontrol.c:mem_cgroup_wb_stats
  - mm/memcontrol.c:__mem_cgroup_usage_unregister_event
  - mm/memcontrol.c:__mem_cgroup_usage_unregister_event
  - mm/memcontrol.c:__mem_cgroup_usage_register_event
  - mm/memcontrol.c:__mem_cgroup_usage_register_event
  - mm/memcontrol.c:__mem_cgroup_threshold
  - mm/memcontrol.c:__mem_cgroup_threshold
  - mm/memcontrol.c:mem_cgroup_write
  - mm/memcontrol.c:mem_cgroup_write
  - mm/memcontrol.c:mem_cgroup_write
  - mm/memcontrol.c:mem_cgroup_write
  - mm/memcontrol.c:mem_cgroup_read_u64
  - mm/memcontrol.c:mem_cgroup_read_u64
  - mm/memcontrol.c:mem_cgroup_read_u64
  - mm/memcontrol.c:mem_cgroup_force_empty_write
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:mem_cgroup_print_oom_info
  - mm/memcontrol.c:mem_cgroup_print_oom_info
  - mm/memcontrol.c:mem_cgroup_print_oom_info
  - mm/memcontrol.c:__mem_cgroup_largest_soft_limit_node
```
```
In mm/hugetlb_cgroup.c (ffffffff812255c0)
Location: include/linux/page_counter.h:32
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_reset
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline
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
In mm/memcontrol.c (ffffffff8122f815)
Location: include/linux/page_counter.h:32
Inline: True
Inline callers:
  - mm/memcontrol.c:swap_current_read
  - mm/memcontrol.c:mem_cgroup_swap_full
  - mm/memcontrol.c:mem_cgroup_get_nr_swap_pages
  - mm/memcontrol.c:mem_cgroup_low
  - mm/memcontrol.c:mem_cgroup_low
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:memory_high_write
  - mm/memcontrol.c:memory_current_read
  - mm/memcontrol.c:mem_cgroup_css_free
  - mm/memcontrol.c:mem_cgroup_wb_stats
  - mm/memcontrol.c:__mem_cgroup_usage_unregister_event
  - mm/memcontrol.c:__mem_cgroup_usage_unregister_event
  - mm/memcontrol.c:__mem_cgroup_usage_register_event
  - mm/memcontrol.c:__mem_cgroup_usage_register_event
  - mm/memcontrol.c:__mem_cgroup_threshold
  - mm/memcontrol.c:__mem_cgroup_threshold
  - mm/memcontrol.c:mem_cgroup_write
  - mm/memcontrol.c:mem_cgroup_write
  - mm/memcontrol.c:mem_cgroup_write
  - mm/memcontrol.c:mem_cgroup_write
  - mm/memcontrol.c:mem_cgroup_read_u64
  - mm/memcontrol.c:mem_cgroup_read_u64
  - mm/memcontrol.c:mem_cgroup_read_u64
  - mm/memcontrol.c:mem_cgroup_force_empty_write
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:mem_cgroup_print_oom_info
  - mm/memcontrol.c:mem_cgroup_print_oom_info
  - mm/memcontrol.c:mem_cgroup_print_oom_info
  - mm/memcontrol.c:__mem_cgroup_largest_soft_limit_node
```
```
In mm/hugetlb_cgroup.c (ffffffff81237ba0)
Location: include/linux/page_counter.h:32
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_reset
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline
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
In mm/memcontrol.c (ffffffff8123b015)
Location: include/linux/page_counter.h:32
Inline: True
Inline callers:
  - mm/memcontrol.c:swap_current_read
  - mm/memcontrol.c:mem_cgroup_swap_full
  - mm/memcontrol.c:mem_cgroup_get_nr_swap_pages
  - mm/memcontrol.c:mem_cgroup_low
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:memory_high_write
  - mm/memcontrol.c:memory_current_read
  - mm/memcontrol.c:mem_cgroup_css_free
  - mm/memcontrol.c:mem_cgroup_wb_stats
  - mm/memcontrol.c:__mem_cgroup_usage_unregister_event
  - mm/memcontrol.c:__mem_cgroup_usage_unregister_event
  - mm/memcontrol.c:__mem_cgroup_usage_register_event
  - mm/memcontrol.c:__mem_cgroup_usage_register_event
  - mm/memcontrol.c:__mem_cgroup_threshold
  - mm/memcontrol.c:__mem_cgroup_threshold
  - mm/memcontrol.c:mem_cgroup_reset
  - mm/memcontrol.c:mem_cgroup_write
  - mm/memcontrol.c:mem_cgroup_write
  - mm/memcontrol.c:mem_cgroup_write
  - mm/memcontrol.c:mem_cgroup_write
  - mm/memcontrol.c:mem_cgroup_read_u64
  - mm/memcontrol.c:mem_cgroup_read_u64
  - mm/memcontrol.c:mem_cgroup_read_u64
  - mm/memcontrol.c:mem_cgroup_force_empty_write
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:mem_cgroup_print_oom_info
  - mm/memcontrol.c:mem_cgroup_print_oom_info
  - mm/memcontrol.c:mem_cgroup_print_oom_info
  - mm/memcontrol.c:__mem_cgroup_largest_soft_limit_node
```
```
In mm/hugetlb_cgroup.c (ffffffff81243810)
Location: include/linux/page_counter.h:32
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_reset
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline
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
In mm/memcontrol.c (ffffffff8125a8a5)
Location: include/linux/page_counter.h:33
Inline: True
Inline callers:
  - mm/memcontrol.c:swap_current_read
  - mm/memcontrol.c:mem_cgroup_swap_full
  - mm/memcontrol.c:mem_cgroup_get_nr_swap_pages
  - mm/memcontrol.c:mem_cgroup_low
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:memory_high_write
  - mm/memcontrol.c:memory_current_read
  - mm/memcontrol.c:mem_cgroup_css_free
  - mm/memcontrol.c:mem_cgroup_wb_stats
  - mm/memcontrol.c:__mem_cgroup_usage_unregister_event
  - mm/memcontrol.c:__mem_cgroup_usage_unregister_event
  - mm/memcontrol.c:__mem_cgroup_usage_register_event
  - mm/memcontrol.c:__mem_cgroup_usage_register_event
  - mm/memcontrol.c:__mem_cgroup_threshold
  - mm/memcontrol.c:__mem_cgroup_threshold
  - mm/memcontrol.c:mem_cgroup_reset
  - mm/memcontrol.c:mem_cgroup_write
  - mm/memcontrol.c:mem_cgroup_write
  - mm/memcontrol.c:mem_cgroup_write
  - mm/memcontrol.c:mem_cgroup_write
  - mm/memcontrol.c:mem_cgroup_read_u64
  - mm/memcontrol.c:mem_cgroup_read_u64
  - mm/memcontrol.c:mem_cgroup_read_u64
  - mm/memcontrol.c:mem_cgroup_force_empty_write
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:mem_cgroup_print_oom_info
  - mm/memcontrol.c:mem_cgroup_print_oom_info
  - mm/memcontrol.c:mem_cgroup_print_oom_info
  - mm/memcontrol.c:__mem_cgroup_largest_soft_limit_node
```
```
In mm/hugetlb_cgroup.c (ffffffff81263660)
Location: include/linux/page_counter.h:33
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_reset
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline
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
In mm/memcontrol.c (ffffffff8127e7b5)
Location: include/linux/page_counter.h:45
Inline: True
Inline callers:
  - mm/memcontrol.c:swap_current_read
  - mm/memcontrol.c:mem_cgroup_swap_full
  - mm/memcontrol.c:mem_cgroup_get_nr_swap_pages
  - mm/memcontrol.c:mem_cgroup_protected
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:memory_high_write
  - mm/memcontrol.c:memory_current_read
  - mm/memcontrol.c:mem_cgroup_css_free
  - mm/memcontrol.c:mem_cgroup_wb_stats
  - mm/memcontrol.c:__mem_cgroup_usage_unregister_event
  - mm/memcontrol.c:__mem_cgroup_usage_unregister_event
  - mm/memcontrol.c:__mem_cgroup_usage_register_event
  - mm/memcontrol.c:__mem_cgroup_usage_register_event
  - mm/memcontrol.c:__mem_cgroup_threshold
  - mm/memcontrol.c:__mem_cgroup_threshold
  - mm/memcontrol.c:mem_cgroup_reset
  - mm/memcontrol.c:mem_cgroup_read_u64
  - mm/memcontrol.c:mem_cgroup_read_u64
  - mm/memcontrol.c:mem_cgroup_read_u64
  - mm/memcontrol.c:mem_cgroup_force_empty_write
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:mem_cgroup_print_oom_info
  - mm/memcontrol.c:mem_cgroup_print_oom_info
  - mm/memcontrol.c:mem_cgroup_print_oom_info
```
```
In mm/hugetlb_cgroup.c (ffffffff81287934)
Location: include/linux/page_counter.h:45
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_reset
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline
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
In mm/memcontrol.c (ffffffff81292f05)
Location: include/linux/page_counter.h:45
Inline: True
Inline callers:
  - mm/memcontrol.c:swap_current_read
  - mm/memcontrol.c:mem_cgroup_swap_full
  - mm/memcontrol.c:mem_cgroup_get_nr_swap_pages
  - mm/memcontrol.c:mem_cgroup_protected
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:memory_high_write
  - mm/memcontrol.c:memory_current_read
  - mm/memcontrol.c:mem_cgroup_css_free
  - mm/memcontrol.c:mem_cgroup_wb_stats
  - mm/memcontrol.c:__mem_cgroup_usage_unregister_event
  - mm/memcontrol.c:__mem_cgroup_usage_unregister_event
  - mm/memcontrol.c:__mem_cgroup_usage_register_event
  - mm/memcontrol.c:__mem_cgroup_usage_register_event
  - mm/memcontrol.c:__mem_cgroup_threshold
  - mm/memcontrol.c:__mem_cgroup_threshold
  - mm/memcontrol.c:mem_cgroup_reset
  - mm/memcontrol.c:mem_cgroup_read_u64
  - mm/memcontrol.c:mem_cgroup_read_u64
  - mm/memcontrol.c:mem_cgroup_read_u64
  - mm/memcontrol.c:mem_cgroup_force_empty_write
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:mem_cgroup_print_oom_meminfo
  - mm/memcontrol.c:mem_cgroup_print_oom_meminfo
  - mm/memcontrol.c:mem_cgroup_print_oom_meminfo
```
```
In mm/hugetlb_cgroup.c (ffffffff8129c884)
Location: include/linux/page_counter.h:45
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_reset
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline
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
In mm/memcontrol.c (ffffffff812ad7a5)
Location: include/linux/page_counter.h:45
Inline: True
Inline callers:
  - mm/memcontrol.c:swap_current_read
  - mm/memcontrol.c:mem_cgroup_swap_full
  - mm/memcontrol.c:mem_cgroup_get_nr_swap_pages
  - mm/memcontrol.c:mem_cgroup_protected
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:memory_high_write
  - mm/memcontrol.c:memory_current_read
  - mm/memcontrol.c:mem_cgroup_wb_stats
  - mm/memcontrol.c:__mem_cgroup_usage_unregister_event
  - mm/memcontrol.c:__mem_cgroup_usage_unregister_event
  - mm/memcontrol.c:__mem_cgroup_usage_register_event
  - mm/memcontrol.c:__mem_cgroup_usage_register_event
  - mm/memcontrol.c:__mem_cgroup_threshold
  - mm/memcontrol.c:__mem_cgroup_threshold
  - mm/memcontrol.c:mem_cgroup_reset
  - mm/memcontrol.c:mem_cgroup_read_u64
  - mm/memcontrol.c:mem_cgroup_read_u64
  - mm/memcontrol.c:mem_cgroup_read_u64
  - mm/memcontrol.c:mem_cgroup_force_empty_write
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:mem_cgroup_print_oom_meminfo
  - mm/memcontrol.c:mem_cgroup_print_oom_meminfo
  - mm/memcontrol.c:mem_cgroup_print_oom_meminfo
  - mm/memcontrol.c:mem_cgroup_print_oom_meminfo
  - mm/memcontrol.c:__mem_cgroup_largest_soft_limit_node
```
```
In mm/hugetlb_cgroup.c (ffffffff812b7a43)
Location: include/linux/page_counter.h:45
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_reset
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline
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
In mm/memcontrol.c (ffffffff812bf2f5)
Location: include/linux/page_counter.h:45
Inline: True
Inline callers:
  - mm/memcontrol.c:swap_current_read
  - mm/memcontrol.c:mem_cgroup_swap_full
  - mm/memcontrol.c:mem_cgroup_get_nr_swap_pages
  - mm/memcontrol.c:mem_cgroup_protected
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:memory_high_write
  - mm/memcontrol.c:memory_current_read
  - mm/memcontrol.c:mem_cgroup_wb_stats
  - mm/memcontrol.c:__mem_cgroup_usage_unregister_event
  - mm/memcontrol.c:__mem_cgroup_usage_unregister_event
  - mm/memcontrol.c:__mem_cgroup_usage_register_event
  - mm/memcontrol.c:__mem_cgroup_usage_register_event
  - mm/memcontrol.c:__mem_cgroup_threshold
  - mm/memcontrol.c:__mem_cgroup_threshold
  - mm/memcontrol.c:mem_cgroup_reset
  - mm/memcontrol.c:mem_cgroup_read_u64
  - mm/memcontrol.c:mem_cgroup_read_u64
  - mm/memcontrol.c:mem_cgroup_read_u64
  - mm/memcontrol.c:mem_cgroup_force_empty_write
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:mem_cgroup_handle_over_high
  - mm/memcontrol.c:mem_cgroup_size
  - mm/memcontrol.c:mem_cgroup_print_oom_meminfo
  - mm/memcontrol.c:mem_cgroup_print_oom_meminfo
  - mm/memcontrol.c:mem_cgroup_print_oom_meminfo
  - mm/memcontrol.c:mem_cgroup_print_oom_meminfo
  - mm/memcontrol.c:__mem_cgroup_largest_soft_limit_node
```
```
In mm/hugetlb_cgroup.c (ffffffff812c9923)
Location: include/linux/page_counter.h:45
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_reset
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline
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
In mm/memcontrol.c (ffffffff812f45f5)
Location: include/linux/page_counter.h:46
Inline: True
Inline callers:
  - mm/memcontrol.c:swap_current_read
  - mm/memcontrol.c:mem_cgroup_swap_full
  - mm/memcontrol.c:mem_cgroup_get_nr_swap_pages
  - mm/memcontrol.c:mem_cgroup_protected
  - mm/memcontrol.c:mem_cgroup_protected
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:memory_high_write
  - mm/memcontrol.c:memory_current_read
  - mm/memcontrol.c:mem_cgroup_wb_stats
  - mm/memcontrol.c:__mem_cgroup_usage_unregister_event
  - mm/memcontrol.c:__mem_cgroup_usage_unregister_event
  - mm/memcontrol.c:__mem_cgroup_usage_register_event
  - mm/memcontrol.c:__mem_cgroup_usage_register_event
  - mm/memcontrol.c:__mem_cgroup_threshold
  - mm/memcontrol.c:__mem_cgroup_threshold
  - mm/memcontrol.c:mem_cgroup_reset
  - mm/memcontrol.c:mem_cgroup_read_u64
  - mm/memcontrol.c:mem_cgroup_read_u64
  - mm/memcontrol.c:mem_cgroup_read_u64
  - mm/memcontrol.c:mem_cgroup_force_empty_write
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:mem_cgroup_handle_over_high
  - mm/memcontrol.c:mem_cgroup_handle_over_high
  - mm/memcontrol.c:mem_cgroup_size
  - mm/memcontrol.c:mem_cgroup_print_oom_meminfo
  - mm/memcontrol.c:mem_cgroup_print_oom_meminfo
  - mm/memcontrol.c:mem_cgroup_print_oom_meminfo
  - mm/memcontrol.c:mem_cgroup_print_oom_meminfo
  - mm/memcontrol.c:__mem_cgroup_largest_soft_limit_node
  - mm/memcontrol.c:mem_cgroup_update_tree
```
```
In mm/hugetlb_cgroup.c (ffffffff812fefb6)
Location: include/linux/page_counter.h:46
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_reset
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_reset
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_read_u64_max
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_read_u64
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_read_u64
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline
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
In mm/vmscan.c (ffffffff812733a3)
Location: include/linux/page_counter.h:46
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_node_memcgs
  - mm/vmscan.c:shrink_node_memcgs
```
```
In mm/page_counter.c (ffffffff812ffc85)
Location: include/linux/page_counter.h:46
Inline: True
Inline callers:
  - mm/page_counter.c:page_counter_set_max
  - mm/page_counter.c:page_counter_set_max
```
```
In mm/memcontrol.c (ffffffff812ffed5)
Location: include/linux/page_counter.h:46
Inline: True
Inline callers:
  - mm/memcontrol.c:swap_current_read
  - mm/memcontrol.c:mem_cgroup_swap_full
  - mm/memcontrol.c:mem_cgroup_get_nr_swap_pages
  - mm/memcontrol.c:mem_cgroup_calculate_protection
  - mm/memcontrol.c:mem_cgroup_calculate_protection
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:memory_high_write
  - mm/memcontrol.c:memory_current_read
  - mm/memcontrol.c:mem_cgroup_wb_stats
  - mm/memcontrol.c:__mem_cgroup_usage_unregister_event
  - mm/memcontrol.c:__mem_cgroup_usage_unregister_event
  - mm/memcontrol.c:__mem_cgroup_usage_register_event
  - mm/memcontrol.c:__mem_cgroup_usage_register_event
  - mm/memcontrol.c:__mem_cgroup_threshold
  - mm/memcontrol.c:__mem_cgroup_threshold
  - mm/memcontrol.c:mem_cgroup_reset
  - mm/memcontrol.c:mem_cgroup_read_u64
  - mm/memcontrol.c:mem_cgroup_read_u64
  - mm/memcontrol.c:mem_cgroup_read_u64
  - mm/memcontrol.c:mem_cgroup_force_empty_write
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:mem_cgroup_handle_over_high
  - mm/memcontrol.c:mem_cgroup_handle_over_high
  - mm/memcontrol.c:mem_cgroup_out_of_memory
  - mm/memcontrol.c:mem_cgroup_out_of_memory
  - mm/memcontrol.c:mem_cgroup_size
  - mm/memcontrol.c:mem_cgroup_print_oom_meminfo
  - mm/memcontrol.c:mem_cgroup_print_oom_meminfo
  - mm/memcontrol.c:mem_cgroup_print_oom_meminfo
  - mm/memcontrol.c:mem_cgroup_print_oom_meminfo
  - mm/memcontrol.c:__mem_cgroup_largest_soft_limit_node
  - mm/memcontrol.c:mem_cgroup_update_tree
```
```
In mm/hugetlb_cgroup.c (ffffffff8130b2f6)
Location: include/linux/page_counter.h:46
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_reset
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_reset
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_read_u64_max
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_read_u64
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_read_u64
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline
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
In mm/vmscan.c (ffffffff812786c3)
Location: include/linux/page_counter.h:53
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_node_memcgs
  - mm/vmscan.c:shrink_node_memcgs
```
```
In mm/page_counter.c (ffffffff81306925)
Location: include/linux/page_counter.h:53
Inline: True
Inline callers:
  - mm/page_counter.c:page_counter_set_max
  - mm/page_counter.c:page_counter_set_max
```
```
In mm/memcontrol.c (ffffffff81306d15)
Location: include/linux/page_counter.h:53
Inline: True
Inline callers:
  - mm/memcontrol.c:swap_current_read
  - mm/memcontrol.c:mem_cgroup_swap_full
  - mm/memcontrol.c:mem_cgroup_get_nr_swap_pages
  - mm/memcontrol.c:mem_cgroup_calculate_protection
  - mm/memcontrol.c:mem_cgroup_calculate_protection
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:memory_high_write
  - mm/memcontrol.c:memory_current_read
  - mm/memcontrol.c:mem_cgroup_wb_stats
  - mm/memcontrol.c:__mem_cgroup_usage_unregister_event
  - mm/memcontrol.c:__mem_cgroup_usage_unregister_event
  - mm/memcontrol.c:__mem_cgroup_usage_register_event
  - mm/memcontrol.c:__mem_cgroup_usage_register_event
  - mm/memcontrol.c:__mem_cgroup_threshold
  - mm/memcontrol.c:__mem_cgroup_threshold
  - mm/memcontrol.c:mem_cgroup_reset
  - mm/memcontrol.c:mem_cgroup_read_u64
  - mm/memcontrol.c:mem_cgroup_read_u64
  - mm/memcontrol.c:mem_cgroup_read_u64
  - mm/memcontrol.c:mem_cgroup_force_empty_write
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:mem_cgroup_handle_over_high
  - mm/memcontrol.c:mem_cgroup_handle_over_high
  - mm/memcontrol.c:mem_cgroup_out_of_memory
  - mm/memcontrol.c:mem_cgroup_out_of_memory
  - mm/memcontrol.c:mem_cgroup_size
  - mm/memcontrol.c:mem_cgroup_print_oom_meminfo
  - mm/memcontrol.c:mem_cgroup_print_oom_meminfo
  - mm/memcontrol.c:mem_cgroup_print_oom_meminfo
  - mm/memcontrol.c:mem_cgroup_print_oom_meminfo
  - mm/memcontrol.c:__mem_cgroup_largest_soft_limit_node
```
```
In mm/hugetlb_cgroup.c (ffffffff81311956)
Location: include/linux/page_counter.h:53
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_reset
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_reset
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_read_u64_max
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_read_u64
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_read_u64
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline
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
In mm/vmscan.c (ffffffff812b6423)
Location: include/linux/page_counter.h:53
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_node_memcgs
  - mm/vmscan.c:shrink_node_memcgs
```
```
In mm/page_counter.c (ffffffff81350775)
Location: include/linux/page_counter.h:53
Inline: True
Inline callers:
  - mm/page_counter.c:page_counter_set_max
  - mm/page_counter.c:page_counter_set_max
```
```
In mm/memcontrol.c (ffffffff81350a15)
Location: include/linux/page_counter.h:53
Inline: True
Inline callers:
  - mm/memcontrol.c:swap_current_read
  - mm/memcontrol.c:mem_cgroup_swap_full
  - mm/memcontrol.c:mem_cgroup_get_nr_swap_pages
  - mm/memcontrol.c:mem_cgroup_calculate_protection
  - mm/memcontrol.c:mem_cgroup_calculate_protection
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:memory_high_write
  - mm/memcontrol.c:memory_current_read
  - mm/memcontrol.c:mem_cgroup_wb_stats
  - mm/memcontrol.c:__mem_cgroup_usage_unregister_event
  - mm/memcontrol.c:__mem_cgroup_usage_unregister_event
  - mm/memcontrol.c:__mem_cgroup_usage_register_event
  - mm/memcontrol.c:__mem_cgroup_usage_register_event
  - mm/memcontrol.c:__mem_cgroup_threshold
  - mm/memcontrol.c:__mem_cgroup_threshold
  - mm/memcontrol.c:mem_cgroup_reset
  - mm/memcontrol.c:mem_cgroup_read_u64
  - mm/memcontrol.c:mem_cgroup_read_u64
  - mm/memcontrol.c:mem_cgroup_read_u64
  - mm/memcontrol.c:mem_cgroup_force_empty_write
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:try_charge_memcg
  - mm/memcontrol.c:try_charge_memcg
  - mm/memcontrol.c:try_charge_memcg
  - mm/memcontrol.c:try_charge_memcg
  - mm/memcontrol.c:mem_cgroup_handle_over_high
  - mm/memcontrol.c:mem_cgroup_handle_over_high
  - mm/memcontrol.c:mem_cgroup_out_of_memory
  - mm/memcontrol.c:mem_cgroup_out_of_memory
  - mm/memcontrol.c:mem_cgroup_size
  - mm/memcontrol.c:mem_cgroup_print_oom_meminfo
  - mm/memcontrol.c:mem_cgroup_print_oom_meminfo
  - mm/memcontrol.c:mem_cgroup_print_oom_meminfo
  - mm/memcontrol.c:mem_cgroup_print_oom_meminfo
  - mm/memcontrol.c:__mem_cgroup_largest_soft_limit_node
```
```
In mm/hugetlb_cgroup.c (ffffffff8135cd75)
Location: include/linux/page_counter.h:53
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_reset
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_reset
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_read_u64_max
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_read_u64
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_read_u64
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline
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
In mm/vmscan.c (ffffffff813118c7)
Location: include/linux/page_counter.h:53
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_node_memcgs
  - mm/vmscan.c:shrink_node_memcgs
```
```
In mm/page_counter.c (ffffffff813c8a95)
Location: include/linux/page_counter.h:53
Inline: True
Inline callers:
  - mm/page_counter.c:page_counter_set_max
  - mm/page_counter.c:page_counter_set_max
```
```
In mm/memcontrol.c (ffffffff813c8ea5)
Location: include/linux/page_counter.h:53
Inline: True
Inline callers:
  - mm/memcontrol.c:swap_current_read
  - mm/memcontrol.c:mem_cgroup_swap_full
  - mm/memcontrol.c:mem_cgroup_get_nr_swap_pages
  - mm/memcontrol.c:mem_cgroup_calculate_protection
  - mm/memcontrol.c:mem_cgroup_calculate_protection
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:memory_high_write
  - mm/memcontrol.c:memory_current_read
  - mm/memcontrol.c:mem_cgroup_wb_stats
  - mm/memcontrol.c:__mem_cgroup_usage_unregister_event
  - mm/memcontrol.c:__mem_cgroup_usage_unregister_event
  - mm/memcontrol.c:__mem_cgroup_usage_register_event
  - mm/memcontrol.c:__mem_cgroup_usage_register_event
  - mm/memcontrol.c:__mem_cgroup_threshold
  - mm/memcontrol.c:__mem_cgroup_threshold
  - mm/memcontrol.c:mem_cgroup_reset
  - mm/memcontrol.c:mem_cgroup_read_u64
  - mm/memcontrol.c:mem_cgroup_read_u64
  - mm/memcontrol.c:mem_cgroup_read_u64
  - mm/memcontrol.c:mem_cgroup_force_empty_write
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:try_charge_memcg
  - mm/memcontrol.c:try_charge_memcg
  - mm/memcontrol.c:try_charge_memcg
  - mm/memcontrol.c:try_charge_memcg
  - mm/memcontrol.c:mem_cgroup_handle_over_high
  - mm/memcontrol.c:mem_cgroup_handle_over_high
  - mm/memcontrol.c:mem_cgroup_out_of_memory
  - mm/memcontrol.c:mem_cgroup_out_of_memory
  - mm/memcontrol.c:mem_cgroup_size
  - mm/memcontrol.c:mem_cgroup_print_oom_meminfo
  - mm/memcontrol.c:mem_cgroup_print_oom_meminfo
  - mm/memcontrol.c:mem_cgroup_print_oom_meminfo
  - mm/memcontrol.c:mem_cgroup_print_oom_meminfo
  - mm/memcontrol.c:__mem_cgroup_largest_soft_limit_node
```
```
In mm/hugetlb_cgroup.c (ffffffff813d6a69)
Location: include/linux/page_counter.h:53
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_reset
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_reset
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_read_u64_max
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_read_u64
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_read_u64
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_read_numa_stat
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline
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
In mm/vmscan.c (ffffffff81384f3b)
Location: include/linux/page_counter.h:55
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_node_memcgs
  - mm/vmscan.c:shrink_node_memcgs
  - mm/vmscan.c:get_nr_to_scan
  - mm/vmscan.c:get_nr_to_scan
  - mm/vmscan.c:lru_gen_age_node
```
```
In mm/page_counter.c (ffffffff8144d1a5)
Location: include/linux/page_counter.h:55
Inline: True
Inline callers:
  - mm/page_counter.c:page_counter_set_max
  - mm/page_counter.c:page_counter_set_max
```
```
In mm/memcontrol.c (ffffffff8144d695)
Location: include/linux/page_counter.h:55
Inline: True
Inline callers:
  - mm/memcontrol.c:swap_current_read
  - mm/memcontrol.c:mem_cgroup_swap_full
  - mm/memcontrol.c:mem_cgroup_get_nr_swap_pages
  - mm/memcontrol.c:mem_cgroup_calculate_protection
  - mm/memcontrol.c:mem_cgroup_calculate_protection
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:memory_high_write
  - mm/memcontrol.c:memory_current_read
  - mm/memcontrol.c:mem_cgroup_wb_stats
  - mm/memcontrol.c:__mem_cgroup_usage_unregister_event
  - mm/memcontrol.c:__mem_cgroup_threshold
  - mm/memcontrol.c:__mem_cgroup_threshold
  - mm/memcontrol.c:mem_cgroup_reset
  - mm/memcontrol.c:mem_cgroup_read_u64
  - mm/memcontrol.c:mem_cgroup_force_empty_write
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:try_charge_memcg
  - mm/memcontrol.c:try_charge_memcg
  - mm/memcontrol.c:try_charge_memcg
  - mm/memcontrol.c:try_charge_memcg
  - mm/memcontrol.c:mem_cgroup_handle_over_high
  - mm/memcontrol.c:mem_cgroup_handle_over_high
  - mm/memcontrol.c:mem_cgroup_out_of_memory
  - mm/memcontrol.c:mem_cgroup_out_of_memory
  - mm/memcontrol.c:mem_cgroup_size
  - mm/memcontrol.c:mem_cgroup_print_oom_meminfo
  - mm/memcontrol.c:mem_cgroup_print_oom_meminfo
  - mm/memcontrol.c:mem_cgroup_print_oom_meminfo
  - mm/memcontrol.c:mem_cgroup_print_oom_meminfo
  - mm/memcontrol.c:__mem_cgroup_largest_soft_limit_node
```
```
In mm/hugetlb_cgroup.c (ffffffff8145c573)
Location: include/linux/page_counter.h:55
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_reset
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_reset
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_read_u64_max
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_read_u64
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_read_u64
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_read_numa_stat
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline
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
In mm/vmscan.c (ffffffff813b6a9b)
Location: include/linux/page_counter.h:55
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_node_memcgs
  - mm/vmscan.c:shrink_node_memcgs
  - mm/vmscan.c:shrink_one
  - mm/vmscan.c:shrink_one
  - mm/vmscan.c:try_to_shrink_lruvec
  - mm/vmscan.c:lru_gen_age_node
```
```
In mm/page_counter.c (ffffffff81482a65)
Location: include/linux/page_counter.h:55
Inline: True
Inline callers:
  - mm/page_counter.c:page_counter_set_max
  - mm/page_counter.c:page_counter_set_max
```
```
In mm/memcontrol.c (ffffffff81482f85)
Location: include/linux/page_counter.h:55
Inline: True
Inline callers:
  - mm/memcontrol.c:swap_current_read
  - mm/memcontrol.c:mem_cgroup_swap_full
  - mm/memcontrol.c:mem_cgroup_get_nr_swap_pages
  - mm/memcontrol.c:mem_cgroup_calculate_protection
  - mm/memcontrol.c:mem_cgroup_calculate_protection
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:memory_high_write
  - mm/memcontrol.c:memory_current_read
  - mm/memcontrol.c:mem_cgroup_wb_stats
  - mm/memcontrol.c:__mem_cgroup_usage_unregister_event
  - mm/memcontrol.c:__mem_cgroup_usage_unregister_event
  - mm/memcontrol.c:__mem_cgroup_usage_register_event
  - mm/memcontrol.c:__mem_cgroup_usage_register_event
  - mm/memcontrol.c:__mem_cgroup_threshold
  - mm/memcontrol.c:__mem_cgroup_threshold
  - mm/memcontrol.c:mem_cgroup_reset
  - mm/memcontrol.c:mem_cgroup_read_u64
  - mm/memcontrol.c:mem_cgroup_read_u64
  - mm/memcontrol.c:mem_cgroup_read_u64
  - mm/memcontrol.c:mem_cgroup_force_empty_write
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:try_charge_memcg
  - mm/memcontrol.c:try_charge_memcg
  - mm/memcontrol.c:try_charge_memcg
  - mm/memcontrol.c:try_charge_memcg
  - mm/memcontrol.c:mem_cgroup_handle_over_high
  - mm/memcontrol.c:mem_cgroup_handle_over_high
  - mm/memcontrol.c:mem_cgroup_out_of_memory
  - mm/memcontrol.c:mem_cgroup_out_of_memory
  - mm/memcontrol.c:mem_cgroup_size
  - mm/memcontrol.c:mem_cgroup_print_oom_meminfo
  - mm/memcontrol.c:mem_cgroup_print_oom_meminfo
  - mm/memcontrol.c:mem_cgroup_print_oom_meminfo
  - mm/memcontrol.c:mem_cgroup_print_oom_meminfo
  - mm/memcontrol.c:memcg_check_events
  - mm/memcontrol.c:memcg_check_events
  - mm/memcontrol.c:__mem_cgroup_largest_soft_limit_node
```
```
In mm/hugetlb_cgroup.c (ffffffff81492202)
Location: include/linux/page_counter.h:55
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_reset
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_reset
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_read_u64_max
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_read_u64
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_read_u64
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_read_numa_stat
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline
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
In mm/vmscan.c (ffffffff813df95b)
Location: include/linux/page_counter.h:55
Inline: True
Inline callers:
  - mm/vmscan.c:shrink_node_memcgs
  - mm/vmscan.c:shrink_node_memcgs
  - mm/vmscan.c:shrink_one
  - mm/vmscan.c:shrink_one
  - mm/vmscan.c:try_to_shrink_lruvec
  - mm/vmscan.c:lru_gen_age_node
```
```
In mm/page_counter.c (ffffffff814b1de5)
Location: include/linux/page_counter.h:55
Inline: True
Inline callers:
  - mm/page_counter.c:page_counter_set_max
  - mm/page_counter.c:page_counter_set_max
```
```
In mm/memcontrol.c (ffffffff814b2335)
Location: include/linux/page_counter.h:55
Inline: True
Inline callers:
  - mm/memcontrol.c:swap_current_read
  - mm/memcontrol.c:mem_cgroup_swap_full
  - mm/memcontrol.c:mem_cgroup_get_nr_swap_pages
  - mm/memcontrol.c:mem_cgroup_calculate_protection
  - mm/memcontrol.c:mem_cgroup_calculate_protection
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:memory_high_write
  - mm/memcontrol.c:memory_current_read
  - mm/memcontrol.c:mem_cgroup_wb_stats
  - mm/memcontrol.c:__mem_cgroup_usage_unregister_event
  - mm/memcontrol.c:__mem_cgroup_usage_unregister_event
  - mm/memcontrol.c:__mem_cgroup_usage_register_event
  - mm/memcontrol.c:__mem_cgroup_usage_register_event
  - mm/memcontrol.c:__mem_cgroup_threshold
  - mm/memcontrol.c:__mem_cgroup_threshold
  - mm/memcontrol.c:mem_cgroup_reset
  - mm/memcontrol.c:mem_cgroup_read_u64
  - mm/memcontrol.c:mem_cgroup_read_u64
  - mm/memcontrol.c:mem_cgroup_read_u64
  - mm/memcontrol.c:mem_cgroup_force_empty_write
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:try_charge_memcg
  - mm/memcontrol.c:try_charge_memcg
  - mm/memcontrol.c:try_charge_memcg
  - mm/memcontrol.c:try_charge_memcg
  - mm/memcontrol.c:mem_cgroup_handle_over_high
  - mm/memcontrol.c:mem_cgroup_handle_over_high
  - mm/memcontrol.c:reclaim_high
  - mm/memcontrol.c:mem_cgroup_out_of_memory
  - mm/memcontrol.c:mem_cgroup_out_of_memory
  - mm/memcontrol.c:mem_cgroup_size
  - mm/memcontrol.c:mem_cgroup_print_oom_meminfo
  - mm/memcontrol.c:mem_cgroup_print_oom_meminfo
  - mm/memcontrol.c:mem_cgroup_print_oom_meminfo
  - mm/memcontrol.c:mem_cgroup_print_oom_meminfo
  - mm/memcontrol.c:memcg_check_events
  - mm/memcontrol.c:memcg_check_events
  - mm/memcontrol.c:__mem_cgroup_largest_soft_limit_node
```
```
In mm/hugetlb_cgroup.c (ffffffff814c1c12)
Location: include/linux/page_counter.h:55
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_reset
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_reset
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_read_u64_max
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_read_u64
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_read_u64
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_read_numa_stat
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline
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
In mm/memcontrol.c (ffff8000103610e0)
Location: include/linux/page_counter.h:45
Inline: True
Inline callers:
  - mm/memcontrol.c:swap_current_read
  - mm/memcontrol.c:mem_cgroup_swap_full
  - mm/memcontrol.c:mem_cgroup_get_nr_swap_pages
  - mm/memcontrol.c:mem_cgroup_protected
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:memory_high_write
  - mm/memcontrol.c:memory_current_read
  - mm/memcontrol.c:mem_cgroup_wb_stats
  - mm/memcontrol.c:__mem_cgroup_usage_unregister_event
  - mm/memcontrol.c:__mem_cgroup_usage_unregister_event
  - mm/memcontrol.c:__mem_cgroup_usage_register_event
  - mm/memcontrol.c:__mem_cgroup_usage_register_event
  - mm/memcontrol.c:__mem_cgroup_threshold
  - mm/memcontrol.c:__mem_cgroup_threshold
  - mm/memcontrol.c:mem_cgroup_reset
  - mm/memcontrol.c:mem_cgroup_read_u64
  - mm/memcontrol.c:mem_cgroup_read_u64
  - mm/memcontrol.c:mem_cgroup_read_u64
  - mm/memcontrol.c:mem_cgroup_force_empty_write
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:mem_cgroup_handle_over_high
  - mm/memcontrol.c:mem_cgroup_size
  - mm/memcontrol.c:mem_cgroup_print_oom_meminfo
  - mm/memcontrol.c:mem_cgroup_print_oom_meminfo
  - mm/memcontrol.c:mem_cgroup_print_oom_meminfo
  - mm/memcontrol.c:mem_cgroup_print_oom_meminfo
  - mm/memcontrol.c:__mem_cgroup_largest_soft_limit_node
```
```
In mm/hugetlb_cgroup.c (ffff80001036d088)
Location: include/linux/page_counter.h:45
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_reset
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline
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
In mm/memcontrol.c (c05536e4)
Location: include/linux/page_counter.h:45
Inline: True
Inline callers:
  - mm/memcontrol.c:swap_current_read
  - mm/memcontrol.c:mem_cgroup_swap_full
  - mm/memcontrol.c:mem_cgroup_get_nr_swap_pages
  - mm/memcontrol.c:mem_cgroup_protected
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:memory_high_write
  - mm/memcontrol.c:memory_current_read
  - mm/memcontrol.c:mem_cgroup_wb_stats
  - mm/memcontrol.c:__mem_cgroup_usage_unregister_event
  - mm/memcontrol.c:__mem_cgroup_usage_unregister_event
  - mm/memcontrol.c:__mem_cgroup_usage_register_event
  - mm/memcontrol.c:__mem_cgroup_usage_register_event
  - mm/memcontrol.c:__mem_cgroup_threshold
  - mm/memcontrol.c:__mem_cgroup_threshold
  - mm/memcontrol.c:mem_cgroup_reset
  - mm/memcontrol.c:mem_cgroup_read_u64
  - mm/memcontrol.c:mem_cgroup_read_u64
  - mm/memcontrol.c:mem_cgroup_read_u64
  - mm/memcontrol.c:mem_cgroup_force_empty_write
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:mem_cgroup_handle_over_high
  - mm/memcontrol.c:mem_cgroup_size
  - mm/memcontrol.c:mem_cgroup_print_oom_meminfo
  - mm/memcontrol.c:mem_cgroup_print_oom_meminfo
  - mm/memcontrol.c:mem_cgroup_print_oom_meminfo
  - mm/memcontrol.c:mem_cgroup_print_oom_meminfo
  - mm/memcontrol.c:__mem_cgroup_largest_soft_limit_node
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
In mm/memcontrol.c (c00000000044c3e8)
Location: include/linux/page_counter.h:45
Inline: True
Inline callers:
  - mm/memcontrol.c:swap_current_read
  - mm/memcontrol.c:mem_cgroup_swap_full
  - mm/memcontrol.c:mem_cgroup_get_nr_swap_pages
  - mm/memcontrol.c:mem_cgroup_protected
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:memory_high_write
  - mm/memcontrol.c:memory_current_read
  - mm/memcontrol.c:mem_cgroup_wb_stats
  - mm/memcontrol.c:__mem_cgroup_usage_unregister_event
  - mm/memcontrol.c:__mem_cgroup_usage_unregister_event
  - mm/memcontrol.c:__mem_cgroup_usage_register_event
  - mm/memcontrol.c:__mem_cgroup_usage_register_event
  - mm/memcontrol.c:__mem_cgroup_threshold
  - mm/memcontrol.c:__mem_cgroup_threshold
  - mm/memcontrol.c:mem_cgroup_reset
  - mm/memcontrol.c:mem_cgroup_read_u64
  - mm/memcontrol.c:mem_cgroup_read_u64
  - mm/memcontrol.c:mem_cgroup_force_empty_write
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:mem_cgroup_handle_over_high
  - mm/memcontrol.c:mem_cgroup_size
  - mm/memcontrol.c:mem_cgroup_print_oom_meminfo
  - mm/memcontrol.c:mem_cgroup_print_oom_meminfo
  - mm/memcontrol.c:mem_cgroup_print_oom_meminfo
  - mm/memcontrol.c:mem_cgroup_print_oom_meminfo
  - mm/memcontrol.c:__mem_cgroup_largest_soft_limit_node
```
```
In mm/hugetlb_cgroup.c (c00000000045d040)
Location: include/linux/page_counter.h:45
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_reset
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline
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
In mm/memcontrol.c (ffffffe000240868)
Location: include/linux/page_counter.h:45
Inline: True
Inline callers:
  - mm/memcontrol.c:swap_current_read
  - mm/memcontrol.c:mem_cgroup_swap_full
  - mm/memcontrol.c:mem_cgroup_get_nr_swap_pages
  - mm/memcontrol.c:mem_cgroup_protected
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:memory_high_write
  - mm/memcontrol.c:memory_current_read
  - mm/memcontrol.c:mem_cgroup_wb_stats
  - mm/memcontrol.c:__mem_cgroup_usage_unregister_event
  - mm/memcontrol.c:__mem_cgroup_usage_unregister_event
  - mm/memcontrol.c:__mem_cgroup_usage_register_event
  - mm/memcontrol.c:__mem_cgroup_usage_register_event
  - mm/memcontrol.c:__mem_cgroup_threshold
  - mm/memcontrol.c:__mem_cgroup_threshold
  - mm/memcontrol.c:mem_cgroup_reset
  - mm/memcontrol.c:mem_cgroup_read_u64
  - mm/memcontrol.c:mem_cgroup_read_u64
  - mm/memcontrol.c:mem_cgroup_read_u64
  - mm/memcontrol.c:mem_cgroup_force_empty_write
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:mem_cgroup_handle_over_high
  - mm/memcontrol.c:mem_cgroup_size
  - mm/memcontrol.c:mem_cgroup_print_oom_meminfo
  - mm/memcontrol.c:mem_cgroup_print_oom_meminfo
  - mm/memcontrol.c:mem_cgroup_print_oom_meminfo
  - mm/memcontrol.c:mem_cgroup_print_oom_meminfo
  - mm/memcontrol.c:__mem_cgroup_largest_soft_limit_node
```
```
In mm/hugetlb_cgroup.c (ffffffe000249e6c)
Location: include/linux/page_counter.h:45
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_reset
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline
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
In mm/memcontrol.c (ffffffff812b78d5)
Location: include/linux/page_counter.h:45
Inline: True
Inline callers:
  - mm/memcontrol.c:swap_current_read
  - mm/memcontrol.c:mem_cgroup_swap_full
  - mm/memcontrol.c:mem_cgroup_get_nr_swap_pages
  - mm/memcontrol.c:mem_cgroup_protected
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:memory_high_write
  - mm/memcontrol.c:memory_current_read
  - mm/memcontrol.c:mem_cgroup_wb_stats
  - mm/memcontrol.c:__mem_cgroup_usage_unregister_event
  - mm/memcontrol.c:__mem_cgroup_usage_unregister_event
  - mm/memcontrol.c:__mem_cgroup_usage_register_event
  - mm/memcontrol.c:__mem_cgroup_usage_register_event
  - mm/memcontrol.c:__mem_cgroup_threshold
  - mm/memcontrol.c:__mem_cgroup_threshold
  - mm/memcontrol.c:mem_cgroup_reset
  - mm/memcontrol.c:mem_cgroup_read_u64
  - mm/memcontrol.c:mem_cgroup_read_u64
  - mm/memcontrol.c:mem_cgroup_read_u64
  - mm/memcontrol.c:mem_cgroup_force_empty_write
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:mem_cgroup_handle_over_high
  - mm/memcontrol.c:mem_cgroup_size
  - mm/memcontrol.c:mem_cgroup_print_oom_meminfo
  - mm/memcontrol.c:mem_cgroup_print_oom_meminfo
  - mm/memcontrol.c:mem_cgroup_print_oom_meminfo
  - mm/memcontrol.c:mem_cgroup_print_oom_meminfo
  - mm/memcontrol.c:__mem_cgroup_largest_soft_limit_node
```
```
In mm/hugetlb_cgroup.c (ffffffff812c1f03)
Location: include/linux/page_counter.h:45
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_reset
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline
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
In mm/memcontrol.c (ffffffff812a8aa5)
Location: include/linux/page_counter.h:45
Inline: True
Inline callers:
  - mm/memcontrol.c:swap_current_read
  - mm/memcontrol.c:mem_cgroup_swap_full
  - mm/memcontrol.c:mem_cgroup_get_nr_swap_pages
  - mm/memcontrol.c:mem_cgroup_protected
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:memory_high_write
  - mm/memcontrol.c:memory_current_read
  - mm/memcontrol.c:mem_cgroup_wb_stats
  - mm/memcontrol.c:__mem_cgroup_usage_unregister_event
  - mm/memcontrol.c:__mem_cgroup_usage_unregister_event
  - mm/memcontrol.c:__mem_cgroup_usage_register_event
  - mm/memcontrol.c:__mem_cgroup_usage_register_event
  - mm/memcontrol.c:__mem_cgroup_threshold
  - mm/memcontrol.c:__mem_cgroup_threshold
  - mm/memcontrol.c:mem_cgroup_reset
  - mm/memcontrol.c:mem_cgroup_read_u64
  - mm/memcontrol.c:mem_cgroup_read_u64
  - mm/memcontrol.c:mem_cgroup_read_u64
  - mm/memcontrol.c:mem_cgroup_force_empty_write
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:mem_cgroup_handle_over_high
  - mm/memcontrol.c:mem_cgroup_size
  - mm/memcontrol.c:mem_cgroup_print_oom_meminfo
  - mm/memcontrol.c:mem_cgroup_print_oom_meminfo
  - mm/memcontrol.c:mem_cgroup_print_oom_meminfo
  - mm/memcontrol.c:mem_cgroup_print_oom_meminfo
  - mm/memcontrol.c:__mem_cgroup_largest_soft_limit_node
```
```
In mm/hugetlb_cgroup.c (ffffffff812b2f53)
Location: include/linux/page_counter.h:45
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_reset
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline
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
In mm/memcontrol.c (ffffffff812b56e5)
Location: include/linux/page_counter.h:45
Inline: True
Inline callers:
  - mm/memcontrol.c:swap_current_read
  - mm/memcontrol.c:mem_cgroup_swap_full
  - mm/memcontrol.c:mem_cgroup_get_nr_swap_pages
  - mm/memcontrol.c:mem_cgroup_protected
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:memory_high_write
  - mm/memcontrol.c:memory_current_read
  - mm/memcontrol.c:mem_cgroup_wb_stats
  - mm/memcontrol.c:__mem_cgroup_usage_unregister_event
  - mm/memcontrol.c:__mem_cgroup_usage_unregister_event
  - mm/memcontrol.c:__mem_cgroup_usage_register_event
  - mm/memcontrol.c:__mem_cgroup_usage_register_event
  - mm/memcontrol.c:__mem_cgroup_threshold
  - mm/memcontrol.c:__mem_cgroup_threshold
  - mm/memcontrol.c:mem_cgroup_reset
  - mm/memcontrol.c:mem_cgroup_read_u64
  - mm/memcontrol.c:mem_cgroup_read_u64
  - mm/memcontrol.c:mem_cgroup_read_u64
  - mm/memcontrol.c:mem_cgroup_force_empty_write
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:mem_cgroup_handle_over_high
  - mm/memcontrol.c:mem_cgroup_size
  - mm/memcontrol.c:mem_cgroup_print_oom_meminfo
  - mm/memcontrol.c:mem_cgroup_print_oom_meminfo
  - mm/memcontrol.c:mem_cgroup_print_oom_meminfo
  - mm/memcontrol.c:mem_cgroup_print_oom_meminfo
  - mm/memcontrol.c:__mem_cgroup_largest_soft_limit_node
```
```
In mm/hugetlb_cgroup.c (ffffffff812bfd13)
Location: include/linux/page_counter.h:45
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_reset
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline
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
In mm/memcontrol.c (ffffffff812c5c05)
Location: include/linux/page_counter.h:45
Inline: True
Inline callers:
  - mm/memcontrol.c:swap_current_read
  - mm/memcontrol.c:mem_cgroup_swap_full
  - mm/memcontrol.c:mem_cgroup_get_nr_swap_pages
  - mm/memcontrol.c:mem_cgroup_protected
  - mm/memcontrol.c:memory_max_write
  - mm/memcontrol.c:memory_high_write
  - mm/memcontrol.c:memory_current_read
  - mm/memcontrol.c:mem_cgroup_wb_stats
  - mm/memcontrol.c:__mem_cgroup_usage_unregister_event
  - mm/memcontrol.c:__mem_cgroup_usage_unregister_event
  - mm/memcontrol.c:__mem_cgroup_usage_register_event
  - mm/memcontrol.c:__mem_cgroup_usage_register_event
  - mm/memcontrol.c:__mem_cgroup_threshold
  - mm/memcontrol.c:__mem_cgroup_threshold
  - mm/memcontrol.c:mem_cgroup_reset
  - mm/memcontrol.c:mem_cgroup_read_u64
  - mm/memcontrol.c:mem_cgroup_read_u64
  - mm/memcontrol.c:mem_cgroup_read_u64
  - mm/memcontrol.c:mem_cgroup_force_empty_write
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:mem_cgroup_soft_limit_reclaim
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:mem_cgroup_handle_over_high
  - mm/memcontrol.c:mem_cgroup_size
  - mm/memcontrol.c:mem_cgroup_print_oom_meminfo
  - mm/memcontrol.c:mem_cgroup_print_oom_meminfo
  - mm/memcontrol.c:mem_cgroup_print_oom_meminfo
  - mm/memcontrol.c:mem_cgroup_print_oom_meminfo
  - mm/memcontrol.c:__mem_cgroup_largest_soft_limit_node
```
```
In mm/hugetlb_cgroup.c (ffffffff812d0753)
Location: include/linux/page_counter.h:45
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_reset
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_offline
```
</details>
</li>
</ul>

## Differences
