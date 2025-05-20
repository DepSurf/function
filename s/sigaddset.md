# Function: <code>sigaddset</code>

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
In kernel/fork.c (ffffffff8107f560)
Location: include/linux/signal.h:40
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/signal.c (ffffffff8108ceaf)
Location: include/linux/signal.h:40
Inline: True
Inline callers:
  - kernel/signal.c:__flush_itimer_signals
  - kernel/signal.c:kernel_sigaction
  - kernel/signal.c:complete_signal
  - kernel/signal.c:__send_signal
  - kernel/signal.c:zap_other_threads
  - kernel/signal.c:send_sigqueue
  - kernel/signal.c:signal_setup_done
  - kernel/signal.c:do_sigaction
```
```
In fs/coredump.c (ffffffff8126ebcb)
Location: include/linux/signal.h:40
Inline: True
Inline callers:
  - fs/coredump.c:zap_process
```
```
In fs/proc/array.c (ffffffff8127fe66)
Location: include/linux/signal.h:40
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
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
In kernel/fork.c (ffffffff8108178f)
Location: include/linux/signal.h:55
Inline: True
```
```
In kernel/signal.c (ffffffff81094873)
Location: include/linux/signal.h:55
Inline: True
Inline callers:
  - kernel/signal.c:do_sigaction
  - kernel/signal.c:kernel_sigaction
  - kernel/signal.c:signal_setup_done
  - kernel/signal.c:send_sigqueue
  - kernel/signal.c:zap_other_threads
  - kernel/signal.c:__send_signal
  - kernel/signal.c:complete_signal
  - kernel/signal.c:__flush_itimer_signals
```
```
In fs/coredump.c (ffffffff8129a33b)
Location: include/linux/signal.h:55
Inline: True
Inline callers:
  - fs/coredump.c:zap_process
```
```
In fs/proc/array.c (ffffffff812aceb0)
Location: include/linux/signal.h:55
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
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
In kernel/fork.c (ffffffff810861a9)
Location: include/linux/signal.h:55
Inline: True
```
```
In kernel/signal.c (ffffffff8109987e)
Location: include/linux/signal.h:55
Inline: True
Inline callers:
  - kernel/signal.c:do_sigaction
  - kernel/signal.c:kernel_sigaction
  - kernel/signal.c:signal_setup_done
  - kernel/signal.c:send_sigqueue
  - kernel/signal.c:zap_other_threads
  - kernel/signal.c:__send_signal
  - kernel/signal.c:complete_signal
  - kernel/signal.c:__flush_itimer_signals
```
```
In fs/coredump.c (ffffffff812aeecb)
Location: include/linux/signal.h:55
Inline: True
Inline callers:
  - fs/coredump.c:zap_process
```
```
In fs/proc/array.c (ffffffff812c2781)
Location: include/linux/signal.h:55
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
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
In kernel/fork.c (ffffffff81082b45)
Location: include/linux/signal.h:33
Inline: True
```
```
In kernel/signal.c (ffffffff810968d0)
Location: include/linux/signal.h:33
Inline: True
Inline callers:
  - kernel/signal.c:do_sigaction
  - kernel/signal.c:kernel_sigaction
  - kernel/signal.c:signal_setup_done
  - kernel/signal.c:send_sigqueue
  - kernel/signal.c:zap_other_threads
  - kernel/signal.c:__send_signal
  - kernel/signal.c:complete_signal
  - kernel/signal.c:__flush_itimer_signals
```
```
In fs/coredump.c (ffffffff812bc2fb)
Location: include/linux/signal.h:33
Inline: True
Inline callers:
  - fs/coredump.c:zap_process
