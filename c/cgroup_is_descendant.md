# Function: <code>cgroup_is_descendant</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
bool cgroup_is_descendant(struct cgroup *cgrp, struct cgroup *ancestor);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup.c (ffffffff811160b0)
Location: kernel/cgroup.c:490
Inline: True
Inline callers:
  - kernel/cgroup.c:__cgroup_procs_write
Direct callers:
  - arch/x86/events/intel/cqm.c:__conflict_event
  - arch/x86/events/intel/cqm.c:__conflict_event
  - kernel/events/core.c:perf_event_aux_ctx
  - kernel/events/core.c:__perf_event_enable
  - kernel/events/core.c:__perf_event_enable
  - kernel/events/core.c:perf_event_task_tick
  - mm/rmap.c:invalid_page_referenced_vma
  - mm/memcontrol.c:memcg_oom_wake_function
  - mm/memcontrol.c:memcg_oom_wake_function
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:task_in_mem_cgroup
```
**Symbols:**

```
ffffffff811160b0-ffffffff811160d7: cgroup_is_descendant (STB_GLOBAL)
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
In arch/x86/events/intel/cqm.c (ffffffff8100e468)
Location: include/linux/cgroup.h:492
Inline: True
Inline callers:
  - arch/x86/events/intel/cqm.c:__conflict_event
  - arch/x86/events/intel/cqm.c:__conflict_event
  - arch/x86/events/intel/cqm.c:__conflict_event
```
```
In kernel/cgroup.c (ffffffff8111e505)
Location: include/linux/cgroup.h:492
Inline: True
```
```
In kernel/events/core.c (ffffffff8118d35e)
Location: include/linux/cgroup.h:492
Inline: True
Inline callers:
  - kernel/events/core.c:perf_iterate_sb
  - kernel/events/core.c:perf_iterate_ctx
  - kernel/events/core.c:perf_event_task_tick
  - kernel/events/core.c:ctx_sched_in
  - kernel/events/core.c:ctx_sched_in
  - kernel/events/core.c:__perf_event_enable
  - kernel/events/core.c:__perf_event_enable
```
```
In mm/rmap.c (ffffffff811e698f)
Location: include/linux/cgroup.h:492
Inline: True
Inline callers:
  - mm/rmap.c:invalid_page_referenced_vma
```
```
In mm/memcontrol.c (ffffffff8121fbd0)
Location: include/linux/cgroup.h:492
Inline: True
Inline callers:
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:memcg_oom_wake_function
  - mm/memcontrol.c:memcg_oom_wake_function
  - mm/memcontrol.c:task_in_mem_cgroup
```
```
In block/cfq-iosched.c (ffffffff8142a23c)
Location: include/linux/cgroup.h:492
Inline: True
Inline callers:
  - block/cfq-iosched.c:cfq_insert_request
```
```
In net/core/filter.c (ffffffff8179b66a)
Location: include/linux/cgroup.h:492
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_under_cgroup
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
In arch/x86/events/intel/cqm.c (ffffffff8100e528)
Location: include/linux/cgroup.h:492
Inline: True
Inline callers:
  - arch/x86/events/intel/cqm.c:__conflict_event
  - arch/x86/events/intel/cqm.c:__conflict_event
  - arch/x86/events/intel/cqm.c:__conflict_event
```
```
In kernel/cgroup.c (ffffffff81126895)
Location: include/linux/cgroup.h:492
Inline: True
```
```
In kernel/trace/bpf_trace.c (ffffffff8117f68c)
Location: include/linux/cgroup.h:492
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:bpf_current_task_under_cgroup
```
```
In kernel/events/core.c (ffffffff8119c99e)
Location: include/linux/cgroup.h:492
Inline: True
Inline callers:
  - kernel/events/core.c:perf_iterate_sb
  - kernel/events/core.c:perf_iterate_ctx
  - kernel/events/core.c:perf_event_task_tick
  - kernel/events/core.c:ctx_sched_in
  - kernel/events/core.c:ctx_sched_in
  - kernel/events/core.c:__perf_event_enable
  - kernel/events/core.c:__perf_event_enable
```
```
In mm/rmap.c (ffffffff811f7d2f)
Location: include/linux/cgroup.h:492
Inline: True
Inline callers:
  - mm/rmap.c:invalid_page_referenced_vma
```
```
In mm/memcontrol.c (ffffffff8123224f)
Location: include/linux/cgroup.h:492
Inline: True
Inline callers:
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:memcg_oom_wake_function
  - mm/memcontrol.c:memcg_oom_wake_function
  - mm/memcontrol.c:task_in_mem_cgroup
```
```
In block/cfq-iosched.c (ffffffff8144406d)
Location: include/linux/cgroup.h:492
Inline: True
Inline callers:
  - block/cfq-iosched.c:cfq_insert_request
```
```
In net/core/filter.c (ffffffff817c966f)
Location: include/linux/cgroup.h:492
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_under_cgroup
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
In kernel/cgroup/cgroup.c (ffffffff8112753d)
Location: include/linux/cgroup.h:512
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:__cgroup_procs_write
  - kernel/cgroup/cgroup.c:__cgroup_procs_write
  - kernel/cgroup/cgroup.c:__cgroup_procs_write
