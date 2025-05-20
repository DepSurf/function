# Function: <code>track_data_alloc</code>

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
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811bf17f)
Location: kernel/trace/trace_events_hist.c:553
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:action_create
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
In kernel/trace/trace_events_hist.c (ffffffff811ca9cf)
Location: kernel/trace/trace_events_hist.c:560
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:action_create
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct track_data *track_data_alloc(unsigned int key_len, struct action_data *action_data, struct hist_trigger_data *hist_data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811e55b0)
Location: kernel/trace/trace_events_hist.c:498
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:action_create
```
**Symbols:**

```
ffffffff811e55b0-ffffffff811e56b1: track_data_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct track_data *track_data_alloc(unsigned int key_len, struct action_data *action_data, struct hist_trigger_data *hist_data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811e2fe0)
Location: kernel/trace/trace_events_hist.c:501
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:action_create
```
**Symbols:**

```
ffffffff811e2fe0-ffffffff811e30e1: track_data_alloc (STB_LOCAL)
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
In kernel/trace/trace_events_hist.c (ffffffff811e6e1f)
Location: kernel/trace/trace_events_hist.c:514
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:action_create
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
In kernel/trace/trace_events_hist.c (ffffffff8121630a)
Location: kernel/trace/trace_events_hist.c:538
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:action_create
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff81254799)
Location: kernel/trace/trace_events_hist.c:693
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:action_create
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
In kernel/trace/trace_events_hist.c (ffffffff812a3c09)
Location: kernel/trace/trace_events_hist.c:726
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:action_create
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
In kernel/trace/trace_events_hist.c (ffffffff812c1abd)
Location: kernel/trace/trace_events_hist.c:723
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:action_create
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
In kernel/trace/trace_events_hist.c (ffffffff812dde8b)
Location: kernel/trace/trace_events_hist.c:723
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:action_create
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
In kernel/trace/trace_events_hist.c (ffff80001024b570)
Location: kernel/trace/trace_events_hist.c:560
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:action_create
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
In kernel/trace/trace_events_hist.c (c0000000002e4c0c)
Location: kernel/trace/trace_events_hist.c:560
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:action_create
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
In kernel/trace/trace_events_hist.c (ffffffff811c2fef)
Location: kernel/trace/trace_events_hist.c:560
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:action_create
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
In kernel/trace/trace_events_hist.c (ffffffff811b5dcf)
Location: kernel/trace/trace_events_hist.c:560
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:action_create
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
In kernel/trace/trace_events_hist.c (ffffffff811c0dbf)
Location: kernel/trace/trace_events_hist.c:560
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:action_create
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
In kernel/trace/trace_events_hist.c (ffffffff811cee5f)
Location: kernel/trace/trace_events_hist.c:560
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:action_create
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
</ul>
