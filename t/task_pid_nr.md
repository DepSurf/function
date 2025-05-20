# Function: <code>task_pid_nr</code>

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
In init/main.c (0)
Location: include/linux/sched.h:1915
Inline: True
```
```
In arch/x86/entry/vsyscall/vsyscall_64.c (0)
Location: include/linux/sched.h:1915
Inline: True
```
```
In arch/x86/kernel/signal.c (0)
Location: include/linux/sched.h:1915
Inline: True
```
```
In arch/x86/kernel/traps.c (0)
Location: include/linux/sched.h:1915
Inline: True
```
```
In arch/x86/mm/fault.c (ffffffff8106b0e3)
Location: include/linux/sched.h:1915
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:__bad_area_nosemaphore
```
```
In arch/x86/net/bpf_jit_comp.c (0)
Location: include/linux/sched.h:1915
Inline: True
```
```
In kernel/cpu.c (0)
Location: include/linux/sched.h:1915
Inline: True
```
```
In kernel/exit.c (0)
Location: include/linux/sched.h:1915
Inline: True
```
```
In kernel/workqueue.c (ffffffff8118bb3f)
Location: include/linux/sched.h:1915
Inline: True
Inline callers:
  - kernel/workqueue.c:show_workqueue_state
  - kernel/workqueue.c:show_workqueue_state
  - kernel/workqueue.c:show_workqueue_state
```
```
In kernel/async.c (0)
Location: include/linux/sched.h:1915
Inline: True
```
```
In kernel/sched/core.c (ffffffff810a568c)
Location: include/linux/sched.h:1915
Inline: True
Inline callers:
  - kernel/sched/core.c:trace_event_raw_event_sched_swap_numa
  - kernel/sched/core.c:trace_event_raw_event_sched_swap_numa
  - kernel/sched/core.c:perf_trace_sched_move_task_template
  - kernel/sched/core.c:perf_trace_sched_swap_numa
  - kernel/sched/core.c:perf_trace_sched_swap_numa
  - kernel/sched/core.c:trace_event_raw_event_sched_move_task_template
  - kernel/sched/core.c:sched_show_task
```
```
In kernel/sched/debug.c (ffffffff810c672f)
Location: include/linux/sched.h:1915
Inline: True
Inline callers:
  - kernel/sched/debug.c:print_cpu
  - kernel/sched/debug.c:print_cpu
```
```
In kernel/locking/rtmutex.c (0)
Location: include/linux/sched.h:1915
Inline: True
```
```
In kernel/printk/printk.c (0)
Location: include/linux/sched.h:1915
Inline: True
```
```
In kernel/time/posix-cpu-timers.c (0)
Location: include/linux/sched.h:1915
Inline: True
```
```
In kernel/audit.c (ffffffff81122a84)
Location: include/linux/sched.h:1915
Inline: True
```
```
In kernel/auditfilter.c (0)
Location: include/linux/sched.h:1915
Inline: True
```
```
In kernel/auditsc.c (ffffffff811293dc)
Location: include/linux/sched.h:1915
Inline: True
Inline callers:
  - kernel/auditsc.c:__audit_ptrace
  - kernel/auditsc.c:__audit_log_capset
```
```
In kernel/watchdog.c (0)
Location: include/linux/sched.h:1915
Inline: True
```
```
In mm/oom_kill.c (0)
Location: include/linux/sched.h:1915
Inline: True
```
```
In fs/fs-writeback.c (0)
Location: include/linux/sched.h:1915
Inline: True
```
```
In fs/coredump.c (0)
Location: include/linux/sched.h:1915
Inline: True
```
```
In fs/drop_caches.c (0)
Location: include/linux/sched.h:1915
Inline: True
```
```
In fs/proc/base.c (ffffffff8127d50b)
Location: include/linux/sched.h:1915
Inline: True
Inline callers:
  - fs/proc/base.c:oom_adj_write
```
```
In ipc/sem.c (0)
Location: include/linux/sched.h:1915
Inline: True
```
```
In security/lsm_audit.c (ffffffff813666bb)
Location: include/linux/sched.h:1915
Inline: True
Inline callers:
  - security/lsm_audit.c:common_lsm_audit
```
```
In security/tomoyo/audit.c (ffffffff81366bb3)
Location: include/linux/sched.h:1915
Inline: True
Inline callers:
  - security/tomoyo/audit.c:tomoyo_init_log
```
```
In security/integrity/integrity_audit.c (0)
Location: include/linux/sched.h:1915
Inline: True
```
```
In block/blk-core.c (0)
Location: include/linux/sched.h:1915
Inline: True
```
```
In drivers/pci/quirks.c (0)
Location: include/linux/sched.h:1915
Inline: True
```
```
In drivers/tty/tty_io.c (0)
Location: include/linux/sched.h:1915
Inline: True
```
```
In drivers/tty/tty_audit.c (ffffffff814ece39)
Location: include/linux/sched.h:1915
Inline: True
Inline callers:
  - drivers/tty/tty_audit.c:tty_audit_log
```
```
In drivers/base/power/main.c (ffffffff815585ea)
Location: include/linux/sched.h:1915
Inline: True
Inline callers:
  - drivers/base/power/main.c:initcall_debug_start
```
```
In drivers/cdrom/cdrom.c (0)
Location: include/linux/sched.h:1915
Inline: True
```
```
In drivers/usb/core/devio.c (0)
Location: include/linux/sched.h:1915
Inline: True
```
```
In drivers/md/md.c (ffffffff8168f678)
Location: include/linux/sched.h:1915
Inline: True
Inline callers:
  - drivers/md/md.c:md_unregister_thread
```
```
In net/core/sock.c (0)
Location: include/linux/sched.h:1915
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
In init/main.c (0)
Location: include/linux/sched.h:2054
Inline: True
```
```
In arch/x86/entry/vsyscall/vsyscall_64.c (0)
Location: include/linux/sched.h:2054
Inline: True
```
```
In arch/x86/kernel/signal.c (0)
Location: include/linux/sched.h:2054
Inline: True
```
```
In arch/x86/kernel/traps.c (0)
Location: include/linux/sched.h:2054
Inline: True
```
```
In arch/x86/mm/fault.c (ffffffff8106ae19)
Location: include/linux/sched.h:2054
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:__bad_area_nosemaphore
```
```
In arch/x86/net/bpf_jit_comp.c (0)
Location: include/linux/sched.h:2054
Inline: True
```
```
In kernel/cpu.c (0)
Location: include/linux/sched.h:2054
Inline: True
```
```
In kernel/exit.c (0)
Location: include/linux/sched.h:2054
Inline: True
```
```
In kernel/workqueue.c (ffffffff810a0066)
Location: include/linux/sched.h:2054
Inline: True
Inline callers:
  - kernel/workqueue.c:show_workqueue_state
  - kernel/workqueue.c:show_workqueue_state
  - kernel/workqueue.c:show_workqueue_state
```
```
In kernel/async.c (0)
Location: include/linux/sched.h:2054
Inline: True
```
```
In kernel/sched/core.c (ffffffff810b0e3e)
Location: include/linux/sched.h:2054
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_show_task
  - kernel/sched/core.c:perf_trace_sched_swap_numa
  - kernel/sched/core.c:perf_trace_sched_swap_numa
  - kernel/sched/core.c:perf_trace_sched_move_task_template
  - kernel/sched/core.c:trace_event_raw_event_sched_swap_numa
  - kernel/sched/core.c:trace_event_raw_event_sched_swap_numa
  - kernel/sched/core.c:trace_event_raw_event_sched_move_task_template
```
```
In kernel/sched/debug.c (ffffffff810ca683)
Location: include/linux/sched.h:2054
Inline: True
Inline callers:
  - kernel/sched/debug.c:print_cpu
  - kernel/sched/debug.c:print_cpu
```
```
In kernel/locking/rtmutex.c (0)
Location: include/linux/sched.h:2054
Inline: True
```
```
In kernel/printk/printk.c (0)
Location: include/linux/sched.h:2054
Inline: True
```
```
In kernel/time/posix-cpu-timers.c (0)
Location: include/linux/sched.h:2054
Inline: True
```
```
In kernel/audit.c (ffffffff8112aa2c)
Location: include/linux/sched.h:2054
Inline: True
```
```
In kernel/auditfilter.c (0)
Location: include/linux/sched.h:2054
Inline: True
```
```
In kernel/auditsc.c (ffffffff81131986)
Location: include/linux/sched.h:2054
Inline: True
Inline callers:
  - kernel/auditsc.c:__audit_log_capset
  - kernel/auditsc.c:__audit_ptrace
```
```
In kernel/watchdog.c (0)
Location: include/linux/sched.h:2054
Inline: True
```
```
In kernel/trace/bpf_trace.c (0)
Location: include/linux/sched.h:2054
Inline: True
```
```
In mm/oom_kill.c (0)
Location: include/linux/sched.h:2054
Inline: True
```
```
In fs/fs-writeback.c (0)
Location: include/linux/sched.h:2054
Inline: True
```
```
In fs/coredump.c (0)
Location: include/linux/sched.h:2054
Inline: True
```
```
In fs/drop_caches.c (0)
Location: include/linux/sched.h:2054
Inline: True
```
```
In fs/proc/base.c (ffffffff812a9cdd)
Location: include/linux/sched.h:2054
Inline: True
Inline callers:
  - fs/proc/base.c:__set_oom_adj
```
```
In ipc/sem.c (0)
Location: include/linux/sched.h:2054
Inline: True
```
```
In security/selinux/hooks.c (0)
Location: include/linux/sched.h:2054
Inline: True
```
```
In security/lsm_audit.c (ffffffff8139c845)
Location: include/linux/sched.h:2054
Inline: True
Inline callers:
  - security/lsm_audit.c:common_lsm_audit
```
```
In security/tomoyo/audit.c (ffffffff8139cc53)
Location: include/linux/sched.h:2054
Inline: True
Inline callers:
  - security/tomoyo/audit.c:tomoyo_init_log
```
```
In security/integrity/integrity_audit.c (0)
Location: include/linux/sched.h:2054
Inline: True
```
```
In block/blk-core.c (0)
Location: include/linux/sched.h:2054
Inline: True
```
```
In drivers/pci/quirks.c (0)
Location: include/linux/sched.h:2054
Inline: True
```
```
In drivers/tty/tty_io.c (ffffffff81534a16)
Location: include/linux/sched.h:2054
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:__do_SAK
  - drivers/tty/tty_io.c:__do_SAK
  - drivers/tty/tty_io.c:__do_SAK
```
```
In drivers/tty/tty_audit.c (ffffffff8153de30)
Location: include/linux/sched.h:2054
Inline: True
Inline callers:
  - drivers/tty/tty_audit.c:tty_audit_log
```
```
In drivers/base/power/main.c (ffffffff815aa89a)
Location: include/linux/sched.h:2054
Inline: True
Inline callers:
  - drivers/base/power/main.c:initcall_debug_start
```
```
In drivers/cdrom/cdrom.c (0)
Location: include/linux/sched.h:2054
Inline: True
```
```
In drivers/usb/core/devio.c (0)
Location: include/linux/sched.h:2054
Inline: True
```
```
In drivers/md/md.c (ffffffff816f0484)
Location: include/linux/sched.h:2054
Inline: True
Inline callers:
  - drivers/md/md.c:md_unregister_thread
```
```
In net/core/sock.c (0)
Location: include/linux/sched.h:2054
Inline: True
```
```
In net/ipv4/tcp.c (0)
Location: include/linux/sched.h:2054
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
In init/main.c (0)
Location: include/linux/sched.h:2141
Inline: True
```
```
In arch/x86/entry/vsyscall/vsyscall_64.c (0)
Location: include/linux/sched.h:2141
Inline: True
```
```
In arch/x86/kernel/signal.c (0)
Location: include/linux/sched.h:2141
Inline: True
```
```
In arch/x86/kernel/traps.c (0)
Location: include/linux/sched.h:2141
Inline: True
```
```
In arch/x86/mm/fault.c (ffffffff8106ea29)
Location: include/linux/sched.h:2141
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:__bad_area_nosemaphore
```
```
In arch/x86/net/bpf_jit_comp.c (0)
Location: include/linux/sched.h:2141
Inline: True
```
```
In kernel/exit.c (0)
Location: include/linux/sched.h:2141
Inline: True
```
```
In kernel/workqueue.c (ffffffff810a4f36)
Location: include/linux/sched.h:2141
Inline: True
Inline callers:
  - kernel/workqueue.c:show_workqueue_state
  - kernel/workqueue.c:show_workqueue_state
  - kernel/workqueue.c:show_workqueue_state
```
```
In kernel/async.c (0)
Location: include/linux/sched.h:2141
Inline: True
```
```
In kernel/sched/core.c (ffffffff810b70cd)
Location: include/linux/sched.h:2141
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_show_task
  - kernel/sched/core.c:perf_trace_sched_swap_numa
  - kernel/sched/core.c:perf_trace_sched_swap_numa
  - kernel/sched/core.c:perf_trace_sched_move_task_template
  - kernel/sched/core.c:trace_event_raw_event_sched_swap_numa
  - kernel/sched/core.c:trace_event_raw_event_sched_swap_numa
  - kernel/sched/core.c:trace_event_raw_event_sched_move_task_template
```
```
In kernel/sched/debug.c (ffffffff810d06b3)
Location: include/linux/sched.h:2141
Inline: True
Inline callers:
  - kernel/sched/debug.c:print_cpu
  - kernel/sched/debug.c:print_cpu
```
```
In kernel/locking/rtmutex.c (0)
Location: include/linux/sched.h:2141
Inline: True
```
```
In kernel/printk/printk.c (0)
Location: include/linux/sched.h:2141
Inline: True
```
```
In kernel/time/posix-cpu-timers.c (0)
Location: include/linux/sched.h:2141
Inline: True
```
```
In kernel/auditfilter.c (0)
Location: include/linux/sched.h:2141
Inline: True
```
```
In kernel/watchdog.c (0)
Location: include/linux/sched.h:2141
Inline: True
```
```
In kernel/trace/bpf_trace.c (0)
Location: include/linux/sched.h:2141
Inline: True
```
```
In mm/oom_kill.c (0)
Location: include/linux/sched.h:2141
Inline: True
```
```
In fs/fs-writeback.c (0)
Location: include/linux/sched.h:2141
Inline: True
```
```
In fs/coredump.c (0)
Location: include/linux/sched.h:2141
Inline: True
```
```
In fs/drop_caches.c (0)
Location: include/linux/sched.h:2141
Inline: True
```
```
In fs/proc/base.c (ffffffff812bf5fd)
Location: include/linux/sched.h:2141
Inline: True
Inline callers:
  - fs/proc/base.c:__set_oom_adj
```
```
In ipc/sem.c (0)
Location: include/linux/sched.h:2141
Inline: True
```
```
In security/selinux/hooks.c (0)
Location: include/linux/sched.h:2141
Inline: True
```
```
In security/tomoyo/audit.c (ffffffff813b3833)
Location: include/linux/sched.h:2141
Inline: True
Inline callers:
  - security/tomoyo/audit.c:tomoyo_init_log
```
```
In security/integrity/integrity_audit.c (0)
Location: include/linux/sched.h:2141
Inline: True
```
```
In block/blk-core.c (0)
Location: include/linux/sched.h:2141
Inline: True
```
```
In drivers/pci/quirks.c (0)
Location: include/linux/sched.h:2141
Inline: True
```
```
In drivers/tty/tty_io.c (ffffffff81561146)
Location: include/linux/sched.h:2141
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:__do_SAK
  - drivers/tty/tty_io.c:__do_SAK
  - drivers/tty/tty_io.c:__do_SAK
```
```
In drivers/tty/tty_audit.c (ffffffff8156a480)
Location: include/linux/sched.h:2141
Inline: True
Inline callers:
  - drivers/tty/tty_audit.c:tty_audit_log
```
```
In drivers/base/power/main.c (ffffffff815d97be)
Location: include/linux/sched.h:2141
Inline: True
```
```
In drivers/cdrom/cdrom.c (0)
Location: include/linux/sched.h:2141
Inline: True
```
```
In drivers/usb/core/devio.c (0)
Location: include/linux/sched.h:2141
Inline: True
```
```
In drivers/md/md.c (ffffffff81721d44)
Location: include/linux/sched.h:2141
Inline: True
Inline callers:
  - drivers/md/md.c:md_unregister_thread
```
```
In net/core/sock.c (0)
Location: include/linux/sched.h:2141
Inline: True
```
```
In net/ipv4/tcp.c (0)
Location: include/linux/sched.h:2141
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
In init/main.c (0)
Location: include/linux/sched.h:1146
Inline: True
```
```
In arch/x86/entry/vsyscall/vsyscall_64.c (0)
Location: include/linux/sched.h:1146
Inline: True
```
```
In arch/x86/kernel/signal.c (0)
Location: include/linux/sched.h:1146
Inline: True
```
```
In arch/x86/kernel/traps.c (0)
Location: include/linux/sched.h:1146
Inline: True
```
```
In arch/x86/mm/fault.c (ffffffff8106e1b2)
Location: include/linux/sched.h:1146
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:__bad_area_nosemaphore
```
```
In arch/x86/net/bpf_jit_comp.c (0)
Location: include/linux/sched.h:1146
Inline: True
```
```
In kernel/exit.c (0)
Location: include/linux/sched.h:1146
Inline: True
```
```
In kernel/workqueue.c (ffffffff810a20e3)
Location: include/linux/sched.h:1146
Inline: True
Inline callers:
  - kernel/workqueue.c:show_workqueue_state
  - kernel/workqueue.c:show_workqueue_state
  - kernel/workqueue.c:show_workqueue_state
```
```
In kernel/async.c (0)
Location: include/linux/sched.h:1146
Inline: True
```
```
In kernel/sched/core.c (ffffffff810ac32e)
Location: include/linux/sched.h:1146
Inline: True
Inline callers:
  - kernel/sched/core.c:perf_trace_sched_swap_numa
  - kernel/sched/core.c:perf_trace_sched_swap_numa
  - kernel/sched/core.c:perf_trace_sched_move_task_template
  - kernel/sched/core.c:trace_event_raw_event_sched_swap_numa
  - kernel/sched/core.c:trace_event_raw_event_sched_swap_numa
  - kernel/sched/core.c:trace_event_raw_event_sched_move_task_template
```
```
In kernel/sched/debug.c (ffffffff810cf723)
Location: include/linux/sched.h:1146
Inline: True
Inline callers:
  - kernel/sched/debug.c:print_cpu
  - kernel/sched/debug.c:print_cpu
```
```
In kernel/locking/rtmutex.c (0)
Location: include/linux/sched.h:1146
Inline: True
```
```
In kernel/printk/printk.c (0)
Location: include/linux/sched.h:1146
Inline: True
```
```
In kernel/time/posix-cpu-timers.c (0)
Location: include/linux/sched.h:1146
Inline: True
```
```
In kernel/auditfilter.c (0)
Location: include/linux/sched.h:1146
Inline: True
```
```
In kernel/watchdog.c (0)
Location: include/linux/sched.h:1146
Inline: True
```
```
In kernel/trace/bpf_trace.c (0)
Location: include/linux/sched.h:1146
Inline: True
```
```
In mm/oom_kill.c (0)
Location: include/linux/sched.h:1146
Inline: True
```
```
In fs/fs-writeback.c (0)
Location: include/linux/sched.h:1146
Inline: True
```
```
In fs/coredump.c (0)
Location: include/linux/sched.h:1146
Inline: True
```
```
In fs/drop_caches.c (0)
Location: include/linux/sched.h:1146
Inline: True
```
```
In fs/proc/base.c (ffffffff812cc1ea)
Location: include/linux/sched.h:1146
Inline: True
Inline callers:
  - fs/proc/base.c:__set_oom_adj
```
```
In ipc/sem.c (0)
Location: include/linux/sched.h:1146
Inline: True
```
```
In security/selinux/hooks.c (0)
Location: include/linux/sched.h:1146
Inline: True
```
```
In security/tomoyo/audit.c (ffffffff813ca1f2)
Location: include/linux/sched.h:1146
Inline: True
Inline callers:
  - security/tomoyo/audit.c:tomoyo_init_log
```
```
In security/integrity/integrity_audit.c (0)
Location: include/linux/sched.h:1146
Inline: True
```
```
In block/blk-core.c (0)
Location: include/linux/sched.h:1146
Inline: True
```
```
In drivers/pci/quirks.c (0)
Location: include/linux/sched.h:1146
Inline: True
```
```
In drivers/tty/tty_io.c (ffffffff8157444a)
Location: include/linux/sched.h:1146
Inline: True
```
```
In drivers/tty/tty_audit.c (ffffffff8157eacb)
Location: include/linux/sched.h:1146
Inline: True
Inline callers:
  - drivers/tty/tty_audit.c:tty_audit_log
```
```
In drivers/base/power/main.c (ffffffff815ee1ae)
Location: include/linux/sched.h:1146
Inline: True
```
```
In drivers/cdrom/cdrom.c (0)
Location: include/linux/sched.h:1146
Inline: True
```
```
In drivers/usb/core/devio.c (0)
Location: include/linux/sched.h:1146
Inline: True
```
```
In drivers/md/md.c (ffffffff81739774)
Location: include/linux/sched.h:1146
Inline: True
Inline callers:
  - drivers/md/md.c:md_unregister_thread
```
```
In net/core/sock.c (0)
Location: include/linux/sched.h:1146
Inline: True
```
```
In net/ipv4/tcp.c (0)
Location: include/linux/sched.h:1146
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
In init/main.c (0)
Location: include/linux/sched.h:1146
Inline: True
```
```
In arch/x86/entry/vsyscall/vsyscall_64.c (0)
Location: include/linux/sched.h:1146
Inline: True
```
```
In arch/x86/kernel/signal.c (0)
Location: include/linux/sched.h:1146
Inline: True
```
```
In arch/x86/kernel/traps.c (0)
Location: include/linux/sched.h:1146
Inline: True
```
```
In arch/x86/kernel/umip.c (0)
Location: include/linux/sched.h:1146
Inline: True
```
```
In arch/x86/mm/fault.c (ffffffff810731f2)
Location: include/linux/sched.h:1146
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:__bad_area_nosemaphore
```
```
In arch/x86/net/bpf_jit_comp.c (0)
Location: include/linux/sched.h:1146
Inline: True
```
```
In kernel/panic.c (0)
Location: include/linux/sched.h:1146
Inline: True
```
```
In kernel/exit.c (0)
Location: include/linux/sched.h:1146
Inline: True
```
```
In kernel/workqueue.c (ffffffff810a8977)
Location: include/linux/sched.h:1146
Inline: True
Inline callers:
  - kernel/workqueue.c:show_workqueue_state
  - kernel/workqueue.c:show_workqueue_state
  - kernel/workqueue.c:show_workqueue_state
