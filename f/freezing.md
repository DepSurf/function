# Function: <code>freezing</code>

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
In kernel/fork.c (ffffffff81080394)
Location: include/linux/freezer.h:34
Inline: True
Inline callers:
  - kernel/fork.c:_do_fork
```
```
In kernel/exit.c (ffffffff81083ab1)
Location: include/linux/freezer.h:34
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/signal.c (ffffffff8108d17f)
Location: include/linux/freezer.h:34
Inline: True
Inline callers:
  - kernel/signal.c:ptrace_stop
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:get_signal
  - kernel/signal.c:do_sigtimedwait
```
```
In kernel/kmod.c (ffffffff810960b2)
Location: include/linux/freezer.h:34
Inline: True
Inline callers:
  - kernel/kmod.c:usermodehelper_read_trylock
```
```
In kernel/kthread.c (ffffffff810a0102)
Location: include/linux/freezer.h:34
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_freezable_should_stop
  - kernel/kthread.c:kthread_worker_fn
  - kernel/kthread.c:kthread_worker_fn
```
```
In kernel/power/process.c (ffffffff810cdb77)
Location: include/linux/freezer.h:34
Inline: True
Inline callers:
  - kernel/power/process.c:try_to_freeze_tasks
```
```
In kernel/freezer.c (ffffffff810e9b9d)
Location: include/linux/freezer.h:34
Inline: True
Inline callers:
  - kernel/freezer.c:__refrigerator
  - kernel/freezer.c:set_freezable
  - kernel/freezer.c:freeze_task
```
```
In kernel/time/hrtimer.c (ffffffff818236b0)
Location: include/linux/freezer.h:34
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:do_nanosleep
```
```
In kernel/time/alarmtimer.c (ffffffff810fb56c)
Location: include/linux/freezer.h:34
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_timer_nsleep
  - kernel/time/alarmtimer.c:alarm_timer_nsleep_restart
```
```
In kernel/futex.c (ffffffff81100121)
Location: include/linux/freezer.h:34
Inline: True
Inline callers:
  - kernel/futex.c:futex_wait_queue_me
```
```
In kernel/cgroup_freezer.c (ffffffff8111a062)
Location: include/linux/freezer.h:34
Inline: True
Inline callers:
  - kernel/cgroup_freezer.c:freezer_read
```
```
In kernel/audit.c (ffffffff8112109d)
Location: include/linux/freezer.h:34
Inline: True
Inline callers:
  - kernel/audit.c:kauditd_thread
```
```
In mm/vmscan.c (ffffffff811a5942)
Location: include/linux/freezer.h:34
Inline: True
Inline callers:
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd
```
```
In mm/ksm.c (ffffffff811e6447)
Location: include/linux/freezer.h:34
Inline: True
Inline callers:
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
```
```
In mm/huge_memory.c (ffffffff811f4747)
Location: include/linux/freezer.h:34
Inline: True
Inline callers:
  - mm/huge_memory.c:khugepaged
  - mm/huge_memory.c:khugepaged
  - mm/huge_memory.c:khugepaged
  - mm/huge_memory.c:khugepaged
```
```
In fs/ext4/super.c (ffffffff812ad137)
Location: include/linux/freezer.h:34
Inline: True
```
```
In fs/jbd2/journal.c (ffffffff812ef19e)
Location: include/linux/freezer.h:34
Inline: True
Inline callers:
  - fs/jbd2/journal.c:kjournald2
  - fs/jbd2/journal.c:kjournald2
```
```
In fs/ecryptfs/kthread.c (ffffffff8130ae0f)
Location: include/linux/freezer.h:34
Inline: True
Inline callers:
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
```
```
In drivers/virtio/virtio_balloon.c (ffffffff814c425f)
Location: include/linux/freezer.h:34
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:balloon
  - drivers/virtio/virtio_balloon.c:balloon
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff814fe604)
Location: include/linux/freezer.h:34
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:khvcd
```
```
In drivers/char/virtio_console.c (ffffffff8151696a)
Location: include/linux/freezer.h:34
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:port_fops_read
  - drivers/char/virtio_console.c:wait_port_writable
```
```
In drivers/char/tpm/tpm-interface.c (ffffffff815237dd)
Location: include/linux/freezer.h:34
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-interface.c:wait_for_tpm_stat
```
```
In drivers/char/tpm/tpm_tis.c (ffffffff81528b0d)
Location: include/linux/freezer.h:34
Inline: True
```
```
In net/unix/af_unix.c (ffffffff817bfaf7)
Location: include/linux/freezer.h:34
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
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
In kernel/fork.c (ffffffff810821cc)
Location: include/linux/freezer.h:34
Inline: True
Inline callers:
  - kernel/fork.c:_do_fork
```
```
In kernel/exit.c (ffffffff81086bcc)
Location: include/linux/freezer.h:34
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/signal.c (ffffffff81094502)
Location: include/linux/freezer.h:34
Inline: True
Inline callers:
  - kernel/signal.c:do_sigtimedwait
  - kernel/signal.c:get_signal
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:ptrace_stop
```
```
In kernel/kmod.c (ffffffff81099462)
Location: include/linux/freezer.h:34
Inline: True
Inline callers:
  - kernel/kmod.c:usermodehelper_read_trylock
```
```
In kernel/kthread.c (ffffffff810a41e6)
Location: include/linux/freezer.h:34
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_worker_fn
  - kernel/kthread.c:kthread_worker_fn
  - kernel/kthread.c:kthread_freezable_should_stop
```
```
In kernel/power/process.c (ffffffff810d261a)
Location: include/linux/freezer.h:34
Inline: True
Inline callers:
  - kernel/power/process.c:try_to_freeze_tasks
```
```
In kernel/freezer.c (ffffffff810f09e5)
Location: include/linux/freezer.h:34
Inline: True
Inline callers:
  - kernel/freezer.c:set_freezable
  - kernel/freezer.c:freeze_task
  - kernel/freezer.c:__refrigerator
```
```
In kernel/time/hrtimer.c (ffffffff8189e320)
Location: include/linux/freezer.h:34
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:do_nanosleep
```
```
In kernel/time/alarmtimer.c (ffffffff81102893)
Location: include/linux/freezer.h:34
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_timer_nsleep
  - kernel/time/alarmtimer.c:alarm_timer_nsleep_restart
```
```
In kernel/futex.c (ffffffff81107123)
Location: include/linux/freezer.h:34
Inline: True
Inline callers:
  - kernel/futex.c:futex_wait_queue_me
```
```
In kernel/cgroup_freezer.c (ffffffff81121e8b)
Location: include/linux/freezer.h:34
Inline: True
Inline callers:
  - kernel/cgroup_freezer.c:freezer_read
```
```
In kernel/audit.c (ffffffff81128fe7)
Location: include/linux/freezer.h:34
Inline: True
Inline callers:
  - kernel/audit.c:kauditd_thread
```
```
In mm/oom_kill.c (ffffffff811a5179)
Location: include/linux/freezer.h:34
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_reaper
```
```
In mm/vmscan.c (ffffffff811bc3a3)
Location: include/linux/freezer.h:34
Inline: True
Inline callers:
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd
```
```
In mm/compaction.c (ffffffff811d1ed3)
Location: include/linux/freezer.h:34
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd
```
```
In mm/ksm.c (ffffffff81204675)
Location: include/linux/freezer.h:34
Inline: True
Inline callers:
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
```
```
In mm/khugepaged.c (ffffffff8121c20b)
Location: include/linux/freezer.h:34
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
```
```
In fs/ext4/super.c (ffffffff812e1a10)
Location: include/linux/freezer.h:34
Inline: True
```
```
In fs/jbd2/journal.c (ffffffff8131d6ee)
Location: include/linux/freezer.h:34
Inline: True
Inline callers:
  - fs/jbd2/journal.c:kjournald2
  - fs/jbd2/journal.c:kjournald2
```
```
In fs/ecryptfs/kthread.c (ffffffff8133f059)
Location: include/linux/freezer.h:34
Inline: True
Inline callers:
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff8154f13c)
Location: include/linux/freezer.h:34
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:khvcd
```
```
In drivers/char/virtio_console.c (ffffffff8156a5c2)
Location: include/linux/freezer.h:34
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:wait_port_writable
  - drivers/char/virtio_console.c:port_fops_read
```
```
In drivers/char/tpm/tpm-interface.c (ffffffff8157671c)
Location: include/linux/freezer.h:34
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-interface.c:wait_for_tpm_stat
```
```
In drivers/char/tpm/tpm_tis_core.c (ffffffff8157bf00)
Location: include/linux/freezer.h:34
Inline: True
```
```
In net/unix/af_unix.c (ffffffff8182ca29)
Location: include/linux/freezer.h:34
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
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
In kernel/fork.c (ffffffff81086c2c)
Location: include/linux/freezer.h:34
Inline: True
Inline callers:
  - kernel/fork.c:_do_fork
```
```
In kernel/exit.c (ffffffff8108bb36)
Location: include/linux/freezer.h:34
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/signal.c (ffffffff810994f3)
Location: include/linux/freezer.h:34
Inline: True
Inline callers:
  - kernel/signal.c:do_sigtimedwait
  - kernel/signal.c:get_signal
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:ptrace_stop
```
```
In kernel/kmod.c (ffffffff8109e412)
Location: include/linux/freezer.h:34
Inline: True
Inline callers:
  - kernel/kmod.c:usermodehelper_read_trylock
```
```
In kernel/kthread.c (ffffffff810a99cb)
Location: include/linux/freezer.h:34
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_worker_fn
  - kernel/kthread.c:kthread_worker_fn
  - kernel/kthread.c:kthread_freezable_should_stop
```
```
In kernel/power/process.c (ffffffff810d91c4)
Location: include/linux/freezer.h:34
Inline: True
Inline callers:
  - kernel/power/process.c:try_to_freeze_tasks
