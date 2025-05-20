# Function: <code>mm_find_pmd</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
pmd_t *mm_find_pmd(struct mm_struct *mm, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff811ca820)
Location: mm/rmap.c:717
Inline: False
Direct callers:
  - mm/rmap.c:__page_check_address
  - mm/ksm.c:try_to_merge_with_ksm_page
  - mm/migrate.c:remove_migration_pte
  - mm/huge_memory.c:khugepaged
  - mm/huge_memory.c:khugepaged
```
**Symbols:**

```
ffffffff811ca820-ffffffff811ca90d: mm_find_pmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
pmd_t *mm_find_pmd(struct mm_struct *mm, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff811e7230)
Location: mm/rmap.c:685
Inline: False
Direct callers:
  - mm/rmap.c:__page_check_address
  - mm/ksm.c:try_to_merge_with_ksm_page
  - mm/migrate.c:remove_migration_pte
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
```
**Symbols:**

```
ffffffff811e7230-ffffffff811e732c: mm_find_pmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
pmd_t *mm_find_pmd(struct mm_struct *mm, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff811f85c0)
Location: mm/rmap.c:684
Inline: False
Direct callers:
  - mm/rmap.c:__page_check_address
  - mm/ksm.c:try_to_merge_one_page
  - mm/migrate.c:remove_migration_pte
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:__collapse_huge_page_swapin
```
**Symbols:**

```
ffffffff811f85c0-ffffffff811f86bc: mm_find_pmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
pmd_t *mm_find_pmd(struct mm_struct *mm, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff81203a60)
Location: mm/rmap.c:708
Inline: False
Direct callers:
  - mm/ksm.c:try_to_merge_one_page
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:__collapse_huge_page_swapin
```
**Symbols:**

```
ffffffff81203a60-ffffffff81203b5c: mm_find_pmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
pmd_t *mm_find_pmd(struct mm_struct *mm, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff8121c760)
Location: mm/rmap.c:709
Inline: False
Direct callers:
  - mm/ksm.c:try_to_merge_one_page
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:__collapse_huge_page_swapin
```
**Symbols:**

```
ffffffff8121c760-ffffffff8121c8c5: mm_find_pmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
pmd_t *mm_find_pmd(struct mm_struct *mm, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff8123e550)
Location: mm/rmap.c:710
Inline: False
Direct callers:
  - mm/ksm.c:try_to_merge_one_page
  - mm/khugepaged.c:khugepaged_scan_mm_slot
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:__collapse_huge_page_swapin
```
**Symbols:**

```
ffffffff8123e550-ffffffff8123e65e: mm_find_pmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
pmd_t *mm_find_pmd(struct mm_struct *mm, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff81252ae0)
Location: mm/rmap.c:710
Inline: False
Direct callers:
  - mm/ksm.c:try_to_merge_one_page
  - mm/khugepaged.c:khugepaged
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:__collapse_huge_page_swapin
```
**Symbols:**

```
ffffffff81252ae0-ffffffff81252bee: mm_find_pmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
pmd_t *mm_find_pmd(struct mm_struct *mm, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff81264e60)
Location: mm/rmap.c:710
Inline: False
Direct callers:
  - mm/ksm.c:replace_page
  - mm/khugepaged.c:collapse_shmem
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:__collapse_huge_page_swapin
```
**Symbols:**

```
ffffffff81264e60-ffffffff81264f70: mm_find_pmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
pmd_t *mm_find_pmd(struct mm_struct *mm, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff812736f0)
Location: mm/rmap.c:711
Inline: False
Direct callers:
  - mm/ksm.c:replace_page
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:__collapse_huge_page_swapin
```
**Symbols:**

```
ffffffff812736f0-ffffffff81273800: mm_find_pmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
pmd_t *mm_find_pmd(struct mm_struct *mm, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff812a4870)
Location: mm/rmap.c:724
Inline: False
Direct callers:
  - mm/ksm.c:replace_page
  - mm/khugepaged.c:retract_page_tables
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:__collapse_huge_page_swapin
```
**Symbols:**

```
ffffffff812a4870-ffffffff812a49c8: mm_find_pmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
pmd_t *mm_find_pmd(struct mm_struct *mm, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff812b0000)
Location: mm/rmap.c:724
Inline: False
Direct callers:
  - mm/ksm.c:replace_page
  - mm/khugepaged.c:retract_page_tables
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:__collapse_huge_page_swapin
```
**Symbols:**

```
ffffffff812b0000-ffffffff812b0158: mm_find_pmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
pmd_t *mm_find_pmd(struct mm_struct *mm, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff812b5620)
Location: mm/rmap.c:728
Inline: False
Direct callers:
  - mm/ksm.c:replace_page
  - mm/khugepaged.c:retract_page_tables
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:__collapse_huge_page_swapin
```
**Symbols:**

```
ffffffff812b5620-ffffffff812b5756: mm_find_pmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
pmd_t *mm_find_pmd(struct mm_struct *mm, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/rmap.c (0)
Location: mm/rmap.c:729
Inline: False
Direct callers:
  - mm/ksm.c:replace_page
  - mm/khugepaged.c:retract_page_tables
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:__collapse_huge_page_swapin
```
**Symbols:**

```
ffffffff81cbcd65-ffffffff81cbcd7e: mm_find_pmd.cold (STB_LOCAL)
ffffffff812f72a0-ffffffff812f73ed: mm_find_pmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
pmd_t *mm_find_pmd(struct mm_struct *mm, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/rmap.c (0)
Location: mm/rmap.c:773
Inline: False
Direct callers:
  - mm/ksm.c:replace_page
  - mm/khugepaged.c:retract_page_tables
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:__collapse_huge_page_swapin
```
**Symbols:**

```
ffffffff81e6e9ca-ffffffff81e6e9e3: mm_find_pmd.cold (STB_LOCAL)
ffffffff8135c8b0-ffffffff8135ca15: mm_find_pmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
pmd_t *mm_find_pmd(struct mm_struct *mm, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/rmap.c (0)
Location: mm/rmap.c:773
Inline: False
Direct callers:
  - mm/ksm.c:replace_page
  - mm/huge_memory.c:vma_adjust_trans_huge
  - mm/huge_memory.c:vma_adjust_trans_huge
  - mm/huge_memory.c:vma_adjust_trans_huge
  - mm/khugepaged.c:find_pmd_or_thp_or_none
```
**Symbols:**

```
ffffffff82064879-ffffffff82064892: mm_find_pmd.cold (STB_LOCAL)
ffffffff813d6f90-ffffffff813d70a9: mm_find_pmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
pmd_t *mm_find_pmd(struct mm_struct *mm, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/rmap.c (0)
Location: mm/rmap.c:776
Inline: False
Direct callers:
  - mm/ksm.c:replace_page
  - mm/huge_memory.c:vma_adjust_trans_huge
  - mm/huge_memory.c:vma_adjust_trans_huge
  - mm/huge_memory.c:vma_adjust_trans_huge
  - mm/khugepaged.c:find_pmd_or_thp_or_none
```
**Symbols:**

```
ffffffff820e3fbe-ffffffff820e3fd7: mm_find_pmd.cold (STB_LOCAL)
ffffffff8140be90-ffffffff8140bfac: mm_find_pmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
pmd_t *mm_find_pmd(struct mm_struct *mm, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/rmap.c (0)
Location: mm/rmap.c:801
Inline: False
Direct callers:
  - mm/ksm.c:replace_page
  - mm/huge_memory.c:vma_adjust_trans_huge
  - mm/huge_memory.c:vma_adjust_trans_huge
  - mm/huge_memory.c:vma_adjust_trans_huge
  - mm/khugepaged.c:find_pmd_or_thp_or_none
  - mm/userfaultfd.c:move_pages
```
**Symbols:**

```
ffffffff821c0bec-ffffffff821c0c05: mm_find_pmd.cold (STB_LOCAL)
ffffffff81438730-ffffffff8143884c: mm_find_pmd (STB_GLOBAL)
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
pmd_t *mm_find_pmd(struct mm_struct *mm, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffff800010309290)
Location: mm/rmap.c:711
Inline: False
Direct callers:
  - mm/ksm.c:try_to_merge_one_page
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:__collapse_huge_page_swapin
```
**Symbols:**

```
ffff800010309290-ffff800010309324: mm_find_pmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
pmd_t *mm_find_pmd(struct mm_struct *mm, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (c0525fa0)
Location: mm/rmap.c:711
Inline: False
Direct callers:
  - mm/ksm.c:replace_page
```
**Symbols:**

```
c0525fa0-c0525fd0: mm_find_pmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
pmd_t *mm_find_pmd(struct mm_struct *mm, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (c0000000003d86a0)
Location: mm/rmap.c:711
Inline: False
Direct callers:
  - mm/ksm.c:replace_page
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:__collapse_huge_page_swapin
```
**Symbols:**

```
c0000000003d86a0-c0000000003d887c: mm_find_pmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
pmd_t *mm_find_pmd(struct mm_struct *mm, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffe00021372e)
Location: mm/rmap.c:711
Inline: False
Direct callers:
  - mm/ksm.c:try_to_merge_one_page
```
**Symbols:**

```
ffffffe00021372e-ffffffe00021379a: mm_find_pmd (STB_GLOBAL)
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
pmd_t *mm_find_pmd(struct mm_struct *mm, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff8126bd40)
Location: mm/rmap.c:711
Inline: False
Direct callers:
  - mm/ksm.c:replace_page
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:__collapse_huge_page_swapin
```
**Symbols:**

```
ffffffff8126bd40-ffffffff8126be50: mm_find_pmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
pmd_t *mm_find_pmd(struct mm_struct *mm, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff8125dde0)
Location: mm/rmap.c:711
Inline: False
Direct callers:
  - mm/ksm.c:replace_page
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:__collapse_huge_page_swapin
```
**Symbols:**

```
ffffffff8125dde0-ffffffff8125deb6: mm_find_pmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
pmd_t *mm_find_pmd(struct mm_struct *mm, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff81269ae0)
Location: mm/rmap.c:711
Inline: False
Direct callers:
  - mm/ksm.c:replace_page
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:__collapse_huge_page_swapin
```
**Symbols:**

```
ffffffff81269ae0-ffffffff81269bf0: mm_find_pmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
pmd_t *mm_find_pmd(struct mm_struct *mm, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff81279450)
Location: mm/rmap.c:711
Inline: False
Direct callers:
  - mm/ksm.c:replace_page
  - mm/khugepaged.c:collapse_file
  - mm/khugepaged.c:collapse_pte_mapped_thp
  - mm/khugepaged.c:khugepaged_scan_pmd
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:collapse_huge_page
  - mm/khugepaged.c:__collapse_huge_page_swapin
```
**Symbols:**

```
ffffffff81279450-ffffffff81279560: mm_find_pmd (STB_GLOBAL)
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
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
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