```
```
In kernel/trace/bpf_trace.c (ffffffff81182389)
Location: include/linux/cgroup.h:512
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:bpf_current_task_under_cgroup
```
```
In kernel/events/core.c (ffffffff811a470d)
Location: include/linux/cgroup.h:512
Inline: True
Inline callers:
  - kernel/events/core.c:perf_iterate_sb
  - kernel/events/core.c:perf_iterate_ctx
  - kernel/events/core.c:perf_event_task_tick
  - kernel/events/core.c:ctx_sched_in
  - kernel/events/core.c:ctx_sched_in
  - kernel/events/core.c:__perf_event_enable
  - kernel/events/core.c:__perf_event_enable
```
```
In mm/rmap.c (ffffffff81202f13)
Location: include/linux/cgroup.h:512
Inline: True
Inline callers:
  - mm/rmap.c:invalid_page_referenced_vma
```
```
In mm/memcontrol.c (ffffffff8123d502)
Location: include/linux/cgroup.h:512
Inline: True
Inline callers:
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:memcg_oom_wake_function
  - mm/memcontrol.c:memcg_oom_wake_function
  - mm/memcontrol.c:task_in_mem_cgroup
```
```
In block/cfq-iosched.c (ffffffff814531c1)
Location: include/linux/cgroup.h:512
Inline: True
Inline callers:
  - block/cfq-iosched.c:cfq_insert_request
```
```
In net/core/filter.c (ffffffff817e85a9)
Location: include/linux/cgroup.h:512
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_under_cgroup
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
In kernel/cgroup/cgroup.c (ffffffff8112e570)
Location: include/linux/cgroup.h:548
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_procs_write_permission
  - kernel/cgroup/cgroup.c:cgroup_procs_write_permission
  - kernel/cgroup/cgroup.c:cgroup_procs_write_permission
```
```
In kernel/trace/bpf_trace.c (ffffffff8118fd4c)
Location: include/linux/cgroup.h:548
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:bpf_current_task_under_cgroup
```
```
In kernel/events/core.c (ffffffff811b86cd)
Location: include/linux/cgroup.h:548
Inline: True
Inline callers:
  - kernel/events/core.c:perf_iterate_sb
  - kernel/events/core.c:perf_iterate_ctx
  - kernel/events/core.c:perf_event_read
  - kernel/events/core.c:__perf_event_read
  - kernel/events/core.c:perf_event_task_tick
  - kernel/events/core.c:ctx_sched_in
  - kernel/events/core.c:ctx_sched_in
  - kernel/events/core.c:__perf_event_enable
  - kernel/events/core.c:list_add_event
```
```
In mm/rmap.c (ffffffff8121bc53)
Location: include/linux/cgroup.h:548
Inline: True
Inline callers:
  - mm/rmap.c:invalid_page_referenced_vma
```
```
In mm/memcontrol.c (ffffffff8125d0d9)
Location: include/linux/cgroup.h:548
Inline: True
Inline callers:
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:memcg_oom_wake_function
  - mm/memcontrol.c:memcg_oom_wake_function
  - mm/memcontrol.c:task_in_mem_cgroup
```
```
In block/cfq-iosched.c (ffffffff8147dd3d)
Location: include/linux/cgroup.h:548
Inline: True
Inline callers:
  - block/cfq-iosched.c:cfq_insert_request
```
```
In net/core/filter.c (ffffffff8186390c)
Location: include/linux/cgroup.h:548
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_under_cgroup
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
In kernel/cgroup/cgroup.c (ffffffff8113bc86)
Location: include/linux/cgroup.h:548
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_procs_write_permission
  - kernel/cgroup/cgroup.c:cgroup_procs_write_permission
  - kernel/cgroup/cgroup.c:cgroup_procs_write_permission
```
```
In kernel/trace/bpf_trace.c (ffffffff811a45a4)
Location: include/linux/cgroup.h:548
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:bpf_current_task_under_cgroup
```
```
In kernel/events/core.c (ffffffff811d8031)
Location: include/linux/cgroup.h:548
Inline: True
Inline callers:
  - kernel/events/core.c:perf_iterate_sb
  - kernel/events/core.c:perf_iterate_ctx
  - kernel/events/core.c:perf_event_read
  - kernel/events/core.c:__perf_event_read
  - kernel/events/core.c:perf_event_task_tick
  - kernel/events/core.c:__perf_event_enable
  - kernel/events/core.c:__perf_install_in_context
  - kernel/events/core.c:__perf_event_disable
  - kernel/events/core.c:list_add_event
```
```
In mm/rmap.c (ffffffff8123da9f)
Location: include/linux/cgroup.h:548
Inline: True
Inline callers:
  - mm/rmap.c:invalid_page_referenced_vma
```
```
In mm/memcontrol.c (ffffffff8128197a)
Location: include/linux/cgroup.h:548
Inline: True
Inline callers:
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:memcg_oom_wake_function
  - mm/memcontrol.c:memcg_oom_wake_function
  - mm/memcontrol.c:task_in_mem_cgroup
```
```
In block/cfq-iosched.c (ffffffff814b3c88)
Location: include/linux/cgroup.h:548
Inline: True
Inline callers:
  - block/cfq-iosched.c:cfq_insert_request
