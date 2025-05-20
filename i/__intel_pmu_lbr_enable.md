# Function: <code>__intel_pmu_lbr_enable</code>

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
In arch/x86/events/intel/lbr.c (ffffffff81011b17)
Location: arch/x86/events/intel/lbr.c:138
Inline: True
Inline callers:
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_enable_all
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
In arch/x86/events/intel/lbr.c (ffffffff81011499)
Location: arch/x86/events/intel/lbr.c:149
Inline: True
Inline callers:
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_enable_all
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
In arch/x86/events/intel/lbr.c (ffffffff810115a9)
Location: arch/x86/events/intel/lbr.c:149
Inline: True
Inline callers:
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_enable_all
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
In arch/x86/events/intel/lbr.c (ffffffff8100fbda)
Location: arch/x86/events/intel/lbr.c:149
Inline: True
Inline callers:
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_enable_all
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
In arch/x86/events/intel/lbr.c (ffffffff8101037d)
Location: arch/x86/events/intel/lbr.c:153
Inline: True
Inline callers:
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_enable_all
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
In arch/x86/events/intel/lbr.c (ffffffff81010dcd)
Location: arch/x86/events/intel/lbr.c:153
Inline: True
Inline callers:
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_enable_all
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
In arch/x86/events/intel/lbr.c (ffffffff8101142d)
Location: arch/x86/events/intel/lbr.c:153
Inline: True
Inline callers:
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_enable_all
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
In arch/x86/events/intel/lbr.c (ffffffff81012882)
Location: arch/x86/events/intel/lbr.c:153
Inline: True
Inline callers:
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_enable_all
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
In arch/x86/events/intel/lbr.c (ffffffff81013032)
Location: arch/x86/events/intel/lbr.c:153
Inline: True
Inline callers:
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_enable_all
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
In arch/x86/events/intel/lbr.c (ffffffff810148f2)
Location: arch/x86/events/intel/lbr.c:153
Inline: True
Inline callers:
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_enable_all
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __intel_pmu_lbr_enable(bool pmi);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/lbr.c (ffffffff81014090)
Location: arch/x86/events/intel/lbr.c:188
Inline: False
Direct callers:
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_enable_all
```
**Symbols:**

```
ffffffff81014090-ffffffff81014172: __intel_pmu_lbr_enable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __intel_pmu_lbr_enable(bool pmi);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/lbr.c (ffffffff810151f0)
Location: arch/x86/events/intel/lbr.c:188
Inline: False
Direct callers:
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_enable_all
```
**Symbols:**

```
ffffffff810151f0-ffffffff810152da: __intel_pmu_lbr_enable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __intel_pmu_lbr_enable(bool pmi);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/lbr.c (ffffffff81016810)
Location: arch/x86/events/intel/lbr.c:188
Inline: False
Direct callers:
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_enable_all
```
**Symbols:**

```
ffffffff81016810-ffffffff810168fa: __intel_pmu_lbr_enable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __intel_pmu_lbr_enable(bool pmi);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/lbr.c (ffffffff81018a60)
Location: arch/x86/events/intel/lbr.c:180
Inline: False
Direct callers:
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_enable_all
```
**Symbols:**

```
ffffffff81018a60-ffffffff81018b7a: __intel_pmu_lbr_enable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __intel_pmu_lbr_enable(bool pmi);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/lbr.c (ffffffff8101c8f0)
Location: arch/x86/events/intel/lbr.c:120
Inline: False
Direct callers:
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_enable_all
```
**Symbols:**

```
ffffffff8101c8f0-ffffffff8101ca10: __intel_pmu_lbr_enable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __intel_pmu_lbr_enable(bool pmi);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/lbr.c (ffffffff8101c5b0)
Location: arch/x86/events/intel/lbr.c:120
Inline: False
Direct callers:
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_enable_all
```
**Symbols:**

```
ffffffff8101c5b0-ffffffff8101c6d0: __intel_pmu_lbr_enable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __intel_pmu_lbr_enable(bool pmi);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/intel/lbr.c (ffffffff81022540)
Location: arch/x86/events/intel/lbr.c:120
Inline: False
Direct callers:
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_enable_all
```
**Symbols:**

```
ffffffff81022540-ffffffff81022660: __intel_pmu_lbr_enable (STB_LOCAL)
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
In arch/x86/events/intel/lbr.c (ffffffff81013032)
Location: arch/x86/events/intel/lbr.c:153
Inline: True
Inline callers:
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_enable_all
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
In arch/x86/events/intel/lbr.c (ffffffff81012092)
Location: arch/x86/events/intel/lbr.c:153
Inline: True
Inline callers:
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_enable_all
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
In arch/x86/events/intel/lbr.c (ffffffff81012ff2)
Location: arch/x86/events/intel/lbr.c:153
Inline: True
Inline callers:
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_enable_all
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
In arch/x86/events/intel/lbr.c (ffffffff81013212)
Location: arch/x86/events/intel/lbr.c:153
Inline: True
Inline callers:
  - arch/x86/events/intel/lbr.c:intel_pmu_lbr_enable_all
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
