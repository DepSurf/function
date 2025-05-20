# Function: <code>ktime_get_ns</code>

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
In kernel/fork.c (ffffffff8107eb2f)
Location: include/linux/timekeeping.h:209
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/acct.c (ffffffff8110b9d7)
Location: include/linux/timekeeping.h:209
Inline: True
Inline callers:
  - kernel/acct.c:do_acct_process
```
```
In kernel/delayacct.c (ffffffff8113de09)
Location: include/linux/timekeeping.h:209
Inline: True
Inline callers:
  - kernel/delayacct.c:delayacct_end
  - kernel/delayacct.c:__delayacct_blkio_start
  - kernel/delayacct.c:__delayacct_freepages_start
```
```
In kernel/tsacct.c (ffffffff8113f07e)
Location: include/linux/timekeeping.h:209
Inline: True
Inline callers:
  - kernel/tsacct.c:bacct_add_tsk
```
```
In drivers/connector/cn_proc.c (ffffffff81542067)
Location: include/linux/timekeeping.h:209
Inline: True
Inline callers:
  - drivers/connector/cn_proc.c:proc_fork_connector
  - drivers/connector/cn_proc.c:proc_exec_connector
  - drivers/connector/cn_proc.c:proc_id_connector
  - drivers/connector/cn_proc.c:proc_sid_connector
  - drivers/connector/cn_proc.c:proc_ptrace_connector
  - drivers/connector/cn_proc.c:proc_comm_connector
  - drivers/connector/cn_proc.c:proc_coredump_connector
  - drivers/connector/cn_proc.c:proc_exit_connector
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
In kernel/fork.c (ffffffff81080804)
Location: include/linux/timekeeping.h:225
Inline: True
```
```
In kernel/acct.c (ffffffff81113237)
Location: include/linux/timekeeping.h:225
Inline: True
Inline callers:
  - kernel/acct.c:do_acct_process
```
```
In kernel/delayacct.c (ffffffff811467aa)
Location: include/linux/timekeeping.h:225
Inline: True
Inline callers:
  - kernel/delayacct.c:__delayacct_freepages_start
  - kernel/delayacct.c:__delayacct_blkio_start
  - kernel/delayacct.c:delayacct_end
```
```
In kernel/tsacct.c (ffffffff8114767e)
Location: include/linux/timekeeping.h:225
Inline: True
Inline callers:
  - kernel/tsacct.c:bacct_add_tsk
```
```
In crypto/jitterentropy-kcapi.c (ffffffff813efac8)
Location: include/linux/timekeeping.h:225
Inline: True
Inline callers:
  - crypto/jitterentropy-kcapi.c:jent_get_nstime
```
```
In block/cfq-iosched.c (ffffffff814259cd)
Location: include/linux/timekeeping.h:225
Inline: True
Inline callers:
  - block/cfq-iosched.c:cfq_init_queue
  - block/cfq-iosched.c:cfq_init_queue
  - block/cfq-iosched.c:cfq_idle_slice_timer
  - block/cfq-iosched.c:cfq_completed_request
  - block/cfq-iosched.c:cfq_completed_request
  - block/cfq-iosched.c:cfq_completed_request
  - block/cfq-iosched.c:cfq_completed_request
  - block/cfq-iosched.c:cfq_insert_request
  - block/cfq-iosched.c:cfq_insert_request
  - block/cfq-iosched.c:__cfq_update_io_thinktime
  - block/cfq-iosched.c:cfq_init_icq
  - block/cfq-iosched.c:cfq_dispatch_requests
  - block/cfq-iosched.c:cfq_dispatch_requests
  - block/cfq-iosched.c:cfq_dispatch_requests
  - block/cfq-iosched.c:cfq_dispatch_requests
  - block/cfq-iosched.c:cfq_dispatch_requests
  - block/cfq-iosched.c:cfq_dispatch_requests
  - block/cfq-iosched.c:cfq_dispatch_requests
  - block/cfq-iosched.c:cfq_check_fifo
  - block/cfq-iosched.c:cfq_arm_slice_timer
  - block/cfq-iosched.c:__cfq_slice_expired
  - block/cfq-iosched.c:__cfq_set_active_queue
  - block/cfq-iosched.c:cfq_service_tree_add
  - block/cfq-iosched.c:cfq_pd_alloc
  - block/cfq-iosched.c:cfq_pd_alloc
  - block/cfq-iosched.c:cfq_group_served
  - block/cfq-iosched.c:cfq_group_served
  - block/cfq-iosched.c:cfq_set_prio_slice
```
```
In drivers/connector/cn_proc.c (ffffffff81594156)
Location: include/linux/timekeeping.h:225
Inline: True
Inline callers:
  - drivers/connector/cn_proc.c:proc_exit_connector
  - drivers/connector/cn_proc.c:proc_coredump_connector
  - drivers/connector/cn_proc.c:proc_comm_connector
  - drivers/connector/cn_proc.c:proc_ptrace_connector
  - drivers/connector/cn_proc.c:proc_sid_connector
  - drivers/connector/cn_proc.c:proc_id_connector
  - drivers/connector/cn_proc.c:proc_exec_connector
  - drivers/connector/cn_proc.c:proc_fork_connector
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
In kernel/fork.c (ffffffff810850d4)
Location: include/linux/timekeeping.h:225
Inline: True
```
```
In kernel/acct.c (ffffffff8111a947)
Location: include/linux/timekeeping.h:225
Inline: True
Inline callers:
  - kernel/acct.c:do_acct_process
```
```
In kernel/delayacct.c (ffffffff811505ea)
Location: include/linux/timekeeping.h:225
Inline: True
Inline callers:
  - kernel/delayacct.c:__delayacct_freepages_start
  - kernel/delayacct.c:__delayacct_blkio_start
  - kernel/delayacct.c:delayacct_end
```
```
In kernel/tsacct.c (ffffffff8115151e)
Location: include/linux/timekeeping.h:225
Inline: True
Inline callers:
  - kernel/tsacct.c:bacct_add_tsk
```
```
In crypto/jitterentropy-kcapi.c (ffffffff81409348)
Location: include/linux/timekeeping.h:225
Inline: True
Inline callers:
  - crypto/jitterentropy-kcapi.c:jent_get_nstime
```
```
In block/cfq-iosched.c (ffffffff8144478d)
Location: include/linux/timekeeping.h:225
Inline: True
Inline callers:
  - block/cfq-iosched.c:cfq_init_queue
  - block/cfq-iosched.c:cfq_init_queue
  - block/cfq-iosched.c:cfq_idle_slice_timer
  - block/cfq-iosched.c:cfq_completed_request
  - block/cfq-iosched.c:cfq_completed_request
  - block/cfq-iosched.c:cfq_completed_request
  - block/cfq-iosched.c:cfq_completed_request
  - block/cfq-iosched.c:cfq_insert_request
  - block/cfq-iosched.c:cfq_insert_request
  - block/cfq-iosched.c:__cfq_update_io_thinktime
  - block/cfq-iosched.c:cfq_init_icq
  - block/cfq-iosched.c:cfq_dispatch_requests
  - block/cfq-iosched.c:cfq_dispatch_requests
  - block/cfq-iosched.c:cfq_dispatch_requests
  - block/cfq-iosched.c:cfq_dispatch_requests
  - block/cfq-iosched.c:cfq_dispatch_requests
  - block/cfq-iosched.c:cfq_dispatch_request
  - block/cfq-iosched.c:cfq_dispatch_request
  - block/cfq-iosched.c:cfq_dispatch_request
  - block/cfq-iosched.c:cfq_arm_slice_timer
  - block/cfq-iosched.c:__cfq_slice_expired
  - block/cfq-iosched.c:__cfq_set_active_queue
  - block/cfq-iosched.c:cfq_service_tree_add
  - block/cfq-iosched.c:cfq_pd_alloc
  - block/cfq-iosched.c:cfq_pd_alloc
  - block/cfq-iosched.c:cfq_group_served
  - block/cfq-iosched.c:cfq_group_served
  - block/cfq-iosched.c:cfq_set_prio_slice
```
```
In drivers/connector/cn_proc.c (ffffffff815c1a16)
Location: include/linux/timekeeping.h:225
Inline: True
Inline callers:
  - drivers/connector/cn_proc.c:proc_exit_connector
  - drivers/connector/cn_proc.c:proc_coredump_connector
  - drivers/connector/cn_proc.c:proc_comm_connector
  - drivers/connector/cn_proc.c:proc_ptrace_connector
  - drivers/connector/cn_proc.c:proc_sid_connector
  - drivers/connector/cn_proc.c:proc_id_connector
  - drivers/connector/cn_proc.c:proc_exec_connector
  - drivers/connector/cn_proc.c:proc_fork_connector
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
In kernel/fork.c (ffffffff81082001)
Location: include/linux/timekeeping.h:214
Inline: True
```
```
In kernel/sched/clock.c (ffffffff810b4e41)
Location: include/linux/timekeeping.h:214
Inline: True
Inline callers:
  - kernel/sched/clock.c:sched_clock_tick_stable
  - kernel/sched/clock.c:__sched_clock_work
```
```
In kernel/acct.c (ffffffff8111c4dd)
Location: include/linux/timekeeping.h:214
Inline: True
Inline callers:
  - kernel/acct.c:do_acct_process
```
```
In kernel/delayacct.c (ffffffff81152bda)
Location: include/linux/timekeeping.h:214
Inline: True
Inline callers:
  - kernel/delayacct.c:__delayacct_freepages_start
  - kernel/delayacct.c:__delayacct_blkio_start
  - kernel/delayacct.c:delayacct_end
```
```
In kernel/taskstats.c (ffffffff81153405)
Location: include/linux/timekeeping.h:214
Inline: True
```
```
In kernel/tsacct.c (ffffffff81153b9e)
Location: include/linux/timekeeping.h:214
Inline: True
Inline callers:
  - kernel/tsacct.c:bacct_add_tsk
```
```
In crypto/jitterentropy-kcapi.c (ffffffff81416a30)
Location: include/linux/timekeeping.h:214
Inline: True
Inline callers:
  - crypto/jitterentropy-kcapi.c:jent_get_nstime
```
```
In block/blk-throttle.c (ffffffff8144bae8)
Location: include/linux/timekeeping.h:214
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:throtl_tg_is_idle
```
```
In block/cfq-iosched.c (ffffffff81453c7d)
Location: include/linux/timekeeping.h:214
Inline: True
Inline callers:
  - block/cfq-iosched.c:cfq_init_queue
  - block/cfq-iosched.c:cfq_init_queue
  - block/cfq-iosched.c:cfq_idle_slice_timer
  - block/cfq-iosched.c:cfq_completed_request
  - block/cfq-iosched.c:cfq_completed_request
  - block/cfq-iosched.c:cfq_completed_request
  - block/cfq-iosched.c:cfq_completed_request
  - block/cfq-iosched.c:cfq_insert_request
  - block/cfq-iosched.c:cfq_insert_request
  - block/cfq-iosched.c:__cfq_update_io_thinktime
  - block/cfq-iosched.c:cfq_init_icq
  - block/cfq-iosched.c:cfq_dispatch_requests
  - block/cfq-iosched.c:cfq_dispatch_requests
  - block/cfq-iosched.c:cfq_dispatch_requests
  - block/cfq-iosched.c:cfq_dispatch_requests
  - block/cfq-iosched.c:cfq_dispatch_requests
  - block/cfq-iosched.c:cfq_dispatch_request
  - block/cfq-iosched.c:cfq_dispatch_request
  - block/cfq-iosched.c:cfq_dispatch_request
  - block/cfq-iosched.c:cfq_arm_slice_timer
  - block/cfq-iosched.c:__cfq_slice_expired
  - block/cfq-iosched.c:__cfq_set_active_queue
  - block/cfq-iosched.c:cfq_service_tree_add
  - block/cfq-iosched.c:cfq_pd_alloc
  - block/cfq-iosched.c:cfq_pd_alloc
  - block/cfq-iosched.c:cfq_group_served
  - block/cfq-iosched.c:cfq_group_served
  - block/cfq-iosched.c:cfq_set_prio_slice
```
```
In drivers/connector/cn_proc.c (ffffffff815d74f6)
Location: include/linux/timekeeping.h:214
Inline: True
Inline callers:
  - drivers/connector/cn_proc.c:proc_exit_connector
  - drivers/connector/cn_proc.c:proc_coredump_connector
  - drivers/connector/cn_proc.c:proc_comm_connector
  - drivers/connector/cn_proc.c:proc_ptrace_connector
  - drivers/connector/cn_proc.c:proc_sid_connector
  - drivers/connector/cn_proc.c:proc_id_connector
  - drivers/connector/cn_proc.c:proc_exec_connector
  - drivers/connector/cn_proc.c:proc_fork_connector
```
```
In net/bpf/test_run.c (ffffffff8180c6a8)
Location: include/linux/timekeeping.h:214
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_test_run
  - net/bpf/test_run.c:bpf_test_run
  - net/bpf/test_run.c:bpf_test_run
  - net/bpf/test_run.c:bpf_test_run
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
In kernel/fork.c (ffffffff81088871)
Location: include/linux/timekeeping.h:94
Inline: True
```
```
In kernel/sched/clock.c (ffffffff810bc131)
Location: include/linux/timekeeping.h:94
Inline: True
Inline callers:
  - kernel/sched/clock.c:sched_clock_tick_stable
  - kernel/sched/clock.c:__sched_clock_work
