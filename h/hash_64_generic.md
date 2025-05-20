# Function: <code>hash_64_generic</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/kmmio.c (ffffffff810743df)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:kmmio_page_list
```
```
In kernel/workqueue.c (ffffffff8109b200)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - kernel/workqueue.c:work_busy
  - kernel/workqueue.c:flush_work
  - kernel/workqueue.c:process_one_work
  - kernel/workqueue.c:__queue_work
```
```
In kernel/pid.c (ffffffff810a1108)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - kernel/pid.c:find_pid_ns
  - kernel/pid.c:alloc_pid
```
```
In kernel/sched/wait.c (ffffffff810c7075)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - kernel/sched/wait.c:bit_waitqueue
```
```
In kernel/locking/qspinlock.c (ffffffff810cf5e3)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - kernel/locking/qspinlock.c:__pv_queued_spin_unlock_slowpath
```
```
In kernel/cgroup.c (ffffffff81fab204)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - kernel/cgroup.c:cgroup_init
  - kernel/cgroup.c:cgroup_init
  - kernel/cgroup.c:find_css_set
  - kernel/cgroup.c:find_css_set
```
```
In kernel/kprobes.c (ffffffff81135302)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - kernel/kprobes.c:pre_handler_kretprobe
  - kernel/kprobes.c:__get_valid_kprobe
  - kernel/kprobes.c:kprobe_flush_task
  - kernel/kprobes.c:kretprobe_hash_unlock
  - kernel/kprobes.c:kretprobe_hash_lock
  - kernel/kprobes.c:get_optimized_kprobe
```
```
In kernel/trace/ftrace.c (ffffffff8114dc08)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:register_ftrace_function_probe
  - kernel/trace/ftrace.c:function_trace_probe_call
  - kernel/trace/ftrace.c:__add_hash_entry
  - kernel/trace/ftrace.c:ftrace_lookup_ip
  - kernel/trace/ftrace.c:profile_graph_return
  - kernel/trace/ftrace.c:profile_graph_entry
```
```
In kernel/events/core.c (ffffffff81192166)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - kernel/events/core.c:perf_swevent_add
  - kernel/events/core.c:___perf_sw_event
```
```
In mm/filemap.c (ffffffff8119fe1d)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - mm/filemap.c:__lock_page_killable
  - mm/filemap.c:__lock_page
  - mm/filemap.c:unlock_page
  - mm/filemap.c:add_page_wait_queue
  - mm/filemap.c:wait_on_page_bit_killable_timeout
  - mm/filemap.c:wait_on_page_bit_killable
  - mm/filemap.c:wait_on_page_bit
```
```
In mm/ksm.c (ffffffff81205bd9)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - mm/ksm.c:__ksm_exit
  - mm/ksm.c:__ksm_enter
```
```
In mm/khugepaged.c (ffffffff8121cbb9)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - mm/khugepaged.c:__khugepaged_exit
  - mm/khugepaged.c:__khugepaged_enter
```
```
In fs/dax.c (ffffffff81287756)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - fs/dax.c:dax_wake_mapping_entry_waiter
  - fs/dax.c:get_unlocked_mapping_entry
```
```
In fs/locks.c (ffffffff8128cc99)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - fs/locks.c:posix_lock_inode
```
```
In fs/jbd2/revoke.c (ffffffff8131aeb1)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:insert_revoke_hash
```
```
In fs/ecryptfs/messaging.c (ffffffff8133f7d1)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - fs/ecryptfs/messaging.c:ecryptfs_spawn_daemon
  - fs/ecryptfs/messaging.c:ecryptfs_find_daemon_by_euid
```
```
In security/tomoyo/memory.c (ffffffff813a73fc)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - security/tomoyo/memory.c:tomoyo_get_name
```
```
In security/integrity/ima/ima_queue.c (ffffffff813d3199)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - security/integrity/ima/ima_queue.c:ima_add_template_entry
  - security/integrity/ima/ima_queue.c:ima_add_template_entry
```
```
In block/elevator.c (ffffffff813f77e2)
Location: include/linux/hash.h:77
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
In arch/x86/mm/kmmio.c (ffffffff81077f5f)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:kmmio_page_list
```
```
In kernel/workqueue.c (ffffffff8109ffe0)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - kernel/workqueue.c:work_busy
  - kernel/workqueue.c:flush_work
  - kernel/workqueue.c:process_one_work
  - kernel/workqueue.c:__queue_work
```
```
In kernel/pid.c (ffffffff810a61c8)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - kernel/pid.c:find_pid_ns
  - kernel/pid.c:alloc_pid
```
```
In kernel/ucount.c (ffffffff810ad7c6)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - kernel/ucount.c:inc_ucount
```
```
In kernel/sched/core.c (ffffffff810ae1a0)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - kernel/sched/core.c:bit_waitqueue
```
```
In kernel/locking/qspinlock.c (ffffffff810d5fc3)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - kernel/locking/qspinlock.c:__pv_queued_spin_unlock_slowpath
```
```
In kernel/cgroup.c (ffffffff81fe747a)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - kernel/cgroup.c:cgroup_init
  - kernel/cgroup.c:cgroup_init
  - kernel/cgroup.c:find_css_set
  - kernel/cgroup.c:find_css_set
```
```
In kernel/kprobes.c (ffffffff8113f082)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - kernel/kprobes.c:pre_handler_kretprobe
  - kernel/kprobes.c:__get_valid_kprobe
  - kernel/kprobes.c:kprobe_flush_task
  - kernel/kprobes.c:kretprobe_hash_unlock
  - kernel/kprobes.c:kretprobe_hash_lock
  - kernel/kprobes.c:get_optimized_kprobe
```
```
In kernel/trace/ftrace.c (ffffffff81157b58)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:register_ftrace_function_probe
  - kernel/trace/ftrace.c:function_trace_probe_call
  - kernel/trace/ftrace.c:__add_hash_entry
  - kernel/trace/ftrace.c:ftrace_lookup_ip
  - kernel/trace/ftrace.c:profile_graph_return
  - kernel/trace/ftrace.c:profile_graph_entry
```
```
In kernel/events/core.c (ffffffff811a1916)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - kernel/events/core.c:perf_swevent_add
  - kernel/events/core.c:___perf_sw_event
```
```
In mm/filemap.c (ffffffff811b1057)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_read_iter
  - mm/filemap.c:__lock_page_killable
  - mm/filemap.c:__lock_page
  - mm/filemap.c:add_page_wait_queue
  - mm/filemap.c:wake_up_page_bit
  - mm/filemap.c:__filemap_fdatawait_range
```
```
In mm/ksm.c (ffffffff81217be9)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - mm/ksm.c:__ksm_exit
  - mm/ksm.c:__ksm_enter
```
```
In mm/khugepaged.c (ffffffff8122f1b9)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - mm/khugepaged.c:__khugepaged_exit
  - mm/khugepaged.c:__khugepaged_enter
```
```
In fs/dax.c (ffffffff8129b347)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - fs/dax.c:dax_wake_mapping_entry_waiter
  - fs/dax.c:get_unlocked_mapping_entry
```
```
In fs/locks.c (ffffffff812a268e)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - fs/locks.c:posix_lock_inode
```
```
In fs/jbd2/revoke.c (ffffffff81330e91)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:insert_revoke_hash
```
```
In fs/ecryptfs/messaging.c (ffffffff81355551)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - fs/ecryptfs/messaging.c:ecryptfs_spawn_daemon
  - fs/ecryptfs/messaging.c:ecryptfs_find_daemon_by_euid
```
```
In security/tomoyo/memory.c (ffffffff813bdf7c)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - security/tomoyo/memory.c:tomoyo_get_name
```
```
In security/integrity/ima/ima_queue.c (ffffffff813ea9ea)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - security/integrity/ima/ima_queue.c:ima_add_template_entry
  - security/integrity/ima/ima_queue.c:ima_add_digest_entry
```
```
In block/elevator.c (ffffffff81411395)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - block/elevator.c:elv_rqhash_find
```
```
In net/ipv4/udp.c (ffffffff81824d07)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
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
In arch/x86/mm/kmmio.c (ffffffff8107687f)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:kmmio_page_list
```
```
In kernel/workqueue.c (ffffffff8109d3b0)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - kernel/workqueue.c:work_busy
  - kernel/workqueue.c:flush_work
  - kernel/workqueue.c:process_one_work
  - kernel/workqueue.c:__queue_work
```
```
In kernel/pid.c (ffffffff810a31a8)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - kernel/pid.c:find_pid_ns
  - kernel/pid.c:alloc_pid
```
```
In kernel/ucount.c (ffffffff810aa3a6)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - kernel/ucount.c:inc_ucount
```
```
In kernel/sched/wait_bit.c (ffffffff810c9ce0)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - kernel/sched/wait_bit.c:wake_up_atomic_t
  - kernel/sched/wait_bit.c:out_of_line_wait_on_atomic_t
  - kernel/sched/wait_bit.c:wake_up_bit
  - kernel/sched/wait_bit.c:out_of_line_wait_on_bit_lock
  - kernel/sched/wait_bit.c:out_of_line_wait_on_bit_timeout
  - kernel/sched/wait_bit.c:out_of_line_wait_on_bit
```
```
In kernel/locking/qspinlock.c (ffffffff810d4f43)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - kernel/locking/qspinlock.c:__pv_queued_spin_unlock_slowpath
```
```
In kernel/cgroup/cgroup.c (ffffffff820c7a0f)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/cgroup/cgroup.c:find_css_set
  - kernel/cgroup/cgroup.c:find_css_set
```
```
In kernel/kprobes.c (ffffffff811405ff)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - kernel/kprobes.c:pre_handler_kretprobe
  - kernel/kprobes.c:__get_valid_kprobe
  - kernel/kprobes.c:kprobe_flush_task
  - kernel/kprobes.c:kretprobe_hash_unlock
  - kernel/kprobes.c:kretprobe_hash_lock
  - kernel/kprobes.c:get_optimized_kprobe
```
```
In kernel/trace/ftrace.c (ffffffff8115a6fa)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_module_enable
  - kernel/trace/ftrace.c:__add_hash_entry
  - kernel/trace/ftrace.c:ftrace_lookup_ip
  - kernel/trace/ftrace.c:profile_graph_return
  - kernel/trace/ftrace.c:profile_graph_entry
```
```
In kernel/events/core.c (ffffffff811a91ae)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - kernel/events/core.c:perf_swevent_add
  - kernel/events/core.c:___perf_sw_event
```
```
In mm/filemap.c (ffffffff811b84b2)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_read_iter
  - mm/filemap.c:__lock_page_killable
  - mm/filemap.c:__lock_page
  - mm/filemap.c:add_page_wait_queue
  - mm/filemap.c:wake_up_page_bit
  - mm/filemap.c:__filemap_fdatawait_range
```
```
In mm/ksm.c (ffffffff812237d9)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - mm/ksm.c:__ksm_exit
  - mm/ksm.c:__ksm_enter
```
```
In mm/khugepaged.c (ffffffff8123aa09)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - mm/khugepaged.c:__khugepaged_exit
  - mm/khugepaged.c:__khugepaged_enter
```
```
In fs/dax.c (ffffffff812a9f15)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - fs/dax.c:get_unlocked_mapping_entry
  - fs/dax.c:dax_wake_mapping_entry_waiter
```
```
In fs/locks.c (ffffffff812b1b3d)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - fs/locks.c:posix_lock_inode
```
```
In fs/jbd2/revoke.c (ffffffff81345df1)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:insert_revoke_hash
```
```
In fs/ecryptfs/messaging.c (ffffffff8136a151)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - fs/ecryptfs/messaging.c:ecryptfs_spawn_daemon
  - fs/ecryptfs/messaging.c:ecryptfs_find_daemon_by_euid
```
```
In security/tomoyo/memory.c (ffffffff813d484b)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - security/tomoyo/memory.c:tomoyo_get_name
```
```
In security/integrity/ima/ima_queue.c (ffffffff813f6d25)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - security/integrity/ima/ima_queue.c:ima_add_template_entry
  - security/integrity/ima/ima_queue.c:ima_add_digest_entry
```
```
In block/elevator.c (ffffffff8141ee25)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - block/elevator.c:elv_rqhash_find
```
```
In net/ipv4/udp.c (ffffffff818481bb)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
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
In arch/x86/mm/kmmio.c (ffffffff8107cb7f)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:kmmio_page_list
```
```
In kernel/workqueue.c (ffffffff810a49e0)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - kernel/workqueue.c:work_busy
  - kernel/workqueue.c:flush_work
  - kernel/workqueue.c:process_one_work
  - kernel/workqueue.c:__queue_work
```
```
In kernel/ucount.c (ffffffff810b0c06)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - kernel/ucount.c:inc_ucount
```
```
In kernel/sched/wait_bit.c (ffffffff810d1500)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - kernel/sched/wait_bit.c:wake_up_atomic_t
  - kernel/sched/wait_bit.c:out_of_line_wait_on_atomic_t
  - kernel/sched/wait_bit.c:wake_up_bit
  - kernel/sched/wait_bit.c:out_of_line_wait_on_bit_lock
  - kernel/sched/wait_bit.c:out_of_line_wait_on_bit_timeout
  - kernel/sched/wait_bit.c:out_of_line_wait_on_bit
```
```
In kernel/locking/qspinlock.c (ffffffff810dcea3)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - kernel/locking/qspinlock.c:__pv_queued_spin_unlock_slowpath
```
```
In kernel/livepatch/shadow.c (ffffffff81103092)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - kernel/livepatch/shadow.c:klp_shadow_free
  - kernel/livepatch/shadow.c:__klp_shadow_get_or_alloc
  - kernel/livepatch/shadow.c:__klp_shadow_get_or_alloc
```
```
In kernel/cgroup/cgroup.c (ffffffff826d0075)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/cgroup/cgroup.c:find_css_set
  - kernel/cgroup/cgroup.c:find_css_set
```
```
In kernel/kprobes.c (ffffffff8114d4a2)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - kernel/kprobes.c:pre_handler_kretprobe
  - kernel/kprobes.c:__get_valid_kprobe
  - kernel/kprobes.c:kprobe_flush_task
  - kernel/kprobes.c:kretprobe_hash_unlock
  - kernel/kprobes.c:kretprobe_hash_lock
  - kernel/kprobes.c:get_optimized_kprobe
```
```
In kernel/trace/ftrace.c (ffffffff8116738a)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_module_enable
  - kernel/trace/ftrace.c:__add_hash_entry
  - kernel/trace/ftrace.c:ftrace_lookup_ip
  - kernel/trace/ftrace.c:profile_graph_return
  - kernel/trace/ftrace.c:profile_graph_entry
```
```
In kernel/events/core.c (ffffffff811bc9f2)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - kernel/events/core.c:perf_swevent_add
  - kernel/events/core.c:___perf_sw_event
```
```
In mm/filemap.c (ffffffff811ccc19)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_read_iter
  - mm/filemap.c:__lock_page_killable
  - mm/filemap.c:__lock_page
  - mm/filemap.c:add_page_wait_queue
  - mm/filemap.c:wake_up_page_bit
  - mm/filemap.c:__filemap_fdatawait_range
```
```
In mm/ksm.c (ffffffff8123ee19)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - mm/ksm.c:__ksm_exit
  - mm/ksm.c:__ksm_enter
```
```
In mm/khugepaged.c (ffffffff8125a299)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - mm/khugepaged.c:__khugepaged_exit
  - mm/khugepaged.c:__khugepaged_enter
```
```
In fs/dax.c (ffffffff812cd4c5)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - fs/dax.c:get_unlocked_mapping_entry
  - fs/dax.c:dax_wake_mapping_entry_waiter
```
```
In fs/locks.c (ffffffff812d565e)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - fs/locks.c:posix_lock_inode
```
```
In fs/jbd2/revoke.c (ffffffff8136a481)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:insert_revoke_hash
```
```
In fs/ecryptfs/messaging.c (ffffffff8138ed11)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - fs/ecryptfs/messaging.c:ecryptfs_spawn_daemon
  - fs/ecryptfs/messaging.c:ecryptfs_find_daemon_by_euid
```
```
In security/tomoyo/memory.c (ffffffff813fad5b)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - security/tomoyo/memory.c:tomoyo_get_name
```
```
In security/integrity/ima/ima_queue.c (ffffffff8141ee45)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - security/integrity/ima/ima_queue.c:ima_add_template_entry
  - security/integrity/ima/ima_queue.c:ima_add_digest_entry
```
```
In block/elevator.c (ffffffff81449905)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - block/elevator.c:elv_rqhash_find
```
```
In net/ipv4/udp.c (ffffffff818c7c01)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
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
In arch/x86/mm/kmmio.c (ffffffff8107fb3e)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:kmmio_page_list
```
```
In kernel/workqueue.c (ffffffff810ab1f0)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - kernel/workqueue.c:work_busy
  - kernel/workqueue.c:__flush_work
  - kernel/workqueue.c:process_one_work
  - kernel/workqueue.c:__queue_work
```
```
In kernel/ucount.c (ffffffff810b7a05)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - kernel/ucount.c:inc_ucount
```
```
In kernel/sched/wait_bit.c (ffffffff810d9ab5)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - kernel/sched/wait_bit.c:wake_up_var
  - kernel/sched/wait_bit.c:wake_up_bit
  - kernel/sched/wait_bit.c:out_of_line_wait_on_bit_lock
  - kernel/sched/wait_bit.c:out_of_line_wait_on_bit_timeout
  - kernel/sched/wait_bit.c:out_of_line_wait_on_bit
```
```
In kernel/locking/qspinlock.c (ffffffff810e5543)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - kernel/locking/qspinlock.c:__pv_queued_spin_unlock_slowpath
```
```
In kernel/livepatch/shadow.c (ffffffff8110b746)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - kernel/livepatch/shadow.c:klp_shadow_free
  - kernel/livepatch/shadow.c:__klp_shadow_get_or_alloc
```
```
In kernel/cgroup/cgroup.c (ffffffff826fa7a8)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/cgroup/cgroup.c:find_css_set
  - kernel/cgroup/cgroup.c:find_css_set
```
```
In kernel/kprobes.c (ffffffff8115be3a)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - kernel/kprobes.c:pre_handler_kretprobe
  - kernel/kprobes.c:__get_valid_kprobe
  - kernel/kprobes.c:kprobe_flush_task
  - kernel/kprobes.c:kretprobe_hash_unlock
  - kernel/kprobes.c:kretprobe_hash_lock
  - kernel/kprobes.c:get_optimized_kprobe
```
```
In kernel/trace/ftrace.c (ffffffff81176282)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_module_enable
  - kernel/trace/ftrace.c:__add_hash_entry
  - kernel/trace/ftrace.c:ftrace_lookup_ip
  - kernel/trace/ftrace.c:profile_graph_return
  - kernel/trace/ftrace.c:profile_graph_entry
```
```
In kernel/events/core.c (ffffffff811dcbac)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - kernel/events/core.c:perf_swevent_add
  - kernel/events/core.c:___perf_sw_event
```
```
In mm/filemap.c (ffffffff811edd03)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:__lock_page_killable
  - mm/filemap.c:__lock_page
  - mm/filemap.c:add_page_wait_queue
  - mm/filemap.c:wake_up_page_bit
  - mm/filemap.c:__filemap_fdatawait_range
```
```
In mm/ksm.c (ffffffff812625c9)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - mm/ksm.c:__ksm_exit
  - mm/ksm.c:__ksm_enter
```
```
In mm/khugepaged.c (ffffffff8127dfc9)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - mm/khugepaged.c:__khugepaged_exit
  - mm/khugepaged.c:__khugepaged_enter
```
```
In fs/dax.c (ffffffff812f7827)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - fs/dax.c:__get_unlocked_mapping_entry
  - fs/dax.c:dax_wake_mapping_entry_waiter
```
```
In fs/locks.c (ffffffff812fff67)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - fs/locks.c:posix_lock_inode
```
```
In fs/kernfs/dir.c (ffffffff8132b8db)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_name_hash
```
```
In fs/jbd2/revoke.c (ffffffff81398de4)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:find_revoke_record
  - fs/jbd2/revoke.c:insert_revoke_hash
```
```
In fs/fat/namei_vfat.c (ffffffff813b0ec5)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - fs/fat/namei_vfat.c:vfat_hashi
```
```
In fs/ecryptfs/messaging.c (ffffffff813bddb1)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - fs/ecryptfs/messaging.c:ecryptfs_spawn_daemon
  - fs/ecryptfs/messaging.c:ecryptfs_find_daemon_by_euid
```
```
In fs/efivarfs/super.c (ffffffff813d5862)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - fs/efivarfs/super.c:efivarfs_d_hash
```
```
In security/tomoyo/memory.c (ffffffff8142bd0c)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - security/tomoyo/memory.c:tomoyo_get_name
```
```
In security/integrity/ima/ima_queue.c (ffffffff814510c3)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - security/integrity/ima/ima_queue.c:ima_add_template_entry
  - security/integrity/ima/ima_queue.c:ima_add_digest_entry
```
```
In block/elevator.c (ffffffff8147c655)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - block/elevator.c:elv_rqhash_find
```
```
In net/ipv4/udp.c (ffffffff8191df74)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
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
In arch/x86/mm/kmmio.c (ffffffff8108667e)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:kmmio_page_list
```
```
In kernel/workqueue.c (ffffffff810b4270)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - kernel/workqueue.c:work_busy
  - kernel/workqueue.c:__flush_work
  - kernel/workqueue.c:process_one_work
  - kernel/workqueue.c:__queue_work
```
```
In kernel/ucount.c (ffffffff810c0b05)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - kernel/ucount.c:inc_ucount
```
```
In kernel/sched/wait_bit.c (ffffffff810e35b5)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - kernel/sched/wait_bit.c:wake_up_var
  - kernel/sched/wait_bit.c:wake_up_bit
  - kernel/sched/wait_bit.c:out_of_line_wait_on_bit_lock
  - kernel/sched/wait_bit.c:out_of_line_wait_on_bit_timeout
  - kernel/sched/wait_bit.c:out_of_line_wait_on_bit
```
```
In kernel/locking/qspinlock.c (ffffffff810f0ad3)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - kernel/locking/qspinlock.c:__pv_queued_spin_unlock_slowpath
```
```
In kernel/livepatch/shadow.c (ffffffff81116f36)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - kernel/livepatch/shadow.c:klp_shadow_free
  - kernel/livepatch/shadow.c:__klp_shadow_get_or_alloc
```
```
In kernel/cgroup/cgroup.c (ffffffff828b16a4)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/cgroup/cgroup.c:find_css_set
  - kernel/cgroup/cgroup.c:find_css_set
```
```
In kernel/kprobes.c (ffffffff81168bca)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - kernel/kprobes.c:pre_handler_kretprobe
  - kernel/kprobes.c:__get_valid_kprobe
  - kernel/kprobes.c:kprobe_flush_task
  - kernel/kprobes.c:kretprobe_hash_unlock
  - kernel/kprobes.c:kretprobe_hash_lock
  - kernel/kprobes.c:get_optimized_kprobe
```
```
In kernel/trace/ftrace.c (ffffffff81183ec2)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_module_enable
  - kernel/trace/ftrace.c:__add_hash_entry
  - kernel/trace/ftrace.c:ftrace_lookup_ip
  - kernel/trace/ftrace.c:profile_graph_return
```
```
In kernel/events/core.c (ffffffff811ecfac)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - kernel/events/core.c:perf_swevent_add
  - kernel/events/core.c:___perf_sw_event
```
```
In mm/filemap.c (ffffffff811ff2bc)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:__lock_page_killable
  - mm/filemap.c:__lock_page
  - mm/filemap.c:add_page_wait_queue
  - mm/filemap.c:put_and_wait_on_page_locked
  - mm/filemap.c:wake_up_page_bit
  - mm/filemap.c:__filemap_fdatawait_range
```
```
In mm/ksm.c (ffffffff81276e49)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - mm/ksm.c:__ksm_exit
  - mm/ksm.c:__ksm_enter
```
```
In mm/khugepaged.c (ffffffff812926a9)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - mm/khugepaged.c:__khugepaged_exit
  - mm/khugepaged.c:__khugepaged_enter
```
```
In fs/dax.c (ffffffff8130cc01)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - fs/dax.c:wait_entry_unlocked
  - fs/dax.c:get_unlocked_entry
  - fs/dax.c:dax_wake_entry
```
```
In fs/crypto/keyinfo.c (ffffffff81311123)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - fs/crypto/keyinfo.c:find_or_insert_master_key
```
```
In fs/locks.c (ffffffff81315a86)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - fs/locks.c:posix_lock_inode
```
```
In fs/kernfs/dir.c (ffffffff81342c3b)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_name_hash
```
```
In fs/jbd2/revoke.c (ffffffff813b1b54)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:find_revoke_record
  - fs/jbd2/revoke.c:insert_revoke_hash
```
```
In fs/fat/namei_vfat.c (ffffffff813ca525)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - fs/fat/namei_vfat.c:vfat_hashi
```
```
In fs/ecryptfs/messaging.c (ffffffff813d73f1)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - fs/ecryptfs/messaging.c:ecryptfs_spawn_daemon
  - fs/ecryptfs/messaging.c:ecryptfs_find_daemon_by_euid
```
```
In fs/fuse/dev.c (ffffffff813dbdab)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_do_write
```
```
In fs/efivarfs/super.c (ffffffff813efeb2)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - fs/efivarfs/super.c:efivarfs_d_hash
```
```
In security/tomoyo/memory.c (ffffffff8144862c)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - security/tomoyo/memory.c:tomoyo_get_name
```
```
In security/integrity/ima/ima_queue.c (ffffffff8146e0a5)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - security/integrity/ima/ima_queue.c:ima_add_template_entry
  - security/integrity/ima/ima_queue.c:ima_add_digest_entry
```
```
In block/elevator.c (ffffffff8149a645)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - block/elevator.c:elv_rqhash_find
```
```
In net/ipv4/udp.c (ffffffff8194cbc4)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
```
```
In lib/vsprintf.c (ffffffff81a1449a)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - lib/vsprintf.c:ptr_to_id
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
In arch/x86/mm/kmmio.c (ffffffff8108a28e)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:kmmio_page_list
```
```
In kernel/workqueue.c (ffffffff810b926e)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - kernel/workqueue.c:work_busy
  - kernel/workqueue.c:__flush_work
  - kernel/workqueue.c:process_one_work
  - kernel/workqueue.c:__queue_work
```
```
In kernel/ucount.c (ffffffff810c6c05)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - kernel/ucount.c:inc_ucount
```
```
In kernel/sched/wait_bit.c (ffffffff810ea1c5)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - kernel/sched/wait_bit.c:wake_up_var
  - kernel/sched/wait_bit.c:wake_up_bit
  - kernel/sched/wait_bit.c:out_of_line_wait_on_bit_lock
  - kernel/sched/wait_bit.c:out_of_line_wait_on_bit_timeout
  - kernel/sched/wait_bit.c:out_of_line_wait_on_bit
```
```
In kernel/locking/qspinlock.c (ffffffff810f91a9)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - kernel/locking/qspinlock.c:__pv_queued_spin_unlock_slowpath
```
```
In kernel/livepatch/shadow.c (ffffffff811211b6)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - kernel/livepatch/shadow.c:klp_shadow_free
  - kernel/livepatch/shadow.c:__klp_shadow_get_or_alloc
  - kernel/livepatch/shadow.c:klp_shadow_get
```
```
In kernel/cgroup/cgroup.c (ffffffff828ca349)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/cgroup/cgroup.c:find_css_set
  - kernel/cgroup/cgroup.c:find_css_set
```
```
In kernel/kprobes.c (ffffffff8117585d)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - kernel/kprobes.c:pre_handler_kretprobe
  - kernel/kprobes.c:__get_valid_kprobe
  - kernel/kprobes.c:kprobe_flush_task
  - kernel/kprobes.c:kretprobe_hash_unlock
  - kernel/kprobes.c:kretprobe_hash_lock
  - kernel/kprobes.c:get_optimized_kprobe
```
```
In kernel/trace/ftrace.c (ffffffff81190c38)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_module_enable
  - kernel/trace/ftrace.c:__add_hash_entry
  - kernel/trace/ftrace.c:ftrace_lookup_ip
  - kernel/trace/ftrace.c:profile_graph_return
```
```
In kernel/events/core.c (ffffffff81204998)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - kernel/events/core.c:perf_swevent_add
  - kernel/events/core.c:___perf_sw_event
```
```
In mm/filemap.c (ffffffff8121631e)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:__lock_page_killable
  - mm/filemap.c:__lock_page
  - mm/filemap.c:add_page_wait_queue
  - mm/filemap.c:put_and_wait_on_page_locked
  - mm/filemap.c:wake_up_page_bit
```
```
In mm/ksm.c (ffffffff812926ba)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - mm/ksm.c:__ksm_exit
  - mm/ksm.c:__ksm_enter
```
```
In mm/khugepaged.c (ffffffff812ad08a)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - mm/khugepaged.c:__khugepaged_exit
  - mm/khugepaged.c:__khugepaged_enter
```
```
In fs/dax.c (ffffffff813341bd)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - fs/dax.c:wait_entry_unlocked
  - fs/dax.c:get_unlocked_entry
  - fs/dax.c:dax_wake_entry
```
```
In fs/crypto/keyinfo.c (ffffffff813384a3)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - fs/crypto/keyinfo.c:find_or_insert_master_key
```
```
In fs/locks.c (ffffffff8133d3bc)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:__locks_insert_block
```
```
In fs/kernfs/dir.c (ffffffff8136aec9)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_name_hash
```
```
In fs/jbd2/revoke.c (ffffffff813dc194)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:find_revoke_record
  - fs/jbd2/revoke.c:insert_revoke_hash
```
```
In fs/fat/namei_vfat.c (ffffffff813f50c9)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - fs/fat/namei_vfat.c:vfat_hashi
```
```
In fs/ecryptfs/messaging.c (ffffffff81401d41)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - fs/ecryptfs/messaging.c:ecryptfs_spawn_daemon
  - fs/ecryptfs/messaging.c:ecryptfs_find_daemon_by_euid
```
```
In fs/fuse/dev.c (ffffffff8140819d)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_do_write
```
```
In fs/efivarfs/super.c (ffffffff8141c1e8)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - fs/efivarfs/super.c:efivarfs_d_hash
```
```
In security/tomoyo/memory.c (ffffffff8147627d)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - security/tomoyo/memory.c:tomoyo_get_name
```
```
In security/integrity/ima/ima_queue.c (ffffffff8149b775)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - security/integrity/ima/ima_queue.c:ima_add_template_entry
  - security/integrity/ima/ima_queue.c:ima_add_digest_entry
```
```
In block/elevator.c (ffffffff814c8725)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - block/elevator.c:elv_rqhash_find
```
```
In net/core/bpf_sk_storage.c (ffffffff81952985)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:selem_link_map
  - net/core/bpf_sk_storage.c:selem_unlink_map
```
```
In net/ipv4/udp.c (ffffffff819b1387)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
```
```
In lib/vsprintf.c (ffffffff81a83c51)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - lib/vsprintf.c:ptr_to_id
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
In arch/x86/mm/kmmio.c (ffffffff8108aefe)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:kmmio_page_list
```
```
In kernel/workqueue.c (ffffffff810bf7ae)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - kernel/workqueue.c:work_busy
  - kernel/workqueue.c:__flush_work
  - kernel/workqueue.c:process_one_work
  - kernel/workqueue.c:__queue_work
```
```
In kernel/ucount.c (ffffffff810cfcd5)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - kernel/ucount.c:inc_ucount
```
```
In kernel/sched/wait_bit.c (ffffffff810f5b95)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - kernel/sched/wait_bit.c:wake_up_var
  - kernel/sched/wait_bit.c:wake_up_bit
  - kernel/sched/wait_bit.c:out_of_line_wait_on_bit_lock
  - kernel/sched/wait_bit.c:out_of_line_wait_on_bit_timeout
  - kernel/sched/wait_bit.c:out_of_line_wait_on_bit
```
```
In kernel/locking/qspinlock.c (ffffffff81104f99)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - kernel/locking/qspinlock.c:__pv_queued_spin_unlock_slowpath
```
```
In kernel/livepatch/shadow.c (ffffffff8112d7d6)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - kernel/livepatch/shadow.c:klp_shadow_free
  - kernel/livepatch/shadow.c:__klp_shadow_get_or_alloc
  - kernel/livepatch/shadow.c:klp_shadow_get
```
```
In kernel/cgroup/cgroup.c (ffffffff828d28a7)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/cgroup/cgroup.c:find_css_set
  - kernel/cgroup/cgroup.c:find_css_set
```
```
In kernel/kprobes.c (ffffffff811816cd)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - kernel/kprobes.c:pre_handler_kretprobe
  - kernel/kprobes.c:__get_valid_kprobe
  - kernel/kprobes.c:kprobe_flush_task
  - kernel/kprobes.c:kretprobe_hash_unlock
  - kernel/kprobes.c:kretprobe_hash_lock
  - kernel/kprobes.c:get_optimized_kprobe
```
```
In kernel/trace/ftrace.c (ffffffff8119cc38)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_module_enable
  - kernel/trace/ftrace.c:__add_hash_entry
  - kernel/trace/ftrace.c:ftrace_lookup_ip
  - kernel/trace/ftrace.c:profile_graph_return
```
```
In kernel/events/core.c (ffffffff81211588)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - kernel/events/core.c:perf_swevent_add
  - kernel/events/core.c:___perf_sw_event
```
```
In mm/filemap.c (ffffffff81223c2e)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:__lock_page_killable
  - mm/filemap.c:__lock_page
  - mm/filemap.c:add_page_wait_queue
  - mm/filemap.c:put_and_wait_on_page_locked
  - mm/filemap.c:wake_up_page_bit
```
```
In mm/ksm.c (ffffffff812a243a)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - mm/ksm.c:__ksm_exit
  - mm/ksm.c:__ksm_enter
```
```
In mm/khugepaged.c (ffffffff812bcbad)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:__khugepaged_exit
  - mm/khugepaged.c:__khugepaged_enter
```
```
In fs/dax.c (ffffffff81347d7d)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - fs/dax.c:wait_entry_unlocked
  - fs/dax.c:get_unlocked_entry
  - fs/dax.c:dax_wake_entry
```
```
In fs/crypto/keysetup_v1.c (ffffffff8134e2af)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:find_or_insert_direct_key
```
```
In fs/locks.c (ffffffff8135596c)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:__locks_insert_block
```
```
In fs/kernfs/dir.c (ffffffff81383089)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_name_hash
```
```
In fs/jbd2/revoke.c (ffffffff813f61e4)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:find_revoke_record
  - fs/jbd2/revoke.c:insert_revoke_hash
```
```
In fs/fat/namei_vfat.c (ffffffff8140ef99)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - fs/fat/namei_vfat.c:vfat_hashi
```
```
In fs/ecryptfs/messaging.c (ffffffff8141bc31)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - fs/ecryptfs/messaging.c:ecryptfs_spawn_daemon
  - fs/ecryptfs/messaging.c:ecryptfs_find_daemon_by_euid
```
```
In fs/fuse/dev.c (ffffffff81422438)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_do_write
```
```
In fs/efivarfs/super.c (ffffffff81436038)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - fs/efivarfs/super.c:efivarfs_d_hash
```
```
In security/tomoyo/memory.c (ffffffff8149001d)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - security/tomoyo/memory.c:tomoyo_get_name
```
```
In security/integrity/ima/ima_queue.c (ffffffff814b59b5)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - security/integrity/ima/ima_queue.c:ima_add_template_entry
  - security/integrity/ima/ima_queue.c:ima_add_digest_entry
```
```
In block/elevator.c (ffffffff814e1845)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - block/elevator.c:elv_rqhash_find
```
```
In net/core/bpf_sk_storage.c (ffffffff81988cd5)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:selem_link_map
  - net/core/bpf_sk_storage.c:selem_unlink_map
```
```
In net/ipv4/udp.c (ffffffff819e80b3)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
```
```
In lib/vsprintf.c (ffffffff81abaec1)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - lib/vsprintf.c:ptr_to_id
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
In arch/x86/mm/kmmio.c (ffffffff81092960)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:add_kmmio_fault_page
  - arch/x86/mm/kmmio.c:get_kmmio_fault_page
```
```
In kernel/workqueue.c (ffffffff810c7a3f)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - kernel/workqueue.c:work_busy
  - kernel/workqueue.c:process_one_work
  - kernel/workqueue.c:__queue_work
```
```
In kernel/ucount.c (ffffffff810d9ad5)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - kernel/ucount.c:get_ucounts
```
```
In kernel/sched/wait_bit.c (ffffffff810ff34e)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - kernel/sched/wait_bit.c:wake_up_var
  - kernel/sched/wait_bit.c:wake_up_bit
  - kernel/sched/wait_bit.c:out_of_line_wait_on_bit_lock
  - kernel/sched/wait_bit.c:out_of_line_wait_on_bit_timeout
  - kernel/sched/wait_bit.c:out_of_line_wait_on_bit
```
```
In kernel/locking/qspinlock.c (ffffffff8110fd79)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - kernel/locking/qspinlock.c:__pv_queued_spin_unlock_slowpath
  - kernel/locking/qspinlock.c:pv_hash
```
```
In kernel/livepatch/shadow.c (ffffffff8113bf48)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - kernel/livepatch/shadow.c:klp_shadow_free
  - kernel/livepatch/shadow.c:__klp_shadow_get_or_alloc
  - kernel/livepatch/shadow.c:klp_shadow_get
```
```
In kernel/cgroup/cgroup.c (ffffffff82cf3273)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/cgroup/cgroup.c:find_css_set
  - kernel/cgroup/cgroup.c:find_existing_css_set
```
```
In kernel/kprobes.c (ffffffff81196bb8)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - kernel/kprobes.c:enable_kprobe
  - kernel/kprobes.c:pre_handler_kretprobe
  - kernel/kprobes.c:__disable_kprobe
  - kernel/kprobes.c:kprobe_flush_task
  - kernel/kprobes.c:kretprobe_hash_unlock
  - kernel/kprobes.c:kretprobe_hash_lock
  - kernel/kprobes.c:get_optimized_kprobe
```
```
In kernel/trace/ftrace.c (ffffffff811aebfc)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:referenced_filters
  - kernel/trace/ftrace.c:find_direct_entry
  - kernel/trace/ftrace.c:ftrace_find_rec_direct
  - kernel/trace/ftrace.c:dup_hash
  - kernel/trace/ftrace.c:ftrace_lookup_ip
  - kernel/trace/ftrace.c:ftrace_profile_alloc
