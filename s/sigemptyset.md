# Function: <code>sigemptyset</code>

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
In kernel/fork.c (ffffffff8107e9b8)
Location: include/linux/signal.h:147
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
```
```
In kernel/signal.c (ffffffff8108db8d)
Location: include/linux/signal.h:147
Inline: True
Inline callers:
  - kernel/signal.c:flush_sigqueue
  - kernel/signal.c:flush_signal_handlers
  - kernel/signal.c:do_sigtimedwait
  - kernel/signal.c:SyS_signal
```
```
In fs/proc/array.c (ffffffff8127fe60)
Location: include/linux/signal.h:147
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
```
```
In security/selinux/hooks.c (ffffffff813453d0)
Location: include/linux/signal.h:147
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_bprm_committed_creds
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
In kernel/fork.c (ffffffff8108066e)
Location: include/linux/signal.h:162
Inline: True
```
```
In kernel/signal.c (ffffffff8109532d)
Location: include/linux/signal.h:162
Inline: True
Inline callers:
  - kernel/signal.c:SyS_signal
  - kernel/signal.c:do_sigtimedwait
  - kernel/signal.c:flush_signal_handlers
  - kernel/signal.c:flush_sigqueue
```
```
In fs/proc/array.c (ffffffff812aceaa)
Location: include/linux/signal.h:162
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
```
```
In security/selinux/hooks.c (ffffffff8137ac70)
Location: include/linux/signal.h:162
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_bprm_committed_creds
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
In kernel/fork.c (ffffffff81084f7a)
Location: include/linux/signal.h:179
Inline: True
```
```
In kernel/signal.c (ffffffff8109a32d)
Location: include/linux/signal.h:179
Inline: True
Inline callers:
  - kernel/signal.c:SyS_signal
  - kernel/signal.c:do_sigtimedwait
  - kernel/signal.c:flush_signal_handlers
  - kernel/signal.c:flush_sigqueue
```
```
In fs/proc/array.c (ffffffff812c277b)
Location: include/linux/signal.h:179
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
```
```
In security/selinux/hooks.c (ffffffff813910bb)
Location: include/linux/signal.h:179
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_bprm_committed_creds
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
In kernel/fork.c (ffffffff81081e9d)
Location: include/linux/signal.h:157
Inline: True
```
```
In kernel/signal.c (ffffffff810974bd)
Location: include/linux/signal.h:157
Inline: True
Inline callers:
  - kernel/signal.c:SyS_signal
  - kernel/signal.c:do_sigtimedwait
  - kernel/signal.c:flush_signal_handlers
  - kernel/signal.c:__flush_itimer_signals
  - kernel/signal.c:flush_sigqueue
```
```
In fs/proc/array.c (ffffffff812cfa0b)
Location: include/linux/signal.h:157
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
```
```
In security/selinux/hooks.c (ffffffff813a780f)
Location: include/linux/signal.h:157
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_bprm_committed_creds
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
In kernel/fork.c (ffffffff8108871b)
Location: include/linux/signal.h:172
Inline: True
```
```
In kernel/signal.c (ffffffff8109e19d)
Location: include/linux/signal.h:172
Inline: True
Inline callers:
  - kernel/signal.c:SyS_signal
  - kernel/signal.c:do_sigtimedwait
  - kernel/signal.c:flush_signal_handlers
  - kernel/signal.c:__flush_itimer_signals
  - kernel/signal.c:flush_sigqueue
```
```
In fs/proc/array.c (ffffffff812f418d)
Location: include/linux/signal.h:172
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
```
```
In security/selinux/hooks.c (ffffffff813ccfdf)
Location: include/linux/signal.h:172
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_bprm_committed_creds
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
In kernel/fork.c (ffffffff8108c4e8)
Location: include/linux/signal.h:174
Inline: True
```
```
In kernel/signal.c (ffffffff810a2938)
Location: include/linux/signal.h:174
Inline: True
Inline callers:
  - kernel/signal.c:__ia32_sys_signal
  - kernel/signal.c:__x64_sys_signal
  - kernel/signal.c:flush_signal_handlers
  - kernel/signal.c:__flush_itimer_signals
  - kernel/signal.c:flush_sigqueue
