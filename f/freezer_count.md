# Function: <code>freezer_count</code>

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
In kernel/fork.c (ffffffff81080381)
Location: include/linux/freezer.h:118
Inline: True
Inline callers:
  - kernel/fork.c:_do_fork
```
```
In kernel/exit.c (ffffffff81083aa0)
Location: include/linux/freezer.h:118
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/signal.c (ffffffff8108ebde)
Location: include/linux/freezer.h:118
Inline: True
Inline callers:
  - kernel/signal.c:ptrace_stop
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:do_sigtimedwait
```
```
In kernel/time/hrtimer.c (ffffffff8182369f)
Location: include/linux/freezer.h:118
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:do_nanosleep
```
```
In kernel/futex.c (ffffffff81100112)
Location: include/linux/freezer.h:118
Inline: True
Inline callers:
  - kernel/futex.c:futex_wait_queue_me
```
```
In mm/huge_memory.c (ffffffff811f4738)
Location: include/linux/freezer.h:118
Inline: True
Inline callers:
  - mm/huge_memory.c:khugepaged
```
```
In net/unix/af_unix.c (ffffffff817bfae4)
Location: include/linux/freezer.h:118
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
In kernel/fork.c (ffffffff810821ba)
Location: include/linux/freezer.h:118
Inline: True
Inline callers:
  - kernel/fork.c:_do_fork
```
```
In kernel/exit.c (ffffffff81086bbb)
Location: include/linux/freezer.h:118
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/signal.c (ffffffff810944ef)
Location: include/linux/freezer.h:118
Inline: True
Inline callers:
  - kernel/signal.c:do_sigtimedwait
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:ptrace_stop
```
```
In kernel/time/hrtimer.c (ffffffff8189e30f)
Location: include/linux/freezer.h:118
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:do_nanosleep
```
```
In kernel/futex.c (ffffffff81107114)
Location: include/linux/freezer.h:118
Inline: True
Inline callers:
  - kernel/futex.c:futex_wait_queue_me
```
```
In mm/khugepaged.c (ffffffff8121c1fc)
Location: include/linux/freezer.h:118
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
```
```
In net/unix/af_unix.c (ffffffff8182ca11)
Location: include/linux/freezer.h:118
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
In kernel/fork.c (ffffffff81086c1a)
Location: include/linux/freezer.h:118
Inline: True
Inline callers:
  - kernel/fork.c:_do_fork
```
```
In kernel/exit.c (ffffffff8108bb25)
Location: include/linux/freezer.h:118
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/signal.c (ffffffff810994e0)
Location: include/linux/freezer.h:118
Inline: True
Inline callers:
  - kernel/signal.c:do_sigtimedwait
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:ptrace_stop
```
```
In kernel/time/hrtimer.c (ffffffff818d31b0)
Location: include/linux/freezer.h:118
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:do_nanosleep
```
```
In kernel/futex.c (ffffffff8110e8d4)
Location: include/linux/freezer.h:118
Inline: True
Inline callers:
  - kernel/futex.c:futex_wait_queue_me
```
```
In mm/khugepaged.c (ffffffff8122d9a4)
Location: include/linux/freezer.h:118
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
```
```
In fs/coredump.c (ffffffff812af6cf)
Location: include/linux/freezer.h:118
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In net/unix/af_unix.c (ffffffff8185e4d9)
Location: include/linux/freezer.h:118
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
In kernel/fork.c (ffffffff81083966)
Location: include/linux/freezer.h:118
Inline: True
Inline callers:
  - kernel/fork.c:_do_fork
```
```
In kernel/exit.c (ffffffff81088cb5)
Location: include/linux/freezer.h:118
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/signal.c (ffffffff8109323f)
Location: include/linux/freezer.h:118
Inline: True
Inline callers:
  - kernel/signal.c:do_sigtimedwait
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:ptrace_stop
```
```
In kernel/time/hrtimer.c (ffffffff8190a333)
Location: include/linux/freezer.h:118
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:do_nanosleep
```
```
In kernel/futex.c (ffffffff8110fdca)
Location: include/linux/freezer.h:118
Inline: True
Inline callers:
  - kernel/futex.c:futex_wait_queue_me
```
```
In mm/khugepaged.c (ffffffff812399ab)
Location: include/linux/freezer.h:118
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
```
```
In fs/coredump.c (ffffffff812bcb23)
Location: include/linux/freezer.h:118
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In net/unix/af_unix.c (ffffffff8188389f)
Location: include/linux/freezer.h:118
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
In kernel/fork.c (ffffffff8108a249)
Location: include/linux/freezer.h:119
Inline: True
Inline callers:
  - kernel/fork.c:_do_fork
```
```
In kernel/exit.c (ffffffff8108f9f8)
Location: include/linux/freezer.h:119
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/signal.c (ffffffff8109a11f)
Location: include/linux/freezer.h:119
Inline: True
Inline callers:
  - kernel/signal.c:do_sigtimedwait
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:ptrace_stop
```
```
In kernel/time/hrtimer.c (ffffffff81994679)
Location: include/linux/freezer.h:119
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:do_nanosleep
```
```
In kernel/futex.c (ffffffff8111b0ba)
Location: include/linux/freezer.h:119
Inline: True
Inline callers:
  - kernel/futex.c:futex_wait_queue_me
