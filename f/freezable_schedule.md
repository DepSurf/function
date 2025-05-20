# Function: <code>freezable_schedule</code>

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
In kernel/exit.c (ffffffff81083a6b)
Location: include/linux/freezer.h:168
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/signal.c (ffffffff8108ebc9)
Location: include/linux/freezer.h:168
Inline: True
Inline callers:
  - kernel/signal.c:ptrace_stop
  - kernel/signal.c:do_signal_stop
```
```
In kernel/time/hrtimer.c (ffffffff81823691)
Location: include/linux/freezer.h:168
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:do_nanosleep
```
```
In kernel/futex.c (ffffffff811000fd)
Location: include/linux/freezer.h:168
Inline: True
Inline callers:
  - kernel/futex.c:futex_wait_queue_me
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
In kernel/exit.c (ffffffff81086b86)
Location: include/linux/freezer.h:168
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/signal.c (ffffffff81091f0f)
Location: include/linux/freezer.h:168
Inline: True
Inline callers:
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:ptrace_stop
```
```
In kernel/time/hrtimer.c (ffffffff8189e301)
Location: include/linux/freezer.h:168
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:do_nanosleep
```
```
In kernel/futex.c (ffffffff811070ff)
Location: include/linux/freezer.h:168
Inline: True
Inline callers:
  - kernel/futex.c:futex_wait_queue_me
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
In kernel/exit.c (ffffffff8108baef)
Location: include/linux/freezer.h:168
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/signal.c (ffffffff81096ea0)
Location: include/linux/freezer.h:168
Inline: True
Inline callers:
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:ptrace_stop
```
```
In kernel/time/hrtimer.c (ffffffff818d31a2)
Location: include/linux/freezer.h:168
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:do_nanosleep
```
```
In kernel/futex.c (ffffffff8110e8bf)
Location: include/linux/freezer.h:168
Inline: True
Inline callers:
  - kernel/futex.c:futex_wait_queue_me
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
In kernel/exit.c (ffffffff81088ca8)
Location: include/linux/freezer.h:168
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/signal.c (ffffffff810941e2)
Location: include/linux/freezer.h:168
Inline: True
Inline callers:
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:ptrace_stop
```
```
In kernel/time/hrtimer.c (ffffffff8190a325)
Location: include/linux/freezer.h:168
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:do_nanosleep
```
```
In kernel/futex.c (ffffffff8110fdb5)
Location: include/linux/freezer.h:168
Inline: True
Inline callers:
  - kernel/futex.c:futex_wait_queue_me
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
In kernel/exit.c (ffffffff8108f9eb)
Location: include/linux/freezer.h:169
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/signal.c (ffffffff8109b07b)
Location: include/linux/freezer.h:169
Inline: True
Inline callers:
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:ptrace_stop
```
```
In kernel/time/hrtimer.c (ffffffff8199466b)
Location: include/linux/freezer.h:169
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:do_nanosleep
```
```
In kernel/futex.c (ffffffff8111b0a5)
Location: include/linux/freezer.h:169
Inline: True
Inline callers:
  - kernel/futex.c:futex_wait_queue_me
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
In kernel/exit.c (ffffffff8109353a)
Location: include/linux/freezer.h:169
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/signal.c (ffffffff8109efc4)
Location: include/linux/freezer.h:169
Inline: True
Inline callers:
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:ptrace_stop
```
```
In kernel/time/hrtimer.c (ffffffff819f0bf8)
Location: include/linux/freezer.h:169
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:do_nanosleep
```
```
In kernel/futex.c (ffffffff811281ef)
Location: include/linux/freezer.h:169
Inline: True
Inline callers:
  - kernel/futex.c:futex_wait_queue_me
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
In kernel/exit.c (ffffffff8109b7f9)
Location: include/linux/freezer.h:169
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/signal.c (ffffffff810a7286)
Location: include/linux/freezer.h:169
Inline: True
Inline callers:
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:ptrace_stop
```
```
In kernel/time/hrtimer.c (ffffffff81a2bf78)
Location: include/linux/freezer.h:169
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:do_nanosleep
```
```
In kernel/futex.c (ffffffff81133acf)
Location: include/linux/freezer.h:169
Inline: True
Inline callers:
  - kernel/futex.c:futex_wait_queue_me
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
In kernel/exit.c (ffffffff8109fe71)
Location: include/linux/freezer.h:169
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/signal.c (ffffffff810aeff1)
Location: include/linux/freezer.h:169
Inline: True
Inline callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:ptrace_stop
```
```
In kernel/time/hrtimer.c (ffffffff81a9c132)
Location: include/linux/freezer.h:169
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:do_nanosleep
```
```
In kernel/futex.c (ffffffff8113ea2f)
Location: include/linux/freezer.h:169
Inline: True
Inline callers:
  - kernel/futex.c:futex_wait_queue_me