```
```
In fs/proc/array.c (ffffffff813214f1)
Location: include/linux/signal.h:174
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
```
```
In security/selinux/hooks.c (ffffffff813fae3e)
Location: include/linux/signal.h:174
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_bprm_committed_creds
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
In kernel/fork.c (ffffffff81093af3)
Location: include/linux/signal.h:182
Inline: True
```
```
In kernel/signal.c (ffffffff810ab508)
Location: include/linux/signal.h:182
Inline: True
Inline callers:
  - kernel/signal.c:__ia32_sys_signal
  - kernel/signal.c:__x64_sys_signal
  - kernel/signal.c:flush_signal_handlers
  - kernel/signal.c:__flush_itimer_signals
  - kernel/signal.c:flush_sigqueue
```
```
In fs/proc/array.c (ffffffff81338601)
Location: include/linux/signal.h:182
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
```
```
In security/selinux/hooks.c (ffffffff81417425)
Location: include/linux/signal.h:182
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_bprm_committed_creds
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
In kernel/fork.c (ffffffff8109826b)
Location: include/linux/signal.h:182
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
```
```
In kernel/signal.c (ffffffff810b0a03)
Location: include/linux/signal.h:182
Inline: True
Inline callers:
  - kernel/signal.c:__ia32_sys_signal
  - kernel/signal.c:__x64_sys_signal
  - kernel/signal.c:flush_signal_handlers
  - kernel/signal.c:__flush_itimer_signals
  - kernel/signal.c:flush_sigqueue
```
```
In fs/proc/array.c (ffffffff81360cc2)
Location: include/linux/signal.h:182
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
```
```
In security/selinux/hooks.c (ffffffff81444ffe)
Location: include/linux/signal.h:182
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_bprm_committed_creds
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
In kernel/fork.c (ffffffff8109e83b)
Location: include/linux/signal.h:182
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
```
```
In kernel/signal.c (ffffffff810b6fd3)
Location: include/linux/signal.h:182
Inline: True
Inline callers:
  - kernel/signal.c:__ia32_sys_signal
  - kernel/signal.c:__x64_sys_signal
  - kernel/signal.c:flush_signal_handlers
  - kernel/signal.c:__flush_itimer_signals
  - kernel/signal.c:flush_sigqueue
```
```
In fs/proc/array.c (ffffffff81378f22)
Location: include/linux/signal.h:182
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
```
```
In security/selinux/hooks.c (ffffffff8145eb6e)
Location: include/linux/signal.h:182
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_bprm_committed_creds
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
In kernel/fork.c (ffffffff810a5f39)
Location: include/linux/signal.h:190
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_signal
```
```
In kernel/signal.c (ffffffff810befc3)
Location: include/linux/signal.h:190
Inline: True
Inline callers:
  - kernel/signal.c:__ia32_sys_signal
  - kernel/signal.c:__x64_sys_signal
  - kernel/signal.c:do_sigtimedwait
  - kernel/signal.c:flush_signal_handlers
  - kernel/signal.c:__flush_itimer_signals
  - kernel/signal.c:flush_signals
  - kernel/signal.c:flush_signals
```
```
In fs/proc/array.c (ffffffff813c2ded)
Location: include/linux/signal.h:190
Inline: True
Inline callers:
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
```
```
In security/selinux/hooks.c (ffffffff814b5c5a)
Location: include/linux/signal.h:190
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_bprm_committed_creds
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
In kernel/fork.c (ffffffff810a1912)
Location: include/linux/signal.h:190
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_signal
```
```
In kernel/signal.c (ffffffff810ba363)
Location: include/linux/signal.h:190
Inline: True
Inline callers:
  - kernel/signal.c:__ia32_sys_signal
  - kernel/signal.c:__x64_sys_signal
  - kernel/signal.c:do_sigtimedwait
  - kernel/signal.c:flush_signal_handlers
  - kernel/signal.c:__flush_itimer_signals
  - kernel/signal.c:flush_signals
  - kernel/signal.c:flush_signals
