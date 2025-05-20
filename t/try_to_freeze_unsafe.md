# Function: <code>try_to_freeze_unsafe</code>

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
In kernel/fork.c (ffffffff8108038f)
Location: include/linux/freezer.h:54
Inline: True
Inline callers:
  - kernel/fork.c:_do_fork
```
```
In kernel/exit.c (ffffffff81083aac)
Location: include/linux/freezer.h:54
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/signal.c (ffffffff8108ebe8)
Location: include/linux/freezer.h:54
Inline: True
Inline callers:
  - kernel/signal.c:ptrace_stop
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:get_signal
  - kernel/signal.c:do_sigtimedwait
```
```
In kernel/kmod.c (ffffffff810960ad)
Location: include/linux/freezer.h:54
Inline: True
Inline callers:
  - kernel/kmod.c:usermodehelper_read_trylock
```
```
In kernel/kthread.c (ffffffff810a0a74)
Location: include/linux/freezer.h:54
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_worker_fn
```
```
In kernel/freezer.c (ffffffff810e9c80)
Location: include/linux/freezer.h:54
Inline: True
Inline callers:
  - kernel/freezer.c:set_freezable
```
```
In kernel/time/hrtimer.c (ffffffff818236ab)
Location: include/linux/freezer.h:54
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:do_nanosleep
```
```
In kernel/futex.c (ffffffff8110011c)
Location: include/linux/freezer.h:54
Inline: True
Inline callers:
  - kernel/futex.c:futex_wait_queue_me
```
```
In kernel/audit.c (ffffffff81120f48)
Location: include/linux/freezer.h:54
Inline: True
Inline callers:
  - kernel/audit.c:kauditd_thread
```
```
In mm/vmscan.c (ffffffff811a58cd)
Location: include/linux/freezer.h:54
Inline: True
Inline callers:
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd
```
```
In mm/ksm.c (ffffffff811e5c47)
Location: include/linux/freezer.h:54
Inline: True
Inline callers:
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
```
```
In mm/huge_memory.c (ffffffff811f4742)
Location: include/linux/freezer.h:54
Inline: True
Inline callers:
  - mm/huge_memory.c:khugepaged
  - mm/huge_memory.c:khugepaged
  - mm/huge_memory.c:khugepaged
  - mm/huge_memory.c:khugepaged
```
```
In fs/ext4/super.c (ffffffff812acfc6)
Location: include/linux/freezer.h:54
Inline: True
```
```
In fs/jbd2/journal.c (ffffffff812ef279)
Location: include/linux/freezer.h:54
Inline: True
Inline callers:
  - fs/jbd2/journal.c:kjournald2
```
```
In fs/ecryptfs/kthread.c (ffffffff8130aca2)
Location: include/linux/freezer.h:54
Inline: True
Inline callers:
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
```
```
In drivers/virtio/virtio_balloon.c (ffffffff814c425a)
Location: include/linux/freezer.h:54
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:balloon
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff814fe5e2)
Location: include/linux/freezer.h:54
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:khvcd
```
```
In drivers/char/virtio_console.c (ffffffff81516925)
Location: include/linux/freezer.h:54
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:port_fops_read
  - drivers/char/virtio_console.c:wait_port_writable
```
```
In net/unix/af_unix.c (ffffffff817bfaf2)
Location: include/linux/freezer.h:54
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
In kernel/fork.c (ffffffff810821c7)
Location: include/linux/freezer.h:54
Inline: True
Inline callers:
  - kernel/fork.c:_do_fork
```
```
In kernel/exit.c (ffffffff81086bc7)
Location: include/linux/freezer.h:54
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/signal.c (ffffffff810944fd)
Location: include/linux/freezer.h:54
Inline: True
Inline callers:
  - kernel/signal.c:do_sigtimedwait
  - kernel/signal.c:get_signal
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:ptrace_stop
```
```
In kernel/kmod.c (ffffffff8109945d)
Location: include/linux/freezer.h:54
Inline: True
Inline callers:
  - kernel/kmod.c:usermodehelper_read_trylock
```
```
In kernel/kthread.c (ffffffff810a4155)
Location: include/linux/freezer.h:54
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_worker_fn
```
```
In kernel/freezer.c (ffffffff810f09e0)
Location: include/linux/freezer.h:54
Inline: True
Inline callers:
  - kernel/freezer.c:set_freezable
```
```
In kernel/time/hrtimer.c (ffffffff8189e31b)
Location: include/linux/freezer.h:54
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:do_nanosleep
```
```
In kernel/futex.c (ffffffff8110711e)
Location: include/linux/freezer.h:54
Inline: True
Inline callers:
  - kernel/futex.c:futex_wait_queue_me
```
```
In kernel/audit.c (ffffffff81128e80)
Location: include/linux/freezer.h:54
Inline: True
Inline callers:
  - kernel/audit.c:kauditd_thread
```
```
In mm/oom_kill.c (ffffffff811a4fe0)
Location: include/linux/freezer.h:54
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_reaper
```
```
In mm/vmscan.c (ffffffff811bc34d)
Location: include/linux/freezer.h:54
Inline: True
Inline callers:
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd
```
```
In mm/compaction.c (ffffffff811d1e28)
Location: include/linux/freezer.h:54
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd
```
```
In mm/ksm.c (ffffffff812045c7)
Location: include/linux/freezer.h:54
Inline: True
Inline callers:
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
```
```
In mm/khugepaged.c (ffffffff8121c206)
Location: include/linux/freezer.h:54
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
```
```
In fs/ext4/super.c (ffffffff812e1882)
Location: include/linux/freezer.h:54
Inline: True
```
```
In fs/jbd2/journal.c (ffffffff8131d7d7)
Location: include/linux/freezer.h:54
Inline: True
Inline callers:
  - fs/jbd2/journal.c:kjournald2
```
```
In fs/ecryptfs/kthread.c (ffffffff8133eefa)
Location: include/linux/freezer.h:54
Inline: True
Inline callers:
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff8154f119)
Location: include/linux/freezer.h:54
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:khvcd
```
```
In drivers/char/virtio_console.c (ffffffff8156a598)
Location: include/linux/freezer.h:54
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:wait_port_writable
  - drivers/char/virtio_console.c:port_fops_read
