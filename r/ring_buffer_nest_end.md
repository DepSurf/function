# Function: <code>ring_buffer_nest_end</code>

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
void ring_buffer_nest_end(struct ring_buffer *buffer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff8117c250)
Location: kernel/trace/ring_buffer.c:2715
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:trace_event_raw_event_synth
```
**Symbols:**

```
ffffffff8117c250-ffffffff8117c26c: ring_buffer_nest_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void ring_buffer_nest_end(struct ring_buffer *buffer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81189a50)
Location: kernel/trace/ring_buffer.c:2778
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:trace_event_raw_event_synth
```
**Symbols:**

```
ffffffff81189a50-ffffffff81189a6c: ring_buffer_nest_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void ring_buffer_nest_end(struct ring_buffer *buffer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81197020)
Location: kernel/trace/ring_buffer.c:2755
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:trace_event_raw_event_synth
```
**Symbols:**

```
ffffffff81197020-ffffffff81197037: ring_buffer_nest_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void ring_buffer_nest_end(struct ring_buffer *buffer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811a2a20)
Location: kernel/trace/ring_buffer.c:2756
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:trace_event_raw_event_synth
```
**Symbols:**

```
ffffffff811a2a20-ffffffff811a2a37: ring_buffer_nest_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void ring_buffer_nest_end(struct trace_buffer *buffer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811b9600)
Location: kernel/trace/ring_buffer.c:2825
Inline: False
Direct callers:
  - kernel/trace/trace.c:trace_vbprintk
  - kernel/trace/trace_events_synth.c:synth_event_trace_end
  - kernel/trace/trace_events_synth.c:synth_event_trace_start
  - kernel/trace/trace_events_synth.c:synth_event_trace_array
  - kernel/trace/trace_events_synth.c:synth_event_trace_array
  - kernel/trace/trace_events_synth.c:synth_event_trace
  - kernel/trace/trace_events_synth.c:synth_event_trace
  - kernel/trace/trace_events_synth.c:trace_event_raw_event_synth
```
**Symbols:**

```
ffffffff811b9600-ffffffff811b9617: ring_buffer_nest_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void ring_buffer_nest_end(struct trace_buffer *buffer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811b7040)
Location: kernel/trace/ring_buffer.c:3158
Inline: False
Direct callers:
  - kernel/trace/trace.c:trace_vbprintk
  - kernel/trace/trace_events_synth.c:synth_event_trace_end
  - kernel/trace/trace_events_synth.c:synth_event_trace_array
  - kernel/trace/trace_events_synth.c:synth_event_trace_array
  - kernel/trace/trace_events_synth.c:synth_event_trace
  - kernel/trace/trace_events_synth.c:synth_event_trace
  - kernel/trace/trace_events_synth.c:trace_event_raw_event_synth
```
**Symbols:**

```
ffffffff811b7040-ffffffff811b7057: ring_buffer_nest_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void ring_buffer_nest_end(struct trace_buffer *buffer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811b7ad0)
Location: kernel/trace/ring_buffer.c:3241
Inline: False
Direct callers:
  - kernel/trace/trace.c:trace_vbprintk
  - kernel/trace/trace_events_synth.c:synth_event_trace_end
  - kernel/trace/trace_events_synth.c:synth_event_trace_array
  - kernel/trace/trace_events_synth.c:synth_event_trace_array
  - kernel/trace/trace_events_synth.c:synth_event_trace
  - kernel/trace/trace_events_synth.c:synth_event_trace
  - kernel/trace/trace_events_synth.c:trace_event_raw_event_synth
```
**Symbols:**

```
ffffffff811b7ad0-ffffffff811b7ae7: ring_buffer_nest_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void ring_buffer_nest_end(struct trace_buffer *buffer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811e1d10)
Location: kernel/trace/ring_buffer.c:3241
Inline: False
Direct callers:
  - kernel/trace/trace.c:trace_vbprintk
  - kernel/trace/trace_events_synth.c:synth_event_trace_end
  - kernel/trace/trace_events_synth.c:synth_event_trace_array
  - kernel/trace/trace_events_synth.c:synth_event_trace_array
  - kernel/trace/trace_events_synth.c:synth_event_trace
  - kernel/trace/trace_events_synth.c:synth_event_trace
  - kernel/trace/trace_events_synth.c:trace_event_raw_event_synth
```
**Symbols:**

```
ffffffff811e1d10-ffffffff811e1d27: ring_buffer_nest_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void ring_buffer_nest_end(struct trace_buffer *buffer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81218a60)
Location: kernel/trace/ring_buffer.c:3279
Inline: False
Direct callers:
  - kernel/trace/trace.c:__trace_array_vprintk
  - kernel/trace/trace.c:trace_vbprintk
  - kernel/trace/trace.c:__trace_puts
  - kernel/trace/trace_events_synth.c:synth_event_trace_end
  - kernel/trace/trace_events_synth.c:synth_event_trace_array
  - kernel/trace/trace_events_synth.c:synth_event_trace_array
  - kernel/trace/trace_events_synth.c:synth_event_trace
  - kernel/trace/trace_events_synth.c:synth_event_trace
  - kernel/trace/trace_events_synth.c:trace_event_raw_event_synth
