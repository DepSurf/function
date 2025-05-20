# Function: <code>page_mapcount_reset</code>

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
In mm/page_alloc.c (ffffffff81191d7c)
Location: include/linux/mm.h:438
Inline: True
Inline callers:
  - mm/page_alloc.c:free_pages_prepare
  - mm/page_alloc.c:free_pages_prepare
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:memmap_init_zone
  - mm/page_alloc.c:memmap_init_zone
```
```
In mm/slub.c (ffffffff811e9118)
Location: include/linux/mm.h:438
Inline: True
Inline callers:
  - mm/slub.c:__free_slab
```
```
In mm/zsmalloc.c (ffffffff81204feb)
Location: include/linux/mm.h:438
Inline: True
Inline callers:
  - mm/zsmalloc.c:free_zspage
  - mm/zsmalloc.c:free_zspage
  - mm/zsmalloc.c:free_zspage
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
In mm/filemap.c (ffffffff811a204b)
Location: include/linux/mm.h:519
Inline: True
Inline callers:
  - mm/filemap.c:__delete_from_page_cache
```
```
In mm/page_alloc.c (ffffffff818972b0)
Location: include/linux/mm.h:519
Inline: True
Inline callers:
  - mm/page_alloc.c:memmap_init_zone
  - mm/page_alloc.c:memmap_init_zone
  - mm/page_alloc.c:check_new_page_bad
  - mm/page_alloc.c:bad_page
```
```
In mm/slub.c (ffffffff81208c27)
Location: include/linux/mm.h:519
Inline: True
Inline callers:
  - mm/slub.c:__free_slab
```
```
In mm/zsmalloc.c (ffffffff8122a114)
Location: include/linux/mm.h:519
Inline: True
Inline callers:
  - mm/zsmalloc.c:reset_page
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
In mm/filemap.c (ffffffff811b1eae)
Location: include/linux/mm.h:506
Inline: True
Inline callers:
  - mm/filemap.c:__delete_from_page_cache
```
```
In mm/page_alloc.c (ffffffff818cba08)
Location: include/linux/mm.h:506
Inline: True
Inline callers:
  - mm/page_alloc.c:memmap_init_zone
  - mm/page_alloc.c:memmap_init_zone
  - mm/page_alloc.c:check_new_page_bad
  - mm/page_alloc.c:bad_page
```
```
In mm/slub.c (ffffffff8121aca3)
Location: include/linux/mm.h:506
Inline: True
Inline callers:
  - mm/slub.c:__free_slab
```
```
In mm/zsmalloc.c (ffffffff8123c664)
Location: include/linux/mm.h:506
Inline: True
Inline callers:
  - mm/zsmalloc.c:reset_page
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
In mm/filemap.c (ffffffff811b8b6f)
Location: include/linux/mm.h:562
Inline: True
Inline callers:
  - mm/filemap.c:__delete_from_page_cache
```
```
In mm/page_alloc.c (ffffffff8190302a)
Location: include/linux/mm.h:562
Inline: True
Inline callers:
  - mm/page_alloc.c:memmap_init_zone
  - mm/page_alloc.c:check_new_page_bad
  - mm/page_alloc.c:bad_page
```
```
In mm/slub.c (ffffffff81226706)
Location: include/linux/mm.h:562
Inline: True
Inline callers:
  - mm/slub.c:__free_slab
```
```
In mm/zsmalloc.c (ffffffff8124826f)
Location: include/linux/mm.h:562
Inline: True
Inline callers:
  - mm/zsmalloc.c:reset_page
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
In mm/filemap.c (ffffffff811ca25f)
Location: include/linux/mm.h:579
Inline: True
Inline callers:
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/page_alloc.c (ffffffff811d3539)
Location: include/linux/mm.h:579
Inline: True
Inline callers:
  - mm/page_alloc.c:check_new_page_bad
  - mm/page_alloc.c:bad_page
```
```
In mm/slub.c (ffffffff8124174e)
Location: include/linux/mm.h:579
Inline: True
Inline callers:
  - mm/slub.c:__free_slab