```
```
In kernel/async.c (0)
Location: include/linux/sched.h:1146
Inline: True
```
```
In kernel/sched/core.c (ffffffff810b3124)
Location: include/linux/sched.h:1146
Inline: True
Inline callers:
  - kernel/sched/core.c:perf_trace_sched_swap_numa
  - kernel/sched/core.c:perf_trace_sched_swap_numa
  - kernel/sched/core.c:perf_trace_sched_move_task_template
  - kernel/sched/core.c:trace_event_raw_event_sched_swap_numa
  - kernel/sched/core.c:trace_event_raw_event_sched_swap_numa
  - kernel/sched/core.c:trace_event_raw_event_sched_move_task_template
```
```
In kernel/sched/debug.c (ffffffff810d7082)
Location: include/linux/sched.h:1146
Inline: True
Inline callers:
  - kernel/sched/debug.c:print_cpu
  - kernel/sched/debug.c:print_cpu
```
```
In kernel/locking/rtmutex.c (0)
Location: include/linux/sched.h:1146
Inline: True
```
```
In kernel/printk/printk.c (0)
Location: include/linux/sched.h:1146
Inline: True
```
```
In kernel/time/posix-cpu-timers.c (0)
Location: include/linux/sched.h:1146
Inline: True
```
```
In kernel/auditfilter.c (0)
Location: include/linux/sched.h:1146
Inline: True
```
```
In kernel/watchdog.c (0)
Location: include/linux/sched.h:1146
Inline: True
```
```
In kernel/trace/bpf_trace.c (0)
Location: include/linux/sched.h:1146
Inline: True
```
```
In mm/oom_kill.c (0)
Location: include/linux/sched.h:1146
Inline: True
```
```
In fs/fs-writeback.c (0)
Location: include/linux/sched.h:1146
Inline: True
```
```
In fs/coredump.c (0)
Location: include/linux/sched.h:1146
Inline: True
```
```
In fs/drop_caches.c (0)
Location: include/linux/sched.h:1146
Inline: True
```
```
In fs/proc/base.c (ffffffff812f098b)
Location: include/linux/sched.h:1146
Inline: True
Inline callers:
  - fs/proc/base.c:__set_oom_adj
```
```
In ipc/sem.c (0)
Location: include/linux/sched.h:1146
Inline: True
```
```
In security/selinux/hooks.c (0)
Location: include/linux/sched.h:1146
Inline: True
```
```
In security/tomoyo/audit.c (ffffffff813f0692)
Location: include/linux/sched.h:1146
Inline: True
Inline callers:
  - security/tomoyo/audit.c:tomoyo_init_log
```
```
In security/integrity/integrity_audit.c (0)
Location: include/linux/sched.h:1146
Inline: True
```
```
In block/blk-core.c (0)
Location: include/linux/sched.h:1146
Inline: True
```
```
In drivers/pci/quirks.c (0)
Location: include/linux/sched.h:1146
Inline: True
```
```
In drivers/tty/tty_io.c (ffffffff815d75ca)
Location: include/linux/sched.h:1146
Inline: True
```
```
In drivers/tty/tty_audit.c (ffffffff815e363b)
Location: include/linux/sched.h:1146
Inline: True
Inline callers:
  - drivers/tty/tty_audit.c:tty_audit_log
```
```
In drivers/base/dd.c (ffffffff8164705a)
Location: include/linux/sched.h:1146
Inline: True
Inline callers:
  - drivers/base/dd.c:deferred_probe_work_func
```
```
In drivers/base/power/main.c (ffffffff8165558e)
Location: include/linux/sched.h:1146
Inline: True
```
```
In drivers/cdrom/cdrom.c (0)
Location: include/linux/sched.h:1146
Inline: True
```
```
In drivers/usb/core/devio.c (0)
Location: include/linux/sched.h:1146
Inline: True
```
```
In drivers/md/md.c (ffffffff817abef4)
Location: include/linux/sched.h:1146
Inline: True
Inline callers:
  - drivers/md/md.c:md_unregister_thread
```
```
In net/core/sock.c (0)
Location: include/linux/sched.h:1146
Inline: True
```
```
In net/ipv4/tcp.c (0)
Location: include/linux/sched.h:1146
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
In init/main.c (ffffffff81002940)
Location: include/linux/sched.h:1238
Inline: True
Inline callers:
  - init/main.c:trace_initcall_start_cb
```
```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff81005602)
Location: include/linux/sched.h:1238
Inline: True
```
```
In arch/x86/kernel/signal.c (ffffffff8102dee7)
Location: include/linux/sched.h:1238
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:signal_fault
```
```
In arch/x86/kernel/traps.c (ffffffff8102ef0f)
Location: include/linux/sched.h:1238
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:do_general_protection
```
```
In arch/x86/kernel/umip.c (ffffffff810703b3)
Location: include/linux/sched.h:1238
Inline: True
Inline callers:
  - arch/x86/kernel/umip.c:umip_printk
```
```
In arch/x86/mm/fault.c (ffffffff81075b33)
Location: include/linux/sched.h:1238
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:__bad_area_nosemaphore
  - arch/x86/mm/fault.c:__bad_area_nosemaphore
```
```
In arch/x86/net/bpf_jit_comp.c (ffffffff8108a2ba)
Location: include/linux/sched.h:1238
Inline: True
Inline callers:
  - arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile
```
```
In kernel/panic.c (ffffffff8108e91d)
Location: include/linux/sched.h:1238
Inline: True
Inline callers:
  - kernel/panic.c:refcount_error_report
```
```
In kernel/exit.c (ffffffff81094309)
Location: include/linux/sched.h:1238
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/umh.c (ffffffff810a98dd)
Location: include/linux/sched.h:1238
Inline: True
Inline callers:
  - kernel/umh.c:call_usermodehelper_exec_async
```
```
In kernel/workqueue.c (ffffffff810b05d2)
Location: include/linux/sched.h:1238
Inline: True
Inline callers:
  - kernel/workqueue.c:show_workqueue_state
  - kernel/workqueue.c:show_workqueue_state
  - kernel/workqueue.c:show_workqueue_state
  - kernel/workqueue.c:pr_cont_work
  - kernel/workqueue.c:process_one_work
```
```
In kernel/async.c (ffffffff810b674f)
Location: include/linux/sched.h:1238
Inline: True
Inline callers:
  - kernel/async.c:async_synchronize_cookie_domain
  - kernel/async.c:async_synchronize_cookie_domain
  - kernel/async.c:async_run_entry_fn
```
```
In kernel/sched/core.c (ffffffff810c2f10)
Location: include/linux/sched.h:1238
Inline: True
Inline callers:
  - kernel/sched/core.c:select_fallback_rq
  - kernel/sched/core.c:perf_trace_sched_swap_numa
  - kernel/sched/core.c:perf_trace_sched_swap_numa
  - kernel/sched/core.c:perf_trace_sched_move_task_template
  - kernel/sched/core.c:trace_event_raw_event_sched_swap_numa
  - kernel/sched/core.c:trace_event_raw_event_sched_swap_numa
  - kernel/sched/core.c:trace_event_raw_event_sched_move_task_template
```
```
In kernel/sched/debug.c (ffffffff810deb58)
Location: include/linux/sched.h:1238
Inline: True
Inline callers:
  - kernel/sched/debug.c:print_cpu
  - kernel/sched/debug.c:print_cpu
  - kernel/sched/debug.c:print_cpu
  - kernel/sched/debug.c:print_cpu
```
```
In kernel/locking/rtmutex.c (ffffffff810e6532)
Location: include/linux/sched.h:1238
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
```
```
In kernel/printk/printk.c (ffffffff810f4e56)
Location: include/linux/sched.h:1238
Inline: True
Inline callers:
  - kernel/printk/printk.c:check_syslog_permissions
```
```
In kernel/time/posix-cpu-timers.c (ffffffff811228e9)
Location: include/linux/sched.h:1238
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
```
```
In kernel/auditfilter.c (ffffffff811541af)
Location: include/linux/sched.h:1238
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_filter
```
```
In kernel/watchdog.c (ffffffff8116a765)
Location: include/linux/sched.h:1238
Inline: True
Inline callers:
  - kernel/watchdog.c:watchdog_timer_fn
```
```
In kernel/trace/bpf_trace.c (ffffffff811a6072)
Location: include/linux/sched.h:1238
Inline: True
```
```
In mm/oom_kill.c (ffffffff811f3b7e)
Location: include/linux/sched.h:1238
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_kill_process
  - mm/oom_kill.c:oom_kill_process
  - mm/oom_kill.c:oom_kill_process
  - mm/oom_kill.c:oom_kill_process
  - mm/oom_kill.c:oom_reaper
  - mm/oom_kill.c:oom_reaper
```
```
In fs/fs-writeback.c (ffffffff812c9932)
Location: include/linux/sched.h:1238
Inline: True
Inline callers:
  - fs/fs-writeback.c:block_dump___mark_inode_dirty
```
```
In fs/binfmt_elf.c (ffffffff81303524)
Location: include/linux/sched.h:1238
Inline: True
Inline callers:
  - fs/binfmt_elf.c:elf_map
```
```
In fs/compat_binfmt_elf.c (ffffffff81306c03)
Location: include/linux/sched.h:1238
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:elf_map
```
```
In fs/coredump.c (ffffffff8130cc01)
Location: include/linux/sched.h:1238
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/drop_caches.c (ffffffff8130d35e)
Location: include/linux/sched.h:1238
Inline: True
Inline callers:
  - fs/drop_caches.c:drop_caches_sysctl_handler
```
```
In fs/proc/base.c (ffffffff8131fed9)
Location: include/linux/sched.h:1238
Inline: True
Inline callers:
  - fs/proc/base.c:__set_oom_adj
  - fs/proc/base.c:__set_oom_adj
  - fs/proc/base.c:__set_oom_adj
  - fs/proc/base.c:__set_oom_adj
```
```
In ipc/sem.c (ffffffff813dd589)
Location: include/linux/sched.h:1238
Inline: True
```
```
In security/selinux/hooks.c (ffffffff81402aad)
Location: include/linux/sched.h:1238
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_netlink_send
```
```
In security/tomoyo/audit.c (ffffffff81421599)
Location: include/linux/sched.h:1238
Inline: True
Inline callers:
  - security/tomoyo/audit.c:tomoyo_init_log
```
```
In security/integrity/integrity_audit.c (ffffffff81450190)
Location: include/linux/sched.h:1238
Inline: True
Inline callers:
  - security/integrity/integrity_audit.c:integrity_audit_msg
```
```
In block/blk-core.c (ffffffff81483748)
Location: include/linux/sched.h:1238
Inline: True
Inline callers:
  - block/blk-core.c:submit_bio
```
```
In drivers/pci/quirks.c (ffffffff8152bd89)
Location: include/linux/sched.h:1238
Inline: True
Inline callers:
  - drivers/pci/quirks.c:pci_do_fixups
```
```
In drivers/tty/tty_io.c (ffffffff8161311a)
Location: include/linux/sched.h:1238
Inline: True
```
```
In drivers/tty/tty_audit.c (ffffffff8161c904)
Location: include/linux/sched.h:1238
Inline: True
Inline callers:
  - drivers/tty/tty_audit.c:tty_audit_log
```
```
In drivers/base/dd.c (ffffffff81683764)
Location: include/linux/sched.h:1238
Inline: True
Inline callers:
  - drivers/base/dd.c:deferred_probe_work_func
```
```
In drivers/base/power/main.c (ffffffff816910cd)
Location: include/linux/sched.h:1238
Inline: True
```
```
In drivers/cdrom/cdrom.c (ffffffff8174abdf)
Location: include/linux/sched.h:1238
Inline: True
Inline callers:
  - drivers/cdrom/cdrom.c:open_for_data
```
```
In drivers/usb/core/devio.c (ffffffff8176b3a3)
Location: include/linux/sched.h:1238
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_open
  - drivers/usb/core/devio.c:check_ctrlrecip
  - drivers/usb/core/devio.c:checkintf
```
```
In drivers/md/md.c (ffffffff817f698e)
Location: include/linux/sched.h:1238
Inline: True
Inline callers:
  - drivers/md/md.c:md_unregister_thread
```
```
In net/core/sock.c (ffffffff8187987b)
Location: include/linux/sched.h:1238
Inline: True
```
```
In net/ipv4/tcp.c (ffffffff818f79b2)
Location: include/linux/sched.h:1238
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
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
In init/main.c (ffffffff81002940)
Location: include/linux/sched.h:1240
Inline: True
Inline callers:
  - init/main.c:trace_initcall_start_cb
```
```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff81005502)
Location: include/linux/sched.h:1240
Inline: True
```
```
In arch/x86/kernel/signal.c (ffffffff8102f127)
Location: include/linux/sched.h:1240
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:signal_fault
```
```
In arch/x86/kernel/traps.c (ffffffff8103019c)
Location: include/linux/sched.h:1240
Inline: True
```
```
In arch/x86/kernel/umip.c (ffffffff81076389)
Location: include/linux/sched.h:1240
Inline: True
Inline callers:
  - arch/x86/kernel/umip.c:umip_printk
```
```
In arch/x86/mm/fault.c (ffffffff8107b917)
Location: include/linux/sched.h:1240
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:__bad_area_nosemaphore
  - arch/x86/mm/fault.c:__bad_area_nosemaphore
```
```
In arch/x86/net/bpf_jit_comp.c (ffffffff81092204)
Location: include/linux/sched.h:1240
Inline: True
Inline callers:
  - arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile
```
```
In kernel/panic.c (ffffffff81096c5d)
Location: include/linux/sched.h:1240
Inline: True
Inline callers:
  - kernel/panic.c:refcount_error_report
```
```
In kernel/exit.c (ffffffff8109beeb)
Location: include/linux/sched.h:1240
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/umh.c (ffffffff810b2579)
Location: include/linux/sched.h:1240
Inline: True
Inline callers:
  - kernel/umh.c:call_usermodehelper_exec_async
```
```
In kernel/workqueue.c (ffffffff810b9712)
Location: include/linux/sched.h:1240
Inline: True
Inline callers:
  - kernel/workqueue.c:show_workqueue_state
  - kernel/workqueue.c:show_workqueue_state
  - kernel/workqueue.c:show_workqueue_state
  - kernel/workqueue.c:pr_cont_work
  - kernel/workqueue.c:process_one_work
```
```
In kernel/async.c (ffffffff810bfb9f)
Location: include/linux/sched.h:1240
Inline: True
Inline callers:
  - kernel/async.c:async_synchronize_cookie_domain
  - kernel/async.c:async_synchronize_cookie_domain
  - kernel/async.c:async_run_entry_fn
```
```
In kernel/sched/core.c (ffffffff810cc1c2)
Location: include/linux/sched.h:1240
Inline: True
Inline callers:
  - kernel/sched/core.c:select_fallback_rq
  - kernel/sched/core.c:perf_trace_sched_swap_numa
  - kernel/sched/core.c:perf_trace_sched_swap_numa
  - kernel/sched/core.c:perf_trace_sched_move_task_template
  - kernel/sched/core.c:trace_event_raw_event_sched_swap_numa
  - kernel/sched/core.c:trace_event_raw_event_sched_swap_numa
  - kernel/sched/core.c:trace_event_raw_event_sched_move_task_template
```
```
In kernel/sched/debug.c (ffffffff810e92d8)
Location: include/linux/sched.h:1240
Inline: True
Inline callers:
  - kernel/sched/debug.c:print_cpu
  - kernel/sched/debug.c:print_cpu
  - kernel/sched/debug.c:print_cpu
  - kernel/sched/debug.c:print_cpu
```
```
In kernel/locking/rtmutex.c (ffffffff810f1ab2)
Location: include/linux/sched.h:1240
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
```
```
In kernel/printk/printk.c (ffffffff81100616)
Location: include/linux/sched.h:1240
Inline: True
Inline callers:
  - kernel/printk/printk.c:check_syslog_permissions
```
```
In kernel/time/posix-cpu-timers.c (ffffffff8112dfc9)
Location: include/linux/sched.h:1240
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
```
```
In kernel/auditfilter.c (ffffffff81160fa1)
Location: include/linux/sched.h:1240
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_filter
```
```
In kernel/watchdog.c (ffffffff8117700e)
Location: include/linux/sched.h:1240
Inline: True
Inline callers:
  - kernel/watchdog.c:watchdog_timer_fn
```
```
In kernel/trace/bpf_trace.c (ffffffff811b4422)
Location: include/linux/sched.h:1240
Inline: True
```
```
In mm/oom_kill.c (ffffffff81205cc8)
Location: include/linux/sched.h:1240
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:oom_reaper
  - mm/oom_kill.c:oom_reaper
```
```
In fs/fs-writeback.c (ffffffff812deb62)
Location: include/linux/sched.h:1240
Inline: True
Inline callers:
  - fs/fs-writeback.c:block_dump___mark_inode_dirty
```
```
In fs/binfmt_elf.c (ffffffff81318c24)
Location: include/linux/sched.h:1240
Inline: True
Inline callers:
  - fs/binfmt_elf.c:elf_map
```
```
In fs/compat_binfmt_elf.c (ffffffff8131c373)
Location: include/linux/sched.h:1240
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:elf_map
```
```
In fs/coredump.c (ffffffff8132247a)
Location: include/linux/sched.h:1240
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/drop_caches.c (ffffffff81322c4e)
Location: include/linux/sched.h:1240
Inline: True
Inline callers:
  - fs/drop_caches.c:drop_caches_sysctl_handler
```
```
In fs/proc/base.c (ffffffff81336fb5)
Location: include/linux/sched.h:1240
Inline: True
Inline callers:
  - fs/proc/base.c:__set_oom_adj
  - fs/proc/base.c:__set_oom_adj
```
```
In ipc/sem.c (ffffffff813f7c16)
Location: include/linux/sched.h:1240
Inline: True
```
```
In security/selinux/hooks.c (ffffffff8141e686)
Location: include/linux/sched.h:1240
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_netlink_send
```
```
In security/tomoyo/audit.c (ffffffff8143dc19)
Location: include/linux/sched.h:1240
Inline: True
Inline callers:
  - security/tomoyo/audit.c:tomoyo_init_log
```
```
In security/integrity/integrity_audit.c (ffffffff8146d170)
Location: include/linux/sched.h:1240
Inline: True
Inline callers:
  - security/integrity/integrity_audit.c:integrity_audit_msg
```
```
In block/blk-core.c (ffffffff8149ef08)
Location: include/linux/sched.h:1240
Inline: True
Inline callers:
  - block/blk-core.c:submit_bio
```
```
In drivers/pci/quirks.c (ffffffff81542c07)
Location: include/linux/sched.h:1240
Inline: True
Inline callers:
  - drivers/pci/quirks.c:pci_do_fixups
```
```
In drivers/tty/tty_io.c (ffffffff816301ba)
Location: include/linux/sched.h:1240
Inline: True
```
```
In drivers/tty/tty_audit.c (ffffffff81639b84)
Location: include/linux/sched.h:1240
Inline: True
Inline callers:
  - drivers/tty/tty_audit.c:tty_audit_log
```
```
In drivers/base/power/main.c (ffffffff816b172d)
Location: include/linux/sched.h:1240
Inline: True
```
```
In drivers/cdrom/cdrom.c (ffffffff8176ed4f)
Location: include/linux/sched.h:1240
Inline: True
Inline callers:
  - drivers/cdrom/cdrom.c:open_for_data
```
```
In drivers/usb/core/devio.c (ffffffff8178f933)
Location: include/linux/sched.h:1240
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_open
  - drivers/usb/core/devio.c:check_ctrlrecip
  - drivers/usb/core/devio.c:checkintf
```
```
In drivers/md/md.c (ffffffff8182290e)
Location: include/linux/sched.h:1240
Inline: True
Inline callers:
  - drivers/md/md.c:md_unregister_thread
```
```
In net/core/sock.c (ffffffff8189a4cb)
Location: include/linux/sched.h:1240
Inline: True
```
```
In net/ipv4/tcp.c (ffffffff81926002)
Location: include/linux/sched.h:1240
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
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
In init/main.c (ffffffff81002a65)
Location: include/linux/sched.h:1312
Inline: True
Inline callers:
  - init/main.c:trace_initcall_start_cb
```
```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff810055b2)
Location: include/linux/sched.h:1312
Inline: True
```
```
In arch/x86/kernel/signal.c (ffffffff81030ef8)
Location: include/linux/sched.h:1312
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:signal_fault
```
```
In arch/x86/kernel/traps.c (ffffffff81031f5c)
Location: include/linux/sched.h:1312
Inline: True
```
```
In arch/x86/kernel/umip.c (ffffffff81079f40)
Location: include/linux/sched.h:1312
Inline: True
Inline callers:
  - arch/x86/kernel/umip.c:umip_printk
```
```
In arch/x86/mm/fault.c (ffffffff8107f435)
Location: include/linux/sched.h:1312
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:__bad_area_nosemaphore
  - arch/x86/mm/fault.c:__bad_area_nosemaphore
```
```
In arch/x86/net/bpf_jit_comp.c (ffffffff81096129)
Location: include/linux/sched.h:1312
Inline: True
Inline callers:
  - arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile
```
```
In kernel/panic.c (ffffffff8109b1b2)
Location: include/linux/sched.h:1312
Inline: True
Inline callers:
  - kernel/panic.c:refcount_error_report
```
```
In kernel/exit.c (ffffffff810a0cbd)
Location: include/linux/sched.h:1312
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/umh.c (ffffffff810b810a)
Location: include/linux/sched.h:1312
Inline: True
Inline callers:
  - kernel/umh.c:call_usermodehelper_exec_async
```
```
In kernel/workqueue.c (ffffffff810bf45a)
Location: include/linux/sched.h:1312
Inline: True
Inline callers:
  - kernel/workqueue.c:show_workqueue_state
  - kernel/workqueue.c:show_workqueue_state
  - kernel/workqueue.c:show_workqueue_state
  - kernel/workqueue.c:pr_cont_work
  - kernel/workqueue.c:process_one_work
```
```
In kernel/async.c (ffffffff810c5ccb)
Location: include/linux/sched.h:1312
Inline: True
Inline callers:
  - kernel/async.c:async_synchronize_cookie_domain
  - kernel/async.c:async_synchronize_cookie_domain
  - kernel/async.c:async_run_entry_fn
