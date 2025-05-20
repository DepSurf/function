# Function: <code>ns2usecs</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
long long unsigned int ns2usecs(cycle_t nsec);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8114bfb8)
Location: kernel/trace/trace.c:242
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_stats_read
  - kernel/trace/trace.c:tracing_stats_read
Direct callers:
  - kernel/trace/trace_output.c:trace_print_context
  - kernel/trace/trace_output.c:trace_print_lat_context
  - kernel/trace/trace_output.c:trace_print_lat_context
  - kernel/trace/trace_output.c:trace_print_lat_context
  - kernel/trace/trace_mmiotrace.c:mmio_print_line
  - kernel/trace/trace_mmiotrace.c:mmio_print_line
  - kernel/trace/trace_mmiotrace.c:mmio_print_line
```
**Symbols:**

```
ffffffff8114d570-ffffffff8114d598: ns2usecs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
long long unsigned int ns2usecs(cycle_t nsec);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811549d8)
Location: kernel/trace/trace.c:237
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_stats_read
  - kernel/trace/trace.c:tracing_stats_read
Direct callers:
  - kernel/trace/trace_output.c:trace_print_lat_context
  - kernel/trace/trace_output.c:trace_print_lat_context
  - kernel/trace/trace_output.c:trace_print_lat_context
  - kernel/trace/trace_output.c:trace_print_context
  - kernel/trace/trace_mmiotrace.c:mmio_print_line
  - kernel/trace/trace_mmiotrace.c:mmio_print_line
  - kernel/trace/trace_mmiotrace.c:mmio_print_line
```
**Symbols:**

```
ffffffff81155d80-ffffffff81155da8: ns2usecs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
long long unsigned int ns2usecs(u64 nsec);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8115ee68)
Location: kernel/trace/trace.c:239
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_stats_read
  - kernel/trace/trace.c:tracing_stats_read
Direct callers:
  - kernel/trace/trace_output.c:trace_print_lat_context
  - kernel/trace/trace_output.c:trace_print_lat_context
  - kernel/trace/trace_output.c:trace_print_lat_context
  - kernel/trace/trace_output.c:trace_print_context
  - kernel/trace/trace_mmiotrace.c:mmio_print_line
  - kernel/trace/trace_mmiotrace.c:mmio_print_line
  - kernel/trace/trace_mmiotrace.c:mmio_print_line
```
**Symbols:**

```
ffffffff811604b0-ffffffff811604d8: ns2usecs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
long long unsigned int ns2usecs(u64 nsec);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff81162088)
Location: kernel/trace/trace.c:239
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_stats_read
  - kernel/trace/trace.c:tracing_stats_read
Direct callers:
  - kernel/trace/trace_output.c:trace_print_lat_context
  - kernel/trace/trace_output.c:trace_print_lat_context
  - kernel/trace/trace_output.c:trace_print_lat_context
  - kernel/trace/trace_output.c:trace_print_context
  - kernel/trace/trace_mmiotrace.c:mmio_print_line
  - kernel/trace/trace_mmiotrace.c:mmio_print_line
  - kernel/trace/trace_mmiotrace.c:mmio_print_line
```
**Symbols:**

```
ffffffff811638b0-ffffffff811638d8: ns2usecs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
long long unsigned int ns2usecs(u64 nsec);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8116f0d8)
Location: kernel/trace/trace.c:239
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_stats_read
  - kernel/trace/trace.c:tracing_stats_read
Direct callers:
  - kernel/trace/trace_output.c:trace_print_lat_context
  - kernel/trace/trace_output.c:trace_print_lat_context
  - kernel/trace/trace_output.c:trace_print_lat_context
  - kernel/trace/trace_output.c:trace_print_context
  - kernel/trace/trace_mmiotrace.c:mmio_print_line
  - kernel/trace/trace_mmiotrace.c:mmio_print_line
  - kernel/trace/trace_mmiotrace.c:mmio_print_line
```
**Symbols:**

```
ffffffff81170830-ffffffff81170858: ns2usecs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
long long unsigned int ns2usecs(u64 nsec);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8117e145)
Location: kernel/trace/trace.c:240
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_stats_read
  - kernel/trace/trace.c:tracing_stats_read