```
```
In mm/khugepaged.c (ffffffff8125817d)
Location: include/linux/freezer.h:119
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
```
```
In fs/coredump.c (ffffffff812e0404)
Location: include/linux/freezer.h:119
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In net/unix/af_unix.c (ffffffff81903fa5)
Location: include/linux/freezer.h:119
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
In kernel/fork.c (ffffffff8108da9d)
Location: include/linux/freezer.h:119
Inline: True
Inline callers:
  - kernel/fork.c:_do_fork
```
```
In kernel/exit.c (ffffffff81093547)
Location: include/linux/freezer.h:119
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/signal.c (ffffffff8109efd9)
Location: include/linux/freezer.h:119
Inline: True
Inline callers:
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:ptrace_stop
```
```
In kernel/time/hrtimer.c (ffffffff819f0c06)
Location: include/linux/freezer.h:119
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:do_nanosleep
```
```
In kernel/futex.c (ffffffff81128204)
Location: include/linux/freezer.h:119
Inline: True
Inline callers:
  - kernel/futex.c:futex_wait_queue_me
```
```
In mm/khugepaged.c (ffffffff8127d965)
Location: include/linux/freezer.h:119
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
```
```
In fs/coredump.c (ffffffff8130c62f)
Location: include/linux/freezer.h:119
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In net/unix/af_unix.c (ffffffff8195c0e3)
Location: include/linux/freezer.h:119
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
In kernel/fork.c (ffffffff81095d2d)
Location: include/linux/freezer.h:119
Inline: True
Inline callers:
  - kernel/fork.c:_do_fork
```
```
In kernel/exit.c (ffffffff8109b806)
Location: include/linux/freezer.h:119
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/signal.c (ffffffff810a729b)
Location: include/linux/freezer.h:119
Inline: True
Inline callers:
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:ptrace_stop
```
```
In kernel/time/hrtimer.c (ffffffff81a2bf86)
Location: include/linux/freezer.h:119
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:do_nanosleep
```
```
In kernel/futex.c (ffffffff81133ae4)
Location: include/linux/freezer.h:119
Inline: True
Inline callers:
  - kernel/futex.c:futex_wait_queue_me
```
```
In mm/khugepaged.c (ffffffff81291431)
Location: include/linux/freezer.h:119
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
```
```
In fs/coredump.c (ffffffff81321e8f)
Location: include/linux/freezer.h:119
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In net/unix/af_unix.c (ffffffff819908f2)
Location: include/linux/freezer.h:119
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
In kernel/fork.c (ffffffff81099fc5)
Location: include/linux/freezer.h:119
Inline: True
Inline callers:
  - kernel/fork.c:_do_fork
```
```
In kernel/exit.c (ffffffff8109fe7e)
Location: include/linux/freezer.h:119
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/signal.c (ffffffff810aeffd)
Location: include/linux/freezer.h:119
Inline: True
Inline callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:ptrace_stop
```
```
In kernel/time/hrtimer.c (ffffffff81a9c140)
Location: include/linux/freezer.h:119
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:do_nanosleep
```
```
In kernel/futex.c (ffffffff8113ea46)
Location: include/linux/freezer.h:119
Inline: True
Inline callers:
  - kernel/futex.c:futex_wait_queue_me
```
```
In kernel/audit.c (ffffffff81168e4f)
Location: include/linux/freezer.h:119
Inline: True
Inline callers:
  - kernel/audit.c:kauditd_thread
```
```
In mm/oom_kill.c (ffffffff8121cb59)
Location: include/linux/freezer.h:119
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_reaper
```
```
In mm/compaction.c (ffffffff812478c5)
Location: include/linux/freezer.h:119
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd
```
```
In mm/ksm.c (ffffffff812922b2)
Location: include/linux/freezer.h:119
Inline: True
Inline callers:
  - mm/ksm.c:ksm_scan_thread
```
```
In mm/khugepaged.c (ffffffff812ac577)
Location: include/linux/freezer.h:119
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
```
```
In fs/coredump.c (ffffffff81349cde)
Location: include/linux/freezer.h:119
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/ecryptfs/kthread.c (ffffffff814015f3)
Location: include/linux/freezer.h:119
Inline: True
Inline callers:
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
```
```
In drivers/char/virtio_console.c (ffffffff8169eda2)
Location: include/linux/freezer.h:119
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:wait_port_writable
  - drivers/char/virtio_console.c:port_fops_read
```
```
In net/unix/af_unix.c (ffffffff819fbfc3)
Location: include/linux/freezer.h:119
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
In kernel/fork.c (ffffffff810a05a5)
Location: include/linux/freezer.h:119
Inline: True
Inline callers:
  - kernel/fork.c:_do_fork
```
```
In kernel/exit.c (ffffffff810a64fc)
Location: include/linux/freezer.h:119
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/signal.c (ffffffff810b5614)
Location: include/linux/freezer.h:119
Inline: True
Inline callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:ptrace_stop
```
```
In kernel/time/hrtimer.c (ffffffff81ad3a97)
Location: include/linux/freezer.h:119
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:do_nanosleep
```
```
In kernel/futex.c (ffffffff8114a9bb)
Location: include/linux/freezer.h:119
Inline: True
Inline callers:
  - kernel/futex.c:futex_wait_queue_me
