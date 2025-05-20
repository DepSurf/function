# Function: <code>trace_probe_probe_list</code>

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
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kprobe.c (ffffffff811cf077)
Location: kernel/trace/trace_probe.h:308
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:enable_trace_kprobe
  - kernel/trace/trace_kprobe.c:enable_trace_kprobe
  - kernel/trace/trace_kprobe.c:__disable_trace_kprobe
  - kernel/trace/trace_kprobe.c:__disable_trace_kprobe
```
```
In kernel/trace/trace_probe.c (ffffffff811d783d)
Location: kernel/trace/trace_probe.h:308
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:trace_probe_unlink
  - kernel/trace/trace_probe.c:trace_probe_append
  - kernel/trace/trace_probe.c:trace_probe_append
```
```
In kernel/trace/trace_uprobe.c (ffffffff811d84b0)
Location: kernel/trace/trace_probe.h:308
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:uprobe_perf_close
  - kernel/trace/trace_uprobe.c:uprobe_perf_close
  - kernel/trace/trace_uprobe.c:probe_event_enable
  - kernel/trace/trace_uprobe.c:probe_event_enable
  - kernel/trace/trace_uprobe.c:__probe_event_disable
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
In kernel/trace/trace_kprobe.c (ffffffff811eb327)
Location: kernel/trace/trace_probe.h:308
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:enable_trace_kprobe
  - kernel/trace/trace_kprobe.c:enable_trace_kprobe
  - kernel/trace/trace_kprobe.c:__disable_trace_kprobe
  - kernel/trace/trace_kprobe.c:__disable_trace_kprobe
```
```
In kernel/trace/trace_probe.c (ffffffff811f4193)
Location: kernel/trace/trace_probe.h:308
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:trace_probe_unlink
  - kernel/trace/trace_probe.c:trace_probe_append
  - kernel/trace/trace_probe.c:trace_probe_append
```
```
In kernel/trace/trace_uprobe.c (ffffffff811f5274)
Location: kernel/trace/trace_probe.h:308
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:uprobe_perf_open
  - kernel/trace/trace_uprobe.c:uprobe_perf_open
  - kernel/trace/trace_uprobe.c:uprobe_perf_close
  - kernel/trace/trace_uprobe.c:uprobe_perf_close
  - kernel/trace/trace_uprobe.c:probe_event_enable
  - kernel/trace/trace_uprobe.c:probe_event_enable
  - kernel/trace/trace_uprobe.c:__probe_event_disable
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
In kernel/trace/trace_kprobe.c (ffffffff811e9477)
Location: kernel/trace/trace_probe.h:307
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:enable_trace_kprobe
  - kernel/trace/trace_kprobe.c:enable_trace_kprobe
  - kernel/trace/trace_kprobe.c:__disable_trace_kprobe
  - kernel/trace/trace_kprobe.c:__disable_trace_kprobe
```
```
In kernel/trace/trace_probe.c (ffffffff811f2b43)
Location: kernel/trace/trace_probe.h:307
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:trace_probe_unlink
  - kernel/trace/trace_probe.c:trace_probe_append
  - kernel/trace/trace_probe.c:trace_probe_append
```
```
In kernel/trace/trace_uprobe.c (ffffffff811f3c04)
Location: kernel/trace/trace_probe.h:307
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:uprobe_perf_open
  - kernel/trace/trace_uprobe.c:uprobe_perf_open
  - kernel/trace/trace_uprobe.c:uprobe_perf_close
  - kernel/trace/trace_uprobe.c:uprobe_perf_close
  - kernel/trace/trace_uprobe.c:probe_event_enable
  - kernel/trace/trace_uprobe.c:probe_event_enable
  - kernel/trace/trace_uprobe.c:__probe_event_disable
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
In kernel/trace/trace_kprobe.c (ffffffff811ea307)
Location: kernel/trace/trace_probe.h:307
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:enable_trace_kprobe
  - kernel/trace/trace_kprobe.c:enable_trace_kprobe
  - kernel/trace/trace_kprobe.c:__disable_trace_kprobe
  - kernel/trace/trace_kprobe.c:__disable_trace_kprobe
```
```
In kernel/trace/trace_probe.c (ffffffff811f39d3)
Location: kernel/trace/trace_probe.h:307
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:trace_probe_unlink
  - kernel/trace/trace_probe.c:trace_probe_append
  - kernel/trace/trace_probe.c:trace_probe_append
