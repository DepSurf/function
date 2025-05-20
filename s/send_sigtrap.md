# Function: <code>send_sigtrap</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void send_sigtrap(struct task_struct *tsk, struct pt_regs *regs, int error_code, int si_code);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ptrace.c (ffffffff8103d390)
Location: arch/x86/kernel/ptrace.c:1436
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:do_debug
```
**Symbols:**

```
ffffffff8103d390-ffffffff8103d424: send_sigtrap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void send_sigtrap(struct task_struct *tsk, struct pt_regs *regs, int error_code, int si_code);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ptrace.c (ffffffff8103d0e0)
Location: arch/x86/kernel/ptrace.c:1392
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:do_debug
```
**Symbols:**

```
ffffffff8103d0e0-ffffffff8103d177: send_sigtrap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void send_sigtrap(struct task_struct *tsk, struct pt_regs *regs, int error_code, int si_code);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ptrace.c (ffffffff8103c9d0)
Location: arch/x86/kernel/ptrace.c:1392
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:do_debug
```
**Symbols:**

```
ffffffff8103c9d0-ffffffff8103ca67: send_sigtrap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void send_sigtrap(struct task_struct *tsk, struct pt_regs *regs, int error_code, int si_code);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ptrace.c (ffffffff8103aa10)
Location: arch/x86/kernel/ptrace.c:1393
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:do_debug
```
**Symbols:**

```
ffffffff8103aa10-ffffffff8103aab5: send_sigtrap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void send_sigtrap(struct task_struct *tsk, struct pt_regs *regs, int error_code, int si_code);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ptrace.c (ffffffff8103d440)
Location: arch/x86/kernel/ptrace.c:1393
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:do_debug
```
**Symbols:**

```
ffffffff8103d440-ffffffff8103d4e5: send_sigtrap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void send_sigtrap(struct task_struct *tsk, struct pt_regs *regs, int error_code, int si_code);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ptrace.c (ffffffff8103e9c0)
Location: arch/x86/kernel/ptrace.c:1392
Inline: False
Direct callers:
  - arch/x86/kernel/traps.c:do_debug
```
**Symbols:**

```
ffffffff8103e9c0-ffffffff8103ea65: send_sigtrap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void send_sigtrap(struct task_struct *tsk, struct pt_regs *regs, int error_code, int si_code);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ptrace.c (ffffffff81040021)
Location: arch/x86/kernel/ptrace.c:1363
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:user_single_step_report
Direct callers:
  - arch/x86/kernel/traps.c:do_debug
```
**Symbols:**

```
ffffffff8103ffc0-ffffffff81040003: send_sigtrap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void send_sigtrap(struct pt_regs *regs, int error_code, int si_code);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ptrace.c (ffffffff810426a5)
Location: arch/x86/kernel/ptrace.c:1335
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:user_single_step_report
Direct callers:
  - arch/x86/kernel/traps.c:do_debug
```
**Symbols:**

```
ffffffff81042650-ffffffff81042697: send_sigtrap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void send_sigtrap(struct pt_regs *regs, int error_code, int si_code);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ptrace.c (ffffffff81042e25)
Location: arch/x86/kernel/ptrace.c:1335
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:user_single_step_report
Direct callers:
  - arch/x86/kernel/traps.c:do_debug
```
**Symbols:**

```
ffffffff81042dd0-ffffffff81042e17: send_sigtrap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void send_sigtrap(struct pt_regs *regs, int error_code, int si_code);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ptrace.c (ffffffff810463d5)
Location: arch/x86/kernel/ptrace.c:1350
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:user_single_step_report
Direct callers:
  - arch/x86/kernel/traps.c:handle_debug
```
**Symbols:**

```
ffffffff81046380-ffffffff810463c7: send_sigtrap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void send_sigtrap(struct pt_regs *regs, int error_code, int si_code);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ptrace.c (ffffffff81045e75)
Location: arch/x86/kernel/ptrace.c:1325
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:user_single_step_report
Direct callers:
  - arch/x86/kernel/traps.c:noist_exc_debug
