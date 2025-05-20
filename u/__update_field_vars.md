# Function: <code>__update_field_vars</code>

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
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff8119c85e)
Location: kernel/trace/trace_events_hist.c:3073
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger
  - kernel/trace/trace_events_hist.c:onmax_save
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
In kernel/trace/trace_events_hist.c (ffffffff811aac1e)
Location: kernel/trace/trace_events_hist.c:3189
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger
  - kernel/trace/trace_events_hist.c:onmax_save
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
In kernel/trace/trace_events_hist.c (ffffffff811b8cca)
Location: kernel/trace/trace_events_hist.c:3341
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger
  - kernel/trace/trace_events_hist.c:save_track_data_vars
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
In kernel/trace/trace_events_hist.c (ffffffff811c42aa)
Location: kernel/trace/trace_events_hist.c:3458
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger
  - kernel/trace/trace_events_hist.c:save_track_data_vars
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
In kernel/trace/trace_events_hist.c (ffffffff811e0b7a)
Location: kernel/trace/trace_events_hist.c:2553
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:hist_trigger_elt_update
  - kernel/trace/trace_events_hist.c:save_track_data_vars
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
In kernel/trace/trace_events_hist.c (ffffffff811de540)
Location: kernel/trace/trace_events_hist.c:2563
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:hist_trigger_elt_update
  - kernel/trace/trace_events_hist.c:save_track_data_vars
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
In kernel/trace/trace_events_hist.c (ffffffff811df901)
Location: kernel/trace/trace_events_hist.c:2620
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:hist_trigger_elt_update
  - kernel/trace/trace_events_hist.c:save_track_data_vars
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
In kernel/trace/trace_events_hist.c (ffffffff8120f1fb)
Location: kernel/trace/trace_events_hist.c:2674
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:hist_trigger_elt_update
  - kernel/trace/trace_events_hist.c:save_track_data_vars
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __update_field_vars(struct tracing_map_elt *elt, struct trace_buffer *buffer, struct ring_buffer_event *rbe, void *rec, struct field_var **field_vars, unsigned int n_field_vars, unsigned int field_var_str_start);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff8124bd90)
Location: kernel/trace/trace_events_hist.c:3051
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:hist_trigger_elt_update
  - kernel/trace/trace_events_hist.c:save_track_data_vars
```
**Symbols:**

```
ffffffff8124bd90-ffffffff8124be77: __update_field_vars (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __update_field_vars(struct tracing_map_elt *elt, struct trace_buffer *buffer, struct ring_buffer_event *rbe, void *rec, struct field_var **field_vars, unsigned int n_field_vars, unsigned int field_var_str_start);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff8129d710)
Location: kernel/trace/trace_events_hist.c:3102
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:hist_trigger_elt_update
  - kernel/trace/trace_events_hist.c:save_track_data_vars
```
**Symbols:**

```
ffffffff8129d710-ffffffff8129d7f5: __update_field_vars (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __update_field_vars(struct tracing_map_elt *elt, struct trace_buffer *buffer, struct ring_buffer_event *rbe, void *rec, struct field_var **field_vars, unsigned int n_field_vars, unsigned int field_var_str_start);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff812bb090)
Location: kernel/trace/trace_events_hist.c:3124
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:hist_trigger_elt_update
  - kernel/trace/trace_events_hist.c:save_track_data_vars
```
**Symbols:**

```
ffffffff812bb090-ffffffff812bb1c2: __update_field_vars (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __update_field_vars(struct tracing_map_elt *elt, struct trace_buffer *buffer, struct ring_buffer_event *rbe, void *rec, struct field_var **field_vars, unsigned int n_field_vars, unsigned int field_var_str_start);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff812d76e0)
Location: kernel/trace/trace_events_hist.c:3117
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:hist_trigger_elt_update
  - kernel/trace/trace_events_hist.c:save_track_data_vars
```
**Symbols:**

```
ffffffff812d76e0-ffffffff812d7812: __update_field_vars (STB_LOCAL)
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
In kernel/trace/trace_events_hist.c (ffff800010243e50)
Location: kernel/trace/trace_events_hist.c:3458
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger
  - kernel/trace/trace_events_hist.c:save_track_data_vars
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
In kernel/trace/trace_events_hist.c (c0000000002d6f30)
Location: kernel/trace/trace_events_hist.c:3458
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger
  - kernel/trace/trace_events_hist.c:save_track_data_vars
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
In kernel/trace/trace_events_hist.c (ffffffff811bc8ca)
Location: kernel/trace/trace_events_hist.c:3458
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger
  - kernel/trace/trace_events_hist.c:save_track_data_vars
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
In kernel/trace/trace_events_hist.c (ffffffff811af6aa)
Location: kernel/trace/trace_events_hist.c:3458
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger
  - kernel/trace/trace_events_hist.c:save_track_data_vars
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
In kernel/trace/trace_events_hist.c (ffffffff811ba69a)
Location: kernel/trace/trace_events_hist.c:3458
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger
  - kernel/trace/trace_events_hist.c:save_track_data_vars
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
In kernel/trace/trace_events_hist.c (ffffffff811c873a)
Location: kernel/trace/trace_events_hist.c:3458
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger
  - kernel/trace/trace_events_hist.c:save_track_data_vars
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
