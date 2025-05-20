# Function: <code>task_work_add</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int task_work_add(struct task_struct *task, struct callback_head *work, bool notify);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/task_work.c (ffffffff8109e800)
Location: kernel/task_work.c:27
Inline: False
Direct callers:
  - kernel/sched/fair.c:task_tick_numa
  - kernel/irq/manage.c:irq_thread
  - kernel/events/uprobes.c:uprobe_copy_process
  - security/keys/keyctl.c:keyctl_session_to_parent
```
**Symbols:**

```
ffffffff8109e800-ffffffff8109e852: task_work_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int task_work_add(struct task_struct *task, struct callback_head *work, bool notify);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/task_work.c (ffffffff810a1f40)
Location: kernel/task_work.c:27
Inline: False
Direct callers:
  - kernel/sched/fair.c:task_tick_numa
  - kernel/irq/manage.c:irq_thread
  - kernel/events/uprobes.c:uprobe_copy_process
  - security/keys/keyctl.c:keyctl_session_to_parent
  - security/yama/yama_lsm.c:report_access
```
**Symbols:**

```
ffffffff810a1f40-ffffffff810a1f8f: task_work_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int task_work_add(struct task_struct *task, struct callback_head *work, bool notify);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/task_work.c (ffffffff810a7000)
Location: kernel/task_work.c:27
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_tasks_write
  - kernel/sched/fair.c:task_tick_numa
  - kernel/irq/manage.c:irq_thread
  - kernel/events/uprobes.c:uprobe_copy_process
  - security/keys/keyctl.c:keyctl_session_to_parent
  - security/yama/yama_lsm.c:report_access
```
**Symbols:**

```
ffffffff810a7000-ffffffff810a704a: task_work_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int task_work_add(struct task_struct *task, struct callback_head *work, bool notify);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/task_work.c (ffffffff810a3f50)
Location: kernel/task_work.c:27
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_tasks_write
  - kernel/sched/fair.c:task_tick_numa
  - kernel/irq/manage.c:irq_thread
  - kernel/events/uprobes.c:uprobe_copy_process
  - security/keys/keyctl.c:keyctl_session_to_parent
  - security/yama/yama_lsm.c:report_access
```
**Symbols:**

```
ffffffff810a3f50-ffffffff810a3f9a: task_work_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int task_work_add(struct task_struct *task, struct callback_head *work, bool notify);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/task_work.c (ffffffff810aa560)
Location: kernel/task_work.c:28
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_tasks_write
  - kernel/sched/fair.c:task_tick_numa
  - kernel/irq/manage.c:irq_thread
  - kernel/events/uprobes.c:uprobe_copy_process
  - security/keys/keyctl.c:keyctl_session_to_parent
  - security/yama/yama_lsm.c:report_access
```
**Symbols:**

```
ffffffff810aa560-ffffffff810aa5c2: task_work_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int task_work_add(struct task_struct *task, struct callback_head *work, bool notify);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/task_work.c (ffffffff810b1190)
Location: kernel/task_work.c:28
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdtgroup_tasks_write
  - kernel/sched/fair.c:task_tick_numa
  - kernel/irq/manage.c:irq_thread
  - kernel/events/uprobes.c:uprobe_copy_process
  - security/keys/keyctl.c:keyctl_session_to_parent
  - security/yama/yama_lsm.c:report_access
```
**Symbols:**

```
ffffffff810b1190-ffffffff810b11f3: task_work_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int task_work_add(struct task_struct *task, struct callback_head *work, bool notify);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/task_work.c (ffffffff810ba210)
Location: kernel/task_work.c:28
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
  - kernel/sched/fair.c:task_tick_numa
  - kernel/irq/manage.c:irq_thread
  - kernel/events/uprobes.c:uprobe_copy_process
  - security/keys/keyctl.c:keyctl_session_to_parent
  - security/yama/yama_lsm.c:report_access
```
**Symbols:**

```
ffffffff810ba210-ffffffff810ba273: task_work_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int task_work_add(struct task_struct *task, struct callback_head *work, bool notify);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/task_work.c (ffffffff810c0130)
Location: kernel/task_work.c:28
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
  - kernel/sched/fair.c:task_tick_fair
  - kernel/irq/manage.c:irq_thread
  - kernel/events/uprobes.c:uprobe_copy_process
  - fs/file_table.c:fput_many
  - fs/namespace.c:mntput_no_expire
  - security/keys/keyctl.c:keyctl_session_to_parent
  - security/yama/yama_lsm.c:report_access