```
```
In kernel/freezer.c (ffffffff810f7b45)
Location: include/linux/freezer.h:34
Inline: True
Inline callers:
  - kernel/freezer.c:set_freezable
  - kernel/freezer.c:freeze_task
  - kernel/freezer.c:__refrigerator
```
```
In kernel/time/hrtimer.c (ffffffff818d31c1)
Location: include/linux/freezer.h:34
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:do_nanosleep
```
```
In kernel/time/alarmtimer.c (ffffffff811051b3)
Location: include/linux/freezer.h:34
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarm_timer_nsleep
  - kernel/time/alarmtimer.c:alarm_timer_nsleep_restart
```
```
In kernel/futex.c (ffffffff8110e8e3)
Location: include/linux/freezer.h:34
Inline: True
Inline callers:
  - kernel/futex.c:futex_wait_queue_me
```
```
In kernel/cgroup_freezer.c (ffffffff8112a4c1)
Location: include/linux/freezer.h:34
Inline: True
Inline callers:
  - kernel/cgroup_freezer.c:freezer_read
```
```
In kernel/audit.c (ffffffff81132d5f)
Location: include/linux/freezer.h:34
Inline: True
Inline callers:
  - kernel/audit.c:kauditd_thread
```
```
In mm/oom_kill.c (ffffffff811b51ff)
Location: include/linux/freezer.h:34
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_reaper
```
```
In mm/vmscan.c (ffffffff811cca68)
Location: include/linux/freezer.h:34
Inline: True
Inline callers:
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd
```
```
In mm/compaction.c (ffffffff811e1e2c)
Location: include/linux/freezer.h:34
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd
```
```
In mm/ksm.c (ffffffff8121677a)
Location: include/linux/freezer.h:34
Inline: True
Inline callers:
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
```
```
In mm/khugepaged.c (ffffffff8122d9b3)
Location: include/linux/freezer.h:34
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
```
```
In fs/coredump.c (ffffffff812af6df)
Location: include/linux/freezer.h:34
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/ext4/super.c (ffffffff812f7479)
Location: include/linux/freezer.h:34
Inline: True
```
```
In fs/jbd2/journal.c (ffffffff8133366e)
Location: include/linux/freezer.h:34
Inline: True
Inline callers:
  - fs/jbd2/journal.c:kjournald2
  - fs/jbd2/journal.c:kjournald2
```
```
In fs/ecryptfs/kthread.c (ffffffff81354de1)
Location: include/linux/freezer.h:34
Inline: True
Inline callers:
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff8157b9bc)
Location: include/linux/freezer.h:34
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:khvcd
```
```
In drivers/char/virtio_console.c (ffffffff81596cf6)
Location: include/linux/freezer.h:34
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:wait_port_writable
  - drivers/char/virtio_console.c:port_fops_read
```
```
In drivers/char/tpm/tpm-interface.c (ffffffff815a2de0)
Location: include/linux/freezer.h:34
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-interface.c:wait_for_tpm_stat
```
```
In drivers/char/tpm/tpm_tis_core.c (ffffffff815a8336)
Location: include/linux/freezer.h:34
Inline: True
```
```
In net/unix/af_unix.c (ffffffff8185e4ef)
Location: include/linux/freezer.h:34
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
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
In kernel/fork.c (ffffffff81083979)
Location: include/linux/freezer.h:34
Inline: True
Inline callers:
  - kernel/fork.c:_do_fork
```
```
In kernel/exit.c (ffffffff81088cc5)
Location: include/linux/freezer.h:34
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/signal.c (ffffffff81093252)
Location: include/linux/freezer.h:34
Inline: True
Inline callers:
  - kernel/signal.c:do_sigtimedwait
  - kernel/signal.c:get_signal
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:ptrace_stop
```
```
In kernel/kmod.c (ffffffff8109bb90)
Location: include/linux/freezer.h:34
Inline: True
Inline callers:
  - kernel/kmod.c:usermodehelper_read_trylock
```
```
In kernel/kthread.c (ffffffff810a664a)
Location: include/linux/freezer.h:34
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_worker_fn
  - kernel/kthread.c:kthread_worker_fn
  - kernel/kthread.c:kthread_freezable_should_stop
```
```
In kernel/power/process.c (ffffffff810d81e4)
Location: include/linux/freezer.h:34
Inline: True
Inline callers:
  - kernel/power/process.c:try_to_freeze_tasks
```
```
In kernel/freezer.c (ffffffff810f9a15)
Location: include/linux/freezer.h:34
Inline: True
Inline callers:
  - kernel/freezer.c:set_freezable
  - kernel/freezer.c:freeze_task
  - kernel/freezer.c:__refrigerator
```
```
In kernel/time/hrtimer.c (ffffffff8190a344)
Location: include/linux/freezer.h:34
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:do_nanosleep
```
```
In kernel/time/alarmtimer.c (ffffffff81106f88)
Location: include/linux/freezer.h:34
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarmtimer_do_nsleep
```
```
In kernel/futex.c (ffffffff8110fdd9)
Location: include/linux/freezer.h:34
Inline: True
Inline callers:
  - kernel/futex.c:futex_wait_queue_me
```
```
In kernel/cgroup/freezer.c (ffffffff8112b18d)
Location: include/linux/freezer.h:34
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:freezer_read
```
```
In kernel/audit.c (ffffffff81134361)
Location: include/linux/freezer.h:34
Inline: True
Inline callers:
  - kernel/audit.c:kauditd_thread
```
```
In mm/oom_kill.c (ffffffff811bc9bd)
Location: include/linux/freezer.h:34
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_reaper
```
```
In mm/vmscan.c (ffffffff811d5728)
Location: include/linux/freezer.h:34
Inline: True
Inline callers:
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd
```
```
In mm/compaction.c (ffffffff811ebc2c)
Location: include/linux/freezer.h:34
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd
```
```
In mm/ksm.c (ffffffff812223c3)
Location: include/linux/freezer.h:34
Inline: True
Inline callers:
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
```
```
In mm/khugepaged.c (ffffffff8123978c)
Location: include/linux/freezer.h:34
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
```
```
In fs/coredump.c (ffffffff812bcb33)
Location: include/linux/freezer.h:34
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/ext4/super.c (ffffffff8132be39)
Location: include/linux/freezer.h:34
Inline: True
```
```
In fs/jbd2/journal.c (ffffffff81348416)
Location: include/linux/freezer.h:34
Inline: True
Inline callers:
  - fs/jbd2/journal.c:kjournald2
  - fs/jbd2/journal.c:kjournald2
```
```
In fs/ecryptfs/kthread.c (ffffffff81369971)
Location: include/linux/freezer.h:34
Inline: True
Inline callers:
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff8158f8fc)
Location: include/linux/freezer.h:34
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:khvcd
```
```
In drivers/char/virtio_console.c (ffffffff815aad24)
Location: include/linux/freezer.h:34
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:wait_port_writable
  - drivers/char/virtio_console.c:port_fops_read
```
```
In drivers/char/tpm/tpm-interface.c (ffffffff815b6932)
Location: include/linux/freezer.h:34
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-interface.c:wait_for_tpm_stat
```
```
In drivers/char/tpm/tpm_tis_core.c (ffffffff815bd857)
Location: include/linux/freezer.h:34
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis_core.c:request_locality
```
```
In net/unix/af_unix.c (ffffffff818838b5)
Location: include/linux/freezer.h:34
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
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
In kernel/fork.c (ffffffff8108a25f)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - kernel/fork.c:_do_fork
```
```
In kernel/exit.c (ffffffff8108fa0b)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/signal.c (ffffffff8109a135)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - kernel/signal.c:do_sigtimedwait
  - kernel/signal.c:get_signal
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:ptrace_stop
```
```
In kernel/umh.c (ffffffff810a274e)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - kernel/umh.c:usermodehelper_read_trylock
```
```
In kernel/kthread.c (ffffffff810acdb6)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_worker_fn
  - kernel/kthread.c:kthread_worker_fn
  - kernel/kthread.c:kthread_freezable_should_stop
```
```
In kernel/power/process.c (ffffffff810e02d8)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - kernel/power/process.c:try_to_freeze_tasks
```
```
In kernel/freezer.c (ffffffff811044d5)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - kernel/freezer.c:set_freezable
  - kernel/freezer.c:freeze_task
  - kernel/freezer.c:__refrigerator
```
```
In kernel/time/hrtimer.c (ffffffff8199468d)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:do_nanosleep
```
```
In kernel/time/alarmtimer.c (ffffffff811120a4)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarmtimer_do_nsleep
```
```
In kernel/futex.c (ffffffff8111b0cc)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - kernel/futex.c:futex_wait_queue_me
```
```
In kernel/cgroup/freezer.c (ffffffff81137d42)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:update_if_frozen
```
```
In kernel/audit.c (ffffffff81141117)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - kernel/audit.c:kauditd_thread
```
```
In mm/oom_kill.c (ffffffff811d15c6)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_reaper
```
```
In mm/vmscan.c (ffffffff811eae5e)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd
```
```
In mm/compaction.c (ffffffff81201fa6)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd
```
```
In mm/ksm.c (ffffffff8123d6fe)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
```
```
In mm/khugepaged.c (ffffffff8125818f)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
```
```
In fs/coredump.c (ffffffff812e0417)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/ext4/super.c (ffffffff813502e8)
Location: include/linux/freezer.h:35
Inline: True
```
```
In fs/jbd2/journal.c (ffffffff8136ca5a)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - fs/jbd2/journal.c:kjournald2
  - fs/jbd2/journal.c:kjournald2
```
```
In fs/ecryptfs/kthread.c (ffffffff8138e52e)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff815f43ef)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:khvcd
```
```
In drivers/char/virtio_console.c (ffffffff81611699)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:wait_port_writable
  - drivers/char/virtio_console.c:port_fops_read