```
**Symbols:**

```
ffffffff81045e20-ffffffff81045e67: send_sigtrap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void send_sigtrap(struct pt_regs *regs, int error_code, int si_code);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ptrace.c (ffffffff81047895)
Location: arch/x86/kernel/ptrace.c:1355
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:user_single_step_report
Direct callers:
  - arch/x86/kernel/traps.c:noist_exc_debug
```
**Symbols:**

```
ffffffff81047840-ffffffff81047887: send_sigtrap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void send_sigtrap(struct pt_regs *regs, int error_code, int si_code);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ptrace.c (ffffffff8104e0f5)
Location: arch/x86/kernel/ptrace.c:1355
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:user_single_step_report
Direct callers:
  - arch/x86/kernel/traps.c:noist_exc_debug
```
**Symbols:**

```
ffffffff8104e0a0-ffffffff8104e0e7: send_sigtrap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void send_sigtrap(struct pt_regs *regs, int error_code, int si_code);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ptrace.c (ffffffff81059195)
Location: arch/x86/kernel/ptrace.c:1354
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:user_single_step_report
Direct callers:
  - arch/x86/kernel/traps.c:noist_exc_debug
```
**Symbols:**

```
ffffffff81059130-ffffffff81059183: send_sigtrap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void send_sigtrap(struct pt_regs *regs, int error_code, int si_code);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ptrace.c (ffffffff81066ab5)
Location: arch/x86/kernel/ptrace.c:1396
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:user_single_step_report
Direct callers:
  - arch/x86/kernel/traps.c:noist_exc_debug
```
**Symbols:**

```
ffffffff81066a40-ffffffff81066a93: send_sigtrap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void send_sigtrap(struct pt_regs *regs, int error_code, int si_code);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ptrace.c (ffffffff810681e5)
Location: arch/x86/kernel/ptrace.c:1396
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:user_single_step_report
Direct callers:
  - arch/x86/kernel/traps.c:noist_exc_debug
```
**Symbols:**

```
ffffffff81068170-ffffffff810681c3: send_sigtrap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void send_sigtrap(struct pt_regs *regs, int error_code, int si_code);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ptrace.c (ffffffff8106f665)
Location: arch/x86/kernel/ptrace.c:1408
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:user_single_step_report
Direct callers:
  - arch/x86/kernel/traps.c:noist_exc_debug
```
**Symbols:**

```
ffffffff8106f5f0-ffffffff8106f643: send_sigtrap (STB_GLOBAL)
```
</details>
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
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void send_sigtrap(struct pt_regs *regs, int error_code, int si_code);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ptrace.c (ffffffff81042fa5)
Location: arch/x86/kernel/ptrace.c:1335
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:user_single_step_report
Direct callers:
  - arch/x86/kernel/traps.c:do_debug
```
**Symbols:**

```
ffffffff81042f50-ffffffff81042f97: send_sigtrap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void send_sigtrap(struct pt_regs *regs, int error_code, int si_code);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ptrace.c (ffffffff810325b5)
Location: arch/x86/kernel/ptrace.c:1335
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:user_single_step_report
Direct callers:
  - arch/x86/kernel/traps.c:do_debug
```
**Symbols:**

```
ffffffff81032560-ffffffff810325a7: send_sigtrap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void send_sigtrap(struct pt_regs *regs, int error_code, int si_code);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ptrace.c (ffffffff81042de5)
Location: arch/x86/kernel/ptrace.c:1335
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:user_single_step_report
Direct callers:
  - arch/x86/kernel/traps.c:do_debug
```
**Symbols:**

```
ffffffff81042d90-ffffffff81042dd7: send_sigtrap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void send_sigtrap(struct pt_regs *regs, int error_code, int si_code);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/ptrace.c (ffffffff810441c5)
Location: arch/x86/kernel/ptrace.c:1335
Inline: True
Inline callers:
  - arch/x86/kernel/ptrace.c:user_single_step_report
Direct callers:
  - arch/x86/kernel/traps.c:do_debug
```
**Symbols:**

```
ffffffff81044170-ffffffff810441b7: send_sigtrap (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.0</code> and <code>5.3</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct task_struct *tsk</code>
</li>
<li>
<b>Param reordered. </b>
<code>tsk, regs, error_code, si_code</code> ➡️ <code>regs, error_code, si_code</code>
</li>
</ul>
</details>
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