```
```
In net/unix/af_unix.c (ffffffff8182ca24)
Location: include/linux/freezer.h:54
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
In kernel/fork.c (ffffffff81086c27)
Location: include/linux/freezer.h:54
Inline: True
Inline callers:
  - kernel/fork.c:_do_fork
```
```
In kernel/exit.c (ffffffff8108bb31)
Location: include/linux/freezer.h:54
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/signal.c (ffffffff810994ee)
Location: include/linux/freezer.h:54
Inline: True
Inline callers:
  - kernel/signal.c:do_sigtimedwait
  - kernel/signal.c:get_signal
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:ptrace_stop
```
```
In kernel/kmod.c (ffffffff8109e40d)
Location: include/linux/freezer.h:54
Inline: True
Inline callers:
  - kernel/kmod.c:usermodehelper_read_trylock
```
```
In kernel/kthread.c (ffffffff810a993c)
Location: include/linux/freezer.h:54
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_worker_fn
```
```
In kernel/freezer.c (ffffffff810f7b40)
Location: include/linux/freezer.h:54
Inline: True
Inline callers:
  - kernel/freezer.c:set_freezable
```
```
In kernel/time/hrtimer.c (ffffffff818d31bc)
Location: include/linux/freezer.h:54
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:do_nanosleep
```
```
In kernel/futex.c (ffffffff8110e8de)
Location: include/linux/freezer.h:54
Inline: True
Inline callers:
  - kernel/futex.c:futex_wait_queue_me
```
```
In kernel/audit.c (ffffffff81132abf)
Location: include/linux/freezer.h:54
Inline: True
Inline callers:
  - kernel/audit.c:kauditd_thread
```
```
In mm/oom_kill.c (ffffffff811b50e3)
Location: include/linux/freezer.h:54
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_reaper
```
```
In mm/vmscan.c (ffffffff811cca12)
Location: include/linux/freezer.h:54
Inline: True
Inline callers:
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd
```
```
In mm/compaction.c (ffffffff811e1d41)
Location: include/linux/freezer.h:54
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd
```
```
In mm/ksm.c (ffffffff812166d4)
Location: include/linux/freezer.h:54
Inline: True
Inline callers:
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
```
```
In mm/khugepaged.c (ffffffff8122d9ae)
Location: include/linux/freezer.h:54
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
```
```
In fs/coredump.c (ffffffff812af6da)
Location: include/linux/freezer.h:54
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/ext4/super.c (ffffffff812f7393)
Location: include/linux/freezer.h:54
Inline: True
```
```
In fs/jbd2/journal.c (ffffffff81333757)
Location: include/linux/freezer.h:54
Inline: True
Inline callers:
  - fs/jbd2/journal.c:kjournald2
```
```
In fs/ecryptfs/kthread.c (ffffffff81354c8a)
Location: include/linux/freezer.h:54
Inline: True
Inline callers:
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff8157b999)
Location: include/linux/freezer.h:54
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:khvcd
```
```
In drivers/char/virtio_console.c (ffffffff81596cd3)
Location: include/linux/freezer.h:54
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:wait_port_writable
  - drivers/char/virtio_console.c:port_fops_read
```
```
In net/unix/af_unix.c (ffffffff8185e4ea)
Location: include/linux/freezer.h:54
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
In kernel/fork.c (ffffffff81083974)
Location: include/linux/freezer.h:54
Inline: True
Inline callers:
  - kernel/fork.c:_do_fork
```
```
In kernel/exit.c (ffffffff81088cc0)
Location: include/linux/freezer.h:54
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/signal.c (ffffffff8109324d)
Location: include/linux/freezer.h:54
Inline: True
Inline callers:
  - kernel/signal.c:do_sigtimedwait
  - kernel/signal.c:get_signal
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:ptrace_stop
```
```
In kernel/kmod.c (ffffffff8109bb8b)
Location: include/linux/freezer.h:54
Inline: True
Inline callers:
  - kernel/kmod.c:usermodehelper_read_trylock
```
```
In kernel/kthread.c (ffffffff810a65dc)
Location: include/linux/freezer.h:54
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_worker_fn
```
```
In kernel/freezer.c (ffffffff810f9a10)
Location: include/linux/freezer.h:54
Inline: True
Inline callers:
  - kernel/freezer.c:set_freezable
```
```
In kernel/time/hrtimer.c (ffffffff8190a33f)
Location: include/linux/freezer.h:54
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:do_nanosleep
```
```
In kernel/futex.c (ffffffff8110fdd4)
Location: include/linux/freezer.h:54
Inline: True
Inline callers:
  - kernel/futex.c:futex_wait_queue_me
```
```
In kernel/audit.c (ffffffff81134204)
Location: include/linux/freezer.h:54
Inline: True
Inline callers:
  - kernel/audit.c:kauditd_thread
```
```
In mm/oom_kill.c (ffffffff811bc8a3)
Location: include/linux/freezer.h:54
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_reaper
```
```
In mm/vmscan.c (ffffffff811d56d1)
Location: include/linux/freezer.h:54
Inline: True
Inline callers:
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd
```
```
In mm/compaction.c (ffffffff811ebb41)
Location: include/linux/freezer.h:54
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd
```
```
In mm/ksm.c (ffffffff812220ca)
Location: include/linux/freezer.h:54
Inline: True
Inline callers:
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
```
```
In mm/khugepaged.c (ffffffff812396f3)
Location: include/linux/freezer.h:54
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
```
```
In fs/coredump.c (ffffffff812bcb2e)
Location: include/linux/freezer.h:54
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/ext4/super.c (ffffffff8132bd53)
Location: include/linux/freezer.h:54
Inline: True
```
```
In fs/jbd2/journal.c (ffffffff813484ff)
Location: include/linux/freezer.h:54
Inline: True
Inline callers:
  - fs/jbd2/journal.c:kjournald2
```
```
In fs/ecryptfs/kthread.c (ffffffff8136984a)
Location: include/linux/freezer.h:54
Inline: True
Inline callers:
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff8158f8d9)
Location: include/linux/freezer.h:54
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:khvcd
```
```
In drivers/char/virtio_console.c (ffffffff815aacd5)
Location: include/linux/freezer.h:54
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:wait_port_writable
  - drivers/char/virtio_console.c:port_fops_read
