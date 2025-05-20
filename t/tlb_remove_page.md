# Function: <code>tlb_remove_page</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff81070c5f)
Location: include/asm-generic/tlb.h:124
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:___pte_free_tlb
  - arch/x86/mm/pgtable.c:___pmd_free_tlb
  - arch/x86/mm/pgtable.c:___pud_free_tlb
```
```
In mm/huge_memory.c (ffffffff811f6a74)
Location: include/asm-generic/tlb.h:124
Inline: True
Inline callers:
  - mm/huge_memory.c:zap_huge_pmd
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff81070bf1)
Location: include/asm-generic/tlb.h:170
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:___pud_free_tlb
  - arch/x86/mm/pgtable.c:___pmd_free_tlb
  - arch/x86/mm/pgtable.c:___pte_free_tlb
```
```
In mm/huge_memory.c (ffffffff8121575e)
Location: include/asm-generic/tlb.h:170
Inline: True
Inline callers:
  - mm/huge_memory.c:zap_huge_pmd
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
In arch/x86/mm/pgtable.c (ffffffff810747d4)
Location: include/asm-generic/tlb.h:156
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:___pud_free_tlb
  - arch/x86/mm/pgtable.c:___pmd_free_tlb
  - arch/x86/mm/pgtable.c:___pte_free_tlb
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
In arch/x86/mm/pgtable.c (ffffffff81073d27)
Location: include/asm-generic/tlb.h:157
Inline: True
Inline callers:
  - arch/x86/mm/pgtable.c:___pud_free_tlb
  - arch/x86/mm/pgtable.c:___pmd_free_tlb
  - arch/x86/mm/pgtable.c:___pte_free_tlb
```
</details>
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void tlb_remove_page(struct mmu_gather *tlb, struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff81073f60)
Location: include/asm-generic/tlb.h:194
Inline: False
```
**Symbols:**

```
ffffffff81073f60-ffffffff81073f84: tlb_remove_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void tlb_remove_page(struct mmu_gather *tlb, struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff81077ae0)
Location: include/asm-generic/tlb.h:421
Inline: False
```
**Symbols:**

```
ffffffff81077ae0-ffffffff81077b07: tlb_remove_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void tlb_remove_page(struct mmu_gather *tlb, struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff81078b50)
Location: include/asm-generic/tlb.h:429
Inline: False
```
**Symbols:**

```
ffffffff81078b50-ffffffff81078b77: tlb_remove_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void tlb_remove_page(struct mmu_gather *tlb, struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff8107fe50)
Location: include/asm-generic/tlb.h:446
Inline: False
```
**Symbols:**

```
ffffffff8107fe50-ffffffff8107fe7b: tlb_remove_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void tlb_remove_page(struct mmu_gather *tlb, struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff8107fa70)
Location: include/asm-generic/tlb.h:445
Inline: False
```
**Symbols:**

```
ffffffff8107fa70-ffffffff8107fa9b: tlb_remove_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void tlb_remove_page(struct mmu_gather *tlb, struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff81080b90)
Location: include/asm-generic/tlb.h:447
Inline: False
```
**Symbols:**

```
ffffffff81080b90-ffffffff81080bbb: tlb_remove_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void tlb_remove_page(struct mmu_gather *tlb, struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff8108fad0)
Location: include/asm-generic/tlb.h:447
Inline: False
```
**Symbols:**

```
ffffffff8108fad0-ffffffff8108fafb: tlb_remove_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void tlb_remove_page(struct mmu_gather *tlb, struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff810a08d0)
Location: include/asm-generic/tlb.h:447
Inline: False
```
**Symbols:**

```
ffffffff810a08d0-ffffffff810a0912: tlb_remove_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void tlb_remove_page(struct mmu_gather *tlb, struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff810b8580)
Location: include/asm-generic/tlb.h:479
Inline: False
```
**Symbols:**

```
ffffffff810b8580-ffffffff810b85c2: tlb_remove_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void tlb_remove_page(struct mmu_gather *tlb, struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff810bb780)
Location: include/asm-generic/tlb.h:479
Inline: False
```
**Symbols:**

```
ffffffff810bb780-ffffffff810bb7c2: tlb_remove_page (STB_LOCAL)
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
In arch/x86/kernel/paravirt.c (ffffffff810c2ba2)
Location: include/asm-generic/tlb.h:478
Inline: True
Inline callers:
  - arch/x86/kernel/paravirt.c:native_tlb_remove_table
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
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (c05175fc)
Location: include/asm-generic/tlb.h:429
Inline: True
Inline callers:
  - mm/memory.c:free_pgd_range
```
</details>
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffe000206b12)
Location: include/asm-generic/tlb.h:429
Inline: True
Inline callers:
  - mm/memory.c:free_pgd_range
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
void tlb_remove_page(struct mmu_gather *tlb, struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff81077b50)
Location: include/asm-generic/tlb.h:429
Inline: False
```
**Symbols:**

```
ffffffff81077b50-ffffffff81077b77: tlb_remove_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void tlb_remove_page(struct mmu_gather *tlb, struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff81067770)
Location: include/asm-generic/tlb.h:429
Inline: False
```
**Symbols:**

```
ffffffff81067770-ffffffff81067797: tlb_remove_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void tlb_remove_page(struct mmu_gather *tlb, struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff81077b00)
Location: include/asm-generic/tlb.h:429
Inline: False
```
**Symbols:**

```
ffffffff81077b00-ffffffff81077b27: tlb_remove_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void tlb_remove_page(struct mmu_gather *tlb, struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/paravirt.c (ffffffff81079ba0)
Location: include/asm-generic/tlb.h:429
Inline: False
```
**Symbols:**

```
ffffffff81079ba0-ffffffff81079bc7: tlb_remove_page (STB_LOCAL)
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
