# Function: <code>init_task_work</code>

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
In kernel/sched/fair.c (ffffffff810bb32a)
Location: include/linux/task_work.h:10
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_tick_numa
```
```
In kernel/irq/manage.c (ffffffff810dbd4b)
Location: include/linux/task_work.h:10
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_thread
```
```
In kernel/events/uprobes.c (ffffffff81188a25)
Location: include/linux/task_work.h:10
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_copy_process
```
```
In fs/file_table.c (ffffffff8120e382)
Location: include/linux/task_work.h:10
Inline: True
```
```
In fs/namespace.c (ffffffff8122cf82)
Location: include/linux/task_work.h:10
Inline: True
```
```
In security/keys/keyctl.c (ffffffff8133345e)
Location: include/linux/task_work.h:10
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_session_to_parent
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
In kernel/sched/fair.c (ffffffff810be7b8)
Location: include/linux/task_work.h:10
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_tick_numa
```
```
In kernel/irq/manage.c (ffffffff810e140a)
Location: include/linux/task_work.h:10
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_thread
```
```
In kernel/events/uprobes.c (ffffffff8119b0f5)
Location: include/linux/task_work.h:10
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_copy_process
```
```
In fs/file_table.c (ffffffff81234da1)
Location: include/linux/task_work.h:10
Inline: True
```
```
In fs/namespace.c (ffffffff81255712)
Location: include/linux/task_work.h:10
Inline: True
```
```
In security/keys/keyctl.c (ffffffff813682fb)
Location: include/linux/task_work.h:10
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_session_to_parent
```
```
In security/yama/yama_lsm.c (ffffffff813d0f4a)
Location: include/linux/task_work.h:10
Inline: True
Inline callers:
  - security/yama/yama_lsm.c:report_access
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
In kernel/sched/fair.c (ffffffff810c3a98)
Location: include/linux/task_work.h:10
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_tick_numa
```
```
In kernel/irq/manage.c (ffffffff810e779a)
Location: include/linux/task_work.h:10
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_thread
```
```
In kernel/events/uprobes.c (ffffffff811aab05)
Location: include/linux/task_work.h:10
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_copy_process
```
```
In fs/file_table.c (ffffffff81247951)
Location: include/linux/task_work.h:10
Inline: True
```
```
In fs/namespace.c (ffffffff81268b02)
Location: include/linux/task_work.h:10
Inline: True
```
```
In security/keys/keyctl.c (ffffffff8137eb0b)
Location: include/linux/task_work.h:10
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_session_to_parent
```
```
In security/yama/yama_lsm.c (ffffffff813e864a)
Location: include/linux/task_work.h:10
Inline: True
Inline callers:
  - security/yama/yama_lsm.c:report_access
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
In kernel/sched/fair.c (ffffffff810be6cd)
Location: include/linux/task_work.h:10
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_tick_numa
```
```
In kernel/irq/manage.c (ffffffff810e71ea)
Location: include/linux/task_work.h:10
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_thread
```
```
In kernel/events/uprobes.c (ffffffff811b205c)
Location: include/linux/task_work.h:10
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_copy_process
```
```
In fs/file_table.c (ffffffff81253181)
Location: include/linux/task_work.h:10
Inline: True
```
```
In fs/namespace.c (ffffffff812762b8)
Location: include/linux/task_work.h:10
Inline: True
```
```
In security/keys/keyctl.c (ffffffff8139299f)
Location: include/linux/task_work.h:10
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_session_to_parent
```
```
In security/yama/yama_lsm.c (ffffffff813f450a)
Location: include/linux/task_work.h:10
Inline: True
Inline callers:
  - security/yama/yama_lsm.c:report_access
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
In kernel/sched/fair.c (ffffffff810c63ad)
Location: include/linux/task_work.h:11
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_tick_numa
```
```
In kernel/irq/manage.c (ffffffff810ef4db)
Location: include/linux/task_work.h:11
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_thread
```
```
In kernel/events/uprobes.c (ffffffff811c5c6c)
Location: include/linux/task_work.h:11
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_copy_process
```
```
In fs/file_table.c (ffffffff81275281)
Location: include/linux/task_work.h:11
Inline: True
```
```
In fs/namespace.c (ffffffff81298c03)
Location: include/linux/task_work.h:11
Inline: True
```
```
In security/keys/keyctl.c (ffffffff813b7fff)
Location: include/linux/task_work.h:11
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_session_to_parent
```
```
In security/yama/yama_lsm.c (ffffffff8141cc37)
Location: include/linux/task_work.h:11
Inline: True
Inline callers:
  - security/yama/yama_lsm.c:report_access
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
In kernel/sched/fair.c (ffffffff810cddac)
Location: include/linux/task_work.h:11
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_tick_numa
```
```
In kernel/irq/manage.c (ffffffff810f78a4)
Location: include/linux/task_work.h:11
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_thread
```
```
In kernel/events/uprobes.c (ffffffff811e616a)
Location: include/linux/task_work.h:11
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_copy_process
```
```
In fs/file_table.c (ffffffff8129bb11)
Location: include/linux/task_work.h:11
Inline: True
```
```
In fs/namespace.c (ffffffff812bedf2)
Location: include/linux/task_work.h:11
Inline: True
```
```
In security/keys/keyctl.c (ffffffff813e8beb)
Location: include/linux/task_work.h:11
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_session_to_parent
```
```
In security/yama/yama_lsm.c (ffffffff8144ee8e)
Location: include/linux/task_work.h:11
Inline: True
Inline callers:
  - security/yama/yama_lsm.c:report_access
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
In kernel/sched/fair.c (ffffffff810d70ec)
Location: include/linux/task_work.h:11
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_tick_numa
```
```
In kernel/irq/manage.c (ffffffff81103134)
Location: include/linux/task_work.h:11
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_thread
```
```
In kernel/events/uprobes.c (ffffffff811f6cba)
Location: include/linux/task_work.h:11
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_copy_process
```
```
In fs/file_table.c (ffffffff812b0e41)
Location: include/linux/task_work.h:11
Inline: True
```
```
In fs/namespace.c (ffffffff812d40c2)
Location: include/linux/task_work.h:11
Inline: True
```
```
In security/keys/keyctl.c (ffffffff814033eb)
Location: include/linux/task_work.h:11
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_session_to_parent
```
```
In security/yama/yama_lsm.c (ffffffff8146be5e)
Location: include/linux/task_work.h:11
Inline: True
Inline callers:
  - security/yama/yama_lsm.c:report_access
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
In kernel/sched/fair.c (ffffffff810dc883)
Location: include/linux/task_work.h:11
Inline: True
Inline callers:
  - kernel/sched/fair.c:task_tick_fair