```
```
In net/unix/af_unix.c (ffffffff818838b0)
Location: include/linux/freezer.h:54
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
In kernel/fork.c (ffffffff8108a25a)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - kernel/fork.c:_do_fork
```
```
In kernel/exit.c (ffffffff8108fa06)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/signal.c (ffffffff8109a130)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - kernel/signal.c:do_sigtimedwait
  - kernel/signal.c:get_signal
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:ptrace_stop
```
```
In kernel/umh.c (ffffffff810a2749)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - kernel/umh.c:usermodehelper_read_trylock
```
```
In kernel/kthread.c (ffffffff810acdb1)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_worker_fn
```
```
In kernel/freezer.c (ffffffff811044d0)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - kernel/freezer.c:set_freezable
```
```
In kernel/time/hrtimer.c (ffffffff81994688)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:do_nanosleep
```
```
In kernel/futex.c (ffffffff8111b0c7)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - kernel/futex.c:futex_wait_queue_me
```
```
In kernel/audit.c (ffffffff81141112)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - kernel/audit.c:kauditd_thread
```
```
In mm/oom_kill.c (ffffffff811d15c1)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_reaper
```
```
In mm/vmscan.c (ffffffff811eae59)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd
```
```
In mm/compaction.c (ffffffff81201fa1)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd
```
```
In mm/ksm.c (ffffffff8123d6f9)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
```
```
In mm/khugepaged.c (ffffffff8125818a)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
```
```
In fs/coredump.c (ffffffff812e0412)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/ext4/super.c (ffffffff813502e3)
Location: include/linux/freezer.h:55
Inline: True
```
```
In fs/jbd2/journal.c (ffffffff8136cb4f)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - fs/jbd2/journal.c:kjournald2
```
```
In fs/ecryptfs/kthread.c (ffffffff8138e529)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff815f43ea)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:khvcd
```
```
In drivers/char/virtio_console.c (ffffffff81611694)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:wait_port_writable
  - drivers/char/virtio_console.c:port_fops_read
```
```
In net/unix/af_unix.c (ffffffff81903fba)
Location: include/linux/freezer.h:55
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
In kernel/fork.c (ffffffff8108daa3)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - kernel/fork.c:_do_fork
```
```
In kernel/exit.c (ffffffff81093555)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/signal.c (ffffffff810a0814)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:ptrace_stop
```
```
In kernel/umh.c (ffffffff810a8fc9)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - kernel/umh.c:usermodehelper_read_trylock
```
```
In kernel/kthread.c (ffffffff810b3aa9)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_worker_fn
```
```
In kernel/freezer.c (ffffffff8110f2d0)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - kernel/freezer.c:set_freezable
```
```
In kernel/time/hrtimer.c (ffffffff819f0c15)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:do_nanosleep
```
```
In kernel/futex.c (ffffffff81128211)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - kernel/futex.c:futex_wait_queue_me
```
```
In kernel/audit.c (ffffffff8114fa9b)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - kernel/audit.c:kauditd_thread
```
```
In mm/oom_kill.c (ffffffff811f2ff0)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_reaper
```
```
In mm/vmscan.c (ffffffff8120c860)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:balance_pgdat
```
```
In mm/compaction.c (ffffffff81223371)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd
```
```
In mm/ksm.c (ffffffff8126148d)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
```
```
In mm/khugepaged.c (ffffffff8127d973)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
```
```
In fs/coredump.c (ffffffff8130c63d)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/ext4/super.c (ffffffff8137e4a3)
Location: include/linux/freezer.h:55
Inline: True
```
```
In fs/jbd2/journal.c (ffffffff8139b23f)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - fs/jbd2/journal.c:kjournald2
```
```
In fs/ecryptfs/kthread.c (ffffffff813bd5d9)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff8162d69a)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:khvcd
```
```
In drivers/char/virtio_console.c (ffffffff8164b27b)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:wait_port_writable
  - drivers/char/virtio_console.c:port_fops_read
```
```
In net/unix/af_unix.c (ffffffff8195c0e9)
Location: include/linux/freezer.h:55
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
In kernel/fork.c (ffffffff81095d33)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - kernel/fork.c:_do_fork
```
```
In kernel/exit.c (ffffffff8109b814)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/signal.c (ffffffff810a8b22)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:ptrace_stop
```
```
In kernel/umh.c (ffffffff810b1e89)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - kernel/umh.c:usermodehelper_read_trylock
```
```
In kernel/kthread.c (ffffffff810bc7b9)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_worker_fn
```
```
In kernel/freezer.c (ffffffff8111a910)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - kernel/freezer.c:set_freezable
```
```
In kernel/time/hrtimer.c (ffffffff81a2bf95)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:do_nanosleep
```
```
In kernel/futex.c (ffffffff81133af1)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - kernel/futex.c:futex_wait_queue_me
```
```
In kernel/audit.c (ffffffff8115c77b)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - kernel/audit.c:kauditd_thread
```
```
In mm/oom_kill.c (ffffffff8120507e)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_reaper
```
```
In mm/vmscan.c (ffffffff8121f6f0)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:balance_pgdat
```
```
In mm/compaction.c (ffffffff812363d6)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd
```
```
In mm/ksm.c (ffffffff81275c6b)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
```
```
In mm/khugepaged.c (ffffffff8129143e)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
```
```
In fs/coredump.c (ffffffff81321e9d)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/ext4/super.c (ffffffff81396d53)
Location: include/linux/freezer.h:55
Inline: True
```
```
In fs/jbd2/journal.c (ffffffff813b3faf)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - fs/jbd2/journal.c:kjournald2
```
```
In fs/ecryptfs/kthread.c (ffffffff813d6c19)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff8164ba9a)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:khvcd
```
```
In drivers/char/virtio_console.c (ffffffff816693eb)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:wait_port_writable
  - drivers/char/virtio_console.c:port_fops_read
