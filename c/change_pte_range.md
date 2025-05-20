# Function: <code>change_pte_range</code>

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
In mm/mprotect.c (ffffffff811c84df)
Location: mm/mprotect.c:62
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
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
In mm/mprotect.c (ffffffff811e465d)
Location: mm/mprotect.c:63
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
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
In mm/mprotect.c (ffffffff811f476e)
Location: mm/mprotect.c:64
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
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
In mm/mprotect.c (ffffffff811ff622)
Location: mm/mprotect.c:36
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
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
In mm/mprotect.c (ffffffff81217ed5)
Location: mm/mprotect.c:37
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
long unsigned int change_pte_range(struct vm_area_struct *vma, pmd_t *pmd, long unsigned int addr, long unsigned int end, pgprot_t newprot, int dirty_accountable, int prot_numa);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mprotect.c (ffffffff81239010)
Location: mm/mprotect.c:38
Inline: False
Direct callers:
  - mm/mprotect.c:change_protection
```
**Symbols:**

```
ffffffff81239010-ffffffff812394d2: change_pte_range (STB_LOCAL)
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
In mm/mprotect.c (ffffffff8124d5d6)
Location: mm/mprotect.c:38
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
long unsigned int change_pte_range(struct vm_area_struct *vma, pmd_t *pmd, long unsigned int addr, long unsigned int end, pgprot_t newprot, int dirty_accountable, int prot_numa);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mprotect.c (ffffffff8125f5b0)
Location: mm/mprotect.c:38
Inline: False
Direct callers:
  - mm/mprotect.c:change_protection_range
```
**Symbols:**

```
ffffffff8125f5b0-ffffffff8125fa88: change_pte_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long unsigned int change_pte_range(struct vm_area_struct *vma, pmd_t *pmd, long unsigned int addr, long unsigned int end, pgprot_t newprot, int dirty_accountable, int prot_numa);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mprotect.c (ffffffff8126ddc0)
Location: mm/mprotect.c:38
Inline: False
Direct callers:
  - mm/mprotect.c:change_protection_range
```
**Symbols:**

```
ffffffff8126ddc0-ffffffff8126e298: change_pte_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long unsigned int change_pte_range(struct vm_area_struct *vma, pmd_t *pmd, long unsigned int addr, long unsigned int end, pgprot_t newprot, long unsigned int cp_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mprotect.c (ffffffff8129e460)
Location: mm/mprotect.c:38
Inline: False
```
**Symbols:**

```
ffffffff8129e460-ffffffff8129ea0f: change_pte_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long unsigned int change_pte_range(struct vm_area_struct *vma, pmd_t *pmd, long unsigned int addr, long unsigned int end, pgprot_t newprot, long unsigned int cp_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mprotect.c (ffffffff812a9820)
Location: mm/mprotect.c:38
Inline: False
```
**Symbols:**

```
ffffffff812a9820-ffffffff812a9dc4: change_pte_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long unsigned int change_pte_range(struct vm_area_struct *vma, pmd_t *pmd, long unsigned int addr, long unsigned int end, pgprot_t newprot, long unsigned int cp_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mprotect.c (ffffffff812aecb0)
Location: mm/mprotect.c:38
Inline: False
```
**Symbols:**

```
ffffffff812aecb0-ffffffff812af24f: change_pte_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long unsigned int change_pte_range(struct vm_area_struct *vma, pmd_t *pmd, long unsigned int addr, long unsigned int end, pgprot_t newprot, long unsigned int cp_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mprotect.c (ffffffff812f04a0)
Location: mm/mprotect.c:38
Inline: False
```
**Symbols:**

```
ffffffff812f04a0-ffffffff812f0a72: change_pte_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long unsigned int change_pte_range(struct mmu_gather *tlb, struct vm_area_struct *vma, pmd_t *pmd, long unsigned int addr, long unsigned int end, pgprot_t newprot, long unsigned int cp_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mprotect.c (ffffffff813539b0)
Location: mm/mprotect.c:41
Inline: False
```
**Symbols:**

```
ffffffff813539b0-ffffffff8135430c: change_pte_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long unsigned int change_pte_range(struct mmu_gather *tlb, struct vm_area_struct *vma, pmd_t *pmd, long unsigned int addr, long unsigned int end, pgprot_t newprot, long unsigned int cp_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mprotect.c (ffffffff813cde50)
Location: mm/mprotect.c:83
Inline: False
```
**Symbols:**

```
ffffffff813cde50-ffffffff813ce819: change_pte_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long int change_pte_range(struct mmu_gather *tlb, struct vm_area_struct *vma, pmd_t *pmd, long unsigned int addr, long unsigned int end, pgprot_t newprot, long unsigned int cp_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mprotect.c (ffffffff81402810)
Location: mm/mprotect.c:83
Inline: False
```
**Symbols:**

```
ffffffff81402810-ffffffff814030e5: change_pte_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long int change_pte_range(struct mmu_gather *tlb, struct vm_area_struct *vma, pmd_t *pmd, long unsigned int addr, long unsigned int end, pgprot_t newprot, long unsigned int cp_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mprotect.c (ffffffff8142ee40)
Location: mm/mprotect.c:83
Inline: False
```
**Symbols:**

```
ffffffff8142ee40-ffffffff8142f67f: change_pte_range (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mprotect.c (ffff800010305064)
Location: mm/mprotect.c:38
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mprotect.c (c05232d8)
Location: mm/mprotect.c:38
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mprotect.c (c0000000003d20c8)
Location: mm/mprotect.c:38
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mprotect.c (ffffffe0002110f2)
Location: mm/mprotect.c:38
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
long unsigned int change_pte_range(struct vm_area_struct *vma, pmd_t *pmd, long unsigned int addr, long unsigned int end, pgprot_t newprot, int dirty_accountable, int prot_numa);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mprotect.c (ffffffff81266410)
Location: mm/mprotect.c:38
Inline: False
Direct callers:
  - mm/mprotect.c:change_protection_range
```
**Symbols:**

```
ffffffff81266410-ffffffff812668e8: change_pte_range (STB_LOCAL)
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
In mm/mprotect.c (ffffffff81258b4d)
Location: mm/mprotect.c:38
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long unsigned int change_pte_range(struct vm_area_struct *vma, pmd_t *pmd, long unsigned int addr, long unsigned int end, pgprot_t newprot, int dirty_accountable, int prot_numa);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mprotect.c (ffffffff812641b0)
Location: mm/mprotect.c:38
Inline: False
Direct callers:
  - mm/mprotect.c:change_protection_range
```
**Symbols:**

```
ffffffff812641b0-ffffffff81264688: change_pte_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long unsigned int change_pte_range(struct vm_area_struct *vma, pmd_t *pmd, long unsigned int addr, long unsigned int end, pgprot_t newprot, int dirty_accountable, int prot_numa);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mprotect.c (ffffffff81273b70)
Location: mm/mprotect.c:38
Inline: False
Direct callers:
  - mm/mprotect.c:change_protection_range
```
**Symbols:**

```
ffffffff81273b70-ffffffff81274046: change_pte_range (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>long unsigned int cp_flags</code>
</li>
<li>
<b>Param removed. </b>
<code>int dirty_accountable</code>
</li>
<li>
<b>Param removed. </b>
<code>int prot_numa</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct mmu_gather *tlb</code>
</li>
<li>
<b>Param reordered. </b>
<code>vma, pmd, addr, end, newprot, cp_flags</code> ➡️ <code>tlb, vma, pmd, addr, end, newprot, cp_flags</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>long unsigned int</code> ➡️ <code>long int</code>
</li>
</ul>
</details>
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
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