```
```
In net/core/filter.c (ffffffff818ae9ec)
Location: include/linux/cgroup.h:548
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_under_cgroup
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
In kernel/cgroup/cgroup.c (ffffffff81147486)
Location: include/linux/cgroup.h:550
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_procs_write_permission
  - kernel/cgroup/cgroup.c:cgroup_procs_write_permission
  - kernel/cgroup/cgroup.c:cgroup_procs_write_permission
```
```
In kernel/trace/bpf_trace.c (ffffffff811b26d4)
Location: include/linux/cgroup.h:550
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:bpf_current_task_under_cgroup
```
```
In kernel/events/core.c (ffffffff811e7d01)
Location: include/linux/cgroup.h:550
Inline: True
Inline callers:
  - kernel/events/core.c:perf_iterate_sb
  - kernel/events/core.c:perf_iterate_ctx
  - kernel/events/core.c:perf_event_read
  - kernel/events/core.c:__perf_event_read
  - kernel/events/core.c:perf_event_task_tick
  - kernel/events/core.c:__perf_event_enable
  - kernel/events/core.c:__perf_install_in_context
  - kernel/events/core.c:__perf_event_disable
  - kernel/events/core.c:list_add_event
```
```
In mm/rmap.c (ffffffff8125206e)
Location: include/linux/cgroup.h:550
Inline: True
Inline callers:
  - mm/rmap.c:invalid_page_referenced_vma
```
```
In mm/memcontrol.c (ffffffff8129895c)
Location: include/linux/cgroup.h:550
Inline: True
Inline callers:
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:memcg_oom_wake_function
  - mm/memcontrol.c:memcg_oom_wake_function
  - mm/memcontrol.c:task_in_mem_cgroup
```
```
In net/core/filter.c (ffffffff818d2c7c)
Location: include/linux/cgroup.h:550
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_under_cgroup
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
In kernel/cgroup/cgroup.c (ffffffff811526f9)
Location: include/linux/cgroup.h:563
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_procs_write_permission
  - kernel/cgroup/cgroup.c:cgroup_procs_write_permission
  - kernel/cgroup/cgroup.c:cgroup_procs_write_permission
```
```
In kernel/trace/bpf_trace.c (ffffffff811c1115)
Location: include/linux/cgroup.h:563
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:bpf_current_task_under_cgroup
```
```
In kernel/events/core.c (ffffffff811ff350)
Location: include/linux/cgroup.h:563
Inline: True
Inline callers:
  - kernel/events/core.c:perf_iterate_sb
  - kernel/events/core.c:perf_iterate_ctx
  - kernel/events/core.c:perf_event_read
  - kernel/events/core.c:__perf_event_read
  - kernel/events/core.c:perf_event_task_tick
  - kernel/events/core.c:__perf_event_enable
  - kernel/events/core.c:__perf_install_in_context
  - kernel/events/core.c:__perf_event_disable
  - kernel/events/core.c:list_add_event
```
```
In mm/rmap.c (ffffffff812643ab)
Location: include/linux/cgroup.h:563
Inline: True
Inline callers:
  - mm/rmap.c:invalid_page_referenced_vma
```
```
In mm/memcontrol.c (ffffffff812b3e3a)
Location: include/linux/cgroup.h:563
Inline: True
Inline callers:
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:memcg_oom_wake_function
  - mm/memcontrol.c:memcg_oom_wake_function
```
```
In net/core/filter.c (ffffffff81922fdd)
Location: include/linux/cgroup.h:563
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_under_cgroup
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
In kernel/cgroup/cgroup.c (ffffffff8115e349)
Location: include/linux/cgroup.h:565
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_procs_write_permission
  - kernel/cgroup/cgroup.c:cgroup_procs_write_permission
  - kernel/cgroup/cgroup.c:cgroup_procs_write_permission
```
```
In kernel/trace/bpf_trace.c (ffffffff811cc8c5)
Location: include/linux/cgroup.h:565
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:bpf_current_task_under_cgroup
```
```
In kernel/events/core.c (ffffffff8120c3c0)
Location: include/linux/cgroup.h:565
Inline: True
Inline callers:
  - kernel/events/core.c:perf_iterate_sb
  - kernel/events/core.c:perf_iterate_ctx
  - kernel/events/core.c:perf_event_read
  - kernel/events/core.c:__perf_event_read
  - kernel/events/core.c:perf_event_task_tick
  - kernel/events/core.c:__perf_event_enable
  - kernel/events/core.c:__perf_install_in_context
  - kernel/events/core.c:__perf_event_disable
  - kernel/events/core.c:list_add_event
```
```
In mm/rmap.c (ffffffff81272c1b)
Location: include/linux/cgroup.h:565
Inline: True
Inline callers:
  - mm/rmap.c:invalid_page_referenced_vma
```
```
In mm/memcontrol.c (ffffffff812c575b)
Location: include/linux/cgroup.h:565
Inline: True
Inline callers:
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:memcg_oom_wake_function
  - mm/memcontrol.c:memcg_oom_wake_function
```
```
In net/core/filter.c (ffffffff8195520d)
Location: include/linux/cgroup.h:565
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_under_cgroup
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
In kernel/cgroup/cgroup.c (ffffffff8116f4b8)
Location: include/linux/cgroup.h:571
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_procs_write_permission
  - kernel/cgroup/cgroup.c:cgroup_procs_write_permission
  - kernel/cgroup/cgroup.c:cgroup_procs_write_permission
