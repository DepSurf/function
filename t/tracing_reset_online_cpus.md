# Function: <code>tracing_reset_online_cpus</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void tracing_reset_online_cpus(struct trace_buffer *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8114e1a0)
Location: kernel/trace/trace.c:1319
Inline: False
Direct callers:
  - kernel/trace/trace.c:free_snapshot
  - kernel/trace/trace.c:tracing_set_clock
  - kernel/trace/trace.c:tracing_set_clock
  - kernel/trace/trace.c:tracing_set_tracer
  - kernel/trace/trace.c:tracing_reset_all_online_cpus
  - kernel/trace/trace.c:tracing_reset_all_online_cpus
  - kernel/trace/trace.c:tracing_open
  - kernel/trace/trace.c:tracing_snapshot_write
  - kernel/trace/trace_functions.c:function_trace_start
  - kernel/trace/trace_sched_wakeup.c:wakeup_reset
  - kernel/trace/trace_mmiotrace.c:mmio_trace_start
  - kernel/trace/trace_mmiotrace.c:mmio_trace_reset
  - kernel/trace/trace_mmiotrace.c:mmio_trace_init
```
**Symbols:**

```
ffffffff8114e1a0-ffffffff8114e216: tracing_reset_online_cpus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void tracing_reset_online_cpus(struct trace_buffer *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff81156e00)
Location: kernel/trace/trace.c:1564
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_snapshot_write
  - kernel/trace/trace.c:tracing_set_clock
  - kernel/trace/trace.c:tracing_set_clock
  - kernel/trace/trace.c:tracing_set_tracer
  - kernel/trace/trace.c:tracing_open
  - kernel/trace/trace.c:tracing_reset_all_online_cpus
  - kernel/trace/trace.c:tracing_reset_all_online_cpus
  - kernel/trace/trace.c:free_snapshot
  - kernel/trace/trace_functions.c:function_trace_start
  - kernel/trace/trace_sched_wakeup.c:wakeup_reset
  - kernel/trace/trace_mmiotrace.c:mmio_trace_start
  - kernel/trace/trace_mmiotrace.c:mmio_trace_reset
  - kernel/trace/trace_mmiotrace.c:mmio_trace_init
```
**Symbols:**

```
ffffffff81156e00-ffffffff81156e76: tracing_reset_online_cpus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void tracing_reset_online_cpus(struct trace_buffer *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff81161f40)
Location: kernel/trace/trace.c:1608
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_snapshot_write
  - kernel/trace/trace.c:tracing_set_clock
  - kernel/trace/trace.c:tracing_set_clock
  - kernel/trace/trace.c:tracing_set_tracer
  - kernel/trace/trace.c:tracing_open
  - kernel/trace/trace.c:tracing_reset_all_online_cpus
  - kernel/trace/trace.c:tracing_reset_all_online_cpus
  - kernel/trace/trace.c:free_snapshot
  - kernel/trace/trace_functions.c:function_trace_start
  - kernel/trace/trace_sched_wakeup.c:wakeup_reset
  - kernel/trace/trace_mmiotrace.c:mmio_trace_start
  - kernel/trace/trace_mmiotrace.c:mmio_trace_reset
  - kernel/trace/trace_mmiotrace.c:mmio_trace_init
```
**Symbols:**

```
ffffffff81161f40-ffffffff81161fb8: tracing_reset_online_cpus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void tracing_reset_online_cpus(struct trace_buffer *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff81165360)
Location: kernel/trace/trace.c:1678
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_snapshot_write
  - kernel/trace/trace.c:tracing_set_clock
  - kernel/trace/trace.c:tracing_set_clock
  - kernel/trace/trace.c:tracing_set_tracer
  - kernel/trace/trace.c:tracing_open
  - kernel/trace/trace.c:tracing_reset_all_online_cpus
  - kernel/trace/trace.c:tracing_reset_all_online_cpus
  - kernel/trace/trace.c:free_snapshot
  - kernel/trace/trace_functions.c:function_trace_start
  - kernel/trace/trace_sched_wakeup.c:wakeup_reset
  - kernel/trace/trace_mmiotrace.c:mmio_trace_start
  - kernel/trace/trace_mmiotrace.c:mmio_trace_reset
  - kernel/trace/trace_mmiotrace.c:mmio_trace_init