```
```
In kernel/audit.c (ffffffff81168e43)
Location: include/linux/freezer.h:169
Inline: True
Inline callers:
  - kernel/audit.c:kauditd_thread
```
```
In mm/oom_kill.c (ffffffff8121cb49)
Location: include/linux/freezer.h:169
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_reaper
```
```
In mm/compaction.c (ffffffff812478b8)
Location: include/linux/freezer.h:169
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd
```
```
In mm/ksm.c (ffffffff812922a4)
Location: include/linux/freezer.h:169
Inline: True
Inline callers:
  - mm/ksm.c:ksm_scan_thread
```
```
In mm/khugepaged.c (ffffffff812ac6d1)
Location: include/linux/freezer.h:169
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
```
```
In fs/ecryptfs/kthread.c (ffffffff814015e3)
Location: include/linux/freezer.h:169
Inline: True
Inline callers:
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
```
```
In drivers/char/virtio_console.c (ffffffff8169ed95)
Location: include/linux/freezer.h:169
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:wait_port_writable
  - drivers/char/virtio_console.c:port_fops_read
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
In kernel/exit.c (ffffffff810a64ef)
Location: include/linux/freezer.h:169
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/signal.c (ffffffff810b5608)
Location: include/linux/freezer.h:169
Inline: True
Inline callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:ptrace_stop
```
```
In kernel/time/hrtimer.c (ffffffff81ad3a89)
Location: include/linux/freezer.h:169
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:do_nanosleep
```
```
In kernel/futex.c (ffffffff8114a9a4)
Location: include/linux/freezer.h:169
Inline: True
Inline callers:
  - kernel/futex.c:futex_wait_queue_me
```
```
In kernel/audit.c (ffffffff81174ce3)
Location: include/linux/freezer.h:169
Inline: True
Inline callers:
  - kernel/audit.c:kauditd_thread
```
```
In mm/oom_kill.c (ffffffff8122a529)
Location: include/linux/freezer.h:169
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_reaper
```
```
In mm/compaction.c (ffffffff81255d18)
Location: include/linux/freezer.h:169
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd
```
```
In mm/ksm.c (ffffffff812a2024)
Location: include/linux/freezer.h:169
Inline: True
Inline callers:
  - mm/ksm.c:ksm_scan_thread
```
```
In mm/khugepaged.c (ffffffff812bec05)
Location: include/linux/freezer.h:169
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
```
```
In fs/ecryptfs/kthread.c (ffffffff8141b4d3)
Location: include/linux/freezer.h:169
Inline: True
Inline callers:
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
```
```
In drivers/char/virtio_console.c (ffffffff816c1b25)
Location: include/linux/freezer.h:169
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:wait_port_writable
  - drivers/char/virtio_console.c:port_fops_read
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
In kernel/exit.c (ffffffff810adf59)
Location: include/linux/freezer.h:169
Inline: True
Inline callers:
  - kernel/exit.c:exit_mm
```
```
In kernel/signal.c (ffffffff810be2c6)
Location: include/linux/freezer.h:169
Inline: True
Inline callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:ptrace_stop
```
```
In kernel/time/hrtimer.c (ffffffff81bcb9f3)
Location: include/linux/freezer.h:169
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:do_nanosleep
```
```
In kernel/futex.c (ffffffff8115b5c4)
Location: include/linux/freezer.h:169
Inline: True
Inline callers:
  - kernel/futex.c:futex_wait_queue_me
```
```
In kernel/audit.c (ffffffff81186d7a)
Location: include/linux/freezer.h:169
Inline: True
Inline callers:
  - kernel/audit.c:kauditd_thread