```
```
In fs/proc/array.c (ffffffff812cfa11)
Location: include/linux/signal.h:33
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
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
In kernel/fork.c (ffffffff8108994c)
Location: include/linux/signal.h:48
Inline: True
```
```
In kernel/signal.c (ffffffff8109d660)
Location: include/linux/signal.h:48
Inline: True
Inline callers:
  - kernel/signal.c:do_sigaction
  - kernel/signal.c:kernel_sigaction
  - kernel/signal.c:signal_setup_done
  - kernel/signal.c:send_sigqueue
  - kernel/signal.c:zap_other_threads
  - kernel/signal.c:__send_signal
  - kernel/signal.c:complete_signal
  - kernel/signal.c:__flush_itimer_signals
```
```
In fs/coredump.c (ffffffff812dfbf9)
Location: include/linux/signal.h:48
Inline: True
Inline callers:
  - fs/coredump.c:zap_process
```
```
In fs/proc/array.c (ffffffff812f4193)
Location: include/linux/signal.h:48
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
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
In kernel/fork.c (ffffffff8108d477)
Location: include/linux/signal.h:50
Inline: True
```
```
In kernel/signal.c (ffffffff810a2378)
Location: include/linux/signal.h:50
Inline: True
Inline callers:
  - kernel/signal.c:do_sigaction
  - kernel/signal.c:kernel_sigaction
  - kernel/signal.c:signal_setup_done
  - kernel/signal.c:send_sigqueue
  - kernel/signal.c:zap_other_threads
  - kernel/signal.c:__send_signal
  - kernel/signal.c:complete_signal
  - kernel/signal.c:__flush_itimer_signals
```
```
In fs/coredump.c (ffffffff8130be19)
Location: include/linux/signal.h:50
Inline: True
Inline callers:
  - fs/coredump.c:zap_process
```
```
In fs/proc/array.c (ffffffff813215db)
Location: include/linux/signal.h:50
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
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
In kernel/fork.c (ffffffff81095069)
Location: include/linux/signal.h:54
Inline: True
```
```
In kernel/signal.c (ffffffff810aaf06)
Location: include/linux/signal.h:54
Inline: True
Inline callers:
  - kernel/signal.c:do_sigaction
  - kernel/signal.c:kernel_sigaction
  - kernel/signal.c:signal_setup_done
  - kernel/signal.c:send_sigqueue
  - kernel/signal.c:zap_other_threads
  - kernel/signal.c:__send_signal
  - kernel/signal.c:__send_signal
  - kernel/signal.c:complete_signal
  - kernel/signal.c:__flush_itimer_signals
```
```
In fs/coredump.c (ffffffff81321679)
Location: include/linux/signal.h:54
Inline: True
Inline callers:
  - fs/coredump.c:zap_process
```
```
In fs/proc/array.c (ffffffff813386eb)
Location: include/linux/signal.h:54
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
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
In kernel/fork.c (ffffffff81099801)
Location: include/linux/signal.h:54
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/signal.c (ffffffff810b03fe)
Location: include/linux/signal.h:54
Inline: True
Inline callers:
  - kernel/signal.c:do_sigaction
  - kernel/signal.c:kernel_sigaction
  - kernel/signal.c:signal_setup_done
  - kernel/signal.c:send_sigqueue
  - kernel/signal.c:zap_other_threads
  - kernel/signal.c:__send_signal
  - kernel/signal.c:__send_signal
  - kernel/signal.c:complete_signal
  - kernel/signal.c:__flush_itimer_signals
```
```
In fs/coredump.c (ffffffff81348f2b)
Location: include/linux/signal.h:54
Inline: True
Inline callers:
  - fs/coredump.c:zap_process
```
```
In fs/proc/array.c (ffffffff81360da9)
Location: include/linux/signal.h:54
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
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
In kernel/fork.c (ffffffff810a0102)
Location: include/linux/signal.h:54
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/signal.c (ffffffff810b6a0e)
Location: include/linux/signal.h:54
Inline: True
Inline callers:
  - kernel/signal.c:do_sigaction
  - kernel/signal.c:kernel_sigaction
  - kernel/signal.c:signal_setup_done
  - kernel/signal.c:send_sigqueue
  - kernel/signal.c:zap_other_threads
  - kernel/signal.c:__send_signal
  - kernel/signal.c:__send_signal
  - kernel/signal.c:complete_signal
  - kernel/signal.c:__flush_itimer_signals