```
```
In kernel/bpf/trampoline.c (ffffffff8121ee9f)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - kernel/bpf/trampoline.c:bpf_trampoline_lookup
```
```
In kernel/events/core.c (ffffffff8123d5f3)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - kernel/events/core.c:perf_swevent_add
  - kernel/events/core.c:___perf_sw_event
```
```
In mm/filemap.c (ffffffff81252dfd)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_page_mkwrite
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:find_lock_entry
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:add_page_wait_queue
  - mm/filemap.c:put_and_wait_on_page_locked
  - mm/filemap.c:wake_up_page_bit
```
```
In mm/ksm.c (ffffffff812d6b4a)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - mm/ksm.c:__ksm_exit
  - mm/ksm.c:__ksm_enter
```
```
In mm/khugepaged.c (ffffffff812f12a1)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - mm/khugepaged.c:retract_page_tables
  - mm/khugepaged.c:__khugepaged_exit
  - mm/khugepaged.c:__khugepaged_enter
```
```
In fs/io_uring.c (ffffffff8137f298)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - fs/io_uring.c:__io_arm_poll_handler
```
```
In fs/io-wq.c (ffffffff8138b0e5)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - fs/io-wq.c:io_wq_hash_work
```
```
In fs/dax.c (ffffffff8138d30d)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - fs/dax.c:wait_entry_unlocked
  - fs/dax.c:get_unlocked_entry
  - fs/dax.c:dax_wake_entry
```
```
In fs/crypto/keysetup_v1.c (ffffffff8139437f)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:find_or_insert_direct_key
```
```
In fs/locks.c (ffffffff8139c645)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:__locks_insert_block
```
```
In fs/kernfs/dir.c (ffffffff813cd9d7)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_name_hash
```
```
In fs/jbd2/revoke.c (ffffffff81443724)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:find_revoke_record
  - fs/jbd2/revoke.c:insert_revoke_hash
```
```
In fs/fat/namei_vfat.c (ffffffff8145cdde)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - fs/fat/namei_vfat.c:vfat_hashi
```
```
In fs/ecryptfs/messaging.c (ffffffff8146a8e1)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - fs/ecryptfs/messaging.c:ecryptfs_spawn_daemon
  - fs/ecryptfs/messaging.c:ecryptfs_find_daemon_by_euid
```
```
In fs/fuse/dev.c (ffffffff8147152e)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_do_write
  - fs/fuse/dev.c:fuse_dev_do_read
```
```
In fs/efivarfs/super.c (ffffffff81485dcd)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - fs/efivarfs/super.c:efivarfs_d_hash
```
```
In security/tomoyo/memory.c (ffffffff814e737d)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - security/tomoyo/memory.c:tomoyo_get_name
```
```
In block/elevator.c (ffffffff815403b5)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - block/elevator.c:elv_rqhash_find
```
```
In block/keyslot-manager.c (ffffffff8158143b)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - block/keyslot-manager.c:blk_ksm_get_slot_for_key
```
```
In lib/vsprintf.c (ffffffff815f6b9f)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - lib/vsprintf.c:ptr_to_id
```
```
In net/core/bpf_sk_storage.c (ffffffff81a60995)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:selem_link_map
  - net/core/bpf_sk_storage.c:selem_unlink_map
```
```
In net/ipv4/udp.c (ffffffff81ad5ff6)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
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
In arch/x86/mm/kmmio.c (ffffffff81091ff0)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:add_kmmio_fault_page
  - arch/x86/mm/kmmio.c:get_kmmio_fault_page
```
```
In kernel/workqueue.c (ffffffff810c2a23)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - kernel/workqueue.c:work_busy
  - kernel/workqueue.c:process_one_work
  - kernel/workqueue.c:__queue_work
```
```
In kernel/ucount.c (ffffffff810d4c9f)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - kernel/ucount.c:get_ucounts
```
```
In kernel/sched/wait_bit.c (ffffffff810fde4e)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - kernel/sched/wait_bit.c:wake_up_var
  - kernel/sched/wait_bit.c:wake_up_bit
  - kernel/sched/wait_bit.c:out_of_line_wait_on_bit_lock
  - kernel/sched/wait_bit.c:out_of_line_wait_on_bit_timeout
  - kernel/sched/wait_bit.c:out_of_line_wait_on_bit
```
```
In kernel/locking/qspinlock.c (ffffffff8110cf39)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - kernel/locking/qspinlock.c:__pv_queued_spin_unlock_slowpath
  - kernel/locking/qspinlock.c:pv_hash
```
```
In kernel/livepatch/shadow.c (ffffffff81136658)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - kernel/livepatch/shadow.c:klp_shadow_free
  - kernel/livepatch/shadow.c:__klp_shadow_get_or_alloc
  - kernel/livepatch/shadow.c:klp_shadow_get
```
```
In kernel/cgroup/cgroup.c (ffffffff82fdfd4d)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/cgroup/cgroup.c:find_css_set
  - kernel/cgroup/cgroup.c:find_existing_css_set
```
```
In kernel/kprobes.c (ffffffff81193c68)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - kernel/kprobes.c:enable_kprobe
  - kernel/kprobes.c:get_optimized_kprobe
```
```
In kernel/trace/ftrace.c (ffffffff811ac4eb)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:referenced_filters
  - kernel/trace/ftrace.c:find_direct_entry
  - kernel/trace/ftrace.c:ftrace_find_rec_direct
  - kernel/trace/ftrace.c:dup_hash
  - kernel/trace/ftrace.c:ftrace_lookup_ip
  - kernel/trace/ftrace.c:ftrace_profile_alloc
```
```
In kernel/bpf/trampoline.c (ffffffff8122253d)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - kernel/bpf/trampoline.c:bpf_trampoline_lookup
```
```
In kernel/bpf/bpf_local_storage.c (ffffffff8122fc25)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - kernel/bpf/bpf_local_storage.c:bpf_selem_link_map
  - kernel/bpf/bpf_local_storage.c:bpf_selem_unlink_map
```
```
In kernel/events/core.c (ffffffff81247993)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - kernel/events/core.c:perf_swevent_add
```
```
In mm/filemap.c (ffffffff8125d9ca)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_page_mkwrite
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_buffered_read_pagenotuptodate
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:find_lock_entry
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:add_page_wait_queue
  - mm/filemap.c:put_and_wait_on_page_locked
  - mm/filemap.c:__wait_on_page_locked_async
  - mm/filemap.c:wake_up_page_bit
```
```
In mm/ksm.c (ffffffff812e268c)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - mm/ksm.c:__ksm_exit
  - mm/ksm.c:__ksm_enter
```
```
In mm/khugepaged.c (ffffffff812fc82a)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - mm/khugepaged.c:retract_page_tables
  - mm/khugepaged.c:__khugepaged_exit
  - mm/khugepaged.c:__khugepaged_enter
```
```
In fs/io_uring.c (ffffffff8138d376)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - fs/io_uring.c:__io_arm_poll_handler
```
```
In fs/io-wq.c (ffffffff8139c345)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - fs/io-wq.c:io_wq_hash_work
```
```
In fs/dax.c (ffffffff8139ea9d)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - fs/dax.c:wait_entry_unlocked
  - fs/dax.c:get_unlocked_entry
  - fs/dax.c:dax_wake_entry
```
```
In fs/crypto/keysetup_v1.c (ffffffff813a583f)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:find_or_insert_direct_key
```
```
In fs/locks.c (ffffffff813ae045)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:__locks_insert_block
```
```
In fs/kernfs/dir.c (ffffffff813df607)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_name_hash
```
```
In fs/jbd2/revoke.c (ffffffff8145f804)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:find_revoke_record
  - fs/jbd2/revoke.c:insert_revoke_hash
```
```
In fs/fat/namei_vfat.c (ffffffff81478ace)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - fs/fat/namei_vfat.c:vfat_hashi
```
```
In fs/ecryptfs/messaging.c (ffffffff81485351)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - fs/ecryptfs/messaging.c:ecryptfs_spawn_daemon
  - fs/ecryptfs/messaging.c:ecryptfs_find_daemon_by_euid
```
```
In fs/unicode/utf8-core.c (ffffffff814882d4)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - fs/unicode/utf8-core.c:utf8_casefold_hash
```
```
In fs/fuse/dev.c (ffffffff8148bdbe)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_do_write
  - fs/fuse/dev.c:fuse_dev_do_read
```
```
In fs/efivarfs/super.c (ffffffff814a33bd)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - fs/efivarfs/super.c:efivarfs_d_hash
```
```
In security/tomoyo/memory.c (ffffffff8150474d)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - security/tomoyo/memory.c:tomoyo_get_name
```
```
In block/elevator.c (ffffffff8155cb55)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - block/elevator.c:elv_rqhash_find
```
```
In block/keyslot-manager.c (ffffffff8159e46b)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - block/keyslot-manager.c:blk_ksm_get_slot_for_key
```
```
In lib/vsprintf.c (ffffffff8161bbbf)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - lib/vsprintf.c:ptr_to_id
```
```
In net/ipv4/udp.c (ffffffff81ae25d6)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
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
In arch/x86/mm/kmmio.c (ffffffff81092ba8)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:register_kmmio_probe
  - arch/x86/mm/kmmio.c:get_kmmio_fault_page
```
```
In kernel/workqueue.c (ffffffff810c4841)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - kernel/workqueue.c:work_busy
  - kernel/workqueue.c:process_one_work
  - kernel/workqueue.c:__queue_work
```
```
In kernel/ucount.c (ffffffff831e5520)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - kernel/ucount.c:user_namespace_sysctl_init
  - kernel/ucount.c:alloc_ucounts
```
```
In kernel/sched/wait_bit.c (ffffffff8110022e)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - kernel/sched/wait_bit.c:wake_up_var
  - kernel/sched/wait_bit.c:wake_up_bit
  - kernel/sched/wait_bit.c:out_of_line_wait_on_bit_lock
  - kernel/sched/wait_bit.c:out_of_line_wait_on_bit_timeout
  - kernel/sched/wait_bit.c:out_of_line_wait_on_bit
```
```
In kernel/locking/qspinlock.c (ffffffff8110ed2c)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - kernel/locking/qspinlock.c:__pv_queued_spin_unlock_slowpath
  - kernel/locking/qspinlock.c:pv_hash
```
```
In kernel/livepatch/shadow.c (ffffffff81137456)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - kernel/livepatch/shadow.c:klp_shadow_free
  - kernel/livepatch/shadow.c:__klp_shadow_get_or_alloc
  - kernel/livepatch/shadow.c:klp_shadow_get
```
```
In kernel/cgroup/cgroup.c (ffffffff831ea95f)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/cgroup/cgroup.c:find_css_set
  - kernel/cgroup/cgroup.c:find_existing_css_set
```
```
In kernel/kprobes.c (ffffffff81194c48)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - kernel/kprobes.c:enable_kprobe
  - kernel/kprobes.c:get_optimized_kprobe
```
```
In kernel/trace/ftrace.c (ffffffff811ad05a)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:referenced_filters
  - kernel/trace/ftrace.c:find_direct_entry
  - kernel/trace/ftrace.c:ftrace_find_rec_direct
  - kernel/trace/ftrace.c:dup_hash
  - kernel/trace/ftrace.c:ftrace_lookup_ip
```
```
In kernel/bpf/bpf_local_storage.c (ffffffff812251e5)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - kernel/bpf/bpf_local_storage.c:bpf_selem_link_map
  - kernel/bpf/bpf_local_storage.c:bpf_selem_unlink_map
```
```
In kernel/bpf/trampoline.c (ffffffff81226fc2)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - kernel/bpf/trampoline.c:bpf_trampoline_get
```
```
In kernel/events/core.c (ffffffff8124b83d)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - kernel/events/core.c:perf_swevent_add
  - kernel/events/core.c:___perf_sw_event
```
```
In mm/filemap.c (ffffffff8126071c)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_page_mkwrite
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:mapping_seek_hole_data
  - mm/filemap.c:filemap_update_page
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:__lock_page_async
  - mm/filemap.c:wait_on_page_private_2_killable
  - mm/filemap.c:wait_on_page_private_2
  - mm/filemap.c:add_page_wait_queue
  - mm/filemap.c:wake_up_page_bit
```
```
In mm/ksm.c (ffffffff812e9e1c)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - mm/ksm.c:__ksm_exit
  - mm/ksm.c:__ksm_enter
```
```
In mm/khugepaged.c (ffffffff81303597)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - mm/khugepaged.c:retract_page_tables
  - mm/khugepaged.c:__khugepaged_exit
  - mm/khugepaged.c:__khugepaged_enter
```
```
In fs/notify/fanotify/fanotify.c (ffffffff8137e7f2)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
```
```
In fs/io_uring.c (ffffffff81397b00)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - fs/io_uring.c:__io_arm_poll_handler
```
```
In fs/io-wq.c (ffffffff813a3495)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - fs/io-wq.c:io_wq_hash_work
```
```
In fs/dax.c (ffffffff813a5b8d)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - fs/dax.c:wait_entry_unlocked
  - fs/dax.c:get_unlocked_entry
  - fs/dax.c:dax_wake_entry
```
```
In fs/crypto/keysetup_v1.c (ffffffff813ac89f)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:find_or_insert_direct_key
```
```
In fs/locks.c (ffffffff813b5583)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:__locks_insert_block
```
```
In fs/kernfs/dir.c (ffffffff813e62a7)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_name_hash
```
```
In fs/jbd2/revoke.c (ffffffff81464ef4)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:find_revoke_record
  - fs/jbd2/revoke.c:insert_revoke_hash
```
```
In fs/fat/namei_vfat.c (ffffffff8147e539)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - fs/fat/namei_vfat.c:vfat_hashi
```
```
In fs/ecryptfs/messaging.c (ffffffff8148ac71)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - fs/ecryptfs/messaging.c:ecryptfs_spawn_daemon
  - fs/ecryptfs/messaging.c:ecryptfs_find_daemon_by_euid
```
```
In fs/unicode/utf8-core.c (ffffffff8148dcb4)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - fs/unicode/utf8-core.c:utf8_casefold_hash
```
```
In fs/fuse/dev.c (ffffffff814916c0)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_do_write
  - fs/fuse/dev.c:fuse_dev_do_read
```
```
In fs/efivarfs/super.c (ffffffff814a93dc)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - fs/efivarfs/super.c:efivarfs_d_hash
```
```
In security/tomoyo/memory.c (ffffffff8150b2cd)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - security/tomoyo/memory.c:tomoyo_get_name
```
```
In block/elevator.c (ffffffff815653e5)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - block/elevator.c:elv_rqhash_find
```
```
In block/keyslot-manager.c (ffffffff815a524d)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - block/keyslot-manager.c:blk_ksm_get_slot_for_key
```
```
In lib/vsprintf.c (ffffffff815ff45d)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - lib/vsprintf.c:ptr_to_id
```
```
In net/ipv4/route.c (ffffffff81a85965)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - net/ipv4/route.c:fnhe_hashfun
```
```
In net/ipv4/udp.c (ffffffff81acd4f6)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
```
```
In net/ipv6/route.c (ffffffff81b3d832)
Location: include/linux/hash.h:77
Inline: True
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
In arch/x86/mm/kmmio.c (ffffffff810a21fe)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:kmmio_page_list
```
```
In kernel/workqueue.c (ffffffff810d7461)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - kernel/workqueue.c:work_busy
  - kernel/workqueue.c:process_one_work
  - kernel/workqueue.c:__queue_work
```
```
In kernel/ucount.c (ffffffff832c93f8)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - kernel/ucount.c:user_namespace_sysctl_init
  - kernel/ucount.c:alloc_ucounts
```
```
In kernel/sched/wait_bit.c (ffffffff8111c2ce)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - kernel/sched/wait_bit.c:wake_up_var
  - kernel/sched/wait_bit.c:wake_up_bit
  - kernel/sched/wait_bit.c:out_of_line_wait_on_bit_lock
  - kernel/sched/wait_bit.c:out_of_line_wait_on_bit_timeout
  - kernel/sched/wait_bit.c:out_of_line_wait_on_bit
```
```
In kernel/locking/qspinlock.c (ffffffff8112e58a)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - kernel/locking/qspinlock.c:__pv_queued_spin_unlock_slowpath
  - kernel/locking/qspinlock.c:pv_hash
```
```
In kernel/livepatch/shadow.c (ffffffff8115a106)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - kernel/livepatch/shadow.c:klp_shadow_free
  - kernel/livepatch/shadow.c:__klp_shadow_get_or_alloc
  - kernel/livepatch/shadow.c:klp_shadow_get
```
```
In kernel/cgroup/cgroup.c (ffffffff832cf154)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/cgroup/cgroup.c:find_css_set
  - kernel/cgroup/cgroup.c:find_existing_css_set
```
```
In kernel/kprobes.c (ffffffff811bdb08)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - kernel/kprobes.c:enable_kprobe
  - kernel/kprobes.c:get_optimized_kprobe
```
```
In kernel/trace/ftrace.c (ffffffff811d6def)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:referenced_filters
  - kernel/trace/ftrace.c:find_direct_entry
  - kernel/trace/ftrace.c:ftrace_find_rec_direct
  - kernel/trace/ftrace.c:hash_contains_ip
  - kernel/trace/ftrace.c:hash_contains_ip
  - kernel/trace/ftrace.c:dup_hash
  - kernel/trace/ftrace.c:ftrace_lookup_ip
```
```
In kernel/bpf/bpf_local_storage.c (ffffffff8125d1aa)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - kernel/bpf/bpf_local_storage.c:bpf_selem_link_map
  - kernel/bpf/bpf_local_storage.c:bpf_selem_unlink_map
```
```
In kernel/bpf/trampoline.c (ffffffff8125f0c2)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - kernel/bpf/trampoline.c:bpf_trampoline_get
```
```
In kernel/events/core.c (ffffffff81284d6d)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - kernel/events/core.c:perf_swevent_add
  - kernel/events/core.c:___perf_sw_event
```
```
In mm/filemap.c (ffffffff8129d10e)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_page_mkwrite
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:mapping_seek_hole_data
  - mm/filemap.c:filemap_update_page
  - mm/filemap.c:pagecache_get_page
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:__lock_page_async
  - mm/filemap.c:wait_on_page_private_2_killable
  - mm/filemap.c:wait_on_page_private_2
  - mm/filemap.c:add_page_wait_queue
  - mm/filemap.c:wake_up_page_bit
```
```
In mm/ksm.c (ffffffff81331d4c)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - mm/ksm.c:__ksm_exit
  - mm/ksm.c:__ksm_enter
```
```
In mm/khugepaged.c (ffffffff8134d301)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - mm/khugepaged.c:retract_page_tables
  - mm/khugepaged.c:__khugepaged_exit
  - mm/khugepaged.c:__khugepaged_enter
```
```
In fs/notify/fanotify/fanotify.c (ffffffff813cb8d2)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
```
```
In fs/io_uring.c (ffffffff813e4748)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - fs/io_uring.c:__io_arm_poll_handler
```
```
In fs/io-wq.c (ffffffff813f2975)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - fs/io-wq.c:io_wq_hash_work
```
```
In fs/dax.c (ffffffff813f55fd)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - fs/dax.c:wait_entry_unlocked
  - fs/dax.c:get_unlocked_entry
  - fs/dax.c:dax_wake_entry
```
```
In fs/crypto/keysetup_v1.c (ffffffff813fc210)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:find_or_insert_direct_key
```
```
In fs/locks.c (ffffffff8140527e)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:__locks_insert_block
```
```
In fs/kernfs/dir.c (ffffffff81437ea7)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_name_hash
```
```
In fs/jbd2/revoke.c (ffffffff814ba86b)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:find_revoke_record
  - fs/jbd2/revoke.c:insert_revoke_hash
```
```
In fs/fat/namei_vfat.c (ffffffff814d5ce9)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - fs/fat/namei_vfat.c:vfat_hashi
```
```
In fs/ecryptfs/messaging.c (ffffffff814e2495)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - fs/ecryptfs/messaging.c:ecryptfs_spawn_daemon
  - fs/ecryptfs/messaging.c:ecryptfs_find_daemon_by_euid
```
```
In fs/unicode/utf8-core.c (ffffffff814e5724)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - fs/unicode/utf8-core.c:utf8_casefold_hash
```
```
In fs/fuse/dev.c (ffffffff814e9174)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_do_write
  - fs/fuse/dev.c:fuse_dev_do_read
```
```
In fs/efivarfs/super.c (ffffffff8150176c)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - fs/efivarfs/super.c:efivarfs_d_hash
```
```
In security/tomoyo/memory.c (ffffffff81568add)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - security/tomoyo/memory.c:tomoyo_get_name
```
```
In block/elevator.c (ffffffff815c9785)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - block/elevator.c:elv_rqhash_find
```
```
In block/keyslot-manager.c (ffffffff8160dd03)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - block/keyslot-manager.c:blk_ksm_get_slot_for_key
```
```
In lib/vsprintf.c (ffffffff8166d1cd)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - lib/vsprintf.c:ptr_to_id
```
```
In net/ipv4/route.c (ffffffff81b40172)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - net/ipv4/route.c:fnhe_hashfun
```
```
In net/ipv4/udp.c (ffffffff81b8bee0)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
```
```
In net/ipv6/route.c (ffffffff81c0408f)
Location: include/linux/hash.h:77
Inline: True
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
In arch/x86/mm/kmmio.c (ffffffff810b6785)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:kmmio_page_list
```
```
In kernel/workqueue.c (ffffffff810f0b46)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - kernel/workqueue.c:work_busy
  - kernel/workqueue.c:process_one_work
  - kernel/workqueue.c:__queue_work
```
```
In kernel/ucount.c (ffffffff8347c5e7)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - kernel/ucount.c:user_namespace_sysctl_init
  - kernel/ucount.c:alloc_ucounts
```
```
In kernel/sched/build_utility.c (ffffffff81141d4d)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:wake_up_var
  - kernel/sched/build_utility.c:wake_up_bit
  - kernel/sched/build_utility.c:out_of_line_wait_on_bit_lock
  - kernel/sched/build_utility.c:out_of_line_wait_on_bit_timeout
  - kernel/sched/build_utility.c:out_of_line_wait_on_bit
```
```
In kernel/locking/qspinlock.c (ffffffff8114f79a)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - kernel/locking/qspinlock.c:__pv_queued_spin_unlock_slowpath
  - kernel/locking/qspinlock.c:pv_hash
```
```
In kernel/livepatch/shadow.c (ffffffff81183596)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - kernel/livepatch/shadow.c:klp_shadow_free
  - kernel/livepatch/shadow.c:__klp_shadow_get_or_alloc
  - kernel/livepatch/shadow.c:__klp_shadow_get_or_alloc
```
```
In kernel/cgroup/cgroup.c (ffffffff83482e99)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/cgroup/cgroup.c:find_css_set
  - kernel/cgroup/cgroup.c:find_existing_css_set
```
```
In kernel/kprobes.c (ffffffff811f1bd4)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - kernel/kprobes.c:register_kprobe
  - kernel/kprobes.c:register_kprobe
  - kernel/kprobes.c:__get_valid_kprobe
  - kernel/kprobes.c:get_optimized_kprobe
```
```
In kernel/trace/ftrace.c (ffffffff8120c102)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:referenced_filters
  - kernel/trace/ftrace.c:modify_ftrace_direct_multi
  - kernel/trace/ftrace.c:remove_direct_functions_hash
  - kernel/trace/ftrace.c:find_direct_entry
  - kernel/trace/ftrace.c:ftrace_find_rec_direct
  - kernel/trace/ftrace.c:hash_contains_ip
  - kernel/trace/ftrace.c:hash_contains_ip
  - kernel/trace/ftrace.c:dup_hash
  - kernel/trace/ftrace.c:ftrace_lookup_ip
  - kernel/trace/ftrace.c:profile_graph_return
```
```
In kernel/bpf/bpf_local_storage.c (ffffffff812a730a)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - kernel/bpf/bpf_local_storage.c:bpf_selem_link_map
  - kernel/bpf/bpf_local_storage.c:bpf_selem_unlink_map
```
```
In kernel/bpf/trampoline.c (ffffffff812a9702)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - kernel/bpf/trampoline.c:bpf_trampoline_get
```
```
In kernel/events/core.c (ffffffff812d92b6)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - kernel/events/core.c:perf_swevent_add
  - kernel/events/core.c:___perf_sw_event
```
```
In mm/filemap.c (ffffffff812f4154)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_folio
  - mm/filemap.c:filemap_update_page
  - mm/filemap.c:__folio_lock_or_retry
  - mm/filemap.c:__folio_lock_or_retry
  - mm/filemap.c:folio_wait_private_2_killable
  - mm/filemap.c:folio_wait_private_2
  - mm/filemap.c:folio_add_wait_queue
  - mm/filemap.c:migration_entry_wait_on_locked
  - mm/filemap.c:folio_wake_bit
```
```
In mm/ksm.c (ffffffff813a2edb)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - mm/ksm.c:__ksm_exit
  - mm/ksm.c:__ksm_enter
```
```
In mm/khugepaged.c (ffffffff813c3d4e)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - mm/khugepaged.c:retract_page_tables
  - mm/khugepaged.c:__khugepaged_exit
  - mm/khugepaged.c:__khugepaged_enter
```
```
In fs/notify/fanotify/fanotify.c (ffffffff8145400b)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
```
```
In fs/dax.c (ffffffff81467736)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - fs/dax.c:wait_entry_unlocked
  - fs/dax.c:get_unlocked_entry
  - fs/dax.c:dax_wake_entry
```
```
In fs/crypto/keysetup_v1.c (ffffffff8146f68f)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:find_or_insert_direct_key
```
```
In fs/locks.c (ffffffff81478f6a)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:__locks_insert_block
```
```
In fs/kernfs/dir.c (ffffffff814b2c49)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_name_hash
```
```
In fs/jbd2/revoke.c (ffffffff815446eb)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:find_revoke_record
  - fs/jbd2/revoke.c:insert_revoke_hash
```
```
In fs/fat/namei_vfat.c (ffffffff81562e09)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - fs/fat/namei_vfat.c:vfat_hashi
```
```
In fs/ecryptfs/messaging.c (ffffffff81570725)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - fs/ecryptfs/messaging.c:ecryptfs_spawn_daemon
  - fs/ecryptfs/messaging.c:ecryptfs_find_daemon_by_euid
```
```
In fs/unicode/utf8-core.c (ffffffff81573701)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - fs/unicode/utf8-core.c:utf8_casefold_hash
```
```
In fs/fuse/dev.c (ffffffff81577906)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_do_write
  - fs/fuse/dev.c:fuse_dev_do_read
```
```
In fs/efivarfs/super.c (ffffffff81592b4e)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - fs/efivarfs/super.c:efivarfs_d_hash
```
```
In security/tomoyo/memory.c (ffffffff816047fc)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - security/tomoyo/memory.c:tomoyo_get_name
```
```
In block/elevator.c (ffffffff81674a15)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - block/elevator.c:elv_rqhash_find
```
```
In block/blk-crypto-profile.c (ffffffff816c27b5)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - block/blk-crypto-profile.c:blk_crypto_get_keyslot
```
```
In io_uring/io_uring.c (ffffffff816ce8e2)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - io_uring/io_uring.c:__io_arm_poll_handler
```
```
In io_uring/io-wq.c (ffffffff816db505)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - io_uring/io-wq.c:io_wq_hash_work
```
```
In lib/vsprintf.c (ffffffff817874c0)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - lib/vsprintf.c:default_pointer
```
```
In net/ipv4/route.c (ffffffff81cccaef)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - net/ipv4/route.c:fnhe_hashfun
```
```
In net/ipv4/udp.c (ffffffff81d18b8a)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
```
```
In net/ipv6/route.c (ffffffff81d9e32f)
Location: include/linux/hash.h:74
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
In arch/x86/mm/kmmio.c (ffffffff810d19a5)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:kmmio_page_list
```
```
In kernel/workqueue.c (ffffffff811127f6)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - kernel/workqueue.c:work_busy
  - kernel/workqueue.c:process_one_work
  - kernel/workqueue.c:__queue_work
```
```
In kernel/ucount.c (ffffffff83ea799c)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - kernel/ucount.c:user_namespace_sysctl_init
  - kernel/ucount.c:alloc_ucounts
```
```
In kernel/sched/build_utility.c (ffffffff8116ca3d)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:wake_up_var
  - kernel/sched/build_utility.c:wake_up_bit
  - kernel/sched/build_utility.c:out_of_line_wait_on_bit_lock
  - kernel/sched/build_utility.c:out_of_line_wait_on_bit_timeout
  - kernel/sched/build_utility.c:out_of_line_wait_on_bit
```
```
In kernel/locking/qspinlock.c (ffffffff820d6a7a)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - kernel/locking/qspinlock.c:__pv_queued_spin_unlock_slowpath
  - kernel/locking/qspinlock.c:pv_hash
```
```
In kernel/livepatch/shadow.c (ffffffff811be726)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - kernel/livepatch/shadow.c:klp_shadow_free
  - kernel/livepatch/shadow.c:__klp_shadow_get_or_alloc
  - kernel/livepatch/shadow.c:__klp_shadow_get_or_alloc
```
```
In kernel/cgroup/cgroup.c (ffffffff83eb06c7)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/cgroup/cgroup.c:find_css_set
  - kernel/cgroup/cgroup.c:find_existing_css_set
```
```
In kernel/kprobes.c (ffffffff81238883)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - kernel/kprobes.c:register_kprobe
  - kernel/kprobes.c:register_kprobe
  - kernel/kprobes.c:__get_valid_kprobe
  - kernel/kprobes.c:get_optimized_kprobe
```
```
In kernel/trace/ftrace.c (ffffffff81254b65)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ops_references_ip
  - kernel/trace/ftrace.c:remove_direct_functions_hash
  - kernel/trace/ftrace.c:find_direct_entry
  - kernel/trace/ftrace.c:ftrace_find_rec_direct
  - kernel/trace/ftrace.c:hash_contains_ip
  - kernel/trace/ftrace.c:hash_contains_ip
  - kernel/trace/ftrace.c:dup_hash
  - kernel/trace/ftrace.c:ftrace_lookup_ip
  - kernel/trace/ftrace.c:profile_graph_return
```
```
In kernel/bpf/bpf_local_storage.c (ffffffff813059ea)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - kernel/bpf/bpf_local_storage.c:bpf_selem_link_map
  - kernel/bpf/bpf_local_storage.c:bpf_selem_unlink_map
```
```
In kernel/bpf/trampoline.c (ffffffff8130859d)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - kernel/bpf/trampoline.c:bpf_trampoline_lookup
```
```
In kernel/events/core.c (ffffffff81341786)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - kernel/events/core.c:perf_swevent_add
  - kernel/events/core.c:___perf_sw_event
```
```
In mm/filemap.c (ffffffff8135c988)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - mm/filemap.c:filemap_update_page
  - mm/filemap.c:folio_add_wait_queue
  - mm/filemap.c:migration_entry_wait_on_locked
  - mm/filemap.c:folio_wait_bit_common
  - mm/filemap.c:folio_wake_bit
```
```
In mm/vmscan.c (ffffffff8137fa57)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - mm/vmscan.c:walk_pmd_range
  - mm/vmscan.c:update_bloom_filter
```
```
In mm/ksm.c (ffffffff81422b5b)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - mm/ksm.c:__ksm_exit
  - mm/ksm.c:__ksm_enter
```
```
In mm/khugepaged.c (ffffffff81444bfe)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_add_pte_mapped_thp
  - mm/khugepaged.c:__khugepaged_exit
  - mm/khugepaged.c:__khugepaged_enter
```
```
In fs/notify/fanotify/fanotify.c (ffffffff814e2ebb)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
```
```
In fs/dax.c (ffffffff814f7a46)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - fs/dax.c:wait_entry_unlocked
  - fs/dax.c:get_unlocked_entry
  - fs/dax.c:dax_wake_entry
```
```
In fs/crypto/keysetup_v1.c (ffffffff81500e20)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:find_or_insert_direct_key
```
```
In fs/locks.c (ffffffff8150b89a)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:__locks_insert_block
```
```
In fs/kernfs/dir.c (ffffffff81549878)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_name_hash
```
```
In fs/kernfs/file.c (ffffffff8154d8f5)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - fs/kernfs/file.c:kernfs_drain_open_files
  - fs/kernfs/file.c:kernfs_fop_release
  - fs/kernfs/file.c:kernfs_fop_open
  - fs/kernfs/file.c:kernfs_unlink_open_file
```
```
In fs/jbd2/revoke.c (ffffffff815e374b)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:find_revoke_record
  - fs/jbd2/revoke.c:insert_revoke_hash
```
```
In fs/fat/namei_vfat.c (ffffffff816058d9)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - fs/fat/namei_vfat.c:vfat_hashi
```
```
In fs/ecryptfs/messaging.c (ffffffff81615665)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - fs/ecryptfs/messaging.c:ecryptfs_spawn_daemon
  - fs/ecryptfs/messaging.c:ecryptfs_find_daemon_by_euid
```
```
In fs/unicode/utf8-core.c (ffffffff81618cf1)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - fs/unicode/utf8-core.c:utf8_casefold_hash
```
```
In fs/fuse/dev.c (ffffffff8161ce26)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_do_write
  - fs/fuse/dev.c:fuse_dev_do_read
```
```
In fs/efivarfs/super.c (ffffffff8163a57e)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - fs/efivarfs/super.c:efivarfs_d_hash
```
```
In security/tomoyo/memory.c (ffffffff816b5aec)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - security/tomoyo/memory.c:tomoyo_get_name
```
```
In block/elevator.c (ffffffff81730755)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - block/elevator.c:elv_rqhash_find
```
```
In block/blk-crypto-profile.c (ffffffff81783b15)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - block/blk-crypto-profile.c:blk_crypto_get_keyslot
```
```
In io_uring/poll.c (ffffffff8179c853)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - io_uring/poll.c:io_poll_add_hash
  - io_uring/poll.c:io_poll_add_hash
  - io_uring/poll.c:io_poll_task_func
```
```
In io_uring/io-wq.c (ffffffff817a75e5)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - io_uring/io-wq.c:io_wq_hash_work
```
```
In net/ipv4/route.c (ffffffff81e8c9df)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - net/ipv4/route.c:fnhe_hashfun
```
```
In net/ipv4/udp.c (ffffffff81ee1a4d)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
```
```
In net/ipv6/route.c (ffffffff81f6d1df)
Location: include/linux/hash.h:74
Inline: True
```
```
In lib/vsprintf.c (ffffffff82044648)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - lib/vsprintf.c:default_pointer
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
In arch/x86/mm/kmmio.c (ffffffff810d4e55)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:kmmio_page_list
```
```
In kernel/workqueue.c (ffffffff8111edf6)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - kernel/workqueue.c:work_busy
  - kernel/workqueue.c:process_one_work
  - kernel/workqueue.c:__queue_work
  - kernel/workqueue.c:wq_cpu_intensive_report
```
```
In kernel/ucount.c (ffffffff836cc30c)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - kernel/ucount.c:user_namespace_sysctl_init
  - kernel/ucount.c:alloc_ucounts
```
```
In kernel/sched/build_utility.c (ffffffff8117d29d)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:wake_up_var
  - kernel/sched/build_utility.c:wake_up_bit
  - kernel/sched/build_utility.c:out_of_line_wait_on_bit_lock
  - kernel/sched/build_utility.c:out_of_line_wait_on_bit_timeout
  - kernel/sched/build_utility.c:out_of_line_wait_on_bit
```
```
In kernel/locking/qspinlock.c (ffffffff82159e61)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - kernel/locking/qspinlock.c:__pv_queued_spin_unlock_slowpath
  - kernel/locking/qspinlock.c:pv_hash
```
```
In kernel/livepatch/shadow.c (ffffffff811d1156)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - kernel/livepatch/shadow.c:klp_shadow_free
  - kernel/livepatch/shadow.c:__klp_shadow_get_or_alloc
  - kernel/livepatch/shadow.c:__klp_shadow_get_or_alloc
```
```
In kernel/module/main.c (ffffffff811e0562)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - kernel/module/main.c:idempotent_init_module
  - kernel/module/main.c:idempotent_init_module
```
```
In kernel/cgroup/cgroup.c (ffffffff836d56b7)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/cgroup/cgroup.c:find_css_set
  - kernel/cgroup/cgroup.c:find_existing_css_set
```
```
In kernel/kprobes.c (ffffffff8124f9e3)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - kernel/kprobes.c:register_kprobe
  - kernel/kprobes.c:register_kprobe
  - kernel/kprobes.c:__get_valid_kprobe
  - kernel/kprobes.c:get_optimized_kprobe
```
```
In kernel/trace/ftrace.c (ffffffff8126be85)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ops_references_ip
  - kernel/trace/ftrace.c:remove_direct_functions_hash
  - kernel/trace/ftrace.c:ftrace_find_rec_direct
  - kernel/trace/ftrace.c:hash_contains_ip
  - kernel/trace/ftrace.c:hash_contains_ip
  - kernel/trace/ftrace.c:dup_hash
  - kernel/trace/ftrace.c:ftrace_lookup_ip
  - kernel/trace/ftrace.c:profile_graph_return
```
```
In kernel/bpf/bpf_local_storage.c (ffffffff813346ca)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - kernel/bpf/bpf_local_storage.c:bpf_selem_link_map
  - kernel/bpf/bpf_local_storage.c:bpf_selem_unlink_map
```
```
In kernel/bpf/trampoline.c (ffffffff8133737d)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - kernel/bpf/trampoline.c:bpf_trampoline_lookup
```
```
In kernel/events/core.c (ffffffff81372766)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - kernel/events/core.c:perf_swevent_add
  - kernel/events/core.c:___perf_sw_event
```
```
In mm/filemap.c (ffffffff8138e9b8)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - mm/filemap.c:filemap_update_page
  - mm/filemap.c:folio_add_wait_queue
  - mm/filemap.c:migration_entry_wait_on_locked
  - mm/filemap.c:folio_wait_bit_common
  - mm/filemap.c:folio_wake_bit
```
```
In mm/vmscan.c (ffffffff813b0fdc)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - mm/vmscan.c:walk_pmd_range
  - mm/vmscan.c:update_bloom_filter
```
```
In mm/ksm.c (ffffffff81457b6b)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - mm/ksm.c:__ksm_exit
  - mm/ksm.c:__ksm_enter
