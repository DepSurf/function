# Function: <code>tlb_remove_table</code>

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
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void tlb_remove_table(struct mmu_gather *tlb, void *table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81209730)
Location: mm/memory.c:375
Inline: False
Direct callers:
  - arch/x86/mm/pgtable.c:___pud_free_tlb
  - arch/x86/mm/pgtable.c:___pmd_free_tlb
  - arch/x86/mm/pgtable.c:___pte_free_tlb
```
**Symbols:**

```
ffffffff81209730-ffffffff812097d6: tlb_remove_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void tlb_remove_table(struct mmu_gather *tlb, void *table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8122a5b0)
Location: mm/memory.c:390
Inline: False
Direct callers:
  - arch/x86/mm/pgtable.c:___pud_free_tlb
  - arch/x86/mm/pgtable.c:___pmd_free_tlb
  - arch/x86/mm/pgtable.c:___pte_free_tlb
```
**Symbols:**

```
ffffffff8122a5b0-ffffffff8122a644: tlb_remove_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void tlb_remove_table(struct mmu_gather *tlb, void *table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_gather.c (ffffffff8124cea0)
Location: mm/mmu_gather.c:207
Inline: False
```
**Symbols:**

```
ffffffff8124cea0-ffffffff8124d008: tlb_remove_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void tlb_remove_table(struct mmu_gather *tlb, void *table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_gather.c (ffffffff8125f010)
Location: mm/mmu_gather.c:157
Inline: False
```
**Symbols:**

```
ffffffff8125f010-ffffffff8125f19e: tlb_remove_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void tlb_remove_table(struct mmu_gather *tlb, void *table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_gather.c (ffffffff8126d820)
Location: mm/mmu_gather.c:157
Inline: False
```
**Symbols:**

```
ffffffff8126d820-ffffffff8126d9ae: tlb_remove_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void tlb_remove_table(struct mmu_gather *tlb, void *table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_gather.c (ffffffff8129d8e0)
Location: mm/mmu_gather.c:207
Inline: False
```
**Symbols:**

```
ffffffff8129d8e0-ffffffff8129dbac: tlb_remove_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void tlb_remove_table(struct mmu_gather *tlb, void *table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_gather.c (ffffffff812a8c60)
Location: mm/mmu_gather.c:207
Inline: False
```
**Symbols:**

```
ffffffff812a8c60-ffffffff812a8f2c: tlb_remove_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void tlb_remove_table(struct mmu_gather *tlb, void *table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_gather.c (ffffffff812ae110)
Location: mm/mmu_gather.c:207
Inline: False
```
**Symbols:**

```
ffffffff812ae110-ffffffff812ae399: tlb_remove_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void tlb_remove_table(struct mmu_gather *tlb, void *table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_gather.c (ffffffff812ef8b0)
Location: mm/mmu_gather.c:207
Inline: False
```
**Symbols:**

```
ffffffff812ef8b0-ffffffff812efb39: tlb_remove_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void tlb_remove_table(struct mmu_gather *tlb, void *table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_gather.c (ffffffff81352db0)
Location: mm/mmu_gather.c:220
Inline: False
```
**Symbols:**

```
ffffffff81352db0-ffffffff8135305b: tlb_remove_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void tlb_remove_table(struct mmu_gather *tlb, void *table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_gather.c (ffffffff813cd040)
Location: mm/mmu_gather.c:257
Inline: False
```
**Symbols:**

```
ffffffff813cd040-ffffffff813cd2e8: tlb_remove_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void tlb_remove_table(struct mmu_gather *tlb, void *table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_gather.c (ffffffff814019a0)
Location: mm/mmu_gather.c:257
Inline: False
```
**Symbols:**

```
ffffffff814019a0-ffffffff81401c48: tlb_remove_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void tlb_remove_table(struct mmu_gather *tlb, void *table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_gather.c (ffffffff8142e060)
Location: mm/mmu_gather.c:258
Inline: False
```
**Symbols:**

```
ffffffff8142e060-ffffffff8142e2b6: tlb_remove_table (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void tlb_remove_table(struct mmu_gather *tlb, void *table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_gather.c (ffff800010304ba8)
Location: mm/mmu_gather.c:157
Inline: False
Direct callers:
  - mm/memory.c:free_pgd_range
  - mm/memory.c:free_pgd_range
  - mm/memory.c:free_pgd_range
```
**Symbols:**

```
ffff800010304ba8-ffff800010304c60: tlb_remove_table (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void tlb_remove_table(struct mmu_gather *tlb, void *table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_gather.c (c0000000003d1650)
Location: mm/mmu_gather.c:157
Inline: False
Direct callers:
  - arch/powerpc/mm/book3s64/pgtable.c:pgtable_free_tlb
```
**Symbols:**

```
c0000000003d1650-c0000000003d18f0: tlb_remove_table (STB_GLOBAL)
```
</details>
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
void tlb_remove_table(struct mmu_gather *tlb, void *table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_gather.c (ffffffff81265e70)
Location: mm/mmu_gather.c:157
Inline: False
```
**Symbols:**

```
ffffffff81265e70-ffffffff81265ffe: tlb_remove_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void tlb_remove_table(struct mmu_gather *tlb, void *table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_gather.c (ffffffff81258290)
Location: mm/mmu_gather.c:157
Inline: False
```
**Symbols:**

```
ffffffff81258290-ffffffff8125841e: tlb_remove_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void tlb_remove_table(struct mmu_gather *tlb, void *table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_gather.c (ffffffff81263c10)
Location: mm/mmu_gather.c:157
Inline: False
```
**Symbols:**

```
ffffffff81263c10-ffffffff81263d9e: tlb_remove_table (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void tlb_remove_table(struct mmu_gather *tlb, void *table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_gather.c (ffffffff812735d0)
Location: mm/mmu_gather.c:157
Inline: False
```
**Symbols:**

```
ffffffff812735d0-ffffffff8127375e: tlb_remove_table (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
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