```
```
In mm/oom_kill.c (ffffffff812574b9)
Location: include/linux/freezer.h:169
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_reaper
```
```
In mm/compaction.c (ffffffff81284408)
Location: include/linux/freezer.h:169
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd
```
```
In mm/ksm.c (ffffffff812d68dd)
Location: include/linux/freezer.h:169
Inline: True
Inline callers:
  - mm/ksm.c:ksm_scan_thread
```
```
In mm/khugepaged.c (ffffffff812effe8)
Location: include/linux/freezer.h:169
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_wait_work
```
```
In fs/ecryptfs/kthread.c (ffffffff81469fc8)
Location: include/linux/freezer.h:169
Inline: True
Inline callers:
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
```
```
In drivers/char/virtio_console.c (ffffffff8177724a)
Location: include/linux/freezer.h:169
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:wait_port_writable
  - drivers/char/virtio_console.c:port_fops_read
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
In arch/x86/kernel/cpu/sgx/main.c (ffffffff81068f05)
Location: include/linux/freezer.h:169
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:ksgxd
```
```
In kernel/exit.c (ffffffff810a95ea)
Location: include/linux/freezer.h:169
Inline: True
Inline callers:
  - kernel/exit.c:exit_mm
```
```
In kernel/signal.c (ffffffff810b95ba)
Location: include/linux/freezer.h:169
Inline: True
Inline callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:ptrace_stop
```
```
In kernel/time/hrtimer.c (ffffffff81c44873)
Location: include/linux/freezer.h:169
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:do_nanosleep
```
```
In kernel/futex.c (ffffffff811576f4)
Location: include/linux/freezer.h:169
Inline: True
Inline callers:
  - kernel/futex.c:futex_wait_queue_me
```
```
In kernel/audit.c (ffffffff811840ae)
Location: include/linux/freezer.h:169
Inline: True
Inline callers:
  - kernel/audit.c:kauditd_thread
```
```
In mm/oom_kill.c (ffffffff81262099)
Location: include/linux/freezer.h:169
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_reaper
```
```
In mm/ksm.c (ffffffff812e241a)
Location: include/linux/freezer.h:169
Inline: True
Inline callers:
  - mm/ksm.c:ksm_scan_thread
```
```
In mm/khugepaged.c (ffffffff812fb7a8)
Location: include/linux/freezer.h:169
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_wait_work
```
```
In fs/ecryptfs/kthread.c (ffffffff81484a38)
Location: include/linux/freezer.h:169
Inline: True
Inline callers:
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
```
```
In drivers/char/virtio_console.c (ffffffff81791f7a)
Location: include/linux/freezer.h:169
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:wait_port_writable
  - drivers/char/virtio_console.c:port_fops_read
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
In arch/x86/kernel/cpu/sgx/main.c (ffffffff81069025)
Location: include/linux/freezer.h:169
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:ksgxd
```
```
In kernel/exit.c (ffffffff810aa62a)
Location: include/linux/freezer.h:169
Inline: True
Inline callers:
  - kernel/exit.c:exit_mm
```
```
In kernel/signal.c (ffffffff810bad62)
Location: include/linux/freezer.h:169
Inline: True
Inline callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:ptrace_stop
```
```
In kernel/time/hrtimer.c (ffffffff81c37ae3)
Location: include/linux/freezer.h:169
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:do_nanosleep
```
```
In kernel/futex.c (ffffffff81158b43)
Location: include/linux/freezer.h:169
Inline: True
Inline callers:
  - kernel/futex.c:futex_wait_queue_me
```
```
In kernel/audit.c (ffffffff81184fda)
Location: include/linux/freezer.h:169
Inline: True
Inline callers:
  - kernel/audit.c:kauditd_thread
```
```
In mm/oom_kill.c (ffffffff812669df)
Location: include/linux/freezer.h:169
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_reaper
```
```
In mm/ksm.c (ffffffff812e9bac)
Location: include/linux/freezer.h:169
Inline: True
Inline callers:
  - mm/ksm.c:ksm_scan_thread
