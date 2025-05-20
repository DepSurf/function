# Function: <code>intel_pmu_check_extra_regs</code>

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
In arch/x86/events/intel/core.c (ffffffff831be047)
Location: arch/x86/events/intel/core.c:5458
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
ffffffff81bc44e1-ffffffff81bc4520: intel_pmu_check_extra_regs.part.0 (STB_LOCAL)
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
In arch/x86/events/intel/core.c (ffffffff8329e4ae)
Location: arch/x86/events/intel/core.c:5478
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
ffffffff81c95a56-ffffffff81c95ab1: intel_pmu_check_extra_regs.part.0 (STB_LOCAL)
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
In arch/x86/events/intel/core.c (ffffffff8344d04e)
Location: arch/x86/events/intel/core.c:5552
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
ffffffff81e44e14-ffffffff81e44e77: intel_pmu_check_extra_regs.part.0 (STB_LOCAL)
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
In arch/x86/events/intel/core.c (ffffffff83e66cd3)
Location: arch/x86/events/intel/core.c:5678
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
ffffffff81014ff0-ffffffff8101505a: intel_pmu_check_extra_regs.part.0 (STB_LOCAL)
ffffffff82050774-ffffffff8205078f: intel_pmu_check_extra_regs.part.0.cold (STB_LOCAL)
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
In arch/x86/events/intel/core.c (ffffffff8368737a)
Location: arch/x86/events/intel/core.c:5844
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
ffffffff81014850-ffffffff810148ba: intel_pmu_check_extra_regs.part.0 (STB_LOCAL)
ffffffff820cebba-ffffffff820cebd5: intel_pmu_check_extra_regs.part.0.cold (STB_LOCAL)
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
In arch/x86/events/intel/core.c (ffffffff838b65dc)
Location: arch/x86/events/intel/core.c:6031
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
ffffffff8101a300-ffffffff8101a36a: intel_pmu_check_extra_regs.part.0 (STB_LOCAL)
ffffffff821a943d-ffffffff821a9458: intel_pmu_check_extra_regs.part.0.cold (STB_LOCAL)
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
