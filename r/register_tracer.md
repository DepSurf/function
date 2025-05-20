# Function: <code>register_tracer</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int register_tracer(struct tracer *type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff81f83ad3)
Location: kernel/trace/trace.c:1230
Inline: False
Direct callers:
  - kernel/trace/trace.c:trace_init
  - kernel/trace/trace_functions.c:init_function_trace
  - kernel/trace/trace_mmiotrace.c:init_mmio_trace
  - kernel/trace/trace_functions_graph.c:init_graph_trace
```
**Symbols:**

```
ffffffff81f83ad3-ffffffff81f83c6b: register_tracer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int register_tracer(struct tracer *type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff81fad02a)
Location: kernel/trace/trace.c:1465
Inline: False
Direct callers:
  - kernel/trace/trace.c:trace_init
  - kernel/trace/trace_functions.c:init_function_trace
  - kernel/trace/trace_mmiotrace.c:init_mmio_trace
  - kernel/trace/trace_functions_graph.c:init_graph_trace
```
**Symbols:**

```
ffffffff81fad02a-ffffffff81fad1ec: register_tracer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int register_tracer(struct tracer *type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff81fe934a)
Location: kernel/trace/trace.c:1509
Inline: False
Direct callers:
  - kernel/trace/trace.c:trace_init
  - kernel/trace/trace_functions.c:init_function_trace
  - kernel/trace/trace_hwlat.c:init_hwlat_tracer
  - kernel/trace/trace_mmiotrace.c:init_mmio_trace
  - kernel/trace/trace_functions_graph.c:init_graph_trace
```
**Symbols:**

```
ffffffff81fe934a-ffffffff81fe950c: register_tracer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int register_tracer(struct tracer *type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff820c9d22)
Location: kernel/trace/trace.c:1579
Inline: False
Direct callers:
  - kernel/trace/trace.c:early_trace_init
  - kernel/trace/trace_functions.c:init_function_trace
  - kernel/trace/trace_hwlat.c:init_hwlat_tracer
  - kernel/trace/trace_mmiotrace.c:init_mmio_trace
  - kernel/trace/trace_functions_graph.c:init_graph_trace
```
**Symbols:**

```
ffffffff820c9d22-ffffffff820c9ee4: register_tracer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int register_tracer(struct tracer *type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff826d23fa)
Location: kernel/trace/trace.c:1579
Inline: False
Direct callers:
  - kernel/trace/trace.c:early_trace_init
  - kernel/trace/trace_functions.c:init_function_trace
  - kernel/trace/trace_hwlat.c:init_hwlat_tracer
  - kernel/trace/trace_mmiotrace.c:init_mmio_trace
  - kernel/trace/trace_functions_graph.c:init_graph_trace
```
**Symbols:**

```
ffffffff826d23fa-ffffffff826d25bc: register_tracer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int register_tracer(struct tracer *type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff826fcbd0)
Location: kernel/trace/trace.c:1590
Inline: False
Direct callers:
  - kernel/trace/trace.c:early_trace_init
  - kernel/trace/trace_functions.c:init_function_trace
  - kernel/trace/trace_sched_wakeup.c:init_wakeup_tracer
  - kernel/trace/trace_sched_wakeup.c:init_wakeup_tracer
  - kernel/trace/trace_sched_wakeup.c:init_wakeup_tracer
  - kernel/trace/trace_hwlat.c:init_hwlat_tracer
  - kernel/trace/trace_mmiotrace.c:init_mmio_trace
  - kernel/trace/trace_functions_graph.c:init_graph_trace
  - kernel/trace/blktrace.c:init_blk_tracer
