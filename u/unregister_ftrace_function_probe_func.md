# Function: <code>unregister_ftrace_function_probe_func</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void unregister_ftrace_function_probe_func(char *glob, struct ftrace_probe_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81144cd0)
Location: kernel/trace/ftrace.c:3919
Inline: False
Direct callers:
  - kernel/trace/trace.c:ftrace_trace_snapshot_callback
  - kernel/trace/trace_events.c:event_enable_func
```
**Symbols:**

```
ffffffff81144cd0-ffffffff81144ce2: unregister_ftrace_function_probe_func (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void unregister_ftrace_function_probe_func(char *glob, struct ftrace_probe_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff8114d430)
Location: kernel/trace/ftrace.c:3956
Inline: False
Direct callers:
  - kernel/trace/trace.c:ftrace_trace_snapshot_callback
  - kernel/trace/trace_events.c:event_enable_func
```
**Symbols:**

```
ffffffff8114d430-ffffffff8114d442: unregister_ftrace_function_probe_func (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void unregister_ftrace_function_probe_func(char *glob, struct ftrace_probe_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81157370)
Location: kernel/trace/ftrace.c:3985
Inline: False
Direct callers:
  - kernel/trace/trace.c:ftrace_trace_snapshot_callback
  - kernel/trace/trace_events.c:event_enable_func
```
**Symbols:**

```
ffffffff81157370-ffffffff81157382: unregister_ftrace_function_probe_func (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int unregister_ftrace_function_probe_func(char *glob, struct trace_array *tr, struct ftrace_probe_ops *probe_ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81159fa0)
Location: kernel/trace/ftrace.c:4466
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:clear_ftrace_function_probes
  - kernel/trace/trace.c:ftrace_trace_snapshot_callback
  - kernel/trace/trace_events.c:event_enable_func
```
**Symbols:**

```
ffffffff81159fa0-ffffffff8115a4a3: unregister_ftrace_function_probe_func (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int unregister_ftrace_function_probe_func(char *glob, struct trace_array *tr, struct ftrace_probe_ops *probe_ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81166ab0)
Location: kernel/trace/ftrace.c:4434
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:clear_ftrace_function_probes
  - kernel/trace/trace.c:ftrace_trace_snapshot_callback
  - kernel/trace/trace_events.c:event_enable_func
```
**Symbols:**

```
ffffffff81166ab0-ffffffff81166fad: unregister_ftrace_function_probe_func (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int unregister_ftrace_function_probe_func(char *glob, struct trace_array *tr, struct ftrace_probe_ops *probe_ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff811757a0)
Location: kernel/trace/ftrace.c:4422
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:clear_ftrace_function_probes
  - kernel/trace/trace.c:ftrace_trace_snapshot_callback
  - kernel/trace/trace_events.c:event_enable_func
```
**Symbols:**

```
ffffffff811757a0-ffffffff81175cbf: unregister_ftrace_function_probe_func (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int unregister_ftrace_function_probe_func(char *glob, struct trace_array *tr, struct ftrace_probe_ops *probe_ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff811833e0)
Location: kernel/trace/ftrace.c:4381
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:clear_ftrace_function_probes
  - kernel/trace/trace.c:ftrace_trace_snapshot_callback
  - kernel/trace/trace_events.c:event_enable_func
```
**Symbols:**

```
ffffffff811833e0-ffffffff811838ff: unregister_ftrace_function_probe_func (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int unregister_ftrace_function_probe_func(char *glob, struct trace_array *tr, struct ftrace_probe_ops *probe_ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/ftrace.c (0)
Location: kernel/trace/ftrace.c:4429
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:clear_ftrace_function_probes
  - kernel/trace/trace.c:ftrace_trace_snapshot_callback
  - kernel/trace/trace_events.c:event_enable_func
```
**Symbols:**

```
ffffffff8119234d-ffffffff81192381: unregister_ftrace_function_probe_func.cold (STB_LOCAL)
ffffffff81190170-ffffffff81190687: unregister_ftrace_function_probe_func (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int unregister_ftrace_function_probe_func(char *glob, struct trace_array *tr, struct ftrace_probe_ops *probe_ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff8119c140)
Location: kernel/trace/ftrace.c:4453
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:clear_ftrace_function_probes
  - kernel/trace/trace.c:ftrace_trace_snapshot_callback
  - kernel/trace/trace_events.c:event_enable_func
```
**Symbols:**

```
ffffffff8119c140-ffffffff8119c673: unregister_ftrace_function_probe_func (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int unregister_ftrace_function_probe_func(char *glob, struct trace_array *tr, struct ftrace_probe_ops *probe_ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff811b2260)
Location: kernel/trace/ftrace.c:4580
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:clear_ftrace_function_probes
  - kernel/trace/trace.c:ftrace_trace_snapshot_callback
  - kernel/trace/trace_functions.c:ftrace_cpudump_callback
  - kernel/trace/trace_functions.c:ftrace_dump_callback
  - kernel/trace/trace_functions.c:ftrace_stacktrace_callback
  - kernel/trace/trace_events.c:event_enable_func
```
**Symbols:**

```
ffffffff811b2260-ffffffff811b27a4: unregister_ftrace_function_probe_func (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int unregister_ftrace_function_probe_func(char *glob, struct trace_array *tr, struct ftrace_probe_ops *probe_ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff811afcd0)
Location: kernel/trace/ftrace.c:4657
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:clear_ftrace_function_probes
  - kernel/trace/trace.c:ftrace_trace_snapshot_callback
  - kernel/trace/trace_functions.c:ftrace_cpudump_callback
  - kernel/trace/trace_functions.c:ftrace_dump_callback
  - kernel/trace/trace_functions.c:ftrace_stacktrace_callback
  - kernel/trace/trace_events.c:event_enable_func
```
**Symbols:**

```
ffffffff811afcd0-ffffffff811b0214: unregister_ftrace_function_probe_func (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int unregister_ftrace_function_probe_func(char *glob, struct trace_array *tr, struct ftrace_probe_ops *probe_ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff811b05e0)
Location: kernel/trace/ftrace.c:4657
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:clear_ftrace_function_probes
  - kernel/trace/trace.c:ftrace_trace_snapshot_callback
  - kernel/trace/trace_functions.c:ftrace_cpudump_callback
  - kernel/trace/trace_functions.c:ftrace_dump_callback
  - kernel/trace/trace_functions.c:ftrace_stacktrace_callback
  - kernel/trace/trace_events.c:event_enable_func
```
**Symbols:**

```
ffffffff811b05e0-ffffffff811b0b23: unregister_ftrace_function_probe_func (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int unregister_ftrace_function_probe_func(char *glob, struct trace_array *tr, struct ftrace_probe_ops *probe_ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/ftrace.c (0)
Location: kernel/trace/ftrace.c:4657
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:clear_ftrace_function_probes
  - kernel/trace/trace.c:ftrace_trace_snapshot_callback
  - kernel/trace/trace_functions.c:ftrace_cpudump_callback
  - kernel/trace/trace_functions.c:ftrace_dump_callback
  - kernel/trace/trace_functions.c:ftrace_stacktrace_callback
  - kernel/trace/trace_events.c:event_enable_func
```
**Symbols:**

```
ffffffff81cb472e-ffffffff81cb4755: unregister_ftrace_function_probe_func.cold (STB_LOCAL)
ffffffff811da460-ffffffff811da9ad: unregister_ftrace_function_probe_func (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int unregister_ftrace_function_probe_func(char *glob, struct trace_array *tr, struct ftrace_probe_ops *probe_ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/ftrace.c (0)
Location: kernel/trace/ftrace.c:4799
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:clear_ftrace_function_probes
  - kernel/trace/trace.c:ftrace_trace_snapshot_callback
  - kernel/trace/trace_events.c:event_enable_func
```
**Symbols:**

```
ffffffff81e656f4-ffffffff81e65737: unregister_ftrace_function_probe_func.cold (STB_LOCAL)
ffffffff81210200-ffffffff812108a3: unregister_ftrace_function_probe_func (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int unregister_ftrace_function_probe_func(char *glob, struct trace_array *tr, struct ftrace_probe_ops *probe_ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/ftrace.c (0)
Location: kernel/trace/ftrace.c:4820
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:clear_ftrace_function_probes
  - kernel/trace/trace.c:ftrace_trace_snapshot_callback
  - kernel/trace/trace_events.c:event_enable_func
```
**Symbols:**

```
ffffffff8205ceea-ffffffff8205cf2d: unregister_ftrace_function_probe_func.cold (STB_LOCAL)
ffffffff81259640-ffffffff81259ce3: unregister_ftrace_function_probe_func (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int unregister_ftrace_function_probe_func(char *glob, struct trace_array *tr, struct ftrace_probe_ops *probe_ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/ftrace.c (0)
Location: kernel/trace/ftrace.c:4975
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:clear_ftrace_function_probes
  - kernel/trace/trace.c:ftrace_trace_snapshot_callback
  - kernel/trace/trace_events.c:event_enable_func
```
**Symbols:**

```
ffffffff820db87e-ffffffff820db8c1: unregister_ftrace_function_probe_func.cold (STB_LOCAL)
ffffffff81270a10-ffffffff812710a1: unregister_ftrace_function_probe_func (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int unregister_ftrace_function_probe_func(char *glob, struct trace_array *tr, struct ftrace_probe_ops *probe_ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/ftrace.c (0)
Location: kernel/trace/ftrace.c:4941
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:clear_ftrace_function_probes
  - kernel/trace/trace.c:ftrace_trace_snapshot_callback
  - kernel/trace/trace_events.c:event_enable_func
```
**Symbols:**

```
ffffffff821b75de-ffffffff821b7621: unregister_ftrace_function_probe_func.cold (STB_LOCAL)
ffffffff8128ae90-ffffffff8128b521: unregister_ftrace_function_probe_func (STB_GLOBAL)
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
int unregister_ftrace_function_probe_func(char *glob, struct trace_array *tr, struct ftrace_probe_ops *probe_ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffff800010215010)
Location: kernel/trace/ftrace.c:4453
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:clear_ftrace_function_probes
  - kernel/trace/trace.c:ftrace_trace_snapshot_callback
  - kernel/trace/trace_events.c:event_enable_func
```
**Symbols:**

```
ffff800010215010-ffff800010215464: unregister_ftrace_function_probe_func (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int unregister_ftrace_function_probe_func(char *glob, struct trace_array *tr, struct ftrace_probe_ops *probe_ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (c0453d4c)
Location: kernel/trace/ftrace.c:4453
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:clear_ftrace_function_probes
  - kernel/trace/trace.c:ftrace_trace_snapshot_callback
  - kernel/trace/trace_events.c:event_enable_func
```
**Symbols:**

```
c0453d4c-c04541e8: unregister_ftrace_function_probe_func (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int unregister_ftrace_function_probe_func(char *glob, struct trace_array *tr, struct ftrace_probe_ops *probe_ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (c000000000296610)
Location: kernel/trace/ftrace.c:4453
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:clear_ftrace_function_probes
  - kernel/trace/trace.c:ftrace_trace_snapshot_callback
  - kernel/trace/trace_events.c:event_enable_func
```
**Symbols:**

```
c000000000296610-c000000000296c18: unregister_ftrace_function_probe_func (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int unregister_ftrace_function_probe_func(char *glob, struct trace_array *tr, struct ftrace_probe_ops *probe_ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffe000174de2)
Location: kernel/trace/ftrace.c:4453
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:clear_ftrace_function_probes
  - kernel/trace/trace.c:ftrace_trace_snapshot_callback
  - kernel/trace/trace_events.c:event_enable_func
```
**Symbols:**

```
ffffffe000174de2-ffffffe000175192: unregister_ftrace_function_probe_func (STB_GLOBAL)
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
int unregister_ftrace_function_probe_func(char *glob, struct trace_array *tr, struct ftrace_probe_ops *probe_ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81194760)
Location: kernel/trace/ftrace.c:4453
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:clear_ftrace_function_probes
  - kernel/trace/trace.c:ftrace_trace_snapshot_callback
  - kernel/trace/trace_events.c:event_enable_func
```
**Symbols:**

```
ffffffff81194760-ffffffff81194c93: unregister_ftrace_function_probe_func (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int unregister_ftrace_function_probe_func(char *glob, struct trace_array *tr, struct ftrace_probe_ops *probe_ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81187870)
Location: kernel/trace/ftrace.c:4453
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:clear_ftrace_function_probes
  - kernel/trace/trace.c:ftrace_trace_snapshot_callback
  - kernel/trace/trace_events.c:event_enable_func
```
**Symbols:**

```
ffffffff81187870-ffffffff81187da3: unregister_ftrace_function_probe_func (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int unregister_ftrace_function_probe_func(char *glob, struct trace_array *tr, struct ftrace_probe_ops *probe_ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81192530)
Location: kernel/trace/ftrace.c:4453
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:clear_ftrace_function_probes
  - kernel/trace/trace.c:ftrace_trace_snapshot_callback
  - kernel/trace/trace_events.c:event_enable_func
```
**Symbols:**

```
ffffffff81192530-ffffffff81192a63: unregister_ftrace_function_probe_func (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int unregister_ftrace_function_probe_func(char *glob, struct trace_array *tr, struct ftrace_probe_ops *probe_ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff811a00c0)
Location: kernel/trace/ftrace.c:4453
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:clear_ftrace_function_probes
  - kernel/trace/trace.c:ftrace_trace_snapshot_callback
  - kernel/trace/trace_events.c:event_enable_func
```
**Symbols:**

```
ffffffff811a00c0-ffffffff811a05f3: unregister_ftrace_function_probe_func (STB_GLOBAL)
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
<code>struct trace_array *tr</code>
</li>
<li>
<b>Param added. </b>
<code>struct ftrace_probe_ops *probe_ops</code>
</li>
<li>
<b>Param removed. </b>
<code>struct ftrace_probe_ops *ops</code>
</li>
<li>
<b>Return type changed. </b>
<code>void</code> ➡️ <code>int</code>
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
