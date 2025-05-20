# Function: <code>cgroup_id</code>

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
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff811748da)
Location: include/linux/cgroup.h:310
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_create
  - kernel/cgroup/cgroup.c:cgroup_procs_write_permission
  - kernel/cgroup/cgroup.c:cgroup_procs_write_permission
  - kernel/cgroup/cgroup.c:perf_trace_cgroup_event
  - kernel/cgroup/cgroup.c:perf_trace_cgroup_migrate
  - kernel/cgroup/cgroup.c:perf_trace_cgroup
  - kernel/cgroup/cgroup.c:trace_event_raw_event_cgroup_event
  - kernel/cgroup/cgroup.c:trace_event_raw_event_cgroup_migrate
  - kernel/cgroup/cgroup.c:trace_event_raw_event_cgroup
```
```
In kernel/trace/blktrace.c (ffffffff811d23ad)
Location: include/linux/cgroup.h:310
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:blk_add_driver_data
  - kernel/trace/blktrace.c:blk_add_trace_rq_remap
  - kernel/trace/blktrace.c:blk_add_trace_bio_remap
  - kernel/trace/blktrace.c:blk_add_trace_split
  - kernel/trace/blktrace.c:blk_add_trace_bio_queue
  - kernel/trace/blktrace.c:blk_add_trace_bio_frontmerge
  - kernel/trace/blktrace.c:blk_add_trace_bio_backmerge
  - kernel/trace/blktrace.c:blk_add_trace_bio_complete
  - kernel/trace/blktrace.c:blk_add_trace_bio_bounce
  - kernel/trace/blktrace.c:blk_add_trace_rq_complete
  - kernel/trace/blktrace.c:blk_add_trace_rq_requeue
  - kernel/trace/blktrace.c:blk_add_trace_rq_issue
  - kernel/trace/blktrace.c:blk_add_trace_rq_insert
  - kernel/trace/blktrace.c:__trace_note_message
```
```
In kernel/trace/bpf_trace.c (ffffffff811e82be)
Location: include/linux/cgroup.h:310
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:bpf_current_task_under_cgroup
```
```
In kernel/bpf/helpers.c (ffffffff812148b4)
Location: include/linux/cgroup.h:310
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:bpf_get_current_ancestor_cgroup_id
  - kernel/bpf/helpers.c:bpf_get_current_cgroup_id
```
```
In kernel/bpf/local_storage.c (ffffffff8121d841)
Location: include/linux/cgroup.h:310
Inline: True
Inline callers:
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_link
```
```
In kernel/bpf/cgroup.c (ffffffff8122c02d)
Location: include/linux/cgroup.h:310
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:bpf_cgroup_link_fill_link_info
  - kernel/bpf/cgroup.c:bpf_cgroup_link_show_fdinfo
```
```
In kernel/events/core.c (ffffffff81233969)
Location: include/linux/cgroup.h:310
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_cgroup
  - kernel/events/core.c:__perf_pmu_output_stop
  - kernel/events/core.c:perf_iterate_sb
  - kernel/events/core.c:perf_prepare_sample
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
In mm/rmap.c (ffffffff812a3a3a)
Location: include/linux/cgroup.h:310
Inline: True
Inline callers:
  - mm/rmap.c:invalid_page_referenced_vma
```
```
In mm/memcontrol.c (ffffffff812fc489)
Location: include/linux/cgroup.h:310
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_get_oom_group
  - mm/memcontrol.c:memcg_oom_wake_function
  - mm/memcontrol.c:memcg_oom_wake_function
  - mm/memcontrol.c:mem_cgroup_wait_acct_move
  - mm/memcontrol.c:mem_cgroup_wait_acct_move
