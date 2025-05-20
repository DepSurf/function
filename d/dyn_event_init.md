# Function: <code>dyn_event_init</code>

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
In kernel/trace/trace_events_hist.c (ffffffff811af841)
Location: kernel/trace/trace_dynevent.h:68
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:__create_synth_event
```
```
In kernel/trace/trace_kprobe.c (ffffffff811b528b)
Location: kernel/trace/trace_dynevent.h:68
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:alloc_trace_kprobe
```
```
In kernel/trace/trace_uprobe.c (ffffffff811bdc81)
Location: kernel/trace/trace_dynevent.h:68
Inline: True
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
In kernel/trace/trace_events_hist.c (ffffffff811c09b3)
Location: kernel/trace/trace_dynevent.h:68
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:__create_synth_event
```
```
In kernel/trace/trace_kprobe.c (ffffffff811c403c)
Location: kernel/trace/trace_dynevent.h:68
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:alloc_trace_kprobe
```
```
In kernel/trace/trace_uprobe.c (ffffffff811ccbdc)
Location: kernel/trace/trace_dynevent.h:68
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:alloc_trace_uprobe
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
In kernel/trace/trace_events_hist.c (ffffffff811cc263)
Location: kernel/trace/trace_dynevent.h:69
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:__create_synth_event
```
```
In kernel/trace/trace_kprobe.c (ffffffff811cff5e)
Location: kernel/trace/trace_dynevent.h:69
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:alloc_trace_kprobe
```
```
In kernel/trace/trace_uprobe.c (ffffffff811d918e)
Location: kernel/trace/trace_dynevent.h:69
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:alloc_trace_uprobe
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
In kernel/trace/trace_events_synth.c (ffffffff811df754)
Location: kernel/trace/trace_dynevent.h:69
Inline: True
Inline callers:
  - kernel/trace/trace_events_synth.c:alloc_synth_event
```
```
In kernel/trace/trace_kprobe.c (ffffffff811ed5f1)
Location: kernel/trace/trace_dynevent.h:69
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:alloc_trace_kprobe
```
```
In kernel/trace/trace_uprobe.c (ffffffff811f4e9e)
Location: kernel/trace/trace_dynevent.h:69
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:alloc_trace_uprobe
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
In kernel/trace/trace_events_synth.c (ffffffff811dcf4d)
Location: kernel/trace/trace_dynevent.h:69
Inline: True
Inline callers:
  - kernel/trace/trace_events_synth.c:alloc_synth_event
```
```
In kernel/trace/trace_kprobe.c (ffffffff811eb741)
Location: kernel/trace/trace_dynevent.h:69
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:alloc_trace_kprobe
```
```
In kernel/trace/trace_uprobe.c (ffffffff811f382e)
Location: kernel/trace/trace_dynevent.h:69
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:alloc_trace_uprobe
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
In kernel/trace/trace_events_synth.c (ffffffff811de1aa)
Location: kernel/trace/trace_dynevent.h:69
Inline: True
Inline callers:
  - kernel/trace/trace_events_synth.c:alloc_synth_event
```
```
In kernel/trace/trace_kprobe.c (ffffffff811ecb11)
Location: kernel/trace/trace_dynevent.h:69
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:alloc_trace_kprobe
```
```
In kernel/trace/trace_uprobe.c (ffffffff811f47ae)
Location: kernel/trace/trace_dynevent.h:69
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:alloc_trace_uprobe
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
In kernel/trace/trace_eprobe.c (ffffffff8120ac28)
Location: kernel/trace/trace_dynevent.h:69
Inline: True
Inline callers:
  - kernel/trace/trace_eprobe.c:__trace_eprobe_create
```
```
In kernel/trace/trace_events_synth.c (ffffffff8120da25)
Location: kernel/trace/trace_dynevent.h:69
Inline: True
Inline callers:
  - kernel/trace/trace_events_synth.c:alloc_synth_event