```
```
In drivers/char/tpm/tpm-interface.c (ffffffff8161d659)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-interface.c:wait_for_tpm_stat
```
```
In drivers/char/tpm/tpm_tis_core.c (ffffffff81623d35)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis_core.c:request_locality
```
```
In net/unix/af_unix.c (ffffffff81903fbf)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
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
In kernel/fork.c (ffffffff8108daa8)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - kernel/fork.c:_do_fork
```
```
In kernel/exit.c (ffffffff8109355a)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/signal.c (ffffffff810a0828)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:ptrace_stop
```
```
In kernel/umh.c (ffffffff810a8fdd)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - kernel/umh.c:usermodehelper_read_trylock
```
```
In kernel/kthread.c (ffffffff810b3aba)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_worker_fn
  - kernel/kthread.c:kthread_worker_fn
  - kernel/kthread.c:kthread_freezable_should_stop
```
```
In kernel/power/process.c (ffffffff810e8c37)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - kernel/power/process.c:try_to_freeze_tasks
```
```
In kernel/freezer.c (ffffffff8110f2d5)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - kernel/freezer.c:set_freezable
  - kernel/freezer.c:freeze_task
  - kernel/freezer.c:__refrigerator
```
```
In kernel/time/hrtimer.c (ffffffff819f0c1a)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:do_nanosleep
```
```
In kernel/time/alarmtimer.c (ffffffff8111d935)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarmtimer_do_nsleep
```
```
In kernel/futex.c (ffffffff81128216)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - kernel/futex.c:futex_wait_queue_me
```
```
In kernel/cgroup/freezer.c (ffffffff81146652)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:update_if_frozen
```
```
In kernel/audit.c (ffffffff8114faaf)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - kernel/audit.c:kauditd_thread
```
```
In mm/oom_kill.c (ffffffff811f3007)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_reaper
```
```
In mm/vmscan.c (ffffffff8120c75d)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:balance_pgdat
```
```
In mm/compaction.c (ffffffff81223385)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd
```
```
In mm/ksm.c (ffffffff8126149f)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
```
```
In mm/khugepaged.c (ffffffff8127d978)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
```
```
In fs/coredump.c (ffffffff8130c642)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/ext4/super.c (ffffffff8137e4c1)
Location: include/linux/freezer.h:35
Inline: True
```
```
In fs/jbd2/journal.c (ffffffff8139b15b)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - fs/jbd2/journal.c:kjournald2
  - fs/jbd2/journal.c:kjournald2
```
```
In fs/ecryptfs/kthread.c (ffffffff813bd5ed)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff8162d6ab)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:khvcd
```
```
In drivers/char/virtio_console.c (ffffffff8164b28f)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:wait_port_writable
  - drivers/char/virtio_console.c:port_fops_read
```
```
In drivers/char/tpm/tpm_tis_core.c (ffffffff8165de4c)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis_core.c:request_locality
  - drivers/char/tpm/tpm_tis_core.c:release_locality
  - drivers/char/tpm/tpm_tis_core.c:wait_for_tpm_stat
```
```
In net/unix/af_unix.c (ffffffff8195c0ee)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
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
In kernel/fork.c (ffffffff81095d38)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - kernel/fork.c:_do_fork
```
```
In kernel/exit.c (ffffffff8109b819)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/signal.c (ffffffff810a8b36)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:ptrace_stop
```
```
In kernel/umh.c (ffffffff810b1e9d)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - kernel/umh.c:usermodehelper_read_trylock
```
```
In kernel/kthread.c (ffffffff810bc7ca)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_worker_fn
  - kernel/kthread.c:kthread_worker_fn
  - kernel/kthread.c:kthread_freezable_should_stop
```
```
In kernel/power/process.c (ffffffff810f4225)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - kernel/power/process.c:try_to_freeze_tasks
```
```
In kernel/freezer.c (ffffffff8111a915)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - kernel/freezer.c:set_freezable
  - kernel/freezer.c:freeze_task
  - kernel/freezer.c:__refrigerator
```
```
In kernel/time/hrtimer.c (ffffffff81a2bf9a)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:do_nanosleep
```
```
In kernel/time/alarmtimer.c (ffffffff81129235)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarmtimer_do_nsleep
```
```
In kernel/futex.c (ffffffff81133af6)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - kernel/futex.c:futex_wait_queue_me
```
```
In kernel/cgroup/freezer.c (ffffffff811521f2)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:update_if_frozen
```
```
In kernel/audit.c (ffffffff8115c78f)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - kernel/audit.c:kauditd_thread
```
```
In mm/oom_kill.c (ffffffff81205095)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_reaper
```
```
In mm/vmscan.c (ffffffff8121f5ed)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:balance_pgdat
```
```
In mm/compaction.c (ffffffff812363ea)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd
```
```
In mm/ksm.c (ffffffff81275c7d)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
```
```
In mm/khugepaged.c (ffffffff81291443)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
```
```
In fs/coredump.c (ffffffff81321ea2)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/ext4/super.c (ffffffff81396d71)
Location: include/linux/freezer.h:35
Inline: True
```
```
In fs/jbd2/journal.c (ffffffff813b3ecb)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - fs/jbd2/journal.c:kjournald2
  - fs/jbd2/journal.c:kjournald2
```
```
In fs/ecryptfs/kthread.c (ffffffff813d6c2d)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff8164baab)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:khvcd
```
```
In drivers/char/virtio_console.c (ffffffff816693ff)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:wait_port_writable
  - drivers/char/virtio_console.c:port_fops_read
```
```
In drivers/char/tpm/tpm_tis_core.c (ffffffff8167c30c)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis_core.c:request_locality
  - drivers/char/tpm/tpm_tis_core.c:release_locality
  - drivers/char/tpm/tpm_tis_core.c:wait_for_tpm_stat
```
```
In net/unix/af_unix.c (ffffffff819908fd)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
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
In kernel/fork.c (ffffffff81099fd8)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - kernel/fork.c:_do_fork
```
```
In kernel/exit.c (ffffffff8109fe91)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/signal.c (ffffffff810af00f)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:get_signal
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:ptrace_stop
```
```
In kernel/umh.c (ffffffff810b7a39)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - kernel/umh.c:usermodehelper_read_trylock
```
```
In kernel/kthread.c (ffffffff810c26e0)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_worker_fn
  - kernel/kthread.c:kthread_worker_fn
  - kernel/kthread.c:kthread_freezable_should_stop
```
```
In kernel/power/process.c (ffffffff810fc6ca)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - kernel/power/process.c:try_to_freeze_tasks
```
```
In kernel/freezer.c (ffffffff81125018)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - kernel/freezer.c:set_freezable
  - kernel/freezer.c:freeze_task
  - kernel/freezer.c:__refrigerator
```
```
In kernel/time/hrtimer.c (ffffffff81a9c154)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:do_nanosleep
```
```
In kernel/time/alarmtimer.c (ffffffff81133c89)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarmtimer_do_nsleep
```
```
In kernel/futex.c (ffffffff8113ea5a)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - kernel/futex.c:futex_wait_queue_me
```
```
In kernel/cgroup/legacy_freezer.c (ffffffff8115e885)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:update_if_frozen
```
```
In kernel/audit.c (ffffffff81168e61)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - kernel/audit.c:kauditd_thread
```
```
In mm/oom_kill.c (ffffffff8121cb6b)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_reaper
```
```
In mm/vmscan.c (ffffffff8122edca)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:balance_pgdat
```
```
In mm/compaction.c (ffffffff812478d8)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd
```
```
In mm/ksm.c (ffffffff812922c6)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
```
```
In mm/khugepaged.c (ffffffff812ac589)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
```
```
In fs/coredump.c (ffffffff81349cf1)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/ext4/super.c (ffffffff813c0deb)
Location: include/linux/freezer.h:35
Inline: True
```
```
In fs/jbd2/journal.c (ffffffff813de46c)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - fs/jbd2/journal.c:kjournald2
  - fs/jbd2/journal.c:kjournald2
```
```
In fs/ecryptfs/kthread.c (ffffffff81401605)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff816802f9)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:khvcd
```
```
In drivers/char/virtio_console.c (ffffffff8169edb5)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:wait_port_writable
  - drivers/char/virtio_console.c:port_fops_read
```
```
In drivers/char/tpm/tpm_tis_core.c (ffffffff816b3253)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis_core.c:request_locality
  - drivers/char/tpm/tpm_tis_core.c:release_locality
  - drivers/char/tpm/tpm_tis_core.c:wait_for_tpm_stat
```
```
In net/unix/af_unix.c (ffffffff819fbfdc)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
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
In kernel/fork.c (ffffffff810a05b8)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - kernel/fork.c:_do_fork
```
```
In kernel/exit.c (ffffffff810a650f)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/signal.c (ffffffff810b5626)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:get_signal
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:ptrace_stop
```
```
In kernel/umh.c (ffffffff810bdf39)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - kernel/umh.c:usermodehelper_read_trylock
```
```
In kernel/kthread.c (ffffffff810c908e)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_worker_fn
  - kernel/kthread.c:kthread_worker_fn
  - kernel/kthread.c:kthread_freezable_should_stop
```
```
In kernel/power/process.c (ffffffff81108aea)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - kernel/power/process.c:try_to_freeze_tasks
```
```
In kernel/freezer.c (ffffffff81130fd8)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - kernel/freezer.c:set_freezable
  - kernel/freezer.c:freeze_task
  - kernel/freezer.c:__refrigerator
