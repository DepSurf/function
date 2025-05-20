# Function: <code>set_page_refcounted</code>

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
In mm/page_alloc.c (ffffffff81191739)
Location: mm/internal.h:62
Inline: True
Inline callers:
  - mm/page_alloc.c:__free_pages_bootmem
  - mm/page_alloc.c:make_alloc_exact
  - mm/page_alloc.c:init_cma_reserved_pageblock
  - mm/page_alloc.c:split_free_page
  - mm/page_alloc.c:split_free_page
  - mm/page_alloc.c:get_page_from_freelist
```
```
In mm/hugetlb.c (ffffffff811da2ca)
Location: mm/internal.h:62
Inline: True
Inline callers:
  - mm/hugetlb.c:dequeue_huge_page_node
  - mm/hugetlb.c:update_and_free_page
  - mm/hugetlb.c:update_and_free_page
  - mm/hugetlb.c:dequeue_hwpoisoned_huge_page
```
```
In mm/page_isolation.c (ffffffff81203be5)
Location: mm/internal.h:62
Inline: True
Inline callers:
  - mm/page_isolation.c:unset_migratetype_isolate
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
In mm/page_alloc.c (ffffffff811a9058)
Location: mm/internal.h:67
Inline: True
Inline callers:
  - mm/page_alloc.c:make_alloc_exact
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:init_cma_reserved_pageblock
  - mm/page_alloc.c:__free_pages_bootmem
```
```
In mm/hugetlb.c (ffffffff811fe0e4)
Location: mm/internal.h:67
Inline: True
Inline callers:
  - mm/hugetlb.c:dequeue_hwpoisoned_huge_page
  - mm/hugetlb.c:update_and_free_page
  - mm/hugetlb.c:update_and_free_page
  - mm/hugetlb.c:dequeue_huge_page_node
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
In mm/page_alloc.c (ffffffff811b95e7)
Location: mm/internal.h:69
Inline: True
Inline callers:
  - mm/page_alloc.c:make_alloc_exact
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:init_cma_reserved_pageblock
  - mm/page_alloc.c:__free_pages_bootmem
```
```
In mm/hugetlb.c (ffffffff8120ebb4)
Location: mm/internal.h:69
Inline: True
Inline callers:
  - mm/hugetlb.c:dequeue_hwpoisoned_huge_page
  - mm/hugetlb.c:update_and_free_page
  - mm/hugetlb.c:update_and_free_page
  - mm/hugetlb.c:dequeue_huge_page_node
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
In mm/page_alloc.c (ffffffff811c1657)
Location: mm/internal.h:74
Inline: True
Inline callers:
  - mm/page_alloc.c:make_alloc_exact
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:init_cma_reserved_pageblock
  - mm/page_alloc.c:__free_pages_bootmem
```
```
In mm/hugetlb.c (ffffffff81214e0a)
Location: mm/internal.h:74
Inline: True
Inline callers:
  - mm/hugetlb.c:update_and_free_page
  - mm/hugetlb.c:update_and_free_page
  - mm/hugetlb.c:dequeue_huge_page_nodemask
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
In mm/page_alloc.c (ffffffff811d5a77)
Location: mm/internal.h:74
Inline: True
Inline callers:
  - mm/page_alloc.c:make_alloc_exact
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:init_cma_reserved_pageblock
  - mm/page_alloc.c:__free_pages_bootmem
```
```
In mm/hugetlb.c (ffffffff8122fb2d)
Location: mm/internal.h:74
Inline: True
Inline callers:
  - mm/hugetlb.c:update_and_free_page
  - mm/hugetlb.c:update_and_free_page
  - mm/hugetlb.c:dequeue_huge_page_nodemask
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
In mm/page_alloc.c (ffffffff811f6e85)
Location: mm/internal.h:74
Inline: True
Inline callers:
  - mm/page_alloc.c:make_alloc_exact
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:init_cma_reserved_pageblock
  - mm/page_alloc.c:__free_pages_bootmem