```
```
In kernel/sched/core.c (ffffffff810d4573)
Location: include/linux/sched.h:1312
Inline: True
Inline callers:
  - kernel/sched/core.c:select_fallback_rq
  - kernel/sched/core.c:perf_trace_sched_swap_numa
  - kernel/sched/core.c:perf_trace_sched_swap_numa
  - kernel/sched/core.c:perf_trace_sched_move_task_template
  - kernel/sched/core.c:trace_event_raw_event_sched_swap_numa
  - kernel/sched/core.c:trace_event_raw_event_sched_swap_numa
  - kernel/sched/core.c:trace_event_raw_event_sched_move_task_template
```
```
In kernel/sched/debug.c (ffffffff810f03d7)
Location: include/linux/sched.h:1312
Inline: True
Inline callers:
  - kernel/sched/debug.c:print_cpu
  - kernel/sched/debug.c:print_cpu
```
```
In kernel/locking/rtmutex.c (ffffffff810fa3c7)
Location: include/linux/sched.h:1312
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
```
```
In kernel/printk/printk.c (ffffffff811082d7)
Location: include/linux/sched.h:1312
Inline: True
Inline callers:
  - kernel/printk/printk.c:vprintk_store
  - kernel/printk/printk.c:check_syslog_permissions
```
```
In kernel/time/posix-cpu-timers.c (ffffffff81138997)
Location: include/linux/sched.h:1312
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
  - kernel/time/posix-cpu-timers.c:run_posix_cpu_timers
```
```
In kernel/auditfilter.c (ffffffff8116d64c)
Location: include/linux/sched.h:1312
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_filter
```
```
In kernel/watchdog.c (ffffffff811845a4)
Location: include/linux/sched.h:1312
Inline: True
Inline callers:
  - kernel/watchdog.c:watchdog_timer_fn
```
```
In kernel/trace/bpf_trace.c (ffffffff811c3434)
Location: include/linux/sched.h:1312
Inline: True
```
```
In mm/oom_kill.c (ffffffff8121c163)
Location: include/linux/sched.h:1312
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:oom_reaper
  - mm/oom_kill.c:oom_reaper
```
```
In fs/fs-writeback.c (ffffffff812fd1f9)
Location: include/linux/sched.h:1312
Inline: True
Inline callers:
  - fs/fs-writeback.c:block_dump___mark_inode_dirty
```
```
In fs/binfmt_elf.c (ffffffff813436b1)
Location: include/linux/sched.h:1312
Inline: True
Inline callers:
  - fs/binfmt_elf.c:elf_map
```
```
In fs/compat_binfmt_elf.c (ffffffff81347030)
Location: include/linux/sched.h:1312
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:elf_map
```
```
In fs/coredump.c (ffffffff8134986a)
Location: include/linux/sched.h:1312
Inline: True
```
```
In fs/drop_caches.c (ffffffff8134a66e)
Location: include/linux/sched.h:1312
Inline: True
Inline callers:
  - fs/drop_caches.c:drop_caches_sysctl_handler
```
```
In fs/proc/base.c (ffffffff8135f0eb)
Location: include/linux/sched.h:1312
Inline: True
Inline callers:
  - fs/proc/base.c:__set_oom_adj
  - fs/proc/base.c:__set_oom_adj
```
```
In ipc/sem.c (ffffffff814240fa)
Location: include/linux/sched.h:1312
Inline: True
```
```
In security/selinux/hooks.c (ffffffff8144c275)
Location: include/linux/sched.h:1312
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_netlink_send
```
```
In security/tomoyo/audit.c (ffffffff8146b7ab)
Location: include/linux/sched.h:1312
Inline: True
Inline callers:
  - security/tomoyo/audit.c:tomoyo_print_header
```
```
In security/integrity/integrity_audit.c (ffffffff8149a87e)
Location: include/linux/sched.h:1312
Inline: True
Inline callers:
  - security/integrity/integrity_audit.c:integrity_audit_msg
```
```
In block/blk-core.c (ffffffff814ccfe8)
Location: include/linux/sched.h:1312
Inline: True
Inline callers:
  - block/blk-core.c:submit_bio
```
```
In drivers/pci/quirks.c (ffffffff81576727)
Location: include/linux/sched.h:1312
Inline: True
Inline callers:
  - drivers/pci/quirks.c:pci_do_fixups
```
```
In drivers/tty/tty_io.c (ffffffff816640b8)
Location: include/linux/sched.h:1312
Inline: True
```
```
In drivers/tty/tty_audit.c (ffffffff8166dea2)
Location: include/linux/sched.h:1312
Inline: True
Inline callers:
  - drivers/tty/tty_audit.c:tty_audit_log
```
```
In drivers/base/power/main.c (ffffffff816ee949)
Location: include/linux/sched.h:1312
Inline: True
```
```
In drivers/cdrom/cdrom.c (ffffffff817acbb7)
Location: include/linux/sched.h:1312
Inline: True
Inline callers:
  - drivers/cdrom/cdrom.c:open_for_data
```
```
In drivers/usb/core/devio.c (ffffffff817ce70e)
Location: include/linux/sched.h:1312
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_open
  - drivers/usb/core/devio.c:check_ctrlrecip
```
```
In drivers/md/md.c (ffffffff81864e24)
Location: include/linux/sched.h:1312
Inline: True
Inline callers:
  - drivers/md/md.c:md_unregister_thread
```
```
In net/core/sock.c (ffffffff818e4acc)
Location: include/linux/sched.h:1312
Inline: True
Inline callers:
  - net/core/sock.c:sock_set_timeout
```
```
In net/ipv4/tcp.c (ffffffff81989ab6)
Location: include/linux/sched.h:1312
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
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
In init/main.c (ffffffff81002a65)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - init/main.c:trace_initcall_start_cb
```
```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff81005632)
Location: include/linux/sched.h:1306
Inline: True
```
```
In arch/x86/kernel/signal.c (ffffffff810317df)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:signal_fault
```
```
In arch/x86/kernel/traps.c (ffffffff8103281c)
Location: include/linux/sched.h:1306
Inline: True
```
```
In arch/x86/kernel/umip.c (ffffffff8107b031)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - arch/x86/kernel/umip.c:umip_printk
```
```
In arch/x86/mm/fault.c (ffffffff810804c5)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:__bad_area_nosemaphore
  - arch/x86/mm/fault.c:__bad_area_nosemaphore
```
```
In arch/x86/net/bpf_jit_comp.c (ffffffff8109c6e9)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile
```
```
In kernel/panic.c (ffffffff810a16d2)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - kernel/panic.c:refcount_error_report
```
```
In kernel/exit.c (ffffffff810a7261)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/umh.c (ffffffff810be60a)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - kernel/umh.c:call_usermodehelper_exec_async
```
```
In kernel/workqueue.c (ffffffff810c585d)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - kernel/workqueue.c:show_workqueue_state
  - kernel/workqueue.c:show_workqueue_state
  - kernel/workqueue.c:show_workqueue_state
  - kernel/workqueue.c:pr_cont_work
  - kernel/workqueue.c:process_one_work
```
```
In kernel/async.c (ffffffff810cedab)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - kernel/async.c:async_synchronize_cookie_domain
  - kernel/async.c:async_synchronize_cookie_domain
  - kernel/async.c:async_run_entry_fn
```
```
In kernel/sched/core.c (ffffffff810deb7b)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - kernel/sched/core.c:select_fallback_rq
  - kernel/sched/core.c:perf_trace_sched_swap_numa
  - kernel/sched/core.c:perf_trace_sched_swap_numa
  - kernel/sched/core.c:perf_trace_sched_move_task_template
  - kernel/sched/core.c:trace_event_raw_event_sched_swap_numa
  - kernel/sched/core.c:trace_event_raw_event_sched_swap_numa
  - kernel/sched/core.c:trace_event_raw_event_sched_move_task_template
```
```
In kernel/sched/debug.c (ffffffff810fc217)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - kernel/sched/debug.c:print_cpu
  - kernel/sched/debug.c:print_cpu
```
```
In kernel/locking/rtmutex.c (ffffffff811061a4)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
```
```
In kernel/printk/printk.c (ffffffff811146b7)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - kernel/printk/printk.c:vprintk_store
  - kernel/printk/printk.c:check_syslog_permissions
```
```
In kernel/time/posix-cpu-timers.c (ffffffff81144670)
Location: include/linux/sched.h:1306
Inline: True
```
```
In kernel/auditfilter.c (ffffffff811794ec)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_filter
```
```
In kernel/watchdog.c (ffffffff81190424)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - kernel/watchdog.c:watchdog_timer_fn
```
```
In kernel/trace/bpf_trace.c (ffffffff811cebe4)
Location: include/linux/sched.h:1306
Inline: True
```
```
In mm/oom_kill.c (ffffffff81229b15)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:oom_reaper
  - mm/oom_kill.c:oom_reaper
```
```
In fs/fs-writeback.c (ffffffff8130f6e9)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - fs/fs-writeback.c:block_dump___mark_inode_dirty
```
```
In fs/binfmt_elf.c (ffffffff8135baef)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - fs/binfmt_elf.c:elf_map
```
```
In fs/compat_binfmt_elf.c (ffffffff8135f33e)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:elf_map
```
```
In fs/coredump.c (ffffffff81361b0a)
Location: include/linux/sched.h:1306
Inline: True
```
```
In fs/drop_caches.c (ffffffff8136290e)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - fs/drop_caches.c:drop_caches_sysctl_handler
```
```
In fs/proc/base.c (ffffffff8137734b)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - fs/proc/base.c:__set_oom_adj
  - fs/proc/base.c:__set_oom_adj
```
```
In ipc/sem.c (ffffffff8143de50)
Location: include/linux/sched.h:1306
Inline: True
```
```
In security/selinux/hooks.c (ffffffff81466065)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_netlink_send
```
```
In security/tomoyo/audit.c (ffffffff8148558b)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - security/tomoyo/audit.c:tomoyo_print_header
```
```
In security/integrity/integrity_audit.c (ffffffff814b4a7e)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - security/integrity/integrity_audit.c:integrity_audit_msg
```
```
In block/blk-core.c (ffffffff814e62c7)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - block/blk-core.c:submit_bio
```
```
In drivers/pci/quirks.c (ffffffff81597e15)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - drivers/pci/quirks.c:pci_do_fixups
```
```
In drivers/tty/tty_io.c (ffffffff81686739)
Location: include/linux/sched.h:1306
Inline: True
```
```
In drivers/tty/tty_audit.c (ffffffff81690512)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - drivers/tty/tty_audit.c:tty_audit_log
```
```
In drivers/base/power/main.c (ffffffff81712929)
Location: include/linux/sched.h:1306
Inline: True
```
```
In drivers/vfio/vfio.c (ffffffff817d25aa)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_group_fops_unl_ioctl
  - drivers/vfio/vfio.c:vfio_del_group_dev
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff817d5e09)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_pin_pages
```
```
In drivers/cdrom/cdrom.c (ffffffff817dce97)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - drivers/cdrom/cdrom.c:open_for_data
```
```
In drivers/usb/core/devio.c (ffffffff817ff282)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_open
  - drivers/usb/core/devio.c:check_ctrlrecip
```
```
In drivers/md/md.c (ffffffff81896b64)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - drivers/md/md.c:md_unregister_thread
```
```
In net/core/sock.c (ffffffff81916ca4)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - net/core/sock.c:sock_set_timeout
```
```
In net/ipv4/tcp.c (ffffffff819c0f1a)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
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
In init/main.c (ffffffff81003ad6)
Location: include/linux/sched.h:1347
Inline: True
Inline callers:
  - init/main.c:trace_initcall_start_cb
```
```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff810064f3)
Location: include/linux/sched.h:1347
Inline: True
```
```
In arch/x86/kernel/signal.c (ffffffff8103403f)
Location: include/linux/sched.h:1347
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:signal_fault
```
```
In arch/x86/kernel/traps.c (ffffffff810346fe)
Location: include/linux/sched.h:1347
Inline: True
```
```
In arch/x86/kernel/umip.c (ffffffff8108243f)
Location: include/linux/sched.h:1347
Inline: True
Inline callers:
  - arch/x86/kernel/umip.c:umip_printk
```
```
In arch/x86/mm/fault.c (ffffffff8108754b)
Location: include/linux/sched.h:1347
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:__bad_area_nosemaphore
  - arch/x86/mm/fault.c:__bad_area_nosemaphore
```
```
In arch/x86/net/bpf_jit_comp.c (ffffffff810a3316)
Location: include/linux/sched.h:1347
Inline: True
Inline callers:
  - arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile
```
```
In kernel/exit.c (ffffffff810ae9e7)
Location: include/linux/sched.h:1347
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/umh.c (ffffffff810c5abd)
Location: include/linux/sched.h:1347
Inline: True
Inline callers:
  - kernel/umh.c:call_usermodehelper_exec_async
```
```
In kernel/workqueue.c (ffffffff810cd188)
Location: include/linux/sched.h:1347
Inline: True
Inline callers:
  - kernel/workqueue.c:show_workqueue_state
  - kernel/workqueue.c:show_workqueue_state
  - kernel/workqueue.c:show_pwq
  - kernel/workqueue.c:pr_cont_work
  - kernel/workqueue.c:process_one_work
```
```
In kernel/async.c (ffffffff810d8aab)
Location: include/linux/sched.h:1347
Inline: True
Inline callers:
  - kernel/async.c:async_synchronize_cookie_domain
  - kernel/async.c:async_synchronize_cookie_domain
  - kernel/async.c:async_run_entry_fn
```
```
In kernel/sched/core.c (ffffffff810e6dfd)
Location: include/linux/sched.h:1347
Inline: True
Inline callers:
  - kernel/sched/core.c:select_fallback_rq
  - kernel/sched/core.c:perf_trace_sched_numa_pair_template
  - kernel/sched/core.c:perf_trace_sched_numa_pair_template
  - kernel/sched/core.c:perf_trace_sched_move_numa
  - kernel/sched/core.c:trace_event_raw_event_sched_numa_pair_template
  - kernel/sched/core.c:trace_event_raw_event_sched_numa_pair_template
  - kernel/sched/core.c:trace_event_raw_event_sched_move_numa
```
```
In kernel/sched/debug.c (ffffffff8110695c)
Location: include/linux/sched.h:1347
Inline: True
Inline callers:
  - kernel/sched/debug.c:print_cpu
  - kernel/sched/debug.c:print_cpu
```
```
In kernel/locking/rtmutex.c (ffffffff8111114c)
Location: include/linux/sched.h:1347
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
```
```
In kernel/printk/printk.c (ffffffff8112009d)
Location: include/linux/sched.h:1347
Inline: True
Inline callers:
  - kernel/printk/printk.c:vprintk_store
  - kernel/printk/printk.c:check_syslog_permissions
```
```
In kernel/time/posix-cpu-timers.c (ffffffff81153ff5)
Location: include/linux/sched.h:1347
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:check_process_timers
  - kernel/time/posix-cpu-timers.c:check_process_timers
  - kernel/time/posix-cpu-timers.c:check_thread_timers
  - kernel/time/posix-cpu-timers.c:check_thread_timers
```
```
In kernel/audit.c (ffffffff81188712)
Location: include/linux/sched.h:1347
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_multicast
```
```
In kernel/auditfilter.c (ffffffff8118c56f)
Location: include/linux/sched.h:1347
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_filter
```
```
In kernel/auditsc.c (ffffffff8118d60c)
Location: include/linux/sched.h:1347
Inline: True
Inline callers:
  - kernel/auditsc.c:__audit_log_nfcfg
```
```
In kernel/watchdog.c (ffffffff811a4fa4)
Location: include/linux/sched.h:1347
Inline: True
Inline callers:
  - kernel/watchdog.c:watchdog_timer_fn
```
```
In kernel/trace/bpf_trace.c (ffffffff811eb104)
Location: include/linux/sched.h:1347
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:bpf_tracing_func_proto
```
```
In mm/oom_kill.c (ffffffff8125696b)
Location: include/linux/sched.h:1347
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:oom_reaper
  - mm/oom_kill.c:oom_reap_task_mm
```
```
In fs/ioctl.c (ffffffff8132c296)
Location: include/linux/sched.h:1347
Inline: True
Inline callers:
  - fs/ioctl.c:ioctl_fibmap
```
```
In fs/fs-writeback.c (ffffffff81348d52)
Location: include/linux/sched.h:1347
Inline: True
Inline callers:
  - fs/fs-writeback.c:block_dump___mark_inode_dirty
```
```
In fs/binfmt_elf.c (ffffffff813a1aa3)
Location: include/linux/sched.h:1347
Inline: True
Inline callers:
  - fs/binfmt_elf.c:elf_map
```
```
In fs/compat_binfmt_elf.c (ffffffff813a4d90)
Location: include/linux/sched.h:1347
Inline: True
```
```
In fs/coredump.c (ffffffff813a7a4c)
Location: include/linux/sched.h:1347
Inline: True
Inline callers:
  - fs/coredump.c:format_corename
```
```
In fs/drop_caches.c (ffffffff813a86de)
Location: include/linux/sched.h:1347
Inline: True
Inline callers:
  - fs/drop_caches.c:drop_caches_sysctl_handler
```
```
In fs/proc/base.c (ffffffff813c00a6)
Location: include/linux/sched.h:1347
Inline: True
```
```
In fs/ext4/balloc.c (ffffffff813da2c3)
Location: include/linux/sched.h:1347
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_inode_to_goal_block
  - fs/ext4/balloc.c:ext4_inode_to_goal_block
```
```
In ipc/sem.c (ffffffff8148eb45)
Location: include/linux/sched.h:1347
Inline: True
Inline callers:
  - ipc/sem.c:count_semcnt
```
```
In security/selinux/hooks.c (ffffffff814b9d34)
Location: include/linux/sched.h:1347
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_netlink_send
```
```
In security/tomoyo/audit.c (ffffffff814db75b)
Location: include/linux/sched.h:1347
Inline: True
Inline callers:
  - security/tomoyo/audit.c:tomoyo_print_header
```
```
In security/integrity/integrity_audit.c (ffffffff81513fce)
Location: include/linux/sched.h:1347
Inline: True
Inline callers:
  - security/integrity/integrity_audit.c:integrity_audit_msg
```
```
In block/blk-core.c (ffffffff81545523)
Location: include/linux/sched.h:1347
Inline: True
Inline callers:
  - block/blk-core.c:submit_bio
```
```
In drivers/pci/quirks.c (ffffffff8164674a)
Location: include/linux/sched.h:1347
Inline: True
Inline callers:
  - drivers/pci/quirks.c:pci_do_fixups
```
```
In drivers/tty/tty_io.c (ffffffff817384f9)
Location: include/linux/sched.h:1347
Inline: True
```
```
In drivers/tty/tty_audit.c (ffffffff81742c52)
Location: include/linux/sched.h:1347
Inline: True
Inline callers:
  - drivers/tty/tty_audit.c:tty_audit_log
```
```
In drivers/base/power/main.c (ffffffff817ce170)
Location: include/linux/sched.h:1347
Inline: True
```
```
In drivers/vfio/vfio.c (ffffffff8189d70c)
Location: include/linux/sched.h:1347
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_group_get_device_fd
  - drivers/vfio/vfio.c:vfio_del_group_dev
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff818a266f)
Location: include/linux/sched.h:1347
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_pin_page_external
```
```
In drivers/cdrom/cdrom.c (ffffffff818ab26f)
Location: include/linux/sched.h:1347
Inline: True
Inline callers:
  - drivers/cdrom/cdrom.c:open_for_data
```
```
In drivers/usb/core/devio.c (ffffffff818cfb74)
Location: include/linux/sched.h:1347
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_open
  - drivers/usb/core/devio.c:check_ctrlrecip
```
```
In drivers/md/md.c (ffffffff81964024)
Location: include/linux/sched.h:1347
Inline: True
Inline callers:
  - drivers/md/md.c:md_unregister_thread
```
```
In net/core/sock.c (ffffffff819e962f)
Location: include/linux/sched.h:1347
Inline: True
Inline callers:
  - net/core/sock.c:sock_set_timeout
```
```
In net/ipv4/tcp.c (ffffffff81aaba0d)
Location: include/linux/sched.h:1347
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
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
In init/main.c (ffffffff81bd16ca)
Location: include/linux/sched.h:1406
Inline: True
Inline callers:
  - init/main.c:trace_initcall_start_cb
```
```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff81bd1afc)
Location: include/linux/sched.h:1406
Inline: True
```
```
In arch/x86/kernel/signal.c (ffffffff81bd325d)
Location: include/linux/sched.h:1406
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:signal_fault
```
```
In arch/x86/kernel/traps.c (ffffffff81bd32aa)
Location: include/linux/sched.h:1406
Inline: True
```
```
In arch/x86/kernel/umip.c (ffffffff81bd8348)
Location: include/linux/sched.h:1406
Inline: True
Inline callers:
  - arch/x86/kernel/umip.c:umip_printk
```
```
In arch/x86/mm/fault.c (ffffffff81087c10)
Location: include/linux/sched.h:1406
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:__bad_area_nosemaphore
  - arch/x86/mm/fault.c:__bad_area_nosemaphore
```
```
In arch/x86/net/bpf_jit_comp.c (ffffffff81bdb04e)
Location: include/linux/sched.h:1406
Inline: True
Inline callers:
  - arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile
```
```
In kernel/exit.c (ffffffff81bdb786)
Location: include/linux/sched.h:1406
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/workqueue.c (ffffffff81bdbfe9)
Location: include/linux/sched.h:1406
Inline: True
Inline callers:
  - kernel/workqueue.c:show_workqueue_state
  - kernel/workqueue.c:show_workqueue_state
  - kernel/workqueue.c:show_pwq
  - kernel/workqueue.c:pr_cont_work
  - kernel/workqueue.c:process_one_work
```
```
In kernel/async.c (ffffffff810d3c4b)
Location: include/linux/sched.h:1406
Inline: True
Inline callers:
  - kernel/async.c:async_synchronize_cookie_domain
  - kernel/async.c:async_synchronize_cookie_domain
  - kernel/async.c:async_run_entry_fn
```
```
In kernel/sched/core.c (ffffffff81bdc633)
Location: include/linux/sched.h:1406
Inline: True
Inline callers:
  - kernel/sched/core.c:select_fallback_rq
  - kernel/sched/core.c:perf_trace_sched_numa_pair_template
  - kernel/sched/core.c:perf_trace_sched_numa_pair_template
  - kernel/sched/core.c:perf_trace_sched_move_numa
  - kernel/sched/core.c:trace_event_raw_event_sched_numa_pair_template
  - kernel/sched/core.c:trace_event_raw_event_sched_numa_pair_template
  - kernel/sched/core.c:trace_event_raw_event_sched_move_numa
