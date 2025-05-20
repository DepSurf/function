# Function: <code>intel_pmu_enable_fixed</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff8100bf7a)
Location: arch/x86/events/intel/core.c:1698
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_enable_event
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff8100c1c6)
Location: arch/x86/events/intel/core.c:1927
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_enable_event
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff8100c26f)
Location: arch/x86/events/intel/core.c:1928
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_enable_event
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff8100bff9)
Location: arch/x86/events/intel/core.c:2063
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_enable_event
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff8100c79f)
Location: arch/x86/events/intel/core.c:2063
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_enable_event
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff8100cf17)
Location: arch/x86/events/intel/core.c:2071
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_enable_event
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff8100d2d0)
Location: arch/x86/events/intel/core.c:2120
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_enable_event
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff8100db44)
Location: arch/x86/events/intel/core.c:2192
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_enable_event
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
In arch/x86/events/intel/core.c (ffffffff8100e17f)
Location: arch/x86/events/intel/core.c:2193
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_enable_event
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void intel_pmu_enable_fixed(struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff8100e310)
Location: arch/x86/events/intel/core.c:2200
Inline: False
Direct callers:
  - arch/x86/events/intel/core.c:intel_pmu_enable_event
```
**Symbols:**

```
ffffffff8100e310-ffffffff8100e3e7: intel_pmu_enable_fixed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void intel_pmu_enable_fixed(struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff8100d740)
Location: arch/x86/events/intel/core.c:2446
Inline: False
Direct callers:
  - arch/x86/events/intel/core.c:intel_pmu_enable_event
```
**Symbols:**

```
ffffffff8100d740-ffffffff8100d8db: intel_pmu_enable_fixed (STB_LOCAL)
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
In arch/x86/events/intel/core.c (ffffffff8100f836)
Location: arch/x86/events/intel/core.c:2628
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_enable_event
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void intel_pmu_enable_fixed(struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/events/intel/core.c (0)
Location: arch/x86/events/intel/core.c:2630
Inline: False
Direct callers:
  - arch/x86/events/intel/core.c:intel_pmu_enable_event
```
**Symbols:**

```
ffffffff8100ecf0-ffffffff8100eed4: intel_pmu_enable_fixed (STB_LOCAL)
ffffffff81c95b33-ffffffff81c95bb4: intel_pmu_enable_fixed.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void intel_pmu_enable_fixed(struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/events/intel/core.c (0)
Location: arch/x86/events/intel/core.c:2698
Inline: False
Direct callers:
  - arch/x86/events/intel/core.c:intel_pmu_enable_event
```
**Symbols:**

```
ffffffff810100d0-ffffffff810102bd: intel_pmu_enable_fixed (STB_LOCAL)
ffffffff81e44ea0-ffffffff81e44f00: intel_pmu_enable_fixed.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void intel_pmu_enable_fixed(struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/events/intel/core.c (0)
Location: arch/x86/events/intel/core.c:2716
Inline: False
Direct callers:
  - arch/x86/events/intel/core.c:intel_pmu_enable_event
```
**Symbols:**

```
ffffffff81013980-ffffffff81013b3b: intel_pmu_enable_fixed (STB_LOCAL)
ffffffff8205070a-ffffffff82050774: intel_pmu_enable_fixed.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void intel_pmu_enable_fixed(struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/events/intel/core.c (0)
Location: arch/x86/events/intel/core.c:2736
Inline: False
Direct callers:
  - arch/x86/events/intel/core.c:intel_pmu_enable_event
```
**Symbols:**

```
ffffffff81012f30-ffffffff81013101: intel_pmu_enable_fixed (STB_LOCAL)
ffffffff820ceb46-ffffffff820cebba: intel_pmu_enable_fixed.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void intel_pmu_enable_fixed(struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/events/intel/core.c (0)
Location: arch/x86/events/intel/core.c:2741
Inline: False
Direct callers:
  - arch/x86/events/intel/core.c:intel_pmu_enable_event
```
**Symbols:**

```
ffffffff810185d0-ffffffff810187a1: intel_pmu_enable_fixed (STB_LOCAL)
ffffffff821a93a1-ffffffff821a9415: intel_pmu_enable_fixed.cold (STB_LOCAL)
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
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff8100e17f)
Location: arch/x86/events/intel/core.c:2193
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_enable_event
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
In arch/x86/events/intel/core.c (ffffffff8100cc1b)
Location: arch/x86/events/intel/core.c:2193
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_enable_event
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
In arch/x86/events/intel/core.c (ffffffff8100e13f)
Location: arch/x86/events/intel/core.c:2193
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_enable_event
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
In arch/x86/events/intel/core.c (ffffffff8100e30f)
Location: arch/x86/events/intel/core.c:2193
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_enable_event
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