```
**Symbols:**

```
ffffffff810c0130-ffffffff810c017b: task_work_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int task_work_add(struct task_struct *task, struct callback_head *work, bool notify);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/task_work.c (ffffffff810c64f0)
Location: kernel/task_work.c:28
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
  - kernel/sched/fair.c:task_tick_fair
  - kernel/irq/manage.c:irq_thread
  - kernel/events/uprobes.c:uprobe_copy_process
  - fs/file_table.c:fput_many
  - fs/namespace.c:mntput_no_expire
  - security/keys/keyctl.c:keyctl_session_to_parent
  - security/yama/yama_lsm.c:report_access
```
**Symbols:**

```
ffffffff810c64f0-ffffffff810c653b: task_work_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int task_work_add(struct task_struct *task, struct callback_head *work, int notify);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/task_work.c (ffffffff810ce4d0)
Location: kernel/task_work.c:28
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:do_machine_check
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:__rdtgroup_move_task
  - kernel/sched/fair.c:task_tick_fair
  - kernel/irq/manage.c:irq_thread
  - kernel/events/uprobes.c:uprobe_copy_process
  - fs/namespace.c:mntput_no_expire
  - fs/io_uring.c:__io_async_wake
  - fs/io_uring.c:__io_async_wake
  - security/keys/keyctl.c:keyctl_session_to_parent
  - security/yama/yama_lsm.c:report_access
  - drivers/acpi/apei/ghes.c:ghes_proc_in_irq
```
**Symbols:**

```
ffffffff810ce4d0-ffffffff810ce59c: task_work_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int task_work_add(struct task_struct *task, struct callback_head *work, enum task_work_notify_mode notify);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/task_work.c (ffffffff810c9030)
Location: kernel/task_work.c:32
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:queue_task_work
  - kernel/sched/fair.c:task_tick_fair
  - kernel/irq/manage.c:irq_thread
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/events/uprobes.c:uprobe_copy_process
  - fs/namespace.c:mntput_no_expire
  - fs/io_uring.c:io_link_timeout_fn
  - fs/io_uring.c:io_link_timeout_fn
  - fs/io_uring.c:io_wq_submit_work
  - fs/io_uring.c:io_timeout_cancel
  - fs/io_uring.c:io_poll_remove_one
  - fs/io_uring.c:__io_async_wake
  - fs/io_uring.c:io_async_buf_func
  - fs/io_uring.c:io_put_req_deferred_cb
  - fs/io_uring.c:io_req_free_batch
  - fs/io_uring.c:__io_req_task_cancel
  - fs/io_uring.c:io_req_task_work_add
  - fs/io_uring.c:io_fail_links
  - fs/io_uring.c:io_fail_links
  - fs/io_uring.c:io_commit_cqring
  - fs/io_uring.c:io_flush_timeouts
  - fs/io_uring.c:io_kill_timeouts
  - security/keys/keyctl.c:keyctl_session_to_parent
  - security/yama/yama_lsm.c:report_access
  - drivers/acpi/apei/ghes.c:ghes_proc_in_irq
```
**Symbols:**

```
ffffffff810c9030-ffffffff810c90b6: task_work_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int task_work_add(struct task_struct *task, struct callback_head *work, enum task_work_notify_mode notify);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/task_work.c (ffffffff810caa30)
Location: kernel/task_work.c:32
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:queue_task_work
  - kernel/sched/fair.c:task_tick_fair
  - kernel/irq/manage.c:irq_thread
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/events/uprobes.c:uprobe_copy_process
  - fs/namespace.c:mntput_no_expire
  - fs/io_uring.c:io_ring_exit_work
  - fs/io_uring.c:io_req_task_work_add
  - security/keys/keyctl.c:keyctl_session_to_parent
  - security/yama/yama_lsm.c:report_access
  - drivers/acpi/apei/ghes.c:ghes_proc_in_irq
```
**Symbols:**

```
ffffffff810caa30-ffffffff810caab2: task_work_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int task_work_add(struct task_struct *task, struct callback_head *work, enum task_work_notify_mode notify);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/task_work.c (ffffffff810ddbb0)
Location: kernel/task_work.c:32
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:queue_task_work
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
  - kernel/sched/fair.c:task_tick_fair
  - kernel/irq/manage.c:irq_thread
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/events/uprobes.c:uprobe_copy_process
  - fs/namespace.c:mntput_no_expire
  - fs/io_uring.c:io_ring_exit_work
  - fs/io_uring.c:io_req_task_work_add
  - fs/io-wq.c:io_queue_worker_create
  - security/keys/keyctl.c:keyctl_session_to_parent
  - security/yama/yama_lsm.c:report_access
  - drivers/acpi/apei/ghes.c:ghes_proc_in_irq
