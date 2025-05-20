# Function: <code>wait_task_inactive</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
long unsigned int wait_task_inactive(struct task_struct *p, long int match_state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810abf40)
Location: kernel/sched/core.c:1427
Inline: False
Direct callers:
  - kernel/ptrace.c:ptrace_check_attach
  - fs/coredump.c:do_coredump
  - lib/syscall.c:task_current_syscall
  - lib/syscall.c:task_current_syscall
```
**Symbols:**

```
ffffffff810abf40-ffffffff810ac164: wait_task_inactive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
long unsigned int wait_task_inactive(struct task_struct *p, long int match_state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810aebd0)
Location: kernel/sched/core.c:1374
Inline: False
Direct callers:
  - kernel/ptrace.c:ptrace_check_attach
  - fs/coredump.c:do_coredump
  - lib/syscall.c:task_current_syscall
  - lib/syscall.c:task_current_syscall
```
**Symbols:**

```
ffffffff810aebd0-ffffffff810aed55: wait_task_inactive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
long unsigned int wait_task_inactive(struct task_struct *p, long int match_state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810b4d00)
Location: kernel/sched/core.c:1385
Inline: False
Direct callers:
  - kernel/ptrace.c:ptrace_check_attach
  - fs/coredump.c:do_coredump
  - lib/syscall.c:task_current_syscall
  - lib/syscall.c:task_current_syscall
```
**Symbols:**

```
ffffffff810b4d00-ffffffff810b4e88: wait_task_inactive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
long unsigned int wait_task_inactive(struct task_struct *p, long int match_state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810b0df0)
Location: kernel/sched/core.c:1317
Inline: False
Direct callers:
  - kernel/ptrace.c:ptrace_check_attach
  - fs/coredump.c:do_coredump
  - lib/syscall.c:task_current_syscall
  - lib/syscall.c:task_current_syscall
```
**Symbols:**

```
ffffffff810b0df0-ffffffff810b0f83: wait_task_inactive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
long unsigned int wait_task_inactive(struct task_struct *p, long int match_state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810b8240)
Location: kernel/sched/core.c:1336
Inline: False
Direct callers:
  - kernel/ptrace.c:ptrace_check_attach
  - fs/coredump.c:do_coredump
  - lib/syscall.c:task_current_syscall
  - lib/syscall.c:task_current_syscall
```
**Symbols:**

```
ffffffff810b8240-ffffffff810b83cc: wait_task_inactive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
long unsigned int wait_task_inactive(struct task_struct *p, long int match_state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810bfd40)
Location: kernel/sched/core.c:1334
Inline: False
Direct callers:
  - kernel/ptrace.c:ptrace_check_attach
  - kernel/kthread.c:kthread_park
  - fs/coredump.c:do_coredump
  - lib/syscall.c:task_current_syscall
  - lib/syscall.c:task_current_syscall
```
**Symbols:**

```
ffffffff810bfd40-ffffffff810bfec7: wait_task_inactive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
long unsigned int wait_task_inactive(struct task_struct *p, long int match_state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810c90b0)
Location: kernel/sched/core.c:1332
Inline: False
Direct callers:
  - kernel/ptrace.c:ptrace_check_attach
  - kernel/kthread.c:kthread_park
  - fs/coredump.c:do_coredump
  - lib/syscall.c:task_current_syscall
  - lib/syscall.c:task_current_syscall
  - drivers/powercap/idle_inject.c:idle_inject_stop
```
**Symbols:**

```
ffffffff810c90b0-ffffffff810c9237: wait_task_inactive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
long unsigned int wait_task_inactive(struct task_struct *p, long int match_state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810d0c70)
Location: kernel/sched/core.c:1772
Inline: False
Direct callers:
  - kernel/ptrace.c:ptrace_check_attach
  - kernel/kthread.c:kthread_park
  - fs/coredump.c:do_coredump
  - lib/syscall.c:task_current_syscall
  - lib/syscall.c:task_current_syscall
  - drivers/powercap/idle_inject.c:idle_inject_stop
```
**Symbols:**

```
ffffffff810d0c70-ffffffff810d0e0f: wait_task_inactive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long unsigned int wait_task_inactive(struct task_struct *p, long int match_state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810dac20)
Location: kernel/sched/core.c:1892
Inline: False
Direct callers:
  - kernel/ptrace.c:ptrace_check_attach
  - kernel/kthread.c:kthread_park
  - fs/coredump.c:do_coredump
  - lib/syscall.c:task_current_syscall
  - lib/syscall.c:task_current_syscall
  - drivers/powercap/idle_inject.c:idle_inject_stop
```
**Symbols:**

```
ffffffff810dac20-ffffffff810dadbf: wait_task_inactive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long unsigned int wait_task_inactive(struct task_struct *p, long int match_state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810e3ab0)
Location: kernel/sched/core.c:1962
Inline: False
Direct callers:
  - kernel/ptrace.c:ptrace_check_attach
  - kernel/kthread.c:kthread_park
  - fs/coredump.c:coredump_wait
  - lib/syscall.c:task_current_syscall
  - lib/syscall.c:task_current_syscall
  - drivers/powercap/idle_inject.c:idle_inject_stop
