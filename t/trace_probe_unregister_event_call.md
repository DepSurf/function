# Function: <code>trace_probe_unregister_event_call</code>

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
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kprobe.c (ffffffff811c4829)
Location: kernel/trace/trace_probe.h:279
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:trace_kprobe_create
  - kernel/trace/trace_kprobe.c:unregister_trace_kprobe
```
```
In kernel/trace/trace_uprobe.c (ffffffff811cd3c0)
Location: kernel/trace/trace_probe.h:279
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
In kernel/trace/trace_kprobe.c (ffffffff811cfc45)
Location: kernel/trace/trace_probe.h:320
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:register_trace_kprobe
```
```
In kernel/trace/trace_uprobe.c (ffffffff811d861d)
Location: kernel/trace/trace_probe.h:320
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
In kernel/trace/trace_kprobe.c (ffffffff811edd4d)
Location: kernel/trace/trace_probe.h:320
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:register_trace_kprobe
```
```
In kernel/trace/trace_uprobe.c (ffffffff811f64cf)
Location: kernel/trace/trace_probe.h:320
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
In kernel/trace/trace_kprobe.c (ffffffff811ebebd)
Location: kernel/trace/trace_probe.h:319
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:register_trace_kprobe
```
```
In kernel/trace/trace_uprobe.c (ffffffff811f4eaf)
Location: kernel/trace/trace_probe.h:319
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
In kernel/trace/trace_kprobe.c (ffffffff811eb5ee)
Location: kernel/trace/trace_probe.h:319
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:register_trace_kprobe
```
```
In kernel/trace/trace_uprobe.c (ffffffff811f5d9f)
Location: kernel/trace/trace_probe.h:319
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
In kernel/trace/trace_eprobe.c (ffffffff812098f3)
Location: kernel/trace/trace_probe.h:321
Inline: True
Inline callers:
  - kernel/trace/trace_eprobe.c:eprobe_dyn_event_release
```
```
In kernel/trace/trace_kprobe.c (ffffffff8121c47e)
Location: kernel/trace/trace_probe.h:321
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:register_trace_kprobe
```
```
In kernel/trace/trace_uprobe.c (ffffffff81227e8c)
Location: kernel/trace/trace_probe.h:321
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
In kernel/trace/trace_eprobe.c (ffffffff812460d7)
Location: kernel/trace/trace_probe.h:320
Inline: True
Inline callers:
  - kernel/trace/trace_eprobe.c:eprobe_dyn_event_release
```
```
In kernel/trace/trace_kprobe.c (ffffffff8125cf33)
Location: kernel/trace/trace_probe.h:320
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:register_trace_kprobe
```
```
In kernel/trace/trace_uprobe.c (ffffffff81267234)
Location: kernel/trace/trace_probe.h:320
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
In kernel/trace/trace_eprobe.c (ffffffff81292ff7)
Location: kernel/trace/trace_probe.h:325
Inline: True
Inline callers:
  - kernel/trace/trace_eprobe.c:eprobe_dyn_event_release
```
```
In kernel/trace/trace_kprobe.c (ffffffff812abf06)
Location: kernel/trace/trace_probe.h:325
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:register_trace_kprobe
```
```
In kernel/trace/trace_uprobe.c (ffffffff812b92a4)
Location: kernel/trace/trace_probe.h:325
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
In kernel/trace/trace_eprobe.c (ffffffff812b0177)
Location: kernel/trace/trace_probe.h:329
Inline: True
Inline callers:
  - kernel/trace/trace_eprobe.c:eprobe_dyn_event_release
```
```
In kernel/trace/trace_kprobe.c (ffffffff812ce706)
Location: kernel/trace/trace_probe.h:329
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:register_trace_kprobe
```
```
In kernel/trace/trace_uprobe.c (ffffffff812dc904)
Location: kernel/trace/trace_probe.h:329
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:trace_uprobe_release
```
```
In kernel/trace/trace_fprobe.c (ffffffff812e05c6)
Location: kernel/trace/trace_probe.h:329
Inline: True
Inline callers:
  - kernel/trace/trace_fprobe.c:register_trace_fprobe
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
In kernel/trace/trace_eprobe.c (ffffffff812cc6e7)
Location: kernel/trace/trace_probe.h:329
Inline: True
Inline callers:
  - kernel/trace/trace_eprobe.c:eprobe_dyn_event_release
```
```
In kernel/trace/trace_kprobe.c (ffffffff812ec106)
Location: kernel/trace/trace_probe.h:329
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:register_trace_kprobe
```
```
In kernel/trace/trace_uprobe.c (ffffffff812fa9e4)
Location: kernel/trace/trace_probe.h:329
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:trace_uprobe_release
```
```
In kernel/trace/trace_fprobe.c (ffffffff812fe526)
Location: kernel/trace/trace_probe.h:329
Inline: True
Inline callers:
  - kernel/trace/trace_fprobe.c:register_trace_fprobe
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
In kernel/trace/trace_kprobe.c (ffff80001025048c)
Location: kernel/trace/trace_probe.h:320
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:register_trace_kprobe
```
```
In kernel/trace/trace_uprobe.c (ffff800010258924)
Location: kernel/trace/trace_probe.h:320
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
In kernel/trace/trace_kprobe.c (c0483ecc)
Location: kernel/trace/trace_probe.h:320
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:register_trace_kprobe
```
```
In kernel/trace/trace_uprobe.c (c048b880)
Location: kernel/trace/trace_probe.h:320
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
In kernel/trace/trace_kprobe.c (c0000000002ee544)
Location: kernel/trace/trace_probe.h:320
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:register_trace_kprobe
```
```
In kernel/trace/trace_uprobe.c (c0000000002fbce0)
Location: kernel/trace/trace_probe.h:320
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
In kernel/trace/trace_kprobe.c (ffffffff811c8265)
Location: kernel/trace/trace_probe.h:320
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:register_trace_kprobe
```
```
In kernel/trace/trace_uprobe.c (ffffffff811d0c3d)
Location: kernel/trace/trace_probe.h:320
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
In kernel/trace/trace_kprobe.c (ffffffff811bb045)
Location: kernel/trace/trace_probe.h:320
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:register_trace_kprobe
```
```
In kernel/trace/trace_uprobe.c (ffffffff811c3a0d)
Location: kernel/trace/trace_probe.h:320
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
In kernel/trace/trace_kprobe.c (ffffffff811c6035)
Location: kernel/trace/trace_probe.h:320
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:register_trace_kprobe
```
```
In kernel/trace/trace_uprobe.c (ffffffff811cea0d)
Location: kernel/trace/trace_probe.h:320
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
In kernel/trace/trace_kprobe.c (ffffffff811d4295)
Location: kernel/trace/trace_probe.h:320
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:register_trace_kprobe
```
```
In kernel/trace/trace_uprobe.c (ffffffff811dcc7d)
Location: kernel/trace/trace_probe.h:320
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:trace_uprobe_release
```
</details>
</li>
</ul>

## Differences