```
```
In fs/proc/array.c (ffffffff813d4f7d)
Location: include/linux/signal.h:190
Inline: True
Inline callers:
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
```
```
In security/selinux/hooks.c (ffffffff814d393a)
Location: include/linux/signal.h:190
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_bprm_committed_creds
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
In kernel/fork.c (ffffffff810a269a)
Location: include/linux/signal.h:192
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_signal
```
```
In kernel/signal.c (ffffffff810bbb03)
Location: include/linux/signal.h:192
Inline: True
Inline callers:
  - kernel/signal.c:__ia32_sys_signal
  - kernel/signal.c:__x64_sys_signal
  - kernel/signal.c:do_sigtimedwait
  - kernel/signal.c:flush_signal_handlers
  - kernel/signal.c:__flush_itimer_signals
  - kernel/signal.c:flush_signals
  - kernel/signal.c:flush_signals
```
```
In fs/proc/array.c (ffffffff813dbdad)
Location: include/linux/signal.h:192
Inline: True
Inline callers:
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
```
```
In security/selinux/hooks.c (ffffffff814da3ba)
Location: include/linux/signal.h:192
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_bprm_committed_creds
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
In kernel/fork.c (ffffffff810b3d97)
Location: include/linux/signal.h:192
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_signal
```
```
In kernel/signal.c (ffffffff810ce3e3)
Location: include/linux/signal.h:192
Inline: True
Inline callers:
  - kernel/signal.c:__ia32_sys_signal
  - kernel/signal.c:__x64_sys_signal
  - kernel/signal.c:do_sigtimedwait
  - kernel/signal.c:flush_signal_handlers
  - kernel/signal.c:__flush_itimer_signals
  - kernel/signal.c:flush_sigqueue
```
```
In fs/proc/array.c (ffffffff8142c64f)
Location: include/linux/signal.h:192
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
```
```
In security/selinux/hooks.c (ffffffff815332ba)
Location: include/linux/signal.h:192
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_bprm_committed_creds
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
In kernel/fork.c (ffffffff810ca08a)
Location: include/linux/signal.h:191
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_signal
```
```
In kernel/signal.c (ffffffff810e6647)
Location: include/linux/signal.h:191
Inline: True
Inline callers:
  - kernel/signal.c:__ia32_sys_signal
  - kernel/signal.c:__x64_sys_signal
  - kernel/signal.c:do_sigtimedwait
  - kernel/signal.c:flush_signal_handlers
  - kernel/signal.c:__flush_itimer_signals
  - kernel/signal.c:flush_sigqueue
```
```
In fs/proc/array.c (ffffffff814a5eff)
Location: include/linux/signal.h:191
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
```
```
In security/selinux/hooks.c (ffffffff815c563d)
Location: include/linux/signal.h:191
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_bprm_committed_creds
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
In kernel/fork.c (ffffffff810e76f3)
Location: include/linux/signal.h:191
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_signal
```
```
In kernel/signal.c (ffffffff81107287)
Location: include/linux/signal.h:191
Inline: True
Inline callers:
  - kernel/signal.c:__ia32_sys_signal
  - kernel/signal.c:__x64_sys_signal
  - kernel/signal.c:do_sigtimedwait
  - kernel/signal.c:flush_signal_handlers
  - kernel/signal.c:__flush_itimer_signals
  - kernel/signal.c:flush_sigqueue