```
```
In fs/coredump.c (ffffffff813611cb)
Location: include/linux/signal.h:54
Inline: True
Inline callers:
  - fs/coredump.c:zap_process
```
```
In fs/proc/array.c (ffffffff81379009)
Location: include/linux/signal.h:54
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
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
In kernel/fork.c (ffffffff810a6e51)
Location: include/linux/signal.h:62
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/signal.c (ffffffff810bea5e)
Location: include/linux/signal.h:62
Inline: True
Inline callers:
  - kernel/signal.c:do_sigaction
  - kernel/signal.c:kernel_sigaction
  - kernel/signal.c:signal_setup_done
  - kernel/signal.c:send_sigqueue
  - kernel/signal.c:zap_other_threads
  - kernel/signal.c:__send_signal
  - kernel/signal.c:__send_signal
  - kernel/signal.c:complete_signal
  - kernel/signal.c:__flush_itimer_signals
```
```
In fs/coredump.c (ffffffff813a6ffb)
Location: include/linux/signal.h:62
Inline: True
Inline callers:
  - fs/coredump.c:zap_process
```
```
In fs/proc/array.c (ffffffff813c20b7)
Location: include/linux/signal.h:62
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
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
In kernel/fork.c (ffffffff810a2a83)
Location: include/linux/signal.h:62
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/signal.c (ffffffff810b9d9f)
Location: include/linux/signal.h:62
Inline: True
Inline callers:
  - kernel/signal.c:do_sigaction
  - kernel/signal.c:kernel_sigaction
  - kernel/signal.c:signal_setup_done
  - kernel/signal.c:send_sigqueue
  - kernel/signal.c:zap_other_threads
  - kernel/signal.c:__send_signal
  - kernel/signal.c:__send_signal
  - kernel/signal.c:complete_signal
  - kernel/signal.c:__flush_itimer_signals
```
```
In fs/coredump.c (ffffffff813b7d9b)
Location: include/linux/signal.h:62
Inline: True
Inline callers:
  - fs/coredump.c:zap_process
```
```
In fs/proc/array.c (ffffffff813d4206)
Location: include/linux/signal.h:62
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
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
In kernel/fork.c (ffffffff810a377d)
Location: include/linux/signal.h:64
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/signal.c (ffffffff810bb58f)
Location: include/linux/signal.h:64
Inline: True
Inline callers:
  - kernel/signal.c:do_sigaction
  - kernel/signal.c:kernel_sigaction
  - kernel/signal.c:signal_setup_done
  - kernel/signal.c:send_sigqueue
  - kernel/signal.c:zap_other_threads
  - kernel/signal.c:__send_signal
  - kernel/signal.c:__send_signal
  - kernel/signal.c:complete_signal
  - kernel/signal.c:__flush_itimer_signals
```
```
In fs/coredump.c (ffffffff813bee9b)
Location: include/linux/signal.h:64
Inline: True
Inline callers:
  - fs/coredump.c:zap_process
```
```
In fs/proc/array.c (ffffffff813db046)
Location: include/linux/signal.h:64
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
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
In kernel/fork.c (ffffffff810b5103)
Location: include/linux/signal.h:64
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/signal.c (ffffffff810cdee4)
Location: include/linux/signal.h:64
Inline: True
Inline callers:
  - kernel/signal.c:do_sigaction
  - kernel/signal.c:kernel_sigaction
  - kernel/signal.c:signal_setup_done
  - kernel/signal.c:send_sigqueue
  - kernel/signal.c:zap_other_threads
  - kernel/signal.c:__send_signal
  - kernel/signal.c:__send_signal
  - kernel/signal.c:complete_signal
  - kernel/signal.c:__flush_itimer_signals
