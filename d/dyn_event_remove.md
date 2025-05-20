# Function: <code>dyn_event_remove</code>

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
In kernel/trace/trace_events_hist.c (ffffffff811afd94)
Location: kernel/trace/trace_dynevent.h:89
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:create_or_delete_synth_event
```
```
In kernel/trace/trace_kprobe.c (ffffffff811b4ea8)
Location: kernel/trace/trace_dynevent.h:89
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:unregister_trace_kprobe
```
```
In kernel/trace/trace_uprobe.c (ffffffff811bd913)
Location: kernel/trace/trace_dynevent.h:89
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:trace_uprobe_release
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
In kernel/trace/trace_events_hist.c (ffffffff811c0dbf)
Location: kernel/trace/trace_dynevent.h:89
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:create_or_delete_synth_event
```
```
In kernel/trace/trace_kprobe.c (ffffffff811c361e)
Location: kernel/trace/trace_dynevent.h:89
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:unregister_trace_kprobe
```
```
In kernel/trace/trace_uprobe.c (ffffffff811cd3de)
Location: kernel/trace/trace_dynevent.h:89
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:trace_uprobe_release
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
In kernel/trace/trace_events_hist.c (ffffffff811cc66f)
Location: kernel/trace/trace_dynevent.h:90
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:create_or_delete_synth_event
```
```
In kernel/trace/trace_kprobe.c (ffffffff811cf717)
Location: kernel/trace/trace_dynevent.h:90
Inline: True
```
```
In kernel/trace/trace_uprobe.c (ffffffff811d85e1)
Location: kernel/trace/trace_dynevent.h:90
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:trace_uprobe_release
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
In kernel/trace/trace_events_synth.c (ffffffff811def65)
Location: kernel/trace/trace_dynevent.h:90
Inline: True
```
```
In kernel/trace/trace_kprobe.c (ffffffff811ed460)
Location: kernel/trace/trace_dynevent.h:90
Inline: True
```
```
In kernel/trace/trace_uprobe.c (ffffffff811f6477)
Location: kernel/trace/trace_dynevent.h:90
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:trace_uprobe_release
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
In kernel/trace/trace_events_synth.c (ffffffff811dc285)
Location: kernel/trace/trace_dynevent.h:90
Inline: True
```
```
In kernel/trace/trace_kprobe.c (ffffffff811eb5b0)
Location: kernel/trace/trace_dynevent.h:90
Inline: True
```
```
In kernel/trace/trace_uprobe.c (ffffffff811f4e57)
Location: kernel/trace/trace_dynevent.h:90
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:trace_uprobe_release
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
In kernel/trace/trace_events_synth.c (ffffffff811dd775)
Location: kernel/trace/trace_dynevent.h:90
Inline: True
```
```
In kernel/trace/trace_kprobe.c (ffffffff811ec980)
Location: kernel/trace/trace_dynevent.h:90
Inline: True
```
```
In kernel/trace/trace_uprobe.c (ffffffff811f5d47)
Location: kernel/trace/trace_dynevent.h:90
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:trace_uprobe_release
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
In kernel/trace/trace_eprobe.c (ffffffff812098b7)
Location: kernel/trace/trace_dynevent.h:92
Inline: True
Inline callers:
  - kernel/trace/trace_eprobe.c:eprobe_dyn_event_release
```
```
In kernel/trace/trace_events_synth.c (ffffffff8120cf84)
Location: kernel/trace/trace_dynevent.h:92
Inline: True
```
```
In kernel/trace/trace_kprobe.c (ffffffff8121d9e0)
Location: kernel/trace/trace_dynevent.h:92
Inline: True
```
```
In kernel/trace/trace_uprobe.c (ffffffff81227e27)
Location: kernel/trace/trace_dynevent.h:92
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:trace_uprobe_release
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
In kernel/trace/trace_eprobe.c (ffffffff81246097)
Location: kernel/trace/trace_dynevent.h:92
Inline: True
Inline callers:
  - kernel/trace/trace_eprobe.c:eprobe_dyn_event_release
```
```
In kernel/trace/trace_events_synth.c (ffffffff81249663)
Location: kernel/trace/trace_dynevent.h:92
Inline: True
```
```
In kernel/trace/trace_kprobe.c (ffffffff8125cfaf)
Location: kernel/trace/trace_dynevent.h:92
Inline: True
```
```
In kernel/trace/trace_uprobe.c (ffffffff812671d4)
Location: kernel/trace/trace_dynevent.h:92
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:trace_uprobe_release
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
In kernel/trace/trace_eprobe.c (ffffffff81292fb7)
Location: kernel/trace/trace_dynevent.h:92
Inline: True
Inline callers:
  - kernel/trace/trace_eprobe.c:eprobe_dyn_event_release
```
```
In kernel/trace/trace_events_synth.c (ffffffff81298afa)
Location: kernel/trace/trace_dynevent.h:92
Inline: True
Inline callers:
  - kernel/trace/trace_events_synth.c:synth_event_delete
```
```
In kernel/trace/trace_kprobe.c (ffffffff812ac23f)
Location: kernel/trace/trace_dynevent.h:92
Inline: True
```
```
In kernel/trace/trace_uprobe.c (ffffffff812b9244)
Location: kernel/trace/trace_dynevent.h:92
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:trace_uprobe_release
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
In kernel/trace/trace_eprobe.c (ffffffff812b0137)
Location: kernel/trace/trace_dynevent.h:92
Inline: True
Inline callers:
  - kernel/trace/trace_eprobe.c:eprobe_dyn_event_release