```
```
In kernel/audit.c (ffffffff81174cef)
Location: include/linux/freezer.h:119
Inline: True
Inline callers:
  - kernel/audit.c:kauditd_thread
```
```
In mm/oom_kill.c (ffffffff8122a539)
Location: include/linux/freezer.h:119
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_reaper
```
```
In mm/compaction.c (ffffffff81255d25)
Location: include/linux/freezer.h:119
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd
```
```
In mm/ksm.c (ffffffff812a2032)
Location: include/linux/freezer.h:119
Inline: True
Inline callers:
  - mm/ksm.c:ksm_scan_thread
```
```
In mm/khugepaged.c (ffffffff812beab5)
Location: include/linux/freezer.h:119
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
```
```
In fs/coredump.c (ffffffff81361f7e)
Location: include/linux/freezer.h:119
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/ecryptfs/kthread.c (ffffffff8141b4e3)
Location: include/linux/freezer.h:119
Inline: True
Inline callers:
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
```
```
In drivers/char/virtio_console.c (ffffffff816c1b32)
Location: include/linux/freezer.h:119
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:wait_port_writable
  - drivers/char/virtio_console.c:port_fops_read
```
```
In net/unix/af_unix.c (ffffffff81a32c53)
Location: include/linux/freezer.h:119
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
In kernel/fork.c (ffffffff810a51ed)
Location: include/linux/freezer.h:119
Inline: True
Inline callers:
  - kernel/fork.c:wait_for_vfork_done
```
```
In kernel/exit.c (ffffffff810adf65)
Location: include/linux/freezer.h:119
Inline: True
Inline callers:
  - kernel/exit.c:exit_mm
```
```
In kernel/signal.c (ffffffff810b9238)
Location: include/linux/freezer.h:119
Inline: True
Inline callers:
  - kernel/signal.c:do_sigtimedwait
  - kernel/signal.c:get_signal
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:ptrace_stop
```
```
In kernel/time/hrtimer.c (ffffffff81bcba01)
Location: include/linux/freezer.h:119
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:do_nanosleep
```
```
In kernel/futex.c (ffffffff8115b5db)
Location: include/linux/freezer.h:119
Inline: True
Inline callers:
  - kernel/futex.c:futex_wait_queue_me
```
```
In kernel/audit.c (ffffffff81186d86)
Location: include/linux/freezer.h:119
Inline: True
Inline callers:
  - kernel/audit.c:kauditd_thread
```
```
In mm/oom_kill.c (ffffffff812574c6)
Location: include/linux/freezer.h:119
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_reaper
```
```
In mm/compaction.c (ffffffff81284415)
Location: include/linux/freezer.h:119
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd
```
```
In mm/ksm.c (ffffffff812d68eb)
Location: include/linux/freezer.h:119
Inline: True
Inline callers:
  - mm/ksm.c:ksm_scan_thread
```
```
In mm/khugepaged.c (ffffffff812f0068)
Location: include/linux/freezer.h:119
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_wait_work
  - mm/khugepaged.c:khugepaged_wait_work
  - mm/khugepaged.c:khugepaged_do_scan
```
```
In fs/coredump.c (ffffffff813a7e30)
Location: include/linux/freezer.h:119
Inline: True
Inline callers:
  - fs/coredump.c:coredump_wait
```
```
In fs/ecryptfs/kthread.c (ffffffff81469fd6)
Location: include/linux/freezer.h:119
Inline: True
Inline callers:
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
```
```
In drivers/char/virtio_console.c (ffffffff81777257)
Location: include/linux/freezer.h:119
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:wait_port_writable
  - drivers/char/virtio_console.c:port_fops_read
```
```
In net/unix/af_unix.c (ffffffff81b24853)
Location: include/linux/freezer.h:119
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
In arch/x86/kernel/cpu/sgx/main.c (ffffffff81068f11)
Location: include/linux/freezer.h:119
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:ksgxd
```
```
In kernel/fork.c (ffffffff810a090d)
Location: include/linux/freezer.h:119
Inline: True
Inline callers:
  - kernel/fork.c:wait_for_vfork_done
```
```
In kernel/exit.c (ffffffff810a95f6)
Location: include/linux/freezer.h:119
Inline: True
Inline callers:
  - kernel/exit.c:exit_mm
```
```
In kernel/signal.c (ffffffff810b44e8)
Location: include/linux/freezer.h:119
Inline: True
Inline callers:
  - kernel/signal.c:do_sigtimedwait
  - kernel/signal.c:get_signal
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:ptrace_stop
```
```
In kernel/time/hrtimer.c (ffffffff81c44881)
Location: include/linux/freezer.h:119
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:do_nanosleep
```
```
In kernel/futex.c (ffffffff8115770b)
Location: include/linux/freezer.h:119
Inline: True
Inline callers:
  - kernel/futex.c:futex_wait_queue_me
