# Function: <code>trace_probe_has_single_file</code>

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
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kprobe.c (ffffffff811c37b0)
Location: kernel/trace/trace_probe.h:285
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:disable_trace_kprobe
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kprobe.c (ffffffff811cf191)
Location: kernel/trace/trace_probe.h:326
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:disable_trace_kprobe
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kprobe.c (ffffffff811eb441)
Location: kernel/trace/trace_probe.h:326
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:disable_trace_kprobe
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kprobe.c (ffffffff811e9591)
Location: kernel/trace/trace_probe.h:325
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:disable_trace_kprobe
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kprobe.c (ffffffff811ea421)
Location: kernel/trace/trace_probe.h:325
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:disable_trace_kprobe
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
In kernel/trace/trace_eprobe.c (ffffffff8120a3b6)
Location: kernel/trace/trace_probe.h:327
Inline: True
Inline callers:
  - kernel/trace/trace_eprobe.c:eprobe_register
```
```
In kernel/trace/trace_kprobe.c (ffffffff8121b261)
Location: kernel/trace/trace_probe.h:327
Inline: True
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
In kernel/trace/trace_eprobe.c (ffffffff81246353)
Location: kernel/trace/trace_probe.h:326
Inline: True
Inline callers:
  - kernel/trace/trace_eprobe.c:eprobe_register
```
```
In kernel/trace/trace_kprobe.c (ffffffff8125a4f0)
Location: kernel/trace/trace_probe.h:326
Inline: True
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
In kernel/trace/trace_eprobe.c (ffffffff81293353)
Location: kernel/trace/trace_probe.h:331
Inline: True
Inline callers:
  - kernel/trace/trace_eprobe.c:eprobe_register
```
```
In kernel/trace/trace_kprobe.c (ffffffff812aa920)
Location: kernel/trace/trace_probe.h:331
Inline: True
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
In kernel/trace/trace_eprobe.c (ffffffff812b0512)
Location: kernel/trace/trace_probe.h:335
Inline: True
Inline callers:
  - kernel/trace/trace_eprobe.c:eprobe_register
```
```
In kernel/trace/trace_kprobe.c (ffffffff812cd0f0)
Location: kernel/trace/trace_probe.h:335
Inline: True
```
```
In kernel/trace/trace_fprobe.c (ffffffff812df334)
Location: kernel/trace/trace_probe.h:335
Inline: True
Inline callers:
  - kernel/trace/trace_fprobe.c:disable_trace_fprobe
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
In kernel/trace/trace_eprobe.c (ffffffff812ccad2)
Location: kernel/trace/trace_probe.h:335
Inline: True
Inline callers:
  - kernel/trace/trace_eprobe.c:eprobe_register
```
```
In kernel/trace/trace_kprobe.c (ffffffff812eaae0)
Location: kernel/trace/trace_probe.h:335
Inline: True
```
```
In kernel/trace/trace_fprobe.c (ffffffff812fd294)
Location: kernel/trace/trace_probe.h:335
Inline: True
Inline callers:
  - kernel/trace/trace_fprobe.c:disable_trace_fprobe
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kprobe.c (ffff80001024fa18)
Location: kernel/trace/trace_probe.h:326
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:disable_trace_kprobe
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kprobe.c (c0482a5c)
Location: kernel/trace/trace_probe.h:326
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:disable_trace_kprobe
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kprobe.c (c0000000002ed1e8)
Location: kernel/trace/trace_probe.h:326
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:disable_trace_kprobe
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
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kprobe.c (ffffffff811c77b1)
Location: kernel/trace/trace_probe.h:326
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:disable_trace_kprobe
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kprobe.c (ffffffff811ba591)
Location: kernel/trace/trace_probe.h:326
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:disable_trace_kprobe
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kprobe.c (ffffffff811c5581)
Location: kernel/trace/trace_probe.h:326
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:disable_trace_kprobe
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kprobe.c (ffffffff811d37e1)
Location: kernel/trace/trace_probe.h:326
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:disable_trace_kprobe
```
</details>
</li>
</ul>

## Differences