```
**Symbols:**

```
ffffffff826fcbd0-ffffffff826fcd92: register_tracer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int register_tracer(struct tracer *type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff828b3aea)
Location: kernel/trace/trace.c:1591
Inline: False
Direct callers:
  - kernel/trace/trace.c:early_trace_init
  - kernel/trace/trace_functions.c:init_function_trace
  - kernel/trace/trace_sched_wakeup.c:init_wakeup_tracer
  - kernel/trace/trace_sched_wakeup.c:init_wakeup_tracer
  - kernel/trace/trace_sched_wakeup.c:init_wakeup_tracer
  - kernel/trace/trace_hwlat.c:init_hwlat_tracer
  - kernel/trace/trace_mmiotrace.c:init_mmio_trace
  - kernel/trace/trace_functions_graph.c:init_graph_trace
  - kernel/trace/blktrace.c:init_blk_tracer
```
**Symbols:**

```
ffffffff828b3aea-ffffffff828b3cac: register_tracer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int register_tracer(struct tracer *type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff828cc866)
Location: kernel/trace/trace.c:1774
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracer_alloc_buffers
  - kernel/trace/trace_functions.c:init_function_trace
  - kernel/trace/trace_sched_wakeup.c:init_wakeup_tracer
  - kernel/trace/trace_sched_wakeup.c:init_wakeup_tracer
  - kernel/trace/trace_sched_wakeup.c:init_wakeup_tracer
  - kernel/trace/trace_hwlat.c:init_hwlat_tracer
  - kernel/trace/trace_mmiotrace.c:init_mmio_trace
  - kernel/trace/trace_functions_graph.c:init_graph_trace
  - kernel/trace/blktrace.c:init_blk_tracer
```
**Symbols:**

```
ffffffff828cc866-ffffffff828cca29: register_tracer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int register_tracer(struct tracer *type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff828d4d59)
Location: kernel/trace/trace.c:1794
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracer_alloc_buffers
  - kernel/trace/trace_functions.c:init_function_trace
  - kernel/trace/trace_sched_wakeup.c:init_wakeup_tracer
  - kernel/trace/trace_sched_wakeup.c:init_wakeup_tracer
  - kernel/trace/trace_sched_wakeup.c:init_wakeup_tracer
  - kernel/trace/trace_hwlat.c:init_hwlat_tracer
  - kernel/trace/trace_mmiotrace.c:init_mmio_trace
  - kernel/trace/trace_functions_graph.c:init_graph_trace
  - kernel/trace/blktrace.c:init_blk_tracer
```
**Symbols:**

```
ffffffff828d4d59-ffffffff828d4f47: register_tracer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int register_tracer(struct tracer *type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff82cf5677)
Location: kernel/trace/trace.c:1898
Inline: False
Direct callers:
  - kernel/trace/trace_functions.c:init_function_trace
  - kernel/trace/trace_sched_wakeup.c:init_wakeup_tracer
  - kernel/trace/trace_sched_wakeup.c:init_wakeup_tracer
  - kernel/trace/trace_sched_wakeup.c:init_wakeup_tracer
  - kernel/trace/trace_hwlat.c:init_hwlat_tracer
  - kernel/trace/trace_mmiotrace.c:init_mmio_trace
  - kernel/trace/trace_functions_graph.c:init_graph_trace
  - kernel/trace/blktrace.c:init_blk_tracer
```
**Symbols:**

```
ffffffff82cf5677-ffffffff82cf5859: register_tracer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int register_tracer(struct tracer *type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff82fe2263)
Location: kernel/trace/trace.c:2048
Inline: False
Direct callers:
  - kernel/trace/trace_functions.c:init_function_trace
  - kernel/trace/trace_sched_wakeup.c:init_wakeup_tracer
  - kernel/trace/trace_sched_wakeup.c:init_wakeup_tracer
  - kernel/trace/trace_sched_wakeup.c:init_wakeup_tracer
  - kernel/trace/trace_hwlat.c:init_hwlat_tracer
  - kernel/trace/trace_mmiotrace.c:init_mmio_trace
  - kernel/trace/trace_functions_graph.c:init_graph_trace
  - kernel/trace/blktrace.c:init_blk_tracer
