# Function: <code>register_ftrace_graph</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int register_ftrace_graph(trace_func_graph_ret_t retfunc, trace_func_graph_ent_t entryfunc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81145c90)
Location: kernel/trace/ftrace.c:5841
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_profile_write
  - kernel/trace/trace_functions_graph.c:graph_trace_init
  - kernel/trace/trace_functions_graph.c:graph_trace_init
```
**Symbols:**

```
ffffffff81145c90-ffffffff81145f32: register_ftrace_graph (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int register_ftrace_graph(trace_func_graph_ret_t retfunc, trace_func_graph_ent_t entryfunc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff8114e4d0)
Location: kernel/trace/ftrace.c:5874
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_profile_write
  - kernel/trace/trace_functions_graph.c:graph_trace_init
  - kernel/trace/trace_functions_graph.c:graph_trace_init
```
**Symbols:**

```
ffffffff8114e4d0-ffffffff8114e789: register_ftrace_graph (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int register_ftrace_graph(trace_func_graph_ret_t retfunc, trace_func_graph_ent_t entryfunc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81158410)
Location: kernel/trace/ftrace.c:5923
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_profile_write
  - kernel/trace/trace_functions_graph.c:graph_trace_init
  - kernel/trace/trace_functions_graph.c:graph_trace_init
```
**Symbols:**

```
ffffffff81158410-ffffffff811586cb: register_ftrace_graph (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int register_ftrace_graph(trace_func_graph_ret_t retfunc, trace_func_graph_ent_t entryfunc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff8115b760)
Location: kernel/trace/ftrace.c:6704
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_profile_write
  - kernel/trace/trace_functions_graph.c:graph_trace_init
  - kernel/trace/trace_functions_graph.c:graph_trace_init
```
**Symbols:**

```
ffffffff8115b760-ffffffff8115b9fe: register_ftrace_graph (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int register_ftrace_graph(trace_func_graph_ret_t retfunc, trace_func_graph_ent_t entryfunc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81168840)
Location: kernel/trace/ftrace.c:7003
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_profile_write
  - kernel/trace/trace_functions_graph.c:graph_trace_init
  - kernel/trace/trace_functions_graph.c:graph_trace_init
```
**Symbols:**

```
ffffffff81168840-ffffffff81168ace: register_ftrace_graph (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int register_ftrace_graph(trace_func_graph_ret_t retfunc, trace_func_graph_ent_t entryfunc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/ftrace.c (0)
Location: kernel/trace/ftrace.c:6990
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_profile_write
  - kernel/trace/trace_functions_graph.c:graph_trace_init
  - kernel/trace/trace_functions_graph.c:graph_trace_init
```
**Symbols:**

```
ffffffff81177bdf-ffffffff81177bf0: register_ftrace_graph.cold.72 (STB_LOCAL)
ffffffff81177510-ffffffff81177798: register_ftrace_graph (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int register_ftrace_graph(struct fgraph_ops *gops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/fgraph.c (0)
Location: kernel/trace/fgraph.c:570
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_profile_write
  - kernel/trace/trace_functions_graph.c:graph_trace_init
  - kernel/trace/trace_functions_graph.c:graph_trace_init
```
**Symbols:**

```
ffffffff811a0ba3-ffffffff811a0bb4: register_ftrace_graph.cold.9 (STB_LOCAL)
ffffffff811a0880-ffffffff811a0b12: register_ftrace_graph (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int register_ftrace_graph(struct fgraph_ops *gops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/fgraph.c (ffffffff811ae8e0)
Location: kernel/trace/fgraph.c:570
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_profile_write
  - kernel/trace/trace_functions_graph.c:graph_trace_init
  - kernel/trace/trace_functions_graph.c:graph_trace_init
```
**Symbols:**

```
ffffffff811ae8e0-ffffffff811ae9bf: register_ftrace_graph (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int register_ftrace_graph(struct fgraph_ops *gops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/fgraph.c (ffffffff811ba060)
Location: kernel/trace/fgraph.c:570
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_profile_write
  - kernel/trace/trace_functions_graph.c:graph_trace_init
  - kernel/trace/trace_functions_graph.c:graph_trace_init
```
**Symbols:**

```
ffffffff811ba060-ffffffff811ba13f: register_ftrace_graph (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int register_ftrace_graph(struct fgraph_ops *gops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/fgraph.c (ffffffff811d2ed0)
Location: kernel/trace/fgraph.c:598
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_profile_write
  - kernel/trace/trace_sched_wakeup.c:start_func_tracer
  - kernel/trace/trace_sched_wakeup.c:wakeup_flag_changed
  - kernel/trace/trace_functions_graph.c:graph_trace_update_thresh
  - kernel/trace/trace_functions_graph.c:graph_trace_update_thresh
```
**Symbols:**

```
ffffffff811d2ed0-ffffffff811d2fb1: register_ftrace_graph (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int register_ftrace_graph(struct fgraph_ops *gops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/fgraph.c (ffffffff811d0030)
Location: kernel/trace/fgraph.c:595
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_profile_write
  - kernel/trace/trace_sched_wakeup.c:start_func_tracer
  - kernel/trace/trace_sched_wakeup.c:wakeup_flag_changed
  - kernel/trace/trace_functions_graph.c:graph_trace_update_thresh
  - kernel/trace/trace_functions_graph.c:graph_trace_update_thresh
```
**Symbols:**

```
ffffffff811d0030-ffffffff811d0111: register_ftrace_graph (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int register_ftrace_graph(struct fgraph_ops *gops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/fgraph.c (ffffffff811d12e0)
Location: kernel/trace/fgraph.c:595
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_profile_write
  - kernel/trace/trace_sched_wakeup.c:start_func_tracer
  - kernel/trace/trace_sched_wakeup.c:wakeup_flag_changed
  - kernel/trace/trace_functions_graph.c:graph_trace_update_thresh
  - kernel/trace/trace_functions_graph.c:graph_trace_update_thresh
```
**Symbols:**

```
ffffffff811d12e0-ffffffff811d13c1: register_ftrace_graph (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int register_ftrace_graph(struct fgraph_ops *gops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/fgraph.c (ffffffff811fdfe0)
Location: kernel/trace/fgraph.c:595
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_profile_write
  - kernel/trace/trace_sched_wakeup.c:start_func_tracer
  - kernel/trace/trace_sched_wakeup.c:wakeup_flag_changed
  - kernel/trace/trace_functions_graph.c:graph_trace_update_thresh
  - kernel/trace/trace_functions_graph.c:graph_trace_update_thresh
```
**Symbols:**

```
ffffffff811fdfe0-ffffffff811fe0c1: register_ftrace_graph (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int register_ftrace_graph(struct fgraph_ops *gops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/fgraph.c (ffffffff812389c0)
Location: kernel/trace/fgraph.c:608
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_profile_write
  - kernel/trace/trace_sched_wakeup.c:start_func_tracer
  - kernel/trace/trace_sched_wakeup.c:wakeup_flag_changed
  - kernel/trace/trace_functions_graph.c:graph_trace_update_thresh
  - kernel/trace/trace_functions_graph.c:graph_trace_update_thresh
```
**Symbols:**

```
ffffffff812389c0-ffffffff81238aab: register_ftrace_graph (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int register_ftrace_graph(struct fgraph_ops *gops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/fgraph.c (ffffffff812858a0)
Location: kernel/trace/fgraph.c:608
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_profile_write
  - kernel/trace/trace_sched_wakeup.c:start_func_tracer
  - kernel/trace/trace_sched_wakeup.c:wakeup_flag_changed
  - kernel/trace/trace_functions_graph.c:graph_trace_update_thresh
  - kernel/trace/trace_functions_graph.c:graph_trace_update_thresh
```
**Symbols:**

```
ffffffff812858a0-ffffffff8128598b: register_ftrace_graph (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int register_ftrace_graph(struct fgraph_ops *gops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/fgraph.c (ffffffff812a2560)
Location: kernel/trace/fgraph.c:633
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_profile_write
  - kernel/trace/trace_sched_wakeup.c:start_func_tracer
  - kernel/trace/trace_sched_wakeup.c:wakeup_flag_changed
  - kernel/trace/trace_functions_graph.c:graph_trace_update_thresh
  - kernel/trace/trace_functions_graph.c:graph_trace_update_thresh
```
**Symbols:**

```
ffffffff812a2560-ffffffff812a264b: register_ftrace_graph (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int register_ftrace_graph(struct fgraph_ops *gops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/fgraph.c (ffffffff812bdd60)
Location: kernel/trace/fgraph.c:633
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_profile_write
  - kernel/trace/trace_sched_wakeup.c:start_func_tracer
  - kernel/trace/trace_sched_wakeup.c:wakeup_flag_changed
  - kernel/trace/trace_functions_graph.c:graph_trace_update_thresh
  - kernel/trace/trace_functions_graph.c:graph_trace_update_thresh
```
**Symbols:**

```
ffffffff812bdd60-ffffffff812bde4b: register_ftrace_graph (STB_GLOBAL)
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
int register_ftrace_graph(struct fgraph_ops *gops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/fgraph.c (ffff800010238880)
Location: kernel/trace/fgraph.c:570
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_profile_write
  - kernel/trace/trace_functions_graph.c:graph_trace_init
  - kernel/trace/trace_functions_graph.c:graph_trace_init
```
**Symbols:**

```
ffff800010238880-ffff80001023899c: register_ftrace_graph (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int register_ftrace_graph(struct fgraph_ops *gops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/fgraph.c (c047446c)
Location: kernel/trace/fgraph.c:570
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_profile_write
  - kernel/trace/trace_functions_graph.c:graph_trace_init
```
**Symbols:**

```
c047446c-c0474578: register_ftrace_graph (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int register_ftrace_graph(struct fgraph_ops *gops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/fgraph.c (c0000000002c4d50)
Location: kernel/trace/fgraph.c:570
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_profile_write
  - kernel/trace/trace_functions_graph.c:graph_trace_init
  - kernel/trace/trace_functions_graph.c:graph_trace_init
```
**Symbols:**

```
c0000000002c4d50-c0000000002c4ee8: register_ftrace_graph (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int register_ftrace_graph(struct fgraph_ops *gops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/fgraph.c (ffffffe00018f4fc)
Location: kernel/trace/fgraph.c:570
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_profile_write
  - kernel/trace/trace_functions_graph.c:graph_trace_init
  - kernel/trace/trace_functions_graph.c:graph_trace_init
```
**Symbols:**

```
ffffffe00018f4fc-ffffffe00018f7be: register_ftrace_graph (STB_GLOBAL)
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
int register_ftrace_graph(struct fgraph_ops *gops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/fgraph.c (ffffffff811b2680)
Location: kernel/trace/fgraph.c:570
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_profile_write
  - kernel/trace/trace_functions_graph.c:graph_trace_init
  - kernel/trace/trace_functions_graph.c:graph_trace_init
```
**Symbols:**

```
ffffffff811b2680-ffffffff811b275f: register_ftrace_graph (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int register_ftrace_graph(struct fgraph_ops *gops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/fgraph.c (ffffffff811a5490)
Location: kernel/trace/fgraph.c:570
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_profile_write
  - kernel/trace/trace_functions_graph.c:graph_trace_init
  - kernel/trace/trace_functions_graph.c:graph_trace_init
```
**Symbols:**

```
ffffffff811a5490-ffffffff811a556f: register_ftrace_graph (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int register_ftrace_graph(struct fgraph_ops *gops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/fgraph.c (ffffffff811b0450)
Location: kernel/trace/fgraph.c:570
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_profile_write
  - kernel/trace/trace_functions_graph.c:graph_trace_init
  - kernel/trace/trace_functions_graph.c:graph_trace_init
```
**Symbols:**

```
ffffffff811b0450-ffffffff811b052f: register_ftrace_graph (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int register_ftrace_graph(struct fgraph_ops *gops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/fgraph.c (ffffffff811be4e0)
Location: kernel/trace/fgraph.c:570
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:ftrace_profile_write
  - kernel/trace/trace_functions_graph.c:graph_trace_init
  - kernel/trace/trace_functions_graph.c:graph_trace_init
```
**Symbols:**

```
ffffffff811be4e0-ffffffff811be5bf: register_ftrace_graph (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct fgraph_ops *gops</code>
</li>
<li>
<b>Param removed. </b>
<code>trace_func_graph_ret_t retfunc</code>
</li>
<li>
<b>Param removed. </b>
<code>trace_func_graph_ent_t entryfunc</code>
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
