# Function: <code>save_stack_trace</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void save_stack_trace(struct stack_trace *trace);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/stacktrace.c (ffffffff8103e510)
Location: arch/x86/kernel/stacktrace.c:61
Inline: False
Direct callers:
  - kernel/trace/trace.c:__ftrace_trace_stack
  - kernel/trace/trace.c:__ftrace_trace_stack
  - kernel/trace/trace_stack.c:check_stack
  - mm/slub.c:set_track
```
**Symbols:**

```
ffffffff8103e510-ffffffff8103e556: save_stack_trace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void save_stack_trace(struct stack_trace *trace);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/stacktrace.c (ffffffff8103e350)
Location: arch/x86/kernel/stacktrace.c:65
Inline: False
Direct callers:
  - kernel/trace/trace.c:__ftrace_trace_stack
  - kernel/trace/trace.c:__ftrace_trace_stack
  - kernel/trace/trace_stack.c:check_stack
  - kernel/trace/trace_events_hist.c:event_hist_trigger
  - mm/slub.c:set_track
```
**Symbols:**

```
ffffffff8103e350-ffffffff8103e396: save_stack_trace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void save_stack_trace(struct stack_trace *trace);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/stacktrace.c (ffffffff8103dd60)
Location: arch/x86/kernel/stacktrace.c:55
Inline: False
Direct callers:
  - kernel/trace/trace.c:__ftrace_trace_stack
  - kernel/trace/trace.c:__ftrace_trace_stack
  - kernel/trace/trace_stack.c:check_stack
  - kernel/trace/trace_events_hist.c:event_hist_trigger
  - mm/slub.c:set_track
```
**Symbols:**

```
ffffffff8103dd60-ffffffff8103dd7d: save_stack_trace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void save_stack_trace(struct stack_trace *trace);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/stacktrace.c (ffffffff8103bdf0)
Location: arch/x86/kernel/stacktrace.c:57
Inline: False
Direct callers:
  - kernel/trace/trace.c:__ftrace_trace_stack
  - kernel/trace/trace.c:__ftrace_trace_stack
  - kernel/trace/trace_stack.c:check_stack
  - kernel/trace/trace_events_hist.c:event_hist_trigger
  - mm/slub.c:set_track
```
**Symbols:**

```
ffffffff8103bdf0-ffffffff8103be0d: save_stack_trace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void save_stack_trace(struct stack_trace *trace);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/stacktrace.c (ffffffff8103e810)
Location: arch/x86/kernel/stacktrace.c:57
Inline: False
Direct callers:
  - kernel/trace/trace.c:__ftrace_trace_stack
  - kernel/trace/trace.c:__ftrace_trace_stack
  - kernel/trace/trace_stack.c:check_stack
  - kernel/trace/trace_events_hist.c:event_hist_trigger
  - mm/slub.c:set_track
```
**Symbols:**

```
ffffffff8103e810-ffffffff8103e831: save_stack_trace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void save_stack_trace(struct stack_trace *trace);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/stacktrace.c (ffffffff8103fdd0)
Location: arch/x86/kernel/stacktrace.c:57
Inline: False
Direct callers:
  - kernel/trace/trace.c:__ftrace_trace_stack
  - kernel/trace/trace.c:__ftrace_trace_stack
  - kernel/trace/trace_stack.c:check_stack
  - kernel/trace/trace_events_hist.c:event_hist_trigger
  - mm/slub.c:set_track
```
**Symbols:**

```
ffffffff8103fdd0-ffffffff8103fdf1: save_stack_trace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void save_stack_trace(struct stack_trace *trace);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/stacktrace.c (ffffffff81041400)
Location: arch/x86/kernel/stacktrace.c:57
Inline: False
Direct callers:
  - kernel/trace/trace.c:__ftrace_trace_stack
  - kernel/trace/trace.c:__ftrace_trace_stack
  - kernel/trace/trace_stack.c:check_stack
  - kernel/trace/trace_events_hist.c:event_hist_trigger
  - mm/slub.c:set_track
```
**Symbols:**

```
ffffffff81041400-ffffffff81041421: save_stack_trace (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void save_stack_trace(struct stack_trace *trace);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/arm64/kernel/stacktrace.c (ffff800010093cc0)
Location: arch/arm64/kernel/stacktrace.c:206
Inline: False
Direct callers:
  - kernel/stacktrace.c:stack_trace_save
```
**Symbols:**

```
ffff800010093cc0-ffff800010093cf4: save_stack_trace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void save_stack_trace(struct stack_trace *trace);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/arm/kernel/stacktrace.c (c030ef80)
Location: arch/arm/kernel/stacktrace.c:161
Inline: False
Direct callers:
  - kernel/stacktrace.c:stack_trace_save
```
**Symbols:**

```
c030ef80-c030efb4: save_stack_trace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void save_stack_trace(struct stack_trace *trace);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/powerpc/kernel/stacktrace.c (c0000000000692d0)
Location: arch/powerpc/kernel/stacktrace.c:56
Inline: False
Direct callers:
  - kernel/stacktrace.c:stack_trace_save
```
**Symbols:**

```
c0000000000692d0-c000000000069320: save_stack_trace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void save_stack_trace(struct stack_trace *trace);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/riscv/kernel/stacktrace.c (ffffffe0000b7298)
Location: arch/riscv/kernel/stacktrace.c:163
Inline: False
Direct callers:
  - kernel/stacktrace.c:stack_trace_save
```
**Symbols:**

```
ffffffe0000b7298-ffffffe0000b72ce: save_stack_trace (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
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
</ul>
<b>Arch</b>
<ul>
</ul>