```
```
In fs/proc/array.c (ffffffff8153b53f)
Location: include/linux/signal.h:191
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
```
```
In security/selinux/hooks.c (ffffffff8167222d)
Location: include/linux/signal.h:191
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_bprm_committed_creds
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
In kernel/fork.c (ffffffff810f3264)
Location: include/linux/signal.h:191
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_signal
```
```
In kernel/signal.c (ffffffff81113577)
Location: include/linux/signal.h:191
Inline: True
Inline callers:
  - kernel/signal.c:__ia32_sys_signal
  - kernel/signal.c:__x64_sys_signal
  - kernel/signal.c:flush_signal_handlers
  - kernel/signal.c:__flush_itimer_signals
  - kernel/signal.c:flush_sigqueue
```
```
In fs/proc/array.c (ffffffff8157386f)
Location: include/linux/signal.h:191
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
```
```
In security/selinux/hooks.c (ffffffff816aa772)
Location: include/linux/signal.h:191
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_bprm_committed_creds
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
In kernel/fork.c (ffffffff810fc614)
Location: include/linux/signal.h:192
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_signal
```
```
In kernel/signal.c (ffffffff8111cf67)
Location: include/linux/signal.h:192
Inline: True
Inline callers:
  - kernel/signal.c:__ia32_sys_signal
  - kernel/signal.c:__x64_sys_signal
  - kernel/signal.c:flush_signal_handlers
  - kernel/signal.c:__flush_itimer_signals
  - kernel/signal.c:flush_sigqueue
```
```
In fs/proc/array.c (ffffffff815ac21b)
Location: include/linux/signal.h:192
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
```
```
In security/selinux/hooks.c (ffffffff816e77c5)
Location: include/linux/signal.h:192
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_bprm_committed_creds
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
In virt/kvm/kvm_main.c (ffff8000100be834)
Location: include/linux/signal.h:182
Inline: True
Inline callers:
  - virt/kvm/kvm_main.c:kvm_sigset_deactivate
```
```
In kernel/fork.c (ffff8000100f3664)
Location: include/linux/signal.h:182
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
```
```
In kernel/signal.c (ffff80001010cd28)
Location: include/linux/signal.h:182
Inline: True
Inline callers:
  - kernel/signal.c:flush_signal_handlers
  - kernel/signal.c:__flush_itimer_signals
  - kernel/signal.c:flush_sigqueue
```
```
In fs/proc/array.c (ffff800010445448)
Location: include/linux/signal.h:182
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
```
```
In security/selinux/hooks.c (ffff800010554148)
Location: include/linux/signal.h:182
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_bprm_committed_creds
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
In kernel/fork.c (c0351c20)
Location: include/linux/signal.h:182
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
```
```
In kernel/signal.c (c0369ce4)
Location: include/linux/signal.h:182
Inline: True
Inline callers:
  - kernel/signal.c:do_sigaction
  - kernel/signal.c:kernel_sigaction
  - kernel/signal.c:do_sigtimedwait
  - kernel/signal.c:flush_signal_handlers
  - kernel/signal.c:__flush_itimer_signals
  - kernel/signal.c:flush_sigqueue
```
```
In fs/proc/array.c (c060a308)
Location: include/linux/signal.h:182
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
```
```
In security/selinux/hooks.c (c0707348)
Location: include/linux/signal.h:182
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_bprm_committed_creds
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
In kernel/fork.c (c0000000001392a0)
Location: include/linux/signal.h:182
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
```
```
In kernel/signal.c (c00000000015b28c)
Location: include/linux/signal.h:182
Inline: True
Inline callers:
  - kernel/signal.c:__se_sys_signal
  - kernel/signal.c:flush_signal_handlers
  - kernel/signal.c:__flush_itimer_signals
  - kernel/signal.c:flush_sigqueue
