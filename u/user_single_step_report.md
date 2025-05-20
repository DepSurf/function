# Function: <code>user_single_step_report</code>

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
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void user_single_step_report(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ptrace.c (ffffffff81040010)
Location: arch/x86/kernel/ptrace.c:1374
Inline: False
Direct callers:
  - arch/x86/entry/common.c:syscall_slow_exit_work
```
**Symbols:**

```
ffffffff81040010-ffffffff8104005b: user_single_step_report (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void user_single_step_report(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ptrace.c (ffffffff810426a0)
Location: arch/x86/kernel/ptrace.c:1347
Inline: False
Direct callers:
  - arch/x86/entry/common.c:syscall_slow_exit_work
```
**Symbols:**

```
ffffffff810426a0-ffffffff810426eb: user_single_step_report (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void user_single_step_report(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ptrace.c (ffffffff81042e20)
Location: arch/x86/kernel/ptrace.c:1347
Inline: False
Direct callers:
  - arch/x86/entry/common.c:syscall_slow_exit_work
```
**Symbols:**

```
ffffffff81042e20-ffffffff81042e6b: user_single_step_report (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void user_single_step_report(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ptrace.c (ffffffff810463d0)
Location: arch/x86/kernel/ptrace.c:1362
Inline: False
Direct callers:
  - arch/x86/entry/common.c:__syscall_return_slowpath
```
**Symbols:**

```
ffffffff810463d0-ffffffff8104641b: user_single_step_report (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void user_single_step_report(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ptrace.c (ffffffff81045e70)
Location: arch/x86/kernel/ptrace.c:1337
Inline: False
Direct callers:
  - kernel/entry/common.c:syscall_exit_work
```
**Symbols:**

```
ffffffff81045e70-ffffffff81045ebb: user_single_step_report (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void user_single_step_report(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ptrace.c (ffffffff81047890)
Location: arch/x86/kernel/ptrace.c:1367
Inline: False
Direct callers:
  - kernel/entry/common.c:syscall_exit_work
```
**Symbols:**

```
ffffffff81047890-ffffffff810478db: user_single_step_report (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void user_single_step_report(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ptrace.c (ffffffff8104e0f0)
Location: arch/x86/kernel/ptrace.c:1367
Inline: False
Direct callers:
  - kernel/entry/common.c:syscall_exit_work
```
**Symbols:**

```
ffffffff8104e0f0-ffffffff8104e13b: user_single_step_report (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void user_single_step_report(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ptrace.c (ffffffff81059190)
Location: arch/x86/kernel/ptrace.c:1366
Inline: False
Direct callers:
  - kernel/entry/common.c:syscall_exit_work
```
**Symbols:**

```
ffffffff81059190-ffffffff810591e7: user_single_step_report (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void user_single_step_report(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ptrace.c (ffffffff81066ab0)
Location: arch/x86/kernel/ptrace.c:1408
Inline: False
Direct callers:
  - kernel/entry/common.c:syscall_exit_work
```
**Symbols:**

```
ffffffff81066ab0-ffffffff81066b07: user_single_step_report (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void user_single_step_report(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ptrace.c (ffffffff810681e0)
Location: arch/x86/kernel/ptrace.c:1408
Inline: False
Direct callers:
  - kernel/entry/common.c:syscall_exit_work
```
**Symbols:**

```
ffffffff810681e0-ffffffff81068237: user_single_step_report (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void user_single_step_report(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ptrace.c (ffffffff8106f660)
Location: arch/x86/kernel/ptrace.c:1420
Inline: False
Direct callers:
  - kernel/entry/common.c:syscall_exit_work
```
**Symbols:**

```
ffffffff8106f660-ffffffff8106f6b7: user_single_step_report (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/arm64/kernel/ptrace.c (0)
Location: include/linux/ptrace.h:349
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/arm/kernel/ptrace.c (0)
Location: include/linux/ptrace.h:349
Inline: False
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void user_single_step_report(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/powerpc/kernel/traps.c (c00000000002d900)
Location: arch/powerpc/kernel/traps.c:305
Inline: False
Direct callers:
  - arch/powerpc/kernel/ptrace.c:do_syscall_trace_leave
```
**Symbols:**

```
c00000000002d900-c00000000002d944: user_single_step_report (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/riscv/kernel/ptrace.c (0)
Location: include/linux/ptrace.h:349
Inline: True
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
void user_single_step_report(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ptrace.c (ffffffff81042fa0)
Location: arch/x86/kernel/ptrace.c:1347
Inline: False
Direct callers:
  - arch/x86/entry/common.c:syscall_slow_exit_work
```
**Symbols:**

```
ffffffff81042fa0-ffffffff81042feb: user_single_step_report (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void user_single_step_report(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ptrace.c (ffffffff810325b0)
Location: arch/x86/kernel/ptrace.c:1347
Inline: False
Direct callers:
  - arch/x86/entry/common.c:syscall_slow_exit_work
```
**Symbols:**

```
ffffffff810325b0-ffffffff810325fb: user_single_step_report (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void user_single_step_report(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ptrace.c (ffffffff81042de0)
Location: arch/x86/kernel/ptrace.c:1347
Inline: False
Direct callers:
  - arch/x86/entry/common.c:syscall_slow_exit_work
```
**Symbols:**

```
ffffffff81042de0-ffffffff81042e2b: user_single_step_report (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void user_single_step_report(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ptrace.c (ffffffff810441c0)
Location: arch/x86/kernel/ptrace.c:1347
Inline: False
Direct callers:
  - arch/x86/entry/common.c:syscall_slow_exit_work
```
**Symbols:**

```
ffffffff810441c0-ffffffff8104420b: user_single_step_report (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
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