```
```
In kernel/sched/debug.c (ffffffff81104fac)
Location: include/linux/sched.h:1406
Inline: True
Inline callers:
  - kernel/sched/debug.c:print_cpu
  - kernel/sched/debug.c:print_cpu
```
```
In kernel/locking/rtmutex.c (ffffffff81bde8d2)
Location: include/linux/sched.h:1406
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
```
```
In kernel/printk/printk.c (ffffffff8111ad48)
Location: include/linux/sched.h:1406
Inline: True
Inline callers:
  - kernel/printk/printk.c:vprintk_store
  - kernel/printk/printk.c:check_syslog_permissions
```
```
In kernel/time/posix-cpu-timers.c (ffffffff81be3b26)
Location: include/linux/sched.h:1406
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:check_process_timers
  - kernel/time/posix-cpu-timers.c:check_process_timers
  - kernel/time/posix-cpu-timers.c:check_thread_timers
  - kernel/time/posix-cpu-timers.c:check_thread_timers
```
```
In kernel/audit.c (ffffffff81185a62)
Location: include/linux/sched.h:1406
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_multicast
```
```
In kernel/auditfilter.c (ffffffff8118978d)
Location: include/linux/sched.h:1406
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_filter
```
```
In kernel/auditsc.c (ffffffff8118a7b9)
Location: include/linux/sched.h:1406
Inline: True
Inline callers:
  - kernel/auditsc.c:__audit_log_nfcfg
```
```
In kernel/watchdog.c (ffffffff81be4f4b)
Location: include/linux/sched.h:1406
Inline: True
Inline callers:
  - kernel/watchdog.c:watchdog_timer_fn
```
```
In kernel/trace/bpf_trace.c (ffffffff81be63a2)
Location: include/linux/sched.h:1406
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:bpf_tracing_func_proto
```
```
In mm/oom_kill.c (ffffffff8126150e)
Location: include/linux/sched.h:1406
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:oom_reaper
  - mm/oom_kill.c:oom_reap_task_mm
```
```
In fs/ioctl.c (ffffffff81bea674)
Location: include/linux/sched.h:1406
Inline: True
Inline callers:
  - fs/ioctl.c:ioctl_fibmap
```
```
In fs/fs-writeback.c (ffffffff81355cb2)
Location: include/linux/sched.h:1406
Inline: True
Inline callers:
  - fs/fs-writeback.c:block_dump___mark_inode_dirty
```
```
In fs/io_uring.c (ffffffff8138df70)
Location: include/linux/sched.h:1406
Inline: True
Inline callers:
  - fs/io_uring.c:__io_uring_show_fdinfo
```
```
In fs/binfmt_elf.c (ffffffff81beba56)
Location: include/linux/sched.h:1406
Inline: True
Inline callers:
  - fs/binfmt_elf.c:elf_map
```
```
In fs/compat_binfmt_elf.c (ffffffff81beba80)
Location: include/linux/sched.h:1406
Inline: True
```
```
In fs/coredump.c (ffffffff813b85c2)
Location: include/linux/sched.h:1406
Inline: True
Inline callers:
  - fs/coredump.c:format_corename
```
```
In fs/drop_caches.c (ffffffff81bebafd)
Location: include/linux/sched.h:1406
Inline: True
Inline callers:
  - fs/drop_caches.c:drop_caches_sysctl_handler
```
```
In fs/proc/base.c (ffffffff81bebcde)
Location: include/linux/sched.h:1406
Inline: True
```
```
In fs/ext4/balloc.c (ffffffff813ebfa0)
Location: include/linux/sched.h:1406
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_inode_to_goal_block
  - fs/ext4/balloc.c:ext4_inode_to_goal_block
```
```
In ipc/sem.c (ffffffff81befaff)
Location: include/linux/sched.h:1406
Inline: True
Inline callers:
  - ipc/sem.c:count_semcnt
```
```
In security/selinux/hooks.c (ffffffff81bf01de)
Location: include/linux/sched.h:1406
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_netlink_send
```
```
In security/tomoyo/audit.c (ffffffff814f8bcb)
Location: include/linux/sched.h:1406
Inline: True
Inline callers:
  - security/tomoyo/audit.c:tomoyo_print_header
```
```
In security/integrity/integrity_audit.c (ffffffff8153112e)
Location: include/linux/sched.h:1406
Inline: True
Inline callers:
  - security/integrity/integrity_audit.c:integrity_audit_message
```
```
In block/blk-core.c (ffffffff81561b83)
Location: include/linux/sched.h:1406
Inline: True
Inline callers:
  - block/blk-core.c:submit_bio
```
```
In drivers/pci/quirks.c (ffffffff81bfa31b)
Location: include/linux/sched.h:1406
Inline: True
Inline callers:
  - drivers/pci/quirks.c:pci_do_fixups
```
```
In drivers/tty/tty_io.c (ffffffff81c07454)
Location: include/linux/sched.h:1406
Inline: True
```
```
In drivers/tty/tty_audit.c (ffffffff8175eaf2)
Location: include/linux/sched.h:1406
Inline: True
Inline callers:
  - drivers/tty/tty_audit.c:tty_audit_log
```
```
In drivers/base/power/main.c (ffffffff81c0ed44)
Location: include/linux/sched.h:1406
Inline: True
```
```
In drivers/vfio/vfio.c (ffffffff81c19fa8)
Location: include/linux/sched.h:1406
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_group_get_device_fd
  - drivers/vfio/vfio.c:vfio_del_group_dev
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff81c19ff0)
Location: include/linux/sched.h:1406
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_pin_page_external
```
```
In drivers/cdrom/cdrom.c (ffffffff818b9f8d)
Location: include/linux/sched.h:1406
Inline: True
Inline callers:
  - drivers/cdrom/cdrom.c:open_for_data
```
```
In drivers/usb/core/devio.c (ffffffff81c1e89f)
Location: include/linux/sched.h:1406
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_open
  - drivers/usb/core/devio.c:check_ctrlrecip
```
```
In drivers/md/md.c (ffffffff8196a914)
Location: include/linux/sched.h:1406
Inline: True
Inline callers:
  - drivers/md/md.c:md_unregister_thread
```
```
In net/core/sock.c (ffffffff81c30470)
Location: include/linux/sched.h:1406
Inline: True
Inline callers:
  - net/core/sock.c:sock_set_timeout
```
```
In net/ipv4/tcp.c (ffffffff81ab697a)
Location: include/linux/sched.h:1406
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg_locked
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
In init/main.c (ffffffff81bc36da)
Location: include/linux/sched.h:1428
Inline: True
Inline callers:
  - init/main.c:trace_initcall_start_cb
```
```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff81bc3b9d)
Location: include/linux/sched.h:1428
Inline: True
```
```
In arch/x86/kernel/signal.c (ffffffff81bc5675)
Location: include/linux/sched.h:1428
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:signal_fault
```
```
In arch/x86/kernel/traps.c (ffffffff81bc56c2)
Location: include/linux/sched.h:1428
Inline: True
```
```
In arch/x86/kernel/umip.c (ffffffff81bca185)
Location: include/linux/sched.h:1428
Inline: True
Inline callers:
  - arch/x86/kernel/umip.c:umip_printk
```
```
In arch/x86/mm/fault.c (ffffffff810887b0)
Location: include/linux/sched.h:1428
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:__bad_area_nosemaphore
  - arch/x86/mm/fault.c:__bad_area_nosemaphore
```
```
In arch/x86/net/bpf_jit_comp.c (ffffffff81bcd11c)
Location: include/linux/sched.h:1428
Inline: True
Inline callers:
  - arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile
```
```
In kernel/exit.c (ffffffff81bcd899)
Location: include/linux/sched.h:1428
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/workqueue.c (ffffffff81bce10e)
Location: include/linux/sched.h:1428
Inline: True
Inline callers:
  - kernel/workqueue.c:show_workqueue_state
  - kernel/workqueue.c:show_workqueue_state
  - kernel/workqueue.c:show_pwq
  - kernel/workqueue.c:pr_cont_work
  - kernel/workqueue.c:process_one_work
```
```
In kernel/async.c (ffffffff810d5892)
Location: include/linux/sched.h:1428
Inline: True
Inline callers:
  - kernel/async.c:async_synchronize_cookie_domain
  - kernel/async.c:async_synchronize_cookie_domain
  - kernel/async.c:async_run_entry_fn
```
```
In kernel/sched/core.c (ffffffff81bce7b5)
Location: include/linux/sched.h:1428
Inline: True
Inline callers:
  - kernel/sched/core.c:select_fallback_rq
  - kernel/sched/core.c:perf_trace_sched_numa_pair_template
  - kernel/sched/core.c:perf_trace_sched_numa_pair_template
  - kernel/sched/core.c:perf_trace_sched_move_numa
  - kernel/sched/core.c:trace_event_raw_event_sched_numa_pair_template
  - kernel/sched/core.c:trace_event_raw_event_sched_numa_pair_template
  - kernel/sched/core.c:trace_event_raw_event_sched_move_numa
```
```
In kernel/sched/debug.c (ffffffff811073e8)
Location: include/linux/sched.h:1428
Inline: True
Inline callers:
  - kernel/sched/debug.c:print_cpu
  - kernel/sched/debug.c:print_cpu
```
```
In kernel/locking/rtmutex.c (ffffffff81c36a2e)
Location: include/linux/sched.h:1428
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
```
```
In kernel/printk/printk.c (ffffffff8111b2e8)
Location: include/linux/sched.h:1428
Inline: True
Inline callers:
  - kernel/printk/printk.c:vprintk_store
  - kernel/printk/printk.c:check_syslog_permissions
```
```
In kernel/time/posix-cpu-timers.c (ffffffff81bd5a0f)
Location: include/linux/sched.h:1428
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_timers_work
  - kernel/time/posix-cpu-timers.c:posix_cpu_timers_work
  - kernel/time/posix-cpu-timers.c:check_process_timers
  - kernel/time/posix-cpu-timers.c:check_process_timers
```
```
In kernel/audit.c (ffffffff81186a52)
Location: include/linux/sched.h:1428
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_multicast
```
```
In kernel/auditfilter.c (ffffffff8118a5da)
Location: include/linux/sched.h:1428
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_filter
```
```
In kernel/auditsc.c (ffffffff8118b669)
Location: include/linux/sched.h:1428
Inline: True
Inline callers:
  - kernel/auditsc.c:__audit_log_nfcfg
```
```
In kernel/watchdog.c (ffffffff811a2562)
Location: include/linux/sched.h:1428
Inline: True
Inline callers:
  - kernel/watchdog.c:watchdog_timer_fn
```
```
In kernel/trace/bpf_trace.c (ffffffff81bd805d)
Location: include/linux/sched.h:1428
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:bpf_tracing_func_proto
```
```
In mm/oom_kill.c (ffffffff81265d4a)
Location: include/linux/sched.h:1428
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:oom_reaper
  - mm/oom_kill.c:oom_reaper
```
```
In fs/ioctl.c (ffffffff81bdc6b0)
Location: include/linux/sched.h:1428
Inline: True
Inline callers:
  - fs/ioctl.c:do_vfs_ioctl
```
```
In fs/io_uring.c (ffffffff81397e4d)
Location: include/linux/sched.h:1428
Inline: True
Inline callers:
  - fs/io_uring.c:__io_uring_show_fdinfo
```
```
In fs/binfmt_elf.c (ffffffff81bddab8)
Location: include/linux/sched.h:1428
Inline: True
Inline callers:
  - fs/binfmt_elf.c:elf_map
```
```
In fs/compat_binfmt_elf.c (ffffffff81bddae2)
Location: include/linux/sched.h:1428
Inline: True
```
```
In fs/coredump.c (ffffffff813bf602)
Location: include/linux/sched.h:1428
Inline: True
```
```
In fs/drop_caches.c (ffffffff81bddb5c)
Location: include/linux/sched.h:1428
Inline: True
Inline callers:
  - fs/drop_caches.c:drop_caches_sysctl_handler
```
```
In fs/proc/base.c (ffffffff81bddced)
Location: include/linux/sched.h:1428
Inline: True
```
```
In fs/ext4/balloc.c (ffffffff813f24cd)
Location: include/linux/sched.h:1428
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_inode_to_goal_block
  - fs/ext4/balloc.c:ext4_inode_to_goal_block
```
```
In ipc/sem.c (ffffffff81be1ba6)
Location: include/linux/sched.h:1428
Inline: True
Inline callers:
  - ipc/sem.c:count_semcnt
```
```
In security/selinux/hooks.c (ffffffff81be225d)
Location: include/linux/sched.h:1428
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_netlink_send
```
```
In security/tomoyo/audit.c (ffffffff814ff95b)
Location: include/linux/sched.h:1428
Inline: True
Inline callers:
  - security/tomoyo/audit.c:tomoyo_print_header
```
```
In security/integrity/integrity_audit.c (ffffffff8153955e)
Location: include/linux/sched.h:1428
Inline: True
Inline callers:
  - security/integrity/integrity_audit.c:integrity_audit_message
```
```
In block/blk-core.c (ffffffff8156a2e3)
Location: include/linux/sched.h:1428
Inline: True
Inline callers:
  - block/blk-core.c:submit_bio
```
```
In drivers/pci/quirks.c (ffffffff81bec178)
Location: include/linux/sched.h:1428
Inline: True
Inline callers:
  - drivers/pci/quirks.c:pci_fixup_device
```
```
In drivers/tty/tty_io.c (ffffffff81bf907a)
Location: include/linux/sched.h:1428
Inline: True
```
```
In drivers/tty/tty_audit.c (ffffffff81742932)
Location: include/linux/sched.h:1428
Inline: True
Inline callers:
  - drivers/tty/tty_audit.c:tty_audit_log
```
```
In drivers/base/power/main.c (ffffffff81c00ebd)
Location: include/linux/sched.h:1428
Inline: True
```
```
In drivers/vfio/vfio.c (ffffffff81c0bdc1)
Location: include/linux/sched.h:1428
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_group_get_device_fd
  - drivers/vfio/vfio.c:vfio_unregister_group_dev
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff81c0be3b)
Location: include/linux/sched.h:1428
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_pin_pages
```
```
In drivers/cdrom/cdrom.c (ffffffff8189d4df)
Location: include/linux/sched.h:1428
Inline: True
Inline callers:
  - drivers/cdrom/cdrom.c:open_for_data
```
```
In drivers/usb/core/devio.c (ffffffff81c106be)
Location: include/linux/sched.h:1428
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_open
  - drivers/usb/core/devio.c:check_ctrlrecip
```
```
In drivers/md/md.c (ffffffff8194fcd4)
Location: include/linux/sched.h:1428
Inline: True
Inline callers:
  - drivers/md/md.c:md_unregister_thread
```
```
In net/core/sock.c (ffffffff81c22748)
Location: include/linux/sched.h:1428
Inline: True
Inline callers:
  - net/core/sock.c:sock_set_timeout
```
```
In net/ipv4/tcp.c (ffffffff81aa1b30)
Location: include/linux/sched.h:1428
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg_locked
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
In init/main.c (ffffffff81c9474f)
Location: include/linux/sched.h:1526
Inline: True
Inline callers:
  - init/main.c:trace_initcall_start_cb
```
```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff81c94bee)
Location: include/linux/sched.h:1526
Inline: True
```
```
In arch/x86/kernel/signal.c (ffffffff81c9828c)
Location: include/linux/sched.h:1526
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:signal_fault
```
```
In arch/x86/kernel/traps.c (ffffffff81d460b7)
Location: include/linux/sched.h:1526
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:exc_general_protection
```
```
In arch/x86/kernel/umip.c (ffffffff81c9f4ec)
Location: include/linux/sched.h:1526
Inline: True
Inline callers:
  - arch/x86/kernel/umip.c:umip_printk
```
```
In arch/x86/mm/fault.c (ffffffff81097be0)
Location: include/linux/sched.h:1526
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:__bad_area_nosemaphore
  - arch/x86/mm/fault.c:__bad_area_nosemaphore
```
```
In arch/x86/net/bpf_jit_comp.c (ffffffff81ca3878)
Location: include/linux/sched.h:1526
Inline: True
Inline callers:
  - arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile
```
```
In kernel/exit.c (ffffffff81ca41df)
Location: include/linux/sched.h:1526
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/workqueue.c (ffffffff81ca53be)
Location: include/linux/sched.h:1526
Inline: True
Inline callers:
  - kernel/workqueue.c:show_workqueue_state
  - kernel/workqueue.c:show_workqueue_state
  - kernel/workqueue.c:show_pwq
  - kernel/workqueue.c:pr_cont_work
  - kernel/workqueue.c:process_one_work
```
```
In kernel/async.c (ffffffff810e8aac)
Location: include/linux/sched.h:1526
Inline: True
Inline callers:
  - kernel/async.c:async_synchronize_cookie_domain
  - kernel/async.c:async_synchronize_cookie_domain
  - kernel/async.c:async_run_entry_fn
```
```
In kernel/sched/core.c (ffffffff81ca5c44)
Location: include/linux/sched.h:1526
Inline: True
Inline callers:
  - kernel/sched/core.c:select_fallback_rq
  - kernel/sched/core.c:force_compatible_cpus_allowed_ptr
  - kernel/sched/core.c:perf_trace_sched_numa_pair_template
  - kernel/sched/core.c:perf_trace_sched_numa_pair_template
  - kernel/sched/core.c:perf_trace_sched_move_numa
  - kernel/sched/core.c:trace_event_raw_event_sched_numa_pair_template
  - kernel/sched/core.c:trace_event_raw_event_sched_numa_pair_template
  - kernel/sched/core.c:trace_event_raw_event_sched_move_numa
```
```
In kernel/sched/debug.c (ffffffff81125495)
Location: include/linux/sched.h:1526
Inline: True
Inline callers:
  - kernel/sched/debug.c:print_cpu
  - kernel/sched/debug.c:print_cpu
```
```
In kernel/locking/rtmutex_api.c (ffffffff81d55342)
Location: include/linux/sched.h:1526
Inline: True
Inline callers:
  - kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain
```
```
In kernel/printk/printk.c (ffffffff8113b5d9)
Location: include/linux/sched.h:1526
Inline: True
Inline callers:
  - kernel/printk/printk.c:vprintk_store
  - kernel/printk/printk.c:check_syslog_permissions
```
```
In kernel/time/posix-cpu-timers.c (ffffffff81cb1ce3)
Location: include/linux/sched.h:1526
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_timers_work
  - kernel/time/posix-cpu-timers.c:posix_cpu_timers_work
  - kernel/time/posix-cpu-timers.c:check_process_timers
  - kernel/time/posix-cpu-timers.c:check_process_timers
```
```
In kernel/audit.c (ffffffff811aee82)
Location: include/linux/sched.h:1526
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_multicast
```
```
In kernel/auditfilter.c (ffffffff811b30df)
Location: include/linux/sched.h:1526
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_filter
```
```
In kernel/auditsc.c (ffffffff811b4272)
Location: include/linux/sched.h:1526
Inline: True
Inline callers:
  - kernel/auditsc.c:__audit_log_nfcfg
```
```
In kernel/watchdog.c (ffffffff811cbd42)
Location: include/linux/sched.h:1526
Inline: True
Inline callers:
  - kernel/watchdog.c:watchdog_timer_fn
```
```
In kernel/trace/bpf_trace.c (ffffffff81cb7211)
Location: include/linux/sched.h:1526
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:bpf_tracing_func_proto
```
```
In mm/oom_kill.c (ffffffff812a2574)
Location: include/linux/sched.h:1526
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:oom_reaper
  - mm/oom_kill.c:oom_reaper
```
```
In mm/kfence/core.c (ffffffff8133bb85)
Location: include/linux/sched.h:1526
Inline: True
Inline callers:
  - mm/kfence/core.c:metadata_update_state
```
```
In fs/ioctl.c (ffffffff81cc3ab1)
Location: include/linux/sched.h:1526
Inline: True
Inline callers:
  - fs/ioctl.c:do_vfs_ioctl
```
```
In fs/io_uring.c (ffffffff813e39ae)
Location: include/linux/sched.h:1526
Inline: True
Inline callers:
  - fs/io_uring.c:__io_uring_show_fdinfo
```
```
In fs/binfmt_elf.c (0)
Location: include/linux/sched.h:1526
Inline: True
```
```
In fs/compat_binfmt_elf.c (0)
Location: include/linux/sched.h:1526
Inline: True
```
```
In fs/coredump.c (ffffffff8140f432)
Location: include/linux/sched.h:1526
Inline: True
```
```
In fs/drop_caches.c (ffffffff81cc7652)
Location: include/linux/sched.h:1526
Inline: True
Inline callers:
  - fs/drop_caches.c:drop_caches_sysctl_handler
```
```
In fs/proc/base.c (ffffffff81cc80ef)
Location: include/linux/sched.h:1526
Inline: True
```
```
In fs/ext4/balloc.c (ffffffff814444ae)
Location: include/linux/sched.h:1526
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_inode_to_goal_block
  - fs/ext4/balloc.c:ext4_inode_to_goal_block
```
```
In ipc/sem.c (ffffffff81cd2aa8)
Location: include/linux/sched.h:1526
Inline: True
Inline callers:
  - ipc/sem.c:count_semcnt
```
```
In security/selinux/hooks.c (ffffffff81cd3638)
Location: include/linux/sched.h:1526
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_netlink_send
```
```
In security/tomoyo/audit.c (ffffffff8155a9cb)
Location: include/linux/sched.h:1526
Inline: True
Inline callers:
  - security/tomoyo/audit.c:tomoyo_print_header
```
```
In security/integrity/integrity_audit.c (ffffffff81597da1)
Location: include/linux/sched.h:1526
Inline: True
Inline callers:
  - security/integrity/integrity_audit.c:integrity_audit_message
```
```
In drivers/pci/quirks.c (ffffffff81ce7601)
Location: include/linux/sched.h:1526
Inline: True
Inline callers:
  - drivers/pci/quirks.c:pci_fixup_device
```
```
In drivers/tty/tty_io.c (ffffffff81cf88d2)
Location: include/linux/sched.h:1526
Inline: True
```
```
In drivers/tty/tty_audit.c (ffffffff817c3382)
Location: include/linux/sched.h:1526
Inline: True
Inline callers:
  - drivers/tty/tty_audit.c:tty_audit_log
```
```
In drivers/base/power/main.c (ffffffff81d03977)
Location: include/linux/sched.h:1526
Inline: True
```
```
In drivers/vfio/vfio.c (ffffffff81d116c5)
Location: include/linux/sched.h:1526
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_group_get_device_fd
  - drivers/vfio/vfio.c:vfio_unregister_group_dev
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff81d11b39)
Location: include/linux/sched.h:1526
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_pin_pages
```
```
In drivers/cdrom/cdrom.c (ffffffff81931f45)
Location: include/linux/sched.h:1526
Inline: True
Inline callers:
  - drivers/cdrom/cdrom.c:open_for_data
