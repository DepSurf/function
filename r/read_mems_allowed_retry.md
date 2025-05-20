# Function: <code>read_mems_allowed_retry</code>

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
In mm/filemap.c (ffffffff8118d5ff)
Location: include/linux/cpuset.h:119
Inline: True
```
```
In mm/page_alloc.c (ffffffff81192505)
Location: include/linux/cpuset.h:119
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_nodemask
```
```
In mm/hugetlb.c (ffffffff811dad90)
Location: include/linux/cpuset.h:119
Inline: True
Inline callers:
  - mm/hugetlb.c:__alloc_buddy_huge_page
  - mm/hugetlb.c:alloc_huge_page
```
```
In mm/mempolicy.c (ffffffff811e0806)
Location: include/linux/cpuset.h:119
Inline: True
Inline callers:
  - mm/mempolicy.c:alloc_pages_current
  - mm/mempolicy.c:alloc_pages_vma
```
```
In mm/slub.c (ffffffff811ea7c8)
Location: include/linux/cpuset.h:119
Inline: True
Inline callers:
  - mm/slub.c:___slab_alloc
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
In mm/filemap.c (ffffffff811a01f1)
Location: include/linux/cpuset.h:128
Inline: True
```
```
In mm/page_alloc.c (ffffffff811ab0c4)
Location: include/linux/cpuset.h:128
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_nodemask
```
```
In mm/hugetlb.c (ffffffff811fac36)
Location: include/linux/cpuset.h:128
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:__alloc_buddy_huge_page
```
```
In mm/mempolicy.c (ffffffff811fead1)
Location: include/linux/cpuset.h:128
Inline: True
Inline callers:
  - mm/mempolicy.c:alloc_pages_current
  - mm/mempolicy.c:alloc_pages_vma
```
```
In mm/slub.c (ffffffff81209dd9)
Location: include/linux/cpuset.h:128
Inline: True
Inline callers:
  - mm/slub.c:___slab_alloc
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
In mm/filemap.c (ffffffff811af631)
Location: include/linux/cpuset.h:128
Inline: True
```
```
In mm/page_alloc.c (ffffffff811bac0a)
Location: include/linux/cpuset.h:128
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
```
```
In mm/hugetlb.c (ffffffff8120b736)
Location: include/linux/cpuset.h:128
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:__alloc_buddy_huge_page
```
```
In mm/mempolicy.c (ffffffff81210311)
Location: include/linux/cpuset.h:128
Inline: True
Inline callers:
  - mm/mempolicy.c:alloc_pages_current
  - mm/mempolicy.c:alloc_pages_vma
```
```
In mm/slub.c (ffffffff8121be49)
Location: include/linux/cpuset.h:128
Inline: True
Inline callers:
  - mm/slub.c:___slab_alloc
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
In mm/filemap.c (ffffffff811b651b)
Location: include/linux/cpuset.h:147
Inline: True
```
```
In mm/page_alloc.c (ffffffff811c31f5)
Location: include/linux/cpuset.h:147
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
```
```
In mm/hugetlb.c (ffffffff8121445c)
Location: include/linux/cpuset.h:147
Inline: True
Inline callers:
  - mm/hugetlb.c:dequeue_huge_page_nodemask
```
```
In mm/slub.c (ffffffff812279a8)
Location: include/linux/cpuset.h:147
Inline: True
Inline callers:
  - mm/slub.c:___slab_alloc
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
In mm/filemap.c (ffffffff811ca8a1)
Location: include/linux/cpuset.h:142
Inline: True
```
```
In mm/page_alloc.c (ffffffff811d7f97)
Location: include/linux/cpuset.h:142
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
```
```
In mm/hugetlb.c (ffffffff8122f114)
Location: include/linux/cpuset.h:142
Inline: True
Inline callers:
  - mm/hugetlb.c:dequeue_huge_page_nodemask