```
**Symbols:**

```
ffffffff810ddbb0-ffffffff810ddc32: task_work_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int task_work_add(struct task_struct *task, struct callback_head *work, enum task_work_notify_mode notify);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/task_work.c (ffffffff810f7700)
Location: kernel/task_work.c:42
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:queue_task_work
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
  - kernel/sched/fair.c:task_tick_fair
  - kernel/irq/manage.c:irq_thread
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/events/uprobes.c:uprobe_copy_process
  - fs/namespace.c:mntput_no_expire
  - security/keys/keyctl.c:keyctl_session_to_parent
  - security/yama/yama_lsm.c:report_access
  - io_uring/io_uring.c:io_ring_exit_work
  - io_uring/io_uring.c:__io_req_task_work_add
  - io_uring/io-wq.c:io_queue_worker_create
  - drivers/acpi/apei/ghes.c:ghes_proc_in_irq
```
**Symbols:**

```
ffffffff810f7700-ffffffff810f77a8: task_work_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int task_work_add(struct task_struct *task, struct callback_head *work, enum task_work_notify_mode notify);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/task_work.c (ffffffff81119ea0)
Location: kernel/task_work.c:42
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:queue_task_work
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
  - kernel/sched/fair.c:task_tick_fair
  - kernel/irq/manage.c:irq_thread
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/events/core.c:event_sched_out
  - kernel/events/uprobes.c:uprobe_copy_process
  - fs/namespace.c:mntput_no_expire
  - security/keys/keyctl.c:keyctl_session_to_parent
  - security/yama/yama_lsm.c:report_access
  - io_uring/io_uring.c:io_ring_exit_work
  - io_uring/io_uring.c:__io_req_task_work_add
  - io_uring/msg_ring.c:io_msg_ring
  - io_uring/msg_ring.c:io_msg_ring
  - io_uring/rsrc.c:io_rsrc_node_ref_zero
  - io_uring/io-wq.c:io_queue_worker_create
  - drivers/acpi/apei/ghes.c:ghes_proc_in_irq
```
**Symbols:**

```
ffffffff81119ea0-ffffffff81119f59: task_work_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int task_work_add(struct task_struct *task, struct callback_head *work, enum task_work_notify_mode notify);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/task_work.c (ffffffff81127110)
Location: kernel/task_work.c:42
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:queue_task_work
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
  - kernel/sched/core.c:task_tick_mm_cid
  - kernel/sched/fair.c:task_tick_fair
  - kernel/irq/manage.c:irq_thread
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/events/core.c:event_sched_out
  - kernel/events/uprobes.c:uprobe_copy_process
  - fs/namespace.c:mntput_no_expire
  - security/keys/keyctl.c:keyctl_session_to_parent
  - security/yama/yama_lsm.c:report_access
  - io_uring/io_uring.c:io_ring_exit_work
  - io_uring/io_uring.c:io_activate_pollwq
  - io_uring/io_uring.c:io_req_normal_work_add
  - io_uring/msg_ring.c:io_msg_send_fd
  - io_uring/msg_ring.c:io_msg_ring_data
  - io_uring/io-wq.c:io_queue_worker_create
  - drivers/acpi/apei/ghes.c:ghes_proc_in_irq
```
**Symbols:**

```
ffffffff81127110-ffffffff811271cb: task_work_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int task_work_add(struct task_struct *task, struct callback_head *work, enum task_work_notify_mode notify);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/task_work.c (ffffffff811316f0)
Location: kernel/task_work.c:42
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/core.c:queue_task_work
  - arch/x86/mm/tlb.c:switch_mm_irqs_off
  - kernel/sched/core.c:task_tick_mm_cid
  - kernel/sched/fair.c:task_tick_fair
  - kernel/irq/manage.c:irq_thread
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/events/core.c:event_sched_out
  - kernel/events/uprobes.c:uprobe_copy_process
  - fs/namespace.c:mntput_no_expire
  - security/keys/keyctl.c:keyctl_session_to_parent
  - security/yama/yama_lsm.c:report_access
  - io_uring/io_uring.c:io_ring_exit_work
  - io_uring/io_uring.c:io_activate_pollwq
  - io_uring/io_uring.c:io_req_normal_work_add
  - io_uring/msg_ring.c:io_msg_send_fd
  - io_uring/msg_ring.c:io_msg_ring_data
  - io_uring/io-wq.c:io_queue_worker_create
  - drivers/acpi/apei/ghes.c:ghes_proc_in_irq
```
**Symbols:**

```
ffffffff811316f0-ffffffff811317ab: task_work_add (STB_GLOBAL)
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
int task_work_add(struct task_struct *task, struct callback_head *work, bool notify);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/task_work.c (ffff800010124f00)
Location: kernel/task_work.c:28
Inline: False
Direct callers:
  - kernel/sched/fair.c:task_tick_fair
  - kernel/irq/manage.c:irq_thread
  - kernel/events/uprobes.c:uprobe_copy_process
  - fs/file_table.c:fput_many
  - fs/namespace.c:mntput_no_expire
  - security/keys/keyctl.c:keyctl_session_to_parent
  - security/yama/yama_lsm.c:report_access
