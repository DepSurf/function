# Function: <code>next_thread</code>

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
In kernel/exit.c (ffffffff81082804)
Location: include/linux/sched.h:2714
Inline: True
Inline callers:
  - kernel/exit.c:release_task
  - kernel/exit.c:do_wait
```
```
In kernel/signal.c (ffffffff8108de4a)
Location: include/linux/sched.h:2714
Inline: True
Inline callers:
  - kernel/signal.c:complete_signal
  - kernel/signal.c:complete_signal
  - kernel/signal.c:retarget_shared_pending
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:zap_other_threads
```
```
In kernel/sys.c (ffffffff81092793)
Location: include/linux/sched.h:2714
Inline: True
Inline callers:
  - kernel/sys.c:k_getrusage
  - kernel/sys.c:SyS_setpriority
  - kernel/sys.c:SyS_setpriority
  - kernel/sys.c:SyS_getpriority
  - kernel/sys.c:SyS_getpriority
```
```
In kernel/cgroup.c (ffffffff81116cef)
Location: include/linux/sched.h:2714
Inline: True
Inline callers:
  - kernel/cgroup.c:cgroup_migrate
  - kernel/cgroup.c:cgroup_attach_task
  - kernel/cgroup.c:cgroup_mount
```
```
In kernel/debug/gdbstub.c (ffffffff8113176b)
Location: include/linux/sched.h:2714
Inline: True
Inline callers:
  - kernel/debug/gdbstub.c:gdb_serial_stub
```
```
In kernel/debug/kdb/kdb_main.c (ffffffff8113761d)
Location: include/linux/sched.h:2714
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_main.c:kdb_ps_suppressed
  - kernel/debug/kdb/kdb_main.c:kdb_ps
```
```
In kernel/debug/kdb/kdb_bt.c (ffffffff811390ac)
Location: include/linux/sched.h:2714
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
```
```
In kernel/taskstats.c (ffffffff8113eac3)
Location: include/linux/sched.h:2714
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_user_cmd
```
```
In kernel/trace/ftrace.c (ffffffff81145e5b)
Location: include/linux/sched.h:2714
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:register_ftrace_graph
```
```
In fs/exec.c (ffffffff81213f84)
Location: include/linux/sched.h:2714
Inline: True
```
```
In fs/fs_struct.c (ffffffff8124154d)
Location: include/linux/sched.h:2714
Inline: True
Inline callers:
  - fs/fs_struct.c:chroot_fs_refs
```
```
In fs/proc/base.c (ffffffff8127b356)
Location: include/linux/sched.h:2714
Inline: True
Inline callers:
  - fs/proc/base.c:do_io_accounting
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_task_readdir
```
```
In fs/proc/array.c (ffffffff8128050d)
Location: include/linux/sched.h:2714
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
```
```
In block/ioprio.c (ffffffff813cdd40)
Location: include/linux/sched.h:2714
Inline: True
Inline callers:
  - block/ioprio.c:SyS_ioprio_set
  - block/ioprio.c:SyS_ioprio_set
  - block/ioprio.c:SyS_ioprio_get
  - block/ioprio.c:SyS_ioprio_get
```
```
In drivers/tty/tty_io.c (ffffffff814e36ba)
Location: include/linux/sched.h:2714
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:__do_SAK
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
In kernel/exit.c (ffffffff8108661f)
Location: include/linux/sched.h:2983
Inline: True
Inline callers:
  - kernel/exit.c:do_wait
  - kernel/exit.c:release_task
```
```
In kernel/signal.c (ffffffff81091064)
Location: include/linux/sched.h:2983
Inline: True
Inline callers:
  - kernel/signal.c:retarget_shared_pending
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:zap_other_threads
  - kernel/signal.c:complete_signal
  - kernel/signal.c:complete_signal
```
```
In kernel/sys.c (ffffffff81095913)
Location: include/linux/sched.h:2983
Inline: True
Inline callers:
  - kernel/sys.c:k_getrusage
  - kernel/sys.c:SyS_getpriority
  - kernel/sys.c:SyS_getpriority
  - kernel/sys.c:SyS_setpriority
  - kernel/sys.c:SyS_setpriority
```
```
In kernel/cgroup.c (ffffffff8111e0f4)
Location: include/linux/sched.h:2983
Inline: True
Inline callers:
  - kernel/cgroup.c:cgroup_attach_task
  - kernel/cgroup.c:cgroup_migrate
  - kernel/cgroup.c:cgroup_mount
```
```
In kernel/debug/gdbstub.c (ffffffff81139b43)
Location: include/linux/sched.h:2983
Inline: True
Inline callers:
  - kernel/debug/gdbstub.c:gdb_serial_stub
```
```
In kernel/debug/kdb/kdb_main.c (ffffffff8113fe01)
Location: include/linux/sched.h:2983
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_main.c:kdb_ps
  - kernel/debug/kdb/kdb_main.c:kdb_ps_suppressed
```
```
In kernel/debug/kdb/kdb_bt.c (ffffffff811415ac)
Location: include/linux/sched.h:2983
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
```
```
In kernel/taskstats.c (ffffffff811470f0)
Location: include/linux/sched.h:2983
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_user_cmd
```
```
In kernel/trace/ftrace.c (ffffffff8114e6ba)
Location: include/linux/sched.h:2983
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:register_ftrace_graph
```
```
In fs/exec.c (ffffffff8123ace5)
Location: include/linux/sched.h:2983
Inline: True
```
```
In fs/fs_struct.c (ffffffff81269847)
Location: include/linux/sched.h:2983
Inline: True
Inline callers:
  - fs/fs_struct.c:chroot_fs_refs
```
```
In fs/proc/base.c (ffffffff812ab555)
Location: include/linux/sched.h:2983
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:do_io_accounting
```
```
In fs/proc/array.c (ffffffff812ad56c)
Location: include/linux/sched.h:2983
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
```
```
In block/ioprio.c (ffffffff8141249f)
Location: include/linux/sched.h:2983
Inline: True
Inline callers:
  - block/ioprio.c:SyS_ioprio_get
  - block/ioprio.c:SyS_ioprio_get
  - block/ioprio.c:SyS_ioprio_set
  - block/ioprio.c:SyS_ioprio_set
```
```
In drivers/tty/tty_io.c (ffffffff815349b4)
Location: include/linux/sched.h:2983
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:__do_SAK
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
In kernel/exit.c (ffffffff8108b590)
Location: include/linux/sched.h:3097
Inline: True
Inline callers:
  - kernel/exit.c:do_wait
  - kernel/exit.c:release_task
```
```
In kernel/signal.c (ffffffff81095fd4)
Location: include/linux/sched.h:3097
Inline: True
Inline callers:
  - kernel/signal.c:retarget_shared_pending
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:zap_other_threads
  - kernel/signal.c:complete_signal
  - kernel/signal.c:complete_signal
```
```
In kernel/sys.c (ffffffff8109a903)
Location: include/linux/sched.h:3097
Inline: True
Inline callers:
  - kernel/sys.c:k_getrusage
  - kernel/sys.c:SyS_getpriority
  - kernel/sys.c:SyS_getpriority
  - kernel/sys.c:SyS_setpriority
  - kernel/sys.c:SyS_setpriority
```
```
In kernel/cgroup.c (ffffffff81126424)
Location: include/linux/sched.h:3097
Inline: True
Inline callers:
  - kernel/cgroup.c:cgroup_attach_task
  - kernel/cgroup.c:cgroup_migrate
  - kernel/cgroup.c:cgroup_mount
```
```
In kernel/debug/gdbstub.c (ffffffff811438d3)
Location: include/linux/sched.h:3097
Inline: True
Inline callers:
  - kernel/debug/gdbstub.c:gdb_serial_stub
```
```
In kernel/debug/kdb/kdb_main.c (ffffffff81149bd3)
Location: include/linux/sched.h:3097
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_main.c:kdb_ps
  - kernel/debug/kdb/kdb_main.c:kdb_ps_suppressed