```
```
In mm/slub.c (ffffffff81243d11)
Location: include/linux/cpuset.h:142
Inline: True
Inline callers:
  - mm/slub.c:___slab_alloc
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
In mm/filemap.c (ffffffff811eb8f1)
Location: include/linux/cpuset.h:142
Inline: True
```
```
In mm/page_alloc.c (ffffffff811f9092)
Location: include/linux/cpuset.h:142
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
```
```
In mm/hugetlb.c (ffffffff8125189b)
Location: include/linux/cpuset.h:142
Inline: True
Inline callers:
  - mm/hugetlb.c:dequeue_huge_page_nodemask
```
```
In mm/slub.c (ffffffff81266423)
Location: include/linux/cpuset.h:142
Inline: True
Inline callers:
  - mm/slub.c:___slab_alloc
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
In mm/filemap.c (ffffffff811fc471)
Location: include/linux/cpuset.h:142
Inline: True
```
```
In mm/page_alloc.c (ffffffff8120b640)
Location: include/linux/cpuset.h:142
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
```
```
In mm/hugetlb.c (ffffffff81265c9b)
Location: include/linux/cpuset.h:142
Inline: True
Inline callers:
  - mm/hugetlb.c:dequeue_huge_page_nodemask
```
```
In mm/slub.c (ffffffff8127b15e)
Location: include/linux/cpuset.h:142
Inline: True
Inline callers:
  - mm/slub.c:___slab_alloc
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
In mm/filemap.c (ffffffff81213b3d)
Location: include/linux/cpuset.h:142
Inline: True
```
```
In mm/page_alloc.c (ffffffff812718b4)
Location: include/linux/cpuset.h:142
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
```
```
In mm/hugetlb.c (ffffffff812811de)
Location: include/linux/cpuset.h:142
Inline: True
Inline callers:
  - mm/hugetlb.c:dequeue_huge_page_nodemask
```
```
In mm/slub.c (ffffffff81296be0)
Location: include/linux/cpuset.h:142
Inline: True
Inline callers:
  - mm/slub.c:___slab_alloc
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
In mm/filemap.c (ffffffff8122130d)
Location: include/linux/cpuset.h:144
Inline: True
```
```
In mm/page_alloc.c (ffffffff81280764)
Location: include/linux/cpuset.h:144
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
```
```
In mm/hugetlb.c (ffffffff81290e6e)
Location: include/linux/cpuset.h:144
Inline: True
Inline callers:
  - mm/hugetlb.c:dequeue_huge_page_nodemask
```
```
In mm/slub.c (ffffffff812a69aa)
Location: include/linux/cpuset.h:144
Inline: True
Inline callers:
  - mm/slub.c:___slab_alloc
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
In mm/filemap.c (ffffffff8124e349)
Location: include/linux/cpuset.h:144
Inline: True
```
```
In mm/page_alloc.c (ffffffff812b2eec)
Location: include/linux/cpuset.h:144
Inline: True
```
```
In mm/hugetlb.c (ffffffff812c3718)
Location: include/linux/cpuset.h:144
Inline: True
Inline callers:
  - mm/hugetlb.c:dequeue_huge_page_nodemask
```
```
In mm/slub.c (ffffffff812db06a)
Location: include/linux/cpuset.h:144
Inline: True
Inline callers:
  - mm/slub.c:get_any_partial
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
In mm/filemap.c (ffffffff8125875a)
Location: include/linux/cpuset.h:144
Inline: True
```
```
In mm/page_alloc.c (ffffffff812bea29)
Location: include/linux/cpuset.h:144
Inline: True
```
```
In mm/hugetlb.c (ffffffff812cf6d9)
Location: include/linux/cpuset.h:144
Inline: True
Inline callers:
  - mm/hugetlb.c:dequeue_huge_page_nodemask