```
```
In mm/zsmalloc.c (ffffffff8126842f)
Location: include/linux/mm.h:579
Inline: True
Inline callers:
  - mm/zsmalloc.c:reset_page
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
In mm/filemap.c (ffffffff811f0c9a)
Location: include/linux/mm.h:621
Inline: True
Inline callers:
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/page_alloc.c (ffffffff819e9775)
Location: include/linux/mm.h:621
Inline: True
Inline callers:
  - mm/page_alloc.c:memmap_init_zone
  - mm/page_alloc.c:check_new_page_bad
  - mm/page_alloc.c:bad_page
```
```
In mm/zsmalloc.c (ffffffff8128cdbf)
Location: include/linux/mm.h:621
Inline: True
Inline callers:
  - mm/zsmalloc.c:reset_page
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81202af6)
Location: include/linux/mm.h:649
Inline: True
Inline callers:
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/page_alloc.c (ffffffff81206c09)
Location: include/linux/mm.h:649
Inline: True
Inline callers:
  - mm/page_alloc.c:check_new_page_bad
  - mm/page_alloc.c:bad_page
```
```
In mm/zsmalloc.c (ffffffff812a1d3f)
Location: include/linux/mm.h:649
Inline: True
Inline callers:
  - mm/zsmalloc.c:reset_page
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81219f27)
Location: include/linux/mm.h:715
Inline: True
Inline callers:
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/page_alloc.c (ffffffff81a9143b)
Location: include/linux/mm.h:715
Inline: True
Inline callers:
  - mm/page_alloc.c:memmap_init_zone_device
  - mm/page_alloc.c:memmap_init_zone
  - mm/page_alloc.c:check_new_page_bad
  - mm/page_alloc.c:bad_page
```
```
In mm/zsmalloc.c (ffffffff812bcfcf)
Location: include/linux/mm.h:715
Inline: True
Inline callers:
  - mm/zsmalloc.c:reset_page
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81227897)
Location: include/linux/mm.h:710
Inline: True
Inline callers:
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/page_alloc.c (ffffffff81ac8770)
Location: include/linux/mm.h:710
Inline: True
Inline callers:
  - mm/page_alloc.c:memmap_init_zone_device
  - mm/page_alloc.c:memmap_init_zone
  - mm/page_alloc.c:check_new_page_bad
  - mm/page_alloc.c:bad_page
```
```
In mm/zsmalloc.c (ffffffff812ceebf)
Location: include/linux/mm.h:710
Inline: True
Inline callers:
  - mm/zsmalloc.c:reset_page
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff812541d6)
Location: include/linux/mm.h:799
Inline: True
Inline callers:
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/page_alloc.c (ffffffff82cfb4d8)
Location: include/linux/mm.h:799
Inline: True
Inline callers:
  - mm/page_alloc.c:init_unavailable_range
  - mm/page_alloc.c:memmap_init_zone_device
  - mm/page_alloc.c:memmap_init_zone
  - mm/page_alloc.c:check_new_page_bad
  - mm/page_alloc.c:bad_page
```
```
In mm/zsmalloc.c (ffffffff813056bf)
Location: include/linux/mm.h:799
Inline: True
Inline callers:
  - mm/zsmalloc.c:reset_page
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81be6a76)
Location: include/linux/mm.h:832
Inline: True
Inline callers:
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/page_alloc.c (ffffffff812b9622)
Location: include/linux/mm.h:832
Inline: True
Inline callers:
  - mm/page_alloc.c:check_new_page_bad
  - mm/page_alloc.c:bad_page
```
```
In mm/zsmalloc.c (ffffffff8131141f)
Location: include/linux/mm.h:832
Inline: True
Inline callers:
  - mm/zsmalloc.c:reset_page
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81bd880c)
Location: include/linux/mm.h:855
Inline: True
Inline callers:
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/page_alloc.c (ffffffff812be9bf)
Location: include/linux/mm.h:855
Inline: True
Inline callers:
  - mm/page_alloc.c:check_new_page_bad
  - mm/page_alloc.c:bad_page