```
```
In kernel/debug/kdb/kdb_bt.c (ffffffff8114b38e)
Location: include/linux/sched.h:3097
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
```
```
In kernel/taskstats.c (ffffffff81150f97)
Location: include/linux/sched.h:3097
Inline: True
```
```
In kernel/trace/ftrace.c (ffffffff811585fc)
Location: include/linux/sched.h:3097
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:register_ftrace_graph
```
```
In fs/exec.c (ffffffff8124da89)
Location: include/linux/sched.h:3097
Inline: True
```
```
In fs/fs_struct.c (ffffffff8127c7f7)
Location: include/linux/sched.h:3097
Inline: True
Inline callers:
  - fs/fs_struct.c:chroot_fs_refs
```
```
In fs/proc/base.c (ffffffff812c0c35)
Location: include/linux/sched.h:3097
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:do_io_accounting
```
```
In fs/proc/array.c (ffffffff812c2e93)
Location: include/linux/sched.h:3097
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
```
```
In block/ioprio.c (ffffffff8142d8ff)
Location: include/linux/sched.h:3097
Inline: True
Inline callers:
  - block/ioprio.c:SyS_ioprio_get
  - block/ioprio.c:SyS_ioprio_get
  - block/ioprio.c:SyS_ioprio_set
  - block/ioprio.c:SyS_ioprio_set
```
```
In drivers/tty/tty_io.c (ffffffff815610e4)
Location: include/linux/sched.h:3097
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:__do_SAK
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
In kernel/exit.c (ffffffff8108830f)
Location: include/linux/sched/signal.h:557
Inline: True
Inline callers:
  - kernel/exit.c:do_wait
  - kernel/exit.c:release_task
```
```
In kernel/signal.c (ffffffff81092fb4)
Location: include/linux/sched/signal.h:557
Inline: True
Inline callers:
  - kernel/signal.c:retarget_shared_pending
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:zap_other_threads
  - kernel/signal.c:complete_signal
  - kernel/signal.c:complete_signal
```
```
In kernel/sys.c (ffffffff8109b09d)
Location: include/linux/sched/signal.h:557
Inline: True
Inline callers:
  - kernel/sys.c:getrusage
  - kernel/sys.c:SyS_getpriority
  - kernel/sys.c:SyS_setpriority
```
```
In kernel/cgroup/cgroup.c (ffffffff8112548d)
Location: include/linux/sched/signal.h:557
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_attach_task
  - kernel/cgroup/cgroup.c:cgroup_migrate
  - kernel/cgroup/cgroup.c:cgroup_mount
```
```
In kernel/debug/gdbstub.c (ffffffff81145379)
Location: include/linux/sched/signal.h:557
Inline: True
Inline callers:
  - kernel/debug/gdbstub.c:gdb_serial_stub
```
```
In kernel/debug/kdb/kdb_main.c (ffffffff8114b9d2)
Location: include/linux/sched/signal.h:557
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_main.c:kdb_ps
  - kernel/debug/kdb/kdb_main.c:kdb_ps_suppressed
```
```
In kernel/debug/kdb/kdb_bt.c (ffffffff8114d2fe)
Location: include/linux/sched/signal.h:557
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
```
```
In kernel/taskstats.c (ffffffff81153497)
Location: include/linux/sched/signal.h:557
Inline: True
```
```
In kernel/trace/ftrace.c (ffffffff8115b8fb)
Location: include/linux/sched/signal.h:557
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:register_ftrace_graph
```
```
In fs/exec.c (ffffffff81259a61)
Location: include/linux/sched/signal.h:557
Inline: True
```
```
In fs/fs_struct.c (ffffffff81289e75)
Location: include/linux/sched/signal.h:557
Inline: True
Inline callers:
  - fs/fs_struct.c:chroot_fs_refs
```
```
In fs/proc/base.c (ffffffff812ce01b)
Location: include/linux/sched/signal.h:557
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:do_io_accounting
```
```
In fs/proc/array.c (ffffffff812cfae2)
Location: include/linux/sched/signal.h:557
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
```
```
In drivers/tty/tty_io.c (ffffffff81574419)
Location: include/linux/sched/signal.h:557
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
In kernel/exit.c (ffffffff8108f087)
Location: include/linux/sched/signal.h:558
Inline: True
Inline callers:
  - kernel/exit.c:do_wait
  - kernel/exit.c:release_task
```
```
In kernel/signal.c (ffffffff81099e94)
Location: include/linux/sched/signal.h:558
Inline: True
Inline callers:
  - kernel/signal.c:retarget_shared_pending
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:zap_other_threads
  - kernel/signal.c:complete_signal
  - kernel/signal.c:complete_signal
```
```
In kernel/sys.c (ffffffff810a1d7d)
Location: include/linux/sched/signal.h:558
Inline: True
Inline callers:
  - kernel/sys.c:getrusage
  - kernel/sys.c:SyS_getpriority
  - kernel/sys.c:SyS_setpriority
```
```
In kernel/cgroup/cgroup.c (ffffffff8113175d)
Location: include/linux/sched/signal.h:558
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_attach_task
  - kernel/cgroup/cgroup.c:cgroup_migrate
  - kernel/cgroup/cgroup.c:cgroup_mount
```
```
In kernel/debug/gdbstub.c (ffffffff81151ea7)
Location: include/linux/sched/signal.h:558
Inline: True
Inline callers:
  - kernel/debug/gdbstub.c:gdb_serial_stub
```
```
In kernel/debug/kdb/kdb_main.c (ffffffff81158294)
Location: include/linux/sched/signal.h:558
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_main.c:kdb_ps
  - kernel/debug/kdb/kdb_main.c:kdb_ps_suppressed
```
```
In kernel/debug/kdb/kdb_bt.c (ffffffff81159b8c)
Location: include/linux/sched/signal.h:558
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
```
```
In kernel/taskstats.c (ffffffff8115fc97)
Location: include/linux/sched/signal.h:558
Inline: True
```
```
In kernel/trace/ftrace.c (ffffffff811689cb)
Location: include/linux/sched/signal.h:558
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:register_ftrace_graph
```
```
In fs/exec.c (ffffffff8127bcba)
Location: include/linux/sched/signal.h:558
Inline: True
```
```
In fs/fs_struct.c (ffffffff812ac9b5)
Location: include/linux/sched/signal.h:558
Inline: True
Inline callers:
  - fs/fs_struct.c:chroot_fs_refs
```
```
In fs/proc/base.c (ffffffff812f2871)
Location: include/linux/sched/signal.h:558
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:do_io_accounting
```
```
In fs/proc/array.c (ffffffff812f4264)
Location: include/linux/sched/signal.h:558
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
```
```
In drivers/tty/tty_io.c (ffffffff815d7599)
Location: include/linux/sched/signal.h:558
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
In kernel/exit.c (ffffffff81092b96)
Location: include/linux/sched/signal.h:586
Inline: True
Inline callers:
  - kernel/exit.c:do_wait
```
```
In kernel/signal.c (ffffffff8109de94)
Location: include/linux/sched/signal.h:586
Inline: True
Inline callers:
  - kernel/signal.c:retarget_shared_pending
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:zap_other_threads
  - kernel/signal.c:complete_signal
  - kernel/signal.c:complete_signal
```
```
In kernel/sys.c (ffffffff810a809f)
Location: include/linux/sched/signal.h:586
Inline: True
Inline callers:
  - kernel/sys.c:getrusage
  - kernel/sys.c:__ia32_sys_getpriority
  - kernel/sys.c:__x64_sys_getpriority
  - kernel/sys.c:__ia32_sys_setpriority
  - kernel/sys.c:__x64_sys_setpriority
```
```
In kernel/cgroup/cgroup.c (ffffffff8113fe97)
Location: include/linux/sched/signal.h:586
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_attach_task
  - kernel/cgroup/cgroup.c:cgroup_migrate
  - kernel/cgroup/cgroup.c:cgroup_mount