```
```
In kernel/acct.c (ffffffff81127bfd)
Location: include/linux/timekeeping.h:94
Inline: True
Inline callers:
  - kernel/acct.c:do_acct_process
```
```
In kernel/delayacct.c (ffffffff8115f3fa)
Location: include/linux/timekeeping.h:94
Inline: True
Inline callers:
  - kernel/delayacct.c:__delayacct_freepages_start
  - kernel/delayacct.c:__delayacct_blkio_start
  - kernel/delayacct.c:delayacct_end
```
```
In kernel/taskstats.c (ffffffff8115fc05)
Location: include/linux/timekeeping.h:94
Inline: True
```
```
In kernel/tsacct.c (ffffffff8116039e)
Location: include/linux/timekeeping.h:94
Inline: True
Inline callers:
  - kernel/tsacct.c:bacct_add_tsk
```
```
In crypto/jitterentropy-kcapi.c (ffffffff8144120c)
Location: include/linux/timekeeping.h:94
Inline: True
Inline callers:
  - crypto/jitterentropy-kcapi.c:jent_get_nstime
```
```
In block/blk-throttle.c (ffffffff81477fda)
Location: include/linux/timekeeping.h:94
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:throtl_tg_is_idle
```
```
In block/cfq-iosched.c (ffffffff8147d1dd)
Location: include/linux/timekeeping.h:94
Inline: True
Inline callers:
  - block/cfq-iosched.c:cfq_init_queue
  - block/cfq-iosched.c:cfq_init_queue
  - block/cfq-iosched.c:cfq_idle_slice_timer
  - block/cfq-iosched.c:cfq_completed_request
  - block/cfq-iosched.c:cfq_completed_request
  - block/cfq-iosched.c:cfq_completed_request
  - block/cfq-iosched.c:cfq_completed_request
  - block/cfq-iosched.c:cfq_completed_request
  - block/cfq-iosched.c:cfq_completed_request
  - block/cfq-iosched.c:cfq_insert_request
  - block/cfq-iosched.c:cfq_insert_request
  - block/cfq-iosched.c:__cfq_update_io_thinktime
  - block/cfq-iosched.c:cfq_init_icq
  - block/cfq-iosched.c:cfq_dispatch_requests
  - block/cfq-iosched.c:cfq_dispatch_requests
  - block/cfq-iosched.c:cfq_dispatch_requests
  - block/cfq-iosched.c:cfq_dispatch_requests
  - block/cfq-iosched.c:cfq_dispatch_requests
  - block/cfq-iosched.c:cfq_dispatch_requests
  - block/cfq-iosched.c:cfq_dispatch_requests
  - block/cfq-iosched.c:cfq_dispatch_requests
  - block/cfq-iosched.c:__cfq_slice_expired
  - block/cfq-iosched.c:__cfq_slice_expired
  - block/cfq-iosched.c:__cfq_slice_expired
  - block/cfq-iosched.c:__cfq_set_active_queue
  - block/cfq-iosched.c:cfq_service_tree_add
  - block/cfq-iosched.c:cfq_pd_alloc
  - block/cfq-iosched.c:cfq_pd_alloc
```
```
In drivers/connector/cn_proc.c (ffffffff8163e2e6)
Location: include/linux/timekeeping.h:94
Inline: True
Inline callers:
  - drivers/connector/cn_proc.c:proc_exit_connector
  - drivers/connector/cn_proc.c:proc_coredump_connector
  - drivers/connector/cn_proc.c:proc_comm_connector
  - drivers/connector/cn_proc.c:proc_ptrace_connector
  - drivers/connector/cn_proc.c:proc_sid_connector
  - drivers/connector/cn_proc.c:proc_id_connector
  - drivers/connector/cn_proc.c:proc_exec_connector
  - drivers/connector/cn_proc.c:proc_fork_connector
```
```
In net/bpf/test_run.c (ffffffff8188b688)
Location: include/linux/timekeeping.h:94
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_test_run
  - net/bpf/test_run.c:bpf_test_run
  - net/bpf/test_run.c:bpf_test_run
  - net/bpf/test_run.c:bpf_test_run
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
In kernel/fork.c (ffffffff8108c5da)
Location: include/linux/timekeeping.h:109
Inline: True
```
```
In kernel/sched/clock.c (ffffffff810c37c1)
Location: include/linux/timekeeping.h:109
Inline: True
Inline callers:
  - kernel/sched/clock.c:sched_clock_tick_stable
  - kernel/sched/clock.c:__sched_clock_work
```
```
In kernel/acct.c (ffffffff811359f1)
Location: include/linux/timekeeping.h:109
Inline: True
Inline callers:
  - kernel/acct.c:do_acct_process
```
```
In kernel/delayacct.c (ffffffff8116e36a)
Location: include/linux/timekeeping.h:109
Inline: True
Inline callers:
  - kernel/delayacct.c:__delayacct_freepages_start
  - kernel/delayacct.c:__delayacct_blkio_start
  - kernel/delayacct.c:delayacct_end
```
```
In kernel/taskstats.c (ffffffff8116eb52)
Location: include/linux/timekeeping.h:109
Inline: True
```
```
In kernel/tsacct.c (ffffffff8116f2b5)
Location: include/linux/timekeeping.h:109
Inline: True
Inline callers:
  - kernel/tsacct.c:bacct_add_tsk
```
```
In crypto/jitterentropy-kcapi.c (ffffffff8147410e)
Location: include/linux/timekeeping.h:109
Inline: True
Inline callers:
  - crypto/jitterentropy-kcapi.c:jent_get_nstime
```
```
In block/blk-core.c (ffffffff81483fd6)
Location: include/linux/timekeeping.h:109
Inline: True
Inline callers:
  - block/blk-core.c:blk_finish_request
  - block/blk-core.c:blk_start_request
  - block/blk-core.c:blk_rq_init
```
```
In block/blk-mq.c (ffffffff8148dfcb)
Location: include/linux/timekeeping.h:109
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_start_request
  - block/blk-mq.c:blk_mq_get_request
```
```
In block/blk-throttle.c (ffffffff814ac650)
Location: include/linux/timekeeping.h:109
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:throtl_tg_is_idle
```
```
In block/cfq-iosched.c (ffffffff814b414d)
Location: include/linux/timekeeping.h:109
Inline: True
Inline callers:
  - block/cfq-iosched.c:cfq_init_queue
  - block/cfq-iosched.c:cfq_init_queue
  - block/cfq-iosched.c:cfq_idle_slice_timer
  - block/cfq-iosched.c:cfq_completed_request
  - block/cfq-iosched.c:cfq_completed_request
  - block/cfq-iosched.c:cfq_completed_request
  - block/cfq-iosched.c:cfq_completed_request
  - block/cfq-iosched.c:cfq_completed_request
  - block/cfq-iosched.c:cfq_completed_request
  - block/cfq-iosched.c:cfq_completed_request
  - block/cfq-iosched.c:cfq_insert_request
  - block/cfq-iosched.c:cfq_insert_request
  - block/cfq-iosched.c:__cfq_update_io_thinktime
  - block/cfq-iosched.c:cfq_init_icq
  - block/cfq-iosched.c:cfq_dispatch_requests
  - block/cfq-iosched.c:cfq_dispatch_requests
  - block/cfq-iosched.c:cfq_dispatch_requests
  - block/cfq-iosched.c:cfq_dispatch_requests
  - block/cfq-iosched.c:cfq_dispatch_requests
  - block/cfq-iosched.c:cfq_dispatch_requests
  - block/cfq-iosched.c:cfq_dispatch_requests
  - block/cfq-iosched.c:cfq_dispatch_requests
  - block/cfq-iosched.c:__cfq_slice_expired
  - block/cfq-iosched.c:__cfq_slice_expired
  - block/cfq-iosched.c:__cfq_slice_expired
  - block/cfq-iosched.c:__cfq_set_active_queue
  - block/cfq-iosched.c:cfq_service_tree_add
  - block/cfq-iosched.c:cfq_pd_alloc
  - block/cfq-iosched.c:cfq_pd_alloc
```
```
In drivers/connector/cn_proc.c (ffffffff816798c6)
Location: include/linux/timekeeping.h:109
Inline: True
Inline callers:
  - drivers/connector/cn_proc.c:proc_exit_connector
  - drivers/connector/cn_proc.c:proc_coredump_connector
  - drivers/connector/cn_proc.c:proc_comm_connector
  - drivers/connector/cn_proc.c:proc_ptrace_connector
  - drivers/connector/cn_proc.c:proc_sid_connector
  - drivers/connector/cn_proc.c:proc_id_connector
  - drivers/connector/cn_proc.c:proc_exec_connector
  - drivers/connector/cn_proc.c:proc_fork_connector
```
```
In drivers/md/dm-rq.c (ffffffff81815f38)
Location: include/linux/timekeeping.h:109
Inline: True
Inline callers:
  - drivers/md/dm-rq.c:map_request
```
```
In net/bpf/test_run.c (ffffffff818df0f2)
Location: include/linux/timekeeping.h:109
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_test_run
  - net/bpf/test_run.c:bpf_test_run
  - net/bpf/test_run.c:bpf_test_run
  - net/bpf/test_run.c:bpf_test_run
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
In kernel/fork.c (ffffffff81094a55)
Location: include/linux/timekeeping.h:124
Inline: True
```
```
In kernel/sched/clock.c (ffffffff810cc894)
Location: include/linux/timekeeping.h:124
Inline: True
Inline callers:
  - kernel/sched/clock.c:__sched_clock_gtod_offset
  - kernel/sched/clock.c:__sched_clock_work
```
```
In kernel/acct.c (ffffffff81141181)
Location: include/linux/timekeeping.h:124
Inline: True
Inline callers:
  - kernel/acct.c:do_acct_process
```
```
In kernel/delayacct.c (ffffffff8117be3a)
Location: include/linux/timekeeping.h:124
Inline: True
Inline callers:
  - kernel/delayacct.c:__delayacct_thrashing_start
  - kernel/delayacct.c:__delayacct_freepages_start
  - kernel/delayacct.c:__delayacct_blkio_start
  - kernel/delayacct.c:delayacct_end
```
```
In kernel/taskstats.c (ffffffff8117c652)
Location: include/linux/timekeeping.h:124
Inline: True
```
```
In kernel/tsacct.c (ffffffff8117cdb5)
Location: include/linux/timekeeping.h:124
Inline: True
Inline callers:
  - kernel/tsacct.c:bacct_add_tsk
```
```
In crypto/jitterentropy-kcapi.c (ffffffff81491c7e)
Location: include/linux/timekeeping.h:124
Inline: True
Inline callers:
  - crypto/jitterentropy-kcapi.c:jent_get_nstime
```
```
In block/bio.c (ffffffff81498297)
Location: include/linux/timekeeping.h:124
Inline: True
Inline callers:
  - block/bio.c:__bio_clone_fast
```
```
In block/blk-core.c (ffffffff8149d637)
Location: include/linux/timekeeping.h:124
Inline: True
Inline callers:
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:blk_rq_init
```
```
In block/blk-mq.c (ffffffff814a7855)
Location: include/linux/timekeeping.h:124
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_start_request
  - block/blk-mq.c:blk_mq_get_request
```
```
In block/bounce.c (ffffffff814be44a)
Location: include/linux/timekeeping.h:124
Inline: True
Inline callers:
  - block/bounce.c:blk_queue_bounce
```
```
In block/blk-throttle.c (ffffffff814c69fb)
Location: include/linux/timekeeping.h:124
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:throtl_tg_is_idle
```
```
In drivers/connector/cn_proc.c (ffffffff816989b6)
Location: include/linux/timekeeping.h:124
Inline: True
Inline callers:
  - drivers/connector/cn_proc.c:proc_exit_connector
  - drivers/connector/cn_proc.c:proc_coredump_connector
  - drivers/connector/cn_proc.c:proc_comm_connector
  - drivers/connector/cn_proc.c:proc_ptrace_connector
  - drivers/connector/cn_proc.c:proc_sid_connector
  - drivers/connector/cn_proc.c:proc_id_connector
  - drivers/connector/cn_proc.c:proc_exec_connector
  - drivers/connector/cn_proc.c:proc_fork_connector
```
```
In drivers/media/cec/cec-adap.c (ffffffff81805125)
Location: include/linux/timekeeping.h:124
Inline: True
Inline callers:
  - drivers/media/cec/cec-adap.c:cec_transmit_msg_fh
  - drivers/media/cec/cec-adap.c:cec_wait_timeout
  - drivers/media/cec/cec-adap.c:cec_data_cancel
  - drivers/media/cec/cec-adap.c:cec_data_cancel
  - drivers/media/cec/cec-adap.c:cec_post_state_event
  - drivers/media/cec/cec-adap.c:cec_queue_msg_fh
  - drivers/media/cec/cec-adap.c:cec_queue_event_fh
```
```
In drivers/md/dm-rq.c (ffffffff81841da5)
Location: include/linux/timekeeping.h:124
Inline: True
Inline callers:
  - drivers/md/dm-rq.c:dm_mq_queue_rq
```
```
In net/bpf/test_run.c (ffffffff8190bb12)
Location: include/linux/timekeeping.h:124
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_test_run
  - net/bpf/test_run.c:bpf_test_run
  - net/bpf/test_run.c:bpf_test_run
  - net/bpf/test_run.c:bpf_test_run
```
```
In net/ipv4/tcp.c (ffffffff8192489c)
Location: include/linux/timekeeping.h:124
Inline: True
```
```
In net/ipv4/tcp_input.c (ffffffff8192e724)
Location: include/linux/timekeeping.h:124
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_conn_request
  - net/ipv4/tcp_input.c:tcp_synack_rtt_meas
