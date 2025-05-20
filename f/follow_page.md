# Function: <code>follow_page</code>

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
In mm/ksm.c (ffffffff811e41f1)
Location: include/linux/mm.h:2113
Inline: True
Inline callers:
  - mm/ksm.c:break_ksm
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
```
```
In mm/migrate.c (ffffffff811f09ae)
Location: include/linux/mm.h:2113
Inline: True
Inline callers:
  - mm/migrate.c:do_pages_stat
  - mm/migrate.c:SyS_move_pages
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
In mm/ksm.c (ffffffff81205390)
Location: include/linux/mm.h:2237
Inline: True
Inline callers:
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:break_ksm
```
```
In mm/migrate.c (ffffffff812128d3)
Location: include/linux/mm.h:2237
Inline: True
Inline callers:
  - mm/migrate.c:SyS_move_pages
  - mm/migrate.c:do_pages_stat
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mlock.c (ffffffff811eeeef)
Location: include/linux/mm.h:2223
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
```
```
In mm/ksm.c (ffffffff81216a65)
Location: include/linux/mm.h:2223
Inline: True
Inline callers:
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:break_ksm
```
```
In mm/migrate.c (ffffffff81224b99)
Location: include/linux/mm.h:2223
Inline: True
Inline callers:
  - mm/migrate.c:SYSC_move_pages
  - mm/migrate.c:do_pages_stat
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mlock.c (ffffffff811f9eb2)
Location: include/linux/mm.h:2328
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
```
```
In mm/ksm.c (ffffffff8122246e)
Location: include/linux/mm.h:2328
Inline: True
Inline callers:
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:break_ksm
```
```
In mm/migrate.c (ffffffff81230271)
Location: include/linux/mm.h:2328
Inline: True
Inline callers:
  - mm/migrate.c:SYSC_move_pages
  - mm/migrate.c:do_pages_stat
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mlock.c (ffffffff81212306)
Location: include/linux/mm.h:2437
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
```
```
In mm/ksm.c (ffffffff8123d7ab)
Location: include/linux/mm.h:2437
Inline: True
Inline callers:
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:break_ksm
```
```
In mm/migrate.c (ffffffff8124df01)
Location: include/linux/mm.h:2437
Inline: True
Inline callers:
  - mm/migrate.c:SYSC_move_pages
  - mm/migrate.c:do_pages_stat
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mlock.c (ffffffff81233049)
Location: include/linux/mm.h:2571
Inline: True
Inline callers:
  - mm/mlock.c:munlock_vma_pages_range
```
```
In mm/ksm.c (ffffffff81260dcc)
Location: include/linux/mm.h:2571
Inline: True
Inline callers:
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:break_ksm
```
```
In mm/migrate.c (ffffffff81271c07)
Location: include/linux/mm.h:2571
Inline: True
Inline callers:
  - mm/migrate.c:kernel_move_pages
  - mm/migrate.c:do_pages_stat
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct page *follow_page(struct vm_area_struct *vma, long unsigned int address, unsigned int foll_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff8123c130)
Location: mm/gup.c:442
Inline: False
Direct callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:break_ksm
  - mm/migrate.c:kernel_move_pages
  - mm/migrate.c:do_pages_stat
```
**Symbols:**

```
ffffffff8123c130-ffffffff8123c1af: follow_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct page *follow_page(struct vm_area_struct *vma, long unsigned int address, unsigned int foll_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff8124dc90)
Location: mm/gup.c:559
Inline: False
Direct callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:break_ksm
  - mm/migrate.c:do_pages_stat
  - mm/migrate.c:do_pages_move
```
**Symbols:**

```
ffffffff8124dc90-ffffffff8124dd0f: follow_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct page *follow_page(struct vm_area_struct *vma, long unsigned int address, unsigned int foll_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff8125c1c0)
Location: mm/gup.c:558
Inline: False
Direct callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:break_ksm
  - mm/migrate.c:do_pages_stat
  - mm/migrate.c:do_pages_move
```
**Symbols:**

```
ffffffff8125c1c0-ffffffff8125c23f: follow_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct page *follow_page(struct vm_area_struct *vma, long unsigned int address, unsigned int foll_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff8128b600)
Location: mm/gup.c:792
Inline: False
Direct callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:unstable_tree_search_insert
  - mm/ksm.c:break_ksm
  - mm/migrate.c:do_pages_stat
  - mm/migrate.c:add_page_for_migration
```
**Symbols:**

```
ffffffff8128b600-ffffffff8128b67f: follow_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct page *follow_page(struct vm_area_struct *vma, long unsigned int address, unsigned int foll_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff81295470)
Location: mm/gup.c:756
Inline: False
Direct callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:unstable_tree_search_insert
  - mm/ksm.c:break_ksm
  - mm/migrate.c:do_pages_stat_array
  - mm/migrate.c:add_page_for_migration
```
**Symbols:**

```
ffffffff81295470-ffffffff812954fe: follow_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct page *follow_page(struct vm_area_struct *vma, long unsigned int address, unsigned int foll_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff8129add0)
Location: mm/gup.c:841
Inline: False
Direct callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:unstable_tree_search_insert
  - mm/ksm.c:break_ksm
  - mm/migrate.c:do_pages_stat
  - mm/migrate.c:add_page_for_migration
  - mm/huge_memory.c:split_huge_pages_pid