```
```
In kernel/debug/gdbstub.c (ffffffff811609c2)
Location: include/linux/sched/signal.h:586
Inline: True
Inline callers:
  - kernel/debug/gdbstub.c:gdb_serial_stub
```
```
In kernel/debug/kdb/kdb_main.c (ffffffff81166e94)
Location: include/linux/sched/signal.h:586
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_main.c:kdb_ps
  - kernel/debug/kdb/kdb_main.c:kdb_ps_suppressed
```
```
In kernel/debug/kdb/kdb_bt.c (ffffffff811687a7)
Location: include/linux/sched/signal.h:586
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
```
```
In kernel/taskstats.c (ffffffff8116ec14)
Location: include/linux/sched/signal.h:586
Inline: True
```
```
In kernel/trace/ftrace.c (ffffffff81177631)
Location: include/linux/sched/signal.h:586
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:register_ftrace_graph
```
```
In fs/exec.c (ffffffff812a2a69)
Location: include/linux/sched/signal.h:586
Inline: True
```
```
In fs/fs_struct.c (ffffffff812d4594)
Location: include/linux/sched/signal.h:586
Inline: True
Inline callers:
  - fs/fs_struct.c:chroot_fs_refs
```
```
In fs/proc/base.c (ffffffff8131f6e3)
Location: include/linux/sched/signal.h:586
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:do_io_accounting
```
```
In fs/proc/array.c (ffffffff8132166d)
Location: include/linux/sched/signal.h:586
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
```
```
In drivers/tty/tty_io.c (ffffffff81610a25)
Location: include/linux/sched/signal.h:586
Inline: True
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
In kernel/exit.c (ffffffff8109ae86)
Location: include/linux/sched/signal.h:628
Inline: True
Inline callers:
  - kernel/exit.c:do_wait
```
```
In kernel/signal.c (ffffffff810a61a4)
Location: include/linux/sched/signal.h:628
Inline: True
Inline callers:
  - kernel/signal.c:retarget_shared_pending
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:zap_other_threads
  - kernel/signal.c:complete_signal
  - kernel/signal.c:complete_signal
```
```
In kernel/sys.c (ffffffff810b0daf)
Location: include/linux/sched/signal.h:628
Inline: True
Inline callers:
  - kernel/sys.c:getrusage
  - kernel/sys.c:__ia32_sys_getpriority
  - kernel/sys.c:__x64_sys_getpriority
  - kernel/sys.c:__ia32_sys_setpriority
  - kernel/sys.c:__x64_sys_setpriority
```
```
In kernel/cgroup/cgroup.c (ffffffff8114b8b7)
Location: include/linux/sched/signal.h:628
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_attach_task
  - kernel/cgroup/cgroup.c:cgroup_migrate
  - kernel/cgroup/cgroup.c:cgroup_mount
```
```
In kernel/debug/gdbstub.c (ffffffff8116d841)
Location: include/linux/sched/signal.h:628
Inline: True
Inline callers:
  - kernel/debug/gdbstub.c:gdb_serial_stub
```
```
In kernel/debug/kdb/kdb_main.c (ffffffff81173bf4)
Location: include/linux/sched/signal.h:628
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_main.c:kdb_ps
  - kernel/debug/kdb/kdb_main.c:kdb_ps_suppressed
```
```
In kernel/debug/kdb/kdb_bt.c (ffffffff811755e7)
Location: include/linux/sched/signal.h:628
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
```
```
In kernel/taskstats.c (ffffffff8117c714)
Location: include/linux/sched/signal.h:628
Inline: True
```
```
In kernel/trace/fgraph.c (ffffffff811a09a5)
Location: include/linux/sched/signal.h:628
Inline: True
Inline callers:
  - kernel/trace/fgraph.c:register_ftrace_graph
```
```
In fs/exec.c (ffffffff812b78fe)
Location: include/linux/sched/signal.h:628
Inline: True
```
```
In fs/fs_struct.c (ffffffff812e9964)
Location: include/linux/sched/signal.h:628
Inline: True
Inline callers:
  - fs/fs_struct.c:chroot_fs_refs
```
```
In fs/proc/base.c (ffffffff81336813)
Location: include/linux/sched/signal.h:628
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:do_io_accounting
```
```
In fs/proc/array.c (ffffffff8133877d)
Location: include/linux/sched/signal.h:628
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
```
```
In drivers/tty/tty_io.c (ffffffff8162d765)
Location: include/linux/sched/signal.h:628
Inline: True
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
In kernel/exit.c (ffffffff8109f4f0)
Location: include/linux/sched/signal.h:659
Inline: True
Inline callers:
  - kernel/exit.c:do_wait
  - kernel/exit.c:release_task
```
```
In kernel/signal.c (ffffffff810aae88)
Location: include/linux/sched/signal.h:659
Inline: True
Inline callers:
  - kernel/signal.c:retarget_shared_pending
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:zap_other_threads
  - kernel/signal.c:complete_signal
  - kernel/signal.c:complete_signal
```
```
In kernel/sys.c (ffffffff810b68fe)
Location: include/linux/sched/signal.h:659
Inline: True
Inline callers:
  - kernel/sys.c:getrusage
  - kernel/sys.c:__ia32_sys_getpriority
  - kernel/sys.c:__x64_sys_getpriority
  - kernel/sys.c:__ia32_sys_setpriority
  - kernel/sys.c:__x64_sys_setpriority
```
```
In kernel/cgroup/cgroup.c (ffffffff811571bc)
Location: include/linux/sched/signal.h:659
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_attach_task
  - kernel/cgroup/cgroup.c:cgroup_migrate
  - kernel/cgroup/cgroup.c:cgroup_init_fs_context
```
```
In kernel/debug/gdbstub.c (ffffffff81179f20)
Location: include/linux/sched/signal.h:659
Inline: True
Inline callers:
  - kernel/debug/gdbstub.c:gdb_cmd_query
```
```
In kernel/debug/kdb/kdb_main.c (ffffffff811809cc)
Location: include/linux/sched/signal.h:659
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_main.c:kdb_ps
  - kernel/debug/kdb/kdb_main.c:kdb_ps_suppressed
```
```
In kernel/debug/kdb/kdb_bt.c (ffffffff8118234c)
Location: include/linux/sched/signal.h:659
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
```
```
In kernel/taskstats.c (ffffffff811895b8)
Location: include/linux/sched/signal.h:659
Inline: True
```
```
In kernel/trace/fgraph.c (ffffffff811ae788)
Location: include/linux/sched/signal.h:659
Inline: True
Inline callers:
  - kernel/trace/fgraph.c:start_graph_tracing
```
```
In fs/exec.c (ffffffff812d3f46)
Location: include/linux/sched/signal.h:659
Inline: True
```
```
In fs/fs_struct.c (ffffffff8130831b)
Location: include/linux/sched/signal.h:659
Inline: True
Inline callers:
  - fs/fs_struct.c:chroot_fs_refs
```
```
In fs/proc/base.c (ffffffff8135e8b8)
Location: include/linux/sched/signal.h:659
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:do_io_accounting
```
```
In fs/proc/array.c (ffffffff81360e3b)
Location: include/linux/sched/signal.h:659
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
```
```
In drivers/tty/tty_io.c (ffffffff81661393)
Location: include/linux/sched/signal.h:659
Inline: True
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
In kernel/exit.c (ffffffff810a5a80)
Location: include/linux/sched/signal.h:651
Inline: True
Inline callers:
  - kernel/exit.c:do_wait
  - kernel/exit.c:release_task
```
```
In kernel/signal.c (ffffffff810b1488)
Location: include/linux/sched/signal.h:651
Inline: True
Inline callers:
  - kernel/signal.c:retarget_shared_pending
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:zap_other_threads
  - kernel/signal.c:complete_signal
  - kernel/signal.c:complete_signal
