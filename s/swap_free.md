# Function: <code>swap_free</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void swap_free(swp_entry_t entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff811d3ff0)
Location: mm/swapfile.c:838
Inline: False
Direct callers:
  - kernel/power/swap.c:alloc_swapdev_block
  - kernel/power/swap.c:free_all_swap_pages
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_unuse
  - mm/memory.c:handle_mm_fault
  - mm/swapfile.c:unuse_mm
```
**Symbols:**

```
ffffffff811d3ff0-ffffffff811d402f: swap_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void swap_free(swp_entry_t entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff811f1e20)
Location: mm/swapfile.c:833
Inline: False
Direct callers:
  - kernel/power/swap.c:free_all_swap_pages
  - kernel/power/swap.c:alloc_swapdev_block
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_unuse
  - mm/memory.c:do_swap_page
  - mm/swapfile.c:unuse_mm
```
**Symbols:**

```
ffffffff811f1e20-ffffffff811f1e5f: swap_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void swap_free(swp_entry_t entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff81202810)
Location: mm/swapfile.c:839
Inline: False
Direct callers:
  - kernel/power/swap.c:free_all_swap_pages
  - kernel/power/swap.c:alloc_swapdev_block
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_unuse
  - mm/memory.c:do_swap_page
  - mm/swapfile.c:unuse_mm
```
**Symbols:**

```
ffffffff81202810-ffffffff8120284f: swap_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void swap_free(swp_entry_t entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff8120d8f0)
Location: mm/swapfile.c:1138
Inline: False
Direct callers:
  - kernel/power/swap.c:free_all_swap_pages
  - kernel/power/swap.c:alloc_swapdev_block
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_unuse
  - mm/memory.c:do_swap_page
  - mm/swapfile.c:unuse_mm
```
**Symbols:**

```
ffffffff8120d8f0-ffffffff8120d929: swap_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void swap_free(swp_entry_t entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff81228aa0)
Location: mm/swapfile.c:1173
Inline: False
Direct callers:
  - kernel/power/swap.c:free_all_swap_pages
  - kernel/power/swap.c:alloc_swapdev_block
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_unuse
  - mm/memory.c:do_swap_page
  - mm/swapfile.c:unuse_mm
```
**Symbols:**

```
ffffffff81228aa0-ffffffff81228ad9: swap_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void swap_free(swp_entry_t entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff81249e10)
Location: mm/swapfile.c:1173
Inline: False
Direct callers:
  - kernel/power/swap.c:free_all_swap_pages
  - kernel/power/swap.c:alloc_swapdev_block
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_unuse
  - mm/memory.c:do_swap_page
  - mm/swapfile.c:unuse_vma
```
**Symbols:**

```
ffffffff81249e10-ffffffff81249e49: swap_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void swap_free(swp_entry_t entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff8125e460)
Location: mm/swapfile.c:1213
Inline: False
Direct callers:
  - kernel/power/swap.c:free_all_swap_pages
  - kernel/power/swap.c:alloc_swapdev_block
  - mm/shmem.c:shmem_getpage_gfp
  - mm/shmem.c:shmem_unuse
  - mm/memory.c:do_swap_page
  - mm/swapfile.c:unuse_vma
```
**Symbols:**

```
ffffffff8125e460-ffffffff8125e485: swap_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void swap_free(swp_entry_t entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff812795d0)
Location: mm/swapfile.c:1313
Inline: False
Direct callers:
  - kernel/power/swap.c:free_all_swap_pages
  - kernel/power/swap.c:alloc_swapdev_block
  - mm/shmem.c:shmem_swapin_page
  - mm/memory.c:do_swap_page
```
**Symbols:**

```
ffffffff812795d0-ffffffff812795f7: swap_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void swap_free(swp_entry_t entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff812890b0)
Location: mm/swapfile.c:1313
Inline: False
Direct callers:
  - kernel/power/swap.c:free_all_swap_pages
  - kernel/power/swap.c:alloc_swapdev_block
  - mm/shmem.c:shmem_swapin_page
  - mm/memory.c:do_swap_page
