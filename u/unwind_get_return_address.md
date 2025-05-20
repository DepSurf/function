# Function: <code>unwind_get_return_address</code>

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
long unsigned int unwind_get_return_address(struct unwind_state *state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/unwind_frame.c (ffffffff81069a00)
Location: arch/x86/kernel/unwind_frame.c:55
Inline: False
Direct callers:
  - arch/x86/events/core.c:perf_callchain_kernel
  - arch/x86/kernel/stacktrace.c:__save_stack_trace
```
**Symbols:**

```
ffffffff81069a00-ffffffff81069a5d: unwind_get_return_address (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
long unsigned int unwind_get_return_address(struct unwind_state *state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/unwind_frame.c (ffffffff81068f00)
Location: arch/x86/kernel/unwind_frame.c:69
Inline: True
Direct callers:
  - arch/x86/events/core.c:perf_callchain_kernel
  - arch/x86/kernel/stacktrace.c:__save_stack_trace
```
**Symbols:**

```
ffffffff81068f00-ffffffff81068f2f: unwind_get_return_address (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
long unsigned int unwind_get_return_address(struct unwind_state *state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/unwind_frame.c (ffffffff8106d780)
Location: arch/x86/kernel/unwind_frame.c:13
Inline: True
Direct callers:
  - arch/x86/events/core.c:perf_callchain_kernel
  - arch/x86/kernel/stacktrace.c:save_stack_trace_tsk_reliable
  - arch/x86/kernel/stacktrace.c:__save_stack_trace
```
**Symbols:**

```
ffffffff8106d780-ffffffff8106d7af: unwind_get_return_address (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
long unsigned int unwind_get_return_address(struct unwind_state *state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/unwind_frame.c (ffffffff810705d0)
Location: arch/x86/kernel/unwind_frame.c:13
Inline: True
Direct callers:
  - arch/x86/events/core.c:perf_callchain_kernel
  - arch/x86/kernel/stacktrace.c:save_stack_trace_tsk_reliable
  - arch/x86/kernel/stacktrace.c:__save_stack_trace
```
**Symbols:**

```
ffffffff810705d0-ffffffff810705ff: unwind_get_return_address (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
long unsigned int unwind_get_return_address(struct unwind_state *state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/unwind_frame.c (ffffffff810765a0)
Location: arch/x86/kernel/unwind_frame.c:13
Inline: True
Direct callers:
  - arch/x86/events/core.c:perf_callchain_kernel
  - arch/x86/kernel/stacktrace.c:save_stack_trace_tsk_reliable
  - arch/x86/kernel/stacktrace.c:__save_stack_trace
```
**Symbols:**

```
ffffffff810765a0-ffffffff810765cf: unwind_get_return_address (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
long unsigned int unwind_get_return_address(struct unwind_state *state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/unwind_frame.c (ffffffff8107a150)
Location: arch/x86/kernel/unwind_frame.c:14
Inline: True
Direct callers:
  - arch/x86/events/core.c:perf_callchain_kernel
  - arch/x86/kernel/stacktrace.c:arch_stack_walk_reliable
  - arch/x86/kernel/stacktrace.c:arch_stack_walk
```
**Symbols:**

```
ffffffff8107a150-ffffffff8107a17f: unwind_get_return_address (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
long unsigned int unwind_get_return_address(struct unwind_state *state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/unwind_frame.c (ffffffff8107b240)
Location: arch/x86/kernel/unwind_frame.c:14
Inline: True
Direct callers:
  - arch/x86/events/core.c:perf_callchain_kernel
  - arch/x86/kernel/stacktrace.c:arch_stack_walk_reliable
  - arch/x86/kernel/stacktrace.c:arch_stack_walk
```
**Symbols:**

```
ffffffff8107b240-ffffffff8107b26f: unwind_get_return_address (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
long unsigned int unwind_get_return_address(struct unwind_state *state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/unwind_frame.c (ffffffff81082650)
Location: arch/x86/kernel/unwind_frame.c:14
Inline: True
Direct callers:
  - arch/x86/events/core.c:perf_callchain_kernel
  - arch/x86/kernel/stacktrace.c:arch_stack_walk_reliable
  - arch/x86/kernel/stacktrace.c:arch_stack_walk
```
**Symbols:**

```
ffffffff81082650-ffffffff81082685: unwind_get_return_address (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
long unsigned int unwind_get_return_address(struct unwind_state *state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/unwind_frame.c (ffffffff81082100)
Location: arch/x86/kernel/unwind_frame.c:14
Inline: True
Direct callers:
  - arch/x86/events/core.c:perf_callchain_kernel
  - arch/x86/kernel/stacktrace.c:arch_stack_walk_reliable
  - arch/x86/kernel/stacktrace.c:arch_stack_walk
```
**Symbols:**

```
ffffffff81082100-ffffffff81082135: unwind_get_return_address (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
long unsigned int unwind_get_return_address(struct unwind_state *state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/unwind_frame.c (ffffffff81082f20)
Location: arch/x86/kernel/unwind_frame.c:14
Inline: True
Direct callers:
  - arch/x86/events/core.c:perf_callchain_kernel
  - arch/x86/kernel/stacktrace.c:arch_stack_walk_reliable
  - arch/x86/kernel/stacktrace.c:arch_stack_walk
```
**Symbols:**

```
ffffffff81082f20-ffffffff81082f55: unwind_get_return_address (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
long unsigned int unwind_get_return_address(struct unwind_state *state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/unwind_frame.c (ffffffff81091ff0)
Location: arch/x86/kernel/unwind_frame.c:14
Inline: True
Direct callers:
  - arch/x86/events/core.c:perf_callchain_kernel
  - arch/x86/kernel/stacktrace.c:arch_stack_walk_reliable
  - arch/x86/kernel/stacktrace.c:arch_stack_walk
```
**Symbols:**

```
ffffffff81091ff0-ffffffff81092025: unwind_get_return_address (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long unsigned int unwind_get_return_address(struct unwind_state *state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/unwind_frame.c (ffffffff810a3000)
Location: arch/x86/kernel/unwind_frame.c:14
Inline: False
Direct callers:
  - arch/x86/events/core.c:perf_callchain_kernel
  - arch/x86/kernel/process.c:__get_wchan
  - arch/x86/kernel/stacktrace.c:arch_stack_walk_reliable
  - arch/x86/kernel/stacktrace.c:arch_stack_walk
```
**Symbols:**

```
ffffffff810a3000-ffffffff810a3047: unwind_get_return_address (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long unsigned int unwind_get_return_address(struct unwind_state *state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/unwind_frame.c (ffffffff810bb2f0)
Location: arch/x86/kernel/unwind_frame.c:14
Inline: False
Direct callers:
  - arch/x86/events/core.c:perf_callchain_kernel
  - arch/x86/kernel/process.c:__get_wchan
  - arch/x86/kernel/stacktrace.c:arch_stack_walk_reliable
  - arch/x86/kernel/stacktrace.c:arch_stack_walk
```
**Symbols:**

```
ffffffff810bb2f0-ffffffff810bb337: unwind_get_return_address (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long unsigned int unwind_get_return_address(struct unwind_state *state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/unwind_frame.c (ffffffff810be430)
Location: arch/x86/kernel/unwind_frame.c:14
Inline: False
Direct callers:
  - arch/x86/events/core.c:perf_callchain_kernel
  - arch/x86/kernel/process.c:__get_wchan
  - arch/x86/kernel/stacktrace.c:arch_stack_walk_reliable
  - arch/x86/kernel/stacktrace.c:arch_stack_walk
```
**Symbols:**

```
ffffffff810be430-ffffffff810be477: unwind_get_return_address (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long unsigned int unwind_get_return_address(struct unwind_state *state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/unwind_frame.c (ffffffff810c55b0)
Location: arch/x86/kernel/unwind_frame.c:14
Inline: False
Direct callers:
  - arch/x86/events/core.c:perf_callchain_kernel
  - arch/x86/kernel/process.c:__get_wchan
  - arch/x86/kernel/stacktrace.c:arch_stack_walk_reliable
  - arch/x86/kernel/stacktrace.c:arch_stack_walk
```
**Symbols:**

```
ffffffff810c55b0-ffffffff810c55f7: unwind_get_return_address (STB_GLOBAL)
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
long unsigned int unwind_get_return_address(struct unwind_state *state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/unwind_frame.c (ffffffff8107a240)
Location: arch/x86/kernel/unwind_frame.c:14
Inline: True
Direct callers:
  - arch/x86/events/core.c:perf_callchain_kernel
  - arch/x86/kernel/stacktrace.c:arch_stack_walk_reliable
  - arch/x86/kernel/stacktrace.c:arch_stack_walk
```
**Symbols:**

```
ffffffff8107a240-ffffffff8107a26f: unwind_get_return_address (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
long unsigned int unwind_get_return_address(struct unwind_state *state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/unwind_frame.c (ffffffff81069970)
Location: arch/x86/kernel/unwind_frame.c:14
Inline: True
Direct callers:
  - arch/x86/events/core.c:perf_callchain_kernel
  - arch/x86/kernel/stacktrace.c:arch_stack_walk_reliable
  - arch/x86/kernel/stacktrace.c:arch_stack_walk
```
**Symbols:**

```
ffffffff81069970-ffffffff8106999f: unwind_get_return_address (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
long unsigned int unwind_get_return_address(struct unwind_state *state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/unwind_frame.c (ffffffff8107a1f0)
Location: arch/x86/kernel/unwind_frame.c:14
Inline: True
Direct callers:
  - arch/x86/events/core.c:perf_callchain_kernel
  - arch/x86/kernel/stacktrace.c:arch_stack_walk_reliable
  - arch/x86/kernel/stacktrace.c:arch_stack_walk
```
**Symbols:**

```
ffffffff8107a1f0-ffffffff8107a21f: unwind_get_return_address (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
long unsigned int unwind_get_return_address(struct unwind_state *state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/unwind_frame.c (ffffffff8107c2f0)
Location: arch/x86/kernel/unwind_frame.c:14
Inline: True
Direct callers:
  - arch/x86/events/core.c:perf_callchain_kernel
  - arch/x86/kernel/stacktrace.c:arch_stack_walk_reliable
  - arch/x86/kernel/stacktrace.c:arch_stack_walk
```
**Symbols:**

```
ffffffff8107c2f0-ffffffff8107c31f: unwind_get_return_address (STB_GLOBAL)
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
