# Function: <code>pmdp_huge_clear_flush</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In None (0)
Location: None
Inline: False
Direct callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/huge_memory.c:__split_huge_page_pmd
  - mm/huge_memory.c:__split_huge_page_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
```
**Symbols:**

```
ffffffff811d0710-ffffffff811d0720: pmdp_huge_clear_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
pmd_t pmdp_huge_clear_flush(struct vm_area_struct *vma, long unsigned int address, pmd_t *pmdp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pgtable-generic.c (0)
Location: mm/pgtable-generic.c:116
Inline: False
Direct callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
```
**Symbols:**

```
ffffffff811ed860-ffffffff811ed870: pmdp_huge_clear_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
pmd_t pmdp_huge_clear_flush(struct vm_area_struct *vma, long unsigned int address, pmd_t *pmdp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pgtable-generic.c (0)
Location: mm/pgtable-generic.c:116
Inline: False
Direct callers:
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
```
**Symbols:**

```
ffffffff811f7c30-ffffffff811f7c40: pmdp_huge_clear_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
pmd_t pmdp_huge_clear_flush(struct vm_area_struct *vma, long unsigned int address, pmd_t *pmdp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pgtable-generic.c (ffffffff81202be0)
Location: mm/pgtable-generic.c:122
Inline: False
Direct callers:
  - mm/rmap.c:page_mkclean_one
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - fs/dax.c:dax_writeback_mapping_range
```
**Symbols:**

```
ffffffff81202be0-ffffffff81202c09: pmdp_huge_clear_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
pmd_t pmdp_huge_clear_flush(struct vm_area_struct *vma, long unsigned int address, pmd_t *pmdp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pgtable-generic.c (ffffffff8121b940)
Location: mm/pgtable-generic.c:123
Inline: False
Direct callers:
  - mm/rmap.c:page_mkclean_one
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - fs/dax.c:dax_writeback_mapping_range
```
**Symbols:**

```
ffffffff8121b940-ffffffff8121b969: pmdp_huge_clear_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
pmd_t pmdp_huge_clear_flush(struct vm_area_struct *vma, long unsigned int address, pmd_t *pmdp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pgtable-generic.c (ffffffff8123d720)
Location: mm/pgtable-generic.c:123
Inline: False
Direct callers:
  - mm/rmap.c:page_mkclean_one
  - mm/migrate.c:migrate_misplaced_transhuge_page
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:__split_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - fs/dax.c:dax_writeback_mapping_range
```
**Symbols:**

```
ffffffff8123d720-ffffffff8123d749: pmdp_huge_clear_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
pmd_t pmdp_huge_clear_flush(struct vm_area_struct *vma, long unsigned int address, pmd_t *pmdp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pgtable-generic.c (ffffffff81251c70)
Location: mm/pgtable-generic.c:124
Inline: False
Direct callers:
  - mm/rmap.c:page_mkclean_one
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - fs/dax.c:dax_entry_mkclean
```
**Symbols:**

```
ffffffff81251c70-ffffffff81251cc3: pmdp_huge_clear_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
pmd_t pmdp_huge_clear_flush(struct vm_area_struct *vma, long unsigned int address, pmd_t *pmdp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pgtable-generic.c (ffffffff81263f50)
Location: mm/pgtable-generic.c:124
Inline: False
Direct callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
```
**Symbols:**

```
ffffffff81263f50-ffffffff81263fa6: pmdp_huge_clear_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
pmd_t pmdp_huge_clear_flush(struct vm_area_struct *vma, long unsigned int address, pmd_t *pmdp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pgtable-generic.c (ffffffff812727c0)
Location: mm/pgtable-generic.c:124
Inline: False
Direct callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
```
**Symbols:**

```
ffffffff812727c0-ffffffff81272816: pmdp_huge_clear_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
pmd_t pmdp_huge_clear_flush(struct vm_area_struct *vma, long unsigned int address, pmd_t *pmdp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/pgtable-generic.c (ffffffff812a3580)
Location: mm/pgtable-generic.c:133
Inline: True
Direct callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_zero_page_pmd
```
**Symbols:**

```
ffffffff812a3580-ffffffff812a35d8: pmdp_huge_clear_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
pmd_t pmdp_huge_clear_flush(struct vm_area_struct *vma, long unsigned int address, pmd_t *pmdp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/pgtable-generic.c (ffffffff812aee60)
Location: mm/pgtable-generic.c:133
Inline: True
Direct callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_zero_page_pmd
```
**Symbols:**

```
ffffffff812aee60-ffffffff812aeeb8: pmdp_huge_clear_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
pmd_t pmdp_huge_clear_flush(struct vm_area_struct *vma, long unsigned int address, pmd_t *pmdp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/pgtable-generic.c (ffffffff812b4390)
Location: mm/pgtable-generic.c:133
Inline: True
Direct callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_zero_page_pmd
```
**Symbols:**

```
ffffffff812b4390-ffffffff812b43eb: pmdp_huge_clear_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
pmd_t pmdp_huge_clear_flush(struct vm_area_struct *vma, long unsigned int address, pmd_t *pmdp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/pgtable-generic.c (ffffffff812f5f70)
Location: mm/pgtable-generic.c:133
Inline: True
Direct callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_zero_page_pmd
```
**Symbols:**

```
ffffffff812f5f70-ffffffff812f5fcb: pmdp_huge_clear_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
pmd_t pmdp_huge_clear_flush(struct vm_area_struct *vma, long unsigned int address, pmd_t *pmdp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/pgtable-generic.c (ffffffff81359f20)
Location: mm/pgtable-generic.c:134
Inline: True
Direct callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_zero_page_pmd
```
**Symbols:**

```
ffffffff81359f20-ffffffff81359f88: pmdp_huge_clear_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
pmd_t pmdp_huge_clear_flush(struct vm_area_struct *vma, long unsigned int address, pmd_t *pmdp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/pgtable-generic.c (ffffffff813d4960)
Location: mm/pgtable-generic.c:134
Inline: True
Direct callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_zero_page_pmd
```
**Symbols:**

```
ffffffff813d4960-ffffffff813d49c5: pmdp_huge_clear_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
pmd_t pmdp_huge_clear_flush(struct vm_area_struct *vma, long unsigned int address, pmd_t *pmdp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/pgtable-generic.c (ffffffff81409330)
Location: mm/pgtable-generic.c:136
Inline: True
Direct callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_zero_page_pmd
```
**Symbols:**

```
ffffffff81409330-ffffffff8140939b: pmdp_huge_clear_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
pmd_t pmdp_huge_clear_flush(struct vm_area_struct *vma, long unsigned int address, pmd_t *pmdp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/pgtable-generic.c (ffffffff81435b20)
Location: mm/pgtable-generic.c:137
Inline: True
Direct callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_zero_page_pmd
  - mm/huge_memory.c:move_pages_huge_pmd
```
**Symbols:**

```
ffffffff81435b20-ffffffff81435b8b: pmdp_huge_clear_flush (STB_GLOBAL)
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
pmd_t pmdp_huge_clear_flush(struct vm_area_struct *vma, long unsigned int address, pmd_t *pmdp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pgtable-generic.c (ffff8000103081f0)
Location: mm/pgtable-generic.c:124
Inline: False
Direct callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
```
**Symbols:**

```
ffff8000103081f0-ffff800010308320: pmdp_huge_clear_flush (STB_GLOBAL)
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
pmd_t pmdp_huge_clear_flush(struct vm_area_struct *vma, long unsigned int address, pmd_t *pmdp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pgtable-generic.c (c0000000003d73b0)
Location: mm/pgtable-generic.c:124
Inline: False
Direct callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
```
**Symbols:**

```
c0000000003d73b0-c0000000003d7458: pmdp_huge_clear_flush (STB_GLOBAL)
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
pmd_t pmdp_huge_clear_flush(struct vm_area_struct *vma, long unsigned int address, pmd_t *pmdp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pgtable-generic.c (ffffffff8126ae10)
Location: mm/pgtable-generic.c:124
Inline: False
Direct callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
```
**Symbols:**

```
ffffffff8126ae10-ffffffff8126ae66: pmdp_huge_clear_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
pmd_t pmdp_huge_clear_flush(struct vm_area_struct *vma, long unsigned int address, pmd_t *pmdp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pgtable-generic.c (ffffffff8125ce40)
Location: mm/pgtable-generic.c:124
Inline: False
Direct callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
```
**Symbols:**

```
ffffffff8125ce40-ffffffff8125ce96: pmdp_huge_clear_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
pmd_t pmdp_huge_clear_flush(struct vm_area_struct *vma, long unsigned int address, pmd_t *pmdp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pgtable-generic.c (ffffffff81268bb0)
Location: mm/pgtable-generic.c:124
Inline: False
Direct callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
```
**Symbols:**

```
ffffffff81268bb0-ffffffff81268c06: pmdp_huge_clear_flush (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
pmd_t pmdp_huge_clear_flush(struct vm_area_struct *vma, long unsigned int address, pmd_t *pmdp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pgtable-generic.c (ffffffff81278540)
Location: mm/pgtable-generic.c:124
Inline: False
Direct callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
```
**Symbols:**

```
ffffffff81278540-ffffffff81278596: pmdp_huge_clear_flush (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
