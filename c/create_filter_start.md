# Function: <code>create_filter_start</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events_filter.c (ffffffff81164790)
Location: kernel/trace/trace_events_filter.c:1909
Inline: True
Direct callers:
  - kernel/trace/trace_events_filter.c:create_filter
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
```
**Symbols:**

```
ffffffff81164790-ffffffff81164cac: create_filter_start.constprop.27 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events_filter.c (ffffffff8116e5f0)
Location: kernel/trace/trace_events_filter.c:1856
Inline: True
Direct callers:
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:create_filter
```
**Symbols:**

```
ffffffff8116e5f0-ffffffff8116eb5b: create_filter_start.constprop.28 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events_filter.c (ffffffff81179b90)
Location: kernel/trace/trace_events_filter.c:1889
Inline: True
Direct callers:
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:create_filter
```
**Symbols:**

```
ffffffff81179b90-ffffffff8117a0f4: create_filter_start.constprop.30 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events_filter.c (ffffffff8117c6a0)
Location: kernel/trace/trace_events_filter.c:1889
Inline: True
Direct callers:
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:create_filter
```
**Symbols:**

```
ffffffff8117c6a0-ffffffff8117cc0f: create_filter_start.constprop.32 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events_filter.c (ffffffff81189f30)
Location: kernel/trace/trace_events_filter.c:1888
Inline: True
Direct callers:
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:create_filter
```
**Symbols:**

```
ffffffff81189f30-ffffffff8118a49f: create_filter_start.constprop.32 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int create_filter_start(char *filter_string, bool set_str, struct filter_parse_error **pse, struct event_filter **filterp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_filter.c (ffffffff81198930)
Location: kernel/trace/trace_events_filter.c:1660
Inline: False
Direct callers:
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:create_filter
```
**Symbols:**

```
ffffffff81198930-ffffffff81198a44: create_filter_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int create_filter_start(char *filter_string, bool set_str, struct filter_parse_error **pse, struct event_filter **filterp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_filter.c (ffffffff811a68e0)
Location: kernel/trace/trace_events_filter.c:1653
Inline: False
Direct callers:
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:create_filter
```
**Symbols:**

```
ffffffff811a68e0-ffffffff811a69f4: create_filter_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int create_filter_start(char *filter_string, bool set_str, struct filter_parse_error **pse, struct event_filter **filterp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_filter.c (ffffffff811b4820)
Location: kernel/trace/trace_events_filter.c:1675
Inline: False
Direct callers:
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:create_filter
```
**Symbols:**

```
ffffffff811b4820-ffffffff811b4934: create_filter_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int create_filter_start(char *filter_string, bool set_str, struct filter_parse_error **pse, struct event_filter **filterp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_filter.c (ffffffff811bfe50)
Location: kernel/trace/trace_events_filter.c:1677
Inline: False
Direct callers:
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:create_filter
```
**Symbols:**

```
ffffffff811bfe50-ffffffff811bff64: create_filter_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events_filter.c (ffffffff811d9df0)
Location: kernel/trace/trace_events_filter.c:1677
Inline: True
Direct callers:
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:create_filter
```
**Symbols:**

```
ffffffff811d9df0-ffffffff811d9ee8: create_filter_start.constprop.0 (STB_LOCAL)
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
In kernel/trace/trace_events_filter.c (ffffffff811d6ef0)
Location: kernel/trace/trace_events_filter.c:1656
Inline: True
Direct callers:
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:create_filter
```
**Symbols:**

```
ffffffff811d6ef0-ffffffff811d6fe8: create_filter_start.constprop.0 (STB_LOCAL)
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
In kernel/trace/trace_events_filter.c (ffffffff811d81e0)
Location: kernel/trace/trace_events_filter.c:1656
Inline: True
Direct callers:
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:create_filter
```
**Symbols:**

```
ffffffff811d81e0-ffffffff811d82d8: create_filter_start.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events_filter.c (ffffffff81205260)
Location: kernel/trace/trace_events_filter.c:1749
Inline: True
Direct callers:
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:create_event_filter
```
**Symbols:**

```
ffffffff81205260-ffffffff81205358: create_filter_start.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events_filter.c (ffffffff81240930)
Location: kernel/trace/trace_events_filter.c:1777
Inline: True
Direct callers:
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:create_event_filter
```
**Symbols:**

```
ffffffff81240930-ffffffff81240a3d: create_filter_start.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events_filter.c (ffffffff8128e3b0)
Location: kernel/trace/trace_events_filter.c:1874
Inline: True
Direct callers:
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:create_event_filter
```
**Symbols:**

```
ffffffff8128e3b0-ffffffff8128e4bd: create_filter_start.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events_filter.c (ffffffff812ab300)
Location: kernel/trace/trace_events_filter.c:1965
Inline: True
Direct callers:
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:create_event_filter
```
**Symbols:**

```
ffffffff812ab300-ffffffff812ab40d: create_filter_start.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events_filter.c (ffffffff812c6950)
Location: kernel/trace/trace_events_filter.c:2226
Inline: True
Direct callers:
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:create_event_filter
```
**Symbols:**

```
ffffffff812c6950-ffffffff812c6b15: create_filter_start.constprop.0 (STB_LOCAL)
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
int create_filter_start(char *filter_string, bool set_str, struct filter_parse_error **pse, struct event_filter **filterp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_filter.c (ffff80001023f418)
Location: kernel/trace/trace_events_filter.c:1677
Inline: False
Direct callers:
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:create_filter
```
**Symbols:**

```
ffff80001023f418-ffff80001023f554: create_filter_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int create_filter_start(char *filter_string, bool set_str, struct filter_parse_error **pse, struct event_filter **filterp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_filter.c (c047aec0)
Location: kernel/trace/trace_events_filter.c:1677
Inline: False
Direct callers:
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:create_filter
```
**Symbols:**

```
c047aec0-c047b00c: create_filter_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int create_filter_start(char *filter_string, bool set_str, struct filter_parse_error **pse, struct event_filter **filterp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_filter.c (c0000000002cfcd0)
Location: kernel/trace/trace_events_filter.c:1677
Inline: False
Direct callers:
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:create_filter
```
**Symbols:**

```
c0000000002cfcd0-c0000000002cfe64: create_filter_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int create_filter_start(char *filter_string, bool set_str, struct filter_parse_error **pse, struct event_filter **filterp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_filter.c (ffffffe000194a06)
Location: kernel/trace/trace_events_filter.c:1677
Inline: False
Direct callers:
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:create_filter
```
**Symbols:**

```
ffffffe000194a06-ffffffe000194aea: create_filter_start (STB_LOCAL)
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
int create_filter_start(char *filter_string, bool set_str, struct filter_parse_error **pse, struct event_filter **filterp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_filter.c (ffffffff811b8470)
Location: kernel/trace/trace_events_filter.c:1677
Inline: False
Direct callers:
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:create_filter
```
**Symbols:**

```
ffffffff811b8470-ffffffff811b8584: create_filter_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int create_filter_start(char *filter_string, bool set_str, struct filter_parse_error **pse, struct event_filter **filterp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_filter.c (ffffffff811ab250)
Location: kernel/trace/trace_events_filter.c:1677
Inline: False
Direct callers:
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:create_filter
```
**Symbols:**

```
ffffffff811ab250-ffffffff811ab364: create_filter_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int create_filter_start(char *filter_string, bool set_str, struct filter_parse_error **pse, struct event_filter **filterp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_filter.c (ffffffff811b6240)
Location: kernel/trace/trace_events_filter.c:1677
Inline: False
Direct callers:
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:create_filter
```
**Symbols:**

```
ffffffff811b6240-ffffffff811b6354: create_filter_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int create_filter_start(char *filter_string, bool set_str, struct filter_parse_error **pse, struct event_filter **filterp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_filter.c (ffffffff811c42e0)
Location: kernel/trace/trace_events_filter.c:1677
Inline: False
Direct callers:
  - kernel/trace/trace_events_filter.c:apply_subsystem_event_filter
  - kernel/trace/trace_events_filter.c:create_filter
```
**Symbols:**

```
ffffffff811c42e0-ffffffff811c43f4: create_filter_start (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
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
