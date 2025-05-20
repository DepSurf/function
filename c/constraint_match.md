# Function: <code>constraint_match</code>

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
In arch/x86/events/intel/core.c (ffffffff8100d127)
Location: arch/x86/events/perf_event.h:60
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:icl_get_event_constraints
  - arch/x86/events/intel/core.c:intel_get_event_constraints
```
```
In arch/x86/events/intel/ds.c (ffffffff8101140a)
Location: arch/x86/events/perf_event.h:60
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:intel_pebs_constraints
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
In arch/x86/events/intel/core.c (ffffffff8100d597)
Location: arch/x86/events/perf_event.h:60
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:icl_get_event_constraints
  - arch/x86/events/intel/core.c:intel_get_event_constraints
```
```
In arch/x86/events/intel/ds.c (ffffffff81011aea)
Location: arch/x86/events/perf_event.h:60
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:intel_pebs_constraints
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
In arch/x86/events/intel/core.c (ffffffff8100e96f)
Location: arch/x86/events/perf_event.h:60
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:icl_get_event_constraints
  - arch/x86/events/intel/core.c:intel_get_event_constraints
```
```
In arch/x86/events/intel/ds.c (ffffffff81012f5a)
Location: arch/x86/events/perf_event.h:60
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:intel_pebs_constraints
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
In arch/x86/events/intel/core.c (ffffffff8100dd8f)
Location: arch/x86/events/perf_event.h:60
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:icl_get_event_constraints
  - arch/x86/events/intel/core.c:intel_get_event_constraints
  - arch/x86/events/intel/core.c:intel_get_event_constraints
```
```
In arch/x86/events/intel/ds.c (ffffffff81012b0a)
Location: arch/x86/events/perf_event.h:60
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:intel_pebs_constraints
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
In arch/x86/events/intel/core.c (ffffffff810101f3)
Location: arch/x86/events/perf_event.h:61
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:adl_get_event_constraints
  - arch/x86/events/intel/core.c:spr_get_event_constraints
  - arch/x86/events/intel/core.c:spr_get_event_constraints
  - arch/x86/events/intel/core.c:intel_get_event_constraints
  - arch/x86/events/intel/core.c:x86_get_event_constraints
```
```
In arch/x86/events/intel/ds.c (ffffffff81013cff)
Location: arch/x86/events/perf_event.h:61
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:intel_pebs_constraints
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
In arch/x86/events/intel/core.c (ffffffff81010d63)
Location: arch/x86/events/perf_event.h:61
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:adl_get_event_constraints
  - arch/x86/events/intel/core.c:spr_get_event_constraints
  - arch/x86/events/intel/core.c:spr_get_event_constraints
  - arch/x86/events/intel/core.c:intel_get_event_constraints
  - arch/x86/events/intel/core.c:x86_get_event_constraints
```
```
In arch/x86/events/intel/ds.c (ffffffff8101501c)
Location: arch/x86/events/perf_event.h:61
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:intel_pebs_constraints
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
In arch/x86/events/intel/core.c (ffffffff8101248e)
Location: arch/x86/events/perf_event.h:62
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:adl_get_event_constraints
  - arch/x86/events/intel/core.c:spr_get_event_constraints
  - arch/x86/events/intel/core.c:spr_get_event_constraints
  - arch/x86/events/intel/core.c:intel_get_event_constraints
  - arch/x86/events/intel/core.c:x86_get_event_constraints
```
```
In arch/x86/events/intel/ds.c (ffffffff81016ee3)
Location: arch/x86/events/perf_event.h:62
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:intel_pebs_constraints
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
In arch/x86/events/intel/core.c (ffffffff810163fe)
Location: arch/x86/events/perf_event.h:62
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:adl_get_event_constraints
  - arch/x86/events/intel/core.c:spr_get_event_constraints
  - arch/x86/events/intel/core.c:spr_get_event_constraints
  - arch/x86/events/intel/core.c:intel_get_event_constraints
  - arch/x86/events/intel/core.c:x86_get_event_constraints
```
```
In arch/x86/events/intel/ds.c (ffffffff8101b053)
Location: arch/x86/events/perf_event.h:62
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:intel_pebs_constraints
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
In arch/x86/events/intel/core.c (ffffffff81015c6e)
Location: arch/x86/events/perf_event.h:64
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:mtl_get_event_constraints
  - arch/x86/events/intel/core.c:mtl_get_event_constraints
  - arch/x86/events/intel/core.c:adl_get_event_constraints
  - arch/x86/events/intel/core.c:spr_get_event_constraints
  - arch/x86/events/intel/core.c:spr_get_event_constraints
  - arch/x86/events/intel/core.c:intel_get_event_constraints
  - arch/x86/events/intel/core.c:x86_get_event_constraints
```
```
In arch/x86/events/intel/ds.c (ffffffff8101ab03)
Location: arch/x86/events/perf_event.h:64
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:intel_pebs_constraints
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
In arch/x86/events/intel/core.c (ffffffff8101b753)
Location: arch/x86/events/perf_event.h:64
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:mtl_get_event_constraints
  - arch/x86/events/intel/core.c:cmt_get_event_constraints
  - arch/x86/events/intel/core.c:adl_get_event_constraints
  - arch/x86/events/intel/core.c:glc_get_event_constraints
  - arch/x86/events/intel/core.c:glc_get_event_constraints
  - arch/x86/events/intel/core.c:intel_get_event_constraints
  - arch/x86/events/intel/core.c:x86_get_event_constraints
```
```
In arch/x86/events/intel/ds.c (ffffffff81020663)
Location: arch/x86/events/perf_event.h:64
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:intel_pebs_constraints
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
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
In arch/x86/events/intel/core.c (ffffffff8100d597)
Location: arch/x86/events/perf_event.h:60
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:icl_get_event_constraints
  - arch/x86/events/intel/core.c:intel_get_event_constraints
```
```
In arch/x86/events/intel/ds.c (ffffffff81011aea)
Location: arch/x86/events/perf_event.h:60
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:intel_pebs_constraints
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
In arch/x86/events/intel/core.c (ffffffff8100bd97)
Location: arch/x86/events/perf_event.h:60
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:icl_get_event_constraints
  - arch/x86/events/intel/core.c:intel_get_event_constraints
```
```
In arch/x86/events/intel/ds.c (ffffffff810108ea)
Location: arch/x86/events/perf_event.h:60
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:intel_pebs_constraints
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
In arch/x86/events/intel/core.c (ffffffff8100d557)
Location: arch/x86/events/perf_event.h:60
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:icl_get_event_constraints
  - arch/x86/events/intel/core.c:intel_get_event_constraints
```
```
In arch/x86/events/intel/ds.c (ffffffff81011aaa)
Location: arch/x86/events/perf_event.h:60
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:intel_pebs_constraints
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
In arch/x86/events/intel/core.c (ffffffff8100d787)
Location: arch/x86/events/perf_event.h:60
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:icl_get_event_constraints
  - arch/x86/events/intel/core.c:intel_get_event_constraints
```
```
In arch/x86/events/intel/ds.c (ffffffff81011cca)
Location: arch/x86/events/perf_event.h:60
Inline: True
Inline callers:
  - arch/x86/events/intel/ds.c:intel_pebs_constraints
```
</details>
</li>
</ul>

## Differences