```
```
In mm/khugepaged.c (ffffffff8147a234)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_add_pte_mapped_thp
  - mm/khugepaged.c:__khugepaged_exit
  - mm/khugepaged.c:__khugepaged_enter
```
```
In fs/notify/fanotify/fanotify.c (ffffffff815196b0)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
```
```
In fs/dax.c (ffffffff8152e896)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - fs/dax.c:wait_entry_unlocked
  - fs/dax.c:get_unlocked_entry
  - fs/dax.c:dax_wake_entry
```
```
In fs/crypto/keysetup_v1.c (ffffffff815384b0)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:find_or_insert_direct_key
```
```
In fs/locks.c (ffffffff81542ffa)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:__locks_insert_block
```
```
In fs/kernfs/dir.c (ffffffff81581448)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_name_hash
```
```
In fs/kernfs/file.c (ffffffff81585595)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - fs/kernfs/file.c:kernfs_drain_open_files
  - fs/kernfs/file.c:kernfs_fop_release
  - fs/kernfs/file.c:kernfs_fop_open
  - fs/kernfs/file.c:kernfs_unlink_open_file
```
```
In fs/jbd2/revoke.c (ffffffff8161af0b)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:find_revoke_record
  - fs/jbd2/revoke.c:insert_revoke_hash
```
```
In fs/fat/namei_vfat.c (ffffffff8163d7e9)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - fs/fat/namei_vfat.c:vfat_hashi
```
```
In fs/ecryptfs/messaging.c (ffffffff8164d6f5)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - fs/ecryptfs/messaging.c:ecryptfs_spawn_daemon
  - fs/ecryptfs/messaging.c:ecryptfs_find_daemon_by_euid
```
```
In fs/unicode/utf8-core.c (ffffffff81650db1)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - fs/unicode/utf8-core.c:utf8_casefold_hash
```
```
In fs/fuse/dev.c (ffffffff81654f86)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_do_write
  - fs/fuse/dev.c:fuse_dev_do_read
```
```
In fs/efivarfs/super.c (ffffffff816729de)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - fs/efivarfs/super.c:efivarfs_d_hash
```
```
In security/tomoyo/memory.c (ffffffff816ee4cc)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - security/tomoyo/memory.c:tomoyo_get_name
```
```
In block/elevator.c (ffffffff8176c9c4)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - block/elevator.c:elv_rqhash_find
```
```
In block/blk-crypto-profile.c (ffffffff817c3e05)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - block/blk-crypto-profile.c:blk_crypto_get_keyslot
```
```
In io_uring/poll.c (ffffffff817dd813)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - io_uring/poll.c:io_poll_add_hash
  - io_uring/poll.c:io_poll_add_hash
  - io_uring/poll.c:io_poll_task_func
```
```
In io_uring/io-wq.c (ffffffff817e8635)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - io_uring/io-wq.c:io_wq_hash_work
```
```
In net/ipv4/route.c (ffffffff81eeb10f)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - net/ipv4/route.c:fnhe_hashfun
```
```
In net/ipv4/udp.c (ffffffff81f4144e)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
```
```
In net/ipv6/route.c (ffffffff81fcd2ff)
Location: include/linux/hash.h:74
Inline: True
```
```
In lib/vsprintf.c (ffffffff820c2c30)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - lib/vsprintf.c:default_pointer
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
In init/main.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In init/initramfs.c (ffffffff838b2e4a)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - init/initramfs.c:unpack_to_rootfs
  - init/initramfs.c:unpack_to_rootfs
  - init/initramfs.c:find_link
```
```
In arch/x86/events/core.c (ffffffff8100c4be)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - arch/x86/events/core.c:allocate_fake_cpuc
```
```
In arch/x86/events/amd/core.c (ffffffff81010f57)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_pmu_cpu_prepare
  - arch/x86/events/amd/core.c:amd_pmu_cpu_prepare
```
```
In arch/x86/events/amd/iommu.c (ffffffff838b541e)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - arch/x86/events/amd/iommu.c:init_one_iommu
```
```
In arch/x86/events/intel/core.c (ffffffff838b6684)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_init
  - arch/x86/events/intel/core.c:intel_pmu_init
  - arch/x86/events/intel/core.c:intel_cpuc_prepare
  - arch/x86/events/intel/core.c:intel_cpuc_prepare
  - arch/x86/events/intel/core.c:intel_cpuc_prepare
```
```
In arch/x86/events/intel/bts.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In arch/x86/events/intel/ds.c (ffffffff8101d804)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:alloc_pebs_buffer
```
```
In arch/x86/events/intel/pt.c (ffffffff81025fdb)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - arch/x86/events/intel/pt.c:pt_addr_filters_init
  - arch/x86/events/intel/pt.c:pt_buffer_setup_aux
  - arch/x86/events/intel/pt.c:pt_pmu_hw_init
  - arch/x86/events/intel/pt.c:pt_pmu_hw_init
```
```
In arch/x86/events/intel/uncore.c (ffffffff8102ab09)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore.c:__find_pci2phy_map
```
```
In arch/x86/events/intel/uncore_snbep.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In arch/x86/events/intel/uncore_discovery.c (ffffffff81036e2e)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - arch/x86/events/intel/uncore_discovery.c:intel_uncore_generic_init_uncores
  - arch/x86/events/intel/uncore_discovery.c:uncore_insert_box_info
```
```
In arch/x86/xen/grant-table.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In arch/x86/xen/smp_pv.c (ffffffff8104a288)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - arch/x86/xen/smp_pv.c:cpu_initialize_context
```
```
In arch/x86/hyperv/hv_init.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In arch/x86/hyperv/irqdomain.c (ffffffff8104e611)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - arch/x86/hyperv/irqdomain.c:hv_irq_compose_msi_msg
```
```
In arch/x86/hyperv/ivm.c (ffffffff8104fa3e)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - arch/x86/hyperv/ivm.c:hv_vtom_set_host_visibility
```
```
In arch/x86/hyperv/hv_proc.c (ffffffff81050a41)
Location: include/linux/hash.h:74
Inline: True
```
```
In arch/x86/kernel/ioport.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In arch/x86/kernel/ldt.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In arch/x86/kernel/ksysfs.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In arch/x86/kernel/alternative.c (ffffffff81062165)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:alternatives_smp_module_add
```
```
In arch/x86/kernel/tboot.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In arch/x86/kernel/cpu/cacheinfo.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In arch/x86/kernel/cpu/mce/core.c (ffffffff810808b0)
Location: include/linux/hash.h:74
Inline: True
```
```
In arch/x86/kernel/cpu/mce/amd.c (ffffffff81085825)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/mce/amd.c:threshold_create_bank
  - arch/x86/kernel/cpu/mce/amd.c:allocate_threshold_blocks
```
```
In arch/x86/kernel/cpu/mce/dev-mcelog.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In arch/x86/kernel/cpu/mtrr/if.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In arch/x86/kernel/cpu/mtrr/generic.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff8108c757)
Location: include/linux/hash.h:74
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff8108d4bb)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:domain_add_cpu
```
```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81092a03)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_rdt_prepare
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_init_fs_context
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:schemata_list_add
```
```
In arch/x86/kernel/cpu/resctrl/monitor.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff81098602)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter
```
```
In arch/x86/kernel/cpu/sgx/driver.c (ffffffff81098fa6)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/driver.c:sgx_open
```
```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff81099e7f)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_mm_add
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_eaug_page
```
```
In arch/x86/kernel/cpu/sgx/ioctl.c (ffffffff8109d4f2)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_ioctl
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_ioc_enclave_init
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_grow
```
```
In arch/x86/kernel/cpu/sgx/main.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In arch/x86/kernel/cpu/sgx/virt.c (ffffffff8109f399)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_open
```
```
In arch/x86/kernel/apic/vector.c (ffffffff810ab82a)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - arch/x86/kernel/apic/vector.c:x86_vector_alloc_irqs
```
```
In arch/x86/kernel/apic/io_apic.c (ffffffff810aef0e)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - arch/x86/kernel/apic/io_apic.c:mp_irqdomain_alloc
  - arch/x86/kernel/apic/io_apic.c:__add_pin_to_irq_node
```
```
In arch/x86/kernel/apic/x2apic_uv_x.c (ffffffff838e7f81)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_uv_x.c:uv_system_init_hub
```
```
In arch/x86/kernel/apic/x2apic_cluster.c (ffffffff810b38e6)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - arch/x86/kernel/apic/x2apic_cluster.c:alloc_clustermask
```
```
In arch/x86/kernel/kexec-bzimage64.c (ffffffff810b91a3)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - arch/x86/kernel/kexec-bzimage64.c:bzImage64_load
```
```
In arch/x86/kernel/kprobes/opt.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In arch/x86/kernel/hpet.c (ffffffff838e97ee)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - arch/x86/kernel/hpet.c:hpet_select_clockevents
```
```
In arch/x86/kernel/amd_nb.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In arch/x86/kernel/kvm.c (ffffffff810c0cef)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - arch/x86/kernel/kvm.c:kvm_async_pf_task_wake
```
```
In arch/x86/mm/pat/memtype.c (ffffffff810da56e)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - arch/x86/mm/pat/memtype.c:memtype_get_idx
  - arch/x86/mm/pat/memtype.c:memtype_reserve
```
```
In arch/x86/mm/kmmio.c (ffffffff810de161)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:unregister_kmmio_probe
  - arch/x86/mm/kmmio.c:register_kmmio_probe
  - arch/x86/mm/kmmio.c:kmmio_page_list
```
```
In arch/x86/mm/mmio-mod.c (ffffffff810df616)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - arch/x86/mm/mmio-mod.c:mmiotrace_ioremap
```
```
In arch/x86/platform/efi/quirks.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In arch/x86/platform/efi/runtime-map.c (ffffffff810ed626)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - arch/x86/platform/efi/runtime-map.c:add_sysfs_runtime_map_entry
```
```
In arch/x86/platform/uv/uv_irq.c (ffffffff810ef2c9)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_irq.c:uv_domain_alloc
```
```
In arch/x86/platform/uv/uv_time.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In arch/x86/platform/uv/uv_nmi.c (ffffffff838f9726)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_common
  - arch/x86/platform/uv/uv_nmi.c:uv_nmi_setup_common
```
```
In arch/x86/net/bpf_jit_comp.c (ffffffff810f86a4)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile
```
```
In kernel/resource.c (ffffffff8110b3a7)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - kernel/resource.c:get_free_mem_region
  - kernel/resource.c:release_mem_region_adjustable
  - kernel/resource.c:__request_region
  - kernel/resource.c:reserve_region_with_split
  - kernel/resource.c:reserve_region_with_split
```
```
In kernel/umh.c (ffffffff81125346)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - kernel/umh.c:call_usermodehelper
```
```
In kernel/workqueue.c (ffffffff8112f851)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - kernel/workqueue.c:workqueue_sysfs_register
  - kernel/workqueue.c:work_busy
  - kernel/workqueue.c:alloc_workqueue
  - kernel/workqueue.c:get_unbound_pool
  - kernel/workqueue.c:alloc_workqueue_attrs
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:worker_thread
  - kernel/workqueue.c:process_one_work
  - kernel/workqueue.c:alloc_worker
  - kernel/workqueue.c:wq_cpu_intensive_report
  - kernel/workqueue.c:workqueue_init_early
  - kernel/workqueue.c:workqueue_init_early
```
```
In kernel/params.c (ffffffff838fce49)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - kernel/params.c:locate_module_kobject
  - kernel/params.c:add_sysfs_param
  - kernel/params.c:add_sysfs_param
```
```
In kernel/kthread.c (ffffffff811345a4)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - kernel/kthread.c:__kthread_create_worker
  - kernel/kthread.c:__kthread_create_on_node
  - kernel/kthread.c:set_kthread_struct
```
```
In kernel/reboot.c (ffffffff811400fc)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - kernel/reboot.c:register_sys_off_handler
```
```
In kernel/async.c (ffffffff811415a1)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - kernel/async.c:async_schedule_dev_nocall
  - kernel/async.c:async_schedule_node_domain
```
```
In kernel/smpboot.c (ffffffff81141d39)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - kernel/smpboot.c:__smpboot_create_thread
```
```
In kernel/ucount.c (ffffffff838fd70e)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - kernel/ucount.c:user_namespace_sysctl_init
  - kernel/ucount.c:alloc_ucounts
  - kernel/ucount.c:alloc_ucounts
```
```
In kernel/regset.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In kernel/vhost_task.c (ffffffff81143ede)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - kernel/vhost_task.c:vhost_task_create
```
```
In kernel/sched/core.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In kernel/sched/fair.c (ffffffff81174172)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - kernel/sched/fair.c:alloc_fair_sched_group
  - kernel/sched/fair.c:alloc_fair_sched_group
  - kernel/sched/fair.c:task_numa_work
```
```
In kernel/sched/build_policy.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In kernel/sched/build_utility.c (ffffffff811901be)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:sched_autogroup_create_attach
  - kernel/sched/build_utility.c:psi_trigger_create
  - kernel/sched/build_utility.c:psi_cgroup_alloc
  - kernel/sched/build_utility.c:sched_core_share_pid
  - kernel/sched/build_utility.c:build_sched_domains
  - kernel/sched/build_utility.c:__sdt_alloc
  - kernel/sched/build_utility.c:build_perf_domains
  - kernel/sched/build_utility.c:wake_up_var
  - kernel/sched/build_utility.c:wake_up_bit
  - kernel/sched/build_utility.c:out_of_line_wait_on_bit_lock
  - kernel/sched/build_utility.c:out_of_line_wait_on_bit_timeout
  - kernel/sched/build_utility.c:out_of_line_wait_on_bit
  - kernel/sched/build_utility.c:sugov_init
  - kernel/sched/build_utility.c:sugov_init
```
```
In kernel/locking/qspinlock.c (ffffffff8223d6e1)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - kernel/locking/qspinlock.c:__pv_queued_spin_unlock_slowpath
  - kernel/locking/qspinlock.c:pv_hash
```
```
In kernel/power/qos.c (ffffffff8119e189)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - kernel/power/qos.c:cpu_latency_qos_open
```
```
In kernel/power/console.c (ffffffff811a0394)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - kernel/power/console.c:pm_vt_switch_required
```
```
In kernel/power/snapshot.c (ffffffff811a5fe6)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - kernel/power/snapshot.c:create_basic_memory_bitmaps
  - kernel/power/snapshot.c:create_basic_memory_bitmaps
  - kernel/power/snapshot.c:create_mem_extents
```
```
In kernel/power/swap.c (ffffffff811ab445)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - kernel/power/swap.c:swsusp_read
  - kernel/power/swap.c:load_image_lzo
  - kernel/power/swap.c:save_image_lzo
  - kernel/power/swap.c:alloc_swapdev_block
```
```
In kernel/power/wakelock.c (ffffffff811ac887)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - kernel/power/wakelock.c:wakelock_lookup_add
```
```
In kernel/power/energy_model.c (ffffffff811ad3b7)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - kernel/power/energy_model.c:em_create_pd
```
```
In kernel/printk/printk.c (ffffffff811af901)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - kernel/printk/printk.c:syslog_print_all
  - kernel/printk/printk.c:syslog_print
```
```
In kernel/printk/nbcon.c (ffffffff811b3b4c)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - kernel/printk/nbcon.c:nbcon_alloc
```
```
In kernel/irq/irqdesc.c (ffffffff811b69bf)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - kernel/irq/irqdesc.c:irq_set_percpu_devid_partition
  - kernel/irq/irqdesc.c:alloc_desc
```
```
In kernel/irq/manage.c (ffffffff811baa36)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - kernel/irq/manage.c:request_percpu_nmi
  - kernel/irq/manage.c:__request_percpu_irq
  - kernel/irq/manage.c:request_nmi
  - kernel/irq/manage.c:request_threaded_irq
  - kernel/irq/manage.c:__setup_irq
```
```
In kernel/irq/generic-chip.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In kernel/irq/irqdomain.c (ffffffff811c27f9)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - kernel/irq/irqdomain.c:irq_domain_push_irq
  - kernel/irq/irqdomain.c:irq_domain_alloc_irqs_locked
  - kernel/irq/irqdomain.c:__irq_domain_alloc_fwnode
```
```
In kernel/irq/irq_sim.c (ffffffff811c2f8c)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - kernel/irq/irq_sim.c:irq_domain_create_sim
  - kernel/irq/irq_sim.c:irq_sim_domain_map
```
```
In kernel/irq/msi.c (ffffffff811c63a4)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - kernel/irq/msi.c:msi_domain_add_simple_msi_descs
```
```
In kernel/irq/affinity.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In kernel/irq/matrix.c (ffffffff83901995)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - kernel/irq/matrix.c:irq_alloc_matrix
```
```
In kernel/rcu/srcutree.c (ffffffff811d0670)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:init_srcu_struct_fields
```
```
In kernel/livepatch/core.c (ffffffff811e3e4f)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - kernel/livepatch/core.c:klp_add_nops
  - kernel/livepatch/core.c:klp_add_nops
```
```
In kernel/livepatch/patch.c (ffffffff811e58ac)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - kernel/livepatch/patch.c:klp_patch_func
```
```
In kernel/livepatch/shadow.c (ffffffff811e5dd6)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - kernel/livepatch/shadow.c:klp_shadow_free
  - kernel/livepatch/shadow.c:__klp_shadow_get_or_alloc
  - kernel/livepatch/shadow.c:__klp_shadow_get_or_alloc
```
```
In kernel/dma/mapping.c (ffffffff811e8421)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - kernel/dma/mapping.c:dma_alloc_noncontiguous
```
```
In kernel/dma/direct.c (ffffffff811eb10f)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - kernel/dma/direct.c:dma_direct_set_offset
```
```
In kernel/dma/swiotlb.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In kernel/module/main.c (ffffffff811f6292)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - kernel/module/main.c:idempotent_init_module
  - kernel/module/main.c:idempotent_init_module
  - kernel/module/main.c:do_init_module
  - kernel/module/main.c:ref_module
```
```
In kernel/module/kmod.c (ffffffff811f74dc)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - kernel/module/kmod.c:__request_module
```
```
In kernel/module/livepatch.c (ffffffff811f7e4c)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - kernel/module/livepatch.c:copy_module_elf
```
```
In kernel/module/sysfs.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In kernel/profile.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In kernel/time/posix-clock.c (ffffffff8121598c)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - kernel/time/posix-clock.c:posix_clock_open
```
```
In kernel/time/namespace.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In kernel/futex/syscalls.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In kernel/futex/pi.c (ffffffff812218bc)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - kernel/futex/pi.c:refill_pi_state_cache
```
```
In kernel/acct.c (ffffffff8122934d)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - kernel/acct.c:acct_on
```
```
In kernel/kexec_core.c (ffffffff8122b781)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - kernel/kexec_core.c:__crash_shrink_memory
  - kernel/kexec_core.c:do_kimage_alloc_init
```
```
In kernel/kexec.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In kernel/kexec_file.c (ffffffff8122ecfd)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - kernel/kexec_file.c:kexec_calculate_store_digests
```
```
In kernel/cgroup/cgroup.c (ffffffff8123cf19)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:proc_cgroup_show
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/cgroup/cgroup.c:cgroup_file_open
  - kernel/cgroup/cgroup.c:cgroup_init_fs_context
  - kernel/cgroup/cgroup.c:cgroup_show_path
  - kernel/cgroup/cgroup.c:find_css_set
  - kernel/cgroup/cgroup.c:find_css_set
  - kernel/cgroup/cgroup.c:allocate_cgrp_cset_links
  - kernel/cgroup/cgroup.c:find_existing_css_set
```
```
In kernel/cgroup/namespace.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In kernel/cgroup/cgroup-v1.c (ffffffff8124090b)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_root_to_use
  - kernel/cgroup/cgroup-v1.c:cgroup1_release_agent
  - kernel/cgroup/cgroup-v1.c:cgroup1_release_agent
  - kernel/cgroup/cgroup-v1.c:pidlist_array_load
```
```
In kernel/cgroup/legacy_freezer.c (ffffffff812433ac)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_css_alloc
```
```
In kernel/cgroup/pids.c (ffffffff81243a3c)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - kernel/cgroup/pids.c:pids_css_alloc
```
```
In kernel/cgroup/rdma.c (ffffffff8124478c)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - kernel/cgroup/rdma.c:rdmacg_css_alloc
  - kernel/cgroup/rdma.c:rdmacg_resource_set_max
  - kernel/cgroup/rdma.c:get_cg_rpool_locked
```
```
In kernel/cgroup/cpuset.c (ffffffff8124ec3e)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - kernel/cgroup/cpuset.c:proc_cpuset_show
  - kernel/cgroup/cpuset.c:generate_sched_domains
```
```
In kernel/cgroup/misc.c (ffffffff8124f660)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - kernel/cgroup/misc.c:misc_cg_alloc
```
```
In kernel/user_namespace.c (ffffffff812501ec)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - kernel/user_namespace.c:insert_extent
```
```
In kernel/audit.c (ffffffff81256e1f)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_d_path
  - kernel/audit.c:auditd_set
```
```
In kernel/auditfilter.c (ffffffff8125b13f)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_list_rules_send
  - kernel/auditfilter.c:audit_init_entry
  - kernel/auditfilter.c:audit_register_class
```
```
In kernel/auditsc.c (ffffffff81261b60)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - kernel/auditsc.c:__audit_log_bprm_fcaps
  - kernel/auditsc.c:audit_signal_info_syscall
  - kernel/auditsc.c:__audit_sockaddr
  - kernel/auditsc.c:audit_alloc_name
  - kernel/auditsc.c:audit_log_proctitle
  - kernel/auditsc.c:audit_log_execve_info
  - kernel/auditsc.c:audit_alloc
  - kernel/auditsc.c:grow_tree_refs
```
```
In kernel/audit_watch.c (ffffffff8126307d)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_watch.c:audit_init_watch
```
```
In kernel/audit_fsnotify.c (ffffffff812636de)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - kernel/audit_fsnotify.c:audit_alloc_mark
```
```
In kernel/audit_tree.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In kernel/kprobes.c (ffffffff81269f93)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - kernel/kprobes.c:kprobe_add_ksym_blacklist
  - kernel/kprobes.c:register_kprobe
  - kernel/kprobes.c:register_kprobe
  - kernel/kprobes.c:__get_valid_kprobe
  - kernel/kprobes.c:alloc_aggr_kprobe
  - kernel/kprobes.c:get_optimized_kprobe
```
```
In kernel/debug/kdb/kdb_main.c (ffffffff81271692)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd
  - kernel/debug/kdb/kdb_main.c:kdb_defcmd2
```
```
In kernel/debug/kdb/kdb_support.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In kernel/seccomp.c (ffffffff8127be67)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/seccomp.c:seccomp_set_mode_filter
```
```
In kernel/relay.c (ffffffff8127e4e9)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - kernel/relay.c:relay_open
  - kernel/relay.c:relay_create_buf_file
  - kernel/relay.c:relay_create_buf
```
```
In kernel/taskstats.c (ffffffff8127fd67)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - kernel/taskstats.c:add_del_listener
```
```
In kernel/tracepoint.c (ffffffff812813dc)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - kernel/tracepoint.c:tracepoint_module_notify
```
```
In kernel/trace/ftrace.c (ffffffff8128c216)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_free_mem
  - kernel/trace/ftrace.c:ftrace_free_mem
  - kernel/trace/ftrace.c:save_ftrace_mod_rec
  - kernel/trace/ftrace.c:ops_references_ip
  - kernel/trace/ftrace.c:ftrace_graph_notrace_open
  - kernel/trace/ftrace.c:ftrace_graph_open
  - kernel/trace/ftrace.c:unregister_ftrace_direct
  - kernel/trace/ftrace.c:register_ftrace_function_probe
  - kernel/trace/ftrace.c:ftrace_func_mapper_add_ip
  - kernel/trace/ftrace.c:cache_mod
  - kernel/trace/ftrace.c:ftrace_regex_open
  - kernel/trace/ftrace.c:ftrace_allocate_pages
  - kernel/trace/ftrace.c:ftrace_allocate_pages
  - kernel/trace/ftrace.c:ftrace_find_rec_direct
  - kernel/trace/ftrace.c:hash_contains_ip
  - kernel/trace/ftrace.c:hash_contains_ip
  - kernel/trace/ftrace.c:__ftrace_hash_move
  - kernel/trace/ftrace.c:alloc_ftrace_hash
  - kernel/trace/ftrace.c:ftrace_lookup_ip
  - kernel/trace/ftrace.c:profile_graph_return
  - kernel/trace/ftrace.c:ftrace_profile_init
```
```
In kernel/trace/ring_buffer.c (ffffffff8128f130)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - kernel/trace/ring_buffer.c:ring_buffer_read_prepare
```
```
In kernel/trace/trace.c (ffffffff812a4ec2)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_parse_run_command
  - kernel/trace/trace.c:trace_array_create_systems
  - kernel/trace/trace.c:tracing_read_dyn_info
  - kernel/trace/trace.c:tracing_buffers_splice_read
  - kernel/trace/trace.c:tracing_log_err
  - kernel/trace/trace.c:tracing_snapshot_open
  - kernel/trace/trace.c:__tracing_open
  - kernel/trace/trace.c:register_tracer
  - kernel/trace/trace.c:tracing_snapshot_cond_enable
```
```
In kernel/trace/trace_stat.c (ffffffff812a8f9d)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - kernel/trace/trace_stat.c:register_stat_tracer
  - kernel/trace/trace_stat.c:insert_stat
```
```
In kernel/trace/trace_printk.c (ffffffff812a9378)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - kernel/trace/trace_printk.c:hold_module_trace_bprintk_format
```
```
In kernel/trace/pid_list.c (ffffffff812aa2f4)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - kernel/trace/pid_list.c:trace_pid_list_alloc
  - kernel/trace/pid_list.c:trace_pid_list_alloc
  - kernel/trace/pid_list.c:trace_pid_list_alloc
  - kernel/trace/pid_list.c:pid_list_refill_irq
  - kernel/trace/pid_list.c:pid_list_refill_irq
```
```
In kernel/trace/tracing_map.c (ffffffff812abcbb)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_sort_entries
  - kernel/trace/tracing_map.c:tracing_map_create
  - kernel/trace/tracing_map.c:tracing_map_elt_alloc
  - kernel/trace/tracing_map.c:tracing_map_array_alloc
```
```
In kernel/trace/trace_functions.c (ffffffff812ad901)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - kernel/trace/trace_functions.c:ftrace_allocate_ftrace_ops
```
```
In kernel/trace/trace_osnoise.c (ffffffff812b223b)
Location: include/linux/hash.h:74
Inline: True
```
```
In kernel/trace/trace_mmiotrace.c (ffffffff812b6591)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - kernel/trace/trace_mmiotrace.c:mmio_pipe_open
```
```
In kernel/trace/trace_functions_graph.c (ffffffff812b6e91)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - kernel/trace/trace_functions_graph.c:graph_trace_open
```
```
In kernel/trace/blktrace.c (ffffffff812bac6c)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - kernel/trace/blktrace.c:blk_trace_setup_queue
  - kernel/trace/blktrace.c:do_blk_trace_setup
```
```
In kernel/trace/fgraph.c (ffffffff812bd999)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - kernel/trace/fgraph.c:start_graph_tracing
  - kernel/trace/fgraph.c:start_graph_tracing
  - kernel/trace/fgraph.c:ftrace_graph_init_task
```
```
In kernel/trace/trace_events.c (ffffffff812c3d64)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:event_enable_func
  - kernel/trace/trace_events.c:update_event_fields
  - kernel/trace/trace_events.c:event_subsystem_dir
  - kernel/trace/trace_events.c:event_subsystem_dir
  - kernel/trace/trace_events.c:event_subsystem_dir
  - kernel/trace/trace_events.c:system_tr_open
```
```
In kernel/trace/trace_syscalls.c (ffffffff8390dcd8)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - kernel/trace/trace_syscalls.c:init_ftrace_syscalls
```
```
In kernel/trace/trace_events_filter.c (ffffffff812c90fd)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - kernel/trace/trace_events_filter.c:process_system_preds
  - kernel/trace/trace_events_filter.c:process_system_preds
  - kernel/trace/trace_events_filter.c:parse_pred
  - kernel/trace/trace_events_filter.c:parse_pred
  - kernel/trace/trace_events_filter.c:parse_pred
```
```
In kernel/trace/trace_events_trigger.c (ffffffff812cbbce)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - kernel/trace/trace_events_trigger.c:event_enable_trigger_parse
  - kernel/trace/trace_events_trigger.c:event_trigger_alloc
```
```
In kernel/trace/trace_eprobe.c (ffffffff812cc867)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - kernel/trace/trace_eprobe.c:enable_trace_eprobe
  - kernel/trace/trace_eprobe.c:enable_trace_eprobe
```
```
In kernel/trace/trace_events_inject.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In kernel/trace/trace_events_synth.c (ffffffff812d0fff)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - kernel/trace/trace_events_synth.c:synth_event_create
  - kernel/trace/trace_events_synth.c:alloc_synth_event
  - kernel/trace/trace_events_synth.c:register_synth_event
  - kernel/trace/trace_events_synth.c:parse_synth_field
```
```
In kernel/trace/trace_events_hist.c (ffffffff812de4f4)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_parse
  - kernel/trace/trace_events_hist.c:event_hist_trigger_parse
  - kernel/trace/trace_events_hist.c:parse_actions
  - kernel/trace/trace_events_hist.c:onmatch_parse
  - kernel/trace/trace_events_hist.c:action_create
  - kernel/trace/trace_events_hist.c:action_create
  - kernel/trace/trace_events_hist.c:action_create
  - kernel/trace/trace_events_hist.c:create_field_var
  - kernel/trace/trace_events_hist.c:create_var
  - kernel/trace/trace_events_hist.c:create_field_var_hist
  - kernel/trace/trace_events_hist.c:create_field_var_hist
  - kernel/trace/trace_events_hist.c:find_synthetic_field_var
  - kernel/trace/trace_events_hist.c:create_var_ref
  - kernel/trace/trace_events_hist.c:expr_str
  - kernel/trace/trace_events_hist.c:hist_trigger_elt_data_alloc
  - kernel/trace/trace_events_hist.c:hist_trigger_elt_data_alloc
  - kernel/trace/trace_events_hist.c:hist_trigger_elt_data_alloc
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
```
```
In kernel/trace/trace_events_user.c (ffffffff8390e1e4)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - kernel/trace/trace_events_user.c:trace_events_user_init
  - kernel/trace/trace_events_user.c:trace_events_user_init
```
```
In kernel/trace/bpf_trace.c (ffffffff812ea3af)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:bpf_uprobe_multi_link_attach
  - kernel/trace/bpf_trace.c:bpf_kprobe_multi_link_attach
  - kernel/trace/bpf_trace.c:bpf_event_notify
  - kernel/trace/bpf_trace.c:bpf_lookup_system_key
  - kernel/trace/bpf_trace.c:bpf_lookup_user_key
```
```
In kernel/trace/trace_kprobe.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In kernel/trace/trace_probe.c (ffffffff812f7e57)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:trace_probe_add_file
  - kernel/trace/trace_probe.c:traceprobe_parse_probe_arg_body
```
```
In kernel/trace/trace_btf.c (ffffffff812f850f)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - kernel/trace/trace_btf.c:btf_find_struct_member
```
```
In kernel/trace/trace_uprobe.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In kernel/trace/fprobe.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In kernel/trace/rethook.c (ffffffff812fcf9c)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - kernel/trace/rethook.c:rethook_alloc
```
```
In kernel/trace/trace_fprobe.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In kernel/trace/rv/rv.c (ffffffff81301755)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - kernel/trace/rv/rv.c:rv_register_monitor
```
```
In kernel/trace/rv/rv_reactors.c (ffffffff813028b8)
Location: include/linux/hash.h:74
Inline: True
```
```
In kernel/bpf/core.c (ffffffff81306630)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_alloc_no_stats
```
```
In kernel/bpf/syscall.c (ffffffff81312e30)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_raw_tp_link_attach
  - kernel/bpf/syscall.c:bpf_perf_link_attach
  - kernel/bpf/syscall.c:bpf_tracing_prog_attach
```
```
In kernel/bpf/verifier.c (ffffffff8133c68d)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:do_check_common
  - kernel/bpf/verifier.c:do_check_common
  - kernel/bpf/verifier.c:is_state_visited
  - kernel/bpf/verifier.c:push_callback_call
  - kernel/bpf/verifier.c:push_callback_call
  - kernel/bpf/verifier.c:setup_func_entry
  - kernel/bpf/verifier.c:add_kfunc_call
  - kernel/bpf/verifier.c:push_stack
  - kernel/bpf/verifier.c:copy_verifier_state
```
```
In kernel/bpf/inode.c (ffffffff8133f8e0)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - kernel/bpf/inode.c:bpf_init_fs_context
  - kernel/bpf/inode.c:bpffs_map_open
```
```
In kernel/bpf/bpf_iter.c (ffffffff813478ef)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - kernel/bpf/bpf_iter.c:bpf_iter_link_attach
  - kernel/bpf/bpf_iter.c:bpf_iter_reg_target
```
```
In kernel/bpf/hashtab.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In kernel/bpf/arraymap.c (ffffffff81351743)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - kernel/bpf/arraymap.c:perf_event_fd_array_get_ptr
  - kernel/bpf/arraymap.c:prog_array_map_poke_track
```
```
In kernel/bpf/lpm_trie.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In kernel/bpf/map_in_map.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In kernel/bpf/bpf_local_storage.c (ffffffff81358dda)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - kernel/bpf/bpf_local_storage.c:bpf_selem_link_map
  - kernel/bpf/bpf_local_storage.c:bpf_selem_unlink_map
```
```
In kernel/bpf/trampoline.c (ffffffff8135e877)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - kernel/bpf/trampoline.c:bpf_trampoline_link_cgroup_shim
  - kernel/bpf/trampoline.c:bpf_trampoline_update
  - kernel/bpf/trampoline.c:bpf_trampoline_update
  - kernel/bpf/trampoline.c:bpf_trampoline_lookup
  - kernel/bpf/trampoline.c:bpf_trampoline_lookup
  - kernel/bpf/trampoline.c:bpf_trampoline_lookup
```
```
In kernel/bpf/btf.c (ffffffff8137126b)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - kernel/bpf/btf.c:bpf_core_apply
  - kernel/bpf/btf.c:btf_populate_kfunc_set
  - kernel/bpf/btf.c:btf_module_notify
  - kernel/bpf/btf.c:btf_module_notify
  - kernel/bpf/btf.c:btf_parse_module
  - kernel/bpf/btf.c:btf_parse_module
  - kernel/bpf/btf.c:btf_parse_vmlinux
  - kernel/bpf/btf.c:btf_parse_vmlinux
  - kernel/bpf/btf.c:btf_parse
  - kernel/bpf/btf.c:btf_parse
```
```
In kernel/bpf/memalloc.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In kernel/bpf/offload.c (ffffffff8137822c)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - kernel/bpf/offload.c:bpf_offload_dev_create
  - kernel/bpf/offload.c:__bpf_prog_dev_bound_init
  - kernel/bpf/offload.c:__bpf_offload_dev_netdev_register
```
```
In kernel/bpf/net_namespace.c (ffffffff8137b1fe)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - kernel/bpf/net_namespace.c:netns_bpf_link_create
```
```
In kernel/bpf/tcx.c (ffffffff8137c8a1)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - kernel/bpf/tcx.c:tcx_link_attach
  - kernel/bpf/tcx.c:tcx_link_prog_attach
  - kernel/bpf/tcx.c:tcx_prog_attach
```
```
In kernel/bpf/cgroup_iter.c (ffffffff8137df49)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - kernel/bpf/cgroup_iter.c:bpf_iter_cgroup_show_fdinfo
```
```
In kernel/bpf/cgroup.c (ffffffff81383257)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_link_attach
  - kernel/bpf/cgroup.c:__cgroup_bpf_attach
```
```
In kernel/bpf/bpf_struct_ops.c (ffffffff8138617f)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_link_create
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_update_elem
  - kernel/bpf/bpf_struct_ops.c:bpf_struct_ops_map_update_elem
```
```
In kernel/static_call_inline.c (ffffffff8138d1c7)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - kernel/static_call_inline.c:__static_call_init
  - kernel/static_call_inline.c:__static_call_init
```
```
In kernel/events/core.c (ffffffff81391bdd)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - kernel/events/core.c:perf_cgroup_css_alloc
  - kernel/events/core.c:perf_event_init_cpu
  - kernel/events/core.c:pmu_dev_alloc
  - kernel/events/core.c:perf_event_parse_addr_filter
  - kernel/events/core.c:swevent_hlist_get
  - kernel/events/core.c:perf_swevent_add
  - kernel/events/core.c:___perf_sw_event
  - kernel/events/core.c:perf_event_mmap_event
  - kernel/events/core.c:perf_event_cgroup
  - kernel/events/core.c:find_get_pmu_context
  - kernel/events/core.c:alloc_perf_context
```
```
In kernel/events/ring_buffer.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In kernel/events/callchain.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In kernel/events/uprobes.c (ffffffff813acf21)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - kernel/events/uprobes.c:prepare_uretprobe
  - kernel/events/uprobes.c:uprobe_copy_process
  - kernel/events/uprobes.c:uprobe_copy_process
  - kernel/events/uprobes.c:get_utask
  - kernel/events/uprobes.c:__create_xol_area
  - kernel/events/uprobes.c:__create_xol_area
  - kernel/events/uprobes.c:build_map_info
  - kernel/events/uprobes.c:build_map_info
  - kernel/events/uprobes.c:alloc_uprobe
  - kernel/events/uprobes.c:update_ref_ctr
```
```
In kernel/padata.c (ffffffff813ae71e)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - kernel/padata.c:padata_alloc_shell
  - kernel/padata.c:padata_alloc
  - kernel/padata.c:padata_alloc_pd
```
```
In kernel/jump_label.c (ffffffff813b0006)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - kernel/jump_label.c:jump_label_add_module
  - kernel/jump_label.c:jump_label_add_module
```
```
In kernel/watch_queue.c (ffffffff813b3690)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - kernel/watch_queue.c:watch_queue_init
```
```
In certs/system_keyring.c (ffffffff83911d88)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - certs/system_keyring.c:system_trusted_keyring_init
```
```
In certs/blacklist.c (ffffffff8391209c)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - certs/blacklist.c:blacklist_init
```
```
In mm/filemap.c (ffffffff813b8248)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - mm/filemap.c:filemap_update_page
  - mm/filemap.c:folio_add_wait_queue
  - mm/filemap.c:migration_entry_wait_on_locked
  - mm/filemap.c:folio_wait_bit_common
  - mm/filemap.c:folio_wake_bit