```
**Symbols:**

```
ffffffff82fe2263-ffffffff82fe243e: register_tracer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int register_tracer(struct tracer *type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff831ec734)
Location: kernel/trace/trace.c:2051
Inline: False
Direct callers:
  - kernel/trace/trace_functions.c:init_function_trace
  - kernel/trace/trace_sched_wakeup.c:init_wakeup_tracer
  - kernel/trace/trace_sched_wakeup.c:init_wakeup_tracer
  - kernel/trace/trace_sched_wakeup.c:init_wakeup_tracer
  - kernel/trace/trace_hwlat.c:init_hwlat_tracer
  - kernel/trace/trace_mmiotrace.c:init_mmio_trace
  - kernel/trace/trace_functions_graph.c:init_graph_trace
  - kernel/trace/blktrace.c:init_blk_tracer
```
**Symbols:**

```
ffffffff831ec734-ffffffff831ec90f: register_tracer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int register_tracer(struct tracer *type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff832d1204)
Location: kernel/trace/trace.c:2065
Inline: False
Direct callers:
  - kernel/trace/trace_functions.c:init_function_trace
  - kernel/trace/trace_sched_wakeup.c:init_wakeup_tracer
  - kernel/trace/trace_sched_wakeup.c:init_wakeup_tracer
  - kernel/trace/trace_sched_wakeup.c:init_wakeup_tracer
  - kernel/trace/trace_hwlat.c:init_hwlat_tracer
  - kernel/trace/trace_mmiotrace.c:init_mmio_trace
  - kernel/trace/trace_functions_graph.c:init_graph_trace
  - kernel/trace/blktrace.c:init_blk_tracer
```
**Symbols:**

```
ffffffff832d1204-ffffffff832d13df: register_tracer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int register_tracer(struct tracer *type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff83485426)
Location: kernel/trace/trace.c:2056
Inline: False
Direct callers:
  - kernel/trace/trace_functions.c:init_function_trace
  - kernel/trace/trace_sched_wakeup.c:init_wakeup_tracer
  - kernel/trace/trace_sched_wakeup.c:init_wakeup_tracer
  - kernel/trace/trace_sched_wakeup.c:init_wakeup_tracer
  - kernel/trace/trace_hwlat.c:init_hwlat_tracer
  - kernel/trace/trace_mmiotrace.c:init_mmio_trace
  - kernel/trace/trace_functions_graph.c:init_graph_trace
  - kernel/trace/blktrace.c:init_blk_tracer
```
**Symbols:**

```
ffffffff83485426-ffffffff83485616: register_tracer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int register_tracer(struct tracer *type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff83eb42f0)
Location: kernel/trace/trace.c:2062
Inline: False
Direct callers:
  - kernel/trace/trace_functions.c:init_function_trace
  - kernel/trace/trace_functions.c:init_function_trace
  - kernel/trace/trace_sched_wakeup.c:init_wakeup_tracer
  - kernel/trace/trace_sched_wakeup.c:init_wakeup_tracer
  - kernel/trace/trace_sched_wakeup.c:init_wakeup_tracer
  - kernel/trace/trace_hwlat.c:init_hwlat_tracer
  - kernel/trace/trace_mmiotrace.c:init_mmio_trace
  - kernel/trace/trace_functions_graph.c:init_graph_trace
  - kernel/trace/blktrace.c:init_blk_tracer
```
**Symbols:**

```
ffffffff83eb42f0-ffffffff83eb4574: register_tracer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int register_tracer(struct tracer *type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff836d9620)
Location: kernel/trace/trace.c:2136
Inline: False
Direct callers:
  - kernel/trace/trace_functions.c:init_function_trace
  - kernel/trace/trace_functions.c:init_function_trace
  - kernel/trace/trace_sched_wakeup.c:init_wakeup_tracer
  - kernel/trace/trace_sched_wakeup.c:init_wakeup_tracer
  - kernel/trace/trace_sched_wakeup.c:init_wakeup_tracer
  - kernel/trace/trace_hwlat.c:init_hwlat_tracer
  - kernel/trace/trace_osnoise.c:init_osnoise_tracer
  - kernel/trace/trace_osnoise.c:init_osnoise_tracer
  - kernel/trace/trace_mmiotrace.c:init_mmio_trace
  - kernel/trace/trace_functions_graph.c:init_graph_trace
  - kernel/trace/blktrace.c:init_blk_tracer
