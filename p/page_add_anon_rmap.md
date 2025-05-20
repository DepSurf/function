# Function: <code>page_add_anon_rmap</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void page_add_anon_rmap(struct page *page, struct vm_area_struct *vma, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff811caef0)
Location: mm/rmap.c:1140
Inline: False
Direct callers:
  - mm/swapfile.c:unuse_mm
  - mm/ksm.c:try_to_merge_with_ksm_page
  - mm/migrate.c:remove_migration_pte
  - mm/migrate.c:migrate_misplaced_transhuge_page
```
**Symbols:**

```
ffffffff811caef0-ffffffff811caf02: page_add_anon_rmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void page_add_anon_rmap(struct page *page, struct vm_area_struct *vma, long unsigned int address, bool compound);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff811e7d40)
Location: mm/rmap.c:1180
Inline: False
Direct callers:
  - mm/swapfile.c:unuse_mm
  - mm/ksm.c:try_to_merge_with_ksm_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:remove_migration_pte
```
**Symbols:**

```
ffffffff811e7d40-ffffffff811e7d5a: page_add_anon_rmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void page_add_anon_rmap(struct page *page, struct vm_area_struct *vma, long unsigned int address, bool compound);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff811f90c0)
Location: mm/rmap.c:1179
Inline: False
Direct callers:
  - mm/swapfile.c:unuse_mm
  - mm/ksm.c:try_to_merge_one_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:remove_migration_pte
```
**Symbols:**

```
ffffffff811f90c0-ffffffff811f90da: page_add_anon_rmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void page_add_anon_rmap(struct page *page, struct vm_area_struct *vma, long unsigned int address, bool compound);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff81203c70)
Location: mm/rmap.c:1082
Inline: False
Direct callers:
  - mm/swapfile.c:unuse_mm
  - mm/ksm.c:try_to_merge_one_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:remove_migration_pte
```
**Symbols:**

```
ffffffff81203c70-ffffffff81203c8a: page_add_anon_rmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void page_add_anon_rmap(struct page *page, struct vm_area_struct *vma, long unsigned int address, bool compound);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff8121c9e0)
Location: mm/rmap.c:1086
Inline: False
Direct callers:
  - mm/swapfile.c:unuse_mm
  - mm/ksm.c:try_to_merge_one_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:remove_migration_pte
  - mm/huge_memory.c:remove_migration_pmd
```
**Symbols:**

```
ffffffff8121c9e0-ffffffff8121c9fa: page_add_anon_rmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void page_add_anon_rmap(struct page *page, struct vm_area_struct *vma, long unsigned int address, bool compound);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff8123e770)
Location: mm/rmap.c:1087
Inline: False
Direct callers:
  - mm/swapfile.c:unuse_vma
  - mm/ksm.c:try_to_merge_one_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:remove_migration_pte
  - mm/huge_memory.c:remove_migration_pmd
```
**Symbols:**

```
ffffffff8123e770-ffffffff8123e78a: page_add_anon_rmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void page_add_anon_rmap(struct page *page, struct vm_area_struct *vma, long unsigned int address, bool compound);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff81252d00)
Location: mm/rmap.c:1089
Inline: False
Direct callers:
  - mm/swapfile.c:unuse_vma
  - mm/ksm.c:try_to_merge_one_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:remove_migration_pte
  - mm/huge_memory.c:remove_migration_pmd
```
**Symbols:**

```
ffffffff81252d00-ffffffff81252d1a: page_add_anon_rmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void page_add_anon_rmap(struct page *page, struct vm_area_struct *vma, long unsigned int address, bool compound);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff812650a0)
Location: mm/rmap.c:1090
Inline: False
Direct callers:
  - mm/ksm.c:replace_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:remove_migration_pte
  - mm/huge_memory.c:remove_migration_pmd
