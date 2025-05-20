# Function: <code>copy_from_user_nmi</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
long unsigned int copy_from_user_nmi(void *to, const void *from, long unsigned int n);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/lib/usercopy.c (ffffffff813f78d0)
Location: arch/x86/lib/usercopy.c:18
Inline: True
Direct callers:
  - arch/x86/events/core.c:perf_callchain_user
  - arch/x86/events/core.c:perf_callchain_user
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_fixup_ip
  - arch/x86/events/intel/lbr.c:branch_type
  - kernel/events/core.c:perf_output_sample
```
**Symbols:**

```
ffffffff813f78d0-ffffffff813f792d: copy_from_user_nmi.part.0 (STB_LOCAL)
ffffffff813f7930-ffffffff813f7992: copy_from_user_nmi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
long unsigned int copy_from_user_nmi(void *to, const void *from, long unsigned int n);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/lib/usercopy.c (ffffffff8143e750)
Location: arch/x86/lib/usercopy.c:18
Inline: True
Direct callers:
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_fixup_ip
  - arch/x86/events/intel/lbr.c:branch_type
  - kernel/events/core.c:perf_output_sample
```
**Symbols:**

```
ffffffff8143e750-ffffffff8143e7df: copy_from_user_nmi.part.1 (STB_LOCAL)
ffffffff8143e7e0-ffffffff8143e842: copy_from_user_nmi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

```c
long unsigned int copy_from_user_nmi(void *to, const void *from, long unsigned int n);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/lib/usercopy.c (ffffffff8145b730)
Location: arch/x86/lib/usercopy.c:18
Inline: True
Direct callers:
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_fixup_ip
  - arch/x86/events/intel/lbr.c:branch_type
  - kernel/events/core.c:perf_output_sample
```
**Symbols:**

```
ffffffff8145b730-ffffffff8145b7bf: copy_from_user_nmi.part.3 (STB_LOCAL)
ffffffff8145b840-ffffffff8145b897: copy_from_user_nmi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
long unsigned int copy_from_user_nmi(void *to, const void *from, long unsigned int n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/usercopy.c (ffffffff818fd460)
Location: arch/x86/lib/usercopy.c:15
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_fixup_ip
  - arch/x86/events/intel/lbr.c:branch_type
  - kernel/events/core.c:perf_output_sample
```
**Symbols:**

```
ffffffff818fd460-ffffffff818fd4f9: copy_from_user_nmi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
long unsigned int copy_from_user_nmi(void *to, const void *from, long unsigned int n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/usercopy.c (ffffffff81984f40)
Location: arch/x86/lib/usercopy.c:15
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_fixup_ip
  - arch/x86/events/intel/lbr.c:branch_type
  - kernel/events/core.c:perf_output_sample
```
**Symbols:**

```
ffffffff81984f40-ffffffff81984fda: copy_from_user_nmi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
long unsigned int copy_from_user_nmi(void *to, const void *from, long unsigned int n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/usercopy.c (ffffffff819e1410)
Location: arch/x86/lib/usercopy.c:17
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_fixup_ip
  - arch/x86/events/intel/lbr.c:branch_type
  - kernel/events/core.c:perf_output_sample
```
**Symbols:**

```
ffffffff819e1410-ffffffff819e14c7: copy_from_user_nmi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
long unsigned int copy_from_user_nmi(void *to, const void *from, long unsigned int n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/usercopy.c (ffffffff81a1c3c0)
Location: arch/x86/lib/usercopy.c:17
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_fixup_ip
  - arch/x86/events/intel/lbr.c:branch_type
  - kernel/events/core.c:perf_output_sample
```
**Symbols:**

```
ffffffff81a1c3c0-ffffffff81a1c477: copy_from_user_nmi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
long unsigned int copy_from_user_nmi(void *to, const void *from, long unsigned int n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/usercopy.c (ffffffff81a8c070)
Location: arch/x86/lib/usercopy.c:17
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_fixup_ip
  - arch/x86/events/intel/lbr.c:branch_type
  - kernel/events/core.c:perf_output_sample
```
**Symbols:**

```
ffffffff81a8c070-ffffffff81a8c127: copy_from_user_nmi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long unsigned int copy_from_user_nmi(void *to, const void *from, long unsigned int n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/usercopy.c (ffffffff81ac3330)
Location: arch/x86/lib/usercopy.c:17
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_fixup_ip
  - arch/x86/events/intel/lbr.c:branch_type
  - kernel/events/core.c:perf_output_sample
```
**Symbols:**

```
ffffffff81ac3330-ffffffff81ac33e7: copy_from_user_nmi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long unsigned int copy_from_user_nmi(void *to, const void *from, long unsigned int n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/usercopy.c (ffffffff815ff890)
Location: arch/x86/lib/usercopy.c:17
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_fixup_ip
  - arch/x86/events/intel/lbr.c:branch_type
  - arch/x86/kernel/dumpstack.c:show_opcodes
  - kernel/events/core.c:perf_output_sample_ustack
```
**Symbols:**

```
ffffffff815ff890-ffffffff815ff95e: copy_from_user_nmi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long unsigned int copy_from_user_nmi(void *to, const void *from, long unsigned int n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/usercopy.c (ffffffff816247c0)
Location: arch/x86/lib/usercopy.c:31
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_fixup_ip
  - arch/x86/events/intel/lbr.c:branch_type
  - arch/x86/kernel/dumpstack.c:show_opcodes
  - kernel/events/core.c:perf_output_sample
```
**Symbols:**

