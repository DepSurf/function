# Function: <code>parse_assignment</code>

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
In kernel/trace/trace_events_hist.c (ffffffff811a13a4)
Location: kernel/trace/trace_events_hist.c:1814
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
In kernel/trace/trace_events_hist.c (ffffffff811b0db5)
Location: kernel/trace/trace_events_hist.c:1898
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:event_hist_trigger_func
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
In kernel/trace/trace_events_hist.c (ffffffff811be72f)
Location: kernel/trace/trace_events_hist.c:2050
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
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
In kernel/trace/trace_events_hist.c (ffffffff811c9f42)
Location: kernel/trace/trace_events_hist.c:2122
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int parse_assignment(struct trace_array *tr, char *str, struct hist_trigger_attrs *attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811e1830)
Location: kernel/trace/trace_events_hist.c:1213
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
```
**Symbols:**

```
ffffffff811e1830-ffffffff811e1a8f: parse_assignment (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int parse_assignment(struct trace_array *tr, char *str, struct hist_trigger_attrs *attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811df450)
Location: kernel/trace/trace_events_hist.c:1216
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
```
**Symbols:**

```
ffffffff811df450-ffffffff811df6af: parse_assignment (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int parse_assignment(struct trace_array *tr, char *str, struct hist_trigger_attrs *attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811e0600)
Location: kernel/trace/trace_events_hist.c:1233
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
```
**Symbols:**

```
ffffffff811e0600-ffffffff811e084f: parse_assignment (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int parse_assignment(struct trace_array *tr, char *str, struct hist_trigger_attrs *attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events_hist.c (0)
Location: kernel/trace/trace_events_hist.c:1258
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
```
**Symbols:**

```
ffffffff8120f420-ffffffff8120f70b: parse_assignment (STB_LOCAL)
ffffffff81cb6e41-ffffffff81cb6e5a: parse_assignment.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int parse_assignment(struct trace_array *tr, char *str, struct hist_trigger_attrs *attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events_hist.c (0)
Location: kernel/trace/trace_events_hist.c:1432
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
```
**Symbols:**

```
ffffffff8124c260-ffffffff8124c53e: parse_assignment (STB_LOCAL)
ffffffff81e67ee0-ffffffff81e67ef8: parse_assignment.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int parse_assignment(struct trace_array *tr, char *str, struct hist_trigger_attrs *attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events_hist.c (0)
Location: kernel/trace/trace_events_hist.c:1461
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
```
**Symbols:**

```
ffffffff8129a5b0-ffffffff8129a88e: parse_assignment (STB_LOCAL)
ffffffff8205e870-ffffffff8205e888: parse_assignment.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int parse_assignment(struct trace_array *tr, char *str, struct hist_trigger_attrs *attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events_hist.c (0)
Location: kernel/trace/trace_events_hist.c:1466
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
```
**Symbols:**

```
ffffffff812b7d20-ffffffff812b7ffe: parse_assignment (STB_LOCAL)
ffffffff820dd3b4-ffffffff820dd3cc: parse_assignment.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int parse_assignment(struct trace_array *tr, char *str, struct hist_trigger_attrs *attrs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events_hist.c (0)
Location: kernel/trace/trace_events_hist.c:1459
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
```
**Symbols:**

```
ffffffff812d4370-ffffffff812d464e: parse_assignment (STB_LOCAL)
ffffffff821b91b8-ffffffff821b91d0: parse_assignment.cold (STB_LOCAL)
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
In kernel/trace/trace_events_hist.c (ffff800010245a88)
Location: kernel/trace/trace_events_hist.c:2122
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
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
In kernel/trace/trace_events_hist.c (c0000000002debec)
Location: kernel/trace/trace_events_hist.c:2122
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
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
In kernel/trace/trace_events_hist.c (ffffffff811c2562)
Location: kernel/trace/trace_events_hist.c:2122
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
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
In kernel/trace/trace_events_hist.c (ffffffff811b5342)
Location: kernel/trace/trace_events_hist.c:2122
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
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
In kernel/trace/trace_events_hist.c (ffffffff811c0332)
Location: kernel/trace/trace_events_hist.c:2122
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
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
In kernel/trace/trace_events_hist.c (ffffffff811ce3d2)
Location: kernel/trace/trace_events_hist.c:2122
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:parse_hist_trigger_attrs
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
