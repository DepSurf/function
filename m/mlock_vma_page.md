# Function: <code>mlock_vma_page</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void mlock_vma_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mlock.c (ffffffff811c30f0)
Location: mm/mlock.c:80
Inline: False
Direct callers:
  - mm/gup.c:follow_page_pte
  - mm/rmap.c:try_to_unmap_one
  - mm/ksm.c:try_to_merge_with_ksm_page
  - mm/migrate.c:remove_migration_pte
  - mm/huge_memory.c:follow_trans_huge_pmd
```
**Symbols:**

```
ffffffff811c30f0-ffffffff811c3188: mlock_vma_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void mlock_vma_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mlock.c (ffffffff811dee20)
Location: mm/mlock.c:80
Inline: False
Direct callers:
  - mm/gup.c:follow_page_pte
  - mm/rmap.c:try_to_unmap_one
  - mm/ksm.c:try_to_merge_with_ksm_page
  - mm/migrate.c:remove_migration_pte
  - mm/huge_memory.c:follow_trans_huge_pmd
```
**Symbols:**

```
ffffffff811dee20-ffffffff811deed1: mlock_vma_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void mlock_vma_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mlock.c (ffffffff811eec40)
Location: mm/mlock.c:80
Inline: False
Direct callers:
  - mm/gup.c:follow_page_pte
  - mm/rmap.c:try_to_unmap_one
  - mm/ksm.c:try_to_merge_one_page
  - mm/migrate.c:remove_migration_pte
  - mm/huge_memory.c:follow_trans_huge_pmd
```
**Symbols:**

```
ffffffff811eec40-ffffffff811eecf1: mlock_vma_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void mlock_vma_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mlock.c (ffffffff811f9c00)
Location: mm/mlock.c:81
Inline: False
Direct callers:
  - mm/gup.c:follow_page_pte
  - mm/rmap.c:try_to_unmap_one
  - mm/ksm.c:try_to_merge_one_page
  - mm/migrate.c:remove_migration_pte
  - mm/huge_memory.c:follow_trans_huge_pmd
```
**Symbols:**

```
ffffffff811f9c00-ffffffff811f9cae: mlock_vma_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void mlock_vma_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mlock.c (ffffffff81212050)
Location: mm/mlock.c:82
Inline: False
Direct callers:
  - mm/gup.c:follow_page_pte
  - mm/rmap.c:try_to_unmap_one
  - mm/ksm.c:try_to_merge_one_page
  - mm/migrate.c:remove_migration_pte
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:follow_trans_huge_pmd
```
**Symbols:**

```
ffffffff81212050-ffffffff812120ff: mlock_vma_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void mlock_vma_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mlock.c (ffffffff81232d90)
Location: mm/mlock.c:88
Inline: False
Direct callers:
  - mm/gup.c:follow_page_pte
  - mm/rmap.c:try_to_unmap_one
  - mm/ksm.c:try_to_merge_one_page
  - mm/migrate.c:remove_migration_pte
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:follow_trans_huge_pmd
```
**Symbols:**

```
ffffffff81232d90-ffffffff81232e40: mlock_vma_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void mlock_vma_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mlock.c (ffffffff81246560)
Location: mm/mlock.c:88
Inline: False
Direct callers:
  - mm/gup.c:follow_page_pte
  - mm/rmap.c:try_to_unmap_one
  - mm/ksm.c:try_to_merge_one_page
  - mm/migrate.c:remove_migration_pte
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:follow_trans_huge_pmd
```
**Symbols:**

```
ffffffff81246560-ffffffff81246610: mlock_vma_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void mlock_vma_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mlock.c (ffffffff812587b0)
Location: mm/mlock.c:88
Inline: False
Direct callers:
  - mm/gup.c:follow_page_pte
  - mm/rmap.c:try_to_unmap_one
  - mm/ksm.c:try_to_merge_one_page
  - mm/migrate.c:remove_migration_pte
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:follow_trans_huge_pmd
```
**Symbols:**

```
ffffffff812587b0-ffffffff81258861: mlock_vma_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void mlock_vma_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mlock.c (ffffffff81266c80)
Location: mm/mlock.c:88
Inline: False
Direct callers:
  - mm/gup.c:follow_page_pte
  - mm/rmap.c:try_to_unmap_one
  - mm/ksm.c:try_to_merge_one_page
  - mm/migrate.c:remove_migration_pte
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:follow_trans_huge_pmd
```
**Symbols:**

```
ffffffff81266c80-ffffffff81266d31: mlock_vma_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void mlock_vma_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mlock.c (ffffffff81296ed0)
Location: mm/mlock.c:88
Inline: False
Direct callers:
  - mm/gup.c:follow_page_pte
  - mm/rmap.c:try_to_unmap_one
  - mm/ksm.c:try_to_merge_one_page
  - mm/migrate.c:remove_migration_pte
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:follow_trans_huge_pmd
```
**Symbols:**

```
ffffffff81296ed0-ffffffff81296f7e: mlock_vma_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void mlock_vma_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mlock.c (ffffffff812a1f10)
Location: mm/mlock.c:90
Inline: False
Direct callers:
  - mm/gup.c:follow_page_pte
  - mm/rmap.c:try_to_unmap_one
  - mm/ksm.c:try_to_merge_one_page
  - mm/migrate.c:remove_migration_pte
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:follow_trans_huge_pmd
```
**Symbols:**

```
ffffffff812a1f10-ffffffff812a1fbf: mlock_vma_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void mlock_vma_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mlock.c (ffffffff812a77a0)
Location: mm/mlock.c:90
Inline: False
Direct callers:
  - mm/gup.c:follow_page_pte
  - mm/rmap.c:try_to_unmap_one
  - mm/ksm.c:try_to_merge_one_page
  - mm/migrate.c:remove_migration_pte
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:follow_trans_huge_pmd
```
**Symbols:**

```
ffffffff812a77a0-ffffffff812a784f: mlock_vma_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void mlock_vma_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mlock.c (ffffffff812e8d40)
Location: mm/mlock.c:91
Inline: False
Direct callers:
  - mm/gup.c:follow_page_pte
  - mm/memory.c:restore_exclusive_pte
  - mm/rmap.c:page_mlock_one
  - mm/rmap.c:try_to_unmap_one
  - mm/ksm.c:try_to_merge_one_page
  - mm/migrate.c:remove_migration_pte
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:follow_trans_huge_pmd
```
**Symbols:**

```
ffffffff812e8d40-ffffffff812e8e22: mlock_vma_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff8135d18f)
Location: mm/internal.h:527
Inline: True
Inline callers:
  - mm/rmap.c:page_add_file_rmap
  - mm/rmap.c:page_add_anon_rmap
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/rmap.c (ffffffff813d7d16)
Location: mm/internal.h:525
Inline: True
Inline callers:
  - mm/rmap.c:page_add_file_rmap
  - mm/rmap.c:page_add_anon_rmap
