# Function: <code>perf_uprobe_init</code>

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
<summary>In <code>4.18</code>: ✅</summary>

```c
int perf_uprobe_init(struct perf_event *p_event, bool is_retprobe);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_event_perf.c (ffffffff81197c40)
Location: kernel/trace/trace_event_perf.c:292
Inline: False
Direct callers:
  - kernel/events/core.c:perf_uprobe_event_init
```
**Symbols:**

```
ffffffff81197c40-ffffffff81197d35: perf_uprobe_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int perf_uprobe_init(struct perf_event *p_event, long unsigned int ref_ctr_offset, bool is_retprobe);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_event_perf.c (ffffffff811a5db0)
Location: kernel/trace/trace_event_perf.c:293
Inline: False
Direct callers:
  - kernel/events/core.c:perf_uprobe_event_init
```
**Symbols:**

```
ffffffff811a5db0-ffffffff811a5e8f: perf_uprobe_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int perf_uprobe_init(struct perf_event *p_event, long unsigned int ref_ctr_offset, bool is_retprobe);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_event_perf.c (ffffffff811b3cc0)
Location: kernel/trace/trace_event_perf.c:293
Inline: False
Direct callers:
  - kernel/events/core.c:perf_uprobe_event_init
```
**Symbols:**

```
ffffffff811b3cc0-ffffffff811b3d8b: perf_uprobe_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int perf_uprobe_init(struct perf_event *p_event, long unsigned int ref_ctr_offset, bool is_retprobe);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_event_perf.c (ffffffff811bf2f0)
Location: kernel/trace/trace_event_perf.c:297
Inline: False
Direct callers:
  - kernel/events/core.c:perf_uprobe_event_init
```
**Symbols:**

```
ffffffff811bf2f0-ffffffff811bf3bb: perf_uprobe_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int perf_uprobe_init(struct perf_event *p_event, long unsigned int ref_ctr_offset, bool is_retprobe);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_event_perf.c (ffffffff811d8c00)
Location: kernel/trace/trace_event_perf.c:302
Inline: False
Direct callers:
  - kernel/events/core.c:perf_uprobe_event_init
```
**Symbols:**

```
ffffffff811d8c00-ffffffff811d8ccb: perf_uprobe_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int perf_uprobe_init(struct perf_event *p_event, long unsigned int ref_ctr_offset, bool is_retprobe);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_event_perf.c (ffffffff811d5d20)
Location: kernel/trace/trace_event_perf.c:302
Inline: False
Direct callers:
  - kernel/events/core.c:perf_uprobe_event_init
```
**Symbols:**

```
ffffffff811d5d20-ffffffff811d5deb: perf_uprobe_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int perf_uprobe_init(struct perf_event *p_event, long unsigned int ref_ctr_offset, bool is_retprobe);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_event_perf.c (ffffffff811d7360)
Location: kernel/trace/trace_event_perf.c:302
Inline: False
Direct callers:
  - kernel/events/core.c:perf_uprobe_event_init
```
**Symbols:**

```
ffffffff811d7360-ffffffff811d742b: perf_uprobe_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int perf_uprobe_init(struct perf_event *p_event, long unsigned int ref_ctr_offset, bool is_retprobe);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_event_perf.c (ffffffff81204320)
Location: kernel/trace/trace_event_perf.c:302
Inline: False
Direct callers:
  - kernel/events/core.c:perf_uprobe_event_init
```
**Symbols:**

```
ffffffff81204320-ffffffff812043eb: perf_uprobe_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int perf_uprobe_init(struct perf_event *p_event, long unsigned int ref_ctr_offset, bool is_retprobe);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_event_perf.c (ffffffff8123f780)
Location: kernel/trace/trace_event_perf.c:302
Inline: False
Direct callers:
  - kernel/events/core.c:perf_uprobe_event_init
```
**Symbols:**

```
ffffffff8123f780-ffffffff8123f864: perf_uprobe_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int perf_uprobe_init(struct perf_event *p_event, long unsigned int ref_ctr_offset, bool is_retprobe);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_event_perf.c (ffffffff8128d240)
Location: kernel/trace/trace_event_perf.c:298
Inline: False
Direct callers:
  - kernel/events/core.c:perf_uprobe_event_init
```
**Symbols:**

