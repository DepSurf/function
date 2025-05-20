# Function: <code>process_system_preds</code>

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
In kernel/trace/trace_events_filter.c (ffffffff8119a07a)
Location: kernel/trace/trace_events_filter.c:1573
Inline: True
Inline callers:
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
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
In kernel/trace/trace_events_filter.c (ffffffff811a8246)
Location: kernel/trace/trace_events_filter.c:1566
Inline: True
Inline callers:
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
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
In kernel/trace/trace_events_filter.c (ffffffff811b6151)
Location: kernel/trace/trace_events_filter.c:1588
Inline: True
Inline callers:
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
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
In kernel/trace/trace_events_filter.c (ffffffff811c17e1)
Location: kernel/trace/trace_events_filter.c:1590
Inline: True
Inline callers:
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int process_system_preds(struct trace_subsystem_dir *dir, struct trace_array *tr, struct filter_parse_error *pe, char *filter_string);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_filter.c (ffffffff811daf10)
Location: kernel/trace/trace_events_filter.c:1590
Inline: False
Direct callers:
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
```
**Symbols:**

```
ffffffff811daf10-ffffffff811db211: process_system_preds (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int process_system_preds(struct trace_subsystem_dir *dir, struct trace_array *tr, struct filter_parse_error *pe, char *filter_string);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_filter.c (ffffffff811d8040)
Location: kernel/trace/trace_events_filter.c:1569
Inline: False
Direct callers:
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
```
**Symbols:**

```
ffffffff811d8040-ffffffff811d8341: process_system_preds (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int process_system_preds(struct trace_subsystem_dir *dir, struct trace_array *tr, struct filter_parse_error *pe, char *filter_string);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_filter.c (ffffffff811d94e0)
Location: kernel/trace/trace_events_filter.c:1569
Inline: False
Direct callers:
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
```
**Symbols:**

```
ffffffff811d94e0-ffffffff811d97e1: process_system_preds (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int process_system_preds(struct trace_subsystem_dir *dir, struct trace_array *tr, struct filter_parse_error *pe, char *filter_string);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_filter.c (ffffffff812067f0)
Location: kernel/trace/trace_events_filter.c:1662
Inline: False
Direct callers:
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
```
**Symbols:**

```
ffffffff812067f0-ffffffff81206af1: process_system_preds (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int process_system_preds(struct trace_subsystem_dir *dir, struct trace_array *tr, struct filter_parse_error *pe, char *filter_string);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_filter.c (ffffffff81242080)
Location: kernel/trace/trace_events_filter.c:1690
Inline: False
Direct callers:
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
```
**Symbols:**

```
ffffffff81242080-ffffffff8124236c: process_system_preds (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int process_system_preds(struct trace_subsystem_dir *dir, struct trace_array *tr, struct filter_parse_error *pe, char *filter_string);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_filter.c (ffffffff8128fa40)
Location: kernel/trace/trace_events_filter.c:1787
Inline: False
Direct callers:
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
```
**Symbols:**

```
ffffffff8128fa40-ffffffff8128fd2c: process_system_preds (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int process_system_preds(struct trace_subsystem_dir *dir, struct trace_array *tr, struct filter_parse_error *pe, char *filter_string);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_filter.c (ffffffff812acc00)
Location: kernel/trace/trace_events_filter.c:1878
Inline: False
Direct callers:
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
```
**Symbols:**

```
ffffffff812acc00-ffffffff812aceec: process_system_preds (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int process_system_preds(struct trace_subsystem_dir *dir, struct trace_array *tr, struct filter_parse_error *pe, char *filter_string);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_filter.c (ffffffff812c9090)
Location: kernel/trace/trace_events_filter.c:2139
Inline: False
Direct callers:
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
```
**Symbols:**

```
ffffffff812c9090-ffffffff812c93da: process_system_preds (STB_LOCAL)
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
In kernel/trace/trace_events_filter.c (ffff800010240ef0)
Location: kernel/trace/trace_events_filter.c:1590
Inline: True
Inline callers:
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_filter.c (c047c938)
Location: kernel/trace/trace_events_filter.c:1590
Inline: True
Inline callers:
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_filter.c (c0000000002d2008)
Location: kernel/trace/trace_events_filter.c:1590
Inline: True
Inline callers:
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_filter.c (ffffffe000195fdc)
Location: kernel/trace/trace_events_filter.c:1590
Inline: True
Inline callers:
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
```
</details>
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
In kernel/trace/trace_events_filter.c (ffffffff811b9e01)
Location: kernel/trace/trace_events_filter.c:1590
Inline: True
Inline callers:
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
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
In kernel/trace/trace_events_filter.c (ffffffff811acbe1)
Location: kernel/trace/trace_events_filter.c:1590
Inline: True
Inline callers:
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
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
In kernel/trace/trace_events_filter.c (ffffffff811b7bd1)
Location: kernel/trace/trace_events_filter.c:1590
Inline: True
Inline callers:
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
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
In kernel/trace/trace_events_filter.c (ffffffff811c5c71)
Location: kernel/trace/trace_events_filter.c:1590
Inline: True
Inline callers:
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
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