```
```
In drivers/usb/core/devio.c (ffffffff81d17b31)
Location: include/linux/sched.h:1526
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_open
  - drivers/usb/core/devio.c:check_ctrlrecip
```
```
In drivers/md/md.c (ffffffff819f5151)
Location: include/linux/sched.h:1526
Inline: True
Inline callers:
  - drivers/md/md.c:md_unregister_thread
```
```
In net/core/sock.c (ffffffff81d34b99)
Location: include/linux/sched.h:1526
Inline: True
Inline callers:
  - net/core/sock.c:sock_set_timeout
```
```
In net/ipv4/tcp.c (ffffffff81b5dad4)
Location: include/linux/sched.h:1526
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg_locked
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
In init/main.c (ffffffff81e4389b)
Location: include/linux/sched.h:1538
Inline: True
Inline callers:
  - init/main.c:trace_initcall_start_cb
```
```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff81e43ea4)
Location: include/linux/sched.h:1538
Inline: True
```
```
In arch/x86/kernel/signal.c (ffffffff81e47723)
Location: include/linux/sched.h:1538
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:signal_fault
```
```
In arch/x86/kernel/traps.c (ffffffff81f1436d)
Location: include/linux/sched.h:1538
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:exc_general_protection
```
```
In arch/x86/kernel/umip.c (ffffffff81e4ec88)
Location: include/linux/sched.h:1538
Inline: True
Inline callers:
  - arch/x86/kernel/umip.c:umip_printk
```
```
In arch/x86/mm/fault.c (ffffffff810aa783)
Location: include/linux/sched.h:1538
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:__bad_area_nosemaphore
  - arch/x86/mm/fault.c:__bad_area_nosemaphore
```
```
In arch/x86/net/bpf_jit_comp.c (ffffffff81e52f86)
Location: include/linux/sched.h:1538
Inline: True
Inline callers:
  - arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile
```
```
In kernel/exit.c (ffffffff81e53a75)
Location: include/linux/sched.h:1538
Inline: True
Inline callers:
  - kernel/exit.c:make_task_dead
```
```
In kernel/workqueue.c (ffffffff81e54ccb)
Location: include/linux/sched.h:1538
Inline: True
Inline callers:
  - kernel/workqueue.c:show_all_workqueues
  - kernel/workqueue.c:show_all_workqueues
  - kernel/workqueue.c:show_pwq
  - kernel/workqueue.c:pr_cont_work
  - kernel/workqueue.c:process_one_work
```
```
In kernel/async.c (ffffffff8110352e)
Location: include/linux/sched.h:1538
Inline: True
Inline callers:
  - kernel/async.c:async_synchronize_cookie_domain
  - kernel/async.c:async_synchronize_cookie_domain
  - kernel/async.c:async_run_entry_fn
```
```
In kernel/sched/core.c (ffffffff81e5555c)
Location: include/linux/sched.h:1538
Inline: True
Inline callers:
  - kernel/sched/core.c:select_fallback_rq
  - kernel/sched/core.c:force_compatible_cpus_allowed_ptr
  - kernel/sched/core.c:perf_trace_sched_numa_pair_template
  - kernel/sched/core.c:perf_trace_sched_numa_pair_template
  - kernel/sched/core.c:perf_trace_sched_move_numa
  - kernel/sched/core.c:trace_event_raw_event_sched_numa_pair_template
  - kernel/sched/core.c:trace_event_raw_event_sched_numa_pair_template
  - kernel/sched/core.c:trace_event_raw_event_sched_move_numa
```
```
In kernel/sched/build_policy.c (ffffffff81e5665a)
Location: include/linux/sched.h:1538
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:enqueue_task_dl
```
```
In kernel/sched/build_utility.c (ffffffff81140972)
Location: include/linux/sched.h:1538
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:print_cpu
  - kernel/sched/build_utility.c:print_cpu
```
```
In kernel/locking/rtmutex_api.c (ffffffff81f26fa5)
Location: include/linux/sched.h:1538
Inline: True
Inline callers:
  - kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain
```
```
In kernel/printk/printk.c (ffffffff8115e86b)
Location: include/linux/sched.h:1538
Inline: True
Inline callers:
  - kernel/printk/printk.c:vprintk_store
  - kernel/printk/printk.c:check_syslog_permissions
```
```
In kernel/time/posix-cpu-timers.c (ffffffff81e6328f)
Location: include/linux/sched.h:1538
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_timers_work
  - kernel/time/posix-cpu-timers.c:posix_cpu_timers_work
  - kernel/time/posix-cpu-timers.c:check_process_timers
  - kernel/time/posix-cpu-timers.c:check_process_timers
```
```
In kernel/audit.c (ffffffff811e10db)
Location: include/linux/sched.h:1538
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_multicast
```
```
In kernel/auditfilter.c (ffffffff811e5537)
Location: include/linux/sched.h:1538
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_filter
```
```
In kernel/auditsc.c (ffffffff811e6794)
Location: include/linux/sched.h:1538
Inline: True
Inline callers:
  - kernel/auditsc.c:__audit_log_nfcfg
```
```
In kernel/watchdog.c (ffffffff811ffaec)
Location: include/linux/sched.h:1538
Inline: True
Inline callers:
  - kernel/watchdog.c:watchdog_timer_fn
```
```
In kernel/trace/bpf_trace.c (ffffffff81e682b7)
Location: include/linux/sched.h:1538
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:bpf_tracing_func_proto
```
```
In mm/oom_kill.c (ffffffff812fa0c4)
Location: include/linux/sched.h:1538
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:oom_reaper
  - mm/oom_kill.c:oom_reaper
```
```
In mm/kfence/core.c (ffffffff813ae471)
Location: include/linux/sched.h:1538
Inline: True
Inline callers:
  - mm/kfence/core.c:metadata_update_state
```
```
In fs/ioctl.c (ffffffff81e762d2)
Location: include/linux/sched.h:1538
Inline: True
Inline callers:
  - fs/ioctl.c:do_vfs_ioctl
```
```
In fs/binfmt_elf.c (ffffffff81e79a84)
Location: include/linux/sched.h:1538
Inline: True
Inline callers:
  - fs/binfmt_elf.c:elf_map
```
```
In fs/compat_binfmt_elf.c (ffffffff81e79aae)
Location: include/linux/sched.h:1538
Inline: True
```
```
In fs/coredump.c (ffffffff8148507e)
Location: include/linux/sched.h:1538
Inline: True
```
```
In fs/drop_caches.c (ffffffff81e79ca1)
Location: include/linux/sched.h:1538
Inline: True
Inline callers:
  - fs/drop_caches.c:drop_caches_sysctl_handler
```
```
In fs/proc/base.c (ffffffff81e7ac96)
Location: include/linux/sched.h:1538
Inline: True
```
```
In fs/ext4/balloc.c (ffffffff814c038e)
Location: include/linux/sched.h:1538
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_inode_to_goal_block
  - fs/ext4/balloc.c:ext4_inode_to_goal_block
```
```
In ipc/sem.c (ffffffff81e85c05)
Location: include/linux/sched.h:1538
Inline: True
Inline callers:
  - ipc/sem.c:count_semcnt
```
```
In security/selinux/hooks.c (ffffffff81e86770)
Location: include/linux/sched.h:1538
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_netlink_send
```
```
In security/tomoyo/audit.c (ffffffff815f5799)
Location: include/linux/sched.h:1538
Inline: True
Inline callers:
  - security/tomoyo/audit.c:tomoyo_print_header
```
```
In security/integrity/integrity_audit.c (ffffffff8163c58d)
Location: include/linux/sched.h:1538
Inline: True
Inline callers:
  - security/integrity/integrity_audit.c:integrity_audit_message
```
```
In io_uring/io_uring.c (ffffffff81e90093)
Location: include/linux/sched.h:1538
Inline: True
Inline callers:
  - io_uring/io_uring.c:__io_uring_show_fdinfo
```
```
In drivers/pci/quirks.c (ffffffff81eae701)
Location: include/linux/sched.h:1538
Inline: True
Inline callers:
  - drivers/pci/quirks.c:pci_fixup_device
```
```
In drivers/tty/tty_io.c (ffffffff81ec0b1e)
Location: include/linux/sched.h:1538
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:__do_SAK
  - drivers/tty/tty_io.c:__do_SAK
  - drivers/tty/tty_io.c:__do_SAK
```
```
In drivers/tty/tty_audit.c (ffffffff818fff2d)
Location: include/linux/sched.h:1538
Inline: True
Inline callers:
  - drivers/tty/tty_audit.c:tty_audit_log
```
```
In drivers/base/power/main.c (ffffffff81ecc230)
Location: include/linux/sched.h:1538
Inline: True
```
```
In drivers/vfio/vfio.c (ffffffff81edc3fb)
Location: include/linux/sched.h:1538
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_device_open
  - drivers/vfio/vfio.c:vfio_unregister_group_dev
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff81edc8b4)
Location: include/linux/sched.h:1538
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_pin_pages
```
```
In drivers/cdrom/cdrom.c (ffffffff81a89304)
Location: include/linux/sched.h:1538
Inline: True
Inline callers:
  - drivers/cdrom/cdrom.c:open_for_data
```
```
In drivers/usb/core/devio.c (ffffffff81ee28f9)
Location: include/linux/sched.h:1538
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_open
  - drivers/usb/core/devio.c:check_ctrlrecip
```
```
In drivers/md/md.c (ffffffff81b59f6b)
Location: include/linux/sched.h:1538
Inline: True
Inline callers:
  - drivers/md/md.c:md_unregister_thread
```
```
In net/core/sock.c (ffffffff81f010b0)
Location: include/linux/sched.h:1538
Inline: True
Inline callers:
  - net/core/sock.c:sock_set_timeout
```
```
In net/ipv4/tcp.c (ffffffff81cec46f)
Location: include/linux/sched.h:1538
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg_locked
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
In init/main.c (ffffffff8100114c)
Location: include/linux/sched.h:1560
Inline: True
Inline callers:
  - init/main.c:trace_initcall_start_cb
```
```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff81005355)
Location: include/linux/sched.h:1560
Inline: True
```
```
In arch/x86/kernel/signal.c (ffffffff8104b76e)
Location: include/linux/sched.h:1560
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:signal_fault
  - arch/x86/kernel/signal.c:get_sigframe
```
```
In arch/x86/kernel/traps.c (ffffffff820bb69a)
Location: include/linux/sched.h:1560
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:exc_general_protection
  - arch/x86/kernel/traps.c:exc_general_protection
```
```
In arch/x86/kernel/umip.c (ffffffff810bac75)
Location: include/linux/sched.h:1560
Inline: True
Inline callers:
  - arch/x86/kernel/umip.c:umip_printk
```
```
In arch/x86/mm/fault.c (ffffffff810c427a)
Location: include/linux/sched.h:1560
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:__bad_area_nosemaphore
  - arch/x86/mm/fault.c:__bad_area_nosemaphore
```
```
In arch/x86/net/bpf_jit_comp.c (ffffffff810e3c85)
Location: include/linux/sched.h:1560
Inline: True
Inline callers:
  - arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile
```
```
In kernel/exit.c (ffffffff810f201d)
Location: include/linux/sched.h:1560
Inline: True
Inline callers:
  - kernel/exit.c:make_task_dead
  - kernel/exit.c:make_task_dead
```
```
In kernel/workqueue.c (ffffffff811172fe)
Location: include/linux/sched.h:1560
Inline: True
Inline callers:
  - kernel/workqueue.c:show_all_workqueues
  - kernel/workqueue.c:show_all_workqueues
  - kernel/workqueue.c:show_pwq
  - kernel/workqueue.c:show_pwq
  - kernel/workqueue.c:show_pwq
  - kernel/workqueue.c:show_pwq
  - kernel/workqueue.c:process_one_work
```
```
In kernel/async.c (ffffffff81128bce)
Location: include/linux/sched.h:1560
Inline: True
Inline callers:
  - kernel/async.c:async_synchronize_cookie_domain
  - kernel/async.c:async_synchronize_cookie_domain
  - kernel/async.c:async_run_entry_fn
```
```
In kernel/sched/core.c (ffffffff81134fe4)
Location: include/linux/sched.h:1560
Inline: True
Inline callers:
  - kernel/sched/core.c:select_fallback_rq
  - kernel/sched/core.c:force_compatible_cpus_allowed_ptr
  - kernel/sched/core.c:perf_trace_sched_numa_pair_template
  - kernel/sched/core.c:perf_trace_sched_numa_pair_template
  - kernel/sched/core.c:perf_trace_sched_move_numa
  - kernel/sched/core.c:trace_event_raw_event_sched_numa_pair_template
  - kernel/sched/core.c:trace_event_raw_event_sched_numa_pair_template
  - kernel/sched/core.c:trace_event_raw_event_sched_move_numa
```
```
In kernel/sched/build_policy.c (ffffffff8115feca)
Location: include/linux/sched.h:1560
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:enqueue_task_dl
```
```
In kernel/sched/build_utility.c (ffffffff8116b4b2)
Location: include/linux/sched.h:1560
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:print_cpu
  - kernel/sched/build_utility.c:print_cpu
```
```
In kernel/locking/rtmutex_api.c (ffffffff820d25ca)
Location: include/linux/sched.h:1560
Inline: True
Inline callers:
  - kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain
```
```
In kernel/printk/printk.c (ffffffff811917b8)
Location: include/linux/sched.h:1560
Inline: True
Inline callers:
  - kernel/printk/printk.c:vprintk_store
  - kernel/printk/printk.c:check_syslog_permissions
```
```
In kernel/time/posix-cpu-timers.c (ffffffff811ea423)
Location: include/linux/sched.h:1560
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_timers_work
  - kernel/time/posix-cpu-timers.c:posix_cpu_timers_work
  - kernel/time/posix-cpu-timers.c:check_process_timers
  - kernel/time/posix-cpu-timers.c:check_process_timers
```
```
In kernel/audit.c (ffffffff81226f2b)
Location: include/linux/sched.h:1560
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_multicast
```
```
In kernel/auditfilter.c (ffffffff8122b5b7)
Location: include/linux/sched.h:1560
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_filter
```
```
In kernel/auditsc.c (ffffffff8122c214)
Location: include/linux/sched.h:1560
Inline: True
Inline callers:
  - kernel/auditsc.c:__audit_log_nfcfg
```
```
In kernel/watchdog.c (ffffffff8124750c)
Location: include/linux/sched.h:1560
Inline: True
Inline callers:
  - kernel/watchdog.c:watchdog_timer_fn
```
```
In kernel/trace/bpf_trace.c (ffffffff812a8c42)
Location: include/linux/sched.h:1560
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:bpf_tracing_func_proto
```
```
In mm/oom_kill.c (ffffffff813647ea)
Location: include/linux/sched.h:1560
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:oom_reaper
  - mm/oom_kill.c:oom_reaper
```
```
In mm/kfence/core.c (ffffffff8142eae1)
Location: include/linux/sched.h:1560
Inline: True
Inline callers:
  - mm/kfence/core.c:metadata_update_state
```
```
In fs/ioctl.c (ffffffff81497297)
Location: include/linux/sched.h:1560
Inline: True
Inline callers:
  - fs/ioctl.c:do_vfs_ioctl
```
```
In fs/binfmt_elf.c (ffffffff8151028f)
Location: include/linux/sched.h:1560
Inline: True
Inline callers:
  - fs/binfmt_elf.c:elf_map
```
```
In fs/compat_binfmt_elf.c (ffffffff815132f7)
Location: include/linux/sched.h:1560
Inline: True
```
```
In fs/coredump.c (ffffffff815188b1)
Location: include/linux/sched.h:1560
Inline: True
```
```
In fs/drop_caches.c (ffffffff81519c71)
Location: include/linux/sched.h:1560
Inline: True
Inline callers:
  - fs/drop_caches.c:drop_caches_sysctl_handler
```
```
In fs/proc/base.c (ffffffff81536819)
Location: include/linux/sched.h:1560
Inline: True
```
```
In fs/ext4/balloc.c (ffffffff815583de)
Location: include/linux/sched.h:1560
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_inode_to_goal_block
  - fs/ext4/balloc.c:ext4_inode_to_goal_block
```
```
In ipc/sem.c (ffffffff816409cd)
Location: include/linux/sched.h:1560
Inline: True
Inline callers:
  - ipc/sem.c:count_semcnt
```
```
In security/selinux/hooks.c (ffffffff81671b38)
Location: include/linux/sched.h:1560
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_netlink_send
```
```
In security/tomoyo/audit.c (ffffffff816a6299)
Location: include/linux/sched.h:1560
Inline: True
Inline callers:
  - security/tomoyo/audit.c:tomoyo_print_header
```
```
In security/integrity/integrity_audit.c (ffffffff816f3ddd)
Location: include/linux/sched.h:1560
Inline: True
Inline callers:
  - security/integrity/integrity_audit.c:integrity_audit_message
```
```
In io_uring/fdinfo.c (ffffffff8179b8b1)
Location: include/linux/sched.h:1560
Inline: True
Inline callers:
  - io_uring/fdinfo.c:__io_uring_show_fdinfo
```
```
In drivers/pci/quirks.c (ffffffff81908957)
Location: include/linux/sched.h:1560
Inline: True
Inline callers:
  - drivers/pci/quirks.c:pci_fixup_device
```
```
In drivers/tty/tty_io.c (ffffffff81a4c838)
Location: include/linux/sched.h:1560
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:__do_SAK
  - drivers/tty/tty_io.c:__do_SAK
  - drivers/tty/tty_io.c:__do_SAK
```
```
In drivers/tty/tty_audit.c (ffffffff81a5999d)
Location: include/linux/sched.h:1560
Inline: True
Inline callers:
  - drivers/tty/tty_audit.c:tty_audit_log
```
```
In drivers/base/power/main.c (ffffffff81b03c45)
Location: include/linux/sched.h:1560
Inline: True
```
```
In drivers/cdrom/cdrom.c (ffffffff81c0a19c)
Location: include/linux/sched.h:1560
Inline: True
Inline callers:
  - drivers/cdrom/cdrom.c:open_for_data
```
```
In drivers/usb/core/devio.c (ffffffff81c33158)
Location: include/linux/sched.h:1560
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_open
  - drivers/usb/core/devio.c:check_ctrlrecip
  - drivers/usb/core/devio.c:checkintf
```
```
In drivers/md/md.c (ffffffff81cf26bb)
Location: include/linux/sched.h:1560
Inline: True
Inline callers:
  - drivers/md/md.c:md_unregister_thread
```
```
In net/core/sock.c (ffffffff81d9bee2)
Location: include/linux/sched.h:1560
Inline: True
Inline callers:
  - net/core/sock.c:sock_set_timeout
```
```
In net/ipv4/tcp.c (ffffffff81eb0342)
Location: include/linux/sched.h:1560
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg_locked
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
In init/main.c (ffffffff81000f0c)
Location: include/linux/sched.h:1569
Inline: True
Inline callers:
  - init/main.c:trace_initcall_start_cb
```
```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff81004b75)
Location: include/linux/sched.h:1569
Inline: True
```
```
In arch/x86/kernel/signal.c (ffffffff8104bffe)
Location: include/linux/sched.h:1569
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:signal_fault
  - arch/x86/kernel/signal.c:get_sigframe
```
```
In arch/x86/kernel/traps.c (ffffffff8213cdc1)
Location: include/linux/sched.h:1569
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:exc_general_protection
  - arch/x86/kernel/traps.c:exc_general_protection
```
```
In arch/x86/kernel/umip.c (ffffffff810bddc5)
Location: include/linux/sched.h:1569
Inline: True
Inline callers:
  - arch/x86/kernel/umip.c:umip_printk
```
```
In arch/x86/mm/fault.c (ffffffff810c7aba)
Location: include/linux/sched.h:1569
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:__bad_area_nosemaphore
  - arch/x86/mm/fault.c:__bad_area_nosemaphore
```
```
In arch/x86/net/bpf_jit_comp.c (ffffffff810ef371)
Location: include/linux/sched.h:1569
Inline: True
Inline callers:
  - arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile
```
```
In kernel/exit.c (ffffffff810fdf9d)
Location: include/linux/sched.h:1569
Inline: True
Inline callers:
  - kernel/exit.c:make_task_dead
  - kernel/exit.c:make_task_dead
```
```
In kernel/workqueue.c (ffffffff811242c0)
Location: include/linux/sched.h:1569
Inline: True
Inline callers:
  - kernel/workqueue.c:show_all_workqueues
  - kernel/workqueue.c:show_all_workqueues
  - kernel/workqueue.c:show_pwq
  - kernel/workqueue.c:show_pwq
  - kernel/workqueue.c:process_one_work
```
```
In kernel/async.c (ffffffff8113607e)
Location: include/linux/sched.h:1569
Inline: True
Inline callers:
  - kernel/async.c:async_synchronize_cookie_domain
  - kernel/async.c:async_synchronize_cookie_domain
  - kernel/async.c:async_run_entry_fn
```
```
In kernel/sched/core.c (ffffffff811441e4)
Location: include/linux/sched.h:1569
Inline: True
Inline callers:
  - kernel/sched/core.c:select_fallback_rq
  - kernel/sched/core.c:force_compatible_cpus_allowed_ptr
  - kernel/sched/core.c:perf_trace_sched_numa_pair_template
  - kernel/sched/core.c:perf_trace_sched_numa_pair_template
  - kernel/sched/core.c:perf_trace_sched_move_numa
  - kernel/sched/core.c:trace_event_raw_event_sched_numa_pair_template
  - kernel/sched/core.c:trace_event_raw_event_sched_numa_pair_template
  - kernel/sched/core.c:trace_event_raw_event_sched_move_numa
```
```
In kernel/sched/build_policy.c (ffffffff811705da)
Location: include/linux/sched.h:1569
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:enqueue_task_dl
```
```
In kernel/sched/build_utility.c (ffffffff8117bb92)
Location: include/linux/sched.h:1569
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:print_cpu
  - kernel/sched/build_utility.c:print_cpu
```
```
In kernel/locking/rtmutex_api.c (ffffffff82156990)
Location: include/linux/sched.h:1569
Inline: True
Inline callers:
  - kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain
```
```
In kernel/printk/printk.c (ffffffff811a3061)
Location: include/linux/sched.h:1569
Inline: True
Inline callers:
  - kernel/printk/printk.c:vprintk_store
  - kernel/printk/printk.c:check_syslog_permissions
