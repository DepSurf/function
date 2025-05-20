# Function: <code>__synth_event_add_val</code>

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
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events_synth.c (ffffffff811dec20)
Location: kernel/trace/trace_events_synth.c:1456
Inline: True
Inline callers:
  - kernel/trace/trace_events_synth.c:synth_event_add_val
  - kernel/trace/trace_events_synth.c:synth_event_add_next_val
Direct callers:
  - kernel/trace/trace_events_synth.c:synth_event_add_val
  - kernel/trace/trace_events_synth.c:synth_event_add_next_val
```
**Symbols:**

```
ffffffff811deae0-ffffffff811dec1f: __synth_event_add_val.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events_synth.c (ffffffff811db4b0)
Location: kernel/trace/trace_events_synth.c:1751
Inline: True
Inline callers:
  - kernel/trace/trace_events_synth.c:synth_event_add_val
  - kernel/trace/trace_events_synth.c:synth_event_add_next_val
Direct callers:
  - kernel/trace/trace_events_synth.c:synth_event_add_val
  - kernel/trace/trace_events_synth.c:synth_event_add_next_val
```
**Symbols:**

```
ffffffff811db360-ffffffff811db4a6: __synth_event_add_val.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events_synth.c (ffffffff811dcac0)
Location: kernel/trace/trace_events_synth.c:1853
Inline: True
Inline callers:
  - kernel/trace/trace_events_synth.c:synth_event_add_val
  - kernel/trace/trace_events_synth.c:synth_event_add_next_val
Direct callers:
  - kernel/trace/trace_events_synth.c:synth_event_add_val
  - kernel/trace/trace_events_synth.c:synth_event_add_next_val
```
**Symbols:**

```
ffffffff811dc970-ffffffff811dcab6: __synth_event_add_val.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int __synth_event_add_val(const char *field_name, u64 val, struct synth_event_trace_state *trace_state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events_synth.c (0)
Location: kernel/trace/trace_events_synth.c:1853
Inline: False
Direct callers:
  - kernel/trace/trace_events_synth.c:synth_event_add_val
  - kernel/trace/trace_events_synth.c:synth_event_add_next_val
```
**Symbols:**

```
ffffffff8120be10-ffffffff8120bfba: __synth_event_add_val (STB_LOCAL)
ffffffff81cb6abf-ffffffff81cb6b37: __synth_event_add_val.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int __synth_event_add_val(const char *field_name, u64 val, struct synth_event_trace_state *trace_state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events_synth.c (0)
Location: kernel/trace/trace_events_synth.c:1862
Inline: False
Direct callers:
  - kernel/trace/trace_events_synth.c:synth_event_add_val
  - kernel/trace/trace_events_synth.c:synth_event_add_next_val
```
**Symbols:**

```
ffffffff81248210-ffffffff812483c0: __synth_event_add_val (STB_LOCAL)
ffffffff81e67b10-ffffffff81e67b88: __synth_event_add_val.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int __synth_event_add_val(const char *field_name, u64 val, struct synth_event_trace_state *trace_state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events_synth.c (0)
Location: kernel/trace/trace_events_synth.c:1870
Inline: False
Direct callers:
  - kernel/trace/trace_events_synth.c:synth_event_add_val
  - kernel/trace/trace_events_synth.c:synth_event_add_next_val
```
**Symbols:**

```
ffffffff81296890-ffffffff81296a40: __synth_event_add_val (STB_LOCAL)
ffffffff8205e554-ffffffff8205e5cc: __synth_event_add_val.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int __synth_event_add_val(const char *field_name, u64 val, struct synth_event_trace_state *trace_state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events_synth.c (0)
Location: kernel/trace/trace_events_synth.c:1943
Inline: False
Direct callers:
  - kernel/trace/trace_events_synth.c:synth_event_add_val
  - kernel/trace/trace_events_synth.c:synth_event_add_next_val
```
**Symbols:**

```
ffffffff812b3840-ffffffff812b39f0: __synth_event_add_val (STB_LOCAL)
ffffffff820dd009-ffffffff820dd081: __synth_event_add_val.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int __synth_event_add_val(const char *field_name, u64 val, struct synth_event_trace_state *trace_state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events_synth.c (0)
Location: kernel/trace/trace_events_synth.c:1944
Inline: False
Direct callers:
  - kernel/trace/trace_events_synth.c:synth_event_add_val
  - kernel/trace/trace_events_synth.c:synth_event_add_next_val
```
**Symbols:**

```
ffffffff812cfdf0-ffffffff812cffa0: __synth_event_add_val (STB_LOCAL)
ffffffff821b8e0d-ffffffff821b8e85: __synth_event_add_val.cold (STB_LOCAL)
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