```
```
In kernel/trace/bpf_trace.c (ffffffff811e82a2)
Location: include/linux/cgroup.h:571
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:bpf_current_task_under_cgroup
```
```
In kernel/events/core.c (ffffffff812330e7)
Location: include/linux/cgroup.h:571
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_pmu_output_stop
  - kernel/events/core.c:perf_iterate_sb
  - kernel/events/core.c:perf_event_read
  - kernel/events/core.c:__perf_event_read
  - kernel/events/core.c:perf_adjust_freq_unthr_context
  - kernel/events/core.c:merge_sched_in
  - kernel/events/core.c:__perf_event_enable
  - kernel/events/core.c:__perf_event_enable
  - kernel/events/core.c:__perf_install_in_context
  - kernel/events/core.c:__perf_event_disable
  - kernel/events/core.c:list_add_event
```
```
In mm/rmap.c (ffffffff812a39fb)
Location: include/linux/cgroup.h:571
Inline: True
Inline callers:
  - mm/rmap.c:invalid_page_referenced_vma
```
```
In mm/memcontrol.c (ffffffff812fc461)
Location: include/linux/cgroup.h:571
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_get_oom_group
  - mm/memcontrol.c:memcg_oom_wake_function
  - mm/memcontrol.c:memcg_oom_wake_function
  - mm/memcontrol.c:mem_cgroup_wait_acct_move
  - mm/memcontrol.c:mem_cgroup_wait_acct_move
```
```
In net/core/filter.c (ffffffff81a2779a)
Location: include/linux/cgroup.h:571
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_under_cgroup
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
In kernel/cgroup/cgroup.c (ffffffff8116bfc8)
Location: include/linux/cgroup.h:571
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_procs_write_permission
  - kernel/cgroup/cgroup.c:cgroup_procs_write_permission
  - kernel/cgroup/cgroup.c:cgroup_procs_write_permission
```
```
In kernel/trace/bpf_trace.c (ffffffff811e5de2)
Location: include/linux/cgroup.h:571
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:bpf_current_task_under_cgroup
```
```
In kernel/events/core.c (ffffffff8123ceb7)
Location: include/linux/cgroup.h:571
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_pmu_output_stop
  - kernel/events/core.c:perf_iterate_sb
  - kernel/events/core.c:perf_event_read
  - kernel/events/core.c:__perf_event_read
  - kernel/events/core.c:perf_adjust_freq_unthr_context
  - kernel/events/core.c:merge_sched_in
  - kernel/events/core.c:__perf_event_enable
  - kernel/events/core.c:__perf_event_enable
  - kernel/events/core.c:__perf_install_in_context
  - kernel/events/core.c:__perf_event_disable
  - kernel/events/core.c:list_add_event
```
```
In mm/rmap.c (ffffffff812af2c0)
Location: include/linux/cgroup.h:571
Inline: True
Inline callers:
  - mm/rmap.c:invalid_page_referenced_vma
```
```
In mm/memcontrol.c (ffffffff8130866b)
Location: include/linux/cgroup.h:571
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_get_oom_group
  - mm/memcontrol.c:memcg_oom_wake_function
  - mm/memcontrol.c:memcg_oom_wake_function
  - mm/memcontrol.c:mem_cgroup_wait_acct_move
  - mm/memcontrol.c:mem_cgroup_wait_acct_move
```
```
In net/core/filter.c (ffffffff81a27faa)
Location: include/linux/cgroup.h:571
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_under_cgroup
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
In kernel/cgroup/cgroup.c (ffffffff8116cf33)
Location: include/linux/cgroup.h:571
Inline: True
```
```
In kernel/trace/bpf_trace.c (ffffffff811e74b5)
Location: include/linux/cgroup.h:571
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:bpf_current_task_under_cgroup
```
```
In kernel/events/core.c (ffffffff81241937)
Location: include/linux/cgroup.h:571
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_pmu_output_stop
  - kernel/events/core.c:perf_iterate_sb
  - kernel/events/core.c:perf_event_read
  - kernel/events/core.c:__perf_event_read
  - kernel/events/core.c:perf_adjust_freq_unthr_context
  - kernel/events/core.c:merge_sched_in
  - kernel/events/core.c:__perf_event_enable
  - kernel/events/core.c:__perf_event_enable
  - kernel/events/core.c:__perf_install_in_context
  - kernel/events/core.c:__perf_event_disable
  - kernel/events/core.c:list_add_event
```
```
In mm/rmap.c (ffffffff812b47a0)
Location: include/linux/cgroup.h:571
Inline: True
Inline callers:
  - mm/rmap.c:invalid_page_referenced_vma
```
```
In mm/memcontrol.c (ffffffff8130d856)
Location: include/linux/cgroup.h:571
Inline: True
Inline callers:
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:mem_cgroup_get_oom_group
  - mm/memcontrol.c:memcg_oom_wake_function
  - mm/memcontrol.c:memcg_oom_wake_function