Direct callers:
  - kernel/trace/trace_output.c:trace_print_lat_context
  - kernel/trace/trace_output.c:trace_print_lat_context
  - kernel/trace/trace_output.c:trace_print_lat_context
  - kernel/trace/trace_output.c:trace_print_context
  - kernel/trace/trace_mmiotrace.c:mmio_print_line
  - kernel/trace/trace_mmiotrace.c:mmio_print_line
  - kernel/trace/trace_mmiotrace.c:mmio_print_line
  - kernel/trace/trace_events_hist.c:hist_field_timestamp
```
**Symbols:**

```
ffffffff8117f950-ffffffff8117f973: ns2usecs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
long long unsigned int ns2usecs(u64 nsec);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8118ba35)
Location: kernel/trace/trace.c:241
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_stats_read
  - kernel/trace/trace.c:tracing_stats_read
Direct callers:
  - kernel/trace/trace_output.c:trace_print_lat_context
  - kernel/trace/trace_output.c:trace_print_lat_context
  - kernel/trace/trace_output.c:trace_print_lat_context
  - kernel/trace/trace_output.c:trace_print_context
  - kernel/trace/trace_mmiotrace.c:mmio_print_line
  - kernel/trace/trace_mmiotrace.c:mmio_print_line
  - kernel/trace/trace_mmiotrace.c:mmio_print_line
  - kernel/trace/trace_events_hist.c:hist_field_timestamp
```
**Symbols:**

```
ffffffff8118d2c0-ffffffff8118d2e3: ns2usecs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
long long unsigned int ns2usecs(u64 nsec);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff81198ce8)
Location: kernel/trace/trace.c:243
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_stats_read
  - kernel/trace/trace.c:tracing_stats_read
Direct callers:
  - kernel/trace/trace_output.c:trace_print_lat_context
  - kernel/trace/trace_output.c:trace_print_lat_context
  - kernel/trace/trace_output.c:trace_print_lat_context
  - kernel/trace/trace_output.c:trace_print_context
  - kernel/trace/trace_mmiotrace.c:mmio_print_line
  - kernel/trace/trace_mmiotrace.c:mmio_print_line
  - kernel/trace/trace_mmiotrace.c:mmio_print_line
  - kernel/trace/trace_events_hist.c:hist_field_timestamp
```
**Symbols:**

```
ffffffff8119abd0-ffffffff8119abf3: ns2usecs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
long long unsigned int ns2usecs(u64 nsec);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811a4668)
Location: kernel/trace/trace.c:244
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_stats_read
  - kernel/trace/trace.c:tracing_stats_read
Direct callers:
  - kernel/trace/trace_output.c:trace_print_lat_context
  - kernel/trace/trace_output.c:trace_print_lat_context
  - kernel/trace/trace_output.c:trace_print_lat_context
  - kernel/trace/trace_output.c:trace_print_context
  - kernel/trace/trace_mmiotrace.c:mmio_print_line
  - kernel/trace/trace_mmiotrace.c:mmio_print_line
  - kernel/trace/trace_mmiotrace.c:mmio_print_line
  - kernel/trace/trace_events_hist.c:hist_field_timestamp
```
**Symbols:**

```
ffffffff811a6480-ffffffff811a64a3: ns2usecs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
long long unsigned int ns2usecs(u64 nsec);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811bac08)
Location: kernel/trace/trace.c:247
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_stats_read
  - kernel/trace/trace.c:tracing_stats_read
Direct callers:
  - kernel/trace/trace_output.c:trace_print_context
  - kernel/trace/trace_mmiotrace.c:mmio_print_line
  - kernel/trace/trace_mmiotrace.c:mmio_print_map
  - kernel/trace/trace_mmiotrace.c:mmio_print_rw
  - kernel/trace/trace_events_hist.c:hist_field_timestamp