```
**Symbols:**

```
ffffffff810e3ab0-ffffffff810e3c4f: wait_task_inactive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long unsigned int wait_task_inactive(struct task_struct *p, long int match_state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810e1500)
Location: kernel/sched/core.c:2588
Inline: False
Direct callers:
  - kernel/ptrace.c:ptrace_check_attach
  - kernel/kthread.c:kthread_park
  - fs/coredump.c:coredump_wait
  - lib/syscall.c:task_current_syscall
  - lib/syscall.c:task_current_syscall
  - drivers/powercap/idle_inject.c:idle_inject_stop
```
**Symbols:**

```
ffffffff810e1500-ffffffff810e169c: wait_task_inactive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long unsigned int wait_task_inactive(struct task_struct *p, long int match_state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810e3310)
Location: kernel/sched/core.c:2609
Inline: False
Direct callers:
  - kernel/ptrace.c:ptrace_check_attach
  - kernel/kthread.c:kthread_park
  - fs/coredump.c:coredump_wait
  - lib/syscall.c:task_current_syscall
  - lib/syscall.c:task_current_syscall
  - drivers/powercap/idle_inject.c:idle_inject_stop
```
**Symbols:**

```
ffffffff810e3310-ffffffff810e34ac: wait_task_inactive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long unsigned int wait_task_inactive(struct task_struct *p, unsigned int match_state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810f9db0)
Location: kernel/sched/core.c:3177
Inline: False
Direct callers:
  - kernel/ptrace.c:ptrace_check_attach
  - kernel/kthread.c:kthread_park
  - kernel/kthread.c:kthread_bind_mask
  - kernel/kthread.c:__kthread_bind
  - fs/coredump.c:coredump_wait
  - lib/syscall.c:task_current_syscall
  - lib/syscall.c:task_current_syscall
  - drivers/powercap/idle_inject.c:idle_inject_stop
```
**Symbols:**

```
ffffffff810f9db0-ffffffff810f9f77: wait_task_inactive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long unsigned int wait_task_inactive(struct task_struct *p, unsigned int match_state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff81116390)
Location: kernel/sched/core.c:3276
Inline: False
Direct callers:
  - kernel/ptrace.c:ptrace_check_attach
  - kernel/kthread.c:kthread_park
  - kernel/kthread.c:kthread_bind_mask
  - kernel/kthread.c:__kthread_bind
  - kernel/smpboot.c:__smpboot_create_thread
  - fs/coredump.c:coredump_wait
  - lib/syscall.c:task_current_syscall
  - lib/syscall.c:task_current_syscall
  - drivers/powercap/idle_inject.c:idle_inject_stop
```
**Symbols:**

```
ffffffff81116390-ffffffff81116558: wait_task_inactive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long unsigned int wait_task_inactive(struct task_struct *p, unsigned int match_state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff8113d870)
Location: kernel/sched/core.c:3332
Inline: False
Direct callers:
  - kernel/ptrace.c:ptrace_check_attach
  - kernel/kthread.c:kthread_park
  - kernel/kthread.c:kthread_bind_mask
  - kernel/kthread.c:__kthread_bind
  - kernel/smpboot.c:__smpboot_create_thread
  - fs/coredump.c:coredump_wait
  - lib/syscall.c:task_current_syscall
  - lib/syscall.c:task_current_syscall
  - drivers/powercap/idle_inject.c:idle_inject_stop
```
**Symbols:**

```
ffffffff8113d870-ffffffff8113da44: wait_task_inactive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long unsigned int wait_task_inactive(struct task_struct *p, unsigned int match_state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff81149f00)
Location: kernel/sched/core.c:2265
Inline: False
Direct callers:
  - kernel/ptrace.c:ptrace_check_attach
  - kernel/kthread.c:kthread_park
  - kernel/kthread.c:kthread_bind_mask
  - kernel/kthread.c:__kthread_bind
  - kernel/smpboot.c:__smpboot_create_thread
  - fs/coredump.c:coredump_wait
  - lib/syscall.c:task_current_syscall
  - lib/syscall.c:task_current_syscall
  - drivers/powercap/idle_inject.c:idle_inject_stop
```
**Symbols:**

```
ffffffff81149f00-ffffffff8114a0bd: wait_task_inactive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long unsigned int wait_task_inactive(struct task_struct *p, unsigned int match_state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff81155a00)
Location: kernel/sched/core.c:2293
Inline: False
Direct callers:
  - kernel/ptrace.c:ptrace_check_attach
  - kernel/kthread.c:kthread_park
  - kernel/kthread.c:kthread_bind_mask
  - kernel/kthread.c:__kthread_bind
  - kernel/smpboot.c:__smpboot_create_thread
  - fs/coredump.c:coredump_wait
  - lib/syscall.c:task_current_syscall
  - lib/syscall.c:task_current_syscall
  - drivers/powercap/idle_inject.c:idle_inject_stop
