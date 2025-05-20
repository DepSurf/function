# Function: <code>trace_string</code>

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
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
unsigned int trace_string(struct synth_trace_event *entry, struct synth_event *event, char *str_val, bool is_dynamic, unsigned int data_size, unsigned int *n_u64);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_synth.c (ffffffff811dada0)
Location: kernel/trace/trace_events_synth.c:394
Inline: False
Direct callers:
  - kernel/trace/trace_events_synth.c:synth_event_trace_array
  - kernel/trace/trace_events_synth.c:synth_event_trace
  - kernel/trace/trace_events_synth.c:trace_event_raw_event_synth
```
**Symbols:**

```
ffffffff811dada0-ffffffff811dae28: trace_string (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
unsigned int trace_string(struct synth_trace_event *entry, struct synth_event *event, char *str_val, bool is_dynamic, unsigned int data_size, unsigned int *n_u64);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_synth.c (ffffffff811dc3b0)
Location: kernel/trace/trace_events_synth.c:395
Inline: False
Direct callers:
  - kernel/trace/trace_events_synth.c:synth_event_trace_array
  - kernel/trace/trace_events_synth.c:synth_event_trace
  - kernel/trace/trace_events_synth.c:trace_event_raw_event_synth
```
**Symbols:**

```
ffffffff811dc3b0-ffffffff811dc440: trace_string (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
unsigned int trace_string(struct synth_trace_event *entry, struct synth_event *event, char *str_val, bool is_dynamic, unsigned int data_size, unsigned int *n_u64);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_synth.c (ffffffff8120bb00)
Location: kernel/trace/trace_events_synth.c:395
Inline: False
Direct callers:
  - kernel/trace/trace_events_synth.c:synth_event_trace_array
  - kernel/trace/trace_events_synth.c:synth_event_trace
  - kernel/trace/trace_events_synth.c:trace_event_raw_event_synth
```
**Symbols:**

```
ffffffff8120bb00-ffffffff8120bb90: trace_string (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
unsigned int trace_string(struct synth_trace_event *entry, struct synth_event *event, char *str_val, bool is_dynamic, unsigned int data_size, unsigned int *n_u64);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_synth.c (ffffffff81247ca0)
Location: kernel/trace/trace_events_synth.c:403
Inline: False
Direct callers:
  - kernel/trace/trace_events_synth.c:synth_event_trace_array
  - kernel/trace/trace_events_synth.c:synth_event_trace
  - kernel/trace/trace_events_synth.c:trace_event_raw_event_synth
```
**Symbols:**

```
ffffffff81247ca0-ffffffff81247d54: trace_string (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
unsigned int trace_string(struct synth_trace_event *entry, struct synth_event *event, char *str_val, bool is_dynamic, unsigned int data_size, unsigned int *n_u64);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_synth.c (ffffffff81297e50)
Location: kernel/trace/trace_events_synth.c:405
Inline: False
Direct callers:
  - kernel/trace/trace_events_synth.c:synth_event_trace_array
  - kernel/trace/trace_events_synth.c:synth_event_trace
  - kernel/trace/trace_events_synth.c:trace_event_raw_event_synth
```
**Symbols:**

```
ffffffff81297e50-ffffffff8129812d: trace_string (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
unsigned int trace_string(struct synth_trace_event *entry, struct synth_event *event, char *str_val, bool is_dynamic, unsigned int data_size, unsigned int *n_u64);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_synth.c (ffffffff812b4ec0)
Location: kernel/trace/trace_events_synth.c:430
Inline: False
Direct callers:
  - kernel/trace/trace_events_synth.c:synth_event_trace_array
  - kernel/trace/trace_events_synth.c:synth_event_trace
  - kernel/trace/trace_events_synth.c:trace_event_raw_event_synth
```
**Symbols:**

```
ffffffff812b4ec0-ffffffff812b5113: trace_string (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
unsigned int trace_string(struct synth_trace_event *entry, struct synth_event *event, char *str_val, bool is_dynamic, unsigned int data_size, unsigned int *n_u64);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_synth.c (ffffffff812d1510)
Location: kernel/trace/trace_events_synth.c:430
Inline: False
Direct callers:
  - kernel/trace/trace_events_synth.c:synth_event_trace_array
  - kernel/trace/trace_events_synth.c:synth_event_trace
  - kernel/trace/trace_events_synth.c:trace_event_raw_event_synth
```
**Symbols:**

```
ffffffff812d1510-ffffffff812d1782: trace_string (STB_LOCAL)
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
