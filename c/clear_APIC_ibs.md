# Function: <code>clear_APIC_ibs</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/events/amd/ibs.c (ffffffff810096f0)
Location: arch/x86/events/amd/ibs.c:872
Inline: True
Direct callers:
  - arch/x86/events/amd/ibs.c:perf_ibs_suspend
  - arch/x86/events/amd/ibs.c:perf_ibs_cpu_notifier
```
**Symbols:**

```
ffffffff810096f0-ffffffff8100974a: clear_APIC_ibs.isra.6 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void clear_APIC_ibs();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/amd/ibs.c (ffffffff81009390)
Location: arch/x86/events/amd/ibs.c:939
Inline: False
Direct callers:
  - arch/x86/events/amd/ibs.c:x86_pmu_amd_ibs_dying_cpu
  - arch/x86/events/amd/ibs.c:perf_ibs_suspend
```
**Symbols:**

```
ffffffff81009390-ffffffff810093bf: clear_APIC_ibs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void clear_APIC_ibs();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/amd/ibs.c (ffffffff810093d0)
Location: arch/x86/events/amd/ibs.c:939
Inline: False
Direct callers:
  - arch/x86/events/amd/ibs.c:x86_pmu_amd_ibs_dying_cpu
  - arch/x86/events/amd/ibs.c:perf_ibs_suspend
```
**Symbols:**

```
ffffffff810093d0-ffffffff810093ff: clear_APIC_ibs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void clear_APIC_ibs();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/amd/ibs.c (ffffffff810090b0)
Location: arch/x86/events/amd/ibs.c:940
Inline: False
Direct callers:
  - arch/x86/events/amd/ibs.c:x86_pmu_amd_ibs_dying_cpu
  - arch/x86/events/amd/ibs.c:perf_ibs_suspend
```
**Symbols:**

```
ffffffff810090b0-ffffffff810090e1: clear_APIC_ibs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void clear_APIC_ibs();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/amd/ibs.c (ffffffff810094e0)
Location: arch/x86/events/amd/ibs.c:940
Inline: False
Direct callers:
  - arch/x86/events/amd/ibs.c:x86_pmu_amd_ibs_dying_cpu
  - arch/x86/events/amd/ibs.c:perf_ibs_suspend
```
**Symbols:**

```
ffffffff810094e0-ffffffff8100950f: clear_APIC_ibs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void clear_APIC_ibs();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/amd/ibs.c (ffffffff81009be0)
Location: arch/x86/events/amd/ibs.c:944
Inline: False
Direct callers:
  - arch/x86/events/amd/ibs.c:x86_pmu_amd_ibs_dying_cpu
  - arch/x86/events/amd/ibs.c:perf_ibs_suspend
```
**Symbols:**

```
ffffffff81009be0-ffffffff81009c0f: clear_APIC_ibs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void clear_APIC_ibs();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/amd/ibs.c (ffffffff81009b10)
Location: arch/x86/events/amd/ibs.c:944
Inline: False
Direct callers:
  - arch/x86/events/amd/ibs.c:x86_pmu_amd_ibs_dying_cpu
  - arch/x86/events/amd/ibs.c:perf_ibs_suspend
```
**Symbols:**

```
ffffffff81009b10-ffffffff81009b3f: clear_APIC_ibs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void clear_APIC_ibs();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/amd/ibs.c (ffffffff81009fe0)
Location: arch/x86/events/amd/ibs.c:940
Inline: False
Direct callers:
  - arch/x86/events/amd/ibs.c:x86_pmu_amd_ibs_dying_cpu
  - arch/x86/events/amd/ibs.c:perf_ibs_suspend
```
**Symbols:**

```
ffffffff81009fe0-ffffffff8100a00f: clear_APIC_ibs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void clear_APIC_ibs();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/amd/ibs.c (ffffffff8100a3d0)
Location: arch/x86/events/amd/ibs.c:942
Inline: False
Direct callers:
  - arch/x86/events/amd/ibs.c:x86_pmu_amd_ibs_dying_cpu
  - arch/x86/events/amd/ibs.c:perf_ibs_suspend