```
```
In kernel/trace/trace_kprobe.c (ffffffff8121db8d)
Location: kernel/trace/trace_dynevent.h:69
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:alloc_trace_kprobe
```
```
In kernel/trace/trace_uprobe.c (ffffffff81225b43)
Location: kernel/trace/trace_dynevent.h:69
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:alloc_trace_uprobe
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
In kernel/trace/trace_eprobe.c (ffffffff81246c5a)
Location: kernel/trace/trace_dynevent.h:69
Inline: True
Inline callers:
  - kernel/trace/trace_eprobe.c:__trace_eprobe_create
```
```
In kernel/trace/trace_events_synth.c (ffffffff81249a32)
Location: kernel/trace/trace_dynevent.h:69
Inline: True
Inline callers:
  - kernel/trace/trace_events_synth.c:alloc_synth_event
```
```
In kernel/trace/trace_kprobe.c (ffffffff8125d15a)
Location: kernel/trace/trace_dynevent.h:69
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:alloc_trace_kprobe
```
```
In kernel/trace/trace_uprobe.c (ffffffff81265b7f)
Location: kernel/trace/trace_dynevent.h:69
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:alloc_trace_uprobe
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
In kernel/trace/trace_eprobe.c (ffffffff81293da5)
Location: kernel/trace/trace_dynevent.h:69
Inline: True
Inline callers:
  - kernel/trace/trace_eprobe.c:__trace_eprobe_create
```
```
In kernel/trace/trace_events_synth.c (ffffffff81297d62)
Location: kernel/trace/trace_dynevent.h:69
Inline: True
Inline callers:
  - kernel/trace/trace_events_synth.c:alloc_synth_event
```
```
In kernel/trace/trace_kprobe.c (ffffffff812ac3fa)
Location: kernel/trace/trace_dynevent.h:69
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:alloc_trace_kprobe
```
```
In kernel/trace/trace_uprobe.c (ffffffff812b74bf)
Location: kernel/trace/trace_dynevent.h:69
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:alloc_trace_uprobe
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
In kernel/trace/trace_eprobe.c (ffffffff812b0e95)
Location: kernel/trace/trace_dynevent.h:69
Inline: True
Inline callers:
  - kernel/trace/trace_eprobe.c:__trace_eprobe_create
```
```
In kernel/trace/trace_events_synth.c (ffffffff812b4dd2)
Location: kernel/trace/trace_dynevent.h:69
Inline: True
Inline callers:
  - kernel/trace/trace_events_synth.c:alloc_synth_event
```
```
In kernel/trace/trace_events_user.c (ffffffff812c67c1)
Location: kernel/trace/trace_dynevent.h:69
Inline: True
Inline callers:
  - kernel/trace/trace_events_user.c:user_event_parse
```
```
In kernel/trace/trace_kprobe.c (ffffffff812d0036)
Location: kernel/trace/trace_dynevent.h:69
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:alloc_trace_kprobe
```
```
In kernel/trace/trace_uprobe.c (ffffffff812dab1d)
Location: kernel/trace/trace_dynevent.h:69
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:alloc_trace_uprobe
```
```
In kernel/trace/trace_fprobe.c (ffffffff812dfe59)
Location: kernel/trace/trace_dynevent.h:69
Inline: True
Inline callers:
  - kernel/trace/trace_fprobe.c:alloc_trace_fprobe
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
In kernel/trace/trace_eprobe.c (ffffffff812cd458)
Location: kernel/trace/trace_dynevent.h:69
Inline: True
Inline callers:
  - kernel/trace/trace_eprobe.c:__trace_eprobe_create
```
```
In kernel/trace/trace_events_synth.c (ffffffff812d1421)
Location: kernel/trace/trace_dynevent.h:69
Inline: True
Inline callers:
  - kernel/trace/trace_events_synth.c:alloc_synth_event
```
```
In kernel/trace/trace_events_user.c (ffffffff812e3274)
Location: kernel/trace/trace_dynevent.h:69
Inline: True
Inline callers:
  - kernel/trace/trace_events_user.c:user_event_parse