```
```
In kernel/sys.c (ffffffff810bcebe)
Location: include/linux/sched/signal.h:651
Inline: True
Inline callers:
  - kernel/sys.c:getrusage
  - kernel/sys.c:__ia32_sys_getpriority
  - kernel/sys.c:__x64_sys_getpriority
  - kernel/sys.c:__ia32_sys_setpriority
  - kernel/sys.c:__x64_sys_setpriority
```
```
In kernel/cgroup/cgroup.c (ffffffff81162e2c)
Location: include/linux/sched/signal.h:651
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_attach_task
  - kernel/cgroup/cgroup.c:cgroup_migrate
  - kernel/cgroup/cgroup.c:cgroup_enable_task_cg_lists
```
```
In kernel/debug/gdbstub.c (ffffffff81185db0)
Location: include/linux/sched/signal.h:651
Inline: True
Inline callers:
  - kernel/debug/gdbstub.c:gdb_cmd_query
```
```
In kernel/debug/kdb/kdb_main.c (ffffffff8118c83c)
Location: include/linux/sched/signal.h:651
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_main.c:kdb_ps
  - kernel/debug/kdb/kdb_main.c:kdb_ps_suppressed
```
```
In kernel/debug/kdb/kdb_bt.c (ffffffff8118e1bc)
Location: include/linux/sched/signal.h:651
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
```
```
In kernel/taskstats.c (ffffffff811954f8)
Location: include/linux/sched/signal.h:651
Inline: True
```
```
In kernel/trace/fgraph.c (ffffffff811b9f08)
Location: include/linux/sched/signal.h:651
Inline: True
Inline callers:
  - kernel/trace/fgraph.c:start_graph_tracing
```
```
In fs/exec.c (ffffffff812e5ad6)
Location: include/linux/sched/signal.h:651
Inline: True
```
```
In fs/fs_struct.c (ffffffff8131b3bb)
Location: include/linux/sched/signal.h:651
Inline: True
Inline callers:
  - fs/fs_struct.c:chroot_fs_refs
```
```
In fs/proc/base.c (ffffffff81376b18)
Location: include/linux/sched/signal.h:651
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:do_io_accounting
```
```
In fs/proc/array.c (ffffffff8137909b)
Location: include/linux/sched/signal.h:651
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
```
```
In drivers/tty/tty_io.c (ffffffff816839e3)
Location: include/linux/sched/signal.h:651
Inline: True
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
In kernel/exit.c (ffffffff810ad59d)
Location: include/linux/sched/signal.h:663
Inline: True
Inline callers:
  - kernel/exit.c:do_wait
  - kernel/exit.c:__exit_signal
```
```
In kernel/signal.c (ffffffff810bc4a7)
Location: include/linux/sched/signal.h:663
Inline: True
Inline callers:
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:zap_other_threads
  - kernel/signal.c:complete_signal
  - kernel/signal.c:complete_signal
```
```
In kernel/sys.c (ffffffff810c45fe)
Location: include/linux/sched/signal.h:663
Inline: True
Inline callers:
  - kernel/sys.c:getrusage
  - kernel/sys.c:__do_sys_getpriority
  - kernel/sys.c:__do_sys_setpriority
```
```
In kernel/cgroup/cgroup.c (ffffffff81174405)
Location: include/linux/sched/signal.h:663
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_attach_task
  - kernel/cgroup/cgroup.c:cgroup_migrate
```
```
In kernel/debug/gdbstub.c (ffffffff8119a070)
Location: include/linux/sched/signal.h:663
Inline: True
Inline callers:
  - kernel/debug/gdbstub.c:gdb_cmd_query
```
```
In kernel/debug/kdb/kdb_main.c (ffffffff811a1091)
Location: include/linux/sched/signal.h:663
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_main.c:kdb_ps
  - kernel/debug/kdb/kdb_main.c:kdb_ps_suppressed
```
```
In kernel/debug/kdb/kdb_bt.c (ffffffff811a2d3e)
Location: include/linux/sched/signal.h:663
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
```
```
In kernel/taskstats.c (ffffffff811aa433)
Location: include/linux/sched/signal.h:663
Inline: True
Inline callers:
  - kernel/taskstats.c:fill_stats_for_tgid
```
```
In kernel/trace/fgraph.c (ffffffff811d294b)
Location: include/linux/sched/signal.h:663
Inline: True
Inline callers:
  - kernel/trace/fgraph.c:alloc_retstack_tasklist
```
```
In fs/exec.c (ffffffff8131d1ed)
Location: include/linux/sched/signal.h:663
Inline: True
Inline callers:
  - fs/exec.c:check_unsafe_exec
```
```
In fs/fs_struct.c (ffffffff8135506d)
Location: include/linux/sched/signal.h:663
Inline: True
Inline callers:
  - fs/fs_struct.c:chroot_fs_refs
```
```
In fs/proc/base.c (ffffffff813bf7dc)
Location: include/linux/sched/signal.h:663
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:do_io_accounting
```
```
In fs/proc/array.c (ffffffff813c2147)
Location: include/linux/sched/signal.h:663
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
```
```
In drivers/tty/tty_io.c (ffffffff81735214)
Location: include/linux/sched/signal.h:663
Inline: True
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
In kernel/exit.c (ffffffff810a8c6d)
Location: include/linux/sched/signal.h:676
Inline: True
Inline callers:
  - kernel/exit.c:do_wait
  - kernel/exit.c:__exit_signal
```
```
In kernel/signal.c (ffffffff810b7797)
Location: include/linux/sched/signal.h:676
Inline: True
Inline callers:
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:zap_other_threads
  - kernel/signal.c:complete_signal
  - kernel/signal.c:complete_signal
```
```
In kernel/sys.c (ffffffff810bf9fe)
Location: include/linux/sched/signal.h:676
Inline: True
Inline callers:
  - kernel/sys.c:getrusage
  - kernel/sys.c:__do_sys_getpriority
  - kernel/sys.c:__do_sys_setpriority
```
```
In kernel/cgroup/cgroup.c (ffffffff811710e5)
Location: include/linux/sched/signal.h:676
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_attach_task
  - kernel/cgroup/cgroup.c:cgroup_migrate
```
```
In kernel/taskstats.c (ffffffff811a79d3)
Location: include/linux/sched/signal.h:676
Inline: True
Inline callers:
  - kernel/taskstats.c:fill_stats_for_tgid
```
```
In fs/exec.c (ffffffff81328741)
Location: include/linux/sched/signal.h:676
Inline: True
Inline callers:
  - fs/exec.c:check_unsafe_exec
```
```
In fs/fs_struct.c (ffffffff8136198d)
Location: include/linux/sched/signal.h:676
Inline: True
Inline callers:
  - fs/fs_struct.c:chroot_fs_refs
```
```
In fs/proc/base.c (ffffffff813d165c)
Location: include/linux/sched/signal.h:676
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:do_io_accounting
```
```
In fs/proc/array.c (ffffffff813d4296)
Location: include/linux/sched/signal.h:676
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
```
```
In drivers/tty/tty_io.c (ffffffff81751cde)
Location: include/linux/sched/signal.h:676
Inline: True
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
In kernel/exit.c (ffffffff810a9d5b)
Location: include/linux/sched/signal.h:682
Inline: True
Inline callers:
  - kernel/exit.c:do_wait
  - kernel/exit.c:__exit_signal
```
```
In kernel/signal.c (ffffffff810b8d07)
Location: include/linux/sched/signal.h:682
Inline: True
Inline callers:
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:zap_other_threads
  - kernel/signal.c:complete_signal
  - kernel/signal.c:complete_signal
```
```
In kernel/sys.c (ffffffff810c142e)
Location: include/linux/sched/signal.h:682
Inline: True
Inline callers:
  - kernel/sys.c:getrusage
  - kernel/sys.c:__do_sys_getpriority
  - kernel/sys.c:__do_sys_setpriority