```
```
In fs/coredump.c (ffffffff8140eccb)
Location: include/linux/signal.h:64
Inline: True
Inline callers:
  - fs/coredump.c:zap_process
```
```
In fs/proc/array.c (ffffffff8142c2dc)
Location: include/linux/signal.h:64
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
In kernel/fork.c (ffffffff810cb2a3)
Location: include/linux/signal.h:64
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/signal.c (ffffffff810e60b4)
Location: include/linux/signal.h:64
Inline: True
Inline callers:
  - kernel/signal.c:do_sigaction
  - kernel/signal.c:kernel_sigaction
  - kernel/signal.c:signal_setup_done
  - kernel/signal.c:send_sigqueue
  - kernel/signal.c:zap_other_threads
  - kernel/signal.c:__send_signal_locked
  - kernel/signal.c:__send_signal_locked
  - kernel/signal.c:complete_signal
  - kernel/signal.c:__flush_itimer_signals
```
```
In fs/coredump.c (ffffffff814847ca)
Location: include/linux/signal.h:64
Inline: True
Inline callers:
  - fs/coredump.c:coredump_wait
```
```
In fs/proc/array.c (ffffffff814a55ac)
Location: include/linux/signal.h:64
Inline: True
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
In kernel/fork.c (ffffffff810e8947)
Location: include/linux/signal.h:64
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/signal.c (ffffffff81106cb4)
Location: include/linux/signal.h:64
Inline: True
Inline callers:
  - kernel/signal.c:do_sigaction
  - kernel/signal.c:kernel_sigaction
  - kernel/signal.c:signal_setup_done
  - kernel/signal.c:send_sigqueue
  - kernel/signal.c:zap_other_threads
  - kernel/signal.c:__send_signal_locked
  - kernel/signal.c:__send_signal_locked
  - kernel/signal.c:complete_signal
  - kernel/signal.c:__flush_itimer_signals
```
```
In fs/coredump.c (ffffffff81517cca)
Location: include/linux/signal.h:64
Inline: True
Inline callers:
  - fs/coredump.c:coredump_wait
```
```
In fs/proc/array.c (ffffffff8153ab7c)
Location: include/linux/signal.h:64
Inline: True
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
In kernel/fork.c (ffffffff810f45c9)
Location: include/linux/signal.h:64
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/signal.c (ffffffff81112fc3)
Location: include/linux/signal.h:64
Inline: True
Inline callers:
  - kernel/signal.c:do_sigaction
  - kernel/signal.c:kernel_sigaction
  - kernel/signal.c:signal_setup_done
  - kernel/signal.c:send_sigqueue
  - kernel/signal.c:zap_other_threads
  - kernel/signal.c:__send_signal_locked
  - kernel/signal.c:__send_signal_locked
  - kernel/signal.c:complete_signal
  - kernel/signal.c:__flush_itimer_signals
```
```
In fs/coredump.c (ffffffff8154f5bd)
Location: include/linux/signal.h:64
Inline: True
Inline callers:
  - fs/coredump.c:coredump_wait
```
```
In fs/proc/array.c (ffffffff81572e73)
Location: include/linux/signal.h:64
Inline: True
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
In kernel/fork.c (ffffffff810fd964)
Location: include/linux/signal.h:65
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/signal.c (ffffffff8111c9b3)
Location: include/linux/signal.h:65
Inline: True
Inline callers:
  - kernel/signal.c:do_sigaction
  - kernel/signal.c:kernel_sigaction
  - kernel/signal.c:signal_setup_done
  - kernel/signal.c:send_sigqueue
  - kernel/signal.c:zap_other_threads
  - kernel/signal.c:__send_signal_locked
  - kernel/signal.c:__send_signal_locked
  - kernel/signal.c:complete_signal
  - kernel/signal.c:__flush_itimer_signals