```
**Symbols:**

```
ffffffff811bf390-ffffffff811bf3b3: ns2usecs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
long long unsigned int ns2usecs(u64 nsec);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811b87a8)
Location: kernel/trace/trace.c:259
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_stats_read
  - kernel/trace/trace.c:tracing_stats_read
Direct callers:
  - kernel/trace/trace_output.c:trace_print_context
  - kernel/trace/trace_mmiotrace.c:mmio_print_line
  - kernel/trace/trace_mmiotrace.c:mmio_print_map
  - kernel/trace/trace_mmiotrace.c:mmio_print_rw
  - kernel/trace/trace_events_hist.c:hist_field_timestamp
```
**Symbols:**

```
ffffffff811bcfc0-ffffffff811bcfe3: ns2usecs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
long long unsigned int ns2usecs(u64 nsec);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811b9053)
Location: kernel/trace/trace.c:259
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_stats_read
  - kernel/trace/trace.c:tracing_stats_read
Direct callers:
  - kernel/trace/trace_output.c:trace_func_repeats_print
  - kernel/trace/trace_output.c:trace_print_lat_context
  - kernel/trace/trace_output.c:trace_print_lat_context
  - kernel/trace/trace_output.c:trace_print_lat_context
  - kernel/trace/trace_output.c:trace_print_context
  - kernel/trace/trace_mmiotrace.c:mmio_print_line
  - kernel/trace/trace_mmiotrace.c:mmio_print_line
  - kernel/trace/trace_mmiotrace.c:mmio_print_rw
  - kernel/trace/trace_events_hist.c:hist_field_timestamp
```
**Symbols:**

```
ffffffff811bcac0-ffffffff811bcae3: ns2usecs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
long long unsigned int ns2usecs(u64 nsec);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811e34cd)
Location: kernel/trace/trace.c:272
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_stats_read
  - kernel/trace/trace.c:tracing_stats_read
Direct callers:
  - kernel/trace/trace_output.c:trace_func_repeats_print
  - kernel/trace/trace_output.c:trace_print_lat_context
  - kernel/trace/trace_output.c:trace_print_lat_context
  - kernel/trace/trace_output.c:trace_print_lat_context
  - kernel/trace/trace_output.c:trace_print_context
  - kernel/trace/trace_mmiotrace.c:mmio_print_line
  - kernel/trace/trace_mmiotrace.c:mmio_print_line
  - kernel/trace/trace_mmiotrace.c:mmio_print_rw
  - kernel/trace/trace_events_hist.c:hist_field_timestamp
```
**Symbols:**

```
ffffffff811e7570-ffffffff811e7593: ns2usecs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
long long unsigned int ns2usecs(u64 nsec);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8121a820)
Location: kernel/trace/trace.c:282
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_stats_read
  - kernel/trace/trace.c:tracing_stats_read
Direct callers:
  - kernel/trace/trace_output.c:trace_func_repeats_print
  - kernel/trace/trace_output.c:trace_print_lat_context
  - kernel/trace/trace_output.c:trace_print_lat_context
  - kernel/trace/trace_output.c:trace_print_lat_context
  - kernel/trace/trace_output.c:trace_print_context
  - kernel/trace/trace_mmiotrace.c:mmio_print_line
  - kernel/trace/trace_mmiotrace.c:mmio_print_line
  - kernel/trace/trace_mmiotrace.c:mmio_print_rw
  - kernel/trace/trace_events_hist.c:hist_field_timestamp
```
**Symbols:**

```
ffffffff8121f520-ffffffff8121f54a: ns2usecs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
long long unsigned int ns2usecs(u64 nsec);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff81264560)
Location: kernel/trace/trace.c:281
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_stats_read
  - kernel/trace/trace.c:tracing_stats_read
Direct callers:
  - kernel/trace/trace_output.c:trace_func_repeats_print
  - kernel/trace/trace_output.c:trace_print_lat_context
  - kernel/trace/trace_output.c:trace_print_lat_context
  - kernel/trace/trace_output.c:trace_print_lat_context
  - kernel/trace/trace_output.c:trace_print_context
  - kernel/trace/trace_mmiotrace.c:mmio_print_line
  - kernel/trace/trace_mmiotrace.c:mmio_print_line
  - kernel/trace/trace_mmiotrace.c:mmio_print_rw
  - kernel/trace/trace_events_hist.c:hist_fn_call
