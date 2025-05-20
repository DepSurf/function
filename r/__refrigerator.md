# Function: <code>__refrigerator</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
bool __refrigerator(bool check_kthr_stop);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/freezer.c (ffffffff810e9b00)
Location: kernel/freezer.c:59
Inline: False
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
  - kernel/freezer.c:set_freezable
  - kernel/time/hrtimer.c:do_nanosleep
  - kernel/futex.c:futex_wait_queue_me
  - kernel/audit.c:kauditd_thread
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/huge_memory.c:khugepaged
  - mm/huge_memory.c:khugepaged
  - mm/huge_memory.c:khugepaged
  - mm/huge_memory.c:khugepaged
  - fs/jbd2/journal.c:kjournald2
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
  - drivers/virtio/virtio_balloon.c:balloon
  - drivers/tty/hvc/hvc_console.c:khvcd
  - drivers/char/virtio_console.c:port_fops_read
  - drivers/char/virtio_console.c:wait_port_writable
  - net/unix/af_unix.c:unix_stream_read_generic
```
**Symbols:**

```
ffffffff810e9b00-ffffffff810e9c40: __refrigerator (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
bool __refrigerator(bool check_kthr_stop);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/freezer.c (ffffffff810f0850)
Location: kernel/freezer.c:59
Inline: False
Direct callers:
  - kernel/fork.c:_do_fork
  - kernel/exit.c:do_exit
  - kernel/signal.c:do_sigtimedwait
  - kernel/signal.c:get_signal
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:ptrace_stop
  - kernel/kmod.c:usermodehelper_read_trylock
  - kernel/kthread.c:kthread_worker_fn
  - kernel/kthread.c:kthread_freezable_should_stop
  - kernel/freezer.c:set_freezable
  - kernel/time/hrtimer.c:do_nanosleep
  - kernel/futex.c:futex_wait_queue_me
  - kernel/audit.c:kauditd_thread
  - mm/oom_kill.c:oom_reaper
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd
  - mm/compaction.c:kcompactd
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - fs/jbd2/journal.c:kjournald2
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
  - drivers/tty/hvc/hvc_console.c:khvcd
  - drivers/char/virtio_console.c:wait_port_writable
  - drivers/char/virtio_console.c:port_fops_read
  - net/unix/af_unix.c:unix_stream_read_generic
```
**Symbols:**

```
ffffffff810f0850-ffffffff810f099c: __refrigerator (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
bool __refrigerator(bool check_kthr_stop);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/freezer.c (ffffffff810f79b0)
Location: kernel/freezer.c:59
Inline: False
Direct callers:
  - kernel/fork.c:_do_fork
  - kernel/exit.c:do_exit
  - kernel/signal.c:do_sigtimedwait
  - kernel/signal.c:get_signal
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:ptrace_stop
  - kernel/kmod.c:usermodehelper_read_trylock
  - kernel/kthread.c:kthread_worker_fn
  - kernel/kthread.c:kthread_freezable_should_stop
  - kernel/freezer.c:set_freezable
  - kernel/time/hrtimer.c:do_nanosleep
  - kernel/futex.c:futex_wait_queue_me
  - kernel/audit.c:kauditd_thread
  - mm/oom_kill.c:oom_reaper
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd
  - mm/compaction.c:kcompactd
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - fs/coredump.c:do_coredump
  - fs/jbd2/journal.c:kjournald2
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
  - drivers/tty/hvc/hvc_console.c:khvcd
  - drivers/char/virtio_console.c:wait_port_writable
  - drivers/char/virtio_console.c:port_fops_read
  - net/unix/af_unix.c:unix_stream_read_generic
```
**Symbols:**

```
ffffffff810f79b0-ffffffff810f7aff: __refrigerator (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
bool __refrigerator(bool check_kthr_stop);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/freezer.c (ffffffff810f9880)
Location: kernel/freezer.c:59
Inline: False
Direct callers:
  - kernel/fork.c:_do_fork
  - kernel/exit.c:do_exit
  - kernel/signal.c:do_sigtimedwait
  - kernel/signal.c:get_signal
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:ptrace_stop
  - kernel/kmod.c:usermodehelper_read_trylock
  - kernel/kthread.c:kthread_worker_fn
  - kernel/kthread.c:kthread_freezable_should_stop
  - kernel/freezer.c:set_freezable
  - kernel/time/hrtimer.c:do_nanosleep
  - kernel/futex.c:futex_wait_queue_me
  - kernel/audit.c:kauditd_thread
  - mm/oom_kill.c:oom_reaper
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd
  - mm/compaction.c:kcompactd
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - fs/coredump.c:do_coredump
  - fs/jbd2/journal.c:kjournald2
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
  - drivers/tty/hvc/hvc_console.c:khvcd
  - drivers/char/virtio_console.c:wait_port_writable
  - drivers/char/virtio_console.c:port_fops_read
  - net/unix/af_unix.c:unix_stream_read_generic
```
**Symbols:**

```
ffffffff810f9880-ffffffff810f99cf: __refrigerator (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
bool __refrigerator(bool check_kthr_stop);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/freezer.c (ffffffff81104330)
Location: kernel/freezer.c:59
Inline: False
Direct callers:
  - kernel/fork.c:_do_fork
  - kernel/exit.c:do_exit
  - kernel/signal.c:do_sigtimedwait
  - kernel/signal.c:get_signal
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:ptrace_stop
  - kernel/umh.c:usermodehelper_read_trylock
  - kernel/kthread.c:kthread_worker_fn
  - kernel/kthread.c:kthread_freezable_should_stop
  - kernel/freezer.c:set_freezable
  - kernel/time/hrtimer.c:do_nanosleep
  - kernel/futex.c:futex_wait_queue_me
  - kernel/audit.c:kauditd_thread
  - mm/oom_kill.c:oom_reaper
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:kswapd
  - mm/compaction.c:kcompactd
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - fs/coredump.c:do_coredump
  - fs/jbd2/journal.c:kjournald2
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
  - drivers/tty/hvc/hvc_console.c:khvcd
  - drivers/char/virtio_console.c:wait_port_writable
  - drivers/char/virtio_console.c:port_fops_read
  - net/unix/af_unix.c:unix_stream_read_generic
```
**Symbols:**

```
ffffffff81104330-ffffffff81104485: __refrigerator (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
bool __refrigerator(bool check_kthr_stop);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/freezer.c (ffffffff8110f130)
Location: kernel/freezer.c:59
Inline: False
Direct callers:
  - kernel/fork.c:_do_fork
  - kernel/exit.c:do_exit
  - kernel/signal.c:get_signal
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:ptrace_stop
  - kernel/umh.c:usermodehelper_read_trylock
  - kernel/kthread.c:kthread_worker_fn
  - kernel/kthread.c:kthread_freezable_should_stop
  - kernel/freezer.c:set_freezable
  - kernel/time/hrtimer.c:do_nanosleep
  - kernel/futex.c:futex_wait_queue_me
  - kernel/audit.c:kauditd_thread
  - mm/oom_kill.c:oom_reaper
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:balance_pgdat
  - mm/compaction.c:kcompactd
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - fs/coredump.c:do_coredump
  - fs/jbd2/journal.c:kjournald2
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
  - drivers/tty/hvc/hvc_console.c:khvcd
  - drivers/char/virtio_console.c:wait_port_writable
  - drivers/char/virtio_console.c:port_fops_read
  - net/unix/af_unix.c:unix_stream_read_generic
```
**Symbols:**

```
ffffffff8110f130-ffffffff8110f285: __refrigerator (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool __refrigerator(bool check_kthr_stop);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/freezer.c (ffffffff8111a770)
Location: kernel/freezer.c:61
Inline: False
Direct callers:
  - kernel/fork.c:_do_fork
  - kernel/exit.c:do_exit
  - kernel/signal.c:get_signal
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:ptrace_stop
  - kernel/umh.c:usermodehelper_read_trylock
  - kernel/kthread.c:kthread_worker_fn
  - kernel/kthread.c:kthread_freezable_should_stop
  - kernel/freezer.c:set_freezable
  - kernel/time/hrtimer.c:do_nanosleep
  - kernel/futex.c:futex_wait_queue_me
  - kernel/audit.c:kauditd_thread
  - mm/oom_kill.c:oom_reaper
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:balance_pgdat
  - mm/compaction.c:kcompactd
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - fs/coredump.c:do_coredump
  - fs/jbd2/journal.c:kjournald2
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
  - drivers/tty/hvc/hvc_console.c:khvcd
  - drivers/char/virtio_console.c:wait_port_writable
  - drivers/char/virtio_console.c:port_fops_read
  - net/unix/af_unix.c:unix_stream_read_generic
```
**Symbols:**

```
ffffffff8111a770-ffffffff8111a8c5: __refrigerator (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool __refrigerator(bool check_kthr_stop);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/freezer.c (ffffffff81124e80)
Location: kernel/freezer.c:62
Inline: False
Direct callers:
  - kernel/fork.c:_do_fork
  - kernel/exit.c:do_exit
  - kernel/signal.c:get_signal
  - kernel/signal.c:get_signal
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:ptrace_stop
  - kernel/umh.c:usermodehelper_read_trylock
  - kernel/kthread.c:kthread_worker_fn
  - kernel/kthread.c:kthread_freezable_should_stop
  - kernel/freezer.c:set_freezable
  - kernel/time/hrtimer.c:do_nanosleep
  - kernel/futex.c:futex_wait_queue_me
  - kernel/audit.c:kauditd_thread
  - mm/oom_kill.c:oom_reaper
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:balance_pgdat
  - mm/compaction.c:kcompactd
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - fs/coredump.c:do_coredump
  - fs/jbd2/journal.c:kjournald2
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
  - drivers/tty/hvc/hvc_console.c:khvcd
  - drivers/char/virtio_console.c:wait_port_writable
  - drivers/char/virtio_console.c:port_fops_read
  - net/unix/af_unix.c:unix_stream_read_generic
```
**Symbols:**

```
ffffffff81124e80-ffffffff81124fcf: __refrigerator (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool __refrigerator(bool check_kthr_stop);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/freezer.c (ffffffff81130e40)
Location: kernel/freezer.c:56
Inline: False
Direct callers:
  - kernel/fork.c:_do_fork
  - kernel/exit.c:do_exit
  - kernel/signal.c:get_signal
  - kernel/signal.c:get_signal
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:ptrace_stop
  - kernel/umh.c:usermodehelper_read_trylock
  - kernel/kthread.c:kthread_worker_fn
  - kernel/kthread.c:kthread_freezable_should_stop
  - kernel/freezer.c:set_freezable
  - kernel/time/hrtimer.c:do_nanosleep
  - kernel/futex.c:futex_wait_queue_me
  - kernel/audit.c:kauditd_thread
  - mm/oom_kill.c:oom_reaper
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:balance_pgdat
  - mm/compaction.c:kcompactd
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - fs/coredump.c:do_coredump
  - fs/jbd2/journal.c:kjournald2
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
  - drivers/tty/hvc/hvc_console.c:khvcd
  - drivers/char/virtio_console.c:wait_port_writable
  - drivers/char/virtio_console.c:port_fops_read
  - net/unix/af_unix.c:unix_stream_read_generic
```
**Symbols:**

```
ffffffff81130e40-ffffffff81130f8f: __refrigerator (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool __refrigerator(bool check_kthr_stop);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/freezer.c (ffffffff81140200)
Location: kernel/freezer.c:56
Inline: False
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
  - kernel/kthread.c:kthread_freezable_should_stop
  - kernel/freezer.c:set_freezable
  - kernel/time/hrtimer.c:do_nanosleep
  - kernel/futex.c:futex_wait_queue_me
  - kernel/audit.c:kauditd_thread
  - mm/oom_kill.c:oom_reaper
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:balance_pgdat
  - mm/compaction.c:kcompactd
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/khugepaged.c:khugepaged_wait_work
  - mm/khugepaged.c:khugepaged_wait_work
  - mm/khugepaged.c:khugepaged_do_scan
  - mm/khugepaged.c:khugepaged_do_scan
  - fs/coredump.c:coredump_wait
  - fs/jbd2/journal.c:kjournald2
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
  - drivers/tty/hvc/hvc_console.c:khvcd
  - drivers/char/virtio_console.c:wait_port_writable
  - drivers/char/virtio_console.c:port_fops_read
  - net/unix/af_unix.c:unix_stream_data_wait
```
**Symbols:**

```
ffffffff81140200-ffffffff81140347: __refrigerator (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool __refrigerator(bool check_kthr_stop);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/freezer.c (ffffffff8113c570)
Location: kernel/freezer.c:56
Inline: False
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
  - kernel/kthread.c:kthread_freezable_should_stop
  - kernel/freezer.c:set_freezable
  - kernel/time/hrtimer.c:do_nanosleep
  - kernel/futex.c:futex_wait_queue_me
  - kernel/audit.c:kauditd_thread
  - mm/oom_kill.c:oom_reaper
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:balance_pgdat
  - mm/compaction.c:kcompactd
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/khugepaged.c:khugepaged_wait_work
  - mm/khugepaged.c:khugepaged_wait_work
  - mm/khugepaged.c:khugepaged_do_scan
  - mm/khugepaged.c:khugepaged_do_scan
  - fs/coredump.c:coredump_wait
  - fs/jbd2/journal.c:kjournald2
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
  - drivers/tty/hvc/hvc_console.c:khvcd
  - drivers/char/virtio_console.c:wait_port_writable
  - drivers/char/virtio_console.c:port_fops_read
  - net/unix/af_unix.c:unix_stream_data_wait
```
**Symbols:**

```
ffffffff8113c570-ffffffff8113c6b7: __refrigerator (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool __refrigerator(bool check_kthr_stop);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/freezer.c (ffffffff8113d7d0)
Location: kernel/freezer.c:56
Inline: False
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
  - kernel/kthread.c:kthread_freezable_should_stop
  - kernel/freezer.c:set_freezable
  - kernel/time/hrtimer.c:do_nanosleep
  - kernel/futex.c:futex_wait_queue_me
  - kernel/audit.c:kauditd_thread
  - mm/oom_kill.c:oom_reaper
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:balance_pgdat
  - mm/compaction.c:kcompactd
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged_wait_work
  - mm/khugepaged.c:khugepaged_wait_work
  - fs/coredump.c:coredump_wait
  - fs/jbd2/journal.c:kjournald2
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
  - drivers/tty/hvc/hvc_console.c:khvcd
  - drivers/char/virtio_console.c:wait_port_writable
  - drivers/char/virtio_console.c:port_fops_read
  - net/unix/af_unix.c:unix_stream_data_wait
```
**Symbols:**

```
ffffffff8113d7d0-ffffffff8113d90e: __refrigerator (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool __refrigerator(bool check_kthr_stop);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/freezer.c (ffffffff81160960)
Location: kernel/freezer.c:56
Inline: False
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
  - kernel/kthread.c:kthread_freezable_should_stop
  - kernel/freezer.c:set_freezable
  - kernel/time/hrtimer.c:do_nanosleep
  - kernel/futex.c:futex_wait_queue_me
  - kernel/audit.c:kauditd_thread
  - mm/oom_kill.c:oom_reaper
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:balance_pgdat
  - mm/compaction.c:kcompactd
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged_wait_work
  - mm/khugepaged.c:khugepaged_wait_work
  - fs/coredump.c:coredump_wait
  - fs/jbd2/journal.c:kjournald2
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
  - drivers/xen/balloon.c:balloon_thread
  - drivers/tty/hvc/hvc_console.c:khvcd
  - drivers/char/virtio_console.c:wait_port_writable
  - drivers/char/virtio_console.c:port_fops_read
  - net/unix/af_unix.c:unix_stream_data_wait
```
**Symbols:**

```
ffffffff81160960-ffffffff81160a85: __refrigerator (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool __refrigerator(bool check_kthr_stop);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/freezer.c (ffffffff811936f0)
Location: kernel/freezer.c:56
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
  - kernel/kthread.c:kthread_freezable_should_stop
  - kernel/freezer.c:set_freezable
  - kernel/time/hrtimer.c:do_nanosleep
  - kernel/futex/waitwake.c:futex_wait_multiple
  - kernel/futex/waitwake.c:futex_wait_queue
  - kernel/audit.c:kauditd_thread
  - mm/oom_kill.c:oom_reaper
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:balance_pgdat
  - mm/compaction.c:kcompactd
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged_wait_work
  - mm/khugepaged.c:khugepaged_wait_work
  - fs/coredump.c:coredump_wait
  - fs/jbd2/journal.c:kjournald2
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
  - drivers/xen/balloon.c:balloon_thread
  - drivers/tty/hvc/hvc_console.c:khvcd
  - drivers/char/virtio_console.c:wait_port_writable
  - drivers/char/virtio_console.c:port_fops_read
  - net/unix/af_unix.c:unix_stream_data_wait
```
**Symbols:**

```
ffffffff811936f0-ffffffff81193805: __refrigerator (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool __refrigerator(bool check_kthr_stop);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/freezer.c (ffffffff811d1070)
Location: kernel/freezer.c:62
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/main.c:ksgxd
  - kernel/signal.c:get_signal
  - kernel/umh.c:usermodehelper_read_trylock
  - kernel/kthread.c:kthread_worker_fn
  - kernel/kthread.c:kthread_freezable_should_stop
  - kernel/freezer.c:set_freezable
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:balance_pgdat
  - mm/ksm.c:ksm_scan_thread
  - mm/khugepaged.c:khugepaged
  - fs/jbd2/journal.c:kjournald2
  - drivers/tty/hvc/hvc_console.c:khvcd
```
**Symbols:**

```
ffffffff811d1070-ffffffff811d1194: __refrigerator (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool __refrigerator(bool check_kthr_stop);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/freezer.c (ffffffff811e52e0)
Location: kernel/freezer.c:62
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/main.c:ksgxd
  - kernel/signal.c:get_signal
  - kernel/umh.c:usermodehelper_read_trylock
  - kernel/kthread.c:kthread_worker_fn
  - kernel/kthread.c:kthread_freezable_should_stop
  - kernel/freezer.c:set_freezable
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:balance_pgdat
  - mm/ksm.c:ksm_scan_thread
  - mm/khugepaged.c:khugepaged
  - fs/jbd2/journal.c:kjournald2
  - drivers/tty/hvc/hvc_console.c:khvcd
```
**Symbols:**

```
ffffffff811e52e0-ffffffff811e5404: __refrigerator (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool __refrigerator(bool check_kthr_stop);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/freezer.c (ffffffff811fb070)
Location: kernel/freezer.c:62
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/main.c:ksgxd
  - kernel/signal.c:get_signal
  - kernel/umh.c:usermodehelper_read_trylock
  - kernel/kthread.c:kthread_worker_fn
  - kernel/kthread.c:kthread_freezable_should_stop
  - kernel/freezer.c:set_freezable
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:balance_pgdat
  - fs/jbd2/journal.c:kjournald2
  - drivers/tty/hvc/hvc_console.c:khvcd
```
**Symbols:**

```
ffffffff811fb070-ffffffff811fb1b5: __refrigerator (STB_GLOBAL)
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
bool __refrigerator(bool check_kthr_stop);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/freezer.c (ffff800010198038)
Location: kernel/freezer.c:56
Inline: False
Direct callers:
  - kernel/fork.c:_do_fork
  - kernel/exit.c:do_exit
  - kernel/signal.c:get_signal
  - kernel/signal.c:get_signal
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:ptrace_stop
  - kernel/umh.c:usermodehelper_read_trylock
  - kernel/kthread.c:kthread_worker_fn
  - kernel/kthread.c:kthread_freezable_should_stop
  - kernel/freezer.c:set_freezable
  - kernel/time/hrtimer.c:do_nanosleep
  - kernel/futex.c:futex_wait_queue_me
  - kernel/audit.c:kauditd_thread
  - mm/oom_kill.c:oom_reaper
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:balance_pgdat
  - mm/compaction.c:kcompactd
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - fs/coredump.c:do_coredump
  - fs/jbd2/journal.c:kjournald2
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
  - drivers/tty/hvc/hvc_console.c:khvcd
  - drivers/char/virtio_console.c:wait_port_writable
  - drivers/char/virtio_console.c:port_fops_read
  - net/unix/af_unix.c:unix_stream_read_generic
```
**Symbols:**

```
ffff800010198038-ffff800010198214: __refrigerator (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool __refrigerator(bool check_kthr_stop);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/freezer.c (c03e3098)
Location: kernel/freezer.c:56
Inline: False
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
  - kernel/kthread.c:kthread_freezable_should_stop
  - kernel/freezer.c:set_freezable
  - kernel/time/hrtimer.c:do_nanosleep
  - kernel/futex.c:futex_wait_queue_me
  - kernel/audit.c:kauditd_thread
  - mm/oom_kill.c:oom_reaper
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:balance_pgdat
  - mm/compaction.c:kcompactd
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - fs/coredump.c:do_coredump
  - fs/jbd2/journal.c:kjournald2
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
  - drivers/tty/hvc/hvc_console.c:khvcd
  - drivers/char/virtio_console.c:wait_port_writable
  - drivers/char/virtio_console.c:port_fops_read
  - net/unix/af_unix.c:unix_stream_read_generic
```
**Symbols:**

```
c03e3098-c03e3250: __refrigerator (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool __refrigerator(bool check_kthr_stop);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/freezer.c (c0000000001f7f20)
Location: kernel/freezer.c:56
Inline: False
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
  - kernel/kthread.c:kthread_freezable_should_stop
  - kernel/freezer.c:set_freezable
  - kernel/time/hrtimer.c:do_nanosleep
  - kernel/futex.c:futex_wait_queue_me
  - kernel/audit.c:kauditd_thread
  - mm/oom_kill.c:oom_reaper
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:balance_pgdat
  - mm/compaction.c:kcompactd
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - fs/coredump.c:do_coredump
  - fs/jbd2/journal.c:kjournald2
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
  - drivers/tty/hvc/hvc_console.c:khvcd
  - drivers/char/virtio_console.c:wait_port_writable
  - drivers/char/virtio_console.c:port_fops_read
  - net/unix/af_unix.c:unix_stream_read_generic
```
**Symbols:**

```
c0000000001f7f20-c0000000001f814c: __refrigerator (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool __refrigerator(bool check_kthr_stop);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/freezer.c (ffffffe000128e00)
Location: kernel/freezer.c:56
Inline: False
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
  - kernel/kthread.c:kthread_freezable_should_stop
  - kernel/freezer.c:set_freezable
  - kernel/time/hrtimer.c:do_nanosleep
  - kernel/futex.c:futex_wait_queue_me
  - kernel/audit.c:kauditd_thread
  - mm/oom_kill.c:oom_reaper
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:balance_pgdat
  - mm/compaction.c:kcompactd
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - fs/coredump.c:do_coredump
  - fs/jbd2/journal.c:kjournald2
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
  - drivers/tty/hvc/hvc_console.c:khvcd
  - drivers/char/virtio_console.c:wait_port_writable
  - drivers/char/virtio_console.c:port_fops_read
  - net/unix/af_unix.c:unix_stream_read_generic
```
**Symbols:**

```
ffffffe000128e00-ffffffe000128f6e: __refrigerator (STB_GLOBAL)
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
bool __refrigerator(bool check_kthr_stop);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/freezer.c (ffffffff811295f0)
Location: kernel/freezer.c:56
Inline: False
Direct callers:
  - kernel/fork.c:_do_fork
  - kernel/exit.c:do_exit
  - kernel/signal.c:get_signal
  - kernel/signal.c:get_signal
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:ptrace_stop
  - kernel/umh.c:usermodehelper_read_trylock
  - kernel/kthread.c:kthread_worker_fn
  - kernel/kthread.c:kthread_freezable_should_stop
  - kernel/freezer.c:set_freezable
  - kernel/time/hrtimer.c:do_nanosleep
  - kernel/futex.c:futex_wait_queue_me
  - kernel/audit.c:kauditd_thread
  - mm/oom_kill.c:oom_reaper
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:balance_pgdat
  - mm/compaction.c:kcompactd
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - fs/coredump.c:do_coredump
  - fs/jbd2/journal.c:kjournald2
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
  - drivers/tty/hvc/hvc_console.c:khvcd
  - drivers/char/virtio_console.c:wait_port_writable
  - drivers/char/virtio_console.c:port_fops_read
  - net/unix/af_unix.c:unix_stream_read_generic
```
**Symbols:**

```
ffffffff811295f0-ffffffff8112973f: __refrigerator (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool __refrigerator(bool check_kthr_stop);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/freezer.c (ffffffff8111be80)
Location: kernel/freezer.c:56
Inline: False
Direct callers:
  - kernel/fork.c:_do_fork
  - kernel/exit.c:do_exit
  - kernel/signal.c:get_signal
  - kernel/signal.c:get_signal
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:ptrace_stop
  - kernel/umh.c:usermodehelper_read_trylock
  - kernel/kthread.c:kthread_worker_fn
  - kernel/kthread.c:kthread_freezable_should_stop
  - kernel/freezer.c:set_freezable
  - kernel/time/hrtimer.c:do_nanosleep
  - kernel/futex.c:futex_wait_queue_me
  - kernel/audit.c:kauditd_thread
  - mm/oom_kill.c:oom_reaper
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:balance_pgdat
  - mm/compaction.c:kcompactd
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - fs/coredump.c:do_coredump
  - fs/jbd2/journal.c:kjournald2
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
  - drivers/tty/hvc/hvc_console.c:khvcd
  - drivers/char/virtio_console.c:wait_port_writable
  - drivers/char/virtio_console.c:port_fops_read
  - net/unix/af_unix.c:unix_stream_read_generic
```
**Symbols:**

```
ffffffff8111be80-ffffffff8111bfc9: __refrigerator (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool __refrigerator(bool check_kthr_stop);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/freezer.c (ffffffff81127310)
Location: kernel/freezer.c:56
Inline: False
Direct callers:
  - kernel/fork.c:_do_fork
  - kernel/exit.c:do_exit
  - kernel/signal.c:get_signal
  - kernel/signal.c:get_signal
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:ptrace_stop
  - kernel/umh.c:usermodehelper_read_trylock
  - kernel/kthread.c:kthread_worker_fn
  - kernel/kthread.c:kthread_freezable_should_stop
  - kernel/freezer.c:set_freezable
  - kernel/time/hrtimer.c:do_nanosleep
  - kernel/futex.c:futex_wait_queue_me
  - kernel/audit.c:kauditd_thread
  - mm/oom_kill.c:oom_reaper
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:balance_pgdat
  - mm/compaction.c:kcompactd
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - fs/coredump.c:do_coredump
  - fs/jbd2/journal.c:kjournald2
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
  - drivers/tty/hvc/hvc_console.c:khvcd
  - drivers/char/virtio_console.c:wait_port_writable
  - drivers/char/virtio_console.c:port_fops_read
  - net/unix/af_unix.c:unix_stream_read_generic
```
**Symbols:**

```
ffffffff81127310-ffffffff8112745f: __refrigerator (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool __refrigerator(bool check_kthr_stop);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/freezer.c (ffffffff81133970)
Location: kernel/freezer.c:56
Inline: False
Direct callers:
  - kernel/fork.c:_do_fork
  - kernel/exit.c:do_exit
  - kernel/signal.c:get_signal
  - kernel/signal.c:get_signal
  - kernel/signal.c:do_signal_stop
  - kernel/signal.c:ptrace_stop
  - kernel/umh.c:usermodehelper_read_trylock
  - kernel/kthread.c:kthread_worker_fn
  - kernel/kthread.c:kthread_freezable_should_stop
  - kernel/freezer.c:set_freezable
  - kernel/time/hrtimer.c:do_nanosleep
  - kernel/futex.c:futex_wait_queue_me
  - kernel/audit.c:kauditd_thread
  - mm/oom_kill.c:oom_reaper
  - mm/vmscan.c:kswapd
  - mm/vmscan.c:balance_pgdat
  - mm/compaction.c:kcompactd
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - fs/coredump.c:do_coredump
  - fs/jbd2/journal.c:kjournald2
  - fs/ecryptfs/kthread.c:ecryptfs_threadfn
  - drivers/tty/hvc/hvc_console.c:khvcd
  - drivers/char/virtio_console.c:wait_port_writable
  - drivers/char/virtio_console.c:port_fops_read
  - net/unix/af_unix.c:unix_stream_read_generic
```
**Symbols:**

```
ffffffff81133970-ffffffff81133aaa: __refrigerator (STB_GLOBAL)
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