```
```
In mm/zsmalloc.c (ffffffff813174ef)
Location: include/linux/mm.h:855
Inline: True
Inline callers:
  - mm/zsmalloc.c:reset_page
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81cb9e66)
Location: include/linux/mm.h:858
Inline: True
Inline callers:
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/page_alloc.c (ffffffff8130131f)
Location: include/linux/mm.h:858
Inline: True
Inline callers:
  - mm/page_alloc.c:check_new_page_bad
  - mm/page_alloc.c:bad_page
```
```
In mm/zsmalloc.c (ffffffff81363a4f)
Location: include/linux/mm.h:858
Inline: True
Inline callers:
  - mm/zsmalloc.c:reset_page
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81e6b4af)
Location: include/linux/mm.h:807
Inline: True
Inline callers:
  - mm/filemap.c:filemap_unaccount_folio
```
```
In mm/page_alloc.c (ffffffff81368ef1)
Location: include/linux/mm.h:807
Inline: True
Inline callers:
  - mm/page_alloc.c:check_new_pages
  - mm/page_alloc.c:bad_page
```
```
In mm/zsmalloc.c (ffffffff813e1e50)
Location: include/linux/mm.h:807
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:__free_zspage
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81359a51)
Location: include/linux/mm.h:870
Inline: True
Inline callers:
  - mm/filemap.c:filemap_unaccount_folio
```
```
In mm/page_alloc.c (ffffffff83ebe830)
Location: include/linux/mm.h:870
Inline: True
Inline callers:
  - mm/page_alloc.c:init_unavailable_range
  - mm/page_alloc.c:__init_zone_device_page
  - mm/page_alloc.c:memmap_init_range
  - mm/page_alloc.c:check_new_pages
  - mm/page_alloc.c:bad_page
```
```
In mm/zsmalloc.c (ffffffff81469433)
Location: include/linux/mm.h:870
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:__free_zspage
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8138b39e)
Location: include/linux/mm.h:1111
Inline: True
Inline callers:
  - mm/filemap.c:filemap_unaccount_folio
```
```
In mm/mm_init.c (ffffffff8214bfbc)
Location: include/linux/mm.h:1111
Inline: True
Inline callers:
  - mm/mm_init.c:memmap_init_range
  - mm/mm_init.c:init_unavailable_range
```
```
In mm/page_alloc.c (ffffffff8141eaef)
Location: include/linux/mm.h:1111
Inline: True
Inline callers:
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:__rmqueue_pcplist
  - mm/page_alloc.c:bad_page
```
```
In mm/zsmalloc.c (ffffffff8149e3c2)
Location: include/linux/mm.h:1111
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:__free_zspage
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff813b4ec5)
Location: include/linux/mm.h:1194
Inline: True
Inline callers:
  - mm/filemap.c:filemap_unaccount_folio
```
```
In mm/mm_init.c (ffffffff8222eb52)
Location: include/linux/mm.h:1194
Inline: True
Inline callers:
  - mm/mm_init.c:memmap_init_range
  - mm/mm_init.c:init_unavailable_range
```
```
In mm/page_alloc.c (ffffffff8144b6dc)
Location: include/linux/mm.h:1194
Inline: True
Inline callers:
  - mm/page_alloc.c:rmqueue
  - mm/page_alloc.c:__rmqueue_pcplist
  - mm/page_alloc.c:bad_page
```
```
In mm/zsmalloc.c (ffffffff814cd4f3)
Location: include/linux/mm.h:1194
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:__free_zspage
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
In mm/filemap.c (ffff8000102aeecc)
Location: include/linux/mm.h:710
Inline: True
Inline callers:
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/page_alloc.c (ffff800010d9fe4c)
Location: include/linux/mm.h:710
Inline: True
Inline callers:
  - mm/page_alloc.c:memmap_init_zone
  - mm/page_alloc.c:check_new_page_bad
  - mm/page_alloc.c:bad_page
```
```
In mm/zsmalloc.c (ffff8000103744c4)
Location: include/linux/mm.h:710
Inline: True
Inline callers:
  - mm/zsmalloc.c:reset_page
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
In mm/filemap.c (c04dab00)
Location: include/linux/mm.h:710
Inline: True
Inline callers:
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/page_alloc.c (c15bdd5c)
Location: include/linux/mm.h:710
Inline: True
Inline callers:
  - mm/page_alloc.c:memmap_init_zone
  - mm/page_alloc.c:bad_page