```
**Symbols:**

```
ffffffff81165360-ffffffff811653d7: tracing_reset_online_cpus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void tracing_reset_online_cpus(struct trace_buffer *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811722b0)
Location: kernel/trace/trace.c:1678
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_snapshot_write
  - kernel/trace/trace.c:tracing_set_clock
  - kernel/trace/trace.c:tracing_set_clock
  - kernel/trace/trace.c:tracing_set_tracer
  - kernel/trace/trace.c:tracing_open
  - kernel/trace/trace.c:tracing_reset_all_online_cpus
  - kernel/trace/trace.c:tracing_reset_all_online_cpus
  - kernel/trace/trace.c:free_snapshot
  - kernel/trace/trace_functions.c:function_trace_start
  - kernel/trace/trace_sched_wakeup.c:wakeup_reset
  - kernel/trace/trace_mmiotrace.c:mmio_trace_start
  - kernel/trace/trace_mmiotrace.c:mmio_trace_reset
  - kernel/trace/trace_mmiotrace.c:mmio_trace_init
```
**Symbols:**

```
ffffffff811722b0-ffffffff8117231d: tracing_reset_online_cpus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void tracing_reset_online_cpus(struct trace_buffer *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff81181440)
Location: kernel/trace/trace.c:1689
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_snapshot_write
  - kernel/trace/trace.c:tracing_set_clock
  - kernel/trace/trace.c:tracing_set_clock
  - kernel/trace/trace.c:tracing_set_tracer
  - kernel/trace/trace.c:tracing_open
  - kernel/trace/trace.c:tracing_reset_all_online_cpus
  - kernel/trace/trace.c:tracing_reset_all_online_cpus
  - kernel/trace/trace.c:free_snapshot
  - kernel/trace/trace_functions.c:function_trace_start
  - kernel/trace/trace_sched_wakeup.c:wakeup_reset
  - kernel/trace/trace_mmiotrace.c:mmio_trace_start
  - kernel/trace/trace_mmiotrace.c:mmio_trace_reset
  - kernel/trace/trace_mmiotrace.c:mmio_trace_init
```
**Symbols:**

```
ffffffff81181440-ffffffff811814ad: tracing_reset_online_cpus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void tracing_reset_online_cpus(struct trace_buffer *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8118ee00)
Location: kernel/trace/trace.c:1690
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_snapshot_write
  - kernel/trace/trace.c:tracing_set_clock
  - kernel/trace/trace.c:tracing_set_clock
  - kernel/trace/trace.c:tracing_set_tracer
  - kernel/trace/trace.c:tracing_open
  - kernel/trace/trace.c:tracing_reset_all_online_cpus
  - kernel/trace/trace.c:tracing_reset_all_online_cpus
  - kernel/trace/trace.c:free_snapshot
  - kernel/trace/trace_functions.c:function_trace_start
  - kernel/trace/trace_sched_wakeup.c:wakeup_reset
  - kernel/trace/trace_mmiotrace.c:mmio_trace_start
  - kernel/trace/trace_mmiotrace.c:mmio_trace_reset
  - kernel/trace/trace_mmiotrace.c:mmio_trace_init
```
**Symbols:**

```
ffffffff8118ee00-ffffffff8118ee6d: tracing_reset_online_cpus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void tracing_reset_online_cpus(struct trace_buffer *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8119c780)
Location: kernel/trace/trace.c:1873
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_snapshot_write
  - kernel/trace/trace.c:tracing_set_clock
  - kernel/trace/trace.c:tracing_set_clock
  - kernel/trace/trace.c:tracing_set_tracer
  - kernel/trace/trace.c:tracing_open
  - kernel/trace/trace.c:tracing_reset_all_online_cpus
  - kernel/trace/trace.c:tracing_reset_all_online_cpus
  - kernel/trace/trace.c:free_snapshot
  - kernel/trace/trace_functions.c:function_trace_start
  - kernel/trace/trace_sched_wakeup.c:wakeup_reset
  - kernel/trace/trace_mmiotrace.c:mmio_trace_start
  - kernel/trace/trace_mmiotrace.c:mmio_trace_reset
  - kernel/trace/trace_mmiotrace.c:mmio_trace_init
