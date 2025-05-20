# Function: <code>setup_APIC_ibs</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void setup_APIC_ibs(void *dummy);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/amd/ibs.c (ffffffff81009670)
Location: arch/x86/events/amd/ibs.c:857
Inline: True
Direct callers:
  - arch/x86/events/amd/ibs.c:perf_ibs_cpu_notifier
  - arch/x86/events/amd/ibs.c:perf_ibs_resume
  - arch/x86/events/amd/ibs.c:perf_ibs_resume
```
**Symbols:**

```
ffffffff81009670-ffffffff810096e3: setup_APIC_ibs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void setup_APIC_ibs();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/amd/ibs.c (ffffffff81009b30)
Location: arch/x86/events/amd/ibs.c:924
Inline: True
Direct callers:
  - arch/x86/events/amd/ibs.c:perf_ibs_resume
  - arch/x86/events/amd/ibs.c:perf_ibs_resume
  - arch/x86/events/amd/ibs.c:x86_pmu_amd_ibs_starting_cpu
```
**Symbols:**

```
ffffffff81009b30-ffffffff81009b78: setup_APIC_ibs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void setup_APIC_ibs();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/amd/ibs.c (ffffffff81009b70)
Location: arch/x86/events/amd/ibs.c:924
Inline: True
Direct callers:
  - arch/x86/events/amd/ibs.c:perf_ibs_resume
  - arch/x86/events/amd/ibs.c:perf_ibs_resume
  - arch/x86/events/amd/ibs.c:x86_pmu_amd_ibs_starting_cpu
```
**Symbols:**

```
ffffffff81009b70-ffffffff81009bb8: setup_APIC_ibs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void setup_APIC_ibs();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/amd/ibs.c (ffffffff810098e0)
Location: arch/x86/events/amd/ibs.c:925
Inline: True
Direct callers:
  - arch/x86/events/amd/ibs.c:perf_ibs_resume
  - arch/x86/events/amd/ibs.c:perf_ibs_resume
  - arch/x86/events/amd/ibs.c:x86_pmu_amd_ibs_starting_cpu
```
**Symbols:**

```
ffffffff810098e0-ffffffff81009928: setup_APIC_ibs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void setup_APIC_ibs();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/amd/ibs.c (ffffffff81009470)
Location: arch/x86/events/amd/ibs.c:925
Inline: True
Direct callers:
  - arch/x86/events/amd/ibs.c:perf_ibs_resume
  - arch/x86/events/amd/ibs.c:perf_ibs_resume
  - arch/x86/events/amd/ibs.c:x86_pmu_amd_ibs_starting_cpu
```
**Symbols:**

```
ffffffff81009470-ffffffff810094b8: setup_APIC_ibs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void setup_APIC_ibs();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/amd/ibs.c (ffffffff81009b70)
Location: arch/x86/events/amd/ibs.c:929
Inline: True
Direct callers:
  - arch/x86/events/amd/ibs.c:perf_ibs_resume
  - arch/x86/events/amd/ibs.c:perf_ibs_resume
  - arch/x86/events/amd/ibs.c:x86_pmu_amd_ibs_starting_cpu
```
**Symbols:**

```
ffffffff81009b70-ffffffff81009bb8: setup_APIC_ibs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void setup_APIC_ibs();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/events/amd/ibs.c (ffffffff81009aa0)
Location: arch/x86/events/amd/ibs.c:929
Inline: True
Direct callers:
  - arch/x86/events/amd/ibs.c:perf_ibs_resume
  - arch/x86/events/amd/ibs.c:perf_ibs_resume
  - arch/x86/events/amd/ibs.c:x86_pmu_amd_ibs_starting_cpu
```
**Symbols:**

```
ffffffff81009aa0-ffffffff81009ae8: setup_APIC_ibs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
void setup_APIC_ibs();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/events/amd/ibs.c (ffffffff8100ab16)
Location: arch/x86/events/amd/ibs.c:925
Inline: True
Direct callers:
  - arch/x86/events/amd/ibs.c:perf_ibs_resume
  - arch/x86/events/amd/ibs.c:perf_ibs_resume
  - arch/x86/events/amd/ibs.c:x86_pmu_amd_ibs_starting_cpu