```
```
In mm/hugetlb.c (ffffffff81251f7a)
Location: mm/internal.h:74
Inline: True
Inline callers:
  - mm/hugetlb.c:update_and_free_page
  - mm/hugetlb.c:update_and_free_page
  - mm/hugetlb.c:dequeue_huge_page_nodemask
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
In mm/page_alloc.c (ffffffff81209225)
Location: mm/internal.h:74
Inline: True
Inline callers:
  - mm/page_alloc.c:make_alloc_exact
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:init_cma_reserved_pageblock
  - mm/page_alloc.c:memblock_free_pages
```
```
In mm/hugetlb.c (ffffffff81266378)
Location: mm/internal.h:74
Inline: True
Inline callers:
  - mm/hugetlb.c:update_and_free_page
  - mm/hugetlb.c:update_and_free_page
  - mm/hugetlb.c:dequeue_huge_page_nodemask
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
In mm/page_alloc.c (ffffffff81270643)
Location: mm/internal.h:70
Inline: True
Inline callers:
  - mm/page_alloc.c:make_alloc_exact
  - mm/page_alloc.c:prep_new_page
  - mm/page_alloc.c:init_cma_reserved_pageblock
  - mm/page_alloc.c:__free_pages_core
```
```
In mm/hugetlb.c (ffffffff812814fc)
Location: mm/internal.h:70
Inline: True
Inline callers:
  - mm/hugetlb.c:update_and_free_page
  - mm/hugetlb.c:update_and_free_page
  - mm/hugetlb.c:dequeue_huge_page_nodemask
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
In mm/page_alloc.c (ffffffff8127f483)
Location: mm/internal.h:70
Inline: True
Inline callers:
  - mm/page_alloc.c:make_alloc_exact
  - mm/page_alloc.c:prep_new_page
  - mm/page_alloc.c:init_cma_reserved_pageblock
  - mm/page_alloc.c:__free_pages_core
```
```
In mm/hugetlb.c (ffffffff81290ffc)
Location: mm/internal.h:70
Inline: True
Inline callers:
  - mm/hugetlb.c:update_and_free_page
  - mm/hugetlb.c:update_and_free_page
  - mm/hugetlb.c:dequeue_huge_page_nodemask
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
In mm/page_alloc.c (ffffffff812b1b5b)
Location: mm/internal.h:95
Inline: True
Inline callers:
  - mm/page_alloc.c:make_alloc_exact
  - mm/page_alloc.c:prep_new_page
  - mm/page_alloc.c:__free_pages_core
```
```
In mm/hugetlb.c (ffffffff812c4bae)
Location: mm/internal.h:95
Inline: True
Inline callers:
  - mm/hugetlb.c:update_and_free_page
  - mm/hugetlb.c:destroy_compound_gigantic_page
  - mm/hugetlb.c:dequeue_huge_page_nodemask
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
In mm/page_alloc.c (ffffffff812bd4d9)
Location: mm/internal.h:93
Inline: True
Inline callers:
  - mm/page_alloc.c:make_alloc_exact
  - mm/page_alloc.c:__alloc_pages_direct_compact
  - mm/page_alloc.c:get_page_from_freelist
```
```
In mm/hugetlb.c (ffffffff812d0860)
Location: mm/internal.h:93
Inline: True
Inline callers:
  - mm/hugetlb.c:update_and_free_page
  - mm/hugetlb.c:update_and_free_page
  - mm/hugetlb.c:dequeue_huge_page_nodemask
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
In mm/page_alloc.c (ffffffff812c246a)
Location: mm/internal.h:92
Inline: True
Inline callers:
  - mm/page_alloc.c:make_alloc_exact
  - mm/page_alloc.c:__alloc_pages_bulk
  - mm/page_alloc.c:__alloc_pages_direct_compact
  - mm/page_alloc.c:get_page_from_freelist