```
```
In kernel/trace/trace_uprobe.c (ffffffff811f5033)
Location: kernel/trace/trace_probe.h:307
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:trace_uprobe_register
  - kernel/trace/trace_uprobe.c:trace_uprobe_register
  - kernel/trace/trace_uprobe.c:uprobe_perf_close
  - kernel/trace/trace_uprobe.c:uprobe_perf_close
  - kernel/trace/trace_uprobe.c:probe_event_enable
  - kernel/trace/trace_uprobe.c:probe_event_enable
  - kernel/trace/trace_uprobe.c:__probe_event_disable
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
In kernel/trace/trace_eprobe.c (ffffffff8120a408)
Location: kernel/trace/trace_probe.h:309
Inline: True
Inline callers:
  - kernel/trace/trace_eprobe.c:eprobe_register
  - kernel/trace/trace_eprobe.c:enable_trace_eprobe
  - kernel/trace/trace_eprobe.c:enable_trace_eprobe
  - kernel/trace/trace_eprobe.c:eprobe_dyn_event_release
```
```
In kernel/trace/trace_kprobe.c (ffffffff8121b147)
Location: kernel/trace/trace_probe.h:309
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:enable_trace_kprobe
  - kernel/trace/trace_kprobe.c:enable_trace_kprobe
  - kernel/trace/trace_kprobe.c:__disable_trace_kprobe
  - kernel/trace/trace_kprobe.c:__disable_trace_kprobe
```
```
In kernel/trace/trace_probe.c (ffffffff81224c93)
Location: kernel/trace/trace_probe.h:309
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:trace_probe_unlink
  - kernel/trace/trace_probe.c:trace_probe_append
  - kernel/trace/trace_probe.c:trace_probe_append
```
```
In kernel/trace/trace_uprobe.c (ffffffff8122800d)
Location: kernel/trace/trace_probe.h:309
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:trace_uprobe_register
  - kernel/trace/trace_uprobe.c:trace_uprobe_register
  - kernel/trace/trace_uprobe.c:uprobe_perf_close
  - kernel/trace/trace_uprobe.c:uprobe_perf_close
  - kernel/trace/trace_uprobe.c:probe_event_enable
  - kernel/trace/trace_uprobe.c:probe_event_enable
  - kernel/trace/trace_uprobe.c:__probe_event_disable
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
In kernel/trace/trace_eprobe.c (ffffffff812463bd)
Location: kernel/trace/trace_probe.h:308
Inline: True
Inline callers:
  - kernel/trace/trace_eprobe.c:eprobe_register
  - kernel/trace/trace_eprobe.c:enable_trace_eprobe
  - kernel/trace/trace_eprobe.c:enable_trace_eprobe
  - kernel/trace/trace_eprobe.c:eprobe_dyn_event_release
```
```
In kernel/trace/trace_kprobe.c (ffffffff8125a39b)
Location: kernel/trace/trace_probe.h:308
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:enable_trace_kprobe
  - kernel/trace/trace_kprobe.c:enable_trace_kprobe
  - kernel/trace/trace_kprobe.c:__disable_trace_kprobe
  - kernel/trace/trace_kprobe.c:__disable_trace_kprobe
```
```
In kernel/trace/trace_probe.c (ffffffff81264b03)
Location: kernel/trace/trace_probe.h:308
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:trace_probe_unlink
  - kernel/trace/trace_probe.c:trace_probe_append
  - kernel/trace/trace_probe.c:trace_probe_append
```
```
In kernel/trace/trace_uprobe.c (ffffffff81268136)
Location: kernel/trace/trace_probe.h:308
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:trace_uprobe_register
  - kernel/trace/trace_uprobe.c:trace_uprobe_register
  - kernel/trace/trace_uprobe.c:uprobe_perf_close
  - kernel/trace/trace_uprobe.c:uprobe_perf_close
  - kernel/trace/trace_uprobe.c:probe_event_enable
  - kernel/trace/trace_uprobe.c:probe_event_enable
  - kernel/trace/trace_uprobe.c:__probe_event_disable
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
In kernel/trace/trace_eprobe.c (ffffffff812933bd)
Location: kernel/trace/trace_probe.h:313
Inline: True
Inline callers:
  - kernel/trace/trace_eprobe.c:eprobe_register
  - kernel/trace/trace_eprobe.c:enable_trace_eprobe
  - kernel/trace/trace_eprobe.c:enable_trace_eprobe
  - kernel/trace/trace_eprobe.c:eprobe_dyn_event_release
```
```
In kernel/trace/trace_kprobe.c (ffffffff812aa7bb)
Location: kernel/trace/trace_probe.h:313
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:enable_trace_kprobe
  - kernel/trace/trace_kprobe.c:enable_trace_kprobe
  - kernel/trace/trace_kprobe.c:__disable_trace_kprobe
  - kernel/trace/trace_kprobe.c:__disable_trace_kprobe
