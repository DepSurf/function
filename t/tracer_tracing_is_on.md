# Function: <code>tracer_tracing_is_on</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8114ab17)
Location: kernel/trace/trace.c:815
Inline: True
Inline callers:
  - kernel/trace/trace.c:rb_simple_read
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff81153d30)
Location: kernel/trace/trace.c:1050
Inline: True
Inline callers:
  - kernel/trace/trace.c:rb_simple_read
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int tracer_tracing_is_on(struct trace_array *tr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8115e30c)
Location: kernel/trace/trace.c:1093
Inline: True
Inline callers:
  - kernel/trace/trace.c:rb_simple_read
Direct callers:
  - kernel/trace/trace_hwlat.c:hwlat_tracer_init
  - kernel/trace/trace_hwlat.c:hwlat_tracer_init
```
**Symbols:**

```
ffffffff811619e0-ffffffff81161a05: tracer_tracing_is_on (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int tracer_tracing_is_on(struct trace_array *tr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811617bc)
Location: kernel/trace/trace.c:1091
Inline: True
Inline callers:
  - kernel/trace/trace.c:rb_simple_read
Direct callers:
  - kernel/trace/trace_functions.c:ftrace_traceoff
  - kernel/trace/trace_functions.c:ftrace_traceon
  - kernel/trace/trace_hwlat.c:hwlat_tracer_init
  - kernel/trace/trace_hwlat.c:hwlat_tracer_init
```
**Symbols:**

```
ffffffff81164dc0-ffffffff81164de5: tracer_tracing_is_on (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int tracer_tracing_is_on(struct trace_array *tr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8116ec4c)
Location: kernel/trace/trace.c:1091
Inline: True
Inline callers:
  - kernel/trace/trace.c:rb_simple_read
Direct callers:
  - kernel/trace/trace_functions.c:ftrace_traceoff
  - kernel/trace/trace_functions.c:ftrace_traceon
  - kernel/trace/trace_hwlat.c:hwlat_tracer_init
  - kernel/trace/trace_hwlat.c:hwlat_tracer_init
```
**Symbols:**

```
ffffffff81171d10-ffffffff81171d35: tracer_tracing_is_on (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int tracer_tracing_is_on(struct trace_array *tr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8117cb35)
Location: kernel/trace/trace.c:1090
Inline: True
Inline callers:
  - kernel/trace/trace.c:rb_simple_write
  - kernel/trace/trace.c:rb_simple_read
Direct callers:
  - kernel/trace/trace_functions.c:ftrace_traceoff
  - kernel/trace/trace_functions.c:ftrace_traceon
  - kernel/trace/trace_hwlat.c:hwlat_tracer_init
  - kernel/trace/trace_hwlat.c:hwlat_tracer_init
```
**Symbols:**

```
ffffffff81180e80-ffffffff81180ea5: tracer_tracing_is_on (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
bool tracer_tracing_is_on(struct trace_array *tr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8118a3d2)
Location: kernel/trace/trace.c:1091
Inline: True
Inline callers:
  - kernel/trace/trace.c:rb_simple_write
  - kernel/trace/trace.c:rb_simple_read
Direct callers:
  - kernel/trace/trace_functions.c:ftrace_traceoff
  - kernel/trace/trace_functions.c:ftrace_traceon
  - kernel/trace/trace_hwlat.c:hwlat_tracer_init
  - kernel/trace/trace_hwlat.c:hwlat_tracer_init
```
**Symbols:**

```
ffffffff8118e840-ffffffff8118e863: tracer_tracing_is_on (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
bool tracer_tracing_is_on(struct trace_array *tr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff81197adc)
Location: kernel/trace/trace.c:1262
Inline: True
Inline callers:
  - kernel/trace/trace.c:rb_simple_write
  - kernel/trace/trace.c:rb_simple_read
Direct callers:
  - kernel/trace/trace_functions.c:ftrace_traceoff
  - kernel/trace/trace_functions.c:ftrace_traceon
  - kernel/trace/trace_hwlat.c:hwlat_tracer_init
  - kernel/trace/trace_hwlat.c:hwlat_tracer_init
```
**Symbols:**

```
ffffffff8119c250-ffffffff8119c273: tracer_tracing_is_on (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
bool tracer_tracing_is_on(struct trace_array *tr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811a347c)
Location: kernel/trace/trace.c:1280
Inline: True
Inline callers:
  - kernel/trace/trace.c:rb_simple_write
  - kernel/trace/trace.c:rb_simple_read
Direct callers:
  - kernel/trace/trace_functions.c:ftrace_traceoff
  - kernel/trace/trace_functions.c:ftrace_traceon
  - kernel/trace/trace_hwlat.c:hwlat_tracer_init
  - kernel/trace/trace_hwlat.c:hwlat_tracer_init
```
**Symbols:**

```
ffffffff811a7c40-ffffffff811a7c63: tracer_tracing_is_on (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
bool tracer_tracing_is_on(struct trace_array *tr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811bceec)
Location: kernel/trace/trace.c:1315
Inline: True
Inline callers:
  - kernel/trace/trace.c:rb_simple_write
  - kernel/trace/trace.c:rb_simple_read
  - kernel/trace/trace.c:tracing_wait_pipe
  - kernel/trace/trace.c:tracing_record_tgid
  - kernel/trace/trace.c:tracing_record_taskinfo_sched_switch
Direct callers:
  - kernel/trace/trace_functions.c:ftrace_traceoff
  - kernel/trace/trace_functions.c:ftrace_traceon
  - kernel/trace/trace_functions.c:ftrace_traceoff_count
  - kernel/trace/trace_functions.c:ftrace_traceon_count
  - kernel/trace/trace_hwlat.c:hwlat_tracer_init
  - kernel/trace/trace_hwlat.c:hwlat_tracer_init
```
**Symbols:**

```
ffffffff811bffe0-ffffffff811c0003: tracer_tracing_is_on (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
bool tracer_tracing_is_on(struct trace_array *tr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811baafc)
Location: kernel/trace/trace.c:1466
Inline: True
Inline callers:
  - kernel/trace/trace.c:rb_simple_write
  - kernel/trace/trace.c:rb_simple_read
  - kernel/trace/trace.c:tracing_wait_pipe
  - kernel/trace/trace.c:tracing_record_tgid
  - kernel/trace/trace.c:tracing_record_taskinfo_sched_switch
Direct callers:
  - kernel/trace/trace_functions.c:ftrace_traceoff
  - kernel/trace/trace_functions.c:ftrace_traceon
  - kernel/trace/trace_functions.c:ftrace_traceoff_count
  - kernel/trace/trace_functions.c:ftrace_traceon_count
  - kernel/trace/trace_hwlat.c:hwlat_tracer_init
  - kernel/trace/trace_hwlat.c:hwlat_tracer_init
```
**Symbols:**

```
ffffffff811bdc10-ffffffff811bdc33: tracer_tracing_is_on (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
bool tracer_tracing_is_on(struct trace_array *tr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811bad6c)
Location: kernel/trace/trace.c:1463
Inline: True
Inline callers:
  - kernel/trace/trace.c:rb_simple_write
  - kernel/trace/trace.c:rb_simple_read
  - kernel/trace/trace.c:tracing_wait_pipe
  - kernel/trace/trace.c:tracing_is_on
Direct callers:
  - kernel/trace/trace_functions.c:ftrace_traceoff
  - kernel/trace/trace_functions.c:ftrace_traceon
  - kernel/trace/trace_functions.c:ftrace_traceoff_count
  - kernel/trace/trace_functions.c:ftrace_traceon_count
  - kernel/trace/trace_hwlat.c:hwlat_tracer_init
  - kernel/trace/trace_hwlat.c:hwlat_tracer_init
```
**Symbols:**

```
ffffffff811bd720-ffffffff811bd743: tracer_tracing_is_on (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
bool tracer_tracing_is_on(struct trace_array *tr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811e551c)
Location: kernel/trace/trace.c:1476
Inline: True
Inline callers:
  - kernel/trace/trace.c:rb_simple_write
  - kernel/trace/trace.c:rb_simple_read
  - kernel/trace/trace.c:tracing_wait_pipe
  - kernel/trace/trace.c:tracing_is_on
Direct callers:
  - kernel/trace/trace_functions.c:ftrace_traceoff
  - kernel/trace/trace_functions.c:ftrace_traceon
  - kernel/trace/trace_functions.c:ftrace_traceoff_count
  - kernel/trace/trace_functions.c:ftrace_traceon_count
  - kernel/trace/trace_hwlat.c:hwlat_tracer_init
  - kernel/trace/trace_hwlat.c:hwlat_tracer_init
  - kernel/trace/trace_events_trigger.c:traceoff_count_trigger
  - kernel/trace/trace_events_trigger.c:traceon_count_trigger
```
**Symbols:**

```
ffffffff811e8220-ffffffff811e8243: tracer_tracing_is_on (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
bool tracer_tracing_is_on(struct trace_array *tr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8121c8f4)
Location: kernel/trace/trace.c:1466
Inline: True
Inline callers:
  - kernel/trace/trace.c:rb_simple_write
  - kernel/trace/trace.c:rb_simple_read
  - kernel/trace/trace.c:tracing_wait_pipe
  - kernel/trace/trace.c:tracing_is_on
Direct callers:
  - kernel/trace/trace_functions.c:ftrace_traceoff
  - kernel/trace/trace_functions.c:ftrace_traceon
  - kernel/trace/trace_functions.c:ftrace_traceoff_count
  - kernel/trace/trace_functions.c:ftrace_traceon_count
  - kernel/trace/trace_hwlat.c:hwlat_tracer_init
  - kernel/trace/trace_hwlat.c:hwlat_tracer_init
  - kernel/trace/trace_events_trigger.c:traceoff_count_trigger
  - kernel/trace/trace_events_trigger.c:traceon_count_trigger
```
**Symbols:**

```
ffffffff8121fd50-ffffffff8121fd7f: tracer_tracing_is_on (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
bool tracer_tracing_is_on(struct trace_array *tr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff812671ba)
Location: kernel/trace/trace.c:1472
Inline: True
Inline callers:
  - kernel/trace/trace.c:rb_simple_write
  - kernel/trace/trace.c:rb_simple_read
  - kernel/trace/trace.c:tracing_buffers_splice_read
  - kernel/trace/trace.c:tracing_wait_pipe
  - kernel/trace/trace.c:tracing_is_on
Direct callers:
  - kernel/trace/trace_functions.c:ftrace_traceoff
  - kernel/trace/trace_functions.c:ftrace_traceon
  - kernel/trace/trace_functions.c:ftrace_traceoff_count
  - kernel/trace/trace_functions.c:ftrace_traceon_count
  - kernel/trace/trace_hwlat.c:hwlat_tracer_init
  - kernel/trace/trace_hwlat.c:hwlat_tracer_init
  - kernel/trace/trace_events_trigger.c:traceoff_count_trigger
  - kernel/trace/trace_events_trigger.c:traceon_count_trigger
```
**Symbols:**

```
ffffffff8126a9e0-ffffffff8126aa0f: tracer_tracing_is_on (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
bool tracer_tracing_is_on(struct trace_array *tr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8127e27a)
Location: kernel/trace/trace.c:1523
Inline: True
Inline callers:
  - kernel/trace/trace.c:rb_simple_write
  - kernel/trace/trace.c:rb_simple_read
  - kernel/trace/trace.c:tracing_buffers_splice_read
  - kernel/trace/trace.c:tracing_wait_pipe
  - kernel/trace/trace.c:tracing_is_on
Direct callers:
  - kernel/trace/trace_functions.c:ftrace_traceoff
  - kernel/trace/trace_functions.c:ftrace_traceon
  - kernel/trace/trace_functions.c:ftrace_traceoff_count
  - kernel/trace/trace_functions.c:ftrace_traceon_count
  - kernel/trace/trace_hwlat.c:hwlat_tracer_init
  - kernel/trace/trace_hwlat.c:hwlat_tracer_init
  - kernel/trace/trace_osnoise.c:osnoise_main
  - kernel/trace/trace_osnoise.c:notify_new_max_latency
  - kernel/trace/trace_events_trigger.c:traceoff_count_trigger
  - kernel/trace/trace_events_trigger.c:traceon_count_trigger
```
**Symbols:**

```
ffffffff81281b60-ffffffff81281b8f: tracer_tracing_is_on (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
bool tracer_tracing_is_on(struct trace_array *tr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff81298eba)
Location: kernel/trace/trace.c:1533
Inline: True
Inline callers:
  - kernel/trace/trace.c:rb_simple_write
  - kernel/trace/trace.c:rb_simple_read
  - kernel/trace/trace.c:tracing_buffers_splice_read
  - kernel/trace/trace.c:tracing_wait_pipe
  - kernel/trace/trace.c:tracing_is_on
Direct callers:
  - kernel/trace/trace_functions.c:ftrace_traceoff
  - kernel/trace/trace_functions.c:ftrace_traceon
  - kernel/trace/trace_functions.c:ftrace_traceoff_count
  - kernel/trace/trace_functions.c:ftrace_traceon_count
  - kernel/trace/trace_hwlat.c:hwlat_tracer_init
  - kernel/trace/trace_hwlat.c:hwlat_tracer_init
  - kernel/trace/trace_osnoise.c:osnoise_main
  - kernel/trace/trace_osnoise.c:notify_new_max_latency
  - kernel/trace/trace_events_trigger.c:traceoff_count_trigger
  - kernel/trace/trace_events_trigger.c:traceon_count_trigger
```
**Symbols:**

```
ffffffff8129cce0-ffffffff8129cd0f: tracer_tracing_is_on (STB_GLOBAL)
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
bool tracer_tracing_is_on(struct trace_array *tr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffff80001021e718)
Location: kernel/trace/trace.c:1280
Inline: True
Inline callers:
  - kernel/trace/trace.c:rb_simple_write
  - kernel/trace/trace.c:rb_simple_read
Direct callers:
  - kernel/trace/trace_functions.c:ftrace_traceoff
  - kernel/trace/trace_functions.c:ftrace_traceon
  - kernel/trace/trace_hwlat.c:hwlat_tracer_init
  - kernel/trace/trace_hwlat.c:hwlat_tracer_init
```
**Symbols:**

```
ffff800010224278-ffff8000102242ac: tracer_tracing_is_on (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
bool tracer_tracing_is_on(struct trace_array *tr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (c045c5cc)
Location: kernel/trace/trace.c:1280
Inline: True
Inline callers:
  - kernel/trace/trace.c:rb_simple_write
  - kernel/trace/trace.c:rb_simple_read
  - kernel/trace/trace.c:tracing_wait_pipe
Direct callers:
  - kernel/trace/trace_functions.c:ftrace_traceoff
  - kernel/trace/trace_functions.c:ftrace_traceon
  - kernel/trace/trace_functions.c:ftrace_traceoff_count
  - kernel/trace/trace_functions.c:ftrace_traceon_count
  - kernel/trace/trace_hwlat.c:hwlat_tracer_init
```
**Symbols:**

```
c04619ec-c0461a20: tracer_tracing_is_on (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
bool tracer_tracing_is_on(struct trace_array *tr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (c0000000002a1968)
Location: kernel/trace/trace.c:1280
Inline: True
Inline callers:
  - kernel/trace/trace.c:rb_simple_write
  - kernel/trace/trace.c:rb_simple_read
  - kernel/trace/trace.c:tracing_wait_pipe
Direct callers:
  - kernel/trace/trace_functions.c:ftrace_traceoff
  - kernel/trace/trace_functions.c:ftrace_traceon
  - kernel/trace/trace_hwlat.c:hwlat_tracer_init
  - kernel/trace/trace_hwlat.c:hwlat_tracer_init
```
**Symbols:**

```
c0000000002a91e0-c0000000002a9238: tracer_tracing_is_on (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
bool tracer_tracing_is_on(struct trace_array *tr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffe00017b0e2)
Location: kernel/trace/trace.c:1280
Inline: True
Inline callers:
  - kernel/trace/trace.c:rb_simple_write
  - kernel/trace/trace.c:rb_simple_read
  - kernel/trace/trace.c:tracing_wait_pipe
Direct callers:
  - kernel/trace/trace_functions.c:ftrace_traceoff
  - kernel/trace/trace_functions.c:ftrace_traceon
  - kernel/trace/trace_hwlat.c:hwlat_tracer_init
  - kernel/trace/trace_hwlat.c:hwlat_tracer_init
```
**Symbols:**

```
ffffffe00017f794-ffffffe00017f7bc: tracer_tracing_is_on (STB_GLOBAL)
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
bool tracer_tracing_is_on(struct trace_array *tr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8119ba9c)
Location: kernel/trace/trace.c:1280
Inline: True
Inline callers:
  - kernel/trace/trace.c:rb_simple_write
  - kernel/trace/trace.c:rb_simple_read
Direct callers:
  - kernel/trace/trace_functions.c:ftrace_traceoff
  - kernel/trace/trace_functions.c:ftrace_traceon
  - kernel/trace/trace_hwlat.c:hwlat_tracer_init
  - kernel/trace/trace_hwlat.c:hwlat_tracer_init
```
**Symbols:**

```
ffffffff811a0260-ffffffff811a0283: tracer_tracing_is_on (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
bool tracer_tracing_is_on(struct trace_array *tr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8118eb1c)
Location: kernel/trace/trace.c:1280
Inline: True
Inline callers:
  - kernel/trace/trace.c:rb_simple_write
  - kernel/trace/trace.c:rb_simple_read
Direct callers:
  - kernel/trace/trace_functions.c:ftrace_traceoff
  - kernel/trace/trace_functions.c:ftrace_traceon
  - kernel/trace/trace_hwlat.c:hwlat_tracer_init
  - kernel/trace/trace_hwlat.c:hwlat_tracer_init
```
**Symbols:**

```
ffffffff81193270-ffffffff81193293: tracer_tracing_is_on (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
bool tracer_tracing_is_on(struct trace_array *tr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8119986c)
Location: kernel/trace/trace.c:1280
Inline: True
Inline callers:
  - kernel/trace/trace.c:rb_simple_write
  - kernel/trace/trace.c:rb_simple_read
Direct callers:
  - kernel/trace/trace_functions.c:ftrace_traceoff
  - kernel/trace/trace_functions.c:ftrace_traceon
  - kernel/trace/trace_hwlat.c:hwlat_tracer_init
  - kernel/trace/trace_hwlat.c:hwlat_tracer_init
```
**Symbols:**

```
ffffffff8119e030-ffffffff8119e053: tracer_tracing_is_on (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
bool tracer_tracing_is_on(struct trace_array *tr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811a750c)
Location: kernel/trace/trace.c:1280
Inline: True
Inline callers:
  - kernel/trace/trace.c:rb_simple_write
  - kernel/trace/trace.c:rb_simple_read
Direct callers:
  - kernel/trace/trace_functions.c:ftrace_traceoff
  - kernel/trace/trace_functions.c:ftrace_traceon
  - kernel/trace/trace_hwlat.c:hwlat_tracer_init
  - kernel/trace/trace_hwlat.c:hwlat_tracer_init
```
**Symbols:**

```
ffffffff811abd10-ffffffff811abd33: tracer_tracing_is_on (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>bool</code>
</li>
</ul>
</details>
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