```
```
In net/core/filter.c (ffffffff81a2c18a)
Location: include/linux/cgroup.h:310
Inline: True
Inline callers:
  - net/core/filter.c:bpf_sk_ancestor_cgroup_id
  - net/core/filter.c:bpf_sk_cgroup_id
  - net/core/filter.c:bpf_skb_ancestor_cgroup_id
  - net/core/filter.c:bpf_skb_cgroup_id
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
In kernel/cgroup/cgroup.c (ffffffff811715c8)
Location: include/linux/cgroup.h:310
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_create
  - kernel/cgroup/cgroup.c:cgroup_procs_write_permission
  - kernel/cgroup/cgroup.c:cgroup_procs_write_permission
  - kernel/cgroup/cgroup.c:perf_trace_cgroup_event
  - kernel/cgroup/cgroup.c:perf_trace_cgroup_migrate
  - kernel/cgroup/cgroup.c:perf_trace_cgroup
  - kernel/cgroup/cgroup.c:trace_event_raw_event_cgroup_event
  - kernel/cgroup/cgroup.c:trace_event_raw_event_cgroup_migrate
  - kernel/cgroup/cgroup.c:trace_event_raw_event_cgroup
```
```
In kernel/trace/blktrace.c (ffffffff811cefe9)
Location: include/linux/cgroup.h:310
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:blk_add_trace_bio_remap
  - kernel/trace/blktrace.c:blk_add_trace_split
  - kernel/trace/blktrace.c:blk_add_trace_bio
  - kernel/trace/blktrace.c:blk_add_trace_rq_complete
  - kernel/trace/blktrace.c:blk_add_trace_rq_requeue
  - kernel/trace/blktrace.c:blk_add_trace_rq_merge
  - kernel/trace/blktrace.c:blk_add_trace_rq_issue
  - kernel/trace/blktrace.c:blk_add_trace_rq_insert
  - kernel/trace/blktrace.c:__trace_note_message
```
```
In kernel/trace/bpf_trace.c (ffffffff811e5dfe)
Location: include/linux/cgroup.h:310
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:bpf_current_task_under_cgroup
```
```
In kernel/bpf/helpers.c (ffffffff81216394)
Location: include/linux/cgroup.h:310
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:bpf_get_current_ancestor_cgroup_id
  - kernel/bpf/helpers.c:bpf_get_current_cgroup_id
```
```
In kernel/bpf/local_storage.c (ffffffff81220606)
Location: include/linux/cgroup.h:310
Inline: True
Inline callers:
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_link
```
```
In kernel/bpf/cgroup.c (ffffffff8123444d)
Location: include/linux/cgroup.h:310
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:bpf_cgroup_link_fill_link_info
  - kernel/bpf/cgroup.c:bpf_cgroup_link_show_fdinfo
  - kernel/bpf/cgroup.c:__cgroup_bpf_attach
```
```
In kernel/events/core.c (ffffffff8123d739)
Location: include/linux/cgroup.h:310
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_cgroup
  - kernel/events/core.c:__perf_pmu_output_stop
  - kernel/events/core.c:perf_iterate_sb
  - kernel/events/core.c:perf_prepare_sample
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
In mm/rmap.c (ffffffff812af2f6)
Location: include/linux/cgroup.h:310
Inline: True
Inline callers:
  - mm/rmap.c:invalid_page_referenced_vma
```
```
In mm/memcontrol.c (ffffffff813086a7)
Location: include/linux/cgroup.h:310
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_get_oom_group
  - mm/memcontrol.c:memcg_oom_wake_function
  - mm/memcontrol.c:memcg_oom_wake_function
  - mm/memcontrol.c:mem_cgroup_wait_acct_move
  - mm/memcontrol.c:mem_cgroup_wait_acct_move
```
```
In net/core/filter.c (ffffffff81a2e8c0)
Location: include/linux/cgroup.h:310
Inline: True
Inline callers:
  - net/core/filter.c:bpf_sk_ancestor_cgroup_id
  - net/core/filter.c:bpf_sk_cgroup_id
  - net/core/filter.c:bpf_skb_ancestor_cgroup_id
  - net/core/filter.c:bpf_skb_cgroup_id
  - net/core/filter.c:bpf_skb_under_cgroup
```
```
In net/mptcp/subflow.c (ffffffff81bc35d4)
Location: include/linux/cgroup.h:310
Inline: True
Inline callers:
  - net/mptcp/subflow.c:mptcp_subflow_create_socket
  - net/mptcp/subflow.c:mptcp_subflow_create_socket
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
In kernel/cgroup/cgroup.c (ffffffff811721f6)
Location: include/linux/cgroup.h:310
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_create
  - kernel/cgroup/cgroup.c:perf_trace_cgroup_event
  - kernel/cgroup/cgroup.c:perf_trace_cgroup_migrate
  - kernel/cgroup/cgroup.c:perf_trace_cgroup
  - kernel/cgroup/cgroup.c:trace_event_raw_event_cgroup_event
  - kernel/cgroup/cgroup.c:trace_event_raw_event_cgroup_migrate
  - kernel/cgroup/cgroup.c:trace_event_raw_event_cgroup