```
```
In kernel/time/hrtimer.c (ffffffff81ad3aab)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:do_nanosleep
```
```
In kernel/time/alarmtimer.c (ffffffff8113fc59)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarmtimer_do_nsleep
```
```
In kernel/futex.c (ffffffff8114a9cf)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - kernel/futex.c:futex_wait_queue_me
```
```
In kernel/cgroup/legacy_freezer.c (ffffffff8116a4db)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:update_if_frozen
```
```
In kernel/audit.c (ffffffff81174d01)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - kernel/audit.c:kauditd_thread
```
```
In mm/oom_kill.c (ffffffff8122a54b)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_reaper
```
```
In mm/vmscan.c (ffffffff8123cf5a)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:balance_pgdat
```
```
In mm/compaction.c (ffffffff81255d38)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd
```
```
In mm/ksm.c (ffffffff812a2046)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
```
```
In mm/khugepaged.c (ffffffff812be865)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
```
```
In fs/coredump.c (ffffffff81361f91)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/ext4/super.c (ffffffff813da13b)
Location: include/linux/freezer.h:35
Inline: True
```
```
In fs/jbd2/journal.c (ffffffff813f84bc)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - fs/jbd2/journal.c:kjournald2
  - fs/jbd2/journal.c:kjournald2
```
```
In fs/ecryptfs/kthread.c (ffffffff8141b4f5)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff816a29a9)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:khvcd
```
```
In drivers/char/virtio_console.c (ffffffff816c1b45)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:wait_port_writable
  - drivers/char/virtio_console.c:port_fops_read
```
```
In drivers/char/tpm/tpm_tis_core.c (ffffffff816d5f33)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis_core.c:request_locality
  - drivers/char/tpm/tpm_tis_core.c:release_locality
  - drivers/char/tpm/tpm_tis_core.c:wait_for_tpm_stat
```
```
In net/unix/af_unix.c (ffffffff81a32c6c)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
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
In kernel/fork.c (ffffffff810a5200)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - kernel/fork.c:wait_for_vfork_done
```
```
In kernel/exit.c (ffffffff810adf77)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - kernel/exit.c:exit_mm
```
```
In kernel/signal.c (ffffffff810b9243)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - kernel/signal.c:do_sigtimedwait
  - kernel/signal.c:get_signal
  - kernel/signal.c:get_signal
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:ptrace_stop
```
```
In kernel/umh.c (ffffffff810c53a8)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - kernel/umh.c:usermodehelper_read_trylock
```
```
In kernel/kthread.c (ffffffff810d14b0)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_worker_fn
  - kernel/kthread.c:kthread_worker_fn
  - kernel/kthread.c:kthread_freezable_should_stop
```
```
In kernel/power/process.c (ffffffff811136ec)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - kernel/power/process.c:try_to_freeze_tasks
```
```
In kernel/freezer.c (ffffffff81140398)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - kernel/freezer.c:set_freezable
  - kernel/freezer.c:freeze_task
  - kernel/freezer.c:__refrigerator
```
```
In kernel/time/hrtimer.c (ffffffff81bcba15)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:do_nanosleep
```
```
In kernel/time/alarmtimer.c (ffffffff8114eb48)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarmtimer_do_nsleep
```
```
In kernel/futex.c (ffffffff8115b5ef)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - kernel/futex.c:futex_wait_queue_me
```
```
In kernel/cgroup/legacy_freezer.c (ffffffff8117bffd)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:update_if_frozen
```
```
In kernel/audit.c (ffffffff81186d98)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - kernel/audit.c:kauditd_thread
```
```
In mm/oom_kill.c (ffffffff812574d9)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_reaper
```
```
In mm/vmscan.c (ffffffff81269d89)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd_try_to_sleep
  - mm/vmscan.c:balance_pgdat
```
```
In mm/compaction.c (ffffffff81284428)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd
```
```
In mm/ksm.c (ffffffff812d68ff)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
```
```
In mm/khugepaged.c (ffffffff812f0073)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_wait_work
  - mm/khugepaged.c:khugepaged_wait_work
  - mm/khugepaged.c:khugepaged_do_scan
  - mm/khugepaged.c:khugepaged_do_scan
```
```
In fs/coredump.c (ffffffff813a7e44)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - fs/coredump.c:coredump_wait
```
```
In fs/ext4/super.c (ffffffff81427048)
Location: include/linux/freezer.h:35
Inline: True
```
```
In fs/jbd2/journal.c (ffffffff81445cff)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - fs/jbd2/journal.c:kjournald2
  - fs/jbd2/journal.c:kjournald2
```
```
In fs/ecryptfs/kthread.c (ffffffff81469fea)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff81754e3f)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:khvcd
```
```
In drivers/char/virtio_console.c (ffffffff8177726a)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:wait_port_writable
  - drivers/char/virtio_console.c:port_fops_read
```
```
In drivers/char/tpm/tpm_tis_core.c (ffffffff8178a473)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis_core.c:request_locality
  - drivers/char/tpm/tpm_tis_core.c:release_locality
  - drivers/char/tpm/tpm_tis_core.c:wait_for_tpm_stat
```
```
In net/unix/af_unix.c (ffffffff81b2485e)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_data_wait
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
In arch/x86/kernel/cpu/sgx/main.c (ffffffff81068f23)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:ksgxd
  - arch/x86/kernel/cpu/sgx/main.c:ksgxd
```
```
In kernel/fork.c (ffffffff810a0920)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - kernel/fork.c:wait_for_vfork_done
```
```
In kernel/exit.c (ffffffff810a9608)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - kernel/exit.c:exit_mm
```
```
In kernel/signal.c (ffffffff810b44f3)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - kernel/signal.c:do_sigtimedwait
  - kernel/signal.c:get_signal
  - kernel/signal.c:get_signal
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:ptrace_stop
```
```
In kernel/umh.c (ffffffff810c0788)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - kernel/umh.c:usermodehelper_read_trylock
```
```
In kernel/kthread.c (ffffffff810cbe72)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_worker_fn
  - kernel/kthread.c:kthread_worker_fn
  - kernel/kthread.c:kthread_freezable_should_stop
```
```
In kernel/power/process.c (ffffffff81bdea1f)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - kernel/power/process.c:try_to_freeze_tasks
```
```
In kernel/freezer.c (ffffffff8113c708)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - kernel/freezer.c:set_freezable
  - kernel/freezer.c:freeze_task
  - kernel/freezer.c:__refrigerator
```
```
In kernel/time/hrtimer.c (ffffffff81c44895)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:do_nanosleep
```
```
In kernel/time/alarmtimer.c (ffffffff8114adc3)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarmtimer_do_nsleep
```
```
In kernel/futex.c (ffffffff8115771f)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - kernel/futex.c:futex_wait_queue_me
```
```
In kernel/cgroup/legacy_freezer.c (ffffffff81178e37)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:update_if_frozen
```
```
In kernel/audit.c (ffffffff811840cc)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - kernel/audit.c:kauditd_thread
```
```
In mm/oom_kill.c (ffffffff812620b9)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_reaper
```
```
In mm/vmscan.c (ffffffff812748ba)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd_try_to_sleep
  - mm/vmscan.c:balance_pgdat
```
```
In mm/compaction.c (ffffffff8128e5cf)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd
```
```
In mm/ksm.c (ffffffff812e243c)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
```
```
In mm/khugepaged.c (ffffffff812fb833)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_wait_work
  - mm/khugepaged.c:khugepaged_wait_work
  - mm/khugepaged.c:khugepaged_do_scan
  - mm/khugepaged.c:khugepaged_do_scan
```
```
In fs/coredump.c (ffffffff813b8d0b)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - fs/coredump.c:coredump_wait
```
```
In fs/ext4/super.c (ffffffff8143ee4b)
Location: include/linux/freezer.h:35
Inline: True
```
```
In fs/jbd2/journal.c (ffffffff814620df)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - fs/jbd2/journal.c:kjournald2
  - fs/jbd2/journal.c:kjournald2
```
```
In fs/ecryptfs/kthread.c (ffffffff81484a5a)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff8177013f)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:khvcd
```
```
In drivers/char/virtio_console.c (ffffffff81791f9a)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:wait_port_writable
  - drivers/char/virtio_console.c:port_fops_read
```
```
In drivers/char/tpm/tpm_tis_core.c (ffffffff817a13f3)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis_core.c:request_locality
  - drivers/char/tpm/tpm_tis_core.c:wait_for_tpm_stat
```
```
In net/unix/af_unix.c (ffffffff81b332ce)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_data_wait
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
In arch/x86/kernel/cpu/sgx/main.c (ffffffff81069043)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:ksgxd
  - arch/x86/kernel/cpu/sgx/main.c:ksgxd
```
```
In kernel/fork.c (ffffffff810a3cf6)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - kernel/fork.c:kernel_clone
```
```
In kernel/exit.c (ffffffff810aa648)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - kernel/exit.c:exit_mm
```
```
In kernel/signal.c (ffffffff810b6104)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - kernel/signal.c:do_sigtimedwait
  - kernel/signal.c:get_signal
  - kernel/signal.c:get_signal
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:ptrace_stop
```
```
In kernel/umh.c (ffffffff810c2188)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - kernel/umh.c:usermodehelper_read_trylock
```
```
In kernel/kthread.c (ffffffff810cd7c2)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_worker_fn
  - kernel/kthread.c:kthread_worker_fn
  - kernel/kthread.c:kthread_freezable_should_stop
```
```
In kernel/power/process.c (ffffffff81bd0b98)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - kernel/power/process.c:try_to_freeze_tasks
```
```
In kernel/freezer.c (ffffffff8113d958)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - kernel/freezer.c:set_freezable
  - kernel/freezer.c:freeze_task
  - kernel/freezer.c:__refrigerator
```
```
In kernel/time/hrtimer.c (ffffffff81c37b05)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:do_nanosleep
```
```
In kernel/time/alarmtimer.c (ffffffff8114c280)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarmtimer_do_nsleep
```
```
In kernel/futex.c (ffffffff81158b6e)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - kernel/futex.c:futex_wait_queue_me
```
```
In kernel/cgroup/legacy_freezer.c (ffffffff811799a7)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:update_if_frozen
```
```
In kernel/audit.c (ffffffff81184ff8)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - kernel/audit.c:kauditd_thread
```
```
In mm/oom_kill.c (ffffffff81266a01)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_reaper
```
```
In mm/vmscan.c (ffffffff81279bca)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd_try_to_sleep
  - mm/vmscan.c:balance_pgdat