```
**Symbols:**

```
ffffffff8129add0-ffffffff8129ae5e: follow_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct page *follow_page(struct vm_area_struct *vma, long unsigned int address, unsigned int foll_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff812db7a0)
Location: mm/gup.c:864
Inline: False
Direct callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:unstable_tree_search_insert
  - mm/ksm.c:break_ksm
  - mm/migrate.c:do_pages_stat
  - mm/migrate.c:add_page_for_migration
  - mm/huge_memory.c:split_huge_pages_pid
```
**Symbols:**

```
ffffffff812db7a0-ffffffff812db85a: follow_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct page *follow_page(struct vm_area_struct *vma, long unsigned int address, unsigned int foll_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff8133b520)
Location: mm/gup.c:885
Inline: False
Direct callers:
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:break_ksm
  - mm/migrate.c:do_pages_stat
  - mm/migrate.c:add_page_for_migration
  - mm/huge_memory.c:split_huge_pages_pid
```
**Symbols:**

```
ffffffff8133b520-ffffffff8133b5f3: follow_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct page *follow_page(struct vm_area_struct *vma, long unsigned int address, unsigned int foll_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff813b30b0)
Location: mm/gup.c:812
Inline: False
Direct callers:
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/migrate.c:do_pages_stat
  - mm/migrate.c:add_page_for_migration
  - mm/huge_memory.c:split_huge_pages_pid
```
**Symbols:**

```
ffffffff813b30b0-ffffffff813b3183: follow_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct page *follow_page(struct vm_area_struct *vma, long unsigned int address, unsigned int foll_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff813e7e60)
Location: mm/gup.c:842
Inline: False
Direct callers:
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/migrate.c:do_pages_stat
  - mm/migrate.c:add_page_for_migration
  - mm/huge_memory.c:split_huge_pages_pid
```
**Symbols:**

```
ffffffff813e7e60-ffffffff813e7f3a: follow_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct page *follow_page(struct vm_area_struct *vma, long unsigned int address, unsigned int foll_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff81412ad0)
Location: mm/gup.c:837
Inline: False
Direct callers:
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/migrate.c:do_pages_stat
  - mm/migrate.c:add_page_for_migration
  - mm/huge_memory.c:split_huge_pages_pid
```
**Symbols:**

```
ffffffff81412ad0-ffffffff81412baa: follow_page (STB_GLOBAL)
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
struct page *follow_page(struct vm_area_struct *vma, long unsigned int address, unsigned int foll_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffff8000102f35e8)
Location: mm/gup.c:558
Inline: False
Direct callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:break_ksm
  - mm/migrate.c:do_pages_stat
  - mm/migrate.c:do_pages_move
```
**Symbols:**

```
ffff8000102f35e8-ffff8000102f36cc: follow_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct page *follow_page(struct vm_area_struct *vma, long unsigned int address, unsigned int foll_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (c05158d8)
Location: mm/gup.c:558
Inline: False
Direct callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/ksm.c:ksm_do_scan
  - mm/ksm.c:ksm_do_scan
  - mm/ksm.c:break_ksm
```
**Symbols:**

```
c05158d8-c0515948: follow_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct page *follow_page(struct vm_area_struct *vma, long unsigned int address, unsigned int foll_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (c0000000003ba180)
Location: mm/gup.c:558
Inline: False
Direct callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/ksm.c:scan_get_next_rmap_item
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:break_ksm
  - mm/migrate.c:do_pages_stat
  - mm/migrate.c:do_pages_move
```
**Symbols:**

```
c0000000003ba180-c0000000003ba280: follow_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct page *follow_page(struct vm_area_struct *vma, long unsigned int address, unsigned int foll_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffe000205776)
Location: mm/gup.c:558
Inline: False
Direct callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/ksm.c:ksm_do_scan
  - mm/ksm.c:ksm_do_scan
  - mm/ksm.c:break_ksm
```
**Symbols:**

```
ffffffe000205776-ffffffe000205808: follow_page (STB_GLOBAL)
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
struct page *follow_page(struct vm_area_struct *vma, long unsigned int address, unsigned int foll_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff81254810)
Location: mm/gup.c:558
Inline: False
Direct callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:break_ksm
  - mm/migrate.c:do_pages_stat
  - mm/migrate.c:do_pages_move
```
**Symbols:**

```
ffffffff81254810-ffffffff8125488f: follow_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct page *follow_page(struct vm_area_struct *vma, long unsigned int address, unsigned int foll_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff81247460)
Location: mm/gup.c:558
Inline: False
Direct callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:break_ksm
  - mm/migrate.c:do_pages_stat
  - mm/migrate.c:do_pages_move
```
**Symbols:**

```
ffffffff81247460-ffffffff812474df: follow_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct page *follow_page(struct vm_area_struct *vma, long unsigned int address, unsigned int foll_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff812525b0)
Location: mm/gup.c:558
Inline: False
Direct callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:break_ksm
  - mm/migrate.c:do_pages_stat
  - mm/migrate.c:do_pages_move
```
**Symbols:**

```
ffffffff812525b0-ffffffff8125262f: follow_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct page *follow_page(struct vm_area_struct *vma, long unsigned int address, unsigned int foll_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff81261f60)
Location: mm/gup.c:558
Inline: False
Direct callers:
  - mm/mlock.c:munlock_vma_pages_range
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:cmp_and_merge_page
  - mm/ksm.c:break_ksm
  - mm/migrate.c:do_pages_stat
  - mm/migrate.c:do_pages_move
```
**Symbols:**

```
ffffffff81261f60-ffffffff81261ff6: follow_page (STB_GLOBAL)
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