```
```
In kernel/trace/blktrace.c (ffffffff811d0857)
Location: include/linux/cgroup.h:310
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:blk_add_trace_bio_remap
  - kernel/trace/blktrace.c:blk_add_trace_split
  - kernel/trace/blktrace.c:blk_add_trace_bio
  - kernel/trace/blktrace.c:blk_add_trace_rq_complete
  - kernel/trace/blktrace.c:blk_add_trace_rq_requeue
  - kernel/trace/blktrace.c:blk_add_trace_rq_merge
  - kernel/trace/blktrace.c:blk_add_trace_rq_issue
  - kernel/trace/blktrace.c:blk_add_trace_rq_insert
  - kernel/trace/blktrace.c:__trace_note_message
```
```
In kernel/trace/bpf_trace.c (ffffffff811e74d1)
Location: include/linux/cgroup.h:310
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:bpf_current_task_under_cgroup
```
```
In kernel/bpf/helpers.c (ffffffff812190a7)
Location: include/linux/cgroup.h:310
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:bpf_get_current_ancestor_cgroup_id
  - kernel/bpf/helpers.c:bpf_get_current_cgroup_id
```
```
In kernel/bpf/local_storage.c (ffffffff81224096)
Location: include/linux/cgroup.h:310
Inline: True
Inline callers:
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_link
```
```
In kernel/bpf/cgroup.c (ffffffff8123828d)
Location: include/linux/cgroup.h:310
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:bpf_cgroup_link_fill_link_info
  - kernel/bpf/cgroup.c:bpf_cgroup_link_show_fdinfo
  - kernel/bpf/cgroup.c:__cgroup_bpf_attach
```
```
In kernel/events/core.c (ffffffff812421a9)
Location: include/linux/cgroup.h:310
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_cgroup
  - kernel/events/core.c:__perf_pmu_output_stop
  - kernel/events/core.c:perf_iterate_sb
  - kernel/events/core.c:perf_prepare_sample
  - kernel/events/core.c:perf_event_read
  - kernel/events/core.c:__perf_event_read
  - kernel/events/core.c:perf_adjust_freq_unthr_context
  - kernel/events/core.c:merge_sched_in
  - kernel/events/core.c:__perf_event_enable
  - kernel/events/core.c:__perf_event_enable
  - kernel/events/core.c:__perf_install_in_context
  - kernel/events/core.c:__perf_event_disable
  - kernel/events/core.c:list_add_event
  - kernel/events/core.c:perf_event_groups_first
  - kernel/events/core.c:perf_event_groups_first
  - kernel/events/core.c:perf_event_groups_insert
  - kernel/events/core.c:perf_event_groups_insert
```
```
In mm/rmap.c (ffffffff812b47d6)
Location: include/linux/cgroup.h:310
Inline: True
Inline callers:
  - mm/rmap.c:invalid_page_referenced_vma
```
```
In mm/memcontrol.c (ffffffff8130d994)
Location: include/linux/cgroup.h:310
Inline: True
Inline callers:
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:mem_cgroup_get_oom_group
  - mm/memcontrol.c:memcg_oom_wake_function
  - mm/memcontrol.c:memcg_oom_wake_function
```
```
In net/core/filter.c (ffffffff81a15efe)
Location: include/linux/cgroup.h:310
Inline: True
Inline callers:
  - net/core/filter.c:bpf_sk_ancestor_cgroup_id
  - net/core/filter.c:bpf_sk_cgroup_id
  - net/core/filter.c:bpf_skb_ancestor_cgroup_id
  - net/core/filter.c:bpf_skb_cgroup_id
  - net/core/filter.c:bpf_skb_under_cgroup