```
**Symbols:**

```
ffffffff812890b0-ffffffff812890d7: swap_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void swap_free(swp_entry_t entry);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff812bbd1c)
Location: mm/swapfile.c:1350
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte
Direct callers:
  - kernel/power/swap.c:free_all_swap_pages
  - kernel/power/swap.c:alloc_swapdev_block
  - mm/shmem.c:shmem_swapin_page
  - mm/memory.c:do_swap_page
```
**Symbols:**

```
ffffffff812bc010-ffffffff812bc039: swap_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void swap_free(swp_entry_t entry);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff812c77c5)
Location: mm/swapfile.c:1368
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte
Direct callers:
  - kernel/power/swap.c:free_all_swap_pages
  - kernel/power/swap.c:alloc_swapdev_block
  - mm/shmem.c:shmem_swapin_page
  - mm/memory.c:do_swap_page
```
**Symbols:**

```
ffffffff812c7b40-ffffffff812c7b69: swap_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void swap_free(swp_entry_t entry);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff812ce13d)
Location: mm/swapfile.c:1367
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte
Direct callers:
  - kernel/power/swap.c:free_all_swap_pages
  - kernel/power/swap.c:alloc_swapdev_block
  - mm/shmem.c:shmem_swapin_page
  - mm/memory.c:do_swap_page
```
**Symbols:**

```
ffffffff812ce490-ffffffff812ce4b9: swap_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void swap_free(swp_entry_t entry);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff813135bd)
Location: mm/swapfile.c:1336
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte
Direct callers:
  - kernel/power/swap.c:free_all_swap_pages
  - kernel/power/swap.c:alloc_swapdev_block
  - mm/shmem.c:shmem_swapin_page
  - mm/memory.c:do_swap_page
```
**Symbols:**

```
ffffffff81313a20-ffffffff81313a49: swap_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void swap_free(swp_entry_t entry);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff8137e8f5)
Location: mm/swapfile.c:1319
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte
  - mm/swapfile.c:unuse_pte
Direct callers:
  - kernel/power/swap.c:free_all_swap_pages
  - kernel/power/swap.c:alloc_swapdev_block
  - mm/shmem.c:shmem_swapin_folio
  - mm/shmem.c:shmem_swapin_folio
  - mm/memory.c:do_swap_page
  - mm/rmap.c:try_to_unmap_one
```
**Symbols:**

```
ffffffff8137f080-ffffffff8137f0b2: swap_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void swap_free(swp_entry_t entry);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff813fd453)
Location: mm/swapfile.c:1323
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte
Direct callers:
  - kernel/power/swap.c:free_all_swap_pages
  - kernel/power/swap.c:alloc_swapdev_block
  - mm/shmem.c:shmem_swapin_folio
  - mm/shmem.c:shmem_swapin_folio
  - mm/memory.c:do_swap_page
  - mm/rmap.c:try_to_unmap_one
```
**Symbols:**

```
ffffffff813fdbe0-ffffffff813fdc12: swap_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void swap_free(swp_entry_t entry);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff81430735)
Location: mm/swapfile.c:1329
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte
Direct callers:
  - kernel/power/swap.c:free_all_swap_pages
  - kernel/power/swap.c:alloc_swapdev_block
  - mm/shmem.c:shmem_swapin_folio
  - mm/shmem.c:shmem_swapin_folio
  - mm/memory.c:do_swap_page
  - mm/rmap.c:try_to_unmap_one