```
```
In mm/compaction.c (ffffffff81293c5f)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd
```
```
In mm/ksm.c (ffffffff812e9bca)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
```
```
In mm/khugepaged.c (ffffffff81306437)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged_wait_work
  - mm/khugepaged.c:khugepaged_wait_work
```
```
In fs/coredump.c (ffffffff813bf087)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - fs/coredump.c:dump_interrupted
  - fs/coredump.c:coredump_wait
```
```
In fs/ext4/super.c (ffffffff81444c8b)
Location: include/linux/freezer.h:35
Inline: True
```
```
In fs/jbd2/journal.c (ffffffff8146778f)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - fs/jbd2/journal.c:kjournald2
  - fs/jbd2/journal.c:kjournald2
```
```
In fs/ecryptfs/kthread.c (ffffffff8148a50a)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff81753bef)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:khvcd
```
```
In drivers/char/virtio_console.c (ffffffff81774a1a)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:wait_port_writable
  - drivers/char/virtio_console.c:port_fops_read
```
```
In drivers/char/tpm/tpm_tis_core.c (ffffffff81783f83)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis_core.c:request_locality
  - drivers/char/tpm/tpm_tis_core.c:wait_for_tpm_stat
```
```
In net/unix/af_unix.c (ffffffff81b21006)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_data_wait
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
In arch/x86/kernel/cpu/sgx/main.c (ffffffff810739f5)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:ksgxd
  - arch/x86/kernel/cpu/sgx/main.c:ksgxd
```
```
In kernel/fork.c (ffffffff810b5513)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - kernel/fork.c:kernel_clone
```
```
In kernel/exit.c (ffffffff810bc184)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - kernel/exit.c:exit_mm
```
```
In kernel/signal.c (ffffffff810c8f94)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - kernel/signal.c:do_sigtimedwait
  - kernel/signal.c:get_signal
  - kernel/signal.c:get_signal
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:ptrace_stop
```
```
In kernel/umh.c (ffffffff810d4cc8)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - kernel/umh.c:usermodehelper_read_trylock
```
```
In kernel/kthread.c (ffffffff810e09ad)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_worker_fn
  - kernel/kthread.c:kthread_worker_fn
  - kernel/kthread.c:kthread_freezable_should_stop
```
```
In kernel/power/process.c (ffffffff81ca98bd)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - kernel/power/process.c:try_to_freeze_tasks
```
```
In kernel/freezer.c (ffffffff81160ad8)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - kernel/freezer.c:set_freezable
  - kernel/freezer.c:freeze_task
  - kernel/freezer.c:__refrigerator
```
```
In kernel/time/hrtimer.c (ffffffff81d5637a)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:do_nanosleep
```
```
In kernel/time/alarmtimer.c (ffffffff81170046)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarmtimer_do_nsleep
```
```
In kernel/futex.c (ffffffff8117da4b)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - kernel/futex.c:futex_wait_queue_me
```
```
In kernel/cgroup/legacy_freezer.c (ffffffff811a12c7)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:update_if_frozen
```
```
In kernel/audit.c (ffffffff811ad3e8)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - kernel/audit.c:kauditd_thread
```
```
In mm/oom_kill.c (ffffffff812a2fd1)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_reaper
```
```
In mm/vmscan.c (ffffffff812b7b77)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd_try_to_sleep
  - mm/vmscan.c:balance_pgdat
```
```
In mm/compaction.c (ffffffff812d42bb)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd
```
```
In mm/ksm.c (ffffffff81331afa)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
```
```
In mm/khugepaged.c (ffffffff813503a0)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged_wait_work
  - mm/khugepaged.c:khugepaged_wait_work
```
```
In fs/coredump.c (ffffffff8140eeb7)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - fs/coredump.c:dump_interrupted
  - fs/coredump.c:coredump_wait
```
```
In fs/ext4/super.c (ffffffff81498b1b)
Location: include/linux/freezer.h:35
Inline: True
```
```
In fs/jbd2/journal.c (ffffffff814bd72f)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - fs/jbd2/journal.c:kjournald2
  - fs/jbd2/journal.c:kjournald2
```
```
In fs/ecryptfs/kthread.c (ffffffff814e1d0a)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
```
```
In drivers/xen/balloon.c (ffffffff81791e5a)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - drivers/xen/balloon.c:balloon_thread
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff817d713b)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:khvcd
```
```
In drivers/char/virtio_console.c (ffffffff817f9d47)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:wait_port_writable
  - drivers/char/virtio_console.c:port_fops_read
```
```
In drivers/char/tpm/tpm_tis_core.c (ffffffff8180a9bc)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis_core.c:request_locality
  - drivers/char/tpm/tpm_tis_core.c:wait_for_tpm_stat
```
```
In net/unix/af_unix.c (ffffffff81be60c6)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_data_wait
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
In arch/x86/kernel/cpu/sgx/main.c (ffffffff81081ee7)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:ksgxd
  - arch/x86/kernel/cpu/sgx/main.c:ksgxd
```
```
In kernel/fork.c (ffffffff810cb886)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - kernel/fork.c:kernel_clone
```
```
In kernel/exit.c (ffffffff810d2de4)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/signal.c (ffffffff810e050f)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - kernel/signal.c:do_sigtimedwait
  - kernel/signal.c:get_signal
  - kernel/signal.c:get_signal
  - kernel/signal.c:do_signal_stop
```
```
In kernel/umh.c (ffffffff810edc67)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - kernel/umh.c:usermodehelper_read_trylock
```
```
In kernel/kthread.c (ffffffff810fab3b)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_worker_fn
  - kernel/kthread.c:kthread_worker_fn
  - kernel/kthread.c:kthread_freezable_should_stop
```
```
In kernel/power/process.c (ffffffff81e598a8)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - kernel/power/process.c:try_to_freeze_tasks
```
```
In kernel/freezer.c (ffffffff8119384c)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - kernel/freezer.c:set_freezable
  - kernel/freezer.c:freeze_task
  - kernel/freezer.c:__refrigerator
```
```
In kernel/time/hrtimer.c (ffffffff81f28588)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:do_nanosleep
```
```
In kernel/time/alarmtimer.c (ffffffff811a4586)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarmtimer_do_nsleep
```
```
In kernel/futex/waitwake.c (ffffffff811b7438)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - kernel/futex/waitwake.c:futex_wait_multiple
  - kernel/futex/waitwake.c:futex_wait_queue
```
```
In kernel/cgroup/legacy_freezer.c (ffffffff811d1bc0)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:update_if_frozen
```
```
In kernel/audit.c (ffffffff811df0e3)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - kernel/audit.c:kauditd_thread
```
```
In mm/oom_kill.c (ffffffff812fae31)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_reaper
```
```
In mm/vmscan.c (ffffffff81312959)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd_try_to_sleep
  - mm/vmscan.c:balance_pgdat
```
```
In mm/compaction.c (ffffffff81333223)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd
```
```
In mm/ksm.c (ffffffff813a2b64)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
```
```
In mm/khugepaged.c (ffffffff813c849b)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged_wait_work
  - mm/khugepaged.c:khugepaged_wait_work
```
```
In fs/coredump.c (ffffffff814845e7)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - fs/coredump.c:dump_interrupted
  - fs/coredump.c:coredump_wait
```
```
In fs/ext4/super.c (ffffffff815239d8)
Location: include/linux/freezer.h:35
Inline: True
```
```
In fs/jbd2/journal.c (ffffffff81548ddc)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - fs/jbd2/journal.c:kjournald2
  - fs/jbd2/journal.c:kjournald2
```
```
In fs/ecryptfs/kthread.c (ffffffff8156ff1b)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
```
```
In drivers/xen/balloon.c (ffffffff818caa92)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - drivers/xen/balloon.c:balloon_thread
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff8191528b)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:khvcd
```
```
In drivers/char/virtio_console.c (ffffffff81938839)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:wait_port_writable
  - drivers/char/virtio_console.c:port_fops_read
```
```
In drivers/char/tpm/tpm_tis_core.c (ffffffff8194a49a)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis_core.c:request_locality
  - drivers/char/tpm/tpm_tis_core.c:wait_for_tpm_stat
```
```
In net/unix/af_unix.c (ffffffff81d7d2bd)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_data_wait
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
In arch/x86/kernel/cpu/sgx/main.c (ffffffff810947be)
Location: include/linux/freezer.h:34
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:ksgxd
```
```
In kernel/signal.c (ffffffff811054eb)
Location: include/linux/freezer.h:34
Inline: True
Inline callers:
  - kernel/signal.c:get_signal
```
```
In kernel/umh.c (ffffffff8110f12c)
Location: include/linux/freezer.h:34
Inline: True
Inline callers:
  - kernel/umh.c:usermodehelper_read_trylock
```
```
In kernel/kthread.c (ffffffff8111d9ab)
Location: include/linux/freezer.h:34
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_worker_fn
  - kernel/kthread.c:kthread_worker_fn
  - kernel/kthread.c:kthread_freezable_should_stop
```
```
In kernel/power/process.c (ffffffff8118104f)
Location: include/linux/freezer.h:34
Inline: True
Inline callers:
  - kernel/power/process.c:try_to_freeze_tasks
```
```
In kernel/freezer.c (ffffffff811d11ec)
Location: include/linux/freezer.h:34
Inline: True
Inline callers:
  - kernel/freezer.c:set_freezable
  - kernel/freezer.c:__thaw_task
  - kernel/freezer.c:freeze_task
  - kernel/freezer.c:__refrigerator
```
```
In kernel/time/alarmtimer.c (ffffffff811e3ea4)
Location: include/linux/freezer.h:34
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarmtimer_do_nsleep
```
```
In kernel/cgroup/legacy_freezer.c (ffffffff81215890)
Location: include/linux/freezer.h:34
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:update_if_frozen
```
```
In mm/vmscan.c (ffffffff81385d9c)
Location: include/linux/freezer.h:34
Inline: True
Inline callers:
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd_try_to_sleep
  - mm/vmscan.c:balance_pgdat