```
```
In mm/slub.c (ffffffff812e7957)
Location: include/linux/cpuset.h:144
Inline: True
Inline callers:
  - mm/slub.c:get_any_partial
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
In mm/filemap.c (ffffffff8125cde4)
Location: include/linux/cpuset.h:144
Inline: True
```
```
In mm/page_alloc.c (ffffffff812c3aad)
Location: include/linux/cpuset.h:144
Inline: True
```
```
In mm/hugetlb.c (ffffffff812d68fb)
Location: include/linux/cpuset.h:144
Inline: True
Inline callers:
  - mm/hugetlb.c:dequeue_huge_page_nodemask
```
```
In mm/slub.c (ffffffff812ef0c7)
Location: include/linux/cpuset.h:144
Inline: True
Inline callers:
  - mm/slub.c:get_any_partial
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
In mm/filemap.c (ffffffff81298d61)
Location: include/linux/cpuset.h:145
Inline: True
```
```
In mm/page_alloc.c (ffffffff81307946)
Location: include/linux/cpuset.h:145
Inline: True
```
```
In mm/hugetlb.c (ffffffff8131c6c7)
Location: include/linux/cpuset.h:145
Inline: True
Inline callers:
  - mm/hugetlb.c:dequeue_huge_page_nodemask
```
```
In mm/slub.c (ffffffff813373d4)
Location: include/linux/cpuset.h:145
Inline: True
Inline callers:
  - mm/slub.c:get_any_partial
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
In mm/filemap.c (ffffffff812ef5c6)
Location: include/linux/cpuset.h:160
Inline: True
```
```
In mm/page_alloc.c (ffffffff8136fc25)
Location: include/linux/cpuset.h:160
Inline: True
```
```
In mm/hugetlb.c (ffffffff81387889)
Location: include/linux/cpuset.h:160
Inline: True
Inline callers:
  - mm/hugetlb.c:dequeue_huge_page_nodemask
```
```
In mm/slub.c (ffffffff813a8cd6)
Location: include/linux/cpuset.h:160
Inline: True
Inline callers:
  - mm/slub.c:get_any_partial
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
In mm/filemap.c (ffffffff8135a0e8)
Location: include/linux/cpuset.h:160
Inline: True
```
```
In mm/page_alloc.c (ffffffff813ec24f)
Location: include/linux/cpuset.h:160
Inline: True
```
```
In mm/hugetlb.c (ffffffff81405cab)
Location: include/linux/cpuset.h:160
Inline: True
Inline callers:
  - mm/hugetlb.c:dequeue_huge_page_nodemask
```
```
In mm/slub.c (ffffffff81429e14)
Location: include/linux/cpuset.h:160
Inline: True
Inline callers:
  - mm/slub.c:get_any_partial
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
In mm/filemap.c (ffffffff8138bb48)
Location: include/linux/cpuset.h:155
Inline: True
```
```
In mm/page_alloc.c (ffffffff81421201)
Location: include/linux/cpuset.h:155
Inline: True
```
```
In mm/hugetlb.c (ffffffff814391eb)
Location: include/linux/cpuset.h:155
Inline: True
Inline callers:
  - mm/hugetlb.c:dequeue_hugetlb_folio_nodemask
```
```
In mm/slub.c (ffffffff8145f209)
Location: include/linux/cpuset.h:155
Inline: True
Inline callers:
  - mm/slub.c:get_any_partial
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
In mm/filemap.c (ffffffff813b56b8)
Location: include/linux/cpuset.h:156
Inline: True
```
```
In mm/page_alloc.c (ffffffff8144df7a)
Location: include/linux/cpuset.h:156
Inline: True
```
```
In mm/slub.c (ffffffff8145a376)
Location: include/linux/cpuset.h:156
Inline: True
Inline callers:
  - mm/slub.c:get_any_partial
```
```
In mm/hugetlb.c (ffffffff81472d1b)
Location: include/linux/cpuset.h:156
Inline: True
Inline callers:
  - mm/hugetlb.c:dequeue_hugetlb_folio_nodemask
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
In mm/filemap.c (ffff8000102adfd8)
Location: include/linux/cpuset.h:144
Inline: True
```
```
In mm/page_alloc.c (ffff800010318754)
Location: include/linux/cpuset.h:144
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
```
```
In mm/hugetlb.c (ffff80001032d970)
Location: include/linux/cpuset.h:144
Inline: True
Inline callers:
  - mm/hugetlb.c:dequeue_huge_page_nodemask