```
```
In mm/mempool.c (ffffffff813bd567)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - mm/mempool.c:mempool_create
```
```
In mm/vmscan.c (ffffffff813d38dd)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - mm/vmscan.c:set_mm_walk
  - mm/vmscan.c:walk_pmd_range
  - mm/vmscan.c:update_bloom_filter
```
```
In mm/shrinker.c (ffffffff813e4326)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - mm/shrinker.c:shrinker_alloc
  - mm/shrinker.c:expand_one_shrinker_info
  - mm/shrinker.c:alloc_shrinker_info
```
```
In mm/shmem.c (ffffffff813e7860)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - mm/shmem.c:shmem_init_fs_context
  - mm/shmem.c:shmem_fill_super
```
```
In mm/util.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In mm/vmstat.c (ffffffff813f2828)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - mm/vmstat.c:vmstat_start
```
```
In mm/backing-dev.c (ffffffff813f648f)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - mm/backing-dev.c:bdi_alloc
  - mm/backing-dev.c:cgwb_create
```
```
In mm/percpu.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In mm/slab_common.c (ffffffff813fec9b)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - mm/slab_common.c:kmalloc_size_roundup
```
```
In mm/shmem_quota.c (ffffffff814090cc)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - mm/shmem_quota.c:shmem_acquire_dquot
  - mm/shmem_quota.c:shmem_read_file_info
```
```
In mm/list_lru.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In mm/mmap_lock.c (ffffffff81413ce9)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - mm/mmap_lock.c:trace_mmap_lock_reg
```
```
In mm/vmalloc.c (ffffffff81441f20)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - mm/vmalloc.c:pcpu_get_vm_areas
  - mm/vmalloc.c:__get_vm_area_node
```
```
In mm/process_vm_access.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In mm/memblock.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In mm/memory_hotplug.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In mm/slub.c (ffffffff8145cd29)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - mm/slub.c:sysfs_slab_alias
  - mm/slub.c:sysfs_slab_add
  - mm/slub.c:__kmalloc_node_track_caller
  - mm/slub.c:__kmalloc
  - mm/slub.c:__kmalloc_node
```
```
In mm/madvise.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In mm/swapfile.c (ffffffff8146731e)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - mm/swapfile.c:add_swap_extent
```
```
In mm/zswap.c (ffffffff814715f4)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - mm/zswap.c:zswap_swapon
  - mm/zswap.c:zswap_store
  - mm/zswap.c:__zswap_load
  - mm/zswap.c:zswap_pool_create
  - mm/zswap.c:zswap_cpu_comp_prepare
  - mm/zswap.c:zswap_free_entry
```
```
In mm/dmapool.c (ffffffff81471b03)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - mm/dmapool.c:dma_pool_alloc
  - mm/dmapool.c:dma_pool_create
```
```
In mm/hugetlb.c (ffffffff81475350)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - mm/hugetlb.c:set_max_huge_pages
  - mm/hugetlb.c:hugetlb_hstate_alloc_pages
  - mm/hugetlb.c:resv_map_alloc
  - mm/hugetlb.c:resv_map_alloc
  - mm/hugetlb.c:region_del
  - mm/hugetlb.c:allocate_file_region_entries
  - mm/hugetlb.c:hugepage_new_subpool
```
```
In mm/mempolicy.c (ffffffff81487807)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_shared_policy_init
  - mm/mempolicy.c:kernel_migrate_pages
  - mm/mempolicy.c:do_mbind
  - mm/mempolicy.c:do_set_mempolicy
```
```
In mm/sparse.c (ffffffff82231ed1)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - mm/sparse.c:sparse_add_section
  - mm/sparse.c:sparse_index_alloc
```
```
In mm/mmu_notifier.c (ffffffff814897f2)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - mm/mmu_notifier.c:__mmu_notifier_register
```
```
In mm/ksm.c (ffffffff8149263b)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - mm/ksm.c:__ksm_exit
  - mm/ksm.c:__ksm_enter
```
```
In mm/memory-tiers.c (ffffffff8149af4f)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - mm/memory-tiers.c:alloc_memory_type
  - mm/memory-tiers.c:find_create_memory_tier
```
```
In mm/huge_memory.c (ffffffff8391e9d3)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - mm/huge_memory.c:hugepage_init_sysfs
```
```
In mm/khugepaged.c (ffffffff814b1668)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - mm/khugepaged.c:madvise_collapse
  - mm/khugepaged.c:__khugepaged_exit
  - mm/khugepaged.c:__khugepaged_enter
```
```
In mm/memcontrol.c (ffffffff8391efd4)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_init
  - mm/memcontrol.c:memory_stat_show
  - mm/memcontrol.c:mem_cgroup_css_online
  - mm/memcontrol.c:mem_cgroup_alloc
  - mm/memcontrol.c:mem_cgroup_alloc
  - mm/memcontrol.c:memcg_write_event_control
  - mm/memcontrol.c:mem_cgroup_oom_register_event
```
```
In mm/vmpressure.c (ffffffff814c1343)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - mm/vmpressure.c:vmpressure_register_event
```
```
In mm/hugetlb_cgroup.c (ffffffff814c296a)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_css_alloc
```
```
In mm/memory-failure.c (ffffffff814c9001)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - mm/memory-failure.c:__get_huge_page_for_hwpoison
  - mm/memory-failure.c:__add_to_kill
```
```
In mm/zpool.c (ffffffff814cace3)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - mm/zpool.c:zpool_create_pool
```
```
In mm/zbud.c (ffffffff814cb5ec)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - mm/zbud.c:zbud_zpool_create
```
```
In mm/zsmalloc.c (ffffffff814cc17a)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_create_pool
  - mm/zsmalloc.c:zs_create_pool
  - mm/zsmalloc.c:zs_cpu_prepare
```
```
In mm/memfd.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In mm/page_reporting.c (ffffffff814d8467)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - mm/page_reporting.c:page_reporting_process
```
```
In fs/file_table.c (ffffffff814e312b)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - fs/file_table.c:alloc_empty_backing_file
```
```
In fs/super.c (ffffffff814e6f4c)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - fs/super.c:emergency_thaw_all
  - fs/super.c:emergency_remount
  - fs/super.c:alloc_super
```
```
In fs/char_dev.c (ffffffff814e74cd)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - fs/char_dev.c:cdev_alloc
  - fs/char_dev.c:__register_chrdev_region
```
```
In fs/exec.c (ffffffff814ebea4)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - fs/exec.c:alloc_bprm
```
```
In fs/pipe.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In fs/namei.c (ffffffff814f1a4d)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - fs/namei.c:nd_alloc_stack
  - fs/namei.c:getname_kernel
```
```
In fs/select.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In fs/dcache.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In fs/file.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In fs/namespace.c (ffffffff815113a3)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - fs/namespace.c:copy_mount_options
  - fs/namespace.c:get_mountpoint
```
```
In fs/seq_file.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In fs/libfs.c (ffffffff81521f88)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - fs/libfs.c:simple_attr_open
  - fs/libfs.c:init_pseudo
```
```
In fs/fs-writeback.c (ffffffff8152d211)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - fs/fs-writeback.c:cgroup_writeback_by_id
  - fs/fs-writeback.c:bdi_split_work_to_wbs
  - fs/fs-writeback.c:cleanup_offline_cgwb
  - fs/fs-writeback.c:inode_switch_wbs
```
```
In fs/splice.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In fs/sync.c (ffffffff815336cc)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - fs/sync.c:emergency_sync
```
```
In fs/fs_context.c (ffffffff81538a65)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - fs/fs_context.c:legacy_parse_param
```
```
In fs/fsopen.c (ffffffff8153aa90)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - fs/fsopen.c:fscontext_alloc_log
```
```
In fs/mnt_idmapping.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In fs/buffer.c (ffffffff8153fcbf)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - fs/buffer.c:end_buffer_async_read_io
```
```
In fs/notify/group.c (ffffffff8154807b)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - fs/notify/group.c:fsnotify_alloc_group
```
```
In fs/notify/inotify/inotify_fsnotify.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In fs/notify/inotify/inotify_user.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In fs/notify/fanotify/fanotify.c (ffffffff8154da90)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
```
```
In fs/notify/fanotify/fanotify_user.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In fs/eventpoll.c (ffffffff81552d58)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - fs/eventpoll.c:do_epoll_create
```
```
In fs/signalfd.c (ffffffff8155518d)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - fs/signalfd.c:do_signalfd4
```
```
In fs/timerfd.c (ffffffff8155618e)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - fs/timerfd.c:__do_sys_timerfd_create
```
```
In fs/eventfd.c (ffffffff8155794e)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - fs/eventfd.c:do_eventfd
```
```
In fs/userfaultfd.c (ffffffff8155c265)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - fs/userfaultfd.c:userfaultfd_unmap_prep
  - fs/userfaultfd.c:dup_userfaultfd
```
```
In fs/aio.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In fs/dax.c (ffffffff81563776)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - fs/dax.c:wait_entry_unlocked
  - fs/dax.c:get_unlocked_entry
  - fs/dax.c:dax_wake_entry
```
```
In fs/crypto/crypto.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In fs/crypto/fname.c (ffffffff81569228)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - fs/crypto/fname.c:fscrypt_setup_filename
```
```
In fs/crypto/hooks.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In fs/crypto/keyring.c (ffffffff8156b4df)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - fs/crypto/keyring.c:add_master_key
```
```
In fs/crypto/keysetup_v1.c (ffffffff8156d7c0)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:fscrypt_get_direct_key
  - fs/crypto/keysetup_v1.c:find_or_insert_direct_key
```
```
In fs/crypto/policy.c (ffffffff8156e36a)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - fs/crypto/policy.c:fscrypt_parse_test_dummy_encryption
```
```
In fs/crypto/inline_crypt.c (ffffffff8157055e)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - fs/crypto/inline_crypt.c:fscrypt_prepare_inline_crypt_key
```
```
In fs/verity/enable.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In fs/verity/hash_algs.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In fs/verity/open.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In fs/verity/signature.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In fs/locks.c (ffffffff81578526)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:__locks_insert_block
```
```
In fs/binfmt_elf.c (ffffffff8157c8dd)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - fs/binfmt_elf.c:elf_core_dump
  - fs/binfmt_elf.c:elf_core_dump
  - fs/binfmt_elf.c:fill_note_info
  - fs/binfmt_elf.c:load_elf_binary
```
```
In fs/compat_binfmt_elf.c (ffffffff8157f914)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:elf_core_dump
  - fs/compat_binfmt_elf.c:elf_core_dump
  - fs/compat_binfmt_elf.c:fill_note_info
  - fs/compat_binfmt_elf.c:load_elf_binary
```
```
In fs/mbcache.c (ffffffff81582034)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - fs/mbcache.c:mb_cache_create
```
```
In fs/posix_acl.c (ffffffff81583923)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - fs/posix_acl.c:posix_acl_from_mode
```
```
In fs/coredump.c (ffffffff81585b27)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - fs/coredump.c:cn_print_exe_file
```
```
In fs/fhandle.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In fs/iomap/buffered-io.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In fs/iomap/direct-io.c (ffffffff8158eef9)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - fs/iomap/direct-io.c:__iomap_dio_rw
```
```
In fs/iomap/swapfile.c (ffffffff81590159)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - fs/iomap/swapfile.c:iomap_swapfile_fail
```
```
In fs/proc/task_mmu.c (ffffffff8159c461)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_read
```
```
In fs/proc/root.c (ffffffff815a274e)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - fs/proc/root.c:proc_init_fs_context
  - fs/proc/root.c:proc_fill_super
```
```
In fs/proc/base.c (ffffffff815a6bdb)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - fs/proc/base.c:proc_pid_readlink
  - fs/proc/base.c:proc_pid_stack
```
```
In fs/proc/generic.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In fs/proc/self.c (ffffffff815b0f51)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - fs/proc/self.c:proc_self_get_link
```
```
In fs/proc/thread_self.c (ffffffff815b11bd)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - fs/proc/thread_self.c:proc_thread_self_get_link
```
```
In fs/proc/proc_sysctl.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In fs/proc/kcore.c (ffffffff815b5a2f)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - fs/proc/kcore.c:kclist_add_private
  - fs/proc/kcore.c:kclist_add_private
```
```
In fs/proc/vmcore.c (ffffffff83924c30)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - fs/proc/vmcore.c:parse_crash_elf32_headers
  - fs/proc/vmcore.c:parse_crash_elf64_headers
```
```
In fs/proc/bootconfig.c (ffffffff83925012)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - fs/proc/bootconfig.c:copy_xbc_key_value_list
```
```
In fs/kernfs/mount.c (ffffffff815b90bb)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - fs/kernfs/mount.c:kernfs_get_tree
```
```
In fs/kernfs/dir.c (ffffffff815bc32e)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_create_root
  - fs/kernfs/dir.c:kernfs_name_hash
```
```
In fs/kernfs/file.c (ffffffff815be045)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - fs/kernfs/file.c:kernfs_drain_open_files
  - fs/kernfs/file.c:kernfs_fop_release
  - fs/kernfs/file.c:kernfs_fop_open
  - fs/kernfs/file.c:kernfs_fop_open
  - fs/kernfs/file.c:kernfs_fop_open
  - fs/kernfs/file.c:kernfs_unlink_open_file
```
```
In fs/kernfs/symlink.c (ffffffff815be499)
Location: include/linux/hash.h:74
Inline: True
```
```
In fs/sysfs/dir.c (ffffffff815bfa39)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - fs/sysfs/dir.c:sysfs_warn_dup
```
```
In fs/sysfs/mount.c (ffffffff815c0260)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - fs/sysfs/mount.c:sysfs_init_fs_context
```
```
In fs/configfs/inode.c (ffffffff815c12fb)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - fs/configfs/inode.c:configfs_setattr
```
```
In fs/configfs/file.c (ffffffff815c1c86)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - fs/configfs/file.c:__configfs_open_file
```
```
In fs/configfs/dir.c (ffffffff815c53e1)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - fs/configfs/dir.c:configfs_register_default_group
  - fs/configfs/dir.c:new_fragment
```
```
In fs/configfs/symlink.c (ffffffff815c587a)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - fs/configfs/symlink.c:create_link
```
```
In fs/devpts/inode.c (ffffffff815c6bf5)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_fill_super
```
```
In fs/ext4/block_validity.c (ffffffff815c969f)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - fs/ext4/block_validity.c:ext4_setup_system_zone
```
```
In fs/ext4/dir.c (ffffffff815ca43b)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - fs/ext4/dir.c:ext4_dx_readdir
```
```
In fs/ext4/extents.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In fs/ext4/fsmap.c (ffffffff815dbf4d)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - fs/ext4/fsmap.c:ext4_getfsmap_find_fixed_metadata
  - fs/ext4/fsmap.c:ext4_getfsmap_find_fixed_metadata
  - fs/ext4/fsmap.c:ext4_getfsmap_find_fixed_metadata
  - fs/ext4/fsmap.c:ext4_getfsmap_find_fixed_metadata
  - fs/ext4/fsmap.c:ext4_getfsmap_find_fixed_metadata
  - fs/ext4/fsmap.c:ext4_getfsmap_find_fixed_metadata
```
```
In fs/ext4/hash.c (ffffffff815de1d5)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - fs/ext4/hash.c:ext4fs_dirhash
```
```
In fs/ext4/inline.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In fs/ext4/mballoc.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In fs/ext4/namei.c (ffffffff8160c5ee)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_fname_setup_ci_filename
```
```
In fs/ext4/resize.c (ffffffff8161552f)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - fs/ext4/resize.c:alloc_flex_gd
```
```
In fs/ext4/super.c (ffffffff81637d12)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_register_li_request
  - fs/ext4/super.c:ext4_register_li_request
  - fs/ext4/super.c:parse_apply_sb_mount_options
  - fs/ext4/super.c:parse_apply_sb_mount_options
  - fs/ext4/super.c:ext4_init_fs_context
```
```
In fs/ext4/sysfs.c (ffffffff83925bd1)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - fs/ext4/sysfs.c:ext4_init_sysfs
```
```
In fs/ext4/xattr.c (ffffffff8163e7e3)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_expand_inode_array
  - fs/ext4/xattr.c:ext4_xattr_move_to_block
  - fs/ext4/xattr.c:ext4_xattr_move_to_block
```
```
In fs/ext4/fast_commit.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In fs/ext4/orphan.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In fs/ext4/acl.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In fs/jbd2/revoke.c (ffffffff81653e2b)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:find_revoke_record
  - fs/jbd2/revoke.c:insert_revoke_hash
```
```
In fs/jbd2/journal.c (ffffffff8165ada5)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - fs/jbd2/journal.c:journal_init_common
  - fs/jbd2/journal.c:jbd2_seq_info_open
  - fs/jbd2/journal.c:jbd2_seq_info_open
```
```
In fs/squashfs/cache.c (ffffffff8165e1e6)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - fs/squashfs/cache.c:squashfs_cache_init
  - fs/squashfs/cache.c:squashfs_cache_init
```
```
In fs/squashfs/dir.c (ffffffff8165e888)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - fs/squashfs/dir.c:squashfs_readdir
```
```
In fs/squashfs/file.c (ffffffff8165f2c9)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - fs/squashfs/file.c:read_indexes
```
```
In fs/squashfs/namei.c (ffffffff81661862)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - fs/squashfs/namei.c:squashfs_lookup
  - fs/squashfs/namei.c:get_dir_index_using_name
```
```
In fs/squashfs/super.c (ffffffff81662120)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - fs/squashfs/super.c:squashfs_init_fs_context
  - fs/squashfs/super.c:squashfs_fill_super
```
```
In fs/squashfs/decompressor.c (ffffffff816630aa)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - fs/squashfs/decompressor.c:squashfs_decompressor_setup
```
```
In fs/squashfs/page_actor.c (ffffffff816634d5)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - fs/squashfs/page_actor.c:squashfs_page_actor_init_special
  - fs/squashfs/page_actor.c:squashfs_page_actor_init_special
  - fs/squashfs/page_actor.c:squashfs_page_actor_init
```
```
In fs/squashfs/file_direct.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In fs/squashfs/decompressor_single.c (ffffffff81663c2c)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - fs/squashfs/decompressor_single.c:squashfs_decompressor_create
```
```
In fs/squashfs/decompressor_multi.c (ffffffff81663f53)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - fs/squashfs/decompressor_multi.c:squashfs_decompress
  - fs/squashfs/decompressor_multi.c:squashfs_decompressor_create
  - fs/squashfs/decompressor_multi.c:squashfs_decompressor_create
```
```
In fs/squashfs/xattr.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In fs/squashfs/lz4_wrapper.c (ffffffff81665261)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - fs/squashfs/lz4_wrapper.c:lz4_init
```
```
In fs/squashfs/lzo_wrapper.c (ffffffff81665681)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - fs/squashfs/lzo_wrapper.c:lzo_init
```
```
In fs/squashfs/xz_wrapper.c (ffffffff81665a9a)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - fs/squashfs/xz_wrapper.c:squashfs_xz_init
  - fs/squashfs/xz_wrapper.c:squashfs_xz_comp_opts
```
```
In fs/squashfs/zlib_wrapper.c (ffffffff81665ded)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - fs/squashfs/zlib_wrapper.c:zlib_init
```
```
In fs/squashfs/zstd_wrapper.c (ffffffff8166619e)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - fs/squashfs/zstd_wrapper.c:zstd_init
```
```
In fs/ramfs/inode.c (ffffffff81666440)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - fs/ramfs/inode.c:ramfs_init_fs_context
```
```
In fs/hugetlbfs/inode.c (ffffffff81666fd6)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_init_fs_context
  - fs/hugetlbfs/inode.c:hugetlbfs_fill_super
```
```
In fs/fat/inode.c (ffffffff81674257)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
```
```
In fs/fat/namei_vfat.c (ffffffff816788f9)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - fs/fat/namei_vfat.c:vfat_add_entry
  - fs/fat/namei_vfat.c:vfat_hashi
