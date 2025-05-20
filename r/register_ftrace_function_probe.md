# Function: <code>register_ftrace_function_probe</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int register_ftrace_function_probe(char *glob, struct ftrace_probe_ops *ops, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81145140)
Location: kernel/trace/ftrace.c:3708
Inline: False
Direct callers:
  - kernel/trace/trace.c:ftrace_trace_snapshot_callback
  - kernel/trace/trace_events.c:event_enable_func
```
**Symbols:**

```
ffffffff81145140-ffffffff811454b7: register_ftrace_function_probe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int register_ftrace_function_probe(char *glob, struct ftrace_probe_ops *ops, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff8114da30)
Location: kernel/trace/ftrace.c:3745
Inline: False
Direct callers:
  - kernel/trace/trace.c:ftrace_trace_snapshot_callback
  - kernel/trace/trace_events.c:event_enable_func
```
**Symbols:**

```
ffffffff8114da30-ffffffff8114ddb6: register_ftrace_function_probe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int register_ftrace_function_probe(char *glob, struct ftrace_probe_ops *ops, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81157970)
Location: kernel/trace/ftrace.c:3771
Inline: False
Direct callers:
  - kernel/trace/trace.c:ftrace_trace_snapshot_callback
  - kernel/trace/trace_events.c:event_enable_func
```
**Symbols:**

```
ffffffff81157970-ffffffff81157cfd: register_ftrace_function_probe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int register_ftrace_function_probe(char *glob, struct trace_array *tr, struct ftrace_probe_ops *probe_ops, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff8115ac70)
Location: kernel/trace/ftrace.c:4332
Inline: False
Direct callers:
  - kernel/trace/trace.c:ftrace_trace_snapshot_callback
  - kernel/trace/trace_events.c:event_enable_func
```
**Symbols:**

```
ffffffff8115ac70-ffffffff8115b05b: register_ftrace_function_probe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int register_ftrace_function_probe(char *glob, struct trace_array *tr, struct ftrace_probe_ops *probe_ops, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81167d50)
Location: kernel/trace/ftrace.c:4300
Inline: False
Direct callers:
  - kernel/trace/trace.c:ftrace_trace_snapshot_callback
  - kernel/trace/trace_events.c:event_enable_func
```
**Symbols:**

```
ffffffff81167d50-ffffffff81168143: register_ftrace_function_probe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int register_ftrace_function_probe(char *glob, struct trace_array *tr, struct ftrace_probe_ops *probe_ops, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81176a30)
Location: kernel/trace/ftrace.c:4288
Inline: False
Direct callers:
  - kernel/trace/trace.c:ftrace_trace_snapshot_callback
  - kernel/trace/trace_events.c:event_enable_func
```
**Symbols:**

```
ffffffff81176a30-ffffffff81176e6e: register_ftrace_function_probe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int register_ftrace_function_probe(char *glob, struct trace_array *tr, struct ftrace_probe_ops *probe_ops, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81184680)
Location: kernel/trace/ftrace.c:4247
Inline: False
Direct callers:
  - kernel/trace/trace.c:ftrace_trace_snapshot_callback
  - kernel/trace/trace_events.c:event_enable_func
