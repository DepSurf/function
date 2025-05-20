# Function: <code>hist_trigger_elt_update</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff81171cc5)
Location: kernel/trace/trace_events_hist.c:840
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger
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
In kernel/trace/trace_events_hist.c (ffffffff8117d435)
Location: kernel/trace/trace_events_hist.c:840
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger
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
In kernel/trace/trace_events_hist.c (ffffffff8117ffbc)
Location: kernel/trace/trace_events_hist.c:841
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff8118d852)
Location: kernel/trace/trace_events_hist.c:884
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff8119c781)
Location: kernel/trace/trace_events_hist.c:4558
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger
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
In kernel/trace/trace_events_hist.c (ffffffff811aab41)
Location: kernel/trace/trace_events_hist.c:4643
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger
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
In kernel/trace/trace_events_hist.c (ffffffff811b8bce)
Location: kernel/trace/trace_events_hist.c:5159
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger
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
In kernel/trace/trace_events_hist.c (ffffffff811c41ae)
Location: kernel/trace/trace_events_hist.c:5269
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void hist_trigger_elt_update(struct hist_trigger_data *hist_data, struct tracing_map_elt *elt, void *rec, struct ring_buffer_event *rbe, u64 *var_ref_vals);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811e0a90)
Location: kernel/trace/trace_events_hist.c:4377
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger
```
**Symbols:**

```
ffffffff811e0a90-ffffffff811e0c3c: hist_trigger_elt_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void hist_trigger_elt_update(struct hist_trigger_data *hist_data, struct tracing_map_elt *elt, void *rec, struct ring_buffer_event *rbe, u64 *var_ref_vals);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811de3f0)
Location: kernel/trace/trace_events_hist.c:4402
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger
```
**Symbols:**

```
ffffffff811de3f0-ffffffff811de5f2: hist_trigger_elt_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void hist_trigger_elt_update(struct hist_trigger_data *hist_data, struct tracing_map_elt *elt, struct trace_buffer *buffer, void *rec, struct ring_buffer_event *rbe, u64 *var_ref_vals);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811df7b0)
Location: kernel/trace/trace_events_hist.c:4470
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger
```
**Symbols:**

```
ffffffff811df7b0-ffffffff811df9a5: hist_trigger_elt_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void hist_trigger_elt_update(struct hist_trigger_data *hist_data, struct tracing_map_elt *elt, struct trace_buffer *buffer, void *rec, struct ring_buffer_event *rbe, u64 *var_ref_vals);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff8120f070)
Location: kernel/trace/trace_events_hist.c:4565
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger
```
**Symbols:**

```
ffffffff8120f070-ffffffff8120f2e1: hist_trigger_elt_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void hist_trigger_elt_update(struct hist_trigger_data *hist_data, struct tracing_map_elt *elt, struct trace_buffer *buffer, void *rec, struct ring_buffer_event *rbe, u64 *var_ref_vals);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff8124bed0)
Location: kernel/trace/trace_events_hist.c:4944
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger
```
**Symbols:**

```
ffffffff8124bed0-ffffffff8124c094: hist_trigger_elt_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void hist_trigger_elt_update(struct hist_trigger_data *hist_data, struct tracing_map_elt *elt, struct trace_buffer *buffer, void *rec, struct ring_buffer_event *rbe, u64 *var_ref_vals);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff8129d870)
Location: kernel/trace/trace_events_hist.c:5075
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger
```
**Symbols:**

```
ffffffff8129d870-ffffffff8129da2c: hist_trigger_elt_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void hist_trigger_elt_update(struct hist_trigger_data *hist_data, struct tracing_map_elt *elt, struct trace_buffer *buffer, void *rec, struct ring_buffer_event *rbe, u64 *var_ref_vals);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff812bb240)
Location: kernel/trace/trace_events_hist.c:5152
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger
```
**Symbols:**

```
ffffffff812bb240-ffffffff812bb453: hist_trigger_elt_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void hist_trigger_elt_update(struct hist_trigger_data *hist_data, struct tracing_map_elt *elt, struct trace_buffer *buffer, void *rec, struct ring_buffer_event *rbe, u64 *var_ref_vals);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff812d7890)
Location: kernel/trace/trace_events_hist.c:5144
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger
```
**Symbols:**

```
ffffffff812d7890-ffffffff812d7aa3: hist_trigger_elt_update (STB_LOCAL)
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
In kernel/trace/trace_events_hist.c (ffff800010243d80)
Location: kernel/trace/trace_events_hist.c:5269
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (c0000000002d6e10)
Location: kernel/trace/trace_events_hist.c:5269
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger
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
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811bc7ce)
Location: kernel/trace/trace_events_hist.c:5269
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger
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
In kernel/trace/trace_events_hist.c (ffffffff811af5ae)
Location: kernel/trace/trace_events_hist.c:5269
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger
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
In kernel/trace/trace_events_hist.c (ffffffff811ba59e)
Location: kernel/trace/trace_events_hist.c:5269
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger
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
In kernel/trace/trace_events_hist.c (ffffffff811c863e)
Location: kernel/trace/trace_events_hist.c:5269
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<code>hist_data, elt, rec, rbe, var_ref_vals</code> ➡️ <code>hist_data, elt, buffer, rec, rbe, var_ref_vals</code>
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