```
```
In kernel/cgroup/cgroup.c (ffffffff81171d66)
Location: include/linux/sched/signal.h:682
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_attach_task
  - kernel/cgroup/cgroup.c:cgroup_migrate
```
```
In kernel/taskstats.c (ffffffff811a83b3)
Location: include/linux/sched/signal.h:682
Inline: True
Inline callers:
  - kernel/taskstats.c:fill_stats_for_tgid
```
```
In fs/exec.c (ffffffff8132e680)
Location: include/linux/sched/signal.h:682
Inline: True
```
```
In fs/fs_struct.c (ffffffff8136846d)
Location: include/linux/sched/signal.h:682
Inline: True
Inline callers:
  - fs/fs_struct.c:chroot_fs_refs
```
```
In fs/proc/base.c (ffffffff813d8556)
Location: include/linux/sched/signal.h:682
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:do_io_accounting
```
```
In fs/proc/array.c (ffffffff813db0d6)
Location: include/linux/sched/signal.h:682
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
```
```
In drivers/tty/tty_io.c (ffffffff8173592a)
Location: include/linux/sched/signal.h:682
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
In kernel/exit.c (ffffffff810bb888)
Location: include/linux/sched/signal.h:680
Inline: True
Inline callers:
  - kernel/exit.c:do_wait
  - kernel/exit.c:__exit_signal
```
```
In kernel/signal.c (ffffffff810cb297)
Location: include/linux/sched/signal.h:680
Inline: True
Inline callers:
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:zap_other_threads
  - kernel/signal.c:complete_signal
  - kernel/signal.c:complete_signal
```
```
In kernel/sys.c (ffffffff810d3f1e)
Location: include/linux/sched/signal.h:680
Inline: True
Inline callers:
  - kernel/sys.c:getrusage
  - kernel/sys.c:__do_sys_getpriority
  - kernel/sys.c:__do_sys_setpriority
```
```
In kernel/cgroup/cgroup.c (ffffffff81198826)
Location: include/linux/sched/signal.h:680
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_attach_task
  - kernel/cgroup/cgroup.c:cgroup_migrate
```
```
In kernel/taskstats.c (ffffffff811d1c8f)
Location: include/linux/sched/signal.h:680
Inline: True
Inline callers:
  - kernel/taskstats.c:fill_stats_for_tgid
```
```
In fs/exec.c (ffffffff8137be90)
Location: include/linux/sched/signal.h:680
Inline: True
```
```
In fs/fs_struct.c (ffffffff813b716d)
Location: include/linux/sched/signal.h:680
Inline: True
Inline callers:
  - fs/fs_struct.c:chroot_fs_refs
```
```
In fs/proc/base.c (ffffffff81429c86)
Location: include/linux/sched/signal.h:680
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:do_io_accounting
```
```
In fs/proc/array.c (ffffffff8142c796)
Location: include/linux/sched/signal.h:680
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
```
```
In drivers/tty/tty_io.c (ffffffff817b62ea)
Location: include/linux/sched/signal.h:680
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
In kernel/exit.c (ffffffff810d22d5)
Location: include/linux/sched/signal.h:720
Inline: True
Inline callers:
  - kernel/exit.c:do_wait
  - kernel/exit.c:__exit_signal
```
```
In kernel/signal.c (ffffffff810e48e3)
Location: include/linux/sched/signal.h:720
Inline: True
Inline callers:
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:zap_other_threads
  - kernel/signal.c:complete_signal
  - kernel/signal.c:complete_signal
```
```
In kernel/sys.c (ffffffff810ecbe8)
Location: include/linux/sched/signal.h:720
Inline: True
Inline callers:
  - kernel/sys.c:getrusage
```
```
In kernel/cgroup/cgroup.c (ffffffff811c8942)
Location: include/linux/sched/signal.h:720
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_attach_task
  - kernel/cgroup/cgroup.c:cgroup_migrate
```
```
In kernel/taskstats.c (ffffffff812064a0)
Location: include/linux/sched/signal.h:720
Inline: True
Inline callers:
  - kernel/taskstats.c:fill_stats_for_tgid
```
```
In fs/exec.c (ffffffff813fc2f5)
Location: include/linux/sched/signal.h:720
Inline: True
```
```
In fs/fs_struct.c (ffffffff8143c7db)
Location: include/linux/sched/signal.h:720
Inline: True
Inline callers:
  - fs/fs_struct.c:chroot_fs_refs
```
```
In fs/proc/base.c (ffffffff814a3103)
Location: include/linux/sched/signal.h:720
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:do_io_accounting
```
```
In fs/proc/array.c (ffffffff814a6049)
Location: include/linux/sched/signal.h:720
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
```
```
In drivers/tty/tty_io.c (ffffffff818f41b8)
Location: include/linux/sched/signal.h:720
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:__do_SAK
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
In kernel/exit.c (ffffffff810f0d49)
Location: include/linux/sched/signal.h:721
Inline: True
Inline callers:
  - kernel/exit.c:do_wait
  - kernel/exit.c:__exit_signal
```
```
In kernel/signal.c (ffffffff81104f63)
Location: include/linux/sched/signal.h:721
Inline: True
Inline callers:
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:zap_other_threads
  - kernel/signal.c:complete_signal
  - kernel/signal.c:complete_signal
```
```
In kernel/sys.c (ffffffff8110df88)
Location: include/linux/sched/signal.h:721
Inline: True
Inline callers:
  - kernel/sys.c:getrusage
```
```
In kernel/cgroup/cgroup.c (ffffffff8120b942)
Location: include/linux/sched/signal.h:721
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_attach_task
  - kernel/cgroup/cgroup.c:cgroup_migrate
```
```
In kernel/taskstats.c (ffffffff8124e7a0)
Location: include/linux/sched/signal.h:721
Inline: True
Inline callers:
  - kernel/taskstats.c:fill_stats_for_tgid
```
```
In kernel/bpf/task_iter.c (ffffffff812f7062)
Location: include/linux/sched/signal.h:721
Inline: True
Inline callers:
  - kernel/bpf/task_iter.c:task_group_seq_get_next
```
```
In fs/exec.c (ffffffff81485d85)
Location: include/linux/sched/signal.h:721
Inline: True
```
```
In fs/fs_struct.c (ffffffff814caefb)
Location: include/linux/sched/signal.h:721
Inline: True
Inline callers:
  - fs/fs_struct.c:chroot_fs_refs
```
```
In fs/proc/base.c (ffffffff81538383)
Location: include/linux/sched/signal.h:721
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:do_io_accounting
```
```
In fs/proc/array.c (ffffffff8153b689)
Location: include/linux/sched/signal.h:721
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
```
```
In drivers/tty/tty_io.c (ffffffff81a4c937)
Location: include/linux/sched/signal.h:721
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:__do_SAK
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
In kernel/exit.c (ffffffff810fccf9)
Location: include/linux/sched/signal.h:721
Inline: True
Inline callers:
  - kernel/exit.c:do_wait
  - kernel/exit.c:__exit_signal
```
```
In kernel/signal.c (ffffffff811111e3)
Location: include/linux/sched/signal.h:721
Inline: True
Inline callers:
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:zap_other_threads
  - kernel/signal.c:complete_signal
  - kernel/signal.c:complete_signal
```
```
In kernel/sys.c (ffffffff8111a211)
Location: include/linux/sched/signal.h:721
Inline: True
Inline callers:
  - kernel/sys.c:getrusage
```
```
In kernel/cgroup/cgroup.c (ffffffff81220f42)
Location: include/linux/sched/signal.h:721
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_attach_task
  - kernel/cgroup/cgroup.c:cgroup_migrate
```
```
In kernel/taskstats.c (ffffffff81265b50)
Location: include/linux/sched/signal.h:721
Inline: True
Inline callers:
  - kernel/taskstats.c:fill_stats_for_tgid
```
```
In kernel/bpf/task_iter.c (ffffffff81324f1e)
Location: include/linux/sched/signal.h:721
Inline: True
Inline callers:
  - kernel/bpf/task_iter.c:task_group_seq_get_next