```
```
In kernel/irq/manage.c (ffffffff8110b7c4)
Location: include/linux/task_work.h:11
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_thread
```
```
In kernel/events/uprobes.c (ffffffff8120ea6d)
Location: include/linux/task_work.h:11
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_copy_process
```
```
In fs/file_table.c (ffffffff812cd864)
Location: include/linux/task_work.h:11
Inline: True
```
```
In fs/namespace.c (ffffffff812f1100)
Location: include/linux/task_work.h:11
Inline: True
Inline callers:
  - fs/namespace.c:mntput_no_expire
```
```
In security/keys/keyctl.c (ffffffff8142fff9)
Location: include/linux/task_work.h:11
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_session_to_parent
```
```
In security/yama/yama_lsm.c (ffffffff81498e4d)
Location: include/linux/task_work.h:11
Inline: True
Inline callers:
  - security/yama/yama_lsm.c:report_access
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
In kernel/sched/fair.c (ffffffff810e933c)
Location: include/linux/task_work.h:11
Inline: True
Inline callers:
  - kernel/sched/fair.c:init_numa_balancing
```
```
In kernel/irq/manage.c (ffffffff81117ac4)
Location: include/linux/task_work.h:11
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_thread
```
```
In kernel/events/uprobes.c (ffffffff8121c0ad)
Location: include/linux/task_work.h:11
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_copy_process
```
```
In fs/file_table.c (ffffffff812df284)
Location: include/linux/task_work.h:11
Inline: True
```
```
In fs/namespace.c (ffffffff81302ca0)
Location: include/linux/task_work.h:11
Inline: True
Inline callers:
  - fs/namespace.c:mntput_no_expire