```
```
In kernel/trace/trace_probe.c (ffffffff812b6673)
Location: kernel/trace/trace_probe.h:313
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:trace_probe_unlink
  - kernel/trace/trace_probe.c:trace_probe_append
  - kernel/trace/trace_probe.c:trace_probe_append
```
```
In kernel/trace/trace_uprobe.c (ffffffff812ba2e6)
Location: kernel/trace/trace_probe.h:313
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:trace_uprobe_register
  - kernel/trace/trace_uprobe.c:trace_uprobe_register
  - kernel/trace/trace_uprobe.c:uprobe_perf_close
  - kernel/trace/trace_uprobe.c:uprobe_perf_close
  - kernel/trace/trace_uprobe.c:probe_event_enable
  - kernel/trace/trace_uprobe.c:probe_event_enable
  - kernel/trace/trace_uprobe.c:__probe_event_disable
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
In kernel/trace/trace_eprobe.c (ffffffff812b058f)
Location: kernel/trace/trace_probe.h:317
Inline: True
Inline callers:
  - kernel/trace/trace_eprobe.c:eprobe_register
  - kernel/trace/trace_eprobe.c:enable_trace_eprobe
  - kernel/trace/trace_eprobe.c:enable_trace_eprobe
  - kernel/trace/trace_eprobe.c:enable_trace_eprobe
  - kernel/trace/trace_eprobe.c:enable_trace_eprobe
  - kernel/trace/trace_eprobe.c:eprobe_dyn_event_release
```
```
In kernel/trace/trace_kprobe.c (ffffffff812ccf7f)
Location: kernel/trace/trace_probe.h:317
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:enable_trace_kprobe
  - kernel/trace/trace_kprobe.c:enable_trace_kprobe
  - kernel/trace/trace_kprobe.c:__disable_trace_kprobe
  - kernel/trace/trace_kprobe.c:__disable_trace_kprobe
```
```
In kernel/trace/trace_probe.c (ffffffff812d9b63)
Location: kernel/trace/trace_probe.h:317
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:trace_probe_unlink
  - kernel/trace/trace_probe.c:trace_probe_append
  - kernel/trace/trace_probe.c:trace_probe_append
```
```
In kernel/trace/trace_uprobe.c (ffffffff812dd126)
Location: kernel/trace/trace_probe.h:317
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:trace_uprobe_register
  - kernel/trace/trace_uprobe.c:trace_uprobe_register
  - kernel/trace/trace_uprobe.c:uprobe_perf_close
  - kernel/trace/trace_uprobe.c:uprobe_perf_close
  - kernel/trace/trace_uprobe.c:probe_event_enable
  - kernel/trace/trace_uprobe.c:probe_event_enable
  - kernel/trace/trace_uprobe.c:__probe_event_disable
  - kernel/trace/trace_uprobe.c:trace_uprobe_release
```
```
In kernel/trace/trace_fprobe.c (ffffffff812df3a8)
Location: kernel/trace/trace_probe.h:317
Inline: True
Inline callers:
  - kernel/trace/trace_fprobe.c:disable_trace_fprobe
  - kernel/trace/trace_fprobe.c:enable_trace_fprobe
  - kernel/trace/trace_fprobe.c:enable_trace_fprobe
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
In kernel/trace/trace_eprobe.c (ffffffff812ccb59)
Location: kernel/trace/trace_probe.h:317
Inline: True
Inline callers:
  - kernel/trace/trace_eprobe.c:eprobe_register
  - kernel/trace/trace_eprobe.c:enable_trace_eprobe
  - kernel/trace/trace_eprobe.c:enable_trace_eprobe
  - kernel/trace/trace_eprobe.c:enable_trace_eprobe
  - kernel/trace/trace_eprobe.c:enable_trace_eprobe
  - kernel/trace/trace_eprobe.c:eprobe_dyn_event_release
```
```
In kernel/trace/trace_kprobe.c (ffffffff812ea96f)
Location: kernel/trace/trace_probe.h:317
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:enable_trace_kprobe
  - kernel/trace/trace_kprobe.c:enable_trace_kprobe
  - kernel/trace/trace_kprobe.c:__disable_trace_kprobe
  - kernel/trace/trace_kprobe.c:__disable_trace_kprobe
```
```
In kernel/trace/trace_probe.c (ffffffff812f7ac3)
Location: kernel/trace/trace_probe.h:317
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:trace_probe_unlink
  - kernel/trace/trace_probe.c:trace_probe_append
  - kernel/trace/trace_probe.c:trace_probe_append
