# Function: <code>user_disable_single_step</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void user_disable_single_step(struct task_struct *child);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/step.c (ffffffff8103de90)
Location: arch/x86/kernel/step.c:220
Inline: False
Direct callers:
  - arch/x86/kernel/signal.c:do_signal
  - arch/x86/kernel/ptrace.c:ptrace_disable
  - kernel/fork.c:copy_process
  - kernel/ptrace.c:ptrace_resume
```
**Symbols:**

```
ffffffff8103de90-ffffffff8103dee0: user_disable_single_step (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void user_disable_single_step(struct task_struct *child);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/step.c (ffffffff8103dcb0)
Location: arch/x86/kernel/step.c:220
Inline: False
Direct callers:
  - arch/x86/kernel/signal.c:do_signal
  - arch/x86/kernel/ptrace.c:ptrace_disable
  - kernel/ptrace.c:ptrace_resume
```
**Symbols:**

```
ffffffff8103dcb0-ffffffff8103dcfd: user_disable_single_step (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void user_disable_single_step(struct task_struct *child);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/step.c (ffffffff8103d580)
Location: arch/x86/kernel/step.c:221
Inline: False
Direct callers:
  - arch/x86/kernel/signal.c:do_signal
  - arch/x86/kernel/ptrace.c:ptrace_disable
  - kernel/ptrace.c:ptrace_resume
```
**Symbols:**

```
ffffffff8103d580-ffffffff8103d5bd: user_disable_single_step (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void user_disable_single_step(struct task_struct *child);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/step.c (ffffffff8103b5d0)
Location: arch/x86/kernel/step.c:222
Inline: False
Direct callers:
  - arch/x86/kernel/signal.c:do_signal
  - arch/x86/kernel/ptrace.c:ptrace_disable
  - kernel/ptrace.c:ptrace_resume
```
**Symbols:**

```
ffffffff8103b5d0-ffffffff8103b60d: user_disable_single_step (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void user_disable_single_step(struct task_struct *child);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/step.c (ffffffff8103dff0)
Location: arch/x86/kernel/step.c:223
Inline: False
Direct callers:
  - arch/x86/kernel/signal.c:do_signal
  - arch/x86/kernel/ptrace.c:ptrace_disable
  - kernel/ptrace.c:ptrace_resume
```
**Symbols:**

```
ffffffff8103dff0-ffffffff8103e02d: user_disable_single_step (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void user_disable_single_step(struct task_struct *child);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/step.c (ffffffff8103f5a0)
Location: arch/x86/kernel/step.c:223
Inline: False
Direct callers:
  - arch/x86/kernel/signal.c:do_signal
  - arch/x86/kernel/ptrace.c:ptrace_disable
  - kernel/ptrace.c:ptrace_resume
```
**Symbols:**

```
ffffffff8103f5a0-ffffffff8103f5de: user_disable_single_step (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void user_disable_single_step(struct task_struct *child);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/step.c (ffffffff81040ba0)
Location: arch/x86/kernel/step.c:223
Inline: False
Direct callers:
  - arch/x86/kernel/signal.c:do_signal
  - arch/x86/kernel/ptrace.c:ptrace_disable
  - kernel/ptrace.c:ptrace_resume
```
**Symbols:**

```
ffffffff81040ba0-ffffffff81040bde: user_disable_single_step (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void user_disable_single_step(struct task_struct *child);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/step.c (ffffffff81043280)
Location: arch/x86/kernel/step.c:223
Inline: False
Direct callers:
  - arch/x86/kernel/signal.c:do_signal
  - arch/x86/kernel/ptrace.c:ptrace_disable
  - kernel/fork.c:copy_process
  - kernel/ptrace.c:ptrace_resume
```
**Symbols:**

```
ffffffff81043280-ffffffff810432be: user_disable_single_step (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void user_disable_single_step(struct task_struct *child);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/step.c (ffffffff810439e0)
Location: arch/x86/kernel/step.c:223
Inline: False
Direct callers:
  - arch/x86/kernel/signal.c:do_signal
  - arch/x86/kernel/ptrace.c:ptrace_disable
  - kernel/fork.c:copy_process
  - kernel/ptrace.c:ptrace_resume
```
**Symbols:**

```
ffffffff810439e0-ffffffff81043a1e: user_disable_single_step (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void user_disable_single_step(struct task_struct *child);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/step.c (ffffffff81047280)
Location: arch/x86/kernel/step.c:223
Inline: False
Direct callers:
  - arch/x86/kernel/signal.c:do_signal
  - arch/x86/kernel/ptrace.c:ptrace_disable
  - kernel/fork.c:copy_process
  - kernel/ptrace.c:ptrace_resume
```
**Symbols:**

```
ffffffff81047280-ffffffff810472c1: user_disable_single_step (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void user_disable_single_step(struct task_struct *child);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/step.c (ffffffff81046ad0)
Location: arch/x86/kernel/step.c:228
Inline: False
Direct callers:
  - arch/x86/kernel/signal.c:arch_do_signal_or_restart
  - arch/x86/kernel/ptrace.c:ptrace_disable
  - kernel/fork.c:copy_process
  - kernel/ptrace.c:ptrace_resume
```
**Symbols:**

```
ffffffff81046ad0-ffffffff81046b16: user_disable_single_step (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void user_disable_single_step(struct task_struct *child);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/step.c (ffffffff81048500)
Location: arch/x86/kernel/step.c:228
Inline: False
Direct callers:
  - arch/x86/kernel/signal.c:handle_signal
  - arch/x86/kernel/ptrace.c:ptrace_disable
  - kernel/fork.c:copy_process
  - kernel/ptrace.c:ptrace_resume
```
**Symbols:**

```
ffffffff81048500-ffffffff81048546: user_disable_single_step (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void user_disable_single_step(struct task_struct *child);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/step.c (ffffffff8104ee40)
Location: arch/x86/kernel/step.c:228
Inline: False
Direct callers:
  - arch/x86/kernel/signal.c:handle_signal
  - arch/x86/kernel/ptrace.c:ptrace_disable
  - kernel/fork.c:copy_process
  - kernel/ptrace.c:ptrace_resume
```
**Symbols:**

```
ffffffff8104ee40-ffffffff8104ee86: user_disable_single_step (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void user_disable_single_step(struct task_struct *child);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/step.c (ffffffff8105a090)
Location: arch/x86/kernel/step.c:227
Inline: False
Direct callers:
  - arch/x86/kernel/signal.c:handle_signal
  - arch/x86/kernel/ptrace.c:ptrace_disable
  - kernel/fork.c:copy_process
  - kernel/ptrace.c:ptrace_request
```
**Symbols:**

```
ffffffff8105a090-ffffffff8105a0e0: user_disable_single_step (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void user_disable_single_step(struct task_struct *child);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/step.c (ffffffff81067aa0)
Location: arch/x86/kernel/step.c:227
Inline: False
Direct callers:
  - arch/x86/kernel/signal.c:handle_signal
  - arch/x86/kernel/ptrace.c:ptrace_disable
  - kernel/fork.c:copy_process
  - kernel/ptrace.c:ptrace_request
```
**Symbols:**

```
ffffffff81067aa0-ffffffff81067af0: user_disable_single_step (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void user_disable_single_step(struct task_struct *child);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/step.c (ffffffff81069350)
Location: arch/x86/kernel/step.c:227
Inline: False
Direct callers:
  - arch/x86/kernel/signal.c:handle_signal
  - arch/x86/kernel/ptrace.c:ptrace_disable
  - kernel/fork.c:copy_process
  - kernel/ptrace.c:ptrace_request
```
**Symbols:**

```
ffffffff81069350-ffffffff810693a0: user_disable_single_step (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void user_disable_single_step(struct task_struct *child);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/step.c (ffffffff810707c0)
Location: arch/x86/kernel/step.c:227
Inline: False
Direct callers:
  - arch/x86/kernel/signal.c:handle_signal
  - arch/x86/kernel/ptrace.c:ptrace_disable
  - kernel/fork.c:copy_process
  - kernel/ptrace.c:ptrace_request
```
**Symbols:**

```
ffffffff810707c0-ffffffff81070810: user_disable_single_step (STB_GLOBAL)
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
void user_disable_single_step(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/arm64/kernel/debug-monitors.c (ffff800010085fa0)
Location: arch/arm64/kernel/debug-monitors.c:442
Inline: False
Direct callers:
  - arch/arm64/kernel/ptrace.c:ptrace_disable
  - arch/arm64/kernel/hw_breakpoint.c:reinstall_suspended_bps
  - arch/arm64/kernel/probes/uprobes.c:arch_uprobe_abort_xol
  - arch/arm64/kernel/probes/uprobes.c:arch_uprobe_post_xol
  - kernel/fork.c:copy_process
  - kernel/ptrace.c:ptrace_resume
```
**Symbols:**

```
ffff800010085fa0-ffff800010085fe8: user_disable_single_step (STB_GLOBAL)
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
In kernel/fork.c (0)
Location: include/linux/ptrace.h:309
Inline: True
```
```
In kernel/ptrace.c (0)
Location: include/linux/ptrace.h:309
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void user_disable_single_step(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/powerpc/kernel/ptrace.c (c0000000000189f8)
Location: arch/powerpc/kernel/ptrace.c:2336
Inline: True
Inline callers:
  - arch/powerpc/kernel/ptrace.c:ptrace_disable
Direct callers:
  - arch/powerpc/kernel/uprobes.c:arch_uprobe_abort_xol
  - arch/powerpc/kernel/uprobes.c:arch_uprobe_post_xol
  - arch/powerpc/kernel/uprobes.c:arch_uprobe_post_xol
  - kernel/fork.c:copy_process
  - kernel/ptrace.c:ptrace_resume
```
**Symbols:**

```
c0000000000189b0-c0000000000189f0: user_disable_single_step (STB_GLOBAL)
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
In kernel/fork.c (0)
Location: include/linux/ptrace.h:309
Inline: True
```
```
In kernel/ptrace.c (0)
Location: include/linux/ptrace.h:309
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
void user_disable_single_step(struct task_struct *child);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/step.c (ffffffff81043b60)
Location: arch/x86/kernel/step.c:223
Inline: False
Direct callers:
  - arch/x86/kernel/signal.c:do_signal
  - arch/x86/kernel/ptrace.c:ptrace_disable
  - kernel/fork.c:copy_process
  - kernel/ptrace.c:ptrace_resume
```
**Symbols:**

```
ffffffff81043b60-ffffffff81043b9e: user_disable_single_step (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void user_disable_single_step(struct task_struct *child);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/step.c (ffffffff81033190)
Location: arch/x86/kernel/step.c:223
Inline: False
Direct callers:
  - arch/x86/kernel/signal.c:do_signal
  - arch/x86/kernel/ptrace.c:ptrace_disable
  - kernel/fork.c:copy_process
  - kernel/ptrace.c:ptrace_resume
```
**Symbols:**

```
ffffffff81033190-ffffffff810331ce: user_disable_single_step (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void user_disable_single_step(struct task_struct *child);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/step.c (ffffffff810439a0)
Location: arch/x86/kernel/step.c:223
Inline: False
Direct callers:
  - arch/x86/kernel/signal.c:do_signal
  - arch/x86/kernel/ptrace.c:ptrace_disable
  - kernel/fork.c:copy_process
  - kernel/ptrace.c:ptrace_resume
```
**Symbols:**

```
ffffffff810439a0-ffffffff810439de: user_disable_single_step (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void user_disable_single_step(struct task_struct *child);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/step.c (ffffffff81044da0)
Location: arch/x86/kernel/step.c:223
Inline: False
Direct callers:
  - arch/x86/kernel/signal.c:do_signal
  - arch/x86/kernel/ptrace.c:ptrace_disable
  - kernel/fork.c:copy_process
  - kernel/ptrace.c:ptrace_resume
```
**Symbols:**

```
ffffffff81044da0-ffffffff81044dde: user_disable_single_step (STB_GLOBAL)
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
<details>
<summary>Changed between <code>amd64</code> and <code>arm64</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct task_struct *task</code>
</li>
<li>
<b>Param removed. </b>
<code>struct task_struct *child</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>amd64</code> and <code>ppc64el</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct task_struct *task</code>
</li>
<li>
<b>Param removed. </b>
<code>struct task_struct *child</code>
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