```
```
In net/mptcp/subflow.c (ffffffff81bb3c44)
Location: include/linux/cgroup.h:310
Inline: True
Inline callers:
  - net/mptcp/subflow.c:mptcp_subflow_create_socket
  - net/mptcp/subflow.c:mptcp_subflow_create_socket
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
In kernel/cgroup/cgroup.c (ffffffff81198ce6)
Location: include/linux/cgroup.h:310
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_create
  - kernel/cgroup/cgroup.c:perf_trace_cgroup_event
  - kernel/cgroup/cgroup.c:perf_trace_cgroup_migrate
  - kernel/cgroup/cgroup.c:perf_trace_cgroup
  - kernel/cgroup/cgroup.c:trace_event_raw_event_cgroup_event
  - kernel/cgroup/cgroup.c:trace_event_raw_event_cgroup_migrate
  - kernel/cgroup/cgroup.c:trace_event_raw_event_cgroup
```
```
In kernel/trace/blktrace.c (ffffffff811fd187)
Location: include/linux/cgroup.h:310
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:blk_add_trace_bio_remap
  - kernel/trace/blktrace.c:blk_add_trace_split
  - kernel/trace/blktrace.c:blk_add_trace_bio
  - kernel/trace/blktrace.c:blk_add_trace_rq_complete
  - kernel/trace/blktrace.c:blk_add_trace_rq_requeue
  - kernel/trace/blktrace.c:blk_add_trace_rq_merge
  - kernel/trace/blktrace.c:blk_add_trace_rq_issue
  - kernel/trace/blktrace.c:blk_add_trace_rq_insert
  - kernel/trace/blktrace.c:__trace_note_message
```
```
In kernel/trace/bpf_trace.c (ffffffff81218151)
Location: include/linux/cgroup.h:310
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:bpf_current_task_under_cgroup
```
```
In kernel/bpf/helpers.c (ffffffff8124fc56)
Location: include/linux/cgroup.h:310
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:bpf_get_current_ancestor_cgroup_id
  - kernel/bpf/helpers.c:bpf_get_current_cgroup_id
```
```
In kernel/bpf/local_storage.c (ffffffff8125bfd6)
Location: include/linux/cgroup.h:310
Inline: True
Inline callers:
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_link
```
```
In kernel/bpf/cgroup.c (ffffffff8127288d)
Location: include/linux/cgroup.h:310
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:bpf_cgroup_link_fill_link_info
  - kernel/bpf/cgroup.c:bpf_cgroup_link_show_fdinfo
  - kernel/bpf/cgroup.c:__cgroup_bpf_attach
```
```
In kernel/events/core.c (ffffffff8127cab9)
Location: include/linux/cgroup.h:310
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_cgroup
  - kernel/events/core.c:__perf_pmu_output_stop
  - kernel/events/core.c:perf_iterate_sb
  - kernel/events/core.c:perf_prepare_sample
  - kernel/events/core.c:perf_event_read
  - kernel/events/core.c:__perf_event_read
  - kernel/events/core.c:perf_adjust_freq_unthr_context
  - kernel/events/core.c:merge_sched_in
  - kernel/events/core.c:__perf_event_enable
  - kernel/events/core.c:__perf_event_enable
  - kernel/events/core.c:__perf_install_in_context
  - kernel/events/core.c:__perf_event_disable
  - kernel/events/core.c:list_add_event
  - kernel/events/core.c:perf_event_groups_first
  - kernel/events/core.c:perf_event_groups_first
  - kernel/events/core.c:perf_event_groups_insert
  - kernel/events/core.c:perf_event_groups_insert
```
```
In mm/rmap.c (ffffffff812f63b6)
Location: include/linux/cgroup.h:310
Inline: True
Inline callers:
  - mm/rmap.c:invalid_page_referenced_vma
```
```
In mm/memcontrol.c (ffffffff813587cd)
Location: include/linux/cgroup.h:310
Inline: True
Inline callers:
  - mm/memcontrol.c:try_charge_memcg
  - mm/memcontrol.c:try_charge_memcg
  - mm/memcontrol.c:mem_cgroup_get_oom_group
  - mm/memcontrol.c:memcg_oom_wake_function
  - mm/memcontrol.c:memcg_oom_wake_function
```
```
In net/core/filter.c (ffffffff81acc086)
Location: include/linux/cgroup.h:310
Inline: True
Inline callers:
  - net/core/filter.c:bpf_sk_ancestor_cgroup_id
  - net/core/filter.c:bpf_sk_cgroup_id
  - net/core/filter.c:bpf_skb_ancestor_cgroup_id
  - net/core/filter.c:bpf_skb_cgroup_id
  - net/core/filter.c:bpf_skb_under_cgroup