```
```
In net/unix/af_unix.c (ffffffff819908f8)
Location: include/linux/freezer.h:55
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
In kernel/fork.c (ffffffff81099fd3)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - kernel/fork.c:_do_fork
```
```
In kernel/exit.c (ffffffff8109fe8c)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/signal.c (ffffffff810af00a)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:get_signal
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:ptrace_stop
```
```
In kernel/umh.c (ffffffff810b7a34)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - kernel/umh.c:usermodehelper_read_trylock
```
```
In kernel/kthread.c (ffffffff810c26db)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_worker_fn
```
```
In kernel/freezer.c (ffffffff81125013)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - kernel/freezer.c:set_freezable
```
```
In kernel/time/hrtimer.c (ffffffff81a9c14f)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:do_nanosleep
```
```
In kernel/futex.c (ffffffff8113ea55)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - kernel/futex.c:futex_wait_queue_me
```
```
In kernel/audit.c (ffffffff81168e5c)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - kernel/audit.c:kauditd_thread
```
```
In mm/oom_kill.c (ffffffff8121cb66)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_reaper
```
```
In mm/vmscan.c (ffffffff8122eebc)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:balance_pgdat
```
```
In mm/compaction.c (ffffffff812478d3)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd
```
```
In mm/ksm.c (ffffffff812922c1)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
```
```
In mm/khugepaged.c (ffffffff812ac584)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
```
```
In fs/coredump.c (ffffffff81349cec)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/ext4/super.c (ffffffff813c0de6)
Location: include/linux/freezer.h:55
Inline: True
```
```
In fs/jbd2/journal.c (ffffffff813de5c9)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - fs/jbd2/journal.c:kjournald2
```
```
In fs/ecryptfs/kthread.c (ffffffff81401600)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff816802f4)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:khvcd
```
```
In drivers/char/virtio_console.c (ffffffff8169edb0)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:wait_port_writable
  - drivers/char/virtio_console.c:port_fops_read
```
```
In net/unix/af_unix.c (ffffffff819fbfd7)
Location: include/linux/freezer.h:55
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
In kernel/fork.c (ffffffff810a05b3)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - kernel/fork.c:_do_fork
```
```
In kernel/exit.c (ffffffff810a650a)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/signal.c (ffffffff810b5621)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:get_signal
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:ptrace_stop
```
```
In kernel/umh.c (ffffffff810bdf34)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - kernel/umh.c:usermodehelper_read_trylock
```
```
In kernel/kthread.c (ffffffff810c9089)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_worker_fn
```
```
In kernel/freezer.c (ffffffff81130fd3)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - kernel/freezer.c:set_freezable
```
```
In kernel/time/hrtimer.c (ffffffff81ad3aa6)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:do_nanosleep
```
```
In kernel/futex.c (ffffffff8114a9ca)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - kernel/futex.c:futex_wait_queue_me
```
```
In kernel/audit.c (ffffffff81174cfc)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - kernel/audit.c:kauditd_thread
```
```
In mm/oom_kill.c (ffffffff8122a546)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_reaper
```
```
In mm/vmscan.c (ffffffff8123d04c)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:balance_pgdat
```
```
In mm/compaction.c (ffffffff81255d33)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd
```
```
In mm/ksm.c (ffffffff812a2041)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
```
```
In mm/khugepaged.c (ffffffff812be860)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
```
```
In fs/coredump.c (ffffffff81361f8c)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/ext4/super.c (ffffffff813da136)
Location: include/linux/freezer.h:55
Inline: True
```
```
In fs/jbd2/journal.c (ffffffff813f8619)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - fs/jbd2/journal.c:kjournald2
```
```
In fs/ecryptfs/kthread.c (ffffffff8141b4f0)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff816a29a4)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:khvcd
```
```
In drivers/char/virtio_console.c (ffffffff816c1b40)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:wait_port_writable
  - drivers/char/virtio_console.c:port_fops_read
```
```
In net/unix/af_unix.c (ffffffff81a32c67)
Location: include/linux/freezer.h:55
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
In kernel/fork.c (ffffffff810a51fb)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - kernel/fork.c:wait_for_vfork_done
```
```
In kernel/exit.c (ffffffff810adf72)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - kernel/exit.c:exit_mm
```
```
In kernel/signal.c (ffffffff810b923e)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - kernel/signal.c:do_sigtimedwait
  - kernel/signal.c:get_signal
  - kernel/signal.c:get_signal
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:ptrace_stop
```
```
In kernel/umh.c (ffffffff810c53a3)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - kernel/umh.c:usermodehelper_read_trylock
```
```
In kernel/kthread.c (ffffffff810d14ab)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_worker_fn
```
```
In kernel/freezer.c (ffffffff81140393)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - kernel/freezer.c:set_freezable
```
```
In kernel/time/hrtimer.c (ffffffff81bcba10)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:do_nanosleep
```
```
In kernel/futex.c (ffffffff8115b5ea)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - kernel/futex.c:futex_wait_queue_me
```
```
In kernel/audit.c (ffffffff81186d93)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - kernel/audit.c:kauditd_thread
```
```
In mm/oom_kill.c (ffffffff812574d4)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_reaper
```
```
In mm/vmscan.c (ffffffff81269d84)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:balance_pgdat
```
```
In mm/compaction.c (ffffffff81284423)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd
```
```
In mm/ksm.c (ffffffff812d68fa)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
```
```
In mm/khugepaged.c (ffffffff812f006e)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_wait_work
  - mm/khugepaged.c:khugepaged_wait_work
  - mm/khugepaged.c:khugepaged_do_scan
  - mm/khugepaged.c:khugepaged_do_scan
```
```
In fs/coredump.c (ffffffff813a7e3f)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - fs/coredump.c:coredump_wait
```
```
In fs/ext4/super.c (ffffffff81427043)
Location: include/linux/freezer.h:55
Inline: True
```
```
In fs/jbd2/journal.c (ffffffff81445e5b)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - fs/jbd2/journal.c:kjournald2
```
```
In fs/ecryptfs/kthread.c (ffffffff81469fe5)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff81754e3a)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:khvcd
```
```
In drivers/char/virtio_console.c (ffffffff81777265)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:wait_port_writable
  - drivers/char/virtio_console.c:port_fops_read
```
```
In net/unix/af_unix.c (ffffffff81b24859)
Location: include/linux/freezer.h:55
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
In arch/x86/kernel/cpu/sgx/main.c (ffffffff81068f1e)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:ksgxd
  - arch/x86/kernel/cpu/sgx/main.c:ksgxd