```
```
In fs/coredump.c (ffffffff815853fd)
Location: include/linux/signal.h:65
Inline: True
Inline callers:
  - fs/coredump.c:coredump_wait
```
```
In fs/proc/array.c (ffffffff815ab823)
Location: include/linux/signal.h:65
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
In kernel/fork.c (ffff8000100f49b8)
Location: include/linux/signal.h:54
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/signal.c (ffff800010112b80)
Location: include/linux/signal.h:54
Inline: True
Inline callers:
  - kernel/signal.c:do_sigaction
  - kernel/signal.c:kernel_sigaction
  - kernel/signal.c:signal_setup_done
  - kernel/signal.c:send_sigqueue
  - kernel/signal.c:zap_other_threads
  - kernel/signal.c:__send_signal
  - kernel/signal.c:__send_signal
  - kernel/signal.c:complete_signal
  - kernel/signal.c:__flush_itimer_signals
```
```
In fs/coredump.c (ffff800010427764)
Location: include/linux/signal.h:54
Inline: True
Inline callers:
  - fs/coredump.c:zap_process
```
```
In fs/proc/array.c (ffff800010445500)
Location: include/linux/signal.h:54
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
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
In kernel/fork.c (c035317c)
Location: include/linux/signal.h:54
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/signal.c (c0369d00)
Location: include/linux/signal.h:54
Inline: True
Inline callers:
  - kernel/signal.c:do_sigaction
  - kernel/signal.c:kernel_sigaction
  - kernel/signal.c:signal_setup_done
  - kernel/signal.c:send_sigqueue
  - kernel/signal.c:zap_other_threads
  - kernel/signal.c:__send_signal
  - kernel/signal.c:__send_signal
  - kernel/signal.c:complete_signal
  - kernel/signal.c:__flush_itimer_signals
```
```
In fs/coredump.c (c05f0318)
Location: include/linux/signal.h:54
Inline: True
Inline callers:
  - fs/coredump.c:zap_process
```
```
In fs/proc/array.c (c0609810)
Location: include/linux/signal.h:54
Inline: True
Inline callers:
  - fs/proc/array.c:collect_sigign_sigcatch
  - fs/proc/array.c:collect_sigign_sigcatch
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
In kernel/fork.c (c00000000013a8dc)
Location: include/linux/signal.h:54
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/signal.c (c00000000015a680)
Location: include/linux/signal.h:54
Inline: True
Inline callers:
  - kernel/signal.c:do_sigaction
  - kernel/signal.c:kernel_sigaction
  - kernel/signal.c:signal_setup_done
  - kernel/signal.c:send_sigqueue
  - kernel/signal.c:zap_other_threads
  - kernel/signal.c:__send_signal
  - kernel/signal.c:__send_signal
  - kernel/signal.c:complete_signal
  - kernel/signal.c:__flush_itimer_signals
```
```
In fs/coredump.c (c000000000537458)
Location: include/linux/signal.h:54
Inline: True
Inline callers:
  - fs/coredump.c:zap_process
```
```
In fs/proc/array.c (c00000000055aee8)
Location: include/linux/signal.h:54
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
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
In kernel/fork.c (ffffffe0000c0e1e)
Location: include/linux/signal.h:54
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/signal.c (ffffffe0000d1b6a)
Location: include/linux/signal.h:54
Inline: True
Inline callers:
  - kernel/signal.c:do_sigaction
  - kernel/signal.c:kernel_sigaction
  - kernel/signal.c:signal_setup_done
  - kernel/signal.c:send_sigqueue
  - kernel/signal.c:zap_other_threads
  - kernel/signal.c:__send_signal
  - kernel/signal.c:__send_signal
  - kernel/signal.c:complete_signal
  - kernel/signal.c:__flush_itimer_signals
```
```
In fs/coredump.c (ffffffe0002c5c6c)
Location: include/linux/signal.h:54
Inline: True
Inline callers:
  - fs/coredump.c:zap_process