```
```
In kernel/time/posix-cpu-timers.c (ffffffff811feb43)
Location: include/linux/sched.h:1569
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:posix_cpu_timers_work
  - kernel/time/posix-cpu-timers.c:posix_cpu_timers_work
  - kernel/time/posix-cpu-timers.c:check_process_timers
  - kernel/time/posix-cpu-timers.c:check_process_timers
```
```
In kernel/audit.c (ffffffff8123d54b)
Location: include/linux/sched.h:1569
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_multicast
```
```
In kernel/auditfilter.c (ffffffff81241bca)
Location: include/linux/sched.h:1569
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_filter
```
```
In kernel/auditsc.c (ffffffff812428d4)
Location: include/linux/sched.h:1569
Inline: True
Inline callers:
  - kernel/auditsc.c:__audit_log_nfcfg
```
```
In kernel/watchdog.c (ffffffff8125e5cc)
Location: include/linux/sched.h:1569
Inline: True
Inline callers:
  - kernel/watchdog.c:watchdog_timer_fn
```
```
In kernel/trace/bpf_trace.c (ffffffff812cb475)
Location: include/linux/sched.h:1569
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:bpf_tracing_func_proto
```
```
In mm/oom_kill.c (ffffffff81396cc4)
Location: include/linux/sched.h:1569
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:oom_reaper
  - mm/oom_kill.c:oom_reaper
```
```
In mm/gup.c (ffffffff813e267d)
Location: include/linux/sched.h:1569
Inline: True
Inline callers:
  - mm/gup.c:gup_vma_lookup
```
```
In mm/kfence/core.c (ffffffff81464239)
Location: include/linux/sched.h:1569
Inline: True
Inline callers:
  - mm/kfence/core.c:metadata_update_state
```
```
In mm/memfd.c (ffffffff814a5fdf)
Location: include/linux/sched.h:1569
Inline: True
Inline callers:
  - mm/memfd.c:__do_sys_memfd_create
  - mm/memfd.c:__do_sys_memfd_create
```
```
In fs/ioctl.c (ffffffff814cc2fa)
Location: include/linux/sched.h:1569
Inline: True
Inline callers:
  - fs/ioctl.c:do_vfs_ioctl
```
```
In fs/binfmt_elf.c (ffffffff81547bbd)
Location: include/linux/sched.h:1569
Inline: True
Inline callers:
  - fs/binfmt_elf.c:elf_map
```
```
In fs/compat_binfmt_elf.c (ffffffff8154ad45)
Location: include/linux/sched.h:1569
Inline: True
```
```
In fs/coredump.c (ffffffff815502b8)
Location: include/linux/sched.h:1569
Inline: True
```
```
In fs/drop_caches.c (ffffffff81551578)
Location: include/linux/sched.h:1569
Inline: True
Inline callers:
  - fs/drop_caches.c:drop_caches_sysctl_handler
```
```
In fs/proc/base.c (ffffffff8156e9d7)
Location: include/linux/sched.h:1569
Inline: True
```
```
In fs/ext4/balloc.c (ffffffff8159022a)
Location: include/linux/sched.h:1569
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_inode_to_goal_block
  - fs/ext4/balloc.c:ext4_inode_to_goal_block
```
```
In ipc/sem.c (ffffffff81678f25)
Location: include/linux/sched.h:1569
Inline: True
Inline callers:
  - ipc/sem.c:count_semcnt
```
```
In security/selinux/hooks.c (ffffffff816aa30d)
Location: include/linux/sched.h:1569
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_netlink_send
```
```
In security/tomoyo/audit.c (ffffffff816dec79)
Location: include/linux/sched.h:1569
Inline: True
Inline callers:
  - security/tomoyo/audit.c:tomoyo_print_header
```
```
In security/integrity/integrity_audit.c (ffffffff8172df0d)
Location: include/linux/sched.h:1569
Inline: True
Inline callers:
  - security/integrity/integrity_audit.c:integrity_audit_message
```
```
In io_uring/fdinfo.c (ffffffff817dc9d6)
Location: include/linux/sched.h:1569
Inline: True
Inline callers:
  - io_uring/fdinfo.c:__io_uring_show_fdinfo
```
```
In drivers/pci/quirks.c (ffffffff8194bf80)
Location: include/linux/sched.h:1569
Inline: True
Inline callers:
  - drivers/pci/quirks.c:pci_fixup_device
```
```
In drivers/tty/tty_io.c (ffffffff81a96b28)
Location: include/linux/sched.h:1569
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:__do_SAK
  - drivers/tty/tty_io.c:__do_SAK
  - drivers/tty/tty_io.c:__do_SAK
```
```
In drivers/tty/tty_audit.c (ffffffff81aa3fcd)
Location: include/linux/sched.h:1569
Inline: True
Inline callers:
  - drivers/tty/tty_audit.c:tty_audit_log
```
```
In drivers/base/power/main.c (ffffffff81b51ca5)
Location: include/linux/sched.h:1569
Inline: True
```
```
In drivers/cdrom/cdrom.c (ffffffff81c710cb)
Location: include/linux/sched.h:1569
Inline: True
Inline callers:
  - drivers/cdrom/cdrom.c:open_for_data
```
```
In drivers/usb/core/devio.c (ffffffff81c9b0f2)
Location: include/linux/sched.h:1569
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_open
  - drivers/usb/core/devio.c:check_ctrlrecip
  - drivers/usb/core/devio.c:checkintf
```
```
In drivers/md/md.c (ffffffff81d5a573)
Location: include/linux/sched.h:1569
Inline: True
Inline callers:
  - drivers/md/md.c:md_unregister_thread
```
```
In net/core/sock.c (ffffffff81e0a71b)
Location: include/linux/sched.h:1569
Inline: True
Inline callers:
  - net/core/sock.c:sock_set_timeout
```
```
In net/ipv4/tcp.c (ffffffff81f0e6ce)
Location: include/linux/sched.h:1569
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg_locked
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
In init/main.c (ffffffff81000f1c)
Location: include/linux/pid.h:228
Inline: True
Inline callers:
  - init/main.c:trace_initcall_start_cb
```
```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff81007485)
Location: include/linux/pid.h:228
Inline: True
```
```
In arch/x86/kernel/signal.c (ffffffff8105327e)
Location: include/linux/pid.h:228
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:signal_fault
  - arch/x86/kernel/signal.c:get_sigframe
```
```
In arch/x86/kernel/traps.c (ffffffff8221ede3)
Location: include/linux/pid.h:228
Inline: True
Inline callers:
  - arch/x86/kernel/traps.c:exc_general_protection
  - arch/x86/kernel/traps.c:exc_general_protection
```
```
In arch/x86/kernel/umip.c (ffffffff810c4f45)
Location: include/linux/pid.h:228
Inline: True
Inline callers:
  - arch/x86/kernel/umip.c:umip_printk
```
```
In arch/x86/kernel/cet.c (ffffffff810ca063)
Location: include/linux/pid.h:228
Inline: True
Inline callers:
  - arch/x86/kernel/cet.c:do_user_cp_fault
```
```
In arch/x86/mm/fault.c (ffffffff810cff8a)
Location: include/linux/pid.h:228
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:__bad_area_nosemaphore
  - arch/x86/mm/fault.c:__bad_area_nosemaphore
```
```
In arch/x86/net/bpf_jit_comp.c (ffffffff810f8631)
Location: include/linux/pid.h:228
Inline: True
Inline callers:
  - arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile
```
```
In kernel/exit.c (ffffffff81106c4d)
Location: include/linux/pid.h:228
Inline: True
Inline callers:
  - kernel/exit.c:make_task_dead
  - kernel/exit.c:make_task_dead
```
```
In kernel/workqueue.c (ffffffff8112e9c0)
Location: include/linux/pid.h:228
Inline: True
Inline callers:
  - kernel/workqueue.c:show_all_workqueues
  - kernel/workqueue.c:show_all_workqueues
  - kernel/workqueue.c:show_pwq
  - kernel/workqueue.c:show_pwq
  - kernel/workqueue.c:process_one_work
```
```
In kernel/async.c (ffffffff8114122e)
Location: include/linux/pid.h:228
Inline: True
Inline callers:
  - kernel/async.c:async_synchronize_cookie_domain
  - kernel/async.c:async_synchronize_cookie_domain
  - kernel/async.c:async_run_entry_fn
```
```
In kernel/sched/core.c (ffffffff8114f704)
Location: include/linux/pid.h:228
Inline: True
Inline callers:
  - kernel/sched/core.c:select_fallback_rq
  - kernel/sched/core.c:force_compatible_cpus_allowed_ptr
  - kernel/sched/core.c:perf_trace_sched_numa_pair_template
  - kernel/sched/core.c:perf_trace_sched_numa_pair_template
  - kernel/sched/core.c:perf_trace_sched_move_numa
  - kernel/sched/core.c:trace_event_raw_event_sched_numa_pair_template
  - kernel/sched/core.c:trace_event_raw_event_sched_numa_pair_template
  - kernel/sched/core.c:trace_event_raw_event_sched_move_numa
```
```
In kernel/sched/build_policy.c (ffffffff8117dfdb)
Location: include/linux/pid.h:228
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:enqueue_task_dl
```
```
In kernel/sched/build_utility.c (ffffffff81189872)
Location: include/linux/pid.h:228
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:print_cpu
  - kernel/sched/build_utility.c:print_cpu
```
```
In kernel/locking/rtmutex_api.c (ffffffff822397d0)
Location: include/linux/pid.h:228
Inline: True
Inline callers:
  - kernel/locking/rtmutex_api.c:rt_mutex_adjust_prio_chain
```
```
In kernel/printk/printk.c (ffffffff811b0f21)
Location: include/linux/pid.h:228
Inline: True
Inline callers:
  - kernel/printk/printk.c:vprintk_store
  - kernel/printk/printk.c:check_syslog_permissions
```
```
In kernel/time/posix-cpu-timers.c (ffffffff81214dc8)
Location: include/linux/pid.h:228
Inline: True
Inline callers:
  - kernel/time/posix-cpu-timers.c:check_process_timers
  - kernel/time/posix-cpu-timers.c:check_process_timers
  - kernel/time/posix-cpu-timers.c:check_thread_timers
  - kernel/time/posix-cpu-timers.c:check_thread_timers
```
```
In kernel/audit.c (ffffffff81257463)
Location: include/linux/pid.h:228
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_multicast
```
```
In kernel/auditfilter.c (ffffffff8125b9df)
Location: include/linux/pid.h:228
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_filter
```
```
In kernel/auditsc.c (ffffffff8125c854)
Location: include/linux/pid.h:228
Inline: True
Inline callers:
  - kernel/auditsc.c:__audit_log_nfcfg
```
```
In kernel/watchdog.c (ffffffff81278531)
Location: include/linux/pid.h:228
Inline: True
Inline callers:
  - kernel/watchdog.c:watchdog_timer_fn
```
```
In kernel/trace/bpf_trace.c (ffffffff812e8715)
Location: include/linux/pid.h:228
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:bpf_tracing_func_proto
```
```
In mm/oom_kill.c (ffffffff813c0a34)
Location: include/linux/pid.h:228
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:oom_reaper
  - mm/oom_kill.c:oom_reaper
```
```
In mm/gup.c (ffffffff8140cead)
Location: include/linux/pid.h:228
Inline: True
Inline callers:
  - mm/gup.c:gup_vma_lookup
```
```
In mm/kfence/core.c (ffffffff814935b9)
Location: include/linux/pid.h:228
Inline: True
Inline callers:
  - mm/kfence/core.c:metadata_update_state
```
```
In mm/memfd.c (ffffffff814d6fed)
Location: include/linux/pid.h:228
Inline: True
Inline callers:
  - mm/memfd.c:__do_sys_memfd_create
```
```
In fs/ioctl.c (ffffffff814febb9)
Location: include/linux/pid.h:228
Inline: True
Inline callers:
  - fs/ioctl.c:do_vfs_ioctl
```
```
In fs/binfmt_elf.c (ffffffff8157ced1)
Location: include/linux/pid.h:228
Inline: True
Inline callers:
  - fs/binfmt_elf.c:elf_load
```
```
In fs/compat_binfmt_elf.c (ffffffff8157ff0c)
Location: include/linux/pid.h:228
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:elf_load
```
```
In fs/coredump.c (ffffffff81586147)
Location: include/linux/pid.h:228
Inline: True
```
```
In fs/drop_caches.c (ffffffff8158747d)
Location: include/linux/pid.h:228
Inline: True
Inline callers:
  - fs/drop_caches.c:drop_caches_sysctl_handler
```
```
In fs/proc/base.c (ffffffff815a7397)
Location: include/linux/pid.h:228
Inline: True
```
```
In fs/ext4/balloc.c (ffffffff815c8f6a)
Location: include/linux/pid.h:228
Inline: True
Inline callers:
  - fs/ext4/balloc.c:ext4_inode_to_goal_block
  - fs/ext4/balloc.c:ext4_inode_to_goal_block
```
```
In ipc/sem.c (ffffffff816b5315)
Location: include/linux/pid.h:228
Inline: True
Inline callers:
  - ipc/sem.c:count_semcnt
```
```
In security/selinux/hooks.c (ffffffff816e710d)
Location: include/linux/pid.h:228
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_netlink_send
```
```
In security/tomoyo/audit.c (ffffffff8171b848)
Location: include/linux/pid.h:228
Inline: True
Inline callers:
  - security/tomoyo/audit.c:tomoyo_print_header
```
```
In security/integrity/integrity_audit.c (ffffffff8176e86d)
Location: include/linux/pid.h:228
Inline: True
Inline callers:
  - security/integrity/integrity_audit.c:integrity_audit_message
```
```
In drivers/pci/quirks.c (ffffffff81995250)
Location: include/linux/pid.h:228
Inline: True
Inline callers:
  - drivers/pci/quirks.c:pci_fixup_device
```
```
In drivers/tty/tty_io.c (ffffffff81ae9518)
Location: include/linux/pid.h:228
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:__do_SAK
  - drivers/tty/tty_io.c:__do_SAK
  - drivers/tty/tty_io.c:__do_SAK
```
```
In drivers/tty/tty_audit.c (ffffffff81af698d)
Location: include/linux/pid.h:228
Inline: True
Inline callers:
  - drivers/tty/tty_audit.c:tty_audit_log
```
```
In drivers/base/power/main.c (ffffffff81baa295)
Location: include/linux/pid.h:228
Inline: True
```
```
In drivers/gpu/drm/drm_file.c (ffffffff81c97aa5)
Location: include/linux/pid.h:228
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_file.c:drm_open_helper
  - drivers/gpu/drm/drm_file.c:drm_file_free
```
```
In drivers/gpu/drm/drm_ioctl.c (ffffffff81c9e90b)
Location: include/linux/pid.h:228
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_ioctl.c:drm_ioctl
  - drivers/gpu/drm/drm_ioctl.c:drm_ioctl
  - drivers/gpu/drm/drm_ioctl.c:drm_ioctl
```
```
In drivers/gpu/drm/drm_ioc32.c (ffffffff81cb92f2)
Location: include/linux/pid.h:228
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_ioc32.c:drm_compat_ioctl
```
```
In drivers/cdrom/cdrom.c (ffffffff81d2597b)
Location: include/linux/pid.h:228
Inline: True
Inline callers:
  - drivers/cdrom/cdrom.c:open_for_data
```
```
In drivers/usb/core/devio.c (ffffffff81d4fcb3)
Location: include/linux/pid.h:228
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_open
  - drivers/usb/core/devio.c:check_ctrlrecip
  - drivers/usb/core/devio.c:checkintf
```
```
In drivers/md/md.c (ffffffff81e119b3)
Location: include/linux/pid.h:228
Inline: True
Inline callers:
  - drivers/md/md.c:md_unregister_thread
```
```
In net/core/sock.c (ffffffff81ec7116)
Location: include/linux/pid.h:228
Inline: True
Inline callers:
  - net/core/sock.c:sock_set_timeout
```
```
In net/core/netdev-genl.c (ffffffff81f3d934)
Location: include/linux/pid.h:228
Inline: True
Inline callers:
  - net/core/netdev-genl.c:netdev_nl_napi_fill_one
```
```
In net/ipv4/tcp.c (ffffffff81fd26e2)
Location: include/linux/pid.h:228
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg_locked
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
In init/main.c (ffff8000100850c4)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - init/main.c:trace_initcall_start_cb
```
```
In arch/arm64/kernel/traps.c (ffff800010093e68)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - arch/arm64/kernel/traps.c:arm64_show_signal
```
```
In arch/arm64/net/bpf_jit_comp.c (ffff8000100b4de4)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - arch/arm64/net/bpf_jit_comp.c:bpf_int_jit_compile
```
```
In virt/kvm/kvm_main.c (ffff8000100bfa44)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - virt/kvm/kvm_main.c:kvm_vm_create_worker_thread
  - virt/kvm/kvm_main.c:kvm_vm_worker_thread
```
```
In virt/kvm/arm/arm.c (ffff8000100c7e78)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - virt/kvm/arm/arm.c:kvm_arch_init
  - virt/kvm/arm/arm.c:kvm_arch_init
  - virt/kvm/arm/arm.c:kvm_arch_init
  - virt/kvm/arm/arm.c:init_hyp_mode
  - virt/kvm/arm/arm.c:init_hyp_mode
  - virt/kvm/arm/arm.c:init_hyp_mode
  - virt/kvm/arm/arm.c:init_hyp_mode
  - virt/kvm/arm/arm.c:init_hyp_mode
  - virt/kvm/arm/arm.c:init_hyp_mode
  - virt/kvm/arm/arm.c:init_hyp_mode
  - virt/kvm/arm/arm.c:init_hyp_mode
```
```
In virt/kvm/arm/mmu.c (ffff8000100cccec)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - virt/kvm/arm/mmu.c:kvm_mmu_init
  - virt/kvm/arm/mmu.c:kvm_mmu_init
  - virt/kvm/arm/mmu.c:kvm_mmu_init
  - virt/kvm/arm/mmu.c:kvm_mmu_init
  - virt/kvm/arm/mmu.c:kvm_mmu_init
  - virt/kvm/arm/mmu.c:kvm_mmu_init
  - virt/kvm/arm/mmu.c:kvm_handle_guest_abort
  - virt/kvm/arm/mmu.c:user_mem_abort
  - virt/kvm/arm/mmu.c:user_mem_abort
  - virt/kvm/arm/mmu.c:kvm_alloc_stage2_pgd
  - virt/kvm/arm/mmu.c:__create_hyp_mappings
  - virt/kvm/arm/mmu.c:__create_hyp_mappings
  - virt/kvm/arm/mmu.c:__create_hyp_mappings
```
```
In virt/kvm/arm/mmio.c (ffff8000100cde54)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - virt/kvm/arm/mmio.c:io_mem_abort
```
```
In arch/arm64/kvm/handle_exit.c (ffff8000100d01c0)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - arch/arm64/kvm/handle_exit.c:kvm_handle_guest_debug
```
```
In arch/arm64/kvm/reset.c (ffff8000100d4e70)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - arch/arm64/kvm/reset.c:kvm_set_ipa_limit
```
```
In arch/arm64/kvm/sys_regs.c (ffff8000100d7028)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - arch/arm64/kvm/sys_regs.c:check_sysreg_table
  - arch/arm64/kvm/sys_regs.c:kvm_handle_sys_reg
  - arch/arm64/kvm/sys_regs.c:unhandled_cp_access
```
```
In virt/kvm/arm/vgic/vgic.c (ffff8000100dc7dc)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - virt/kvm/arm/vgic/vgic.c:kvm_vgic_map_phys_irq
```
```
In virt/kvm/arm/vgic/vgic-init.c (ffff8000100de3fc)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - virt/kvm/arm/vgic/vgic-init.c:kvm_vgic_hyp_init
  - virt/kvm/arm/vgic/vgic-init.c:kvm_vgic_hyp_init
  - virt/kvm/arm/vgic/vgic-init.c:kvm_vgic_hyp_init
  - virt/kvm/arm/vgic/vgic-init.c:kvm_vgic_hyp_init
  - virt/kvm/arm/vgic/vgic-init.c:kvm_vgic_hyp_init
```
```
In virt/kvm/arm/vgic/vgic-v2.c (ffff8000100df024)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - virt/kvm/arm/vgic/vgic-v2.c:vgic_v2_probe
  - virt/kvm/arm/vgic/vgic-v2.c:vgic_v2_probe
  - virt/kvm/arm/vgic/vgic-v2.c:vgic_v2_probe
  - virt/kvm/arm/vgic/vgic-v2.c:vgic_v2_probe
  - virt/kvm/arm/vgic/vgic-v2.c:vgic_v2_probe
  - virt/kvm/arm/vgic/vgic-v2.c:vgic_v2_probe
  - virt/kvm/arm/vgic/vgic-v2.c:vgic_v2_map_resources
  - virt/kvm/arm/vgic/vgic-v2.c:vgic_v2_map_resources
  - virt/kvm/arm/vgic/vgic-v2.c:vgic_v2_map_resources
  - virt/kvm/arm/vgic/vgic-v2.c:vgic_v2_map_resources
  - virt/kvm/arm/vgic/vgic-v2.c:vgic_v2_map_resources
```
```
In virt/kvm/arm/vgic/vgic-v3.c (ffff8000100e029c)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - virt/kvm/arm/vgic/vgic-v3.c:vgic_v3_probe
  - virt/kvm/arm/vgic/vgic-v3.c:vgic_v3_probe
  - virt/kvm/arm/vgic/vgic-v3.c:vgic_v3_probe
  - virt/kvm/arm/vgic/vgic-v3.c:vgic_v3_probe
  - virt/kvm/arm/vgic/vgic-v3.c:vgic_v3_probe
  - virt/kvm/arm/vgic/vgic-v3.c:vgic_v3_probe
  - virt/kvm/arm/vgic/vgic-v3.c:vgic_v3_probe
  - virt/kvm/arm/vgic/vgic-v3.c:vgic_v3_map_resources
  - virt/kvm/arm/vgic/vgic-v3.c:vgic_v3_map_resources
  - virt/kvm/arm/vgic/vgic-v3.c:vgic_v3_map_resources
  - virt/kvm/arm/vgic/vgic-v3.c:vgic_v3_map_resources
```
```
In virt/kvm/arm/vgic/vgic-v4.c (ffff8000100e0ac0)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - virt/kvm/arm/vgic/vgic-v4.c:vgic_v4_init
  - virt/kvm/arm/vgic/vgic-v4.c:vgic_v4_init