```
```
In net/ipv4/tcp_output.c (ffffffff8193a565)
Location: include/linux/timekeeping.h:124
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_window_probe
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_send_active_reset
  - net/ipv4/tcp_output.c:tcp_write_xmit
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81940637)
Location: include/linux/timekeeping.h:124
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack
```
```
In net/ipv4/syncookies.c (ffffffff81975685)
Location: include/linux/timekeeping.h:124
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_init_timestamp
```
```
In net/ipv6/tcp_ipv6.c (ffffffff819cb68e)
Location: include/linux/timekeeping.h:124
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack
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
In kernel/fork.c (ffffffff81099209)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/sched/clock.c (ffffffff810d4ca4)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - kernel/sched/clock.c:__sched_clock_gtod_offset
  - kernel/sched/clock.c:__sched_clock_work
```
```
In kernel/acct.c (ffffffff8114c5a6)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - kernel/acct.c:do_acct_process
```
```
In kernel/delayacct.c (ffffffff81188c5a)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - kernel/delayacct.c:__delayacct_thrashing_start
  - kernel/delayacct.c:__delayacct_freepages_start
  - kernel/delayacct.c:__delayacct_blkio_start
  - kernel/delayacct.c:delayacct_end
```
```
In kernel/taskstats.c (ffffffff811894f6)
Location: include/linux/timekeeping.h:152
Inline: True
```
```
In kernel/tsacct.c (ffffffff81189c75)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - kernel/tsacct.c:bacct_add_tsk
```
```
In kernel/bpf/verifier.c (ffffffff811e414d)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
```
```
In crypto/jitterentropy-kcapi.c (ffffffff814bf2de)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - crypto/jitterentropy-kcapi.c:jent_get_nstime
```
```
In block/bio.c (ffffffff814c6114)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - block/bio.c:__bio_clone_fast
```
```
In block/blk-core.c (ffffffff814cb87c)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:blk_rq_init
```
```
In block/blk-mq.c (ffffffff814d5898)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_start_request
  - block/blk-mq.c:blk_mq_get_request
```
```
In block/bounce.c (ffffffff814ecbd4)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - block/bounce.c:__blk_queue_bounce
```
```
In block/blk-throttle.c (ffffffff814f5243)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:throtl_tg_is_idle
```
```
In drivers/connector/cn_proc.c (ffffffff816d14e6)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - drivers/connector/cn_proc.c:proc_exit_connector
  - drivers/connector/cn_proc.c:proc_coredump_connector
  - drivers/connector/cn_proc.c:proc_comm_connector
  - drivers/connector/cn_proc.c:proc_ptrace_connector
  - drivers/connector/cn_proc.c:proc_sid_connector
  - drivers/connector/cn_proc.c:proc_id_connector
  - drivers/connector/cn_proc.c:proc_exec_connector
  - drivers/connector/cn_proc.c:proc_fork_connector
```
```
In drivers/media/cec/cec-adap.c (ffffffff81846cac)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - drivers/media/cec/cec-adap.c:cec_transmit_msg_fh
  - drivers/media/cec/cec-adap.c:cec_wait_timeout
  - drivers/media/cec/cec-adap.c:cec_data_cancel
  - drivers/media/cec/cec-adap.c:cec_data_cancel
  - drivers/media/cec/cec-adap.c:cec_post_state_event
  - drivers/media/cec/cec-adap.c:cec_queue_msg_fh
  - drivers/media/cec/cec-adap.c:cec_queue_event_fh
```
```
In drivers/md/dm-rq.c (ffffffff81884bf1)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - drivers/md/dm-rq.c:dm_mq_queue_rq
```
```
In net/bpf/test_run.c (ffffffff8196dce4)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_flow_dissector
  - net/bpf/test_run.c:bpf_prog_test_run_flow_dissector
  - net/bpf/test_run.c:bpf_prog_test_run_flow_dissector
  - net/bpf/test_run.c:bpf_prog_test_run_flow_dissector
  - net/bpf/test_run.c:bpf_test_run
  - net/bpf/test_run.c:bpf_test_run
  - net/bpf/test_run.c:bpf_test_run
  - net/bpf/test_run.c:bpf_test_run
```
```
In net/ipv4/tcp.c (ffffffff81987d66)
Location: include/linux/timekeeping.h:152
Inline: True
```
```
In net/ipv4/tcp_input.c (ffffffff81993bc0)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_synack_rtt_meas
```
```
In net/ipv4/tcp_output.c (ffffffff8199e8c0)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_window_probe
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_send_active_reset
  - net/ipv4/tcp_output.c:tcp_write_xmit
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819a4b81)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
```
```
In net/ipv4/syncookies.c (ffffffff819df1a5)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_init_timestamp
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a3a116)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
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
In kernel/fork.c (ffffffff8109f801)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/sched/clock.c (ffffffff810df264)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - kernel/sched/clock.c:__sched_clock_gtod_offset
  - kernel/sched/clock.c:__sched_clock_work
```
```
In kernel/acct.c (ffffffff81158276)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - kernel/acct.c:do_acct_process
```
```
In kernel/delayacct.c (ffffffff81194b9a)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - kernel/delayacct.c:__delayacct_thrashing_start
  - kernel/delayacct.c:__delayacct_freepages_start
  - kernel/delayacct.c:__delayacct_blkio_start
  - kernel/delayacct.c:delayacct_end
```
```
In kernel/taskstats.c (ffffffff81195436)
Location: include/linux/timekeeping.h:152
Inline: True
```
```
In kernel/tsacct.c (ffffffff81195b85)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - kernel/tsacct.c:bacct_add_tsk
```
```
In kernel/bpf/verifier.c (ffffffff811f099d)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
```
```
In crypto/jitterentropy-kcapi.c (ffffffff814d812e)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - crypto/jitterentropy-kcapi.c:jent_get_nstime
```
```
In block/bio.c (ffffffff814de517)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - block/bio.c:__bio_clone_fast
```
```
In block/blk-core.c (ffffffff814e4b3f)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:blk_rq_init
```
```
In block/blk-mq.c (ffffffff814eeb97)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_start_request
  - block/blk-mq.c:blk_mq_get_request
  - block/blk-mq.c:blk_mq_get_request
```
```
In block/bounce.c (ffffffff81506024)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - block/bounce.c:__blk_queue_bounce
```
```
In block/blk-throttle.c (ffffffff8150e914)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:throtl_tg_is_idle
```
```
In block/blk-iocost.c (ffffffff81510658)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_refresh_params
```
```
In drivers/connector/cn_proc.c (ffffffff816f5306)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - drivers/connector/cn_proc.c:proc_exit_connector
  - drivers/connector/cn_proc.c:proc_coredump_connector
  - drivers/connector/cn_proc.c:proc_comm_connector
  - drivers/connector/cn_proc.c:proc_ptrace_connector
  - drivers/connector/cn_proc.c:proc_sid_connector
  - drivers/connector/cn_proc.c:proc_id_connector
  - drivers/connector/cn_proc.c:proc_exec_connector
  - drivers/connector/cn_proc.c:proc_fork_connector
```
```
In drivers/media/cec/cec-adap.c (ffffffff818785fc)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - drivers/media/cec/cec-adap.c:cec_transmit_msg_fh
  - drivers/media/cec/cec-adap.c:cec_wait_timeout
  - drivers/media/cec/cec-adap.c:cec_data_cancel
  - drivers/media/cec/cec-adap.c:cec_data_cancel
  - drivers/media/cec/cec-adap.c:cec_post_state_event
  - drivers/media/cec/cec-adap.c:cec_queue_msg_fh
  - drivers/media/cec/cec-adap.c:cec_queue_event_fh
```
```
In drivers/md/dm-rq.c (ffffffff818b69bd)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - drivers/md/dm-rq.c:map_request
```
```
In net/bpf/test_run.c (ffffffff819a4693)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_flow_dissector
  - net/bpf/test_run.c:bpf_prog_test_run_flow_dissector
  - net/bpf/test_run.c:bpf_prog_test_run_flow_dissector
  - net/bpf/test_run.c:bpf_prog_test_run_flow_dissector
  - net/bpf/test_run.c:bpf_test_run
  - net/bpf/test_run.c:bpf_test_run
  - net/bpf/test_run.c:bpf_test_run
  - net/bpf/test_run.c:bpf_test_run
```
```
In net/ipv4/tcp.c (ffffffff819be2fe)
Location: include/linux/timekeeping.h:152
Inline: True
```
```
In net/ipv4/tcp_input.c (ffffffff819ca710)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_synack_rtt_meas
```
```
In net/ipv4/tcp_output.c (ffffffff819d53d0)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_window_probe
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_send_active_reset
  - net/ipv4/tcp_output.c:tcp_write_xmit
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819db881)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
```
```
In net/ipv4/syncookies.c (ffffffff81a16235)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_init_timestamp
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a70cb1)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
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
In kernel/fork.c (ffffffff810a6913)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/sched/clock.c (ffffffff810e7770)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - kernel/sched/clock.c:sched_clock_tick_stable
  - kernel/sched/clock.c:__sched_clock_work
```
```
In kernel/acct.c (ffffffff811691f3)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - kernel/acct.c:fill_ac
```
```
In kernel/delayacct.c (ffffffff811a9c5c)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - kernel/delayacct.c:__delayacct_thrashing_end
  - kernel/delayacct.c:__delayacct_thrashing_start
  - kernel/delayacct.c:__delayacct_freepages_end
  - kernel/delayacct.c:__delayacct_freepages_start
  - kernel/delayacct.c:__delayacct_blkio_end
  - kernel/delayacct.c:__delayacct_blkio_start
```
```
In kernel/taskstats.c (ffffffff811aa379)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - kernel/taskstats.c:fill_stats_for_tgid
```
```
In kernel/tsacct.c (ffffffff811aad45)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - kernel/tsacct.c:bacct_add_tsk
```
```
In kernel/bpf/verifier.c (ffffffff81212fc5)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
```
```
In crypto/jitterentropy-kcapi.c (ffffffff81537901)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - crypto/jitterentropy-kcapi.c:jent_get_nstime
```
```
In block/bio.c (ffffffff8153e036)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - block/bio.c:__bio_clone_fast
```
```
In block/blk-core.c (ffffffff8154277e)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - block/blk-core.c:blk_rq_init
  - block/blk-core.c:blkcg_bio_issue_check
```
```
In block/blk-flush.c (ffffffff81547fab)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - block/blk-flush.c:flush_end_io
  - block/blk-flush.c:flush_end_io
```
```
In block/blk-mq.c (ffffffff81552a7f)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_try_issue_list_directly
  - block/blk-mq.c:blk_mq_start_request
  - block/blk-mq.c:blk_mq_alloc_request_hctx
  - block/blk-mq.c:__blk_mq_alloc_request
  - block/blk-mq.c:blk_mq_rq_ctx_init
```
```
In block/bounce.c (ffffffff8156684b)
Location: include/linux/timekeeping.h:152
Inline: True
```
```
In block/blk-throttle.c (ffffffff8156ff9d)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:throtl_tg_is_idle
```
```
In block/blk-iocost.c (ffffffff81571afd)
Location: include/linux/timekeeping.h:152
Inline: True
```
```
In block/blk-crypto-fallback.c (ffffffff8158291d)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - block/blk-crypto-fallback.c:blk_crypto_clone_bio
```
```
In drivers/gpio/gpiolib.c (ffffffff8160d715)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:lineevent_irq_handler
  - drivers/gpio/gpiolib.c:lineevent_irq_thread
```
```
In drivers/connector/cn_proc.c (ffffffff817adbe4)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - drivers/connector/cn_proc.c:proc_exit_connector
  - drivers/connector/cn_proc.c:proc_coredump_connector
  - drivers/connector/cn_proc.c:proc_comm_connector
  - drivers/connector/cn_proc.c:proc_ptrace_connector
  - drivers/connector/cn_proc.c:proc_sid_connector
  - drivers/connector/cn_proc.c:proc_id_connector
  - drivers/connector/cn_proc.c:proc_exec_connector
  - drivers/connector/cn_proc.c:proc_fork_connector
```
```
In drivers/md/dm-rq.c (ffffffff8198727d)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - drivers/md/dm-rq.c:map_request
```
```
In net/bpf/test_run.c (ffffffff81a7f202)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_flow_dissector
  - net/bpf/test_run.c:bpf_prog_test_run_flow_dissector
  - net/bpf/test_run.c:bpf_prog_test_run_flow_dissector
  - net/bpf/test_run.c:bpf_prog_test_run_flow_dissector
  - net/bpf/test_run.c:bpf_test_run
  - net/bpf/test_run.c:bpf_test_run
  - net/bpf/test_run.c:bpf_test_run
  - net/bpf/test_run.c:bpf_test_run
```
```
In net/ipv4/tcp.c (ffffffff81aaa7c3)
Location: include/linux/timekeeping.h:152
Inline: True
```
```
In net/ipv4/tcp_input.c (ffffffff81ab76df)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_synack_rtt_meas
```
```
In net/ipv4/tcp_output.c (ffffffff81ac1d10)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_window_probe
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_send_active_reset
  - net/ipv4/tcp_output.c:tcp_write_xmit
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ac8955)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b6a4a5)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
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
In kernel/fork.c (ffffffff810a23e9)
Location: include/linux/timekeeping.h:151
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/sched/clock.c (ffffffff810e53b0)
Location: include/linux/timekeeping.h:151
Inline: True
Inline callers:
  - kernel/sched/clock.c:sched_clock_tick_stable
  - kernel/sched/clock.c:__sched_clock_work