```
```
In net/core/filter.c (ffffffff81a0f31f)
Location: include/linux/cgroup.h:571
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_under_cgroup
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
In kernel/cgroup/cgroup.c (ffffffff81192c0f)
Location: include/linux/cgroup.h:571
Inline: True
```
```
In kernel/trace/bpf_trace.c (ffffffff81218135)
Location: include/linux/cgroup.h:571
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:bpf_current_task_under_cgroup
```
```
In kernel/events/core.c (ffffffff8127c327)
Location: include/linux/cgroup.h:571
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_pmu_output_stop
  - kernel/events/core.c:perf_iterate_sb
  - kernel/events/core.c:perf_event_read
  - kernel/events/core.c:__perf_event_read
  - kernel/events/core.c:perf_adjust_freq_unthr_context
  - kernel/events/core.c:merge_sched_in
  - kernel/events/core.c:__perf_event_enable
  - kernel/events/core.c:__perf_event_enable
  - kernel/events/core.c:__perf_install_in_context
  - kernel/events/core.c:__perf_event_disable
  - kernel/events/core.c:list_add_event
```
```
In mm/rmap.c (ffffffff812f6380)
Location: include/linux/cgroup.h:571
Inline: True
Inline callers:
  - mm/rmap.c:invalid_page_referenced_vma
```
```
In mm/memcontrol.c (ffffffff813585bf)
Location: include/linux/cgroup.h:571
Inline: True
Inline callers:
  - mm/memcontrol.c:try_charge_memcg
  - mm/memcontrol.c:try_charge_memcg
  - mm/memcontrol.c:mem_cgroup_get_oom_group
  - mm/memcontrol.c:memcg_oom_wake_function
  - mm/memcontrol.c:memcg_oom_wake_function
```
```
In net/core/filter.c (ffffffff81acbf76)
Location: include/linux/cgroup.h:571
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_under_cgroup
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
In kernel/cgroup/cgroup.c (ffffffff811c3489)
Location: include/linux/cgroup.h:572
Inline: True
```
```
In kernel/trace/bpf_trace.c (ffffffff812561ba)
Location: include/linux/cgroup.h:572
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:bpf_current_task_under_cgroup
```
```
In kernel/events/core.c (ffffffff812d23ee)
Location: include/linux/cgroup.h:572
Inline: True
Inline callers:
  - kernel/events/core.c:__perf_pmu_output_stop
  - kernel/events/core.c:__perf_pmu_output_stop
  - kernel/events/core.c:perf_iterate_sb
  - kernel/events/core.c:perf_adjust_freq_unthr_context
  - kernel/events/core.c:merge_sched_in
  - kernel/events/core.c:__perf_event_enable
  - kernel/events/core.c:__perf_install_in_context
```
```
In mm/rmap.c (ffffffff8135b016)
Location: include/linux/cgroup.h:572
Inline: True
Inline callers:
  - mm/rmap.c:invalid_folio_referenced_vma
```
```
In mm/memcontrol.c (ffffffff813d2563)
Location: include/linux/cgroup.h:572
Inline: True
Inline callers:
  - mm/memcontrol.c:try_charge_memcg
  - mm/memcontrol.c:try_charge_memcg
  - mm/memcontrol.c:mem_cgroup_get_oom_group
  - mm/memcontrol.c:memcg_oom_wake_function
  - mm/memcontrol.c:memcg_oom_wake_function
```
```
In net/core/filter.c (ffffffff81c4899e)
Location: include/linux/cgroup.h:572
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_under_cgroup
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
In kernel/cgroup/cgroup.c (ffffffff812081ae)
Location: include/linux/cgroup.h:514
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_get_from_id
```
```
In kernel/trace/bpf_trace.c (ffffffff812a5812)
Location: include/linux/cgroup.h:514
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:bpf_current_task_under_cgroup
```
```
In kernel/events/core.c (ffffffff81338593)
Location: include/linux/cgroup.h:514
Inline: True
Inline callers:
  - kernel/events/core.c:perf_iterate_sb
  - kernel/events/core.c:perf_iterate_ctx
  - kernel/events/core.c:perf_adjust_freq_unthr_context
  - kernel/events/core.c:merge_sched_in
  - kernel/events/core.c:__perf_event_enable
  - kernel/events/core.c:__perf_install_in_context
```
```
In mm/rmap.c (ffffffff813d5c36)
Location: include/linux/cgroup.h:514
Inline: True
Inline callers:
  - mm/rmap.c:invalid_folio_referenced_vma
```
```
In mm/memcontrol.c (ffffffff81457c2b)
Location: include/linux/cgroup.h:514
Inline: True
Inline callers:
  - mm/memcontrol.c:try_charge_memcg
  - mm/memcontrol.c:try_charge_memcg
  - mm/memcontrol.c:mem_cgroup_get_oom_group
  - mm/memcontrol.c:memcg_oom_wake_function
  - mm/memcontrol.c:memcg_oom_wake_function
