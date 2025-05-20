# Function: <code>native_flush_tlb_others</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void native_flush_tlb_others(const struct cpumask *cpumask, struct mm_struct *mm, long unsigned int start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff81072750)
Location: arch/x86/mm/tlb.c:133
Inline: False
```
**Symbols:**

```
ffffffff81072750-ffffffff81072814: native_flush_tlb_others (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void native_flush_tlb_others(const struct cpumask *cpumask, struct mm_struct *mm, long unsigned int start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff810726d0)
Location: arch/x86/mm/tlb.c:245
Inline: False
```
**Symbols:**

```
ffffffff810726d0-ffffffff810727f6: native_flush_tlb_others (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void native_flush_tlb_others(const struct cpumask *cpumask, struct mm_struct *mm, long unsigned int start, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff81076280)
Location: arch/x86/mm/tlb.c:260
Inline: False
```
**Symbols:**

```
ffffffff81076280-ffffffff810763a6: native_flush_tlb_others (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void native_flush_tlb_others(const struct cpumask *cpumask, const struct flush_tlb_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff81074a90)
Location: arch/x86/mm/tlb.c:206
Inline: False
```
**Symbols:**

```
ffffffff81074a90-ffffffff81074b74: native_flush_tlb_others (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void native_flush_tlb_others(const struct cpumask *cpumask, const struct flush_tlb_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff8107ac00)
Location: arch/x86/mm/tlb.c:554
Inline: False
Direct callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
```
**Symbols:**

```
ffffffff8107ac00-ffffffff8107acea: native_flush_tlb_others (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void native_flush_tlb_others(const struct cpumask *cpumask, const struct flush_tlb_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff8107d9b0)
Location: arch/x86/mm/tlb.c:567
Inline: False
Direct callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others_ex
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/kernel/kvm.c:kvm_flush_tlb_others
```
**Symbols:**

```
ffffffff8107d9b0-ffffffff8107da9a: native_flush_tlb_others (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void native_flush_tlb_others(const struct cpumask *cpumask, const struct flush_tlb_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff810844e0)
Location: arch/x86/mm/tlb.c:662
Inline: False
Direct callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/kernel/kvm.c:kvm_flush_tlb_others
```
**Symbols:**

```
ffffffff810844e0-ffffffff8108460c: native_flush_tlb_others (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void native_flush_tlb_others(const struct cpumask *cpumask, const struct flush_tlb_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff810881b0)
Location: arch/x86/mm/tlb.c:663
Inline: False
Direct callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/kernel/kvm.c:kvm_flush_tlb_others
```
**Symbols:**

```
ffffffff810881b0-ffffffff810882d6: native_flush_tlb_others (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void native_flush_tlb_others(const struct cpumask *cpumask, const struct flush_tlb_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff81088e20)
Location: arch/x86/mm/tlb.c:663
Inline: False
Direct callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/kernel/kvm.c:kvm_flush_tlb_others
```
**Symbols:**

```
ffffffff81088e20-ffffffff81088f88: native_flush_tlb_others (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void native_flush_tlb_others(const struct cpumask *cpumask, const struct flush_tlb_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff8108b500)
Location: arch/x86/mm/tlb.c:839
Inline: False
Direct callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/kernel/kvm.c:kvm_flush_tlb_others
```
**Symbols:**

```
ffffffff8108b500-ffffffff8108b666: native_flush_tlb_others (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void native_flush_tlb_others(const struct cpumask *cpumask, const struct flush_tlb_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff8108b5c0)
Location: arch/x86/mm/tlb.c:798
Inline: False
Direct callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/kernel/kvm.c:kvm_flush_tlb_others
```
**Symbols:**

```
ffffffff8108b5c0-ffffffff8108b6b3: native_flush_tlb_others (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
void native_flush_tlb_others(const struct cpumask *cpumask, const struct flush_tlb_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff81087e20)
Location: arch/x86/mm/tlb.c:663
Inline: False
Direct callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/kernel/kvm.c:kvm_flush_tlb_others
```
**Symbols:**

```
ffffffff81087e20-ffffffff81087f46: native_flush_tlb_others (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void native_flush_tlb_others(const struct cpumask *cpumask, const struct flush_tlb_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff81076a80)
Location: arch/x86/mm/tlb.c:663
Inline: False
Direct callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/kernel/kvm.c:kvm_flush_tlb_others
```
**Symbols:**

```
ffffffff81076a80-ffffffff81076ba6: native_flush_tlb_others (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void native_flush_tlb_others(const struct cpumask *cpumask, const struct flush_tlb_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff81087dd0)
Location: arch/x86/mm/tlb.c:663
Inline: False
Direct callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/kernel/kvm.c:kvm_flush_tlb_others
```
**Symbols:**

```
ffffffff81087dd0-ffffffff81087ef6: native_flush_tlb_others (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void native_flush_tlb_others(const struct cpumask *cpumask, const struct flush_tlb_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff81089fc0)
Location: arch/x86/mm/tlb.c:663
Inline: False
Direct callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_others
  - arch/x86/kernel/kvm.c:kvm_flush_tlb_others
```
**Symbols:**

```
ffffffff81089fc0-ffffffff8108a14c: native_flush_tlb_others (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>const struct flush_tlb_info *info</code>
</li>
<li>
<b>Param removed. </b>
<code>struct mm_struct *mm</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int start</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int end</code>
</li>
</ul>
</details>
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