```
```
In mm/ksm.c (ffffffff81422544)
Location: include/linux/freezer.h:34
Inline: True
Inline callers:
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
```
```
In mm/khugepaged.c (ffffffff8144c65b)
Location: include/linux/freezer.h:34
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
```
```
In fs/coredump.c (ffffffff81517ac3)
Location: include/linux/freezer.h:34
Inline: True
Inline callers:
  - fs/coredump.c:dump_interrupted
```
```
In fs/ext4/super.c (ffffffff815c0bd9)
Location: include/linux/freezer.h:34
Inline: True
```
```
In fs/jbd2/journal.c (ffffffff815e898e)
Location: include/linux/freezer.h:34
Inline: True
Inline callers:
  - fs/jbd2/journal.c:kjournald2
  - fs/jbd2/journal.c:kjournald2
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff81a7052b)
Location: include/linux/freezer.h:34
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:khvcd
```
```
In drivers/char/tpm/tpm_tis_core.c (ffffffff81aadb27)
Location: include/linux/freezer.h:34
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis_core.c:request_locality
  - drivers/char/tpm/tpm_tis_core.c:wait_for_tpm_stat
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
In arch/x86/kernel/cpu/sgx/main.c (ffffffff8109775e)
Location: include/linux/freezer.h:34
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:ksgxd
```
```
In kernel/signal.c (ffffffff81111778)
Location: include/linux/freezer.h:34
Inline: True
Inline callers:
  - kernel/signal.c:get_signal
```
```
In kernel/umh.c (ffffffff8111b5cc)
Location: include/linux/freezer.h:34
Inline: True
Inline callers:
  - kernel/umh.c:usermodehelper_read_trylock
```
```
In kernel/kthread.c (ffffffff8112ab9b)
Location: include/linux/freezer.h:34
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_worker_fn
  - kernel/kthread.c:kthread_worker_fn
  - kernel/kthread.c:kthread_freezable_should_stop
```
```
In kernel/power/process.c (ffffffff81191f44)
Location: include/linux/freezer.h:34
Inline: True
Inline callers:
  - kernel/power/process.c:try_to_freeze_tasks
```
```
In kernel/freezer.c (ffffffff811e545c)
Location: include/linux/freezer.h:34
Inline: True
Inline callers:
  - kernel/freezer.c:set_freezable
  - kernel/freezer.c:__thaw_task
  - kernel/freezer.c:freeze_task
  - kernel/freezer.c:__refrigerator
```
```
In kernel/time/alarmtimer.c (ffffffff811f8514)
Location: include/linux/freezer.h:34
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarmtimer_do_nsleep
```
```
In kernel/cgroup/legacy_freezer.c (ffffffff8122b1c0)
Location: include/linux/freezer.h:34
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:update_if_frozen
```
```
In mm/vmscan.c (ffffffff813b9060)
Location: include/linux/freezer.h:34
Inline: True
Inline callers:
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd_try_to_sleep
  - mm/vmscan.c:balance_pgdat
```
```
In mm/ksm.c (ffffffff814572b4)
Location: include/linux/freezer.h:34
Inline: True
Inline callers:
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
```
```
In mm/khugepaged.c (ffffffff81481f0b)
Location: include/linux/freezer.h:34
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
```
```
In fs/coredump.c (ffffffff8154f3b3)
Location: include/linux/freezer.h:34
Inline: True
Inline callers:
  - fs/coredump.c:dump_interrupted
```
```
In fs/ext4/super.c (ffffffff815f8359)
Location: include/linux/freezer.h:34
Inline: True
```
```
In fs/jbd2/journal.c (ffffffff8162023e)
Location: include/linux/freezer.h:34
Inline: True
Inline callers:
  - fs/jbd2/journal.c:kjournald2
  - fs/jbd2/journal.c:kjournald2
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff81abaceb)
Location: include/linux/freezer.h:34
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:khvcd
```
```
In drivers/char/tpm/tpm_tis_core.c (ffffffff81af93cd)
Location: include/linux/freezer.h:34
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis_core.c:__tpm_tis_request_locality
  - drivers/char/tpm/tpm_tis_core.c:wait_for_tpm_stat
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
In arch/x86/kernel/cpu/sgx/main.c (ffffffff8109ecce)
Location: include/linux/freezer.h:34
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:ksgxd
```
```
In kernel/signal.c (ffffffff8111b118)
Location: include/linux/freezer.h:34
Inline: True
Inline callers:
  - kernel/signal.c:get_signal
```
```
In kernel/umh.c (ffffffff811250bc)
Location: include/linux/freezer.h:34
Inline: True
Inline callers:
  - kernel/umh.c:usermodehelper_read_trylock
```
```
In kernel/kthread.c (ffffffff811352bb)
Location: include/linux/freezer.h:34
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_worker_fn
  - kernel/kthread.c:kthread_worker_fn
  - kernel/kthread.c:kthread_freezable_should_stop
```
```
In kernel/power/process.c (ffffffff811a0934)
Location: include/linux/freezer.h:34
Inline: True
Inline callers:
  - kernel/power/process.c:try_to_freeze_tasks
```
```
In kernel/freezer.c (ffffffff811fb20c)
Location: include/linux/freezer.h:34
Inline: True
Inline callers:
  - kernel/freezer.c:set_freezable
  - kernel/freezer.c:__thaw_task
  - kernel/freezer.c:freeze_task
  - kernel/freezer.c:__refrigerator
```
```
In kernel/time/alarmtimer.c (ffffffff8120e6b4)
Location: include/linux/freezer.h:34
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarmtimer_do_nsleep
```
```
In kernel/cgroup/legacy_freezer.c (ffffffff81243180)
Location: include/linux/freezer.h:34
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:update_if_frozen
```
```
In mm/vmscan.c (ffffffff813e2060)
Location: include/linux/freezer.h:34
Inline: True
Inline callers:
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd_try_to_sleep
  - mm/vmscan.c:balance_pgdat
```
```
In mm/ksm.c (ffffffff81491d9e)
Location: include/linux/freezer.h:34
Inline: True
Inline callers:
  - mm/ksm.c:ksm_scan_thread
```
```
In fs/coredump.c (ffffffff815851f3)
Location: include/linux/freezer.h:34
Inline: True
Inline callers:
  - fs/coredump.c:dump_interrupted
```
```
In fs/ext4/mballoc.c (ffffffff815f9653)
Location: include/linux/freezer.h:34
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_trim_interrupted
```
```
In fs/ext4/super.c (ffffffff81630f09)
Location: include/linux/freezer.h:34
Inline: True
```
```
In fs/jbd2/journal.c (ffffffff8165920e)
Location: include/linux/freezer.h:34
Inline: True
Inline callers:
  - fs/jbd2/journal.c:kjournald2
  - fs/jbd2/journal.c:kjournald2
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff81b0da5b)
Location: include/linux/freezer.h:34
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:khvcd
```
```
In drivers/char/tpm/tpm_tis_core.c (ffffffff81b4c9ed)
Location: include/linux/freezer.h:34
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis_core.c:__tpm_tis_request_locality
  - drivers/char/tpm/tpm_tis_core.c:wait_for_tpm_stat
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
In kernel/fork.c (ffff8000100f4e88)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - kernel/fork.c:_do_fork
```
```
In kernel/exit.c (ffff8000100fd490)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/signal.c (ffff800010111778)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:get_signal
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:ptrace_stop
```
```
In kernel/umh.c (ffff80001011a778)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - kernel/umh.c:usermodehelper_read_trylock
```
```
In kernel/kthread.c (ffff8000101279b4)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_worker_fn
  - kernel/kthread.c:kthread_worker_fn
  - kernel/kthread.c:kthread_freezable_should_stop
```
```
In kernel/power/process.c (ffff80001016fc84)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - kernel/power/process.c:try_to_freeze_tasks
```
```
In kernel/freezer.c (ffff800010198290)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - kernel/freezer.c:set_freezable
  - kernel/freezer.c:freeze_task
  - kernel/freezer.c:__refrigerator
```
```
In kernel/time/hrtimer.c (ffff800010da6638)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:do_nanosleep
```
```
In kernel/time/alarmtimer.c (ffff8000101a9864)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarmtimer_do_nsleep
```
```
In kernel/futex.c (ffff8000101b66f4)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - kernel/futex.c:futex_wait_queue_me
```
```
In kernel/cgroup/legacy_freezer.c (ffff8000101de000)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:update_if_frozen
```
```
In kernel/audit.c (ffff8000101e998c)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - kernel/audit.c:kauditd_thread
```
```
In mm/oom_kill.c (ffff8000102b8538)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_reaper
```
```
In mm/vmscan.c (ffff8000102ce24c)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:balance_pgdat
```
```
In mm/compaction.c (ffff8000102ed2bc)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd
```
```
In mm/ksm.c (ffff800010341898)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
```
```
In mm/khugepaged.c (ffff80001035fd9c)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
```
```
In fs/coredump.c (ffff8000104289a0)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/ext4/super.c (ffff8000104ad7ac)
Location: include/linux/freezer.h:35
Inline: True
```
```
In fs/jbd2/journal.c (ffff8000104d6620)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - fs/jbd2/journal.c:kjournald2
  - fs/jbd2/journal.c:kjournald2
```
```
In fs/ecryptfs/kthread.c (ffff8000104fc930)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
```
```
In drivers/tty/hvc/hvc_console.c (ffff80001087b000)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:khvcd
```
```
In drivers/char/virtio_console.c (ffff8000108b3ebc)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:wait_port_writable
  - drivers/char/virtio_console.c:port_fops_read
```
```
In drivers/char/tpm/tpm_tis_core.c (ffff8000108c0fd8)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis_core.c:request_locality
  - drivers/char/tpm/tpm_tis_core.c:release_locality
  - drivers/char/tpm/tpm_tis_core.c:wait_for_tpm_stat
