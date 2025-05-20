# Function: <code>dyn_event_add</code>

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
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811afa2b)
Location: kernel/trace/trace_dynevent.h:78
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:__create_synth_event
```
```
In kernel/trace/trace_kprobe.c (ffffffff811b5875)
Location: kernel/trace/trace_dynevent.h:78
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:trace_kprobe_create
```
```
In kernel/trace/trace_uprobe.c (ffffffff811be25b)
Location: kernel/trace/trace_dynevent.h:78
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811c0b82)
Location: kernel/trace/trace_dynevent.h:78
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:__create_synth_event
```
```
In kernel/trace/trace_kprobe.c (ffffffff811c45dc)
Location: kernel/trace/trace_dynevent.h:78
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:trace_kprobe_create
```
```
In kernel/trace/trace_uprobe.c (ffffffff811cd281)
Location: kernel/trace/trace_dynevent.h:78
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811cc432)
Location: kernel/trace/trace_dynevent.h:79
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:__create_synth_event
```
```
In kernel/trace/trace_kprobe.c (ffffffff811cfbb6)
Location: kernel/trace/trace_dynevent.h:79
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:register_trace_kprobe
  - kernel/trace/trace_kprobe.c:register_trace_kprobe
```
```
In kernel/trace/trace_uprobe.c (ffffffff811d984f)
Location: kernel/trace/trace_dynevent.h:79
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_synth.c (ffffffff811dfe4e)
Location: kernel/trace/trace_dynevent.h:79
Inline: True
Inline callers:
  - kernel/trace/trace_events_synth.c:__create_synth_event
```
```
In kernel/trace/trace_kprobe.c (ffffffff811edcbf)
Location: kernel/trace/trace_dynevent.h:79
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:register_trace_kprobe
  - kernel/trace/trace_kprobe.c:append_trace_kprobe
```
```
In kernel/trace/trace_uprobe.c (ffffffff811f5dc5)
Location: kernel/trace/trace_dynevent.h:79
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:register_trace_uprobe
  - kernel/trace/trace_uprobe.c:register_trace_uprobe
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_synth.c (ffffffff811dd824)
Location: kernel/trace/trace_dynevent.h:79
Inline: True
Inline callers:
  - kernel/trace/trace_events_synth.c:__create_synth_event
```
```
In kernel/trace/trace_kprobe.c (ffffffff811ebe2f)
Location: kernel/trace/trace_dynevent.h:79
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:register_trace_kprobe
  - kernel/trace/trace_kprobe.c:append_trace_kprobe
```
```
In kernel/trace/trace_uprobe.c (ffffffff811f4755)
Location: kernel/trace/trace_dynevent.h:79
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:register_trace_uprobe
  - kernel/trace/trace_uprobe.c:register_trace_uprobe
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_synth.c (ffffffff811dec52)
Location: kernel/trace/trace_dynevent.h:79
Inline: True
Inline callers:
  - kernel/trace/trace_events_synth.c:__create_synth_event
```
```
In kernel/trace/trace_kprobe.c (ffffffff811eb57b)
Location: kernel/trace/trace_dynevent.h:79
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:register_trace_kprobe
  - kernel/trace/trace_kprobe.c:append_trace_kprobe
```
```
In kernel/trace/trace_uprobe.c (ffffffff811f573e)
Location: kernel/trace/trace_dynevent.h:79
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:register_trace_uprobe
  - kernel/trace/trace_uprobe.c:append_trace_uprobe
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_eprobe.c (ffffffff8120af5d)
Location: kernel/trace/trace_dynevent.h:79
Inline: True
Inline callers:
  - kernel/trace/trace_eprobe.c:__trace_eprobe_create
```
```
In kernel/trace/trace_events_synth.c (ffffffff8120e4f5)
Location: kernel/trace/trace_dynevent.h:79
Inline: True
Inline callers:
  - kernel/trace/trace_events_synth.c:__create_synth_event
```
```
In kernel/trace/trace_kprobe.c (ffffffff8121c404)
Location: kernel/trace/trace_dynevent.h:79
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:register_trace_kprobe
  - kernel/trace/trace_kprobe.c:append_trace_kprobe
