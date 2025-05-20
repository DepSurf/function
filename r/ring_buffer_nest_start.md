# Function: <code>ring_buffer_nest_start</code>

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
void ring_buffer_nest_start(struct ring_buffer *buffer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff8117c230)
Location: kernel/trace/ring_buffer.c:2695
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:trace_event_raw_event_synth
```
**Symbols:**

```
ffffffff8117c230-ffffffff8117c24c: ring_buffer_nest_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void ring_buffer_nest_start(struct ring_buffer *buffer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81189a30)
Location: kernel/trace/ring_buffer.c:2758
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:trace_event_raw_event_synth
```
**Symbols:**

```
ffffffff81189a30-ffffffff81189a4c: ring_buffer_nest_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void ring_buffer_nest_start(struct ring_buffer *buffer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81197000)
Location: kernel/trace/ring_buffer.c:2735
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:trace_event_raw_event_synth
```
**Symbols:**

```
ffffffff81197000-ffffffff81197017: ring_buffer_nest_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void ring_buffer_nest_start(struct ring_buffer *buffer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811a2a00)
Location: kernel/trace/ring_buffer.c:2736
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:trace_event_raw_event_synth
```
**Symbols:**

```
ffffffff811a2a00-ffffffff811a2a17: ring_buffer_nest_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void ring_buffer_nest_start(struct trace_buffer *buffer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811b95e0)
Location: kernel/trace/ring_buffer.c:2805
Inline: False
Direct callers:
  - kernel/trace/trace.c:trace_vbprintk
  - kernel/trace/trace_events_synth.c:synth_event_trace_start
  - kernel/trace/trace_events_synth.c:synth_event_trace_array
  - kernel/trace/trace_events_synth.c:synth_event_trace
  - kernel/trace/trace_events_synth.c:trace_event_raw_event_synth
```
**Symbols:**

```
ffffffff811b95e0-ffffffff811b95f7: ring_buffer_nest_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void ring_buffer_nest_start(struct trace_buffer *buffer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811b7020)
Location: kernel/trace/ring_buffer.c:3138
Inline: False
Direct callers:
  - kernel/trace/trace.c:trace_vbprintk
  - kernel/trace/trace_events_synth.c:synth_event_trace_array
  - kernel/trace/trace_events_synth.c:synth_event_trace
  - kernel/trace/trace_events_synth.c:trace_event_raw_event_synth
```
**Symbols:**

```
ffffffff811b7020-ffffffff811b7037: ring_buffer_nest_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void ring_buffer_nest_start(struct trace_buffer *buffer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811b7ab0)
Location: kernel/trace/ring_buffer.c:3221
Inline: False
Direct callers:
  - kernel/trace/trace.c:trace_vbprintk
  - kernel/trace/trace_events_synth.c:synth_event_trace_array
  - kernel/trace/trace_events_synth.c:synth_event_trace
  - kernel/trace/trace_events_synth.c:trace_event_raw_event_synth
```
**Symbols:**

```
ffffffff811b7ab0-ffffffff811b7ac7: ring_buffer_nest_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void ring_buffer_nest_start(struct trace_buffer *buffer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811e1cf0)
Location: kernel/trace/ring_buffer.c:3221
Inline: False
Direct callers:
  - kernel/trace/trace.c:trace_vbprintk
  - kernel/trace/trace_events_synth.c:synth_event_trace_array
  - kernel/trace/trace_events_synth.c:synth_event_trace
  - kernel/trace/trace_events_synth.c:trace_event_raw_event_synth
```
**Symbols:**

```
ffffffff811e1cf0-ffffffff811e1d07: ring_buffer_nest_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void ring_buffer_nest_start(struct trace_buffer *buffer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81218a30)
Location: kernel/trace/ring_buffer.c:3259
Inline: False
Direct callers:
  - kernel/trace/trace.c:__trace_array_vprintk
  - kernel/trace/trace.c:trace_vbprintk
  - kernel/trace/trace.c:__trace_puts
  - kernel/trace/trace_events_synth.c:synth_event_trace_array
  - kernel/trace/trace_events_synth.c:synth_event_trace
  - kernel/trace/trace_events_synth.c:trace_event_raw_event_synth