```
```
In net/unix/af_unix.c (ffff800010cf23f0)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
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
In kernel/fork.c (c03535fc)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - kernel/fork.c:_do_fork
```
```
In kernel/exit.c (c035a5f8)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/signal.c (c03656ac)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - kernel/signal.c:do_sigtimedwait
  - kernel/signal.c:get_signal
  - kernel/signal.c:get_signal
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:ptrace_stop
```
```
In kernel/umh.c (c036ecb8)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - kernel/umh.c:usermodehelper_read_trylock
```
```
In kernel/kthread.c (c0379f54)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_worker_fn
  - kernel/kthread.c:kthread_worker_fn
  - kernel/kthread.c:kthread_freezable_should_stop
```
```
In kernel/power/process.c (c03ba8f0)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - kernel/power/process.c:try_to_freeze_tasks
```
```
In kernel/freezer.c (c03e32c4)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - kernel/freezer.c:set_freezable
  - kernel/freezer.c:freeze_task
  - kernel/freezer.c:__refrigerator
```
```
In kernel/time/hrtimer.c (c0e9e3c8)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:do_nanosleep
```
```
In kernel/time/alarmtimer.c (c03f5248)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarmtimer_do_nsleep
```
```
In kernel/futex.c (c0401244)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - kernel/futex.c:futex_wait_queue_me
```
```
In kernel/cgroup/legacy_freezer.c (c041ff84)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_read
```
```
In kernel/audit.c (c0429838)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - kernel/audit.c:kauditd_thread
```
```
In mm/oom_kill.c (c04e4d0c)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_reaper
```
```
In mm/vmscan.c (c04f80b4)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:balance_pgdat
```
```
In mm/compaction.c (c0511188)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd
```
```
In mm/ksm.c (c054781c)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_do_scan
```
```
In fs/coredump.c (c05f12c8)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/ext4/super.c (c0676520)
Location: include/linux/freezer.h:35
Inline: True
```
```
In fs/jbd2/journal.c (c0696db0)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - fs/jbd2/journal.c:kjournald2
  - fs/jbd2/journal.c:kjournald2
```
```
In fs/ecryptfs/kthread.c (c06b9f98)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
```
```
In drivers/tty/hvc/hvc_console.c (c097cd40)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:khvcd
```
```
In drivers/char/virtio_console.c (c09aef9c)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:wait_port_writable
  - drivers/char/virtio_console.c:port_fops_read
```
```
In drivers/char/tpm/tpm_tis_core.c (c09b963c)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis_core.c:request_locality
  - drivers/char/tpm/tpm_tis_core.c:release_locality
  - drivers/char/tpm/tpm_tis_core.c:wait_for_tpm_stat
```
```
In net/unix/af_unix.c (c0dfa35c)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
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
In arch/powerpc/platforms/powernv/opal.c (c0000000000c5150)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - arch/powerpc/platforms/powernv/opal.c:kopald
```
```
In kernel/fork.c (c00000000013af70)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - kernel/fork.c:_do_fork
```
```
In kernel/exit.c (c00000000014435c)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/signal.c (c000000000159310)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:get_signal
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:ptrace_stop
```
```
In kernel/umh.c (c000000000162078)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - kernel/umh.c:usermodehelper_read_trylock
```
```
In kernel/kthread.c (c000000000172cf8)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_worker_fn
  - kernel/kthread.c:kthread_worker_fn
  - kernel/kthread.c:kthread_freezable_should_stop
```
```
In kernel/power/process.c (c0000000001c7d5c)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - kernel/power/process.c:try_to_freeze_tasks
```
```
In kernel/freezer.c (c0000000001f81dc)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - kernel/freezer.c:set_freezable
  - kernel/freezer.c:freeze_task
  - kernel/freezer.c:__refrigerator
```
```
In kernel/time/hrtimer.c (c000000000ee8df4)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:do_nanosleep
```
```
In kernel/time/alarmtimer.c (c00000000020d558)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarmtimer_do_nsleep
```
```
In kernel/futex.c (c00000000021c0a0)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - kernel/futex.c:futex_wait_queue_me
```
```
In kernel/cgroup/legacy_freezer.c (c00000000024bdb4)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:update_if_frozen
```
```
In kernel/audit.c (c00000000025a8a4)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - kernel/audit.c:kauditd_thread
```
```
In mm/oom_kill.c (c000000000370744)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_reaper
```
```
In mm/vmscan.c (c00000000038bf58)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:balance_pgdat
```
```
In mm/compaction.c (c0000000003b0f14)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd
```
```
In mm/ksm.c (c00000000041ef74)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
```
```
In mm/khugepaged.c (c00000000044b564)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
```
```
In fs/coredump.c (c000000000538850)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/ext4/super.c (c0000000005e6484)
Location: include/linux/freezer.h:35
Inline: True
```
```
In fs/jbd2/journal.c (c00000000060f0e0)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - fs/jbd2/journal.c:kjournald2
  - fs/jbd2/journal.c:kjournald2
```
```
In fs/ecryptfs/kthread.c (c00000000063f8e8)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
```
```
In drivers/tty/hvc/hvc_console.c (c000000000922124)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:khvcd
```
```
In drivers/char/virtio_console.c (c00000000094d72c)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:wait_port_writable
  - drivers/char/virtio_console.c:port_fops_read
```
```
In drivers/char/tpm/tpm_tis_core.c (c000000000962e20)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis_core.c:request_locality
  - drivers/char/tpm/tpm_tis_core.c:release_locality
  - drivers/char/tpm/tpm_tis_core.c:wait_for_tpm_stat
```
```
In net/unix/af_unix.c (c000000000e18874)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
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
In kernel/fork.c (ffffffe0000c1524)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - kernel/fork.c:_do_fork
```
```
In kernel/exit.c (ffffffe0000c5cce)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/signal.c (ffffffe0000d1524)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - kernel/signal.c:__se_sys_rt_sigtimedwait
  - kernel/signal.c:get_signal
  - kernel/signal.c:get_signal
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:ptrace_stop
```
```
In kernel/umh.c (ffffffe0000d4ed8)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - kernel/umh.c:usermodehelper_read_trylock
```
```
In kernel/kthread.c (ffffffe0000df9be)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_worker_fn
  - kernel/kthread.c:kthread_worker_fn
  - kernel/kthread.c:kthread_freezable_should_stop
```
```
In kernel/power/process.c (ffffffe00010dc52)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - kernel/power/process.c:try_to_freeze_tasks
```
```
In kernel/freezer.c (ffffffe000128fec)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - kernel/freezer.c:set_freezable
  - kernel/freezer.c:freeze_task
  - kernel/freezer.c:__refrigerator
```
```
In kernel/time/hrtimer.c (ffffffe0008c8a0a)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:do_nanosleep
```
```
In kernel/time/alarmtimer.c (ffffffe000135480)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarmtimer_do_nsleep
```
```
In kernel/futex.c (ffffffe00013cbd0)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - kernel/futex.c:futex_wait_queue_me
```
```
In kernel/cgroup/legacy_freezer.c (ffffffe0001556d8)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:update_if_frozen
```
```
In kernel/audit.c (ffffffe00015e522)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - kernel/audit.c:kauditd_thread
```
```
In mm/oom_kill.c (ffffffe0001dc2f6)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_reaper
```
```
In mm/vmscan.c (ffffffe0001ec4b0)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:balance_pgdat
```
```
In mm/compaction.c (ffffffe0002018a2)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd
```
```
In mm/ksm.c (ffffffe000235dde)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_do_scan
```
```
In fs/coredump.c (ffffffe0002c6858)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/ext4/super.c (ffffffe000330b36)
Location: include/linux/freezer.h:35
Inline: True
```
```
In fs/jbd2/journal.c (ffffffe00034b144)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - fs/jbd2/journal.c:kjournald2
  - fs/jbd2/journal.c:kjournald2
```
```
In fs/ecryptfs/kthread.c (ffffffe00036aefc)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
```
```
In drivers/tty/hvc/hvc_console.c (ffffffe00054ac26)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:khvcd
```
```
In drivers/char/virtio_console.c (ffffffe000565d40)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:wait_port_writable
  - drivers/char/virtio_console.c:port_fops_read
```
```
In drivers/char/tpm/tpm_tis_core.c (ffffffe0005724dc)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis_core.c:request_locality
  - drivers/char/tpm/tpm_tis_core.c:release_locality
  - drivers/char/tpm/tpm_tis_core.c:wait_for_tpm_stat
```
```
In net/unix/af_unix.c (ffffffe00083f534)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
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
In kernel/fork.c (ffffffff81099ed8)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - kernel/fork.c:_do_fork
```
```
In kernel/exit.c (ffffffff8109fe2f)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/signal.c (ffffffff810af996)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:get_signal
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:ptrace_stop
```
```
In kernel/umh.c (ffffffff810b82a9)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - kernel/umh.c:usermodehelper_read_trylock
```
```
In kernel/kthread.c (ffffffff810c340e)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_worker_fn
  - kernel/kthread.c:kthread_worker_fn
  - kernel/kthread.c:kthread_freezable_should_stop
```
```
In kernel/power/process.c (ffffffff81101c2a)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - kernel/power/process.c:try_to_freeze_tasks
```
```
In kernel/freezer.c (ffffffff81129788)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - kernel/freezer.c:set_freezable
  - kernel/freezer.c:freeze_task
  - kernel/freezer.c:__refrigerator