```
```
In kernel/trace/trace_uprobe.c (ffffffff8122789e)
Location: kernel/trace/trace_dynevent.h:79
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:register_trace_uprobe
  - kernel/trace/trace_uprobe.c:append_trace_uprobe
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_eprobe.c (ffffffff81247003)
Location: kernel/trace/trace_dynevent.h:79
Inline: True
Inline callers:
  - kernel/trace/trace_eprobe.c:__trace_eprobe_create
```
```
In kernel/trace/trace_events_synth.c (ffffffff8124aa94)
Location: kernel/trace/trace_dynevent.h:79
Inline: True
Inline callers:
  - kernel/trace/trace_events_synth.c:__create_synth_event
```
```
In kernel/trace/trace_kprobe.c (ffffffff8125ceac)
Location: kernel/trace/trace_dynevent.h:79
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:register_trace_kprobe
  - kernel/trace/trace_kprobe.c:append_trace_kprobe
```
```
In kernel/trace/trace_uprobe.c (ffffffff81267a2f)
Location: kernel/trace/trace_dynevent.h:79
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:register_trace_uprobe
  - kernel/trace/trace_uprobe.c:append_trace_uprobe
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_eprobe.c (ffffffff81294187)
Location: kernel/trace/trace_dynevent.h:79
Inline: True
Inline callers:
  - kernel/trace/trace_eprobe.c:__trace_eprobe_create
```
```
In kernel/trace/trace_events_synth.c (ffffffff8129967c)
Location: kernel/trace/trace_dynevent.h:79
Inline: True
Inline callers:
  - kernel/trace/trace_events_synth.c:__create_synth_event
```
```
In kernel/trace/trace_kprobe.c (ffffffff812abe57)
Location: kernel/trace/trace_dynevent.h:79
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:register_trace_kprobe
  - kernel/trace/trace_kprobe.c:append_trace_kprobe
```
```
In kernel/trace/trace_uprobe.c (ffffffff812b9b84)
Location: kernel/trace/trace_dynevent.h:79
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:register_trace_uprobe
  - kernel/trace/trace_uprobe.c:append_trace_uprobe
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_eprobe.c (ffffffff812b1171)
Location: kernel/trace/trace_dynevent.h:79
Inline: True
Inline callers:
  - kernel/trace/trace_eprobe.c:__trace_eprobe_create
```
```
In kernel/trace/trace_events_synth.c (ffffffff812b6a29)
Location: kernel/trace/trace_dynevent.h:79
Inline: True
Inline callers:
  - kernel/trace/trace_events_synth.c:__create_synth_event
```
```
In kernel/trace/trace_events_user.c (ffffffff812c67f0)
Location: kernel/trace/trace_dynevent.h:79
Inline: True
Inline callers:
  - kernel/trace/trace_events_user.c:user_event_parse
```
```
In kernel/trace/trace_kprobe.c (ffffffff812ce657)
Location: kernel/trace/trace_dynevent.h:79
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:register_trace_kprobe
  - kernel/trace/trace_kprobe.c:append_trace_kprobe
```
```
In kernel/trace/trace_uprobe.c (ffffffff812dd3a4)
Location: kernel/trace/trace_dynevent.h:79
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:register_trace_uprobe
  - kernel/trace/trace_uprobe.c:append_trace_uprobe
```
```
In kernel/trace/trace_fprobe.c (ffffffff812e0573)
Location: kernel/trace/trace_dynevent.h:79
Inline: True
Inline callers:
  - kernel/trace/trace_fprobe.c:register_trace_fprobe
  - kernel/trace/trace_fprobe.c:append_trace_fprobe
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_eprobe.c (ffffffff812cd72f)
Location: kernel/trace/trace_dynevent.h:79
Inline: True
Inline callers:
  - kernel/trace/trace_eprobe.c:__trace_eprobe_create
```
```
In kernel/trace/trace_events_synth.c (ffffffff812d3079)
Location: kernel/trace/trace_dynevent.h:79
Inline: True
Inline callers:
  - kernel/trace/trace_events_synth.c:__create_synth_event
```
```
In kernel/trace/trace_events_user.c (ffffffff812e32a6)
Location: kernel/trace/trace_dynevent.h:79
Inline: True
Inline callers:
  - kernel/trace/trace_events_user.c:user_event_parse
