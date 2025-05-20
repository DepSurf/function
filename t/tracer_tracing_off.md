# Function: <code>tracer_tracing_off</code>

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
In kernel/trace/trace.c (ffffffff8114aae7)
Location: kernel/trace/trace.c:772
Inline: True
Inline callers:
  - kernel/trace/trace.c:rb_simple_write
  - kernel/trace/trace.c:tracing_free_buffer_release
  - kernel/trace/trace.c:disable_trace_on_warning
  - kernel/trace/trace.c:tracing_snapshot
  - kernel/trace/trace.c:trace_init
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
In kernel/trace/trace.c (ffffffff81fad53b)
Location: kernel/trace/trace.c:1007
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_init
  - kernel/trace/trace.c:rb_simple_write
  - kernel/trace/trace.c:tracing_free_buffer_release
  - kernel/trace/trace.c:disable_trace_on_warning
  - kernel/trace/trace.c:tracing_snapshot
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff81fe9900)
Location: kernel/trace/trace.c:1050
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_init
  - kernel/trace/trace.c:rb_simple_write
  - kernel/trace/trace.c:tracing_free_buffer_release
  - kernel/trace/trace.c:disable_trace_on_warning
  - kernel/trace/trace.c:tracing_snapshot
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void tracer_tracing_off(struct trace_array *tr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff820ca284)
Location: kernel/trace/trace.c:1048
Inline: True
Inline callers:
  - kernel/trace/trace.c:early_trace_init
  - kernel/trace/trace.c:rb_simple_write
  - kernel/trace/trace.c:tracing_free_buffer_release
  - kernel/trace/trace.c:disable_trace_on_warning
  - kernel/trace/trace.c:tracing_snapshot_instance
Direct callers:
  - kernel/trace/trace_functions.c:ftrace_traceoff