```
```
In fs/ecryptfs/inode.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In fs/ecryptfs/mmap.c (ffffffff8167e3dd)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - fs/ecryptfs/mmap.c:ecryptfs_write_inode_size_to_metadata
```
```
In fs/ecryptfs/crypto.c (ffffffff81681a7d)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_encrypt_and_encode_filename
```
```
In fs/ecryptfs/keystore.c (ffffffff816849b4)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:ecryptfs_parse_tag_70_packet
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
```
In fs/ecryptfs/messaging.c (ffffffff81686b9b)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - fs/ecryptfs/messaging.c:ecryptfs_spawn_daemon
  - fs/ecryptfs/messaging.c:ecryptfs_spawn_daemon
  - fs/ecryptfs/messaging.c:ecryptfs_find_daemon_by_euid
```
```
In fs/ecryptfs/miscdev.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In fs/unicode/utf8-core.c (ffffffff8168a531)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - fs/unicode/utf8-core.c:utf8_load
  - fs/unicode/utf8-core.c:utf8_casefold_hash
```
```
In fs/fuse/dev.c (ffffffff8168dcf6)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_do_write
  - fs/fuse/dev.c:fuse_notify_delete
  - fs/fuse/dev.c:fuse_notify_inval_entry
  - fs/fuse/dev.c:fuse_dev_do_read
```
```
In fs/fuse/dir.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In fs/fuse/file.c (ffffffff81699521)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - fs/fuse/file.c:fuse_direct_IO
  - fs/fuse/file.c:fuse_writepage_args_alloc
  - fs/fuse/file.c:fuse_writepage_args_alloc
  - fs/fuse/file.c:fuse_io_alloc
```
```
In fs/fuse/inode.c (ffffffff8169cd00)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_init_fs_context
  - fs/fuse/inode.c:fuse_get_tree
  - fs/fuse/inode.c:fuse_get_tree
  - fs/fuse/inode.c:fuse_get_tree_submount
  - fs/fuse/inode.c:fuse_dev_alloc
  - fs/fuse/inode.c:fuse_dev_alloc
  - fs/fuse/inode.c:fuse_send_init
  - fs/fuse/inode.c:fuse_sync_bucket_alloc
```
```
In fs/fuse/acl.c (ffffffff816a0ab0)
Location: include/linux/hash.h:74
Inline: True
```
```
In fs/fuse/ioctl.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In fs/fuse/dax.c (ffffffff816a55da)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - fs/fuse/dax.c:fuse_dax_conn_alloc
```
```
In fs/debugfs/inode.c (ffffffff816a6faa)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - fs/debugfs/inode.c:debugfs_create_automount
  - fs/debugfs/inode.c:debug_fill_super
```
```
In fs/debugfs/file.c (ffffffff816a92c0)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - fs/debugfs/file.c:full_proxy_open
  - fs/debugfs/file.c:debugfs_file_get
```
```
In fs/tracefs/inode.c (ffffffff816aa479)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - fs/tracefs/inode.c:trace_fill_super
```
```
In fs/tracefs/event_inode.c (ffffffff816abdc2)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - fs/tracefs/event_inode.c:eventfs_create_events_dir
  - fs/tracefs/event_inode.c:eventfs_create_dir
```
```
In fs/pstore/inode.c (ffffffff816aca83)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - fs/pstore/inode.c:pstore_mkfile
  - fs/pstore/inode.c:pstore_ftrace_seq_start
```
```
In fs/pstore/platform.c (ffffffff816adce4)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - fs/pstore/platform.c:pstore_get_backend_records
```
```
In fs/efivarfs/inode.c (ffffffff816ae1d1)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - fs/efivarfs/inode.c:efivarfs_create
```
```
In fs/efivarfs/file.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In fs/efivarfs/super.c (ffffffff816aef04)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - fs/efivarfs/super.c:efivarfs_init_fs_context
  - fs/efivarfs/super.c:efivarfs_callback
  - fs/efivarfs/super.c:efivarfs_d_hash
```
```
In fs/efivarfs/vars.c (ffffffff816afac7)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - fs/efivarfs/vars.c:efivar_init
```
```
In ipc/util.c (ffffffff83927404)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - ipc/util.c:ipc_init_proc_interface
```
```
In ipc/msgutil.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In ipc/msg.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In ipc/sem.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In ipc/shm.c (ffffffff816bc871)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - ipc/shm.c:do_shmat
```
```
In ipc/mqueue.c (ffffffff816c088e)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - ipc/mqueue.c:do_mq_timedreceive
  - ipc/mqueue.c:do_mq_timedsend
  - ipc/mqueue.c:mqueue_init_fs_context
  - ipc/mqueue.c:msg_insert
```
```
In ipc/namespace.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In security/keys/key.c (ffffffff816c3a3e)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - security/keys/key.c:key_user_lookup
```
```
In security/keys/keyring.c (ffffffff816c5590)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - security/keys/keyring.c:keyring_restrict
```
```
In security/keys/keyctl.c (ffffffff816c99ef)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_watch_key
  - security/keys/keyctl.c:keyctl_watch_key
```
```
In security/keys/request_key_auth.c (ffffffff816ccdb7)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - security/keys/request_key_auth.c:request_key_auth_new
```
```
In security/keys/user_defined.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In security/keys/dh.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In security/keys/keyctl_pkey.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In security/keys/trusted-keys/trusted_core.c (ffffffff816cfb59)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - security/keys/trusted-keys/trusted_core.c:trusted_payload_alloc
```
```
In security/keys/trusted-keys/trusted_tpm1.c (ffffffff816d059a)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - security/keys/trusted-keys/trusted_tpm1.c:trusted_options_alloc
  - security/keys/trusted-keys/trusted_tpm1.c:tpm_seal
```
```
In security/keys/trusted-keys/trusted_tpm2.c (ffffffff816d2800)
Location: include/linux/hash.h:74
Inline: True
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff816d5034)
Location: include/linux/hash.h:74
Inline: True
```
```
In security/commoncap.c (ffffffff816d691a)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - security/commoncap.c:cap_convert_nscap
  - security/commoncap.c:cap_inode_getsecurity
  - security/commoncap.c:cap_inode_getsecurity
```
```
In security/security.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In security/selinux/avc.c (ffffffff8392a11c)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_add_callback
```
```
In security/selinux/hooks.c (ffffffff816e8b70)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_perf_event_alloc
  - security/selinux/hooks.c:selinux_bpf_prog_alloc
  - security/selinux/hooks.c:selinux_bpf_map_alloc
  - security/selinux/hooks.c:selinux_ib_alloc_security
  - security/selinux/hooks.c:selinux_tun_dev_alloc_security
  - security/selinux/hooks.c:inode_doinit_use_xattr
```
```
In security/selinux/selinuxfs.c (ffffffff816f375c)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - security/selinux/selinuxfs.c:sel_fill_super
  - security/selinux/selinuxfs.c:sel_open_policy
```
```
In security/selinux/netif.c (ffffffff816f5176)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - security/selinux/netif.c:sel_netif_sid_slow
```
```
In security/selinux/netnode.c (ffffffff816f55a3)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - security/selinux/netnode.c:sel_netnode_sid
```
```
In security/selinux/netport.c (ffffffff816f5ab3)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - security/selinux/netport.c:sel_netport_sid
```
```
In security/selinux/ss/hashtab.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In security/selinux/ss/sidtab.c (ffffffff816f7ec7)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - security/selinux/ss/sidtab.c:sidtab_convert_tree
  - security/selinux/ss/sidtab.c:sidtab_convert_tree
  - security/selinux/ss/sidtab.c:sidtab_do_lookup
  - security/selinux/ss/sidtab.c:sidtab_do_lookup
  - security/selinux/ss/sidtab.c:sidtab_do_lookup
  - security/selinux/ss/sidtab.c:sidtab_do_lookup
```
```
In security/selinux/ss/policydb.c (ffffffff81701205)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:policydb_read
  - security/selinux/ss/policydb.c:ocontext_read
  - security/selinux/ss/policydb.c:genfs_read
  - security/selinux/ss/policydb.c:genfs_read
  - security/selinux/ss/policydb.c:filename_trans_read_helper
  - security/selinux/ss/policydb.c:filename_trans_read_helper
  - security/selinux/ss/policydb.c:filename_trans_read_helper_compat
  - security/selinux/ss/policydb.c:range_read
  - security/selinux/ss/policydb.c:range_read
  - security/selinux/ss/policydb.c:cat_read
  - security/selinux/ss/policydb.c:sens_read
  - security/selinux/ss/policydb.c:sens_read
  - security/selinux/ss/policydb.c:user_read
  - security/selinux/ss/policydb.c:type_read
  - security/selinux/ss/policydb.c:role_read
  - security/selinux/ss/policydb.c:class_read
  - security/selinux/ss/policydb.c:read_cons_helper
  - security/selinux/ss/policydb.c:read_cons_helper
  - security/selinux/ss/policydb.c:read_cons_helper
  - security/selinux/ss/policydb.c:common_read
```
```
In security/selinux/ss/services.c (ffffffff817091c1)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_netlbl_secattr_to_sid
  - security/selinux/ss/services.c:security_netlbl_secattr_to_sid
  - security/selinux/ss/services.c:security_get_user_sids
  - security/selinux/ss/services.c:security_load_policy
  - security/selinux/ss/services.c:security_load_policy
  - security/selinux/ss/services.c:security_load_policy
```
```
In security/selinux/ss/conditional.c (ffffffff8170a368)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - security/selinux/ss/conditional.c:cond_read_bool
```
```
In security/selinux/xfrm.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In security/selinux/netlabel.c (ffffffff8170cd7d)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - security/selinux/netlabel.c:selinux_netlbl_sock_genattr
```
```
In security/selinux/ibpkey.c (ffffffff8170dea4)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - security/selinux/ibpkey.c:sel_ib_pkey_sid
```
```
In security/selinux/ima.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In security/smack/smack_lsm.c (ffffffff81710ab8)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_cred_prepare
```
```
In security/smack/smack_access.c (ffffffff8171635a)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - security/smack/smack_access.c:smk_import_entry
  - security/smack/smack_access.c:smack_populate_secattr
```
```
In security/smack/smackfs.c (ffffffff817185b6)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_parse_label_list
  - security/smack/smackfs.c:smk_write_net6addr
  - security/smack/smackfs.c:smk_write_net4addr
  - security/smack/smackfs.c:smk_cipso_doi
```
```
In security/tomoyo/audit.c (ffffffff8171c6af)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - security/tomoyo/audit.c:tomoyo_write_log2
  - security/tomoyo/audit.c:tomoyo_print_header
  - security/tomoyo/audit.c:tomoyo_print_bprm
```
```
In security/tomoyo/common.c (ffffffff817232b1)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - security/tomoyo/common.c:tomoyo_open_control
  - security/tomoyo/common.c:tomoyo_open_control
  - security/tomoyo/common.c:tomoyo_write_profile
```
```
In security/tomoyo/condition.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In security/tomoyo/domain.c (ffffffff81727112)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - security/tomoyo/domain.c:tomoyo_dump_page
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - security/tomoyo/domain.c:tomoyo_find_next_domain
  - security/tomoyo/domain.c:tomoyo_environ
```
```
In security/tomoyo/memory.c (ffffffff8172b29c)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - security/tomoyo/memory.c:tomoyo_get_name
```
```
In security/tomoyo/realpath.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In security/apparmor/apparmorfs.c (ffffffff817351d9)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - security/apparmor/apparmorfs.c:ns_revision_open
```
```
In security/apparmor/lib.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In security/apparmor/match.c (ffffffff8173b031)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - security/apparmor/match.c:aa_dfa_unpack
```
```
In security/apparmor/domain.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In security/apparmor/policy.c (ffffffff81743d30)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - security/apparmor/policy.c:aa_alloc_profile
  - security/apparmor/policy.c:aa_alloc_ruleset
  - security/apparmor/policy.c:aa_alloc_pdb
```
```
In security/apparmor/policy_unpack.c (ffffffff81749d05)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - security/apparmor/policy_unpack.c:aa_unpack
  - security/apparmor/policy_unpack.c:unpack_profile
  - security/apparmor/policy_unpack.c:aa_loaddata_alloc
```
```
In security/apparmor/procattr.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In security/apparmor/lsm.c (ffffffff8392bc8f)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - security/apparmor/lsm.c:aa_setup_dfa_engine
```
```
In security/apparmor/policy_ns.c (ffffffff81755ce1)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - security/apparmor/policy_ns.c:alloc_ns
```
```
In security/apparmor/label.c (ffffffff817574cf)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - security/apparmor/label.c:aa_alloc_proxy
```
```
In security/apparmor/mount.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In security/apparmor/notify.c (ffffffff817661ee)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - security/apparmor/notify.c:aa_clone_ruleset
  - security/apparmor/notify.c:aa_new_listener
  - security/apparmor/notify.c:aa_register_listener_proxy
```
```
In security/apparmor/crypto.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In security/yama/yama_lsm.c (ffffffff817673d9)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - security/yama/yama_lsm.c:yama_ptracer_add
  - security/yama/yama_lsm.c:report_access
```
```
In security/safesetid/securityfs.c (ffffffff8176893e)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - security/safesetid/securityfs.c:handle_policy_update
  - security/safesetid/securityfs.c:handle_policy_update
  - security/safesetid/securityfs.c:handle_policy_update
```
```
In security/device_cgroup.c (ffffffff81769bec)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - security/device_cgroup.c:devcgroup_css_alloc
```
```
In security/landlock/object.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In security/landlock/ruleset.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In security/integrity/digsig.c (ffffffff8392ccf6)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - security/integrity/digsig.c:integrity_init_keyring
```
```
In security/integrity/platform_certs/load_uefi.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In security/integrity/ima/ima_queue.c (ffffffff8176fc4c)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - security/integrity/ima/ima_queue.c:ima_add_digest_entry
```
```
In security/integrity/ima/ima_crypto.c (ffffffff81772cd1)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash_tfm
```
```
In security/integrity/ima/ima_api.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In security/integrity/ima/ima_policy.c (ffffffff81777aa2)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:ima_parse_add_rule
```
```
In security/integrity/ima/ima_template.c (ffffffff81778bbf)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - security/integrity/ima/ima_template.c:ima_restore_measurement_list
```
```
In security/integrity/ima/ima_template_lib.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In security/integrity/ima/ima_appraise.c (ffffffff8177b48b)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - security/integrity/ima/ima_appraise.c:ima_inode_setxattr
```
```
In security/integrity/ima/ima_modsig.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In security/integrity/ima/ima_queue_keys.c (ffffffff8177bdfc)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - security/integrity/ima/ima_queue_keys.c:ima_queue_key
```
```
In security/integrity/evm/evm_main.c (ffffffff8177c5e0)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - security/integrity/evm/evm_main.c:evm_inode_init_security
```
```
In security/integrity/evm/evm_crypto.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In security/integrity/evm/evm_secfs.c (ffffffff8177e6a3)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - security/integrity/evm/evm_secfs.c:evm_write_xattrs
```
```
In crypto/api.c (ffffffff8177eedc)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - crypto/api.c:crypto_larval_alloc
```
```
In crypto/cipher.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In crypto/aead.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In crypto/geniv.c (ffffffff817831e5)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - crypto/geniv.c:aead_geniv_alloc
```
```
In crypto/lskcipher.c (ffffffff81784087)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - crypto/lskcipher.c:lskcipher_alloc_instance_simple
  - crypto/lskcipher.c:crypto_lskcipher_crypt_unaligned
  - crypto/lskcipher.c:crypto_lskcipher_crypt_unaligned
```
```
In crypto/skcipher.c (ffffffff817854d2)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - crypto/skcipher.c:skcipher_alloc_instance_simple
  - crypto/skcipher.c:skcipher_next_copy
```
```
In crypto/ahash.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In crypto/akcipher.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In crypto/dh.c (ffffffff8178a4f7)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - crypto/dh.c:__dh_safe_prime_create
```
```
In crypto/rsa-pkcs1pad.c (ffffffff8178c592)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - crypto/rsa-pkcs1pad.c:pkcs1pad_create
```
```
In crypto/acompress.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In crypto/algboss.c (ffffffff8178de64)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - crypto/algboss.c:cryptomgr_schedule_probe
```
```
In crypto/hmac.c (ffffffff8178e8c0)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - crypto/hmac.c:hmac_create
```
```
In crypto/ecb.c (ffffffff817926a2)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - crypto/ecb.c:lskcipher_alloc_instance_simple2
```
```
In crypto/cts.c (ffffffff817933f0)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - crypto/cts.c:crypto_cts_create
```
```
In crypto/xts.c (ffffffff817944a1)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - crypto/xts.c:xts_create
```
```
In crypto/ctr.c (ffffffff81794b40)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - crypto/ctr.c:crypto_rfc3686_create
```
```
In crypto/gcm.c (ffffffff83930410)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_module_init
  - crypto/gcm.c:crypto_rfc4543_create
  - crypto/gcm.c:crypto_rfc4106_create
  - crypto/gcm.c:crypto_gcm_create_common
```
```
In crypto/deflate.c (ffffffff8179939e)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - crypto/deflate.c:deflate_alloc_ctx
```
```
In crypto/rng.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In crypto/drbg.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In crypto/jitterentropy-kcapi.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In crypto/asymmetric_keys/asymmetric_type.c (ffffffff817a0f72)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - crypto/asymmetric_keys/asymmetric_type.c:asymmetric_lookup_restriction
  - crypto/asymmetric_keys/asymmetric_type.c:asymmetric_lookup_restriction
  - crypto/asymmetric_keys/asymmetric_type.c:asymmetric_lookup_restriction
```
```
In crypto/asymmetric_keys/public_key.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In crypto/asymmetric_keys/x509_cert_parser.c (ffffffff817a30c1)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_cert_parse
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_cert_parse
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_cert_parse
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_cert_parse
```
```
In crypto/asymmetric_keys/x509_public_key.c (ffffffff817a4315)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - crypto/asymmetric_keys/x509_public_key.c:x509_key_preparse
```
```
In crypto/asymmetric_keys/pkcs7_parser.c (ffffffff817a5590)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_note_signed_info
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_note_signed_info
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_parse_message
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_parse_message
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_parse_message
  - crypto/asymmetric_keys/pkcs7_parser.c:pkcs7_parse_message
```
```
In crypto/asymmetric_keys/pkcs7_verify.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In crypto/asymmetric_keys/verify_pefile.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In block/bdev.c (ffffffff817a88e1)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - block/bdev.c:bdev_open_by_dev
```
```
In block/fops.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In block/bio.c (ffffffff817acdb8)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - block/bio.c:bioset_init
```
```
In block/elevator.c (ffffffff817aebf4)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - block/elevator.c:elv_rqhash_find
  - block/elevator.c:elevator_alloc
```
```
In block/blk-core.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In block/blk-flush.c (ffffffff817b77c0)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - block/blk-flush.c:blk_alloc_flush_queue
```
```
In block/blk-map.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In block/blk-mq.c (ffffffff817c7cd5)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - block/blk-mq.c:__blk_mq_update_nr_hw_queues
  - block/blk-mq.c:blk_mq_alloc_tag_set
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - block/blk-mq.c:blk_mq_alloc_hctx
```
```
In block/blk-mq-tag.c (ffffffff817cade6)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_init_tags
```
```
In block/blk-stat.c (ffffffff817cb99c)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - block/blk-stat.c:blk_alloc_queue_stats
  - block/blk-stat.c:blk_stat_alloc_callback
```
```
In block/genhd.c (ffffffff817d127e)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - block/genhd.c:__alloc_disk_node
  - block/genhd.c:disk_seqf_start
  - block/genhd.c:__register_blkdev
```
```
In block/badblocks.c (ffffffff817d23f2)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - block/badblocks.c:devm_init_badblocks
  - block/badblocks.c:badblocks_init
```
```
In block/partitions/core.c (ffffffff817d42ac)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - block/partitions/core.c:check_partition
```
```
In block/partitions/aix.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In block/partitions/cmdline.c (ffffffff817d779d)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - block/partitions/cmdline.c:parse_parts
  - block/partitions/cmdline.c:parse_subpart
```
```
In block/partitions/ldm.c (ffffffff817da9e9)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - block/partitions/ldm.c:ldm_partition
  - block/partitions/ldm.c:ldm_ldmdb_add
  - block/partitions/ldm.c:ldm_validate_tocblocks
  - block/partitions/ldm.c:ldm_validate_privheads
  - block/partitions/ldm.c:ldm_validate_privheads
```
```
In block/partitions/efi.c (ffffffff817de721)
Location: include/linux/hash.h:74
Inline: True
```
```
In block/disk-events.c (ffffffff817e0cff)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - block/disk-events.c:disk_alloc_events
```
```
In block/blk-ia-ranges.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In block/bsg.c (ffffffff817e16fc)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - block/bsg.c:bsg_register_queue
```
```
In block/bsg-lib.c (ffffffff817e2330)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - block/bsg-lib.c:bsg_setup_queue
  - block/bsg-lib.c:bsg_init_rq
```
```
In block/blk-cgroup.c (ffffffff817e43c2)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - block/blk-cgroup.c:blkcg_css_alloc
  - block/blk-cgroup.c:blkg_alloc
```
```
In block/blk-throttle.c (ffffffff817ec77e)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_init
  - block/blk-throttle.c:throtl_pd_alloc
```
```
In block/blk-ioprio.c (ffffffff817ecd52)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - block/blk-ioprio.c:ioprio_alloc_cpd
  - block/blk-ioprio.c:ioprio_alloc_pd
```
```
In block/blk-iocost.c (ffffffff817f00f2)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_cpd_alloc
  - block/blk-iocost.c:blk_iocost_init
```
```
In block/mq-deadline.c (ffffffff817f64f9)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - block/mq-deadline.c:dd_init_sched
```
```
In block/bio-integrity.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In block/blk-zoned.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In block/blk-wbt.c (ffffffff817ff6c5)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - block/blk-wbt.c:wbt_init
```
```
In block/sed-opal.c (ffffffff81806d4c)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - block/sed-opal.c:sed_ioctl
  - block/sed-opal.c:init_opal_dev
  - block/sed-opal.c:init_opal_dev
  - block/sed-opal.c:init_opal_dev
```
```
In block/blk-crypto-profile.c (ffffffff81808a95)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - block/blk-crypto-profile.c:blk_crypto_get_keyslot
```
```
In block/blk-crypto-sysfs.c (ffffffff818090f2)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - block/blk-crypto-sysfs.c:blk_crypto_sysfs_register
```
```
In block/blk-crypto-fallback.c (ffffffff818095e8)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - block/blk-crypto-fallback.c:blk_crypto_fallback_init
```
```
In block/holder.c (ffffffff8180aaa7)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - block/holder.c:bd_link_disk_holder
```
```
In io_uring/io_uring.c (ffffffff81812b0e)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_drain_req
  - io_uring/io_uring.c:io_ring_ctx_alloc
```
```
In io_uring/xattr.c (ffffffff81817959)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - io_uring/xattr.c:io_fsetxattr_prep
  - io_uring/xattr.c:__io_getxattr_prep
```
```
In io_uring/sqpoll.c (ffffffff8181f405)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - io_uring/sqpoll.c:io_get_sq_data
```
```
In io_uring/tctx.c (ffffffff81821144)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - io_uring/tctx.c:__io_uring_add_tctx_node
  - io_uring/tctx.c:io_uring_alloc_task_context
  - io_uring/tctx.c:io_uring_alloc_task_context
```
```
In io_uring/poll.c (ffffffff8182309c)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - io_uring/poll.c:io_arm_poll_handler
  - io_uring/poll.c:io_poll_add_hash
  - io_uring/poll.c:io_poll_add_hash
  - io_uring/poll.c:__io_queue_proc
  - io_uring/poll.c:io_poll_task_func
```
```
In io_uring/kbuf.c (ffffffff818254db)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - io_uring/kbuf.c:io_register_pbuf_ring
  - io_uring/kbuf.c:io_init_bl_list
```
```
In io_uring/rsrc.c (ffffffff81825c70)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - io_uring/rsrc.c:io_rsrc_data_alloc
  - io_uring/rsrc.c:io_rsrc_node_alloc
```
```
In io_uring/register.c (ffffffff8182af39)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - io_uring/register.c:io_eventfd_register
```
```
In io_uring/io-wq.c (ffffffff8182e558)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - io_uring/io-wq.c:io_wq_create
  - io_uring/io-wq.c:io_wq_hash_work
  - io_uring/io-wq.c:create_io_worker
```
```
In io_uring/futex.c (ffffffff8182f964)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - io_uring/futex.c:io_futex_wait
```
```
In lib/bitmap.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In lib/scatterlist.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In lib/iov_iter.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In lib/kfifo.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In lib/percpu-refcount.c (ffffffff8185cda1)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - lib/percpu-refcount.c:percpu_ref_init
```
```
In lib/rhashtable.c (ffffffff8185ddc7)
Location: include/linux/hash.h:74
Inline: True
```
```
In lib/once.c (ffffffff8185faec)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - lib/once.c:once_disable_jump
```
```
In lib/string_helpers.c (ffffffff81862c92)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - lib/string_helpers.c:kstrdup_quotable_file
  - lib/string_helpers.c:kstrdup_quotable_cmdline
```
```
In lib/crypto/gf128mul.c (ffffffff81866f5c)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - lib/crypto/gf128mul.c:gf128mul_init_4k_bbe
  - lib/crypto/gf128mul.c:gf128mul_init_4k_lle
  - lib/crypto/gf128mul.c:gf128mul_init_64k_bbe
  - lib/crypto/gf128mul.c:gf128mul_init_64k_bbe
```
```
In lib/crypto/mpi/ec.c (ffffffff8186ce9d)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - lib/crypto/mpi/ec.c:mpi_point_new
```
```
In lib/crypto/mpi/mpicoder.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In lib/crypto/mpi/mpi-mod.c (ffffffff8187299d)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - lib/crypto/mpi/mpi-mod.c:mpi_barrett_init
```
```
In lib/crypto/mpi/mpih-mul.c (ffffffff81875008)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - lib/crypto/mpi/mpih-mul.c:mpihelp_mul_karatsuba_case
```
```
In lib/crypto/mpi/mpiutil.c (ffffffff81875e01)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - lib/crypto/mpi/mpiutil.c:mpi_alloc
```
```
In lib/assoc_array.c (ffffffff8187cf4e)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_clear
  - lib/assoc_array.c:assoc_array_delete
  - lib/assoc_array.c:assoc_array_delete
  - lib/assoc_array.c:assoc_array_insert
  - lib/assoc_array.c:assoc_array_insert
```
```
In lib/genalloc.c (ffffffff8187fb4c)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - lib/genalloc.c:gen_pool_create
```
```
In lib/zlib_inflate/infutil.c (ffffffff818834ac)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - lib/zlib_inflate/infutil.c:zlib_inflate_blob
```
```
In lib/xz/xz_dec_stream.c (ffffffff8191c8a1)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - lib/xz/xz_dec_stream.c:xz_dec_init
```
```
In lib/xz/xz_dec_lzma2.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In lib/xz/xz_dec_bcj.c (ffffffff8191f40f)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - lib/xz/xz_dec_bcj.c:xz_dec_bcj_create
```
```
In lib/error-inject.c (ffffffff81920311)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - lib/error-inject.c:populate_error_injection_list
```
```
In lib/dynamic_debug.c (ffffffff81920e59)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - lib/dynamic_debug.c:ddebug_add_module
```
```
In lib/nlattr.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In lib/cpu_rmap.c (ffffffff819259ec)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - lib/cpu_rmap.c:irq_cpu_rmap_add
```
```
In lib/digsig.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In lib/sbitmap.c (ffffffff8192d182)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - lib/sbitmap.c:sbitmap_queue_init_node
```
```
In lib/group_cpus.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In lib/pldmfw/pldmfw.c (ffffffff8192ef3f)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - lib/pldmfw/pldmfw.c:pldmfw_flash_image
  - lib/pldmfw/pldmfw.c:pldm_parse_components
  - lib/pldmfw/pldmfw.c:pldm_parse_one_record
  - lib/pldmfw/pldmfw.c:pldm_parse_desc_tlvs
```
```
In drivers/phy/phy-core.c (ffffffff81932341)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/phy/phy-core.c:__of_phy_provider_register
  - drivers/phy/phy-core.c:phy_create
  - drivers/phy/phy-core.c:phy_create_lookup
```
```
In drivers/pinctrl/core.c (ffffffff8193497d)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/pinctrl/core.c:pinctrl_register_mappings
  - drivers/pinctrl/core.c:create_pinctrl
  - drivers/pinctrl/core.c:add_setting
  - drivers/pinctrl/core.c:pinctrl_register_pins
```
```
In drivers/gpio/gpiolib.c (ffffffff81947a01)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiochip_add_pin_range
  - drivers/gpio/gpiolib.c:gpiochip_add_pingroup_range
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
```
```
In drivers/gpio/gpiolib-cdev.c (ffffffff8195107a)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-cdev.c:lineevent_create
  - drivers/gpio/gpiolib-cdev.c:linehandle_create
```
```
In drivers/gpio/gpiolib-sysfs.c (ffffffff81953149)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-sysfs.c:gpiod_export
```
```
In drivers/gpio/gpiolib-acpi.c (ffffffff81955bb3)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_adr_space_handler
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_alloc_event
```
```
In drivers/pwm/core.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In drivers/pwm/sysfs.c (ffffffff8195bfb1)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/pwm/sysfs.c:pwm_export_child
```
```
In drivers/pci/bus.c (ffffffff8195f034)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/pci/bus.c:pci_bus_add_resource
```
```
In drivers/pci/probe.c (ffffffff81963131)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_bus_insert_busn_res
  - drivers/pci/probe.c:pci_alloc_dev
```
```
In drivers/pci/pci.c (ffffffff81966eaa)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_pme_active
```
```
In drivers/pci/pci-driver.c (ffffffff819729d1)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/pci/pci-driver.c:new_id_store
  - drivers/pci/pci-driver.c:pci_add_dynid
```
```
In drivers/pci/pci-sysfs.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In drivers/pci/vpd.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In drivers/pci/setup-bus.c (ffffffff8197bf4e)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:__dev_sort_resources
  - drivers/pci/setup-bus.c:add_to_list
```
```
In drivers/pci/pcie/portdrv.c (ffffffff81983d51)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/pci/pcie/portdrv.c:pcie_portdrv_probe
```
```
In drivers/pci/pcie/rcec.c (ffffffff81984493)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/pci/pcie/rcec.c:pci_rcec_init
```
```
In drivers/pci/pcie/aspm.c (ffffffff819869ef)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/pci/pcie/aspm.c:pcie_aspm_init_link_state
```
```
In drivers/pci/pcie/aer.c (ffffffff81989118)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/pci/pcie/aer.c:pci_aer_init
```
```
In drivers/pci/pcie/pme.c (ffffffff8198aada)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/pci/pcie/pme.c:pcie_pme_probe
```
```
In drivers/pci/proc.c (ffffffff8198d320)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/pci/proc.c:proc_bus_pci_open
```
```
In drivers/pci/slot.c (ffffffff8198de4a)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/pci/slot.c:pci_create_slot
```
```
In drivers/pci/quirks.c (ffffffff81996df8)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/pci/quirks.c:quirk_intel_qat_vf_cap
```
```
In drivers/pci/hotplug/cpci_hotplug_core.c (ffffffff81999bb3)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/pci/hotplug/cpci_hotplug_core.c:cpci_hp_register_bus
```
```
In drivers/pci/hotplug/pciehp_core.c (ffffffff8199b19d)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_core.c:pciehp_probe
```
```
In drivers/pci/hotplug/pciehp_hpc.c (ffffffff8199e2b1)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_hpc.c:pcie_init
```
```
In drivers/pci/hotplug/shpchp_core.c (ffffffff8199f0a0)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_core.c:shpc_probe
  - drivers/pci/hotplug/shpchp_core.c:init_slots
```
```
In drivers/pci/hotplug/shpchp_ctrl.c (ffffffff819a08ee)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/pci/hotplug/shpchp_ctrl.c:shpchp_queue_pushbutton_work
```
```
In drivers/pci/hotplug/acpiphp_core.c (ffffffff819a316d)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_core.c:acpiphp_register_hotplug_slot
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff819a4d87)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_enumerate_slots
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
```
```
In drivers/pci/iov.c (ffffffff819a670a)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/pci/iov.c:sriov_init
```
```
In drivers/pci/p2pdma.c (ffffffff819a93c4)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/pci/p2pdma.c:pci_p2pmem_alloc_sgl
  - drivers/pci/p2pdma.c:pci_p2pmem_find_many
```
```
In drivers/pci/vgaarb.c (ffffffff819aafa8)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/pci/vgaarb.c:vga_arb_open
  - drivers/pci/vgaarb.c:vga_arb_read
  - drivers/pci/vgaarb.c:vga_arbiter_add_pci_device
```
```
In drivers/pci/doe.c (ffffffff819acd1b)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/pci/doe.c:pci_doe_create_mb
```
```
In drivers/pci/endpoint/pci-ep-cfs.c (ffffffff819aed29)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_make
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_ep_cfs_add_epc_group
```
```
In drivers/pci/endpoint/pci-epc-core.c (ffffffff819b0388)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-epc-core.c:__pci_epc_create
```
```
In drivers/pci/endpoint/pci-epf-core.c (ffffffff819b10c1)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-epf-core.c:pci_epf_create
```
```
In drivers/pci/endpoint/pci-epc-mem.c (ffffffff819b1973)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/pci/endpoint/pci-epc-mem.c:pci_epc_multi_mem_init
```
```
In drivers/rapidio/rio.c (ffffffff819b9a87)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_register_scan
  - drivers/rapidio/rio.c:rio_add_mport_pw_handler
  - drivers/rapidio/rio.c:rio_request_outb_dbell
  - drivers/rapidio/rio.c:rio_request_inb_dbell
  - drivers/rapidio/rio.c:rio_request_inb_dbell
  - drivers/rapidio/rio.c:rio_request_outb_mbox
  - drivers/rapidio/rio.c:rio_request_inb_mbox
  - drivers/rapidio/rio.c:rio_alloc_net
```
```
In drivers/video/backlight/backlight.c (ffffffff819c2aef)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/video/backlight/backlight.c:backlight_device_register
```
```
In drivers/video/fbdev/core/fb_info.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In drivers/video/fbdev/core/fbmem.c (ffffffff819c41e1)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmem.c:do_register_framebuffer
```
```
In drivers/video/fbdev/core/fbcmap.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In drivers/video/fbdev/core/modedb.c (ffffffff819c6494)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/video/fbdev/core/modedb.c:fb_add_videomode
```
```
In drivers/video/fbdev/core/fbcvt.c (ffffffff819c66cc)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbcvt.c:fb_cvt_print_name
```
```
In drivers/video/fbdev/core/fbmon.c (ffffffff819c7c3c)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbmon.c:fb_get_mode
  - drivers/video/fbdev/core/fbmon.c:fb_create_modedb
  - drivers/video/fbdev/core/fbmon.c:calc_mode_timings
```
```
In drivers/video/fbdev/core/fbcon.c (ffffffff819cd7e2)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/video/fbdev/core/fbcon.c:fbcon_open
```
```
In drivers/video/fbdev/core/bitblit.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In drivers/video/fbdev/core/softcursor.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In drivers/video/fbdev/core/fbcon_rotate.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In drivers/video/fbdev/core/fbcon_cw.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In drivers/video/fbdev/core/fbcon_ud.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In drivers/video/fbdev/core/fbcon_ccw.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In drivers/video/fbdev/core/fb_io_fops.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In drivers/char/ipmi/ipmi_dmi.c (ffffffff83938321)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/char/ipmi/ipmi_dmi.c:scan_for_dmi_ipmi
```
```
In drivers/acpi/osl.c (ffffffff819e3d88)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/acpi/osl.c:acpi_os_create_semaphore
  - drivers/acpi/osl.c:acpi_hotplug_schedule
  - drivers/acpi/osl.c:acpi_os_execute
  - drivers/acpi/osl.c:acpi_os_map_iomem
```
```
In drivers/acpi/utils.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In drivers/acpi/nvs.c (ffffffff819e61d1)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/acpi/nvs.c:acpi_nvs_register
  - drivers/acpi/nvs.c:acpi_nvs_register
```
```
In drivers/acpi/wakeup.c (ffffffff819e66c8)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/acpi/wakeup.c:acpi_register_wakeup_handler
```
```
In drivers/acpi/glue.c (ffffffff819edadc)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/acpi/glue.c:acpi_bind_one
```
```
In drivers/acpi/scan.c (ffffffff819f2605)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_scan_table_notify
  - drivers/acpi/scan.c:acpi_scan_clear_dep
  - drivers/acpi/scan.c:acpi_scan_check_dep
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/scan.c:acpi_add_id
  - drivers/acpi/scan.c:acpi_device_add
```
```
In drivers/acpi/mipi-disco-img.c (ffffffff819f352c)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/acpi/mipi-disco-img.c:acpi_mipi_add_crs_csi2
```
```
In drivers/acpi/acpi_processor.c (ffffffff819f623c)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/acpi/acpi_processor.c:acpi_processor_add
```
```
In drivers/acpi/processor_pdc.c (ffffffff819f6c4e)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/acpi/processor_pdc.c:acpi_processor_alloc_pdc
  - drivers/acpi/processor_pdc.c:acpi_processor_alloc_pdc
  - drivers/acpi/processor_pdc.c:acpi_processor_alloc_pdc
```
```
In drivers/acpi/ec.c (ffffffff819f749d)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_alloc
  - drivers/acpi/ec.c:acpi_ec_submit_query
  - drivers/acpi/ec.c:acpi_ec_add_query_handler
```
```
In drivers/acpi/dock.c (ffffffff819fa7dc)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/acpi/dock.c:add_dock_dependent_device
```
```
In drivers/acpi/pci_root.c (ffffffff819fc8b8)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/acpi/pci_root.c:acpi_pci_root_add
```
```
In drivers/acpi/pci_link.c (ffffffff819fd73b)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/acpi/pci_link.c:acpi_pci_link_add
  - drivers/acpi/pci_link.c:acpi_pci_link_set
```
```
In drivers/acpi/pci_irq.c (ffffffff819fe505)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/acpi/pci_irq.c:acpi_pci_irq_check_entry
```
```
In drivers/acpi/acpi_lpss.c (ffffffff81a00650)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
```
```
In drivers/acpi/acpi_apd.c (ffffffff81a00d04)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/acpi/acpi_apd.c:acpi_apd_create_device
```
```
In drivers/acpi/acpi_platform.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In drivers/acpi/power.c (ffffffff81a0295e)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/acpi/power.c:acpi_add_power_resource
  - drivers/acpi/power.c:acpi_device_power_add_dependent
  - drivers/acpi/power.c:acpi_extract_power_resources
```
```
In drivers/acpi/sysfs.c (ffffffff81a04fdd)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/acpi/sysfs.c:acpi_tables_sysfs_init
  - drivers/acpi/sysfs.c:acpi_tables_sysfs_init
  - drivers/acpi/sysfs.c:acpi_sysfs_table_handler
```
```
In drivers/acpi/property.c (ffffffff81a077a4)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/acpi/property.c:acpi_data_add_props
  - drivers/acpi/property.c:acpi_nondev_subnode_extract
```
```
In drivers/acpi/x86/apple.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In drivers/acpi/x86/s2idle.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In drivers/acpi/acpi_lpat.c (ffffffff81a0a4de)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/acpi/acpi_lpat.c:acpi_lpat_get_conversion_table
```
```
In drivers/acpi/acpi_watchdog.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In drivers/acpi/prmt.c (ffffffff8393c842)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/acpi/prmt.c:acpi_parse_prmt
```
```
In drivers/acpi/acpi_pcc.c (ffffffff81a0b65d)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/acpi/acpi_pcc.c:acpi_pcc_address_space_setup
```
```
In drivers/acpi/acpi_adxl.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In drivers/acpi/acpica/dsfield.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In drivers/acpi/acpica/dsmethod.c (ffffffff81a0f052)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_call_control_method
```
```
In drivers/acpi/acpica/dsobject.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In drivers/acpi/acpica/dspkginit.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In drivers/acpi/acpica/dswstate.c (ffffffff81a16aaa)
Location: include/linux/hash.h:74
Inline: True
```
```
In drivers/acpi/acpica/evgpe.c (ffffffff81a18411)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/acpi/acpica/evgpe.c:acpi_ev_asynch_execute_gpe_method
```
```
In drivers/acpi/acpica/evgpeblk.c (ffffffff81a19693)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/acpi/acpica/evgpeblk.c:acpi_ev_create_gpe_block
```
```
In drivers/acpi/acpica/evgpeutil.c (ffffffff81a1a696)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/acpi/acpica/evgpeutil.c:acpi_ev_get_gpe_xrupt_block
```
```
In drivers/acpi/acpica/evglock.c (ffffffff81a1ab9c)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/acpi/acpica/evglock.c:acpi_ev_init_global_lock_handler
```
```
In drivers/acpi/acpica/evregion.c (ffffffff81a1c451)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/acpi/acpica/evregion.c:acpi_ev_execute_reg_method
```
```
In drivers/acpi/acpica/evrgnini.c (ffffffff81a1d754)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_data_table_region_setup
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_pci_config_region_setup
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_system_memory_region_setup
```
```
In drivers/acpi/acpica/evxface.c (ffffffff81a1f266)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/acpi/acpica/evxface.c:acpi_ev_install_gpe_handler
  - drivers/acpi/acpica/evxface.c:acpi_install_sci_handler
```
```
In drivers/acpi/acpica/evxfgpe.c (ffffffff81a213fd)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/acpi/acpica/evxfgpe.c:acpi_setup_gpe_for_wake
```
```
In drivers/acpi/acpica/exconfig.c (ffffffff81a225a1)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/acpi/acpica/exconfig.c:acpi_ex_load_op
```
```
In drivers/acpi/acpica/exfldio.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In drivers/acpi/acpica/exnames.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In drivers/acpi/acpica/exoparg3.c (ffffffff81a2b40a)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/acpi/acpica/exoparg3.c:acpi_ex_opcode_3A_0T_0R
```
```
In drivers/acpi/acpica/exregion.c (ffffffff81a2c4b5)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/acpi/acpica/exregion.c:acpi_ex_system_memory_space_handler
```
```
In drivers/acpi/acpica/exstorob.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In drivers/acpi/acpica/hwxface.c (ffffffff81a3477a)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/acpi/acpica/hwxface.c:acpi_get_sleep_type_data
```
```
In drivers/acpi/acpica/hwpci.c (ffffffff81a353b6)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/acpi/acpica/hwpci.c:acpi_hw_build_pci_list
```
```
In drivers/acpi/acpica/nsinit.c (ffffffff81a391ed)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsinit.c:acpi_ns_initialize_devices
```
```
In drivers/acpi/acpica/nsnames.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In drivers/acpi/acpica/nsparse.c (ffffffff81a3adff)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsparse.c:acpi_ns_execute_table
```
```
In drivers/acpi/acpica/nsutils.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In drivers/acpi/acpica/nsxfeval.c (ffffffff81a3feec)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsxfeval.c:acpi_evaluate_object
```
```
In drivers/acpi/acpica/nsxfname.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In drivers/acpi/acpica/rscreate.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In drivers/acpi/acpica/rsutils.c (ffffffff81a490fa)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/acpi/acpica/rsutils.c:acpi_rs_set_srs_method_data
```
```
In drivers/acpi/acpica/tbdata.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In drivers/acpi/acpica/tbutils.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In drivers/acpi/acpica/utaddress.c (ffffffff81a4dd7d)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/acpi/acpica/utaddress.c:acpi_ut_add_address_range
```
```
In drivers/acpi/acpica/utalloc.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In drivers/acpi/acpica/utcopy.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In drivers/acpi/acpica/uteval.c (ffffffff81a521b6)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/acpi/acpica/uteval.c:acpi_ut_evaluate_object
```
```
In drivers/acpi/acpica/utids.c (ffffffff81a53157)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/acpi/acpica/utids.c:acpi_ut_execute_CLS
```
```
In drivers/acpi/acpica/utmutex.c (ffffffff81a5445a)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_initialize
  - drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_initialize
  - drivers/acpi/acpica/utmutex.c:acpi_ut_mutex_initialize
```
```
In drivers/acpi/acpica/utobject.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In drivers/acpi/acpica/utosi.c (ffffffff81a55f89)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/acpi/acpica/utosi.c:acpi_ut_install_interface
```
```
In drivers/acpi/acpica/utxface.c (ffffffff81a584bf)
Location: include/linux/hash.h:74
Inline: True
```
```
In drivers/acpi/acpica/dbcmds.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In drivers/acpi/acpica/dbconvert.c (ffffffff81a5a983)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/acpi/acpica/dbconvert.c:acpi_db_encode_pld_buffer
  - drivers/acpi/acpica/dbconvert.c:acpi_db_convert_to_package
```
```
In drivers/acpi/acpica/dbexec.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In drivers/acpi/acpica/dbhistry.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In drivers/acpi/acpica/dbnames.c (ffffffff81a5f71a)
Location: include/linux/hash.h:74
Inline: True
```
```
In drivers/acpi/acpica/dbxface.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In drivers/acpi/ac.c (ffffffff81a62697)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/acpi/ac.c:acpi_ac_probe
```
```
In drivers/acpi/button.c (ffffffff81a62d86)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/acpi/button.c:acpi_button_add
```
```
In drivers/acpi/pci_slot.c (ffffffff81a64df6)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/acpi/pci_slot.c:register_slot
```
```
In drivers/acpi/processor_idle.c (ffffffff81a680a7)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/acpi/processor_idle.c:acpi_processor_power_init
```
```
In drivers/acpi/processor_throttling.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In drivers/acpi/processor_perflib.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In drivers/acpi/container.c (ffffffff81a6b969)
Location: include/linux/hash.h:74
Inline: True
```
```
In drivers/acpi/thermal.c (ffffffff81a6cc9c)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/acpi/thermal.c:acpi_thermal_add
```
```
In drivers/acpi/numa/hmat.c (ffffffff8393f0ed)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/acpi/numa/hmat.c:alloc_target
```
```
In drivers/acpi/acpi_memhotplug.c (ffffffff81a6ecda)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/acpi/acpi_memhotplug.c:acpi_memory_device_add
  - drivers/acpi/acpi_memhotplug.c:acpi_memory_get_resource
```
```
In drivers/acpi/ioapic.c (ffffffff81a6f160)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/acpi/ioapic.c:handle_ioapic_add
```
```
In drivers/acpi/battery.c (ffffffff81a70c10)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/acpi/battery.c:acpi_battery_add
```
```
In drivers/acpi/cppc_acpi.c (ffffffff81a7299b)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe
```
```
In drivers/acpi/apei/apei-base.c (ffffffff81a776a0)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/acpi/apei/apei-base.c:apei_res_sub
  - drivers/acpi/apei/apei-base.c:apei_res_add
```
```
In drivers/acpi/apei/hest.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In drivers/acpi/apei/erst.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In drivers/acpi/apei/ghes.c (ffffffff81a7b56e)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/acpi/apei/ghes.c:ghes_new
```
```
In drivers/acpi/viot.c (ffffffff839418f3)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/acpi/viot.c:viot_parse_node
  - drivers/acpi/viot.c:viot_get_iommu
  - drivers/acpi/viot.c:viot_get_iommu
```
```
In drivers/pnp/core.c (ffffffff81a7f614)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/pnp/core.c:pnp_alloc_dev
```
```
In drivers/pnp/card.c (ffffffff81a80234)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/pnp/card.c:pnp_alloc_card
  - drivers/pnp/card.c:pnp_alloc_card
```
```
In drivers/pnp/driver.c (ffffffff81a8100c)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/pnp/driver.c:pnp_add_id
```
```
In drivers/pnp/resource.c (ffffffff81a828d1)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/pnp/resource.c:pnp_add_bus_resource
  - drivers/pnp/resource.c:pnp_add_mem_resource
  - drivers/pnp/resource.c:pnp_add_io_resource
  - drivers/pnp/resource.c:pnp_add_dma_resource
  - drivers/pnp/resource.c:pnp_add_irq_resource
  - drivers/pnp/resource.c:pnp_register_mem_resource
  - drivers/pnp/resource.c:pnp_register_port_resource
  - drivers/pnp/resource.c:pnp_register_dma_resource
```
```
In drivers/pnp/interface.c (ffffffff81a83c92)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/pnp/interface.c:resources_show
  - drivers/pnp/interface.c:options_show
```
```
In drivers/pnp/quirks.c (ffffffff81a85001)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/pnp/quirks.c:quirk_add_irq_optional_dependent_sets
  - drivers/pnp/quirks.c:quirk_awe32_add_ports
```
```
In drivers/pnp/system.c (ffffffff81a854ff)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/pnp/system.c:reserve_range
```
```
In drivers/pnp/pnpacpi/rsparser.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In drivers/clk/clk-bulk.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In drivers/clk/clkdev.c (ffffffff8222ad81)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/clk/clkdev.c:vclkdev_alloc
```
```
In drivers/clk/clk.c (ffffffff81a8bd0d)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_notifier_register
  - drivers/clk/clk.c:__clk_register
  - drivers/clk/clk.c:alloc_clk
```
```
In drivers/clk/clk-divider.c (ffffffff81a931d5)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/clk/clk-divider.c:__clk_hw_register_divider
```
```
In drivers/clk/clk-fixed-factor.c (ffffffff81a9433a)
Location: include/linux/hash.h:74
Inline: True
```
```
In drivers/clk/clk-fixed-rate.c (ffffffff81a9495f)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/clk/clk-fixed-rate.c:__clk_hw_register_fixed_rate
```
```
In drivers/clk/clk-gate.c (ffffffff81a94bb3)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/clk/clk-gate.c:__clk_hw_register_gate
```
```
In drivers/clk/clk-mux.c (ffffffff81a95797)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/clk/clk-mux.c:__clk_hw_register_mux
```
```
In drivers/clk/clk-composite.c (ffffffff81a960d9)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/clk/clk-composite.c:__clk_hw_register_composite
```
```
In drivers/clk/clk-fractional-divider.c (ffffffff81a973d9)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/clk/clk-fractional-divider.c:clk_register_fractional_divider
```
```
In drivers/clk/x86/clk-pmc-atom.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In drivers/dma/dmaengine.c (ffffffff81a98d76)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/dma/dmaengine.c:__dma_async_device_channel_register
```
```
In drivers/dma/acpi-dma.c (ffffffff81a9bcc9)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/dma/acpi-dma.c:acpi_dma_controller_register
```
```
In drivers/dma/hsu/hsu.c (ffffffff81a9c8de)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/dma/hsu/hsu.c:hsu_dma_alloc_desc
```
```
In drivers/dma/lgm/lgm-dma.c (ffffffff81a9e846)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/dma/lgm/lgm-dma.c:ldma_prep_slave_sg
  - drivers/dma/lgm/lgm-dma.c:ldma_prep_slave_sg
```
```
In drivers/pmdomain/core.c (ffffffff81aa1a88)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/pmdomain/core.c:pm_genpd_init
  - drivers/pmdomain/core.c:pm_genpd_init
  - drivers/pmdomain/core.c:genpd_add_subdomain
  - drivers/pmdomain/core.c:genpd_add_device
  - drivers/pmdomain/core.c:genpd_add_device
```
```
In drivers/virtio/virtio_ring.c (ffffffff81aa8c06)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/virtio/virtio_ring.c:__vring_new_virtqueue
```
```
In drivers/virtio/virtio_mmio.c (ffffffff81aacbae)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/virtio/virtio_mmio.c:virtio_mmio_probe
  - drivers/virtio/virtio_mmio.c:vm_setup_vq
```
```
In drivers/virtio/virtio_pci_modern.c (ffffffff81aae3be)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_modern.c:vp_set_status
  - drivers/virtio/virtio_pci_modern.c:vp_modern_admin_cmd_exec
  - drivers/virtio/virtio_pci_modern.c:vp_modern_admin_cmd_exec
```
```
In drivers/virtio/virtio_pci_common.c (ffffffff81aaea7e)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_common.c:virtio_pci_probe
  - drivers/virtio/virtio_pci_common.c:vp_setup_vq
```
```
In drivers/virtio/virtio_pci_admin_legacy_io.c (ffffffff81ab0668)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_admin_legacy_io.c:virtio_pci_admin_legacy_io_notify_info
  - drivers/virtio/virtio_pci_admin_legacy_io.c:virtio_pci_admin_legacy_io_read
```
```
In drivers/virtio/virtio_balloon.c (ffffffff81ab1dd9)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtballoon_probe
```
```
In drivers/xen/grant-table.c (ffffffff81ab5eca)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/xen/grant-table.c:gnttab_add_deferred
```
```
In drivers/xen/balloon.c (ffffffff81ab69ff)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/xen/balloon.c:reserve_additional_memory
```
```
In drivers/xen/time.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In drivers/xen/events/events_base.c (ffffffff81ab948e)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/xen/events/events_base.c:xen_irq_init
```
```
In drivers/xen/xenbus/xenbus_client.c (ffffffff81ac1252)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_valloc
  - drivers/xen/xenbus/xenbus_client.c:xenbus_va_dev_error
```
```
In drivers/xen/xenbus/xenbus_comms.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff81ac2fc7)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_xs.c:xs_talkv
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_dev_request_and_reply
```
```
In drivers/xen/xenbus/xenbus_probe.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffffffff81ac6f56)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_open
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_write_watch
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_write_transaction
```
```
In drivers/xen/pci.c (ffffffff81ac9169)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/xen/pci.c:xen_register_device_domain_owner
```
```
In drivers/xen/pcpu.c (ffffffff81aca26c)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/xen/pcpu.c:sync_pcpu
```
```
In drivers/xen/sys-hypervisor.c (ffffffff81acb3ec)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/xen/sys-hypervisor.c:virtual_start_show
  - drivers/xen/sys-hypervisor.c:changeset_show
  - drivers/xen/sys-hypervisor.c:capabilities_show
  - drivers/xen/sys-hypervisor.c:compile_date_show
  - drivers/xen/sys-hypervisor.c:compiled_by_show
  - drivers/xen/sys-hypervisor.c:compiler_show
  - drivers/xen/sys-hypervisor.c:extra_show
```
```
In drivers/xen/mcelog.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In drivers/xen/xen-acpi-processor.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In drivers/xen/xlate_mmu.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In drivers/xen/unpopulated-alloc.c (ffffffff81ad054d)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/xen/unpopulated-alloc.c:fill_list
  - drivers/xen/unpopulated-alloc.c:fill_list
  - drivers/xen/unpopulated-alloc.c:fill_list
```
```
In drivers/regulator/core.c (ffffffff81addc81)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/regulator/core.c:regulator_register
  - drivers/regulator/core.c:regulator_register
  - drivers/regulator/core.c:regulator_register
  - drivers/regulator/core.c:regulator_register
  - drivers/regulator/core.c:regulator_register_supply_alias
  - drivers/regulator/core.c:create_regulator
  - drivers/regulator/core.c:constraint_flags_read_file
  - drivers/regulator/core.c:set_consumer_device_supply
```
```
In drivers/regulator/fixed-helper.c (ffffffff81adf8cf)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/regulator/fixed-helper.c:regulator_register_always_on
```
```
In drivers/reset/core.c (ffffffff81ae32ac)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/reset/core.c:__reset_control_get_internal
```
```
In drivers/tty/tty_io.c (ffffffff81ae5be8)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_register_device_attr
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_save_termios
```
```
In drivers/tty/tty_ldisc.c (ffffffff81af0902)
Location: include/linux/hash.h:74
Inline: True
```
```
In drivers/tty/tty_buffer.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In drivers/tty/pty.c (ffffffff81af649b)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/tty/pty.c:pty_common_install
  - drivers/tty/pty.c:pty_common_install
```
```
In drivers/tty/tty_audit.c (ffffffff81af6eec)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/tty/tty_audit.c:tty_audit_add_data
  - drivers/tty/tty_audit.c:tty_audit_add_data
```
```
In drivers/tty/sysrq.c (ffffffff81af7801)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/tty/sysrq.c:sysrq_connect
```
```
In drivers/tty/vt/vc_screen.c (ffffffff81afabbe)
Location: include/linux/hash.h:74
Inline: True
```
```
In drivers/tty/vt/selection.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In drivers/tty/vt/keyboard.c (ffffffff81b004ca)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/tty/vt/keyboard.c:vt_do_kdgkb_ioctl
  - drivers/tty/vt/keyboard.c:vt_kdskbent
  - drivers/tty/vt/keyboard.c:vt_do_diacrit
  - drivers/tty/vt/keyboard.c:vt_do_diacrit
  - drivers/tty/vt/keyboard.c:kbd_connect
```
```
In drivers/tty/vt/consolemap.c (ffffffff81b0125c)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/tty/vt/consolemap.c:con_allocate_new
  - drivers/tty/vt/consolemap.c:con_insert_unipair
  - drivers/tty/vt/consolemap.c:con_insert_unipair
  - drivers/tty/vt/consolemap.c:set_inverse_trans_unicode
  - drivers/tty/vt/consolemap.c:set_inverse_transl
```
```
In drivers/tty/vt/vt.c (ffffffff839467cb)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:con_init
  - drivers/tty/vt/vt.c:vc_allocate
```
```
In drivers/tty/hvc/hvc_console.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In drivers/tty/hvc/hvc_xen.c (ffffffff83946d74)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_xen.c:xen_hvc_init
  - drivers/tty/hvc/hvc_xen.c:xencons_probe
  - drivers/tty/hvc/hvc_xen.c:xen_pv_console_init
  - drivers/tty/hvc/hvc_xen.c:xen_hvm_console_init
```
```
In drivers/tty/serial/serial_core.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In drivers/tty/serial/serial_base_bus.c (ffffffff81b17218)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/tty/serial/serial_base_bus.c:serial_base_port_add
  - drivers/tty/serial/serial_base_bus.c:serial_base_ctrl_add
```
```
In drivers/tty/serial/8250/8250_core.c (ffffffff81b190e4)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_core.c:univ8250_setup_irq
```
```
In drivers/tty/serial/8250/8250_port.c (ffffffff81b1b541)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_port.c:serial8250_em485_config
```
```
In drivers/tty/serial/8250/8250_pci.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In drivers/tty/serial/kgdb_nmi.c (ffffffff81b2db1c)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/tty/serial/kgdb_nmi.c:kgdb_nmi_tty_install
```
```
In drivers/tty/serdev/core.c (ffffffff81b2f871)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:serdev_device_alloc
```
```
In drivers/char/mem.c (ffffffff81b311da)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/char/mem.c:read_mem
```
```
In drivers/char/random.c (ffffffff81b34220)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/char/random.c:rand_initialize_disk
```
```
In drivers/char/virtio_console.c (ffffffff81b38629)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:virtcons_probe
```
```
In drivers/char/hpet.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In drivers/char/hw_random/core.c (ffffffff83948c30)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/char/hw_random/core.c:hwrng_modinit
  - drivers/char/hw_random/core.c:hwrng_modinit
```
```
In drivers/char/agp/backend.c (ffffffff81b3bd3c)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/char/agp/backend.c:agp_alloc_bridge
```
```
In drivers/char/agp/generic.c (ffffffff81b3dd1b)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/char/agp/generic.c:agp_generic_alloc_user
  - drivers/char/agp/generic.c:agp_create_memory
```
```
In drivers/char/agp/isoch.c (ffffffff81b3e8c0)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/char/agp/isoch.c:agp_3_5_enable
  - drivers/char/agp/isoch.c:agp_3_5_enable
```
```
In drivers/char/tpm/tpm-chip.c (ffffffff81b43c71)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-chip.c:tpm_chip_alloc
```
```
In drivers/char/tpm/tpm-dev.c (ffffffff81b44eb6)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-dev.c:tpm_open
```
```
In drivers/char/tpm/tpm1-cmd.c (ffffffff81b46d20)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/char/tpm/tpm1-cmd.c:tpm1_get_pcr_allocation
```
```
In drivers/char/tpm/tpm2-cmd.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In drivers/char/tpm/tpmrm-dev.c (ffffffff81b486ed)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/char/tpm/tpmrm-dev.c:tpmrm_open
```
```
In drivers/char/tpm/tpm2-space.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In drivers/char/tpm/eventlog/tpm1.c (ffffffff81b4b106)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/char/tpm/eventlog/tpm1.c:tpm1_ascii_bios_measurements_show
```
```
In drivers/iommu/amd/iommu.c (ffffffff81b55b3e)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:irq_remapping_alloc
  - drivers/iommu/amd/iommu.c:irq_remapping_alloc
  - drivers/iommu/amd/iommu.c:irq_remapping_alloc
  - drivers/iommu/amd/iommu.c:__alloc_irq_table
  - drivers/iommu/amd/iommu.c:protection_domain_alloc
  - drivers/iommu/amd/iommu.c:iommu_init_device
```
```
In drivers/iommu/amd/init.c (ffffffff8394ca48)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/iommu/amd/init.c:init_iommu_all
  - drivers/iommu/amd/init.c:alloc_pci_segment
  - drivers/iommu/amd/init.c:add_acpi_hid_device
  - drivers/iommu/amd/init.c:add_special_device
```
```
In drivers/iommu/intel/dmar.c (ffffffff81b5f67a)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/iommu/intel/dmar.c:dmar_enable_qi
  - drivers/iommu/intel/dmar.c:dmar_enable_qi
  - drivers/iommu/intel/dmar.c:alloc_iommu
```
```
In drivers/iommu/intel/iommu.c (ffffffff81b627d6)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/iommu/intel/iommu.c:intel_iommu_hw_info
  - drivers/iommu/intel/iommu.c:intel_iommu_set_dev_pasid
  - drivers/iommu/intel/iommu.c:intel_iommu_probe_device
  - drivers/iommu/intel/iommu.c:dmar_parse_one_rmrr
  - drivers/iommu/intel/iommu.c:domain_attach_iommu
  - drivers/iommu/intel/iommu.c:alloc_domain
```
```
In drivers/iommu/intel/pasid.c (ffffffff81b67ddb)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/iommu/intel/pasid.c:intel_pasid_alloc_table
```
```
In drivers/iommu/intel/nested.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In drivers/iommu/intel/svm.c (ffffffff81b6d50c)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/iommu/intel/svm.c:intel_svm_domain_alloc
```
```
In drivers/iommu/intel/irq_remapping.c (ffffffff81b6ec3b)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/iommu/intel/irq_remapping.c:intel_irq_remapping_alloc
  - drivers/iommu/intel/irq_remapping.c:intel_irq_remapping_alloc
  - drivers/iommu/intel/irq_remapping.c:intel_setup_irq_remapping
```
```
In drivers/iommu/intel/perfmon.c (ffffffff81b71360)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/iommu/intel/perfmon.c:alloc_iommu_pmu
```
```
In drivers/iommu/iommufd/iova_bitmap.c (ffffffff81b72065)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/iommu/iommufd/iova_bitmap.c:iova_bitmap_alloc
```
```
In drivers/iommu/iommu.c (ffffffff81b742d1)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/iommu/iommu.c:iommu_fwspec_init
  - drivers/iommu/iommu.c:iommu_register_device_fault_handler
  - drivers/iommu/iommu.c:iommu_group_alloc_device
  - drivers/iommu/iommu.c:iommu_group_alloc
  - drivers/iommu/iommu.c:iommu_insert_resv_region
  - drivers/iommu/iommu.c:iommu_subsys_init
```
```
In drivers/iommu/iommu-sysfs.c (ffffffff81b790f2)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/iommu/iommu-sysfs.c:iommu_device_sysfs_add
```
```
In drivers/iommu/dma-iommu.c (ffffffff81b7c88a)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/iommu/dma-iommu.c:iommu_dma_prepare_msi
  - drivers/iommu/dma-iommu.c:iommu_dma_alloc_noncontiguous
  - drivers/iommu/dma-iommu.c:iommu_get_msi_cookie
  - drivers/iommu/dma-iommu.c:iommu_get_dma_cookie
```
```
In drivers/iommu/iova.c (ffffffff81b7d862)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/iommu/iova.c:free_iova_fast
```
```
In drivers/iommu/hyperv-iommu.c (ffffffff81b7e6d6)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/iommu/hyperv-iommu.c:hyperv_root_irq_remapping_alloc
```
```
In drivers/iommu/virtio-iommu.c (ffffffff81b80626)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/iommu/virtio-iommu.c:viommu_probe_device
  - drivers/iommu/virtio-iommu.c:viommu_domain_alloc
  - drivers/iommu/virtio-iommu.c:viommu_add_mapping
```
```
In drivers/iommu/iommu-sva.c (ffffffff81b8114f)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/iommu/iommu-sva.c:iommu_sva_bind_device
  - drivers/iommu/iommu-sva.c:iommu_sva_bind_device
```
```
In drivers/iommu/io-pgfault.c (ffffffff81b81861)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/iommu/io-pgfault.c:iopf_queue_alloc
  - drivers/iommu/io-pgfault.c:iopf_queue_add_device
  - drivers/iommu/io-pgfault.c:iommu_queue_iopf
  - drivers/iommu/io-pgfault.c:iommu_queue_iopf
```
```
In drivers/connector/cn_queue.c (ffffffff81b820cc)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/connector/cn_queue.c:cn_queue_alloc_dev
  - drivers/connector/cn_queue.c:cn_queue_alloc_callback_entry
```
```
In drivers/connector/cn_proc.c (ffffffff81b82cab)
Location: include/linux/hash.h:74
Inline: True
```
```
In drivers/base/component.c (ffffffff81b8486c)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/base/component.c:__component_add
```
```
In drivers/base/core.c (ffffffff81b8bfd0)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/base/core.c:device_create_groups_vargs
  - drivers/base/core.c:__root_device_register
  - drivers/base/core.c:device_add
  - drivers/base/core.c:get_device_parent
  - drivers/base/core.c:uevent_show
  - drivers/base/core.c:device_link_add
  - drivers/base/core.c:__fwnode_link_add
```
```
In drivers/base/bus.c (ffffffff81b8eaee)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/base/bus.c:bus_register
  - drivers/base/bus.c:bus_add_driver
```
```
In drivers/base/class.c (ffffffff81b9291e)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/base/class.c:class_compat_register
  - drivers/base/class.c:class_create
  - drivers/base/class.c:class_register
```
```
In drivers/base/platform.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In drivers/base/cpu.c (ffffffff81b95f7a)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/base/cpu.c:cpu_device_create
  - drivers/base/cpu.c:cpu_uevent
```
```
In drivers/base/map.c (ffffffff81b96ae9)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/base/map.c:kobj_map_init
  - drivers/base/map.c:kobj_map_init
```
```
In drivers/base/devres.c (ffffffff81b97cd9)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/base/devres.c:devres_open_group
```
```
In drivers/base/attribute_container.c (ffffffff81b9944d)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/base/attribute_container.c:attribute_container_add_device
```
```
In drivers/base/property.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In drivers/base/cacheinfo.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In drivers/base/swnode.c (ffffffff81ba037f)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/base/swnode.c:fwnode_create_software_node
  - drivers/base/swnode.c:swnode_register
```
```
In drivers/base/power/common.c (ffffffff81ba432e)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/base/power/common.c:dev_pm_get_subsys_data
```
```
In drivers/base/power/qos.c (ffffffff81ba5088)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/base/power/qos.c:dev_pm_qos_update_user_latency_tolerance
  - drivers/base/power/qos.c:dev_pm_qos_expose_flags
  - drivers/base/power/qos.c:dev_pm_qos_expose_latency_limit
  - drivers/base/power/qos.c:dev_pm_qos_constraints_allocate
  - drivers/base/power/qos.c:dev_pm_qos_constraints_allocate
```
```
In drivers/base/power/wakeirq.c (ffffffff81ba93f1)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/base/power/wakeirq.c:__dev_pm_set_dedicated_wake_irq
  - drivers/base/power/wakeirq.c:dev_pm_set_wake_irq
```
```
In drivers/base/power/wakeup.c (ffffffff81baea4e)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:wakeup_source_create
```
```
In drivers/base/power/wakeup_stats.c (ffffffff81bb008c)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/base/power/wakeup_stats.c:wakeup_source_device_create
```
```
In drivers/base/power/clock_ops.c (ffffffff81bb0d65)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/base/power/clock_ops.c:__pm_clk_add
```
```
In drivers/base/isa.c (ffffffff81bb18d9)
Location: include/linux/hash.h:74
Inline: True
```
```
In drivers/base/firmware_loader/main.c (ffffffff81bb2d1e)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:dev_create_fw_entry
  - drivers/base/firmware_loader/main.c:request_firmware_nowait
  - drivers/base/firmware_loader/main.c:_request_firmware
  - drivers/base/firmware_loader/main.c:fw_log_firmware_info
  - drivers/base/firmware_loader/main.c:fw_log_firmware_info
  - drivers/base/firmware_loader/main.c:alloc_lookup_fw_priv
```
```
In drivers/base/firmware_loader/sysfs.c (ffffffff81bb54c4)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/base/firmware_loader/sysfs.c:fw_create_instance
```
```
In drivers/base/firmware_loader/sysfs_upload.c (ffffffff81bb591a)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/base/firmware_loader/sysfs_upload.c:firmware_upload_register
  - drivers/base/firmware_loader/sysfs_upload.c:firmware_upload_register
```
```
In drivers/base/node.c (ffffffff81bb7e5c)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/base/node.c:__register_one_node
  - drivers/base/node.c:node_add_cache
  - drivers/base/node.c:node_add_cache
```
```
In drivers/base/memory.c (ffffffff81bb8a7c)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/base/memory.c:memory_group_register
  - drivers/base/memory.c:add_memory_block
```
```
In drivers/base/regmap/regmap.c (ffffffff81bbd0e8)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/base/regmap/regmap.c:regmap_field_alloc
  - drivers/base/regmap/regmap.c:__regmap_init
  - drivers/base/regmap/regmap.c:__regmap_init
```
```
In drivers/base/regmap/regcache.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In drivers/base/regmap/regcache-rbtree.c (ffffffff81bc511e)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_node_alloc
```
```
In drivers/base/regmap/regcache-flat.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In drivers/base/regmap/regcache-maple.c (ffffffff81bc5eae)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/base/regmap/regcache-maple.c:regcache_maple_init
```
```
In drivers/base/regmap/regmap-debugfs.c (ffffffff81bc7999)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-debugfs.c:regmap_debugfs_init
  - drivers/base/regmap/regmap-debugfs.c:regmap_reg_ranges_read_file
  - drivers/base/regmap/regmap-debugfs.c:regmap_name_read_file
```
```
In drivers/base/regmap/regmap-spi.c (ffffffff81bc8a5c)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-spi.c:regmap_spi_async_alloc
```
```
In drivers/base/regmap/regmap-mmio.c (ffffffff81bc98af)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-mmio.c:regmap_mmio_gen_context
```
```
In drivers/base/regmap/regmap-irq.c (ffffffff81bcb253)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/base/regmap/regmap-irq.c:regmap_add_irq_chip_fwnode
```
```
In drivers/base/soc.c (ffffffff81bcc3de)
Location: include/linux/hash.h:74
Inline: True
```
```
In drivers/base/devcoredump.c (ffffffff81bcce55)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/base/devcoredump.c:dev_coredumpm
```
```
In drivers/base/platform-msi.c (ffffffff81bcd1f2)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/base/platform-msi.c:platform_msi_alloc_priv_data
```
```
In drivers/base/physical_location.c (ffffffff81bcd939)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/base/physical_location.c:dev_add_physical_location
```
```
In drivers/block/loop.c (ffffffff81bcf46c)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/block/loop.c:loop_add
  - drivers/block/loop.c:loop_queue_work
```
```
In drivers/block/virtio_blk.c (ffffffff81bd492e)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/block/virtio_blk.c:virtblk_probe
```
```
In drivers/block/xen-blkfront.c (ffffffff81bd6d98)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkfront_setup_indirect
  - drivers/block/xen-blkfront.c:blkfront_probe
```
```
In drivers/misc/sram.c (ffffffff81bdc5db)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/misc/sram.c:sram_reserve_regions
```
```
In drivers/mfd/wm831x-auxadc.c (ffffffff81be0cdf)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/mfd/wm831x-auxadc.c:wm831x_auxadc_read_irq
```
```
In drivers/mfd/twl4030-irq.c (ffffffff81be4b9e)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/mfd/twl4030-irq.c:twl4030_sih_setup
```
```
In drivers/mfd/mfd-core.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In drivers/mfd/ezx-pcap.c (ffffffff81be83c0)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/mfd/ezx-pcap.c:pcap_adc_async
```
```
In drivers/mfd/aat2870-core.c (ffffffff81bf24bb)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/mfd/aat2870-core.c:aat2870_reg_read_file
```
```
In drivers/mfd/syscon.c (ffffffff81bf5005)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/mfd/syscon.c:device_node_to_regmap
```
```
In drivers/nvdimm/core.c (ffffffff81bf636f)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/nvdimm/core.c:alloc_nvdimm_map
```
```
In drivers/nvdimm/bus.c (ffffffff81bf8988)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:__nd_ioctl
  - drivers/nvdimm/bus.c:__nd_ioctl
  - drivers/nvdimm/bus.c:nvdimm_bus_create_ndctl
  - drivers/nvdimm/bus.c:nvdimm_bus_register
```
```
In drivers/nvdimm/dimm_devs.c (ffffffff81bfa5a5)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:__nvdimm_create
```
```
In drivers/nvdimm/nd_perf.c (ffffffff81bfba8c)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/nvdimm/nd_perf.c:register_nvdimm_pmu
  - drivers/nvdimm/nd_perf.c:register_nvdimm_pmu
  - drivers/nvdimm/nd_perf.c:register_nvdimm_pmu
  - drivers/nvdimm/nd_perf.c:register_nvdimm_pmu
```
```
In drivers/nvdimm/dimm.c (ffffffff81bfbeac)
Location: include/linux/hash.h:74
Inline: True
```
```
In drivers/nvdimm/region_devs.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In drivers/nvdimm/namespace_devs.c (ffffffff81c049ce)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/nvdimm/namespace_devs.c:nd_region_register_namespaces
  - drivers/nvdimm/namespace_devs.c:init_active_labels
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:scan_labels
  - drivers/nvdimm/namespace_devs.c:nd_region_create_ns_seed
  - drivers/nvdimm/namespace_devs.c:create_namespace_pmem
  - drivers/nvdimm/namespace_devs.c:alt_name_store
```
```
In drivers/nvdimm/label.c (ffffffff81c0595a)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:init_labels
```
```
In drivers/nvdimm/badrange.c (ffffffff81c07af5)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/nvdimm/badrange.c:badrange_forget
  - drivers/nvdimm/badrange.c:badrange_add
```
```
In drivers/nvdimm/btt_devs.c (ffffffff81c08df9)
Location: include/linux/hash.h:74
Inline: True
```
```
In drivers/nvdimm/pfn_devs.c (ffffffff81c0aa0e)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/nvdimm/pfn_devs.c:nd_pfn_alloc
```
```
In drivers/nvdimm/dax_devs.c (ffffffff81c0af1e)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/nvdimm/dax_devs.c:nd_dax_alloc
```
```
In drivers/dax/bus.c (ffffffff81c10198)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/dax/bus.c:devm_create_dev_dax
  - drivers/dax/bus.c:devm_register_dax_mapping
  - drivers/dax/bus.c:alloc_dax_region
  - drivers/dax/bus.c:do_id_store
```
```
In drivers/dma-buf/dma-buf.c (ffffffff81c11b28)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/dma-buf/dma-buf.c:dma_buf_dynamic_attach
```
```
In drivers/dma-buf/dma-fence.c (ffffffff81c13a54)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/dma-buf/dma-fence.c:dma_fence_allocate_private_stub
```
```
In drivers/dma-buf/dma-fence-array.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In drivers/dma-buf/dma-fence-unwrap.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In drivers/dma-buf/dma-resv.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In drivers/dma-buf/dma-heap.c (ffffffff81c179bf)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/dma-buf/dma-heap.c:dma_heap_add
```
```
In drivers/dma-buf/heaps/system_heap.c (ffffffff81c18573)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/dma-buf/heaps/system_heap.c:system_heap_allocate
  - drivers/dma-buf/heaps/system_heap.c:system_heap_attach
  - drivers/dma-buf/heaps/system_heap.c:system_heap_attach
```
```
In drivers/dma-buf/sync_file.c (ffffffff81c18e0d)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/dma-buf/sync_file.c:sync_file_alloc
```
```
In drivers/dma-buf/sw_sync.c (ffffffff81c1a56f)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/dma-buf/sw_sync.c:sync_pt_create
  - drivers/dma-buf/sw_sync.c:sync_timeline_create
```
```
In drivers/dma-buf/udmabuf.c (ffffffff81c1b6b6)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/dma-buf/udmabuf.c:udmabuf_create
```
```
In drivers/scsi/scsi.c (ffffffff81c1e5f9)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:scsi_cdl_check
```
```
In drivers/scsi/hosts.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In drivers/scsi/scsi_ioctl.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In drivers/scsi/scsi_error.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In drivers/scsi/scsi_lib.c (ffffffff81c27286)
Location: include/linux/hash.h:74
Inline: True
```
```
In drivers/scsi/scsi_scan.c (ffffffff81c2c884)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/scsi/scsi_scan.c:scsi_probe_and_add_lun
  - drivers/scsi/scsi_scan.c:scsi_complete_async_scans
```
```
In drivers/scsi/scsi_devinfo.c (ffffffff81c31a6c)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/scsi/scsi_devinfo.c:scsi_dev_info_add_list
  - drivers/scsi/scsi_devinfo.c:devinfo_seq_start
  - drivers/scsi/scsi_devinfo.c:scsi_dev_info_list_add_keyed
```
```
In drivers/scsi/scsi_proc.c (ffffffff81c330d7)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/scsi/scsi_proc.c:scsi_proc_hostdir_add
```
```
In drivers/scsi/scsi_logging.c (ffffffff81c34424)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/scsi/scsi_logging.c:scsi_print_result
  - drivers/scsi/scsi_logging.c:scsi_log_print_sense
  - drivers/scsi/scsi_logging.c:scsi_log_print_sense_hdr
  - drivers/scsi/scsi_logging.c:scsi_log_print_sense_hdr
  - drivers/scsi/scsi_logging.c:scsi_print_command
  - drivers/scsi/scsi_logging.c:scmd_printk
  - drivers/scsi/scsi_logging.c:sdev_prefix_printk
```
```
In drivers/scsi/virtio_scsi.c (ffffffff81c36abc)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/scsi/virtio_scsi.c:virtscsi_rescan_hotunplug
```
```
In drivers/scsi/sd.c (ffffffff81c3fbe9)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/scsi/sd.c:sd_probe
```
```
In drivers/scsi/sd_zbc.c (ffffffff81c430a4)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_revalidate_zones
```
```
In drivers/scsi/sr.c (ffffffff81c4429d)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/scsi/sr.c:get_capabilities
  - drivers/scsi/sr.c:sr_probe
```
```
In drivers/scsi/sr_ioctl.c (ffffffff81c4596c)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/scsi/sr_ioctl.c:sr_is_xa
  - drivers/scsi/sr_ioctl.c:sr_get_mcn
```
```
In drivers/scsi/sr_vendor.c (ffffffff81c45e55)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/scsi/sr_vendor.c:sr_cd_check
  - drivers/scsi/sr_vendor.c:sr_set_blocklength
```
```
In drivers/scsi/sg.c (ffffffff81c47648)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/scsi/sg.c:dev_seq_start
  - drivers/scsi/sg.c:sg_add_sfp
  - drivers/scsi/sg.c:sg_alloc
  - drivers/scsi/sg.c:sg_ioctl_common
  - drivers/scsi/sg.c:sg_read
```
```
In drivers/ata/libata-core.c (ffffffff81c55af7)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/ata/libata-core.c:ata_dev_config_cdl
```
```
In drivers/ata/libata-scsi.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In drivers/ata/libata-transport.c (ffffffff81c693bd)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/ata/libata-transport.c:ata_attach_transport
```
```
In drivers/ata/libata-sata.c (ffffffff81c6bd73)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/ata/libata-sata.c:ata_slave_link_init
```
```
In drivers/ata/libata-pmp.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In drivers/ata/libata-acpi.c (ffffffff81c73e94)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/ata/libata-acpi.c:ata_acpi_bind_dev
  - drivers/ata/libata-acpi.c:ata_acpi_bind_port
```
```
In drivers/ata/libata-zpodd.c (ffffffff81c74c7a)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/ata/libata-zpodd.c:zpodd_init
  - drivers/ata/libata-zpodd.c:zpodd_init
```
```
In drivers/gpu/drm/drm_atomic.c (ffffffff81c7b3a1)
Location: include/linux/hash.h:74
Inline: True
```
```
In drivers/gpu/drm/drm_atomic_uapi.c (ffffffff81c7d190)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_atomic_uapi.c:prepare_signaling
```
```
In drivers/gpu/drm/drm_auth.c (ffffffff81c7e860)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_auth.c:drm_master_create
```
```
In drivers/gpu/drm/drm_blend.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In drivers/gpu/drm/drm_bridge.c (ffffffff81c80572)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_bridge.c:drm_atomic_bridge_chain_check
```
```
In drivers/gpu/drm/drm_client.c (ffffffff81c81d1c)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_client.c:drm_client_framebuffer_create
```
```
In drivers/gpu/drm/drm_client_modeset.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In drivers/gpu/drm/drm_color_mgmt.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In drivers/gpu/drm/drm_connector.c (ffffffff81c872f1)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_connector.c:drm_mode_create_tile_group
```
```
In drivers/gpu/drm/drm_crtc.c (ffffffff81c8a41e)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_crtc.c:drm_crtc_create_fence
```
```
In drivers/gpu/drm/drm_drv.c (ffffffff81c8c149)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_drv.c:drm_dev_alloc
```
```
In drivers/gpu/drm/drm_edid.c (ffffffff81c91531)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_edid.c:drm_edid_get_panel_id
  - drivers/gpu/drm/drm_edid.c:drm_edid_read_custom
  - drivers/gpu/drm/drm_edid.c:drm_edid_alloc
  - drivers/gpu/drm/drm_edid.c:_drm_do_get_edid
```
```
In drivers/gpu/drm/drm_file.c (ffffffff81c97565)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_file.c:drm_file_alloc
```
```
In drivers/gpu/drm/drm_framebuffer.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In drivers/gpu/drm/drm_ioctl.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In drivers/gpu/drm/drm_lease.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In drivers/gpu/drm/drm_modes.c (ffffffff81ca5ff0)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_modes.c:drm_mode_duplicate
  - drivers/gpu/drm/drm_modes.c:drm_gtf_mode_complex
  - drivers/gpu/drm/drm_modes.c:drm_cvt_mode
  - drivers/gpu/drm/drm_modes.c:drm_analog_tv_mode
```
```
In drivers/gpu/drm/drm_modeset_lock.c (ffffffff81ca8e41)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_modeset_lock.c:drm_modeset_lock_all
```
```
In drivers/gpu/drm/drm_plane.c (ffffffff81cab9af)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_plane.c:drm_mode_page_flip_ioctl
```
```
In drivers/gpu/drm/drm_prime.c (ffffffff81cac051)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_prime.c:drm_prime_pages_to_sg
  - drivers/gpu/drm/drm_prime.c:drm_gem_prime_mmap
  - drivers/gpu/drm/drm_prime.c:drm_gem_prime_mmap
  - drivers/gpu/drm/drm_prime.c:drm_prime_add_buf_handle
```
```
In drivers/gpu/drm/drm_print.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In drivers/gpu/drm/drm_property.c (ffffffff81cae2ad)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_property.c:drm_property_add_enum
  - drivers/gpu/drm/drm_property.c:drm_property_create
```
```
In drivers/gpu/drm/drm_syncobj.c (ffffffff81cb1d7f)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_syncobj.c:drm_syncobj_timeline_signal_ioctl
  - drivers/gpu/drm/drm_syncobj.c:drm_syncobj_eventfd_ioctl
  - drivers/gpu/drm/drm_syncobj.c:drm_syncobj_transfer_ioctl
  - drivers/gpu/drm/drm_syncobj.c:drm_syncobj_create
```
```
In drivers/gpu/drm/drm_sysfs.c (ffffffff81cb32a6)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_sysfs.c:drm_sysfs_minor_alloc
  - drivers/gpu/drm/drm_sysfs.c:drm_sysfs_connector_add
```
```
In drivers/gpu/drm/drm_vblank.c (ffffffff81cb74bc)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_vblank.c:drm_crtc_queue_sequence_ioctl
  - drivers/gpu/drm/drm_vblank.c:drm_queue_vblank_event
```
```
In drivers/gpu/drm/drm_vma_manager.c (ffffffff81cb8131)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_vma_manager.c:vma_node_allow
```
```
In drivers/gpu/drm/drm_writeback.c (ffffffff81cb8837)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_writeback.c:drm_writeback_get_out_fence
  - drivers/gpu/drm/drm_writeback.c:drm_writeback_set_fb
```
```
In drivers/gpu/drm/drm_debugfs_crc.c (ffffffff81cbbbc1)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_debugfs_crc.c:crtc_crc_open
```
```
In drivers/gpu/drm/drm_privacy_screen.c (ffffffff81cbc87c)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_privacy_screen.c:drm_privacy_screen_register
```
```
In drivers/gpu/drm/drm_gem_shmem_helper.c (ffffffff81cbe192)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_gem_shmem_helper.c:__drm_gem_shmem_create
```
```
In drivers/gpu/drm/drm_atomic_helper.c (ffffffff81cc12b1)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_atomic_helper.c:drm_atomic_helper_bridge_propagate_bus_fmt
  - drivers/gpu/drm/drm_atomic_helper.c:drm_atomic_helper_setup_commit
  - drivers/gpu/drm/drm_atomic_helper.c:drm_atomic_helper_setup_commit
```
```
In drivers/gpu/drm/drm_atomic_state_helper.c (ffffffff81cc567e)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_atomic_state_helper.c:drm_atomic_helper_bridge_reset
  - drivers/gpu/drm/drm_atomic_state_helper.c:drm_atomic_helper_bridge_duplicate_state
  - drivers/gpu/drm/drm_atomic_state_helper.c:drm_atomic_helper_connector_duplicate_state
  - drivers/gpu/drm/drm_atomic_state_helper.c:drm_atomic_helper_connector_reset
  - drivers/gpu/drm/drm_atomic_state_helper.c:drm_atomic_helper_plane_duplicate_state
  - drivers/gpu/drm/drm_atomic_state_helper.c:drm_atomic_helper_plane_reset
  - drivers/gpu/drm/drm_atomic_state_helper.c:drm_atomic_helper_crtc_duplicate_state
  - drivers/gpu/drm/drm_atomic_state_helper.c:drm_atomic_helper_crtc_reset
```
```
In drivers/gpu/drm/drm_bridge_connector.c (ffffffff81cc5edc)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_bridge_connector.c:drm_bridge_connector_init
```
```
In drivers/gpu/drm/drm_crtc_helper.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In drivers/gpu/drm/drm_damage_helper.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In drivers/gpu/drm/drm_flip_work.c (ffffffff81cc8b82)
Location: include/linux/hash.h:74
Inline: True
```
```
In drivers/gpu/drm/drm_gem_atomic_helper.c (ffffffff81ccb52d)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_gem_atomic_helper.c:drm_gem_simple_kms_duplicate_shadow_plane_state
  - drivers/gpu/drm/drm_gem_atomic_helper.c:drm_gem_reset_shadow_plane
  - drivers/gpu/drm/drm_gem_atomic_helper.c:drm_gem_plane_helper_prepare_fb
```
```
In drivers/gpu/drm/drm_gem_framebuffer_helper.c (ffffffff81ccc507)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_gem_framebuffer_helper.c:drm_gem_fb_create_with_dirty
  - drivers/gpu/drm/drm_gem_framebuffer_helper.c:drm_gem_fb_create
```
```
In drivers/gpu/drm/drm_plane_helper.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In drivers/gpu/drm/drm_self_refresh_helper.c (ffffffff81ccf90f)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_self_refresh_helper.c:drm_self_refresh_helper_init
```
```
In drivers/gpu/drm/drm_fbdev_generic.c (ffffffff81cd164f)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_fbdev_generic.c:drm_fbdev_generic_setup
```
```
In drivers/gpu/drm/drm_mipi_dsi.c (ffffffff81cd5b55)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_mipi_dsi.c:mipi_dsi_device_register_full
```
```
In drivers/gpu/vga/vga_switcheroo.c (ffffffff81cd7ef8)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/gpu/vga/vga_switcheroo.c:register_client
```
```
In drivers/spi/spi.c (ffffffff8395464d)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/spi/spi.c:spi_init
  - drivers/spi/spi.c:spi_alloc_device
```
```
In drivers/spi/spi-mem.c (ffffffff81ce3802)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/spi/spi-mem.c:spi_mem_dirmap_create
```
```
In drivers/net/netkit.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In drivers/net/phy/mdio-boardinfo.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In drivers/net/phy/phy.c (ffffffff81ce916e)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_ethtool_set_plca_cfg
```
```
In drivers/net/phy/phy_device.c (ffffffff81cf0373)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/net/phy/phy_device.c:phy_package_join
  - drivers/net/phy/phy_device.c:phy_device_create
  - drivers/net/phy/phy_device.c:phy_register_fixup
```
```
In drivers/net/phy/mdio_bus.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In drivers/net/phy/mdio_device.c (ffffffff81cf4a31)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/net/phy/mdio_device.c:mdio_device_create
```
```
In drivers/net/phy/mii_timestamper.c (ffffffff81cf5541)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/net/phy/mii_timestamper.c:register_mii_tstamp_controller
```
```
In drivers/net/phy/sfp-bus.c (ffffffff81cf5b6e)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/net/phy/sfp-bus.c:sfp_bus_get
```
```
In drivers/net/phy/fixed_phy.c (ffffffff81cf7475)
Location: include/linux/hash.h:74
Inline: True
```
```
In drivers/net/pse-pd/pse_core.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In drivers/net/tun.c (ffffffff81cf9b4c)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_flow_update
```
```
In drivers/net/virtio_net.c (ffffffff81d05917)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/net/virtio_net.c:virtnet_alloc_queues
```
```
In drivers/net/ethernet/microchip/vcap/vcap_api.c (ffffffff81d1491e)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/net/ethernet/microchip/vcap/vcap_api.c:vcap_enable
  - drivers/net/ethernet/microchip/vcap/vcap_api.c:vcap_rule_add_action
  - drivers/net/ethernet/microchip/vcap/vcap_api.c:vcap_rule_add_key
  - drivers/net/ethernet/microchip/vcap/vcap_api.c:vcap_decode_keyset
  - drivers/net/ethernet/microchip/vcap/vcap_api.c:vcap_decode_actionset
  - drivers/net/ethernet/microchip/vcap/vcap_api.c:vcap_dup_rule
```
```
In drivers/net/ppp/ppp_generic.c (ffffffff81d16746)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_register_compressor
  - drivers/net/ppp/ppp_generic.c:ppp_register_net_channel
```
```
In drivers/net/slip/slhc.c (ffffffff81d1ce2a)
Location: include/linux/hash.h:74
Inline: True
```
```
In drivers/net/xen-netfront.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In drivers/cdrom/cdrom.c (ffffffff81d26b6f)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/cdrom/cdrom.c:cdrom_ioctl_drive_status
  - drivers/cdrom/cdrom.c:cdrom_ioctl_media_changed
  - drivers/cdrom/cdrom.c:dvd_read_manufact
  - drivers/cdrom/cdrom.c:dvd_read_bca
  - drivers/cdrom/cdrom.c:dvd_read_disckey
  - drivers/cdrom/cdrom.c:cdrom_select_disc
  - drivers/cdrom/cdrom.c:cdrom_number_of_slots
```
```
In drivers/usb/core/usb.c (ffffffff81d2d7d2)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/usb/core/usb.c:usb_alloc_dev
```
```
In drivers/usb/core/hub.c (ffffffff81d35fc6)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_port_connect
  - drivers/usb/core/hub.c:hub_port_init
  - drivers/usb/core/hub.c:hub_probe
  - drivers/usb/core/hub.c:hub_configure
  - drivers/usb/core/hub.c:hub_configure
  - drivers/usb/core/hub.c:hub_configure
  - drivers/usb/core/hub.c:usb_hub_clear_tt_buffer
```
```
In drivers/usb/core/hcd.c (ffffffff81d3a406)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/usb/core/hcd.c:__usb_create_hcd
  - drivers/usb/core/hcd.c:__usb_create_hcd
```
```
In drivers/usb/core/urb.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In drivers/usb/core/message.c (ffffffff81d3fe61)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_driver_set_configuration
  - drivers/usb/core/message.c:usb_set_configuration
  - drivers/usb/core/message.c:usb_get_device_descriptor
  - drivers/usb/core/message.c:usb_cache_string
  - drivers/usb/core/message.c:usb_string
  - drivers/usb/core/message.c:usb_control_msg
```
```
In drivers/usb/core/driver.c (ffffffff81d4381f)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/usb/core/driver.c:usb_unbind_interface
  - drivers/usb/core/driver.c:usb_store_new_id
```
```
In drivers/usb/core/config.c (ffffffff81d46f23)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/usb/core/config.c:usb_get_bos_descriptor
  - drivers/usb/core/config.c:usb_get_bos_descriptor
  - drivers/usb/core/config.c:usb_get_configuration
```
```
In drivers/usb/core/buffer.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In drivers/usb/core/endpoint.c (ffffffff81d4a640)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/usb/core/endpoint.c:usb_create_ep_devs
```
```
In drivers/usb/core/devio.c (ffffffff81d4d045)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:proc_do_submiturb
  - drivers/usb/core/devio.c:do_proc_control
  - drivers/usb/core/devio.c:usbdev_open
  - drivers/usb/core/devio.c:usbdev_mmap
```
```
In drivers/usb/core/quirks.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In drivers/usb/core/port.c (ffffffff81d539ce)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/usb/core/port.c:usb_hub_create_port_device
  - drivers/usb/core/port.c:usb_hub_create_port_device
```
```
In drivers/usb/dwc2/hcd.c (ffffffff81d64165)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_init
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue
```
```
In drivers/usb/dwc2/hcd_queue.c (ffffffff81d6ca8e)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_queue.c:dwc2_hcd_qh_create
```
```
In drivers/usb/dwc2/hcd_ddma.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff81d77f6e)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:iso_stream_find
  - drivers/usb/host/ehci-hcd.c:find_tt
  - drivers/usb/host/ehci-hcd.c:ehci_qh_alloc
  - drivers/usb/host/ehci-hcd.c:debug_registers_open
  - drivers/usb/host/ehci-hcd.c:debug_periodic_open
  - drivers/usb/host/ehci-hcd.c:debug_bandwidth_open
  - drivers/usb/host/ehci-hcd.c:debug_async_open
  - drivers/usb/host/ehci-hcd.c:fill_periodic_buffer
```
```
In drivers/usb/host/ohci-hcd.c (ffffffff81d850ae)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:debug_registers_open
  - drivers/usb/host/ohci-hcd.c:debug_periodic_open
  - drivers/usb/host/ohci-hcd.c:debug_async_open
  - drivers/usb/host/ohci-hcd.c:fill_periodic_buffer
```
```
In drivers/usb/host/uhci-hcd.c (ffffffff81d8ecfd)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/usb/host/uhci-hcd.c:uhci_start
  - drivers/usb/host/uhci-hcd.c:uhci_debug_open
```
```
In drivers/usb/host/xhci.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In drivers/usb/host/xhci-mem.c (ffffffff81d9d183)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_alloc_interrupter
  - drivers/usb/host/xhci-mem.c:xhci_alloc_command
  - drivers/usb/host/xhci-mem.c:xhci_alloc_command
  - drivers/usb/host/xhci-mem.c:scratchpad_alloc
  - drivers/usb/host/xhci-mem.c:xhci_alloc_virt_device
  - drivers/usb/host/xhci-mem.c:xhci_alloc_tt_info
  - drivers/usb/host/xhci-mem.c:xhci_alloc_stream_info
  - drivers/usb/host/xhci-mem.c:xhci_alloc_container_ctx
  - drivers/usb/host/xhci-mem.c:xhci_ring_alloc
  - drivers/usb/host/xhci-mem.c:xhci_segment_alloc
```
```
In drivers/usb/host/xhci-dbgcap.c (ffffffff81db5419)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgcap.c:xhci_alloc_dbc
  - drivers/usb/host/xhci-dbgcap.c:dbc_alloc_request
```
```
In drivers/usb/host/xhci-dbgtty.c (ffffffff81db6822)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_tty_probe
  - drivers/usb/host/xhci-dbgtty.c:xhci_dbc_alloc_requests
```
```
In drivers/usb/host/xhci-debugfs.c (ffffffff81db8e93)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_create_slot
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_create_endpoint
  - drivers/usb/host/xhci-debugfs.c:xhci_debugfs_regset
```
```
In drivers/usb/roles/class.c (ffffffff81dbb85c)
Location: include/linux/hash.h:74
Inline: True
```
```
In drivers/input/serio/serio.c (ffffffff81dbc0b4)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/input/serio/serio.c:serio_queue_event
```
```
In drivers/input/serio/i8042.c (ffffffff81dbe4b0)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/input/serio/i8042.c:i8042_create_aux_port
  - drivers/input/serio/i8042.c:i8042_create_kbd_port
```
```
In drivers/input/input.c (ffffffff81dc3e9e)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/input/input.c:input_allocate_device
```
```
In drivers/input/input-mt.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In drivers/input/input-poller.c (ffffffff81dc87dd)
Location: include/linux/hash.h:74
Inline: True
```
```
In drivers/input/ff-core.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In drivers/input/mousedev.c (ffffffff81dcb037)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/input/mousedev.c:mousedev_create
  - drivers/input/mousedev.c:mousedev_open
```
```
In drivers/input/evdev.c (ffffffff81dcc5db)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/input/evdev.c:evdev_connect
```
```
In drivers/input/keyboard/atkbd.c (ffffffff81dd056c)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/input/keyboard/atkbd.c:atkbd_connect
```
```
In drivers/input/misc/uinput.c (ffffffff81dd4a2c)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/input/misc/uinput.c:uinput_open
```
```
In drivers/rtc/class.c (ffffffff81dd6cfd)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/rtc/class.c:rtc_allocate_device
```
```
In drivers/i2c/i2c-boardinfo.c (ffffffff81ddee7a)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/i2c/i2c-boardinfo.c:i2c_register_board_info
```
```
In drivers/i2c/i2c-core-base.c (ffffffff81de32df)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_new_client_device
```
```
In drivers/i2c/i2c-core-smbus.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In drivers/i2c/i2c-core-acpi.c (ffffffff81de9026)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_install_space_handler
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_space_handler
```
```
In drivers/i2c/i2c-dev.c (ffffffff81de9b12)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/i2c/i2c-dev.c:i2cdev_attach_adapter
  - drivers/i2c/i2c-dev.c:i2cdev_open
```
```
In drivers/pps/kapi.c (ffffffff81deee87)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/pps/kapi.c:pps_register_source
```
```
In drivers/ptp/ptp_clock.c (ffffffff81defe8f)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/ptp/ptp_clock.c:ptp_clock_register
  - drivers/ptp/ptp_clock.c:ptp_clock_register
  - drivers/ptp/ptp_clock.c:ptp_clock_register
```
```
In drivers/ptp/ptp_chardev.c (ffffffff81df1a97)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/ptp/ptp_chardev.c:ptp_read
  - drivers/ptp/ptp_chardev.c:ptp_open
```
```
In drivers/ptp/ptp_sysfs.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In drivers/ptp/ptp_vclock.c (ffffffff81df35fe)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/ptp/ptp_vclock.c:ptp_vclock_register
```
```
In drivers/power/supply/power_supply_core.c (ffffffff81df565f)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_core.c:__power_supply_register
```
```
In drivers/hwmon/hwmon.c (ffffffff81dfb8dd)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/hwmon/hwmon.c:__hwmon_device_register
  - drivers/hwmon/hwmon.c:__hwmon_create_attrs
```
```
In drivers/thermal/thermal_core.c (ffffffff839585f9)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:thermal_init
  - drivers/thermal/thermal_core.c:thermal_zone_device_register_with_trips
  - drivers/thermal/thermal_core.c:thermal_bind_cdev_to_trip
```
```
In drivers/thermal/thermal_sysfs.c (ffffffff81e020da)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/thermal/thermal_sysfs.c:thermal_zone_create_device_groups
```
```
In drivers/thermal/thermal_hwmon.c (ffffffff81e04f17)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/thermal/thermal_hwmon.c:thermal_add_hwmon_sysfs
  - drivers/thermal/thermal_hwmon.c:thermal_add_hwmon_sysfs
```
```
In drivers/thermal/gov_power_allocator.c (ffffffff81e06c3e)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/thermal/gov_power_allocator.c:power_allocator_bind
  - drivers/thermal/gov_power_allocator.c:power_allocator_bind
```
```
In drivers/thermal/devfreq_cooling.c (ffffffff81e07e3c)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/thermal/devfreq_cooling.c:of_devfreq_cooling_register_power
```
```
In drivers/thermal/intel/intel_hfi.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In drivers/watchdog/watchdog_dev.c (ffffffff81e0c32e)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_dev.c:watchdog_cdev_register
```
```
In drivers/watchdog/watchdog_pretimeout.c (ffffffff81e0d8f1)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/watchdog/watchdog_pretimeout.c:watchdog_register_pretimeout
  - drivers/watchdog/watchdog_pretimeout.c:watchdog_register_governor
```
```
In drivers/md/md.c (ffffffff81e1c96e)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/md/md.c:md_autodetect_dev
  - drivers/md/md.c:md_register_thread
  - drivers/md/md.c:get_bitmap_file
  - drivers/md/md.c:md_import_device
  - drivers/md/md.c:md_sb_equal
  - drivers/md/md.c:md_sb_equal
  - drivers/md/md.c:mddev_alloc
```
```
In drivers/md/md-bitmap.c (ffffffff81e287ae)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/md/md-bitmap.c:md_bitmap_create
  - drivers/md/md-bitmap.c:md_bitmap_checkpage
```
```
In drivers/md/dm-init.c (ffffffff8395a23a)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/md/dm-init.c:dm_init_init
  - drivers/md/dm-init.c:dm_parse_table_entry
```
```
In drivers/md/dm-ima.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In drivers/md/dm.c (ffffffff81e305f3)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_get_table_device
```
```
In drivers/md/dm-table.c (ffffffff81e3302e)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_construct_crypto_profile
  - drivers/md/dm-table.c:dm_table_alloc_md_mempools
  - drivers/md/dm-table.c:dm_get_device
  - drivers/md/dm-table.c:dm_table_create
```
```
In drivers/md/dm-target.c (ffffffff81e3546f)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/md/dm-target.c:io_err_ctr
```
```
In drivers/md/dm-linear.c (ffffffff81e35b22)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/md/dm-linear.c:linear_ctr
```
```
In drivers/md/dm-stripe.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In drivers/md/dm-ioctl.c (ffffffff81e36e2f)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:dm_open
  - drivers/md/dm-ioctl.c:dm_hash_insert
```
```
In drivers/md/dm-io.c (ffffffff81e3b3c8)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/md/dm-io.c:dm_io_client_create
```
```
In drivers/md/dm-kcopyd.c (ffffffff81e3b98c)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/md/dm-kcopyd.c:dm_kcopyd_client_create
  - drivers/md/dm-kcopyd.c:alloc_pl
```
```
In drivers/md/dm-stats.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In drivers/md/dm-rq.c (ffffffff81e40453)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/md/dm-rq.c:dm_mq_init_request_queue
```
```
In drivers/edac/edac_mc.c (ffffffff81e424a9)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_mc_alloc
  - drivers/edac/edac_mc.c:edac_mc_alloc_dimms
  - drivers/edac/edac_mc.c:edac_mc_alloc_csrows
  - drivers/edac/edac_mc.c:edac_mc_alloc_csrows
```
```
In drivers/edac/edac_device.c (ffffffff81e42f1f)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/edac/edac_device.c:edac_device_alloc_ctl_info
```
```
In drivers/edac/edac_mc_sysfs.c (ffffffff8395ad71)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/edac/edac_mc_sysfs.c:edac_mc_sysfs_init
```
```
In drivers/edac/edac_pci.c (ffffffff81e45499)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/edac/edac_pci.c:edac_pci_alloc_ctl_info
```
```
In drivers/edac/edac_pci_sysfs.c (ffffffff81e45d85)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/edac/edac_pci_sysfs.c:edac_pci_create_sysfs
```
```
In drivers/eisa/eisa-bus.c (ffffffff8395b81f)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/eisa/eisa-bus.c:eisa_probe
  - drivers/eisa/eisa-bus.c:eisa_probe
```
```
In drivers/opp/core.c (ffffffff81e4a570)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/opp/core.c:dev_pm_opp_set_config
  - drivers/opp/core.c:_add_opp_table_indexed
  - drivers/opp/core.c:_add_opp_dev
```
```
In drivers/opp/cpu.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In drivers/cpufreq/cpufreq.c (ffffffff81e5227e)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq.c:cpufreq_online
  - drivers/cpufreq/cpufreq.c:cpufreq_policy_alloc
```
```
In drivers/cpufreq/cpufreq_stats.c (ffffffff81e538f4)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_stats.c:cpufreq_stats_create_table
```
```
In drivers/cpufreq/cpufreq_userspace.c (ffffffff81e53f6e)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_userspace.c:cpufreq_userspace_policy_init
```
```
In drivers/cpufreq/cpufreq_ondemand.c (ffffffff81e54def)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_ondemand.c:od_init
  - drivers/cpufreq/cpufreq_ondemand.c:od_alloc
```
```
In drivers/cpufreq/cpufreq_conservative.c (ffffffff81e55980)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_conservative.c:cs_init
  - drivers/cpufreq/cpufreq_conservative.c:cs_alloc
```
```
In drivers/cpufreq/cpufreq_governor.c (ffffffff81e561eb)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/cpufreq/cpufreq_governor.c:cpufreq_dbs_governor_init
```
```
In drivers/cpufreq/acpi-cpufreq.c (ffffffff81e57d78)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/cpufreq/acpi-cpufreq.c:acpi_cpufreq_cpu_init
```
```
In drivers/cpufreq/amd-pstate.c (ffffffff81e59d5a)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/cpufreq/amd-pstate.c:amd_pstate_epp_cpu_init
  - drivers/cpufreq/amd-pstate.c:amd_pstate_cpu_init
```
```
In drivers/cpufreq/powernow-k8.c (ffffffff81e5ceb6)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/cpufreq/powernow-k8.c:powernowk8_cpu_init
```
```
In drivers/cpufreq/intel_pstate.c (ffffffff81e61cd4)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/cpufreq/intel_pstate.c:intel_cpufreq_cpu_init
  - drivers/cpufreq/intel_pstate.c:intel_pstate_init_cpu
```
```
In drivers/cpuidle/sysfs.c (ffffffff81e661a5)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/cpuidle/sysfs.c:cpuidle_add_sysfs
  - drivers/cpuidle/sysfs.c:cpuidle_add_state_sysfs
```
```
In drivers/mmc/core/bus.c (ffffffff81e6e451)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/mmc/core/bus.c:mmc_alloc_card
```
```
In drivers/mmc/core/host.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In drivers/mmc/core/mmc_ops.c (ffffffff81e75511)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/mmc/core/mmc_ops.c:mmc_spi_send_cxd
```
```
In drivers/mmc/core/sd.c (ffffffff81e77c05)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/mmc/core/sd.c:_mmc_sd_suspend
  - drivers/mmc/core/sd.c:mmc_sd_init_card
  - drivers/mmc/core/sd.c:sd_flush_cache
  - drivers/mmc/core/sd.c:sd_read_ext_regs
  - drivers/mmc/core/sd.c:sd_parse_ext_reg
  - drivers/mmc/core/sd.c:sd_parse_ext_reg
  - drivers/mmc/core/sd.c:mmc_sd_setup_card
  - drivers/mmc/core/sd.c:mmc_read_ssr
```
```
In drivers/mmc/core/sd_ops.c (ffffffff81e79cce)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/mmc/core/sd_ops.c:mmc_app_send_scr
```
```
In drivers/mmc/core/sdio_bus.c (ffffffff81e7d451)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/mmc/core/sdio_bus.c:sdio_alloc_func
  - drivers/mmc/core/sdio_bus.c:sdio_alloc_func
```
```
In drivers/mmc/core/sdio_cis.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In drivers/leds/led-core.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In drivers/leds/led-triggers.c (ffffffff81e83e39)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/leds/led-triggers.c:led_trigger_register_simple
```
```
In drivers/firmware/edd.c (ffffffff8395faff)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/firmware/edd.c:edd_init
```
```
In drivers/firmware/dmi-id.c (ffffffff83960430)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/firmware/dmi-id.c:dmi_id_init
```
```
In drivers/firmware/memmap.c (ffffffff822335b3)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/firmware/memmap.c:firmware_map_add_hotplug
```
```
In drivers/firmware/efi/efi.c (ffffffff81e86cfc)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/firmware/efi/efi.c:efi_mem_reserve_iomem
```
```
In drivers/firmware/efi/capsule.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In drivers/firmware/efi/esrt.c (ffffffff8396311c)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/firmware/efi/esrt.c:esrt_sysfs_init
```
```
In drivers/firmware/efi/apple-properties.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In drivers/firmware/efi/embedded-firmware.c (ffffffff83964624)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/firmware/efi/embedded-firmware.c:efi_check_md_for_embedded_firmware
```
```
In drivers/firmware/efi/mokvar-table.c (ffffffff8396489d)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/firmware/efi/mokvar-table.c:efi_mokvar_sysfs_init
```
```
In drivers/hid/bpf/hid_bpf_dispatch.c (ffffffff81e8dff6)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/hid/bpf/hid_bpf_dispatch.c:hid_bpf_allocate_context
  - drivers/hid/bpf/hid_bpf_dispatch.c:call_hid_bpf_rdesc_fixup
```
```
In drivers/hid/bpf/hid_bpf_jmp_table.c (ffffffff81e8f730)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/hid/bpf/hid_bpf_jmp_table.c:hid_bpf_preload_skel
  - drivers/hid/bpf/hid_bpf_jmp_table.c:__hid_bpf_attach_prog
  - drivers/hid/bpf/hid_bpf_jmp_table.c:hid_bpf_populate_hdev
```
```
In drivers/staging/vme_user/vme.c (ffffffff81e91378)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/staging/vme_user/vme.c:__vme_register_driver_bus
  - drivers/staging/vme_user/vme.c:vme_lm_request
  - drivers/staging/vme_user/vme.c:vme_register_error_handler
  - drivers/staging/vme_user/vme.c:vme_dma_vme_attribute
  - drivers/staging/vme_user/vme.c:vme_dma_vme_attribute
  - drivers/staging/vme_user/vme.c:vme_dma_pci_attribute
  - drivers/staging/vme_user/vme.c:vme_dma_pci_attribute
  - drivers/staging/vme_user/vme.c:vme_dma_pattern_attribute
  - drivers/staging/vme_user/vme.c:vme_dma_pattern_attribute
  - drivers/staging/vme_user/vme.c:vme_new_dma_list
  - drivers/staging/vme_user/vme.c:vme_dma_request
  - drivers/staging/vme_user/vme.c:vme_master_request
  - drivers/staging/vme_user/vme.c:vme_slave_request
```
```
In drivers/platform/x86/amd/wbrf.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In drivers/platform/x86/intel_scu_ipc.c (ffffffff81e943e8)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/platform/x86/intel_scu_ipc.c:__intel_scu_ipc_register
```
```
In drivers/platform/x86/pmc_atom.c (ffffffff81e94f49)
Location: include/linux/hash.h:74
Inline: True
```
```
In drivers/platform/chrome/cros_ec_proto.c (ffffffff81e960fb)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_get_sensor_count
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_query_all
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_get_host_command_version_mask
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_get_proto_info_legacy
  - drivers/platform/chrome/cros_ec_proto.c:cros_ec_get_proto_info
```
```
In drivers/remoteproc/remoteproc_core.c (ffffffff81e9b34f)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:rproc_of_resm_mem_entry_init
  - drivers/remoteproc/remoteproc_core.c:rproc_mem_entry_init
  - drivers/remoteproc/remoteproc_core.c:rproc_alloc_carveout
  - drivers/remoteproc/remoteproc_core.c:rproc_handle_devmem
  - drivers/remoteproc/remoteproc_core.c:rproc_handle_trace
```
```
In drivers/remoteproc/remoteproc_coredump.c (ffffffff81e9df14)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_coredump.c:rproc_coredump_add_custom_segment
  - drivers/remoteproc/remoteproc_coredump.c:rproc_coredump_add_segment
```
```
In drivers/remoteproc/remoteproc_virtio.c (ffffffff81ea0274)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_virtio.c:rproc_add_virtio_dev
```
```
In drivers/hv/hv_common.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In drivers/devfreq/devfreq.c (ffffffff81ea51d8)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/devfreq/devfreq.c:devfreq_add_device
```
```
In drivers/devfreq/devfreq-event.c (ffffffff81ea6745)
Location: include/linux/hash.h:74
Inline: True
```
```
In drivers/devfreq/governor_userspace.c (ffffffff81ea7227)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/devfreq/governor_userspace.c:devfreq_userspace_handler
```
```
In drivers/devfreq/governor_passive.c (ffffffff81ea7635)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/devfreq/governor_passive.c:cpufreq_passive_register_notifier
```
```
In drivers/extcon/extcon.c (ffffffff81ea9e2c)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/extcon/extcon.c:extcon_dev_allocate
```
```
In drivers/powercap/powercap_sys.c (ffffffff81eabf80)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/powercap/powercap_sys.c:powercap_register_control_type
  - drivers/powercap/powercap_sys.c:powercap_register_zone
```
```
In drivers/powercap/idle_inject.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In drivers/nvmem/core.c (ffffffff81eb1b22)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/nvmem/core.c:nvmem_register
  - drivers/nvmem/core.c:nvmem_register
  - drivers/nvmem/core.c:nvmem_add_one_cell
```
```
In drivers/interconnect/core.c (ffffffff81eb4ef2)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/interconnect/core.c:of_icc_get_from_provider
```
```
In drivers/hte/hte.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In drivers/dpll/dpll_core.c (ffffffff81eb6b2d)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - drivers/dpll/dpll_core.c:dpll_pin_get
  - drivers/dpll/dpll_core.c:dpll_device_register
  - drivers/dpll/dpll_core.c:dpll_device_get
  - drivers/dpll/dpll_core.c:dpll_xa_ref_dpll_add
  - drivers/dpll/dpll_core.c:dpll_xa_ref_dpll_add
  - drivers/dpll/dpll_core.c:dpll_xa_ref_pin_add
  - drivers/dpll/dpll_core.c:dpll_xa_ref_pin_add
```
```
In net/core/sock.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In net/core/scm.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In net/core/gen_estimator.c (ffffffff81ee10e5)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - net/core/gen_estimator.c:gen_new_estimator
```
```
In net/core/net_namespace.c (ffffffff81ee3c96)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - net/core/net_namespace.c:copy_net_ns
```
```
In net/core/sysctl_net_core.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In net/core/dev.c (ffffffff81eed84c)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - net/core/dev.c:netdev_create_hash
  - net/core/dev.c:dev_ingress_queue_create
  - net/core/dev.c:register_netdevice
  - net/core/dev.c:bpf_xdp_link_attach
  - net/core/dev.c:netdev_offload_xstats_enable
  - net/core/dev.c:__netdev_adjacent_dev_insert
  - net/core/dev.c:netdev_name_node_alt_create
```
```
In net/core/dev_addr_lists.c (ffffffff81f01605)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - net/core/dev_addr_lists.c:__hw_addr_create
```
```
In net/core/dst.c (ffffffff81f03789)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - net/core/dst.c:dst_cow_metrics_generic
```
```
In net/core/neighbour.c (ffffffff81f083e5)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_table_init
  - net/core/neighbour.c:neigh_hash_alloc
```
```
In net/core/rtnetlink.c (ffffffff81f148a1)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - net/core/rtnetlink.c:rtnl_newlink
  - net/core/rtnetlink.c:rtnl_register_internal
  - net/core/rtnetlink.c:rtnl_register_internal
```
```
In net/core/filter.c (ffffffff81f3228c)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - net/core/filter.c:__sk_attach_prog
  - net/core/filter.c:bpf_prog_store_orig_filter
```
```
In net/core/sock_diag.c (ffffffff81f34ef0)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - net/core/sock_diag.c:sock_diag_broadcast_destroy
```
```
In net/core/sock_reuseport.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In net/core/xdp.c (ffffffff81f3858a)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - net/core/xdp.c:__xdp_reg_mem_model
  - net/core/xdp.c:__xdp_reg_mem_model
```
```
In net/core/flow_offload.c (ffffffff81f3b029)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - net/core/flow_offload.c:flow_indr_dev_setup_offload
  - net/core/flow_offload.c:flow_indr_block_cb_alloc
  - net/core/flow_offload.c:flow_indr_dev_register
  - net/core/flow_offload.c:flow_block_cb_setup_simple
```
```
In net/core/net-sysfs.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In net/core/page_pool.c (ffffffff81f43350)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - net/core/page_pool.c:page_pool_create
```
```
In net/core/netpoll.c (ffffffff81f47d4a)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - net/core/netpoll.c:__netpoll_setup
```
```
In net/core/fib_rules.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In net/core/drop_monitor.c (ffffffff81f5bc65)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - net/core/drop_monitor.c:dropmon_net_event
  - net/core/drop_monitor.c:net_dm_hw_trap_packet_probe
  - net/core/drop_monitor.c:net_dm_hw_reset_per_cpu_data
```
```
In net/core/selftests.c (ffffffff81f5e749)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - net/core/selftests.c:__net_test_loopback
```
```
In net/core/netprio_cgroup.c (ffffffff81f5f28c)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - net/core/netprio_cgroup.c:cgrp_css_alloc
```
```
In net/core/netclassid_cgroup.c (ffffffff81f5f77c)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - net/core/netclassid_cgroup.c:cgrp_css_alloc
```
```
In net/core/lwtunnel.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In net/core/gro_cells.c (ffffffff81f62421)
Location: include/linux/hash.h:74
Inline: True
```
```
In net/core/failover.c (ffffffff81f62d08)
Location: include/linux/hash.h:74
Inline: True
```
```
In net/core/skmsg.c (ffffffff81f65e00)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_init
  - net/core/skmsg.c:alloc_sk_msg
```
```
In net/core/sock_map.c (ffffffff81f69683)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_map_update_common
```
```
In net/core/bpf_sk_storage.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In net/sched/sch_generic.c (ffffffff81f6f1ca)
Location: include/linux/hash.h:74
Inline: True
```
```
In net/sched/sch_mq.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In net/sched/sch_api.c (ffffffff81f7375a)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - net/sched/sch_api.c:qdisc_get_rtab
```
```
In net/sched/cls_api.c (ffffffff81f793ec)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - net/sched/cls_api.c:tcf_exts_init_ex
  - net/sched/cls_api.c:tcf_exts_init_ex
  - net/sched/cls_api.c:tc_new_tfilter
  - net/sched/cls_api.c:tcf_block_get_ext
  - net/sched/cls_api.c:tcf_block_get_ext
  - net/sched/cls_api.c:tcf_block_get_ext
  - net/sched/cls_api.c:tcf_chain_create
```
```
In net/sched/act_api.c (ffffffff81f81a5f)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - net/sched/act_api.c:tcf_action_init_1
```
```
In net/sched/sch_fifo.c (ffffffff81f84785)
Location: include/linux/hash.h:74
Inline: True
```
```
In net/sched/ematch.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In net/netlink/af_netlink.c (ffffffff8396880c)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_proto_init
  - net/netlink/af_netlink.c:netlink_proto_init
```
```
In net/netlink/genetlink.c (ffffffff81f8eb12)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - net/netlink/genetlink.c:ctrl_dumppolicy_start
  - net/netlink/genetlink.c:genl_start
```
```
In net/netlink/policy.c (ffffffff81f90681)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - net/netlink/policy.c:netlink_policy_dump_add_policy
```
```
In net/bpf/test_run.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In net/bpf/bpf_dummy_struct_ops.c (ffffffff81f94a50)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - net/bpf/bpf_dummy_struct_ops.c:bpf_struct_ops_test_run
  - net/bpf/bpf_dummy_struct_ops.c:bpf_struct_ops_test_run
  - net/bpf/bpf_dummy_struct_ops.c:bpf_struct_ops_test_run
```
```
In net/ethtool/ioctl.c (ffffffff81f98612)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - net/ethtool/ioctl.c:ethtool_rx_flow_rule_create
  - net/ethtool/ioctl.c:dev_ethtool
  - net/ethtool/ioctl.c:ethtool_set_eeprom
  - net/ethtool/ioctl.c:ethtool_get_any_eeprom
```
```
In net/ethtool/common.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In net/ethtool/netlink.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In net/ethtool/strset.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In net/ethtool/rss.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In net/ethtool/privflags.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In net/ethtool/eeprom.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In net/netfilter/nf_log.c (ffffffff81fac8dc)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - net/netfilter/nf_log.c:nf_log_buf_open
```
```
In net/netfilter/nf_queue.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In net/netfilter/nf_bpf_link.c (ffffffff81faeb90)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - net/netfilter/nf_bpf_link.c:bpf_nf_link_attach
```
```
In net/ipv4/route.c (ffffffff81faf9ae)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_inetpeer_init
  - net/ipv4/route.c:update_or_create_fnhe
  - net/ipv4/route.c:fnhe_hashfun
  - net/ipv4/route.c:rt_acct_proc_show
```
```
In net/ipv4/ip_options.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In net/ipv4/ip_output.c (ffffffff81fbc583)
Location: include/linux/hash.h:74
Inline: True
```
```
In net/ipv4/ip_sockglue.c (ffffffff81fc26b9)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - net/ipv4/ip_sockglue.c:ip_ra_control
```
```
In net/ipv4/inet_hashtables.c (ffffffff81fc5090)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:inet_hashinfo2_init_mod
```
```
In net/ipv4/tcp.c (ffffffff81fd055a)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sendmsg_fastopen
```
```
In net/ipv4/tcp_input.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ff28e6)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_md5_do_add
```
```
In net/ipv4/tcp_metrics.c (ffffffff81ffc227)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - net/ipv4/tcp_metrics.c:tcpm_new
```
```
In net/ipv4/tcp_fastopen.c (ffffffff81ffe8d9)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_defer_connect
  - net/ipv4/tcp_fastopen.c:tcp_fastopen_reset_cipher
```
```
In net/ipv4/udp.c (ffffffff8200536f)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_pernet_init
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
```
```
In net/ipv4/devinet.c (ffffffff82017a52)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inetdev_init
```
```
In net/ipv4/af_inet.c (ffffffff8201a28d)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:ipv4_mib_init_net
```
```
In net/ipv4/igmp.c (ffffffff8201f932)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - net/ipv4/igmp.c:ip_mc_add_src
  - net/ipv4/igmp.c:sf_setstate
  - net/ipv4/igmp.c:____ip_mc_inc_group
  - net/ipv4/igmp.c:____ip_mc_inc_group
  - net/ipv4/igmp.c:__igmp_group_dropped
```
```
In net/ipv4/fib_frontend.c (ffffffff82023ae5)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:rtentry_to_fib_config
```
```
In net/ipv4/fib_semantics.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In net/ipv4/fib_trie.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In net/ipv4/inet_fragment.c (ffffffff82030410)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:fqdir_init
```
```
In net/ipv4/metrics.c (ffffffff82036e3a)
Location: include/linux/hash.h:74
Inline: True
```
```
In net/ipv4/nexthop.c (ffffffff8203914b)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nexthop_net_init
  - net/ipv4/nexthop.c:nexthop_create
  - net/ipv4/nexthop.c:nexthop_alloc
  - net/ipv4/nexthop.c:__call_nexthop_res_bucket_notifiers
  - net/ipv4/nexthop.c:nh_notifier_info_init
```
```
In net/ipv4/sysctl_net_ipv4.c (ffffffff8203eec8)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - net/ipv4/sysctl_net_ipv4.c:ipv4_sysctl_init_net
  - net/ipv4/sysctl_net_ipv4.c:proc_tcp_available_ulp
  - net/ipv4/sysctl_net_ipv4.c:proc_tcp_fastopen_key
  - net/ipv4/sysctl_net_ipv4.c:proc_allowed_congestion_control
  - net/ipv4/sysctl_net_ipv4.c:proc_tcp_available_congestion_control
```
```
In net/ipv4/proc.c (ffffffff82040888)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - net/ipv4/proc.c:netstat_seq_show
```
```
In net/ipv4/ipmr_base.c (ffffffff82049aa5)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - net/ipv4/ipmr_base.c:mr_table_alloc
```
```
In net/ipv4/syncookies.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In net/ipv4/tcp_sigpool.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In net/ipv4/tcp_bpf.c (ffffffff8204e961)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict
```
```
In net/ipv4/cipso_ipv4.c (ffffffff8396ae9c)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - net/ipv4/cipso_ipv4.c:cipso_v4_init
  - net/ipv4/cipso_ipv4.c:cipso_v4_req_setattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_sock_setattr
  - net/ipv4/cipso_ipv4.c:cipso_v4_cache_add
```
```
In net/ipv4/tcp_ao.c (ffffffff8205434f)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - net/ipv4/tcp_ao.c:tcp_ao_alloc_info
```
```
In net/xfrm/xfrm_policy.c (ffffffff82061654)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_policy_inexact_alloc_bin
  - net/xfrm/xfrm_policy.c:xfrm_policy_alloc
```
```
In net/xfrm/xfrm_hash.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In net/xfrm/espintcp.c (ffffffff820753fd)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - net/xfrm/espintcp.c:espintcp_init_sk
```
```
In net/unix/af_unix.c (ffffffff82078de2)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_autobind
```
```
In net/ipv6/af_inet6.c (ffffffff8207fa3f)
Location: include/linux/hash.h:74
Inline: True
```
```
In net/ipv6/anycast.c (ffffffff8208105d)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - net/ipv6/anycast.c:__ipv6_dev_ac_inc
```
```
In net/ipv6/ip6_output.c (ffffffff82082ba4)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_setup_cork
```
```
In net/ipv6/addrconf.c (ffffffff8208fb35)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_init_net
  - net/ipv6/addrconf.c:snmp6_alloc_dev
```
```
In net/ipv6/addrlabel.c (ffffffff820987f3)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_alloc
```
```
In net/ipv6/route.c (ffffffff8209a45e)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - net/ipv6/route.c:ipv6_inetpeer_init
  - net/ipv6/route.c:rt6_insert_exception
  - net/ipv6/route.c:rt6_probe
  - net/ipv6/route.c:rt6_probe
```
```
In net/ipv6/ip6_fib.c (ffffffff820ab001)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_metric_set
  - net/ipv6/ip6_fib.c:inet6_dump_fib
  - net/ipv6/ip6_fib.c:fib6_tables_dump
  - net/ipv6/ip6_fib.c:fib6_new_table
```
```
In net/ipv6/ipv6_sockglue.c (ffffffff820ad9e8)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - net/ipv6/ipv6_sockglue.c:ip6_ra_control
```
```
In net/ipv6/mcast.c (ffffffff820c3021)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - net/ipv6/mcast.c:ip6_mc_add_src
  - net/ipv6/mcast.c:sf_setstate
  - net/ipv6/mcast.c:__ipv6_dev_mc_inc
  - net/ipv6/mcast.c:igmp6_group_dropped
```
```
In net/ipv6/tcp_ipv6.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In net/ipv6/exthdrs.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In net/ipv6/ip6_flowlabel.c (ffffffff820d48a7)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - net/ipv6/ip6_flowlabel.c:ipv6_flowlabel_get
  - net/ipv6/ip6_flowlabel.c:fl_create
```
```
In net/ipv6/seg6.c (ffffffff820d6aae)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - net/ipv6/seg6.c:seg6_net_init
  - net/ipv6/seg6.c:seg6_net_init
  - net/ipv6/seg6.c:seg6_genl_dumphmac_start
  - net/ipv6/seg6.c:seg6_genl_sethmac
```
```
In net/ipv6/ioam6.c (ffffffff820d802e)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - net/ipv6/ioam6.c:ioam6_net_init
  - net/ipv6/ioam6.c:ioam6_genl_dumpsc_start
  - net/ipv6/ioam6.c:ioam6_genl_dumpns_start
  - net/ipv6/ioam6.c:ioam6_genl_addns
```
```
In net/ipv6/calipso.c (ffffffff820e6377)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - net/ipv6/calipso.c:calipso_cache_add
  - net/ipv6/calipso.c:calipso_init
```
```
In net/ipv6/seg6_hmac.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In net/ipv6/tcp_ao.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In net/packet/af_packet.c (ffffffff820f5750)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - net/packet/af_packet.c:packet_mc_add
  - net/packet/af_packet.c:fanout_add
```
```
In net/devlink/core.c (ffffffff821009b2)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - net/devlink/core.c:devlink_rel_nested_in_add
```
```
In net/devlink/netlink.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In net/devlink/sb.c (ffffffff82108534)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - net/devlink/sb.c:devl_sb_register
```
```
In net/devlink/dpipe.c (ffffffff8210a9a9)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - net/devlink/dpipe.c:devl_dpipe_table_register
```
```
In net/devlink/resource.c (ffffffff8210d28e)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - net/devlink/resource.c:devl_resource_register
```
```
In net/devlink/param.c (ffffffff8210eb0f)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - net/devlink/param.c:devl_params_register
```
```
In net/devlink/region.c (ffffffff82110579)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - net/devlink/region.c:devlink_port_region_create
  - net/devlink/region.c:devl_region_create
  - net/devlink/region.c:devlink_nl_region_read_dumpit
  - net/devlink/region.c:__devlink_region_snapshot_create
```
```
In net/devlink/health.c (ffffffff82114221)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - net/devlink/health.c:devlink_nl_health_reporter_diagnose_doit
  - net/devlink/health.c:devlink_health_do_dump
  - net/devlink/health.c:__devlink_health_reporter_create
```
```
In net/devlink/trap.c (ffffffff8211510c)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - net/devlink/trap.c:devl_trap_policers_register
  - net/devlink/trap.c:devl_trap_groups_register
```
```
In net/devlink/rate.c (ffffffff82118c89)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - net/devlink/rate.c:devl_rate_leaf_create
  - net/devlink/rate.c:devlink_nl_rate_new_doit
```
```
In net/devlink/linecard.c (ffffffff8211a3e9)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - net/devlink/linecard.c:devl_linecard_create
```
```
In net/8021q/vlan_core.c (ffffffff8211bd57)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - net/8021q/vlan_core.c:vlan_vid_add
  - net/8021q/vlan_core.c:vlan_vid_add
```
```
In net/wireless/wext-core.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In net/wireless/wext-priv.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In net/netlabel/netlabel_kapi.c (ffffffff821201e5)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - net/netlabel/netlabel_kapi.c:netlbl_cfg_calipso_map_add
  - net/netlabel/netlabel_kapi.c:netlbl_cfg_calipso_map_add
  - net/netlabel/netlabel_kapi.c:netlbl_cfg_calipso_map_add
  - net/netlabel/netlabel_kapi.c:netlbl_cfg_cipsov4_map_add
  - net/netlabel/netlabel_kapi.c:netlbl_cfg_cipsov4_map_add
  - net/netlabel/netlabel_kapi.c:netlbl_cfg_cipsov4_map_add
  - net/netlabel/netlabel_kapi.c:netlbl_cfg_unlbl_map_add
  - net/netlabel/netlabel_kapi.c:netlbl_cfg_unlbl_map_add
  - net/netlabel/netlabel_kapi.c:netlbl_cfg_unlbl_map_add
  - net/netlabel/netlabel_kapi.c:netlbl_cfg_unlbl_map_add
```
```
In net/netlabel/netlabel_domainhash.c (ffffffff8396d3f9)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - net/netlabel/netlabel_domainhash.c:netlbl_domhsh_init
```
```
In net/netlabel/netlabel_mgmt.c (ffffffff8212358c)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_add_common
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_add_common
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_add_common
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_add_common
  - net/netlabel/netlabel_mgmt.c:netlbl_mgmt_add_common
```
```
In net/netlabel/netlabel_unlabeled.c (ffffffff8396d758)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_defconf
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlabel_init
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_add
  - net/netlabel/netlabel_unlabeled.c:netlbl_unlhsh_add
```
```
In net/netlabel/netlabel_cipso_v4.c (ffffffff8212739f)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
```
```
In net/netlabel/netlabel_calipso.c (ffffffff82127a34)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - net/netlabel/netlabel_calipso.c:netlbl_calipso_add
```
```
In net/rfkill/core.c (ffffffff82129b04)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - net/rfkill/core.c:rfkill_fop_open
  - net/rfkill/core.c:rfkill_fop_open
  - net/rfkill/core.c:rfkill_send_events
```
```
In net/rfkill/input.c (ffffffff8212ac01)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - net/rfkill/input.c:rfkill_connect
```
```
In net/dcb/dcbnl.c (ffffffff8212bb29)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - net/dcb/dcbnl.c:dcb_app_add
  - net/dcb/dcbnl.c:dcbnl_getapptrust
```
```
In net/dns_resolver/dns_key.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In net/dns_resolver/dns_query.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In net/switchdev/switchdev.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In net/ncsi/ncsi-rsp.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In net/ncsi/ncsi-manage.c (ffffffff8213a345)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - net/ncsi/ncsi-manage.c:ncsi_vlan_rx_add_vid
  - net/ncsi/ncsi-manage.c:ncsi_add_package
  - net/ncsi/ncsi-manage.c:ncsi_add_channel
```
```
In net/xdp/xdp_umem.c (ffffffff821407de)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_create
```
```
In net/xdp/xsk_queue.c (ffffffff821408f9)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - net/xdp/xsk_queue.c:xskq_create
```
```
In net/xdp/xsk_buff_pool.c (ffffffff82141d3a)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - net/xdp/xsk_buff_pool.c:xp_dma_map
```
```
In net/mptcp/subflow.c (ffffffff8214de16)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - net/mptcp/subflow.c:subflow_create_ctx
```
```
In net/mptcp/pm_netlink.c (ffffffff8215ae91)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_get_local_id
  - net/mptcp/pm_netlink.c:mptcp_pm_alloc_anno_list
```
```
In net/mctp/device.c (ffffffff82164830)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - net/mctp/device.c:mctp_add_dev
```
```
In net/mctp/route.c (ffffffff82165d72)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - net/mctp/route.c:mctp_route_add
  - net/mctp/route.c:mctp_key_alloc
```
```
In net/mctp/neigh.c (ffffffff8216829b)
Location: include/linux/hash.h:74
Inline: True
```
```
In net/handshake/request.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In arch/x86/pci/i386.c (ffffffff8216d10c)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - arch/x86/pci/i386.c:pcibios_allocate_dev_resources
```
```
In arch/x86/pci/mmconfig-shared.c (ffffffff8216e1f9)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - arch/x86/pci/mmconfig-shared.c:pci_mmconfig_alloc
```
```
In arch/x86/pci/xen.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In arch/x86/pci/fixup.c (ffffffff82170ac6)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - arch/x86/pci/fixup.c:pci_amd_enable_64bit_bar
```
```
In arch/x86/pci/acpi.c (ffffffff821711eb)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - arch/x86/pci/acpi.c:pci_acpi_scan_root
```
```
In arch/x86/pci/irq.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In arch/x86/pci/common.c (ffffffff82173a90)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - arch/x86/pci/common.c:pcibios_scan_root
```
```
In arch/x86/pci/bus_numa.c (ffffffff8217443e)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - arch/x86/pci/bus_numa.c:update_res
  - arch/x86/pci/bus_numa.c:alloc_pci_root_info
```
```
In arch/x86/power/cpu.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In lib/argv_split.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In lib/cpumask.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In lib/decompress_bunzip2.c (ffffffff8397416e)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - lib/decompress_bunzip2.c:bunzip2
  - lib/decompress_bunzip2.c:bunzip2
```
```
In lib/decompress_inflate.c (ffffffff8397475c)
Location: include/linux/hash.h:74
Inline: True
```
```
In lib/decompress_unlzma.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In lib/decompress_unlzo.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In lib/decompress_unxz.c (ffffffff83976bd4)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - lib/decompress_unxz.c:unxz
  - lib/decompress_unxz.c:unxz
```
```
In lib/idr.c (ffffffff8217961b)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - lib/idr.c:ida_alloc_range
  - lib/idr.c:ida_alloc_range
  - lib/idr.c:ida_alloc_range
```
```
In lib/kobject.c (ffffffff8217b733)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - lib/kobject.c:kset_create_and_add
  - lib/kobject.c:kobject_create_and_add
```
```
In lib/kobject_uevent.c (ffffffff8217c8d1)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - lib/kobject_uevent.c:uevent_net_init
  - lib/kobject_uevent.c:kobject_uevent_env
  - lib/kobject_uevent.c:kobject_action_args
```
```
In lib/memcat_p.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In lib/objpool.c (0)
Location: include/linux/hash.h:74
Inline: True
```
```
In lib/vsprintf.c (ffffffff8219d5b0)
Location: include/linux/hash.h:74
Inline: True
Inline callers:
  - lib/vsprintf.c:default_pointer
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
In kernel/workqueue.c (ffff80001011e19c)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - kernel/workqueue.c:work_busy
  - kernel/workqueue.c:process_one_work
  - kernel/workqueue.c:__queue_work
```
```
In kernel/ucount.c (ffff80001012fe38)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - kernel/ucount.c:get_ucounts
```
```
In kernel/sched/wait_bit.c (ffff800010159200)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - kernel/sched/wait_bit.c:wake_up_var
  - kernel/sched/wait_bit.c:wake_up_bit
  - kernel/sched/wait_bit.c:out_of_line_wait_on_bit_lock
  - kernel/sched/wait_bit.c:out_of_line_wait_on_bit_timeout
  - kernel/sched/wait_bit.c:out_of_line_wait_on_bit
```
```
In kernel/cgroup/cgroup.c (ffff80001144ae08)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/cgroup/cgroup.c:find_css_set
  - kernel/cgroup/cgroup.c:find_css_set
```
```
In kernel/kprobes.c (ffff8000101f8438)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - kernel/kprobes.c:pre_handler_kretprobe
  - kernel/kprobes.c:__get_valid_kprobe
  - kernel/kprobes.c:kprobe_flush_task
  - kernel/kprobes.c:kretprobe_hash_unlock
  - kernel/kprobes.c:kretprobe_hash_lock
```
```
In kernel/trace/ftrace.c (ffff800010215a50)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_module_enable
  - kernel/trace/ftrace.c:__add_hash_entry
  - kernel/trace/ftrace.c:ftrace_lookup_ip
  - kernel/trace/ftrace.c:profile_graph_return
```
```
In kernel/events/core.c (ffff8000102a0954)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - kernel/events/core.c:perf_swevent_add
  - kernel/events/core.c:___perf_sw_event
```
```
In mm/filemap.c (ffff8000102b1638)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:__lock_page_killable
  - mm/filemap.c:__lock_page
  - mm/filemap.c:add_page_wait_queue
  - mm/filemap.c:put_and_wait_on_page_locked
  - mm/filemap.c:wake_up_page_bit
```
```
In mm/ksm.c (ffff800010341d84)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - mm/ksm.c:__ksm_exit
  - mm/ksm.c:__ksm_enter
```
```
In mm/khugepaged.c (ffff80001035de78)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:__khugepaged_exit
  - mm/khugepaged.c:__khugepaged_enter
```
```
In fs/dax.c (ffff80001040886c)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - fs/dax.c:wait_entry_unlocked
  - fs/dax.c:get_unlocked_entry
  - fs/dax.c:dax_wake_entry
```
```
In fs/crypto/keysetup_v1.c (ffff80001040f7bc)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:find_or_insert_direct_key
```
```
In fs/locks.c (ffff800010418570)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:__locks_insert_block
```
```
In fs/kernfs/dir.c (ffff80001045167c)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_name_hash
```
```
In fs/jbd2/revoke.c (ffff8000104d1f98)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:find_revoke_record
  - fs/jbd2/revoke.c:insert_revoke_hash
```
```
In fs/fat/namei_vfat.c (ffff8000104efd9c)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - fs/fat/namei_vfat.c:vfat_hashi
```
```
In fs/ecryptfs/messaging.c (ffff8000104fd0cc)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - fs/ecryptfs/messaging.c:ecryptfs_spawn_daemon
  - fs/ecryptfs/messaging.c:ecryptfs_find_daemon_by_euid
```
```
In fs/fuse/dev.c (ffff800010505144)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_do_write
```
```
In fs/efivarfs/super.c (ffff80001051c39c)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - fs/efivarfs/super.c:efivarfs_d_hash
```
```
In security/tomoyo/memory.c (ffff8000105841d4)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - security/tomoyo/memory.c:tomoyo_get_name
```
```
In security/integrity/ima/ima_queue.c (ffff8000105ade80)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - security/integrity/ima/ima_queue.c:ima_add_template_entry
```
```
In block/elevator.c (ffff8000105de92c)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - block/elevator.c:elv_rqhash_find
```
```
In net/core/bpf_sk_storage.c (ffff800010c311c8)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:selem_link_map
  - net/core/bpf_sk_storage.c:selem_unlink_map
```
```
In net/ipv4/udp.c (ffff800010c9c5f0)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
```
```
In lib/vsprintf.c (ffff800010d95c2c)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - lib/vsprintf.c:ptr_to_id
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
In kernel/events/core.c (c04d0c50)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - kernel/events/core.c:perf_swevent_add
  - kernel/events/core.c:___perf_sw_event
```
```
In fs/jbd2/revoke.c (c06946e0)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:insert_revoke_hash
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
In kernel/workqueue.c (c000000000164a9c)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - kernel/workqueue.c:work_busy
  - kernel/workqueue.c:process_one_work
  - kernel/workqueue.c:__queue_work
```
```
In kernel/ucount.c (c0000000001797a0)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - kernel/ucount.c:inc_ucount
```
```
In kernel/sched/wait_bit.c (c0000000001ad6d0)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - kernel/sched/wait_bit.c:wake_up_var
  - kernel/sched/wait_bit.c:wake_up_bit
  - kernel/sched/wait_bit.c:out_of_line_wait_on_bit_lock
  - kernel/sched/wait_bit.c:out_of_line_wait_on_bit_timeout
  - kernel/sched/wait_bit.c:out_of_line_wait_on_bit
```
```
In kernel/livepatch/shadow.c (c0000000001f244c)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - kernel/livepatch/shadow.c:klp_shadow_free
  - kernel/livepatch/shadow.c:__klp_shadow_get_or_alloc
  - kernel/livepatch/shadow.c:klp_shadow_get
```
```
In kernel/cgroup/cgroup.c (c0000000013705cc)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/cgroup/cgroup.c:find_css_set
  - kernel/cgroup/cgroup.c:find_css_set
```
```
In kernel/kprobes.c (c00000000026cd04)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - kernel/kprobes.c:pre_handler_kretprobe
  - kernel/kprobes.c:__get_valid_kprobe
  - kernel/kprobes.c:kprobe_flush_task
  - kernel/kprobes.c:kretprobe_hash_unlock
  - kernel/kprobes.c:kretprobe_hash_lock
  - kernel/kprobes.c:get_optimized_kprobe
```
```
In kernel/trace/ftrace.c (c0000000002974d4)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_module_enable
  - kernel/trace/ftrace.c:hash_contains_ip
  - kernel/trace/ftrace.c:hash_contains_ip
  - kernel/trace/ftrace.c:__add_hash_entry
  - kernel/trace/ftrace.c:ftrace_lookup_ip
  - kernel/trace/ftrace.c:profile_graph_return
```
```
In kernel/events/core.c (c0000000003527d4)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - kernel/events/core.c:perf_swevent_add
  - kernel/events/core.c:___perf_sw_event
```
```
In mm/filemap.c (c000000000366e80)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:__lock_page_killable
  - mm/filemap.c:__lock_page
  - mm/filemap.c:add_page_wait_queue
  - mm/filemap.c:put_and_wait_on_page_locked
  - mm/filemap.c:wake_up_page_bit
```
```
In mm/ksm.c (c00000000041f500)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - mm/ksm.c:__ksm_exit
  - mm/ksm.c:__ksm_enter
```
```
In mm/khugepaged.c (c000000000449614)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:__khugepaged_exit
  - mm/khugepaged.c:__khugepaged_enter
```
```
In fs/dax.c (c000000000513e5c)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - fs/dax.c:wait_entry_unlocked
  - fs/dax.c:get_unlocked_entry
  - fs/dax.c:dax_wake_entry
```
```
In fs/crypto/keysetup_v1.c (c00000000051ce3c)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:find_or_insert_direct_key
```
```
In fs/locks.c (c000000000525e50)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:__locks_insert_block
```
```
In fs/kernfs/dir.c (c000000000569e0c)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_name_hash
```
```
In fs/jbd2/revoke.c (c00000000060b778)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:find_revoke_record
  - fs/jbd2/revoke.c:insert_revoke_hash
```
```
In fs/fat/namei_vfat.c (c00000000062f0cc)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - fs/fat/namei_vfat.c:vfat_hashi
```
```
In fs/ecryptfs/messaging.c (c000000000640304)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - fs/ecryptfs/messaging.c:ecryptfs_spawn_daemon
  - fs/ecryptfs/messaging.c:ecryptfs_find_daemon_by_euid
```
```
In fs/fuse/dev.c (c00000000064a514)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_do_write
  - fs/fuse/dev.c:fuse_dev_do_read
```
```
In security/tomoyo/memory.c (c0000000006f31b0)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - security/tomoyo/memory.c:tomoyo_get_name
```
```
In security/integrity/ima/ima_queue.c (c00000000072ca64)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - security/integrity/ima/ima_queue.c:ima_add_template_entry
  - security/integrity/ima/ima_queue.c:ima_add_digest_entry
```
```
In block/elevator.c (c000000000770658)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - block/elevator.c:elv_rqhash_find
  - block/elevator.c:elv_rqhash_add
```
```
In net/core/bpf_sk_storage.c (c000000000d29ea0)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:selem_link_map
  - net/core/bpf_sk_storage.c:selem_unlink_map
```
```
In net/ipv4/udp.c (c000000000daeb44)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
```
```
In lib/vsprintf.c (c000000000edb0a0)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - lib/vsprintf.c:ptr_to_id
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
In kernel/workqueue.c (ffffffe0000d6712)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - kernel/workqueue.c:work_busy
  - kernel/workqueue.c:process_one_work
  - kernel/workqueue.c:__queue_work
```
```
In kernel/ucount.c (ffffffe0000e376e)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - kernel/ucount.c:inc_ucount
```
```
In kernel/sched/wait_bit.c (ffffffe0000ff2bc)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - kernel/sched/wait_bit.c:wake_up_var
  - kernel/sched/wait_bit.c:wake_up_bit
  - kernel/sched/wait_bit.c:out_of_line_wait_on_bit_lock
  - kernel/sched/wait_bit.c:out_of_line_wait_on_bit_timeout
  - kernel/sched/wait_bit.c:out_of_line_wait_on_bit
```
```
In kernel/cgroup/cgroup.c (ffffffe00000c1e8)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/cgroup/cgroup.c:find_css_set
  - kernel/cgroup/cgroup.c:find_css_set
```
```
In kernel/trace/ftrace.c (ffffffe0001756f2)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_module_enable
  - kernel/trace/ftrace.c:hash_contains_ip
  - kernel/trace/ftrace.c:hash_contains_ip
  - kernel/trace/ftrace.c:__add_hash_entry
  - kernel/trace/ftrace.c:ftrace_lookup_ip
  - kernel/trace/ftrace.c:profile_graph_return
```
```
In kernel/events/core.c (ffffffe0001cfd22)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - kernel/events/core.c:perf_swevent_add
  - kernel/events/core.c:___perf_sw_event
```
```
In mm/filemap.c (ffffffe0001d6d40)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:__lock_page_killable
  - mm/filemap.c:__lock_page
  - mm/filemap.c:add_page_wait_queue
  - mm/filemap.c:put_and_wait_on_page_locked
  - mm/filemap.c:wake_up_page_bit
```
```
In mm/ksm.c (ffffffe000236108)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - mm/ksm.c:__ksm_exit
  - mm/ksm.c:__ksm_enter
```
```
In fs/namei.c (ffffffe0002633ea)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - fs/namei.c:lookup_one_len_common
  - fs/namei.c:hashlen_string
```
```
In fs/dax.c (ffffffe0002b2b50)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - fs/dax.c:wait_entry_unlocked
  - fs/dax.c:get_unlocked_entry
  - fs/dax.c:dax_wake_entry
```
```
In fs/crypto/keysetup_v1.c (ffffffe0002b8242)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:find_or_insert_direct_key
```
```
In fs/locks.c (ffffffe0002bef80)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:__locks_insert_block
```
```
In fs/kernfs/dir.c (ffffffe0002e47b0)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_name_hash
```
```
In fs/jbd2/revoke.c (ffffffe000349284)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:find_revoke_record
  - fs/jbd2/revoke.c:insert_revoke_hash
```
```
In fs/fat/namei_vfat.c (ffffffe00035fb98)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - fs/fat/namei_vfat.c:vfat_hashi
```
```
In fs/ecryptfs/messaging.c (ffffffe00036b7e4)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - fs/ecryptfs/messaging.c:ecryptfs_spawn_daemon
  - fs/ecryptfs/messaging.c:ecryptfs_find_daemon_by_euid
```
```
In fs/fuse/dev.c (ffffffe000371b52)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_do_write
```
```
In security/tomoyo/memory.c (ffffffe0003d4278)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - security/tomoyo/memory.c:tomoyo_get_name
```
```
In security/integrity/ima/ima_queue.c (ffffffe0003f6190)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - security/integrity/ima/ima_queue.c:ima_add_template_entry
  - security/integrity/ima/ima_queue.c:ima_add_digest_entry
```
```
In block/elevator.c (ffffffe00042153a)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - block/elevator.c:elv_rqhash_find
```
```
In net/core/bpf_sk_storage.c (ffffffe0007a6e20)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:selem_link_map
  - net/core/bpf_sk_storage.c:selem_unlink_map
```
```
In net/ipv4/udp.c (ffffffe0007fa67a)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
```
```
In lib/vsprintf.c (ffffffe0008bf74a)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - lib/vsprintf.c:ptr_to_id
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
In arch/x86/mm/kmmio.c (ffffffff81089ebe)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:kmmio_page_list
```
```
In kernel/workqueue.c (ffffffff810b9b1e)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - kernel/workqueue.c:work_busy
  - kernel/workqueue.c:__flush_work
  - kernel/workqueue.c:process_one_work
  - kernel/workqueue.c:__queue_work
```
```
In kernel/ucount.c (ffffffff810ca055)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - kernel/ucount.c:inc_ucount
```
```
In kernel/sched/wait_bit.c (ffffffff810eef95)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - kernel/sched/wait_bit.c:wake_up_var
  - kernel/sched/wait_bit.c:wake_up_bit
  - kernel/sched/wait_bit.c:out_of_line_wait_on_bit_lock
  - kernel/sched/wait_bit.c:out_of_line_wait_on_bit_timeout
  - kernel/sched/wait_bit.c:out_of_line_wait_on_bit
```
```
In kernel/locking/qspinlock.c (ffffffff810fe2a9)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - kernel/locking/qspinlock.c:__pv_queued_spin_unlock_slowpath
```
```
In kernel/livepatch/shadow.c (ffffffff81125db6)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - kernel/livepatch/shadow.c:klp_shadow_free
  - kernel/livepatch/shadow.c:__klp_shadow_get_or_alloc
  - kernel/livepatch/shadow.c:klp_shadow_get
```
```
In kernel/cgroup/cgroup.c (ffffffff828bb758)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/cgroup/cgroup.c:find_css_set
  - kernel/cgroup/cgroup.c:find_css_set
```
```
In kernel/kprobes.c (ffffffff81179ced)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - kernel/kprobes.c:pre_handler_kretprobe
  - kernel/kprobes.c:__get_valid_kprobe
  - kernel/kprobes.c:kprobe_flush_task
  - kernel/kprobes.c:kretprobe_hash_unlock
  - kernel/kprobes.c:kretprobe_hash_lock
  - kernel/kprobes.c:get_optimized_kprobe
```
```
In kernel/trace/ftrace.c (ffffffff81195258)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_module_enable
  - kernel/trace/ftrace.c:__add_hash_entry
  - kernel/trace/ftrace.c:ftrace_lookup_ip
  - kernel/trace/ftrace.c:profile_graph_return
```
```
In kernel/events/core.c (ffffffff81209bd8)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - kernel/events/core.c:perf_swevent_add
  - kernel/events/core.c:___perf_sw_event
```
```
In mm/filemap.c (ffffffff8121c27e)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:__lock_page_killable
  - mm/filemap.c:__lock_page
  - mm/filemap.c:add_page_wait_queue
  - mm/filemap.c:put_and_wait_on_page_locked
  - mm/filemap.c:wake_up_page_bit
```
```
In mm/ksm.c (ffffffff8129aa1a)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - mm/ksm.c:__ksm_exit
  - mm/ksm.c:__ksm_enter
```
```
In mm/khugepaged.c (ffffffff812b518d)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:__khugepaged_exit
  - mm/khugepaged.c:__khugepaged_enter
```
```
In fs/dax.c (ffffffff8134035d)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - fs/dax.c:wait_entry_unlocked
  - fs/dax.c:get_unlocked_entry
  - fs/dax.c:dax_wake_entry
```
```
In fs/crypto/keysetup_v1.c (ffffffff8134688f)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:find_or_insert_direct_key
```
```
In fs/locks.c (ffffffff8134df4c)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:__locks_insert_block
```
```
In fs/kernfs/dir.c (ffffffff8137b669)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_name_hash
```
```
In fs/jbd2/revoke.c (ffffffff813ee7c4)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:find_revoke_record
  - fs/jbd2/revoke.c:insert_revoke_hash
```
```
In fs/fat/namei_vfat.c (ffffffff81407579)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - fs/fat/namei_vfat.c:vfat_hashi
```
```
In fs/ecryptfs/messaging.c (ffffffff81414211)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - fs/ecryptfs/messaging.c:ecryptfs_spawn_daemon
  - fs/ecryptfs/messaging.c:ecryptfs_find_daemon_by_euid
```
```
In fs/fuse/dev.c (ffffffff8141aa18)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_do_write
```
```
In fs/efivarfs/super.c (ffffffff8142e618)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - fs/efivarfs/super.c:efivarfs_d_hash
```
```
In security/tomoyo/memory.c (ffffffff814885fd)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - security/tomoyo/memory.c:tomoyo_get_name
```
```
In security/integrity/ima/ima_queue.c (ffffffff814adf95)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - security/integrity/ima/ima_queue.c:ima_add_template_entry
  - security/integrity/ima/ima_queue.c:ima_add_digest_entry
```
```
In block/elevator.c (ffffffff814d9e25)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - block/elevator.c:elv_rqhash_find
```
```
In net/core/bpf_sk_storage.c (ffffffff81928b45)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:selem_link_map
  - net/core/bpf_sk_storage.c:selem_unlink_map
```
```
In net/ipv4/udp.c (ffffffff81987f23)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
```
```
In lib/vsprintf.c (ffffffff81a59d11)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - lib/vsprintf.c:ptr_to_id
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
In arch/x86/mm/kmmio.c (ffffffff81078a9e)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:kmmio_page_list
```
```
In kernel/workqueue.c (ffffffff810a845e)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - kernel/workqueue.c:work_busy
  - kernel/workqueue.c:__flush_work
  - kernel/workqueue.c:process_one_work
  - kernel/workqueue.c:__queue_work
```
```
In kernel/ucount.c (ffffffff810b8875)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - kernel/ucount.c:inc_ucount
```
```
In kernel/sched/wait_bit.c (ffffffff810df015)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - kernel/sched/wait_bit.c:wake_up_var
  - kernel/sched/wait_bit.c:wake_up_bit
  - kernel/sched/wait_bit.c:out_of_line_wait_on_bit_lock
  - kernel/sched/wait_bit.c:out_of_line_wait_on_bit_timeout
  - kernel/sched/wait_bit.c:out_of_line_wait_on_bit
```
```
In kernel/locking/qspinlock.c (ffffffff810ee4a9)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - kernel/locking/qspinlock.c:__pv_queued_spin_unlock_slowpath
```
```
In kernel/livepatch/shadow.c (ffffffff81118816)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - kernel/livepatch/shadow.c:klp_shadow_free
  - kernel/livepatch/shadow.c:__klp_shadow_get_or_alloc
  - kernel/livepatch/shadow.c:klp_shadow_get
```
```
In kernel/cgroup/cgroup.c (ffffffff828b3deb)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/cgroup/cgroup.c:find_css_set
  - kernel/cgroup/cgroup.c:find_css_set
```
```
In kernel/kprobes.c (ffffffff8116ce8d)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - kernel/kprobes.c:pre_handler_kretprobe
  - kernel/kprobes.c:__get_valid_kprobe
  - kernel/kprobes.c:kprobe_flush_task
  - kernel/kprobes.c:kretprobe_hash_unlock
  - kernel/kprobes.c:kretprobe_hash_lock
  - kernel/kprobes.c:get_optimized_kprobe
```
```
In kernel/trace/ftrace.c (ffffffff81188368)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_module_enable
  - kernel/trace/ftrace.c:__add_hash_entry
  - kernel/trace/ftrace.c:ftrace_lookup_ip
  - kernel/trace/ftrace.c:profile_graph_return
```
```
In kernel/events/core.c (ffffffff811fc988)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - kernel/events/core.c:perf_swevent_add
  - kernel/events/core.c:___perf_sw_event
```
```
In mm/filemap.c (ffffffff8120f46e)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:__lock_page_killable
  - mm/filemap.c:__lock_page
  - mm/filemap.c:add_page_wait_queue
  - mm/filemap.c:put_and_wait_on_page_locked
  - mm/filemap.c:wake_up_page_bit
```
```
In mm/ksm.c (ffffffff8128c5da)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - mm/ksm.c:__ksm_exit
  - mm/ksm.c:__ksm_enter
```
```
In mm/khugepaged.c (ffffffff812a61af)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:__khugepaged_exit
  - mm/khugepaged.c:__khugepaged_enter
```
```
In fs/dax.c (ffffffff81330fdd)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - fs/dax.c:wait_entry_unlocked
  - fs/dax.c:get_unlocked_entry
  - fs/dax.c:dax_wake_entry
```
```
In fs/crypto/keysetup_v1.c (ffffffff8133756f)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:find_or_insert_direct_key
```
```
In fs/locks.c (ffffffff8133ec2c)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:__locks_insert_block
```
```
In fs/kernfs/dir.c (ffffffff8136c139)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_name_hash
```
```
In fs/jbd2/revoke.c (ffffffff813df244)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:find_revoke_record
  - fs/jbd2/revoke.c:insert_revoke_hash
```
```
In fs/fat/namei_vfat.c (ffffffff813f7ff9)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - fs/fat/namei_vfat.c:vfat_hashi
```
```
In fs/ecryptfs/messaging.c (ffffffff81404c91)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - fs/ecryptfs/messaging.c:ecryptfs_spawn_daemon
  - fs/ecryptfs/messaging.c:ecryptfs_find_daemon_by_euid
```
```
In fs/fuse/dev.c (ffffffff8140b498)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_do_write
```
```
In fs/efivarfs/super.c (ffffffff8141f098)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - fs/efivarfs/super.c:efivarfs_d_hash
```
```
In security/tomoyo/memory.c (ffffffff8147901d)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - security/tomoyo/memory.c:tomoyo_get_name
```
```
In security/integrity/ima/ima_queue.c (ffffffff8149e9b5)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - security/integrity/ima/ima_queue.c:ima_add_template_entry
  - security/integrity/ima/ima_queue.c:ima_add_digest_entry
```
```
In block/elevator.c (ffffffff814ca7d5)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - block/elevator.c:elv_rqhash_find
```
```
In drivers/net/vxlan.c (ffffffff8176f754)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - drivers/net/vxlan.c:vxlan_switchdev_event
  - drivers/net/vxlan.c:vxlan_switchdev_event
  - drivers/net/vxlan.c:vxlan_fdb_offloaded_set
  - drivers/net/vxlan.c:vxlan_snoop
  - drivers/net/vxlan.c:vxlan_fdb_delete
  - drivers/net/vxlan.c:vxlan_fdb_add
  - drivers/net/vxlan.c:vxlan_fdb_insert
  - drivers/net/vxlan.c:__vxlan_find_mac
```
```
In net/core/bpf_sk_storage.c (ffffffff818e28f5)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:selem_link_map
  - net/core/bpf_sk_storage.c:selem_unlink_map
```
```
In net/ipv4/udp.c (ffffffff819419e3)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
```
```
In lib/vsprintf.c (ffffffff81a16df1)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - lib/vsprintf.c:ptr_to_id
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
In arch/x86/mm/kmmio.c (ffffffff81089e6e)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:kmmio_page_list
```
```
In kernel/workqueue.c (ffffffff810b907e)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - kernel/workqueue.c:work_busy
  - kernel/workqueue.c:__flush_work
  - kernel/workqueue.c:process_one_work
  - kernel/workqueue.c:__queue_work
```
```
In kernel/ucount.c (ffffffff810c9585)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - kernel/ucount.c:inc_ucount
```
```
In kernel/sched/wait_bit.c (ffffffff810ec0c5)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - kernel/sched/wait_bit.c:wake_up_var
  - kernel/sched/wait_bit.c:wake_up_bit
  - kernel/sched/wait_bit.c:out_of_line_wait_on_bit_lock
  - kernel/sched/wait_bit.c:out_of_line_wait_on_bit_timeout
  - kernel/sched/wait_bit.c:out_of_line_wait_on_bit
```
```
In kernel/locking/qspinlock.c (ffffffff810fb469)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - kernel/locking/qspinlock.c:__pv_queued_spin_unlock_slowpath
```
```
In kernel/livepatch/shadow.c (ffffffff81123ca6)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - kernel/livepatch/shadow.c:klp_shadow_free
  - kernel/livepatch/shadow.c:__klp_shadow_get_or_alloc
  - kernel/livepatch/shadow.c:klp_shadow_get
```
```
In kernel/cgroup/cgroup.c (ffffffff828ce4db)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/cgroup/cgroup.c:find_css_set
  - kernel/cgroup/cgroup.c:find_css_set
```
```
In kernel/kprobes.c (ffffffff81177abd)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - kernel/kprobes.c:pre_handler_kretprobe
  - kernel/kprobes.c:__get_valid_kprobe
  - kernel/kprobes.c:kprobe_flush_task
  - kernel/kprobes.c:kretprobe_hash_unlock
  - kernel/kprobes.c:kretprobe_hash_lock
  - kernel/kprobes.c:get_optimized_kprobe
```
```
In kernel/trace/ftrace.c (ffffffff81193028)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_module_enable
  - kernel/trace/ftrace.c:__add_hash_entry
  - kernel/trace/ftrace.c:ftrace_lookup_ip
  - kernel/trace/ftrace.c:profile_graph_return
```
```
In kernel/events/core.c (ffffffff81207978)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - kernel/events/core.c:perf_swevent_add
  - kernel/events/core.c:___perf_sw_event
```
```
In mm/filemap.c (ffffffff8121a01e)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:__lock_page_killable
  - mm/filemap.c:__lock_page
  - mm/filemap.c:add_page_wait_queue
  - mm/filemap.c:put_and_wait_on_page_locked
  - mm/filemap.c:wake_up_page_bit
```
```
In mm/ksm.c (ffffffff8129882a)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - mm/ksm.c:__ksm_exit
  - mm/ksm.c:__ksm_enter
```
```
In mm/khugepaged.c (ffffffff812b2f9d)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:__khugepaged_exit
  - mm/khugepaged.c:__khugepaged_enter
```
```
In fs/dax.c (ffffffff8133de2d)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - fs/dax.c:wait_entry_unlocked
  - fs/dax.c:get_unlocked_entry
  - fs/dax.c:dax_wake_entry
```
```
In fs/crypto/keysetup_v1.c (ffffffff8134435f)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:find_or_insert_direct_key
```
```
In fs/locks.c (ffffffff8134ba1c)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:__locks_insert_block
```
```
In fs/kernfs/dir.c (ffffffff81379139)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_name_hash
```
```
In fs/jbd2/revoke.c (ffffffff813ebb44)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:find_revoke_record
  - fs/jbd2/revoke.c:insert_revoke_hash
```
```
In fs/fat/namei_vfat.c (ffffffff814048f9)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - fs/fat/namei_vfat.c:vfat_hashi
```
```
In fs/ecryptfs/messaging.c (ffffffff81411591)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - fs/ecryptfs/messaging.c:ecryptfs_spawn_daemon
  - fs/ecryptfs/messaging.c:ecryptfs_find_daemon_by_euid
```
```
In fs/fuse/dev.c (ffffffff81416bb8)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_do_write
```
```
In fs/efivarfs/super.c (ffffffff8142a7b8)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - fs/efivarfs/super.c:efivarfs_d_hash
```
```
In security/tomoyo/memory.c (ffffffff8148469d)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - security/tomoyo/memory.c:tomoyo_get_name
```
```
In security/integrity/ima/ima_queue.c (ffffffff814aa035)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - security/integrity/ima/ima_queue.c:ima_add_template_entry
  - security/integrity/ima/ima_queue.c:ima_add_digest_entry
```
```
In block/elevator.c (ffffffff814d5eb5)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - block/elevator.c:elv_rqhash_find
```
```
In net/core/bpf_sk_storage.c (ffffffff81979cd5)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:selem_link_map
  - net/core/bpf_sk_storage.c:selem_unlink_map
```
```
In net/ipv4/udp.c (ffffffff819f26f3)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
```
```
In lib/vsprintf.c (ffffffff81ac6101)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - lib/vsprintf.c:ptr_to_id
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
In arch/x86/mm/kmmio.c (ffffffff8108c10e)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:kmmio_page_list
```
```
In kernel/workqueue.c (ffffffff810c1b96)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - kernel/workqueue.c:work_busy
  - kernel/workqueue.c:__flush_work
  - kernel/workqueue.c:process_one_work
  - kernel/workqueue.c:__queue_work
```
```
In kernel/ucount.c (ffffffff810d1ae5)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - kernel/ucount.c:inc_ucount
```
```
In kernel/sched/wait_bit.c (ffffffff810f7115)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - kernel/sched/wait_bit.c:wake_up_var
  - kernel/sched/wait_bit.c:wake_up_bit
  - kernel/sched/wait_bit.c:out_of_line_wait_on_bit_lock
  - kernel/sched/wait_bit.c:out_of_line_wait_on_bit_timeout
  - kernel/sched/wait_bit.c:out_of_line_wait_on_bit
```
```
In kernel/locking/qspinlock.c (ffffffff81106639)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - kernel/locking/qspinlock.c:__pv_queued_spin_unlock_slowpath
```
```
In kernel/livepatch/shadow.c (ffffffff811302e6)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - kernel/livepatch/shadow.c:klp_shadow_free
  - kernel/livepatch/shadow.c:__klp_shadow_get_or_alloc
  - kernel/livepatch/shadow.c:klp_shadow_get
```
```
In kernel/cgroup/cgroup.c (ffffffff828d38d5)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/cgroup/cgroup.c:find_css_set
  - kernel/cgroup/cgroup.c:find_css_set
```
```
In kernel/kprobes.c (ffffffff8118537d)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - kernel/kprobes.c:pre_handler_kretprobe
  - kernel/kprobes.c:__get_valid_kprobe
  - kernel/kprobes.c:kprobe_flush_task
  - kernel/kprobes.c:kretprobe_hash_unlock
  - kernel/kprobes.c:kretprobe_hash_lock
  - kernel/kprobes.c:get_optimized_kprobe
```
```
In kernel/trace/ftrace.c (ffffffff811a0bb8)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_module_enable
  - kernel/trace/ftrace.c:__add_hash_entry
  - kernel/trace/ftrace.c:ftrace_lookup_ip
  - kernel/trace/ftrace.c:profile_graph_return
```
```
In kernel/events/core.c (ffffffff812166d8)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - kernel/events/core.c:perf_swevent_add
  - kernel/events/core.c:___perf_sw_event
```
```
In mm/filemap.c (ffffffff8122910e)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:do_read_cache_page
  - mm/filemap.c:filemap_fault
  - mm/filemap.c:generic_file_buffered_read
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:__lock_page_or_retry
  - mm/filemap.c:__lock_page_killable
  - mm/filemap.c:__lock_page
  - mm/filemap.c:add_page_wait_queue
  - mm/filemap.c:put_and_wait_on_page_locked
  - mm/filemap.c:wake_up_page_bit
```
```
In mm/ksm.c (ffffffff812a85ac)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - mm/ksm.c:__ksm_exit
  - mm/ksm.c:__ksm_enter
```
```
In mm/khugepaged.c (ffffffff812c33e1)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:__khugepaged_exit
  - mm/khugepaged.c:__khugepaged_enter
```
```
In fs/dax.c (ffffffff8134ffdd)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - fs/dax.c:wait_entry_unlocked
  - fs/dax.c:get_unlocked_entry
  - fs/dax.c:dax_wake_entry
```
```
In fs/crypto/keysetup_v1.c (ffffffff8135763f)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - fs/crypto/keysetup_v1.c:find_or_insert_direct_key
```
```
In fs/locks.c (ffffffff8135d845)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - fs/locks.c:posix_lock_inode
  - fs/locks.c:__locks_insert_block
```
```
In fs/kernfs/dir.c (ffffffff8138cbe9)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - fs/kernfs/dir.c:kernfs_name_hash
```
```
In fs/jbd2/revoke.c (ffffffff814012b6)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - fs/jbd2/revoke.c:find_revoke_record
  - fs/jbd2/revoke.c:insert_revoke_hash
```
```
In fs/fat/namei_vfat.c (ffffffff8141a4f9)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - fs/fat/namei_vfat.c:vfat_hashi
```
```
In fs/ecryptfs/messaging.c (ffffffff81427201)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - fs/ecryptfs/messaging.c:ecryptfs_spawn_daemon
  - fs/ecryptfs/messaging.c:ecryptfs_find_daemon_by_euid
```
```
In fs/fuse/dev.c (ffffffff8142d91d)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - fs/fuse/dev.c:fuse_dev_do_write
```
```
In fs/efivarfs/super.c (ffffffff81441678)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - fs/efivarfs/super.c:efivarfs_d_hash
```
```
In security/tomoyo/memory.c (ffffffff8149c1dd)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - security/tomoyo/memory.c:tomoyo_get_name
```
```
In security/integrity/ima/ima_queue.c (ffffffff814c2a8b)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - security/integrity/ima/ima_queue.c:ima_add_template_entry
  - security/integrity/ima/ima_queue.c:ima_add_digest_entry
```
```
In block/elevator.c (ffffffff814eeab5)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - block/elevator.c:elv_rqhash_find
```
```
In net/core/bpf_sk_storage.c (ffffffff8199c205)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - net/core/bpf_sk_storage.c:selem_link_map
  - net/core/bpf_sk_storage.c:selem_unlink_map
```
```
In net/ipv4/udp.c (ffffffff819fc53f)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_enqueue_schedule_skb
```
```
In lib/vsprintf.c (ffffffff81ad25e1)
Location: include/linux/hash.h:77
Inline: True
Inline callers:
  - lib/vsprintf.c:ptr_to_id
```
</details>
</li>
</ul>

## Differences