```
**Symbols:**

```
ffffffff836d9620-ffffffff836d9881: register_tracer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int register_tracer(struct tracer *type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8390bbb0)
Location: kernel/trace/trace.c:2160
Inline: False
Direct callers:
  - kernel/trace/trace_functions.c:init_function_trace
  - kernel/trace/trace_functions.c:init_function_trace
  - kernel/trace/trace_sched_wakeup.c:init_wakeup_tracer
  - kernel/trace/trace_sched_wakeup.c:init_wakeup_tracer
  - kernel/trace/trace_sched_wakeup.c:init_wakeup_tracer
  - kernel/trace/trace_hwlat.c:init_hwlat_tracer
  - kernel/trace/trace_osnoise.c:init_osnoise_tracer
  - kernel/trace/trace_osnoise.c:init_osnoise_tracer
  - kernel/trace/trace_mmiotrace.c:init_mmio_trace
  - kernel/trace/trace_functions_graph.c:init_graph_trace
  - kernel/trace/blktrace.c:init_blk_tracer
```
**Symbols:**

```
ffffffff8390bbb0-ffffffff8390be40: register_tracer (STB_GLOBAL)
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
int register_tracer(struct tracer *type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffff80001144d608)
Location: kernel/trace/trace.c:1794
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracer_alloc_buffers
  - kernel/trace/trace_functions.c:init_function_trace
  - kernel/trace/trace_sched_wakeup.c:init_wakeup_tracer
  - kernel/trace/trace_sched_wakeup.c:init_wakeup_tracer
  - kernel/trace/trace_sched_wakeup.c:init_wakeup_tracer
  - kernel/trace/trace_hwlat.c:init_hwlat_tracer
  - kernel/trace/trace_functions_graph.c:init_graph_trace
  - kernel/trace/blktrace.c:init_blk_tracer
