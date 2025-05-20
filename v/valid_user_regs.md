# Function: <code>valid_user_regs</code>

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
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int valid_user_regs(struct user_pt_regs *regs, struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/arm64/kernel/ptrace.c (ffff80001008f000)
Location: arch/arm64/kernel/ptrace.c:1935
Inline: True
Direct callers:
  - arch/arm64/kernel/ptrace.c:compat_gpr_set
  - arch/arm64/kernel/ptrace.c:gpr_set
  - arch/arm64/kernel/signal.c:do_notify_resume
  - arch/arm64/kernel/signal.c:do_notify_resume
  - arch/arm64/kernel/signal.c:restore_sigframe
  - arch/arm64/kernel/signal.c:restore_sigframe
  - arch/arm64/kernel/signal32.c:compat_restore_sigframe
  - arch/arm64/kernel/signal32.c:compat_restore_sigframe
```
**Symbols:**

```
ffff80001008f000-ffff80001008f0fc: valid_user_regs (STB_GLOBAL)
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
In arch/arm/kernel/ptrace.c (c030ca08)
Location: arch/arm/include/asm/ptrace.h:57
Inline: True
Inline callers:
  - arch/arm/kernel/ptrace.c:arch_ptrace
  - arch/arm/kernel/ptrace.c:gpr_set
```
```
In arch/arm/kernel/signal.c (c030ea94)
Location: arch/arm/include/asm/ptrace.h:57
Inline: True
Inline callers:
  - arch/arm/kernel/signal.c:do_work_pending
  - arch/arm/kernel/signal.c:restore_sigframe
```
</details>
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
<b>Arch</b>
<ul>
</ul>