```
```
In kernel/audit.c (ffffffff811840ba)
Location: include/linux/freezer.h:119
Inline: True
Inline callers:
  - kernel/audit.c:kauditd_thread
```
```
In mm/oom_kill.c (ffffffff812620a6)
Location: include/linux/freezer.h:119
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_reaper
```
```
In mm/compaction.c (ffffffff8128e5c4)
Location: include/linux/freezer.h:119
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd
```
```
In mm/ksm.c (ffffffff812e2428)
Location: include/linux/freezer.h:119
Inline: True
Inline callers:
  - mm/ksm.c:ksm_scan_thread
```
```
In mm/khugepaged.c (ffffffff812fb828)
Location: include/linux/freezer.h:119
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_wait_work
  - mm/khugepaged.c:khugepaged_wait_work
  - mm/khugepaged.c:khugepaged_do_scan
```
```
In fs/coredump.c (ffffffff813b8cf7)
Location: include/linux/freezer.h:119
Inline: True
Inline callers:
  - fs/coredump.c:coredump_wait
```
```
In fs/ecryptfs/kthread.c (ffffffff81484a46)
Location: include/linux/freezer.h:119
Inline: True
Inline callers:
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
```
```
In drivers/char/virtio_console.c (ffffffff81791f87)
Location: include/linux/freezer.h:119
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:wait_port_writable
  - drivers/char/virtio_console.c:port_fops_read
```
```
In net/unix/af_unix.c (ffffffff81b332b8)
Location: include/linux/freezer.h:119
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
In arch/x86/kernel/cpu/sgx/main.c (ffffffff81069031)
Location: include/linux/freezer.h:119
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:ksgxd
```
```
In kernel/fork.c (ffffffff810a3ce2)
Location: include/linux/freezer.h:119
Inline: True
Inline callers:
  - kernel/fork.c:kernel_clone
```
```
In kernel/exit.c (ffffffff810aa636)
Location: include/linux/freezer.h:119
Inline: True
Inline callers:
  - kernel/exit.c:exit_mm
```
```
In kernel/signal.c (ffffffff810b60f9)
Location: include/linux/freezer.h:119
Inline: True
Inline callers:
  - kernel/signal.c:do_sigtimedwait
  - kernel/signal.c:get_signal
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:ptrace_stop
```
```
In kernel/time/hrtimer.c (ffffffff81c37af1)
Location: include/linux/freezer.h:119
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:do_nanosleep
```
```
In kernel/futex.c (ffffffff81158b5a)
Location: include/linux/freezer.h:119
Inline: True
Inline callers:
  - kernel/futex.c:futex_wait_queue_me
```
```
In kernel/audit.c (ffffffff81184fe6)
Location: include/linux/freezer.h:119
Inline: True
Inline callers:
  - kernel/audit.c:kauditd_thread
```
```
In mm/oom_kill.c (ffffffff812669ef)
Location: include/linux/freezer.h:119
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_reaper
```
```
In mm/compaction.c (ffffffff81293c54)
Location: include/linux/freezer.h:119
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd
```
```
In mm/ksm.c (ffffffff812e9bb8)
Location: include/linux/freezer.h:119
Inline: True
Inline callers:
  - mm/ksm.c:ksm_scan_thread
```
```
In mm/khugepaged.c (ffffffff81306424)
Location: include/linux/freezer.h:119
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged_wait_work
  - mm/khugepaged.c:khugepaged_wait_work
```
```
In fs/coredump.c (ffffffff813bfdf4)
Location: include/linux/freezer.h:119
Inline: True
Inline callers:
  - fs/coredump.c:coredump_wait
```
```
In fs/ecryptfs/kthread.c (ffffffff8148a4f6)
Location: include/linux/freezer.h:119
Inline: True
Inline callers:
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
```
```
In drivers/char/virtio_console.c (ffffffff81774a07)
Location: include/linux/freezer.h:119
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:wait_port_writable
  - drivers/char/virtio_console.c:port_fops_read
```
```
In net/unix/af_unix.c (ffffffff81b20ffb)
Location: include/linux/freezer.h:119
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
In arch/x86/kernel/cpu/sgx/main.c (ffffffff810739e3)
Location: include/linux/freezer.h:119
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:ksgxd
```
```
In kernel/fork.c (ffffffff810b54ff)
Location: include/linux/freezer.h:119
Inline: True
Inline callers:
  - kernel/fork.c:kernel_clone
```
```
In kernel/exit.c (ffffffff810bc172)
Location: include/linux/freezer.h:119
Inline: True
Inline callers:
  - kernel/exit.c:exit_mm
```
```
In kernel/signal.c (ffffffff810c8f89)
Location: include/linux/freezer.h:119
Inline: True
Inline callers:
  - kernel/signal.c:do_sigtimedwait
  - kernel/signal.c:get_signal
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:ptrace_stop
```
```
In kernel/time/hrtimer.c (ffffffff81d56366)
Location: include/linux/freezer.h:119
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:do_nanosleep
```
```
In kernel/futex.c (ffffffff8117da37)
Location: include/linux/freezer.h:119
Inline: True
Inline callers:
  - kernel/futex.c:futex_wait_queue_me