```
```
In security/keys/keyctl.c (ffffffff81449d59)
Location: include/linux/task_work.h:11
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_session_to_parent
```
```
In security/yama/yama_lsm.c (ffffffff814b2d7d)
Location: include/linux/task_work.h:11
Inline: True
Inline callers:
  - security/yama/yama_lsm.c:report_access
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
In kernel/sched/fair.c (ffffffff810f38ac)
Location: include/linux/task_work.h:11
Inline: True
Inline callers:
  - kernel/sched/fair.c:init_numa_balancing
```
```
In kernel/irq/manage.c (ffffffff81123585)
Location: include/linux/task_work.h:11
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_thread
```
```
In kernel/events/uprobes.c (ffffffff8124875e)
Location: include/linux/task_work.h:11
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_copy_process
```
```
In fs/file_table.c (ffffffff813160e4)
Location: include/linux/task_work.h:11
Inline: True
```
```
In fs/namespace.c (ffffffff8133c657)
Location: include/linux/task_work.h:11
Inline: True
Inline callers:
  - fs/namespace.c:mntput_no_expire
```
```
In fs/io_uring.c (ffffffff8137d920)
Location: include/linux/task_work.h:11
Inline: True
Inline callers:
  - fs/io_uring.c:__io_async_wake
```
```
In security/keys/keyctl.c (ffffffff8149b759)
Location: include/linux/task_work.h:11
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_session_to_parent
```
```
In security/yama/yama_lsm.c (ffffffff8151214f)
Location: include/linux/task_work.h:11
Inline: True
Inline callers:
  - security/yama/yama_lsm.c:report_access
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
In kernel/sched/fair.c (ffffffff810f1aec)
Location: include/linux/task_work.h:11
Inline: True
Inline callers:
  - kernel/sched/fair.c:init_numa_balancing
```
```
In kernel/irq/manage.c (ffffffff8111f3d5)
Location: include/linux/task_work.h:11
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_thread
```
```
In kernel/time/posix-cpu-timers.c (ffffffff82fde8c8)
Location: include/linux/task_work.h:11
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:posix_cputimers_init_work
```
```
In kernel/events/uprobes.c (ffffffff81252e6e)
Location: include/linux/task_work.h:11
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_copy_process
```
```
In fs/file_table.c (ffffffff8132127b)
Location: include/linux/task_work.h:11
Inline: True
```
```
In fs/namespace.c (ffffffff81348504)
Location: include/linux/task_work.h:11
Inline: True
Inline callers:
  - fs/namespace.c:mntput_no_expire
```
```
In fs/io_uring.c (ffffffff81391af9)
Location: include/linux/task_work.h:11
Inline: True
Inline callers:
  - fs/io_uring.c:io_link_timeout_fn
  - fs/io_uring.c:io_link_timeout_fn
  - fs/io_uring.c:io_link_timeout_fn
  - fs/io_uring.c:io_link_timeout_fn
  - fs/io_uring.c:io_wq_submit_work
  - fs/io_uring.c:io_timeout_cancel
  - fs/io_uring.c:io_timeout_cancel
  - fs/io_uring.c:io_poll_remove_one
  - fs/io_uring.c:io_poll_remove_one
  - fs/io_uring.c:__io_async_wake
  - fs/io_uring.c:__io_async_wake
  - fs/io_uring.c:io_async_buf_func
  - fs/io_uring.c:io_async_buf_func
  - fs/io_uring.c:io_put_req_deferred_cb
  - fs/io_uring.c:io_put_req_deferred_cb
  - fs/io_uring.c:io_req_free_batch
  - fs/io_uring.c:io_req_free_batch
  - fs/io_uring.c:__io_req_task_cancel
  - fs/io_uring.c:__io_req_task_cancel
  - fs/io_uring.c:io_fail_links
  - fs/io_uring.c:io_fail_links
  - fs/io_uring.c:io_fail_links
  - fs/io_uring.c:io_fail_links
  - fs/io_uring.c:io_commit_cqring
  - fs/io_uring.c:io_commit_cqring
  - fs/io_uring.c:io_flush_timeouts
  - fs/io_uring.c:io_flush_timeouts
  - fs/io_uring.c:io_kill_timeouts
  - fs/io_uring.c:io_kill_timeouts
