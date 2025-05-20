# Function: <code>hist_field_timestamp</code>

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
u64 hist_field_timestamp(struct hist_field *hist_field, struct tracing_map_elt *elt, struct ring_buffer_event *rbe, void *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff8119ce30)
Location: kernel/trace/trace_events_hist.c:1223
Inline: False
```
**Symbols:**

```
ffffffff8119ce30-ffffffff8119ce8b: hist_field_timestamp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
u64 hist_field_timestamp(struct hist_field *hist_field, struct tracing_map_elt *elt, struct ring_buffer_event *rbe, void *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811ab480)
Location: kernel/trace/trace_events_hist.c:1303
Inline: False
```
**Symbols:**

```
ffffffff811ab480-ffffffff811ab4db: hist_field_timestamp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
u64 hist_field_timestamp(struct hist_field *hist_field, struct tracing_map_elt *elt, struct ring_buffer_event *rbe, void *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811b9950)
Location: kernel/trace/trace_events_hist.c:1457
Inline: False
```
**Symbols:**

```
ffffffff811b9950-ffffffff811b99ae: hist_field_timestamp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
u64 hist_field_timestamp(struct hist_field *hist_field, struct tracing_map_elt *elt, struct ring_buffer_event *rbe, void *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811c4f70)
Location: kernel/trace/trace_events_hist.c:1531
Inline: False
```
**Symbols:**

```
ffffffff811c4f70-ffffffff811c4fce: hist_field_timestamp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
u64 hist_field_timestamp(struct hist_field *hist_field, struct tracing_map_elt *elt, struct ring_buffer_event *rbe, void *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811e1ae0)
Location: kernel/trace/trace_events_hist.c:622
Inline: False
```
**Symbols:**

```
ffffffff811e1ae0-ffffffff811e1b3e: hist_field_timestamp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
u64 hist_field_timestamp(struct hist_field *hist_field, struct tracing_map_elt *elt, struct ring_buffer_event *rbe, void *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811df700)
Location: kernel/trace/trace_events_hist.c:625
Inline: False
```
**Symbols:**

```
ffffffff811df700-ffffffff811df75e: hist_field_timestamp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
u64 hist_field_timestamp(struct hist_field *hist_field, struct tracing_map_elt *elt, struct trace_buffer *buffer, struct ring_buffer_event *rbe, void *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811e08a0)
Location: kernel/trace/trace_events_hist.c:639
Inline: False
```
**Symbols:**

```
ffffffff811e08a0-ffffffff811e0901: hist_field_timestamp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
u64 hist_field_timestamp(struct hist_field *hist_field, struct tracing_map_elt *elt, struct trace_buffer *buffer, struct ring_buffer_event *rbe, void *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events_hist.c (0)
Location: kernel/trace/trace_events_hist.c:663
Inline: False
```
**Symbols:**

```
ffffffff812108c0-ffffffff8121092d: hist_field_timestamp (STB_LOCAL)
ffffffff81cb6f16-ffffffff81cb6f2a: hist_field_timestamp.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
u64 hist_field_timestamp(struct hist_field *hist_field, struct tracing_map_elt *elt, struct trace_buffer *buffer, struct ring_buffer_event *rbe, void *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events_hist.c (0)
Location: kernel/trace/trace_events_hist.c:837
Inline: False
```
**Symbols:**

```
ffffffff8124d5e0-ffffffff8124d668: hist_field_timestamp (STB_LOCAL)
ffffffff81e68007-ffffffff81e6801c: hist_field_timestamp.cold (STB_LOCAL)
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
In kernel/trace/trace_events_hist.c (ffffffff8129d627)
Location: kernel/trace/trace_events_hist.c:870
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:hist_fn_call
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
In kernel/trace/trace_events_hist.c (ffffffff812bae62)
Location: kernel/trace/trace_events_hist.c:867
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:hist_fn_call
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
In kernel/trace/trace_events_hist.c (ffffffff812d74b2)
Location: kernel/trace/trace_events_hist.c:860
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:hist_fn_call
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
u64 hist_field_timestamp(struct hist_field *hist_field, struct tracing_map_elt *elt, struct ring_buffer_event *rbe, void *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffff800010244d18)
Location: kernel/trace/trace_events_hist.c:1531
Inline: False
```
**Symbols:**

```
ffff800010244d18-ffff800010244d88: hist_field_timestamp (STB_LOCAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
u64 hist_field_timestamp(struct hist_field *hist_field, struct tracing_map_elt *elt, struct ring_buffer_event *rbe, void *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (c0000000002d8ac0)
Location: kernel/trace/trace_events_hist.c:1531
Inline: False
```
**Symbols:**

```
c0000000002d8ac0-c0000000002d8b70: hist_field_timestamp (STB_LOCAL)
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
u64 hist_field_timestamp(struct hist_field *hist_field, struct tracing_map_elt *elt, struct ring_buffer_event *rbe, void *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811bd590)
Location: kernel/trace/trace_events_hist.c:1531
Inline: False
```
**Symbols:**

```
ffffffff811bd590-ffffffff811bd5ee: hist_field_timestamp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
u64 hist_field_timestamp(struct hist_field *hist_field, struct tracing_map_elt *elt, struct ring_buffer_event *rbe, void *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811b0370)
Location: kernel/trace/trace_events_hist.c:1531
Inline: False
```
**Symbols:**

```
ffffffff811b0370-ffffffff811b03ce: hist_field_timestamp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
u64 hist_field_timestamp(struct hist_field *hist_field, struct tracing_map_elt *elt, struct ring_buffer_event *rbe, void *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811bb360)
Location: kernel/trace/trace_events_hist.c:1531
Inline: False
```
**Symbols:**

```
ffffffff811bb360-ffffffff811bb3be: hist_field_timestamp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
u64 hist_field_timestamp(struct hist_field *hist_field, struct tracing_map_elt *elt, struct ring_buffer_event *rbe, void *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811c9400)
Location: kernel/trace/trace_events_hist.c:1531
Inline: False
```
**Symbols:**

```
ffffffff811c9400-ffffffff811c945e: hist_field_timestamp (STB_LOCAL)
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
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.11</code> and <code>5.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct trace_buffer *buffer</code>
</li>
<li>
<b>Param reordered. </b>
<code>hist_field, elt, rbe, event</code> ➡️ <code>hist_field, elt, buffer, rbe, event</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
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