```
**Symbols:**

```
ffffffff81184680-ffffffff81184abe: register_ftrace_function_probe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int register_ftrace_function_probe(char *glob, struct trace_array *tr, struct ftrace_probe_ops *probe_ops, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/ftrace.c (0)
Location: kernel/trace/ftrace.c:4286
Inline: False
Direct callers:
  - kernel/trace/trace.c:ftrace_trace_snapshot_callback
  - kernel/trace/trace_events.c:event_enable_func
```
**Symbols:**

```
ffffffff811923cb-ffffffff811923fd: register_ftrace_function_probe.cold (STB_LOCAL)
ffffffff81191450-ffffffff8119188b: register_ftrace_function_probe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int register_ftrace_function_probe(char *glob, struct trace_array *tr, struct ftrace_probe_ops *probe_ops, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff8119d470)
Location: kernel/trace/ftrace.c:4310
Inline: False
Direct callers:
  - kernel/trace/trace.c:ftrace_trace_snapshot_callback
  - kernel/trace/trace_events.c:event_enable_func
```
**Symbols:**

```
ffffffff8119d470-ffffffff8119d8bb: register_ftrace_function_probe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int register_ftrace_function_probe(char *glob, struct trace_array *tr, struct ftrace_probe_ops *probe_ops, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff811b39a0)
Location: kernel/trace/ftrace.c:4437
Inline: False
Direct callers:
  - kernel/trace/trace.c:ftrace_trace_snapshot_callback
  - kernel/trace/trace_functions.c:ftrace_cpudump_callback
  - kernel/trace/trace_functions.c:ftrace_dump_callback
  - kernel/trace/trace_functions.c:ftrace_stacktrace_callback
  - kernel/trace/trace_events.c:event_enable_func
```
**Symbols:**

```
ffffffff811b39a0-ffffffff811b3e23: register_ftrace_function_probe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int register_ftrace_function_probe(char *glob, struct trace_array *tr, struct ftrace_probe_ops *probe_ops, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff811b1670)
Location: kernel/trace/ftrace.c:4514
Inline: False
Direct callers:
  - kernel/trace/trace.c:ftrace_trace_snapshot_callback
  - kernel/trace/trace_functions.c:ftrace_cpudump_callback
  - kernel/trace/trace_functions.c:ftrace_dump_callback
  - kernel/trace/trace_functions.c:ftrace_stacktrace_callback
  - kernel/trace/trace_events.c:event_enable_func
```
**Symbols:**

```
ffffffff811b1670-ffffffff811b1af3: register_ftrace_function_probe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int register_ftrace_function_probe(char *glob, struct trace_array *tr, struct ftrace_probe_ops *probe_ops, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff811b21b0)
Location: kernel/trace/ftrace.c:4514
Inline: False
Direct callers:
  - kernel/trace/trace.c:ftrace_trace_snapshot_callback
  - kernel/trace/trace_functions.c:ftrace_cpudump_callback
  - kernel/trace/trace_functions.c:ftrace_dump_callback
  - kernel/trace/trace_functions.c:ftrace_stacktrace_callback
  - kernel/trace/trace_events.c:event_enable_func
```
**Symbols:**

```
ffffffff811b21b0-ffffffff811b25f9: register_ftrace_function_probe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int register_ftrace_function_probe(char *glob, struct trace_array *tr, struct ftrace_probe_ops *probe_ops, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/ftrace.c (0)
Location: kernel/trace/ftrace.c:4514
Inline: False
Direct callers:
  - kernel/trace/trace.c:ftrace_trace_snapshot_callback
  - kernel/trace/trace_functions.c:ftrace_cpudump_callback
  - kernel/trace/trace_functions.c:ftrace_dump_callback
  - kernel/trace/trace_functions.c:ftrace_stacktrace_callback
  - kernel/trace/trace_events.c:event_enable_func
```
**Symbols:**

```
ffffffff81cb481a-ffffffff81cb483b: register_ftrace_function_probe.cold (STB_LOCAL)
ffffffff811dc0e0-ffffffff811dc52f: register_ftrace_function_probe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int register_ftrace_function_probe(char *glob, struct trace_array *tr, struct ftrace_probe_ops *probe_ops, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/ftrace.c (0)
Location: kernel/trace/ftrace.c:4654
Inline: False
Direct callers:
  - kernel/trace/trace.c:ftrace_trace_snapshot_callback
  - kernel/trace/trace_events.c:event_enable_func
```
**Symbols:**

```
ffffffff81e6584b-ffffffff81e65874: register_ftrace_function_probe.cold (STB_LOCAL)
ffffffff812122b0-ffffffff812127aa: register_ftrace_function_probe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int register_ftrace_function_probe(char *glob, struct trace_array *tr, struct ftrace_probe_ops *probe_ops, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/ftrace.c (0)
Location: kernel/trace/ftrace.c:4675
Inline: False
Direct callers:
  - kernel/trace/trace.c:ftrace_trace_snapshot_callback
  - kernel/trace/trace_events.c:event_enable_func
```
**Symbols:**

```
ffffffff8205cfa7-ffffffff8205cfd0: register_ftrace_function_probe.cold (STB_LOCAL)
ffffffff8125b980-ffffffff8125be7a: register_ftrace_function_probe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int register_ftrace_function_probe(char *glob, struct trace_array *tr, struct ftrace_probe_ops *probe_ops, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/ftrace.c (0)
Location: kernel/trace/ftrace.c:4830
Inline: False
Direct callers:
  - kernel/trace/trace.c:ftrace_trace_snapshot_callback
  - kernel/trace/trace_events.c:event_enable_func
```
**Symbols:**

```
ffffffff820db93b-ffffffff820db964: register_ftrace_function_probe.cold (STB_LOCAL)
ffffffff81272610-ffffffff81272b1d: register_ftrace_function_probe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int register_ftrace_function_probe(char *glob, struct trace_array *tr, struct ftrace_probe_ops *probe_ops, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/ftrace.c (0)
Location: kernel/trace/ftrace.c:4796
Inline: False
Direct callers:
  - kernel/trace/trace.c:ftrace_trace_snapshot_callback
  - kernel/trace/trace_events.c:event_enable_func
```
**Symbols:**

```
ffffffff821b7706-ffffffff821b772f: register_ftrace_function_probe.cold (STB_LOCAL)
ffffffff8128ce60-ffffffff8128d39c: register_ftrace_function_probe (STB_GLOBAL)
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
int register_ftrace_function_probe(char *glob, struct trace_array *tr, struct ftrace_probe_ops *probe_ops, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffff8000102163b0)
Location: kernel/trace/ftrace.c:4310
Inline: False
Direct callers:
  - kernel/trace/trace.c:ftrace_trace_snapshot_callback
  - kernel/trace/trace_events.c:event_enable_func
```
**Symbols:**

```
ffff8000102163b0-ffff800010216784: register_ftrace_function_probe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int register_ftrace_function_probe(char *glob, struct trace_array *tr, struct ftrace_probe_ops *probe_ops, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (c0455120)
Location: kernel/trace/ftrace.c:4310
Inline: False
Direct callers:
  - kernel/trace/trace.c:ftrace_trace_snapshot_callback
  - kernel/trace/trace_events.c:event_enable_func
```
**Symbols:**

```
c0455120-c0455534: register_ftrace_function_probe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int register_ftrace_function_probe(char *glob, struct trace_array *tr, struct ftrace_probe_ops *probe_ops, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (c0000000002981c0)
Location: kernel/trace/ftrace.c:4310
Inline: False
Direct callers:
  - kernel/trace/trace.c:ftrace_trace_snapshot_callback
  - kernel/trace/trace_events.c:event_enable_func
```
**Symbols:**

```
c0000000002981c0-c000000000298724: register_ftrace_function_probe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int register_ftrace_function_probe(char *glob, struct trace_array *tr, struct ftrace_probe_ops *probe_ops, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffe000175f2e)
Location: kernel/trace/ftrace.c:4310
Inline: False
Direct callers:
  - kernel/trace/trace.c:ftrace_trace_snapshot_callback
  - kernel/trace/trace_events.c:event_enable_func
```
**Symbols:**

```
ffffffe000175f2e-ffffffe000176286: register_ftrace_function_probe (STB_GLOBAL)
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
int register_ftrace_function_probe(char *glob, struct trace_array *tr, struct ftrace_probe_ops *probe_ops, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81195a90)
Location: kernel/trace/ftrace.c:4310
Inline: False
Direct callers:
  - kernel/trace/trace.c:ftrace_trace_snapshot_callback
  - kernel/trace/trace_events.c:event_enable_func
```
**Symbols:**

```
ffffffff81195a90-ffffffff81195edb: register_ftrace_function_probe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int register_ftrace_function_probe(char *glob, struct trace_array *tr, struct ftrace_probe_ops *probe_ops, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81188ba0)
Location: kernel/trace/ftrace.c:4310
Inline: False
Direct callers:
  - kernel/trace/trace.c:ftrace_trace_snapshot_callback
  - kernel/trace/trace_events.c:event_enable_func
```
**Symbols:**

```
ffffffff81188ba0-ffffffff81188feb: register_ftrace_function_probe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int register_ftrace_function_probe(char *glob, struct trace_array *tr, struct ftrace_probe_ops *probe_ops, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81193860)
Location: kernel/trace/ftrace.c:4310
Inline: False
Direct callers:
  - kernel/trace/trace.c:ftrace_trace_snapshot_callback
  - kernel/trace/trace_events.c:event_enable_func
```
**Symbols:**

```
ffffffff81193860-ffffffff81193cab: register_ftrace_function_probe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int register_ftrace_function_probe(char *glob, struct trace_array *tr, struct ftrace_probe_ops *probe_ops, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff811a1430)
Location: kernel/trace/ftrace.c:4310
Inline: False
Direct callers:
  - kernel/trace/trace.c:ftrace_trace_snapshot_callback
  - kernel/trace/trace_events.c:event_enable_func
```
**Symbols:**

```
ffffffff811a1430-ffffffff811a187b: register_ftrace_function_probe (STB_GLOBAL)
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
<b>Param reordered. </b>
<code>glob, ops, data</code> ➡️ <code>glob, tr, probe_ops, data</code>
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