```
```
In security/keys/keyctl.c (ffffffff814b91e9)
Location: include/linux/task_work.h:11
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_session_to_parent
```
```
In security/yama/yama_lsm.c (ffffffff8152efef)
Location: include/linux/task_work.h:11
Inline: True
Inline callers:
  - security/yama/yama_lsm.c:report_access
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
In kernel/sched/fair.c (ffffffff810f3dcc)
Location: include/linux/task_work.h:11
Inline: True
Inline callers:
  - kernel/sched/fair.c:init_numa_balancing
```
```
In kernel/irq/manage.c (ffffffff8111f4f4)
Location: include/linux/task_work.h:11
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_thread
```
```
In kernel/time/posix-cpu-timers.c (ffffffff831e93f1)
Location: include/linux/task_work.h:11
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:posix_cputimers_init_work
```
```
In kernel/events/uprobes.c (ffffffff81257192)
Location: include/linux/task_work.h:11
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_copy_process
```
```
In fs/file_table.c (ffffffff813276e4)
Location: include/linux/task_work.h:11
Inline: True
```
```
In fs/namespace.c (ffffffff8134e8cf)
Location: include/linux/task_work.h:11
Inline: True
Inline callers:
  - fs/namespace.c:mntput_no_expire
```
```
In fs/io_uring.c (ffffffff8139b0dd)
Location: include/linux/task_work.h:11
Inline: True
Inline callers:
  - fs/io_uring.c:io_ring_exit_work
  - fs/io_uring.c:io_uring_alloc_task_context
  - fs/io_uring.c:io_wq_submit_work
  - fs/io_uring.c:__io_async_wake
  - fs/io_uring.c:io_put_req_deferred_cb
  - fs/io_uring.c:io_req_free_batch
  - fs/io_uring.c:io_fail_links
  - fs/io_uring.c:io_commit_cqring
```
```
In fs/io-wq.c (ffffffff813a26ea)
Location: include/linux/task_work.h:11
Inline: True
```
```
In security/keys/keyctl.c (ffffffff814bf039)
Location: include/linux/task_work.h:11
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_session_to_parent
```
```
In security/yama/yama_lsm.c (ffffffff81534f7b)
Location: include/linux/task_work.h:11
Inline: True
Inline callers:
  - security/yama/yama_lsm.c:report_access
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
In kernel/sched/fair.c (ffffffff8110d6dc)
Location: include/linux/task_work.h:11
Inline: True
Inline callers:
  - kernel/sched/fair.c:init_numa_balancing
```
```
In kernel/irq/manage.c (ffffffff8113f96f)
Location: include/linux/task_work.h:11
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_thread
```
```
In kernel/time/posix-cpu-timers.c (ffffffff81175931)
Location: include/linux/task_work.h:11
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:clear_posix_cputimers_work
```
```
In kernel/events/uprobes.c (ffffffff81292f22)
Location: include/linux/task_work.h:11
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_copy_process
```
```
In fs/file_table.c (ffffffff81374ce4)
Location: include/linux/task_work.h:11
Inline: True
```
```
In fs/namespace.c (ffffffff8139c912)
Location: include/linux/task_work.h:11
Inline: True
Inline callers:
  - fs/namespace.c:mntput_no_expire
```
```
In fs/io_uring.c (ffffffff813e9da9)
Location: include/linux/task_work.h:11
Inline: True
Inline callers:
  - fs/io_uring.c:io_ring_exit_work
  - fs/io_uring.c:io_uring_alloc_task_context
```
```
In fs/io-wq.c (ffffffff813f1948)
Location: include/linux/task_work.h:11
Inline: True
Inline callers:
  - fs/io-wq.c:io_queue_worker_create
```
```
In security/keys/keyctl.c (ffffffff81517a59)
Location: include/linux/task_work.h:11
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_session_to_parent
```
```
In security/yama/yama_lsm.c (ffffffff8159348b)
Location: include/linux/task_work.h:11
Inline: True
Inline callers:
  - security/yama/yama_lsm.c:report_access
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
In kernel/sched/fair.c (ffffffff8112932b)
Location: include/linux/task_work.h:11
Inline: True
Inline callers:
  - kernel/sched/fair.c:init_numa_balancing