```
```
In kernel/acct.c (ffffffff811658cd)
Location: include/linux/timekeeping.h:151
Inline: True
Inline callers:
  - kernel/acct.c:fill_ac
```
```
In kernel/delayacct.c (ffffffff811a727c)
Location: include/linux/timekeeping.h:151
Inline: True
Inline callers:
  - kernel/delayacct.c:__delayacct_thrashing_end
  - kernel/delayacct.c:__delayacct_thrashing_start
  - kernel/delayacct.c:__delayacct_freepages_end
  - kernel/delayacct.c:__delayacct_freepages_start
  - kernel/delayacct.c:__delayacct_blkio_end
  - kernel/delayacct.c:__delayacct_blkio_start
```
```
In kernel/taskstats.c (ffffffff811a7919)
Location: include/linux/timekeeping.h:151
Inline: True
Inline callers:
  - kernel/taskstats.c:fill_stats_for_tgid
```
```
In kernel/tsacct.c (ffffffff811a82f5)
Location: include/linux/timekeeping.h:151
Inline: True
Inline callers:
  - kernel/tsacct.c:bacct_add_tsk
```
```
In kernel/bpf/verifier.c (ffffffff812147a5)
Location: include/linux/timekeeping.h:151
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
```
```
In crypto/jitterentropy-kcapi.c (ffffffff815547c1)
Location: include/linux/timekeeping.h:151
Inline: True
Inline callers:
  - crypto/jitterentropy-kcapi.c:jent_get_nstime
```
```
In block/bio.c (ffffffff8155a01b)
Location: include/linux/timekeeping.h:151
Inline: True
Inline callers:
  - block/bio.c:__bio_clone_fast
```
```
In block/blk-core.c (ffffffff8156017b)
Location: include/linux/timekeeping.h:151
Inline: True
Inline callers:
  - block/blk-core.c:submit_bio_checks
  - block/blk-core.c:submit_bio_checks
  - block/blk-core.c:blk_rq_init
```
```
In block/blk-flush.c (ffffffff81563cd6)
Location: include/linux/timekeeping.h:151
Inline: True
Inline callers:
  - block/blk-flush.c:flush_end_io
  - block/blk-flush.c:flush_end_io
```
```
In block/blk-mq.c (ffffffff8156eb3d)
Location: include/linux/timekeeping.h:151
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_try_issue_list_directly
  - block/blk-mq.c:blk_mq_start_request
  - block/blk-mq.c:blk_mq_alloc_request_hctx
  - block/blk-mq.c:__blk_mq_alloc_request
  - block/blk-mq.c:blk_mq_rq_ctx_init
```
```
In block/bounce.c (ffffffff81581752)
Location: include/linux/timekeeping.h:151
Inline: True
```
```
In block/blk-throttle.c (ffffffff8158b12f)
Location: include/linux/timekeeping.h:151
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:throtl_tg_is_idle
```
```
In block/blk-iocost.c (ffffffff8158ccfd)
Location: include/linux/timekeeping.h:151
Inline: True
```
```
In block/blk-crypto-fallback.c (ffffffff8159f807)
Location: include/linux/timekeeping.h:151
Inline: True
Inline callers:
  - block/blk-crypto-fallback.c:blk_crypto_clone_bio
```
```
In drivers/gpio/gpiolib-cdev.c (ffffffff8163b80a)
Location: include/linux/timekeeping.h:151
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-cdev.c:debounce_work_func
  - drivers/gpio/gpiolib-cdev.c:edge_irq_handler
  - drivers/gpio/gpiolib-cdev.c:edge_irq_thread
```
```
In drivers/connector/cn_proc.c (ffffffff817c2784)
Location: include/linux/timekeeping.h:151
Inline: True
Inline callers:
  - drivers/connector/cn_proc.c:proc_exit_connector
  - drivers/connector/cn_proc.c:proc_coredump_connector
  - drivers/connector/cn_proc.c:proc_comm_connector
  - drivers/connector/cn_proc.c:proc_ptrace_connector
  - drivers/connector/cn_proc.c:proc_sid_connector
  - drivers/connector/cn_proc.c:proc_id_connector
  - drivers/connector/cn_proc.c:proc_exec_connector
  - drivers/connector/cn_proc.c:proc_fork_connector
```
```
In drivers/md/dm-rq.c (ffffffff8198b261)
Location: include/linux/timekeeping.h:151
Inline: True
Inline callers:
  - drivers/md/dm-rq.c:map_request
```
```
In net/bpf/test_run.c (ffffffff81a88c8d)
Location: include/linux/timekeeping.h:151
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_flow_dissector
  - net/bpf/test_run.c:bpf_prog_test_run_flow_dissector
  - net/bpf/test_run.c:bpf_prog_test_run_flow_dissector
  - net/bpf/test_run.c:bpf_prog_test_run_flow_dissector
  - net/bpf/test_run.c:bpf_test_run
  - net/bpf/test_run.c:bpf_test_run
  - net/bpf/test_run.c:bpf_test_run
  - net/bpf/test_run.c:bpf_test_run
```
```
In net/ipv4/tcp.c (ffffffff81ab77a5)
Location: include/linux/timekeeping.h:151
Inline: True
```
```
In net/ipv4/tcp_input.c (ffffffff81ac298f)
Location: include/linux/timekeeping.h:151
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_synack_rtt_meas
```
```
In net/ipv4/tcp_output.c (ffffffff81acd780)
Location: include/linux/timekeeping.h:151
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_window_probe
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_send_active_reset
  - net/ipv4/tcp_output.c:tcp_write_xmit
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ad48f5)
Location: include/linux/timekeeping.h:151
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b78fae)
Location: include/linux/timekeeping.h:151
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
```
```
In net/mptcp/protocol.c (ffffffff81bba647)
Location: include/linux/timekeeping.h:151
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_rcv_space_adjust
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
In kernel/fork.c (ffffffff810a30ad)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/sched/clock.c (ffffffff810e7360)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - kernel/sched/clock.c:sched_clock_tick_stable
  - kernel/sched/clock.c:__sched_clock_work
```
```
In kernel/acct.c (ffffffff811665fd)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - kernel/acct.c:fill_ac
```
```
In kernel/delayacct.c (ffffffff811a7dbc)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - kernel/delayacct.c:__delayacct_thrashing_end
  - kernel/delayacct.c:__delayacct_thrashing_start
  - kernel/delayacct.c:__delayacct_freepages_end
  - kernel/delayacct.c:__delayacct_freepages_start
  - kernel/delayacct.c:__delayacct_blkio_end
  - kernel/delayacct.c:__delayacct_blkio_start
```
```
In kernel/taskstats.c (ffffffff811a82f9)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - kernel/taskstats.c:fill_stats_for_tgid
```
```
In kernel/tsacct.c (ffffffff811a8e75)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - kernel/tsacct.c:bacct_add_tsk
```
```
In kernel/bpf/verifier.c (ffffffff8121701f)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
```
```
In crypto/jitterentropy-kcapi.c (ffffffff8155cf31)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - crypto/jitterentropy-kcapi.c:jent_get_nstime
```
```
In block/bio.c (ffffffff8156293c)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - block/bio.c:__bio_clone_fast
```
```
In block/blk-core.c (ffffffff81568309)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - block/blk-core.c:submit_bio_checks
  - block/blk-core.c:submit_bio_checks
  - block/blk-core.c:blk_rq_init
```
```
In block/blk-flush.c (ffffffff8156c4a2)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - block/blk-flush.c:flush_end_io
  - block/blk-flush.c:flush_end_io
```
```
In block/blk-mq.c (ffffffff8157671d)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_try_issue_list_directly
  - block/blk-mq.c:blk_mq_start_request
  - block/blk-mq.c:blk_mq_alloc_request_hctx
  - block/blk-mq.c:__blk_mq_alloc_request
  - block/blk-mq.c:blk_mq_rq_ctx_init
```
```
In block/blk-throttle.c (ffffffff81591dd5)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:throtl_tg_is_idle
```
```
In block/blk-iocost.c (ffffffff81593a4d)
Location: include/linux/timekeeping.h:152
Inline: True
```
```
In block/blk-crypto-fallback.c (ffffffff815a6525)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - block/blk-crypto-fallback.c:blk_crypto_clone_bio
```
```
In drivers/gpio/gpiolib-cdev.c (ffffffff8161f6ea)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-cdev.c:debounce_work_func
  - drivers/gpio/gpiolib-cdev.c:edge_irq_handler
  - drivers/gpio/gpiolib-cdev.c:edge_irq_thread
```
```
In drivers/connector/cn_proc.c (ffffffff817a5c44)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - drivers/connector/cn_proc.c:proc_exit_connector
  - drivers/connector/cn_proc.c:proc_coredump_connector
  - drivers/connector/cn_proc.c:proc_comm_connector
  - drivers/connector/cn_proc.c:proc_ptrace_connector
  - drivers/connector/cn_proc.c:proc_sid_connector
  - drivers/connector/cn_proc.c:proc_id_connector
  - drivers/connector/cn_proc.c:proc_exec_connector
  - drivers/connector/cn_proc.c:proc_fork_connector
```
```
In drivers/md/dm-rq.c (ffffffff8196f951)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - drivers/md/dm-rq.c:map_request
```
```
In net/bpf/test_run.c (ffffffff81a722a0)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_sk_lookup
  - net/bpf/test_run.c:bpf_prog_test_run_flow_dissector
  - net/bpf/test_run.c:bpf_test_run
  - net/bpf/test_run.c:bpf_test_timer_continue
  - net/bpf/test_run.c:bpf_test_timer_continue
  - net/bpf/test_run.c:bpf_test_timer_continue
```
```
In net/ipv4/tcp.c (ffffffff81aa29a3)
Location: include/linux/timekeeping.h:152
Inline: True
```
```
In net/ipv4/tcp_input.c (ffffffff81aadb1f)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_synack_rtt_meas
```
```
In net/ipv4/tcp_output.c (ffffffff81ab8940)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_window_probe
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_send_active_reset
  - net/ipv4/tcp_output.c:tcp_write_xmit
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81abf9ab)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81b67af8)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
```
```
In net/mptcp/protocol.c (ffffffff81ba98d7)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_rcv_space_adjust
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
In kernel/fork.c (ffffffff810b483e)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/sched/clock.c (ffffffff810fe97d)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - kernel/sched/clock.c:sched_clock_tick_stable
  - kernel/sched/clock.c:__sched_clock_work
```
```
In kernel/acct.c (ffffffff8118bdbd)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - kernel/acct.c:fill_ac
```
```
In kernel/taskstats.c (ffffffff811d1be9)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - kernel/taskstats.c:fill_stats_for_tgid
```
```
In kernel/tsacct.c (ffffffff811d29c5)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - kernel/tsacct.c:bacct_add_tsk
```
```
In kernel/bpf/verifier.c (ffffffff8124d7c0)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
```
```
In fs/io_uring.c (ffffffff813e573b)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - fs/io_uring.c:io_cqring_wait
```
```
In crypto/jitterentropy-kcapi.c (ffffffff815be261)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - crypto/jitterentropy-kcapi.c:jent_get_nstime
```
```
In block/bio.c (ffffffff815c6666)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - block/bio.c:__bio_clone_fast
```
```
In block/blk-core.c (ffffffff815cc921)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - block/blk-core.c:submit_bio_checks
  - block/blk-core.c:blk_rq_init
```
```
In block/blk-flush.c (ffffffff815d0942)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - block/blk-flush.c:flush_end_io
  - block/blk-flush.c:flush_end_io
```
```
In block/blk-mq.c (ffffffff815db36d)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_try_issue_list_directly
  - block/blk-mq.c:blk_mq_start_request
  - block/blk-mq.c:blk_mq_alloc_request_hctx
  - block/blk-mq.c:__blk_mq_alloc_request
  - block/blk-mq.c:blk_mq_rq_ctx_init
```
```
In block/blk-throttle.c (ffffffff815f8e7a)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:throtl_tg_is_idle
```
```
In block/blk-iocost.c (ffffffff815fae8c)
Location: include/linux/timekeeping.h:152
Inline: True
```
```
In block/blk-crypto-fallback.c (ffffffff8160f04e)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - block/blk-crypto-fallback.c:blk_crypto_clone_bio
```
```
In drivers/gpio/gpiolib-cdev.c (ffffffff8168ec7a)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-cdev.c:debounce_work_func
  - drivers/gpio/gpiolib-cdev.c:edge_irq_handler
  - drivers/gpio/gpiolib-cdev.c:edge_irq_thread
```
```
In drivers/connector/cn_proc.c (ffffffff818315c4)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - drivers/connector/cn_proc.c:proc_exit_connector
  - drivers/connector/cn_proc.c:proc_coredump_connector
  - drivers/connector/cn_proc.c:proc_comm_connector
  - drivers/connector/cn_proc.c:proc_ptrace_connector
  - drivers/connector/cn_proc.c:proc_sid_connector
  - drivers/connector/cn_proc.c:proc_id_connector
  - drivers/connector/cn_proc.c:proc_exec_connector
  - drivers/connector/cn_proc.c:proc_fork_connector
