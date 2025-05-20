# Function: <code>create_key_fields</code>

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
In kernel/trace/trace_events_hist.c (ffffffff811732ad)
Location: kernel/trace/trace_events_hist.c:586
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:create_hist_data
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
In kernel/trace/trace_events_hist.c (ffffffff8117eca7)
Location: kernel/trace/trace_events_hist.c:586
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
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
In kernel/trace/trace_events_hist.c (ffffffff8118193d)
Location: kernel/trace/trace_events_hist.c:587
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
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
In kernel/trace/trace_events_hist.c (ffffffff8118f2db)
Location: kernel/trace/trace_events_hist.c:627
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
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
In kernel/trace/trace_events_hist.c (ffffffff811a2668)
Location: kernel/trace/trace_events_hist.c:3993
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
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
In kernel/trace/trace_events_hist.c (ffffffff811b0738)
Location: kernel/trace/trace_events_hist.c:4078
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:create_hist_data
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
In kernel/trace/trace_events_hist.c (ffffffff811bcb5f)
Location: kernel/trace/trace_events_hist.c:4549
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:create_hist_fields
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
In kernel/trace/trace_events_hist.c (ffffffff811c92a2)
Location: kernel/trace/trace_events_hist.c:4667
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:create_hist_fields
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
In kernel/trace/trace_events_hist.c (ffffffff811e685c)
Location: kernel/trace/trace_events_hist.c:3769
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:create_hist_data
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
In kernel/trace/trace_events_hist.c (ffffffff811e417a)
Location: kernel/trace/trace_events_hist.c:3794
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:create_hist_fields
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
In kernel/trace/trace_events_hist.c (ffffffff811e57c6)
Location: kernel/trace/trace_events_hist.c:3862
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:create_hist_data
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int create_key_fields(struct hist_trigger_data *hist_data, struct trace_event_file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff81215690)
Location: kernel/trace/trace_events_hist.c:3957
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:create_hist_data
```
**Symbols:**

```
ffffffff81215690-ffffffff81215979: create_key_fields (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int create_key_fields(struct hist_trigger_data *hist_data, struct trace_event_file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff81252b10)
Location: kernel/trace/trace_events_hist.c:4334
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:create_hist_data
```
**Symbols:**

```
ffffffff81252b10-ffffffff81252eed: create_key_fields (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int create_key_fields(struct hist_trigger_data *hist_data, struct trace_event_file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff812a2090)
Location: kernel/trace/trace_events_hist.c:4466
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:create_hist_data
```
**Symbols:**

```
ffffffff812a2090-ffffffff812a246c: create_key_fields (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int create_key_fields(struct hist_trigger_data *hist_data, struct trace_event_file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff812bfcf0)
Location: kernel/trace/trace_events_hist.c:4543
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:create_hist_data
```
**Symbols:**

```
ffffffff812bfcf0-ffffffff812c009d: create_key_fields (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int create_key_fields(struct hist_trigger_data *hist_data, struct trace_event_file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff812dc310)
Location: kernel/trace/trace_events_hist.c:4536
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_parse
```
**Symbols:**

```
ffffffff812dc310-ffffffff812dc6bd: create_key_fields (STB_LOCAL)
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
In kernel/trace/trace_events_hist.c (ffff8000102485c0)
Location: kernel/trace/trace_events_hist.c:4667
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:create_hist_fields
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
In kernel/trace/trace_events_hist.c (c0000000002e2674)
Location: kernel/trace/trace_events_hist.c:4667
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:create_hist_fields
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
In kernel/trace/trace_events_hist.c (ffffffff811c18c2)
Location: kernel/trace/trace_events_hist.c:4667
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:create_hist_fields
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
In kernel/trace/trace_events_hist.c (ffffffff811b46a2)
Location: kernel/trace/trace_events_hist.c:4667
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:create_hist_fields
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
In kernel/trace/trace_events_hist.c (ffffffff811bf692)
Location: kernel/trace/trace_events_hist.c:4667
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:create_hist_fields
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
In kernel/trace/trace_events_hist.c (ffffffff811cd732)
Location: kernel/trace/trace_events_hist.c:4667
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:create_hist_fields
```
</details>
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
