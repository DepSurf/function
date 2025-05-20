# Function: <code>__set_synth_event_print_fmt</code>

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
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff8119f230)
Location: kernel/trace/trace_events_hist.c:693
Inline: True
Direct callers:
  - kernel/trace/trace_events_hist.c:create_synth_event
  - kernel/trace/trace_events_hist.c:create_synth_event
```
**Symbols:**

```
ffffffff8119f230-ffffffff8119f38b: __set_synth_event_print_fmt.isra.30 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811ad0f0)
Location: kernel/trace/trace_events_hist.c:756
Inline: True
Direct callers:
  - kernel/trace/trace_events_hist.c:__create_synth_event
  - kernel/trace/trace_events_hist.c:__create_synth_event
```
**Symbols:**

```
ffffffff811ad0f0-ffffffff811ad24b: __set_synth_event_print_fmt.isra.31 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811bb380)
Location: kernel/trace/trace_events_hist.c:910
Inline: True
Direct callers:
  - kernel/trace/trace_events_hist.c:__create_synth_event
  - kernel/trace/trace_events_hist.c:__create_synth_event
```
**Symbols:**

```
ffffffff811bb380-ffffffff811bb4c4: __set_synth_event_print_fmt.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811c6bd0)
Location: kernel/trace/trace_events_hist.c:980
Inline: True
Direct callers:
  - kernel/trace/trace_events_hist.c:__create_synth_event
  - kernel/trace/trace_events_hist.c:__create_synth_event