```
```
In kernel/trace/trace_events_synth.c (ffffffff812b594a)
Location: kernel/trace/trace_dynevent.h:92
Inline: True
Inline callers:
  - kernel/trace/trace_events_synth.c:synth_event_delete
```
```
In kernel/trace/trace_events_user.c (ffffffff812c52d0)
Location: kernel/trace/trace_dynevent.h:92
Inline: True
```
```
In kernel/trace/trace_kprobe.c (ffffffff812cea3f)
Location: kernel/trace/trace_dynevent.h:92
Inline: True
```
```
In kernel/trace/trace_uprobe.c (ffffffff812dc8a4)
Location: kernel/trace/trace_dynevent.h:92
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:trace_uprobe_release
```
```
In kernel/trace/trace_fprobe.c (ffffffff812dff41)
Location: kernel/trace/trace_dynevent.h:92
Inline: True
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
In kernel/trace/trace_eprobe.c (ffffffff812cc6a7)
Location: kernel/trace/trace_dynevent.h:92
Inline: True
Inline callers:
  - kernel/trace/trace_eprobe.c:eprobe_dyn_event_release
```
```
In kernel/trace/trace_events_synth.c (ffffffff812d1fba)
Location: kernel/trace/trace_dynevent.h:92
Inline: True
Inline callers:
  - kernel/trace/trace_events_synth.c:synth_event_delete
```
```
In kernel/trace/trace_events_user.c (ffffffff812e1d15)
Location: kernel/trace/trace_dynevent.h:92
Inline: True
```
```
In kernel/trace/trace_kprobe.c (ffffffff812ec43f)
Location: kernel/trace/trace_dynevent.h:92
Inline: True
```
```
In kernel/trace/trace_uprobe.c (ffffffff812fa984)
Location: kernel/trace/trace_dynevent.h:92
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:trace_uprobe_release
```
```
In kernel/trace/trace_fprobe.c (ffffffff812fdd61)
Location: kernel/trace/trace_dynevent.h:92
Inline: True
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
In kernel/trace/trace_events_hist.c (ffff80001024c36c)
Location: kernel/trace/trace_dynevent.h:90
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:create_or_delete_synth_event
```
```
In kernel/trace/trace_kprobe.c (ffff80001024fed8)
Location: kernel/trace/trace_dynevent.h:90
Inline: True
```
```
In kernel/trace/trace_uprobe.c (ffff8000102588e4)
Location: kernel/trace/trace_dynevent.h:90
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:trace_uprobe_release
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
In kernel/trace/trace_kprobe.c (c0482d64)
Location: kernel/trace/trace_dynevent.h:90
Inline: True
```
```
In kernel/trace/trace_uprobe.c (c048b848)
Location: kernel/trace/trace_dynevent.h:90
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:trace_uprobe_release
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
In kernel/trace/trace_events_hist.c (c0000000002e7824)
Location: kernel/trace/trace_dynevent.h:90
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:create_or_delete_synth_event
```
```
In kernel/trace/trace_kprobe.c (c0000000002eda94)
Location: kernel/trace/trace_dynevent.h:90
Inline: True
```
```
In kernel/trace/trace_uprobe.c (c0000000002fbc80)
Location: kernel/trace/trace_dynevent.h:90
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:trace_uprobe_release
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
In kernel/trace/trace_events_hist.c (ffffffff811c4c8f)
Location: kernel/trace/trace_dynevent.h:90
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:create_or_delete_synth_event
```
```
In kernel/trace/trace_kprobe.c (ffffffff811c7d37)
Location: kernel/trace/trace_dynevent.h:90
Inline: True
```
```
In kernel/trace/trace_uprobe.c (ffffffff811d0c01)
Location: kernel/trace/trace_dynevent.h:90
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:trace_uprobe_release
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
In kernel/trace/trace_events_hist.c (ffffffff811b7a6f)
Location: kernel/trace/trace_dynevent.h:90
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:create_or_delete_synth_event
```
```
In kernel/trace/trace_kprobe.c (ffffffff811bab17)
Location: kernel/trace/trace_dynevent.h:90
Inline: True
```
```
In kernel/trace/trace_uprobe.c (ffffffff811c39d1)
Location: kernel/trace/trace_dynevent.h:90
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:trace_uprobe_release
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
In kernel/trace/trace_events_hist.c (ffffffff811c2a5f)
Location: kernel/trace/trace_dynevent.h:90
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:create_or_delete_synth_event
```
```
In kernel/trace/trace_kprobe.c (ffffffff811c5b07)
Location: kernel/trace/trace_dynevent.h:90
Inline: True
```
```
In kernel/trace/trace_uprobe.c (ffffffff811ce9d1)
Location: kernel/trace/trace_dynevent.h:90
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:trace_uprobe_release
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
In kernel/trace/trace_events_hist.c (ffffffff811d0aff)
Location: kernel/trace/trace_dynevent.h:90
Inline: True
Inline callers:
  - kernel/trace/trace_events_hist.c:create_or_delete_synth_event
```
```
In kernel/trace/trace_kprobe.c (ffffffff811d3d67)
Location: kernel/trace/trace_dynevent.h:90
Inline: True
```
```
In kernel/trace/trace_uprobe.c (ffffffff811dcc41)
Location: kernel/trace/trace_dynevent.h:90
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:trace_uprobe_release
```
</details>
</li>
</ul>

## Differences