```
**Symbols:**

```
ffffffff8126a0c0-ffffffff8126a0ea: ns2usecs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
long long unsigned int ns2usecs(u64 nsec);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8127b593)
Location: kernel/trace/trace.c:322
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_stats_read
  - kernel/trace/trace.c:tracing_stats_read
Direct callers:
  - kernel/trace/trace_output.c:trace_func_repeats_print
  - kernel/trace/trace_output.c:trace_print_lat_context
  - kernel/trace/trace_output.c:trace_print_lat_context
  - kernel/trace/trace_output.c:trace_print_lat_context
  - kernel/trace/trace_output.c:trace_print_context
  - kernel/trace/trace_mmiotrace.c:mmio_print_line
  - kernel/trace/trace_mmiotrace.c:mmio_print_line
  - kernel/trace/trace_mmiotrace.c:mmio_print_rw
  - kernel/trace/trace_events_hist.c:hist_fn_call
```
**Symbols:**

```
ffffffff81281240-ffffffff8128126a: ns2usecs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
long long unsigned int ns2usecs(u64 nsec);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8129615f)
Location: kernel/trace/trace.c:317
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_stats_read
  - kernel/trace/trace.c:tracing_stats_read
Direct callers:
  - kernel/trace/trace_output.c:trace_func_repeats_print
  - kernel/trace/trace_output.c:trace_print_lat_context
  - kernel/trace/trace_output.c:trace_print_lat_context
  - kernel/trace/trace_output.c:trace_print_lat_context
  - kernel/trace/trace_output.c:trace_print_context
  - kernel/trace/trace_mmiotrace.c:mmio_print_line
  - kernel/trace/trace_mmiotrace.c:mmio_print_line
  - kernel/trace/trace_mmiotrace.c:mmio_print_rw
  - kernel/trace/trace_events_hist.c:hist_fn_call
```
**Symbols:**

```
ffffffff8129c0c0-ffffffff8129c0ea: ns2usecs (STB_GLOBAL)
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
long long unsigned int ns2usecs(u64 nsec);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffff80001021f650)
Location: kernel/trace/trace.c:244
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_stats_read
  - kernel/trace/trace.c:tracing_stats_read
Direct callers:
  - kernel/trace/trace_output.c:trace_print_lat_context
  - kernel/trace/trace_output.c:trace_print_lat_context
  - kernel/trace/trace_output.c:trace_print_lat_context
  - kernel/trace/trace_output.c:trace_print_context
  - kernel/trace/trace_events_hist.c:hist_field_timestamp
```
**Symbols:**

```
ffff800010223238-ffff80001022325c: ns2usecs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
long long unsigned int ns2usecs(u64 nsec);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (c045fe74)
Location: kernel/trace/trace.c:244
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_stats_read
  - kernel/trace/trace.c:tracing_stats_read
Direct callers:
  - kernel/trace/trace_output.c:trace_print_lat_context
  - kernel/trace/trace_output.c:trace_print_lat_context
  - kernel/trace/trace_output.c:trace_print_lat_context
  - kernel/trace/trace_output.c:trace_print_context
```
**Symbols:**

```
c0460b74-c0460bd8: ns2usecs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
long long unsigned int ns2usecs(u64 nsec);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (c0000000002a309c)
Location: kernel/trace/trace.c:244
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_stats_read
  - kernel/trace/trace.c:tracing_stats_read
Direct callers:
  - kernel/trace/trace_output.c:trace_print_lat_context
  - kernel/trace/trace_output.c:trace_print_lat_context
  - kernel/trace/trace_output.c:trace_print_lat_context
  - kernel/trace/trace_output.c:trace_print_context
  - kernel/trace/trace_events_hist.c:hist_field_timestamp
```
**Symbols:**

```
c0000000002a7ae0-c0000000002a7b08: ns2usecs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
long long unsigned int ns2usecs(u64 nsec);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffe00017c21e)
Location: kernel/trace/trace.c:244
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_stats_read
  - kernel/trace/trace.c:tracing_stats_read
