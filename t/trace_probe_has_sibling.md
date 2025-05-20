# Function: <code>trace_probe_has_sibling</code>

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
In kernel/trace/trace_kprobe.c (ffffffff811cf6d0)
Location: kernel/trace/trace_probe.h:313
Inline: True
```
```
In kernel/trace/trace_probe.c (ffffffff811d7780)
Location: kernel/trace/trace_probe.h:313
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:trace_probe_append
```
```
In kernel/trace/trace_uprobe.c (ffffffff811d85a0)
Location: kernel/trace/trace_probe.h:313
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
In kernel/trace/trace_kprobe.c (ffffffff811ed41d)
Location: kernel/trace/trace_probe.h:313
Inline: True
```
```
In kernel/trace/trace_probe.c (ffffffff811f40a0)
Location: kernel/trace/trace_probe.h:313
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:trace_probe_append
```
```
In kernel/trace/trace_uprobe.c (ffffffff811f643a)
Location: kernel/trace/trace_probe.h:313
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
In kernel/trace/trace_kprobe.c (ffffffff811eb56d)
Location: kernel/trace/trace_probe.h:312
Inline: True
```
```
In kernel/trace/trace_probe.c (ffffffff811f2a63)
Location: kernel/trace/trace_probe.h:312
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:trace_probe_append
```
```
In kernel/trace/trace_uprobe.c (ffffffff811f4e1a)
Location: kernel/trace/trace_probe.h:312
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
In kernel/trace/trace_kprobe.c (ffffffff811ec93d)
Location: kernel/trace/trace_probe.h:312
Inline: True
```
```
In kernel/trace/trace_probe.c (ffffffff811f38f3)
Location: kernel/trace/trace_probe.h:312
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:trace_probe_append
```
```
In kernel/trace/trace_uprobe.c (ffffffff811f5d0a)
Location: kernel/trace/trace_probe.h:312
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
In kernel/trace/trace_eprobe.c (ffffffff81209880)
Location: kernel/trace/trace_probe.h:314
Inline: True
Inline callers:
  - kernel/trace/trace_eprobe.c:eprobe_dyn_event_release
```
```
In kernel/trace/trace_kprobe.c (ffffffff8121d99d)
Location: kernel/trace/trace_probe.h:314
Inline: True
```
```
In kernel/trace/trace_probe.c (ffffffff81224bb3)
Location: kernel/trace/trace_probe.h:314
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:trace_probe_append
```
```
In kernel/trace/trace_uprobe.c (ffffffff81227dea)
Location: kernel/trace/trace_probe.h:314
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
In kernel/trace/trace_eprobe.c (ffffffff81246060)
Location: kernel/trace/trace_probe.h:313
Inline: True
Inline callers:
  - kernel/trace/trace_eprobe.c:eprobe_dyn_event_release
```
```
In kernel/trace/trace_kprobe.c (ffffffff8125cf6d)
Location: kernel/trace/trace_probe.h:313
Inline: True
```
```
In kernel/trace/trace_probe.c (ffffffff81264a13)
Location: kernel/trace/trace_probe.h:313
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:trace_probe_append
```
```
In kernel/trace/trace_uprobe.c (ffffffff8126719a)
Location: kernel/trace/trace_probe.h:313
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
In kernel/trace/trace_eprobe.c (ffffffff81292f80)
Location: kernel/trace/trace_probe.h:318
Inline: True
Inline callers:
  - kernel/trace/trace_eprobe.c:eprobe_dyn_event_release
```
```
In kernel/trace/trace_kprobe.c (ffffffff812ac1fd)
Location: kernel/trace/trace_probe.h:318
Inline: True
```
```
In kernel/trace/trace_probe.c (ffffffff812b6573)
Location: kernel/trace/trace_probe.h:318
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:trace_probe_append
```
```
In kernel/trace/trace_uprobe.c (ffffffff812b920a)
Location: kernel/trace/trace_probe.h:318
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
In kernel/trace/trace_eprobe.c (ffffffff812b0100)
Location: kernel/trace/trace_probe.h:322
Inline: True
Inline callers:
  - kernel/trace/trace_eprobe.c:eprobe_dyn_event_release