```
**Symbols:**

```
ffffffff8119c780-ffffffff8119c7f0: tracing_reset_online_cpus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void tracing_reset_online_cpus(struct trace_buffer *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811a8130)
Location: kernel/trace/trace.c:1899
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_snapshot_write
  - kernel/trace/trace.c:tracing_set_clock
  - kernel/trace/trace.c:tracing_set_clock
  - kernel/trace/trace.c:tracing_set_tracer
  - kernel/trace/trace.c:tracing_open
  - kernel/trace/trace.c:tracing_reset_all_online_cpus
  - kernel/trace/trace.c:tracing_reset_all_online_cpus
  - kernel/trace/trace.c:free_snapshot
  - kernel/trace/trace_functions.c:function_trace_start
  - kernel/trace/trace_sched_wakeup.c:wakeup_reset
  - kernel/trace/trace_mmiotrace.c:mmio_trace_start
  - kernel/trace/trace_mmiotrace.c:mmio_trace_reset
  - kernel/trace/trace_mmiotrace.c:mmio_trace_init
```
**Symbols:**

```
ffffffff811a8130-ffffffff811a81a0: tracing_reset_online_cpus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void tracing_reset_online_cpus(struct array_buffer *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811c04f0)
Location: kernel/trace/trace.c:2003
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_snapshot_write
  - kernel/trace/trace.c:tracing_snapshot_write
  - kernel/trace/trace.c:tracing_set_clock
  - kernel/trace/trace.c:tracing_set_clock
  - kernel/trace/trace.c:tracing_set_tracer
  - kernel/trace/trace.c:tracing_set_tracer
  - kernel/trace/trace.c:tracing_open
  - kernel/trace/trace.c:tracing_reset_all_online_cpus
  - kernel/trace/trace.c:tracing_reset_all_online_cpus
  - kernel/trace/trace_functions.c:function_trace_start
  - kernel/trace/trace_sched_wakeup.c:wakeup_reset
  - kernel/trace/trace_mmiotrace.c:mmio_trace_start
  - kernel/trace/trace_mmiotrace.c:mmio_trace_reset
  - kernel/trace/trace_mmiotrace.c:mmio_trace_init
```
**Symbols:**

```
ffffffff811c04f0-ffffffff811c05b7: tracing_reset_online_cpus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void tracing_reset_online_cpus(struct array_buffer *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811be160)
Location: kernel/trace/trace.c:2149
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_snapshot_write
  - kernel/trace/trace.c:tracing_snapshot_write
  - kernel/trace/trace.c:tracing_set_clock
  - kernel/trace/trace.c:tracing_set_clock
  - kernel/trace/trace.c:tracing_set_tracer
  - kernel/trace/trace.c:tracing_set_tracer
  - kernel/trace/trace.c:tracing_open
  - kernel/trace/trace.c:tracing_reset_all_online_cpus
  - kernel/trace/trace.c:tracing_reset_all_online_cpus
  - kernel/trace/trace_functions.c:function_trace_start
  - kernel/trace/trace_sched_wakeup.c:wakeup_reset
  - kernel/trace/trace_mmiotrace.c:mmio_trace_start
  - kernel/trace/trace_mmiotrace.c:mmio_trace_reset
  - kernel/trace/trace_mmiotrace.c:mmio_trace_init
```
**Symbols:**

```
ffffffff811be160-ffffffff811be1fc: tracing_reset_online_cpus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void tracing_reset_online_cpus(struct array_buffer *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811bdcb0)
Location: kernel/trace/trace.c:2152
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_snapshot_write
  - kernel/trace/trace.c:tracing_snapshot_write
  - kernel/trace/trace.c:tracing_set_clock
  - kernel/trace/trace.c:tracing_set_clock
  - kernel/trace/trace.c:tracing_set_tracer
  - kernel/trace/trace.c:tracing_set_tracer
  - kernel/trace/trace.c:tracing_open
  - kernel/trace/trace.c:tracing_reset_all_online_cpus
  - kernel/trace/trace.c:tracing_reset_all_online_cpus
  - kernel/trace/trace_functions.c:function_trace_start
  - kernel/trace/trace_sched_wakeup.c:wakeup_reset
  - kernel/trace/trace_mmiotrace.c:mmio_trace_start
  - kernel/trace/trace_mmiotrace.c:mmio_trace_reset
  - kernel/trace/trace_mmiotrace.c:mmio_trace_init