```
```
In fs/exec.c (ffffffff814b99e5)
Location: include/linux/sched/signal.h:721
Inline: True
```
```
In fs/fs_struct.c (ffffffff8150113a)
Location: include/linux/sched/signal.h:721
Inline: True
Inline callers:
  - fs/fs_struct.c:chroot_fs_refs
```
```
In fs/proc/base.c (ffffffff815705c6)
Location: include/linux/sched/signal.h:721
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:do_io_accounting
```
```
In fs/proc/array.c (ffffffff815739b4)
Location: include/linux/sched/signal.h:721
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
```
```
In drivers/tty/tty_io.c (ffffffff81a96c27)
Location: include/linux/sched/signal.h:721
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:__do_SAK
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
In kernel/exit.c (ffffffff81106ffc)
Location: include/linux/sched/signal.h:724
Inline: True
Inline callers:
  - kernel/exit.c:__do_wait
  - kernel/exit.c:__exit_signal
```
```
In kernel/signal.c (ffffffff8111ab5d)
Location: include/linux/sched/signal.h:724
Inline: True
Inline callers:
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:zap_other_threads
  - kernel/signal.c:complete_signal
```
```
In kernel/cgroup/cgroup.c (ffffffff81238bf4)
Location: include/linux/sched/signal.h:724
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_attach_task
  - kernel/cgroup/cgroup.c:cgroup_migrate
```
```
In fs/exec.c (ffffffff814eb0c1)
Location: include/linux/sched/signal.h:724
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
In kernel/exit.c (ffff8000100fbadc)
Location: include/linux/sched/signal.h:651
Inline: True
Inline callers:
  - kernel/exit.c:do_wait
  - kernel/exit.c:release_task
```
```
In kernel/signal.c (ffff80001010d0bc)
Location: include/linux/sched/signal.h:651
Inline: True
Inline callers:
  - kernel/signal.c:retarget_shared_pending
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:zap_other_threads
  - kernel/signal.c:complete_signal
  - kernel/signal.c:complete_signal
```
```
In kernel/sys.c (ffff800010119a18)
Location: include/linux/sched/signal.h:651
Inline: True
Inline callers:
  - kernel/sys.c:getrusage
  - kernel/sys.c:__arm64_sys_getpriority
  - kernel/sys.c:__arm64_sys_setpriority
```
```
In kernel/cgroup/cgroup.c (ffff8000101d43fc)
Location: include/linux/sched/signal.h:651
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_attach_task
  - kernel/cgroup/cgroup.c:cgroup_migrate
  - kernel/cgroup/cgroup.c:cgroup_enable_task_cg_lists
```
```
In kernel/debug/gdbstub.c (ffff8000101fbd84)
Location: include/linux/sched/signal.h:651
Inline: True
Inline callers:
  - kernel/debug/gdbstub.c:gdb_cmd_query
```
```
In kernel/debug/kdb/kdb_main.c (ffff800010203b50)
Location: include/linux/sched/signal.h:651
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_main.c:kdb_ps
  - kernel/debug/kdb/kdb_main.c:kdb_ps_suppressed
```
```
In kernel/debug/kdb/kdb_bt.c (ffff8000102056fc)
Location: include/linux/sched/signal.h:651
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
```
```
In kernel/taskstats.c (ffff80001020d764)
Location: include/linux/sched/signal.h:651
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_user_cmd
```
```
In kernel/trace/fgraph.c (ffff8000102386fc)
Location: include/linux/sched/signal.h:651
Inline: True
Inline callers:
  - kernel/trace/fgraph.c:start_graph_tracing
```
```
In fs/exec.c (ffff80001038de70)
Location: include/linux/sched/signal.h:651
Inline: True
```
```
In fs/fs_struct.c (ffff8000103d285c)
Location: include/linux/sched/signal.h:651
Inline: True
Inline callers:
  - fs/fs_struct.c:chroot_fs_refs
```
```
In fs/proc/base.c (ffff80001044216c)
Location: include/linux/sched/signal.h:651
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:do_io_accounting
```
```
In fs/proc/array.c (ffff800010445584)
Location: include/linux/sched/signal.h:651
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
```
```
In drivers/tty/tty_io.c (ffff800010850188)
Location: include/linux/sched/signal.h:651
Inline: True
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
In kernel/exit.c (c0359a98)
Location: include/linux/sched/signal.h:651
Inline: True
Inline callers:
  - kernel/exit.c:do_wait
  - kernel/exit.c:release_task
```
```
In kernel/signal.c (c0365328)
Location: include/linux/sched/signal.h:651
Inline: True
Inline callers:
  - kernel/signal.c:retarget_shared_pending
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:zap_other_threads
  - kernel/signal.c:complete_signal
  - kernel/signal.c:complete_signal
```
```
In kernel/sys.c (c036df70)
Location: include/linux/sched/signal.h:651
Inline: True
Inline callers:
  - kernel/sys.c:getrusage
  - kernel/sys.c:__se_sys_getpriority
  - kernel/sys.c:__se_sys_setpriority
```
```
In kernel/cgroup/cgroup.c (c0417030)
Location: include/linux/sched/signal.h:651
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_attach_task
  - kernel/cgroup/cgroup.c:cgroup_migrate
  - kernel/cgroup/cgroup.c:cgroup_enable_task_cg_lists
```
```
In kernel/debug/gdbstub.c (c043bbac)
Location: include/linux/sched/signal.h:651
Inline: True
Inline callers:
  - kernel/debug/gdbstub.c:gdb_cmd_query
```
```
In kernel/debug/kdb/kdb_main.c (c0442ac8)
Location: include/linux/sched/signal.h:651
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_main.c:kdb_ps
  - kernel/debug/kdb/kdb_main.c:kdb_ps_suppressed
```
```
In kernel/debug/kdb/kdb_bt.c (c04443c0)
Location: include/linux/sched/signal.h:651
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
```
```
In kernel/taskstats.c (c044c214)
Location: include/linux/sched/signal.h:651
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_user_cmd
```
```
In kernel/trace/fgraph.c (c0474308)
Location: include/linux/sched/signal.h:651
Inline: True
Inline callers:
  - kernel/trace/fgraph.c:start_graph_tracing
```
```
In fs/exec.c (c0575790)
Location: include/linux/sched/signal.h:651
Inline: True
Inline callers:
  - fs/exec.c:__do_execve_file
```
```
In fs/fs_struct.c (c05ad470)
Location: include/linux/sched/signal.h:651
Inline: True
Inline callers:
  - fs/fs_struct.c:chroot_fs_refs
```
```
In fs/proc/base.c (c06079ac)
Location: include/linux/sched/signal.h:651
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:do_io_accounting
```
```
In fs/proc/array.c (c060a5b8)
Location: include/linux/sched/signal.h:651
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
```
```
In drivers/tty/tty_io.c (c095c998)
Location: include/linux/sched/signal.h:651
Inline: True
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
In kernel/exit.c (c000000000143114)
Location: include/linux/sched/signal.h:651
Inline: True
Inline callers:
  - kernel/exit.c:do_wait
  - kernel/exit.c:release_task
```
```
In kernel/signal.c (c000000000154168)
Location: include/linux/sched/signal.h:651
Inline: True
Inline callers:
  - kernel/signal.c:retarget_shared_pending
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:zap_other_threads
  - kernel/signal.c:complete_signal
  - kernel/signal.c:complete_signal
```
```
In kernel/sys.c (c000000000161250)
Location: include/linux/sched/signal.h:651
Inline: True
Inline callers:
  - kernel/sys.c:getrusage
  - kernel/sys.c:__se_sys_getpriority
  - kernel/sys.c:__se_sys_setpriority
```
```
In kernel/cgroup/cgroup.c (c00000000023f9d0)
Location: include/linux/sched/signal.h:651
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_attach_task
  - kernel/cgroup/cgroup.c:cgroup_migrate
  - kernel/cgroup/cgroup.c:cgroup_enable_task_cg_lists