```
```
In kernel/audit.c (ffffffff811ad3d6)
Location: include/linux/freezer.h:119
Inline: True
Inline callers:
  - kernel/audit.c:kauditd_thread
```
```
In mm/oom_kill.c (ffffffff812a2fbf)
Location: include/linux/freezer.h:119
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_reaper
```
```
In mm/compaction.c (ffffffff812d42b0)
Location: include/linux/freezer.h:119
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd
```
```
In mm/ksm.c (ffffffff81331ae8)
Location: include/linux/freezer.h:119
Inline: True
Inline callers:
  - mm/ksm.c:ksm_scan_thread
```
```
In mm/khugepaged.c (ffffffff8135038d)
Location: include/linux/freezer.h:119
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged_wait_work
  - mm/khugepaged.c:khugepaged_wait_work
```
```
In fs/coredump.c (ffffffff8140fc23)
Location: include/linux/freezer.h:119
Inline: True
Inline callers:
  - fs/coredump.c:coredump_wait
```
```
In fs/ecryptfs/kthread.c (ffffffff814e1cf6)
Location: include/linux/freezer.h:119
Inline: True
Inline callers:
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
```
```
In drivers/xen/balloon.c (ffffffff81791e4f)
Location: include/linux/freezer.h:119
Inline: True
Inline callers:
  - drivers/xen/balloon.c:balloon_thread
```
```
In drivers/char/virtio_console.c (ffffffff817f9d34)
Location: include/linux/freezer.h:119
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:wait_port_writable
  - drivers/char/virtio_console.c:port_fops_read
```
```
In net/unix/af_unix.c (ffffffff81be60bb)
Location: include/linux/freezer.h:119
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
In arch/x86/kernel/cpu/sgx/main.c (ffffffff81081ed5)
Location: include/linux/freezer.h:119
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:ksgxd
```
```
In kernel/fork.c (ffffffff810cb873)
Location: include/linux/freezer.h:119
Inline: True
Inline callers:
  - kernel/fork.c:kernel_clone
```
```
In kernel/exit.c (ffffffff810d2dd2)
Location: include/linux/freezer.h:119
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/signal.c (ffffffff810e0504)
Location: include/linux/freezer.h:119
Inline: True
Inline callers:
  - kernel/signal.c:do_sigtimedwait
  - kernel/signal.c:get_signal
  - kernel/signal.c:do_signal_stop
```
```
In kernel/time/hrtimer.c (ffffffff81f28574)
Location: include/linux/freezer.h:119
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:do_nanosleep
```
```
In kernel/futex/waitwake.c (ffffffff811b7425)
Location: include/linux/freezer.h:119
Inline: True
Inline callers:
  - kernel/futex/waitwake.c:futex_wait_multiple
  - kernel/futex/waitwake.c:futex_wait_queue
```
```
In kernel/audit.c (ffffffff811df0cf)
Location: include/linux/freezer.h:119
Inline: True
Inline callers:
  - kernel/audit.c:kauditd_thread
```
```
In mm/oom_kill.c (ffffffff812fae1f)
Location: include/linux/freezer.h:119
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_reaper
```
```
In mm/compaction.c (ffffffff81333218)
Location: include/linux/freezer.h:119
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd
```
```
In mm/ksm.c (ffffffff813a2b50)
Location: include/linux/freezer.h:119
Inline: True
Inline callers:
  - mm/ksm.c:ksm_scan_thread
```
```
In mm/khugepaged.c (ffffffff813c8488)
Location: include/linux/freezer.h:119
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged_wait_work
  - mm/khugepaged.c:khugepaged_wait_work
```
```
In fs/coredump.c (ffffffff81484857)
Location: include/linux/freezer.h:119
Inline: True
Inline callers:
  - fs/coredump.c:coredump_wait
```
```
In fs/ecryptfs/kthread.c (ffffffff8156ff09)
Location: include/linux/freezer.h:119
Inline: True
Inline callers:
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
```
```
In drivers/xen/balloon.c (ffffffff818caa87)
Location: include/linux/freezer.h:119
Inline: True
Inline callers:
  - drivers/xen/balloon.c:balloon_thread
```
```
In drivers/char/virtio_console.c (ffffffff81938826)
Location: include/linux/freezer.h:119
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:wait_port_writable
  - drivers/char/virtio_console.c:port_fops_read
```
```
In net/unix/af_unix.c (ffffffff81d7d2b2)
Location: include/linux/freezer.h:119
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
In kernel/fork.c (ffff8000100f4e74)
Location: include/linux/freezer.h:119
Inline: True
Inline callers:
  - kernel/fork.c:_do_fork
```
```
In kernel/exit.c (ffff8000100fd47c)
Location: include/linux/freezer.h:119
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/signal.c (ffff800010111764)
Location: include/linux/freezer.h:119
Inline: True
Inline callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:ptrace_stop
```
```
In kernel/time/hrtimer.c (ffff800010da6624)
Location: include/linux/freezer.h:119
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:do_nanosleep
```
```
In kernel/futex.c (ffff8000101b66e0)
Location: include/linux/freezer.h:119
Inline: True
Inline callers:
  - kernel/futex.c:futex_wait_queue_me
