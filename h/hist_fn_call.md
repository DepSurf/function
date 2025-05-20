# Function: <code>hist_fn_call</code>

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
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
u64 hist_fn_call(struct hist_field *hist_field, struct tracing_map_elt *elt, struct trace_buffer *buffer, struct ring_buffer_event *rbe, void *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events_hist.c (0)
Location: kernel/trace/trace_events_hist.c:4245
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger
  - kernel/trace/trace_events_hist.c:hist_trigger_elt_update
  - kernel/trace/trace_events_hist.c:hist_trigger_elt_update
  - kernel/trace/trace_events_hist.c:hist_fn_call
  - kernel/trace/trace_events_hist.c:hist_fn_call
  - kernel/trace/trace_events_hist.c:hist_fn_call
  - kernel/trace/trace_events_hist.c:hist_fn_call
  - kernel/trace/trace_events_hist.c:hist_fn_call
  - kernel/trace/trace_events_hist.c:hist_fn_call
  - kernel/trace/trace_events_hist.c:hist_fn_call
  - kernel/trace/trace_events_hist.c:hist_fn_call
  - kernel/trace/trace_events_hist.c:hist_fn_call
  - kernel/trace/trace_events_hist.c:hist_fn_call
  - kernel/trace/trace_events_hist.c:hist_fn_call
  - kernel/trace/trace_events_hist.c:hist_fn_call
  - kernel/trace/trace_events_hist.c:hist_fn_call
  - kernel/trace/trace_events_hist.c:hist_fn_call
  - kernel/trace/trace_events_hist.c:__update_field_vars
  - kernel/trace/trace_events_hist.c:parse_expr
```
**Symbols:**

```
ffffffff8129d1f0-ffffffff8129d6f6: hist_fn_call (STB_LOCAL)
ffffffff8205eaee-ffffffff8205eb5f: hist_fn_call.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
u64 hist_fn_call(struct hist_field *hist_field, struct tracing_map_elt *elt, struct trace_buffer *buffer, struct ring_buffer_event *rbe, void *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events_hist.c (0)
Location: kernel/trace/trace_events_hist.c:4319
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger
  - kernel/trace/trace_events_hist.c:event_hist_trigger
  - kernel/trace/trace_events_hist.c:hist_trigger_elt_update
  - kernel/trace/trace_events_hist.c:hist_trigger_elt_update
  - kernel/trace/trace_events_hist.c:hist_fn_call
  - kernel/trace/trace_events_hist.c:hist_fn_call
  - kernel/trace/trace_events_hist.c:hist_fn_call
  - kernel/trace/trace_events_hist.c:hist_fn_call
  - kernel/trace/trace_events_hist.c:hist_fn_call
  - kernel/trace/trace_events_hist.c:hist_fn_call
  - kernel/trace/trace_events_hist.c:hist_fn_call
  - kernel/trace/trace_events_hist.c:hist_fn_call
  - kernel/trace/trace_events_hist.c:hist_fn_call
  - kernel/trace/trace_events_hist.c:hist_fn_call
  - kernel/trace/trace_events_hist.c:hist_fn_call
  - kernel/trace/trace_events_hist.c:hist_fn_call
  - kernel/trace/trace_events_hist.c:hist_fn_call
  - kernel/trace/trace_events_hist.c:hist_fn_call
  - kernel/trace/trace_events_hist.c:__update_field_vars
  - kernel/trace/trace_events_hist.c:parse_expr
```
**Symbols:**

```
ffffffff812bab80-ffffffff812bb071: hist_fn_call (STB_LOCAL)
ffffffff820dd62b-ffffffff820dd69c: hist_fn_call.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
u64 hist_fn_call(struct hist_field *hist_field, struct tracing_map_elt *elt, struct trace_buffer *buffer, struct ring_buffer_event *rbe, void *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events_hist.c (0)
Location: kernel/trace/trace_events_hist.c:4312
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger
  - kernel/trace/trace_events_hist.c:event_hist_trigger
  - kernel/trace/trace_events_hist.c:hist_trigger_elt_update
  - kernel/trace/trace_events_hist.c:hist_trigger_elt_update
  - kernel/trace/trace_events_hist.c:hist_fn_call
  - kernel/trace/trace_events_hist.c:hist_fn_call
  - kernel/trace/trace_events_hist.c:hist_fn_call
  - kernel/trace/trace_events_hist.c:hist_fn_call
  - kernel/trace/trace_events_hist.c:hist_fn_call
  - kernel/trace/trace_events_hist.c:hist_fn_call
  - kernel/trace/trace_events_hist.c:hist_fn_call
  - kernel/trace/trace_events_hist.c:hist_fn_call
  - kernel/trace/trace_events_hist.c:hist_fn_call
  - kernel/trace/trace_events_hist.c:hist_fn_call
  - kernel/trace/trace_events_hist.c:hist_fn_call
  - kernel/trace/trace_events_hist.c:hist_fn_call
  - kernel/trace/trace_events_hist.c:hist_fn_call
  - kernel/trace/trace_events_hist.c:hist_fn_call
  - kernel/trace/trace_events_hist.c:__update_field_vars
  - kernel/trace/trace_events_hist.c:parse_expr
```
**Symbols:**

```
ffffffff812d71d0-ffffffff812d76c1: hist_fn_call (STB_LOCAL)
ffffffff821b942f-ffffffff821b94a0: hist_fn_call.cold (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