```
```
In kernel/fork.c (ffffffff810a091b)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - kernel/fork.c:wait_for_vfork_done
```
```
In kernel/exit.c (ffffffff810a9603)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - kernel/exit.c:exit_mm
```
```
In kernel/signal.c (ffffffff810b44ee)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - kernel/signal.c:do_sigtimedwait
  - kernel/signal.c:get_signal
  - kernel/signal.c:get_signal
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:ptrace_stop
```
```
In kernel/umh.c (ffffffff810c0783)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - kernel/umh.c:usermodehelper_read_trylock
```
```
In kernel/kthread.c (ffffffff810cbe6d)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_worker_fn
```
```
In kernel/freezer.c (ffffffff8113c703)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - kernel/freezer.c:set_freezable
```
```
In kernel/time/hrtimer.c (ffffffff81c44890)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:do_nanosleep
```
```
In kernel/futex.c (ffffffff8115771a)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - kernel/futex.c:futex_wait_queue_me
```
```
In kernel/audit.c (ffffffff811840c7)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - kernel/audit.c:kauditd_thread
```
```
In mm/oom_kill.c (ffffffff812620b4)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_reaper
```
```
In mm/vmscan.c (ffffffff812748b5)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:balance_pgdat
```
```
In mm/compaction.c (ffffffff8128e5ca)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd
```
```
In mm/ksm.c (ffffffff812e2437)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
```
```
In mm/khugepaged.c (ffffffff812fb82e)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_wait_work
  - mm/khugepaged.c:khugepaged_wait_work
  - mm/khugepaged.c:khugepaged_do_scan
  - mm/khugepaged.c:khugepaged_do_scan
```
```
In fs/coredump.c (ffffffff813b8d06)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - fs/coredump.c:coredump_wait
```
```
In fs/ext4/super.c (ffffffff8143ee46)
Location: include/linux/freezer.h:55
Inline: True
```
```
In fs/jbd2/journal.c (ffffffff8146223b)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - fs/jbd2/journal.c:kjournald2
```
```
In fs/ecryptfs/kthread.c (ffffffff81484a55)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff8177013a)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:khvcd
```
```
In drivers/char/virtio_console.c (ffffffff81791f95)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:wait_port_writable
  - drivers/char/virtio_console.c:port_fops_read
```
```
In net/unix/af_unix.c (ffffffff81b332c9)
Location: include/linux/freezer.h:55
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
In arch/x86/kernel/cpu/sgx/main.c (ffffffff8106903e)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:ksgxd
  - arch/x86/kernel/cpu/sgx/main.c:ksgxd
```
```
In kernel/fork.c (ffffffff810a3cf1)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - kernel/fork.c:kernel_clone
```
```
In kernel/exit.c (ffffffff810aa643)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - kernel/exit.c:exit_mm
```
```
In kernel/signal.c (ffffffff810b60ff)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - kernel/signal.c:do_sigtimedwait
  - kernel/signal.c:get_signal
  - kernel/signal.c:get_signal
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:ptrace_stop
```
```
In kernel/umh.c (ffffffff810c2183)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - kernel/umh.c:usermodehelper_read_trylock
```
```
In kernel/kthread.c (ffffffff810cd7bd)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_worker_fn
```
```
In kernel/freezer.c (ffffffff8113d953)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - kernel/freezer.c:set_freezable
```
```
In kernel/time/hrtimer.c (ffffffff81c37b00)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:do_nanosleep
```
```
In kernel/futex.c (ffffffff81158b69)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - kernel/futex.c:futex_wait_queue_me
```
```
In kernel/audit.c (ffffffff81184ff3)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - kernel/audit.c:kauditd_thread
```
```
In mm/oom_kill.c (ffffffff812669fc)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_reaper
```
```
In mm/vmscan.c (ffffffff81279bc5)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:balance_pgdat
```
```
In mm/compaction.c (ffffffff81293c5a)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd
```
```
In mm/ksm.c (ffffffff812e9bc5)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
```
```
In mm/khugepaged.c (ffffffff81306432)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged_wait_work
  - mm/khugepaged.c:khugepaged_wait_work
```
```
In fs/coredump.c (ffffffff813bfe03)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - fs/coredump.c:coredump_wait
```
```
In fs/ext4/super.c (ffffffff81444c86)
Location: include/linux/freezer.h:55
Inline: True
```
```
In fs/jbd2/journal.c (ffffffff814678eb)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - fs/jbd2/journal.c:kjournald2
```
```
In fs/ecryptfs/kthread.c (ffffffff8148a505)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff81753bea)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:khvcd
```
```
In drivers/char/virtio_console.c (ffffffff81774a15)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:wait_port_writable
  - drivers/char/virtio_console.c:port_fops_read
```
```
In net/unix/af_unix.c (ffffffff81b21001)
Location: include/linux/freezer.h:55
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
In arch/x86/kernel/cpu/sgx/main.c (ffffffff810739f0)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:ksgxd
  - arch/x86/kernel/cpu/sgx/main.c:ksgxd
```
```
In kernel/fork.c (ffffffff810b550e)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - kernel/fork.c:kernel_clone
```
```
In kernel/exit.c (ffffffff810bc17f)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - kernel/exit.c:exit_mm
```
```
In kernel/signal.c (ffffffff810c8f8f)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - kernel/signal.c:do_sigtimedwait
  - kernel/signal.c:get_signal
  - kernel/signal.c:get_signal
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:ptrace_stop
```
```
In kernel/umh.c (ffffffff810d4cc3)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - kernel/umh.c:usermodehelper_read_trylock
```
```
In kernel/kthread.c (ffffffff810e09a8)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_worker_fn
```
```
In kernel/freezer.c (ffffffff81160ad3)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - kernel/freezer.c:set_freezable
```
```
In kernel/time/hrtimer.c (ffffffff81d56375)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:do_nanosleep
```
```
In kernel/futex.c (ffffffff8117da46)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - kernel/futex.c:futex_wait_queue_me
```
```
In kernel/audit.c (ffffffff811ad3e3)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - kernel/audit.c:kauditd_thread
```
```
In mm/oom_kill.c (ffffffff812a2fcc)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_reaper
```
```
In mm/vmscan.c (ffffffff812b7b72)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:balance_pgdat
```
```
In mm/compaction.c (ffffffff812d42b6)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd
```
```
In mm/ksm.c (ffffffff81331af5)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
```
```
In mm/khugepaged.c (ffffffff8135039b)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged_wait_work
  - mm/khugepaged.c:khugepaged_wait_work
