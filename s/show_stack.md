# Function: <code>show_stack</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void show_stack(struct task_struct *task, long unsigned int *sp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/dumpstack.c (ffffffff81032000)
Location: arch/x86/kernel/dumpstack.c:183
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_show_task
  - kernel/debug/kdb/kdb_bt.c:kdb_show_stack
  - kernel/debug/kdb/kdb_bt.c:kdb_show_stack
  - kernel/debug/kdb/kdb_bt.c:kdb_show_stack
  - lib/dump_stack.c:dump_stack
```
**Symbols:**

```
ffffffff81032000-ffffffff81032069: show_stack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void show_stack(struct task_struct *task, long unsigned int *sp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/dumpstack.c (ffffffff81031120)
Location: arch/x86/kernel/dumpstack.c:191
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_show_task
  - kernel/debug/kdb/kdb_bt.c:kdb_show_stack
  - kernel/debug/kdb/kdb_bt.c:kdb_show_stack
  - kernel/debug/kdb/kdb_bt.c:kdb_show_stack
  - lib/dump_stack.c:dump_stack
```
**Symbols:**

```
ffffffff81031120-ffffffff81031189: show_stack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void show_stack(struct task_struct *task, long unsigned int *sp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/dumpstack.c (ffffffff81030d80)
Location: arch/x86/kernel/dumpstack.c:163
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_show_task
  - kernel/debug/kdb/kdb_bt.c:kdb_show_stack
  - kernel/debug/kdb/kdb_bt.c:kdb_show_stack
  - kernel/debug/kdb/kdb_bt.c:kdb_show_stack
  - lib/dump_stack.c:dump_stack
```
**Symbols:**

```
ffffffff81030d80-ffffffff81030dd1: show_stack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void show_stack(struct task_struct *task, long unsigned int *sp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/dumpstack.c (ffffffff8102f0a0)
Location: arch/x86/kernel/dumpstack.c:165
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_bt.c:kdb_show_stack
  - kernel/debug/kdb/kdb_bt.c:kdb_show_stack
  - kernel/debug/kdb/kdb_bt.c:kdb_show_stack
  - lib/dump_stack.c:dump_stack
```
**Symbols:**

```
ffffffff8102f0a0-ffffffff8102f0e1: show_stack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void show_stack(struct task_struct *task, long unsigned int *sp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/dumpstack.c (ffffffff810310a0)
Location: arch/x86/kernel/dumpstack.c:225
Inline: False
Direct callers:
  - arch/x86/kernel/stacktrace.c:save_stack_trace_tsk_reliable
  - arch/x86/kernel/stacktrace.c:save_stack_trace_tsk_reliable
  - arch/x86/kernel/stacktrace.c:save_stack_trace_tsk_reliable
  - kernel/debug/kdb/kdb_bt.c:kdb_show_stack
  - kernel/debug/kdb/kdb_bt.c:kdb_show_stack
  - kernel/debug/kdb/kdb_bt.c:kdb_show_stack
  - lib/dump_stack.c:dump_stack
```
**Symbols:**

```
ffffffff810310a0-ffffffff810310e1: show_stack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void show_stack(struct task_struct *task, long unsigned int *sp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/dumpstack.c (ffffffff810322b2)
Location: arch/x86/kernel/dumpstack.c:291
Inline: False
Direct callers:
  - arch/x86/kernel/stacktrace.c:save_stack_trace_tsk_reliable
  - arch/x86/kernel/stacktrace.c:save_stack_trace_tsk_reliable
  - arch/x86/kernel/stacktrace.c:save_stack_trace_tsk_reliable
  - kernel/debug/kdb/kdb_bt.c:kdb_show_stack
  - kernel/debug/kdb/kdb_bt.c:kdb_show_stack
  - kernel/debug/kdb/kdb_bt.c:kdb_show_stack
  - lib/dump_stack.c:dump_stack
```
**Symbols:**

```
ffffffff810322b2-ffffffff810322f1: show_stack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void show_stack(struct task_struct *task, long unsigned int *sp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/dumpstack.c (ffffffff81033577)
Location: arch/x86/kernel/dumpstack.c:282
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_bt.c:kdb_show_stack
  - kernel/debug/kdb/kdb_bt.c:kdb_show_stack
  - kernel/debug/kdb/kdb_bt.c:kdb_show_stack
  - lib/dump_stack.c:dump_stack
```
**Symbols:**

```
ffffffff81033577-ffffffff810335b6: show_stack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void show_stack(struct task_struct *task, long unsigned int *sp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/dumpstack.c (ffffffff81034ef0)
Location: arch/x86/kernel/dumpstack.c:282
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_bt.c:kdb_show_stack
  - kernel/debug/kdb/kdb_bt.c:kdb_show_stack
  - kernel/debug/kdb/kdb_bt.c:kdb_show_stack
  - lib/dump_stack.c:dump_stack
```
**Symbols:**

```
ffffffff81034ef0-ffffffff81034f32: show_stack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void show_stack(struct task_struct *task, long unsigned int *sp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/dumpstack.c (ffffffff81035720)
Location: arch/x86/kernel/dumpstack.c:282
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_bt.c:kdb_show_stack
  - kernel/debug/kdb/kdb_bt.c:kdb_show_stack
  - kernel/debug/kdb/kdb_bt.c:kdb_show_stack
  - lib/dump_stack.c:dump_stack
```
**Symbols:**

```
ffffffff81035720-ffffffff81035762: show_stack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void show_stack(struct task_struct *task, long unsigned int *sp, const char *loglvl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/dumpstack.c (ffffffff81037cf9)
Location: arch/x86/kernel/dumpstack.c:289
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_bt.c:kdb_show_stack
  - lib/dump_stack.c:dump_stack
```
**Symbols:**

```
ffffffff81037cf9-ffffffff81037d51: show_stack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void show_stack(struct task_struct *task, long unsigned int *sp, const char *loglvl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/dumpstack.c (ffffffff81bd38be)
Location: arch/x86/kernel/dumpstack.c:306
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_bt.c:kdb_show_stack
  - lib/dump_stack.c:dump_stack
```
**Symbols:**

```
ffffffff81bd38be-ffffffff81bd3916: show_stack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void show_stack(struct task_struct *task, long unsigned int *sp, const char *loglvl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/dumpstack.c (ffffffff81bc5d30)
Location: arch/x86/kernel/dumpstack.c:306
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_bt.c:kdb_show_stack
  - lib/dump_stack.c:dump_stack
```
**Symbols:**

```
ffffffff81bc5d30-ffffffff81bc5d88: show_stack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void show_stack(struct task_struct *task, long unsigned int *sp, const char *loglvl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/dumpstack.c (ffffffff81c98a7a)
Location: arch/x86/kernel/dumpstack.c:306
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_bt.c:kdb_show_stack
  - lib/dump_stack.c:dump_stack_lvl
```
**Symbols:**

```
ffffffff81c98a7a-ffffffff81c98ad2: show_stack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void show_stack(struct task_struct *task, long unsigned int *sp, const char *loglvl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/dumpstack.c (ffffffff81e48017)
Location: arch/x86/kernel/dumpstack.c:300
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_bt.c:kdb_show_stack
  - lib/dump_stack.c:dump_stack_lvl
```
**Symbols:**

```
ffffffff81e48017-ffffffff81e48078: show_stack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void show_stack(struct task_struct *task, long unsigned int *sp, const char *loglvl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/dumpstack.c (ffffffff81051b30)
Location: arch/x86/kernel/dumpstack.c:306
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_bt.c:kdb_show_stack
  - lib/dump_stack.c:dump_stack_lvl
```
**Symbols:**

```
ffffffff81051b30-ffffffff81051b98: show_stack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void show_stack(struct task_struct *task, long unsigned int *sp, const char *loglvl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/dumpstack.c (ffffffff81052870)
Location: arch/x86/kernel/dumpstack.c:309
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_bt.c:kdb_show_stack
  - lib/dump_stack.c:dump_stack_lvl
```
**Symbols:**

```
ffffffff81052870-ffffffff810528d8: show_stack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void show_stack(struct task_struct *task, long unsigned int *sp, const char *loglvl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/dumpstack.c (ffffffff81059a90)
Location: arch/x86/kernel/dumpstack.c:309
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_bt.c:kdb_show_stack
  - lib/dump_stack.c:dump_stack_lvl
```
**Symbols:**

```
ffffffff81059a90-ffffffff81059af8: show_stack (STB_GLOBAL)
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
void show_stack(struct task_struct *tsk, long unsigned int *sp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/arm64/kernel/traps.c (ffff8000100948e0)
Location: arch/arm64/kernel/traps.c:138
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_bt.c:kdb_show_stack
  - kernel/debug/kdb/kdb_bt.c:kdb_show_stack
  - lib/dump_stack.c:dump_stack
```
**Symbols:**

```
ffff8000100948e0-ffff800010094910: show_stack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void show_stack(struct task_struct *tsk, long unsigned int *sp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/arm/kernel/traps.c (c0310228)
Location: arch/arm/kernel/traps.c:243
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_bt.c:kdb_show_stack
  - lib/dump_stack.c:dump_stack
```
**Symbols:**

```
c0310228-c031024c: show_stack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void show_stack(struct task_struct *tsk, long unsigned int *stack);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/powerpc/kernel/process.c (c000000000022a80)
Location: arch/powerpc/kernel/process.c:2031
Inline: False
Direct callers:
  - arch/powerpc/kernel/process.c:show_regs
  - kernel/debug/kdb/kdb_bt.c:kdb_show_stack
  - kernel/debug/kdb/kdb_bt.c:kdb_show_stack
  - lib/dump_stack.c:dump_stack
```
**Symbols:**

```
c000000000022a80-c000000000022dec: show_stack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void show_stack(struct task_struct *task, long unsigned int *sp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/riscv/kernel/stacktrace.c (ffffffe0000b73fc)
Location: arch/riscv/kernel/stacktrace.c:105
Inline: False
Direct callers:
  - lib/dump_stack.c:dump_stack
```
**Symbols:**

```
ffffffe0000b73fc-ffffffe0000b7442: show_stack (STB_GLOBAL)
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
void show_stack(struct task_struct *task, long unsigned int *sp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/dumpstack.c (ffffffff81035880)
Location: arch/x86/kernel/dumpstack.c:282
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_bt.c:kdb_show_stack
  - kernel/debug/kdb/kdb_bt.c:kdb_show_stack
  - kernel/debug/kdb/kdb_bt.c:kdb_show_stack
  - lib/dump_stack.c:dump_stack
```
**Symbols:**

```
ffffffff81035880-ffffffff810358c2: show_stack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void show_stack(struct task_struct *task, long unsigned int *sp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/dumpstack.c (ffffffff810251d0)
Location: arch/x86/kernel/dumpstack.c:282
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_bt.c:kdb_show_stack
  - kernel/debug/kdb/kdb_bt.c:kdb_show_stack
  - kernel/debug/kdb/kdb_bt.c:kdb_show_stack
  - lib/dump_stack.c:dump_stack
```
**Symbols:**

```
ffffffff810251d0-ffffffff81025212: show_stack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void show_stack(struct task_struct *task, long unsigned int *sp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/dumpstack.c (ffffffff810356e0)
Location: arch/x86/kernel/dumpstack.c:282
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_bt.c:kdb_show_stack
  - kernel/debug/kdb/kdb_bt.c:kdb_show_stack
  - kernel/debug/kdb/kdb_bt.c:kdb_show_stack
  - lib/dump_stack.c:dump_stack
```
**Symbols:**

```
ffffffff810356e0-ffffffff81035722: show_stack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void show_stack(struct task_struct *task, long unsigned int *sp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/dumpstack.c (ffffffff810366c0)
Location: arch/x86/kernel/dumpstack.c:282
Inline: False
Direct callers:
  - kernel/debug/kdb/kdb_bt.c:kdb_show_stack
  - kernel/debug/kdb/kdb_bt.c:kdb_show_stack
  - kernel/debug/kdb/kdb_bt.c:kdb_show_stack
  - lib/dump_stack.c:dump_stack
```
**Symbols:**

```
ffffffff810366c0-ffffffff81036702: show_stack (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>const char *loglvl</code>
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
<li>
<details>
<summary>Changed between <code>amd64</code> and <code>arm64</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct task_struct *tsk</code>
</li>
<li>
<b>Param removed. </b>
<code>struct task_struct *task</code>
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
<code>struct task_struct *tsk</code>
</li>
<li>
<b>Param removed. </b>
<code>struct task_struct *task</code>
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
<code>struct task_struct *tsk</code>
</li>
<li>
<b>Param added. </b>
<code>long unsigned int *stack</code>
</li>
<li>
<b>Param removed. </b>
<code>struct task_struct *task</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int *sp</code>
</li>
</ul>
</details>
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
