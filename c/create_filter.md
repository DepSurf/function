# Function: <code>create_filter</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int create_filter(struct trace_event_call *call, char *filter_str, bool set_str, struct event_filter **filterp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_filter.c (ffffffff81164cb0)
Location: kernel/trace/trace_events_filter.c:1968
Inline: False
Direct callers:
  - kernel/trace/trace_events_filter.c:create_event_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
  - kernel/trace/trace_events_filter.c:ftrace_profile_set_filter
```
**Symbols:**

```
ffffffff81164cb0-ffffffff81164d6c: create_filter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int create_filter(struct trace_event_call *call, char *filter_str, bool set_str, struct event_filter **filterp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_filter.c (ffffffff8116f4d0)
Location: kernel/trace/trace_events_filter.c:1915
Inline: False
Direct callers:
  - kernel/trace/trace_events_filter.c:ftrace_profile_set_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
  - kernel/trace/trace_events_filter.c:create_event_filter
```
**Symbols:**

```
ffffffff8116f4d0-ffffffff8116f58c: create_filter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int create_filter(struct trace_event_call *call, char *filter_str, bool set_str, struct event_filter **filterp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_filter.c (ffffffff8117acb0)
Location: kernel/trace/trace_events_filter.c:1948
Inline: False
Direct callers:
  - kernel/trace/trace_events_filter.c:ftrace_profile_set_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
  - kernel/trace/trace_events_filter.c:create_event_filter
```
**Symbols:**

```
ffffffff8117acb0-ffffffff8117ad6c: create_filter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int create_filter(struct trace_event_call *call, char *filter_str, bool set_str, struct event_filter **filterp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_filter.c (ffffffff8117d920)
Location: kernel/trace/trace_events_filter.c:1948
Inline: False
Direct callers:
  - kernel/trace/trace_events_filter.c:ftrace_profile_set_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
  - kernel/trace/trace_events_filter.c:create_event_filter
```
**Symbols:**

```
ffffffff8117d920-ffffffff8117da0b: create_filter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int create_filter(struct trace_event_call *call, char *filter_str, bool set_str, struct event_filter **filterp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_filter.c (ffffffff8118b1b0)
Location: kernel/trace/trace_events_filter.c:1947
Inline: False
Direct callers:
  - kernel/trace/trace_events_filter.c:ftrace_profile_set_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
  - kernel/trace/trace_events_filter.c:create_event_filter
```
**Symbols:**

```
ffffffff8118b1b0-ffffffff8118b29b: create_filter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int create_filter(struct trace_event_call *call, char *filter_string, bool set_str, struct event_filter **filterp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_filter.c (ffffffff81199b30)
Location: kernel/trace/trace_events_filter.c:1715
Inline: False
Direct callers:
  - kernel/trace/trace_events_filter.c:ftrace_profile_set_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
  - kernel/trace/trace_events_filter.c:create_event_filter
```
**Symbols:**

```
ffffffff81199b30-ffffffff81199be0: create_filter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int create_filter(struct trace_event_call *call, char *filter_string, bool set_str, struct event_filter **filterp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_filter.c (ffffffff811a7cb0)
Location: kernel/trace/trace_events_filter.c:1708
Inline: False
Direct callers:
  - kernel/trace/trace_events_filter.c:ftrace_profile_set_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
  - kernel/trace/trace_events_filter.c:create_event_filter
```
**Symbols:**

```
ffffffff811a7cb0-ffffffff811a7d7c: create_filter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int create_filter(struct trace_array *tr, struct trace_event_call *call, char *filter_string, bool set_str, struct event_filter **filterp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events_filter.c (0)
Location: kernel/trace/trace_events_filter.c:1730
Inline: False
Direct callers:
  - kernel/trace/trace_events_filter.c:ftrace_profile_set_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
  - kernel/trace/trace_events_filter.c:create_event_filter
```
**Symbols:**

```
ffffffff811b5b80-ffffffff811b5c4b: create_filter (STB_LOCAL)
ffffffff811b674f-ffffffff811b6769: create_filter.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int create_filter(struct trace_array *tr, struct trace_event_call *call, char *filter_string, bool set_str, struct event_filter **filterp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_filter.c (ffffffff811c1200)
Location: kernel/trace/trace_events_filter.c:1732
Inline: False
Direct callers:
  - kernel/trace/trace_events_filter.c:ftrace_profile_set_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
  - kernel/trace/trace_events_filter.c:create_event_filter
```
**Symbols:**

```
ffffffff811c1200-ffffffff811c12d9: create_filter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int create_filter(struct trace_array *tr, struct trace_event_call *call, char *filter_string, bool set_str, struct event_filter **filterp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_filter.c (ffffffff811dae40)
Location: kernel/trace/trace_events_filter.c:1732
Inline: False
Direct callers:
  - kernel/trace/trace_events_filter.c:ftrace_profile_set_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
  - kernel/trace/trace_events_filter.c:create_event_filter
```
**Symbols:**

```
ffffffff811dae40-ffffffff811daf0d: create_filter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int create_filter(struct trace_array *tr, struct trace_event_call *call, char *filter_string, bool set_str, struct event_filter **filterp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_filter.c (ffffffff811d7f70)
Location: kernel/trace/trace_events_filter.c:1711
Inline: False
Direct callers:
  - kernel/trace/trace_events_filter.c:ftrace_profile_set_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
  - kernel/trace/trace_events_filter.c:create_event_filter
```
**Symbols:**

```
ffffffff811d7f70-ffffffff811d803d: create_filter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int create_filter(struct trace_array *tr, struct trace_event_call *call, char *filter_string, bool set_str, struct event_filter **filterp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_filter.c (ffffffff811d9410)
Location: kernel/trace/trace_events_filter.c:1712
Inline: False
Direct callers:
  - kernel/trace/trace_events_filter.c:ftrace_profile_set_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
  - kernel/trace/trace_events_filter.c:create_event_filter
```
**Symbols:**

```
ffffffff811d9410-ffffffff811d94df: create_filter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int create_filter(struct trace_array *tr, struct trace_event_call *call, char *filter_string, bool set_str, struct event_filter **filterp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_filter.c (ffffffff81206c93)
Location: kernel/trace/trace_events_filter.c:1805
Inline: True
Inline callers:
  - kernel/trace/trace_events_filter.c:create_event_filter
Direct callers:
  - kernel/trace/trace_events_filter.c:ftrace_profile_set_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
```
**Symbols:**

```
ffffffff81206720-ffffffff812067ef: create_filter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int create_filter(struct trace_array *tr, struct trace_event_call *call, char *filter_string, bool set_str, struct event_filter **filterp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_filter.c (ffffffff812425a3)
Location: kernel/trace/trace_events_filter.c:1833
Inline: True
Inline callers:
  - kernel/trace/trace_events_filter.c:create_event_filter
Direct callers:
  - kernel/trace/trace_events_filter.c:ftrace_profile_set_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
```
**Symbols:**

```
ffffffff81241f90-ffffffff8124207c: create_filter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int create_filter(struct trace_array *tr, struct trace_event_call *call, char *filter_string, bool set_str, struct event_filter **filterp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_filter.c (ffffffff8128ffb3)
Location: kernel/trace/trace_events_filter.c:1930
Inline: True
Inline callers:
  - kernel/trace/trace_events_filter.c:create_event_filter
Direct callers:
  - kernel/trace/trace_events_filter.c:ftrace_profile_set_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
```
**Symbols:**

```
ffffffff8128f940-ffffffff8128fa2c: create_filter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int create_filter(struct trace_array *tr, struct trace_event_call *call, char *filter_string, bool set_str, struct event_filter **filterp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_filter.c (ffffffff812ad170)
Location: kernel/trace/trace_events_filter.c:2021
Inline: True
Inline callers:
  - kernel/trace/trace_events_filter.c:create_event_filter
Direct callers:
  - kernel/trace/trace_events_filter.c:ftrace_profile_set_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
```
**Symbols:**

```
ffffffff812acb00-ffffffff812acbec: create_filter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int create_filter(struct trace_array *tr, struct trace_event_call *call, char *filter_string, bool set_str, struct event_filter **filterp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_filter.c (ffffffff812c9680)
Location: kernel/trace/trace_events_filter.c:2282
Inline: True
Inline callers:
  - kernel/trace/trace_events_filter.c:create_event_filter
Direct callers:
  - kernel/trace/trace_events_filter.c:ftrace_profile_set_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
```
**Symbols:**

```
ffffffff812c8f90-ffffffff812c907c: create_filter (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int create_filter(struct trace_array *tr, struct trace_event_call *call, char *filter_string, bool set_str, struct event_filter **filterp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_filter.c (ffff8000102408b8)
Location: kernel/trace/trace_events_filter.c:1732
Inline: False
Direct callers:
  - kernel/trace/trace_events_filter.c:ftrace_profile_set_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
  - kernel/trace/trace_events_filter.c:create_event_filter
```
**Symbols:**

```
ffff8000102408b8-ffff8000102409a8: create_filter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int create_filter(struct trace_array *tr, struct trace_event_call *call, char *filter_string, bool set_str, struct event_filter **filterp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_filter.c (c047c2e0)
Location: kernel/trace/trace_events_filter.c:1732
Inline: False
Direct callers:
  - kernel/trace/trace_events_filter.c:ftrace_profile_set_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
  - kernel/trace/trace_events_filter.c:create_event_filter
```
**Symbols:**

```
c047c2e0-c047c3dc: create_filter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int create_filter(struct trace_array *tr, struct trace_event_call *call, char *filter_string, bool set_str, struct event_filter **filterp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_filter.c (c0000000002d1550)
Location: kernel/trace/trace_events_filter.c:1732
Inline: False
Direct callers:
  - kernel/trace/trace_events_filter.c:ftrace_profile_set_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
  - kernel/trace/trace_events_filter.c:create_event_filter
```
**Symbols:**

```
c0000000002d1550-c0000000002d1698: create_filter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int create_filter(struct trace_array *tr, struct trace_event_call *call, char *filter_string, bool set_str, struct event_filter **filterp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_filter.c (ffffffe000195ad8)
Location: kernel/trace/trace_events_filter.c:1732
Inline: False
Direct callers:
  - kernel/trace/trace_events_filter.c:ftrace_profile_set_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
  - kernel/trace/trace_events_filter.c:create_event_filter
```
**Symbols:**

```
ffffffe000195ad8-ffffffe000195b78: create_filter (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int create_filter(struct trace_array *tr, struct trace_event_call *call, char *filter_string, bool set_str, struct event_filter **filterp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_filter.c (ffffffff811b9820)
Location: kernel/trace/trace_events_filter.c:1732
Inline: False
Direct callers:
  - kernel/trace/trace_events_filter.c:ftrace_profile_set_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
  - kernel/trace/trace_events_filter.c:create_event_filter
```
**Symbols:**

```
ffffffff811b9820-ffffffff811b98f9: create_filter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int create_filter(struct trace_array *tr, struct trace_event_call *call, char *filter_string, bool set_str, struct event_filter **filterp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_filter.c (ffffffff811ac600)
Location: kernel/trace/trace_events_filter.c:1732
Inline: False
Direct callers:
  - kernel/trace/trace_events_filter.c:ftrace_profile_set_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
  - kernel/trace/trace_events_filter.c:create_event_filter
```
**Symbols:**

```
ffffffff811ac600-ffffffff811ac6d9: create_filter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int create_filter(struct trace_array *tr, struct trace_event_call *call, char *filter_string, bool set_str, struct event_filter **filterp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_filter.c (ffffffff811b75f0)
Location: kernel/trace/trace_events_filter.c:1732
Inline: False
Direct callers:
  - kernel/trace/trace_events_filter.c:ftrace_profile_set_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
  - kernel/trace/trace_events_filter.c:create_event_filter
```
**Symbols:**

```
ffffffff811b75f0-ffffffff811b76c9: create_filter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int create_filter(struct trace_array *tr, struct trace_event_call *call, char *filter_string, bool set_str, struct event_filter **filterp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_filter.c (ffffffff811c5690)
Location: kernel/trace/trace_events_filter.c:1732
Inline: False
Direct callers:
  - kernel/trace/trace_events_filter.c:ftrace_profile_set_filter
  - kernel/trace/trace_events_filter.c:apply_event_filter
  - kernel/trace/trace_events_filter.c:create_event_filter
```
**Symbols:**

```
ffffffff811c5690-ffffffff811c5769: create_filter (STB_LOCAL)
```
</details>
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
<li>
<details>
<summary>Changed between <code>4.15</code> and <code>4.18</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>char *filter_string</code>
</li>
<li>
<b>Param removed. </b>
<code>char *filter_str</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.0</code> and <code>5.3</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct trace_array *tr</code>
</li>
<li>
<b>Param reordered. </b>
<code>call, filter_string, set_str, filterp</code> ➡️ <code>tr, call, filter_string, set_str, filterp</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
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
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