```
ffffffff816247c0-ffffffff8162488e: copy_from_user_nmi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long unsigned int copy_from_user_nmi(void *to, const void *from, long unsigned int n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/usercopy.c (ffffffff816081b0)
Location: arch/x86/lib/usercopy.c:31
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_fixup_ip
  - arch/x86/events/intel/lbr.c:branch_type
  - arch/x86/kernel/dumpstack.c:show_opcodes
  - kernel/events/core.c:perf_output_sample
```
**Symbols:**

```
ffffffff816081b0-ffffffff8160825e: copy_from_user_nmi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long unsigned int copy_from_user_nmi(void *to, const void *from, long unsigned int n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/usercopy.c (ffffffff81676df0)
Location: arch/x86/lib/usercopy.c:31
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_fixup_ip
  - arch/x86/events/intel/lbr.c:branch_type
  - arch/x86/kernel/dumpstack.c:show_opcodes
  - kernel/events/core.c:perf_output_sample
```
**Symbols:**

```
ffffffff81676df0-ffffffff81676e9e: copy_from_user_nmi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
long unsigned int copy_from_user_nmi(void *to, const void *from, long unsigned int n);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/lib/usercopy.c (ffffffff81791d90)
Location: arch/x86/lib/usercopy.c:31
Inline: True
Direct callers:
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_fixup_ip
  - arch/x86/events/intel/lbr.c:branch_type
  - arch/x86/kernel/dumpstack.c:show_opcodes
  - kernel/events/core.c:perf_output_sample
```
**Symbols:**

```
ffffffff81791d90-ffffffff81791e43: copy_from_user_nmi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
long unsigned int copy_from_user_nmi(void *to, const void *from, long unsigned int n);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/lib/usercopy.c (ffffffff8204fbc0)
Location: arch/x86/lib/usercopy.c:32
Inline: True
Direct callers:
  - arch/x86/events/utils.c:get_branch_type
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_fixup_ip
  - arch/x86/kernel/dumpstack.c:show_opcodes
  - kernel/events/core.c:perf_output_sample
```
**Symbols:**

```
ffffffff8204fbc0-ffffffff8204fc66: copy_from_user_nmi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
long unsigned int copy_from_user_nmi(void *to, const void *from, long unsigned int n);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/lib/usercopy.c (ffffffff820ce110)
Location: arch/x86/lib/usercopy.c:32
Inline: True
Direct callers:
  - arch/x86/events/utils.c:get_branch_type
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_fixup_ip
  - arch/x86/kernel/dumpstack.c:show_opcodes
  - kernel/events/core.c:perf_output_sample
```
**Symbols:**

```
ffffffff820ce110-ffffffff820ce1b5: copy_from_user_nmi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
long unsigned int copy_from_user_nmi(void *to, const void *from, long unsigned int n);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/lib/usercopy.c (ffffffff821a8940)
Location: arch/x86/lib/usercopy.c:32
Inline: True
Direct callers:
  - arch/x86/events/utils.c:get_branch_type
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_fixup_ip
  - arch/x86/kernel/dumpstack.c:show_opcodes
  - kernel/events/core.c:perf_output_sample
```
**Symbols:**

```
ffffffff821a8940-ffffffff821a89cd: copy_from_user_nmi (STB_GLOBAL)
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
long unsigned int copy_from_user_nmi(void *to, const void *from, long unsigned int n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/usercopy.c (ffffffff81a62180)
Location: arch/x86/lib/usercopy.c:17
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_fixup_ip
  - arch/x86/events/intel/lbr.c:branch_type
  - kernel/events/core.c:perf_output_sample
```
**Symbols:**

```
ffffffff81a62180-ffffffff81a62237: copy_from_user_nmi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long unsigned int copy_from_user_nmi(void *to, const void *from, long unsigned int n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/usercopy.c (ffffffff81a1f1f0)
Location: arch/x86/lib/usercopy.c:17
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_fixup_ip
  - arch/x86/events/intel/lbr.c:branch_type
  - kernel/events/core.c:perf_output_sample
```
**Symbols:**

```
ffffffff81a1f1f0-ffffffff81a1f2a7: copy_from_user_nmi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long unsigned int copy_from_user_nmi(void *to, const void *from, long unsigned int n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/usercopy.c (ffffffff81ace570)
Location: arch/x86/lib/usercopy.c:17
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_fixup_ip
  - arch/x86/events/intel/lbr.c:branch_type
  - kernel/events/core.c:perf_output_sample
```
**Symbols:**

```
ffffffff81ace570-ffffffff81ace627: copy_from_user_nmi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long unsigned int copy_from_user_nmi(void *to, const void *from, long unsigned int n);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/usercopy.c (ffffffff81adaa80)
Location: arch/x86/lib/usercopy.c:17
Inline: False
Direct callers:
  - arch/x86/events/intel/ds.c:intel_pmu_pebs_fixup_ip
  - arch/x86/events/intel/lbr.c:branch_type
  - kernel/events/core.c:perf_output_sample
```
**Symbols:**

```
ffffffff81adaa80-ffffffff81adab37: copy_from_user_nmi (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
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
