# Function: <code>syscall_trace_enter</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
long int syscall_trace_enter(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/entry/common.c (ffffffff81003b90)
Location: arch/x86/entry/common.c:211
Inline: False
Direct callers:
  - arch/x86/entry/common.c:do_syscall_32_irqs_off
  - arch/x86/entry/common.c:do_fast_syscall_32
```
**Symbols:**

```
ffffffff81003b90-ffffffff81003bea: syscall_trace_enter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
long int syscall_trace_enter(struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/entry/common.c (ffffffff810032e0)
Location: arch/x86/entry/common.c:70
Inline: False
Direct callers:
  - arch/x86/entry/common.c:do_fast_syscall_32
  - arch/x86/entry/common.c:do_int80_syscall_32
  - arch/x86/entry/common.c:do_syscall_64
```
**Symbols:**

```
ffffffff810032e0-ffffffff810035c9: syscall_trace_enter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
long int syscall_trace_enter(struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/entry/common.c (ffffffff810032c0)
Location: arch/x86/entry/common.c:63
Inline: False
Direct callers:
  - arch/x86/entry/common.c:do_fast_syscall_32
  - arch/x86/entry/common.c:do_int80_syscall_32
  - arch/x86/entry/common.c:do_syscall_64
```
**Symbols:**

```
ffffffff810032c0-ffffffff8100359d: syscall_trace_enter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
long int syscall_trace_enter(struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/entry/common.c (ffffffff81003170)
Location: arch/x86/entry/common.c:65
Inline: False
Direct callers:
  - arch/x86/entry/common.c:do_fast_syscall_32
  - arch/x86/entry/common.c:do_int80_syscall_32
  - arch/x86/entry/common.c:do_syscall_64
```
**Symbols:**

```
ffffffff81003170-ffffffff8100342f: syscall_trace_enter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
long int syscall_trace_enter(struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/entry/common.c (ffffffff810030c0)
Location: arch/x86/entry/common.c:67
Inline: False
Direct callers:
  - arch/x86/entry/common.c:do_fast_syscall_32
  - arch/x86/entry/common.c:do_int80_syscall_32
  - arch/x86/entry/common.c:do_syscall_64
```
**Symbols:**

```
ffffffff810030c0-ffffffff8100338b: syscall_trace_enter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
long int syscall_trace_enter(struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/entry/common.c (ffffffff810038a0)
Location: arch/x86/entry/common.c:67
Inline: False
Direct callers:
  - arch/x86/entry/common.c:do_fast_syscall_32
  - arch/x86/entry/common.c:do_int80_syscall_32
  - arch/x86/entry/common.c:do_syscall_64
```
**Symbols:**

```
ffffffff810038a0-ffffffff81003b52: syscall_trace_enter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
long int syscall_trace_enter(struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/entry/common.c (ffffffff81003d60)
Location: arch/x86/entry/common.c:67
Inline: False
Direct callers:
  - arch/x86/entry/common.c:do_fast_syscall_32
  - arch/x86/entry/common.c:do_int80_syscall_32
  - arch/x86/entry/common.c:do_syscall_64
```
**Symbols:**

```
ffffffff81003d60-ffffffff81004012: syscall_trace_enter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
long int syscall_trace_enter(struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/entry/common.c (ffffffff81003ba0)
Location: arch/x86/entry/common.c:69
Inline: False
Direct callers:
  - arch/x86/entry/common.c:do_fast_syscall_32
  - arch/x86/entry/common.c:do_int80_syscall_32
  - arch/x86/entry/common.c:do_syscall_64
```
**Symbols:**

```
ffffffff81003ba0-ffffffff81003e43: syscall_trace_enter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long int syscall_trace_enter(struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/entry/common.c (ffffffff81003ba0)
Location: arch/x86/entry/common.c:69
Inline: False
Direct callers:
  - arch/x86/entry/common.c:do_fast_syscall_32
  - arch/x86/entry/common.c:do_int80_syscall_32
  - arch/x86/entry/common.c:do_syscall_64
```
**Symbols:**

```
ffffffff81003ba0-ffffffff81003e43: syscall_trace_enter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long int syscall_trace_enter(struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/entry/common.c (ffffffff81005380)
Location: arch/x86/entry/common.c:156
Inline: False
Direct callers:
  - arch/x86/entry/common.c:do_syscall_32_irqs_on
  - arch/x86/entry/common.c:do_syscall_64
```
**Symbols:**

```
ffffffff81005380-ffffffff810055f0: syscall_trace_enter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/entry/common.c (ffffffff8113b370)
Location: kernel/entry/common.c:43
Inline: True
Direct callers:
  - kernel/entry/common.c:syscall_enter_from_user_mode
  - kernel/entry/common.c:syscall_enter_from_user_mode_work
```
**Symbols:**

```
ffffffff8113b370-ffffffff8113b528: syscall_trace_enter.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/entry/common.c (ffffffff8113c650)
Location: kernel/entry/common.c:44
Inline: True
Direct callers:
  - kernel/entry/common.c:syscall_enter_from_user_mode
  - kernel/entry/common.c:syscall_enter_from_user_mode_work
```
**Symbols:**

```
ffffffff8113c650-ffffffff8113c80f: syscall_trace_enter.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/entry/common.c (ffffffff8115f770)
Location: kernel/entry/common.c:44
Inline: True
Direct callers:
  - kernel/entry/common.c:syscall_enter_from_user_mode
  - kernel/entry/common.c:syscall_enter_from_user_mode_work
```
**Symbols:**

```
ffffffff8115f770-ffffffff8115f92c: syscall_trace_enter.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/entry/common.c (ffffffff81189cf0)
Location: kernel/entry/common.c:46
Inline: True
Direct callers:
  - kernel/entry/common.c:syscall_enter_from_user_mode
  - kernel/entry/common.c:syscall_enter_from_user_mode_work
```
**Symbols:**

```
ffffffff81189cf0-ffffffff81189ea1: syscall_trace_enter.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/entry/common.c (ffffffff811c6200)
Location: kernel/entry/common.c:48
Inline: True
Direct callers:
  - kernel/entry/common.c:syscall_enter_from_user_mode
  - kernel/entry/common.c:syscall_enter_from_user_mode_work
```
**Symbols:**

```
ffffffff811c6200-ffffffff811c63b1: syscall_trace_enter.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/entry/common.c (ffffffff811d8e20)
Location: kernel/entry/common.c:48
Inline: True
Direct callers:
  - kernel/entry/common.c:syscall_enter_from_user_mode
  - kernel/entry/common.c:syscall_enter_from_user_mode_work
```
**Symbols:**

```
ffffffff811d8e20-ffffffff811d8fd1: syscall_trace_enter.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long int syscall_trace_enter(struct pt_regs *regs, long int syscall, long unsigned int work);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/entry/common.c (ffffffff811eeda0)
Location: kernel/entry/common.c:28
Inline: False
Direct callers:
  - arch/x86/entry/common.c:__do_fast_syscall_32
  - arch/x86/entry/common.c:do_int80_emulation
  - arch/x86/entry/common.c:do_syscall_64
```
**Symbols:**

```
ffffffff811eeda0-ffffffff811eef51: syscall_trace_enter (STB_GLOBAL)
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
int syscall_trace_enter(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/arm64/kernel/ptrace.c (ffff80001008ec78)
Location: arch/arm64/kernel/ptrace.c:1830
Inline: False
```
**Symbols:**

```
ffff80001008ec78-ffff80001008ee70: syscall_trace_enter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int syscall_trace_enter(struct pt_regs *regs, int scno);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/arm/kernel/ptrace.c (c030ce6c)
Location: arch/arm/kernel/ptrace.c:917
Inline: False
```
**Symbols:**

```
c030ce6c-c030d04c: syscall_trace_enter (STB_GLOBAL)
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
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
long int syscall_trace_enter(struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/entry/common.c (ffffffff81003ba0)
Location: arch/x86/entry/common.c:69
Inline: False
Direct callers:
  - arch/x86/entry/common.c:do_fast_syscall_32
  - arch/x86/entry/common.c:do_int80_syscall_32
  - arch/x86/entry/common.c:do_syscall_64
```
**Symbols:**

```
ffffffff81003ba0-ffffffff81003e43: syscall_trace_enter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long int syscall_trace_enter(struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/entry/common.c (ffffffff81002080)
Location: arch/x86/entry/common.c:69
Inline: False
Direct callers:
  - arch/x86/entry/common.c:do_fast_syscall_32
  - arch/x86/entry/common.c:do_int80_syscall_32
  - arch/x86/entry/common.c:do_syscall_64
```
**Symbols:**

```
ffffffff81002080-ffffffff81002323: syscall_trace_enter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long int syscall_trace_enter(struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/entry/common.c (ffffffff81003ba0)
Location: arch/x86/entry/common.c:69
Inline: False
Direct callers:
  - arch/x86/entry/common.c:do_fast_syscall_32
  - arch/x86/entry/common.c:do_int80_syscall_32
  - arch/x86/entry/common.c:do_syscall_64
```
**Symbols:**

```
ffffffff81003ba0-ffffffff81003e43: syscall_trace_enter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long int syscall_trace_enter(struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/entry/common.c (ffffffff81003c70)
Location: arch/x86/entry/common.c:69
Inline: False
Direct callers:
  - arch/x86/entry/common.c:do_fast_syscall_32
  - arch/x86/entry/common.c:do_int80_syscall_32
  - arch/x86/entry/common.c:do_syscall_64
```
**Symbols:**

```
ffffffff81003c70-ffffffff81003f2a: syscall_trace_enter (STB_LOCAL)
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
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Changed between <code>amd64</code> and <code>arm64</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>long int</code> ➡️ <code>int</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>amd64</code> and <code>armhf</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>int scno</code>
</li>
<li>
<b>Return type changed. </b>
<code>long int</code> ➡️ <code>int</code>
</li>
</ul>
</details>
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