```
```
In mm/hugetlb.c (ffffffff812d61d4)
Location: mm/internal.h:92
Inline: True
Inline callers:
  - mm/hugetlb.c:update_and_free_page
  - mm/hugetlb.c:remove_hugetlb_page
  - mm/hugetlb.c:dequeue_huge_page_nodemask
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
In mm/page_alloc.c (ffffffff81308637)
Location: mm/internal.h:92
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_bulk
  - mm/page_alloc.c:__alloc_pages_direct_compact
  - mm/page_alloc.c:get_page_from_freelist
  - mm/page_alloc.c:split_page
```
```
In mm/hugetlb.c (ffffffff81325506)
Location: mm/internal.h:92
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_and_dissolve_huge_page
  - mm/hugetlb.c:prep_compound_gigantic_page
  - mm/hugetlb.c:remove_hugetlb_page
  - mm/hugetlb.c:dequeue_huge_page_nodemask
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
In mm/page_alloc.c (ffffffff813709e8)
Location: mm/internal.h:157
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_bulk
  - mm/page_alloc.c:split_page
```
```
In mm/hugetlb.c (ffffffff81389adb)
Location: mm/internal.h:157
Inline: True
Inline callers:
  - mm/hugetlb.c:demote_free_huge_page
  - mm/hugetlb.c:demote_free_huge_page
  - mm/hugetlb.c:alloc_and_dissolve_huge_page
  - mm/hugetlb.c:__prep_compound_gigantic_page
  - mm/hugetlb.c:__remove_hugetlb_page
  - mm/hugetlb.c:__destroy_compound_gigantic_page
  - mm/hugetlb.c:dequeue_huge_page_nodemask
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
In mm/page_alloc.c (ffffffff813e6791)
Location: mm/internal.h:159
Inline: True
Inline callers:
  - mm/page_alloc.c:make_alloc_exact
  - mm/page_alloc.c:__alloc_pages_bulk
  - mm/page_alloc.c:split_page
```
```
In mm/hugetlb.c (ffffffff8140a942)
Location: mm/internal.h:159
Inline: True
Inline callers:
  - mm/hugetlb.c:demote_free_huge_page
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:__prep_compound_gigantic_folio
  - mm/hugetlb.c:__destroy_compound_gigantic_folio
  - mm/hugetlb.c:dequeue_huge_page_nodemask
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
In mm/page_alloc.c (ffffffff8141b709)
Location: mm/internal.h:166
Inline: True
Inline callers:
  - mm/page_alloc.c:make_alloc_exact
  - mm/page_alloc.c:__alloc_pages_bulk
  - mm/page_alloc.c:split_page
```
```
In mm/hugetlb.c (ffffffff81438ef9)
Location: mm/internal.h:166
Inline: True
Inline callers:
  - mm/hugetlb.c:__prep_compound_gigantic_folio
  - mm/hugetlb.c:__update_and_free_hugetlb_folio
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
In mm/page_alloc.c (ffffffff81448749)
Location: mm/internal.h:172
Inline: True
Inline callers:
  - mm/page_alloc.c:make_alloc_exact
  - mm/page_alloc.c:__alloc_pages_bulk
  - mm/page_alloc.c:split_page
```
```
In mm/hugetlb.c (ffffffff814728c2)
Location: mm/internal.h:172
Inline: True
Inline callers:
  - mm/hugetlb.c:__prep_compound_gigantic_folio
  - mm/hugetlb.c:__destroy_compound_gigantic_folio
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
In mm/page_alloc.c (ffff800010317048)
Location: mm/internal.h:70
Inline: True
Inline callers:
  - mm/page_alloc.c:make_alloc_exact
  - mm/page_alloc.c:prep_new_page
  - mm/page_alloc.c:init_cma_reserved_pageblock
  - mm/page_alloc.c:__free_pages_core
