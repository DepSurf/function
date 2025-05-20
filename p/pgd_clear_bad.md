# Function: <code>pgd_clear_bad</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void pgd_clear_bad(pgd_t *pgd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pgtable-generic.c (ffffffff811d0350)
Location: mm/pgtable-generic.c:19
Inline: False
Direct callers:
  - mm/memory.c:free_pgd_range
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_page_range
  - mm/mprotect.c:change_protection_range
  - mm/mremap.c:move_page_tables
  - mm/swapfile.c:unuse_mm
```
**Symbols:**

```
ffffffff811d0350-ffffffff811d039e: pgd_clear_bad (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void pgd_clear_bad(pgd_t *pgd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pgtable-generic.c (ffffffff811ed500)
Location: mm/pgtable-generic.c:19
Inline: False
Direct callers:
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:free_pgd_range
  - mm/mprotect.c:change_protection_range
  - mm/mremap.c:move_page_tables
  - mm/swapfile.c:unuse_mm
```
**Symbols:**

```
ffffffff811ed500-ffffffff811ed54e: pgd_clear_bad (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void pgd_clear_bad(pgd_t *pgd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pgtable-generic.c (ffffffff811f78f0)
Location: mm/pgtable-generic.c:19
Inline: False
Direct callers:
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:free_pgd_range
  - mm/mprotect.c:change_protection_range
  - mm/mremap.c:move_page_tables
  - mm/swapfile.c:unuse_mm
```
**Symbols:**

```
ffffffff811f78f0-ffffffff811f793e: pgd_clear_bad (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void pgd_clear_bad(pgd_t *pgd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pgtable-generic.c (ffffffff81202a40)
Location: mm/pgtable-generic.c:19
Inline: False
```
**Symbols:**

```
ffffffff81202a40-ffffffff81202a73: pgd_clear_bad (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void pgd_clear_bad(pgd_t *pgd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pgtable-generic.c (ffffffff8121b7b0)
Location: mm/pgtable-generic.c:20
Inline: False
```
**Symbols:**

```
ffffffff8121b7b0-ffffffff8121b7e3: pgd_clear_bad (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void pgd_clear_bad(pgd_t *pgd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pgtable-generic.c (ffffffff8123d590)
Location: mm/pgtable-generic.c:20
Inline: False
```
**Symbols:**

```
ffffffff8123d590-ffffffff8123d5c3: pgd_clear_bad (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void pgd_clear_bad(pgd_t *pgd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pgtable-generic.c (ffffffff81251ae0)
Location: mm/pgtable-generic.c:21
Inline: False
```
**Symbols:**

```
ffffffff81251ae0-ffffffff81251b13: pgd_clear_bad (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void pgd_clear_bad(pgd_t *pgd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pgtable-generic.c (ffffffff81263db0)
Location: mm/pgtable-generic.c:21
Inline: False
```
**Symbols:**

```
ffffffff81263db0-ffffffff81263de3: pgd_clear_bad (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void pgd_clear_bad(pgd_t *pgd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pgtable-generic.c (ffffffff81272620)
Location: mm/pgtable-generic.c:21
Inline: False
```
**Symbols:**

```
ffffffff81272620-ffffffff81272653: pgd_clear_bad (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void pgd_clear_bad(pgd_t *pgd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pgtable-generic.c (ffffffff812a3370)
Location: mm/pgtable-generic.c:21
Inline: False
Direct callers:
  - mm/memory.c:__apply_to_page_range
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:free_pgd_range
  - mm/mprotect.c:change_protection_range
  - mm/mremap.c:get_old_pmd
  - mm/pagewalk.c:walk_pgd_range
  - mm/vmalloc.c:unmap_kernel_range_noflush
  - mm/swapfile.c:unuse_vma
```
**Symbols:**

```
ffffffff812a3370-ffffffff812a33e8: pgd_clear_bad (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void pgd_clear_bad(pgd_t *pgd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pgtable-generic.c (ffffffff812aec90)
Location: mm/pgtable-generic.c:21
Inline: False
Direct callers:
  - mm/memory.c:__apply_to_page_range
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:free_pgd_range
  - mm/mprotect.c:change_protection_range
  - mm/mremap.c:get_old_pud
  - mm/pagewalk.c:walk_pgd_range
  - mm/vmalloc.c:unmap_kernel_range_noflush
  - mm/swapfile.c:unuse_vma
```
**Symbols:**

```
ffffffff812aec90-ffffffff812aecf4: pgd_clear_bad (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void pgd_clear_bad(pgd_t *pgd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pgtable-generic.c (ffffffff812b41c0)
Location: mm/pgtable-generic.c:21
Inline: False
Direct callers:
  - mm/memory.c:__apply_to_page_range
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:free_pgd_range
  - mm/mprotect.c:change_protection_range
  - mm/mremap.c:get_old_pud
  - mm/pagewalk.c:walk_pgd_range
  - mm/vmalloc.c:vunmap_range_noflush
  - mm/swapfile.c:unuse_vma
```
**Symbols:**

```
ffffffff812b41c0-ffffffff812b422b: pgd_clear_bad (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void pgd_clear_bad(pgd_t *pgd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pgtable-generic.c (ffffffff812f5da0)
Location: mm/pgtable-generic.c:21
Inline: False
Direct callers:
  - mm/memory.c:__apply_to_page_range
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:free_pgd_range
  - mm/mprotect.c:change_protection_range
  - mm/mremap.c:get_old_pud
  - mm/pagewalk.c:walk_pgd_range
  - mm/vmalloc.c:vunmap_range_noflush
  - mm/swapfile.c:unuse_vma
```
**Symbols:**

```
ffffffff812f5da0-ffffffff812f5e0b: pgd_clear_bad (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void pgd_clear_bad(pgd_t *pgd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pgtable-generic.c (ffffffff81359cd0)
Location: mm/pgtable-generic.c:22
Inline: False
Direct callers:
  - mm/memory.c:__apply_to_page_range
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:free_pgd_range
  - mm/mprotect.c:change_protection_range
  - mm/mremap.c:get_old_pud
  - mm/pagewalk.c:walk_pgd_range
  - mm/vmalloc.c:vunmap_range_noflush
  - mm/swapfile.c:unuse_vma
```
**Symbols:**

```
ffffffff81359cd0-ffffffff81359d64: pgd_clear_bad (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void pgd_clear_bad(pgd_t *pgd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pgtable-generic.c (ffffffff813d46c0)
Location: mm/pgtable-generic.c:22
Inline: False
Direct callers:
  - mm/memory.c:__apply_to_page_range
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:free_pgd_range
  - mm/mprotect.c:change_protection_range
  - mm/mremap.c:get_old_pud
  - mm/pagewalk.c:walk_pgd_range
  - mm/vmalloc.c:__vunmap_range_noflush
  - mm/swapfile.c:unuse_vma
```
**Symbols:**

```
ffffffff813d46c0-ffffffff813d4754: pgd_clear_bad (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void pgd_clear_bad(pgd_t *pgd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pgtable-generic.c (ffffffff81409090)
Location: mm/pgtable-generic.c:24
Inline: False
Direct callers:
  - mm/memory.c:__apply_to_page_range
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:free_pgd_range
  - mm/mprotect.c:change_protection_range
  - mm/mremap.c:get_old_pud
  - mm/pagewalk.c:walk_pgd_range
  - mm/vmalloc.c:__vunmap_range_noflush
  - mm/swapfile.c:unuse_vma
```
**Symbols:**

```
ffffffff81409090-ffffffff81409124: pgd_clear_bad (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void pgd_clear_bad(pgd_t *pgd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pgtable-generic.c (ffffffff81435880)
Location: mm/pgtable-generic.c:25
Inline: False
Direct callers:
  - mm/memory.c:__apply_to_page_range
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:free_pgd_range
  - mm/mprotect.c:change_protection_range
  - mm/mremap.c:get_old_pud
  - mm/pagewalk.c:walk_pgd_range
  - mm/vmalloc.c:__vunmap_range_noflush
  - mm/swapfile.c:unuse_vma
```
**Symbols:**

```
ffffffff81435880-ffffffff81435914: pgd_clear_bad (STB_GLOBAL)
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
void pgd_clear_bad(pgd_t *pgd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pgtable-generic.c (ffff800010307e60)
Location: mm/pgtable-generic.c:21
Inline: False
Direct callers:
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:free_pgd_range
  - mm/mprotect.c:change_protection_range
  - mm/mremap.c:move_page_tables
  - mm/swapfile.c:try_to_unuse
```
**Symbols:**

```
ffff800010307e60-ffff800010307ed0: pgd_clear_bad (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void pgd_clear_bad(pgd_t *pgd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pgtable-generic.c (c05253c4)
Location: mm/pgtable-generic.c:21
Inline: False
```
**Symbols:**

```
c05253c4-c05253f0: pgd_clear_bad (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void pgd_clear_bad(pgd_t *pgd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pgtable-generic.c (c0000000003d7458)
Location: mm/pgtable-generic.c:21
Inline: False
Direct callers:
  - arch/powerpc/mm/hugetlbpage.c:hugetlb_free_pgd_range
  - mm/memory.c:unmap_page_range
  - mm/memory.c:copy_page_range
  - mm/memory.c:free_pgd_range
  - mm/mprotect.c:change_protection_range
  - mm/mremap.c:move_page_tables
  - mm/vmalloc.c:vunmap_page_range
  - mm/swapfile.c:try_to_unuse
```
**Symbols:**

```
c0000000003d7458-c0000000003d74b8: pgd_clear_bad (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void pgd_clear_bad(pgd_t *pgd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pgtable-generic.c (ffffffe000212d78)
Location: mm/pgtable-generic.c:21
Inline: False
```
**Symbols:**

```
ffffffe000212d78-ffffffe000212db4: pgd_clear_bad (STB_GLOBAL)
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
void pgd_clear_bad(pgd_t *pgd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pgtable-generic.c (ffffffff8126ac70)
Location: mm/pgtable-generic.c:21
Inline: False
```
**Symbols:**

```
ffffffff8126ac70-ffffffff8126aca3: pgd_clear_bad (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void pgd_clear_bad(pgd_t *pgd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pgtable-generic.c (ffffffff8125d166)
Location: mm/pgtable-generic.c:21
Inline: False
```
**Symbols:**

```
ffffffff8125d166-ffffffff8125d18f: pgd_clear_bad (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void pgd_clear_bad(pgd_t *pgd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pgtable-generic.c (ffffffff81268a10)
Location: mm/pgtable-generic.c:21
Inline: False
```
**Symbols:**

```
ffffffff81268a10-ffffffff81268a43: pgd_clear_bad (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void pgd_clear_bad(pgd_t *pgd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pgtable-generic.c (ffffffff812783a0)
Location: mm/pgtable-generic.c:21
Inline: False
```
**Symbols:**

```
ffffffff812783a0-ffffffff812783d3: pgd_clear_bad (STB_GLOBAL)
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
