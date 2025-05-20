# Function: <code>tracing_set_filter_buffering</code>

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
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int tracing_set_filter_buffering(struct trace_array *tr, bool set);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811c3690)
Location: kernel/trace/trace.c:7259
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:hist_unregister_trigger
  - kernel/trace/trace_events_hist.c:hist_register_trigger
```
**Symbols:**

```
ffffffff811c3690-ffffffff811c36ee: tracing_set_filter_buffering (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int tracing_set_filter_buffering(struct trace_array *tr, bool set);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811ee840)
Location: kernel/trace/trace.c:7337
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:hist_unregister_trigger
  - kernel/trace/trace_events_hist.c:hist_register_trigger
```
**Symbols:**

```
ffffffff811ee840-ffffffff811ee89e: tracing_set_filter_buffering (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int tracing_set_filter_buffering(struct trace_array *tr, bool set);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff81226ba0)
Location: kernel/trace/trace.c:7342
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:hist_unregister_trigger
  - kernel/trace/trace_events_hist.c:hist_register_trigger
```
**Symbols:**

```
ffffffff81226ba0-ffffffff81226c02: tracing_set_filter_buffering (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int tracing_set_filter_buffering(struct trace_array *tr, bool set);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff81271e40)
Location: kernel/trace/trace.c:7393
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:hist_unregister_trigger
  - kernel/trace/trace_events_hist.c:hist_register_trigger
```
**Symbols:**

```
ffffffff81271e40-ffffffff81271ea2: tracing_set_filter_buffering (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int tracing_set_filter_buffering(struct trace_array *tr, bool set);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff81289150)
Location: kernel/trace/trace.c:7549
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:hist_unregister_trigger
  - kernel/trace/trace_events_hist.c:hist_register_trigger
```
**Symbols:**

```
ffffffff81289150-ffffffff812891b0: tracing_set_filter_buffering (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int tracing_set_filter_buffering(struct trace_array *tr, bool set);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff812a44a0)
Location: kernel/trace/trace.c:7582
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:hist_unregister_trigger
  - kernel/trace/trace_events_hist.c:hist_register_trigger
```
**Symbols:**

```
ffffffff812a44a0-ffffffff812a4500: tracing_set_filter_buffering (STB_GLOBAL)
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
