# Function: <code>show_trace_log_lvl</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void show_trace_log_lvl(struct task_struct *task, struct pt_regs *regs, long unsigned int *stack, long unsigned int bp, char *log_lvl);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/dumpstack.c (ffffffff81031f40)
Location: arch/x86/kernel/dumpstack.c:170
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack.c:show_trace
Direct callers:
  - arch/x86/kernel/dumpstack_64.c:show_stack_log_lvl
```
**Symbols:**

```
ffffffff81031f40-ffffffff81031f96: show_trace_log_lvl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void show_trace_log_lvl(struct task_struct *task, struct pt_regs *regs, long unsigned int *stack, long unsigned int bp, char *log_lvl);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/dumpstack.c (ffffffff810310dc)
Location: arch/x86/kernel/dumpstack.c:178
Inline: True
Inline callers:
  - arch/x86/kernel/dumpstack.c:show_trace
Direct callers:
  - arch/x86/kernel/dumpstack_64.c:show_stack_log_lvl
```
**Symbols:**

```
ffffffff81031060-ffffffff810310b6: show_trace_log_lvl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void show_trace_log_lvl(struct task_struct *task, struct pt_regs *regs, long unsigned int *stack, char *log_lvl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/dumpstack.c (ffffffff81030a20)
Location: arch/x86/kernel/dumpstack.c:51
Inline: False
Direct callers:
  - arch/x86/kernel/dumpstack_64.c:show_regs
  - arch/x86/kernel/dumpstack.c:show_stack_regs
  - arch/x86/kernel/dumpstack.c:show_stack
  - arch/x86/kernel/dumpstack.c:show_stack
```
**Symbols:**

```
ffffffff81030a20-ffffffff81030d80: show_trace_log_lvl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void show_trace_log_lvl(struct task_struct *task, struct pt_regs *regs, long unsigned int *stack, char *log_lvl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/dumpstack.c (ffffffff8102ecf0)
Location: arch/x86/kernel/dumpstack.c:53
Inline: False
Direct callers:
  - arch/x86/kernel/dumpstack_64.c:show_regs
  - arch/x86/kernel/dumpstack.c:show_stack_regs
  - arch/x86/kernel/dumpstack.c:show_stack
```
**Symbols:**

```
ffffffff8102ecf0-ffffffff8102f094: show_trace_log_lvl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void show_trace_log_lvl(struct task_struct *task, struct pt_regs *regs, long unsigned int *stack, char *log_lvl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/dumpstack.c (ffffffff81030cd0)
Location: arch/x86/kernel/dumpstack.c:105
Inline: False
Direct callers:
  - arch/x86/kernel/dumpstack_64.c:show_regs
  - arch/x86/kernel/dumpstack.c:show_stack_regs
  - arch/x86/kernel/dumpstack.c:show_stack
```
**Symbols:**

```
ffffffff81030cd0-ffffffff8103109a: show_trace_log_lvl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void show_trace_log_lvl(struct task_struct *task, struct pt_regs *regs, long unsigned int *stack, char *log_lvl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/dumpstack.c (ffffffff81031fba)
Location: arch/x86/kernel/dumpstack.c:171
Inline: False
Direct callers:
  - arch/x86/kernel/dumpstack.c:show_stack_regs
  - arch/x86/kernel/dumpstack.c:show_stack
```
**Symbols:**

```
ffffffff81031fba-ffffffff810322b2: show_trace_log_lvl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void show_trace_log_lvl(struct task_struct *task, struct pt_regs *regs, long unsigned int *stack, char *log_lvl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/dumpstack.c (ffffffff8103327f)
Location: arch/x86/kernel/dumpstack.c:162
Inline: False
Direct callers:
  - arch/x86/kernel/dumpstack.c:show_stack_regs
  - arch/x86/kernel/dumpstack.c:show_stack
```
**Symbols:**

```
ffffffff8103327f-ffffffff81033577: show_trace_log_lvl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void show_trace_log_lvl(struct task_struct *task, struct pt_regs *regs, long unsigned int *stack, char *log_lvl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/dumpstack.c (ffffffff810350f8)
Location: arch/x86/kernel/dumpstack.c:162
Inline: False
Direct callers:
  - arch/x86/kernel/dumpstack.c:show_stack_regs
  - arch/x86/kernel/dumpstack.c:show_stack
```
**Symbols:**

```
ffffffff810350f8-ffffffff810353e6: show_trace_log_lvl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void show_trace_log_lvl(struct task_struct *task, struct pt_regs *regs, long unsigned int *stack, char *log_lvl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/dumpstack.c (ffffffff81035928)
Location: arch/x86/kernel/dumpstack.c:162
Inline: False
Direct callers:
  - arch/x86/kernel/dumpstack.c:show_stack_regs
  - arch/x86/kernel/dumpstack.c:show_stack
```
**Symbols:**

```
ffffffff81035928-ffffffff81035c16: show_trace_log_lvl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void show_trace_log_lvl(struct task_struct *task, struct pt_regs *regs, long unsigned int *stack, const char *log_lvl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/dumpstack.c (ffffffff810379bf)
Location: arch/x86/kernel/dumpstack.c:169
Inline: False
Direct callers:
  - arch/x86/kernel/dumpstack.c:show_stack_regs
  - arch/x86/kernel/dumpstack.c:show_stack
```
**Symbols:**

```
ffffffff810379bf-ffffffff81037c94: show_trace_log_lvl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void show_trace_log_lvl(struct task_struct *task, struct pt_regs *regs, long unsigned int *stack, const char *log_lvl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/dumpstack.c (ffffffff81bd357e)
Location: arch/x86/kernel/dumpstack.c:186
Inline: False
Direct callers:
  - arch/x86/kernel/dumpstack.c:show_stack_regs
  - arch/x86/kernel/dumpstack.c:show_stack
```
**Symbols:**

```
ffffffff81bd357e-ffffffff81bd3859: show_trace_log_lvl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void show_trace_log_lvl(struct task_struct *task, struct pt_regs *regs, long unsigned int *stack, const char *log_lvl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/dumpstack.c (ffffffff81bc59f0)
Location: arch/x86/kernel/dumpstack.c:186
Inline: False
Direct callers:
  - arch/x86/kernel/dumpstack.c:show_stack_regs
  - arch/x86/kernel/dumpstack.c:show_stack
```
**Symbols:**

```
ffffffff81bc59f0-ffffffff81bc5ccb: show_trace_log_lvl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void show_trace_log_lvl(struct task_struct *task, struct pt_regs *regs, long unsigned int *stack, const char *log_lvl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/dumpstack.c (ffffffff81c9873a)
Location: arch/x86/kernel/dumpstack.c:186
Inline: False
Direct callers:
  - arch/x86/kernel/dumpstack.c:show_stack_regs
  - arch/x86/kernel/dumpstack.c:show_stack
```
**Symbols:**

```
ffffffff81c9873a-ffffffff81c98a15: show_trace_log_lvl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void show_trace_log_lvl(struct task_struct *task, struct pt_regs *regs, long unsigned int *stack, const char *log_lvl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/dumpstack.c (ffffffff81e47c90)
Location: arch/x86/kernel/dumpstack.c:180
Inline: False
Direct callers:
  - arch/x86/kernel/dumpstack.c:show_stack_regs
  - arch/x86/kernel/dumpstack.c:show_stack
```
**Symbols:**

```
ffffffff81e47c90-ffffffff81e47f9e: show_trace_log_lvl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void show_trace_log_lvl(struct task_struct *task, struct pt_regs *regs, long unsigned int *stack, const char *log_lvl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/dumpstack.c (ffffffff81051630)
Location: arch/x86/kernel/dumpstack.c:186
Inline: False
Direct callers:
  - arch/x86/kernel/dumpstack.c:show_stack_regs
  - arch/x86/kernel/dumpstack.c:show_stack
  - arch/x86/kernel/dumpstack.c:show_stack
```
**Symbols:**

```
ffffffff81051630-ffffffff81051a31: show_trace_log_lvl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void show_trace_log_lvl(struct task_struct *task, struct pt_regs *regs, long unsigned int *stack, const char *log_lvl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/dumpstack.c (ffffffff81052390)
Location: arch/x86/kernel/dumpstack.c:186
Inline: False
Direct callers:
  - arch/x86/kernel/dumpstack.c:show_stack_regs
  - arch/x86/kernel/dumpstack.c:show_stack
  - arch/x86/kernel/dumpstack.c:show_stack
```
**Symbols:**

```
ffffffff81052390-ffffffff81052777: show_trace_log_lvl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void show_trace_log_lvl(struct task_struct *task, struct pt_regs *regs, long unsigned int *stack, const char *log_lvl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/dumpstack.c (ffffffff810595b0)
Location: arch/x86/kernel/dumpstack.c:186
Inline: False
Direct callers:
  - arch/x86/kernel/dumpstack.c:show_stack_regs
  - arch/x86/kernel/dumpstack.c:show_stack
  - arch/x86/kernel/dumpstack.c:show_stack
```
**Symbols:**

```
ffffffff810595b0-ffffffff81059997: show_trace_log_lvl (STB_LOCAL)
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
<summary>In <code>aws</code>: ✅</summary>

```c
void show_trace_log_lvl(struct task_struct *task, struct pt_regs *regs, long unsigned int *stack, char *log_lvl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/dumpstack.c (ffffffff81035a88)
Location: arch/x86/kernel/dumpstack.c:162
Inline: False
Direct callers:
  - arch/x86/kernel/dumpstack.c:show_stack_regs
  - arch/x86/kernel/dumpstack.c:show_stack
```
**Symbols:**

```
ffffffff81035a88-ffffffff81035d76: show_trace_log_lvl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void show_trace_log_lvl(struct task_struct *task, struct pt_regs *regs, long unsigned int *stack, char *log_lvl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/dumpstack.c (ffffffff810253d8)
Location: arch/x86/kernel/dumpstack.c:162
Inline: False
Direct callers:
  - arch/x86/kernel/dumpstack.c:show_stack_regs
  - arch/x86/kernel/dumpstack.c:show_stack
```
**Symbols:**

```
ffffffff810253d8-ffffffff810256c6: show_trace_log_lvl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void show_trace_log_lvl(struct task_struct *task, struct pt_regs *regs, long unsigned int *stack, char *log_lvl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/dumpstack.c (ffffffff810358e8)
Location: arch/x86/kernel/dumpstack.c:162
Inline: False
Direct callers:
  - arch/x86/kernel/dumpstack.c:show_stack_regs
  - arch/x86/kernel/dumpstack.c:show_stack
```
**Symbols:**

```
ffffffff810358e8-ffffffff81035bd6: show_trace_log_lvl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void show_trace_log_lvl(struct task_struct *task, struct pt_regs *regs, long unsigned int *stack, char *log_lvl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/dumpstack.c (ffffffff810368c8)
Location: arch/x86/kernel/dumpstack.c:162
Inline: False
Direct callers:
  - arch/x86/kernel/dumpstack.c:show_stack_regs
  - arch/x86/kernel/dumpstack.c:show_stack
```
**Symbols:**

```
ffffffff810368c8-ffffffff81036bb6: show_trace_log_lvl (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.8</code> and <code>4.10</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>long unsigned int bp</code>
</li>
<li>
<b>Param reordered. </b>
<code>task, regs, stack, bp, log_lvl</code> ➡️ <code>task, regs, stack, log_lvl</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>char *log_lvl</code> ➡️ <code>const char *log_lvl</code>
</li>
</ul>
</details>
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