```
```
In mm/hugetlb.c (ffff80001032e468)
Location: mm/internal.h:70
Inline: True
Inline callers:
  - mm/hugetlb.c:update_and_free_page
  - mm/hugetlb.c:update_and_free_page
  - mm/hugetlb.c:dequeue_huge_page_nodemask
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (c0531818)
Location: mm/internal.h:70
Inline: True
Inline callers:
  - mm/page_alloc.c:make_alloc_exact
  - mm/page_alloc.c:prep_new_page
  - mm/page_alloc.c:init_cma_reserved_pageblock
  - mm/page_alloc.c:__free_pages_core
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
In mm/page_alloc.c (c0000000003e9370)
Location: mm/internal.h:70
Inline: True
Inline callers:
  - mm/page_alloc.c:make_alloc_exact
  - mm/page_alloc.c:prep_new_page
  - mm/page_alloc.c:init_cma_reserved_pageblock
  - mm/page_alloc.c:init_cma_reserved_pageblock
  - mm/page_alloc.c:__free_pages_core
```
```
In mm/hugetlb.c (c000000000405f70)
Location: mm/internal.h:70
Inline: True
Inline callers:
  - mm/hugetlb.c:dequeue_huge_page_nodemask
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
In mm/page_alloc.c (ffffffe00021d382)
Location: mm/internal.h:70
Inline: True
Inline callers:
  - mm/page_alloc.c:make_alloc_exact
  - mm/page_alloc.c:prep_new_page
  - mm/page_alloc.c:init_cma_reserved_pageblock
  - mm/page_alloc.c:__free_pages_core
```
```
In mm/hugetlb.c (ffffffe00022c29a)
Location: mm/internal.h:70
Inline: True
Inline callers:
  - mm/hugetlb.c:update_and_free_page
  - mm/hugetlb.c:update_and_free_page
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
In mm/page_alloc.c (ffffffff81277ad3)
Location: mm/internal.h:70
Inline: True
Inline callers:
  - mm/page_alloc.c:make_alloc_exact
  - mm/page_alloc.c:prep_new_page
  - mm/page_alloc.c:init_cma_reserved_pageblock
  - mm/page_alloc.c:__free_pages_core
```
```
In mm/hugetlb.c (ffffffff812895dc)
Location: mm/internal.h:70
Inline: True
Inline callers:
  - mm/hugetlb.c:update_and_free_page
  - mm/hugetlb.c:update_and_free_page
  - mm/hugetlb.c:dequeue_huge_page_nodemask
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
In mm/page_alloc.c (ffffffff812699e3)
Location: mm/internal.h:70
Inline: True
Inline callers:
  - mm/page_alloc.c:make_alloc_exact
  - mm/page_alloc.c:prep_new_page
  - mm/page_alloc.c:init_cma_reserved_pageblock
  - mm/page_alloc.c:__free_pages_core
```
```
In mm/hugetlb.c (ffffffff8127b47c)
Location: mm/internal.h:70
Inline: True
Inline callers:
  - mm/hugetlb.c:update_and_free_page
  - mm/hugetlb.c:update_and_free_page
  - mm/hugetlb.c:dequeue_huge_page_nodemask
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
In mm/page_alloc.c (ffffffff81275873)
Location: mm/internal.h:70
Inline: True
Inline callers:
  - mm/page_alloc.c:make_alloc_exact
  - mm/page_alloc.c:prep_new_page
  - mm/page_alloc.c:init_cma_reserved_pageblock
  - mm/page_alloc.c:__free_pages_core
```
```
In mm/hugetlb.c (ffffffff812873ec)
Location: mm/internal.h:70
Inline: True
Inline callers:
  - mm/hugetlb.c:update_and_free_page
  - mm/hugetlb.c:update_and_free_page
  - mm/hugetlb.c:dequeue_huge_page_nodemask
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
In mm/page_alloc.c (ffffffff81285433)
Location: mm/internal.h:70
Inline: True
Inline callers:
  - mm/page_alloc.c:make_alloc_exact
  - mm/page_alloc.c:prep_new_page
  - mm/page_alloc.c:init_cma_reserved_pageblock
  - mm/page_alloc.c:__free_pages_core
```
```
In mm/hugetlb.c (ffffffff81297b2c)
Location: mm/internal.h:70
Inline: True
Inline callers:
  - mm/hugetlb.c:update_and_free_page
  - mm/hugetlb.c:update_and_free_page
  - mm/hugetlb.c:dequeue_huge_page_nodemask
```
</details>
</li>
</ul>

## Differences
