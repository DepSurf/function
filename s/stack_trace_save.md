# Function: <code>stack_trace_save</code>

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
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
unsigned int stack_trace_save(long unsigned int *store, unsigned int size, unsigned int skipnr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stacktrace.c (ffffffff81125d40)
Location: kernel/stacktrace.c:113
Inline: False
Direct callers:
  - kernel/trace/trace.c:__ftrace_trace_stack
  - kernel/trace/trace_stack.c:stack_trace_call
  - kernel/trace/trace_events_hist.c:event_hist_trigger
  - mm/slub.c:set_track
```
**Symbols:**

```
ffffffff81125d40-ffffffff81125da5: stack_trace_save (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
unsigned int stack_trace_save(long unsigned int *store, unsigned int size, unsigned int skipnr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stacktrace.c (ffffffff81131d10)
Location: kernel/stacktrace.c:113
Inline: False
Direct callers:
  - kernel/trace/trace.c:__ftrace_trace_stack
  - kernel/trace/trace_stack.c:stack_trace_call
  - kernel/trace/trace_events_hist.c:event_hist_trigger
  - mm/slub.c:set_track
```
**Symbols:**

```
ffffffff81131d10-ffffffff81131d75: stack_trace_save (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
unsigned int stack_trace_save(long unsigned int *store, unsigned int size, unsigned int skipnr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stacktrace.c (ffffffff81141130)
Location: kernel/stacktrace.c:113
Inline: False
Direct callers:
  - kernel/trace/trace.c:__ftrace_trace_stack
  - kernel/trace/trace_stack.c:check_stack
  - kernel/trace/trace_events_hist.c:event_hist_trigger
```
**Symbols:**

```
ffffffff81141130-ffffffff81141195: stack_trace_save (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
unsigned int stack_trace_save(long unsigned int *store, unsigned int size, unsigned int skipnr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stacktrace.c (ffffffff8113d3d0)
Location: kernel/stacktrace.c:111
Inline: False
Direct callers:
  - kernel/trace/trace.c:__ftrace_trace_stack
  - kernel/trace/trace_stack.c:check_stack
  - kernel/trace/trace_events_hist.c:event_hist_trigger
```
**Symbols:**

```
ffffffff8113d3d0-ffffffff8113d435: stack_trace_save (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
unsigned int stack_trace_save(long unsigned int *store, unsigned int size, unsigned int skipnr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stacktrace.c (ffffffff8113e620)
Location: kernel/stacktrace.c:111
Inline: False
Direct callers:
  - kernel/trace/trace.c:__ftrace_trace_stack
  - kernel/trace/trace_stack.c:check_stack
  - kernel/trace/trace_events_hist.c:event_hist_trigger
```
**Symbols:**

```
ffffffff8113e620-ffffffff8113e685: stack_trace_save (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
unsigned int stack_trace_save(long unsigned int *store, unsigned int size, unsigned int skipnr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stacktrace.c (ffffffff81161ab0)
Location: kernel/stacktrace.c:111
Inline: False
Direct callers:
  - kernel/trace/trace.c:__ftrace_trace_stack
  - kernel/trace/trace_stack.c:check_stack
  - kernel/trace/trace_events_hist.c:event_hist_trigger
  - mm/kfence/core.c:metadata_update_state
  - mm/kfence/report.c:kfence_report_error
```
**Symbols:**

```
ffffffff81161ab0-ffffffff81161b15: stack_trace_save (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
unsigned int stack_trace_save(long unsigned int *store, unsigned int size, unsigned int skipnr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stacktrace.c (ffffffff81194970)
Location: kernel/stacktrace.c:112
Inline: False
Direct callers:
  - kernel/trace/trace.c:__ftrace_trace_stack
  - kernel/trace/trace_stack.c:check_stack
  - kernel/trace/trace_events_hist.c:event_hist_trigger
  - mm/slub.c:set_track_prepare
  - mm/kfence/core.c:__kfence_alloc
  - mm/kfence/core.c:metadata_update_state
  - mm/kfence/report.c:kfence_report_error
```
**Symbols:**

```
ffffffff81194970-ffffffff811949e1: stack_trace_save (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
unsigned int stack_trace_save(long unsigned int *store, unsigned int size, unsigned int skipnr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stacktrace.c (ffffffff811d25d0)
Location: kernel/stacktrace.c:112
Inline: False
Direct callers:
  - kernel/trace/trace.c:__ftrace_trace_stack
  - kernel/trace/trace_stack.c:check_stack
  - kernel/trace/trace_events_hist.c:event_hist_trigger
  - mm/slub.c:set_track_prepare
  - mm/kfence/core.c:__kfence_alloc
  - mm/kfence/core.c:metadata_update_state
  - mm/kfence/report.c:kfence_report_error
```
**Symbols:**

```
ffffffff811d25d0-ffffffff811d2641: stack_trace_save (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
unsigned int stack_trace_save(long unsigned int *store, unsigned int size, unsigned int skipnr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stacktrace.c (ffffffff811e68c0)
Location: kernel/stacktrace.c:112
Inline: False
Direct callers:
  - kernel/trace/trace.c:__ftrace_trace_stack
  - kernel/trace/trace_osnoise.c:timerlat_irq
  - kernel/trace/trace_osnoise.c:timerlat_irq
  - kernel/trace/trace_stack.c:check_stack
  - kernel/trace/trace_events_hist.c:event_hist_trigger
  - kernel/trace/trace_events_hist.c:hist_trigger_elt_update
  - kernel/trace/trace_events_hist.c:__update_field_vars
  - mm/slub.c:set_track_prepare
  - mm/kfence/core.c:__kfence_alloc
  - mm/kfence/core.c:metadata_update_state
  - mm/kfence/report.c:kfence_report_error
```
**Symbols:**

```
ffffffff811e68c0-ffffffff811e6931: stack_trace_save (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
unsigned int stack_trace_save(long unsigned int *store, unsigned int size, unsigned int skipnr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stacktrace.c (ffffffff811fc610)
Location: kernel/stacktrace.c:112
Inline: False
Direct callers:
  - kernel/trace/trace.c:__ftrace_trace_stack
  - kernel/trace/trace_osnoise.c:timerlat_irq
  - kernel/trace/trace_osnoise.c:timerlat_irq
  - kernel/trace/trace_stack.c:check_stack
  - kernel/trace/trace_events_hist.c:event_hist_trigger
  - kernel/trace/trace_events_hist.c:hist_trigger_elt_update
  - kernel/trace/trace_events_hist.c:__update_field_vars
  - mm/slub.c:set_track_prepare
  - mm/kfence/core.c:__kfence_alloc
  - mm/kfence/core.c:metadata_update_state
  - mm/kfence/report.c:kfence_report_error
```
**Symbols:**

```
ffffffff811fc610-ffffffff811fc681: stack_trace_save (STB_GLOBAL)
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
unsigned int stack_trace_save(long unsigned int *store, unsigned int size, unsigned int skipnr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stacktrace.c (ffff8000101997a0)
Location: kernel/stacktrace.c:272
Inline: False
Direct callers:
  - kernel/trace/trace.c:__ftrace_trace_stack
  - kernel/trace/trace_stack.c:stack_trace_call
  - kernel/trace/trace_events_hist.c:event_hist_trigger
  - mm/slub.c:set_track
```
**Symbols:**

```
ffff8000101997a0-ffff800010199818: stack_trace_save (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
unsigned int stack_trace_save(long unsigned int *store, unsigned int size, unsigned int skipnr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stacktrace.c (c03e41c0)
Location: kernel/stacktrace.c:272
Inline: False
Direct callers:
  - kernel/trace/trace.c:__ftrace_trace_stack
  - kernel/trace/trace_stack.c:stack_trace_call
  - mm/slub.c:set_track
```
**Symbols:**

```
c03e41c0-c03e4238: stack_trace_save (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
unsigned int stack_trace_save(long unsigned int *store, unsigned int size, unsigned int skipnr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stacktrace.c (c0000000001f9970)
Location: kernel/stacktrace.c:272
Inline: False
Direct callers:
  - arch/powerpc/kernel/eeh_event.c:__eeh_send_failure_event
  - kernel/trace/trace.c:__ftrace_trace_stack
  - kernel/trace/trace_stack.c:stack_trace_call
  - kernel/trace/trace_events_hist.c:event_hist_trigger
  - mm/slub.c:set_track
```
**Symbols:**

```
c0000000001f9970-c0000000001f99f4: stack_trace_save (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
unsigned int stack_trace_save(long unsigned int *store, unsigned int size, unsigned int skipnr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stacktrace.c (ffffffe000129dc8)
Location: kernel/stacktrace.c:272
Inline: False
Direct callers:
  - kernel/trace/trace.c:__ftrace_trace_stack
  - kernel/trace/trace_stack.c:stack_trace_call
  - mm/slub.c:set_track
```
**Symbols:**

```
ffffffe000129dc8-ffffffe000129e1a: stack_trace_save (STB_GLOBAL)
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
unsigned int stack_trace_save(long unsigned int *store, unsigned int size, unsigned int skipnr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stacktrace.c (ffffffff8112a4c0)
Location: kernel/stacktrace.c:113
Inline: False
Direct callers:
  - kernel/trace/trace.c:__ftrace_trace_stack
  - kernel/trace/trace_stack.c:stack_trace_call
  - kernel/trace/trace_events_hist.c:event_hist_trigger
  - mm/slub.c:set_track
```
**Symbols:**

```
ffffffff8112a4c0-ffffffff8112a525: stack_trace_save (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
unsigned int stack_trace_save(long unsigned int *store, unsigned int size, unsigned int skipnr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stacktrace.c (ffffffff8111cd30)
Location: kernel/stacktrace.c:113
Inline: False
Direct callers:
  - kernel/trace/trace.c:__ftrace_trace_stack
  - kernel/trace/trace_stack.c:stack_trace_call
  - kernel/trace/trace_events_hist.c:event_hist_trigger
  - mm/slub.c:set_track
```
**Symbols:**

```
ffffffff8111cd30-ffffffff8111cd95: stack_trace_save (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
unsigned int stack_trace_save(long unsigned int *store, unsigned int size, unsigned int skipnr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stacktrace.c (ffffffff811281e0)
Location: kernel/stacktrace.c:113
Inline: False
Direct callers:
  - kernel/trace/trace.c:__ftrace_trace_stack
  - kernel/trace/trace_stack.c:stack_trace_call
  - kernel/trace/trace_events_hist.c:event_hist_trigger
  - mm/slub.c:set_track
```
**Symbols:**

```
ffffffff811281e0-ffffffff81128245: stack_trace_save (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
unsigned int stack_trace_save(long unsigned int *store, unsigned int size, unsigned int skipnr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stacktrace.c (ffffffff81134870)
Location: kernel/stacktrace.c:113
Inline: False
Direct callers:
  - kernel/trace/trace.c:__ftrace_trace_stack
  - kernel/trace/trace_stack.c:stack_trace_call
  - kernel/trace/trace_events_hist.c:event_hist_trigger
  - mm/slub.c:set_track
```
**Symbols:**

```
ffffffff81134870-ffffffff811348d5: stack_trace_save (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
