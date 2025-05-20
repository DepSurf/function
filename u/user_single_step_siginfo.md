# Function: <code>user_single_step_siginfo</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void user_single_step_siginfo(struct task_struct *tsk, struct pt_regs *regs, struct siginfo *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ptrace.c (ffffffff8103d320)
Location: arch/x86/kernel/ptrace.c:1429
Inline: False
Direct callers:
  - arch/x86/entry/common.c:tracehook_report_syscall_exit
```
**Symbols:**

```
ffffffff8103d320-ffffffff8103d38a: user_single_step_siginfo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void user_single_step_siginfo(struct task_struct *tsk, struct pt_regs *regs, struct siginfo *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ptrace.c (ffffffff8103d070)
Location: arch/x86/kernel/ptrace.c:1385
Inline: False
Direct callers:
  - arch/x86/entry/common.c:tracehook_report_syscall_exit
```
**Symbols:**

```
ffffffff8103d070-ffffffff8103d0dd: user_single_step_siginfo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void user_single_step_siginfo(struct task_struct *tsk, struct pt_regs *regs, struct siginfo *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ptrace.c (ffffffff8103c960)
Location: arch/x86/kernel/ptrace.c:1385
Inline: False
Direct callers:
  - arch/x86/entry/common.c:tracehook_report_syscall_exit
```
**Symbols:**

```
ffffffff8103c960-ffffffff8103c9cd: user_single_step_siginfo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void user_single_step_siginfo(struct task_struct *tsk, struct pt_regs *regs, struct siginfo *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ptrace.c (ffffffff8103a9a0)
Location: arch/x86/kernel/ptrace.c:1386
Inline: False
Direct callers:
  - arch/x86/entry/common.c:tracehook_report_syscall_exit
```
**Symbols:**

```
ffffffff8103a9a0-ffffffff8103aa0c: user_single_step_siginfo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void user_single_step_siginfo(struct task_struct *tsk, struct pt_regs *regs, struct siginfo *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ptrace.c (ffffffff8103d3d0)
Location: arch/x86/kernel/ptrace.c:1386
Inline: False
Direct callers:
  - arch/x86/entry/common.c:tracehook_report_syscall_exit
```
**Symbols:**

```
ffffffff8103d3d0-ffffffff8103d43c: user_single_step_siginfo (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void user_single_step_siginfo(struct task_struct *tsk, struct pt_regs *regs, struct siginfo *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ptrace.c (ffffffff8103e970)
Location: arch/x86/kernel/ptrace.c:1385
Inline: False
Direct callers:
  - arch/x86/entry/common.c:tracehook_report_syscall_exit
```
**Symbols:**

```
ffffffff8103e970-ffffffff8103e9b4: user_single_step_siginfo (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
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
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
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
</ul>
