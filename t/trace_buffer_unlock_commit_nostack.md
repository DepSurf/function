# Function: <code>trace_buffer_unlock_commit_nostack</code>

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
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void trace_buffer_unlock_commit_nostack(struct ring_buffer *buffer, struct ring_buffer_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff81162e20)
Location: kernel/trace/trace.c:2223
Inline: False
Direct callers:
  - kernel/trace/trace_hwlat.c:kthread_fn
  - kernel/trace/trace_functions_graph.c:__trace_graph_return
  - kernel/trace/trace_functions_graph.c:__trace_graph_entry
```
**Symbols:**

```
ffffffff81162e20-ffffffff81162e55: trace_buffer_unlock_commit_nostack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void trace_buffer_unlock_commit_nostack(struct ring_buffer *buffer, struct ring_buffer_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff81166260)
Location: kernel/trace/trace.c:2400
Inline: False
Direct callers:
  - kernel/trace/trace_hwlat.c:kthread_fn
  - kernel/trace/trace_functions_graph.c:__trace_graph_return
  - kernel/trace/trace_functions_graph.c:__trace_graph_entry
```
**Symbols:**

```
ffffffff81166260-ffffffff81166295: trace_buffer_unlock_commit_nostack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void trace_buffer_unlock_commit_nostack(struct ring_buffer *buffer, struct ring_buffer_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811731f0)
Location: kernel/trace/trace.c:2408
Inline: False
Direct callers:
  - kernel/trace/trace_hwlat.c:kthread_fn
  - kernel/trace/trace_functions_graph.c:__trace_graph_return
  - kernel/trace/trace_functions_graph.c:__trace_graph_entry
```
**Symbols:**

```
ffffffff811731f0-ffffffff81173225: trace_buffer_unlock_commit_nostack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void trace_buffer_unlock_commit_nostack(struct ring_buffer *buffer, struct ring_buffer_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811821d0)
Location: kernel/trace/trace.c:2420
Inline: False
Direct callers:
  - kernel/trace/trace_hwlat.c:kthread_fn
  - kernel/trace/trace_functions_graph.c:__trace_graph_return
  - kernel/trace/trace_functions_graph.c:__trace_graph_entry
```
**Symbols:**

```
ffffffff811821d0-ffffffff81182205: trace_buffer_unlock_commit_nostack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void trace_buffer_unlock_commit_nostack(struct ring_buffer *buffer, struct ring_buffer_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8118fb90)
Location: kernel/trace/trace.c:2421
Inline: False
Direct callers:
  - kernel/trace/trace_hwlat.c:kthread_fn
  - kernel/trace/trace_functions_graph.c:__trace_graph_return
  - kernel/trace/trace_functions_graph.c:__trace_graph_entry
```
**Symbols:**

```
ffffffff8118fb90-ffffffff8118fbc5: trace_buffer_unlock_commit_nostack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void trace_buffer_unlock_commit_nostack(struct ring_buffer *buffer, struct ring_buffer_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8119d930)
Location: kernel/trace/trace.c:2605
Inline: False
Direct callers:
  - kernel/trace/trace_hwlat.c:kthread_fn
  - kernel/trace/trace_functions_graph.c:__trace_graph_return
  - kernel/trace/trace_functions_graph.c:__trace_graph_entry
```
**Symbols:**

```
ffffffff8119d930-ffffffff8119d965: trace_buffer_unlock_commit_nostack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void trace_buffer_unlock_commit_nostack(struct ring_buffer *buffer, struct ring_buffer_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811a9300)
Location: kernel/trace/trace.c:2631
Inline: False
Direct callers:
  - kernel/trace/trace_hwlat.c:kthread_fn
  - kernel/trace/trace_functions_graph.c:__trace_graph_return
  - kernel/trace/trace_functions_graph.c:__trace_graph_entry
```
**Symbols:**

```
ffffffff811a9300-ffffffff811a9335: trace_buffer_unlock_commit_nostack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void trace_buffer_unlock_commit_nostack(struct trace_buffer *buffer, struct ring_buffer_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811c1410)
Location: kernel/trace/trace.c:2742
Inline: False
Direct callers:
  - kernel/trace/trace_hwlat.c:trace_hwlat_sample
  - kernel/trace/trace_functions_graph.c:__trace_graph_return
  - kernel/trace/trace_functions_graph.c:__trace_graph_entry