```
```
In kernel/irq/manage.c (ffffffff81163315)
Location: include/linux/task_work.h:11
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_thread
```
```
In kernel/time/posix-cpu-timers.c (ffffffff811aa8c1)
Location: include/linux/task_work.h:11
Inline: True
```
```
In kernel/events/uprobes.c (ffffffff812e8976)
Location: include/linux/task_work.h:11
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_copy_process
```
```
In fs/file_table.c (ffffffff813f3671)
Location: include/linux/task_work.h:11
Inline: True
```
```
In fs/namespace.c (ffffffff8141f80d)
Location: include/linux/task_work.h:11
Inline: True
Inline callers:
  - fs/namespace.c:mntput_no_expire
```
```
In security/keys/keyctl.c (ffffffff815aa494)
Location: include/linux/task_work.h:11
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_session_to_parent
```
```
In security/yama/yama_lsm.c (ffffffff8163575d)
Location: include/linux/task_work.h:11
Inline: True
Inline callers:
  - security/yama/yama_lsm.c:report_access
```
```
In io_uring/io_uring.c (ffffffff81e9227b)
Location: include/linux/task_work.h:11
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_ring_exit_work
  - io_uring/io_uring.c:io_uring_alloc_task_context
```
```
In io_uring/io-wq.c (ffffffff816da2ff)
Location: include/linux/task_work.h:11
Inline: True
Inline callers:
  - io_uring/io-wq.c:io_queue_worker_create
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
In kernel/sched/fair.c (ffffffff81152dbb)
Location: include/linux/task_work.h:11
Inline: True
Inline callers:
  - kernel/sched/fair.c:init_numa_balancing
```
```
In kernel/irq/manage.c (ffffffff81196f55)
Location: include/linux/task_work.h:11
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_thread
```
```
In kernel/time/posix-cpu-timers.c (ffffffff83eae6da)
Location: include/linux/task_work.h:11
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:posix_cputimers_init_work
```
```
In kernel/events/core.c (ffffffff8133f481)
Location: include/linux/task_work.h:11
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
```
```
In kernel/events/uprobes.c (ffffffff81352656)
Location: include/linux/task_work.h:11
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_copy_process
```
```
In fs/file_table.c (ffffffff8147c431)
Location: include/linux/task_work.h:11
Inline: True
```
```
In fs/namespace.c (ffffffff814abd40)
Location: include/linux/task_work.h:11
Inline: True
Inline callers:
  - fs/namespace.c:mntput_no_expire
```
```
In security/keys/keyctl.c (ffffffff81654794)
Location: include/linux/task_work.h:11
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_session_to_parent
```
```
In security/yama/yama_lsm.c (ffffffff816ec44d)
Location: include/linux/task_work.h:11
Inline: True
Inline callers:
  - security/yama/yama_lsm.c:report_access
```
```
In io_uring/io_uring.c (ffffffff8178f768)
Location: include/linux/task_work.h:11
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_ring_exit_work
  - io_uring/io_uring.c:io_ring_ctx_alloc
```
```
In io_uring/msg_ring.c (ffffffff81798c17)
Location: include/linux/task_work.h:11
Inline: True
Inline callers:
  - io_uring/msg_ring.c:io_msg_ring
  - io_uring/msg_ring.c:io_msg_ring
```
```
In io_uring/tctx.c (ffffffff8179bb9c)
Location: include/linux/task_work.h:11
Inline: True
Inline callers:
  - io_uring/tctx.c:io_uring_alloc_task_context
```
```
In io_uring/io-wq.c (ffffffff817a63af)
Location: include/linux/task_work.h:11
Inline: True
Inline callers:
  - io_uring/io-wq.c:io_queue_worker_create
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
In kernel/sched/core.c (ffffffff811418de)
Location: include/linux/task_work.h:11
Inline: True
Inline callers:
  - kernel/sched/core.c:__sched_fork
```
```
In kernel/sched/fair.c (ffffffff8116266c)
Location: include/linux/task_work.h:11
Inline: True
Inline callers:
  - kernel/sched/fair.c:init_numa_balancing