```
```
In drivers/md/dm-rq.c (ffffffff81a18291)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - drivers/md/dm-rq.c:map_request
```
```
In net/bpf/test_run.c (ffffffff81b2bbe0)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_sk_lookup
  - net/bpf/test_run.c:bpf_prog_test_run_flow_dissector
  - net/bpf/test_run.c:bpf_test_run
  - net/bpf/test_run.c:bpf_test_timer_continue
  - net/bpf/test_run.c:bpf_test_timer_continue
  - net/bpf/test_run.c:bpf_test_timer_continue
```
```
In net/ipv4/tcp.c (ffffffff81b5eb4e)
Location: include/linux/timekeeping.h:152
Inline: True
```
```
In net/ipv4/tcp_input.c (ffffffff81b6a60f)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_synack_rtt_meas
```
```
In net/ipv4/tcp_output.c (ffffffff81b75b60)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_window_probe
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_send_active_reset
  - net/ipv4/tcp_output.c:tcp_write_xmit
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81b7d518)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81c2f71f)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
```
```
In net/mptcp/protocol.c (ffffffff81c78327)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_rcv_space_adjust
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
In kernel/fork.c (ffffffff810cad30)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/sched/build_utility.c (ffffffff8114541c)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:sched_clock_tick_stable
  - kernel/sched/build_utility.c:__sched_clock_work
```
```
In kernel/acct.c (ffffffff811bb19a)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - kernel/acct.c:fill_ac
```
```
In kernel/taskstats.c (ffffffff812063fa)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - kernel/taskstats.c:fill_stats_for_tgid
```
```
In kernel/tsacct.c (ffffffff81207325)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - kernel/tsacct.c:bacct_add_tsk
```
```
In kernel/bpf/verifier.c (ffffffff8129472f)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
```
```
In crypto/jitterentropy-kcapi.c (ffffffff81667e3b)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - crypto/jitterentropy-kcapi.c:jent_get_nstime
```
```
In block/blk-core.c (ffffffff816794f2)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - block/blk-core.c:submit_bio_noacct
```
```
In block/blk-flush.c (ffffffff8167c163)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - block/blk-flush.c:flush_end_io
  - block/blk-flush.c:flush_end_io
```
```
In block/blk-merge.c (ffffffff816804b0)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - block/blk-merge.c:__blk_queue_split
```
```
In block/blk-mq.c (ffffffff816880a5)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - block/blk-mq.c:blk_insert_cloned_request
  - block/blk-mq.c:blk_mq_try_issue_list_directly
  - block/blk-mq.c:blk_mq_start_request
  - block/blk-mq.c:blk_mq_end_request_batch
  - block/blk-mq.c:blk_mq_alloc_request_hctx
  - block/blk-mq.c:__blk_mq_alloc_requests
  - block/blk-mq.c:blk_rq_init
```
```
In block/blk-throttle.c (ffffffff816aad5e)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - block/blk-throttle.c:__blk_throtl_bio
  - block/blk-throttle.c:throtl_tg_is_idle
```
```
In block/blk-iocost.c (ffffffff816ade96)
Location: include/linux/timekeeping.h:152
Inline: True
```
```
In io_uring/io_uring.c (ffffffff816cf7dc)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_cqring_wait
```
```
In drivers/gpio/gpiolib-cdev.c (ffffffff817aab4d)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-cdev.c:lineinfo_changed_notify
  - drivers/gpio/gpiolib-cdev.c:lineevent_irq_handler
  - drivers/gpio/gpiolib-cdev.c:lineevent_irq_thread
  - drivers/gpio/gpiolib-cdev.c:debounce_work_func
  - drivers/gpio/gpiolib-cdev.c:edge_irq_handler
  - drivers/gpio/gpiolib-cdev.c:edge_irq_thread
```
```
In drivers/connector/cn_proc.c (ffffffff81972b45)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - drivers/connector/cn_proc.c:proc_exit_connector
  - drivers/connector/cn_proc.c:proc_coredump_connector
  - drivers/connector/cn_proc.c:proc_comm_connector
  - drivers/connector/cn_proc.c:proc_ptrace_connector
  - drivers/connector/cn_proc.c:proc_sid_connector
  - drivers/connector/cn_proc.c:proc_id_connector
  - drivers/connector/cn_proc.c:proc_exec_connector
  - drivers/connector/cn_proc.c:proc_fork_connector
```
```
In net/bpf/test_run.c (ffffffff81cb6140)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_sk_lookup
  - net/bpf/test_run.c:bpf_prog_test_run_flow_dissector
  - net/bpf/test_run.c:bpf_test_run
  - net/bpf/test_run.c:bpf_test_run_xdp_live
  - net/bpf/test_run.c:bpf_test_timer_continue
  - net/bpf/test_run.c:bpf_test_timer_continue
  - net/bpf/test_run.c:bpf_test_timer_continue
```
```
In net/ipv4/tcp.c (ffffffff81ced76e)
Location: include/linux/timekeeping.h:152
Inline: True
```
```
In net/ipv4/tcp_input.c (ffffffff81cf9793)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_synack_rtt_meas
```
```
In net/ipv4/tcp_output.c (ffffffff81d0545c)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_window_probe
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_send_active_reset
  - net/ipv4/tcp_output.c:tcp_write_xmit
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81d0d462)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81dccb1a)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
```
```
In net/mptcp/protocol.c (ffffffff81e1d3e7)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_rcv_space_adjust
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
In kernel/fork.c (ffffffff810e82c5)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/sched/build_utility.c (ffffffff8117253c)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:sched_clock_tick_stable
  - kernel/sched/build_utility.c:sched_clock_init
  - kernel/sched/build_utility.c:__sched_clock_work
```
```
In kernel/acct.c (ffffffff811fcf8a)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - kernel/acct.c:fill_ac
```
```
In kernel/taskstats.c (ffffffff8124e6fa)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - kernel/taskstats.c:fill_stats_for_tgid
```
```
In kernel/tsacct.c (ffffffff8124f6b5)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - kernel/tsacct.c:bacct_add_tsk
```
```
In kernel/bpf/verifier.c (ffffffff812ef2df)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
```
```
In crypto/jitterentropy-kcapi.c (ffffffff817224db)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - crypto/jitterentropy-kcapi.c:jent_get_nstime
```
```
In block/blk-core.c (ffffffff81735643)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - block/blk-core.c:submit_bio_noacct_nocheck
```
```
In block/blk-flush.c (ffffffff817389e3)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - block/blk-flush.c:flush_end_io
  - block/blk-flush.c:flush_end_io
```
```
In block/blk-merge.c (ffffffff8173d8d2)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - block/blk-merge.c:__bio_split_to_limits
```
```
In block/blk-mq.c (ffffffff81746487)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - block/blk-mq.c:blk_insert_cloned_request
  - block/blk-mq.c:blk_mq_start_request
  - block/blk-mq.c:blk_mq_end_request_batch
  - block/blk-mq.c:__blk_mq_end_request
  - block/blk-mq.c:blk_mq_alloc_request_hctx
  - block/blk-mq.c:__blk_mq_alloc_requests
  - block/blk-mq.c:blk_rq_init
```
```
In block/blk-iocost.c (ffffffff8176c796)
Location: include/linux/timekeeping.h:152
Inline: True
```
```
In io_uring/io_uring.c (ffffffff81791c3b)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_cqring_wait
```
```
In io_uring/cancel.c (ffffffff8179e977)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - io_uring/cancel.c:io_sync_cancel
```
```
In drivers/gpio/gpiolib-cdev.c (ffffffff818c375d)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-cdev.c:lineinfo_changed_notify
  - drivers/gpio/gpiolib-cdev.c:lineevent_irq_handler
  - drivers/gpio/gpiolib-cdev.c:lineevent_irq_thread
  - drivers/gpio/gpiolib-cdev.c:line_event_timestamp
```
```
In drivers/connector/cn_proc.c (ffffffff81adde75)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - drivers/connector/cn_proc.c:proc_exit_connector
  - drivers/connector/cn_proc.c:proc_coredump_connector
  - drivers/connector/cn_proc.c:proc_comm_connector
  - drivers/connector/cn_proc.c:proc_ptrace_connector
  - drivers/connector/cn_proc.c:proc_sid_connector
  - drivers/connector/cn_proc.c:proc_id_connector
  - drivers/connector/cn_proc.c:proc_exec_connector
  - drivers/connector/cn_proc.c:proc_fork_connector
```
```
In net/bpf/test_run.c (ffffffff81e74615)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_sk_lookup
  - net/bpf/test_run.c:bpf_prog_test_run_flow_dissector
  - net/bpf/test_run.c:bpf_test_run
  - net/bpf/test_run.c:bpf_test_run_xdp_live
  - net/bpf/test_run.c:bpf_test_timer_continue
  - net/bpf/test_run.c:bpf_test_timer_continue
  - net/bpf/test_run.c:bpf_test_timer_continue
```
```
In net/ipv4/tcp.c (ffffffff81eb3f98)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - net/ipv4/tcp.c:do_tcp_getsockopt
  - net/ipv4/tcp.c:do_tcp_setsockopt
```
```
In net/ipv4/tcp_input.c (ffffffff81ebe283)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_synack_rtt_meas
```
```
In net/ipv4/tcp_output.c (ffffffff81eca54c)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_window_probe
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_send_active_reset
  - net/ipv4/tcp_output.c:tcp_write_xmit
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ed2ea8)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81f9dc2d)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
```
```
In net/mptcp/protocol.c (ffffffff81ff4997)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_rcv_space_adjust
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
In kernel/fork.c (ffffffff810f3f24)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/sched/build_utility.c (ffffffff8118359c)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:sched_clock_tick_stable
  - kernel/sched/build_utility.c:sched_clock_init
  - kernel/sched/build_utility.c:__sched_clock_work
```
```
In kernel/acct.c (ffffffff8121212a)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - kernel/acct.c:fill_ac
```
```
In kernel/taskstats.c (ffffffff81265aaa)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - kernel/taskstats.c:fill_stats_for_tgid
```
```
In kernel/tsacct.c (ffffffff81266a65)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - kernel/tsacct.c:bacct_add_tsk
```
```
In kernel/bpf/verifier.c (ffffffff8131bcd5)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
```
```
In crypto/jitterentropy-kcapi.c (ffffffff8175dd92)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - crypto/jitterentropy-kcapi.c:jent_get_nstime
```
```
In block/blk-core.c (ffffffff81771be3)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - block/blk-core.c:submit_bio_noacct_nocheck
```
```
In block/blk-flush.c (ffffffff8177501d)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - block/blk-flush.c:flush_end_io
  - block/blk-flush.c:flush_end_io
```
```
In block/blk-merge.c (ffffffff81779e4f)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - block/blk-merge.c:__bio_split_to_limits
```
```
In block/blk-mq.c (ffffffff81783827)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - block/blk-mq.c:blk_insert_cloned_request
  - block/blk-mq.c:blk_mq_submit_bio
  - block/blk-mq.c:blk_mq_start_request
  - block/blk-mq.c:blk_mq_end_request_batch
  - block/blk-mq.c:blk_mq_end_request
  - block/blk-mq.c:blk_mq_alloc_request_hctx
  - block/blk-mq.c:blk_mq_alloc_request_hctx
  - block/blk-mq.c:blk_mq_alloc_request
  - block/blk-mq.c:__blk_mq_alloc_requests
  - block/blk-mq.c:__blk_mq_alloc_requests
  - block/blk-mq.c:__blk_mq_alloc_requests
  - block/blk-mq.c:blk_rq_init
```
```
In block/blk-iocost.c (ffffffff817aac62)
Location: include/linux/timekeeping.h:152
Inline: True
```
```
In io_uring/io_uring.c (ffffffff817d0da4)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_cqring_wait
```
```
In io_uring/cancel.c (ffffffff817dfb67)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - io_uring/cancel.c:io_sync_cancel
```
```
In drivers/gpio/gpiolib-cdev.c (ffffffff8190682d)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-cdev.c:lineinfo_changed_notify
  - drivers/gpio/gpiolib-cdev.c:lineevent_irq_handler
  - drivers/gpio/gpiolib-cdev.c:lineevent_irq_thread
  - drivers/gpio/gpiolib-cdev.c:line_event_timestamp
```
```
In drivers/connector/cn_proc.c (ffffffff81b2c0e5)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - drivers/connector/cn_proc.c:proc_exit_connector
  - drivers/connector/cn_proc.c:proc_coredump_connector
  - drivers/connector/cn_proc.c:proc_comm_connector
  - drivers/connector/cn_proc.c:proc_ptrace_connector
  - drivers/connector/cn_proc.c:proc_sid_connector
  - drivers/connector/cn_proc.c:proc_id_connector
  - drivers/connector/cn_proc.c:proc_exec_connector
  - drivers/connector/cn_proc.c:proc_fork_connector
```
```
In net/bpf/test_run.c (ffffffff81ed03c5)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_sk_lookup
  - net/bpf/test_run.c:bpf_prog_test_run_flow_dissector
  - net/bpf/test_run.c:bpf_test_run
  - net/bpf/test_run.c:bpf_test_run_xdp_live
  - net/bpf/test_run.c:bpf_test_timer_continue
  - net/bpf/test_run.c:bpf_test_timer_continue
  - net/bpf/test_run.c:bpf_test_timer_continue
```
```
In net/ipv4/tcp.c (ffffffff81f1290e)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - net/ipv4/tcp.c:do_tcp_getsockopt
  - net/ipv4/tcp.c:do_tcp_setsockopt