```
```
In net/core/filter.c (ffffffff81dfd71e)
Location: include/linux/cgroup.h:514
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_under_cgroup
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
In kernel/cgroup/cgroup.c (ffffffff8121d948)
Location: include/linux/cgroup.h:513
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_get_from_id
```
```
In kernel/trace/bpf_trace.c (ffffffff812c7cc2)
Location: include/linux/cgroup.h:513
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:bpf_current_task_under_cgroup
```
```
In kernel/bpf/helpers.c (ffffffff813215ed)
Location: include/linux/cgroup.h:513
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:bpf_task_under_cgroup
```
```
In kernel/events/core.c (ffffffff81368c64)
Location: include/linux/cgroup.h:513
Inline: True
Inline callers:
  - kernel/events/core.c:perf_iterate_ctx
  - kernel/events/core.c:perf_adjust_freq_unthr_context
  - kernel/events/core.c:merge_sched_in
  - kernel/events/core.c:__perf_event_enable
  - kernel/events/core.c:__perf_install_in_context
```
```
In mm/rmap.c (ffffffff8140ab1b)
Location: include/linux/cgroup.h:513
Inline: True
Inline callers:
  - mm/rmap.c:invalid_folio_referenced_vma
```
```
In mm/memcontrol.c (ffffffff8148d95a)
Location: include/linux/cgroup.h:513
Inline: True
Inline callers:
  - mm/memcontrol.c:try_charge_memcg
  - mm/memcontrol.c:try_charge_memcg
  - mm/memcontrol.c:mem_cgroup_get_oom_group
  - mm/memcontrol.c:memcg_oom_wake_function
  - mm/memcontrol.c:memcg_oom_wake_function
```
```
In net/core/filter.c (ffffffff81e6dffa)
Location: include/linux/cgroup.h:513
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_under_cgroup
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
In kernel/cgroup/cgroup.c (ffffffff81235577)
Location: include/linux/cgroup.h:511
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_get_from_id
```
```
In kernel/trace/bpf_trace.c (ffffffff812e4672)
Location: include/linux/cgroup.h:511
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:bpf_current_task_under_cgroup
```
```
In kernel/bpf/helpers.c (ffffffff81343d30)
Location: include/linux/cgroup.h:511
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:bpf_task_under_cgroup
```
```
In kernel/events/core.c (ffffffff81391a94)
Location: include/linux/cgroup.h:511
Inline: True
Inline callers:
  - kernel/events/core.c:perf_iterate_ctx
  - kernel/events/core.c:perf_adjust_freq_unthr_context
  - kernel/events/core.c:merge_sched_in
  - kernel/events/core.c:__perf_event_enable
  - kernel/events/core.c:__perf_install_in_context
```
```
In mm/rmap.c (ffffffff8143737b)
Location: include/linux/cgroup.h:511
Inline: True
Inline callers:
  - mm/rmap.c:invalid_folio_referenced_vma
```
```
In mm/memcontrol.c (ffffffff814bd2da)
Location: include/linux/cgroup.h:511
Inline: True
Inline callers:
  - mm/memcontrol.c:try_charge_memcg
  - mm/memcontrol.c:try_charge_memcg
  - mm/memcontrol.c:mem_cgroup_get_oom_group
  - mm/memcontrol.c:memcg_oom_wake_function
  - mm/memcontrol.c:memcg_oom_wake_function
```
```
In net/core/filter.c (ffffffff81f2d4ea)
Location: include/linux/cgroup.h:511
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_under_cgroup
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
In kernel/cgroup/cgroup.c (ffff8000101ceb34)
Location: include/linux/cgroup.h:565
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_procs_write_permission
  - kernel/cgroup/cgroup.c:cgroup_procs_write_permission
  - kernel/cgroup/cgroup.c:cgroup_procs_write_permission
```
```
In kernel/trace/bpf_trace.c (ffff80001024c5a0)
Location: include/linux/cgroup.h:565
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:bpf_current_task_under_cgroup
```
```
In kernel/events/core.c (ffff800010297cf4)
Location: include/linux/cgroup.h:565
Inline: True
Inline callers:
  - kernel/events/core.c:perf_iterate_sb
  - kernel/events/core.c:perf_event_read
  - kernel/events/core.c:__perf_event_read
  - kernel/events/core.c:perf_event_task_tick
  - kernel/events/core.c:__perf_install_in_context
  - kernel/events/core.c:__perf_event_disable
  - kernel/events/core.c:list_add_event
```
```
In mm/rmap.c (ffff800010308754)
Location: include/linux/cgroup.h:565
Inline: True
Inline callers:
  - mm/rmap.c:invalid_page_referenced_vma
```
```
In mm/memcontrol.c (ffff800010368570)
Location: include/linux/cgroup.h:565
Inline: True
Inline callers:
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:memcg_oom_wake_function
  - mm/memcontrol.c:memcg_oom_wake_function
```
```
In net/core/filter.c (ffff800010bf6d2c)
Location: include/linux/cgroup.h:565
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_under_cgroup
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
In kernel/cgroup/cgroup.c (c041201c)
Location: include/linux/cgroup.h:565
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_procs_write_permission
  - kernel/cgroup/cgroup.c:cgroup_procs_write_permission
  - kernel/cgroup/cgroup.c:cgroup_procs_write_permission
```
```
In kernel/trace/bpf_trace.c (c047ebf0)
Location: include/linux/cgroup.h:565
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:bpf_current_task_under_cgroup
```
```
In kernel/events/core.c (c04c57b4)
Location: include/linux/cgroup.h:565
Inline: True
Inline callers:
  - kernel/events/core.c:perf_iterate_sb
  - kernel/events/core.c:perf_event_read
  - kernel/events/core.c:__perf_event_read
  - kernel/events/core.c:perf_event_task_tick
  - kernel/events/core.c:__perf_event_enable
  - kernel/events/core.c:__perf_install_in_context
  - kernel/events/core.c:__perf_event_disable
  - kernel/events/core.c:list_add_event