```
```
In kernel/irq/manage.c (ffffffff811a8a65)
Location: include/linux/task_work.h:11
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_thread
```
```
In kernel/time/posix-cpu-timers.c (ffffffff811ff0ea)
Location: include/linux/task_work.h:11
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:clear_posix_cputimers_work
```
```
In kernel/events/core.c (ffffffff81370651)
Location: include/linux/task_work.h:11
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
```
```
In kernel/events/uprobes.c (ffffffff81383866)
Location: include/linux/task_work.h:11
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_copy_process
```
```
In fs/file_table.c (ffffffff814b0fb1)
Location: include/linux/task_work.h:11
Inline: True
```
```
In fs/namespace.c (ffffffff814e0afc)
Location: include/linux/task_work.h:11
Inline: True
Inline callers:
  - fs/namespace.c:mntput_no_expire
```
```
In security/keys/keyctl.c (ffffffff8168cfd4)
Location: include/linux/task_work.h:11
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_session_to_parent
```
```
In security/yama/yama_lsm.c (ffffffff8172687d)
Location: include/linux/task_work.h:11
Inline: True
Inline callers:
  - security/yama/yama_lsm.c:report_access
```
```
In io_uring/io_uring.c (ffffffff817d0a98)
Location: include/linux/task_work.h:11
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_ring_exit_work
  - io_uring/io_uring.c:io_activate_pollwq
```
```
In io_uring/msg_ring.c (ffffffff817d9911)
Location: include/linux/task_work.h:11
Inline: True
Inline callers:
  - io_uring/msg_ring.c:io_msg_send_fd
  - io_uring/msg_ring.c:io_msg_ring_data
```
```
In io_uring/tctx.c (ffffffff817dcccc)
Location: include/linux/task_work.h:11
Inline: True
Inline callers:
  - io_uring/tctx.c:io_uring_alloc_task_context
```
```
In io_uring/io-wq.c (ffffffff817e7310)
Location: include/linux/task_work.h:11
Inline: True
Inline callers:
  - io_uring/io-wq.c:io_queue_worker_create
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
In kernel/sched/core.c (ffffffff8114cc5a)
Location: include/linux/task_work.h:11
Inline: True
Inline callers:
  - kernel/sched/core.c:__sched_fork
```
```
In kernel/sched/fair.c (ffffffff8116f13c)
Location: include/linux/task_work.h:11
Inline: True
Inline callers:
  - kernel/sched/fair.c:init_numa_balancing
```
```
In kernel/irq/manage.c (ffffffff811b85c5)
Location: include/linux/task_work.h:11
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_thread
```
```
In kernel/time/posix-cpu-timers.c (ffffffff8121546a)
Location: include/linux/task_work.h:11
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:clear_posix_cputimers_work
```
```
In kernel/events/core.c (ffffffff81399951)
Location: include/linux/task_work.h:11
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_alloc
```
```
In kernel/events/uprobes.c (ffffffff813accc0)
Location: include/linux/task_work.h:11
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_copy_process
```
```
In fs/file_table.c (ffffffff814e277a)
Location: include/linux/task_work.h:11
Inline: True
```
```
In fs/namespace.c (ffffffff81514bcc)
Location: include/linux/task_work.h:11
Inline: True
Inline callers:
  - fs/namespace.c:mntput_no_expire
```
```
In security/keys/keyctl.c (ffffffff816c94c4)
Location: include/linux/task_work.h:11
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_session_to_parent
```
```
In security/yama/yama_lsm.c (ffffffff81767acc)
Location: include/linux/task_work.h:11
Inline: True
Inline callers:
  - security/yama/yama_lsm.c:report_access
```
```
In io_uring/io_uring.c (ffffffff81814388)
Location: include/linux/task_work.h:11
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_ring_exit_work
  - io_uring/io_uring.c:io_activate_pollwq
```
```
In io_uring/msg_ring.c (ffffffff8181dc31)
Location: include/linux/task_work.h:11
Inline: True
Inline callers:
  - io_uring/msg_ring.c:io_msg_send_fd
  - io_uring/msg_ring.c:io_msg_ring_data
```
```
In io_uring/tctx.c (ffffffff81820fae)
Location: include/linux/task_work.h:11
Inline: True
Inline callers:
  - io_uring/tctx.c:io_uring_alloc_task_context
