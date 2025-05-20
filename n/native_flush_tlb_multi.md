# Function: <code>native_flush_tlb_multi</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void native_flush_tlb_multi(const struct cpumask *cpumask, const struct flush_tlb_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff8108c150)
Location: arch/x86/mm/tlb.c:808
Inline: False
Direct callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_multi
  - arch/x86/kernel/kvm.c:kvm_flush_tlb_multi
```
**Symbols:**

```
ffffffff8108c150-ffffffff8108c291: native_flush_tlb_multi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void native_flush_tlb_multi(const struct cpumask *cpumask, const struct flush_tlb_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/tlb.c (0)
Location: arch/x86/mm/tlb.c:867
Inline: False
Direct callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_multi
  - arch/x86/kernel/kvm.c:kvm_flush_tlb_multi
```
**Symbols:**

```
ffffffff81ca11e0-ffffffff81ca11f5: native_flush_tlb_multi.cold (STB_LOCAL)
ffffffff8109b910-ffffffff8109bab9: native_flush_tlb_multi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void native_flush_tlb_multi(const struct cpumask *cpumask, const struct flush_tlb_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff810aedf0)
Location: arch/x86/mm/tlb.c:866
Inline: False
Direct callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_multi
  - arch/x86/kernel/kvm.c:kvm_flush_tlb_multi
```
**Symbols:**

```
ffffffff810aedf0-ffffffff810aef18: native_flush_tlb_multi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void native_flush_tlb_multi(const struct cpumask *cpumask, const struct flush_tlb_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff810c9170)
Location: arch/x86/mm/tlb.c:889
Inline: False
Direct callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_multi
  - arch/x86/kernel/kvm.c:kvm_flush_tlb_multi
```
**Symbols:**

```
ffffffff810c9170-ffffffff810c9298: native_flush_tlb_multi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void native_flush_tlb_multi(const struct cpumask *cpumask, const struct flush_tlb_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff810cc800)
Location: arch/x86/mm/tlb.c:908
Inline: False
Direct callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_multi
  - arch/x86/kernel/kvm.c:kvm_flush_tlb_multi
```
**Symbols:**

```
ffffffff810cc800-ffffffff810cc928: native_flush_tlb_multi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void native_flush_tlb_multi(const struct cpumask *cpumask, const struct flush_tlb_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/tlb.c (ffffffff810d4e90)
Location: arch/x86/mm/tlb.c:909
Inline: False
Direct callers:
  - arch/x86/hyperv/mmu.c:hyperv_flush_tlb_multi
  - arch/x86/kernel/kvm.c:kvm_flush_tlb_multi
```
**Symbols:**

```
ffffffff810d4e90-ffffffff810d4fb8: native_flush_tlb_multi (STB_GLOBAL)
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
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