```
```
In kernel/trace/trace_kprobe.c (ffffffff812eda36)
Location: kernel/trace/trace_dynevent.h:69
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:alloc_trace_kprobe
```
```
In kernel/trace/trace_uprobe.c (ffffffff812f8d6d)
Location: kernel/trace/trace_dynevent.h:69
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:alloc_trace_uprobe
```
```
In kernel/trace/trace_fprobe.c (ffffffff812fdf29)
Location: kernel/trace/trace_dynevent.h:69
Inline: True
Inline callers:
  - kernel/trace/trace_fprobe.c:alloc_trace_fprobe
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
In kernel/trace/trace_events_hist.c (ffff80001024bf7c)
Location: kernel/trace/trace_dynevent.h:69
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:__create_synth_event
```
```
In kernel/trace/trace_kprobe.c (ffff800010250828)
Location: kernel/trace/trace_dynevent.h:69
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:alloc_trace_kprobe
```
```
In kernel/trace/trace_uprobe.c (ffff800010258be8)
Location: kernel/trace/trace_dynevent.h:69
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:alloc_trace_uprobe
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
In kernel/trace/trace_kprobe.c (c04835a8)
Location: kernel/trace/trace_dynevent.h:69
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:alloc_trace_kprobe
```
```
In kernel/trace/trace_uprobe.c (c048c2b0)
Location: kernel/trace/trace_dynevent.h:69
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:alloc_trace_uprobe
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
In kernel/trace/trace_events_hist.c (c0000000002e723c)
Location: kernel/trace/trace_dynevent.h:69
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:__create_synth_event
```
```
In kernel/trace/trace_kprobe.c (c0000000002eefa8)
Location: kernel/trace/trace_dynevent.h:69
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:alloc_trace_kprobe
```
```
In kernel/trace/trace_uprobe.c (c0000000002fc410)
Location: kernel/trace/trace_dynevent.h:69
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:alloc_trace_uprobe
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
In kernel/trace/trace_events_hist.c (ffffffff811c4883)
Location: kernel/trace/trace_dynevent.h:69
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:__create_synth_event
```
```
In kernel/trace/trace_kprobe.c (ffffffff811c857e)
Location: kernel/trace/trace_dynevent.h:69
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:alloc_trace_kprobe
```
```
In kernel/trace/trace_uprobe.c (ffffffff811d17ae)
Location: kernel/trace/trace_dynevent.h:69
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:alloc_trace_uprobe
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
In kernel/trace/trace_events_hist.c (ffffffff811b7663)
Location: kernel/trace/trace_dynevent.h:69
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:__create_synth_event
```
```
In kernel/trace/trace_kprobe.c (ffffffff811bb35e)
Location: kernel/trace/trace_dynevent.h:69
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:alloc_trace_kprobe
```
```
In kernel/trace/trace_uprobe.c (ffffffff811c457e)
Location: kernel/trace/trace_dynevent.h:69
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:alloc_trace_uprobe
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
In kernel/trace/trace_events_hist.c (ffffffff811c2653)
Location: kernel/trace/trace_dynevent.h:69
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:__create_synth_event
```
```
In kernel/trace/trace_kprobe.c (ffffffff811c634e)
Location: kernel/trace/trace_dynevent.h:69
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:alloc_trace_kprobe
```
```
In kernel/trace/trace_uprobe.c (ffffffff811cf57e)
Location: kernel/trace/trace_dynevent.h:69
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:alloc_trace_uprobe
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
In kernel/trace/trace_events_hist.c (ffffffff811d06f3)
Location: kernel/trace/trace_dynevent.h:69
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:__create_synth_event
```
```
In kernel/trace/trace_kprobe.c (ffffffff811d45ae)
Location: kernel/trace/trace_dynevent.h:69
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:alloc_trace_kprobe
```
```
In kernel/trace/trace_uprobe.c (ffffffff811dd81e)
Location: kernel/trace/trace_dynevent.h:69
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:alloc_trace_uprobe
```
</details>
</li>
</ul>

## Differences
