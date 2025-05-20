# Function: <code>ftrace_push_return_trace</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int ftrace_push_return_trace(long unsigned int ret, long unsigned int func, int *depth, long unsigned int frame_pointer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_functions_graph.c (ffffffff811592b0)
Location: kernel/trace/trace_functions_graph.c:120
Inline: False
Direct callers:
  - arch/x86/kernel/ftrace.c:prepare_ftrace_return
```
**Symbols:**

```
ffffffff811592b0-ffffffff811593ed: ftrace_push_return_trace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int ftrace_push_return_trace(long unsigned int ret, long unsigned int func, int *depth, long unsigned int frame_pointer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_functions_graph.c (ffffffff81163b70)
Location: kernel/trace/trace_functions_graph.c:121
Inline: False
Direct callers:
  - arch/x86/kernel/ftrace.c:prepare_ftrace_return
```
**Symbols:**

```
ffffffff81163b70-ffffffff81163cb6: ftrace_push_return_trace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int ftrace_push_return_trace(long unsigned int ret, long unsigned int func, int *depth, long unsigned int frame_pointer, long unsigned int *retp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_functions_graph.c (ffffffff8116eea0)
Location: kernel/trace/trace_functions_graph.c:121
Inline: False
Direct callers:
  - arch/x86/kernel/ftrace.c:prepare_ftrace_return
```
**Symbols:**

```
ffffffff8116eea0-ffffffff8116efd2: ftrace_push_return_trace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int ftrace_push_return_trace(long unsigned int ret, long unsigned int func, int *depth, long unsigned int frame_pointer, long unsigned int *retp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_functions_graph.c (ffffffff811720c0)
Location: kernel/trace/trace_functions_graph.c:121
Inline: False
Direct callers:
  - arch/x86/kernel/ftrace.c:prepare_ftrace_return
```
**Symbols:**

```
ffffffff811720c0-ffffffff811721e7: ftrace_push_return_trace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int ftrace_push_return_trace(long unsigned int ret, long unsigned int func, int *depth, long unsigned int frame_pointer, long unsigned int *retp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_functions_graph.c (ffffffff8117f250)
Location: kernel/trace/trace_functions_graph.c:122
Inline: False
Direct callers:
  - arch/x86/kernel/ftrace.c:prepare_ftrace_return
```
**Symbols:**

```
ffffffff8117f250-ffffffff8117f377: ftrace_push_return_trace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int ftrace_push_return_trace(long unsigned int ret, long unsigned int func, int *depth, long unsigned int frame_pointer, long unsigned int *retp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_functions_graph.c (ffffffff8118e350)
Location: kernel/trace/trace_functions_graph.c:122
Inline: False
Direct callers:
  - arch/x86/kernel/ftrace.c:prepare_ftrace_return
```
**Symbols:**

```
ffffffff8118e350-ffffffff8118e477: ftrace_push_return_trace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/fgraph.c (ffffffff811a0484)
Location: kernel/trace/fgraph.c:59
Inline: True
Inline callers:
  - kernel/trace/fgraph.c:function_graph_enter
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/fgraph.c (ffffffff811ae304)
Location: kernel/trace/fgraph.c:59
Inline: True
Inline callers:
  - kernel/trace/fgraph.c:function_graph_enter
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/fgraph.c (ffffffff811b9a74)
Location: kernel/trace/fgraph.c:59
Inline: True
Inline callers:
  - kernel/trace/fgraph.c:function_graph_enter
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/fgraph.c (ffffffff811d27e0)
Location: kernel/trace/fgraph.c:59
Inline: True
Direct callers:
  - kernel/trace/fgraph.c:function_graph_enter
```
**Symbols:**

```
ffffffff811d27e0-ffffffff811d2897: ftrace_push_return_trace.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/fgraph.c (ffffffff811cf930)
Location: kernel/trace/fgraph.c:59
Inline: True
Direct callers:
  - kernel/trace/fgraph.c:function_graph_enter
```
**Symbols:**

```
ffffffff811cf930-ffffffff811cf9e7: ftrace_push_return_trace.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/fgraph.c (ffffffff811d0d09)
Location: kernel/trace/fgraph.c:59
Inline: True
Inline callers:
  - kernel/trace/fgraph.c:function_graph_enter
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/fgraph.c (ffffffff811fd969)
Location: kernel/trace/fgraph.c:59
Inline: True
Inline callers:
  - kernel/trace/fgraph.c:function_graph_enter
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/fgraph.c (ffffffff8123827d)
Location: kernel/trace/fgraph.c:68
Inline: True
Inline callers:
  - kernel/trace/fgraph.c:function_graph_enter
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/fgraph.c (ffffffff8128509d)
Location: kernel/trace/fgraph.c:68
Inline: True
Inline callers:
  - kernel/trace/fgraph.c:function_graph_enter
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/fgraph.c (ffffffff812a1d3d)
Location: kernel/trace/fgraph.c:69
Inline: True
Inline callers:
  - kernel/trace/fgraph.c:function_graph_enter
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/fgraph.c (ffffffff812bd46d)
Location: kernel/trace/fgraph.c:69
Inline: True
Inline callers:
  - kernel/trace/fgraph.c:function_graph_enter
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/fgraph.c (ffff800010238148)
Location: kernel/trace/fgraph.c:59
Inline: True
Inline callers:
  - kernel/trace/fgraph.c:function_graph_enter
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/fgraph.c (c0473d00)
Location: kernel/trace/fgraph.c:59
Inline: True
Inline callers:
  - kernel/trace/fgraph.c:function_graph_enter
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/fgraph.c (c0000000002c43d4)
Location: kernel/trace/fgraph.c:59
Inline: True
Inline callers:
  - kernel/trace/fgraph.c:function_graph_enter
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/fgraph.c (ffffffe00018f10a)
Location: kernel/trace/fgraph.c:59
Inline: True
Inline callers:
  - kernel/trace/fgraph.c:function_graph_enter
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/fgraph.c (ffffffff811b2094)
Location: kernel/trace/fgraph.c:59
Inline: True
Inline callers:
  - kernel/trace/fgraph.c:function_graph_enter
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/fgraph.c (ffffffff811a4ea4)
Location: kernel/trace/fgraph.c:59
Inline: True
Inline callers:
  - kernel/trace/fgraph.c:function_graph_enter
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/fgraph.c (ffffffff811afe64)
Location: kernel/trace/fgraph.c:59
Inline: True
Inline callers:
  - kernel/trace/fgraph.c:function_graph_enter
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/fgraph.c (ffffffff811bded4)
Location: kernel/trace/fgraph.c:59
Inline: True
Inline callers:
  - kernel/trace/fgraph.c:function_graph_enter
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
<b>Param added. </b>
<code>long unsigned int *retp</code>
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
</ul>
