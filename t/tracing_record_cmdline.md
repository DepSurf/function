# Function: <code>tracing_record_cmdline</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void tracing_record_cmdline(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8114e790)
Location: kernel/trace/trace.c:1636
Inline: True
Direct callers:
  - kernel/trace/trace.c:__update_max_tr
  - kernel/trace/trace_sched_switch.c:probe_sched_switch
  - kernel/trace/trace_sched_switch.c:probe_sched_switch
  - kernel/trace/trace_sched_switch.c:probe_sched_wakeup
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/blktrace.c:__blk_add_trace
```
**Symbols:**

```
ffffffff8114e790-ffffffff8114e8ab: tracing_record_cmdline (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void tracing_record_cmdline(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff81157460)
Location: kernel/trace/trace.c:1881
Inline: True
Direct callers:
  - kernel/trace/trace.c:__update_max_tr
  - kernel/trace/trace_sched_switch.c:probe_sched_wakeup
  - kernel/trace/trace_sched_switch.c:probe_sched_switch
  - kernel/trace/trace_sched_switch.c:probe_sched_switch
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/blktrace.c:__blk_add_trace
```
**Symbols:**

```
ffffffff81157460-ffffffff8115757b: tracing_record_cmdline (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void tracing_record_cmdline(struct task_struct *tsk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811625a0)
Location: kernel/trace/trace.c:1925
Inline: True
Direct callers:
  - kernel/trace/trace.c:__update_max_tr
  - kernel/trace/trace_sched_switch.c:probe_sched_wakeup
  - kernel/trace/trace_sched_switch.c:probe_sched_switch
  - kernel/trace/trace_sched_switch.c:probe_sched_switch
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/blktrace.c:__blk_add_trace
```
**Symbols:**

```
ffffffff811625a0-ffffffff811626bb: tracing_record_cmdline (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void tracing_record_cmdline(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff81165b2b)
Location: kernel/trace/trace.c:2092
Inline: True
Inline callers:
  - kernel/trace/trace.c:__update_max_tr
Direct callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/blktrace.c:__blk_add_trace
```
**Symbols:**

```
ffffffff81165f40-ffffffff81165f50: tracing_record_cmdline (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void tracing_record_cmdline(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff81172abb)
Location: kernel/trace/trace.c:2095
Inline: True
Inline callers:
  - kernel/trace/trace.c:__update_max_tr
Direct callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/blktrace.c:__blk_add_trace
```
**Symbols:**

```
ffffffff81172ed0-ffffffff81172ee0: tracing_record_cmdline (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void tracing_record_cmdline(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff81181ab8)
Location: kernel/trace/trace.c:2107
Inline: True
Inline callers:
  - kernel/trace/trace.c:__update_max_tr
Direct callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/blktrace.c:__blk_add_trace
```
**Symbols:**

```
ffffffff81181eb0-ffffffff81181ec0: tracing_record_cmdline (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void tracing_record_cmdline(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8118f478)
Location: kernel/trace/trace.c:2108
Inline: True
Inline callers:
  - kernel/trace/trace.c:__update_max_tr
Direct callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/blktrace.c:__blk_add_trace
```
**Symbols:**

```
ffffffff8118f870-ffffffff8118f880: tracing_record_cmdline (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void tracing_record_cmdline(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8119ce3d)
Location: kernel/trace/trace.c:2291
Inline: True
Inline callers:
  - kernel/trace/trace.c:__update_max_tr
Direct callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/blktrace.c:__blk_add_trace
```
**Symbols:**

```
ffffffff8119d2a0-ffffffff8119d2b0: tracing_record_cmdline (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void tracing_record_cmdline(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811a87ed)
Location: kernel/trace/trace.c:2317
Inline: True
Inline callers:
  - kernel/trace/trace.c:__update_max_tr
Direct callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/blktrace.c:__blk_add_trace
```
**Symbols:**

```
ffffffff811a8c50-ffffffff811a8c60: tracing_record_cmdline (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void tracing_record_cmdline(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811c0925)
Location: kernel/trace/trace.c:2421
Inline: True
Inline callers:
  - kernel/trace/trace.c:__update_max_tr
Direct callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/blktrace.c:__blk_add_trace
```
**Symbols:**

```
ffffffff811c0e50-ffffffff811c0ec3: tracing_record_cmdline (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void tracing_record_cmdline(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811be54e)
Location: kernel/trace/trace.c:2565
Inline: True
Inline callers:
  - kernel/trace/trace.c:__update_max_tr
Direct callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/blktrace.c:__blk_add_trace
```
**Symbols:**

```
ffffffff811bea80-ffffffff811beaf3: tracing_record_cmdline (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void tracing_record_cmdline(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811bbad3)
Location: kernel/trace/trace.c:2576
Inline: True
Inline callers:
  - kernel/trace/trace.c:__update_max_tr
Direct callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/blktrace.c:__blk_add_trace
```
**Symbols:**

```
ffffffff811be390-ffffffff811be3b3: tracing_record_cmdline (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void tracing_record_cmdline(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811e61e5)
Location: kernel/trace/trace.c:2590
Inline: True
Inline callers:
  - kernel/trace/trace.c:__update_max_tr
Direct callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/blktrace.c:__blk_add_trace
```
**Symbols:**

```
ffffffff811e8bf0-ffffffff811e8c13: tracing_record_cmdline (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void tracing_record_cmdline(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8121deae)
Location: kernel/trace/trace.c:2581
Inline: True
Inline callers:
  - kernel/trace/trace.c:__update_max_tr
  - kernel/trace/trace.c:__update_max_tr
Direct callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/blktrace.c:__blk_add_trace
```
**Symbols:**

```
ffffffff812208a0-ffffffff812208d3: tracing_record_cmdline (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void tracing_record_cmdline(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8126856b)
Location: kernel/trace/trace.c:2605
Inline: True
Inline callers:
  - kernel/trace/trace.c:__update_max_tr
  - kernel/trace/trace.c:__update_max_tr
Direct callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/blktrace.c:__blk_add_trace
```
**Symbols:**

```
ffffffff8126b6e0-ffffffff8126b713: tracing_record_cmdline (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void tracing_record_cmdline(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8127f72b)
Location: kernel/trace/trace.c:2676
Inline: True
Inline callers:
  - kernel/trace/trace.c:__update_max_tr
  - kernel/trace/trace.c:__update_max_tr
Direct callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/blktrace.c:__blk_add_trace
```
**Symbols:**

```
ffffffff81282850-ffffffff81282883: tracing_record_cmdline (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void tracing_record_cmdline(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff81299f0b)
Location: kernel/trace/trace.c:2671
Inline: True
Inline callers:
  - kernel/trace/trace.c:__update_max_tr
  - kernel/trace/trace.c:__update_max_tr
Direct callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/blktrace.c:__blk_add_trace
```
**Symbols:**

```
ffffffff8129d940-ffffffff8129d973: tracing_record_cmdline (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void tracing_record_cmdline(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffff800010225354)
Location: kernel/trace/trace.c:2317
Inline: True
Inline callers:
  - kernel/trace/trace.c:__update_max_tr
Direct callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/blktrace.c:__blk_add_trace
```
**Symbols:**

```
ffff800010225920-ffff800010225938: tracing_record_cmdline (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void tracing_record_cmdline(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (c0462808)
Location: kernel/trace/trace.c:2317
Inline: True
Inline callers:
  - kernel/trace/trace.c:__update_max_tr
Direct callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/blktrace.c:__blk_add_trace
```
**Symbols:**

```
c0462d44-c0462d5c: tracing_record_cmdline (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void tracing_record_cmdline(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (c0000000002aa8cc)
Location: kernel/trace/trace.c:2317
Inline: True
Inline callers:
  - kernel/trace/trace.c:__update_max_tr
Direct callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/blktrace.c:__blk_add_trace
```
**Symbols:**

```
c0000000002ab010-c0000000002ab020: tracing_record_cmdline (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void tracing_record_cmdline(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffe000180286)
Location: kernel/trace/trace.c:2317
Inline: True
Inline callers:
  - kernel/trace/trace.c:__update_max_tr
Direct callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/blktrace.c:__blk_add_trace
```
**Symbols:**

```
ffffffe00018076c-ffffffe000180786: tracing_record_cmdline (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void tracing_record_cmdline(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811a0e0d)
Location: kernel/trace/trace.c:2317
Inline: True
Inline callers:
  - kernel/trace/trace.c:__update_max_tr
Direct callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/blktrace.c:__blk_add_trace
```
**Symbols:**

```
ffffffff811a1270-ffffffff811a1280: tracing_record_cmdline (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void tracing_record_cmdline(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff81193e1d)
Location: kernel/trace/trace.c:2317
Inline: True
Inline callers:
  - kernel/trace/trace.c:__update_max_tr
Direct callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/blktrace.c:__blk_add_trace
```
**Symbols:**

```
ffffffff81194240-ffffffff81194250: tracing_record_cmdline (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void tracing_record_cmdline(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8119ebdd)
Location: kernel/trace/trace.c:2317
Inline: True
Inline callers:
  - kernel/trace/trace.c:__update_max_tr
Direct callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/blktrace.c:__blk_add_trace
```
**Symbols:**

```
ffffffff8119f040-ffffffff8119f050: tracing_record_cmdline (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void tracing_record_cmdline(struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811ac8db)
Location: kernel/trace/trace.c:2317
Inline: True
Inline callers:
  - kernel/trace/trace.c:__update_max_tr
Direct callers:
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/trace_sched_wakeup.c:probe_wakeup
  - kernel/trace/blktrace.c:__blk_add_trace
```
**Symbols:**

```
ffffffff811acd40-ffffffff811acd50: tracing_record_cmdline (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct task_struct *task</code>
</li>
<li>
<b>Param removed. </b>
<code>struct task_struct *tsk</code>
</li>
</ul>
</details>
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