```
**Symbols:**

```
ffff800010124f00-ffff800010124ff4: task_work_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int task_work_add(struct task_struct *task, struct callback_head *work, bool notify);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/task_work.c (c0377e88)
Location: kernel/task_work.c:28
Inline: False
Direct callers:
  - kernel/irq/manage.c:irq_thread
  - kernel/events/uprobes.c:uprobe_copy_process
  - fs/namespace.c:mntput_no_expire
  - security/keys/keyctl.c:keyctl_session_to_parent
  - security/yama/yama_lsm.c:report_access
```
**Symbols:**

```
c0377e88-c0377f28: task_work_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int task_work_add(struct task_struct *task, struct callback_head *work, bool notify);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/task_work.c (c00000000016ebb0)
Location: kernel/task_work.c:28
Inline: False
Direct callers:
  - kernel/sched/fair.c:task_tick_fair
  - kernel/irq/manage.c:irq_thread
  - kernel/events/uprobes.c:uprobe_copy_process
  - fs/file_table.c:fput_many
  - fs/namespace.c:mntput_no_expire
  - security/keys/keyctl.c:keyctl_session_to_parent
  - security/yama/yama_lsm.c:report_access
```
**Symbols:**

```
c00000000016ebb0-c00000000016ec70: task_work_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int task_work_add(struct task_struct *task, struct callback_head *work, bool notify);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/task_work.c (ffffffe0000dce82)
Location: kernel/task_work.c:28
Inline: True
Direct callers:
  - kernel/irq/manage.c:irq_thread
  - fs/file_table.c:fput_many
  - fs/namespace.c:mntput_no_expire
  - security/keys/keyctl.c:keyctl_session_to_parent
  - security/yama/yama_lsm.c:report_access
```
**Symbols:**

```
ffffffe0000dce82-ffffffe0000dcf08: task_work_add (STB_GLOBAL)
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
int task_work_add(struct task_struct *task, struct callback_head *work, bool notify);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/task_work.c (ffffffff810c0870)
Location: kernel/task_work.c:28
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
  - kernel/sched/fair.c:task_tick_fair
  - kernel/irq/manage.c:irq_thread
  - kernel/events/uprobes.c:uprobe_copy_process
  - fs/file_table.c:fput_many
  - fs/namespace.c:mntput_no_expire
  - security/keys/keyctl.c:keyctl_session_to_parent
  - security/yama/yama_lsm.c:report_access
```
**Symbols:**

```
ffffffff810c0870-ffffffff810c08bb: task_work_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int task_work_add(struct task_struct *task, struct callback_head *work, bool notify);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/task_work.c (ffffffff810af070)
Location: kernel/task_work.c:28
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
  - kernel/sched/fair.c:task_tick_fair
  - kernel/irq/manage.c:irq_thread
  - kernel/events/uprobes.c:uprobe_copy_process
  - fs/file_table.c:fput_many
  - fs/namespace.c:mntput_no_expire
  - security/keys/keyctl.c:keyctl_session_to_parent
  - security/yama/yama_lsm.c:report_access
```
**Symbols:**

```
ffffffff810af070-ffffffff810af0bb: task_work_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int task_work_add(struct task_struct *task, struct callback_head *work, bool notify);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/task_work.c (ffffffff810bfdc0)
Location: kernel/task_work.c:28
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
  - kernel/sched/fair.c:task_tick_fair
  - kernel/irq/manage.c:irq_thread
  - kernel/events/uprobes.c:uprobe_copy_process
  - fs/file_table.c:fput_many
  - fs/namespace.c:mntput_no_expire
  - security/keys/keyctl.c:keyctl_session_to_parent
  - security/yama/yama_lsm.c:report_access
```
**Symbols:**

```
ffffffff810bfdc0-ffffffff810bfe0b: task_work_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int task_work_add(struct task_struct *task, struct callback_head *work, bool notify);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/task_work.c (ffffffff810c82a0)
Location: kernel/task_work.c:28
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_tasks_write
  - kernel/sched/fair.c:task_tick_fair
  - kernel/irq/manage.c:irq_thread
  - kernel/events/uprobes.c:uprobe_copy_process
  - fs/file_table.c:fput_many
  - fs/namespace.c:mntput_no_expire
  - security/keys/keyctl.c:keyctl_session_to_parent
  - security/yama/yama_lsm.c:report_access
```
**Symbols:**

```
ffffffff810c82a0-ffffffff810c82eb: task_work_add (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>bool notify</code> ➡️ <code>int notify</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>int notify</code> ➡️ <code>enum task_work_notify_mode notify</code>
</li>
</ul>
</details>
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