```
```
In kernel/debug/gdbstub.c (c000000000273eec)
Location: include/linux/sched/signal.h:651
Inline: True
Inline callers:
  - kernel/debug/gdbstub.c:gdb_cmd_query
```
```
In kernel/debug/kdb/kdb_main.c (c00000000027e340)
Location: include/linux/sched/signal.h:651
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_main.c:kdb_ps
  - kernel/debug/kdb/kdb_main.c:kdb_ps_suppressed
```
```
In kernel/debug/kdb/kdb_bt.c (c000000000280d6c)
Location: include/linux/sched/signal.h:651
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
```
```
In kernel/taskstats.c (c00000000028b7b4)
Location: include/linux/sched/signal.h:651
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_user_cmd
```
```
In kernel/trace/fgraph.c (c0000000002c4b70)
Location: include/linux/sched/signal.h:651
Inline: True
Inline callers:
  - kernel/trace/fgraph.c:start_graph_tracing
```
```
In fs/exec.c (c0000000004860e4)
Location: include/linux/sched/signal.h:651
Inline: True
```
```
In fs/fs_struct.c (c0000000004d53b4)
Location: include/linux/sched/signal.h:651
Inline: True
Inline callers:
  - fs/fs_struct.c:chroot_fs_refs
```
```
In fs/proc/base.c (c0000000005576e4)
Location: include/linux/sched/signal.h:651
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:do_io_accounting
```
```
In fs/proc/array.c (c00000000055af90)
Location: include/linux/sched/signal.h:651
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
```
```
In drivers/tty/tty_io.c (c0000000008f06d0)
Location: include/linux/sched/signal.h:651
Inline: True
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
In kernel/exit.c (ffffffe0000c55c8)
Location: include/linux/sched/signal.h:651
Inline: True
Inline callers:
  - kernel/exit.c:do_wait
  - kernel/exit.c:release_task
```
```
In kernel/signal.c (ffffffe0000ce5fa)
Location: include/linux/sched/signal.h:651
Inline: True
Inline callers:
  - kernel/signal.c:retarget_shared_pending
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:zap_other_threads
  - kernel/signal.c:complete_signal
  - kernel/signal.c:complete_signal
```
```
In kernel/sys.c (ffffffe0000d4718)
Location: include/linux/sched/signal.h:651
Inline: True
Inline callers:
  - kernel/sys.c:getrusage
  - kernel/sys.c:__se_sys_getpriority
  - kernel/sys.c:__se_sys_setpriority
```
```
In kernel/cgroup/cgroup.c (ffffffe00014d954)
Location: include/linux/sched/signal.h:651
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_attach_task
  - kernel/cgroup/cgroup.c:cgroup_migrate
  - kernel/cgroup/cgroup.c:cgroup_enable_task_cg_lists
```
```
In kernel/taskstats.c (ffffffe00016e7ae)
Location: include/linux/sched/signal.h:651
Inline: True
Inline callers:
  - kernel/taskstats.c:taskstats_user_cmd
```
```
In kernel/trace/fgraph.c (ffffffe00018f69a)
Location: include/linux/sched/signal.h:651
Inline: True
Inline callers:
  - kernel/trace/fgraph.c:register_ftrace_graph
```
```
In fs/exec.c (ffffffe00025e98e)
Location: include/linux/sched/signal.h:651
Inline: True
Inline callers:
  - fs/exec.c:__do_execve_file
```
```
In fs/fs_struct.c (ffffffe00028db04)
Location: include/linux/sched/signal.h:651
Inline: True
Inline callers:
  - fs/fs_struct.c:chroot_fs_refs
```
```
In fs/proc/base.c (ffffffe0002d8e5c)
Location: include/linux/sched/signal.h:651
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:do_io_accounting
```
```
In fs/proc/array.c (ffffffe0002db4da)
Location: include/linux/sched/signal.h:651
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
```
```
In drivers/tty/tty_io.c (ffffffe00052e5e6)
Location: include/linux/sched/signal.h:651
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
In kernel/exit.c (ffffffff8109f3a0)
Location: include/linux/sched/signal.h:651
Inline: True
Inline callers:
  - kernel/exit.c:do_wait
  - kernel/exit.c:release_task
```
```
In kernel/signal.c (ffffffff810ab7f8)
Location: include/linux/sched/signal.h:651
Inline: True
Inline callers:
  - kernel/signal.c:retarget_shared_pending
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:zap_other_threads
  - kernel/signal.c:complete_signal
  - kernel/signal.c:complete_signal
```
```
In kernel/sys.c (ffffffff810b722e)
Location: include/linux/sched/signal.h:651
Inline: True
Inline callers:
  - kernel/sys.c:getrusage
  - kernel/sys.c:__ia32_sys_getpriority
  - kernel/sys.c:__x64_sys_getpriority
  - kernel/sys.c:__ia32_sys_setpriority
  - kernel/sys.c:__x64_sys_setpriority
```
```
In kernel/cgroup/cgroup.c (ffffffff8115b44c)
Location: include/linux/sched/signal.h:651
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_attach_task
  - kernel/cgroup/cgroup.c:cgroup_migrate
  - kernel/cgroup/cgroup.c:cgroup_enable_task_cg_lists
```
```
In kernel/debug/gdbstub.c (ffffffff8117e3d0)
Location: include/linux/sched/signal.h:651
Inline: True
Inline callers:
  - kernel/debug/gdbstub.c:gdb_cmd_query
```
```
In kernel/debug/kdb/kdb_main.c (ffffffff81184e5c)
Location: include/linux/sched/signal.h:651
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_main.c:kdb_ps
  - kernel/debug/kdb/kdb_main.c:kdb_ps_suppressed
```
```
In kernel/debug/kdb/kdb_bt.c (ffffffff811867dc)
Location: include/linux/sched/signal.h:651
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
```
```
In kernel/taskstats.c (ffffffff8118db18)
Location: include/linux/sched/signal.h:651
Inline: True
```
```
In kernel/trace/fgraph.c (ffffffff811b2528)
Location: include/linux/sched/signal.h:651
Inline: True
Inline callers:
  - kernel/trace/fgraph.c:start_graph_tracing
```
```
In fs/exec.c (ffffffff812de0b6)
Location: include/linux/sched/signal.h:651
Inline: True
```
```
In fs/fs_struct.c (ffffffff8131399b)
Location: include/linux/sched/signal.h:651
Inline: True
Inline callers:
  - fs/fs_struct.c:chroot_fs_refs
```
```
In fs/proc/base.c (ffffffff8136f0f8)
Location: include/linux/sched/signal.h:651
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:do_io_accounting
```
```
In fs/proc/array.c (ffffffff8137167b)
Location: include/linux/sched/signal.h:651
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
```
```
In drivers/tty/tty_io.c (ffffffff81649463)
Location: include/linux/sched/signal.h:651
Inline: True
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
In kernel/exit.c (ffffffff8108ddd0)
Location: include/linux/sched/signal.h:651
Inline: True
Inline callers:
  - kernel/exit.c:do_wait
  - kernel/exit.c:release_task
```
```
In kernel/signal.c (ffffffff8109a198)
Location: include/linux/sched/signal.h:651
Inline: True
Inline callers:
  - kernel/signal.c:retarget_shared_pending
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:zap_other_threads
  - kernel/signal.c:complete_signal
  - kernel/signal.c:complete_signal
```
```
In kernel/sys.c (ffffffff810a5b6e)
Location: include/linux/sched/signal.h:651
Inline: True
Inline callers:
  - kernel/sys.c:getrusage
  - kernel/sys.c:__ia32_sys_getpriority
  - kernel/sys.c:__x64_sys_getpriority
  - kernel/sys.c:__ia32_sys_setpriority
  - kernel/sys.c:__x64_sys_setpriority