```
```
In kernel/audit.c (ffff8000101e9978)
Location: include/linux/freezer.h:119
Inline: True
Inline callers:
  - kernel/audit.c:kauditd_thread
```
```
In mm/oom_kill.c (ffff8000102b8524)
Location: include/linux/freezer.h:119
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_reaper
```
```
In mm/compaction.c (ffff8000102ed2a8)
Location: include/linux/freezer.h:119
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd
```
```
In mm/ksm.c (ffff800010341884)
Location: include/linux/freezer.h:119
Inline: True
Inline callers:
  - mm/ksm.c:ksm_scan_thread
```
```
In mm/khugepaged.c (ffff80001035fd88)
Location: include/linux/freezer.h:119
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
```
```
In fs/coredump.c (ffff80001042898c)
Location: include/linux/freezer.h:119
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/ecryptfs/kthread.c (ffff8000104fc91c)
Location: include/linux/freezer.h:119
Inline: True
Inline callers:
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
```
```
In drivers/char/virtio_console.c (ffff8000108b3ea8)
Location: include/linux/freezer.h:119
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:wait_port_writable
  - drivers/char/virtio_console.c:port_fops_read
```
```
In net/unix/af_unix.c (ffff800010cf23dc)
Location: include/linux/freezer.h:119
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
In kernel/fork.c (c03535c8)
Location: include/linux/freezer.h:119
Inline: True
Inline callers:
  - kernel/fork.c:_do_fork
```
```
In kernel/exit.c (c035a5d8)
Location: include/linux/freezer.h:119
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/signal.c (c0365680)
Location: include/linux/freezer.h:119
Inline: True
Inline callers:
  - kernel/signal.c:do_sigtimedwait
  - kernel/signal.c:get_signal
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:ptrace_stop
```
```
In kernel/time/hrtimer.c (c0e9e3b0)
Location: include/linux/freezer.h:119
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:do_nanosleep
```
```
In kernel/futex.c (c0401208)
Location: include/linux/freezer.h:119
Inline: True
Inline callers:
  - kernel/futex.c:futex_wait_queue_me
```
```
In kernel/audit.c (c0429820)
Location: include/linux/freezer.h:119
Inline: True
Inline callers:
  - kernel/audit.c:kauditd_thread
```
```
In mm/oom_kill.c (c04e4cf4)
Location: include/linux/freezer.h:119
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_reaper
```
```
In mm/compaction.c (c0511170)
Location: include/linux/freezer.h:119
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd
```
```
In mm/ksm.c (c0547804)
Location: include/linux/freezer.h:119
Inline: True
Inline callers:
  - mm/ksm.c:ksm_scan_thread
```
```
In fs/coredump.c (c05f1294)
Location: include/linux/freezer.h:119
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/ecryptfs/kthread.c (c06b9f80)
Location: include/linux/freezer.h:119
Inline: True
Inline callers:
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
```
```
In drivers/char/virtio_console.c (c09aef84)
Location: include/linux/freezer.h:119
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:wait_port_writable
  - drivers/char/virtio_console.c:port_fops_read
```
```
In net/unix/af_unix.c (c0dfa354)
Location: include/linux/freezer.h:119
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
In kernel/fork.c (c00000000013af58)
Location: include/linux/freezer.h:119
Inline: True
Inline callers:
  - kernel/fork.c:_do_fork
```
```
In kernel/exit.c (c000000000144344)
Location: include/linux/freezer.h:119
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/signal.c (c0000000001592f8)
Location: include/linux/freezer.h:119
Inline: True
Inline callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:ptrace_stop
```
```
In kernel/time/hrtimer.c (c000000000ee8ddc)
Location: include/linux/freezer.h:119
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:do_nanosleep
```
```
In kernel/futex.c (c00000000021c088)
Location: include/linux/freezer.h:119
Inline: True
Inline callers:
  - kernel/futex.c:futex_wait_queue_me
```
```
In kernel/audit.c (c00000000025a88c)
Location: include/linux/freezer.h:119
Inline: True
Inline callers:
  - kernel/audit.c:kauditd_thread
```
```
In mm/oom_kill.c (c00000000037072c)
Location: include/linux/freezer.h:119
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_reaper
```
```
In mm/compaction.c (c0000000003b0efc)
Location: include/linux/freezer.h:119
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd
```
```
In mm/ksm.c (c00000000041ef5c)
Location: include/linux/freezer.h:119
Inline: True
Inline callers:
  - mm/ksm.c:ksm_scan_thread
```
```
In mm/khugepaged.c (c00000000044b54c)
Location: include/linux/freezer.h:119
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
```
```
In fs/coredump.c (c000000000538838)
Location: include/linux/freezer.h:119
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/ecryptfs/kthread.c (c00000000063f8d0)
Location: include/linux/freezer.h:119
Inline: True
Inline callers:
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
```
```
In drivers/char/virtio_console.c (c00000000094d714)
Location: include/linux/freezer.h:119
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:wait_port_writable
  - drivers/char/virtio_console.c:port_fops_read