```
**Symbols:**

```
ffffffff812650a0-ffffffff812650ba: page_add_anon_rmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void page_add_anon_rmap(struct page *page, struct vm_area_struct *vma, long unsigned int address, bool compound);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff81273930)
Location: mm/rmap.c:1088
Inline: False
Direct callers:
  - mm/ksm.c:replace_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:remove_migration_pte
  - mm/huge_memory.c:remove_migration_pmd
```
**Symbols:**

```
ffffffff81273930-ffffffff8127394a: page_add_anon_rmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void page_add_anon_rmap(struct page *page, struct vm_area_struct *vma, long unsigned int address, bool compound);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff812a4c00)
Location: mm/rmap.c:1100
Inline: False
Direct callers:
  - mm/swapfile.c:unuse_pte
  - mm/ksm.c:replace_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:remove_migration_pte
  - mm/huge_memory.c:remove_migration_pmd
```
**Symbols:**

```
ffffffff812a4c00-ffffffff812a4c1a: page_add_anon_rmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void page_add_anon_rmap(struct page *page, struct vm_area_struct *vma, long unsigned int address, bool compound);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff812b02b0)
Location: mm/rmap.c:1106
Inline: False
Direct callers:
  - mm/swapfile.c:unuse_pte
  - mm/ksm.c:replace_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:remove_migration_pte
  - mm/huge_memory.c:remove_migration_pmd
```
**Symbols:**

```
ffffffff812b02b0-ffffffff812b02ca: page_add_anon_rmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void page_add_anon_rmap(struct page *page, struct vm_area_struct *vma, long unsigned int address, bool compound);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff812b58b0)
Location: mm/rmap.c:1109
Inline: False
Direct callers:
  - mm/swapfile.c:unuse_pte
  - mm/ksm.c:replace_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:remove_migration_pte
  - mm/huge_memory.c:remove_migration_pmd
```
**Symbols:**

```
ffffffff812b58b0-ffffffff812b58c5: page_add_anon_rmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void page_add_anon_rmap(struct page *page, struct vm_area_struct *vma, long unsigned int address, bool compound);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff812f7540)
Location: mm/rmap.c:1110
Inline: False
Direct callers:
  - mm/memory.c:restore_exclusive_pte
  - mm/swapfile.c:unuse_pte
  - mm/ksm.c:replace_page
  - mm/migrate.c:remove_migration_pte
  - mm/huge_memory.c:remove_migration_pmd
```
**Symbols:**

```
ffffffff812f7540-ffffffff812f7555: page_add_anon_rmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void page_add_anon_rmap(struct page *page, struct vm_area_struct *vma, long unsigned int address, rmap_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff8135cd20)
Location: mm/rmap.c:1200
Inline: False
Direct callers:
  - mm/memory.c:do_swap_page
  - mm/memory.c:restore_exclusive_pte
  - mm/swapfile.c:unuse_pte
  - mm/ksm.c:replace_page
  - mm/migrate.c:remove_migration_pte
  - mm/huge_memory.c:remove_migration_pmd
```
**Symbols:**

```
ffffffff8135cd20-ffffffff8135cfbd: page_add_anon_rmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void page_add_anon_rmap(struct page *page, struct vm_area_struct *vma, long unsigned int address, rmap_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff813d7760)
Location: mm/rmap.c:1217
Inline: False
Direct callers:
  - mm/memory.c:do_swap_page
  - mm/memory.c:restore_exclusive_pte
  - mm/swapfile.c:unuse_pte
  - mm/ksm.c:replace_page
  - mm/migrate.c:remove_migration_pte
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:__split_huge_pmd_locked
```
**Symbols:**

```
ffffffff813d7760-ffffffff813d7b41: page_add_anon_rmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void page_add_anon_rmap(struct page *page, struct vm_area_struct *vma, long unsigned int address, rmap_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff8140c390)
Location: mm/rmap.c:1215
Inline: False
Direct callers:
  - mm/memory.c:do_swap_page
  - mm/memory.c:restore_exclusive_pte
  - mm/swapfile.c:unuse_pte
  - mm/ksm.c:replace_page
  - mm/migrate.c:remove_migration_pte
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:__split_huge_pmd_locked
```
**Symbols:**

```
ffffffff8140c390-ffffffff8140c642: page_add_anon_rmap (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void page_add_anon_rmap(struct page *page, struct vm_area_struct *vma, long unsigned int address, bool compound);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffff800010309498)
Location: mm/rmap.c:1088
Inline: False
Direct callers:
  - mm/swapfile.c:unuse_pte_range
  - mm/ksm.c:try_to_merge_one_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:remove_migration_pte