```
</details>
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
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void mlock_vma_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mlock.c (ffff8000102fddf0)
Location: mm/mlock.c:88
Inline: False
Direct callers:
  - mm/gup.c:follow_page_pte
  - mm/rmap.c:try_to_unmap_one
  - mm/ksm.c:try_to_merge_one_page
  - mm/migrate.c:remove_migration_pte
  - mm/huge_memory.c:follow_trans_huge_pmd
```
**Symbols:**

```
ffff8000102fddf0-ffff8000102fdf20: mlock_vma_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void mlock_vma_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mlock.c (c051d098)
Location: mm/mlock.c:88
Inline: False
Direct callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/ksm.c:try_to_merge_one_page
  - mm/migrate.c:remove_migration_pte
```
**Symbols:**

```
c051d098-c051d150: mlock_vma_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void mlock_vma_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mlock.c (c0000000003c9430)
Location: mm/mlock.c:88
Inline: False
Direct callers:
  - mm/gup.c:follow_page_pte
  - mm/rmap.c:try_to_unmap_one
  - mm/ksm.c:try_to_merge_one_page
  - mm/migrate.c:remove_migration_pte
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:follow_trans_huge_pmd
```
**Symbols:**

```
c0000000003c9430-c0000000003c9588: mlock_vma_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void mlock_vma_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mlock.c (ffffffe00020c512)
Location: mm/mlock.c:88
Inline: False
Direct callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/ksm.c:try_to_merge_one_page
  - mm/migrate.c:remove_migration_pte
```
**Symbols:**

```
ffffffe00020c512-ffffffe00020c5d6: mlock_vma_page (STB_GLOBAL)
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
void mlock_vma_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mlock.c (ffffffff8125f2d0)
Location: mm/mlock.c:88
Inline: False
Direct callers:
  - mm/gup.c:follow_page_pte
  - mm/rmap.c:try_to_unmap_one
  - mm/ksm.c:try_to_merge_one_page
  - mm/migrate.c:remove_migration_pte
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:follow_trans_huge_pmd
```
**Symbols:**

```
ffffffff8125f2d0-ffffffff8125f381: mlock_vma_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void mlock_vma_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mlock.c (ffffffff812516f0)
Location: mm/mlock.c:88
Inline: False
Direct callers:
  - mm/gup.c:follow_page_pte
  - mm/rmap.c:try_to_unmap_one
  - mm/ksm.c:try_to_merge_one_page
  - mm/migrate.c:remove_migration_pte
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:follow_trans_huge_pmd
```
**Symbols:**

```
ffffffff812516f0-ffffffff812517a1: mlock_vma_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void mlock_vma_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mlock.c (ffffffff8125d070)
Location: mm/mlock.c:88
Inline: False
Direct callers:
  - mm/gup.c:follow_page_pte
  - mm/rmap.c:try_to_unmap_one
  - mm/ksm.c:try_to_merge_one_page
  - mm/migrate.c:remove_migration_pte
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:follow_trans_huge_pmd
```
**Symbols:**

```
ffffffff8125d070-ffffffff8125d121: mlock_vma_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void mlock_vma_page(struct page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mlock.c (ffffffff8126ca70)
Location: mm/mlock.c:88
Inline: False
Direct callers:
  - mm/gup.c:follow_page_pte
  - mm/rmap.c:try_to_unmap_one
  - mm/ksm.c:try_to_merge_one_page
  - mm/migrate.c:remove_migration_pte
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:follow_trans_huge_pmd
```
**Symbols:**

```
ffffffff8126ca70-ffffffff8126cb21: mlock_vma_page (STB_GLOBAL)
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