```
```
In mm/khugepaged.c (ffffffff81302578)
Location: include/linux/freezer.h:169
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_wait_work
```
```
In fs/ecryptfs/kthread.c (ffffffff8148a4e8)
Location: include/linux/freezer.h:169
Inline: True
Inline callers:
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
```
```
In drivers/char/virtio_console.c (ffffffff817749fa)
Location: include/linux/freezer.h:169
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:wait_port_writable
  - drivers/char/virtio_console.c:port_fops_read
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
In arch/x86/kernel/cpu/sgx/main.c (ffffffff810739d7)
Location: include/linux/freezer.h:169
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:ksgxd
```
```
In kernel/exit.c (ffffffff810bc166)
Location: include/linux/freezer.h:169
Inline: True
Inline callers:
  - kernel/exit.c:exit_mm
```
```
In kernel/signal.c (ffffffff810cd5cc)
Location: include/linux/freezer.h:169
Inline: True
Inline callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:ptrace_stop
```
```
In kernel/time/hrtimer.c (ffffffff81d56358)
Location: include/linux/freezer.h:169
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:do_nanosleep
```
```
In kernel/futex.c (ffffffff8117da20)
Location: include/linux/freezer.h:169
Inline: True
Inline callers:
  - kernel/futex.c:futex_wait_queue_me
```
```
In kernel/audit.c (ffffffff811ad3ca)
Location: include/linux/freezer.h:169
Inline: True
Inline callers:
  - kernel/audit.c:kauditd_thread
```
```
In mm/oom_kill.c (ffffffff812a2faf)
Location: include/linux/freezer.h:169
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_reaper
```
```
In mm/ksm.c (ffffffff81331adc)
Location: include/linux/freezer.h:169
Inline: True
Inline callers:
  - mm/ksm.c:ksm_scan_thread
```
```
In mm/khugepaged.c (ffffffff8134c2e8)
Location: include/linux/freezer.h:169
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_wait_work
```
```
In fs/ecryptfs/kthread.c (ffffffff814e1ce8)
Location: include/linux/freezer.h:169
Inline: True
Inline callers:
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
```
```
In drivers/char/virtio_console.c (ffffffff817f9d27)
Location: include/linux/freezer.h:169
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:wait_port_writable
  - drivers/char/virtio_console.c:port_fops_read
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
In arch/x86/kernel/cpu/sgx/main.c (ffffffff81081ec9)
Location: include/linux/freezer.h:169
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:ksgxd
```
```
In kernel/exit.c (ffffffff810d2dc6)
Location: include/linux/freezer.h:169
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/signal.c (ffffffff810e5531)
Location: include/linux/freezer.h:169
Inline: True
Inline callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:do_signal_stop
```
```
In kernel/time/hrtimer.c (ffffffff81f28566)
Location: include/linux/freezer.h:169
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:do_nanosleep
```
```
In kernel/futex/waitwake.c (ffffffff811b7414)
Location: include/linux/freezer.h:169
Inline: True
Inline callers:
  - kernel/futex/waitwake.c:futex_wait_multiple
  - kernel/futex/waitwake.c:futex_wait_queue
```
```
In kernel/audit.c (ffffffff811df0c1)
Location: include/linux/freezer.h:169
Inline: True
Inline callers:
  - kernel/audit.c:kauditd_thread
```
```
In mm/oom_kill.c (ffffffff812fae0f)
Location: include/linux/freezer.h:169
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_reaper
```
```
In mm/ksm.c (ffffffff813a2b42)
Location: include/linux/freezer.h:169
Inline: True
Inline callers:
  - mm/ksm.c:ksm_scan_thread
```
```
In mm/khugepaged.c (ffffffff813c3a2b)
Location: include/linux/freezer.h:169
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_wait_work
```
```
In fs/ecryptfs/kthread.c (ffffffff8156fefd)
Location: include/linux/freezer.h:169
Inline: True
Inline callers:
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
```
```
In drivers/char/virtio_console.c (ffffffff81938819)
Location: include/linux/freezer.h:169
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:wait_port_writable
  - drivers/char/virtio_console.c:port_fops_read
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
In kernel/exit.c (ffff8000100fd46c)
Location: include/linux/freezer.h:169
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/signal.c (ffff800010111754)
Location: include/linux/freezer.h:169
Inline: True
Inline callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:ptrace_stop
```
```
In kernel/time/hrtimer.c (ffff800010da6614)
Location: include/linux/freezer.h:169
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:do_nanosleep
```
```
In kernel/futex.c (ffff8000101b66cc)
Location: include/linux/freezer.h:169
Inline: True
Inline callers:
  - kernel/futex.c:futex_wait_queue_me