```
```
In fs/coredump.c (ffffffff8140fc32)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - fs/coredump.c:coredump_wait
```
```
In fs/ext4/super.c (ffffffff81498b16)
Location: include/linux/freezer.h:55
Inline: True
```
```
In fs/jbd2/journal.c (ffffffff814bd88b)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - fs/jbd2/journal.c:kjournald2
```
```
In fs/ecryptfs/kthread.c (ffffffff814e1d05)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
```
```
In drivers/xen/balloon.c (ffffffff81791e55)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - drivers/xen/balloon.c:balloon_thread
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff817d7136)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:khvcd
```
```
In drivers/char/virtio_console.c (ffffffff817f9d42)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:wait_port_writable
  - drivers/char/virtio_console.c:port_fops_read
```
```
In net/unix/af_unix.c (ffffffff81be60c1)
Location: include/linux/freezer.h:55
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
In arch/x86/kernel/cpu/sgx/main.c (ffffffff81081ee2)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:ksgxd
  - arch/x86/kernel/cpu/sgx/main.c:ksgxd
```
```
In kernel/fork.c (ffffffff810cb881)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - kernel/fork.c:kernel_clone
```
```
In kernel/exit.c (ffffffff810d2ddf)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/signal.c (ffffffff810e050a)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - kernel/signal.c:do_sigtimedwait
  - kernel/signal.c:get_signal
  - kernel/signal.c:get_signal
  - kernel/signal.c:do_signal_stop
```
```
In kernel/umh.c (ffffffff810edc62)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - kernel/umh.c:usermodehelper_read_trylock
```
```
In kernel/kthread.c (ffffffff810fab36)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_worker_fn
```
```
In kernel/freezer.c (ffffffff81193847)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - kernel/freezer.c:set_freezable
```
```
In kernel/time/hrtimer.c (ffffffff81f28583)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:do_nanosleep
```
```
In kernel/futex/waitwake.c (ffffffff811b7433)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - kernel/futex/waitwake.c:futex_wait_multiple
  - kernel/futex/waitwake.c:futex_wait_queue
```
```
In kernel/audit.c (ffffffff811df0de)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - kernel/audit.c:kauditd_thread
```
```
In mm/oom_kill.c (ffffffff812fae2c)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_reaper
```
```
In mm/vmscan.c (ffffffff81312954)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:balance_pgdat
```
```
In mm/compaction.c (ffffffff8133321e)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd
```
```
In mm/ksm.c (ffffffff813a2b5f)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
```
```
In mm/khugepaged.c (ffffffff813c8496)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged_wait_work
  - mm/khugepaged.c:khugepaged_wait_work
```
```
In fs/coredump.c (ffffffff81484864)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - fs/coredump.c:coredump_wait
```
```
In fs/ext4/super.c (ffffffff815239d3)
Location: include/linux/freezer.h:55
Inline: True
```
```
In fs/jbd2/journal.c (ffffffff81548f65)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - fs/jbd2/journal.c:kjournald2
```
```
In fs/ecryptfs/kthread.c (ffffffff8156ff16)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
```
```
In drivers/xen/balloon.c (ffffffff818caa8d)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - drivers/xen/balloon.c:balloon_thread
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff81915286)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:khvcd
```
```
In drivers/char/virtio_console.c (ffffffff81938834)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:wait_port_writable
  - drivers/char/virtio_console.c:port_fops_read