```
```
In mm/zsmalloc.c (c05602f8)
Location: include/linux/mm.h:710
Inline: True
Inline callers:
  - mm/zsmalloc.c:reset_page
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
In mm/filemap.c (c000000000362424)
Location: include/linux/mm.h:710
Inline: True
Inline callers:
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/page_alloc.c (c0000000003ee9dc)
Location: include/linux/mm.h:710
Inline: True
Inline callers:
  - mm/page_alloc.c:memmap_init_zone_device
  - mm/page_alloc.c:memmap_init_zone
  - mm/page_alloc.c:check_new_page_bad
  - mm/page_alloc.c:bad_page
```
```
In mm/zsmalloc.c (c00000000046659c)
Location: include/linux/mm.h:710
Inline: True
Inline callers:
  - mm/zsmalloc.c:reset_page
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
In mm/filemap.c (ffffffe0001d4428)
Location: include/linux/mm.h:710
Inline: True
Inline callers:
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/page_alloc.c (ffffffe0000471c4)
Location: include/linux/mm.h:710
Inline: True
Inline callers:
  - mm/page_alloc.c:memmap_init_zone
  - mm/page_alloc.c:bad_page
```
```
In mm/zsmalloc.c (ffffffe00024e456)
Location: include/linux/mm.h:710
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_page_migrate
  - mm/zsmalloc.c:__free_zspage
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8121fee7)
Location: include/linux/mm.h:710
Inline: True
Inline callers:
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/page_alloc.c (ffffffff81a675e0)
Location: include/linux/mm.h:710
Inline: True
Inline callers:
  - mm/page_alloc.c:memmap_init_zone_device
  - mm/page_alloc.c:memmap_init_zone
  - mm/page_alloc.c:check_new_page_bad
  - mm/page_alloc.c:bad_page
```
```
In mm/zsmalloc.c (ffffffff812c749f)
Location: include/linux/mm.h:710
Inline: True
Inline callers:
  - mm/zsmalloc.c:reset_page
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81213097)
Location: include/linux/mm.h:710
Inline: True
Inline callers:
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/page_alloc.c (ffffffff81a240a0)
Location: include/linux/mm.h:710
Inline: True
Inline callers:
  - mm/page_alloc.c:memmap_init_zone_device
  - mm/page_alloc.c:memmap_init_zone
  - mm/page_alloc.c:check_new_page_bad
  - mm/page_alloc.c:bad_page
```
```
In mm/zsmalloc.c (ffffffff812b84df)
Location: include/linux/mm.h:710
Inline: True
Inline callers:
  - mm/zsmalloc.c:reset_page
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8121dc87)
Location: include/linux/mm.h:710
Inline: True
Inline callers:
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/page_alloc.c (ffffffff81ad39f0)
Location: include/linux/mm.h:710
Inline: True
Inline callers:
  - mm/page_alloc.c:memmap_init_zone_device
  - mm/page_alloc.c:memmap_init_zone
  - mm/page_alloc.c:check_new_page_bad
  - mm/page_alloc.c:bad_page
```
```
In mm/zsmalloc.c (ffffffff812c52af)
Location: include/linux/mm.h:710
Inline: True
Inline callers:
  - mm/zsmalloc.c:reset_page
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8122ccf7)
Location: include/linux/mm.h:710
Inline: True
Inline callers:
  - mm/filemap.c:unaccount_page_cache_page
```
```
In mm/page_alloc.c (ffffffff81adfeea)
Location: include/linux/mm.h:710
Inline: True
Inline callers:
  - mm/page_alloc.c:memmap_init_zone_device
  - mm/page_alloc.c:memmap_init_zone
  - mm/page_alloc.c:check_new_page_bad
  - mm/page_alloc.c:bad_page
```
```
In mm/zsmalloc.c (ffffffff812d5d8f)
Location: include/linux/mm.h:710
Inline: True
Inline callers:
  - mm/zsmalloc.c:reset_page
```
</details>
</li>
</ul>

## Differences