```
```
In kernel/audit.c (ffff8000101e9968)
Location: include/linux/freezer.h:169
Inline: True
Inline callers:
  - kernel/audit.c:kauditd_thread
```
```
In mm/oom_kill.c (ffff8000102b8508)
Location: include/linux/freezer.h:169
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_reaper
```
```
In mm/compaction.c (ffff8000102ed298)
Location: include/linux/freezer.h:169
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd
```
```
In mm/ksm.c (ffff800010341874)
Location: include/linux/freezer.h:169
Inline: True
Inline callers:
  - mm/ksm.c:ksm_scan_thread
```
```
In mm/khugepaged.c (ffff800010360034)
Location: include/linux/freezer.h:169
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
```
```
In fs/ecryptfs/kthread.c (ffff8000104fc908)
Location: include/linux/freezer.h:169
Inline: True
Inline callers:
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
```
```
In drivers/char/virtio_console.c (ffff8000108b3e98)
Location: include/linux/freezer.h:169
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:wait_port_writable
  - drivers/char/virtio_console.c:port_fops_read
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
In kernel/exit.c (c035a5c4)
Location: include/linux/freezer.h:169
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/signal.c (c036908c)
Location: include/linux/freezer.h:169
Inline: True
Inline callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:ptrace_stop
```
```
In kernel/time/hrtimer.c (c0e9e39c)
Location: include/linux/freezer.h:169
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:do_nanosleep
```
```
In kernel/futex.c (c04011f0)
Location: include/linux/freezer.h:169
Inline: True
Inline callers:
  - kernel/futex.c:futex_wait_queue_me
```
```
In kernel/audit.c (c042980c)
Location: include/linux/freezer.h:169
Inline: True
Inline callers:
  - kernel/audit.c:kauditd_thread
```
```
In mm/oom_kill.c (c04e4cc8)
Location: include/linux/freezer.h:169
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_reaper
```
```
In mm/compaction.c (c051115c)
Location: include/linux/freezer.h:169
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd
```
```
In mm/ksm.c (c05477f0)
Location: include/linux/freezer.h:169
Inline: True
Inline callers:
  - mm/ksm.c:ksm_scan_thread
```
```
In fs/ecryptfs/kthread.c (c06b9f6c)
Location: include/linux/freezer.h:169
Inline: True
Inline callers:
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
```
```
In drivers/char/virtio_console.c (c09aef70)
Location: include/linux/freezer.h:169
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:wait_port_writable
  - drivers/char/virtio_console.c:port_fops_read
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
In kernel/exit.c (c000000000144330)
Location: include/linux/freezer.h:169
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/signal.c (c0000000001592e0)
Location: include/linux/freezer.h:169
Inline: True
Inline callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:ptrace_stop
```
```
In kernel/time/hrtimer.c (c000000000ee8dc8)
Location: include/linux/freezer.h:169
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:do_nanosleep
```
```
In kernel/futex.c (c00000000021c070)
Location: include/linux/freezer.h:169
Inline: True
Inline callers:
  - kernel/futex.c:futex_wait_queue_me
```
```
In kernel/audit.c (c00000000025a878)
Location: include/linux/freezer.h:169
Inline: True
Inline callers:
  - kernel/audit.c:kauditd_thread
```
```
In mm/oom_kill.c (c000000000370704)
Location: include/linux/freezer.h:169
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_reaper
```
```
In mm/compaction.c (c0000000003b0ee8)
Location: include/linux/freezer.h:169
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd
```
```
In mm/ksm.c (c00000000041ef48)
Location: include/linux/freezer.h:169
Inline: True
Inline callers:
  - mm/ksm.c:ksm_scan_thread
