# Function: <code>unwind_next_frame</code>

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
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
bool unwind_next_frame(struct unwind_state *state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/unwind_frame.c (ffffffff81069b90)
Location: arch/x86/kernel/unwind_frame.c:160
Inline: False
Direct callers:
  - arch/x86/events/core.c:perf_callchain_kernel
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
  - arch/x86/kernel/stacktrace.c:__save_stack_trace
```
**Symbols:**

```
ffffffff81069b90-ffffffff81069dc6: unwind_next_frame (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool unwind_next_frame(struct unwind_state *state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/unwind_frame.c (ffffffff81068f30)
Location: arch/x86/kernel/unwind_frame.c:264
Inline: True
Direct callers:
  - arch/x86/events/core.c:perf_callchain_kernel
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
  - arch/x86/kernel/stacktrace.c:__save_stack_trace
```
**Symbols:**

```
ffffffff81068f30-ffffffff81069134: unwind_next_frame.part.5 (STB_LOCAL)
ffffffff81069140-ffffffff81069159: unwind_next_frame (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool unwind_next_frame(struct unwind_state *state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/unwind_frame.c (ffffffff8106d7b0)
Location: arch/x86/kernel/unwind_frame.c:282
Inline: True
Direct callers:
  - arch/x86/events/core.c:perf_callchain_kernel
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
  - arch/x86/kernel/stacktrace.c:save_stack_trace_tsk_reliable
  - arch/x86/kernel/stacktrace.c:save_stack_trace_tsk_reliable
  - arch/x86/kernel/stacktrace.c:__save_stack_trace
```
**Symbols:**

```
ffffffff8106d7b0-ffffffff8106d9b3: unwind_next_frame.part.5 (STB_LOCAL)
ffffffff8106d9c0-ffffffff8106d9d9: unwind_next_frame (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool unwind_next_frame(struct unwind_state *state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/unwind_frame.c (ffffffff8107084e)
Location: arch/x86/kernel/unwind_frame.c:282
Inline: True
Inline callers:
  - arch/x86/kernel/unwind_frame.c:__unwind_start
Direct callers:
  - arch/x86/events/core.c:perf_callchain_kernel
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
  - arch/x86/kernel/stacktrace.c:save_stack_trace_tsk_reliable
  - arch/x86/kernel/stacktrace.c:save_stack_trace_tsk_reliable
  - arch/x86/kernel/stacktrace.c:__save_stack_trace
  - arch/x86/kernel/unwind_frame.c:__unwind_start
```
**Symbols:**

```
ffffffff81070600-ffffffff810707a7: unwind_next_frame.part.5 (STB_LOCAL)
ffffffff810709a9-ffffffff810709fd: unwind_next_frame.part.5.cold.7 (STB_LOCAL)
ffffffff810707b0-ffffffff810707c9: unwind_next_frame (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool unwind_next_frame(struct unwind_state *state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/unwind_frame.c (ffffffff81076840)
Location: arch/x86/kernel/unwind_frame.c:282
Inline: True
Inline callers:
  - arch/x86/kernel/unwind_frame.c:__unwind_start
Direct callers:
  - arch/x86/events/core.c:perf_callchain_kernel
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
  - arch/x86/kernel/stacktrace.c:save_stack_trace_tsk_reliable
  - arch/x86/kernel/stacktrace.c:__save_stack_trace
  - arch/x86/kernel/unwind_frame.c:__unwind_start
```
**Symbols:**

```
ffffffff810765d0-ffffffff81076786: unwind_next_frame.part.6 (STB_LOCAL)
ffffffff810769b6-ffffffff81076a0a: unwind_next_frame.part.6.cold.8 (STB_LOCAL)
ffffffff81076790-ffffffff810767a9: unwind_next_frame (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool unwind_next_frame(struct unwind_state *state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/unwind_frame.c (ffffffff8107a3e0)
Location: arch/x86/kernel/unwind_frame.c:260
Inline: True
Inline callers:
  - arch/x86/kernel/unwind_frame.c:__unwind_start
Direct callers:
  - arch/x86/events/core.c:perf_callchain_kernel
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
  - arch/x86/kernel/stacktrace.c:arch_stack_walk_reliable
  - arch/x86/kernel/stacktrace.c:arch_stack_walk
  - arch/x86/kernel/unwind_frame.c:__unwind_start
```
**Symbols:**

```
ffffffff8107a180-ffffffff8107a32d: unwind_next_frame.part.0 (STB_LOCAL)
ffffffff8107a551-ffffffff8107a5a5: unwind_next_frame.part.0.cold (STB_LOCAL)
ffffffff8107a330-ffffffff8107a349: unwind_next_frame (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool unwind_next_frame(struct unwind_state *state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/unwind_frame.c (ffffffff8107b4d0)
Location: arch/x86/kernel/unwind_frame.c:260
Inline: True
Inline callers:
  - arch/x86/kernel/unwind_frame.c:__unwind_start
Direct callers:
  - arch/x86/events/core.c:perf_callchain_kernel
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
  - arch/x86/kernel/stacktrace.c:arch_stack_walk_reliable
  - arch/x86/kernel/stacktrace.c:arch_stack_walk
  - arch/x86/kernel/unwind_frame.c:__unwind_start
```
**Symbols:**

```
ffffffff8107b270-ffffffff8107b41d: unwind_next_frame.part.0 (STB_LOCAL)
ffffffff8107b63d-ffffffff8107b691: unwind_next_frame.part.0.cold (STB_LOCAL)
ffffffff8107b420-ffffffff8107b439: unwind_next_frame (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool unwind_next_frame(struct unwind_state *state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/unwind_frame.c (ffffffff810828fc)
Location: arch/x86/kernel/unwind_frame.c:254
Inline: True
Inline callers:
  - arch/x86/kernel/unwind_frame.c:__unwind_start
Direct callers:
  - arch/x86/events/core.c:perf_callchain_kernel
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
  - arch/x86/kernel/stacktrace.c:arch_stack_walk_reliable
  - arch/x86/kernel/stacktrace.c:arch_stack_walk
  - arch/x86/kernel/unwind_frame.c:__unwind_start
```
**Symbols:**

```
ffffffff81082690-ffffffff81082847: unwind_next_frame.part.0 (STB_LOCAL)
ffffffff81082a5d-ffffffff81082ab1: unwind_next_frame.part.0.cold (STB_LOCAL)
ffffffff81082850-ffffffff81082869: unwind_next_frame (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool unwind_next_frame(struct unwind_state *state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/unwind_frame.c (ffffffff810823ac)
Location: arch/x86/kernel/unwind_frame.c:254
Inline: True
Inline callers:
  - arch/x86/kernel/unwind_frame.c:__unwind_start
Direct callers:
  - arch/x86/events/core.c:perf_callchain_kernel
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
  - arch/x86/kernel/stacktrace.c:arch_stack_walk_reliable
  - arch/x86/kernel/stacktrace.c:arch_stack_walk
  - arch/x86/kernel/unwind_frame.c:__unwind_start
```
**Symbols:**

```
ffffffff81082140-ffffffff810822f7: unwind_next_frame.part.0 (STB_LOCAL)
ffffffff81bd841c-ffffffff81bd8470: unwind_next_frame.part.0.cold (STB_LOCAL)
ffffffff81082300-ffffffff81082319: unwind_next_frame (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool unwind_next_frame(struct unwind_state *state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/unwind_frame.c (ffffffff810831cc)
Location: arch/x86/kernel/unwind_frame.c:254
Inline: True
Inline callers:
  - arch/x86/kernel/unwind_frame.c:__unwind_start
Direct callers:
  - arch/x86/events/core.c:perf_callchain_kernel
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
  - arch/x86/kernel/stacktrace.c:arch_stack_walk_reliable
  - arch/x86/kernel/stacktrace.c:arch_stack_walk
  - arch/x86/kernel/unwind_frame.c:__unwind_start
```
**Symbols:**

```
ffffffff81082f60-ffffffff81083117: unwind_next_frame.part.0 (STB_LOCAL)
ffffffff81bca259-ffffffff81bca2ad: unwind_next_frame.part.0.cold (STB_LOCAL)
ffffffff81083120-ffffffff81083139: unwind_next_frame (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool unwind_next_frame(struct unwind_state *state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/unwind_frame.c (ffffffff810922cc)
Location: arch/x86/kernel/unwind_frame.c:254
Inline: True
Inline callers:
  - arch/x86/kernel/unwind_frame.c:__unwind_start
Direct callers:
  - arch/x86/events/core.c:perf_callchain_kernel
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
  - arch/x86/kernel/stacktrace.c:arch_stack_walk_reliable
  - arch/x86/kernel/stacktrace.c:arch_stack_walk
  - arch/x86/kernel/unwind_frame.c:__unwind_start
```
**Symbols:**

```
ffffffff81092030-ffffffff8109221c: unwind_next_frame.part.0 (STB_LOCAL)
ffffffff81c9f5d6-ffffffff81c9f675: unwind_next_frame.part.0.cold (STB_LOCAL)
ffffffff81092220-ffffffff81092239: unwind_next_frame (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
bool unwind_next_frame(struct unwind_state *state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/unwind_frame.c (0)
Location: arch/x86/kernel/unwind_frame.c:253
Inline: False
Direct callers:
  - arch/x86/events/core.c:perf_callchain_kernel
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
  - arch/x86/kernel/process.c:__get_wchan
  - arch/x86/kernel/stacktrace.c:arch_stack_walk_reliable
  - arch/x86/kernel/stacktrace.c:arch_stack_walk
  - arch/x86/kernel/unwind_frame.c:__unwind_start
```
**Symbols:**

```
ffffffff81e4ed81-ffffffff81e4ee20: unwind_next_frame.cold (STB_LOCAL)
ffffffff810a3290-ffffffff810a34b4: unwind_next_frame (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
bool unwind_next_frame(struct unwind_state *state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/unwind_frame.c (0)
Location: arch/x86/kernel/unwind_frame.c:264
Inline: False
Direct callers:
  - arch/x86/events/core.c:perf_callchain_kernel
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
  - arch/x86/kernel/process.c:__get_wchan
  - arch/x86/kernel/stacktrace.c:arch_stack_walk_reliable
  - arch/x86/kernel/stacktrace.c:arch_stack_walk
  - arch/x86/kernel/unwind_frame.c:__unwind_start
```
**Symbols:**

```
ffffffff820545d3-ffffffff82054612: unwind_next_frame.cold (STB_LOCAL)
ffffffff810bb650-ffffffff810bb8c8: unwind_next_frame (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
bool unwind_next_frame(struct unwind_state *state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/unwind_frame.c (0)
Location: arch/x86/kernel/unwind_frame.c:264
Inline: False
Direct callers:
  - arch/x86/events/core.c:perf_callchain_kernel
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
  - arch/x86/kernel/process.c:__get_wchan
  - arch/x86/kernel/stacktrace.c:arch_stack_walk_reliable
  - arch/x86/kernel/stacktrace.c:arch_stack_walk
  - arch/x86/kernel/unwind_frame.c:__unwind_start
```
**Symbols:**

```
ffffffff820d2bc4-ffffffff820d2c03: unwind_next_frame.cold (STB_LOCAL)
ffffffff810be790-ffffffff810bea08: unwind_next_frame (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
bool unwind_next_frame(struct unwind_state *state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/unwind_frame.c (0)
Location: arch/x86/kernel/unwind_frame.c:264
Inline: False
Direct callers:
  - arch/x86/events/core.c:perf_callchain_kernel
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
  - arch/x86/kernel/process.c:__get_wchan
  - arch/x86/kernel/stacktrace.c:arch_stack_walk_reliable
  - arch/x86/kernel/stacktrace.c:arch_stack_walk
  - arch/x86/kernel/unwind_frame.c:__unwind_start
```
**Symbols:**

```
ffffffff821ada26-ffffffff821ada65: unwind_next_frame.cold (STB_LOCAL)
ffffffff810c5910-ffffffff810c5b88: unwind_next_frame (STB_GLOBAL)
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
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool unwind_next_frame(struct unwind_state *state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/unwind_frame.c (ffffffff8107a4d0)
Location: arch/x86/kernel/unwind_frame.c:260
Inline: True
Inline callers:
  - arch/x86/kernel/unwind_frame.c:__unwind_start
Direct callers:
  - arch/x86/events/core.c:perf_callchain_kernel
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
  - arch/x86/kernel/stacktrace.c:arch_stack_walk_reliable
  - arch/x86/kernel/stacktrace.c:arch_stack_walk
  - arch/x86/kernel/unwind_frame.c:__unwind_start
```
**Symbols:**

```
ffffffff8107a270-ffffffff8107a41d: unwind_next_frame.part.0 (STB_LOCAL)
ffffffff8107a63d-ffffffff8107a691: unwind_next_frame.part.0.cold (STB_LOCAL)
ffffffff8107a420-ffffffff8107a439: unwind_next_frame (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool unwind_next_frame(struct unwind_state *state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/unwind_frame.c (ffffffff81069c00)
Location: arch/x86/kernel/unwind_frame.c:260
Inline: True
Inline callers:
  - arch/x86/kernel/unwind_frame.c:__unwind_start
Direct callers:
  - arch/x86/events/core.c:perf_callchain_kernel
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
  - arch/x86/kernel/stacktrace.c:arch_stack_walk_reliable
  - arch/x86/kernel/stacktrace.c:arch_stack_walk
  - arch/x86/kernel/unwind_frame.c:__unwind_start
```
**Symbols:**

```
ffffffff810699a0-ffffffff81069b4d: unwind_next_frame.part.0 (STB_LOCAL)
ffffffff81069d6d-ffffffff81069dc1: unwind_next_frame.part.0.cold (STB_LOCAL)
ffffffff81069b50-ffffffff81069b69: unwind_next_frame (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool unwind_next_frame(struct unwind_state *state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/unwind_frame.c (ffffffff8107a480)
Location: arch/x86/kernel/unwind_frame.c:260
Inline: True
Inline callers:
  - arch/x86/kernel/unwind_frame.c:__unwind_start
Direct callers:
  - arch/x86/events/core.c:perf_callchain_kernel
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
  - arch/x86/kernel/stacktrace.c:arch_stack_walk_reliable
  - arch/x86/kernel/stacktrace.c:arch_stack_walk
  - arch/x86/kernel/unwind_frame.c:__unwind_start
```
**Symbols:**

```
ffffffff8107a220-ffffffff8107a3cd: unwind_next_frame.part.0 (STB_LOCAL)
ffffffff8107a5ed-ffffffff8107a641: unwind_next_frame.part.0.cold (STB_LOCAL)
ffffffff8107a3d0-ffffffff8107a3e9: unwind_next_frame (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool unwind_next_frame(struct unwind_state *state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/unwind_frame.c (ffffffff8107c580)
Location: arch/x86/kernel/unwind_frame.c:260
Inline: True
Inline callers:
  - arch/x86/kernel/unwind_frame.c:__unwind_start
Direct callers:
  - arch/x86/events/core.c:perf_callchain_kernel
  - arch/x86/kernel/dumpstack.c:show_trace_log_lvl
  - arch/x86/kernel/stacktrace.c:arch_stack_walk_reliable
  - arch/x86/kernel/stacktrace.c:arch_stack_walk
  - arch/x86/kernel/unwind_frame.c:__unwind_start
```
**Symbols:**

```
ffffffff8107c320-ffffffff8107c4cd: unwind_next_frame.part.0 (STB_LOCAL)
ffffffff8107c6ed-ffffffff8107c741: unwind_next_frame.part.0.cold (STB_LOCAL)
ffffffff8107c4d0-ffffffff8107c4e9: unwind_next_frame (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