```
```
In net/ipv4/tcp_input.c (ffffffff81f1c723)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_synack_rtt_meas
```
```
In net/ipv4/tcp_output.c (ffffffff81f2908c)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_window_probe
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_send_active_reset
  - net/ipv4/tcp_output.c:tcp_write_xmit
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81f31ba2)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81ffe763)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
```
```
In net/mptcp/protocol.c (ffffffff82071257)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_rcv_space_adjust
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
In kernel/fork.c (ffffffff810fd2e6)
Location: include/linux/timekeeping.h:153
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/sched/build_utility.c (ffffffff81191cdc)
Location: include/linux/timekeeping.h:153
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:sched_clock_tick_stable
  - kernel/sched/build_utility.c:sched_clock_init
  - kernel/sched/build_utility.c:__sched_clock_work
```
```
In kernel/acct.c (ffffffff812297bb)
Location: include/linux/timekeeping.h:153
Inline: True
Inline callers:
  - kernel/acct.c:fill_ac
```
```
In kernel/taskstats.c (ffffffff8127f939)
Location: include/linux/timekeeping.h:153
Inline: True
Inline callers:
  - kernel/taskstats.c:fill_stats_for_tgid
```
```
In kernel/tsacct.c (ffffffff812809a1)
Location: include/linux/timekeeping.h:153
Inline: True
Inline callers:
  - kernel/tsacct.c:bacct_add_tsk
```
```
In kernel/bpf/verifier.c (ffffffff8133e074)
Location: include/linux/timekeeping.h:153
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
```
```
In crypto/jitterentropy-kcapi.c (ffffffff8179fc6b)
Location: include/linux/timekeeping.h:153
Inline: True
Inline callers:
  - crypto/jitterentropy-kcapi.c:jent_get_nstime
```
```
In block/blk-core.c (ffffffff817b3f23)
Location: include/linux/timekeeping.h:153
Inline: True
Inline callers:
  - block/blk-core.c:submit_bio_noacct_nocheck
```
```
In block/blk-flush.c (ffffffff817b733f)
Location: include/linux/timekeeping.h:153
Inline: True
Inline callers:
  - block/blk-flush.c:flush_end_io
  - block/blk-flush.c:flush_end_io
```
```
In block/blk-merge.c (ffffffff817bc22f)
Location: include/linux/timekeeping.h:153
Inline: True
Inline callers:
  - block/blk-merge.c:__bio_split_to_limits
```
```
In block/blk-mq.c (ffffffff817c5b97)
Location: include/linux/timekeeping.h:153
Inline: True
Inline callers:
  - block/blk-mq.c:blk_insert_cloned_request
  - block/blk-mq.c:blk_mq_submit_bio
  - block/blk-mq.c:blk_mq_start_request
  - block/blk-mq.c:blk_mq_end_request_batch
  - block/blk-mq.c:blk_mq_end_request
  - block/blk-mq.c:blk_mq_alloc_request_hctx
  - block/blk-mq.c:blk_mq_alloc_request_hctx
  - block/blk-mq.c:blk_mq_alloc_request
  - block/blk-mq.c:__blk_mq_alloc_requests
  - block/blk-mq.c:__blk_mq_alloc_requests
  - block/blk-mq.c:blk_rq_init
```
```
In block/blk-iocost.c (ffffffff817eea12)
Location: include/linux/timekeeping.h:153
Inline: True
```
```
In io_uring/io_uring.c (ffffffff818138fb)
Location: include/linux/timekeeping.h:153
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_cqring_wait
```
```
In io_uring/cancel.c (ffffffff81824029)
Location: include/linux/timekeeping.h:153
Inline: True
Inline callers:
  - io_uring/cancel.c:io_sync_cancel
```
```
In drivers/gpio/gpiolib-cdev.c (ffffffff81950bc9)
Location: include/linux/timekeeping.h:153
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-cdev.c:lineinfo_changed_notify
  - drivers/gpio/gpiolib-cdev.c:lineevent_irq_handler
  - drivers/gpio/gpiolib-cdev.c:lineevent_irq_thread
  - drivers/gpio/gpiolib-cdev.c:line_event_timestamp
```
```
In drivers/connector/cn_proc.c (ffffffff81b83845)
Location: include/linux/timekeeping.h:153
Inline: True
Inline callers:
  - drivers/connector/cn_proc.c:proc_exit_connector
  - drivers/connector/cn_proc.c:proc_coredump_connector
  - drivers/connector/cn_proc.c:proc_comm_connector
  - drivers/connector/cn_proc.c:proc_ptrace_connector
  - drivers/connector/cn_proc.c:proc_sid_connector
  - drivers/connector/cn_proc.c:proc_id_connector
  - drivers/connector/cn_proc.c:proc_exec_connector
  - drivers/connector/cn_proc.c:proc_fork_connector
```
```
In net/core/neighbour.c (ffffffff81f0b8bc)
Location: include/linux/timekeeping.h:153
Inline: True
Inline callers:
  - net/core/neighbour.c:neigh_alloc
  - net/core/neighbour.c:neigh_alloc
```
```
In net/bpf/test_run.c (ffffffff81f93d25)
Location: include/linux/timekeeping.h:153
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_sk_lookup
  - net/bpf/test_run.c:bpf_prog_test_run_flow_dissector
  - net/bpf/test_run.c:bpf_test_run
  - net/bpf/test_run.c:bpf_test_run_xdp_live
  - net/bpf/test_run.c:bpf_test_timer_continue
  - net/bpf/test_run.c:bpf_test_timer_continue
  - net/bpf/test_run.c:bpf_test_timer_continue
```
```
In net/ipv4/tcp.c (ffffffff81fd6e3f)
Location: include/linux/timekeeping.h:153
Inline: True
Inline callers:
  - net/ipv4/tcp.c:do_tcp_getsockopt
  - net/ipv4/tcp.c:do_tcp_getsockopt
  - net/ipv4/tcp.c:tcp_get_info
```
```
In net/ipv4/tcp_input.c (ffffffff81fe0f03)
Location: include/linux/timekeeping.h:153
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_synack_rtt_meas
```
```
In net/ipv4/tcp_output.c (ffffffff81fedbcc)
Location: include/linux/timekeeping.h:153
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_window_probe
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_send_active_reset
  - net/ipv4/tcp_output.c:tcp_write_xmit
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ff4024)
Location: include/linux/timekeeping.h:153
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_timewait_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_timewait_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
```
```
In net/ipv4/tcp_minisocks.c (ffffffff81ff8c7c)
Location: include/linux/timekeeping.h:153
Inline: True
Inline callers:
  - net/ipv4/tcp_minisocks.c:tcp_create_openreq_child
  - net/ipv4/tcp_minisocks.c:tcp_create_openreq_child
```
```
In net/ipv6/tcp_ipv6.c (ffffffff820cac46)
Location: include/linux/timekeeping.h:153
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack
  - net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack
  - net/ipv6/tcp_ipv6.c:tcp_v6_timewait_ack
  - net/ipv6/tcp_ipv6.c:tcp_v6_timewait_ack
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
```
```
In net/mptcp/protocol.c (ffffffff82144860)
Location: include/linux/timekeeping.h:153
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_rcv_space_adjust
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
In kernel/fork.c (ffff8000100f3ea8)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/acct.c (ffff8000101c7b14)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - kernel/acct.c:do_acct_process
```
```
In kernel/delayacct.c (ffff80001020cd3c)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - kernel/delayacct.c:__delayacct_thrashing_start
  - kernel/delayacct.c:__delayacct_freepages_start
  - kernel/delayacct.c:__delayacct_blkio_start
  - kernel/delayacct.c:delayacct_end
```
```
In kernel/taskstats.c (ffff80001020d6bc)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_user_cmd
```
```
In kernel/tsacct.c (ffff80001020de74)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - kernel/tsacct.c:bacct_add_tsk
```
```
In kernel/bpf/verifier.c (ffff800010274158)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
```
```
In crypto/jitterentropy-kcapi.c (ffff8000105d3ed0)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - crypto/jitterentropy-kcapi.c:jent_get_nstime
```
```
In block/bio.c (ffff8000105db964)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - block/bio.c:__bio_clone_fast
```
```
In block/blk-core.c (ffff8000105e2e5c)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:blk_rq_init
```
```
In block/blk-mq.c (ffff8000105eea84)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_start_request
  - block/blk-mq.c:blk_mq_get_request
  - block/blk-mq.c:blk_mq_get_request
```
```
In block/blk-throttle.c (ffff8000106125f4)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:throtl_tg_is_idle
```
```
In block/blk-iocost.c (ffff8000106140bc)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_refresh_params
```
```
In drivers/soc/bcm/bcm2835-power.c (ffff80001080dd28)
Location: include/linux/timekeeping.h:152
Inline: True
```
```
In drivers/connector/cn_proc.c (ffff8000108de8f8)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - drivers/connector/cn_proc.c:proc_exit_connector
  - drivers/connector/cn_proc.c:proc_coredump_connector
  - drivers/connector/cn_proc.c:proc_comm_connector
  - drivers/connector/cn_proc.c:proc_ptrace_connector
  - drivers/connector/cn_proc.c:proc_sid_connector
  - drivers/connector/cn_proc.c:proc_id_connector
  - drivers/connector/cn_proc.c:proc_exec_connector
  - drivers/connector/cn_proc.c:proc_fork_connector
```
```
In drivers/media/cec/cec-adap.c (ffff800010ac0014)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - drivers/media/cec/cec-adap.c:cec_transmit_msg_fh
  - drivers/media/cec/cec-adap.c:cec_wait_timeout
  - drivers/media/cec/cec-adap.c:cec_data_cancel
  - drivers/media/cec/cec-adap.c:cec_data_cancel
  - drivers/media/cec/cec-adap.c:cec_post_state_event
  - drivers/media/cec/cec-adap.c:cec_queue_msg_fh
  - drivers/media/cec/cec-adap.c:cec_queue_event_fh
```
```
In drivers/md/dm-rq.c (ffff800010b0ea04)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - drivers/md/dm-rq.c:map_request
```
```
In net/bpf/test_run.c (ffff800010c53a28)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_flow_dissector
  - net/bpf/test_run.c:bpf_prog_test_run_flow_dissector
  - net/bpf/test_run.c:bpf_prog_test_run_flow_dissector
  - net/bpf/test_run.c:bpf_prog_test_run_flow_dissector
  - net/bpf/test_run.c:bpf_test_run
  - net/bpf/test_run.c:bpf_test_run
  - net/bpf/test_run.c:bpf_test_run
  - net/bpf/test_run.c:bpf_test_run
```
```
In net/ipv4/tcp.c (ffff800010c72520)
Location: include/linux/timekeeping.h:152
Inline: True
```
```
In net/ipv4/tcp_input.c (ffff800010c7d40c)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_synack_rtt_meas
```
```
In net/ipv4/tcp_output.c (ffff800010c88050)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_window_probe
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_send_active_reset
  - net/ipv4/tcp_output.c:tcp_write_xmit
```
```
In net/ipv4/tcp_ipv4.c (ffff800010c8ec0c)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
```
```
In net/ipv4/syncookies.c (ffff800010cd1f00)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_init_timestamp
```
```
In net/ipv6/tcp_ipv6.c (ffff800010d39160)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
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
In kernel/fork.c (c0352888)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/acct.c (c040e5bc)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - kernel/acct.c:fill_ac
```
```
In kernel/delayacct.c (c044b794)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - kernel/delayacct.c:__delayacct_thrashing_start
  - kernel/delayacct.c:__delayacct_freepages_start
  - kernel/delayacct.c:__delayacct_blkio_start
  - kernel/delayacct.c:delayacct_end
```
```
In kernel/taskstats.c (c044c0b8)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_user_cmd
```
```
In kernel/tsacct.c (c044c8dc)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - kernel/tsacct.c:bacct_add_tsk
```
```
In kernel/bpf/verifier.c (c04a67d0)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
```
```
In crypto/jitterentropy-kcapi.c (c07819e4)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - crypto/jitterentropy-kcapi.c:jent_get_nstime
```
```
In block/bio.c (c0788510)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - block/bio.c:__bio_clone_fast
```
```
In block/blk-core.c (c078f1ec)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:blk_rq_init
```
```
In block/blk-mq.c (c0799d4c)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_start_request
  - block/blk-mq.c:blk_mq_get_request
  - block/blk-mq.c:blk_mq_get_request
```
```
In block/bounce.c (c07b3338)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - block/bounce.c:__blk_queue_bounce
```
```
In block/blk-throttle.c (c07bd0ac)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:throtl_tg_is_idle
```
```
In block/blk-iocost.c (c07bebbc)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_refresh_params
```
```
In drivers/connector/cn_proc.c (c09cd9e8)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - drivers/connector/cn_proc.c:proc_exit_connector
  - drivers/connector/cn_proc.c:proc_coredump_connector
  - drivers/connector/cn_proc.c:proc_comm_connector
  - drivers/connector/cn_proc.c:proc_ptrace_connector
  - drivers/connector/cn_proc.c:proc_sid_connector
  - drivers/connector/cn_proc.c:proc_id_connector
  - drivers/connector/cn_proc.c:proc_exec_connector
  - drivers/connector/cn_proc.c:proc_fork_connector
```
```
In drivers/media/cec/cec-adap.c (c0ba1d48)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - drivers/media/cec/cec-adap.c:cec_transmit_msg_fh
  - drivers/media/cec/cec-adap.c:cec_wait_timeout
  - drivers/media/cec/cec-adap.c:cec_data_cancel
  - drivers/media/cec/cec-adap.c:cec_data_cancel
  - drivers/media/cec/cec-adap.c:cec_post_state_event
  - drivers/media/cec/cec-adap.c:cec_queue_msg_fh
  - drivers/media/cec/cec-adap.c:cec_queue_event_fh
