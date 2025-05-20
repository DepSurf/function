# Function: <code>intel_pmu_lbr_read_32</code>

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
In arch/x86/events/intel/lbr.c (ffffffff81011e17)
Location: arch/x86/events/intel/lbr.c:391
Inline: True
Inline callers:
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_read
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
In arch/x86/events/intel/lbr.c (ffffffff81011829)
Location: arch/x86/events/intel/lbr.c:494
Inline: True
Inline callers:
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_read
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
In arch/x86/events/intel/lbr.c (ffffffff81011959)
Location: arch/x86/events/intel/lbr.c:488
Inline: True
Inline callers:
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_read
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
In arch/x86/events/intel/lbr.c (ffffffff8100fd5b)
Location: arch/x86/events/intel/lbr.c:492
Inline: True
Inline callers:
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_read
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
In arch/x86/events/intel/lbr.c (ffffffff810104eb)
Location: arch/x86/events/intel/lbr.c:496
Inline: True
Inline callers:
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_read
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
In arch/x86/events/intel/lbr.c (ffffffff8101116d)
Location: arch/x86/events/intel/lbr.c:509
Inline: True
Inline callers:
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_read
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
In arch/x86/events/intel/lbr.c (ffffffff810117cd)
Location: arch/x86/events/intel/lbr.c:531
Inline: True
Inline callers:
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_read
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
In arch/x86/events/intel/lbr.c (ffffffff810129f7)
Location: arch/x86/events/intel/lbr.c:536
Inline: True
Inline callers:
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_read
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
In arch/x86/events/intel/lbr.c (ffffffff810131a7)
Location: arch/x86/events/intel/lbr.c:536
Inline: True
Inline callers:
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_read
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void intel_pmu_lbr_read_32(struct cpu_hw_events *cpuc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/lbr.c (ffffffff81013e20)
Location: arch/x86/events/intel/lbr.c:559
Inline: False
Direct callers:
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_read
```
**Symbols:**

```
ffffffff81013e20-ffffffff81013ee2: intel_pmu_lbr_read_32 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void intel_pmu_lbr_read_32(struct cpu_hw_events *cpuc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/lbr.c (ffffffff81014c10)
Location: arch/x86/events/intel/lbr.c:770
Inline: False
```
**Symbols:**

```
ffffffff81014c10-ffffffff81014ccf: intel_pmu_lbr_read_32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void intel_pmu_lbr_read_32(struct cpu_hw_events *cpuc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/lbr.c (ffffffff81015e10)
Location: arch/x86/events/intel/lbr.c:786
Inline: False
```
**Symbols:**

```
ffffffff81015e10-ffffffff81015ecf: intel_pmu_lbr_read_32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void intel_pmu_lbr_read_32(struct cpu_hw_events *cpuc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/lbr.c (ffffffff81017480)
Location: arch/x86/events/intel/lbr.c:786
Inline: False
```
**Symbols:**

```
ffffffff81017480-ffffffff810176ab: intel_pmu_lbr_read_32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void intel_pmu_lbr_read_32(struct cpu_hw_events *cpuc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/lbr.c (ffffffff81019830)
Location: arch/x86/events/intel/lbr.c:769
Inline: False
```
**Symbols:**

```
ffffffff81019830-ffffffff810198ee: intel_pmu_lbr_read_32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void intel_pmu_lbr_read_32(struct cpu_hw_events *cpuc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/lbr.c (ffffffff8101d800)
Location: arch/x86/events/intel/lbr.c:709
Inline: False
```
**Symbols:**

```
ffffffff8101d800-ffffffff8101d8d4: intel_pmu_lbr_read_32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void intel_pmu_lbr_read_32(struct cpu_hw_events *cpuc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/lbr.c (ffffffff8101d500)
Location: arch/x86/events/intel/lbr.c:709
Inline: False
```
**Symbols:**

```
ffffffff8101d500-ffffffff8101d5d4: intel_pmu_lbr_read_32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void intel_pmu_lbr_read_32(struct cpu_hw_events *cpuc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/lbr.c (ffffffff810234d0)
Location: arch/x86/events/intel/lbr.c:728
Inline: False
```
**Symbols:**

```
ffffffff810234d0-ffffffff810235a4: intel_pmu_lbr_read_32 (STB_GLOBAL)
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
In arch/x86/events/intel/lbr.c (ffffffff810131a7)
Location: arch/x86/events/intel/lbr.c:536
Inline: True
Inline callers:
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_read
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
In arch/x86/events/intel/lbr.c (ffffffff81012289)
Location: arch/x86/events/intel/lbr.c:536
Inline: True
Inline callers:
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_read
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
In arch/x86/events/intel/lbr.c (ffffffff81013167)
Location: arch/x86/events/intel/lbr.c:536
Inline: True
Inline callers:
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_read
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
In arch/x86/events/intel/lbr.c (ffffffff81013387)
Location: arch/x86/events/intel/lbr.c:536
Inline: True
Inline callers:
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_read
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
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
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
