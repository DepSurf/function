# Function: <code>freezing_slow_path</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
bool freezing_slow_path(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/freezer.c (ffffffff810e9a90)
Location: kernel/freezer.c:40
Inline: True
Direct callers:
  - kernel/fork.c:_do_fork
  - kernel/exit.c:do_exit
  - kernel/signal.c:ptrace_stop
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:get_signal
  - kernel/signal.c:do_sigtimedwait
  - kernel/kmod.c:usermodehelper_read_trylock
  - kernel/kthread.c:kthread_freezable_should_stop
  - kernel/kthread.c:kthread_worker_fn
  - kernel/kthread.c:kthread_worker_fn
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/freezer.c:__refrigerator
  - kernel/freezer.c:set_freezable
  - kernel/freezer.c:freeze_task
  - kernel/time/hrtimer.c:do_nanosleep
  - kernel/time/alarmtimer.c:alarm_timer_nsleep
  - kernel/time/alarmtimer.c:alarm_timer_nsleep_restart
  - kernel/futex.c:futex_wait_queue_me
  - kernel/cgroup_freezer.c:freezer_read
  - kernel/audit.c:kauditd_thread
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/huge_memory.c:khugepaged
  - mm/huge_memory.c:khugepaged
  - mm/huge_memory.c:khugepaged
  - mm/huge_memory.c:khugepaged
  - fs/jbd2/journal.c:kjournald2
  - fs/jbd2/journal.c:kjournald2
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
  - drivers/virtio/virtio_balloon.c:balloon
  - drivers/virtio/virtio_balloon.c:balloon
  - drivers/tty/hvc/hvc_console.c:khvcd
  - drivers/char/virtio_console.c:port_fops_read
  - drivers/char/virtio_console.c:wait_port_writable
  - drivers/char/tpm/tpm-interface.c:wait_for_tpm_stat
  - net/unix/af_unix.c:unix_stream_read_generic
```
**Symbols:**

```
ffffffff810e9a90-ffffffff810e9af3: freezing_slow_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
bool freezing_slow_path(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/freezer.c (ffffffff810f07f0)
Location: kernel/freezer.c:40
Inline: True
Direct callers:
  - kernel/fork.c:_do_fork
  - kernel/exit.c:do_exit
  - kernel/signal.c:do_sigtimedwait
  - kernel/signal.c:get_signal
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:ptrace_stop
  - kernel/kmod.c:usermodehelper_read_trylock
  - kernel/kthread.c:kthread_worker_fn
  - kernel/kthread.c:kthread_worker_fn
  - kernel/kthread.c:kthread_freezable_should_stop
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/freezer.c:set_freezable
  - kernel/freezer.c:freeze_task
  - kernel/freezer.c:__refrigerator
  - kernel/time/hrtimer.c:do_nanosleep
  - kernel/time/alarmtimer.c:alarm_timer_nsleep
  - kernel/time/alarmtimer.c:alarm_timer_nsleep_restart
  - kernel/futex.c:futex_wait_queue_me
  - kernel/cgroup_freezer.c:freezer_read
  - kernel/audit.c:kauditd_thread
  - mm/oom_kill.c:oom_reaper
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd
  - mm/compaction.c:kcompactd
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - fs/jbd2/journal.c:kjournald2
  - fs/jbd2/journal.c:kjournald2
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
  - drivers/tty/hvc/hvc_console.c:khvcd
  - drivers/char/virtio_console.c:wait_port_writable
  - drivers/char/virtio_console.c:port_fops_read
  - drivers/char/tpm/tpm-interface.c:wait_for_tpm_stat
  - net/unix/af_unix.c:unix_stream_read_generic
```
**Symbols:**

```
ffffffff810f07f0-ffffffff810f084c: freezing_slow_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
bool freezing_slow_path(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/freezer.c (ffffffff810f7950)
Location: kernel/freezer.c:40
Inline: True
Direct callers:
  - kernel/fork.c:_do_fork
  - kernel/exit.c:do_exit
  - kernel/signal.c:do_sigtimedwait
  - kernel/signal.c:get_signal
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:ptrace_stop
  - kernel/kmod.c:usermodehelper_read_trylock
  - kernel/kthread.c:kthread_worker_fn
  - kernel/kthread.c:kthread_worker_fn
  - kernel/kthread.c:kthread_freezable_should_stop
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/freezer.c:set_freezable
  - kernel/freezer.c:freeze_task
  - kernel/freezer.c:__refrigerator
  - kernel/time/hrtimer.c:do_nanosleep
  - kernel/time/alarmtimer.c:alarm_timer_nsleep
  - kernel/time/alarmtimer.c:alarm_timer_nsleep_restart
  - kernel/futex.c:futex_wait_queue_me
  - kernel/cgroup_freezer.c:freezer_read
  - kernel/audit.c:kauditd_thread
  - mm/oom_kill.c:oom_reaper
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd
  - mm/compaction.c:kcompactd
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - fs/coredump.c:do_coredump
  - fs/jbd2/journal.c:kjournald2
  - fs/jbd2/journal.c:kjournald2
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
  - drivers/tty/hvc/hvc_console.c:khvcd
  - drivers/char/virtio_console.c:wait_port_writable
  - drivers/char/virtio_console.c:port_fops_read
  - drivers/char/tpm/tpm-interface.c:wait_for_tpm_stat
  - net/unix/af_unix.c:unix_stream_read_generic
```
**Symbols:**

```
ffffffff810f7950-ffffffff810f79a7: freezing_slow_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
bool freezing_slow_path(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/freezer.c (ffffffff810f9820)
Location: kernel/freezer.c:40
Inline: True
Direct callers:
  - kernel/fork.c:_do_fork
  - kernel/exit.c:do_exit
  - kernel/signal.c:do_sigtimedwait
  - kernel/signal.c:get_signal
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:ptrace_stop
  - kernel/kmod.c:usermodehelper_read_trylock
  - kernel/kthread.c:kthread_worker_fn
  - kernel/kthread.c:kthread_worker_fn
  - kernel/kthread.c:kthread_freezable_should_stop
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/freezer.c:set_freezable
  - kernel/freezer.c:freeze_task
  - kernel/freezer.c:__refrigerator
  - kernel/time/hrtimer.c:do_nanosleep
  - kernel/time/alarmtimer.c:alarmtimer_do_nsleep
  - kernel/futex.c:futex_wait_queue_me
  - kernel/cgroup/freezer.c:freezer_read
  - kernel/audit.c:kauditd_thread
  - mm/oom_kill.c:oom_reaper
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd
  - mm/compaction.c:kcompactd
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - fs/coredump.c:do_coredump
  - fs/jbd2/journal.c:kjournald2
  - fs/jbd2/journal.c:kjournald2
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
  - drivers/tty/hvc/hvc_console.c:khvcd
  - drivers/char/virtio_console.c:wait_port_writable
  - drivers/char/virtio_console.c:port_fops_read
  - drivers/char/tpm/tpm-interface.c:wait_for_tpm_stat
  - drivers/char/tpm/tpm_tis_core.c:request_locality
  - net/unix/af_unix.c:unix_stream_read_generic
```
**Symbols:**

```
ffffffff810f9820-ffffffff810f9876: freezing_slow_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
bool freezing_slow_path(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/freezer.c (ffffffff811042d0)
Location: kernel/freezer.c:40
Inline: True
Direct callers:
  - kernel/fork.c:_do_fork
  - kernel/exit.c:do_exit
  - kernel/signal.c:do_sigtimedwait
  - kernel/signal.c:get_signal
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:ptrace_stop
  - kernel/umh.c:usermodehelper_read_trylock
  - kernel/kthread.c:kthread_worker_fn
  - kernel/kthread.c:kthread_worker_fn
  - kernel/kthread.c:kthread_freezable_should_stop
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/freezer.c:set_freezable
  - kernel/freezer.c:freeze_task
  - kernel/freezer.c:__refrigerator
  - kernel/time/hrtimer.c:do_nanosleep
  - kernel/time/alarmtimer.c:alarmtimer_do_nsleep
  - kernel/futex.c:futex_wait_queue_me
  - kernel/cgroup/freezer.c:update_if_frozen
  - kernel/audit.c:kauditd_thread
  - mm/oom_kill.c:oom_reaper
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd
  - mm/compaction.c:kcompactd
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - fs/coredump.c:do_coredump
  - fs/jbd2/journal.c:kjournald2
  - fs/jbd2/journal.c:kjournald2
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
  - drivers/tty/hvc/hvc_console.c:khvcd
  - drivers/char/virtio_console.c:wait_port_writable
  - drivers/char/virtio_console.c:port_fops_read
  - drivers/char/tpm/tpm-interface.c:wait_for_tpm_stat
  - drivers/char/tpm/tpm_tis_core.c:request_locality
  - net/unix/af_unix.c:unix_stream_read_generic
```
**Symbols:**

```
ffffffff811042d0-ffffffff81104326: freezing_slow_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
bool freezing_slow_path(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/freezer.c (ffffffff8110f0d0)
Location: kernel/freezer.c:40
Inline: True
Direct callers:
  - kernel/fork.c:_do_fork
  - kernel/exit.c:do_exit
  - kernel/signal.c:get_signal
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:ptrace_stop
  - kernel/umh.c:usermodehelper_read_trylock
  - kernel/kthread.c:kthread_worker_fn
  - kernel/kthread.c:kthread_worker_fn
  - kernel/kthread.c:kthread_freezable_should_stop
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/freezer.c:set_freezable
  - kernel/freezer.c:freeze_task
  - kernel/freezer.c:__refrigerator
  - kernel/time/hrtimer.c:do_nanosleep
  - kernel/time/alarmtimer.c:alarmtimer_do_nsleep
  - kernel/futex.c:futex_wait_queue_me
  - kernel/cgroup/freezer.c:update_if_frozen
  - kernel/audit.c:kauditd_thread
  - mm/oom_kill.c:oom_reaper
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:balance_pgdat
  - mm/compaction.c:kcompactd
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - fs/coredump.c:do_coredump
  - fs/jbd2/journal.c:kjournald2
  - fs/jbd2/journal.c:kjournald2
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
  - drivers/tty/hvc/hvc_console.c:khvcd
  - drivers/char/virtio_console.c:wait_port_writable
  - drivers/char/virtio_console.c:port_fops_read
  - drivers/char/tpm/tpm_tis_core.c:request_locality
  - drivers/char/tpm/tpm_tis_core.c:release_locality
  - drivers/char/tpm/tpm_tis_core.c:wait_for_tpm_stat
  - net/unix/af_unix.c:unix_stream_read_generic
```
**Symbols:**

```
ffffffff8110f0d0-ffffffff8110f12d: freezing_slow_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
bool freezing_slow_path(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/freezer.c (ffffffff8111a710)
Location: kernel/freezer.c:42
Inline: True
Direct callers:
  - kernel/fork.c:_do_fork
  - kernel/exit.c:do_exit
  - kernel/signal.c:get_signal
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:ptrace_stop
  - kernel/umh.c:usermodehelper_read_trylock
  - kernel/kthread.c:kthread_worker_fn
  - kernel/kthread.c:kthread_worker_fn
  - kernel/kthread.c:kthread_freezable_should_stop
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/freezer.c:set_freezable
  - kernel/freezer.c:freeze_task
  - kernel/freezer.c:__refrigerator
  - kernel/time/hrtimer.c:do_nanosleep
  - kernel/time/alarmtimer.c:alarmtimer_do_nsleep
  - kernel/futex.c:futex_wait_queue_me
  - kernel/cgroup/freezer.c:update_if_frozen
  - kernel/audit.c:kauditd_thread
  - mm/oom_kill.c:oom_reaper
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:balance_pgdat
  - mm/compaction.c:kcompactd
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - fs/coredump.c:do_coredump
  - fs/jbd2/journal.c:kjournald2
  - fs/jbd2/journal.c:kjournald2
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
  - drivers/tty/hvc/hvc_console.c:khvcd
  - drivers/char/virtio_console.c:wait_port_writable
  - drivers/char/virtio_console.c:port_fops_read
  - drivers/char/tpm/tpm_tis_core.c:request_locality
  - drivers/char/tpm/tpm_tis_core.c:release_locality
  - drivers/char/tpm/tpm_tis_core.c:wait_for_tpm_stat
  - net/unix/af_unix.c:unix_stream_read_generic
```
**Symbols:**

```
ffffffff8111a710-ffffffff8111a76d: freezing_slow_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
bool freezing_slow_path(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/freezer.c (ffffffff81124e20)
Location: kernel/freezer.c:43
Inline: True
Direct callers:
  - kernel/fork.c:_do_fork
  - kernel/exit.c:do_exit
  - kernel/signal.c:get_signal
  - kernel/signal.c:get_signal
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:ptrace_stop
  - kernel/umh.c:usermodehelper_read_trylock
  - kernel/kthread.c:kthread_worker_fn
  - kernel/kthread.c:kthread_worker_fn
  - kernel/kthread.c:kthread_freezable_should_stop
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/freezer.c:set_freezable
  - kernel/freezer.c:freeze_task
  - kernel/freezer.c:__refrigerator
  - kernel/time/hrtimer.c:do_nanosleep
  - kernel/time/alarmtimer.c:alarmtimer_do_nsleep
  - kernel/futex.c:futex_wait_queue_me
  - kernel/cgroup/legacy_freezer.c:update_if_frozen
  - kernel/audit.c:kauditd_thread
  - mm/oom_kill.c:oom_reaper
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:balance_pgdat
  - mm/compaction.c:kcompactd
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - fs/coredump.c:do_coredump
  - fs/jbd2/journal.c:kjournald2
  - fs/jbd2/journal.c:kjournald2
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
  - drivers/tty/hvc/hvc_console.c:khvcd
  - drivers/char/virtio_console.c:wait_port_writable
  - drivers/char/virtio_console.c:port_fops_read
  - drivers/char/tpm/tpm_tis_core.c:request_locality
  - drivers/char/tpm/tpm_tis_core.c:release_locality
  - drivers/char/tpm/tpm_tis_core.c:wait_for_tpm_stat
  - net/unix/af_unix.c:unix_stream_read_generic
```
**Symbols:**

```
ffffffff81124e20-ffffffff81124e79: freezing_slow_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
bool freezing_slow_path(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/freezer.c (ffffffff81130de0)
Location: kernel/freezer.c:37
Inline: True
Direct callers:
  - kernel/fork.c:_do_fork
  - kernel/exit.c:do_exit
  - kernel/signal.c:get_signal
  - kernel/signal.c:get_signal
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:ptrace_stop
  - kernel/umh.c:usermodehelper_read_trylock
  - kernel/kthread.c:kthread_worker_fn
  - kernel/kthread.c:kthread_worker_fn
  - kernel/kthread.c:kthread_freezable_should_stop
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/freezer.c:set_freezable
  - kernel/freezer.c:freeze_task
  - kernel/freezer.c:__refrigerator
  - kernel/time/hrtimer.c:do_nanosleep
  - kernel/time/alarmtimer.c:alarmtimer_do_nsleep
  - kernel/futex.c:futex_wait_queue_me
  - kernel/cgroup/legacy_freezer.c:update_if_frozen
  - kernel/audit.c:kauditd_thread
  - mm/oom_kill.c:oom_reaper
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:balance_pgdat
  - mm/compaction.c:kcompactd
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - fs/coredump.c:do_coredump
  - fs/jbd2/journal.c:kjournald2
  - fs/jbd2/journal.c:kjournald2
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
  - drivers/tty/hvc/hvc_console.c:khvcd
  - drivers/char/virtio_console.c:wait_port_writable
  - drivers/char/virtio_console.c:port_fops_read
  - drivers/char/tpm/tpm_tis_core.c:request_locality
  - drivers/char/tpm/tpm_tis_core.c:release_locality
  - drivers/char/tpm/tpm_tis_core.c:wait_for_tpm_stat
  - net/unix/af_unix.c:unix_stream_read_generic
```
**Symbols:**

```
ffffffff81130de0-ffffffff81130e39: freezing_slow_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
bool freezing_slow_path(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/freezer.c (ffffffff81140190)
Location: kernel/freezer.c:37
Inline: True
Direct callers:
  - kernel/fork.c:wait_for_vfork_done
  - kernel/exit.c:exit_mm
  - kernel/signal.c:do_sigtimedwait
  - kernel/signal.c:get_signal
  - kernel/signal.c:get_signal
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:ptrace_stop
  - kernel/umh.c:usermodehelper_read_trylock
  - kernel/kthread.c:kthread_worker_fn
  - kernel/kthread.c:kthread_worker_fn
  - kernel/kthread.c:kthread_freezable_should_stop
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/freezer.c:set_freezable
  - kernel/freezer.c:freeze_task
  - kernel/freezer.c:__refrigerator
  - kernel/time/hrtimer.c:do_nanosleep
  - kernel/time/alarmtimer.c:alarmtimer_do_nsleep
  - kernel/futex.c:futex_wait_queue_me
  - kernel/cgroup/legacy_freezer.c:update_if_frozen
  - kernel/audit.c:kauditd_thread
  - mm/oom_kill.c:oom_reaper
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd_try_to_sleep
  - mm/vmscan.c:balance_pgdat
  - mm/compaction.c:kcompactd
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/khugepaged.c:khugepaged_wait_work
  - mm/khugepaged.c:khugepaged_wait_work
  - mm/khugepaged.c:khugepaged_do_scan
  - mm/khugepaged.c:khugepaged_do_scan
  - fs/coredump.c:coredump_wait
  - fs/jbd2/journal.c:kjournald2
  - fs/jbd2/journal.c:kjournald2
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
  - drivers/tty/hvc/hvc_console.c:khvcd
  - drivers/char/virtio_console.c:wait_port_writable
  - drivers/char/virtio_console.c:port_fops_read
  - drivers/char/tpm/tpm_tis_core.c:request_locality
  - drivers/char/tpm/tpm_tis_core.c:release_locality
  - drivers/char/tpm/tpm_tis_core.c:wait_for_tpm_stat
  - net/unix/af_unix.c:unix_stream_data_wait
```
**Symbols:**

```
ffffffff81140190-ffffffff811401f3: freezing_slow_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
bool freezing_slow_path(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/freezer.c (ffffffff8113c500)
Location: kernel/freezer.c:37
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/sgx/main.c:ksgxd
  - arch/x86/kernel/cpu/sgx/main.c:ksgxd
  - kernel/fork.c:wait_for_vfork_done
  - kernel/exit.c:exit_mm
  - kernel/signal.c:do_sigtimedwait
  - kernel/signal.c:get_signal
  - kernel/signal.c:get_signal
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:ptrace_stop
  - kernel/umh.c:usermodehelper_read_trylock
  - kernel/kthread.c:kthread_worker_fn
  - kernel/kthread.c:kthread_worker_fn
  - kernel/kthread.c:kthread_freezable_should_stop
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/freezer.c:set_freezable
  - kernel/freezer.c:freeze_task
  - kernel/freezer.c:__refrigerator
  - kernel/time/hrtimer.c:do_nanosleep
  - kernel/time/alarmtimer.c:alarmtimer_do_nsleep
  - kernel/futex.c:futex_wait_queue_me
  - kernel/cgroup/legacy_freezer.c:update_if_frozen
  - kernel/audit.c:kauditd_thread
  - mm/oom_kill.c:oom_reaper
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd_try_to_sleep
  - mm/vmscan.c:balance_pgdat
  - mm/compaction.c:kcompactd
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/khugepaged.c:khugepaged_wait_work
  - mm/khugepaged.c:khugepaged_wait_work
  - mm/khugepaged.c:khugepaged_do_scan
  - mm/khugepaged.c:khugepaged_do_scan
  - fs/coredump.c:coredump_wait
  - fs/jbd2/journal.c:kjournald2
  - fs/jbd2/journal.c:kjournald2
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
  - drivers/tty/hvc/hvc_console.c:khvcd
  - drivers/char/virtio_console.c:wait_port_writable
  - drivers/char/virtio_console.c:port_fops_read
  - drivers/char/tpm/tpm_tis_core.c:request_locality
  - drivers/char/tpm/tpm_tis_core.c:wait_for_tpm_stat
  - net/unix/af_unix.c:unix_stream_data_wait
```
**Symbols:**

```
ffffffff8113c500-ffffffff8113c563: freezing_slow_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
bool freezing_slow_path(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/freezer.c (ffffffff8113d760)
Location: kernel/freezer.c:37
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/sgx/main.c:ksgxd
  - arch/x86/kernel/cpu/sgx/main.c:ksgxd
  - kernel/fork.c:kernel_clone
  - kernel/exit.c:exit_mm
  - kernel/signal.c:do_sigtimedwait
  - kernel/signal.c:get_signal
  - kernel/signal.c:get_signal
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:ptrace_stop
  - kernel/umh.c:usermodehelper_read_trylock
  - kernel/kthread.c:kthread_worker_fn
  - kernel/kthread.c:kthread_worker_fn
  - kernel/kthread.c:kthread_freezable_should_stop
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/freezer.c:set_freezable
  - kernel/freezer.c:freeze_task
  - kernel/freezer.c:__refrigerator
  - kernel/time/hrtimer.c:do_nanosleep
  - kernel/time/alarmtimer.c:alarmtimer_do_nsleep
  - kernel/futex.c:futex_wait_queue_me
  - kernel/cgroup/legacy_freezer.c:update_if_frozen
  - kernel/audit.c:kauditd_thread
  - mm/oom_kill.c:oom_reaper
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd_try_to_sleep
  - mm/vmscan.c:balance_pgdat
  - mm/compaction.c:kcompactd
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged_wait_work
  - mm/khugepaged.c:khugepaged_wait_work
  - fs/coredump.c:dump_interrupted
  - fs/coredump.c:coredump_wait
  - fs/jbd2/journal.c:kjournald2
  - fs/jbd2/journal.c:kjournald2
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
  - drivers/tty/hvc/hvc_console.c:khvcd
  - drivers/char/virtio_console.c:wait_port_writable
  - drivers/char/virtio_console.c:port_fops_read
  - drivers/char/tpm/tpm_tis_core.c:request_locality
  - drivers/char/tpm/tpm_tis_core.c:wait_for_tpm_stat
  - net/unix/af_unix.c:unix_stream_data_wait
```
**Symbols:**

```
ffffffff8113d760-ffffffff8113d7c3: freezing_slow_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool freezing_slow_path(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/freezer.c (ffffffff81160905)
Location: kernel/freezer.c:37
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/sgx/main.c:ksgxd
  - arch/x86/kernel/cpu/sgx/main.c:ksgxd
  - kernel/fork.c:kernel_clone
  - kernel/exit.c:exit_mm
  - kernel/signal.c:do_sigtimedwait
  - kernel/signal.c:get_signal
  - kernel/signal.c:get_signal
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:ptrace_stop
  - kernel/umh.c:usermodehelper_read_trylock
  - kernel/kthread.c:kthread_worker_fn
  - kernel/kthread.c:kthread_worker_fn
  - kernel/kthread.c:kthread_freezable_should_stop
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/freezer.c:set_freezable
  - kernel/freezer.c:freeze_task
  - kernel/freezer.c:__refrigerator
  - kernel/time/hrtimer.c:do_nanosleep
  - kernel/time/alarmtimer.c:alarmtimer_do_nsleep
  - kernel/futex.c:futex_wait_queue_me
  - kernel/cgroup/legacy_freezer.c:update_if_frozen
  - kernel/audit.c:kauditd_thread
  - mm/oom_kill.c:oom_reaper
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd_try_to_sleep
  - mm/vmscan.c:balance_pgdat
  - mm/compaction.c:kcompactd
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged_wait_work
  - mm/khugepaged.c:khugepaged_wait_work
  - fs/coredump.c:dump_interrupted
  - fs/coredump.c:coredump_wait
  - fs/jbd2/journal.c:kjournald2
  - fs/jbd2/journal.c:kjournald2
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
  - drivers/xen/balloon.c:balloon_thread
  - drivers/tty/hvc/hvc_console.c:khvcd
  - drivers/char/virtio_console.c:wait_port_writable
  - drivers/char/virtio_console.c:port_fops_read
  - drivers/char/tpm/tpm_tis_core.c:request_locality
  - drivers/char/tpm/tpm_tis_core.c:wait_for_tpm_stat
  - net/unix/af_unix.c:unix_stream_data_wait
```
**Symbols:**

```
ffffffff81cb074d-ffffffff81cb0777: freezing_slow_path.cold (STB_LOCAL)
ffffffff811608e0-ffffffff81160960: freezing_slow_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
bool freezing_slow_path(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/freezer.c (0)
Location: kernel/freezer.c:37
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/main.c:ksgxd
  - arch/x86/kernel/cpu/sgx/main.c:ksgxd
  - kernel/fork.c:kernel_clone
  - kernel/exit.c:do_exit
  - kernel/signal.c:do_sigtimedwait
  - kernel/signal.c:get_signal
  - kernel/signal.c:get_signal
  - kernel/signal.c:do_signal_stop
  - kernel/umh.c:usermodehelper_read_trylock
  - kernel/kthread.c:kthread_worker_fn
  - kernel/kthread.c:kthread_worker_fn
  - kernel/kthread.c:kthread_freezable_should_stop
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/freezer.c:set_freezable
  - kernel/freezer.c:freeze_task
  - kernel/freezer.c:__refrigerator
  - kernel/time/hrtimer.c:do_nanosleep
  - kernel/time/alarmtimer.c:alarmtimer_do_nsleep
  - kernel/futex/waitwake.c:futex_wait_multiple
  - kernel/futex/waitwake.c:futex_wait_queue
  - kernel/cgroup/legacy_freezer.c:update_if_frozen
  - kernel/audit.c:kauditd_thread
  - mm/oom_kill.c:oom_reaper
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd_try_to_sleep
  - mm/vmscan.c:balance_pgdat
  - mm/compaction.c:kcompactd
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged_wait_work
  - mm/khugepaged.c:khugepaged_wait_work
  - fs/coredump.c:dump_interrupted
  - fs/coredump.c:coredump_wait
  - fs/jbd2/journal.c:kjournald2
  - fs/jbd2/journal.c:kjournald2
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
  - drivers/xen/balloon.c:balloon_thread
  - drivers/tty/hvc/hvc_console.c:khvcd
  - drivers/char/virtio_console.c:wait_port_writable
  - drivers/char/virtio_console.c:port_fops_read
  - drivers/char/tpm/tpm_tis_core.c:request_locality
  - drivers/char/tpm/tpm_tis_core.c:wait_for_tpm_stat
  - net/unix/af_unix.c:unix_stream_data_wait
```
**Symbols:**

```
ffffffff81e61cae-ffffffff81e61cd8: freezing_slow_path.cold (STB_LOCAL)
ffffffff81193650-ffffffff811936e8: freezing_slow_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
bool freezing_slow_path(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/freezer.c (0)
Location: kernel/freezer.c:38
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/main.c:ksgxd
  - kernel/signal.c:get_signal
  - kernel/umh.c:usermodehelper_read_trylock
  - kernel/kthread.c:kthread_worker_fn
  - kernel/kthread.c:kthread_worker_fn
  - kernel/kthread.c:kthread_freezable_should_stop
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/freezer.c:set_freezable
  - kernel/freezer.c:__thaw_task
  - kernel/freezer.c:freeze_task
  - kernel/freezer.c:__refrigerator
  - kernel/time/alarmtimer.c:alarmtimer_do_nsleep
  - kernel/cgroup/legacy_freezer.c:update_if_frozen
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd_try_to_sleep
  - mm/vmscan.c:balance_pgdat
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/khugepaged.c:khugepaged
  - fs/coredump.c:dump_interrupted
  - fs/jbd2/journal.c:kjournald2
  - fs/jbd2/journal.c:kjournald2
  - drivers/tty/hvc/hvc_console.c:khvcd
  - drivers/char/tpm/tpm_tis_core.c:request_locality
  - drivers/char/tpm/tpm_tis_core.c:wait_for_tpm_stat
```
**Symbols:**

```
ffffffff8205ac8f-ffffffff8205acb9: freezing_slow_path.cold (STB_LOCAL)
ffffffff811d0fc0-ffffffff811d1058: freezing_slow_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
bool freezing_slow_path(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/freezer.c (0)
Location: kernel/freezer.c:38
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/main.c:ksgxd
  - kernel/signal.c:get_signal
  - kernel/umh.c:usermodehelper_read_trylock
  - kernel/kthread.c:kthread_worker_fn
  - kernel/kthread.c:kthread_worker_fn
  - kernel/kthread.c:kthread_freezable_should_stop
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/freezer.c:set_freezable
  - kernel/freezer.c:__thaw_task
  - kernel/freezer.c:freeze_task
  - kernel/freezer.c:__refrigerator
  - kernel/time/alarmtimer.c:alarmtimer_do_nsleep
  - kernel/cgroup/legacy_freezer.c:update_if_frozen
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd_try_to_sleep
  - mm/vmscan.c:balance_pgdat
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/khugepaged.c:khugepaged
  - fs/coredump.c:dump_interrupted
  - fs/jbd2/journal.c:kjournald2
  - fs/jbd2/journal.c:kjournald2
  - drivers/tty/hvc/hvc_console.c:khvcd
  - drivers/char/tpm/tpm_tis_core.c:__tpm_tis_request_locality
  - drivers/char/tpm/tpm_tis_core.c:wait_for_tpm_stat
```
**Symbols:**

```
ffffffff820d9529-ffffffff820d9553: freezing_slow_path.cold (STB_LOCAL)
ffffffff811e5230-ffffffff811e52c8: freezing_slow_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
bool freezing_slow_path(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/freezer.c (0)
Location: kernel/freezer.c:38
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/main.c:ksgxd
  - kernel/signal.c:get_signal
  - kernel/umh.c:usermodehelper_read_trylock
  - kernel/kthread.c:kthread_worker_fn
  - kernel/kthread.c:kthread_worker_fn
  - kernel/kthread.c:kthread_freezable_should_stop
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/freezer.c:set_freezable
  - kernel/freezer.c:__thaw_task
  - kernel/freezer.c:freeze_task
  - kernel/freezer.c:__refrigerator
  - kernel/time/alarmtimer.c:alarmtimer_do_nsleep
  - kernel/cgroup/legacy_freezer.c:update_if_frozen
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd_try_to_sleep
  - mm/vmscan.c:balance_pgdat
  - mm/ksm.c:ksm_scan_thread
  - fs/coredump.c:dump_interrupted
  - fs/ext4/mballoc.c:ext4_trim_interrupted
  - fs/jbd2/journal.c:kjournald2
  - fs/jbd2/journal.c:kjournald2
  - drivers/tty/hvc/hvc_console.c:khvcd
  - drivers/char/tpm/tpm_tis_core.c:__tpm_tis_request_locality
  - drivers/char/tpm/tpm_tis_core.c:wait_for_tpm_stat
```
**Symbols:**

```
ffffffff821b4daa-ffffffff821b4dd4: freezing_slow_path.cold (STB_LOCAL)
ffffffff811fafc0-ffffffff811fb058: freezing_slow_path (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
bool freezing_slow_path(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/freezer.c (ffff800010197fb0)
Location: kernel/freezer.c:37
Inline: True
Direct callers:
  - kernel/fork.c:_do_fork
  - kernel/exit.c:do_exit
  - kernel/signal.c:get_signal
  - kernel/signal.c:get_signal
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:ptrace_stop
  - kernel/umh.c:usermodehelper_read_trylock
  - kernel/kthread.c:kthread_worker_fn
  - kernel/kthread.c:kthread_worker_fn
  - kernel/kthread.c:kthread_freezable_should_stop
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/freezer.c:set_freezable
  - kernel/freezer.c:freeze_task
  - kernel/freezer.c:__refrigerator
  - kernel/time/hrtimer.c:do_nanosleep
  - kernel/time/alarmtimer.c:alarmtimer_do_nsleep
  - kernel/futex.c:futex_wait_queue_me
  - kernel/cgroup/legacy_freezer.c:update_if_frozen
  - kernel/audit.c:kauditd_thread
  - mm/oom_kill.c:oom_reaper
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:balance_pgdat
  - mm/compaction.c:kcompactd
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - fs/coredump.c:do_coredump
  - fs/jbd2/journal.c:kjournald2
  - fs/jbd2/journal.c:kjournald2
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
  - drivers/tty/hvc/hvc_console.c:khvcd
  - drivers/char/virtio_console.c:wait_port_writable
  - drivers/char/virtio_console.c:port_fops_read
  - drivers/char/tpm/tpm_tis_core.c:request_locality
  - drivers/char/tpm/tpm_tis_core.c:release_locality
  - drivers/char/tpm/tpm_tis_core.c:wait_for_tpm_stat
  - net/unix/af_unix.c:unix_stream_read_generic
```
**Symbols:**

```
ffff800010197fb0-ffff800010198038: freezing_slow_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
bool freezing_slow_path(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/freezer.c (c03e3010)
Location: kernel/freezer.c:37
Inline: True
Direct callers:
  - kernel/fork.c:_do_fork
  - kernel/exit.c:do_exit
  - kernel/signal.c:do_sigtimedwait
  - kernel/signal.c:get_signal
  - kernel/signal.c:get_signal
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:ptrace_stop
  - kernel/umh.c:usermodehelper_read_trylock
  - kernel/kthread.c:kthread_worker_fn
  - kernel/kthread.c:kthread_worker_fn
  - kernel/kthread.c:kthread_freezable_should_stop
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/freezer.c:set_freezable
  - kernel/freezer.c:freeze_task
  - kernel/freezer.c:__refrigerator
  - kernel/time/hrtimer.c:do_nanosleep
  - kernel/time/alarmtimer.c:alarmtimer_do_nsleep
  - kernel/futex.c:futex_wait_queue_me
  - kernel/cgroup/legacy_freezer.c:freezer_read
  - kernel/audit.c:kauditd_thread
  - mm/oom_kill.c:oom_reaper
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:balance_pgdat
  - mm/compaction.c:kcompactd
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_do_scan
  - fs/coredump.c:do_coredump
  - fs/jbd2/journal.c:kjournald2
  - fs/jbd2/journal.c:kjournald2
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
  - drivers/tty/hvc/hvc_console.c:khvcd
  - drivers/char/virtio_console.c:wait_port_writable
  - drivers/char/virtio_console.c:port_fops_read
  - drivers/char/tpm/tpm_tis_core.c:request_locality
  - drivers/char/tpm/tpm_tis_core.c:release_locality
  - drivers/char/tpm/tpm_tis_core.c:wait_for_tpm_stat
  - net/unix/af_unix.c:unix_stream_read_generic
```
**Symbols:**

```
c03e3010-c03e3098: freezing_slow_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
bool freezing_slow_path(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/freezer.c (c0000000001f7e30)
Location: kernel/freezer.c:37
Inline: True
Direct callers:
  - arch/powerpc/platforms/powernv/opal.c:kopald
  - kernel/fork.c:_do_fork
  - kernel/exit.c:do_exit
  - kernel/signal.c:get_signal
  - kernel/signal.c:get_signal
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:ptrace_stop
  - kernel/umh.c:usermodehelper_read_trylock
  - kernel/kthread.c:kthread_worker_fn
  - kernel/kthread.c:kthread_worker_fn
  - kernel/kthread.c:kthread_freezable_should_stop
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/freezer.c:set_freezable
  - kernel/freezer.c:freeze_task
  - kernel/freezer.c:__refrigerator
  - kernel/time/hrtimer.c:do_nanosleep
  - kernel/time/alarmtimer.c:alarmtimer_do_nsleep
  - kernel/futex.c:futex_wait_queue_me
  - kernel/cgroup/legacy_freezer.c:update_if_frozen
  - kernel/audit.c:kauditd_thread
  - mm/oom_kill.c:oom_reaper
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:balance_pgdat
  - mm/compaction.c:kcompactd
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - fs/coredump.c:do_coredump
  - fs/jbd2/journal.c:kjournald2
  - fs/jbd2/journal.c:kjournald2
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
  - drivers/tty/hvc/hvc_console.c:khvcd
  - drivers/char/virtio_console.c:wait_port_writable
  - drivers/char/virtio_console.c:port_fops_read
  - drivers/char/tpm/tpm_tis_core.c:request_locality
  - drivers/char/tpm/tpm_tis_core.c:release_locality
  - drivers/char/tpm/tpm_tis_core.c:wait_for_tpm_stat
  - net/unix/af_unix.c:unix_stream_read_generic
```
**Symbols:**

```
c0000000001f7e30-c0000000001f7f18: freezing_slow_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
bool freezing_slow_path(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/freezer.c (ffffffe000128d90)
Location: kernel/freezer.c:37
Inline: True
Direct callers:
  - kernel/fork.c:_do_fork
  - kernel/exit.c:do_exit
  - kernel/signal.c:__se_sys_rt_sigtimedwait
  - kernel/signal.c:get_signal
  - kernel/signal.c:get_signal
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:ptrace_stop
  - kernel/umh.c:usermodehelper_read_trylock
  - kernel/kthread.c:kthread_worker_fn
  - kernel/kthread.c:kthread_worker_fn
  - kernel/kthread.c:kthread_freezable_should_stop
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/freezer.c:set_freezable
  - kernel/freezer.c:freeze_task
  - kernel/freezer.c:__refrigerator
  - kernel/time/hrtimer.c:do_nanosleep
  - kernel/time/alarmtimer.c:alarmtimer_do_nsleep
  - kernel/futex.c:futex_wait_queue_me
  - kernel/cgroup/legacy_freezer.c:update_if_frozen
  - kernel/audit.c:kauditd_thread
  - mm/oom_kill.c:oom_reaper
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:balance_pgdat
  - mm/compaction.c:kcompactd
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_do_scan
  - fs/coredump.c:do_coredump
  - fs/jbd2/journal.c:kjournald2
  - fs/jbd2/journal.c:kjournald2
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
  - drivers/tty/hvc/hvc_console.c:khvcd
  - drivers/char/virtio_console.c:wait_port_writable
  - drivers/char/virtio_console.c:port_fops_read
  - drivers/char/tpm/tpm_tis_core.c:request_locality
  - drivers/char/tpm/tpm_tis_core.c:release_locality
  - drivers/char/tpm/tpm_tis_core.c:wait_for_tpm_stat
  - net/unix/af_unix.c:unix_stream_read_generic
```
**Symbols:**

```
ffffffe000128d90-ffffffe000128e00: freezing_slow_path (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
bool freezing_slow_path(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/freezer.c (ffffffff81129590)
Location: kernel/freezer.c:37
Inline: True
Direct callers:
  - kernel/fork.c:_do_fork
  - kernel/exit.c:do_exit
  - kernel/signal.c:get_signal
  - kernel/signal.c:get_signal
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:ptrace_stop
  - kernel/umh.c:usermodehelper_read_trylock
  - kernel/kthread.c:kthread_worker_fn
  - kernel/kthread.c:kthread_worker_fn
  - kernel/kthread.c:kthread_freezable_should_stop
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/freezer.c:set_freezable
  - kernel/freezer.c:freeze_task
  - kernel/freezer.c:__refrigerator
  - kernel/time/hrtimer.c:do_nanosleep
  - kernel/time/alarmtimer.c:alarmtimer_do_nsleep
  - kernel/futex.c:futex_wait_queue_me
  - kernel/cgroup/legacy_freezer.c:update_if_frozen
  - kernel/audit.c:kauditd_thread
  - mm/oom_kill.c:oom_reaper
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:balance_pgdat
  - mm/compaction.c:kcompactd
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - fs/coredump.c:do_coredump
  - fs/jbd2/journal.c:kjournald2
  - fs/jbd2/journal.c:kjournald2
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
  - drivers/tty/hvc/hvc_console.c:khvcd
  - drivers/char/virtio_console.c:wait_port_writable
  - drivers/char/virtio_console.c:port_fops_read
  - drivers/char/tpm/tpm_tis_core.c:request_locality
  - drivers/char/tpm/tpm_tis_core.c:release_locality
  - drivers/char/tpm/tpm_tis_core.c:wait_for_tpm_stat
  - net/unix/af_unix.c:unix_stream_read_generic
```
**Symbols:**

```
ffffffff81129590-ffffffff811295e9: freezing_slow_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
bool freezing_slow_path(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/freezer.c (ffffffff8111be20)
Location: kernel/freezer.c:37
Inline: True
Direct callers:
  - kernel/fork.c:_do_fork
  - kernel/exit.c:do_exit
  - kernel/signal.c:get_signal
  - kernel/signal.c:get_signal
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:ptrace_stop
  - kernel/umh.c:usermodehelper_read_trylock
  - kernel/kthread.c:kthread_worker_fn
  - kernel/kthread.c:kthread_worker_fn
  - kernel/kthread.c:kthread_freezable_should_stop
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/freezer.c:set_freezable
  - kernel/freezer.c:freeze_task
  - kernel/freezer.c:__refrigerator
  - kernel/time/hrtimer.c:do_nanosleep
  - kernel/time/alarmtimer.c:alarmtimer_do_nsleep
  - kernel/futex.c:futex_wait_queue_me
  - kernel/cgroup/legacy_freezer.c:update_if_frozen
  - kernel/audit.c:kauditd_thread
  - mm/oom_kill.c:oom_reaper
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:balance_pgdat
  - mm/compaction.c:kcompactd
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - fs/coredump.c:do_coredump
  - fs/jbd2/journal.c:kjournald2
  - fs/jbd2/journal.c:kjournald2
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
  - drivers/tty/hvc/hvc_console.c:khvcd
  - drivers/char/virtio_console.c:wait_port_writable
  - drivers/char/virtio_console.c:port_fops_read
  - drivers/char/tpm/tpm_tis_core.c:request_locality
  - drivers/char/tpm/tpm_tis_core.c:release_locality
  - drivers/char/tpm/tpm_tis_core.c:wait_for_tpm_stat
  - net/unix/af_unix.c:unix_stream_read_generic
```
**Symbols:**

```
ffffffff8111be20-ffffffff8111be79: freezing_slow_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
bool freezing_slow_path(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/freezer.c (ffffffff811272b0)
Location: kernel/freezer.c:37
Inline: True
Direct callers:
  - kernel/fork.c:_do_fork
  - kernel/exit.c:do_exit
  - kernel/signal.c:get_signal
  - kernel/signal.c:get_signal
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:ptrace_stop
  - kernel/umh.c:usermodehelper_read_trylock
  - kernel/kthread.c:kthread_worker_fn
  - kernel/kthread.c:kthread_worker_fn
  - kernel/kthread.c:kthread_freezable_should_stop
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/freezer.c:set_freezable
  - kernel/freezer.c:freeze_task
  - kernel/freezer.c:__refrigerator
  - kernel/time/hrtimer.c:do_nanosleep
  - kernel/time/alarmtimer.c:alarmtimer_do_nsleep
  - kernel/futex.c:futex_wait_queue_me
  - kernel/cgroup/legacy_freezer.c:update_if_frozen
  - kernel/audit.c:kauditd_thread
  - mm/oom_kill.c:oom_reaper
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:balance_pgdat
  - mm/compaction.c:kcompactd
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - fs/coredump.c:do_coredump
  - fs/jbd2/journal.c:kjournald2
  - fs/jbd2/journal.c:kjournald2
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
  - drivers/tty/hvc/hvc_console.c:khvcd
  - drivers/char/virtio_console.c:wait_port_writable
  - drivers/char/virtio_console.c:port_fops_read
  - drivers/char/tpm/tpm_tis_core.c:request_locality
  - drivers/char/tpm/tpm_tis_core.c:release_locality
  - drivers/char/tpm/tpm_tis_core.c:wait_for_tpm_stat
  - net/unix/af_unix.c:unix_stream_read_generic
```
**Symbols:**

```
ffffffff811272b0-ffffffff81127309: freezing_slow_path (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
bool freezing_slow_path(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/freezer.c (ffffffff81133910)
Location: kernel/freezer.c:37
Inline: True
Direct callers:
  - kernel/fork.c:_do_fork
  - kernel/exit.c:do_exit
  - kernel/signal.c:get_signal
  - kernel/signal.c:get_signal
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:ptrace_stop
  - kernel/umh.c:usermodehelper_read_trylock
  - kernel/kthread.c:kthread_worker_fn
  - kernel/kthread.c:kthread_worker_fn
  - kernel/kthread.c:kthread_freezable_should_stop
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/freezer.c:set_freezable
  - kernel/freezer.c:freeze_task
  - kernel/freezer.c:__refrigerator
  - kernel/time/hrtimer.c:do_nanosleep
  - kernel/time/alarmtimer.c:alarmtimer_do_nsleep
  - kernel/futex.c:futex_wait_queue_me
  - kernel/cgroup/legacy_freezer.c:update_if_frozen
  - kernel/audit.c:kauditd_thread
  - mm/oom_kill.c:oom_reaper
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:balance_pgdat
  - mm/compaction.c:kcompactd
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - fs/coredump.c:do_coredump
  - fs/jbd2/journal.c:kjournald2
  - fs/jbd2/journal.c:kjournald2
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
  - drivers/tty/hvc/hvc_console.c:khvcd
  - drivers/char/virtio_console.c:wait_port_writable
  - drivers/char/virtio_console.c:port_fops_read
  - drivers/char/tpm/tpm_tis_core.c:request_locality
  - drivers/char/tpm/tpm_tis_core.c:release_locality
  - drivers/char/tpm/tpm_tis_core.c:wait_for_tpm_stat
  - net/unix/af_unix.c:unix_stream_read_generic
```
**Symbols:**

```
ffffffff81133910-ffffffff81133969: freezing_slow_path (STB_GLOBAL)
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
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
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