```
**Symbols:**

```
ffffffff8100a3d0-ffffffff8100a3ff: clear_APIC_ibs (STB_LOCAL)
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
In arch/x86/events/amd/ibs.c (ffffffff8100b745)
Location: arch/x86/events/amd/ibs.c:942
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:x86_pmu_amd_ibs_dying_cpu
  - arch/x86/events/amd/ibs.c:perf_ibs_suspend
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/events/amd/ibs.c (ffffffff8100a545)
Location: arch/x86/events/amd/ibs.c:985
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:x86_pmu_amd_ibs_dying_cpu
  - arch/x86/events/amd/ibs.c:perf_ibs_suspend
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
In arch/x86/events/amd/ibs.c (ffffffff8100ae25)
Location: arch/x86/events/amd/ibs.c:985
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:x86_pmu_amd_ibs_dying_cpu
  - arch/x86/events/amd/ibs.c:perf_ibs_suspend
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
In arch/x86/events/amd/ibs.c (ffffffff8100b5a5)
Location: arch/x86/events/amd/ibs.c:989
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:x86_pmu_amd_ibs_dying_cpu
  - arch/x86/events/amd/ibs.c:perf_ibs_suspend
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
In arch/x86/events/amd/ibs.c (ffffffff8100c035)
Location: arch/x86/events/amd/ibs.c:1134
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:x86_pmu_amd_ibs_dying_cpu
  - arch/x86/events/amd/ibs.c:perf_ibs_suspend
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
In arch/x86/events/amd/ibs.c (ffffffff8100f085)
Location: arch/x86/events/amd/ibs.c:1460
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:x86_pmu_amd_ibs_dying_cpu
  - arch/x86/events/amd/ibs.c:perf_ibs_suspend
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
In arch/x86/events/amd/ibs.c (ffffffff8100e665)
Location: arch/x86/events/amd/ibs.c:1456
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:x86_pmu_amd_ibs_dying_cpu
  - arch/x86/events/amd/ibs.c:perf_ibs_suspend
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
In arch/x86/events/amd/ibs.c (ffffffff81013b35)
Location: arch/x86/events/amd/ibs.c:1465
Inline: True
Inline callers:
  - arch/x86/events/amd/ibs.c:x86_pmu_amd_ibs_dying_cpu
  - arch/x86/events/amd/ibs.c:perf_ibs_suspend
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
void clear_APIC_ibs();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/amd/ibs.c (ffffffff8100a3d0)
Location: arch/x86/events/amd/ibs.c:942
Inline: False
Direct callers:
  - arch/x86/events/amd/ibs.c:x86_pmu_amd_ibs_dying_cpu
  - arch/x86/events/amd/ibs.c:perf_ibs_suspend
```
**Symbols:**

```
ffffffff8100a3d0-ffffffff8100a3ff: clear_APIC_ibs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void clear_APIC_ibs();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/amd/ibs.c (ffffffff81008cd0)
Location: arch/x86/events/amd/ibs.c:942
Inline: False
Direct callers:
  - arch/x86/events/amd/ibs.c:x86_pmu_amd_ibs_dying_cpu
  - arch/x86/events/amd/ibs.c:perf_ibs_suspend
```
**Symbols:**

```
ffffffff81008cd0-ffffffff81008d1c: clear_APIC_ibs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void clear_APIC_ibs();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/amd/ibs.c (ffffffff8100a390)
Location: arch/x86/events/amd/ibs.c:942
Inline: False
Direct callers:
  - arch/x86/events/amd/ibs.c:x86_pmu_amd_ibs_dying_cpu
  - arch/x86/events/amd/ibs.c:perf_ibs_suspend
```
**Symbols:**

```
ffffffff8100a390-ffffffff8100a3bf: clear_APIC_ibs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void clear_APIC_ibs();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/amd/ibs.c (ffffffff8100a4f0)
Location: arch/x86/events/amd/ibs.c:942
Inline: False
Direct callers:
  - arch/x86/events/amd/ibs.c:x86_pmu_amd_ibs_dying_cpu
  - arch/x86/events/amd/ibs.c:perf_ibs_suspend
```
**Symbols:**

```
ffffffff8100a4f0-ffffffff8100a51f: clear_APIC_ibs (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
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
