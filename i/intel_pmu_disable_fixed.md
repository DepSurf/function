# Function: <code>intel_pmu_disable_fixed</code>

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
In arch/x86/events/intel/core.c (ffffffff8100b37b)
Location: arch/x86/events/intel/core.c:1648
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_disable_event
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
In arch/x86/events/intel/core.c (ffffffff8100b428)
Location: arch/x86/events/intel/core.c:1877
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_disable_event
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
In arch/x86/events/intel/core.c (ffffffff8100b4f3)
Location: arch/x86/events/intel/core.c:1877
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_disable_event
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
In arch/x86/events/intel/core.c (ffffffff8100aff3)
Location: arch/x86/events/intel/core.c:2012
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_disable_event
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
In arch/x86/events/intel/core.c (ffffffff8100c643)
Location: arch/x86/events/intel/core.c:2012
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_disable_event
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
In arch/x86/events/intel/core.c (ffffffff8100cda0)
Location: arch/x86/events/intel/core.c:2012
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_disable_event
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
In arch/x86/events/intel/core.c (ffffffff8100d147)
Location: arch/x86/events/intel/core.c:2061
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_disable_event
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
In arch/x86/events/intel/core.c (ffffffff8100d9aa)
Location: arch/x86/events/intel/core.c:2131
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_disable_event
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
In arch/x86/events/intel/core.c (ffffffff8100df9a)
Location: arch/x86/events/intel/core.c:2132
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_disable_event
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
In arch/x86/events/intel/core.c (ffffffff8100f9fc)
Location: arch/x86/events/intel/core.c:2139
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_disable_event
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void intel_pmu_disable_fixed(struct perf_event *event);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff8100d4e0)
Location: arch/x86/events/intel/core.c:2189
Inline: False
Direct callers:
  - arch/x86/events/intel/core.c:intel_pmu_disable_event
```
**Symbols:**

```
ffffffff8100d4e0-ffffffff8100d5b0: intel_pmu_disable_fixed (STB_LOCAL)
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
In arch/x86/events/intel/core.c (ffffffff8100f124)
Location: arch/x86/events/intel/core.c:2343
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_disable_event
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff8100fec4)
Location: arch/x86/events/intel/core.c:2345
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_disable_event
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff810115b1)
Location: arch/x86/events/intel/core.c:2407
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_disable_event
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff81014dd4)
Location: arch/x86/events/intel/core.c:2423
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_disable_event
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff8101462b)
Location: arch/x86/events/intel/core.c:2443
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_disable_event
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff810197eb)
Location: arch/x86/events/intel/core.c:2463
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_disable_event
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
In arch/x86/events/intel/core.c (ffffffff8100df9a)
Location: arch/x86/events/intel/core.c:2132
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_disable_event
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
In arch/x86/events/intel/core.c (ffffffff8100c9ca)
Location: arch/x86/events/intel/core.c:2132
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_disable_event
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
In arch/x86/events/intel/core.c (ffffffff8100df5a)
Location: arch/x86/events/intel/core.c:2132
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_disable_event
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
In arch/x86/events/intel/core.c (ffffffff8100e12a)
Location: arch/x86/events/intel/core.c:2132
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_disable_event
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