```
```
In io_uring/io-wq.c (ffffffff8182d0d0)
Location: include/linux/task_work.h:11
Inline: True
Inline callers:
  - io_uring/io-wq.c:io_queue_worker_create
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
In kernel/sched/fair.c (ffff800010149230)
Location: include/linux/task_work.h:11
Inline: True
Inline callers:
  - kernel/sched/fair.c:init_numa_balancing
```
```
In kernel/irq/manage.c (ffff800010179824)
Location: include/linux/task_work.h:11
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_thread
```
```
In kernel/events/uprobes.c (ffff8000102a79c8)
Location: include/linux/task_work.h:11
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_copy_process
```
```
In fs/file_table.c (ffff800010385b24)
Location: include/linux/task_work.h:11
Inline: True
```
```
In fs/namespace.c (ffff8000103b6044)
Location: include/linux/task_work.h:11
Inline: True
Inline callers:
  - fs/namespace.c:mntput_no_expire
```
```
In security/keys/keyctl.c (ffff800010533ac8)
Location: include/linux/task_work.h:11
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_session_to_parent
```
```
In security/yama/yama_lsm.c (ffff8000105aa5c0)
Location: include/linux/task_work.h:11
Inline: True
Inline callers:
  - security/yama/yama_lsm.c:report_access
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
In kernel/irq/manage.c (c03cb4b8)
Location: include/linux/task_work.h:11
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_thread
```
```
In kernel/events/uprobes.c (c04d6aec)
Location: include/linux/task_work.h:11
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_copy_process
```
```
In fs/file_table.c (c056e9d0)
Location: include/linux/task_work.h:11
Inline: True
```
```
In fs/namespace.c (c05943c4)
Location: include/linux/task_work.h:11
Inline: True
Inline callers:
  - fs/namespace.c:mntput_no_expire
```
```
In security/keys/keyctl.c (c06eb30c)
Location: include/linux/task_work.h:11
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_session_to_parent
```
```
In security/yama/yama_lsm.c (c075a53c)
Location: include/linux/task_work.h:11
Inline: True
Inline callers:
  - security/yama/yama_lsm.c:report_access
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
In kernel/sched/fair.c (c00000000019afd8)
Location: include/linux/task_work.h:11
Inline: True
Inline callers:
  - kernel/sched/fair.c:init_numa_balancing
```
```
In kernel/irq/manage.c (c0000000001d4008)
Location: include/linux/task_work.h:11
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_thread
```
```
In kernel/events/uprobes.c (c00000000035b010)
Location: include/linux/task_work.h:11
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_copy_process
```
```
In fs/file_table.c (c00000000047bd04)
Location: include/linux/task_work.h:11
Inline: True
```
```
In fs/namespace.c (c0000000004b2510)
Location: include/linux/task_work.h:11
Inline: True
Inline callers:
  - fs/namespace.c:mntput_no_expire
```
```
In security/keys/keyctl.c (c000000000681980)
Location: include/linux/task_work.h:11
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_session_to_parent
```
```
In security/yama/yama_lsm.c (c000000000728330)
Location: include/linux/task_work.h:11
Inline: True
Inline callers:
  - security/yama/yama_lsm.c:report_access
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
In kernel/irq/manage.c (ffffffe000114452)
Location: include/linux/task_work.h:11
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_thread
```
```
In fs/file_table.c (ffffffe0002587ae)
Location: include/linux/task_work.h:11
Inline: True
```
```
In fs/namespace.c (ffffffe000278d82)
Location: include/linux/task_work.h:11
Inline: True
Inline callers:
  - fs/namespace.c:mntput_no_expire
```
```
In security/keys/keyctl.c (ffffffe000393efe)
Location: include/linux/task_work.h:11
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_session_to_parent
```
```
In security/yama/yama_lsm.c (ffffffe0003f324e)
Location: include/linux/task_work.h:11
Inline: True
Inline callers:
  - security/yama/yama_lsm.c:report_access
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
In kernel/sched/fair.c (ffffffff810e34ec)
Location: include/linux/task_work.h:11
Inline: True
Inline callers:
  - kernel/sched/fair.c:init_numa_balancing