```
```
In mm/khugepaged.c (c00000000044b644)
Location: include/linux/freezer.h:169
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
```
```
In fs/ecryptfs/kthread.c (c00000000063f8bc)
Location: include/linux/freezer.h:169
Inline: True
Inline callers:
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
```
```
In drivers/char/virtio_console.c (c00000000094d700)
Location: include/linux/freezer.h:169
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:wait_port_writable
  - drivers/char/virtio_console.c:port_fops_read
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
In kernel/exit.c (ffffffe0000c5cc2)
Location: include/linux/freezer.h:169
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/signal.c (ffffffe0000d1174)
Location: include/linux/freezer.h:169
Inline: True
Inline callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:ptrace_stop
```
```
In kernel/time/hrtimer.c (ffffffe0008c89fe)
Location: include/linux/freezer.h:169
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:do_nanosleep
```
```
In kernel/futex.c (ffffffe00013cb9e)
Location: include/linux/freezer.h:169
Inline: True
Inline callers:
  - kernel/futex.c:futex_wait_queue_me
```
```
In kernel/audit.c (ffffffe00015e512)
Location: include/linux/freezer.h:169
Inline: True
Inline callers:
  - kernel/audit.c:kauditd_thread
```
```
In mm/oom_kill.c (ffffffe0001dc18c)
Location: include/linux/freezer.h:169
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_reaper
```
```
In mm/compaction.c (ffffffe000201826)
Location: include/linux/freezer.h:169
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd
```
```
In mm/ksm.c (ffffffe000235be8)
Location: include/linux/freezer.h:169
Inline: True
Inline callers:
  - mm/ksm.c:ksm_scan_thread
```
```
In fs/ecryptfs/kthread.c (ffffffe00036aeee)
Location: include/linux/freezer.h:169
Inline: True
Inline callers:
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
```
```
In drivers/char/virtio_console.c (ffffffe000565d2a)
Location: include/linux/freezer.h:169
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:wait_port_writable
  - drivers/char/virtio_console.c:port_fops_read
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
In kernel/exit.c (ffffffff8109fe0f)
Location: include/linux/freezer.h:169
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/signal.c (ffffffff810af978)
Location: include/linux/freezer.h:169
Inline: True
Inline callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:ptrace_stop
```
```
In kernel/time/hrtimer.c (ffffffff81a728f9)
Location: include/linux/freezer.h:169
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:do_nanosleep
```
```
In kernel/futex.c (ffffffff81142fc4)
Location: include/linux/freezer.h:169
Inline: True
Inline callers:
  - kernel/futex.c:futex_wait_queue_me
```
```
In kernel/audit.c (ffffffff8116d303)
Location: include/linux/freezer.h:169
Inline: True
Inline callers:
  - kernel/audit.c:kauditd_thread
```
```
In mm/oom_kill.c (ffffffff81222b79)
Location: include/linux/freezer.h:169
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_reaper
```
```
In mm/compaction.c (ffffffff8124e368)
Location: include/linux/freezer.h:169
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd
```
```
In mm/ksm.c (ffffffff8129a604)
Location: include/linux/freezer.h:169
Inline: True
Inline callers:
  - mm/ksm.c:ksm_scan_thread
```
```
In mm/khugepaged.c (ffffffff812b71e5)
Location: include/linux/freezer.h:169
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
```
```
In fs/ecryptfs/kthread.c (ffffffff81413ab3)
Location: include/linux/freezer.h:169
Inline: True
Inline callers:
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
```
```
In drivers/char/virtio_console.c (ffffffff81687575)
Location: include/linux/freezer.h:169
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:wait_port_writable
  - drivers/char/virtio_console.c:port_fops_read
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
In kernel/exit.c (ffffffff8108e83f)
Location: include/linux/freezer.h:169
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/signal.c (ffffffff8109e298)
Location: include/linux/freezer.h:169
Inline: True
Inline callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:ptrace_stop
```
```
In kernel/time/hrtimer.c (ffffffff81a2ecc9)
Location: include/linux/freezer.h:169
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:do_nanosleep
```
```
In kernel/futex.c (ffffffff81136324)
Location: include/linux/freezer.h:169
Inline: True
Inline callers:
  - kernel/futex.c:futex_wait_queue_me
```
```
In kernel/audit.c (ffffffff811604a3)
Location: include/linux/freezer.h:169
Inline: True
Inline callers:
  - kernel/audit.c:kauditd_thread
```
```
In mm/oom_kill.c (ffffffff81215d29)
Location: include/linux/freezer.h:169
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_reaper
```
```
In mm/compaction.c (ffffffff81241308)
Location: include/linux/freezer.h:169
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd
```
```
In mm/ksm.c (ffffffff8128c1c4)
Location: include/linux/freezer.h:169
Inline: True
Inline callers:
  - mm/ksm.c:ksm_scan_thread