```
```
In drivers/md/dm-rq.c (c0becdec)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - drivers/md/dm-rq.c:map_request
```
```
In net/bpf/test_run.c (c0d63530)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_flow_dissector
  - net/bpf/test_run.c:bpf_prog_test_run_flow_dissector
  - net/bpf/test_run.c:bpf_prog_test_run_flow_dissector
  - net/bpf/test_run.c:bpf_prog_test_run_flow_dissector
  - net/bpf/test_run.c:bpf_test_run
  - net/bpf/test_run.c:bpf_test_run
  - net/bpf/test_run.c:bpf_test_run
  - net/bpf/test_run.c:bpf_test_run
```
```
In net/ipv4/tcp.c (c0d7f090)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_time_stamp_raw
```
```
In net/ipv4/tcp_input.c (c0d8ce98)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_synack_rtt_meas
```
```
In net/ipv4/tcp_output.c (c0d91550)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_mstamp_refresh
```
```
In net/ipv4/tcp_ipv4.c (c0d9c14c)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_timewait_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
```
```
In net/ipv4/syncookies.c (c0ddbd8c)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_init_timestamp
```
```
In net/ipv6/tcp_ipv6.c (c0e39ee4)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack
  - net/ipv6/tcp_ipv6.c:tcp_v6_timewait_ack
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
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
In kernel/fork.c (c00000000013a20c)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/acct.c (c00000000022fc90)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - kernel/acct.c:do_acct_process
```
```
In kernel/delayacct.c (c00000000028a9e8)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - kernel/delayacct.c:__delayacct_thrashing_start
  - kernel/delayacct.c:__delayacct_freepages_start
  - kernel/delayacct.c:__delayacct_blkio_start
  - kernel/delayacct.c:delayacct_end
```
```
In kernel/taskstats.c (c00000000028b6d4)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_user_cmd
```
```
In kernel/tsacct.c (c00000000028c020)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - kernel/tsacct.c:bacct_add_tsk
```
```
In kernel/bpf/verifier.c (c00000000031bd58)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
```
```
In crypto/jitterentropy-kcapi.c (c000000000761498)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - crypto/jitterentropy-kcapi.c:jent_get_nstime
```
```
In block/bio.c (c00000000076b8b0)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - block/bio.c:__bio_clone_fast
```
```
In block/blk-core.c (c00000000077544c)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:blk_rq_init
```
```
In block/blk-mq.c (c000000000783888)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_start_request
  - block/blk-mq.c:blk_mq_get_request
  - block/blk-mq.c:blk_mq_get_request
```
```
In block/blk-throttle.c (c0000000007b0a40)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:throtl_tg_is_idle
```
```
In block/blk-iocost.c (c0000000007b350c)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_refresh_params
```
```
In drivers/connector/cn_proc.c (c00000000097227c)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - drivers/connector/cn_proc.c:proc_exit_connector
  - drivers/connector/cn_proc.c:proc_coredump_connector
  - drivers/connector/cn_proc.c:proc_comm_connector
  - drivers/connector/cn_proc.c:proc_ptrace_connector
  - drivers/connector/cn_proc.c:proc_sid_connector
  - drivers/connector/cn_proc.c:proc_id_connector
  - drivers/connector/cn_proc.c:proc_exec_connector
  - drivers/connector/cn_proc.c:proc_fork_connector
```
```
In drivers/media/cec/cec-adap.c (c000000000ba1e90)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - drivers/media/cec/cec-adap.c:cec_transmit_msg_fh
  - drivers/media/cec/cec-adap.c:cec_wait_timeout
  - drivers/media/cec/cec-adap.c:cec_data_cancel
  - drivers/media/cec/cec-adap.c:cec_data_cancel
  - drivers/media/cec/cec-adap.c:cec_post_state_event
  - drivers/media/cec/cec-adap.c:cec_queue_msg_fh
  - drivers/media/cec/cec-adap.c:cec_queue_event_fh
```
```
In drivers/md/dm-rq.c (c000000000c01b18)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - drivers/md/dm-rq.c:map_request
```
```
In net/bpf/test_run.c (c000000000d532f8)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_flow_dissector
  - net/bpf/test_run.c:bpf_prog_test_run_flow_dissector
  - net/bpf/test_run.c:bpf_prog_test_run_flow_dissector
  - net/bpf/test_run.c:bpf_prog_test_run_flow_dissector
  - net/bpf/test_run.c:bpf_test_run
  - net/bpf/test_run.c:bpf_test_run
  - net/bpf/test_run.c:bpf_test_run
  - net/bpf/test_run.c:bpf_test_run
```
```
In net/ipv4/tcp.c (c000000000d7956c)
Location: include/linux/timekeeping.h:152
Inline: True
```
```
In net/ipv4/tcp_input.c (c000000000d87f7c)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_synack_rtt_meas
```
```
In net/ipv4/tcp_output.c (c000000000d94e9c)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_window_probe
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_send_active_reset
  - net/ipv4/tcp_output.c:tcp_write_xmit
```
```
In net/ipv4/tcp_ipv4.c (c000000000d9d760)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
```
```
In net/ipv4/syncookies.c (c000000000df02b0)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_init_timestamp
```
```
In net/ipv6/tcp_ipv6.c (c000000000e6c724)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
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
In kernel/fork.c (ffffffe0000c06ac)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/acct.c (ffffffe000147974)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - kernel/acct.c:do_acct_process
```
```
In kernel/delayacct.c (ffffffe00016df8c)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - kernel/delayacct.c:__delayacct_thrashing_start
  - kernel/delayacct.c:__delayacct_freepages_start
  - kernel/delayacct.c:__delayacct_blkio_start
  - kernel/delayacct.c:delayacct_end
```
```
In kernel/taskstats.c (ffffffe00016e71c)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_user_cmd
```
```
In kernel/tsacct.c (ffffffe00016ed30)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - kernel/tsacct.c:bacct_add_tsk
```
```
In kernel/bpf/verifier.c (ffffffe0001acacc)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
```
```
In crypto/jitterentropy-kcapi.c (ffffffe000418456)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - crypto/jitterentropy-kcapi.c:jent_get_nstime
```
```
In block/bio.c (ffffffe00041e580)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - block/bio.c:__bio_clone_fast
```
```
In block/blk-core.c (ffffffe00042411c)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:blk_rq_init
```
```
In block/blk-mq.c (ffffffe00042d108)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_start_request
  - block/blk-mq.c:blk_mq_get_request
  - block/blk-mq.c:blk_mq_get_request
```
```
In block/blk-throttle.c (ffffffe000449c8e)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:throtl_tg_is_idle
```
```
In block/blk-iocost.c (ffffffe00044b80a)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_refresh_params
```
```
In drivers/connector/cn_proc.c (ffffffe000574bc8)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - drivers/connector/cn_proc.c:proc_exit_connector
  - drivers/connector/cn_proc.c:proc_coredump_connector
  - drivers/connector/cn_proc.c:proc_comm_connector
  - drivers/connector/cn_proc.c:proc_ptrace_connector
  - drivers/connector/cn_proc.c:proc_sid_connector
  - drivers/connector/cn_proc.c:proc_id_connector
  - drivers/connector/cn_proc.c:proc_exec_connector
  - drivers/connector/cn_proc.c:proc_fork_connector
```
```
In drivers/media/cec/cec-adap.c (ffffffe0006c17aa)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - drivers/media/cec/cec-adap.c:cec_transmit_msg_fh
  - drivers/media/cec/cec-adap.c:cec_wait_timeout
  - drivers/media/cec/cec-adap.c:cec_data_cancel
  - drivers/media/cec/cec-adap.c:cec_data_cancel
  - drivers/media/cec/cec-adap.c:cec_post_state_event
  - drivers/media/cec/cec-adap.c:cec_queue_msg_fh
  - drivers/media/cec/cec-adap.c:cec_queue_event_fh
```
```
In drivers/md/dm-rq.c (ffffffe0006fbcec)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - drivers/md/dm-rq.c:map_request
```
```
In net/bpf/test_run.c (ffffffe0007be28a)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_flow_dissector
  - net/bpf/test_run.c:bpf_prog_test_run_flow_dissector
  - net/bpf/test_run.c:bpf_prog_test_run_flow_dissector
  - net/bpf/test_run.c:bpf_prog_test_run_flow_dissector
  - net/bpf/test_run.c:bpf_test_run
  - net/bpf/test_run.c:bpf_test_run
  - net/bpf/test_run.c:bpf_test_run
  - net/bpf/test_run.c:bpf_test_run
```
```
In net/ipv4/tcp.c (ffffffe0007d52c6)
Location: include/linux/timekeeping.h:152
Inline: True
```
```
In net/ipv4/tcp_input.c (ffffffe0007e0368)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_synack_rtt_meas
```
```
In net/ipv4/tcp_output.c (ffffffe0007e92ee)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_window_probe
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_send_active_reset
  - net/ipv4/tcp_output.c:tcp_write_xmit
```
```
In net/ipv4/tcp_ipv4.c (ffffffe0007eeef6)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
```
```
In net/ipv4/syncookies.c (ffffffe000823304)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_init_timestamp
```
```
In net/ipv6/tcp_ipv6.c (ffffffe0008764ee)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
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
In kernel/fork.c (ffffffff81099121)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/sched/clock.c (ffffffff810d9454)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - kernel/sched/clock.c:__sched_clock_gtod_offset
  - kernel/sched/clock.c:__sched_clock_work
```
```
In kernel/acct.c (ffffffff81150896)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - kernel/acct.c:do_acct_process
```
```
In kernel/delayacct.c (ffffffff8118d1ba)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - kernel/delayacct.c:__delayacct_thrashing_start
  - kernel/delayacct.c:__delayacct_freepages_start
  - kernel/delayacct.c:__delayacct_blkio_start
  - kernel/delayacct.c:delayacct_end
```
```
In kernel/taskstats.c (ffffffff8118da56)
Location: include/linux/timekeeping.h:152
Inline: True
```
```
In kernel/tsacct.c (ffffffff8118e1a5)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - kernel/tsacct.c:bacct_add_tsk
```
```
In kernel/bpf/verifier.c (ffffffff811e8fbd)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
```
```
In crypto/jitterentropy-kcapi.c (ffffffff814d070e)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - crypto/jitterentropy-kcapi.c:jent_get_nstime
```
```
In block/bio.c (ffffffff814d6af7)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - block/bio.c:__bio_clone_fast
```
```
In block/blk-core.c (ffffffff814dd11f)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:blk_rq_init
```
```
In block/blk-mq.c (ffffffff814e7177)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_start_request
  - block/blk-mq.c:blk_mq_get_request
  - block/blk-mq.c:blk_mq_get_request
```
```
In block/bounce.c (ffffffff814fe604)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - block/bounce.c:__blk_queue_bounce
```
```
In block/blk-throttle.c (ffffffff81506ef4)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:throtl_tg_is_idle
```
```
In block/blk-iocost.c (ffffffff81508c38)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_refresh_params
```
```
In drivers/connector/cn_proc.c (ffffffff816baaf6)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - drivers/connector/cn_proc.c:proc_exit_connector
  - drivers/connector/cn_proc.c:proc_coredump_connector
  - drivers/connector/cn_proc.c:proc_comm_connector
  - drivers/connector/cn_proc.c:proc_ptrace_connector
  - drivers/connector/cn_proc.c:proc_sid_connector
  - drivers/connector/cn_proc.c:proc_id_connector
  - drivers/connector/cn_proc.c:proc_exec_connector
  - drivers/connector/cn_proc.c:proc_fork_connector
```
```
In drivers/media/cec/cec-adap.c (ffffffff81820b6c)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - drivers/media/cec/cec-adap.c:cec_transmit_msg_fh
  - drivers/media/cec/cec-adap.c:cec_wait_timeout
  - drivers/media/cec/cec-adap.c:cec_data_cancel
  - drivers/media/cec/cec-adap.c:cec_data_cancel
  - drivers/media/cec/cec-adap.c:cec_post_state_event
  - drivers/media/cec/cec-adap.c:cec_queue_msg_fh
  - drivers/media/cec/cec-adap.c:cec_queue_event_fh
```
```
In drivers/md/dm-rq.c (ffffffff8185c83d)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - drivers/md/dm-rq.c:map_request
```
```
In net/bpf/test_run.c (ffffffff81944503)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_flow_dissector
  - net/bpf/test_run.c:bpf_prog_test_run_flow_dissector
  - net/bpf/test_run.c:bpf_prog_test_run_flow_dissector
  - net/bpf/test_run.c:bpf_prog_test_run_flow_dissector
  - net/bpf/test_run.c:bpf_test_run
  - net/bpf/test_run.c:bpf_test_run
  - net/bpf/test_run.c:bpf_test_run
  - net/bpf/test_run.c:bpf_test_run
```
```
In net/ipv4/tcp.c (ffffffff8195e16e)
Location: include/linux/timekeeping.h:152
Inline: True
```
```
In net/ipv4/tcp_input.c (ffffffff8196a580)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_synack_rtt_meas
```
```
In net/ipv4/tcp_output.c (ffffffff81975240)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_window_probe
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_send_active_reset
  - net/ipv4/tcp_output.c:tcp_write_xmit
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8197b6f1)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
```
```
In net/ipv4/syncookies.c (ffffffff819b58c5)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_init_timestamp
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a10341)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
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
In kernel/fork.c (ffffffff81087b71)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/sched/clock.c (ffffffff810c7e34)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - kernel/sched/clock.c:__sched_clock_gtod_offset
  - kernel/sched/clock.c:__sched_clock_work
