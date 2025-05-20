# Function: <code>__trace_array_put</code>

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
In kernel/trace/trace.c (ffffffff8114bd5e)
Location: kernel/trace/trace.c:298
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_buffers_release
  - kernel/trace/trace.c:tracing_open_pipe
  - kernel/trace/trace.c:trace_array_put
  - kernel/trace/trace.c:tracing_release
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
In kernel/trace/trace.c (ffffffff8115477e)
Location: kernel/trace/trace.c:296
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_buffers_release
  - kernel/trace/trace.c:tracing_open_pipe
  - kernel/trace/trace.c:tracing_release
  - kernel/trace/trace.c:trace_array_put
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
In kernel/trace/trace.c (ffffffff8115ec0e)
Location: kernel/trace/trace.c:298
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_buffers_release
  - kernel/trace/trace.c:tracing_open_pipe
  - kernel/trace/trace.c:tracing_open_pipe
  - kernel/trace/trace.c:tracing_release
  - kernel/trace/trace.c:trace_array_put
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff81161e4c)
Location: kernel/trace/trace.c:290
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_buffers_release
  - kernel/trace/trace.c:tracing_open_pipe
  - kernel/trace/trace.c:tracing_open_pipe
  - kernel/trace/trace.c:tracing_release
  - kernel/trace/trace.c:trace_array_put
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (ffffffff8116f310)
Location: kernel/trace/trace.c:290
Inline: True
Direct callers:
  - kernel/trace/trace.c:tracing_buffers_release
  - kernel/trace/trace.c:tracing_open_pipe
  - kernel/trace/trace.c:tracing_open_pipe
  - kernel/trace/trace.c:tracing_release
  - kernel/trace/trace.c:trace_array_put
```
**Symbols:**

```
ffffffff8116f310-ffffffff8116f329: __trace_array_put.isra.25 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (ffffffff8117e390)
Location: kernel/trace/trace.c:291
Inline: True
Direct callers:
  - kernel/trace/trace.c:tracing_buffers_release
  - kernel/trace/trace.c:tracing_open_pipe
  - kernel/trace/trace.c:tracing_open_pipe
  - kernel/trace/trace.c:tracing_release
  - kernel/trace/trace.c:trace_array_put
```
**Symbols:**

```
ffffffff8117e390-ffffffff8117e3a9: __trace_array_put.isra.25 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (ffffffff8118bc80)
Location: kernel/trace/trace.c:292
Inline: True
Direct callers:
  - kernel/trace/trace.c:tracing_buffers_release
  - kernel/trace/trace.c:tracing_open_pipe
  - kernel/trace/trace.c:tracing_open_pipe
  - kernel/trace/trace.c:tracing_release
  - kernel/trace/trace.c:trace_array_put
```
**Symbols:**

```
ffffffff8118bc80-ffffffff8118bc99: __trace_array_put.isra.26 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (0)
Location: kernel/trace/trace.c:294
Inline: True
Direct callers:
  - kernel/trace/trace.c:tracing_buffers_release
  - kernel/trace/trace.c:tracing_open_pipe
  - kernel/trace/trace.c:tracing_open_pipe
  - kernel/trace/trace.c:tracing_release
  - kernel/trace/trace.c:trace_array_put