Direct callers:
  - kernel/trace/trace_output.c:trace_print_lat_context
  - kernel/trace/trace_output.c:trace_print_lat_context
  - kernel/trace/trace_output.c:trace_print_lat_context
  - kernel/trace/trace_output.c:trace_print_context
```
**Symbols:**

```
ffffffe00017e9f0-ffffffe00017ea08: ns2usecs (STB_GLOBAL)
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
long long unsigned int ns2usecs(u64 nsec);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8119cc88)
Location: kernel/trace/trace.c:244
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_stats_read
  - kernel/trace/trace.c:tracing_stats_read
Direct callers:
  - kernel/trace/trace_output.c:trace_print_lat_context
  - kernel/trace/trace_output.c:trace_print_lat_context
  - kernel/trace/trace_output.c:trace_print_lat_context
  - kernel/trace/trace_output.c:trace_print_context
  - kernel/trace/trace_mmiotrace.c:mmio_print_line
  - kernel/trace/trace_mmiotrace.c:mmio_print_line
  - kernel/trace/trace_mmiotrace.c:mmio_print_line
  - kernel/trace/trace_events_hist.c:hist_field_timestamp
```
**Symbols:**

```
ffffffff8119eaa0-ffffffff8119eac3: ns2usecs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
long long unsigned int ns2usecs(u64 nsec);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8118fce8)
Location: kernel/trace/trace.c:244
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_stats_read
  - kernel/trace/trace.c:tracing_stats_read
Direct callers:
  - kernel/trace/trace_output.c:trace_print_lat_context
  - kernel/trace/trace_output.c:trace_print_lat_context
  - kernel/trace/trace_output.c:trace_print_lat_context
  - kernel/trace/trace_output.c:trace_print_context
  - kernel/trace/trace_mmiotrace.c:mmio_print_line
  - kernel/trace/trace_mmiotrace.c:mmio_print_line
  - kernel/trace/trace_mmiotrace.c:mmio_print_line
  - kernel/trace/trace_events_hist.c:hist_field_timestamp
```
**Symbols:**

```
ffffffff81191af0-ffffffff81191b13: ns2usecs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
long long unsigned int ns2usecs(u64 nsec);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8119aa58)
Location: kernel/trace/trace.c:244
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_stats_read
  - kernel/trace/trace.c:tracing_stats_read
Direct callers:
  - kernel/trace/trace_output.c:trace_print_lat_context
  - kernel/trace/trace_output.c:trace_print_lat_context
  - kernel/trace/trace_output.c:trace_print_lat_context
  - kernel/trace/trace_output.c:trace_print_context
  - kernel/trace/trace_mmiotrace.c:mmio_print_line
  - kernel/trace/trace_mmiotrace.c:mmio_print_line
  - kernel/trace/trace_mmiotrace.c:mmio_print_line
  - kernel/trace/trace_events_hist.c:hist_field_timestamp
```
**Symbols:**

```
ffffffff8119c870-ffffffff8119c893: ns2usecs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
long long unsigned int ns2usecs(u64 nsec);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811a86f8)
Location: kernel/trace/trace.c:244
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_stats_read
  - kernel/trace/trace.c:tracing_stats_read
Direct callers:
  - kernel/trace/trace_output.c:trace_print_lat_context
  - kernel/trace/trace_output.c:trace_print_lat_context
  - kernel/trace/trace_output.c:trace_print_lat_context
  - kernel/trace/trace_output.c:trace_print_context
  - kernel/trace/trace_mmiotrace.c:mmio_print_line
  - kernel/trace/trace_mmiotrace.c:mmio_print_line
  - kernel/trace/trace_mmiotrace.c:mmio_print_line
  - kernel/trace/trace_events_hist.c:hist_field_timestamp
```
**Symbols:**

```
ffffffff811aa510-ffffffff811aa533: ns2usecs (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.8</code> and <code>4.10</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>cycle_t nsec</code> ➡️ <code>u64 nsec</code>
</li>
</ul>
</details>
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