```
```
In kernel/acct.c (ffffffff81143b46)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - kernel/acct.c:do_acct_process
```
```
In kernel/delayacct.c (ffffffff811802da)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - kernel/delayacct.c:__delayacct_thrashing_start
  - kernel/delayacct.c:__delayacct_freepages_start
  - kernel/delayacct.c:__delayacct_blkio_start
  - kernel/delayacct.c:delayacct_end
```
```
In kernel/taskstats.c (ffffffff81180b74)
Location: include/linux/timekeeping.h:152
Inline: True
```
```
In kernel/tsacct.c (ffffffff811812e1)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - kernel/tsacct.c:bacct_add_tsk
```
```
In kernel/bpf/verifier.c (ffffffff811dbd7d)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
```
```
In crypto/jitterentropy-kcapi.c (ffffffff814c112e)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - crypto/jitterentropy-kcapi.c:jent_get_nstime
```
```
In block/bio.c (ffffffff814c74b7)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - block/bio.c:__bio_clone_fast
```
```
In block/blk-core.c (ffffffff814cdaca)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:blk_rq_init
```
```
In block/blk-mq.c (ffffffff814d76e7)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_start_request
  - block/blk-mq.c:blk_mq_get_request
  - block/blk-mq.c:blk_mq_get_request
```
```
In block/bounce.c (ffffffff814eeb14)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - block/bounce.c:__blk_queue_bounce
```
```
In block/blk-throttle.c (ffffffff814f73b4)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:throtl_tg_is_idle
```
```
In block/blk-iocost.c (ffffffff814f90e8)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_refresh_params
```
```
In drivers/connector/cn_proc.c (ffffffff81698736)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - drivers/connector/cn_proc.c:proc_exit_connector
  - drivers/connector/cn_proc.c:proc_coredump_connector
  - drivers/connector/cn_proc.c:proc_comm_connector
  - drivers/connector/cn_proc.c:proc_ptrace_connector
  - drivers/connector/cn_proc.c:proc_sid_connector
  - drivers/connector/cn_proc.c:proc_id_connector
  - drivers/connector/cn_proc.c:proc_exec_connector
  - drivers/connector/cn_proc.c:proc_fork_connector
```
```
In drivers/media/cec/cec-adap.c (ffffffff817e820c)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - drivers/media/cec/cec-adap.c:cec_transmit_msg_fh
  - drivers/media/cec/cec-adap.c:cec_wait_timeout
  - drivers/media/cec/cec-adap.c:cec_data_cancel
  - drivers/media/cec/cec-adap.c:cec_data_cancel
  - drivers/media/cec/cec-adap.c:cec_post_state_event
  - drivers/media/cec/cec-adap.c:cec_queue_msg_fh
  - drivers/media/cec/cec-adap.c:cec_queue_event_fh
```
```
In drivers/md/dm-rq.c (ffffffff81823e0d)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - drivers/md/dm-rq.c:map_request
```
```
In net/bpf/test_run.c (ffffffff818fdff3)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_flow_dissector
  - net/bpf/test_run.c:bpf_prog_test_run_flow_dissector
  - net/bpf/test_run.c:bpf_prog_test_run_flow_dissector
  - net/bpf/test_run.c:bpf_prog_test_run_flow_dissector
  - net/bpf/test_run.c:bpf_test_run
  - net/bpf/test_run.c:bpf_test_run
  - net/bpf/test_run.c:bpf_test_run
  - net/bpf/test_run.c:bpf_test_run
```
```
In net/ipv4/tcp.c (ffffffff81917c5e)
Location: include/linux/timekeeping.h:152
Inline: True
```
```
In net/ipv4/tcp_input.c (ffffffff81924070)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_synack_rtt_meas
```
```
In net/ipv4/tcp_output.c (ffffffff8192ed00)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_window_probe
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_send_active_reset
  - net/ipv4/tcp_output.c:tcp_write_xmit
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819351b1)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
```
```
In net/ipv4/syncookies.c (ffffffff819726b5)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_init_timestamp
```
```
In net/ipv6/tcp_ipv6.c (ffffffff819cd101)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
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
In kernel/fork.c (ffffffff810990d1)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/sched/clock.c (ffffffff810d5794)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - kernel/sched/clock.c:__sched_clock_gtod_offset
  - kernel/sched/clock.c:__sched_clock_work
```
```
In kernel/acct.c (ffffffff8114e746)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - kernel/acct.c:do_acct_process
```
```
In kernel/delayacct.c (ffffffff8118af8a)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - kernel/delayacct.c:__delayacct_thrashing_start
  - kernel/delayacct.c:__delayacct_freepages_start
  - kernel/delayacct.c:__delayacct_blkio_start
  - kernel/delayacct.c:delayacct_end
```
```
In kernel/taskstats.c (ffffffff8118b826)
Location: include/linux/timekeeping.h:152
Inline: True
```
```
In kernel/tsacct.c (ffffffff8118bf75)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - kernel/tsacct.c:bacct_add_tsk
```
```
In kernel/bpf/verifier.c (ffffffff811e6d8d)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
```
```
In crypto/jitterentropy-kcapi.c (ffffffff814cc79e)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - crypto/jitterentropy-kcapi.c:jent_get_nstime
```
```
In block/bio.c (ffffffff814d2b87)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - block/bio.c:__bio_clone_fast
```
```
In block/blk-core.c (ffffffff814d91af)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:blk_rq_init
```
```
In block/blk-mq.c (ffffffff814e3207)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_start_request
  - block/blk-mq.c:blk_mq_get_request
  - block/blk-mq.c:blk_mq_get_request
```
```
In block/bounce.c (ffffffff814fa694)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - block/bounce.c:__blk_queue_bounce
```
```
In block/blk-throttle.c (ffffffff81502f84)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:throtl_tg_is_idle
```
```
In block/blk-iocost.c (ffffffff81504cc8)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_refresh_params
```
```
In drivers/connector/cn_proc.c (ffffffff816e8fc6)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - drivers/connector/cn_proc.c:proc_exit_connector
  - drivers/connector/cn_proc.c:proc_coredump_connector
  - drivers/connector/cn_proc.c:proc_comm_connector
  - drivers/connector/cn_proc.c:proc_ptrace_connector
  - drivers/connector/cn_proc.c:proc_sid_connector
  - drivers/connector/cn_proc.c:proc_id_connector
  - drivers/connector/cn_proc.c:proc_exec_connector
  - drivers/connector/cn_proc.c:proc_fork_connector
```
```
In drivers/media/cec/cec-adap.c (ffffffff8186daac)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - drivers/media/cec/cec-adap.c:cec_transmit_msg_fh
  - drivers/media/cec/cec-adap.c:cec_wait_timeout
  - drivers/media/cec/cec-adap.c:cec_data_cancel
  - drivers/media/cec/cec-adap.c:cec_data_cancel
  - drivers/media/cec/cec-adap.c:cec_post_state_event
  - drivers/media/cec/cec-adap.c:cec_queue_msg_fh
  - drivers/media/cec/cec-adap.c:cec_queue_event_fh
```
```
In drivers/md/dm-rq.c (ffffffff818abe6d)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - drivers/md/dm-rq.c:map_request
```
```
In net/bpf/test_run.c (ffffffff81995693)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_flow_dissector
  - net/bpf/test_run.c:bpf_prog_test_run_flow_dissector
  - net/bpf/test_run.c:bpf_prog_test_run_flow_dissector
  - net/bpf/test_run.c:bpf_prog_test_run_flow_dissector
  - net/bpf/test_run.c:bpf_test_run
  - net/bpf/test_run.c:bpf_test_run
  - net/bpf/test_run.c:bpf_test_run
  - net/bpf/test_run.c:bpf_test_run
```
```
In net/ipv4/tcp.c (ffffffff819c893e)
Location: include/linux/timekeeping.h:152
Inline: True
```
```
In net/ipv4/tcp_input.c (ffffffff819d4d50)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_synack_rtt_meas
```
```
In net/ipv4/tcp_output.c (ffffffff819dfa10)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_window_probe
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_send_active_reset
  - net/ipv4/tcp_output.c:tcp_write_xmit
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819e5ec1)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
```
```
In net/ipv4/syncookies.c (ffffffff81a20165)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_init_timestamp
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a7adc1)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
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
In kernel/fork.c (ffffffff810a0d0a)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/sched/clock.c (ffffffff810e1064)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - kernel/sched/clock.c:__sched_clock_gtod_offset
  - kernel/sched/clock.c:__sched_clock_work
```
```
In kernel/acct.c (ffffffff8115b526)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - kernel/acct.c:do_acct_process
```
```
In kernel/delayacct.c (ffffffff811988fa)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - kernel/delayacct.c:__delayacct_thrashing_start
  - kernel/delayacct.c:__delayacct_freepages_start
  - kernel/delayacct.c:__delayacct_blkio_start
  - kernel/delayacct.c:delayacct_end
```
```
In kernel/taskstats.c (ffffffff8119919b)
Location: include/linux/timekeeping.h:152
Inline: True
```
```
In kernel/tsacct.c (ffffffff811998f5)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - kernel/tsacct.c:bacct_add_tsk
```
```
In kernel/bpf/verifier.c (ffffffff811f513d)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
```
```
In crypto/jitterentropy-kcapi.c (ffffffff814e526e)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - crypto/jitterentropy-kcapi.c:jent_get_nstime
```
```
In block/bio.c (ffffffff814eb70d)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - block/bio.c:__bio_clone_fast
```
```
In block/blk-core.c (ffffffff814f1dc4)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - block/blk-core.c:generic_make_request_checks
  - block/blk-core.c:blk_rq_init
```
```
In block/blk-mq.c (ffffffff814fc0a6)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_start_request
  - block/blk-mq.c:blk_mq_get_request
  - block/blk-mq.c:blk_mq_get_request
```
```
In block/bounce.c (ffffffff8151381f)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - block/bounce.c:__blk_queue_bounce
```
```
In block/blk-throttle.c (ffffffff8151c416)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - block/blk-throttle.c:blk_throtl_bio
  - block/blk-throttle.c:throtl_tg_is_idle
```
```
In block/blk-iocost.c (ffffffff8151e2e8)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - block/blk-iocost.c:ioc_refresh_params
```
```
In drivers/connector/cn_proc.c (ffffffff817037e6)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - drivers/connector/cn_proc.c:proc_exit_connector
  - drivers/connector/cn_proc.c:proc_coredump_connector
  - drivers/connector/cn_proc.c:proc_comm_connector
  - drivers/connector/cn_proc.c:proc_ptrace_connector
  - drivers/connector/cn_proc.c:proc_sid_connector
  - drivers/connector/cn_proc.c:proc_id_connector
  - drivers/connector/cn_proc.c:proc_exec_connector
  - drivers/connector/cn_proc.c:proc_fork_connector
```
```
In drivers/media/cec/cec-adap.c (ffffffff81887a2c)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - drivers/media/cec/cec-adap.c:cec_transmit_msg_fh
  - drivers/media/cec/cec-adap.c:cec_wait_timeout
  - drivers/media/cec/cec-adap.c:cec_data_cancel
  - drivers/media/cec/cec-adap.c:cec_data_cancel
  - drivers/media/cec/cec-adap.c:cec_post_state_event
  - drivers/media/cec/cec-adap.c:cec_queue_msg_fh
  - drivers/media/cec/cec-adap.c:cec_queue_event_fh
```
```
In drivers/md/dm-rq.c (ffffffff818c80ad)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - drivers/md/dm-rq.c:map_request
```
```
In net/bpf/test_run.c (ffffffff819b821f)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - net/bpf/test_run.c:bpf_prog_test_run_flow_dissector
  - net/bpf/test_run.c:bpf_prog_test_run_flow_dissector
  - net/bpf/test_run.c:bpf_prog_test_run_flow_dissector
  - net/bpf/test_run.c:bpf_prog_test_run_flow_dissector
  - net/bpf/test_run.c:bpf_test_run
  - net/bpf/test_run.c:bpf_test_run
  - net/bpf/test_run.c:bpf_test_run
  - net/bpf/test_run.c:bpf_test_run
```
```
In net/ipv4/tcp.c (ffffffff819d248e)
Location: include/linux/timekeeping.h:152
Inline: True
```
```
In net/ipv4/tcp_input.c (ffffffff819de930)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_synack_rtt_meas
```
```
In net/ipv4/tcp_output.c (ffffffff819e96c0)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_window_probe
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_make_synack
  - net/ipv4/tcp_output.c:tcp_send_active_reset
  - net/ipv4/tcp_output.c:tcp_write_xmit
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819efb81)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_v4_rcv
  - net/ipv4/tcp_ipv4.c:tcp_v4_reqsk_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_ack
  - net/ipv4/tcp_ipv4.c:tcp_v4_send_reset
```
```
In net/ipv4/syncookies.c (ffffffff81a2b665)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - net/ipv4/syncookies.c:cookie_init_timestamp
```
```
In net/ipv6/tcp_ipv6.c (ffffffff81a87601)
Location: include/linux/timekeeping.h:152
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp_v6_rcv
  - net/ipv6/tcp_ipv6.c:tcp_v6_reqsk_send_ack
  - net/ipv6/tcp_ipv6.c:tcp_v6_send_response
```
</details>
</li>
</ul>

## Differences