```
```
In net/mptcp/subflow.c (ffffffff81c8237f)
Location: include/linux/cgroup.h:310
Inline: True
Inline callers:
  - net/mptcp/subflow.c:mptcp_subflow_create_socket
  - net/mptcp/subflow.c:mptcp_subflow_create_socket
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
In kernel/cgroup/cgroup.c (ffffffff811c8e9b)
Location: include/linux/cgroup.h:310
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_create
  - kernel/cgroup/cgroup.c:perf_trace_cgroup_event
  - kernel/cgroup/cgroup.c:perf_trace_cgroup_migrate
  - kernel/cgroup/cgroup.c:perf_trace_cgroup
  - kernel/cgroup/cgroup.c:trace_event_raw_event_cgroup_event
  - kernel/cgroup/cgroup.c:trace_event_raw_event_cgroup_migrate
  - kernel/cgroup/cgroup.c:trace_event_raw_event_cgroup
```
```
In kernel/trace/blktrace.c (ffffffff81237224)
Location: include/linux/cgroup.h:310
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:blk_add_trace_bio_remap
  - kernel/trace/blktrace.c:blk_add_trace_split
  - kernel/trace/blktrace.c:blk_add_trace_getrq
  - kernel/trace/blktrace.c:blk_add_trace_bio_queue
  - kernel/trace/blktrace.c:blk_add_trace_bio_frontmerge
  - kernel/trace/blktrace.c:blk_add_trace_bio_backmerge
  - kernel/trace/blktrace.c:blk_add_trace_bio_bounce
  - kernel/trace/blktrace.c:blk_add_trace_rq_complete
  - kernel/trace/blktrace.c:blk_add_trace_rq_requeue
  - kernel/trace/blktrace.c:blk_add_trace_rq_merge
  - kernel/trace/blktrace.c:blk_add_trace_rq_issue
  - kernel/trace/blktrace.c:blk_add_trace_rq_insert
  - kernel/trace/blktrace.c:__blk_trace_note_message
```
```
In kernel/trace/bpf_trace.c (ffffffff812561e4)
Location: include/linux/cgroup.h:310
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:bpf_current_task_under_cgroup
```
```
In kernel/bpf/helpers.c (ffffffff81297085)
Location: include/linux/cgroup.h:310
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:bpf_get_current_ancestor_cgroup_id
  - kernel/bpf/helpers.c:bpf_get_current_cgroup_id
```
```
In kernel/bpf/local_storage.c (ffffffff812a5ba6)
Location: include/linux/cgroup.h:310
Inline: True
Inline callers:
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_link
```
```
In kernel/bpf/cgroup.c (ffffffff812c1ccd)
Location: include/linux/cgroup.h:310
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:bpf_cgroup_link_fill_link_info
  - kernel/bpf/cgroup.c:bpf_cgroup_link_show_fdinfo
  - kernel/bpf/cgroup.c:__cgroup_bpf_attach
```
```
In kernel/events/core.c (ffffffff812d12f1)
Location: include/linux/cgroup.h:310
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_cgroup
  - kernel/events/core.c:__perf_pmu_output_stop
  - kernel/events/core.c:__perf_pmu_output_stop
  - kernel/events/core.c:perf_iterate_sb
  - kernel/events/core.c:perf_prepare_sample
  - kernel/events/core.c:perf_adjust_freq_unthr_context
  - kernel/events/core.c:merge_sched_in
  - kernel/events/core.c:__perf_event_enable
  - kernel/events/core.c:__perf_install_in_context
  - kernel/events/core.c:perf_event_groups_first
  - kernel/events/core.c:perf_event_groups_first
  - kernel/events/core.c:perf_event_groups_insert
  - kernel/events/core.c:perf_event_groups_insert
```
```
In mm/rmap.c (ffffffff8135b058)
Location: include/linux/cgroup.h:310
Inline: True
Inline callers:
  - mm/rmap.c:invalid_folio_referenced_vma