```
**Symbols:**

```
ffffffff81155a00-ffffffff81155c21: wait_task_inactive (STB_GLOBAL)
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
long unsigned int wait_task_inactive(struct task_struct *p, long int match_state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffff80001013a7f0)
Location: kernel/sched/core.c:1892
Inline: False
Direct callers:
  - kernel/ptrace.c:ptrace_check_attach
  - kernel/kthread.c:kthread_park
  - fs/coredump.c:do_coredump
  - lib/syscall.c:task_current_syscall
  - lib/syscall.c:task_current_syscall
  - drivers/powercap/idle_inject.c:idle_inject_stop
```
**Symbols:**

```
ffff80001013a7f0-ffff80001013a9cc: wait_task_inactive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
long unsigned int wait_task_inactive(struct task_struct *p, long int match_state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (c038a1cc)
Location: kernel/sched/core.c:1892
Inline: False
Direct callers:
  - kernel/ptrace.c:__se_sys_ptrace
  - kernel/kthread.c:kthread_park
  - fs/coredump.c:do_coredump
  - lib/syscall.c:task_current_syscall
  - lib/syscall.c:task_current_syscall
  - drivers/powercap/idle_inject.c:idle_inject_stop
```
**Symbols:**

```
c038a1cc-c038a3fc: wait_task_inactive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long unsigned int wait_task_inactive(struct task_struct *p, long int match_state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (c000000000188180)
Location: kernel/sched/core.c:1892
Inline: False
Direct callers:
  - kernel/ptrace.c:ptrace_check_attach
  - kernel/kthread.c:kthread_park
  - fs/coredump.c:do_coredump
  - lib/syscall.c:task_current_syscall
  - lib/syscall.c:task_current_syscall
  - drivers/powercap/idle_inject.c:idle_inject_stop
```
**Symbols:**

```
c000000000188180-c000000000188448: wait_task_inactive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
long unsigned int wait_task_inactive(struct task_struct *p, long int match_state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffe0000ea012)
Location: kernel/sched/core.c:1892
Inline: False
Direct callers:
  - kernel/ptrace.c:__se_sys_ptrace
  - kernel/kthread.c:kthread_park
  - fs/coredump.c:do_coredump
  - lib/syscall.c:task_current_syscall
  - lib/syscall.c:task_current_syscall
```
**Symbols:**

```
ffffffe0000ea012-ffffffe0000ea19c: wait_task_inactive (STB_GLOBAL)
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
long unsigned int wait_task_inactive(struct task_struct *p, long int match_state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810d50d0)
Location: kernel/sched/core.c:1892
Inline: False
Direct callers:
  - kernel/ptrace.c:ptrace_check_attach
  - kernel/kthread.c:kthread_park
  - fs/coredump.c:do_coredump
  - lib/syscall.c:task_current_syscall
  - lib/syscall.c:task_current_syscall
```
**Symbols:**

```
ffffffff810d50d0-ffffffff810d526f: wait_task_inactive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long unsigned int wait_task_inactive(struct task_struct *p, long int match_state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810c3720)
Location: kernel/sched/core.c:1892
Inline: False
Direct callers:
  - kernel/ptrace.c:ptrace_check_attach
  - kernel/kthread.c:kthread_park
  - fs/coredump.c:do_coredump
  - lib/syscall.c:task_current_syscall
  - lib/syscall.c:task_current_syscall
```
**Symbols:**

```
ffffffff810c3720-ffffffff810c38bf: wait_task_inactive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long unsigned int wait_task_inactive(struct task_struct *p, long int match_state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810d1f10)
Location: kernel/sched/core.c:1892
Inline: False
Direct callers:
  - kernel/ptrace.c:ptrace_check_attach
  - kernel/kthread.c:kthread_park
  - fs/coredump.c:do_coredump
  - lib/syscall.c:task_current_syscall
  - lib/syscall.c:task_current_syscall
  - drivers/powercap/idle_inject.c:idle_inject_stop
```
**Symbols:**

```
ffffffff810d1f10-ffffffff810d20af: wait_task_inactive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long unsigned int wait_task_inactive(struct task_struct *p, long int match_state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810dc950)
Location: kernel/sched/core.c:1892
Inline: False
Direct callers:
  - kernel/kthread.c:kthread_park
  - fs/coredump.c:do_coredump
  - lib/syscall.c:task_current_syscall
  - lib/syscall.c:task_current_syscall
  - drivers/powercap/idle_inject.c:idle_inject_stop
```
**Symbols:**

```
ffffffff810dc950-ffffffff810dcb32: wait_task_inactive (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.13</code> and <code>5.15</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>long int match_state</code> ➡️ <code>unsigned int match_state</code>
</li>
</ul>
</details>
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