```
```
In kernel/trace/trace_kprobe.c (ffffffff812ec057)
Location: kernel/trace/trace_dynevent.h:79
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:register_trace_kprobe
  - kernel/trace/trace_kprobe.c:append_trace_kprobe
```
```
In kernel/trace/trace_uprobe.c (ffffffff812fb484)
Location: kernel/trace/trace_dynevent.h:79
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:register_trace_uprobe
  - kernel/trace/trace_uprobe.c:append_trace_uprobe
```
```
In kernel/trace/trace_fprobe.c (ffffffff812fe4d3)
Location: kernel/trace/trace_dynevent.h:79
Inline: True
Inline callers:
  - kernel/trace/trace_fprobe.c:register_trace_fprobe
  - kernel/trace/trace_fprobe.c:append_trace_fprobe
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffff80001024c0f8)
Location: kernel/trace/trace_dynevent.h:79
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:__create_synth_event
```
```
In kernel/trace/trace_kprobe.c (ffff80001025040c)
Location: kernel/trace/trace_dynevent.h:79
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:register_trace_kprobe
  - kernel/trace/trace_kprobe.c:register_trace_kprobe
```
```
In kernel/trace/trace_uprobe.c (ffff8000102591f8)
Location: kernel/trace/trace_dynevent.h:79
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kprobe.c (c0483e04)
Location: kernel/trace/trace_dynevent.h:79
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:register_trace_kprobe
```
```
In kernel/trace/trace_uprobe.c (c048ccb8)
Location: kernel/trace/trace_dynevent.h:79
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (c0000000002e7400)
Location: kernel/trace/trace_dynevent.h:79
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:__create_synth_event
```
```
In kernel/trace/trace_kprobe.c (c0000000002ee444)
Location: kernel/trace/trace_dynevent.h:79
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:register_trace_kprobe
  - kernel/trace/trace_kprobe.c:register_trace_kprobe
```
```
In kernel/trace/trace_uprobe.c (c0000000002fcc94)
Location: kernel/trace/trace_dynevent.h:79
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
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
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811c4a52)
Location: kernel/trace/trace_dynevent.h:79
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:__create_synth_event
```
```
In kernel/trace/trace_kprobe.c (ffffffff811c81d6)
Location: kernel/trace/trace_dynevent.h:79
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:register_trace_kprobe
  - kernel/trace/trace_kprobe.c:register_trace_kprobe
```
```
In kernel/trace/trace_uprobe.c (ffffffff811d1e6f)
Location: kernel/trace/trace_dynevent.h:79
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811b7832)
Location: kernel/trace/trace_dynevent.h:79
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:__create_synth_event
```
```
In kernel/trace/trace_kprobe.c (ffffffff811bafb6)
Location: kernel/trace/trace_dynevent.h:79
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:register_trace_kprobe
  - kernel/trace/trace_kprobe.c:register_trace_kprobe
```
```
In kernel/trace/trace_uprobe.c (ffffffff811c4c3f)
Location: kernel/trace/trace_dynevent.h:79
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811c2822)
Location: kernel/trace/trace_dynevent.h:79
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:__create_synth_event
```
```
In kernel/trace/trace_kprobe.c (ffffffff811c5fa6)
Location: kernel/trace/trace_dynevent.h:79
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:register_trace_kprobe
  - kernel/trace/trace_kprobe.c:register_trace_kprobe
```
```
In kernel/trace/trace_uprobe.c (ffffffff811cfc3f)
Location: kernel/trace/trace_dynevent.h:79
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events_hist.c (ffffffff811d08c2)
Location: kernel/trace/trace_dynevent.h:79
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:__create_synth_event
```
```
In kernel/trace/trace_kprobe.c (ffffffff811d4206)
Location: kernel/trace/trace_dynevent.h:79
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:register_trace_kprobe
  - kernel/trace/trace_kprobe.c:register_trace_kprobe
```
```
In kernel/trace/trace_uprobe.c (ffffffff811ddedf)
Location: kernel/trace/trace_dynevent.h:79
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
```
</details>
</li>
</ul>

## Differences