```
```
In virt/kvm/arm/arch_timer.c (ffff8000100ede54)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - virt/kvm/arm/arch_timer.c:kvm_timer_enable
  - virt/kvm/arm/arch_timer.c:kvm_timer_hyp_init
  - virt/kvm/arm/arch_timer.c:kvm_timer_hyp_init
  - virt/kvm/arm/arch_timer.c:kvm_timer_hyp_init
  - virt/kvm/arm/arch_timer.c:kvm_timer_hyp_init
  - virt/kvm/arm/arch_timer.c:kvm_timer_hyp_init
  - virt/kvm/arm/arch_timer.c:kvm_timer_hyp_init
  - virt/kvm/arm/arch_timer.c:kvm_timer_hyp_init
  - virt/kvm/arm/arch_timer.c:kvm_timer_hyp_init
  - virt/kvm/arm/arch_timer.c:kvm_timer_hyp_init
  - virt/kvm/arm/arch_timer.c:kvm_timer_hyp_init
```
```
In virt/kvm/arm/pmu.c (ffff8000100ef654)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - virt/kvm/arm/pmu.c:kvm_arm_pmu_v3_set_attr
```
```
In kernel/exit.c (ffff8000100fdbc4)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/umh.c (ffff80001011b224)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - kernel/umh.c:call_usermodehelper_exec_async
```
```
In kernel/workqueue.c (ffff8000101224ac)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - kernel/workqueue.c:show_workqueue_state
  - kernel/workqueue.c:show_workqueue_state
  - kernel/workqueue.c:show_workqueue_state
  - kernel/workqueue.c:pr_cont_work
  - kernel/workqueue.c:process_one_work
```
```
In kernel/async.c (ffff80001012e754)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - kernel/async.c:async_synchronize_cookie_domain
  - kernel/async.c:async_synchronize_cookie_domain
  - kernel/async.c:async_run_entry_fn
```
```
In kernel/sched/core.c (ffff8000101395ac)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - kernel/sched/core.c:select_fallback_rq
  - kernel/sched/core.c:perf_trace_sched_swap_numa
  - kernel/sched/core.c:perf_trace_sched_swap_numa
  - kernel/sched/core.c:perf_trace_sched_move_task_template
  - kernel/sched/core.c:trace_event_raw_event_sched_swap_numa
  - kernel/sched/core.c:trace_event_raw_event_sched_swap_numa
  - kernel/sched/core.c:trace_event_raw_event_sched_move_task_template
```
```
In kernel/sched/debug.c (ffff800010161480)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - kernel/sched/debug.c:print_cpu
  - kernel/sched/debug.c:print_cpu
```
```
In kernel/locking/rtmutex.c (ffff80001016b9a0)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
```
```
In kernel/printk/printk.c (ffff800010175698)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - kernel/printk/printk.c:vprintk_store
  - kernel/printk/printk.c:check_syslog_permissions
```
```
In kernel/time/posix-cpu-timers.c (ffff8000101ad6d0)
Location: include/linux/sched.h:1306
Inline: True
```
```
In kernel/auditfilter.c (ffff8000101ee838)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_filter
```
```
In kernel/watchdog.c (ffff8000102074a4)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - kernel/watchdog.c:watchdog_timer_fn
```
```
In kernel/trace/bpf_trace.c (ffff80001024cf58)
Location: include/linux/sched.h:1306
Inline: True
```
```
In mm/oom_kill.c (ffff8000102b78c0)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:oom_reaper
  - mm/oom_kill.c:oom_reaper
```
```
In fs/fs-writeback.c (ffff8000103c3990)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - fs/fs-writeback.c:block_dump___mark_inode_dirty
```
```
In fs/binfmt_elf.c (ffff80001041dfcc)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - fs/binfmt_elf.c:elf_map
```
```
In fs/compat_binfmt_elf.c (ffff80001042175c)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:elf_map
```
```
In fs/coredump.c (ffff800010428248)
Location: include/linux/sched.h:1306
Inline: True
```
```
In fs/drop_caches.c (ffff8000104291c4)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - fs/drop_caches.c:drop_caches_sysctl_handler
```
```
In fs/proc/base.c (ffff80001043f940)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - fs/proc/base.c:__set_oom_adj
  - fs/proc/base.c:__set_oom_adj
```
```
In ipc/sem.c (ffff8000105216cc)
Location: include/linux/sched.h:1306
Inline: True
```
```
In security/selinux/hooks.c (ffff80001054bb78)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_netlink_send
```
```
In security/tomoyo/audit.c (ffff800010577ac8)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - security/tomoyo/audit.c:tomoyo_print_header
```
```
In security/integrity/integrity_audit.c (ffff8000105acba4)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - security/integrity/integrity_audit.c:integrity_audit_msg
```
```
In block/blk-core.c (ffff8000105e389c)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - block/blk-core.c:submit_bio
```
```
In drivers/irqchip/irq-gic-v4.c (ffff8000106751a4)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic-v4.c:its_alloc_vcpu_irqs
```
```
In drivers/pci/quirks.c (ffff8000106fa9fc)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - drivers/pci/quirks.c:pci_do_fixups
```
```
In drivers/tty/tty_io.c (ffff800010850264)
Location: include/linux/sched.h:1306
Inline: True
```
```
In drivers/tty/tty_audit.c (ffff800010863280)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - drivers/tty/tty_audit.c:tty_audit_log
```
```
In drivers/base/power/main.c (ffff800010903600)
Location: include/linux/sched.h:1306
Inline: True
```
```
In drivers/cdrom/cdrom.c (ffff800010a0a1e8)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - drivers/cdrom/cdrom.c:open_for_data
```
```
In drivers/usb/core/devio.c (ffff800010a327cc)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_open
  - drivers/usb/core/devio.c:check_ctrlrecip
  - drivers/usb/core/devio.c:checkintf
```
```
In drivers/md/md.c (ffff800010aedc5c)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - drivers/md/md.c:md_unregister_thread
```
```
In net/core/sock.c (ffff800010bac11c)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - net/core/sock.c:sock_set_timeout
```
```
In net/ipv4/tcp.c (ffff800010c71078)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
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
In init/main.c (c030387c)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - init/main.c:trace_initcall_start_cb
```
```
In arch/arm/kernel/traps.c (c030f538)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - arch/arm/kernel/traps.c:die
```
```
In arch/arm/mm/alignment.c (c0321874)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - arch/arm/mm/alignment.c:do_alignment
```
```
In arch/arm/net/bpf_jit_32.c (c032c7a8)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - arch/arm/net/bpf_jit_32.c:bpf_int_jit_compile
```
```
In kernel/exit.c (c035ae5c)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/umh.c (c036f684)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - kernel/umh.c:call_usermodehelper_exec_async
```
```
In kernel/workqueue.c (c0375e58)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - kernel/workqueue.c:show_workqueue_state
  - kernel/workqueue.c:show_workqueue_state
  - kernel/workqueue.c:show_workqueue_state
  - kernel/workqueue.c:pr_cont_work
  - kernel/workqueue.c:process_one_work
```
```
In kernel/async.c (c037e89c)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - kernel/async.c:async_synchronize_cookie_domain
  - kernel/async.c:async_synchronize_cookie_domain
  - kernel/async.c:async_run_entry_fn
```
```
In kernel/sched/core.c (c0380c38)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - kernel/sched/core.c:perf_trace_sched_swap_numa
  - kernel/sched/core.c:perf_trace_sched_swap_numa
  - kernel/sched/core.c:perf_trace_sched_move_task_template
  - kernel/sched/core.c:trace_event_raw_event_sched_swap_numa
  - kernel/sched/core.c:trace_event_raw_event_sched_swap_numa
  - kernel/sched/core.c:trace_event_raw_event_sched_move_task_template
```
```
In kernel/sched/debug.c (c03adc40)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - kernel/sched/debug.c:print_cpu
  - kernel/sched/debug.c:print_cpu
  - kernel/sched/debug.c:print_task
  - kernel/sched/debug.c:print_task
```
```
In kernel/locking/rtmutex.c (c03b7458)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
```
```
In kernel/printk/printk.c (c03c78ac)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - kernel/printk/printk.c:vprintk_store
  - kernel/printk/printk.c:check_syslog_permissions
```
```
In kernel/time/posix-cpu-timers.c (c03f8614)
Location: include/linux/sched.h:1306
Inline: True
```
```
In kernel/auditfilter.c (c042e854)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_filter
```
```
In kernel/watchdog.c (c04461ec)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - kernel/watchdog.c:watchdog_timer_fn
```
```
In kernel/trace/bpf_trace.c (c0480f5c)
Location: include/linux/sched.h:1306
Inline: True
```
```
In mm/oom_kill.c (c04e4520)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:oom_reaper
  - mm/oom_kill.c:oom_reaper
```
```
In fs/fs-writeback.c (c05a13f0)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - fs/fs-writeback.c:block_dump___mark_inode_dirty
```
```
In fs/binfmt_elf.c (c05e6890)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - fs/binfmt_elf.c:elf_map
```
```
In fs/coredump.c (c05f0e0c)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - fs/coredump.c:format_corename
```
```
In fs/drop_caches.c (c05f1d98)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - fs/drop_caches.c:drop_caches_sysctl_handler
```
```
In fs/proc/base.c (c06063a0)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - fs/proc/base.c:__set_oom_adj
  - fs/proc/base.c:__set_oom_adj
```
```
In ipc/sem.c (c06dc720)
Location: include/linux/sched.h:1306
Inline: True
```
```
In security/selinux/hooks.c (c0701eb8)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_netlink_send
```
```
In security/tomoyo/audit.c (c072a914)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - security/tomoyo/audit.c:tomoyo_print_header
```
```
In security/integrity/integrity_audit.c (c075c438)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - security/integrity/integrity_audit.c:integrity_audit_msg
```
```
In block/blk-core.c (c0790bb0)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - block/blk-core.c:submit_bio
```
```
In drivers/irqchip/irq-gic-v4.c (c081d568)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - drivers/irqchip/irq-gic-v4.c:its_alloc_vcpu_irqs
```
```
In drivers/pci/quirks.c (c0892ea4)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - drivers/pci/quirks.c:pci_do_fixups
```
```
In drivers/tty/tty_io.c (c095ca24)
Location: include/linux/sched.h:1306
Inline: True
```
```
In drivers/tty/tty_audit.c (c0968f50)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - drivers/tty/tty_audit.c:tty_audit_log
```
```
In drivers/base/power/main.c (c09ed8f8)
Location: include/linux/sched.h:1306
Inline: True
```
```
In drivers/cdrom/cdrom.c (c0ae1f84)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - drivers/cdrom/cdrom.c:open_for_data
```
```
In drivers/usb/core/devio.c (c0b06a48)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_open
  - drivers/usb/core/devio.c:check_ctrlrecip
  - drivers/usb/core/devio.c:checkintf
```
```
In drivers/md/md.c (c0bc7894)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - drivers/md/md.c:md_unregister_thread
```
```
In net/core/sock.c (c0ccae28)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - net/core/sock.c:sock_set_timeout
```
```
In net/ipv4/tcp.c (c0d803e0)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
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
In init/main.c (c0000000000103fc)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - init/main.c:trace_initcall_start_cb
```
```
In arch/powerpc/kernel/process.c (c00000000002030c)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - arch/powerpc/kernel/process.c:set_thread_tidr
```
```
In arch/powerpc/kernel/traps.c (c00000000002f610)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - arch/powerpc/kernel/traps.c:StackOverflow
```
```
In arch/powerpc/net/bpf_jit_comp64.c (c00000000010906c)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - arch/powerpc/net/bpf_jit_comp64.c:bpf_int_jit_compile
```
```
In kernel/exit.c (c000000000144c8c)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/umh.c (c00000000016291c)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - kernel/umh.c:call_usermodehelper_exec_async
```
```
In kernel/workqueue.c (c00000000016be94)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - kernel/workqueue.c:show_workqueue_state
  - kernel/workqueue.c:show_workqueue_state
  - kernel/workqueue.c:show_workqueue_state
  - kernel/workqueue.c:pr_cont_work
  - kernel/workqueue.c:process_one_work
```
```
In kernel/async.c (c000000000177984)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - kernel/async.c:async_synchronize_cookie_domain
  - kernel/async.c:async_synchronize_cookie_domain
  - kernel/async.c:async_run_entry_fn
```
```
In kernel/sched/core.c (c0000000001862b8)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - kernel/sched/core.c:select_fallback_rq
  - kernel/sched/core.c:perf_trace_sched_swap_numa
  - kernel/sched/core.c:perf_trace_sched_swap_numa
  - kernel/sched/core.c:perf_trace_sched_move_task_template
  - kernel/sched/core.c:trace_event_raw_event_sched_swap_numa
  - kernel/sched/core.c:trace_event_raw_event_sched_swap_numa
  - kernel/sched/core.c:trace_event_raw_event_sched_move_task_template
```
```
In kernel/sched/debug.c (c0000000001b714c)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - kernel/sched/debug.c:print_cpu
  - kernel/sched/debug.c:print_cpu
  - kernel/sched/debug.c:print_task
  - kernel/sched/debug.c:print_task
```
```
In kernel/locking/rtmutex.c (c0000000001c343c)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
```
```
In kernel/printk/printk.c (c0000000001cee30)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - kernel/printk/printk.c:vprintk_store
  - kernel/printk/printk.c:check_syslog_permissions
```
```
In kernel/time/posix-cpu-timers.c (c000000000211a58)
Location: include/linux/sched.h:1306
Inline: True
```
```
In kernel/auditfilter.c (c0000000002615b4)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_filter
```
```
In kernel/watchdog.c (c000000000283ac8)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - kernel/watchdog.c:watchdog_timer_fn
```
```
In kernel/trace/bpf_trace.c (c0000000002e9f58)
Location: include/linux/sched.h:1306
Inline: True
```
```
In mm/oom_kill.c (c00000000036f6d8)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:oom_reaper
  - mm/oom_kill.c:oom_reaper
```
```
In fs/fs-writeback.c (c0000000004c4c70)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - fs/fs-writeback.c:block_dump___mark_inode_dirty
```
```
In fs/binfmt_elf.c (c00000000052c97c)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - fs/binfmt_elf.c:elf_map
```
```
In fs/compat_binfmt_elf.c (c00000000053064c)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:elf_map
```
```
In fs/coredump.c (c000000000538160)
Location: include/linux/sched.h:1306
Inline: True
```
```
In fs/drop_caches.c (c000000000539554)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - fs/drop_caches.c:drop_caches_sysctl_handler
```
```
In fs/proc/base.c (c000000000554f58)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - fs/proc/base.c:__set_oom_adj
  - fs/proc/base.c:__set_oom_adj
```
```
In ipc/sem.c (c00000000066af08)
Location: include/linux/sched.h:1306
Inline: True
```
```
In security/selinux/hooks.c (c0000000006a40d8)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_netlink_send
```
```
In security/tomoyo/audit.c (c0000000006e1244)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - security/tomoyo/audit.c:tomoyo_print_header
```
```
In security/integrity/integrity_audit.c (c00000000072b004)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - security/integrity/integrity_audit.c:integrity_audit_msg
```
```
In block/blk-core.c (c0000000007772d4)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - block/blk-core.c:submit_bio
```
```
In drivers/pci/quirks.c (c000000000878484)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - drivers/pci/quirks.c:pci_do_fixups
```
```
In drivers/tty/tty_io.c (c0000000008f0788)
Location: include/linux/sched.h:1306
Inline: True
```
```
In drivers/tty/tty_audit.c (c000000000902014)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - drivers/tty/tty_audit.c:tty_audit_log
```
```
In drivers/base/power/main.c (c0000000009a1d08)
Location: include/linux/sched.h:1306
Inline: True
```
```
In drivers/vfio/vfio.c (c000000000aafc04)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_group_fops_unl_ioctl
  - drivers/vfio/vfio.c:vfio_del_group_dev
```
```
In drivers/cdrom/cdrom.c (c000000000abfba0)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - drivers/cdrom/cdrom.c:open_for_data
```
```
In drivers/usb/core/devio.c (c000000000aeff5c)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_open
  - drivers/usb/core/devio.c:check_ctrlrecip
  - drivers/usb/core/devio.c:checkintf
```
```
In drivers/md/md.c (c000000000bcf390)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - drivers/md/md.c:md_unregister_thread
```
```
In net/core/sock.c (c000000000c7eb20)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - net/core/sock.c:sock_set_timeout
```
```
In net/ipv4/tcp.c (c000000000d782e8)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
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
In init/main.c (ffffffe0000b44c4)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - init/main.c:trace_initcall_start_cb
```
```
In arch/riscv/kernel/signal.c (ffffffe0000b694a)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - arch/riscv/kernel/signal.c:sys_rt_sigreturn
```
```
In arch/riscv/kernel/traps.c (ffffffe0000b6d58)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - arch/riscv/kernel/traps.c:do_trap
```
```
In arch/riscv/net/bpf_jit_comp.c (ffffffe0000be2d2)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - arch/riscv/net/bpf_jit_comp.c:bpf_int_jit_compile
```
```
In kernel/exit.c (ffffffe0000c635c)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/umh.c (ffffffe0000d587e)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - kernel/umh.c:call_usermodehelper_exec_async
```
```
In kernel/workqueue.c (ffffffe0000daf12)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - kernel/workqueue.c:show_workqueue_state
  - kernel/workqueue.c:show_workqueue_state
  - kernel/workqueue.c:show_workqueue_state
  - kernel/workqueue.c:pr_cont_work
  - kernel/workqueue.c:process_one_work
```
```
In kernel/async.c (ffffffe0000e2912)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - kernel/async.c:async_synchronize_cookie_domain
  - kernel/async.c:async_synchronize_cookie_domain
  - kernel/async.c:async_run_entry_fn
```
```
In kernel/sched/core.c (ffffffe0000eaea4)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - kernel/sched/core.c:wake_up_new_task
  - kernel/sched/core.c:try_to_wake_up
  - kernel/sched/core.c:perf_trace_sched_swap_numa
  - kernel/sched/core.c:perf_trace_sched_swap_numa
  - kernel/sched/core.c:perf_trace_sched_move_task_template
  - kernel/sched/core.c:trace_event_raw_event_sched_swap_numa
  - kernel/sched/core.c:trace_event_raw_event_sched_swap_numa
  - kernel/sched/core.c:trace_event_raw_event_sched_move_task_template
```
```
In kernel/sched/debug.c (ffffffe000105260)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - kernel/sched/debug.c:print_cpu
  - kernel/sched/debug.c:print_cpu
  - kernel/sched/debug.c:print_task
  - kernel/sched/debug.c:print_task
```
```
In kernel/locking/rtmutex.c (ffffffe00010bdaa)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
```
```
In kernel/printk/printk.c (ffffffe000110e9e)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - kernel/printk/printk.c:vprintk_store
  - kernel/printk/printk.c:check_syslog_permissions
```
```
In kernel/time/posix-cpu-timers.c (ffffffe000137640)
Location: include/linux/sched.h:1306
Inline: True
```
```
In kernel/auditfilter.c (ffffffe0001628d2)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_filter
```
```
In kernel/watchdog.c (ffffffe000169b9a)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - kernel/watchdog.c:watchdog_timer_fn
```
```
In mm/oom_kill.c (ffffffe0001dbbac)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:oom_reaper
  - mm/oom_kill.c:oom_reaper
```
```
In fs/fs-writeback.c (ffffffe000283dc6)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - fs/fs-writeback.c:block_dump___mark_inode_dirty
```
```
In fs/binfmt_elf.c (ffffffe0002c0744)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - fs/binfmt_elf.c:elf_map
```
```
In fs/coredump.c (ffffffe0002c6314)
Location: include/linux/sched.h:1306
Inline: True
```
```
In fs/drop_caches.c (ffffffe0002c720e)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - fs/drop_caches.c:drop_caches_sysctl_handler
```
```
In fs/proc/base.c (ffffffe0002d7554)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - fs/proc/base.c:__set_oom_adj
  - fs/proc/base.c:__set_oom_adj
```
```
In ipc/sem.c (ffffffe000387932)
Location: include/linux/sched.h:1306
Inline: True
```
```
In security/selinux/hooks.c (ffffffe0003a6490)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_netlink_send
```
```
In security/tomoyo/audit.c (ffffffe0003c9f66)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - security/tomoyo/audit.c:tomoyo_print_header
```
```
In security/integrity/integrity_audit.c (ffffffe0003f51fa)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - security/integrity/integrity_audit.c:integrity_audit_msg
```
```
In block/blk-core.c (ffffffe000425330)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - block/blk-core.c:submit_bio
```
```
In drivers/pci/quirks.c (ffffffe0004caad6)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - drivers/pci/quirks.c:pci_do_fixups
```
```
In drivers/tty/tty_io.c (ffffffe00052e654)
Location: include/linux/sched.h:1306
Inline: True
```
```
In drivers/tty/tty_audit.c (ffffffe000539dac)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - drivers/tty/tty_audit.c:tty_audit_log
```
```
In drivers/cdrom/cdrom.c (ffffffe0006310cc)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - drivers/cdrom/cdrom.c:open_for_data
```
```
In drivers/usb/core/devio.c (ffffffe000650eba)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_open
  - drivers/usb/core/devio.c:check_ctrlrecip
  - drivers/usb/core/devio.c:checkintf
```
```
In drivers/md/md.c (ffffffe0006defd0)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - drivers/md/md.c:md_unregister_thread
```
```
In net/core/sock.c (ffffffe00073cc3c)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - net/core/sock.c:sock_set_timeout
```
```
In net/ipv4/tcp.c (ffffffe0007d6938)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
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
In init/main.c (ffffffff81002a65)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - init/main.c:trace_initcall_start_cb
```
```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff81005632)
Location: include/linux/sched.h:1306
Inline: True
```
```
In arch/x86/kernel/signal.c (ffffffff8103193f)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:signal_fault
```
```
In arch/x86/kernel/traps.c (ffffffff8103297c)
Location: include/linux/sched.h:1306
Inline: True
```
```
In arch/x86/kernel/umip.c (ffffffff8107a031)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - arch/x86/kernel/umip.c:umip_printk
```
```
In arch/x86/mm/fault.c (ffffffff8107f4c5)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:__bad_area_nosemaphore
  - arch/x86/mm/fault.c:__bad_area_nosemaphore
```
```
In arch/x86/net/bpf_jit_comp.c (ffffffff81096009)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile
```
```
In kernel/panic.c (ffffffff8109aff2)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - kernel/panic.c:refcount_error_report
```
```
In kernel/exit.c (ffffffff810a0b81)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/umh.c (ffffffff810b897a)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - kernel/umh.c:call_usermodehelper_exec_async
```
```
In kernel/workqueue.c (ffffffff810bfbcd)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - kernel/workqueue.c:show_workqueue_state
  - kernel/workqueue.c:show_workqueue_state
  - kernel/workqueue.c:show_workqueue_state
  - kernel/workqueue.c:pr_cont_work
  - kernel/workqueue.c:process_one_work