```
**Symbols:**

```
ffffffff811c1410-ffffffff811c1445: trace_buffer_unlock_commit_nostack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void trace_buffer_unlock_commit_nostack(struct trace_buffer *buffer, struct ring_buffer_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811bf050)
Location: kernel/trace/trace.c:2888
Inline: False
Direct callers:
  - kernel/trace/trace_hwlat.c:trace_hwlat_sample
  - kernel/trace/trace_functions_graph.c:__trace_graph_return
  - kernel/trace/trace_functions_graph.c:__trace_graph_entry
```
**Symbols:**

```
ffffffff811bf050-ffffffff811bf085: trace_buffer_unlock_commit_nostack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void trace_buffer_unlock_commit_nostack(struct trace_buffer *buffer, struct ring_buffer_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811bfa10)
Location: kernel/trace/trace.c:2910
Inline: False
Direct callers:
  - kernel/trace/trace_hwlat.c:trace_hwlat_sample
  - kernel/trace/trace_functions_graph.c:__trace_graph_return
  - kernel/trace/trace_functions_graph.c:__trace_graph_entry
```
**Symbols:**

```
ffffffff811bfa10-ffffffff811bfa45: trace_buffer_unlock_commit_nostack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void trace_buffer_unlock_commit_nostack(struct trace_buffer *buffer, struct ring_buffer_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811ea370)
Location: kernel/trace/trace.c:2970
Inline: False
Direct callers:
  - kernel/trace/trace_hwlat.c:trace_hwlat_sample
  - kernel/trace/trace_functions_graph.c:__trace_graph_return
  - kernel/trace/trace_functions_graph.c:__trace_graph_entry
```
**Symbols:**

```
ffffffff811ea370-ffffffff811ea3a5: trace_buffer_unlock_commit_nostack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void trace_buffer_unlock_commit_nostack(struct trace_buffer *buffer, struct ring_buffer_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff81222240)
Location: kernel/trace/trace.c:2968
Inline: False
Direct callers:
  - kernel/trace/trace_hwlat.c:trace_hwlat_sample
  - kernel/trace/trace_functions_graph.c:__trace_graph_return
  - kernel/trace/trace_functions_graph.c:__trace_graph_entry
```
**Symbols:**

```
ffffffff81222240-ffffffff8122229b: trace_buffer_unlock_commit_nostack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void trace_buffer_unlock_commit_nostack(struct trace_buffer *buffer, struct ring_buffer_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8126d220)
Location: kernel/trace/trace.c:2992
Inline: False
Direct callers:
  - kernel/trace/trace_hwlat.c:trace_hwlat_sample
  - kernel/trace/trace_functions_graph.c:__trace_graph_return
  - kernel/trace/trace_functions_graph.c:__trace_graph_entry
```
**Symbols:**

```
ffffffff8126d220-ffffffff8126d27b: trace_buffer_unlock_commit_nostack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void trace_buffer_unlock_commit_nostack(struct trace_buffer *buffer, struct ring_buffer_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff812843b0)
Location: kernel/trace/trace.c:3063
Inline: False
Direct callers:
  - kernel/trace/trace_hwlat.c:trace_hwlat_sample
  - kernel/trace/trace_osnoise.c:__timerlat_dump_stack
  - kernel/trace/trace_osnoise.c:trace_timerlat_sample
  - kernel/trace/trace_functions_graph.c:__trace_graph_return
  - kernel/trace/trace_functions_graph.c:__trace_graph_entry
```
**Symbols:**

```
ffffffff812843b0-ffffffff8128440b: trace_buffer_unlock_commit_nostack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void trace_buffer_unlock_commit_nostack(struct trace_buffer *buffer, struct ring_buffer_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8129f4b0)
Location: kernel/trace/trace.c:3057
Inline: False
Direct callers:
  - kernel/trace/trace_hwlat.c:trace_hwlat_sample
  - kernel/trace/trace_osnoise.c:__timerlat_dump_stack
  - kernel/trace/trace_osnoise.c:trace_timerlat_sample
  - kernel/trace/trace_functions_graph.c:__trace_graph_return
  - kernel/trace/trace_functions_graph.c:__trace_graph_entry