```
**Symbols:**

```
ffffffff811993a0-ffffffff811993ba: __trace_array_put.isra.0 (STB_LOCAL)
ffffffff811a19c9-ffffffff811a19de: __trace_array_put.isra.0.cold (STB_LOCAL)
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
In kernel/trace/trace.c (ffffffff811a441f)
Location: kernel/trace/trace.c:295
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_buffers_release
  - kernel/trace/trace.c:tracing_open_pipe
  - kernel/trace/trace.c:tracing_open_pipe
  - kernel/trace/trace.c:tracing_release
  - kernel/trace/trace.c:trace_array_put
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811bc558)
Location: kernel/trace/trace.c:298
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_buffers_release
  - kernel/trace/trace.c:tracing_buffers_open
  - kernel/trace/trace.c:tracing_buffers_open
  - kernel/trace/trace.c:tracing_err_log_release
  - kernel/trace/trace.c:tracing_err_log_open
  - kernel/trace/trace.c:tracing_snapshot_open
  - kernel/trace/trace.c:tracing_time_stamp_mode_open
  - kernel/trace/trace.c:tracing_clock_open
  - kernel/trace/trace.c:tracing_free_buffer_release
  - kernel/trace/trace.c:tracing_release_pipe
  - kernel/trace/trace.c:tracing_open_pipe
  - kernel/trace/trace.c:tracing_open_pipe
  - kernel/trace/trace.c:tracing_trace_options_open
  - kernel/trace/trace.c:show_traces_release
  - kernel/trace/trace.c:show_traces_open
  - kernel/trace/trace.c:tracing_open
  - kernel/trace/trace.c:tracing_single_release_tr
  - kernel/trace/trace.c:tracing_release_generic_tr
  - kernel/trace/trace.c:tracing_release
  - kernel/trace/trace.c:tracing_release
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811ba168)
Location: kernel/trace/trace.c:449
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_buffers_release
  - kernel/trace/trace.c:tracing_buffers_open
  - kernel/trace/trace.c:tracing_buffers_open
  - kernel/trace/trace.c:tracing_err_log_release
  - kernel/trace/trace.c:tracing_err_log_open
  - kernel/trace/trace.c:tracing_snapshot_open
  - kernel/trace/trace.c:tracing_time_stamp_mode_open
  - kernel/trace/trace.c:tracing_clock_open
  - kernel/trace/trace.c:tracing_free_buffer_release
  - kernel/trace/trace.c:tracing_release_pipe
  - kernel/trace/trace.c:tracing_open_pipe
  - kernel/trace/trace.c:tracing_open_pipe
  - kernel/trace/trace.c:tracing_trace_options_open
  - kernel/trace/trace.c:show_traces_release
  - kernel/trace/trace.c:show_traces_open
  - kernel/trace/trace.c:tracing_open
  - kernel/trace/trace.c:tracing_single_release_tr
  - kernel/trace/trace.c:tracing_release_generic_tr
  - kernel/trace/trace.c:tracing_release
  - kernel/trace/trace.c:tracing_release
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
In kernel/trace/trace.c (ffffffff811ba5c8)
Location: kernel/trace/trace.c:450
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_buffers_release
  - kernel/trace/trace.c:tracing_buffers_open
  - kernel/trace/trace.c:tracing_buffers_open
  - kernel/trace/trace.c:tracing_err_log_release
  - kernel/trace/trace.c:tracing_err_log_open
  - kernel/trace/trace.c:tracing_snapshot_open
  - kernel/trace/trace.c:tracing_time_stamp_mode_open
  - kernel/trace/trace.c:tracing_clock_open
  - kernel/trace/trace.c:tracing_free_buffer_release
  - kernel/trace/trace.c:tracing_release_pipe
  - kernel/trace/trace.c:tracing_open_pipe
  - kernel/trace/trace.c:tracing_open_pipe
  - kernel/trace/trace.c:tracing_trace_options_open
  - kernel/trace/trace.c:show_traces_release
  - kernel/trace/trace.c:show_traces_open
  - kernel/trace/trace.c:tracing_open
  - kernel/trace/trace.c:tracing_single_release_tr
  - kernel/trace/trace.c:tracing_release_generic_tr
  - kernel/trace/trace.c:tracing_release
  - kernel/trace/trace.c:tracing_release
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
In kernel/trace/trace.c (ffffffff811e3288)
Location: kernel/trace/trace.c:463
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_buffers_release
  - kernel/trace/trace.c:tracing_buffers_open
  - kernel/trace/trace.c:tracing_buffers_open
  - kernel/trace/trace.c:tracing_err_log_release
  - kernel/trace/trace.c:tracing_err_log_open
  - kernel/trace/trace.c:tracing_snapshot_open
  - kernel/trace/trace.c:tracing_time_stamp_mode_open
  - kernel/trace/trace.c:tracing_clock_open
  - kernel/trace/trace.c:tracing_free_buffer_release
  - kernel/trace/trace.c:tracing_release_pipe
  - kernel/trace/trace.c:tracing_open_pipe
  - kernel/trace/trace.c:tracing_open_pipe
  - kernel/trace/trace.c:tracing_trace_options_open
  - kernel/trace/trace.c:show_traces_release
  - kernel/trace/trace.c:show_traces_open
  - kernel/trace/trace.c:tracing_open
  - kernel/trace/trace.c:tracing_single_release_tr
  - kernel/trace/trace.c:tracing_release_generic_tr
  - kernel/trace/trace.c:tracing_release
  - kernel/trace/trace.c:tracing_release
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
In kernel/trace/trace.c (ffffffff8121a5b5)
Location: kernel/trace/trace.c:473
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_buffers_release
  - kernel/trace/trace.c:tracing_buffers_open
  - kernel/trace/trace.c:tracing_err_log_release
  - kernel/trace/trace.c:tracing_err_log_open
  - kernel/trace/trace.c:tracing_snapshot_open
  - kernel/trace/trace.c:tracing_time_stamp_mode_open
  - kernel/trace/trace.c:tracing_clock_open
  - kernel/trace/trace.c:tracing_free_buffer_release
  - kernel/trace/trace.c:tracing_release_pipe
  - kernel/trace/trace.c:tracing_open_pipe
  - kernel/trace/trace.c:tracing_open_pipe
  - kernel/trace/trace.c:tracing_trace_options_open
  - kernel/trace/trace.c:show_traces_release
  - kernel/trace/trace.c:show_traces_open
  - kernel/trace/trace.c:tracing_open
  - kernel/trace/trace.c:tracing_single_release_tr
  - kernel/trace/trace.c:tracing_release_generic_tr
  - kernel/trace/trace.c:tracing_release
  - kernel/trace/trace.c:tracing_release
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
In kernel/trace/trace.c (ffffffff812642d5)
Location: kernel/trace/trace.c:472
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_buffers_release
  - kernel/trace/trace.c:tracing_buffers_open
  - kernel/trace/trace.c:tracing_err_log_release
  - kernel/trace/trace.c:tracing_err_log_open
  - kernel/trace/trace.c:tracing_snapshot_open
  - kernel/trace/trace.c:tracing_time_stamp_mode_open
  - kernel/trace/trace.c:tracing_clock_open
  - kernel/trace/trace.c:tracing_free_buffer_release
  - kernel/trace/trace.c:tracing_release_pipe
  - kernel/trace/trace.c:tracing_open_pipe
  - kernel/trace/trace.c:tracing_open_pipe
  - kernel/trace/trace.c:tracing_trace_options_open
  - kernel/trace/trace.c:show_traces_release
  - kernel/trace/trace.c:show_traces_open
  - kernel/trace/trace.c:tracing_open
  - kernel/trace/trace.c:tracing_single_release_tr
  - kernel/trace/trace.c:tracing_release_generic_tr
  - kernel/trace/trace.c:tracing_release
  - kernel/trace/trace.c:tracing_release
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
In kernel/trace/trace.c (ffffffff836da189)
Location: kernel/trace/trace.c:513
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_init
  - kernel/trace/trace.c:tracing_buffers_release
  - kernel/trace/trace.c:tracing_buffers_open
  - kernel/trace/trace.c:tracing_err_log_release
  - kernel/trace/trace.c:tracing_err_log_open
  - kernel/trace/trace.c:tracing_snapshot_open
  - kernel/trace/trace.c:tracing_time_stamp_mode_open
  - kernel/trace/trace.c:tracing_clock_open
  - kernel/trace/trace.c:tracing_free_buffer_release
  - kernel/trace/trace.c:tracing_release_pipe
  - kernel/trace/trace.c:tracing_open_pipe
  - kernel/trace/trace.c:tracing_trace_options_open
  - kernel/trace/trace.c:show_traces_release
  - kernel/trace/trace.c:show_traces_open
  - kernel/trace/trace.c:tracing_open
  - kernel/trace/trace.c:tracing_single_release_tr
  - kernel/trace/trace.c:tracing_release_generic_tr
  - kernel/trace/trace.c:tracing_release
  - kernel/trace/trace.c:tracing_release
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
In kernel/trace/trace.c (ffffffff8390c6fb)
Location: kernel/trace/trace.c:515
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_init
  - kernel/trace/trace.c:tracing_release_options
  - kernel/trace/trace.c:tracing_buffers_release
  - kernel/trace/trace.c:tracing_buffers_open
  - kernel/trace/trace.c:tracing_err_log_release
  - kernel/trace/trace.c:tracing_err_log_open
  - kernel/trace/trace.c:tracing_snapshot_open
  - kernel/trace/trace.c:tracing_time_stamp_mode_open
  - kernel/trace/trace.c:tracing_clock_open
  - kernel/trace/trace.c:tracing_free_buffer_release
  - kernel/trace/trace.c:tracing_release_pipe
  - kernel/trace/trace.c:tracing_open_pipe
  - kernel/trace/trace.c:tracing_trace_options_open
  - kernel/trace/trace.c:show_traces_release
  - kernel/trace/trace.c:show_traces_open
  - kernel/trace/trace.c:tracing_open
  - kernel/trace/trace.c:tracing_single_release_tr
  - kernel/trace/trace.c:tracing_release_generic_tr
  - kernel/trace/trace.c:tracing_release
  - kernel/trace/trace.c:tracing_release
  - kernel/trace/trace.c:tracing_single_release_file_tr
  - kernel/trace/trace.c:tracing_open_file_tr
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
In kernel/trace/trace.c (ffff80001021f3b8)
Location: kernel/trace/trace.c:295
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_buffers_release
  - kernel/trace/trace.c:tracing_open_pipe
  - kernel/trace/trace.c:tracing_release
  - kernel/trace/trace.c:trace_array_put
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __trace_array_put(struct trace_array *this_tr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (c045c080)
Location: kernel/trace/trace.c:295
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_buffers_release
  - kernel/trace/trace.c:tracing_open_pipe
  - kernel/trace/trace.c:tracing_release
  - kernel/trace/trace.c:trace_array_put
```
**Symbols:**

```
c045c080-c045c0c4: __trace_array_put (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __trace_array_put(struct trace_array *this_tr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (c0000000002a0de0)
Location: kernel/trace/trace.c:295
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_buffers_release
  - kernel/trace/trace.c:tracing_open_pipe
  - kernel/trace/trace.c:tracing_release
  - kernel/trace/trace.c:trace_array_put
```
**Symbols:**

```
c0000000002a0de0-c0000000002a0dfc: __trace_array_put (STB_LOCAL)
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
In kernel/trace/trace.c (ffffffe00017bfea)
Location: kernel/trace/trace.c:295
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_buffers_release
  - kernel/trace/trace.c:tracing_open_pipe
  - kernel/trace/trace.c:tracing_release
  - kernel/trace/trace.c:trace_array_put
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
In kernel/trace/trace.c (ffffffff8119ca3f)
Location: kernel/trace/trace.c:295
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_buffers_release
  - kernel/trace/trace.c:tracing_open_pipe
  - kernel/trace/trace.c:tracing_open_pipe
  - kernel/trace/trace.c:tracing_release
  - kernel/trace/trace.c:trace_array_put
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
In kernel/trace/trace.c (ffffffff8118fa9f)
Location: kernel/trace/trace.c:295
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_buffers_release
  - kernel/trace/trace.c:tracing_open_pipe
  - kernel/trace/trace.c:tracing_open_pipe
  - kernel/trace/trace.c:tracing_release
  - kernel/trace/trace.c:trace_array_put
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
In kernel/trace/trace.c (ffffffff8119a80f)
Location: kernel/trace/trace.c:295
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_buffers_release
  - kernel/trace/trace.c:tracing_open_pipe
  - kernel/trace/trace.c:tracing_open_pipe
  - kernel/trace/trace.c:tracing_release
  - kernel/trace/trace.c:trace_array_put
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
In kernel/trace/trace.c (ffffffff811a84af)
Location: kernel/trace/trace.c:295
Inline: True
Inline callers:
  - kernel/trace/trace.c:tracing_buffers_release
  - kernel/trace/trace.c:tracing_open_pipe
  - kernel/trace/trace.c:tracing_open_pipe
  - kernel/trace/trace.c:tracing_release
  - kernel/trace/trace.c:trace_array_put
```
</details>
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
</ul>