```
```
In mm/memcontrol.c (ffffffff813d268d)
Location: include/linux/cgroup.h:310
Inline: True
Inline callers:
  - mm/memcontrol.c:try_charge_memcg
  - mm/memcontrol.c:try_charge_memcg
  - mm/memcontrol.c:mem_cgroup_get_oom_group
  - mm/memcontrol.c:memcg_oom_wake_function
  - mm/memcontrol.c:memcg_oom_wake_function
```
```
In net/core/filter.c (ffffffff81c488d4)
Location: include/linux/cgroup.h:310
Inline: True
Inline callers:
  - net/core/filter.c:bpf_sk_ancestor_cgroup_id
  - net/core/filter.c:bpf_sk_cgroup_id
  - net/core/filter.c:bpf_skb_ancestor_cgroup_id
  - net/core/filter.c:bpf_skb_cgroup_id
  - net/core/filter.c:bpf_skb_under_cgroup
```
```
In net/mptcp/subflow.c (ffffffff81e280b2)
Location: include/linux/cgroup.h:310
Inline: True
Inline callers:
  - net/mptcp/subflow.c:mptcp_subflow_create_socket
  - net/mptcp/subflow.c:mptcp_subflow_create_socket
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
In kernel/cgroup/cgroup.c (ffffffff812048ce)
Location: include/linux/cgroup.h:326
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:perf_trace_cgroup_event
  - kernel/cgroup/cgroup.c:perf_trace_cgroup_migrate
  - kernel/cgroup/cgroup.c:perf_trace_cgroup
  - kernel/cgroup/cgroup.c:trace_event_raw_event_cgroup_event
  - kernel/cgroup/cgroup.c:trace_event_raw_event_cgroup_migrate
  - kernel/cgroup/cgroup.c:trace_event_raw_event_cgroup
```
```
In kernel/trace/blktrace.c (ffffffff81283fa6)
Location: include/linux/cgroup.h:326
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:blk_add_trace_bio_remap
  - kernel/trace/blktrace.c:blk_add_trace_split
  - kernel/trace/blktrace.c:blk_add_trace_getrq
  - kernel/trace/blktrace.c:blk_add_trace_bio_queue
  - kernel/trace/blktrace.c:blk_add_trace_bio_frontmerge
  - kernel/trace/blktrace.c:blk_add_trace_bio_backmerge
  - kernel/trace/blktrace.c:blk_add_trace_bio_complete
  - kernel/trace/blktrace.c:blk_add_trace_bio_bounce
  - kernel/trace/blktrace.c:blk_add_trace_rq_complete
  - kernel/trace/blktrace.c:blk_add_trace_rq_requeue
  - kernel/trace/blktrace.c:blk_add_trace_rq_merge
  - kernel/trace/blktrace.c:blk_add_trace_rq_issue
  - kernel/trace/blktrace.c:blk_add_trace_rq_insert
  - kernel/trace/blktrace.c:__blk_trace_note_message
```
```
In kernel/bpf/helpers.c (ffffffff812f1e77)
Location: include/linux/cgroup.h:326
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:bpf_get_current_ancestor_cgroup_id
  - kernel/bpf/helpers.c:bpf_get_current_cgroup_id
```
```
In kernel/bpf/local_storage.c (ffffffff81303c26)
Location: include/linux/cgroup.h:326
Inline: True
Inline callers:
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_link
```
```
In kernel/bpf/cgroup_iter.c (ffffffff8132503c)
Location: include/linux/cgroup.h:326
Inline: True
Inline callers:
  - kernel/bpf/cgroup_iter.c:bpf_iter_cgroup_fill_link_info
```
```
In kernel/bpf/cgroup.c (ffffffff8132633d)
Location: include/linux/cgroup.h:326
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:bpf_cgroup_link_fill_link_info
  - kernel/bpf/cgroup.c:bpf_cgroup_link_show_fdinfo
  - kernel/bpf/cgroup.c:__cgroup_bpf_attach
```
```
In kernel/events/core.c (ffffffff81338ae1)
Location: include/linux/cgroup.h:326
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_cgroup
  - kernel/events/core.c:perf_prepare_sample
  - kernel/events/core.c:perf_event_groups_first
  - kernel/events/core.c:perf_event_groups_first
  - kernel/events/core.c:perf_event_groups_insert
  - kernel/events/core.c:perf_event_groups_insert