```
**Symbols:**

```
ffffffff81164d50-ffffffff81164d73: tracer_tracing_off (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void tracer_tracing_off(struct trace_array *tr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff826d2953)
Location: kernel/trace/trace.c:1048
Inline: True
Inline callers:
  - kernel/trace/trace.c:early_trace_init
  - kernel/trace/trace.c:rb_simple_write
  - kernel/trace/trace.c:tracing_free_buffer_release
  - kernel/trace/trace.c:disable_trace_on_warning
  - kernel/trace/trace.c:tracing_snapshot_instance
Direct callers:
  - kernel/trace/trace_functions.c:ftrace_traceoff
```
**Symbols:**

```
ffffffff81171cb0-ffffffff81171cd3: tracer_tracing_off (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void tracer_tracing_off(struct trace_array *tr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff826fd13c)
Location: kernel/trace/trace.c:1047
Inline: True
Inline callers:
  - kernel/trace/trace.c:early_trace_init
  - kernel/trace/trace.c:rb_simple_write
  - kernel/trace/trace.c:tracing_free_buffer_release
  - kernel/trace/trace.c:disable_trace_on_warning
  - kernel/trace/trace.c:tracing_snapshot_instance
Direct callers:
  - kernel/trace/trace_functions.c:ftrace_traceoff
```
**Symbols:**

```
ffffffff81180e20-ffffffff81180e43: tracer_tracing_off (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void tracer_tracing_off(struct trace_array *tr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff828b4056)
Location: kernel/trace/trace.c:1048
Inline: True
Inline callers:
  - kernel/trace/trace.c:early_trace_init
  - kernel/trace/trace.c:rb_simple_write
  - kernel/trace/trace.c:tracing_free_buffer_release
  - kernel/trace/trace.c:disable_trace_on_warning
  - kernel/trace/trace.c:tracing_snapshot_instance
Direct callers:
  - kernel/trace/trace_functions.c:ftrace_traceoff
```
**Symbols:**

```
ffffffff8118e7e0-ffffffff8118e803: tracer_tracing_off (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void tracer_tracing_off(struct trace_array *tr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff828ccbd8)
Location: kernel/trace/trace.c:1219
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracer_alloc_buffers
  - kernel/trace/trace.c:rb_simple_write
  - kernel/trace/trace.c:tracing_free_buffer_release
  - kernel/trace/trace.c:disable_trace_on_warning
  - kernel/trace/trace.c:tracing_snapshot_instance_cond
Direct callers:
  - kernel/trace/trace_functions.c:ftrace_traceoff
```
**Symbols:**

```
ffffffff8119c1e0-ffffffff8119c203: tracer_tracing_off (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void tracer_tracing_off(struct trace_array *tr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff828d510a)
Location: kernel/trace/trace.c:1237
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracer_alloc_buffers
  - kernel/trace/trace.c:rb_simple_write
  - kernel/trace/trace.c:tracing_free_buffer_release
  - kernel/trace/trace.c:disable_trace_on_warning
  - kernel/trace/trace.c:tracing_snapshot_instance_cond
Direct callers:
  - kernel/trace/trace_functions.c:ftrace_traceoff
```
**Symbols:**

```
ffffffff811a7bd0-ffffffff811a7bf3: tracer_tracing_off (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void tracer_tracing_off(struct trace_array *tr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811bcf15)
Location: kernel/trace/trace.c:1269
Inline: True
Inline callers:
  - kernel/trace/trace.c:rb_simple_write
  - kernel/trace/trace.c:tracing_free_buffer_release
  - kernel/trace/trace.c:disable_trace_on_warning
  - kernel/trace/trace.c:tracing_snapshot_instance_cond
Direct callers:
  - kernel/trace/trace_functions.c:ftrace_traceoff
  - kernel/trace/trace_functions.c:ftrace_traceoff_count
```
**Symbols:**

```
ffffffff811bffb0-ffffffff811bffd6: tracer_tracing_off (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void tracer_tracing_off(struct trace_array *tr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811bab25)
Location: kernel/trace/trace.c:1420
Inline: True
Inline callers:
  - kernel/trace/trace.c:rb_simple_write
  - kernel/trace/trace.c:tracing_free_buffer_release
  - kernel/trace/trace.c:disable_trace_on_warning
  - kernel/trace/trace.c:tracing_snapshot_instance_cond
Direct callers:
  - kernel/trace/trace_functions.c:ftrace_traceoff
  - kernel/trace/trace_functions.c:ftrace_traceoff_count
  - kernel/trace/trace_boot.c:trace_boot_set_instance_options
```
**Symbols:**

```
ffffffff811bdbe0-ffffffff811bdc06: tracer_tracing_off (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void tracer_tracing_off(struct trace_array *tr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811bad95)
Location: kernel/trace/trace.c:1417
Inline: True
Inline callers:
  - kernel/trace/trace.c:rb_simple_write
  - kernel/trace/trace.c:tracing_free_buffer_release
  - kernel/trace/trace.c:disable_trace_on_warning
  - kernel/trace/trace.c:tracing_snapshot_instance_cond
Direct callers:
  - kernel/trace/trace_functions.c:ftrace_traceoff
  - kernel/trace/trace_functions.c:ftrace_traceoff_count
  - kernel/trace/trace_boot.c:trace_boot_set_instance_options
```
**Symbols:**

```
ffffffff811bd6f0-ffffffff811bd716: tracer_tracing_off (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void tracer_tracing_off(struct trace_array *tr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811e5545)
Location: kernel/trace/trace.c:1430
Inline: True
Inline callers:
  - kernel/trace/trace.c:rb_simple_write
  - kernel/trace/trace.c:tracing_free_buffer_release
  - kernel/trace/trace.c:disable_trace_on_warning
  - kernel/trace/trace.c:tracing_snapshot_instance_cond
Direct callers:
  - kernel/trace/trace_functions.c:ftrace_traceoff
  - kernel/trace/trace_functions.c:ftrace_traceoff_count
  - kernel/trace/trace_events_trigger.c:traceoff_count_trigger
  - kernel/trace/trace_boot.c:trace_boot_set_instance_options
```
**Symbols:**

```
ffffffff811e81f0-ffffffff811e8216: tracer_tracing_off (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void tracer_tracing_off(struct trace_array *tr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8121c91d)
Location: kernel/trace/trace.c:1420
Inline: True
Inline callers:
  - kernel/trace/trace.c:rb_simple_write
  - kernel/trace/trace.c:tracing_free_buffer_release
  - kernel/trace/trace.c:disable_trace_on_warning
  - kernel/trace/trace.c:tracing_snapshot_instance_cond
Direct callers:
  - kernel/trace/trace_functions.c:ftrace_traceoff
  - kernel/trace/trace_functions.c:ftrace_traceoff_count
  - kernel/trace/trace_events_trigger.c:traceoff_count_trigger
  - kernel/trace/trace_boot.c:trace_boot_set_instance_options
```
**Symbols:**

```
ffffffff8121fd20-ffffffff8121fd4c: tracer_tracing_off (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void tracer_tracing_off(struct trace_array *tr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff812671e3)
Location: kernel/trace/trace.c:1426
Inline: True
Inline callers:
  - kernel/trace/trace.c:rb_simple_write
  - kernel/trace/trace.c:tracing_free_buffer_release
  - kernel/trace/trace.c:disable_trace_on_warning
  - kernel/trace/trace.c:tracing_snapshot_instance_cond
Direct callers:
  - kernel/trace/trace_functions.c:ftrace_traceoff
  - kernel/trace/trace_functions.c:ftrace_traceoff_count
  - kernel/trace/trace_events_trigger.c:traceoff_count_trigger
  - kernel/trace/trace_boot.c:trace_boot_set_instance_options
```
**Symbols:**

```
ffffffff8126a9a0-ffffffff8126a9cc: tracer_tracing_off (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void tracer_tracing_off(struct trace_array *tr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8127e2a3)
Location: kernel/trace/trace.c:1477
Inline: True
Inline callers:
  - kernel/trace/trace.c:rb_simple_write
  - kernel/trace/trace.c:tracing_free_buffer_release
  - kernel/trace/trace.c:disable_trace_on_warning
  - kernel/trace/trace.c:tracing_snapshot_instance_cond
Direct callers:
  - kernel/trace/trace_functions.c:ftrace_traceoff
  - kernel/trace/trace_functions.c:ftrace_traceoff_count
  - kernel/trace/trace_osnoise.c:timerlat_fd_read
  - kernel/trace/trace_osnoise.c:timerlat_fd_read
  - kernel/trace/trace_osnoise.c:timerlat_fd_read
  - kernel/trace/trace_osnoise.c:timerlat_main
  - kernel/trace/trace_osnoise.c:timerlat_irq
  - kernel/trace/trace_osnoise.c:trace_sched_migrate_callback
  - kernel/trace/trace_events_trigger.c:traceoff_count_trigger
  - kernel/trace/trace_boot.c:trace_boot_set_instance_options
```
**Symbols:**

```
ffffffff81281b20-ffffffff81281b4c: tracer_tracing_off (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void tracer_tracing_off(struct trace_array *tr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff81298ee3)
Location: kernel/trace/trace.c:1487
Inline: True
Inline callers:
  - kernel/trace/trace.c:rb_simple_write
  - kernel/trace/trace.c:tracing_free_buffer_release
  - kernel/trace/trace.c:disable_trace_on_warning
  - kernel/trace/trace.c:tracing_snapshot_instance_cond
Direct callers:
  - kernel/trace/trace_functions.c:ftrace_traceoff
  - kernel/trace/trace_functions.c:ftrace_traceoff_count
  - kernel/trace/trace_osnoise.c:timerlat_fd_read
  - kernel/trace/trace_osnoise.c:timerlat_fd_read
  - kernel/trace/trace_osnoise.c:timerlat_fd_read
  - kernel/trace/trace_osnoise.c:timerlat_main
  - kernel/trace/trace_osnoise.c:timerlat_irq
  - kernel/trace/trace_osnoise.c:trace_sched_migrate_callback
  - kernel/trace/trace_events_trigger.c:traceoff_count_trigger
  - kernel/trace/trace_boot.c:trace_boot_set_instance_options
```
**Symbols:**

```
ffffffff8129cca0-ffffffff8129cccc: tracer_tracing_off (STB_GLOBAL)
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
void tracer_tracing_off(struct trace_array *tr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffff80001144d974)
Location: kernel/trace/trace.c:1237
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracer_alloc_buffers
  - kernel/trace/trace.c:rb_simple_write
  - kernel/trace/trace.c:tracing_free_buffer_release
  - kernel/trace/trace.c:disable_trace_on_warning
  - kernel/trace/trace.c:tracing_snapshot_instance_cond
Direct callers:
  - kernel/trace/trace_functions.c:ftrace_traceoff
```
**Symbols:**

```
ffff8000102241f8-ffff80001022422c: tracer_tracing_off (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void tracer_tracing_off(struct trace_array *tr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (c1527f30)
Location: kernel/trace/trace.c:1237
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracer_alloc_buffers
  - kernel/trace/trace.c:rb_simple_write
  - kernel/trace/trace.c:tracing_free_buffer_release
  - kernel/trace/trace.c:disable_trace_on_warning
  - kernel/trace/trace.c:tracing_snapshot_instance_cond
Direct callers:
  - kernel/trace/trace_functions.c:ftrace_traceoff
  - kernel/trace/trace_functions.c:ftrace_traceoff_count
```
**Symbols:**

```
c0461974-c04619a4: tracer_tracing_off (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void tracer_tracing_off(struct trace_array *tr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (c000000001373fac)
Location: kernel/trace/trace.c:1237
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracer_alloc_buffers
  - kernel/trace/trace.c:rb_simple_write
  - kernel/trace/trace.c:tracing_free_buffer_release
  - kernel/trace/trace.c:disable_trace_on_warning
  - kernel/trace/trace.c:tracing_snapshot_instance_cond
Direct callers:
  - kernel/trace/trace_functions.c:ftrace_traceoff
```
**Symbols:**

```
c0000000002a9110-c0000000002a9160: tracer_tracing_off (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void tracer_tracing_off(struct trace_array *tr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffe00000dfa8)
Location: kernel/trace/trace.c:1237
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracer_alloc_buffers
  - kernel/trace/trace.c:rb_simple_write
  - kernel/trace/trace.c:tracing_free_buffer_release
  - kernel/trace/trace.c:disable_trace_on_warning
  - kernel/trace/trace.c:tracing_snapshot_instance_cond
Direct callers:
  - kernel/trace/trace_functions.c:ftrace_traceoff
```
**Symbols:**

```
ffffffe00017f72a-ffffffe00017f756: tracer_tracing_off (STB_GLOBAL)
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
void tracer_tracing_off(struct trace_array *tr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff828bdfbb)
Location: kernel/trace/trace.c:1237
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracer_alloc_buffers
  - kernel/trace/trace.c:rb_simple_write
  - kernel/trace/trace.c:tracing_free_buffer_release
  - kernel/trace/trace.c:disable_trace_on_warning
  - kernel/trace/trace.c:tracing_snapshot_instance_cond
Direct callers:
  - kernel/trace/trace_functions.c:ftrace_traceoff
```
**Symbols:**

```
ffffffff811a01f0-ffffffff811a0213: tracer_tracing_off (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void tracer_tracing_off(struct trace_array *tr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff828b665b)
Location: kernel/trace/trace.c:1237
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracer_alloc_buffers
  - kernel/trace/trace.c:rb_simple_write
  - kernel/trace/trace.c:tracing_free_buffer_release
  - kernel/trace/trace.c:disable_trace_on_warning
  - kernel/trace/trace.c:tracing_snapshot_instance_cond
Direct callers:
  - kernel/trace/trace_functions.c:ftrace_traceoff
```
**Symbols:**

```
ffffffff81193200-ffffffff81193223: tracer_tracing_off (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void tracer_tracing_off(struct trace_array *tr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff828d0d3e)
Location: kernel/trace/trace.c:1237
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracer_alloc_buffers
  - kernel/trace/trace.c:rb_simple_write
  - kernel/trace/trace.c:tracing_free_buffer_release
  - kernel/trace/trace.c:disable_trace_on_warning
  - kernel/trace/trace.c:tracing_snapshot_instance_cond
Direct callers:
  - kernel/trace/trace_functions.c:ftrace_traceoff
```
**Symbols:**

```
ffffffff8119dfc0-ffffffff8119dfe3: tracer_tracing_off (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void tracer_tracing_off(struct trace_array *tr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff828d615f)
Location: kernel/trace/trace.c:1237
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracer_alloc_buffers
  - kernel/trace/trace.c:rb_simple_write
  - kernel/trace/trace.c:tracing_free_buffer_release
  - kernel/trace/trace.c:disable_trace_on_warning
  - kernel/trace/trace.c:tracing_snapshot_instance_cond
Direct callers:
  - kernel/trace/trace_functions.c:ftrace_traceoff
```
**Symbols:**

```
ffffffff811abca0-ffffffff811abcc3: tracer_tracing_off (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
