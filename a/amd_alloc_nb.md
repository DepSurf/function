# Function: <code>amd_alloc_nb</code>

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
In arch/x86/events/amd/core.c (ffffffff8100807e)
Location: arch/x86/events/amd/core.c:345
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_pmu_cpu_prepare
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
In arch/x86/events/amd/core.c (ffffffff810082cf)
Location: arch/x86/events/amd/core.c:345
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_pmu_cpu_prepare
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
In arch/x86/events/amd/core.c (ffffffff810082ef)
Location: arch/x86/events/amd/core.c:345
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_pmu_cpu_prepare
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
In arch/x86/events/amd/core.c (ffffffff81007fc8)
Location: arch/x86/events/amd/core.c:345
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_pmu_cpu_prepare
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
In arch/x86/events/amd/core.c (ffffffff81008448)
Location: arch/x86/events/amd/core.c:345
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_pmu_cpu_prepare
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
In arch/x86/events/amd/core.c (ffffffff81008bf8)
Location: arch/x86/events/amd/core.c:345
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_pmu_cpu_prepare
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
In arch/x86/events/amd/core.c (ffffffff81008b18)
Location: arch/x86/events/amd/core.c:345
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_pmu_cpu_prepare
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
In arch/x86/events/amd/core.c (ffffffff810090b8)
Location: arch/x86/events/amd/core.c:471
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_pmu_cpu_prepare
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
In arch/x86/events/amd/core.c (ffffffff81009468)
Location: arch/x86/events/amd/core.c:492
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_pmu_cpu_prepare
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct amd_nb *amd_alloc_nb(int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/amd/core.c (ffffffff8100a430)
Location: arch/x86/events/amd/core.c:492
Inline: False
Direct callers:
  - arch/x86/events/amd/core.c:amd_pmu_cpu_prepare
```
**Symbols:**

```
ffffffff8100a430-ffffffff8100a4b1: amd_alloc_nb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct amd_nb *amd_alloc_nb(int cpu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/amd/core.c (ffffffff810092b0)
Location: arch/x86/events/amd/core.c:492
Inline: False
Direct callers:
  - arch/x86/events/amd/core.c:amd_pmu_cpu_prepare
```
**Symbols:**

```
ffffffff810092b0-ffffffff81009331: amd_alloc_nb (STB_LOCAL)
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
In arch/x86/events/amd/core.c (ffffffff81009ccf)
Location: arch/x86/events/amd/core.c:492
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_pmu_cpu_prepare
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
In arch/x86/events/amd/core.c (ffffffff8100ada4)
Location: arch/x86/events/amd/core.c:492
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_pmu_cpu_prepare
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
In arch/x86/events/amd/core.c (ffffffff8100a4b0)
Location: arch/x86/events/amd/core.c:564
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_pmu_cpu_prepare
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
In arch/x86/events/amd/core.c (ffffffff8100c085)
Location: arch/x86/events/amd/core.c:502
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_pmu_cpu_prepare
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
In arch/x86/events/amd/core.c (ffffffff8100b82d)
Location: arch/x86/events/amd/core.c:502
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_pmu_cpu_prepare
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
In arch/x86/events/amd/core.c (ffffffff81010fde)
Location: arch/x86/events/amd/core.c:502
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_pmu_cpu_prepare
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
In arch/x86/events/amd/core.c (ffffffff81009468)
Location: arch/x86/events/amd/core.c:492
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_pmu_cpu_prepare
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
In arch/x86/events/amd/core.c (ffffffff81007bf8)
Location: arch/x86/events/amd/core.c:492
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_pmu_cpu_prepare
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
In arch/x86/events/amd/core.c (ffffffff81009428)
Location: arch/x86/events/amd/core.c:492
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_pmu_cpu_prepare
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
In arch/x86/events/amd/core.c (ffffffff81009588)
Location: arch/x86/events/amd/core.c:492
Inline: True
Inline callers:
  - arch/x86/events/amd/core.c:amd_pmu_cpu_prepare
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
</ul>
