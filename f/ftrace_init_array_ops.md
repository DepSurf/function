# Function: <code>ftrace_init_array_ops</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void ftrace_init_array_ops(struct trace_array *tr, ftrace_func_t func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81145900)
Location: kernel/trace/ftrace.c:5102
Inline: False
Direct callers:
  - kernel/trace/trace_functions.c:function_trace_init
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
```
**Symbols:**

```
ffffffff81145900-ffffffff81145969: ftrace_init_array_ops (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void ftrace_init_array_ops(struct trace_array *tr, ftrace_func_t func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff8114e100)
Location: kernel/trace/ftrace.c:5189
Inline: False
Direct callers:
  - kernel/trace/trace_functions.c:function_trace_init
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
```
**Symbols:**

```
ffffffff8114e100-ffffffff8114e169: ftrace_init_array_ops (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void ftrace_init_array_ops(struct trace_array *tr, ftrace_func_t func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81158040)
Location: kernel/trace/ftrace.c:5238
Inline: False
Direct callers:
  - kernel/trace/trace_functions.c:function_trace_init
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
```
**Symbols:**

```
ffffffff81158040-ffffffff811580a9: ftrace_init_array_ops (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void ftrace_init_array_ops(struct trace_array *tr, ftrace_func_t func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff8115b310)
Location: kernel/trace/ftrace.c:5972
Inline: False
Direct callers:
  - kernel/trace/trace_functions.c:function_trace_init
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
```
**Symbols:**

```
ffffffff8115b310-ffffffff8115b363: ftrace_init_array_ops (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void ftrace_init_array_ops(struct trace_array *tr, ftrace_func_t func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81168400)
Location: kernel/trace/ftrace.c:6277
Inline: False
Direct callers:
  - kernel/trace/trace_functions.c:function_trace_init
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
```
**Symbols:**

```
ffffffff81168400-ffffffff81168453: ftrace_init_array_ops (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void ftrace_init_array_ops(struct trace_array *tr, ftrace_func_t func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81177100)
Location: kernel/trace/ftrace.c:6263
Inline: False
Direct callers:
  - kernel/trace/trace_functions.c:function_trace_init
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
```
**Symbols:**

```
ffffffff81177100-ffffffff81177153: ftrace_init_array_ops (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void ftrace_init_array_ops(struct trace_array *tr, ftrace_func_t func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81184d50)
Location: kernel/trace/ftrace.c:6202
Inline: False
Direct callers:
  - kernel/trace/trace_functions.c:function_trace_init
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
```
**Symbols:**

```
ffffffff81184d50-ffffffff81184da3: ftrace_init_array_ops (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void ftrace_init_array_ops(struct trace_array *tr, ftrace_func_t func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/ftrace.c (0)
Location: kernel/trace/ftrace.c:6250
Inline: False
Direct callers:
  - kernel/trace/trace_functions.c:function_trace_init
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
```
**Symbols:**

```
ffffffff811923fd-ffffffff8119242d: ftrace_init_array_ops.cold (STB_LOCAL)
ffffffff81191b40-ffffffff81191b7d: ftrace_init_array_ops (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void ftrace_init_array_ops(struct trace_array *tr, ftrace_func_t func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/ftrace.c (0)
Location: kernel/trace/ftrace.c:6283
Inline: False
Direct callers:
  - kernel/trace/trace_functions.c:function_trace_init
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
```
**Symbols:**

```
ffffffff8119e0d3-ffffffff8119e0ed: ftrace_init_array_ops.cold (STB_LOCAL)
ffffffff8119db70-ffffffff8119dbb0: ftrace_init_array_ops (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void ftrace_init_array_ops(struct trace_array *tr, ftrace_func_t func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/ftrace.c (0)
Location: kernel/trace/ftrace.c:6781
Inline: False
Direct callers:
  - kernel/trace/trace_functions.c:function_trace_init
  - kernel/trace/trace_sched_wakeup.c:wakeup_dl_tracer_init
  - kernel/trace/trace_sched_wakeup.c:wakeup_rt_tracer_init
  - kernel/trace/trace_sched_wakeup.c:wakeup_tracer_init
```
**Symbols:**

```
ffffffff811b499f-ffffffff811b49b9: ftrace_init_array_ops.cold (STB_LOCAL)
ffffffff811b42c0-ffffffff811b4300: ftrace_init_array_ops (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void ftrace_init_array_ops(struct trace_array *tr, ftrace_func_t func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/ftrace.c (0)
Location: kernel/trace/ftrace.c:6950
Inline: False
Direct callers:
  - kernel/trace/trace_functions.c:function_trace_init
  - kernel/trace/trace_sched_wakeup.c:wakeup_dl_tracer_init
  - kernel/trace/trace_sched_wakeup.c:wakeup_rt_tracer_init
  - kernel/trace/trace_sched_wakeup.c:wakeup_tracer_init
```
**Symbols:**

```
ffffffff81be546d-ffffffff81be5487: ftrace_init_array_ops.cold (STB_LOCAL)
ffffffff811b1f90-ffffffff811b1fd0: ftrace_init_array_ops (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void ftrace_init_array_ops(struct trace_array *tr, ftrace_func_t func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/ftrace.c (0)
Location: kernel/trace/ftrace.c:6955
Inline: False
Direct callers:
  - kernel/trace/trace_functions.c:function_trace_init
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
```
**Symbols:**

```
ffffffff81bd7269-ffffffff81bd7283: ftrace_init_array_ops.cold (STB_LOCAL)
ffffffff811b2a90-ffffffff811b2ad0: ftrace_init_array_ops (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void ftrace_init_array_ops(struct trace_array *tr, ftrace_func_t func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/ftrace.c (0)
Location: kernel/trace/ftrace.c:6956
Inline: False
Direct callers:
  - kernel/trace/trace_functions.c:function_trace_init
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
```
**Symbols:**

```
ffffffff81cb483b-ffffffff81cb4855: ftrace_init_array_ops.cold (STB_LOCAL)
ffffffff811dc9c0-ffffffff811dca00: ftrace_init_array_ops (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void ftrace_init_array_ops(struct trace_array *tr, ftrace_func_t func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/ftrace.c (0)
Location: kernel/trace/ftrace.c:7397
Inline: False
Direct callers:
  - kernel/trace/trace_functions.c:function_trace_init
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
```
**Symbols:**

```
ffffffff81e65895-ffffffff81e658af: ftrace_init_array_ops.cold (STB_LOCAL)
ffffffff81212f30-ffffffff81212f7a: ftrace_init_array_ops (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void ftrace_init_array_ops(struct trace_array *tr, ftrace_func_t func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff8125c690)
Location: kernel/trace/ftrace.c:7513
Inline: False
Direct callers:
  - kernel/trace/trace_functions.c:function_trace_init
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
```
**Symbols:**

```
ffffffff8125c690-ffffffff8125c6ed: ftrace_init_array_ops (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void ftrace_init_array_ops(struct trace_array *tr, ftrace_func_t func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff812735d0)
Location: kernel/trace/ftrace.c:7328
Inline: False
Direct callers:
  - kernel/trace/trace_functions.c:function_trace_init
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
```
**Symbols:**

```
ffffffff812735d0-ffffffff8127362d: ftrace_init_array_ops (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void ftrace_init_array_ops(struct trace_array *tr, ftrace_func_t func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff8128db60)
Location: kernel/trace/ftrace.c:7328
Inline: False
Direct callers:
  - kernel/trace/trace_functions.c:function_trace_init
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
```
**Symbols:**

```
ffffffff8128db60-ffffffff8128dbbd: ftrace_init_array_ops (STB_GLOBAL)
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
void ftrace_init_array_ops(struct trace_array *tr, ftrace_func_t func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffff800010216a60)
Location: kernel/trace/ftrace.c:6283
Inline: False
Direct callers:
  - kernel/trace/trace_functions.c:function_trace_init
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
```
**Symbols:**

```
ffff800010216a60-ffff800010216acc: ftrace_init_array_ops (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void ftrace_init_array_ops(struct trace_array *tr, ftrace_func_t func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (c04557c4)
Location: kernel/trace/ftrace.c:6283
Inline: False
Direct callers:
  - kernel/trace/trace_functions.c:function_trace_init
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
```
**Symbols:**

```
c04557c4-c0455840: ftrace_init_array_ops (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void ftrace_init_array_ops(struct trace_array *tr, ftrace_func_t func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (c000000000298b40)
Location: kernel/trace/ftrace.c:6283
Inline: False
Direct callers:
  - kernel/trace/trace_functions.c:function_trace_init
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
```
**Symbols:**

```
c000000000298b40-c000000000298bd4: ftrace_init_array_ops (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void ftrace_init_array_ops(struct trace_array *tr, ftrace_func_t func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffe000176510)
Location: kernel/trace/ftrace.c:6283
Inline: False
Direct callers:
  - kernel/trace/trace_functions.c:function_trace_init
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
```
**Symbols:**

```
ffffffe000176510-ffffffe000176574: ftrace_init_array_ops (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
void ftrace_init_array_ops(struct trace_array *tr, ftrace_func_t func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/ftrace.c (0)
Location: kernel/trace/ftrace.c:6283
Inline: False
Direct callers:
  - kernel/trace/trace_functions.c:function_trace_init
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
```
**Symbols:**

```
ffffffff811966f3-ffffffff8119670d: ftrace_init_array_ops.cold (STB_LOCAL)
ffffffff81196190-ffffffff811961d0: ftrace_init_array_ops (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void ftrace_init_array_ops(struct trace_array *tr, ftrace_func_t func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/ftrace.c (0)
Location: kernel/trace/ftrace.c:6283
Inline: False
Direct callers:
  - kernel/trace/trace_functions.c:function_trace_init
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
```
**Symbols:**

```
ffffffff81189802-ffffffff8118981c: ftrace_init_array_ops.cold (STB_LOCAL)
ffffffff811892a0-ffffffff811892e0: ftrace_init_array_ops (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void ftrace_init_array_ops(struct trace_array *tr, ftrace_func_t func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/ftrace.c (0)
Location: kernel/trace/ftrace.c:6283
Inline: False
Direct callers:
  - kernel/trace/trace_functions.c:function_trace_init
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
```
**Symbols:**

```
ffffffff811944c3-ffffffff811944dd: ftrace_init_array_ops.cold (STB_LOCAL)
ffffffff81193f60-ffffffff81193fa0: ftrace_init_array_ops (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void ftrace_init_array_ops(struct trace_array *tr, ftrace_func_t func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/ftrace.c (0)
Location: kernel/trace/ftrace.c:6283
Inline: False
Direct callers:
  - kernel/trace/trace_functions.c:function_trace_init
  - kernel/trace/trace_sched_wakeup.c:__wakeup_tracer_init
```
**Symbols:**

```
ffffffff811a20b3-ffffffff811a20cd: ftrace_init_array_ops.cold (STB_LOCAL)
ffffffff811a1b30-ffffffff811a1b70: ftrace_init_array_ops (STB_GLOBAL)
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