```
```
In kernel/async.c (ffffffff810c912b)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - kernel/async.c:async_synchronize_cookie_domain
  - kernel/async.c:async_synchronize_cookie_domain
  - kernel/async.c:async_run_entry_fn
```
```
In kernel/sched/core.c (ffffffff810d8d6b)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - kernel/sched/core.c:select_fallback_rq
  - kernel/sched/core.c:perf_trace_sched_swap_numa
  - kernel/sched/core.c:perf_trace_sched_swap_numa
  - kernel/sched/core.c:perf_trace_sched_move_task_template
  - kernel/sched/core.c:trace_event_raw_event_sched_swap_numa
  - kernel/sched/core.c:trace_event_raw_event_sched_swap_numa
  - kernel/sched/core.c:trace_event_raw_event_sched_move_task_template
```
```
In kernel/sched/debug.c (ffffffff810f5547)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - kernel/sched/debug.c:print_cpu
  - kernel/sched/debug.c:print_cpu
```
```
In kernel/locking/rtmutex.c (ffffffff810ff4b4)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
```
```
In kernel/printk/printk.c (ffffffff8110cc97)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - kernel/printk/printk.c:vprintk_store
  - kernel/printk/printk.c:check_syslog_permissions
```
```
In kernel/time/posix-cpu-timers.c (ffffffff8113ce20)
Location: include/linux/sched.h:1306
Inline: True
```
```
In kernel/auditfilter.c (ffffffff81171b0c)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_filter
```
```
In kernel/watchdog.c (ffffffff81188a44)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - kernel/watchdog.c:watchdog_timer_fn
```
```
In kernel/trace/bpf_trace.c (ffffffff811c7204)
Location: include/linux/sched.h:1306
Inline: True
```
```
In mm/oom_kill.c (ffffffff81222165)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:oom_reaper
  - mm/oom_kill.c:oom_reaper
```
```
In fs/fs-writeback.c (ffffffff81307cc9)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - fs/fs-writeback.c:block_dump___mark_inode_dirty
```
```
In fs/binfmt_elf.c (ffffffff813540cf)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - fs/binfmt_elf.c:elf_map
```
```
In fs/compat_binfmt_elf.c (ffffffff8135791e)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:elf_map
```
```
In fs/coredump.c (ffffffff8135a0ea)
Location: include/linux/sched.h:1306
Inline: True
```
```
In fs/drop_caches.c (ffffffff8135aeee)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - fs/drop_caches.c:drop_caches_sysctl_handler
```
```
In fs/proc/base.c (ffffffff8136f92b)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - fs/proc/base.c:__set_oom_adj
  - fs/proc/base.c:__set_oom_adj
```
```
In ipc/sem.c (ffffffff81436430)
Location: include/linux/sched.h:1306
Inline: True
```
```
In security/selinux/hooks.c (ffffffff8145e645)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_netlink_send
```
```
In security/tomoyo/audit.c (ffffffff8147db6b)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - security/tomoyo/audit.c:tomoyo_print_header
```
```
In security/integrity/integrity_audit.c (ffffffff814ad05e)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - security/integrity/integrity_audit.c:integrity_audit_msg
```
```
In block/blk-core.c (ffffffff814de8a7)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - block/blk-core.c:submit_bio
```
```
In drivers/pci/quirks.c (ffffffff8158bca5)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - drivers/pci/quirks.c:pci_do_fixups
```
```
In drivers/tty/tty_io.c (ffffffff8164c1b9)
Location: include/linux/sched.h:1306
Inline: True
```
```
In drivers/tty/tty_audit.c (ffffffff81655f92)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - drivers/tty/tty_audit.c:tty_audit_log
```
```
In drivers/base/power/main.c (ffffffff816d8ca9)
Location: include/linux/sched.h:1306
Inline: True
```
```
In drivers/cdrom/cdrom.c (ffffffff81795277)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - drivers/cdrom/cdrom.c:open_for_data
```
```
In drivers/usb/core/devio.c (ffffffff817b7662)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_open
  - drivers/usb/core/devio.c:check_ctrlrecip
```
```
In drivers/md/md.c (ffffffff8183c9e4)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - drivers/md/md.c:md_unregister_thread
```
```
In net/core/sock.c (ffffffff818b6ca4)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - net/core/sock.c:sock_set_timeout
```
```
In net/ipv4/tcp.c (ffffffff81960d8a)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
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
In init/main.c (ffffffff81000f38)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - init/main.c:trace_initcall_start_cb
```
```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff81003d12)
Location: include/linux/sched.h:1306
Inline: True
```
```
In arch/x86/kernel/signal.c (ffffffff8102131f)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:signal_fault
```
```
In arch/x86/kernel/traps.c (ffffffff810222d5)
Location: include/linux/sched.h:1306
Inline: True
```
```
In arch/x86/kernel/umip.c (ffffffff81069766)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - arch/x86/kernel/umip.c:umip_printk
```
```
In arch/x86/mm/fault.c (ffffffff8106e49f)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:__bad_area_nosemaphore
  - arch/x86/mm/fault.c:__bad_area_nosemaphore
```
```
In arch/x86/net/bpf_jit_comp.c (ffffffff81084a99)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile
```
```
In kernel/panic.c (ffffffff81089a32)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - kernel/panic.c:refcount_error_report
```
```
In kernel/exit.c (ffffffff8108f5a1)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/umh.c (ffffffff810a72b4)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - kernel/umh.c:call_usermodehelper_exec_async
```
```
In kernel/workqueue.c (ffffffff810ae3ed)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - kernel/workqueue.c:show_workqueue_state
  - kernel/workqueue.c:show_workqueue_state
  - kernel/workqueue.c:show_workqueue_state
  - kernel/workqueue.c:pr_cont_work
  - kernel/workqueue.c:process_one_work
```
```
In kernel/async.c (ffffffff810b794b)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - kernel/async.c:async_synchronize_cookie_domain
  - kernel/async.c:async_synchronize_cookie_domain
  - kernel/async.c:async_run_entry_fn
```
```
In kernel/sched/core.c (ffffffff810c7776)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - kernel/sched/core.c:select_fallback_rq
  - kernel/sched/core.c:perf_trace_sched_swap_numa
  - kernel/sched/core.c:perf_trace_sched_swap_numa
  - kernel/sched/core.c:perf_trace_sched_move_task_template
  - kernel/sched/core.c:trace_event_raw_event_sched_swap_numa
  - kernel/sched/core.c:trace_event_raw_event_sched_swap_numa
  - kernel/sched/core.c:trace_event_raw_event_sched_move_task_template
```
```
In kernel/sched/debug.c (ffffffff810e5707)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - kernel/sched/debug.c:print_cpu
  - kernel/sched/debug.c:print_cpu
```
```
In kernel/locking/rtmutex.c (ffffffff810ef69e)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
```
```
In kernel/printk/printk.c (ffffffff810fda67)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - kernel/printk/printk.c:vprintk_store
  - kernel/printk/printk.c:check_syslog_permissions
```
```
In kernel/time/posix-cpu-timers.c (ffffffff8112f96a)
Location: include/linux/sched.h:1306
Inline: True
```
```
In kernel/auditfilter.c (ffffffff81164cac)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_filter
```
```
In kernel/watchdog.c (ffffffff8117bb84)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - kernel/watchdog.c:watchdog_timer_fn
```
```
In kernel/trace/bpf_trace.c (ffffffff811b9fe4)
Location: include/linux/sched.h:1306
Inline: True
```
```
In mm/oom_kill.c (ffffffff81215315)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:oom_reaper
  - mm/oom_kill.c:oom_reaper
```
```
In fs/fs-writeback.c (ffffffff812f88e9)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - fs/fs-writeback.c:block_dump___mark_inode_dirty
```
```
In fs/binfmt_elf.c (ffffffff81344d8f)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - fs/binfmt_elf.c:elf_map
```
```
In fs/compat_binfmt_elf.c (ffffffff813485ce)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:elf_map
```
```
In fs/coredump.c (ffffffff8134ad9a)
Location: include/linux/sched.h:1306
Inline: True
```
```
In fs/drop_caches.c (ffffffff8134bb8e)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - fs/drop_caches.c:drop_caches_sysctl_handler
```
```
In fs/proc/base.c (ffffffff813603bb)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - fs/proc/base.c:__set_oom_adj
  - fs/proc/base.c:__set_oom_adj
```
```
In ipc/sem.c (ffffffff81426eb0)
Location: include/linux/sched.h:1306
Inline: True
```
```
In security/selinux/hooks.c (ffffffff8144f075)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_netlink_send
```
```
In security/tomoyo/audit.c (ffffffff8146e58b)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - security/tomoyo/audit.c:tomoyo_print_header
```
```
In security/integrity/integrity_audit.c (ffffffff8149da7e)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - security/integrity/integrity_audit.c:integrity_audit_msg
```
```
In block/blk-core.c (ffffffff814cf247)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - block/blk-core.c:submit_bio
```
```
In drivers/pci/quirks.c (ffffffff8157a7e5)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - drivers/pci/quirks.c:pci_do_fixups
```
```
In drivers/tty/tty_io.c (ffffffff8162c609)
Location: include/linux/sched.h:1306
Inline: True
```
```
In drivers/tty/tty_audit.c (ffffffff81636322)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - drivers/tty/tty_audit.c:tty_audit_log
```
```
In drivers/base/power/main.c (ffffffff816b32e9)
Location: include/linux/sched.h:1306
Inline: True
```
```
In drivers/vfio/vfio.c (ffffffff8177c65a)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_group_fops_unl_ioctl
  - drivers/vfio/vfio.c:vfio_del_group_dev
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff8177feb9)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_pin_pages
```
```
In drivers/cdrom/cdrom.c (ffffffff81786f47)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - drivers/cdrom/cdrom.c:open_for_data
```
```
In drivers/usb/core/devio.c (ffffffff817a9082)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_open
  - drivers/usb/core/devio.c:check_ctrlrecip
```
```
In drivers/md/md.c (ffffffff81804044)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - drivers/md/md.c:md_unregister_thread
```
```
In net/core/sock.c (ffffffff81870bf4)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - net/core/sock.c:sock_set_timeout
```
```
In net/ipv4/tcp.c (ffffffff8191a87a)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
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
In init/main.c (ffffffff81002a65)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - init/main.c:trace_initcall_start_cb
```
```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff810055f2)
Location: include/linux/sched.h:1306
Inline: True
```
```
In arch/x86/kernel/signal.c (ffffffff8103179f)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:signal_fault
```
```
In arch/x86/kernel/traps.c (ffffffff810327dc)
Location: include/linux/sched.h:1306
Inline: True
```
```
In arch/x86/kernel/umip.c (ffffffff81079fe1)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - arch/x86/kernel/umip.c:umip_printk
```
```
In arch/x86/mm/fault.c (ffffffff8107f475)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:__bad_area_nosemaphore
  - arch/x86/mm/fault.c:__bad_area_nosemaphore
```
```
In arch/x86/net/bpf_jit_comp.c (ffffffff81095fb9)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile
```
```
In kernel/panic.c (ffffffff8109afa2)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - kernel/panic.c:refcount_error_report
```
```
In kernel/exit.c (ffffffff810a0b31)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/umh.c (ffffffff810b7eda)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - kernel/umh.c:call_usermodehelper_exec_async
```
```
In kernel/workqueue.c (ffffffff810bf12d)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - kernel/workqueue.c:show_workqueue_state
  - kernel/workqueue.c:show_workqueue_state
  - kernel/workqueue.c:show_workqueue_state
  - kernel/workqueue.c:pr_cont_work
  - kernel/workqueue.c:process_one_work
```
```
In kernel/async.c (ffffffff810c865b)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - kernel/async.c:async_synchronize_cookie_domain
  - kernel/async.c:async_synchronize_cookie_domain
  - kernel/async.c:async_run_entry_fn
```
```
In kernel/sched/core.c (ffffffff810d50ab)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - kernel/sched/core.c:select_fallback_rq
  - kernel/sched/core.c:perf_trace_sched_swap_numa
  - kernel/sched/core.c:perf_trace_sched_swap_numa
  - kernel/sched/core.c:perf_trace_sched_move_task_template
  - kernel/sched/core.c:trace_event_raw_event_sched_swap_numa
  - kernel/sched/core.c:trace_event_raw_event_sched_swap_numa
  - kernel/sched/core.c:trace_event_raw_event_sched_move_task_template
```
```
In kernel/sched/debug.c (ffffffff810f2747)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - kernel/sched/debug.c:print_cpu
  - kernel/sched/debug.c:print_cpu
```
```
In kernel/locking/rtmutex.c (ffffffff810fc674)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
```
```
In kernel/printk/printk.c (ffffffff8110ab87)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - kernel/printk/printk.c:vprintk_store
  - kernel/printk/printk.c:check_syslog_permissions
```
```
In kernel/time/posix-cpu-timers.c (ffffffff8113ab40)
Location: include/linux/sched.h:1306
Inline: True
```
```
In kernel/auditfilter.c (ffffffff8116f8dc)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_filter
```
```
In kernel/watchdog.c (ffffffff81186814)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - kernel/watchdog.c:watchdog_timer_fn
```
```
In kernel/trace/bpf_trace.c (ffffffff811c4fd4)
Location: include/linux/sched.h:1306
Inline: True
```
```
In mm/oom_kill.c (ffffffff8121ff05)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:oom_reaper
  - mm/oom_kill.c:oom_reaper
```
```
In fs/fs-writeback.c (ffffffff81305ab9)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - fs/fs-writeback.c:block_dump___mark_inode_dirty
```
```
In fs/binfmt_elf.c (ffffffff81351b9f)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - fs/binfmt_elf.c:elf_map
```
```
In fs/compat_binfmt_elf.c (ffffffff813553ee)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:elf_map
```
```
In fs/coredump.c (ffffffff81357bba)
Location: include/linux/sched.h:1306
Inline: True
```
```
In fs/drop_caches.c (ffffffff813589be)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - fs/drop_caches.c:drop_caches_sysctl_handler
```
```
In fs/proc/base.c (ffffffff8136d3fb)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - fs/proc/base.c:__set_oom_adj
  - fs/proc/base.c:__set_oom_adj
```
```
In ipc/sem.c (ffffffff814325d0)
Location: include/linux/sched.h:1306
Inline: True
```
```
In security/selinux/hooks.c (ffffffff8145a6e5)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_netlink_send
```
```
In security/tomoyo/audit.c (ffffffff81479c0b)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - security/tomoyo/audit.c:tomoyo_print_header
```
```
In security/integrity/integrity_audit.c (ffffffff814a90fe)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - security/integrity/integrity_audit.c:integrity_audit_msg
```
```
In block/blk-core.c (ffffffff814da937)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - block/blk-core.c:submit_bio
```
```
In drivers/pci/quirks.c (ffffffff8158bb65)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - drivers/pci/quirks.c:pci_do_fixups
```
```
In drivers/tty/tty_io.c (ffffffff8167a579)
Location: include/linux/sched.h:1306
Inline: True
```
```
In drivers/tty/tty_audit.c (ffffffff81684352)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - drivers/tty/tty_audit.c:tty_audit_log
```
```
In drivers/base/power/main.c (ffffffff817065e9)
Location: include/linux/sched.h:1306
Inline: True
```
```
In drivers/vfio/vfio.c (ffffffff817c742a)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_group_fops_unl_ioctl
  - drivers/vfio/vfio.c:vfio_del_group_dev
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff817cac89)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_pin_pages
```
```
In drivers/cdrom/cdrom.c (ffffffff817d1d17)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - drivers/cdrom/cdrom.c:open_for_data
```
```
In drivers/usb/core/devio.c (ffffffff817f4102)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_open
  - drivers/usb/core/devio.c:check_ctrlrecip
```
```
In drivers/md/md.c (ffffffff8188c014)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - drivers/md/md.c:md_unregister_thread
```
```
In net/core/sock.c (ffffffff81907ca4)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - net/core/sock.c:sock_set_timeout
```
```
In net/ipv4/tcp.c (ffffffff819cb55a)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
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
In init/main.c (ffffffff81002a95)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - init/main.c:trace_initcall_start_cb
```
```
In arch/x86/entry/vsyscall/vsyscall_64.c (ffffffff81005752)
Location: include/linux/sched.h:1306
Inline: True
```
```
In arch/x86/kernel/signal.c (ffffffff8103264f)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - arch/x86/kernel/signal.c:signal_fault
```
```
In arch/x86/kernel/traps.c (ffffffff8103373c)
Location: include/linux/sched.h:1306
Inline: True
```
```
In arch/x86/kernel/umip.c (ffffffff8107c0e1)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - arch/x86/kernel/umip.c:umip_printk
```
```
In arch/x86/mm/fault.c (ffffffff81081565)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:__bad_area_nosemaphore
  - arch/x86/mm/fault.c:__bad_area_nosemaphore
```
```
In arch/x86/net/bpf_jit_comp.c (ffffffff8109dba4)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - arch/x86/net/bpf_jit_comp.c:bpf_int_jit_compile
```
```
In kernel/panic.c (ffffffff810a2c12)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - kernel/panic.c:refcount_error_report
```
```
In kernel/exit.c (ffffffff810a8af0)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/umh.c (ffffffff810c00bf)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - kernel/umh.c:call_usermodehelper_exec_async
```
```
In kernel/workqueue.c (ffffffff810c7498)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - kernel/workqueue.c:show_workqueue_state
  - kernel/workqueue.c:show_workqueue_state
  - kernel/workqueue.c:show_workqueue_state
  - kernel/workqueue.c:pr_cont_work
  - kernel/workqueue.c:process_one_work
```
```
In kernel/async.c (ffffffff810d0b95)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - kernel/async.c:async_synchronize_cookie_domain
  - kernel/async.c:async_synchronize_cookie_domain
  - kernel/async.c:async_run_entry_fn
```
```
In kernel/sched/core.c (ffffffff810e095a)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - kernel/sched/core.c:select_fallback_rq
  - kernel/sched/core.c:perf_trace_sched_swap_numa
  - kernel/sched/core.c:perf_trace_sched_swap_numa
  - kernel/sched/core.c:perf_trace_sched_move_task_template
  - kernel/sched/core.c:trace_event_raw_event_sched_swap_numa
  - kernel/sched/core.c:trace_event_raw_event_sched_swap_numa
  - kernel/sched/core.c:trace_event_raw_event_sched_move_task_template
```
```
In kernel/sched/debug.c (ffffffff810fd737)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - kernel/sched/debug.c:print_cpu
  - kernel/sched/debug.c:print_cpu
```
```
In kernel/locking/rtmutex.c (ffffffff8110789b)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_adjust_prio_chain
```
```
In kernel/printk/printk.c (ffffffff81115f97)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - kernel/printk/printk.c:vprintk_store
  - kernel/printk/printk.c:check_syslog_permissions
```
```
In kernel/time/posix-cpu-timers.c (ffffffff811475f7)
Location: include/linux/sched.h:1306
Inline: True
```
```
In kernel/auditfilter.c (ffffffff8117d0e1)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - kernel/auditfilter.c:audit_filter
```
```
In kernel/watchdog.c (ffffffff81194164)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - kernel/watchdog.c:watchdog_timer_fn
```
```
In kernel/trace/bpf_trace.c (ffffffff811d3234)
Location: include/linux/sched.h:1306
Inline: True
```
```
In mm/oom_kill.c (ffffffff8122effb)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:__oom_kill_process
  - mm/oom_kill.c:oom_reaper
  - mm/oom_kill.c:oom_reaper
```
```
In fs/fs-writeback.c (ffffffff81316ff9)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - fs/fs-writeback.c:block_dump___mark_inode_dirty
```
```
In fs/binfmt_elf.c (ffffffff8136513a)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - fs/binfmt_elf.c:elf_map
```
```
In fs/compat_binfmt_elf.c (ffffffff813689c9)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - fs/compat_binfmt_elf.c:elf_map
```
```
In fs/coredump.c (ffffffff8136b29a)
Location: include/linux/sched.h:1306
Inline: True
```
```
In fs/drop_caches.c (ffffffff8136c0be)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - fs/drop_caches.c:drop_caches_sysctl_handler
```
```
In fs/proc/base.c (ffffffff81380d22)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - fs/proc/base.c:__set_oom_adj
  - fs/proc/base.c:__set_oom_adj
```
```
In ipc/sem.c (ffffffff8144969c)
Location: include/linux/sched.h:1306
Inline: True
```
```
In security/selinux/hooks.c (ffffffff81471e85)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_netlink_send
```
```
In security/tomoyo/audit.c (ffffffff814916bb)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - security/tomoyo/audit.c:tomoyo_print_header
```
```
In security/integrity/integrity_audit.c (ffffffff814c1b0e)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - security/integrity/integrity_audit.c:integrity_audit_msg
```
```
In block/blk-core.c (ffffffff814f3637)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - block/blk-core.c:submit_bio
```
```
In drivers/pci/quirks.c (ffffffff815a6015)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - drivers/pci/quirks.c:pci_do_fixups
```
```
In drivers/tty/tty_io.c (ffffffff81694c04)
Location: include/linux/sched.h:1306
Inline: True
```
```
In drivers/tty/tty_audit.c (ffffffff8169e953)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - drivers/tty/tty_audit.c:tty_audit_log
```
```
In drivers/base/power/main.c (ffffffff81720ff9)
Location: include/linux/sched.h:1306
Inline: True
```
```
In drivers/vfio/vfio.c (ffffffff817e16ca)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - drivers/vfio/vfio.c:vfio_group_fops_unl_ioctl
  - drivers/vfio/vfio.c:vfio_del_group_dev
```
```
In drivers/vfio/vfio_iommu_type1.c (ffffffff817e4f29)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - drivers/vfio/vfio_iommu_type1.c:vfio_iommu_type1_pin_pages
```
```
In drivers/cdrom/cdrom.c (ffffffff817ebfb7)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - drivers/cdrom/cdrom.c:open_for_data
```
```
In drivers/usb/core/devio.c (ffffffff8180e33e)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:usbdev_do_ioctl
  - drivers/usb/core/devio.c:usbdev_open
  - drivers/usb/core/devio.c:check_ctrlrecip
```
```
In drivers/md/md.c (ffffffff818a4e32)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - drivers/md/md.c:md_unregister_thread
```
```
In net/core/sock.c (ffffffff81928cd5)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - net/core/sock.c:sock_set_timeout
```
```
In net/ipv4/tcp.c (ffffffff819d50ea)
Location: include/linux/sched.h:1306
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_recvmsg
```
</details>
</li>
</ul>

## Differences