```
```
In kernel/trace/trace_uprobe.c (ffffffff812fb206)
Location: kernel/trace/trace_probe.h:317
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:trace_uprobe_register
  - kernel/trace/trace_uprobe.c:trace_uprobe_register
  - kernel/trace/trace_uprobe.c:uprobe_perf_close
  - kernel/trace/trace_uprobe.c:uprobe_perf_close
  - kernel/trace/trace_uprobe.c:probe_event_enable
  - kernel/trace/trace_uprobe.c:probe_event_enable
  - kernel/trace/trace_uprobe.c:__probe_event_disable
  - kernel/trace/trace_uprobe.c:trace_uprobe_release
```
```
In kernel/trace/trace_fprobe.c (ffffffff812fd308)
Location: kernel/trace/trace_probe.h:317
Inline: True
Inline callers:
  - kernel/trace/trace_fprobe.c:disable_trace_fprobe
  - kernel/trace/trace_fprobe.c:enable_trace_fprobe
  - kernel/trace/trace_fprobe.c:enable_trace_fprobe
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
In kernel/trace/trace_kprobe.c (ffff80001024f8e4)
Location: kernel/trace/trace_probe.h:308
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:enable_trace_kprobe
  - kernel/trace/trace_kprobe.c:enable_trace_kprobe
  - kernel/trace/trace_kprobe.c:__disable_trace_kprobe
  - kernel/trace/trace_kprobe.c:__disable_trace_kprobe
```
```
In kernel/trace/trace_probe.c (ffff800010257ba8)
Location: kernel/trace/trace_probe.h:308
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:trace_probe_unlink
  - kernel/trace/trace_probe.c:trace_probe_append
  - kernel/trace/trace_probe.c:trace_probe_append
```
```
In kernel/trace/trace_uprobe.c (ffff80001025956c)
Location: kernel/trace/trace_probe.h:308
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:uprobe_perf_close
  - kernel/trace/trace_uprobe.c:uprobe_perf_close
  - kernel/trace/trace_uprobe.c:probe_event_enable
  - kernel/trace/trace_uprobe.c:probe_event_enable
  - kernel/trace/trace_uprobe.c:__probe_event_disable
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
In kernel/trace/trace_kprobe.c (c0482928)
Location: kernel/trace/trace_probe.h:308
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:enable_trace_kprobe
  - kernel/trace/trace_kprobe.c:enable_trace_kprobe
  - kernel/trace/trace_kprobe.c:__disable_trace_kprobe
  - kernel/trace/trace_kprobe.c:__disable_trace_kprobe
```
```
In kernel/trace/trace_probe.c (c048ad14)
Location: kernel/trace/trace_probe.h:308
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:trace_probe_unlink
  - kernel/trace/trace_probe.c:trace_probe_append
  - kernel/trace/trace_probe.c:trace_probe_append
```
```
In kernel/trace/trace_uprobe.c (c048b698)
Location: kernel/trace/trace_probe.h:308
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:uprobe_perf_close
  - kernel/trace/trace_uprobe.c:uprobe_perf_close
  - kernel/trace/trace_uprobe.c:probe_event_enable
  - kernel/trace/trace_uprobe.c:probe_event_enable
  - kernel/trace/trace_uprobe.c:__probe_event_disable
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
In kernel/trace/trace_kprobe.c (c0000000002ed01c)
Location: kernel/trace/trace_probe.h:308
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:enable_trace_kprobe
  - kernel/trace/trace_kprobe.c:enable_trace_kprobe
  - kernel/trace/trace_kprobe.c:__disable_trace_kprobe
  - kernel/trace/trace_kprobe.c:__disable_trace_kprobe
```
```
In kernel/trace/trace_probe.c (c0000000002f9b1c)
Location: kernel/trace/trace_probe.h:308
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:trace_probe_unlink
  - kernel/trace/trace_probe.c:trace_probe_append
  - kernel/trace/trace_probe.c:trace_probe_append
```
```
In kernel/trace/trace_uprobe.c (c0000000002fbabc)
Location: kernel/trace/trace_probe.h:308
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:uprobe_perf_close
  - kernel/trace/trace_uprobe.c:uprobe_perf_close
  - kernel/trace/trace_uprobe.c:probe_event_enable
  - kernel/trace/trace_uprobe.c:probe_event_enable
  - kernel/trace/trace_uprobe.c:__probe_event_disable
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
In kernel/trace/trace_kprobe.c (ffffffff811c7697)
Location: kernel/trace/trace_probe.h:308
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:enable_trace_kprobe
  - kernel/trace/trace_kprobe.c:enable_trace_kprobe
  - kernel/trace/trace_kprobe.c:__disable_trace_kprobe
  - kernel/trace/trace_kprobe.c:__disable_trace_kprobe