```
**Symbols:**

```
ffffffff81218a30-ffffffff81218a58: ring_buffer_nest_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void ring_buffer_nest_start(struct trace_buffer *buffer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81262970)
Location: kernel/trace/ring_buffer.c:3339
Inline: False
Direct callers:
  - kernel/trace/trace.c:__trace_array_vprintk
  - kernel/trace/trace.c:trace_vbprintk
  - kernel/trace/trace.c:__trace_puts
  - kernel/trace/trace_events_synth.c:synth_event_trace_array
  - kernel/trace/trace_events_synth.c:synth_event_trace
  - kernel/trace/trace_events_synth.c:trace_event_raw_event_synth
```
**Symbols:**

```
ffffffff81262970-ffffffff81262998: ring_buffer_nest_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void ring_buffer_nest_start(struct trace_buffer *buffer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81279950)
Location: kernel/trace/ring_buffer.c:3343
Inline: False
Direct callers:
  - kernel/trace/trace.c:__trace_array_vprintk
  - kernel/trace/trace.c:trace_vbprintk
  - kernel/trace/trace.c:__trace_array_puts
  - kernel/trace/trace_events_synth.c:synth_event_trace_array
  - kernel/trace/trace_events_synth.c:synth_event_trace
  - kernel/trace/trace_events_synth.c:trace_event_raw_event_synth
```
**Symbols:**

```
ffffffff81279950-ffffffff81279978: ring_buffer_nest_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void ring_buffer_nest_start(struct trace_buffer *buffer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81294430)
Location: kernel/trace/ring_buffer.c:3163
Inline: False
Direct callers:
  - kernel/trace/trace.c:__trace_array_vprintk
  - kernel/trace/trace.c:trace_vbprintk
  - kernel/trace/trace.c:__trace_array_puts
  - kernel/trace/trace_events_synth.c:synth_event_trace_array
  - kernel/trace/trace_events_synth.c:synth_event_trace
  - kernel/trace/trace_events_synth.c:trace_event_raw_event_synth
```
**Symbols:**

```
ffffffff81294430-ffffffff81294458: ring_buffer_nest_start (STB_GLOBAL)
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
void ring_buffer_nest_start(struct ring_buffer *buffer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffff80001021cf00)
Location: kernel/trace/ring_buffer.c:2736
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:trace_event_raw_event_synth
```
**Symbols:**

```
ffff80001021cf00-ffff80001021cf28: ring_buffer_nest_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void ring_buffer_nest_start(struct ring_buffer *buffer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (c045ba14)
Location: kernel/trace/ring_buffer.c:2736
Inline: False
```
**Symbols:**

```
c045ba14-c045ba48: ring_buffer_nest_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void ring_buffer_nest_start(struct ring_buffer *buffer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (c0000000002a0950)
Location: kernel/trace/ring_buffer.c:2736
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:trace_event_raw_event_synth
```
**Symbols:**

```
c0000000002a0950-c0000000002a0970: ring_buffer_nest_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void ring_buffer_nest_start(struct ring_buffer *buffer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffe00017a704)
Location: kernel/trace/ring_buffer.c:2736
Inline: False
```
**Symbols:**

```
ffffffe00017a704-ffffffe00017a722: ring_buffer_nest_start (STB_GLOBAL)
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
void ring_buffer_nest_start(struct ring_buffer *buffer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff8119b020)
Location: kernel/trace/ring_buffer.c:2736
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:trace_event_raw_event_synth
```
**Symbols:**

```
ffffffff8119b020-ffffffff8119b037: ring_buffer_nest_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void ring_buffer_nest_start(struct ring_buffer *buffer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff8118e0a0)
Location: kernel/trace/ring_buffer.c:2736
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:trace_event_raw_event_synth
```
**Symbols:**

```
ffffffff8118e0a0-ffffffff8118e0b7: ring_buffer_nest_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void ring_buffer_nest_start(struct ring_buffer *buffer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81198df0)
Location: kernel/trace/ring_buffer.c:2736
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:trace_event_raw_event_synth
```
**Symbols:**

```
ffffffff81198df0-ffffffff81198e07: ring_buffer_nest_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void ring_buffer_nest_start(struct ring_buffer *buffer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811a6a60)
Location: kernel/trace/ring_buffer.c:2736
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:trace_event_raw_event_synth
```
**Symbols:**

```
ffffffff811a6a60-ffffffff811a6a7e: ring_buffer_nest_start (STB_GLOBAL)
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