```
```
In kernel/irq/manage.c (ffffffff811100a4)
Location: include/linux/task_work.h:11
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_thread
```
```
In kernel/events/uprobes.c (ffffffff812146fd)
Location: include/linux/task_work.h:11
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_copy_process
```
```
In fs/file_table.c (ffffffff812d7864)
Location: include/linux/task_work.h:11
Inline: True
```
```
In fs/namespace.c (ffffffff812fb280)
Location: include/linux/task_work.h:11
Inline: True
Inline callers:
  - fs/namespace.c:mntput_no_expire
```
```
In security/keys/keyctl.c (ffffffff81442339)
Location: include/linux/task_work.h:11
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_session_to_parent
```
```
In security/yama/yama_lsm.c (ffffffff814ab35d)
Location: include/linux/task_work.h:11
Inline: True
Inline callers:
  - security/yama/yama_lsm.c:report_access
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
In kernel/sched/fair.c (ffffffff810d25ec)
Location: include/linux/task_work.h:11
Inline: True
Inline callers:
  - kernel/sched/fair.c:init_numa_balancing
```
```
In kernel/irq/manage.c (ffffffff81100dd4)
Location: include/linux/task_work.h:11
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_thread
```
```
In kernel/events/uprobes.c (ffffffff8120746d)
Location: include/linux/task_work.h:11
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_copy_process
```
```
In fs/file_table.c (ffffffff812c84e4)
Location: include/linux/task_work.h:11
Inline: True
```
```
In fs/namespace.c (ffffffff812ebea0)
Location: include/linux/task_work.h:11
Inline: True
Inline callers:
  - fs/namespace.c:mntput_no_expire
```
```
In security/keys/keyctl.c (ffffffff81432da6)
Location: include/linux/task_work.h:11
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_session_to_parent
```
```
In security/yama/yama_lsm.c (ffffffff8149bd7d)
Location: include/linux/task_work.h:11
Inline: True
Inline callers:
  - security/yama/yama_lsm.c:report_access
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
In kernel/sched/fair.c (ffffffff810df86c)
Location: include/linux/task_work.h:11
Inline: True
Inline callers:
  - kernel/sched/fair.c:init_numa_balancing
```
```
In kernel/irq/manage.c (ffffffff8110df94)
Location: include/linux/task_work.h:11
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_thread
```
```
In kernel/events/uprobes.c (ffffffff8121249d)
Location: include/linux/task_work.h:11
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_copy_process
```
```
In fs/file_table.c (ffffffff812d5674)
Location: include/linux/task_work.h:11
Inline: True
```
```
In fs/namespace.c (ffffffff812f9070)
Location: include/linux/task_work.h:11
Inline: True
Inline callers:
  - fs/namespace.c:mntput_no_expire
```
```
In security/keys/keyctl.c (ffffffff8143e4d9)
Location: include/linux/task_work.h:11
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_session_to_parent
```
```
In security/yama/yama_lsm.c (ffffffff814a73fd)
Location: include/linux/task_work.h:11
Inline: True
Inline callers:
  - security/yama/yama_lsm.c:report_access
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
In kernel/sched/fair.c (ffffffff810eb43c)
Location: include/linux/task_work.h:11
Inline: True
Inline callers:
  - kernel/sched/fair.c:init_numa_balancing
```
```
In kernel/irq/manage.c (ffffffff811194d4)
Location: include/linux/task_work.h:11
Inline: True
Inline callers:
  - kernel/irq/manage.c:irq_thread
```
```
In kernel/events/uprobes.c (ffffffff8122141d)
Location: include/linux/task_work.h:11
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_copy_process
```
```
In fs/file_table.c (ffffffff812e64c4)
Location: include/linux/task_work.h:11
Inline: True
```
```
In fs/namespace.c (ffffffff8130a39c)
Location: include/linux/task_work.h:11
Inline: True
Inline callers:
  - fs/namespace.c:mntput_no_expire
```
```
In security/keys/keyctl.c (ffffffff81455656)
Location: include/linux/task_work.h:11
Inline: True
Inline callers:
  - security/keys/keyctl.c:keyctl_session_to_parent
```
```
In security/yama/yama_lsm.c (ffffffff814bfd5d)
Location: include/linux/task_work.h:11
Inline: True
Inline callers:
  - security/yama/yama_lsm.c:report_access
```
</details>
</li>
</ul>

## Differences