```
```
In mm/slub.c (ffff800010347b1c)
Location: include/linux/cpuset.h:144
Inline: True
Inline callers:
  - mm/slub.c:___slab_alloc
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
In mm/page_alloc.c (c053292c)
Location: include/linux/cpuset.h:144
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
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
In mm/filemap.c (c0000000003630c4)
Location: include/linux/cpuset.h:144
Inline: True
```
```
In mm/page_alloc.c (c0000000003eaf94)
Location: include/linux/cpuset.h:144
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
```
```
In mm/hugetlb.c (c000000000405fe0)
Location: include/linux/cpuset.h:144
Inline: True
Inline callers:
  - mm/hugetlb.c:dequeue_huge_page_nodemask
```
```
In mm/slub.c (c000000000425fe0)
Location: include/linux/cpuset.h:144
Inline: True
Inline callers:
  - mm/slub.c:___slab_alloc
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
In mm/page_alloc.c (ffffffe00021e14c)
Location: include/linux/cpuset.h:144
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
```
```
In mm/hugetlb.c (ffffffe00022c10e)
Location: include/linux/cpuset.h:144
Inline: True
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
In mm/filemap.c (ffffffff8121995d)
Location: include/linux/cpuset.h:144
Inline: True
```
```
In mm/page_alloc.c (ffffffff81278db4)
Location: include/linux/cpuset.h:144
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
```
```
In mm/hugetlb.c (ffffffff8128944e)
Location: include/linux/cpuset.h:144
Inline: True
Inline callers:
  - mm/hugetlb.c:dequeue_huge_page_nodemask
```
```
In mm/slub.c (ffffffff8129ef8a)
Location: include/linux/cpuset.h:144
Inline: True
Inline callers:
  - mm/slub.c:___slab_alloc
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
In mm/filemap.c (ffffffff8120cb6d)
Location: include/linux/cpuset.h:144
Inline: True
```
```
In mm/page_alloc.c (ffffffff8126aca4)
Location: include/linux/cpuset.h:144
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
```
```
In mm/hugetlb.c (ffffffff8127b2ee)
Location: include/linux/cpuset.h:144
Inline: True
Inline callers:
  - mm/hugetlb.c:dequeue_huge_page_nodemask
```
```
In mm/slub.c (ffffffff81290aca)
Location: include/linux/cpuset.h:144
Inline: True
Inline callers:
  - mm/slub.c:___slab_alloc
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
In mm/filemap.c (ffffffff812176fd)
Location: include/linux/cpuset.h:144
Inline: True
```
```
In mm/page_alloc.c (ffffffff81276b54)
Location: include/linux/cpuset.h:144
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
```
```
In mm/hugetlb.c (ffffffff8128725e)
Location: include/linux/cpuset.h:144
Inline: True
Inline callers:
  - mm/hugetlb.c:dequeue_huge_page_nodemask
```
```
In mm/slub.c (ffffffff8129cd9a)
Location: include/linux/cpuset.h:144
Inline: True
Inline callers:
  - mm/slub.c:___slab_alloc
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
In mm/filemap.c (ffffffff812267ad)
Location: include/linux/cpuset.h:144
Inline: True
```
```
In mm/page_alloc.c (ffffffff812866fe)
Location: include/linux/cpuset.h:144
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
  - mm/page_alloc.c:__alloc_pages_slowpath
```
```
In mm/hugetlb.c (ffffffff812979de)
Location: include/linux/cpuset.h:144
Inline: True
Inline callers:
  - mm/hugetlb.c:dequeue_huge_page_nodemask
```
```
In mm/slub.c (ffffffff812ace01)
Location: include/linux/cpuset.h:144
Inline: True
Inline callers:
  - mm/slub.c:___slab_alloc
```
</details>
</li>
</ul>

## Differences