```
```
In kernel/trace/trace_probe.c (ffffffff811cfe5d)
Location: kernel/trace/trace_probe.h:308
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:trace_probe_unlink
  - kernel/trace/trace_probe.c:trace_probe_append
  - kernel/trace/trace_probe.c:trace_probe_append
```
```
In kernel/trace/trace_uprobe.c (ffffffff811d0ad0)
Location: kernel/trace/trace_probe.h:308
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:uprobe_perf_close
  - kernel/trace/trace_uprobe.c:uprobe_perf_close
  - kernel/trace/trace_uprobe.c:probe_event_enable
  - kernel/trace/trace_uprobe.c:probe_event_enable
  - kernel/trace/trace_uprobe.c:__probe_event_disable
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
In kernel/trace/trace_kprobe.c (ffffffff811ba477)
Location: kernel/trace/trace_probe.h:308
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:enable_trace_kprobe
  - kernel/trace/trace_kprobe.c:enable_trace_kprobe
  - kernel/trace/trace_kprobe.c:__disable_trace_kprobe
  - kernel/trace/trace_kprobe.c:__disable_trace_kprobe
```
```
In kernel/trace/trace_probe.c (ffffffff811c2c2d)
Location: kernel/trace/trace_probe.h:308
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:trace_probe_unlink
  - kernel/trace/trace_probe.c:trace_probe_append
  - kernel/trace/trace_probe.c:trace_probe_append
```
```
In kernel/trace/trace_uprobe.c (ffffffff811c38a0)
Location: kernel/trace/trace_probe.h:308
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:uprobe_perf_close
  - kernel/trace/trace_uprobe.c:uprobe_perf_close
  - kernel/trace/trace_uprobe.c:probe_event_enable
  - kernel/trace/trace_uprobe.c:probe_event_enable
  - kernel/trace/trace_uprobe.c:__probe_event_disable
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
In kernel/trace/trace_kprobe.c (ffffffff811c5467)
Location: kernel/trace/trace_probe.h:308
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:enable_trace_kprobe
  - kernel/trace/trace_kprobe.c:enable_trace_kprobe
  - kernel/trace/trace_kprobe.c:__disable_trace_kprobe
  - kernel/trace/trace_kprobe.c:__disable_trace_kprobe
```
```
In kernel/trace/trace_probe.c (ffffffff811cdc2d)
Location: kernel/trace/trace_probe.h:308
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:trace_probe_unlink
  - kernel/trace/trace_probe.c:trace_probe_append
  - kernel/trace/trace_probe.c:trace_probe_append
```
```
In kernel/trace/trace_uprobe.c (ffffffff811ce8a0)
Location: kernel/trace/trace_probe.h:308
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:uprobe_perf_close
  - kernel/trace/trace_uprobe.c:uprobe_perf_close
  - kernel/trace/trace_uprobe.c:probe_event_enable
  - kernel/trace/trace_uprobe.c:probe_event_enable
  - kernel/trace/trace_uprobe.c:__probe_event_disable
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
In kernel/trace/trace_kprobe.c (ffffffff811d36c7)
Location: kernel/trace/trace_probe.h:308
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:enable_trace_kprobe
  - kernel/trace/trace_kprobe.c:enable_trace_kprobe
  - kernel/trace/trace_kprobe.c:__disable_trace_kprobe
  - kernel/trace/trace_kprobe.c:__disable_trace_kprobe
```
```
In kernel/trace/trace_probe.c (ffffffff811dbe8d)
Location: kernel/trace/trace_probe.h:308
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:trace_probe_unlink
  - kernel/trace/trace_probe.c:trace_probe_append
  - kernel/trace/trace_probe.c:trace_probe_append
```
```
In kernel/trace/trace_uprobe.c (ffffffff811dcb02)
Location: kernel/trace/trace_probe.h:308
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:uprobe_perf_close
  - kernel/trace/trace_uprobe.c:uprobe_perf_close
  - kernel/trace/trace_uprobe.c:probe_event_enable
  - kernel/trace/trace_uprobe.c:probe_event_enable
  - kernel/trace/trace_uprobe.c:__probe_event_disable
  - kernel/trace/trace_uprobe.c:trace_uprobe_release
```
</details>
</li>
</ul>

## Differences