```
**Symbols:**

```
ffffffff81009f80-ffffffff81009fbb: setup_APIC_ibs (STB_LOCAL)
ffffffff8100ab16-ffffffff8100ab2e: setup_APIC_ibs.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
void setup_APIC_ibs();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/events/amd/ibs.c (ffffffff8100af32)
Location: arch/x86/events/amd/ibs.c:927
Inline: True
Direct callers:
  - arch/x86/events/amd/ibs.c:perf_ibs_resume
  - arch/x86/events/amd/ibs.c:perf_ibs_resume
  - arch/x86/events/amd/ibs.c:x86_pmu_amd_ibs_starting_cpu
```
**Symbols:**

```
ffffffff8100a370-ffffffff8100a3ab: setup_APIC_ibs (STB_LOCAL)
ffffffff8100af32-ffffffff8100af4a: setup_APIC_ibs.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void setup_APIC_ibs();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/events/amd/ibs.c (ffffffff8100c1b2)
Location: arch/x86/events/amd/ibs.c:927
Inline: True
Direct callers:
  - arch/x86/events/amd/ibs.c:perf_ibs_resume
  - arch/x86/events/amd/ibs.c:perf_ibs_resume
  - arch/x86/events/amd/ibs.c:x86_pmu_amd_ibs_starting_cpu
```
**Symbols:**

```
ffffffff8100b7c0-ffffffff8100b7fb: setup_APIC_ibs (STB_LOCAL)
ffffffff8100c1b2-ffffffff8100c1ca: setup_APIC_ibs.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
void setup_APIC_ibs();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/events/amd/ibs.c (ffffffff81bd20a7)
Location: arch/x86/events/amd/ibs.c:970
Inline: True
Direct callers:
  - arch/x86/events/amd/ibs.c:perf_ibs_resume
  - arch/x86/events/amd/ibs.c:perf_ibs_resume
  - arch/x86/events/amd/ibs.c:x86_pmu_amd_ibs_starting_cpu
```
**Symbols:**

```
ffffffff8100a7c0-ffffffff8100a7fb: setup_APIC_ibs (STB_LOCAL)
ffffffff81bd20a7-ffffffff81bd20bf: setup_APIC_ibs.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
void setup_APIC_ibs();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/events/amd/ibs.c (ffffffff81bc4137)
Location: arch/x86/events/amd/ibs.c:970
Inline: True
Direct callers:
  - arch/x86/events/amd/ibs.c:perf_ibs_resume
  - arch/x86/events/amd/ibs.c:perf_ibs_resume
  - arch/x86/events/amd/ibs.c:x86_pmu_amd_ibs_starting_cpu
```
**Symbols:**

```
ffffffff8100b090-ffffffff8100b0cb: setup_APIC_ibs (STB_LOCAL)
ffffffff81bc4137-ffffffff81bc414f: setup_APIC_ibs.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void setup_APIC_ibs();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/events/amd/ibs.c (ffffffff81c9550a)
Location: arch/x86/events/amd/ibs.c:974
Inline: True
Direct callers:
  - arch/x86/events/amd/ibs.c:perf_ibs_resume
  - arch/x86/events/amd/ibs.c:perf_ibs_resume
  - arch/x86/events/amd/ibs.c:x86_pmu_amd_ibs_starting_cpu
```
**Symbols:**

```
ffffffff8100b620-ffffffff8100b65b: setup_APIC_ibs (STB_LOCAL)
ffffffff81c9550a-ffffffff81c95522: setup_APIC_ibs.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
void setup_APIC_ibs();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/events/amd/ibs.c (ffffffff81e4483c)
Location: arch/x86/events/amd/ibs.c:1119
Inline: True
Direct callers:
  - arch/x86/events/amd/ibs.c:perf_ibs_resume
  - arch/x86/events/amd/ibs.c:perf_ibs_resume
  - arch/x86/events/amd/ibs.c:x86_pmu_amd_ibs_starting_cpu