```
```
In mm/khugepaged.c (ffffffff812a83b5)
Location: include/linux/freezer.h:169
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
```
```
In fs/ecryptfs/kthread.c (ffffffff81404533)
Location: include/linux/freezer.h:169
Inline: True
Inline callers:
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
```
```
In drivers/char/virtio_console.c (ffffffff81665165)
Location: include/linux/freezer.h:169
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:wait_port_writable
  - drivers/char/virtio_console.c:port_fops_read
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
In kernel/exit.c (ffffffff8109fdbf)
Location: include/linux/freezer.h:169
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/signal.c (ffffffff810aeed8)
Location: include/linux/freezer.h:169
Inline: True
Inline callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:ptrace_stop
```
```
In kernel/time/hrtimer.c (ffffffff81aded09)
Location: include/linux/freezer.h:169
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:do_nanosleep
```
```
In kernel/futex.c (ffffffff81140e74)
Location: include/linux/freezer.h:169
Inline: True
Inline callers:
  - kernel/futex.c:futex_wait_queue_me
```
```
In kernel/audit.c (ffffffff8116b0d3)
Location: include/linux/freezer.h:169
Inline: True
Inline callers:
  - kernel/audit.c:kauditd_thread
```
```
In mm/oom_kill.c (ffffffff81220919)
Location: include/linux/freezer.h:169
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_reaper
```
```
In mm/compaction.c (ffffffff8124c108)
Location: include/linux/freezer.h:169
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd
```
```
In mm/ksm.c (ffffffff81298414)
Location: include/linux/freezer.h:169
Inline: True
Inline callers:
  - mm/ksm.c:ksm_scan_thread
```
```
In mm/khugepaged.c (ffffffff812b4ff5)
Location: include/linux/freezer.h:169
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
```
```
In fs/ecryptfs/kthread.c (ffffffff81410e33)
Location: include/linux/freezer.h:169
Inline: True
Inline callers:
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
```
```
In drivers/char/virtio_console.c (ffffffff816b58b5)
Location: include/linux/freezer.h:169
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:wait_port_writable
  - drivers/char/virtio_console.c:port_fops_read
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
In kernel/exit.c (ffffffff810a7d2f)
Location: include/linux/freezer.h:169
Inline: True
Inline callers:
  - kernel/exit.c:do_exit
```
```
In kernel/signal.c (ffffffff810b71a7)
Location: include/linux/freezer.h:169
Inline: True
Inline callers:
  - kernel/signal.c:get_signal
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:ptrace_stop
```
```
In kernel/time/hrtimer.c (ffffffff81aeb199)
Location: include/linux/freezer.h:169
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:do_nanosleep
```
```
In kernel/futex.c (ffffffff8114d402)
Location: include/linux/freezer.h:169
Inline: True
Inline callers:
  - kernel/futex.c:futex_wait_queue_me
```
```
In kernel/audit.c (ffffffff811788d5)
Location: include/linux/freezer.h:169
Inline: True
Inline callers:
  - kernel/audit.c:kauditd_thread
```
```
In mm/oom_kill.c (ffffffff8122fa2c)
Location: include/linux/freezer.h:169
Inline: True
Inline callers:
  - mm/oom_kill.c:oom_reaper
```
```
In mm/compaction.c (ffffffff8125ba6c)
Location: include/linux/freezer.h:169
Inline: True
Inline callers:
  - mm/compaction.c:kcompactd
```
```
In mm/ksm.c (ffffffff812a80c3)
Location: include/linux/freezer.h:169
Inline: True
Inline callers:
  - mm/ksm.c:ksm_scan_thread
```
```
In mm/khugepaged.c (ffffffff812c4e20)
Location: include/linux/freezer.h:169
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
```
```
In fs/ecryptfs/kthread.c (ffffffff81426aac)
Location: include/linux/freezer.h:169
Inline: True
Inline callers:
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
```
```
In drivers/char/virtio_console.c (ffffffff816d0256)
Location: include/linux/freezer.h:169
Inline: True
Inline callers:
  - drivers/char/virtio_console.c:wait_port_writable
  - drivers/char/virtio_console.c:port_fops_read
```
</details>
</li>
</ul>

## Differences