```
```
In net/core/filter.c (ffffffff81dfd3f7)
Location: include/linux/cgroup.h:326
Inline: True
Inline callers:
  - net/core/filter.c:bpf_sk_ancestor_cgroup_id
  - net/core/filter.c:bpf_sk_cgroup_id
  - net/core/filter.c:bpf_skb_ancestor_cgroup_id
  - net/core/filter.c:bpf_skb_cgroup_id
```
```
In net/mptcp/subflow.c (ffffffff82000014)
Location: include/linux/cgroup.h:326
Inline: True
Inline callers:
  - net/mptcp/subflow.c:mptcp_subflow_create_socket
  - net/mptcp/subflow.c:mptcp_subflow_create_socket
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
In kernel/cgroup/cgroup.c (ffffffff81219ebe)
Location: include/linux/cgroup.h:325
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:perf_trace_cgroup_event
  - kernel/cgroup/cgroup.c:perf_trace_cgroup_migrate
  - kernel/cgroup/cgroup.c:perf_trace_cgroup
  - kernel/cgroup/cgroup.c:trace_event_raw_event_cgroup_event
  - kernel/cgroup/cgroup.c:trace_event_raw_event_cgroup_migrate
  - kernel/cgroup/cgroup.c:trace_event_raw_event_cgroup
```
```
In kernel/trace/blktrace.c (ffffffff812a0c50)
Location: include/linux/cgroup.h:325
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:blk_add_trace_bio_remap
  - kernel/trace/blktrace.c:blk_add_trace_split
  - kernel/trace/blktrace.c:blk_add_trace_getrq
  - kernel/trace/blktrace.c:blk_add_trace_bio_queue
  - kernel/trace/blktrace.c:blk_add_trace_bio_frontmerge
  - kernel/trace/blktrace.c:blk_add_trace_bio_backmerge
  - kernel/trace/blktrace.c:blk_add_trace_bio_complete
  - kernel/trace/blktrace.c:blk_add_trace_bio_bounce
  - kernel/trace/blktrace.c:blk_add_trace_rq_complete
  - kernel/trace/blktrace.c:blk_add_trace_rq_requeue
  - kernel/trace/blktrace.c:blk_add_trace_rq_merge
  - kernel/trace/blktrace.c:blk_add_trace_rq_issue
  - kernel/trace/blktrace.c:blk_add_trace_rq_insert
  - kernel/trace/blktrace.c:__blk_trace_note_message
```
```
In kernel/bpf/helpers.c (ffffffff8131e9f7)
Location: include/linux/cgroup.h:325
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:bpf_get_current_ancestor_cgroup_id
  - kernel/bpf/helpers.c:bpf_get_current_cgroup_id
```
```
In kernel/bpf/local_storage.c (ffffffff813325b6)
Location: include/linux/cgroup.h:325
Inline: True
Inline callers:
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_link
```
```
In kernel/bpf/cgroup_iter.c (ffffffff8135528c)
Location: include/linux/cgroup.h:325
Inline: True
Inline callers:
  - kernel/bpf/cgroup_iter.c:bpf_iter_cgroup_fill_link_info
```
```
In kernel/bpf/cgroup.c (ffffffff8135668d)
Location: include/linux/cgroup.h:325
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:bpf_cgroup_link_fill_link_info
  - kernel/bpf/cgroup.c:bpf_cgroup_link_show_fdinfo
  - kernel/bpf/cgroup.c:__cgroup_bpf_attach
```
```
In kernel/events/core.c (ffffffff81369b91)
Location: include/linux/cgroup.h:325
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_cgroup
  - kernel/events/core.c:perf_prepare_sample
  - kernel/events/core.c:perf_event_groups_first
  - kernel/events/core.c:perf_event_groups_first
  - kernel/events/core.c:perf_event_groups_insert
  - kernel/events/core.c:perf_event_groups_insert
```
```
In net/core/filter.c (ffffffff81e6dec0)
Location: include/linux/cgroup.h:325
Inline: True
Inline callers:
  - net/core/filter.c:bpf_sk_ancestor_cgroup_id
  - net/core/filter.c:bpf_sk_cgroup_id
  - net/core/filter.c:bpf_skb_ancestor_cgroup_id
  - net/core/filter.c:bpf_skb_cgroup_id