```
```
In mm/rmap.c (c05256fc)
Location: include/linux/cgroup.h:565
Inline: True
Inline callers:
  - mm/rmap.c:invalid_page_referenced_vma
```
```
In mm/memcontrol.c (c0559a38)
Location: include/linux/cgroup.h:565
Inline: True
Inline callers:
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:memcg_oom_wake_function
  - mm/memcontrol.c:memcg_oom_wake_function
```
```
In net/core/filter.c (c0d0ffc0)
Location: include/linux/cgroup.h:565
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_under_cgroup
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
In kernel/cgroup/cgroup.c (c000000000238b94)
Location: include/linux/cgroup.h:565
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_procs_write_permission
  - kernel/cgroup/cgroup.c:cgroup_procs_write_permission
  - kernel/cgroup/cgroup.c:cgroup_procs_write_permission
```
```
In kernel/trace/bpf_trace.c (c0000000002e7a54)
Location: include/linux/cgroup.h:565
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:bpf_current_task_under_cgroup
```
```
In kernel/events/core.c (c000000000344514)
Location: include/linux/cgroup.h:565
Inline: True
Inline callers:
  - kernel/events/core.c:perf_iterate_sb
  - kernel/events/core.c:perf_event_read
  - kernel/events/core.c:__perf_event_read
  - kernel/events/core.c:perf_event_task_tick
  - kernel/events/core.c:__perf_event_enable
  - kernel/events/core.c:__perf_install_in_context
  - kernel/events/core.c:__perf_event_disable
  - kernel/events/core.c:list_add_event
```
```
In mm/rmap.c (c0000000003d7728)
Location: include/linux/cgroup.h:565
Inline: True
Inline callers:
  - mm/rmap.c:invalid_page_referenced_vma
```
```
In mm/memcontrol.c (c0000000004562ac)
Location: include/linux/cgroup.h:565
Inline: True
Inline callers:
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:memcg_oom_wake_function
  - mm/memcontrol.c:memcg_oom_wake_function
```
```
In net/core/filter.c (c000000000cdc864)
Location: include/linux/cgroup.h:565
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_under_cgroup
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
In kernel/cgroup/cgroup.c (ffffffe0001493c2)
Location: include/linux/cgroup.h:565
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_procs_write_permission
  - kernel/cgroup/cgroup.c:cgroup_procs_write_permission
  - kernel/cgroup/cgroup.c:cgroup_procs_write_permission
```
```
In kernel/events/core.c (ffffffe0001c6fb2)
Location: include/linux/cgroup.h:565
Inline: True
Inline callers:
  - kernel/events/core.c:perf_iterate_sb
  - kernel/events/core.c:perf_event_read
  - kernel/events/core.c:__perf_event_read
  - kernel/events/core.c:perf_event_task_tick
  - kernel/events/core.c:__perf_event_enable
  - kernel/events/core.c:__perf_install_in_context
  - kernel/events/core.c:__perf_event_disable
  - kernel/events/core.c:list_add_event
```
```
In mm/rmap.c (ffffffe000212f8e)
Location: include/linux/cgroup.h:565
Inline: True
Inline callers:
  - mm/rmap.c:invalid_page_referenced_vma
```
```
In mm/memcontrol.c (ffffffe000246278)
Location: include/linux/cgroup.h:565
Inline: True
Inline callers:
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:memcg_oom_wake_function
  - mm/memcontrol.c:memcg_oom_wake_function
```
```
In net/core/filter.c (ffffffe000778440)
Location: include/linux/cgroup.h:565
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_under_cgroup
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
In kernel/cgroup/cgroup.c (ffffffff81156969)
Location: include/linux/cgroup.h:565
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_procs_write_permission
  - kernel/cgroup/cgroup.c:cgroup_procs_write_permission
  - kernel/cgroup/cgroup.c:cgroup_procs_write_permission
```
```
In kernel/trace/bpf_trace.c (ffffffff811c4ee5)
Location: include/linux/cgroup.h:565
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:bpf_current_task_under_cgroup
```
```
In kernel/events/core.c (ffffffff812049e0)
Location: include/linux/cgroup.h:565
Inline: True
Inline callers:
  - kernel/events/core.c:perf_iterate_sb
  - kernel/events/core.c:perf_iterate_ctx
  - kernel/events/core.c:perf_event_read
  - kernel/events/core.c:__perf_event_read
  - kernel/events/core.c:perf_event_task_tick
  - kernel/events/core.c:__perf_event_enable
  - kernel/events/core.c:__perf_install_in_context
  - kernel/events/core.c:__perf_event_disable
  - kernel/events/core.c:list_add_event
```
```
In mm/rmap.c (ffffffff8126b26b)
Location: include/linux/cgroup.h:565
Inline: True
Inline callers:
  - mm/rmap.c:invalid_page_referenced_vma
```
```
In mm/memcontrol.c (ffffffff812bdd3b)
Location: include/linux/cgroup.h:565
Inline: True
Inline callers:
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:memcg_oom_wake_function
  - mm/memcontrol.c:memcg_oom_wake_function