```
**Symbols:**

```
ffffffff811bdcb0-ffffffff811bdd49: tracing_reset_online_cpus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void tracing_reset_online_cpus(struct array_buffer *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811e8800)
Location: kernel/trace/trace.c:2166
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_snapshot_write
  - kernel/trace/trace.c:tracing_snapshot_write
  - kernel/trace/trace.c:tracing_set_clock
  - kernel/trace/trace.c:tracing_set_clock
  - kernel/trace/trace.c:tracing_set_tracer
  - kernel/trace/trace.c:tracing_set_tracer
  - kernel/trace/trace.c:tracing_open
  - kernel/trace/trace.c:tracing_reset_all_online_cpus
  - kernel/trace/trace.c:tracing_reset_all_online_cpus
  - kernel/trace/trace_functions.c:function_trace_start
  - kernel/trace/trace_sched_wakeup.c:wakeup_reset
  - kernel/trace/trace_mmiotrace.c:mmio_trace_start
  - kernel/trace/trace_mmiotrace.c:mmio_trace_reset
  - kernel/trace/trace_mmiotrace.c:mmio_trace_init
```
**Symbols:**

```
ffffffff811e8800-ffffffff811e8899: tracing_reset_online_cpus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void tracing_reset_online_cpus(struct array_buffer *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff81220390)
Location: kernel/trace/trace.c:2157
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_snapshot_write
  - kernel/trace/trace.c:tracing_snapshot_write
  - kernel/trace/trace.c:tracing_set_clock
  - kernel/trace/trace.c:tracing_set_clock
  - kernel/trace/trace.c:tracing_set_tracer
  - kernel/trace/trace.c:tracing_set_tracer
  - kernel/trace/trace.c:tracing_open
  - kernel/trace/trace.c:tracing_reset_all_online_cpus
  - kernel/trace/trace.c:tracing_reset_all_online_cpus
  - kernel/trace/trace_functions.c:function_trace_start
  - kernel/trace/trace_sched_wakeup.c:wakeup_reset
  - kernel/trace/trace_mmiotrace.c:mmio_trace_start
  - kernel/trace/trace_mmiotrace.c:mmio_trace_reset
  - kernel/trace/trace_mmiotrace.c:mmio_trace_init
```
**Symbols:**

```
ffffffff81220390-ffffffff8122043d: tracing_reset_online_cpus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void tracing_reset_online_cpus(struct array_buffer *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8126b100)
Location: kernel/trace/trace.c:2163
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_snapshot_write
  - kernel/trace/trace.c:tracing_snapshot_write
  - kernel/trace/trace.c:tracing_set_clock
  - kernel/trace/trace.c:tracing_set_clock
  - kernel/trace/trace.c:tracing_set_tracer
  - kernel/trace/trace.c:tracing_set_tracer
  - kernel/trace/trace.c:tracing_open
  - kernel/trace/trace.c:tracing_reset_all_online_cpus_unlocked
  - kernel/trace/trace.c:tracing_reset_all_online_cpus_unlocked
  - kernel/trace/trace_functions.c:function_trace_start
  - kernel/trace/trace_sched_wakeup.c:wakeup_reset
  - kernel/trace/trace_mmiotrace.c:mmio_trace_start
  - kernel/trace/trace_mmiotrace.c:mmio_trace_reset
  - kernel/trace/trace_mmiotrace.c:mmio_trace_init
```
**Symbols:**

```
ffffffff8126b100-ffffffff8126b1ad: tracing_reset_online_cpus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void tracing_reset_online_cpus(struct array_buffer *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff81282270)
Location: kernel/trace/trace.c:2234
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_snapshot_write
  - kernel/trace/trace.c:tracing_snapshot_write
  - kernel/trace/trace.c:tracing_set_clock
  - kernel/trace/trace.c:tracing_set_clock
  - kernel/trace/trace.c:tracing_set_tracer
  - kernel/trace/trace.c:tracing_set_tracer
  - kernel/trace/trace.c:tracing_open
  - kernel/trace/trace.c:tracing_reset_all_online_cpus_unlocked
  - kernel/trace/trace.c:tracing_reset_all_online_cpus_unlocked
  - kernel/trace/trace_functions.c:function_trace_start
  - kernel/trace/trace_sched_wakeup.c:wakeup_reset
  - kernel/trace/trace_mmiotrace.c:mmio_trace_start
  - kernel/trace/trace_mmiotrace.c:mmio_trace_reset
  - kernel/trace/trace_mmiotrace.c:mmio_trace_init