```
**Symbols:**

```
ffffffff81430c80-ffffffff81430cb2: swap_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void swap_free(swp_entry_t entry);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff81468f53)
Location: mm/swapfile.c:1329
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte
Direct callers:
  - kernel/power/swap.c:free_all_swap_pages
  - kernel/power/swap.c:alloc_swapdev_block
  - mm/shmem.c:shmem_swapin_folio
  - mm/shmem.c:shmem_swapin_folio
  - mm/memory.c:do_swap_page
  - mm/rmap.c:try_to_unmap_one
```
**Symbols:**

```
ffffffff8146a0a0-ffffffff8146a0d2: swap_free (STB_GLOBAL)
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
void swap_free(swp_entry_t entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffff800010324200)
Location: mm/swapfile.c:1313
Inline: False
Direct callers:
  - mm/shmem.c:shmem_swapin_page
  - mm/memory.c:do_swap_page
  - mm/swapfile.c:unuse_pte_range
```
**Symbols:**

```
ffff800010324200-ffff800010324238: swap_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void swap_free(swp_entry_t entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (c053bf80)
Location: mm/swapfile.c:1313
Inline: False
Direct callers:
  - kernel/power/swap.c:free_all_swap_pages
  - kernel/power/swap.c:alloc_swapdev_block
  - mm/shmem.c:shmem_swapin_page
  - mm/memory.c:do_swap_page
  - mm/swapfile.c:unuse_mm
```
**Symbols:**

```
c053bf80-c053bfb0: swap_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void swap_free(swp_entry_t entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (c0000000003fa040)
Location: mm/swapfile.c:1313
Inline: False
Direct callers:
  - mm/shmem.c:shmem_swapin_page
  - mm/memory.c:do_swap_page
  - mm/swapfile.c:unuse_pte_range
```
**Symbols:**

```
c0000000003fa040-c0000000003fa0a4: swap_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void swap_free(swp_entry_t entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffe00022497a)
Location: mm/swapfile.c:1313
Inline: False
Direct callers:
  - mm/shmem.c:shmem_swapin_page
  - mm/memory.c:do_swap_page
  - mm/swapfile.c:unuse_pte_range
```
**Symbols:**

```
ffffffe00022497a-ffffffe0002249b0: swap_free (STB_GLOBAL)
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
void swap_free(swp_entry_t entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff81281690)
Location: mm/swapfile.c:1313
Inline: False
Direct callers:
  - kernel/power/swap.c:free_all_swap_pages
  - kernel/power/swap.c:alloc_swapdev_block
  - mm/shmem.c:shmem_swapin_page
  - mm/memory.c:do_swap_page
```
**Symbols:**

```
ffffffff81281690-ffffffff812816b7: swap_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void swap_free(swp_entry_t entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff81273500)
Location: mm/swapfile.c:1313
Inline: False
Direct callers:
  - kernel/power/swap.c:free_all_swap_pages
  - kernel/power/swap.c:alloc_swapdev_block
  - mm/shmem.c:shmem_swapin_page
  - mm/memory.c:do_swap_page
  - mm/swapfile.c:unuse_pte_range
```
**Symbols:**

```
ffffffff81273500-ffffffff81273527: swap_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void swap_free(swp_entry_t entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff8127f4a0)
Location: mm/swapfile.c:1313
Inline: False
Direct callers:
  - kernel/power/swap.c:free_all_swap_pages
  - kernel/power/swap.c:alloc_swapdev_block
  - mm/shmem.c:shmem_swapin_page
  - mm/memory.c:do_swap_page
```
**Symbols:**

```
ffffffff8127f4a0-ffffffff8127f4c7: swap_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void swap_free(swp_entry_t entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff8128f170)
Location: mm/swapfile.c:1313
Inline: False
Direct callers:
  - kernel/power/swap.c:free_all_swap_pages
  - kernel/power/swap.c:alloc_swapdev_block
  - mm/shmem.c:shmem_swapin_page
  - mm/memory.c:do_swap_page
```
**Symbols:**

```
ffffffff8128f170-ffffffff8128f197: swap_free (STB_GLOBAL)
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