```
**Symbols:**

```
ffffffff8100c080-ffffffff8100c0d4: setup_APIC_ibs (STB_LOCAL)
ffffffff81e4483c-ffffffff81e44854: setup_APIC_ibs.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void setup_APIC_ibs();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/amd/ibs.c (ffffffff8100f0e0)
Location: arch/x86/events/amd/ibs.c:1445
Inline: False
Direct callers:
  - arch/x86/events/amd/ibs.c:perf_ibs_resume
  - arch/x86/events/amd/ibs.c:perf_ibs_resume
  - arch/x86/events/amd/ibs.c:x86_pmu_amd_ibs_starting_cpu
```
**Symbols:**

```
ffffffff8100f0e0-ffffffff8100f13f: setup_APIC_ibs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void setup_APIC_ibs();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/amd/ibs.c (ffffffff8100e6c0)
Location: arch/x86/events/amd/ibs.c:1441
Inline: False
Direct callers:
  - arch/x86/events/amd/ibs.c:perf_ibs_resume
  - arch/x86/events/amd/ibs.c:perf_ibs_resume
  - arch/x86/events/amd/ibs.c:x86_pmu_amd_ibs_starting_cpu
```
**Symbols:**

```
ffffffff8100e6c0-ffffffff8100e71f: setup_APIC_ibs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void setup_APIC_ibs();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/events/amd/ibs.c (ffffffff81013e00)
Location: arch/x86/events/amd/ibs.c:1450
Inline: False
Direct callers:
  - arch/x86/events/amd/ibs.c:perf_ibs_resume
  - arch/x86/events/amd/ibs.c:perf_ibs_resume
  - arch/x86/events/amd/ibs.c:x86_pmu_amd_ibs_starting_cpu
```
**Symbols:**

```
ffffffff81013e00-ffffffff81013e5f: setup_APIC_ibs (STB_LOCAL)
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
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
void setup_APIC_ibs();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/events/amd/ibs.c (ffffffff8100af32)
Location: arch/x86/events/amd/ibs.c:927
Inline: True
Direct callers:
  - arch/x86/events/amd/ibs.c:perf_ibs_resume
  - arch/x86/events/amd/ibs.c:perf_ibs_resume
  - arch/x86/events/amd/ibs.c:x86_pmu_amd_ibs_starting_cpu
```
**Symbols:**

```
ffffffff8100a370-ffffffff8100a3ab: setup_APIC_ibs (STB_LOCAL)
ffffffff8100af32-ffffffff8100af4a: setup_APIC_ibs.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
void setup_APIC_ibs();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/events/amd/ibs.c (ffffffff810098c1)
Location: arch/x86/events/amd/ibs.c:927
Inline: True
Direct callers:
  - arch/x86/events/amd/ibs.c:perf_ibs_resume
  - arch/x86/events/amd/ibs.c:perf_ibs_resume
  - arch/x86/events/amd/ibs.c:x86_pmu_amd_ibs_starting_cpu
```
**Symbols:**

```
ffffffff81008d60-ffffffff81008db8: setup_APIC_ibs (STB_LOCAL)
ffffffff810098c1-ffffffff810098d9: setup_APIC_ibs.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
void setup_APIC_ibs();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/events/amd/ibs.c (ffffffff8100aef2)
Location: arch/x86/events/amd/ibs.c:927
Inline: True
Direct callers:
  - arch/x86/events/amd/ibs.c:perf_ibs_resume
  - arch/x86/events/amd/ibs.c:perf_ibs_resume
  - arch/x86/events/amd/ibs.c:x86_pmu_amd_ibs_starting_cpu
```
**Symbols:**

```
ffffffff8100a330-ffffffff8100a36b: setup_APIC_ibs (STB_LOCAL)
ffffffff8100aef2-ffffffff8100af0a: setup_APIC_ibs.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
void setup_APIC_ibs();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/events/amd/ibs.c (ffffffff8100b0b6)
Location: arch/x86/events/amd/ibs.c:927
Inline: True
Direct callers:
  - arch/x86/events/amd/ibs.c:perf_ibs_resume
  - arch/x86/events/amd/ibs.c:perf_ibs_resume
  - arch/x86/events/amd/ibs.c:x86_pmu_amd_ibs_starting_cpu
```
**Symbols:**

```
ffffffff8100a490-ffffffff8100a4cb: setup_APIC_ibs (STB_LOCAL)
ffffffff8100b0b6-ffffffff8100b0ce: setup_APIC_ibs.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>void *dummy</code>
</li>
</ul>
</details>
</li>
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