```
**Symbols:**

```
ffffffff81218a60-ffffffff81218a9f: ring_buffer_nest_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void ring_buffer_nest_end(struct trace_buffer *buffer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff812629b0)
Location: kernel/trace/ring_buffer.c:3359
Inline: False
Direct callers:
  - kernel/trace/trace.c:__trace_array_vprintk
  - kernel/trace/trace.c:trace_vbprintk
  - kernel/trace/trace.c:__trace_puts
  - kernel/trace/trace_events_synth.c:synth_event_trace_end
  - kernel/trace/trace_events_synth.c:synth_event_trace_array
  - kernel/trace/trace_events_synth.c:synth_event_trace_array
  - kernel/trace/trace_events_synth.c:synth_event_trace
  - kernel/trace/trace_events_synth.c:synth_event_trace
  - kernel/trace/trace_events_synth.c:trace_event_raw_event_synth
```
**Symbols:**

```
ffffffff812629b0-ffffffff812629ef: ring_buffer_nest_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void ring_buffer_nest_end(struct trace_buffer *buffer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81279990)
Location: kernel/trace/ring_buffer.c:3363
Inline: False
Direct callers:
  - kernel/trace/trace.c:__trace_array_vprintk
  - kernel/trace/trace.c:trace_vbprintk
  - kernel/trace/trace.c:__trace_array_puts
  - kernel/trace/trace_events_synth.c:synth_event_trace_end
  - kernel/trace/trace_events_synth.c:synth_event_trace_array
  - kernel/trace/trace_events_synth.c:synth_event_trace_array
  - kernel/trace/trace_events_synth.c:synth_event_trace
  - kernel/trace/trace_events_synth.c:synth_event_trace
  - kernel/trace/trace_events_synth.c:trace_event_raw_event_synth
```
**Symbols:**

```
ffffffff81279990-ffffffff812799cf: ring_buffer_nest_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void ring_buffer_nest_end(struct trace_buffer *buffer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81294470)
Location: kernel/trace/ring_buffer.c:3183
Inline: False
Direct callers:
  - kernel/trace/trace.c:__trace_array_vprintk
  - kernel/trace/trace.c:trace_vbprintk
  - kernel/trace/trace.c:__trace_array_puts
  - kernel/trace/trace_events_synth.c:synth_event_trace_end
  - kernel/trace/trace_events_synth.c:synth_event_trace_array
  - kernel/trace/trace_events_synth.c:synth_event_trace_array
  - kernel/trace/trace_events_synth.c:synth_event_trace
  - kernel/trace/trace_events_synth.c:synth_event_trace
  - kernel/trace/trace_events_synth.c:trace_event_raw_event_synth
```
**Symbols:**

```
ffffffff81294470-ffffffff812944af: ring_buffer_nest_end (STB_GLOBAL)
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
void ring_buffer_nest_end(struct ring_buffer *buffer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffff80001021cf28)
Location: kernel/trace/ring_buffer.c:2756
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:trace_event_raw_event_synth
```
**Symbols:**

```
ffff80001021cf28-ffff80001021cf50: ring_buffer_nest_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void ring_buffer_nest_end(struct ring_buffer *buffer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (c045ba48)
Location: kernel/trace/ring_buffer.c:2756
Inline: False
```
**Symbols:**

```
c045ba48-c045ba7c: ring_buffer_nest_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void ring_buffer_nest_end(struct ring_buffer *buffer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (c0000000002a0970)
Location: kernel/trace/ring_buffer.c:2756
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:trace_event_raw_event_synth
```
**Symbols:**

```
c0000000002a0970-c0000000002a0990: ring_buffer_nest_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void ring_buffer_nest_end(struct ring_buffer *buffer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffe00017a722)
Location: kernel/trace/ring_buffer.c:2756
Inline: False
```
**Symbols:**

```
ffffffe00017a722-ffffffe00017a740: ring_buffer_nest_end (STB_GLOBAL)
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
void ring_buffer_nest_end(struct ring_buffer *buffer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff8119b040)
Location: kernel/trace/ring_buffer.c:2756
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:trace_event_raw_event_synth
```
**Symbols:**

```
ffffffff8119b040-ffffffff8119b057: ring_buffer_nest_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void ring_buffer_nest_end(struct ring_buffer *buffer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff8118e0c0)
Location: kernel/trace/ring_buffer.c:2756
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:trace_event_raw_event_synth
```
**Symbols:**

```
ffffffff8118e0c0-ffffffff8118e0d7: ring_buffer_nest_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void ring_buffer_nest_end(struct ring_buffer *buffer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff81198e10)
Location: kernel/trace/ring_buffer.c:2756
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:trace_event_raw_event_synth
```
**Symbols:**

```
ffffffff81198e10-ffffffff81198e27: ring_buffer_nest_end (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void ring_buffer_nest_end(struct ring_buffer *buffer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ring_buffer.c (ffffffff811a6a80)
Location: kernel/trace/ring_buffer.c:2756
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:trace_event_raw_event_synth
```
**Symbols:**

```
ffffffff811a6a80-ffffffff811a6aab: ring_buffer_nest_end (STB_GLOBAL)
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
