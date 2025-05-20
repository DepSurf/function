# Function: <code>intel_pmu_check_event_constraints</code>

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
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff831bdfbc)
Location: arch/x86/events/intel/core.c:5415
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_init
  - arch/x86/events/intel/core.c:intel_pmu_init
Direct callers:
  - arch/x86/events/intel/core.c:intel_pmu_init
  - arch/x86/events/intel/core.c:intel_pmu_init
```
**Symbols:**

```
ffffffff81bc431c-ffffffff81bc43c9: intel_pmu_check_event_constraints.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff8329e423)
Location: arch/x86/events/intel/core.c:5435
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_init
  - arch/x86/events/intel/core.c:intel_pmu_init
Direct callers:
  - arch/x86/events/intel/core.c:intel_pmu_init
  - arch/x86/events/intel/core.c:intel_pmu_init
```
**Symbols:**

```
ffffffff81c957f0-ffffffff81c95909: intel_pmu_check_event_constraints.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff8344cf6c)
Location: arch/x86/events/intel/core.c:5505
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_init
  - arch/x86/events/intel/core.c:intel_pmu_init
Direct callers:
  - arch/x86/events/intel/core.c:intel_pmu_init
  - arch/x86/events/intel/core.c:intel_pmu_init
```
**Symbols:**

```
ffffffff81e44cab-ffffffff81e44db4: intel_pmu_check_event_constraints.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff83e66c75)
Location: arch/x86/events/intel/core.c:5631
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_init
  - arch/x86/events/intel/core.c:intel_pmu_init
Direct callers:
  - arch/x86/events/intel/core.c:intel_pmu_init
  - arch/x86/events/intel/core.c:intel_pmu_init
```
**Symbols:**

```
ffffffff810126c0-ffffffff810127c9: intel_pmu_check_event_constraints.part.0 (STB_LOCAL)
ffffffff82050671-ffffffff820506e1: intel_pmu_check_event_constraints.part.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff83687318)
Location: arch/x86/events/intel/core.c:5797
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_init
  - arch/x86/events/intel/core.c:intel_pmu_init
Direct callers:
  - arch/x86/events/intel/core.c:intel_pmu_init
  - arch/x86/events/intel/core.c:intel_pmu_init
```
**Symbols:**

```
ffffffff81011c30-ffffffff81011d39: intel_pmu_check_event_constraints.part.0 (STB_LOCAL)
ffffffff820ceaad-ffffffff820ceb1d: intel_pmu_check_event_constraints.part.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff838b657a)
Location: arch/x86/events/intel/core.c:5984
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_init
  - arch/x86/events/intel/core.c:init_hybrid_pmu
Direct callers:
  - arch/x86/events/intel/core.c:intel_pmu_init
  - arch/x86/events/intel/core.c:init_hybrid_pmu
```
**Symbols:**

```
ffffffff81017430-ffffffff81017539: intel_pmu_check_event_constraints.part.0 (STB_LOCAL)
ffffffff821a9308-ffffffff821a9378: intel_pmu_check_event_constraints.part.0.cold (STB_LOCAL)
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
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
