# Function: <code>force_sig_info_to_task</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int force_sig_info_to_task(struct kernel_siginfo *info, struct task_struct *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810ae2c0)
Location: kernel/signal.c:1304
Inline: False
Direct callers:
  - kernel/signal.c:force_sig_ptrace_errno_trap
  - kernel/signal.c:force_sig_pkuerr
  - kernel/signal.c:force_sig_bnderr
  - kernel/signal.c:force_sig_mceerr
  - kernel/signal.c:force_sig_fault
  - kernel/signal.c:force_sig
```
**Symbols:**

```
ffffffff810ae2c0-ffffffff810ae390: force_sig_info_to_task (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int force_sig_info_to_task(struct kernel_siginfo *info, struct task_struct *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b48d0)
Location: kernel/signal.c:1309
Inline: False
Direct callers:
  - kernel/signal.c:force_sig_ptrace_errno_trap
  - kernel/signal.c:force_sig_pkuerr
  - kernel/signal.c:force_sig_bnderr
  - kernel/signal.c:force_sig_mceerr
  - kernel/signal.c:force_sig_fault
  - kernel/signal.c:force_sig
```
**Symbols:**

```
ffffffff810b48d0-ffffffff810b49a0: force_sig_info_to_task (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int force_sig_info_to_task(struct kernel_siginfo *info, struct task_struct *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810bd680)
Location: kernel/signal.c:1309
Inline: False
Direct callers:
  - kernel/signal.c:force_sig_ptrace_errno_trap
  - kernel/signal.c:force_sig_pkuerr
  - kernel/signal.c:force_sig_bnderr
  - kernel/signal.c:force_sig_mceerr
  - kernel/signal.c:force_sig_fault
  - kernel/signal.c:force_sigsegv
```
**Symbols:**

```
ffffffff810bd680-ffffffff810bd773: force_sig_info_to_task (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int force_sig_info_to_task(struct kernel_siginfo *info, struct task_struct *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b8990)
Location: kernel/signal.c:1310
Inline: False
Direct callers:
  - kernel/signal.c:force_sig_ptrace_errno_trap
  - kernel/signal.c:force_sig_pkuerr
  - kernel/signal.c:force_sig_bnderr
  - kernel/signal.c:force_sig_mceerr
  - kernel/signal.c:force_sig_fault
  - kernel/signal.c:force_sigsegv
```
**Symbols:**

```
ffffffff810b8990-ffffffff810b8a83: force_sig_info_to_task (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int force_sig_info_to_task(struct kernel_siginfo *info, struct task_struct *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b9f10)
Location: kernel/signal.c:1312
Inline: False
Direct callers:
  - kernel/signal.c:force_sig_ptrace_errno_trap
  - kernel/signal.c:force_sig_perf
  - kernel/signal.c:force_sig_pkuerr
  - kernel/signal.c:force_sig_bnderr
  - kernel/signal.c:force_sig_mceerr
  - kernel/signal.c:force_sig_fault
  - kernel/signal.c:force_sigsegv
```
**Symbols:**

```
ffffffff810b9f10-ffffffff810ba002: force_sig_info_to_task (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int force_sig_info_to_task(struct kernel_siginfo *info, struct task_struct *t, enum sig_handler handler);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/signal.c (0)
Location: kernel/signal.c:1319
Inline: False
Direct callers:
  - kernel/signal.c:signal_setup_done
  - kernel/signal.c:force_sig_fault_trapno
  - kernel/signal.c:force_sig_ptrace_errno_trap
  - kernel/signal.c:force_sig_seccomp
  - kernel/signal.c:force_sig_perf
  - kernel/signal.c:force_sig_pkuerr
  - kernel/signal.c:force_sig_bnderr
  - kernel/signal.c:force_sig_mceerr
  - kernel/signal.c:force_sig_fault
  - kernel/signal.c:force_exit_sig
```
**Symbols:**

```
ffffffff810cc520-ffffffff810cc664: force_sig_info_to_task (STB_LOCAL)
ffffffff81ca485d-ffffffff81ca48b3: force_sig_info_to_task.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int force_sig_info_to_task(struct kernel_siginfo *info, struct task_struct *t, enum sig_handler handler);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/signal.c (0)
Location: kernel/signal.c:1320
Inline: False
Direct callers:
  - kernel/signal.c:signal_setup_done
  - kernel/signal.c:signal_setup_done
  - kernel/signal.c:force_sig_fault_trapno
  - kernel/signal.c:force_sig_ptrace_errno_trap
  - kernel/signal.c:force_sig_seccomp
  - kernel/signal.c:force_sig_pkuerr
  - kernel/signal.c:force_sig_bnderr
  - kernel/signal.c:force_sig_mceerr
  - kernel/signal.c:force_sig_fault
  - kernel/signal.c:force_exit_sig
```
**Symbols:**

```
ffffffff810e3780-ffffffff810e391a: force_sig_info_to_task (STB_LOCAL)
ffffffff81e5412e-ffffffff81e5418c: force_sig_info_to_task.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int force_sig_info_to_task(struct kernel_siginfo *info, struct task_struct *t, enum sig_handler handler);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/signal.c (0)
Location: kernel/signal.c:1321
Inline: False
Direct callers:
  - kernel/signal.c:signal_setup_done
  - kernel/signal.c:signal_setup_done
  - kernel/signal.c:force_sig_fault_trapno
  - kernel/signal.c:force_sig_ptrace_errno_trap
  - kernel/signal.c:force_sig_seccomp
  - kernel/signal.c:force_sig_pkuerr
  - kernel/signal.c:force_sig_bnderr
  - kernel/signal.c:force_sig_mceerr
  - kernel/signal.c:force_sig_fault
  - kernel/signal.c:force_exit_sig
```
**Symbols:**

```
ffffffff81103d20-ffffffff81103eba: force_sig_info_to_task (STB_LOCAL)
ffffffff820561e7-ffffffff82056245: force_sig_info_to_task.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int force_sig_info_to_task(struct kernel_siginfo *info, struct task_struct *t, enum sig_handler handler);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/signal.c (0)
Location: kernel/signal.c:1325
Inline: False
Direct callers:
  - kernel/signal.c:signal_setup_done
  - kernel/signal.c:signal_setup_done
  - kernel/signal.c:force_sig_fault_trapno
  - kernel/signal.c:force_sig_ptrace_errno_trap
  - kernel/signal.c:force_sig_seccomp
  - kernel/signal.c:force_sig_pkuerr
  - kernel/signal.c:force_sig_bnderr
  - kernel/signal.c:force_sig_mceerr
  - kernel/signal.c:force_sig_fault
  - kernel/signal.c:force_exit_sig
```
**Symbols:**

```
ffffffff8110ff60-ffffffff81110131: force_sig_info_to_task (STB_LOCAL)
ffffffff820d476e-ffffffff820d47cc: force_sig_info_to_task.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int force_sig_info_to_task(struct kernel_siginfo *info, struct task_struct *t, enum sig_handler handler);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/signal.c (0)
Location: kernel/signal.c:1325
Inline: False
Direct callers:
  - kernel/signal.c:signal_setup_done
  - kernel/signal.c:signal_setup_done
  - kernel/signal.c:force_sig_fault_trapno
  - kernel/signal.c:force_sig_ptrace_errno_trap
  - kernel/signal.c:force_sig_seccomp
  - kernel/signal.c:force_sig_pkuerr
  - kernel/signal.c:force_sig_bnderr
  - kernel/signal.c:force_sig_mceerr
  - kernel/signal.c:force_sig_fault
  - kernel/signal.c:force_exit_sig
```
**Symbols:**

```
ffffffff811198d0-ffffffff81119a82: force_sig_info_to_task (STB_LOCAL)
ffffffff821af667-ffffffff821af6b5: force_sig_info_to_task.cold (STB_LOCAL)
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
int force_sig_info_to_task(struct kernel_siginfo *info, struct task_struct *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffff800010110908)
Location: kernel/signal.c:1309
Inline: False
Direct callers:
  - kernel/signal.c:force_sig_ptrace_errno_trap
  - kernel/signal.c:force_sig_pkuerr
  - kernel/signal.c:force_sig_bnderr
  - kernel/signal.c:force_sig_mceerr
  - kernel/signal.c:force_sig_fault
  - kernel/signal.c:force_sig
```
**Symbols:**

```
ffff800010110908-ffff800010110a3c: force_sig_info_to_task (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int force_sig_info_to_task(struct kernel_siginfo *info, struct task_struct *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (c0368114)
Location: kernel/signal.c:1309
Inline: False
Direct callers:
  - kernel/signal.c:force_sig_ptrace_errno_trap
  - kernel/signal.c:force_sig_pkuerr
  - kernel/signal.c:force_sig_bnderr
  - kernel/signal.c:force_sig_mceerr
  - kernel/signal.c:force_sig_fault
  - kernel/signal.c:force_sig
```
**Symbols:**

```
c0368114-c03681fc: force_sig_info_to_task (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int force_sig_info_to_task(struct kernel_siginfo *info, struct task_struct *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (c0000000001581c0)
Location: kernel/signal.c:1309
Inline: False
Direct callers:
  - kernel/signal.c:force_sig_ptrace_errno_trap
  - kernel/signal.c:force_sig_pkuerr
  - kernel/signal.c:force_sig_bnderr
  - kernel/signal.c:force_sig_mceerr
  - kernel/signal.c:force_sig_fault
  - kernel/signal.c:force_sig
```
**Symbols:**

```
c0000000001581c0-c0000000001582fc: force_sig_info_to_task (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int force_sig_info_to_task(struct kernel_siginfo *info, struct task_struct *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffe0000d058c)
Location: kernel/signal.c:1309
Inline: False
Direct callers:
  - kernel/signal.c:force_sig_ptrace_errno_trap
  - kernel/signal.c:force_sig_pkuerr
  - kernel/signal.c:force_sig_bnderr
  - kernel/signal.c:force_sig_mceerr
  - kernel/signal.c:force_sig_fault_to_task
  - kernel/signal.c:force_sig
```
**Symbols:**

```
ffffffe0000d058c-ffffffe0000d065e: force_sig_info_to_task (STB_LOCAL)
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
int force_sig_info_to_task(struct kernel_siginfo *info, struct task_struct *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810aec40)
Location: kernel/signal.c:1309
Inline: False
Direct callers:
  - kernel/signal.c:force_sig_ptrace_errno_trap
  - kernel/signal.c:force_sig_pkuerr
  - kernel/signal.c:force_sig_bnderr
  - kernel/signal.c:force_sig_mceerr
  - kernel/signal.c:force_sig_fault
  - kernel/signal.c:force_sig
```
**Symbols:**

```
ffffffff810aec40-ffffffff810aed10: force_sig_info_to_task (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int force_sig_info_to_task(struct kernel_siginfo *info, struct task_struct *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8109d590)
Location: kernel/signal.c:1309
Inline: False
Direct callers:
  - kernel/signal.c:force_sig_ptrace_errno_trap
  - kernel/signal.c:force_sig_pkuerr
  - kernel/signal.c:force_sig_bnderr
  - kernel/signal.c:force_sig_mceerr
  - kernel/signal.c:force_sig_fault
  - kernel/signal.c:force_sig
```
**Symbols:**

```
ffffffff8109d590-ffffffff8109d660: force_sig_info_to_task (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int force_sig_info_to_task(struct kernel_siginfo *info, struct task_struct *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810ae1a0)
Location: kernel/signal.c:1309
Inline: False
Direct callers:
  - kernel/signal.c:force_sig_ptrace_errno_trap
  - kernel/signal.c:force_sig_pkuerr
  - kernel/signal.c:force_sig_bnderr
  - kernel/signal.c:force_sig_mceerr
  - kernel/signal.c:force_sig_fault
  - kernel/signal.c:force_sig
```
**Symbols:**

```
ffffffff810ae1a0-ffffffff810ae270: force_sig_info_to_task (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int force_sig_info_to_task(struct kernel_siginfo *info, struct task_struct *t);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b6410)
Location: kernel/signal.c:1309
Inline: False
Direct callers:
  - kernel/signal.c:force_sig_ptrace_errno_trap
  - kernel/signal.c:force_sig_pkuerr
  - kernel/signal.c:force_sig_bnderr
  - kernel/signal.c:force_sig_mceerr
  - kernel/signal.c:force_sig_fault
  - kernel/signal.c:force_sig
```
**Symbols:**

```
ffffffff810b6410-ffffffff810b64e0: force_sig_info_to_task (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<b>Param added. </b>
<code>enum sig_handler handler</code>
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