```
```
In fs/proc/array.c (ffffffe0002db47c)
Location: include/linux/signal.h:54
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
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
In kernel/fork.c (ffffffff81099a22)
Location: include/linux/signal.h:54
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/signal.c (ffffffff810b0d7e)
Location: include/linux/signal.h:54
Inline: True
Inline callers:
  - kernel/signal.c:do_sigaction
  - kernel/signal.c:kernel_sigaction
  - kernel/signal.c:signal_setup_done
  - kernel/signal.c:send_sigqueue
  - kernel/signal.c:zap_other_threads
  - kernel/signal.c:__send_signal
  - kernel/signal.c:__send_signal
  - kernel/signal.c:complete_signal
  - kernel/signal.c:__flush_itimer_signals
```
```
In fs/coredump.c (ffffffff813597ab)
Location: include/linux/signal.h:54
Inline: True
Inline callers:
  - fs/coredump.c:zap_process
```
```
In fs/proc/array.c (ffffffff813715e9)
Location: include/linux/signal.h:54
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
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
In kernel/fork.c (ffffffff81088464)
Location: include/linux/signal.h:54
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/signal.c (ffffffff8109f698)
Location: include/linux/signal.h:54
Inline: True
Inline callers:
  - kernel/signal.c:do_sigaction
  - kernel/signal.c:kernel_sigaction
  - kernel/signal.c:signal_setup_done
  - kernel/signal.c:send_sigqueue
  - kernel/signal.c:zap_other_threads
  - kernel/signal.c:__send_signal
  - kernel/signal.c:__send_signal
  - kernel/signal.c:complete_signal
  - kernel/signal.c:__flush_itimer_signals
```
```
In fs/coredump.c (ffffffff8134a45b)
Location: include/linux/signal.h:54
Inline: True
Inline callers:
  - fs/coredump.c:zap_process
```
```
In fs/proc/array.c (ffffffff81362079)
Location: include/linux/signal.h:54
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
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
In kernel/fork.c (ffffffff810999d2)
Location: include/linux/signal.h:54
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/signal.c (ffffffff810b02de)
Location: include/linux/signal.h:54
Inline: True
Inline callers:
  - kernel/signal.c:do_sigaction
  - kernel/signal.c:kernel_sigaction
  - kernel/signal.c:signal_setup_done
  - kernel/signal.c:send_sigqueue
  - kernel/signal.c:zap_other_threads
  - kernel/signal.c:__send_signal
  - kernel/signal.c:__send_signal
  - kernel/signal.c:complete_signal
  - kernel/signal.c:__flush_itimer_signals
```
```
In fs/coredump.c (ffffffff8135727b)
Location: include/linux/signal.h:54
Inline: True
Inline callers:
  - fs/coredump.c:zap_process
```
```
In fs/proc/array.c (ffffffff8136f0b9)
Location: include/linux/signal.h:54
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
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
In kernel/fork.c (ffffffff810a12fb)
Location: include/linux/signal.h:54
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
```
In kernel/signal.c (ffffffff810b85a5)
Location: include/linux/signal.h:54
Inline: True
Inline callers:
  - kernel/signal.c:do_sigaction
  - kernel/signal.c:kernel_sigaction
  - kernel/signal.c:signal_setup_done
  - kernel/signal.c:send_sigqueue
  - kernel/signal.c:zap_other_threads
  - kernel/signal.c:__send_signal
  - kernel/signal.c:__send_signal
  - kernel/signal.c:complete_signal
  - kernel/signal.c:__flush_itimer_signals
```
```
In fs/coredump.c (ffffffff8136a95b)
Location: include/linux/signal.h:54
Inline: True
Inline callers:
  - fs/coredump.c:zap_process
```
```
In fs/proc/array.c (ffffffff81382a49)
Location: include/linux/signal.h:54
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
```
</details>
</li>
</ul>

## Differences