```
**Symbols:**

```
ffffffff8129f4b0-ffffffff8129f50b: trace_buffer_unlock_commit_nostack (STB_GLOBAL)
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
void trace_buffer_unlock_commit_nostack(struct ring_buffer *buffer, struct ring_buffer_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffff800010225fa0)
Location: kernel/trace/trace.c:2631
Inline: False
Direct callers:
  - kernel/trace/trace_hwlat.c:kthread_fn
  - kernel/trace/trace_functions_graph.c:__trace_graph_return
  - kernel/trace/trace_functions_graph.c:__trace_graph_entry
```
**Symbols:**

```
ffff800010225fa0-ffff800010226028: trace_buffer_unlock_commit_nostack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void trace_buffer_unlock_commit_nostack(struct ring_buffer *buffer, struct ring_buffer_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (c0463504)
Location: kernel/trace/trace.c:2631
Inline: False
Direct callers:
  - kernel/trace/trace_hwlat.c:kthread_fn
  - kernel/trace/trace_functions_graph.c:__trace_graph_return
  - kernel/trace/trace_functions_graph.c:__trace_graph_entry
```
**Symbols:**

```
c0463504-c0463574: trace_buffer_unlock_commit_nostack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void trace_buffer_unlock_commit_nostack(struct ring_buffer *buffer, struct ring_buffer_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (c0000000002ab980)
Location: kernel/trace/trace.c:2631
Inline: False
Direct callers:
  - kernel/trace/trace_hwlat.c:kthread_fn
  - kernel/trace/trace_functions_graph.c:__trace_graph_return
  - kernel/trace/trace_functions_graph.c:__trace_graph_entry
```
**Symbols:**

```
c0000000002ab980-c0000000002aba3c: trace_buffer_unlock_commit_nostack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void trace_buffer_unlock_commit_nostack(struct ring_buffer *buffer, struct ring_buffer_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffe000180dd2)
Location: kernel/trace/trace.c:2631
Inline: False
Direct callers:
  - kernel/trace/trace_hwlat.c:kthread_fn
  - kernel/trace/trace_functions_graph.c:__trace_graph_return
  - kernel/trace/trace_functions_graph.c:__trace_graph_entry
```
**Symbols:**

```
ffffffe000180dd2-ffffffe000180e68: trace_buffer_unlock_commit_nostack (STB_GLOBAL)
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
void trace_buffer_unlock_commit_nostack(struct ring_buffer *buffer, struct ring_buffer_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811a1920)
Location: kernel/trace/trace.c:2631
Inline: False
Direct callers:
  - kernel/trace/trace_hwlat.c:kthread_fn
  - kernel/trace/trace_functions_graph.c:__trace_graph_return
  - kernel/trace/trace_functions_graph.c:__trace_graph_entry
```
**Symbols:**

```
ffffffff811a1920-ffffffff811a1955: trace_buffer_unlock_commit_nostack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void trace_buffer_unlock_commit_nostack(struct ring_buffer *buffer, struct ring_buffer_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811948f0)
Location: kernel/trace/trace.c:2631
Inline: False
Direct callers:
  - kernel/trace/trace_hwlat.c:kthread_fn
  - kernel/trace/trace_functions_graph.c:__trace_graph_return
  - kernel/trace/trace_functions_graph.c:__trace_graph_entry
```
**Symbols:**

```
ffffffff811948f0-ffffffff81194925: trace_buffer_unlock_commit_nostack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void trace_buffer_unlock_commit_nostack(struct ring_buffer *buffer, struct ring_buffer_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8119f6f0)
Location: kernel/trace/trace.c:2631
Inline: False
Direct callers:
  - kernel/trace/trace_hwlat.c:kthread_fn
  - kernel/trace/trace_functions_graph.c:__trace_graph_return
  - kernel/trace/trace_functions_graph.c:__trace_graph_entry
```
**Symbols:**

```
ffffffff8119f6f0-ffffffff8119f725: trace_buffer_unlock_commit_nostack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void trace_buffer_unlock_commit_nostack(struct ring_buffer *buffer, struct ring_buffer_event *event);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811ad470)
Location: kernel/trace/trace.c:2631
Inline: False
Direct callers:
  - kernel/trace/trace_hwlat.c:kthread_fn
  - kernel/trace/trace_functions_graph.c:__trace_graph_return
  - kernel/trace/trace_functions_graph.c:__trace_graph_entry
```
**Symbols:**

```
ffffffff811ad470-ffffffff811ad4a5: trace_buffer_unlock_commit_nostack (STB_GLOBAL)
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
<code>struct ring_buffer *buffer</code> ➡️ <code>struct trace_buffer *buffer</code>
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