```
```
In kernel/time/hrtimer.c (ffffffff81a7291b)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:do_nanosleep
```
```
In kernel/time/alarmtimer.c (ffffffff81138409)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarmtimer_do_nsleep
```
```
In kernel/futex.c (ffffffff81142fef)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - kernel/futex.c:futex_wait_queue_me
```
```
In kernel/cgroup/legacy_freezer.c (ffffffff81162afb)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:update_if_frozen
```
```
In kernel/audit.c (ffffffff8116d321)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - kernel/audit.c:kauditd_thread
```
```
In mm/oom_kill.c (ffffffff81222b9b)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_reaper
```
```
In mm/vmscan.c (ffffffff812355aa)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:balance_pgdat
```
```
In mm/compaction.c (ffffffff8124e388)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd
```
```
In mm/ksm.c (ffffffff8129a626)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
```
```
In mm/khugepaged.c (ffffffff812b6e45)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
```
```
In fs/coredump.c (ffffffff8135a571)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/ext4/super.c (ffffffff813d271b)
Location: include/linux/freezer.h:35
Inline: True
```
```
In fs/jbd2/journal.c (ffffffff813f0a9c)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - fs/jbd2/journal.c:kjournald2
  - fs/jbd2/journal.c:kjournald2
```
```
In fs/ecryptfs/kthread.c (ffffffff81413ad5)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff81668409)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:khvcd
```
```
In drivers/char/virtio_console.c (ffffffff81687595)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:wait_port_writable
  - drivers/char/virtio_console.c:port_fops_read
```
```
In drivers/char/tpm/tpm_tis_core.c (ffffffff8169b983)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis_core.c:request_locality
  - drivers/char/tpm/tpm_tis_core.c:release_locality
  - drivers/char/tpm/tpm_tis_core.c:wait_for_tpm_stat
```
```
In net/unix/af_unix.c (ffffffff819d22fc)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
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
In kernel/fork.c (ffffffff81088918)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - kernel/fork.c:_do_fork
```
```
In kernel/exit.c (ffffffff8108e85f)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/signal.c (ffffffff8109e2b6)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:get_signal
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:ptrace_stop
```
```
In kernel/umh.c (ffffffff810a6be9)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - kernel/umh.c:usermodehelper_read_trylock
```
```
In kernel/kthread.c (ffffffff810b1c4e)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_worker_fn
  - kernel/kthread.c:kthread_worker_fn
  - kernel/kthread.c:kthread_freezable_should_stop
```
```
In kernel/power/process.c (ffffffff810f1fea)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - kernel/power/process.c:try_to_freeze_tasks
```
```
In kernel/freezer.c (ffffffff8111c012)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - kernel/freezer.c:set_freezable
  - kernel/freezer.c:freeze_task
  - kernel/freezer.c:__refrigerator
```
```
In kernel/time/hrtimer.c (ffffffff81a2eceb)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:do_nanosleep
```
```
In kernel/time/alarmtimer.c (ffffffff8112ae59)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarmtimer_do_nsleep
```
```
In kernel/futex.c (ffffffff8113634f)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - kernel/futex.c:futex_wait_queue_me
```
```
In kernel/cgroup/legacy_freezer.c (ffffffff81155d4b)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:update_if_frozen
```
```
In kernel/audit.c (ffffffff811604c1)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - kernel/audit.c:kauditd_thread
```
```
In mm/oom_kill.c (ffffffff81215d4b)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_reaper
```
```
In mm/vmscan.c (ffffffff8122861a)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:balance_pgdat
```
```
In mm/compaction.c (ffffffff81241328)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd
```
```
In mm/ksm.c (ffffffff8128c1e6)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
```
```
In mm/khugepaged.c (ffffffff812a8015)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
```
```
In fs/coredump.c (ffffffff8134b21b)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/ext4/super.c (ffffffff813c319b)
Location: include/linux/freezer.h:35
Inline: True
```
```
In fs/jbd2/journal.c (ffffffff813e151c)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - fs/jbd2/journal.c:kjournald2
  - fs/jbd2/journal.c:kjournald2
```
```
In fs/ecryptfs/kthread.c (ffffffff81404555)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff81648789)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:khvcd
```
```
In drivers/char/virtio_console.c (ffffffff81665185)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:wait_port_writable
  - drivers/char/virtio_console.c:port_fops_read
```
```
In drivers/char/tpm/tpm_tis_core.c (ffffffff81679373)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis_core.c:request_locality
  - drivers/char/tpm/tpm_tis_core.c:release_locality
  - drivers/char/tpm/tpm_tis_core.c:wait_for_tpm_stat
```
```
In net/unix/af_unix.c (ffffffff8198f0bc)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
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
In kernel/fork.c (ffffffff81099e88)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - kernel/fork.c:_do_fork
```
```
In kernel/exit.c (ffffffff8109fddf)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/signal.c (ffffffff810aeef6)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:get_signal
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:ptrace_stop
```
```
In kernel/umh.c (ffffffff810b7809)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - kernel/umh.c:usermodehelper_read_trylock
```
```
In kernel/kthread.c (ffffffff810c295e)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_worker_fn
  - kernel/kthread.c:kthread_worker_fn
  - kernel/kthread.c:kthread_freezable_should_stop
```
```
In kernel/power/process.c (ffffffff810fefba)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - kernel/power/process.c:try_to_freeze_tasks
```
```
In kernel/freezer.c (ffffffff811274a8)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - kernel/freezer.c:set_freezable
  - kernel/freezer.c:freeze_task
  - kernel/freezer.c:__refrigerator
```
```
In kernel/time/hrtimer.c (ffffffff81aded2b)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:do_nanosleep
```
```
In kernel/time/alarmtimer.c (ffffffff81136129)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarmtimer_do_nsleep
```
```
In kernel/futex.c (ffffffff81140e9f)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - kernel/futex.c:futex_wait_queue_me
```
```
In kernel/cgroup/legacy_freezer.c (ffffffff811608cb)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:update_if_frozen
```
```
In kernel/audit.c (ffffffff8116b0f1)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - kernel/audit.c:kauditd_thread
```
```
In mm/oom_kill.c (ffffffff8122093b)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_reaper
```
```
In mm/vmscan.c (ffffffff8123334a)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:balance_pgdat
```
```
In mm/compaction.c (ffffffff8124c128)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd
```
```
In mm/ksm.c (ffffffff81298436)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
```
```
In mm/khugepaged.c (ffffffff812b4c55)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
```
```
In fs/coredump.c (ffffffff81358041)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/ext4/super.c (ffffffff813cfbab)
Location: include/linux/freezer.h:35
Inline: True
```
```
In fs/jbd2/journal.c (ffffffff813ede1c)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - fs/jbd2/journal.c:kjournald2
  - fs/jbd2/journal.c:kjournald2
```
```
In fs/ecryptfs/kthread.c (ffffffff81410e55)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff816967e9)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:khvcd
```
```
In drivers/char/virtio_console.c (ffffffff816b58d5)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:wait_port_writable
  - drivers/char/virtio_console.c:port_fops_read
```
```
In drivers/char/tpm/tpm_tis_core.c (ffffffff816c9bf3)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis_core.c:request_locality
  - drivers/char/tpm/tpm_tis_core.c:release_locality
  - drivers/char/tpm/tpm_tis_core.c:wait_for_tpm_stat
```
```
In net/unix/af_unix.c (ffffffff81a3cd7c)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
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
In kernel/fork.c (ffffffff810a1aec)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - kernel/fork.c:_do_fork
```
```
In kernel/exit.c (ffffffff810a7d4a)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/signal.c (ffffffff810b71c0)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:get_signal
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:ptrace_stop
```
```
In kernel/umh.c (ffffffff810bfb84)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - kernel/umh.c:usermodehelper_read_trylock
```
```
In kernel/kthread.c (ffffffff810ca1fc)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_worker_fn
  - kernel/kthread.c:kthread_worker_fn
  - kernel/kthread.c:kthread_freezable_should_stop
```
```
In kernel/power/process.c (ffffffff8110a2fa)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - kernel/power/process.c:try_to_freeze_tasks
```
```
In kernel/freezer.c (ffffffff81133ae5)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - kernel/freezer.c:set_freezable
  - kernel/freezer.c:freeze_task
  - kernel/freezer.c:__refrigerator
```
```
In kernel/time/hrtimer.c (ffffffff81aeb1b6)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:do_nanosleep
```
```
In kernel/time/alarmtimer.c (ffffffff81142ba9)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - kernel/time/alarmtimer.c:alarmtimer_do_nsleep
```
```
In kernel/futex.c (ffffffff8114d428)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - kernel/futex.c:futex_wait_queue_me
```
```
In kernel/cgroup/legacy_freezer.c (ffffffff8116dc4a)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:update_if_frozen
```
```
In kernel/audit.c (ffffffff811788ee)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - kernel/audit.c:kauditd_thread
```
```
In mm/oom_kill.c (ffffffff8122fa49)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_reaper
```
```
In mm/vmscan.c (ffffffff8124285a)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:balance_pgdat
```
```
In mm/compaction.c (ffffffff8125ba87)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd
```
```
In mm/ksm.c (ffffffff812a80e0)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
```
```
In mm/khugepaged.c (ffffffff812c4ce2)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
```
```
In fs/coredump.c (ffffffff8136b773)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/ext4/super.c (ffffffff813e51a6)
Location: include/linux/freezer.h:35
Inline: True
```
```
In fs/jbd2/journal.c (ffffffff8140393e)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - fs/jbd2/journal.c:kjournald2
  - fs/jbd2/journal.c:kjournald2
```
```
In fs/ecryptfs/kthread.c (ffffffff81426ac9)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff816b0d94)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:khvcd
```
```
In drivers/char/virtio_console.c (ffffffff816d0271)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:wait_port_writable
  - drivers/char/virtio_console.c:port_fops_read
```
```
In drivers/char/tpm/tpm_tis_core.c (ffffffff816e40ce)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis_core.c:request_locality
  - drivers/char/tpm/tpm_tis_core.c:release_locality
  - drivers/char/tpm/tpm_tis_core.c:wait_for_tpm_stat
```
```
In net/unix/af_unix.c (ffffffff81a48333)
Location: include/linux/freezer.h:35
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
```
</details>
</li>
</ul>

## Differences