```
**Symbols:**

```
ffffffff811c6bd0-ffffffff811c6d14: __set_synth_event_print_fmt.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __set_synth_event_print_fmt(struct synth_event *event, char *buf, int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_synth.c (ffffffff811de3d0)
Location: kernel/trace/trace_events_synth.c:405
Inline: False
Direct callers:
  - kernel/trace/trace_events_synth.c:set_synth_event_print_fmt
  - kernel/trace/trace_events_synth.c:set_synth_event_print_fmt
```
**Symbols:**

```
ffffffff811de3d0-ffffffff811de515: __set_synth_event_print_fmt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __set_synth_event_print_fmt(struct synth_event *event, char *buf, int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_synth.c (ffffffff811db780)
Location: kernel/trace/trace_events_synth.c:520
Inline: False
Direct callers:
  - kernel/trace/trace_events_synth.c:set_synth_event_print_fmt
  - kernel/trace/trace_events_synth.c:set_synth_event_print_fmt
```
**Symbols:**

```
ffffffff811db780-ffffffff811db8ff: __set_synth_event_print_fmt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __set_synth_event_print_fmt(struct synth_event *event, char *buf, int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_synth.c (ffffffff811dcd60)
Location: kernel/trace/trace_events_synth.c:521
Inline: False
Direct callers:
  - kernel/trace/trace_events_synth.c:register_synth_event
  - kernel/trace/trace_events_synth.c:register_synth_event
```
**Symbols:**

```
ffffffff811dcd60-ffffffff811dceb6: __set_synth_event_print_fmt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int __set_synth_event_print_fmt(struct synth_event *event, char *buf, int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events_synth.c (0)
Location: kernel/trace/trace_events_synth.c:521
Inline: False
Direct callers:
  - kernel/trace/trace_events_synth.c:register_synth_event
  - kernel/trace/trace_events_synth.c:register_synth_event
```
**Symbols:**

```
ffffffff8120c550-ffffffff8120c6dd: __set_synth_event_print_fmt (STB_LOCAL)
ffffffff81cb6c27-ffffffff81cb6c7d: __set_synth_event_print_fmt.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int __set_synth_event_print_fmt(struct synth_event *event, char *buf, int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events_synth.c (0)
Location: kernel/trace/trace_events_synth.c:529
Inline: False
Direct callers:
  - kernel/trace/trace_events_synth.c:register_synth_event
  - kernel/trace/trace_events_synth.c:register_synth_event
```
**Symbols:**

```
ffffffff81249390-ffffffff8124956b: __set_synth_event_print_fmt (STB_LOCAL)
ffffffff81e67d86-ffffffff81e67dd0: __set_synth_event_print_fmt.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int __set_synth_event_print_fmt(struct synth_event *event, char *buf, int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events_synth.c (0)
Location: kernel/trace/trace_events_synth.c:540
Inline: False
Direct callers:
  - kernel/trace/trace_events_synth.c:register_synth_event
  - kernel/trace/trace_events_synth.c:register_synth_event
```
**Symbols:**

```
ffffffff81297550-ffffffff8129772b: __set_synth_event_print_fmt (STB_LOCAL)
ffffffff8205e68c-ffffffff8205e6d6: __set_synth_event_print_fmt.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int __set_synth_event_print_fmt(struct synth_event *event, char *buf, int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events_synth.c (0)
Location: kernel/trace/trace_events_synth.c:606
Inline: False
Direct callers:
  - kernel/trace/trace_events_synth.c:register_synth_event
  - kernel/trace/trace_events_synth.c:register_synth_event
```
**Symbols:**

```
ffffffff812b4690-ffffffff812b4894: __set_synth_event_print_fmt (STB_LOCAL)
ffffffff820dd156-ffffffff820dd1c5: __set_synth_event_print_fmt.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int __set_synth_event_print_fmt(struct synth_event *event, char *buf, int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events_synth.c (0)
Location: kernel/trace/trace_events_synth.c:607
Inline: False
Direct callers:
  - kernel/trace/trace_events_synth.c:register_synth_event
  - kernel/trace/trace_events_synth.c:register_synth_event
```
**Symbols:**

```
ffffffff812d0c40-ffffffff812d0e44: __set_synth_event_print_fmt (STB_LOCAL)
ffffffff821b8f5a-ffffffff821b8fc9: __set_synth_event_print_fmt.cold (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffff800010246eb8)
Location: kernel/trace/trace_events_hist.c:980
Inline: True
Direct callers:
  - kernel/trace/trace_events_hist.c:__create_synth_event
  - kernel/trace/trace_events_hist.c:__create_synth_event
```
**Symbols:**

```
ffff800010246eb8-ffff80001024701c: __set_synth_event_print_fmt.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events_hist.c (c0000000002db9c0)
Location: kernel/trace/trace_events_hist.c:980
Inline: True
Direct callers:
  - kernel/trace/trace_events_hist.c:__create_synth_event
  - kernel/trace/trace_events_hist.c:__create_synth_event
```
**Symbols:**

```
c0000000002db9c0-c0000000002dbc0c: __set_synth_event_print_fmt.isra.0 (STB_LOCAL)
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
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811bf1f0)
Location: kernel/trace/trace_events_hist.c:980
Inline: True
Direct callers:
  - kernel/trace/trace_events_hist.c:__create_synth_event
  - kernel/trace/trace_events_hist.c:__create_synth_event
```
**Symbols:**

```
ffffffff811bf1f0-ffffffff811bf334: __set_synth_event_print_fmt.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811b1fd0)
Location: kernel/trace/trace_events_hist.c:980
Inline: True
Direct callers:
  - kernel/trace/trace_events_hist.c:__create_synth_event
  - kernel/trace/trace_events_hist.c:__create_synth_event
```
**Symbols:**

```
ffffffff811b1fd0-ffffffff811b2114: __set_synth_event_print_fmt.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811bcfc0)
Location: kernel/trace/trace_events_hist.c:980
Inline: True
Direct callers:
  - kernel/trace/trace_events_hist.c:__create_synth_event
  - kernel/trace/trace_events_hist.c:__create_synth_event
```
**Symbols:**

```
ffffffff811bcfc0-ffffffff811bd104: __set_synth_event_print_fmt.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811cb060)
Location: kernel/trace/trace_events_hist.c:980
Inline: True
Direct callers:
  - kernel/trace/trace_events_hist.c:__create_synth_event
  - kernel/trace/trace_events_hist.c:__create_synth_event
```
**Symbols:**

```
ffffffff811cb060-ffffffff811cb1a4: __set_synth_event_print_fmt.isra.0 (STB_LOCAL)
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