```
ffffffff8128d240-ffffffff8128d324: perf_uprobe_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int perf_uprobe_init(struct perf_event *p_event, long unsigned int ref_ctr_offset, bool is_retprobe);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_event_perf.c (ffffffff812aa1c0)
Location: kernel/trace/trace_event_perf.c:298
Inline: False
Direct callers:
  - kernel/events/core.c:perf_uprobe_event_init
```
**Symbols:**

```
ffffffff812aa1c0-ffffffff812aa2a5: perf_uprobe_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int perf_uprobe_init(struct perf_event *p_event, long unsigned int ref_ctr_offset, bool is_retprobe);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_event_perf.c (ffffffff812c5ed0)
Location: kernel/trace/trace_event_perf.c:298
Inline: False
Direct callers:
  - kernel/events/core.c:perf_uprobe_event_init
```
**Symbols:**

```
ffffffff812c5ed0-ffffffff812c5fb5: perf_uprobe_init (STB_GLOBAL)
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
int perf_uprobe_init(struct perf_event *p_event, long unsigned int ref_ctr_offset, bool is_retprobe);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_event_perf.c (ffff80001023e948)
Location: kernel/trace/trace_event_perf.c:297
Inline: False
Direct callers:
  - kernel/events/core.c:perf_uprobe_event_init
```
**Symbols:**

```
ffff80001023e948-ffff80001023ea28: perf_uprobe_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int perf_uprobe_init(struct perf_event *p_event, long unsigned int ref_ctr_offset, bool is_retprobe);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_event_perf.c (c0479f98)
Location: kernel/trace/trace_event_perf.c:297
Inline: False
Direct callers:
  - kernel/events/core.c:perf_uprobe_event_init
```
**Symbols:**

```
c0479f98-c047a064: perf_uprobe_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int perf_uprobe_init(struct perf_event *p_event, long unsigned int ref_ctr_offset, bool is_retprobe);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_event_perf.c (c0000000002ce760)
Location: kernel/trace/trace_event_perf.c:297
Inline: False
Direct callers:
  - kernel/events/core.c:perf_uprobe_event_init
```
**Symbols:**

```
c0000000002ce760-c0000000002ce8a8: perf_uprobe_init (STB_GLOBAL)
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
<summary>In <code>aws</code>: ✅</summary>

```c
int perf_uprobe_init(struct perf_event *p_event, long unsigned int ref_ctr_offset, bool is_retprobe);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_event_perf.c (ffffffff811b7910)
Location: kernel/trace/trace_event_perf.c:297
Inline: False
Direct callers:
  - kernel/events/core.c:perf_uprobe_event_init
```
**Symbols:**

```
ffffffff811b7910-ffffffff811b79db: perf_uprobe_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int perf_uprobe_init(struct perf_event *p_event, long unsigned int ref_ctr_offset, bool is_retprobe);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_event_perf.c (ffffffff811aa6f0)
Location: kernel/trace/trace_event_perf.c:297
Inline: False
Direct callers:
  - kernel/events/core.c:perf_uprobe_event_init
```
**Symbols:**

```
ffffffff811aa6f0-ffffffff811aa7bb: perf_uprobe_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int perf_uprobe_init(struct perf_event *p_event, long unsigned int ref_ctr_offset, bool is_retprobe);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_event_perf.c (ffffffff811b56e0)
Location: kernel/trace/trace_event_perf.c:297
Inline: False
Direct callers:
  - kernel/events/core.c:perf_uprobe_event_init
```
**Symbols:**

```
ffffffff811b56e0-ffffffff811b57ab: perf_uprobe_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int perf_uprobe_init(struct perf_event *p_event, long unsigned int ref_ctr_offset, bool is_retprobe);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_event_perf.c (ffffffff811c3780)
Location: kernel/trace/trace_event_perf.c:297
Inline: False
Direct callers:
  - kernel/events/core.c:perf_uprobe_event_init
```
**Symbols:**

```
ffffffff811c3780-ffffffff811c384b: perf_uprobe_init (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>long unsigned int ref_ctr_offset</code>
</li>
<li>
<b>Param reordered. </b>
<code>p_event, is_retprobe</code> ➡️ <code>p_event, ref_ctr_offset, is_retprobe</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
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
