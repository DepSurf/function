# Function: <code>__find_event_file</code>

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
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct trace_event_file *__find_event_file(struct trace_array *tr, const char *system, const char *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events.c (ffffffff81196020)
Location: kernel/trace/trace_events.c:2480
Inline: False
Direct callers:
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace_events.c:find_event_file
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
```
**Symbols:**

```
ffffffff81196020-ffffffff8119609d: __find_event_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct trace_event_file *__find_event_file(struct trace_array *tr, const char *system, const char *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events.c (ffffffff811a4180)
Location: kernel/trace/trace_events.c:2481
Inline: False
Direct callers:
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace_events.c:find_event_file
  - kernel/trace/trace_events_hist.c:create_hist_data
```
**Symbols:**

```
ffffffff811a4180-ffffffff811a41fd: __find_event_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct trace_event_file *__find_event_file(struct trace_array *tr, const char *system, const char *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events.c (ffffffff811b2030)
Location: kernel/trace/trace_events.c:2471
Inline: False
Direct callers:
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace_events.c:find_event_file
  - kernel/trace/trace_events_hist.c:create_hist_data
  - kernel/trace/trace_events_hist.c:create_field_var_hist
```
**Symbols:**

```
ffffffff811b2030-ffffffff811b20b0: __find_event_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct trace_event_file *__find_event_file(struct trace_array *tr, const char *system, const char *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events.c (ffffffff811bd6b0)
Location: kernel/trace/trace_events.c:2470
Inline: False
Direct callers:
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace_events.c:find_event_file
  - kernel/trace/trace_events_hist.c:create_hist_data
  - kernel/trace/trace_events_hist.c:create_field_var_hist
```
**Symbols:**

```
ffffffff811bd6b0-ffffffff811bd730: __find_event_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct trace_event_file *__find_event_file(struct trace_array *tr, const char *system, const char *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events.c (ffffffff811d6a90)
Location: kernel/trace/trace_events.c:2675
Inline: False
Direct callers:
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace_events.c:event_enable_func
  - kernel/trace/trace_events.c:trace_get_event_file
  - kernel/trace/trace_events_hist.c:onmatch_parse
  - kernel/trace/trace_events_hist.c:create_field_var_hist
```
**Symbols:**

```
ffffffff811d6a90-ffffffff811d6b10: __find_event_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct trace_event_file *__find_event_file(struct trace_array *tr, const char *system, const char *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events.c (ffffffff811d3e10)
Location: kernel/trace/trace_events.c:2691
Inline: False
Direct callers:
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace_events.c:event_enable_func
  - kernel/trace/trace_events.c:trace_get_event_file
  - kernel/trace/trace_events_hist.c:onmatch_parse
  - kernel/trace/trace_events_hist.c:create_field_var_hist
```
**Symbols:**

```
ffffffff811d3e10-ffffffff811d3e90: __find_event_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct trace_event_file *__find_event_file(struct trace_array *tr, const char *system, const char *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events.c (ffffffff811d5500)
Location: kernel/trace/trace_events.c:2902
Inline: False
Direct callers:
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace_events.c:event_enable_func
  - kernel/trace/trace_events.c:trace_get_event_file
  - kernel/trace/trace_events_hist.c:onmatch_parse
  - kernel/trace/trace_events_hist.c:create_field_var_hist
```
**Symbols:**

```
ffffffff811d5500-ffffffff811d5580: __find_event_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct trace_event_file *__find_event_file(struct trace_array *tr, const char *system, const char *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events.c (ffffffff81202340)
Location: kernel/trace/trace_events.c:2919
Inline: False
Direct callers:
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace_events.c:event_enable_func
  - kernel/trace/trace_events.c:trace_get_event_file
  - kernel/trace/trace_events_hist.c:onmatch_parse
  - kernel/trace/trace_events_hist.c:create_field_var_hist
```
**Symbols:**

```
ffffffff81202340-ffffffff812023c0: __find_event_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct trace_event_file *__find_event_file(struct trace_array *tr, const char *system, const char *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events.c (ffffffff8123d740)
Location: kernel/trace/trace_events.c:3022
Inline: False
Direct callers:
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace_events.c:event_enable_func
  - kernel/trace/trace_events.c:trace_get_event_file
  - kernel/trace/trace_events_hist.c:onmatch_parse
  - kernel/trace/trace_events_hist.c:create_field_var_hist
```
**Symbols:**

```
ffffffff8123d740-ffffffff8123d7ce: __find_event_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct trace_event_file *__find_event_file(struct trace_array *tr, const char *system, const char *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events.c (ffffffff8128ae50)
Location: kernel/trace/trace_events.c:3113
Inline: False
Direct callers:
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace_events.c:event_enable_func
  - kernel/trace/trace_events.c:trace_get_event_file
  - kernel/trace/trace_events_hist.c:onmatch_parse
  - kernel/trace/trace_events_hist.c:create_field_var_hist
```
**Symbols:**

```
ffffffff8128ae50-ffffffff8128aede: __find_event_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct trace_event_file *__find_event_file(struct trace_array *tr, const char *system, const char *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events.c (ffffffff812a7da0)
Location: kernel/trace/trace_events.c:3107
Inline: False
Direct callers:
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace_events.c:event_enable_func
  - kernel/trace/trace_events.c:trace_get_event_file
  - kernel/trace/trace_events_hist.c:onmatch_parse
  - kernel/trace/trace_events_hist.c:create_field_var_hist
```
**Symbols:**

```
ffffffff812a7da0-ffffffff812a7e2e: __find_event_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct trace_event_file *__find_event_file(struct trace_array *tr, const char *system, const char *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events.c (ffffffff812c3a40)
Location: kernel/trace/trace_events.c:3299
Inline: False
Direct callers:
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace_events.c:event_enable_func
  - kernel/trace/trace_events.c:trace_get_event_file
  - kernel/trace/trace_events_hist.c:onmatch_parse
  - kernel/trace/trace_events_hist.c:create_field_var_hist
```
**Symbols:**

```
ffffffff812c3a40-ffffffff812c3ace: __find_event_file (STB_GLOBAL)
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
struct trace_event_file *__find_event_file(struct trace_array *tr, const char *system, const char *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events.c (ffff80001023c9e0)
Location: kernel/trace/trace_events.c:2470
Inline: False
Direct callers:
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace_events.c:find_event_file
  - kernel/trace/trace_events_hist.c:create_hist_data
  - kernel/trace/trace_events_hist.c:create_field_var_hist
```
**Symbols:**

```
ffff80001023c9e0-ffff80001023ca98: __find_event_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct trace_event_file *__find_event_file(struct trace_array *tr, const char *system, const char *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events.c (c04782e4)
Location: kernel/trace/trace_events.c:2470
Inline: False
Direct callers:
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace_events.c:find_event_file
```
**Symbols:**

```
c04782e4-c0478380: __find_event_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct trace_event_file *__find_event_file(struct trace_array *tr, const char *system, const char *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events.c (c0000000002cb940)
Location: kernel/trace/trace_events.c:2470
Inline: False
Direct callers:
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace_events.c:find_event_file
  - kernel/trace/trace_events_hist.c:create_hist_data
  - kernel/trace/trace_events_hist.c:create_field_var_hist
```
**Symbols:**

```
c0000000002cb940-c0000000002cbcd8: __find_event_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct trace_event_file *__find_event_file(struct trace_array *tr, const char *system, const char *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events.c (ffffffe000192b22)
Location: kernel/trace/trace_events.c:2470
Inline: False
Direct callers:
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace_events.c:find_event_file
```
**Symbols:**

```
ffffffe000192b22-ffffffe000192ba0: __find_event_file (STB_GLOBAL)
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
struct trace_event_file *__find_event_file(struct trace_array *tr, const char *system, const char *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events.c (ffffffff811b5cd0)
Location: kernel/trace/trace_events.c:2470
Inline: False
Direct callers:
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace_events.c:find_event_file
  - kernel/trace/trace_events_hist.c:create_hist_data
  - kernel/trace/trace_events_hist.c:create_field_var_hist
```
**Symbols:**

```
ffffffff811b5cd0-ffffffff811b5d50: __find_event_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct trace_event_file *__find_event_file(struct trace_array *tr, const char *system, const char *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events.c (ffffffff811a8ad0)
Location: kernel/trace/trace_events.c:2470
Inline: False
Direct callers:
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace_events.c:find_event_file
  - kernel/trace/trace_events_hist.c:create_hist_data
  - kernel/trace/trace_events_hist.c:create_field_var_hist
```
**Symbols:**

```
ffffffff811a8ad0-ffffffff811a8b50: __find_event_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct trace_event_file *__find_event_file(struct trace_array *tr, const char *system, const char *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events.c (ffffffff811b3aa0)
Location: kernel/trace/trace_events.c:2470
Inline: False
Direct callers:
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace_events.c:find_event_file
  - kernel/trace/trace_events_hist.c:create_hist_data
  - kernel/trace/trace_events_hist.c:create_field_var_hist
```
**Symbols:**

```
ffffffff811b3aa0-ffffffff811b3b20: __find_event_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct trace_event_file *__find_event_file(struct trace_array *tr, const char *system, const char *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events.c (ffffffff811c1b40)
Location: kernel/trace/trace_events.c:2470
Inline: False
Direct callers:
  - kernel/trace/trace.c:init_tracer_tracefs
  - kernel/trace/trace_events.c:find_event_file
  - kernel/trace/trace_events_hist.c:create_hist_data
  - kernel/trace/trace_events_hist.c:create_field_var_hist
```
**Symbols:**

```
ffffffff811c1b40-ffffffff811c1bc0: __find_event_file (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