```
```
In fs/proc/array.c (c00000000055ae1c)
Location: include/linux/signal.h:182
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
```
```
In security/selinux/hooks.c (c0000000006a4288)
Location: include/linux/signal.h:182
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_bprm_committed_creds
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
In kernel/fork.c (ffffffe0000bfcc6)
Location: include/linux/signal.h:182
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
```
```
In kernel/signal.c (ffffffe0000d1548)
Location: include/linux/signal.h:182
Inline: True
Inline callers:
  - kernel/signal.c:__se_sys_rt_sigtimedwait
  - kernel/signal.c:flush_signal_handlers
  - kernel/signal.c:__flush_itimer_signals
  - kernel/signal.c:flush_sigqueue
```
```
In fs/proc/array.c (ffffffe0002db3dc)
Location: include/linux/signal.h:182
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
```
```
In security/selinux/hooks.c (ffffffe0003a9794)
Location: include/linux/signal.h:182
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_bprm_committed_creds
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
In kernel/fork.c (ffffffff8109815b)
Location: include/linux/signal.h:182
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
```
```
In kernel/signal.c (ffffffff810b1343)
Location: include/linux/signal.h:182
Inline: True
Inline callers:
  - kernel/signal.c:__ia32_sys_signal
  - kernel/signal.c:__x64_sys_signal
  - kernel/signal.c:flush_signal_handlers
  - kernel/signal.c:__flush_itimer_signals
  - kernel/signal.c:flush_sigqueue
```
```
In fs/proc/array.c (ffffffff81371502)
Location: include/linux/signal.h:182
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
```
```
In security/selinux/hooks.c (ffffffff8145714e)
Location: include/linux/signal.h:182
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_bprm_committed_creds
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
In kernel/fork.c (ffffffff81086bbb)
Location: include/linux/signal.h:182
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
```
```
In kernel/signal.c (ffffffff8109fc63)
Location: include/linux/signal.h:182
Inline: True
Inline callers:
  - kernel/signal.c:__ia32_sys_signal
  - kernel/signal.c:__x64_sys_signal
  - kernel/signal.c:flush_signal_handlers
  - kernel/signal.c:__flush_itimer_signals
  - kernel/signal.c:flush_sigqueue
```
```
In fs/proc/array.c (ffffffff81361f92)
Location: include/linux/signal.h:182
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
```
```
In security/selinux/hooks.c (ffffffff81447b8e)
Location: include/linux/signal.h:182
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_bprm_committed_creds
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
In kernel/fork.c (ffffffff8109810b)
Location: include/linux/signal.h:182
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
```
```
In kernel/signal.c (ffffffff810b08a3)
Location: include/linux/signal.h:182
Inline: True
Inline callers:
  - kernel/signal.c:__ia32_sys_signal
  - kernel/signal.c:__x64_sys_signal
  - kernel/signal.c:flush_signal_handlers
  - kernel/signal.c:__flush_itimer_signals
  - kernel/signal.c:flush_sigqueue
```
```
In fs/proc/array.c (ffffffff8136efd2)
Location: include/linux/signal.h:182
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
```
```
In security/selinux/hooks.c (ffffffff814531ee)
Location: include/linux/signal.h:182
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_bprm_committed_creds
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
In kernel/fork.c (ffffffff8109fd0b)
Location: include/linux/signal.h:182
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
  - kernel/fork.c:copy_process
```
```
In kernel/signal.c (ffffffff810b8b73)
Location: include/linux/signal.h:182
Inline: True
Inline callers:
  - kernel/signal.c:__ia32_sys_signal
  - kernel/signal.c:__x64_sys_signal
  - kernel/signal.c:flush_signal_handlers
  - kernel/signal.c:__flush_itimer_signals
  - kernel/signal.c:flush_sigqueue
```
```
In fs/proc/array.c (ffffffff81382962)
Location: include/linux/signal.h:182
Inline: True
Inline callers:
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:do_task_stat
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
  - fs/proc/array.c:proc_pid_status
```
```
In security/selinux/hooks.c (ffffffff8146aced)
Location: include/linux/signal.h:182
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_bprm_committed_creds
```
</details>
</li>
</ul>

## Differences