```
**Symbols:**

```
ffffffff81282270-ffffffff8128231d: tracing_reset_online_cpus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void tracing_reset_online_cpus(struct array_buffer *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8129d3f0)
Location: kernel/trace/trace.c:2258
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_snapshot_write
  - kernel/trace/trace.c:tracing_snapshot_write
  - kernel/trace/trace.c:tracing_set_clock
  - kernel/trace/trace.c:tracing_set_clock
  - kernel/trace/trace.c:tracing_set_tracer
  - kernel/trace/trace.c:tracing_set_tracer
  - kernel/trace/trace.c:tracing_open
  - kernel/trace/trace.c:tracing_reset_all_online_cpus_unlocked
  - kernel/trace/trace.c:tracing_reset_all_online_cpus_unlocked
  - kernel/trace/trace_functions.c:function_trace_start
  - kernel/trace/trace_sched_wakeup.c:wakeup_reset
  - kernel/trace/trace_mmiotrace.c:mmio_trace_start
  - kernel/trace/trace_mmiotrace.c:mmio_trace_reset
  - kernel/trace/trace_mmiotrace.c:mmio_trace_init
```
**Symbols:**

```
ffffffff8129d3f0-ffffffff8129d49d: tracing_reset_online_cpus (STB_GLOBAL)
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
void tracing_reset_online_cpus(struct trace_buffer *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffff800010224b48)
Location: kernel/trace/trace.c:1899
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_snapshot_write
  - kernel/trace/trace.c:tracing_set_clock
  - kernel/trace/trace.c:tracing_set_clock
  - kernel/trace/trace.c:tracing_set_tracer
  - kernel/trace/trace.c:tracing_open
  - kernel/trace/trace.c:tracing_reset_all_online_cpus
  - kernel/trace/trace.c:tracing_reset_all_online_cpus
  - kernel/trace/trace.c:free_snapshot
  - kernel/trace/trace_functions.c:function_trace_start
  - kernel/trace/trace_sched_wakeup.c:wakeup_reset
