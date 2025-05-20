# Function: <code>replace_preds</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int replace_preds(struct trace_event_call *call, struct event_filter *filter, struct filter_parse_state *ps, bool dry_run);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_filter.c (ffffffff81163e30)
Location: kernel/trace/trace_events_filter.c:1618
Inline: False
Direct callers:
  - kernel/trace/trace_events_filter.c:create_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
```
**Symbols:**

```
ffffffff81163e30-ffffffff81164787: replace_preds (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int replace_preds(struct trace_event_call *call, struct event_filter *filter, struct filter_parse_state *ps, bool dry_run);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_filter.c (ffffffff8116eb60)
Location: kernel/trace/trace_events_filter.c:1591
Inline: False
Direct callers:
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:create_filter
```
**Symbols:**

```
ffffffff8116eb60-ffffffff8116f4c2: replace_preds (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int replace_preds(struct trace_event_call *call, struct event_filter *filter, struct filter_parse_state *ps, bool dry_run);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_filter.c (ffffffff8117a300)
Location: kernel/trace/trace_events_filter.c:1624
Inline: False
Direct callers:
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:create_filter
```
**Symbols:**

```
ffffffff8117a300-ffffffff8117aca9: replace_preds (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int replace_preds(struct trace_event_call *call, struct event_filter *filter, struct filter_parse_state *ps, bool dry_run);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_filter.c (ffffffff8117cfa0)
Location: kernel/trace/trace_events_filter.c:1624
Inline: False
Direct callers:
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:create_filter
```
**Symbols:**

```
ffffffff8117cfa0-ffffffff8117d919: replace_preds (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int replace_preds(struct trace_event_call *call, struct event_filter *filter, struct filter_parse_state *ps, bool dry_run);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_filter.c (ffffffff8118a830)
Location: kernel/trace/trace_events_filter.c:1623
Inline: False
Direct callers:
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:create_filter
```
**Symbols:**

```
ffffffff8118a830-ffffffff8118b1a9: replace_preds (STB_LOCAL)
```
</details>
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
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
</ul>
