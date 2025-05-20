# Function: <code>intel_pmu_reset</code>

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
In arch/x86/events/intel/core.c (ffffffff8100c5a4)
Location: arch/x86/events/intel/core.c:1788
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
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
In arch/x86/events/intel/core.c (ffffffff8100c814)
Location: arch/x86/events/intel/core.c:2017
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
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
In arch/x86/events/intel/core.c (ffffffff8100c8dc)
Location: arch/x86/events/intel/core.c:2020
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
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
In arch/x86/events/intel/core.c (ffffffff8100c620)
Location: arch/x86/events/intel/core.c:2155
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
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
In arch/x86/events/intel/core.c (ffffffff8100cbcc)
Location: arch/x86/events/intel/core.c:2155
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
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
In arch/x86/events/intel/core.c (ffffffff8100d2fd)
Location: arch/x86/events/intel/core.c:2163
Inline: True
Inline callers:
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void intel_pmu_reset();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff8100b580)
Location: arch/x86/events/intel/core.c:2214
Inline: False
Direct callers:
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
```
**Symbols:**

```
ffffffff8100b580-ffffffff8100b6fc: intel_pmu_reset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void intel_pmu_reset();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff8100bb90)
Location: arch/x86/events/intel/core.c:2291
Inline: False
Direct callers:
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
```
**Symbols:**

```
ffffffff8100bb90-ffffffff8100bd0c: intel_pmu_reset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void intel_pmu_reset();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff8100bfa0)
Location: arch/x86/events/intel/core.c:2292
Inline: False
Direct callers:
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
```
**Symbols:**

```
ffffffff8100bfa0-ffffffff8100c11c: intel_pmu_reset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void intel_pmu_reset();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff8100ef60)
Location: arch/x86/events/intel/core.c:2299
Inline: False
Direct callers:
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
```
**Symbols:**

```
ffffffff8100ef60-ffffffff8100f0e3: intel_pmu_reset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void intel_pmu_reset();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff8100e2d0)
Location: arch/x86/events/intel/core.c:2559
Inline: False
Direct callers:
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
```
**Symbols:**

```
ffffffff8100e2d0-ffffffff8100e453: intel_pmu_reset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void intel_pmu_reset();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff8100f280)
Location: arch/x86/events/intel/core.c:2741
Inline: False
Direct callers:
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
```
**Symbols:**

```
ffffffff8100f280-ffffffff8100f4ac: intel_pmu_reset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void intel_pmu_reset();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/events/intel/core.c (0)
Location: arch/x86/events/intel/core.c:2743
Inline: False
Direct callers:
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
```
**Symbols:**

```
ffffffff81010050-ffffffff8101027f: intel_pmu_reset (STB_LOCAL)
ffffffff81c95be1-ffffffff81c95c06: intel_pmu_reset.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void intel_pmu_reset();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/events/intel/core.c (0)
Location: arch/x86/events/intel/core.c:2811
Inline: False
Direct callers:
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
```
**Symbols:**

```
ffffffff81011650-ffffffff81011893: intel_pmu_reset (STB_LOCAL)
ffffffff81e44f14-ffffffff81e44f39: intel_pmu_reset.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void intel_pmu_reset();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/events/intel/core.c (0)
Location: arch/x86/events/intel/core.c:2844
Inline: False
Direct callers:
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
```
**Symbols:**

```
ffffffff81015070-ffffffff810152cc: intel_pmu_reset (STB_LOCAL)
ffffffff8205078f-ffffffff820507ac: intel_pmu_reset.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void intel_pmu_reset();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/events/intel/core.c (0)
Location: arch/x86/events/intel/core.c:2864
Inline: False
Direct callers:
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
```
**Symbols:**

```
ffffffff810148d0-ffffffff81014b2f: intel_pmu_reset (STB_LOCAL)
ffffffff820cebd5-ffffffff820cebe9: intel_pmu_reset.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void intel_pmu_reset();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/events/intel/core.c (0)
Location: arch/x86/events/intel/core.c:2872
Inline: False
Direct callers:
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
```
**Symbols:**

```
ffffffff810198c0-ffffffff81019b1f: intel_pmu_reset (STB_LOCAL)
ffffffff821a9415-ffffffff821a9429: intel_pmu_reset.cold (STB_LOCAL)
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
<summary>In <code>aws</code>: ✅</summary>

```c
void intel_pmu_reset();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff8100bfa0)
Location: arch/x86/events/intel/core.c:2292
Inline: False
Direct callers:
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
```
**Symbols:**

```
ffffffff8100bfa0-ffffffff8100c11c: intel_pmu_reset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void intel_pmu_reset();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff8100cd00)
Location: arch/x86/events/intel/core.c:2292
Inline: False
Direct callers:
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
```
**Symbols:**

```
ffffffff8100cd00-ffffffff8100cea5: intel_pmu_reset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void intel_pmu_reset();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff8100bf60)
Location: arch/x86/events/intel/core.c:2292
Inline: False
Direct callers:
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
```
**Symbols:**

```
ffffffff8100bf60-ffffffff8100c0dc: intel_pmu_reset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void intel_pmu_reset();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/core.c (ffffffff8100c190)
Location: arch/x86/events/intel/core.c:2292
Inline: False
Direct callers:
  - arch/x86/events/intel/core.c:intel_pmu_handle_irq
```
**Symbols:**

```
ffffffff8100c190-ffffffff8100c30c: intel_pmu_reset (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
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
<b>Arch</b>
<ul>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