```
**Symbols:**

```
ffff80001144d608-ffff80001144d808: register_tracer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int register_tracer(struct tracer *type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (c1527ba0)
Location: kernel/trace/trace.c:1794
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracer_alloc_buffers
  - kernel/trace/trace_functions.c:init_function_trace
  - kernel/trace/trace_sched_wakeup.c:init_wakeup_tracer
  - kernel/trace/trace_sched_wakeup.c:init_wakeup_tracer
  - kernel/trace/trace_sched_wakeup.c:init_wakeup_tracer
  - kernel/trace/trace_hwlat.c:init_hwlat_tracer
  - kernel/trace/trace_functions_graph.c:init_graph_trace
  - kernel/trace/blktrace.c:init_blk_tracer
```
**Symbols:**

```
c1527ba0-c1527da0: register_tracer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int register_tracer(struct tracer *type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (c000000001373b24)
Location: kernel/trace/trace.c:1794
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracer_alloc_buffers
  - kernel/trace/trace_functions.c:init_function_trace
  - kernel/trace/trace_sched_wakeup.c:init_wakeup_tracer
  - kernel/trace/trace_sched_wakeup.c:init_wakeup_tracer
  - kernel/trace/trace_sched_wakeup.c:init_wakeup_tracer
  - kernel/trace/trace_hwlat.c:init_hwlat_tracer
  - kernel/trace/trace_functions_graph.c:init_graph_trace
  - kernel/trace/blktrace.c:init_blk_tracer
```
**Symbols:**

```
c000000001373b24-c000000001373da8: register_tracer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int register_tracer(struct tracer *type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffe00000dc48)
Location: kernel/trace/trace.c:1794
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracer_alloc_buffers
  - kernel/trace/trace_functions.c:init_function_trace
  - kernel/trace/trace_sched_wakeup.c:init_wakeup_tracer
  - kernel/trace/trace_sched_wakeup.c:init_wakeup_tracer
  - kernel/trace/trace_sched_wakeup.c:init_wakeup_tracer
  - kernel/trace/trace_hwlat.c:init_hwlat_tracer
  - kernel/trace/trace_functions_graph.c:init_graph_trace
  - kernel/trace/blktrace.c:init_blk_tracer
```
**Symbols:**

```
ffffffe00000dc48-ffffffe00000de20: register_tracer (STB_GLOBAL)
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
int register_tracer(struct tracer *type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff828bdc0a)
Location: kernel/trace/trace.c:1794
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracer_alloc_buffers
  - kernel/trace/trace_functions.c:init_function_trace
  - kernel/trace/trace_sched_wakeup.c:init_wakeup_tracer
  - kernel/trace/trace_sched_wakeup.c:init_wakeup_tracer
  - kernel/trace/trace_sched_wakeup.c:init_wakeup_tracer
  - kernel/trace/trace_hwlat.c:init_hwlat_tracer
  - kernel/trace/trace_mmiotrace.c:init_mmio_trace
  - kernel/trace/trace_functions_graph.c:init_graph_trace
  - kernel/trace/blktrace.c:init_blk_tracer
```
**Symbols:**

```
ffffffff828bdc0a-ffffffff828bddf8: register_tracer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int register_tracer(struct tracer *type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff828b62aa)
Location: kernel/trace/trace.c:1794
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracer_alloc_buffers
  - kernel/trace/trace_functions.c:init_function_trace
  - kernel/trace/trace_sched_wakeup.c:init_wakeup_tracer
  - kernel/trace/trace_sched_wakeup.c:init_wakeup_tracer
  - kernel/trace/trace_sched_wakeup.c:init_wakeup_tracer
  - kernel/trace/trace_hwlat.c:init_hwlat_tracer
  - kernel/trace/trace_mmiotrace.c:init_mmio_trace
  - kernel/trace/trace_functions_graph.c:init_graph_trace
  - kernel/trace/blktrace.c:init_blk_tracer
```
**Symbols:**

```
ffffffff828b62aa-ffffffff828b6498: register_tracer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int register_tracer(struct tracer *type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff828d098d)
Location: kernel/trace/trace.c:1794
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracer_alloc_buffers
  - kernel/trace/trace_functions.c:init_function_trace
  - kernel/trace/trace_sched_wakeup.c:init_wakeup_tracer
  - kernel/trace/trace_sched_wakeup.c:init_wakeup_tracer
  - kernel/trace/trace_sched_wakeup.c:init_wakeup_tracer
  - kernel/trace/trace_hwlat.c:init_hwlat_tracer
  - kernel/trace/trace_mmiotrace.c:init_mmio_trace
  - kernel/trace/trace_functions_graph.c:init_graph_trace
  - kernel/trace/blktrace.c:init_blk_tracer
```
**Symbols:**

```
ffffffff828d098d-ffffffff828d0b7b: register_tracer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int register_tracer(struct tracer *type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff828d5dae)
Location: kernel/trace/trace.c:1794
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracer_alloc_buffers
  - kernel/trace/trace_functions.c:init_function_trace
  - kernel/trace/trace_sched_wakeup.c:init_wakeup_tracer
  - kernel/trace/trace_sched_wakeup.c:init_wakeup_tracer
  - kernel/trace/trace_sched_wakeup.c:init_wakeup_tracer
  - kernel/trace/trace_hwlat.c:init_hwlat_tracer
  - kernel/trace/trace_mmiotrace.c:init_mmio_trace
  - kernel/trace/trace_functions_graph.c:init_graph_trace
  - kernel/trace/blktrace.c:init_blk_tracer
```
**Symbols:**

```
ffffffff828d5dae-ffffffff828d5f9c: register_tracer (STB_GLOBAL)
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