```
```
In net/unix/af_unix.c (c000000000e18860)
Location: include/linux/freezer.h:119
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
In kernel/fork.c (ffffffe0000c1508)
Location: include/linux/freezer.h:119
Inline: True
Inline callers:
  - kernel/fork.c:_do_fork
```
```
In kernel/exit.c (ffffffe0000c5cc2)
Location: include/linux/freezer.h:119
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/signal.c (ffffffe0000d1506)
Location: include/linux/freezer.h:119
Inline: True
Inline callers:
  - kernel/signal.c:__se_sys_rt_sigtimedwait
  - kernel/signal.c:get_signal
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:ptrace_stop
```
```
In kernel/time/hrtimer.c (ffffffe0008c89fe)
Location: include/linux/freezer.h:119
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:do_nanosleep
```
```
In kernel/futex.c (ffffffe00013cbb4)
Location: include/linux/freezer.h:119
Inline: True
Inline callers:
  - kernel/futex.c:futex_wait_queue_me
```
```
In kernel/audit.c (ffffffe00015e512)
Location: include/linux/freezer.h:119
Inline: True
Inline callers:
  - kernel/audit.c:kauditd_thread
```
```
In mm/oom_kill.c (ffffffe0001dc18c)
Location: include/linux/freezer.h:119
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_reaper
```
```
In mm/compaction.c (ffffffe000201826)
Location: include/linux/freezer.h:119
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd
```
```
In mm/ksm.c (ffffffe000235be8)
Location: include/linux/freezer.h:119
Inline: True
Inline callers:
  - mm/ksm.c:ksm_scan_thread
```
```
In fs/coredump.c (ffffffe0002c683c)
Location: include/linux/freezer.h:119
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/ecryptfs/kthread.c (ffffffe00036aeee)
Location: include/linux/freezer.h:119
Inline: True
Inline callers:
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
```
```
In drivers/char/virtio_console.c (ffffffe000565d2a)
Location: include/linux/freezer.h:119
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:wait_port_writable
  - drivers/char/virtio_console.c:port_fops_read
```
```
In net/unix/af_unix.c (ffffffe00083f092)
Location: include/linux/freezer.h:119
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
In kernel/fork.c (ffffffff81099ec5)
Location: include/linux/freezer.h:119
Inline: True
Inline callers:
  - kernel/fork.c:_do_fork
```
```
In kernel/exit.c (ffffffff8109fe1c)
Location: include/linux/freezer.h:119
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/signal.c (ffffffff810af984)
Location: include/linux/freezer.h:119
Inline: True
Inline callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:ptrace_stop
```
```
In kernel/time/hrtimer.c (ffffffff81a72907)
Location: include/linux/freezer.h:119
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:do_nanosleep
```
```
In kernel/futex.c (ffffffff81142fdb)
Location: include/linux/freezer.h:119
Inline: True
Inline callers:
  - kernel/futex.c:futex_wait_queue_me
```
```
In kernel/audit.c (ffffffff8116d30f)
Location: include/linux/freezer.h:119
Inline: True
Inline callers:
  - kernel/audit.c:kauditd_thread
```
```
In mm/oom_kill.c (ffffffff81222b89)
Location: include/linux/freezer.h:119
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_reaper
```
```
In mm/compaction.c (ffffffff8124e375)
Location: include/linux/freezer.h:119
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd
```
```
In mm/ksm.c (ffffffff8129a612)
Location: include/linux/freezer.h:119
Inline: True
Inline callers:
  - mm/ksm.c:ksm_scan_thread
```
```
In mm/khugepaged.c (ffffffff812b7095)
Location: include/linux/freezer.h:119
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
```
```
In fs/coredump.c (ffffffff8135a55e)
Location: include/linux/freezer.h:119
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/ecryptfs/kthread.c (ffffffff81413ac3)
Location: include/linux/freezer.h:119
Inline: True
Inline callers:
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
```
```
In drivers/char/virtio_console.c (ffffffff81687582)
Location: include/linux/freezer.h:119
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:wait_port_writable
  - drivers/char/virtio_console.c:port_fops_read
```
```
In net/unix/af_unix.c (ffffffff819d22e3)
Location: include/linux/freezer.h:119
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
In kernel/fork.c (ffffffff81088905)
Location: include/linux/freezer.h:119
Inline: True
Inline callers:
  - kernel/fork.c:_do_fork
```
```
In kernel/exit.c (ffffffff8108e84c)
Location: include/linux/freezer.h:119
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/signal.c (ffffffff8109e2a4)
Location: include/linux/freezer.h:119
Inline: True
Inline callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:ptrace_stop
```
```
In kernel/time/hrtimer.c (ffffffff81a2ecd7)
Location: include/linux/freezer.h:119
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:do_nanosleep
```
```
In kernel/futex.c (ffffffff8113633b)
Location: include/linux/freezer.h:119
Inline: True
Inline callers:
  - kernel/futex.c:futex_wait_queue_me
```
```
In kernel/audit.c (ffffffff811604af)
Location: include/linux/freezer.h:119
Inline: True
Inline callers:
  - kernel/audit.c:kauditd_thread