```
```
In net/mptcp/subflow.c (ffffffff8207c1e0)
Location: include/linux/cgroup.h:325
Inline: True
Inline callers:
  - net/mptcp/subflow.c:mptcp_subflow_create_socket
  - net/mptcp/subflow.c:mptcp_subflow_create_socket
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
In kernel/cgroup/cgroup.c (ffffffff812319ee)
Location: include/linux/cgroup.h:324
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:perf_trace_cgroup_event
  - kernel/cgroup/cgroup.c:perf_trace_cgroup_migrate
  - kernel/cgroup/cgroup.c:perf_trace_cgroup
  - kernel/cgroup/cgroup.c:trace_event_raw_event_cgroup_event
  - kernel/cgroup/cgroup.c:trace_event_raw_event_cgroup_migrate
  - kernel/cgroup/cgroup.c:trace_event_raw_event_cgroup
```
```
In kernel/trace/blktrace.c (ffffffff812bc380)
Location: include/linux/cgroup.h:324
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:blk_add_trace_bio_remap
  - kernel/trace/blktrace.c:blk_add_trace_split
  - kernel/trace/blktrace.c:blk_add_trace_getrq
  - kernel/trace/blktrace.c:blk_add_trace_bio_queue
  - kernel/trace/blktrace.c:blk_add_trace_bio_frontmerge
  - kernel/trace/blktrace.c:blk_add_trace_bio_backmerge
  - kernel/trace/blktrace.c:blk_add_trace_bio_complete
  - kernel/trace/blktrace.c:blk_add_trace_bio_bounce
  - kernel/trace/blktrace.c:blk_add_trace_rq_complete
  - kernel/trace/blktrace.c:blk_add_trace_rq_requeue
  - kernel/trace/blktrace.c:blk_add_trace_rq_merge
  - kernel/trace/blktrace.c:blk_add_trace_rq_issue
  - kernel/trace/blktrace.c:blk_add_trace_rq_insert
  - kernel/trace/blktrace.c:__blk_trace_note_message
```
```
In kernel/bpf/helpers.c (ffffffff81340e27)
Location: include/linux/cgroup.h:324
Inline: True
Inline callers:
  - kernel/bpf/helpers.c:bpf_get_current_ancestor_cgroup_id
  - kernel/bpf/helpers.c:bpf_get_current_cgroup_id
```
```
In kernel/bpf/local_storage.c (ffffffff81356b86)
Location: include/linux/cgroup.h:324
Inline: True
Inline callers:
  - kernel/bpf/local_storage.c:bpf_cgroup_storage_link
```
```
In kernel/bpf/cgroup_iter.c (ffffffff8137dc5c)
Location: include/linux/cgroup.h:324
Inline: True
Inline callers:
  - kernel/bpf/cgroup_iter.c:bpf_iter_cgroup_fill_link_info
```
```
In kernel/bpf/cgroup.c (ffffffff8137f1bd)
Location: include/linux/cgroup.h:324
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:bpf_cgroup_link_fill_link_info
  - kernel/bpf/cgroup.c:bpf_cgroup_link_show_fdinfo
  - kernel/bpf/cgroup.c:__cgroup_bpf_attach
```
```
In kernel/events/core.c (ffffffff81392a71)
Location: include/linux/cgroup.h:324
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_cgroup
  - kernel/events/core.c:perf_prepare_sample
  - kernel/events/core.c:perf_event_groups_first
  - kernel/events/core.c:perf_event_groups_first
  - kernel/events/core.c:perf_event_groups_insert
  - kernel/events/core.c:perf_event_groups_insert
```
```
In net/core/filter.c (ffffffff81f2cf50)
Location: include/linux/cgroup.h:324
Inline: True
Inline callers:
  - net/core/filter.c:bpf_sk_ancestor_cgroup_id
  - net/core/filter.c:bpf_sk_cgroup_id
  - net/core/filter.c:bpf_skb_ancestor_cgroup_id
  - net/core/filter.c:bpf_skb_cgroup_id
```
```
In net/mptcp/subflow.c (ffffffff8215169c)
Location: include/linux/cgroup.h:324
Inline: True
Inline callers:
  - net/mptcp/subflow.c:mptcp_subflow_create_socket
  - net/mptcp/subflow.c:mptcp_subflow_create_socket
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