```
```
In kernel/trace/trace_kprobe.c (ffffffff812ce9fd)
Location: kernel/trace/trace_probe.h:322
Inline: True
```
```
In kernel/trace/trace_probe.c (ffffffff812d9a63)
Location: kernel/trace/trace_probe.h:322
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:trace_probe_append
```
```
In kernel/trace/trace_uprobe.c (ffffffff812dc86a)
Location: kernel/trace/trace_probe.h:322
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:trace_uprobe_release
```
```
In kernel/trace/trace_fprobe.c (ffffffff812dfeed)
Location: kernel/trace/trace_probe.h:322
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
In kernel/trace/trace_eprobe.c (ffffffff812cc670)
Location: kernel/trace/trace_probe.h:322
Inline: True
Inline callers:
  - kernel/trace/trace_eprobe.c:eprobe_dyn_event_release
```
```
In kernel/trace/trace_kprobe.c (ffffffff812ec3fd)
Location: kernel/trace/trace_probe.h:322
Inline: True
```
```
In kernel/trace/trace_probe.c (ffffffff812f79c3)
Location: kernel/trace/trace_probe.h:322
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:trace_probe_append
```
```
In kernel/trace/trace_uprobe.c (ffffffff812fa94a)
Location: kernel/trace/trace_probe.h:322
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:trace_uprobe_release
```
```
In kernel/trace/trace_fprobe.c (ffffffff812fdd0d)
Location: kernel/trace/trace_probe.h:322
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
In kernel/trace/trace_kprobe.c (ffff80001024fe90)
Location: kernel/trace/trace_probe.h:313
Inline: True
```
```
In kernel/trace/trace_probe.c (ffff800010257ae8)
Location: kernel/trace/trace_probe.h:313
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:trace_probe_append
```
```
In kernel/trace/trace_uprobe.c (ffff8000102588a0)
Location: kernel/trace/trace_probe.h:313
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
In kernel/trace/trace_kprobe.c (c0482d2c)
Location: kernel/trace/trace_probe.h:313
Inline: True
```
```
In kernel/trace/trace_probe.c (c048ac70)
Location: kernel/trace/trace_probe.h:313
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:trace_probe_append
```
```
In kernel/trace/trace_uprobe.c (c048b818)
Location: kernel/trace/trace_probe.h:313
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
In kernel/trace/trace_kprobe.c (c0000000002eda58)
Location: kernel/trace/trace_probe.h:313
Inline: True
```
```
In kernel/trace/trace_probe.c (c0000000002f9a34)
Location: kernel/trace/trace_probe.h:313
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:trace_probe_append
```
```
In kernel/trace/trace_uprobe.c (c0000000002fbc4c)
Location: kernel/trace/trace_probe.h:313
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
In kernel/trace/trace_kprobe.c (ffffffff811c7cf0)
Location: kernel/trace/trace_probe.h:313
Inline: True
```
```
In kernel/trace/trace_probe.c (ffffffff811cfda0)
Location: kernel/trace/trace_probe.h:313
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:trace_probe_append
```
```
In kernel/trace/trace_uprobe.c (ffffffff811d0bc0)
Location: kernel/trace/trace_probe.h:313
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
In kernel/trace/trace_kprobe.c (ffffffff811baad0)
Location: kernel/trace/trace_probe.h:313
Inline: True
```
```
In kernel/trace/trace_probe.c (ffffffff811c2b70)
Location: kernel/trace/trace_probe.h:313
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:trace_probe_append
```
```
In kernel/trace/trace_uprobe.c (ffffffff811c3990)
Location: kernel/trace/trace_probe.h:313
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
In kernel/trace/trace_kprobe.c (ffffffff811c5ac0)
Location: kernel/trace/trace_probe.h:313
Inline: True
```
```
In kernel/trace/trace_probe.c (ffffffff811cdb70)
Location: kernel/trace/trace_probe.h:313
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:trace_probe_append
```
```
In kernel/trace/trace_uprobe.c (ffffffff811ce990)
Location: kernel/trace/trace_probe.h:313
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
In kernel/trace/trace_kprobe.c (ffffffff811d3d20)
Location: kernel/trace/trace_probe.h:313
Inline: True
```
```
In kernel/trace/trace_probe.c (ffffffff811dbdd0)
Location: kernel/trace/trace_probe.h:313
Inline: True
Inline callers:
  - kernel/trace/trace_probe.c:trace_probe_append
```
```
In kernel/trace/trace_uprobe.c (ffffffff811dcc00)
Location: kernel/trace/trace_probe.h:313
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:trace_uprobe_release
```
</details>
</li>
</ul>

## Differences