```
```
In net/unix/af_unix.c (ffffffff81d7d2b8)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_data_wait
```
</details>
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
In kernel/fork.c (ffff8000100f4e84)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - kernel/fork.c:_do_fork
```
```
In kernel/exit.c (ffff8000100fd48c)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/signal.c (ffff800010111774)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:get_signal
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:ptrace_stop
```
```
In kernel/umh.c (ffff80001011a774)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - kernel/umh.c:usermodehelper_read_trylock
```
```
In kernel/kthread.c (ffff8000101278d0)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_worker_fn
```
```
In kernel/freezer.c (ffff80001019828c)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - kernel/freezer.c:set_freezable
```
```
In kernel/time/hrtimer.c (ffff800010da6634)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:do_nanosleep
```
```
In kernel/futex.c (ffff8000101b66f0)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - kernel/futex.c:futex_wait_queue_me
```
```
In kernel/audit.c (ffff8000101e9988)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - kernel/audit.c:kauditd_thread
```
```
In mm/oom_kill.c (ffff8000102b8534)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_reaper
```
```
In mm/vmscan.c (ffff8000102ce2dc)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:balance_pgdat
```
```
In mm/compaction.c (ffff8000102ed2b8)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd
```
```
In mm/ksm.c (ffff800010341894)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
```
```
In mm/khugepaged.c (ffff80001035fd98)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
```
```
In fs/coredump.c (ffff80001042899c)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/ext4/super.c (ffff8000104ad790)
Location: include/linux/freezer.h:55
Inline: True
```
```
In fs/jbd2/journal.c (ffff8000104d6748)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - fs/jbd2/journal.c:kjournald2
```
```
In fs/ecryptfs/kthread.c (ffff8000104fc92c)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
```
```
In drivers/tty/hvc/hvc_console.c (ffff80001087affc)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:khvcd
```
```
In drivers/char/virtio_console.c (ffff8000108b3eb8)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:wait_port_writable
  - drivers/char/virtio_console.c:port_fops_read
```
```
In net/unix/af_unix.c (ffff800010cf23ec)
Location: include/linux/freezer.h:55
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
In kernel/fork.c (c03535e4)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - kernel/fork.c:_do_fork
```
```
In kernel/exit.c (c035a5ec)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/signal.c (c0365694)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - kernel/signal.c:do_sigtimedwait
  - kernel/signal.c:get_signal
  - kernel/signal.c:get_signal
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:ptrace_stop
```
```
In kernel/umh.c (c036ecb4)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - kernel/umh.c:usermodehelper_read_trylock
```
```
In kernel/kthread.c (c0379ed4)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_worker_fn
```
```
In kernel/freezer.c (c03e32b4)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - kernel/freezer.c:set_freezable
```
```
In kernel/time/hrtimer.c (c0e9e3c4)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:do_nanosleep
```
```
In kernel/futex.c (c0401224)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - kernel/futex.c:futex_wait_queue_me
```
```
In kernel/audit.c (c0429834)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - kernel/audit.c:kauditd_thread
```
```
In mm/oom_kill.c (c04e4d08)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_reaper
```
```
In mm/vmscan.c (c04f8164)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:balance_pgdat
```
```
In mm/compaction.c (c0511184)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd
```
```
In mm/ksm.c (c0547818)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
```
```
In fs/coredump.c (c05f12b0)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/ext4/super.c (c067651c)
Location: include/linux/freezer.h:55
Inline: True
```
```
In fs/jbd2/journal.c (c0696f2c)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - fs/jbd2/journal.c:kjournald2
```
```
In fs/ecryptfs/kthread.c (c06b9f94)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
```
```
In drivers/tty/hvc/hvc_console.c (c097cd2c)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:khvcd
```
```
In drivers/char/virtio_console.c (c09aef98)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:wait_port_writable
  - drivers/char/virtio_console.c:port_fops_read
```
```
In net/unix/af_unix.c (c0dfa358)
Location: include/linux/freezer.h:55
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
In arch/powerpc/platforms/powernv/opal.c (c0000000000c5148)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - arch/powerpc/platforms/powernv/opal.c:kopald
```
```
In kernel/fork.c (c00000000013af68)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - kernel/fork.c:_do_fork
```
```
In kernel/exit.c (c000000000144354)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/signal.c (c000000000159308)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:get_signal
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:ptrace_stop
```
```
In kernel/umh.c (c000000000162070)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - kernel/umh.c:usermodehelper_read_trylock
```
```
In kernel/kthread.c (c000000000172cf0)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_worker_fn
```
```
In kernel/freezer.c (c0000000001f81cc)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - kernel/freezer.c:set_freezable
```
```
In kernel/time/hrtimer.c (c000000000ee8dec)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:do_nanosleep
```
```
In kernel/futex.c (c00000000021c098)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - kernel/futex.c:futex_wait_queue_me
```
```
In kernel/audit.c (c00000000025a89c)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - kernel/audit.c:kauditd_thread
```
```
In mm/oom_kill.c (c00000000037073c)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_reaper
```
```
In mm/vmscan.c (c00000000038c074)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:balance_pgdat
```
```
In mm/compaction.c (c0000000003b0f0c)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd
```
```
In mm/ksm.c (c00000000041ef6c)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
```
```
In mm/khugepaged.c (c00000000044b55c)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
```
```
In fs/coredump.c (c000000000538848)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/ext4/super.c (c0000000005e647c)
Location: include/linux/freezer.h:55
Inline: True
```
```
In fs/jbd2/journal.c (c00000000060f2bc)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - fs/jbd2/journal.c:kjournald2
```
```
In fs/ecryptfs/kthread.c (c00000000063f8e0)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
```
```
In drivers/tty/hvc/hvc_console.c (c00000000092211c)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:khvcd
```
```
In drivers/char/virtio_console.c (c00000000094d724)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:wait_port_writable
  - drivers/char/virtio_console.c:port_fops_read
```
```
In net/unix/af_unix.c (c000000000e1886c)
Location: include/linux/freezer.h:55
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
In kernel/fork.c (ffffffe0000c151c)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - kernel/fork.c:_do_fork
```
```
In kernel/exit.c (ffffffe0000c5cce)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/signal.c (ffffffe0000d151c)
Location: include/linux/freezer.h:55
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
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - kernel/umh.c:usermodehelper_read_trylock
```
```
In kernel/kthread.c (ffffffe0000df9d0)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_worker_fn
```
```
In kernel/freezer.c (ffffffe000128fe4)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - kernel/freezer.c:set_freezable
```
```
In kernel/time/hrtimer.c (ffffffe0008c8a0a)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:do_nanosleep
```
```
In kernel/futex.c (ffffffe00013cbc8)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - kernel/futex.c:futex_wait_queue_me
```
```
In kernel/audit.c (ffffffe00015e522)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - kernel/audit.c:kauditd_thread
```
```
In mm/oom_kill.c (ffffffe0001dc2ee)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_reaper
```
```
In mm/vmscan.c (ffffffe0001ec5bc)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:balance_pgdat
```
```
In mm/compaction.c (ffffffe0002018a2)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd
```
```
In mm/ksm.c (ffffffe000235dd6)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
```
```
In fs/coredump.c (ffffffe0002c6850)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/ext4/super.c (ffffffe000330b2e)
Location: include/linux/freezer.h:55
Inline: True
```
```
In fs/jbd2/journal.c (ffffffe00034b2aa)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - fs/jbd2/journal.c:kjournald2
```
```
In fs/ecryptfs/kthread.c (ffffffe00036aefc)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
```
```
In drivers/tty/hvc/hvc_console.c (ffffffe00054ac1e)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:khvcd
```
```
In drivers/char/virtio_console.c (ffffffe000565d40)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:wait_port_writable
  - drivers/char/virtio_console.c:port_fops_read
```
```
In net/unix/af_unix.c (ffffffe00083f52c)
Location: include/linux/freezer.h:55
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
In kernel/fork.c (ffffffff81099ed3)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - kernel/fork.c:_do_fork
```
```
In kernel/exit.c (ffffffff8109fe2a)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/signal.c (ffffffff810af991)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:get_signal
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:ptrace_stop
```
```
In kernel/umh.c (ffffffff810b82a4)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - kernel/umh.c:usermodehelper_read_trylock
```
```
In kernel/kthread.c (ffffffff810c3409)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_worker_fn
```
```
In kernel/freezer.c (ffffffff81129783)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - kernel/freezer.c:set_freezable
```
```
In kernel/time/hrtimer.c (ffffffff81a72916)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:do_nanosleep
```
```
In kernel/futex.c (ffffffff81142fea)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - kernel/futex.c:futex_wait_queue_me
```
```
In kernel/audit.c (ffffffff8116d31c)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - kernel/audit.c:kauditd_thread
```
```
In mm/oom_kill.c (ffffffff81222b96)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_reaper
```
```
In mm/vmscan.c (ffffffff8123569c)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:balance_pgdat
```
```
In mm/compaction.c (ffffffff8124e383)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd
```
```
In mm/ksm.c (ffffffff8129a621)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
```
```
In mm/khugepaged.c (ffffffff812b6e40)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
```
```
In fs/coredump.c (ffffffff8135a56c)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/ext4/super.c (ffffffff813d2716)
Location: include/linux/freezer.h:55
Inline: True
```
```
In fs/jbd2/journal.c (ffffffff813f0bf9)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - fs/jbd2/journal.c:kjournald2
```
```
In fs/ecryptfs/kthread.c (ffffffff81413ad0)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff81668404)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:khvcd
```
```
In drivers/char/virtio_console.c (ffffffff81687590)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:wait_port_writable
  - drivers/char/virtio_console.c:port_fops_read
```
```
In net/unix/af_unix.c (ffffffff819d22f7)
Location: include/linux/freezer.h:55
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
In kernel/fork.c (ffffffff81088913)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - kernel/fork.c:_do_fork
```
```
In kernel/exit.c (ffffffff8108e85a)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/signal.c (ffffffff8109e2b1)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:get_signal
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:ptrace_stop
```
```
In kernel/umh.c (ffffffff810a6be4)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - kernel/umh.c:usermodehelper_read_trylock
```
```
In kernel/kthread.c (ffffffff810b1c49)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_worker_fn
```
```
In kernel/freezer.c (ffffffff8111c00d)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - kernel/freezer.c:set_freezable
```
```
In kernel/time/hrtimer.c (ffffffff81a2ece6)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:do_nanosleep
```
```
In kernel/futex.c (ffffffff8113634a)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - kernel/futex.c:futex_wait_queue_me
```
```
In kernel/audit.c (ffffffff811604bc)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - kernel/audit.c:kauditd_thread
```
```
In mm/oom_kill.c (ffffffff81215d46)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_reaper
```
```
In mm/vmscan.c (ffffffff8122870c)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:balance_pgdat
```
```
In mm/compaction.c (ffffffff81241323)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd
```
```
In mm/ksm.c (ffffffff8128c1e1)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
```
```
In mm/khugepaged.c (ffffffff812a8010)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
```
```
In fs/coredump.c (ffffffff8134b216)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/ext4/super.c (ffffffff813c3196)
Location: include/linux/freezer.h:55
Inline: True
```
```
In fs/jbd2/journal.c (ffffffff813e1679)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - fs/jbd2/journal.c:kjournald2
```
```
In fs/ecryptfs/kthread.c (ffffffff81404550)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff81648784)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:khvcd
```
```
In drivers/char/virtio_console.c (ffffffff81665180)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:wait_port_writable
  - drivers/char/virtio_console.c:port_fops_read
```
```
In net/unix/af_unix.c (ffffffff8198f0b7)
Location: include/linux/freezer.h:55
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
In kernel/fork.c (ffffffff81099e83)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - kernel/fork.c:_do_fork
```
```
In kernel/exit.c (ffffffff8109fdda)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/signal.c (ffffffff810aeef1)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:get_signal
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:ptrace_stop
```
```
In kernel/umh.c (ffffffff810b7804)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - kernel/umh.c:usermodehelper_read_trylock
```
```
In kernel/kthread.c (ffffffff810c2959)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_worker_fn
```
```
In kernel/freezer.c (ffffffff811274a3)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - kernel/freezer.c:set_freezable
```
```
In kernel/time/hrtimer.c (ffffffff81aded26)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:do_nanosleep
```
```
In kernel/futex.c (ffffffff81140e9a)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - kernel/futex.c:futex_wait_queue_me
```
```
In kernel/audit.c (ffffffff8116b0ec)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - kernel/audit.c:kauditd_thread
```
```
In mm/oom_kill.c (ffffffff81220936)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_reaper
```
```
In mm/vmscan.c (ffffffff8123343c)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:balance_pgdat
```
```
In mm/compaction.c (ffffffff8124c123)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd
```
```
In mm/ksm.c (ffffffff81298431)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
```
```
In mm/khugepaged.c (ffffffff812b4c50)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
```
```
In fs/coredump.c (ffffffff8135803c)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/ext4/super.c (ffffffff813cfba6)
Location: include/linux/freezer.h:55
Inline: True
```
```
In fs/jbd2/journal.c (ffffffff813edf79)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - fs/jbd2/journal.c:kjournald2
```
```
In fs/ecryptfs/kthread.c (ffffffff81410e50)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff816967e4)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:khvcd
```
```
In drivers/char/virtio_console.c (ffffffff816b58d0)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:wait_port_writable
  - drivers/char/virtio_console.c:port_fops_read
```
```
In net/unix/af_unix.c (ffffffff81a3cd77)
Location: include/linux/freezer.h:55
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
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - kernel/fork.c:_do_fork
```
```
In kernel/exit.c (ffffffff810a7d4a)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/signal.c (ffffffff810b71c0)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:get_signal
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:ptrace_stop
```
```
In kernel/umh.c (ffffffff810bfb84)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - kernel/umh.c:usermodehelper_read_trylock
```
```
In kernel/kthread.c (ffffffff810ca1fc)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - kernel/kthread.c:kthread_worker_fn
```
```
In kernel/freezer.c (ffffffff81133ae5)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - kernel/freezer.c:set_freezable
```
```
In kernel/time/hrtimer.c (ffffffff81aeb1b6)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:do_nanosleep
```
```
In kernel/futex.c (ffffffff8114d428)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - kernel/futex.c:futex_wait_queue_me
```
```
In kernel/audit.c (ffffffff811788ee)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - kernel/audit.c:kauditd_thread
```
```
In mm/oom_kill.c (ffffffff8122fa49)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_reaper
```
```
In mm/vmscan.c (ffffffff81242952)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:balance_pgdat
```
```
In mm/compaction.c (ffffffff8125ba87)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd
```
```
In mm/ksm.c (ffffffff812a80e0)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
```
```
In mm/khugepaged.c (ffffffff812c4ce2)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
```
```
In fs/coredump.c (ffffffff8136b773)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/ext4/super.c (ffffffff813e51a6)
Location: include/linux/freezer.h:55
Inline: True
```
```
In fs/jbd2/journal.c (ffffffff81403aa4)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - fs/jbd2/journal.c:kjournald2
```
```
In fs/ecryptfs/kthread.c (ffffffff81426ac9)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
```
```
In drivers/tty/hvc/hvc_console.c (ffffffff816b0d94)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - drivers/tty/hvc/hvc_console.c:khvcd
```
```
In drivers/char/virtio_console.c (ffffffff816d0271)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:wait_port_writable
  - drivers/char/virtio_console.c:port_fops_read
```
```
In net/unix/af_unix.c (ffffffff81a48333)
Location: include/linux/freezer.h:55
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
```
</details>
</li>
</ul>

## Differences