```
```
In mm/oom_kill.c (ffffffff81215d39)
Location: include/linux/freezer.h:119
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_reaper
```
```
In mm/compaction.c (ffffffff81241315)
Location: include/linux/freezer.h:119
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd
```
```
In mm/ksm.c (ffffffff8128c1d2)
Location: include/linux/freezer.h:119
Inline: True
Inline callers:
  - mm/ksm.c:ksm_scan_thread
```
```
In mm/khugepaged.c (ffffffff812a8265)
Location: include/linux/freezer.h:119
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
```
```
In fs/coredump.c (ffffffff8134b208)
Location: include/linux/freezer.h:119
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/ecryptfs/kthread.c (ffffffff81404543)
Location: include/linux/freezer.h:119
Inline: True
Inline callers:
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
```
```
In drivers/char/virtio_console.c (ffffffff81665172)
Location: include/linux/freezer.h:119
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:wait_port_writable
  - drivers/char/virtio_console.c:port_fops_read
```
```
In net/unix/af_unix.c (ffffffff8198f0a3)
Location: include/linux/freezer.h:119
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
In kernel/fork.c (ffffffff81099e75)
Location: include/linux/freezer.h:119
Inline: True
Inline callers:
  - kernel/fork.c:_do_fork
```
```
In kernel/exit.c (ffffffff8109fdcc)
Location: include/linux/freezer.h:119
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/signal.c (ffffffff810aeee4)
Location: include/linux/freezer.h:119
Inline: True
Inline callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:ptrace_stop
```
```
In kernel/time/hrtimer.c (ffffffff81aded17)
Location: include/linux/freezer.h:119
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:do_nanosleep
```
```
In kernel/futex.c (ffffffff81140e8b)
Location: include/linux/freezer.h:119
Inline: True
Inline callers:
  - kernel/futex.c:futex_wait_queue_me
```
```
In kernel/audit.c (ffffffff8116b0df)
Location: include/linux/freezer.h:119
Inline: True
Inline callers:
  - kernel/audit.c:kauditd_thread
```
```
In mm/oom_kill.c (ffffffff81220929)
Location: include/linux/freezer.h:119
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_reaper
```
```
In mm/compaction.c (ffffffff8124c115)
Location: include/linux/freezer.h:119
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd
```
```
In mm/ksm.c (ffffffff81298422)
Location: include/linux/freezer.h:119
Inline: True
Inline callers:
  - mm/ksm.c:ksm_scan_thread
```
```
In mm/khugepaged.c (ffffffff812b4ea5)
Location: include/linux/freezer.h:119
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
```
```
In fs/coredump.c (ffffffff8135802e)
Location: include/linux/freezer.h:119
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/ecryptfs/kthread.c (ffffffff81410e43)
Location: include/linux/freezer.h:119
Inline: True
Inline callers:
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
```
```
In drivers/char/virtio_console.c (ffffffff816b58c2)
Location: include/linux/freezer.h:119
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:wait_port_writable
  - drivers/char/virtio_console.c:port_fops_read
```
```
In net/unix/af_unix.c (ffffffff81a3cd63)
Location: include/linux/freezer.h:119
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
In kernel/fork.c (ffffffff810a1ade)
Location: include/linux/freezer.h:119
Inline: True
Inline callers:
  - kernel/fork.c:_do_fork
```
```
In kernel/exit.c (ffffffff810a7d3c)
Location: include/linux/freezer.h:119
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/signal.c (ffffffff810b71b3)
Location: include/linux/freezer.h:119
Inline: True
Inline callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:ptrace_stop
```
```
In kernel/time/hrtimer.c (ffffffff81aeb1a7)
Location: include/linux/freezer.h:119
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:do_nanosleep
```
```
In kernel/futex.c (ffffffff8114d419)
Location: include/linux/freezer.h:119
Inline: True
Inline callers:
  - kernel/futex.c:futex_wait_queue_me
```
```
In kernel/audit.c (ffffffff811788e1)
Location: include/linux/freezer.h:119
Inline: True
Inline callers:
  - kernel/audit.c:kauditd_thread
```
```
In mm/oom_kill.c (ffffffff8122fa3c)
Location: include/linux/freezer.h:119
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_reaper
```
```
In mm/compaction.c (ffffffff8125ba79)
Location: include/linux/freezer.h:119
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd
```
```
In mm/ksm.c (ffffffff812a80d1)
Location: include/linux/freezer.h:119
Inline: True
Inline callers:
  - mm/ksm.c:ksm_scan_thread
```
```
In mm/khugepaged.c (ffffffff812c4cd5)
Location: include/linux/freezer.h:119
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
```
```
In fs/coredump.c (ffffffff8136b765)
Location: include/linux/freezer.h:119
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
```
```
In fs/ecryptfs/kthread.c (ffffffff81426abc)
Location: include/linux/freezer.h:119
Inline: True
Inline callers:
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
```
```
In drivers/char/virtio_console.c (ffffffff816d0263)
Location: include/linux/freezer.h:119
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:wait_port_writable
  - drivers/char/virtio_console.c:port_fops_read
```
```
In net/unix/af_unix.c (ffffffff81a4831f)
Location: include/linux/freezer.h:119
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_stream_read_generic
```
</details>
</li>
</ul>

## Differences