```
```
In kernel/cgroup/cgroup.c (ffffffff8114e73c)
Location: include/linux/sched/signal.h:651
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_attach_task
  - kernel/cgroup/cgroup.c:cgroup_migrate
  - kernel/cgroup/cgroup.c:cgroup_enable_task_cg_lists
```
```
In kernel/debug/gdbstub.c (ffffffff81171520)
Location: include/linux/sched/signal.h:651
Inline: True
Inline callers:
  - kernel/debug/gdbstub.c:gdb_cmd_query
```
```
In kernel/debug/kdb/kdb_main.c (ffffffff81177f9c)
Location: include/linux/sched/signal.h:651
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_main.c:kdb_ps
  - kernel/debug/kdb/kdb_main.c:kdb_ps_suppressed
```
```
In kernel/debug/kdb/kdb_bt.c (ffffffff8117991c)
Location: include/linux/sched/signal.h:651
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
```
```
In kernel/taskstats.c (ffffffff81180c36)
Location: include/linux/sched/signal.h:651
Inline: True
```
```
In kernel/trace/fgraph.c (ffffffff811a5338)
Location: include/linux/sched/signal.h:651
Inline: True
Inline callers:
  - kernel/trace/fgraph.c:start_graph_tracing
```
```
In fs/exec.c (ffffffff812cf3e6)
Location: include/linux/sched/signal.h:651
Inline: True
```
```
In fs/fs_struct.c (ffffffff813045ab)
Location: include/linux/sched/signal.h:651
Inline: True
Inline callers:
  - fs/fs_struct.c:chroot_fs_refs
```
```
In fs/proc/base.c (ffffffff8135fb88)
Location: include/linux/sched/signal.h:651
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:do_io_accounting
```
```
In fs/proc/array.c (ffffffff81362138)
Location: include/linux/sched/signal.h:651
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
```
```
In drivers/tty/tty_io.c (ffffffff816298c3)
Location: include/linux/sched/signal.h:651
Inline: True
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
In kernel/exit.c (ffffffff8109f350)
Location: include/linux/sched/signal.h:651
Inline: True
Inline callers:
  - kernel/exit.c:do_wait
  - kernel/exit.c:release_task
```
```
In kernel/signal.c (ffffffff810aad58)
Location: include/linux/sched/signal.h:651
Inline: True
Inline callers:
  - kernel/signal.c:retarget_shared_pending
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:zap_other_threads
  - kernel/signal.c:complete_signal
  - kernel/signal.c:complete_signal
```
```
In kernel/sys.c (ffffffff810b678e)
Location: include/linux/sched/signal.h:651
Inline: True
Inline callers:
  - kernel/sys.c:getrusage
  - kernel/sys.c:__ia32_sys_getpriority
  - kernel/sys.c:__x64_sys_getpriority
  - kernel/sys.c:__ia32_sys_setpriority
  - kernel/sys.c:__x64_sys_setpriority
```
```
In kernel/cgroup/cgroup.c (ffffffff8115921c)
Location: include/linux/sched/signal.h:651
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_attach_task
  - kernel/cgroup/cgroup.c:cgroup_migrate
  - kernel/cgroup/cgroup.c:cgroup_enable_task_cg_lists
```
```
In kernel/debug/gdbstub.c (ffffffff8117c1a0)
Location: include/linux/sched/signal.h:651
Inline: True
Inline callers:
  - kernel/debug/gdbstub.c:gdb_cmd_query
```
```
In kernel/debug/kdb/kdb_main.c (ffffffff81182c2c)
Location: include/linux/sched/signal.h:651
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_main.c:kdb_ps
  - kernel/debug/kdb/kdb_main.c:kdb_ps_suppressed
```
```
In kernel/debug/kdb/kdb_bt.c (ffffffff811845ac)
Location: include/linux/sched/signal.h:651
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
```
```
In kernel/taskstats.c (ffffffff8118b8e8)
Location: include/linux/sched/signal.h:651
Inline: True
```
```
In kernel/trace/fgraph.c (ffffffff811b02f8)
Location: include/linux/sched/signal.h:651
Inline: True
Inline callers:
  - kernel/trace/fgraph.c:start_graph_tracing
```
```
In fs/exec.c (ffffffff812dbec6)
Location: include/linux/sched/signal.h:651
Inline: True
```
```
In fs/fs_struct.c (ffffffff8131178b)
Location: include/linux/sched/signal.h:651
Inline: True
Inline callers:
  - fs/fs_struct.c:chroot_fs_refs
```
```
In fs/proc/base.c (ffffffff8136cbc8)
Location: include/linux/sched/signal.h:651
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:do_io_accounting
```
```
In fs/proc/array.c (ffffffff8136f14b)
Location: include/linux/sched/signal.h:651
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
```
```
In drivers/tty/tty_io.c (ffffffff81677823)
Location: include/linux/sched/signal.h:651
Inline: True
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
In kernel/exit.c (ffffffff810a72a0)
Location: include/linux/sched/signal.h:651
Inline: True
Inline callers:
  - kernel/exit.c:do_wait
  - kernel/exit.c:release_task
```
```
In kernel/signal.c (ffffffff810b2e38)
Location: include/linux/sched/signal.h:651
Inline: True
Inline callers:
  - kernel/signal.c:retarget_shared_pending
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:zap_other_threads
  - kernel/signal.c:complete_signal
  - kernel/signal.c:complete_signal
```
```
In kernel/sys.c (ffffffff810beb0e)
Location: include/linux/sched/signal.h:651
Inline: True
Inline callers:
  - kernel/sys.c:getrusage
  - kernel/sys.c:__ia32_sys_getpriority
  - kernel/sys.c:__x64_sys_getpriority
  - kernel/sys.c:__ia32_sys_setpriority
  - kernel/sys.c:__x64_sys_setpriority
```
```
In kernel/cgroup/cgroup.c (ffffffff81166281)
Location: include/linux/sched/signal.h:651
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_attach_task
  - kernel/cgroup/cgroup.c:cgroup_migrate
  - kernel/cgroup/cgroup.c:cgroup_enable_task_cg_lists
```
```
In kernel/debug/gdbstub.c (ffffffff81189ac0)
Location: include/linux/sched/signal.h:651
Inline: True
Inline callers:
  - kernel/debug/gdbstub.c:gdb_cmd_query
```
```
In kernel/debug/kdb/kdb_main.c (ffffffff8119054c)
Location: include/linux/sched/signal.h:651
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_main.c:kdb_ps
  - kernel/debug/kdb/kdb_main.c:kdb_ps_suppressed
```
```
In kernel/debug/kdb/kdb_bt.c (ffffffff81191efc)
Location: include/linux/sched/signal.h:651
Inline: True
Inline callers:
  - kernel/debug/kdb/kdb_bt.c:kdb_bt
```
```
In kernel/taskstats.c (ffffffff8119925d)
Location: include/linux/sched/signal.h:651
Inline: True
```
```
In kernel/trace/fgraph.c (ffffffff811be377)
Location: include/linux/sched/signal.h:651
Inline: True
Inline callers:
  - kernel/trace/fgraph.c:start_graph_tracing
```
```
In fs/exec.c (ffffffff812ecc4b)
Location: include/linux/sched/signal.h:651
Inline: True
```
```
In fs/fs_struct.c (ffffffff81322fd9)
Location: include/linux/sched/signal.h:651
Inline: True
Inline callers:
  - fs/fs_struct.c:chroot_fs_refs
```
```
In fs/proc/base.c (ffffffff813804be)
Location: include/linux/sched/signal.h:651
Inline: True
Inline callers:
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:proc_task_readdir
  - fs/proc/base.c:do_io_accounting
```
```
In fs/proc/array.c (ffffffff81382adb)
Location: include/linux/sched/signal.h:651
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
```
```
In drivers/tty/tty_io.c (ffffffff81691b4e)
Location: include/linux/sched/signal.h:651
Inline: True
```
</details>
</li>
</ul>

## Differences
