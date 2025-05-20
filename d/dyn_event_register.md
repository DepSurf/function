# Function: <code>dyn_event_register</code>

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
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int dyn_event_register(struct dyn_event_operations *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_dynevent.c (ffffffff811ba530)
Location: kernel/trace/trace_dynevent.c:21
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:trace_events_hist_init
  - kernel/trace/trace_kprobe.c:init_kprobe_trace
  - kernel/trace/trace_uprobe.c:init_uprobe_trace
```
**Symbols:**

```
ffffffff811ba530-ffffffff811ba5a6: dyn_event_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int dyn_event_register(struct dyn_event_operations *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_dynevent.c (ffffffff811c95c0)
Location: kernel/trace/trace_dynevent.c:21
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:trace_events_hist_init
  - kernel/trace/trace_kprobe.c:init_kprobe_trace
  - kernel/trace/trace_uprobe.c:init_uprobe_trace
```
**Symbols:**

```
ffffffff811c95c0-ffffffff811c963d: dyn_event_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int dyn_event_register(struct dyn_event_operations *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_dynevent.c (ffffffff811d52b0)
Location: kernel/trace/trace_dynevent.c:21
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:trace_events_hist_init
  - kernel/trace/trace_kprobe.c:init_kprobe_trace
  - kernel/trace/trace_uprobe.c:init_uprobe_trace
```
**Symbols:**

```
ffffffff811d52b0-ffffffff811d532d: dyn_event_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int dyn_event_register(struct dyn_event_operations *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_dynevent.c (ffffffff811f1920)
Location: kernel/trace/trace_dynevent.c:21
Inline: False
Direct callers:
  - kernel/trace/trace_events_synth.c:trace_events_synth_init
  - kernel/trace/trace_kprobe.c:init_kprobe_trace_early
  - kernel/trace/trace_uprobe.c:init_uprobe_trace
```
**Symbols:**

```
ffffffff811f1920-ffffffff811f19a0: dyn_event_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int dyn_event_register(struct dyn_event_operations *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_dynevent.c (ffffffff811f0350)
Location: kernel/trace/trace_dynevent.c:21
Inline: False
Direct callers:
  - kernel/trace/trace_events_synth.c:trace_events_synth_init_early
  - kernel/trace/trace_kprobe.c:init_kprobe_trace_early
  - kernel/trace/trace_uprobe.c:init_uprobe_trace
```
**Symbols:**

```
ffffffff811f0350-ffffffff811f03d0: dyn_event_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int dyn_event_register(struct dyn_event_operations *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_dynevent.c (ffffffff811f1280)
Location: kernel/trace/trace_dynevent.c:21
Inline: False
Direct callers:
  - kernel/trace/trace_events_synth.c:trace_events_synth_init_early
  - kernel/trace/trace_kprobe.c:init_kprobe_trace_early
  - kernel/trace/trace_uprobe.c:init_uprobe_trace
```
**Symbols:**

```
ffffffff811f1280-ffffffff811f1300: dyn_event_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int dyn_event_register(struct dyn_event_operations *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_dynevent.c (ffffffff81222420)
Location: kernel/trace/trace_dynevent.c:59
Inline: False
Direct callers:
  - kernel/trace/trace_eprobe.c:trace_events_eprobe_init_early
  - kernel/trace/trace_events_synth.c:trace_events_synth_init_early
  - kernel/trace/trace_kprobe.c:init_kprobe_trace_early
  - kernel/trace/trace_uprobe.c:init_uprobe_trace
```
**Symbols:**

```
ffffffff81222420-ffffffff812224a0: dyn_event_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int dyn_event_register(struct dyn_event_operations *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_dynevent.c (ffffffff812621e0)
Location: kernel/trace/trace_dynevent.c:59
Inline: False
Direct callers:
  - kernel/trace/trace_eprobe.c:trace_events_eprobe_init_early
  - kernel/trace/trace_events_synth.c:trace_events_synth_init_early
  - kernel/trace/trace_kprobe.c:init_kprobe_trace_early
  - kernel/trace/trace_uprobe.c:init_uprobe_trace
```
**Symbols:**

```
ffffffff812621e0-ffffffff8126226c: dyn_event_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int dyn_event_register(struct dyn_event_operations *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_dynevent.c (ffffffff812b39a0)
Location: kernel/trace/trace_dynevent.c:59
Inline: False
Direct callers:
  - kernel/trace/trace_eprobe.c:trace_events_eprobe_init_early
  - kernel/trace/trace_events_synth.c:trace_events_synth_init_early
  - kernel/trace/trace_kprobe.c:init_kprobe_trace_early
  - kernel/trace/trace_uprobe.c:init_uprobe_trace
```
**Symbols:**

```
ffffffff812b39a0-ffffffff812b3a2c: dyn_event_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int dyn_event_register(struct dyn_event_operations *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_dynevent.c (ffffffff812d6270)
Location: kernel/trace/trace_dynevent.c:59
Inline: False
Direct callers:
  - kernel/trace/trace_eprobe.c:trace_events_eprobe_init_early
  - kernel/trace/trace_events_synth.c:trace_events_synth_init_early
  - kernel/trace/trace_events_user.c:trace_events_user_init
  - kernel/trace/trace_kprobe.c:init_kprobe_trace_early
  - kernel/trace/trace_uprobe.c:init_uprobe_trace
  - kernel/trace/trace_fprobe.c:init_fprobe_trace_early
```
**Symbols:**

```
ffffffff812d6270-ffffffff812d62fc: dyn_event_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int dyn_event_register(struct dyn_event_operations *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_dynevent.c (ffffffff812f3d80)
Location: kernel/trace/trace_dynevent.c:59
Inline: False
Direct callers:
  - kernel/trace/trace_eprobe.c:trace_events_eprobe_init_early
  - kernel/trace/trace_events_synth.c:trace_events_synth_init_early
  - kernel/trace/trace_events_user.c:trace_events_user_init
  - kernel/trace/trace_kprobe.c:init_kprobe_trace_early
  - kernel/trace/trace_uprobe.c:init_uprobe_trace
  - kernel/trace/trace_fprobe.c:init_fprobe_trace_early
```
**Symbols:**

```
ffffffff812f3d80-ffffffff812f3e0c: dyn_event_register (STB_GLOBAL)
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
int dyn_event_register(struct dyn_event_operations *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_dynevent.c (ffff800010255490)
Location: kernel/trace/trace_dynevent.c:21
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:trace_events_hist_init
  - kernel/trace/trace_kprobe.c:init_kprobe_trace
  - kernel/trace/trace_uprobe.c:init_uprobe_trace
```
**Symbols:**

```
ffff800010255490-ffff80001025552c: dyn_event_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int dyn_event_register(struct dyn_event_operations *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_dynevent.c (c04886bc)
Location: kernel/trace/trace_dynevent.c:21
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:init_kprobe_trace
  - kernel/trace/trace_uprobe.c:init_uprobe_trace
```
**Symbols:**

```
c04886bc-c0488750: dyn_event_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int dyn_event_register(struct dyn_event_operations *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_dynevent.c (c0000000002f52c0)
Location: kernel/trace/trace_dynevent.c:21
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:trace_events_hist_init
  - kernel/trace/trace_kprobe.c:init_kprobe_trace
  - kernel/trace/trace_uprobe.c:init_uprobe_trace
```
**Symbols:**

```
c0000000002f52c0-c0000000002f5398: dyn_event_register (STB_GLOBAL)
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
int dyn_event_register(struct dyn_event_operations *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_dynevent.c (ffffffff811cd8d0)
Location: kernel/trace/trace_dynevent.c:21
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:trace_events_hist_init
  - kernel/trace/trace_kprobe.c:init_kprobe_trace
  - kernel/trace/trace_uprobe.c:init_uprobe_trace
```
**Symbols:**

```
ffffffff811cd8d0-ffffffff811cd94d: dyn_event_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int dyn_event_register(struct dyn_event_operations *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_dynevent.c (ffffffff811c06a0)
Location: kernel/trace/trace_dynevent.c:21
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:trace_events_hist_init
  - kernel/trace/trace_kprobe.c:init_kprobe_trace
  - kernel/trace/trace_uprobe.c:init_uprobe_trace
```
**Symbols:**

```
ffffffff811c06a0-ffffffff811c071d: dyn_event_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int dyn_event_register(struct dyn_event_operations *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_dynevent.c (ffffffff811cb6a0)
Location: kernel/trace/trace_dynevent.c:21
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:trace_events_hist_init
  - kernel/trace/trace_kprobe.c:init_kprobe_trace
  - kernel/trace/trace_uprobe.c:init_uprobe_trace
```
**Symbols:**

```
ffffffff811cb6a0-ffffffff811cb71d: dyn_event_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int dyn_event_register(struct dyn_event_operations *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_dynevent.c (ffffffff811d9900)
Location: kernel/trace/trace_dynevent.c:21
Inline: False
Direct callers:
  - kernel/trace/trace_events_hist.c:trace_events_hist_init
  - kernel/trace/trace_kprobe.c:init_kprobe_trace
  - kernel/trace/trace_uprobe.c:init_uprobe_trace
```
**Symbols:**

```
ffffffff811d9900-ffffffff811d997d: dyn_event_register (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