```
**Symbols:**

```
ffff800010224b48-ffff800010224bdc: tracing_reset_online_cpus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void tracing_reset_online_cpus(struct trace_buffer *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (c0461ff0)
Location: kernel/trace/trace.c:1899
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_snapshot_write
  - kernel/trace/trace.c:tracing_set_clock
  - kernel/trace/trace.c:tracing_set_clock
  - kernel/trace/trace.c:tracing_set_tracer
  - kernel/trace/trace.c:tracing_open
  - kernel/trace/trace.c:tracing_reset_all_online_cpus
  - kernel/trace/trace.c:tracing_reset_all_online_cpus
  - kernel/trace/trace.c:free_snapshot
  - kernel/trace/trace_functions.c:function_trace_start
  - kernel/trace/trace_sched_wakeup.c:wakeup_reset
```
**Symbols:**

```
c0461ff0-c0462070: tracing_reset_online_cpus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void tracing_reset_online_cpus(struct trace_buffer *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (c0000000002a9b30)
Location: kernel/trace/trace.c:1899
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_snapshot_write
  - kernel/trace/trace.c:tracing_set_clock
  - kernel/trace/trace.c:tracing_set_clock
  - kernel/trace/trace.c:tracing_set_tracer
  - kernel/trace/trace.c:tracing_open
  - kernel/trace/trace.c:tracing_reset_all_online_cpus
  - kernel/trace/trace.c:tracing_reset_all_online_cpus
  - kernel/trace/trace.c:free_snapshot
  - kernel/trace/trace_functions.c:function_trace_start
  - kernel/trace/trace_sched_wakeup.c:wakeup_reset
```
**Symbols:**

```
c0000000002a9b30-c0000000002a9c10: tracing_reset_online_cpus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void tracing_reset_online_cpus(struct trace_buffer *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffe00017fc90)
Location: kernel/trace/trace.c:1899
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_snapshot_write
  - kernel/trace/trace.c:tracing_set_clock
  - kernel/trace/trace.c:tracing_set_clock
  - kernel/trace/trace.c:tracing_set_tracer
  - kernel/trace/trace.c:tracing_open
  - kernel/trace/trace.c:tracing_reset_all_online_cpus
  - kernel/trace/trace.c:tracing_reset_all_online_cpus
  - kernel/trace/trace.c:free_snapshot
  - kernel/trace/trace_functions.c:function_trace_start
  - kernel/trace/trace_sched_wakeup.c:wakeup_reset
```
**Symbols:**

```
ffffffe00017fc90-ffffffe00017fd22: tracing_reset_online_cpus (STB_GLOBAL)
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
void tracing_reset_online_cpus(struct trace_buffer *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811a0750)
Location: kernel/trace/trace.c:1899
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_snapshot_write
  - kernel/trace/trace.c:tracing_set_clock
  - kernel/trace/trace.c:tracing_set_clock
  - kernel/trace/trace.c:tracing_set_tracer
  - kernel/trace/trace.c:tracing_open
  - kernel/trace/trace.c:tracing_reset_all_online_cpus
  - kernel/trace/trace.c:tracing_reset_all_online_cpus
  - kernel/trace/trace.c:free_snapshot
  - kernel/trace/trace_functions.c:function_trace_start
  - kernel/trace/trace_sched_wakeup.c:wakeup_reset
  - kernel/trace/trace_mmiotrace.c:mmio_trace_start
  - kernel/trace/trace_mmiotrace.c:mmio_trace_reset
  - kernel/trace/trace_mmiotrace.c:mmio_trace_init
```
**Symbols:**

```
ffffffff811a0750-ffffffff811a07c0: tracing_reset_online_cpus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void tracing_reset_online_cpus(struct trace_buffer *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff81193760)
Location: kernel/trace/trace.c:1899
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_snapshot_write
  - kernel/trace/trace.c:tracing_set_clock
  - kernel/trace/trace.c:tracing_set_clock
  - kernel/trace/trace.c:tracing_set_tracer
  - kernel/trace/trace.c:tracing_open
  - kernel/trace/trace.c:tracing_reset_all_online_cpus
  - kernel/trace/trace.c:tracing_reset_all_online_cpus
  - kernel/trace/trace.c:free_snapshot
  - kernel/trace/trace_functions.c:function_trace_start
  - kernel/trace/trace_sched_wakeup.c:wakeup_reset
  - kernel/trace/trace_mmiotrace.c:mmio_trace_start
  - kernel/trace/trace_mmiotrace.c:mmio_trace_reset
  - kernel/trace/trace_mmiotrace.c:mmio_trace_init
```
**Symbols:**

```
ffffffff81193760-ffffffff811937d0: tracing_reset_online_cpus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void tracing_reset_online_cpus(struct trace_buffer *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8119e520)
Location: kernel/trace/trace.c:1899
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_snapshot_write
  - kernel/trace/trace.c:tracing_set_clock
  - kernel/trace/trace.c:tracing_set_clock
  - kernel/trace/trace.c:tracing_set_tracer
  - kernel/trace/trace.c:tracing_open
  - kernel/trace/trace.c:tracing_reset_all_online_cpus
  - kernel/trace/trace.c:tracing_reset_all_online_cpus
  - kernel/trace/trace.c:free_snapshot
  - kernel/trace/trace_functions.c:function_trace_start
  - kernel/trace/trace_sched_wakeup.c:wakeup_reset
  - kernel/trace/trace_mmiotrace.c:mmio_trace_start
  - kernel/trace/trace_mmiotrace.c:mmio_trace_reset
  - kernel/trace/trace_mmiotrace.c:mmio_trace_init
```
**Symbols:**

```
ffffffff8119e520-ffffffff8119e590: tracing_reset_online_cpus (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void tracing_reset_online_cpus(struct trace_buffer *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811ac200)
Location: kernel/trace/trace.c:1899
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_snapshot_write
  - kernel/trace/trace.c:tracing_set_clock
  - kernel/trace/trace.c:tracing_set_clock
  - kernel/trace/trace.c:tracing_set_tracer
  - kernel/trace/trace.c:tracing_open
  - kernel/trace/trace.c:tracing_reset_all_online_cpus
  - kernel/trace/trace.c:tracing_reset_all_online_cpus
  - kernel/trace/trace.c:free_snapshot
  - kernel/trace/trace_functions.c:function_trace_start
  - kernel/trace/trace_sched_wakeup.c:wakeup_reset
  - kernel/trace/trace_mmiotrace.c:mmio_trace_start
  - kernel/trace/trace_mmiotrace.c:mmio_trace_reset
  - kernel/trace/trace_mmiotrace.c:mmio_trace_init
```
**Symbols:**

```
ffffffff811ac200-ffffffff811ac270: tracing_reset_online_cpus (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct trace_buffer *buf</code> ➡️ <code>struct array_buffer *buf</code>
</li>
</ul>
</details>
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