```
```
In net/core/filter.c (ffffffff818f51dd)
Location: include/linux/cgroup.h:565
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_under_cgroup
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
In kernel/cgroup/cgroup.c (ffffffff81149c89)
Location: include/linux/cgroup.h:565
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_procs_write_permission
  - kernel/cgroup/cgroup.c:cgroup_procs_write_permission
  - kernel/cgroup/cgroup.c:cgroup_procs_write_permission
```
```
In kernel/trace/bpf_trace.c (ffffffff811b7cc5)
Location: include/linux/cgroup.h:565
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:bpf_current_task_under_cgroup
```
```
In kernel/events/core.c (ffffffff811f7770)
Location: include/linux/cgroup.h:565
Inline: True
Inline callers:
  - kernel/events/core.c:perf_iterate_sb
  - kernel/events/core.c:perf_iterate_ctx
  - kernel/events/core.c:perf_event_read
  - kernel/events/core.c:__perf_event_read
  - kernel/events/core.c:perf_event_task_tick
  - kernel/events/core.c:__perf_event_enable
  - kernel/events/core.c:__perf_install_in_context
  - kernel/events/core.c:__perf_event_disable
  - kernel/events/core.c:list_add_event
```
```
In mm/rmap.c (ffffffff8125d34b)
Location: include/linux/cgroup.h:565
Inline: True
Inline callers:
  - mm/rmap.c:invalid_page_referenced_vma
```
```
In mm/memcontrol.c (ffffffff812aee73)
Location: include/linux/cgroup.h:565
Inline: True
Inline callers:
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:memcg_oom_wake_function
  - mm/memcontrol.c:memcg_oom_wake_function
```
```
In net/core/filter.c (ffffffff818af00d)
Location: include/linux/cgroup.h:565
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_under_cgroup
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
In kernel/cgroup/cgroup.c (ffffffff81154739)
Location: include/linux/cgroup.h:565
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_procs_write_permission
  - kernel/cgroup/cgroup.c:cgroup_procs_write_permission
  - kernel/cgroup/cgroup.c:cgroup_procs_write_permission
```
```
In kernel/trace/bpf_trace.c (ffffffff811c2cb5)
Location: include/linux/cgroup.h:565
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:bpf_current_task_under_cgroup
```
```
In kernel/events/core.c (ffffffff812027b0)
Location: include/linux/cgroup.h:565
Inline: True
Inline callers:
  - kernel/events/core.c:perf_iterate_sb
  - kernel/events/core.c:perf_iterate_ctx
  - kernel/events/core.c:perf_event_read
  - kernel/events/core.c:__perf_event_read
  - kernel/events/core.c:perf_event_task_tick
  - kernel/events/core.c:__perf_event_enable
  - kernel/events/core.c:__perf_install_in_context
  - kernel/events/core.c:__perf_event_disable
  - kernel/events/core.c:list_add_event
```
```
In mm/rmap.c (ffffffff8126900b)
Location: include/linux/cgroup.h:565
Inline: True
Inline callers:
  - mm/rmap.c:invalid_page_referenced_vma
```
```
In mm/memcontrol.c (ffffffff812bbb4b)
Location: include/linux/cgroup.h:565
Inline: True
Inline callers:
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:memcg_oom_wake_function
  - mm/memcontrol.c:memcg_oom_wake_function
```
```
In net/core/filter.c (ffffffff8194620d)
Location: include/linux/cgroup.h:565
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_under_cgroup
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
In kernel/cgroup/cgroup.c (ffffffff81161639)
Location: include/linux/cgroup.h:565
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_procs_write_permission
  - kernel/cgroup/cgroup.c:cgroup_procs_write_permission
  - kernel/cgroup/cgroup.c:cgroup_procs_write_permission
```
```
In kernel/trace/bpf_trace.c (ffffffff811d0d55)
Location: include/linux/cgroup.h:565
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:bpf_current_task_under_cgroup
```
```
In kernel/events/core.c (ffffffff8121237b)
Location: include/linux/cgroup.h:565
Inline: True
Inline callers:
  - kernel/events/core.c:perf_iterate_sb
  - kernel/events/core.c:perf_iterate_ctx
  - kernel/events/core.c:perf_event_read
  - kernel/events/core.c:__perf_event_read
  - kernel/events/core.c:perf_event_task_tick
  - kernel/events/core.c:__perf_event_enable
  - kernel/events/core.c:__perf_install_in_context
  - kernel/events/core.c:__perf_event_disable
  - kernel/events/core.c:list_add_event
```
```
In mm/rmap.c (ffffffff8127899f)
Location: include/linux/cgroup.h:565
Inline: True
Inline callers:
  - mm/rmap.c:invalid_page_referenced_vma
```
```
In mm/memcontrol.c (ffffffff812cc2d3)
Location: include/linux/cgroup.h:565
Inline: True
Inline callers:
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:memcg_oom_wake_function
  - mm/memcontrol.c:memcg_oom_wake_function
```
```
In net/core/filter.c (ffffffff81967afd)
Location: include/linux/cgroup.h:565
Inline: True
Inline callers:
  - net/core/filter.c:bpf_skb_under_cgroup
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