```
**Symbols:**

```
ffff800010309498-ffff8000103094ec: page_add_anon_rmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void page_add_anon_rmap(struct page *page, struct vm_area_struct *vma, long unsigned int address, bool compound);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (c0526108)
Location: mm/rmap.c:1088
Inline: False
Direct callers:
  - mm/swapfile.c:unuse_mm
  - mm/ksm.c:replace_page
  - mm/migrate.c:remove_migration_pte
```
**Symbols:**

```
c0526108-c0526130: page_add_anon_rmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void page_add_anon_rmap(struct page *page, struct vm_area_struct *vma, long unsigned int address, bool compound);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (c0000000003d8a80)
Location: mm/rmap.c:1088
Inline: False
Direct callers:
  - mm/swapfile.c:unuse_pte_range
  - mm/ksm.c:replace_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:remove_migration_pte
  - mm/huge_memory.c:remove_migration_pmd
```
**Symbols:**

```
c0000000003d8a80-c0000000003d8aa0: page_add_anon_rmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void page_add_anon_rmap(struct page *page, struct vm_area_struct *vma, long unsigned int address, bool compound);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffe0002138c4)
Location: mm/rmap.c:1088
Inline: False
Direct callers:
  - mm/swapfile.c:unuse_pte_range
  - mm/ksm.c:try_to_merge_one_page
  - mm/migrate.c:remove_migration_pte
```
**Symbols:**

```
ffffffe0002138c4-ffffffe00021390a: page_add_anon_rmap (STB_GLOBAL)
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
void page_add_anon_rmap(struct page *page, struct vm_area_struct *vma, long unsigned int address, bool compound);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff8126bf80)
Location: mm/rmap.c:1088
Inline: False
Direct callers:
  - mm/ksm.c:replace_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:remove_migration_pte
  - mm/huge_memory.c:remove_migration_pmd
```
**Symbols:**

```
ffffffff8126bf80-ffffffff8126bf9a: page_add_anon_rmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void page_add_anon_rmap(struct page *page, struct vm_area_struct *vma, long unsigned int address, bool compound);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff8125dff0)
Location: mm/rmap.c:1088
Inline: False
Direct callers:
  - mm/swapfile.c:unuse_pte_range
  - mm/ksm.c:replace_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:remove_migration_pte
  - mm/huge_memory.c:remove_migration_pmd
```
**Symbols:**

```
ffffffff8125dff0-ffffffff8125e00a: page_add_anon_rmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void page_add_anon_rmap(struct page *page, struct vm_area_struct *vma, long unsigned int address, bool compound);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff81269d20)
Location: mm/rmap.c:1088
Inline: False
Direct callers:
  - mm/ksm.c:replace_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:remove_migration_pte
  - mm/huge_memory.c:remove_migration_pmd
```
**Symbols:**

```
ffffffff81269d20-ffffffff81269d3a: page_add_anon_rmap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void page_add_anon_rmap(struct page *page, struct vm_area_struct *vma, long unsigned int address, bool compound);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff81279690)
Location: mm/rmap.c:1088
Inline: False
Direct callers:
  - mm/ksm.c:replace_page
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/migrate.c:remove_migration_pte
  - mm/huge_memory.c:remove_migration_pmd
```
**Symbols:**

```
ffffffff81279690-ffffffff812796aa: page_add_anon_rmap (STB_GLOBAL)
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
<b>Param added. </b>
<code>bool compound</code>
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
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>rmap_t flags</code>
</li>
<li>
<b>Param removed. </b>
<code>bool compound</code>
</li>
</ul>
</details>
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
