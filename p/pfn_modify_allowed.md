# Function: <code>pfn_modify_allowed</code>

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
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
bool pfn_modify_allowed(long unsigned int pfn, pgprot_t prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mmap.c (ffffffff8107ac70)
Location: arch/x86/mm/mmap.c:251
Inline: False
Direct callers:
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:__vm_insert_mixed
  - mm/memory.c:vm_insert_pfn_prot
  - mm/mprotect.c:prot_none_hugetlb_entry
  - mm/mprotect.c:prot_none_pte_entry
```
**Symbols:**

```
ffffffff8107ac70-ffffffff8107ad00: pfn_modify_allowed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool pfn_modify_allowed(long unsigned int pfn, pgprot_t prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mmap.c (ffffffff810815b0)
Location: arch/x86/mm/mmap.c:251
Inline: False
Direct callers:
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:__vm_insert_mixed
  - mm/memory.c:vmf_insert_pfn_prot
  - mm/mprotect.c:prot_none_hugetlb_entry
  - mm/mprotect.c:prot_none_pte_entry
```
**Symbols:**

```
ffffffff810815b0-ffffffff81081640: pfn_modify_allowed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool pfn_modify_allowed(long unsigned int pfn, pgprot_t prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mmap.c (ffffffff81085230)
Location: arch/x86/mm/mmap.c:238
Inline: False
Direct callers:
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:__vm_insert_mixed
  - mm/memory.c:vmf_insert_pfn_prot
  - mm/mprotect.c:prot_none_hugetlb_entry
  - mm/mprotect.c:prot_none_pte_entry
```
**Symbols:**

```
ffffffff81085230-ffffffff810852d2: pfn_modify_allowed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool pfn_modify_allowed(long unsigned int pfn, pgprot_t prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mmap.c (ffffffff81085f20)
Location: arch/x86/mm/mmap.c:238
Inline: False
Direct callers:
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:__vm_insert_mixed
  - mm/memory.c:vmf_insert_pfn_prot
  - mm/mprotect.c:prot_none_hugetlb_entry
  - mm/mprotect.c:prot_none_pte_entry
```
**Symbols:**

```
ffffffff81085f20-ffffffff81085fc2: pfn_modify_allowed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool pfn_modify_allowed(long unsigned int pfn, pgprot_t prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mmap.c (ffffffff81089680)
Location: arch/x86/mm/mmap.c:238
Inline: False
Direct callers:
  - mm/memory.c:remap_pte_range
  - mm/memory.c:__vm_insert_mixed
  - mm/memory.c:vmf_insert_pfn_prot
  - mm/mprotect.c:prot_none_hugetlb_entry
  - mm/mprotect.c:prot_none_pte_entry
```
**Symbols:**

```
ffffffff81089680-ffffffff8108973c: pfn_modify_allowed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool pfn_modify_allowed(long unsigned int pfn, pgprot_t prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mmap.c (ffffffff81089860)
Location: arch/x86/mm/mmap.c:238
Inline: False
Direct callers:
  - mm/memory.c:remap_pte_range
  - mm/memory.c:__vm_insert_mixed
  - mm/memory.c:vmf_insert_pfn_prot
  - mm/mprotect.c:prot_none_hugetlb_entry
  - mm/mprotect.c:prot_none_pte_entry
```
**Symbols:**

```
ffffffff81089860-ffffffff8108991c: pfn_modify_allowed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool pfn_modify_allowed(long unsigned int pfn, pgprot_t prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mmap.c (ffffffff8108a550)
Location: arch/x86/mm/mmap.c:238
Inline: False
Direct callers:
  - mm/memory.c:remap_pfn_range_notrack
  - mm/memory.c:__vm_insert_mixed
  - mm/memory.c:vmf_insert_pfn_prot
  - mm/mprotect.c:prot_none_hugetlb_entry
  - mm/mprotect.c:prot_none_pte_entry
```
**Symbols:**

```
ffffffff8108a550-ffffffff8108a5b2: pfn_modify_allowed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
bool pfn_modify_allowed(long unsigned int pfn, pgprot_t prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/mmap.c (0)
Location: arch/x86/mm/mmap.c:238
Inline: False
Direct callers:
  - mm/memory.c:remap_pfn_range_notrack
  - mm/memory.c:__vm_insert_mixed
  - mm/memory.c:vmf_insert_pfn_prot
  - mm/mprotect.c:prot_none_hugetlb_entry
  - mm/mprotect.c:prot_none_pte_entry
```
**Symbols:**

```
ffffffff81ca1074-ffffffff81ca1093: pfn_modify_allowed.cold (STB_LOCAL)
ffffffff81099ac0-ffffffff81099b2f: pfn_modify_allowed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
bool pfn_modify_allowed(long unsigned int pfn, pgprot_t prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/mmap.c (0)
Location: arch/x86/mm/mmap.c:238
Inline: False
Direct callers:
  - mm/memory.c:remap_pfn_range_notrack
  - mm/memory.c:__vm_insert_mixed
  - mm/memory.c:vmf_insert_pfn_prot
  - mm/mprotect.c:prot_none_hugetlb_entry
  - mm/mprotect.c:prot_none_pte_entry
```
**Symbols:**

```
ffffffff81e50653-ffffffff81e50672: pfn_modify_allowed.cold (STB_LOCAL)
ffffffff810aca20-ffffffff810acb3e: pfn_modify_allowed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
bool pfn_modify_allowed(long unsigned int pfn, pgprot_t prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/mmap.c (0)
Location: arch/x86/mm/mmap.c:238
Inline: False
Direct callers:
  - mm/memory.c:remap_pfn_range_notrack
  - mm/memory.c:__vm_insert_mixed
  - mm/memory.c:vmf_insert_pfn_prot
  - mm/mprotect.c:prot_none_hugetlb_entry
  - mm/mprotect.c:prot_none_pte_entry
```
**Symbols:**

```
ffffffff82054b34-ffffffff82054b53: pfn_modify_allowed.cold (STB_LOCAL)
ffffffff810c6af0-ffffffff810c6bfa: pfn_modify_allowed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
bool pfn_modify_allowed(long unsigned int pfn, pgprot_t prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/mmap.c (0)
Location: arch/x86/mm/mmap.c:238
Inline: False
Direct callers:
  - mm/memory.c:remap_p4d_range
  - mm/memory.c:__vm_insert_mixed
  - mm/memory.c:vmf_insert_pfn_prot
  - mm/mprotect.c:prot_none_hugetlb_entry
  - mm/mprotect.c:prot_none_pte_entry
```
**Symbols:**

```
ffffffff820d313e-ffffffff820d3157: pfn_modify_allowed.cold (STB_LOCAL)
ffffffff810ca280-ffffffff810ca39b: pfn_modify_allowed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
bool pfn_modify_allowed(long unsigned int pfn, pgprot_t prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/mmap.c (0)
Location: arch/x86/mm/mmap.c:238
Inline: False
Direct callers:
  - mm/memory.c:remap_pfn_range_notrack
  - mm/memory.c:__vm_insert_mixed
  - mm/memory.c:vmf_insert_pfn_prot
  - mm/mprotect.c:prot_none_hugetlb_entry
  - mm/mprotect.c:prot_none_pte_entry
```
**Symbols:**

```
ffffffff821adfac-ffffffff821adfc5: pfn_modify_allowed.cold (STB_LOCAL)
ffffffff810d26e0-ffffffff810d2830: pfn_modify_allowed (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (0)
Location: include/asm-generic/pgtable.h:1131
Inline: True
```
```
In mm/mprotect.c (0)
Location: include/asm-generic/pgtable.h:1131
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (0)
Location: include/asm-generic/pgtable.h:1131
Inline: True
```
```
In mm/mprotect.c (0)
Location: include/asm-generic/pgtable.h:1131
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (0)
Location: include/asm-generic/pgtable.h:1131
Inline: True
```
```
In mm/mprotect.c (0)
Location: include/asm-generic/pgtable.h:1131
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (0)
Location: include/asm-generic/pgtable.h:1131
Inline: True
```
```
In mm/mprotect.c (0)
Location: include/asm-generic/pgtable.h:1131
Inline: True
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
bool pfn_modify_allowed(long unsigned int pfn, pgprot_t prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mmap.c (ffffffff81084f20)
Location: arch/x86/mm/mmap.c:238
Inline: False
Direct callers:
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:__vm_insert_mixed
  - mm/memory.c:vmf_insert_pfn_prot
  - mm/mprotect.c:prot_none_hugetlb_entry
  - mm/mprotect.c:prot_none_pte_entry
```
**Symbols:**

```
ffffffff81084f20-ffffffff81084fc2: pfn_modify_allowed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool pfn_modify_allowed(long unsigned int pfn, pgprot_t prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mmap.c (ffffffff81073bf0)
Location: arch/x86/mm/mmap.c:238
Inline: False
Direct callers:
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:__vm_insert_mixed
  - mm/memory.c:vmf_insert_pfn_prot
  - mm/mprotect.c:prot_none_hugetlb_entry
  - mm/mprotect.c:prot_none_pte_entry
```
**Symbols:**

```
ffffffff81073bf0-ffffffff81073c92: pfn_modify_allowed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool pfn_modify_allowed(long unsigned int pfn, pgprot_t prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mmap.c (ffffffff81084ed0)
Location: arch/x86/mm/mmap.c:238
Inline: False
Direct callers:
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:__vm_insert_mixed
  - mm/memory.c:vmf_insert_pfn_prot
  - mm/mprotect.c:prot_none_hugetlb_entry
  - mm/mprotect.c:prot_none_pte_entry
```
**Symbols:**

```
ffffffff81084ed0-ffffffff81084f72: pfn_modify_allowed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool pfn_modify_allowed(long unsigned int pfn, pgprot_t prot);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mmap.c (ffffffff81087020)
Location: arch/x86/mm/mmap.c:238
Inline: False
Direct callers:
  - mm/memory.c:remap_pfn_range
  - mm/memory.c:__vm_insert_mixed
  - mm/memory.c:vmf_insert_pfn_prot
  - mm/mprotect.c:prot_none_hugetlb_entry
  - mm/mprotect.c:prot_none_pte_entry
```
**Symbols:**

```
ffffffff81087020-ffffffff810870c2: pfn_modify_allowed (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
