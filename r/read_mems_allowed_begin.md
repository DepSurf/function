# Function: <code>read_mems_allowed_begin</code>

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
In mm/filemap.c (ffffffff8118d5fc)
Location: include/linux/cpuset.h:105
Inline: True
```
```
In mm/page_alloc.c (ffffffff811924f9)
Location: include/linux/cpuset.h:105
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_nodemask
```
```
In mm/hugetlb.c (ffffffff811dad83)
Location: include/linux/cpuset.h:105
Inline: True
Inline callers:
  - mm/hugetlb.c:__alloc_buddy_huge_page
  - mm/hugetlb.c:alloc_huge_page
```
```
In mm/mempolicy.c (ffffffff811e07fd)
Location: include/linux/cpuset.h:105
Inline: True
Inline callers:
  - mm/mempolicy.c:alloc_pages_current
  - mm/mempolicy.c:alloc_pages_vma
```
```
In mm/slub.c (ffffffff811ea7f8)
Location: include/linux/cpuset.h:105
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
In mm/filemap.c (ffffffff811a01eb)
Location: include/linux/cpuset.h:114
Inline: True
```
```
In mm/page_alloc.c (ffffffff811ab0b3)
Location: include/linux/cpuset.h:114
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_nodemask
```
```
In mm/hugetlb.c (ffffffff811fac26)
Location: include/linux/cpuset.h:114
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:__alloc_buddy_huge_page
```
```
In mm/mempolicy.c (ffffffff811feac0)
Location: include/linux/cpuset.h:114
Inline: True
Inline callers:
  - mm/mempolicy.c:alloc_pages_current
  - mm/mempolicy.c:alloc_pages_vma
```
```
In mm/slub.c (ffffffff81209e0d)
Location: include/linux/cpuset.h:114
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
In mm/filemap.c (ffffffff811af62b)
Location: include/linux/cpuset.h:114
Inline: True
```
```
In mm/page_alloc.c (ffffffff811babfa)
Location: include/linux/cpuset.h:114
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
```
```
In mm/hugetlb.c (ffffffff8120b726)
Location: include/linux/cpuset.h:114
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_huge_page
  - mm/hugetlb.c:__alloc_buddy_huge_page
```
```
In mm/mempolicy.c (ffffffff81210300)
Location: include/linux/cpuset.h:114
Inline: True
Inline callers:
  - mm/mempolicy.c:alloc_pages_current
  - mm/mempolicy.c:alloc_pages_vma
```
```
In mm/slub.c (ffffffff8121be7d)
Location: include/linux/cpuset.h:114
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
In mm/filemap.c (ffffffff811b6518)
Location: include/linux/cpuset.h:133
Inline: True
```
```
In mm/page_alloc.c (ffffffff811c2c88)
Location: include/linux/cpuset.h:133
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
```
```
In mm/hugetlb.c (ffffffff8121447c)
Location: include/linux/cpuset.h:133
Inline: True
Inline callers:
  - mm/hugetlb.c:dequeue_huge_page_nodemask
```
```
In mm/slub.c (ffffffff812279e1)
Location: include/linux/cpuset.h:133
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
In mm/filemap.c (ffffffff811ca882)
Location: include/linux/cpuset.h:128
Inline: True
```
```
In mm/page_alloc.c (ffffffff811d79f5)
Location: include/linux/cpuset.h:128
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
```
```
In mm/hugetlb.c (ffffffff8122f038)
Location: include/linux/cpuset.h:128
Inline: True
Inline callers:
  - mm/hugetlb.c:dequeue_huge_page_nodemask
```
```
In mm/slub.c (ffffffff81243c33)
Location: include/linux/cpuset.h:128
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
In mm/filemap.c (ffffffff811eb8d2)
Location: include/linux/cpuset.h:128
Inline: True
```
```
In mm/page_alloc.c (ffffffff811f8be6)
Location: include/linux/cpuset.h:128
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
```
```
In mm/hugetlb.c (ffffffff812517f6)
Location: include/linux/cpuset.h:128
Inline: True
Inline callers:
  - mm/hugetlb.c:dequeue_huge_page_nodemask
```
```
In mm/slub.c (ffffffff8126636f)
Location: include/linux/cpuset.h:128
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
In mm/filemap.c (ffffffff811fc452)
Location: include/linux/cpuset.h:128
Inline: True
```
```
In mm/page_alloc.c (ffffffff8120b173)
Location: include/linux/cpuset.h:128
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
```
```
In mm/hugetlb.c (ffffffff81265bf6)
Location: include/linux/cpuset.h:128
Inline: True
Inline callers:
  - mm/hugetlb.c:dequeue_huge_page_nodemask
```
```
In mm/slub.c (ffffffff8127b0aa)
Location: include/linux/cpuset.h:128
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
In mm/filemap.c (ffffffff81213b1e)
Location: include/linux/cpuset.h:128
Inline: True
```
```
In mm/page_alloc.c (ffffffff81271409)
Location: include/linux/cpuset.h:128
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
```
```
In mm/hugetlb.c (ffffffff812810ed)
Location: include/linux/cpuset.h:128
Inline: True
Inline callers:
  - mm/hugetlb.c:dequeue_huge_page_nodemask
```
```
In mm/slub.c (ffffffff81296a40)
Location: include/linux/cpuset.h:128
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
In mm/filemap.c (ffffffff812212ee)
Location: include/linux/cpuset.h:130
Inline: True
```
```
In mm/page_alloc.c (ffffffff81280249)
Location: include/linux/cpuset.h:130
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
```
```
In mm/hugetlb.c (ffffffff81290d7d)
Location: include/linux/cpuset.h:130
Inline: True
Inline callers:
  - mm/hugetlb.c:dequeue_huge_page_nodemask
```
```
In mm/slub.c (ffffffff812a67fb)
Location: include/linux/cpuset.h:130
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
In mm/filemap.c (ffffffff8124e32a)
Location: include/linux/cpuset.h:130
Inline: True
```
```
In mm/page_alloc.c (ffffffff812b2a7e)
Location: include/linux/cpuset.h:130
Inline: True
```
```
In mm/hugetlb.c (ffffffff812c3625)
Location: include/linux/cpuset.h:130
Inline: True
Inline callers:
  - mm/hugetlb.c:dequeue_huge_page_nodemask
```
```
In mm/slub.c (ffffffff812dafe4)
Location: include/linux/cpuset.h:130
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
In mm/filemap.c (ffffffff8125873a)
Location: include/linux/cpuset.h:130
Inline: True
```
```
In mm/page_alloc.c (ffffffff812be5eb)
Location: include/linux/cpuset.h:130
Inline: True
```
```
In mm/hugetlb.c (ffffffff812cf5a3)
Location: include/linux/cpuset.h:130
Inline: True
Inline callers:
  - mm/hugetlb.c:dequeue_huge_page_nodemask
```
```
In mm/slub.c (ffffffff812e78d4)
Location: include/linux/cpuset.h:130
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
In mm/filemap.c (ffffffff8125cdc5)
Location: include/linux/cpuset.h:130
Inline: True
```
```
In mm/page_alloc.c (ffffffff812c367b)
Location: include/linux/cpuset.h:130
Inline: True
```
```
In mm/hugetlb.c (ffffffff812d677e)
Location: include/linux/cpuset.h:130
Inline: True
Inline callers:
  - mm/hugetlb.c:dequeue_huge_page_nodemask
```
```
In mm/slub.c (ffffffff812ef044)
Location: include/linux/cpuset.h:130
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
In mm/filemap.c (ffffffff81298d45)
Location: include/linux/cpuset.h:131
Inline: True
```
```
In mm/page_alloc.c (ffffffff813074fb)
Location: include/linux/cpuset.h:131
Inline: True
```
```
In mm/hugetlb.c (ffffffff8131c512)
Location: include/linux/cpuset.h:131
Inline: True
Inline callers:
  - mm/hugetlb.c:dequeue_huge_page_nodemask
```
```
In mm/slub.c (ffffffff81337354)
Location: include/linux/cpuset.h:131
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
In mm/filemap.c (ffffffff812ef5a9)
Location: include/linux/cpuset.h:146
Inline: True
```
```
In mm/page_alloc.c (ffffffff8136f814)
Location: include/linux/cpuset.h:146
Inline: True
```
```
In mm/hugetlb.c (ffffffff81387692)
Location: include/linux/cpuset.h:146
Inline: True
Inline callers:
  - mm/hugetlb.c:dequeue_huge_page_nodemask
```
```
In mm/slub.c (ffffffff813a8c54)
Location: include/linux/cpuset.h:146
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
In mm/filemap.c (ffffffff8135a0be)
Location: include/linux/cpuset.h:146
Inline: True
```
```
In mm/page_alloc.c (ffffffff813ebe34)
Location: include/linux/cpuset.h:146
Inline: True
```
```
In mm/hugetlb.c (ffffffff81405ac2)
Location: include/linux/cpuset.h:146
Inline: True
Inline callers:
  - mm/hugetlb.c:dequeue_huge_page_nodemask
```
```
In mm/slub.c (ffffffff81429d1f)
Location: include/linux/cpuset.h:146
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
In mm/filemap.c (ffffffff8138bb1e)
Location: include/linux/cpuset.h:141
Inline: True
```
```
In mm/page_alloc.c (ffffffff81420e27)
Location: include/linux/cpuset.h:141
Inline: True
```
```
In mm/hugetlb.c (ffffffff81438ffb)
Location: include/linux/cpuset.h:141
Inline: True
Inline callers:
  - mm/hugetlb.c:dequeue_hugetlb_folio_nodemask
```
```
In mm/slub.c (ffffffff8145f0ff)
Location: include/linux/cpuset.h:141
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
In mm/filemap.c (ffffffff813b568e)
Location: include/linux/cpuset.h:142
Inline: True
```
```
In mm/page_alloc.c (ffffffff8144dbf6)
Location: include/linux/cpuset.h:142
Inline: True
```
```
In mm/slub.c (ffffffff8145a26e)
Location: include/linux/cpuset.h:142
Inline: True
Inline callers:
  - mm/slub.c:get_any_partial
```
```
In mm/hugetlb.c (ffffffff81472b2b)
Location: include/linux/cpuset.h:142
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
In mm/filemap.c (ffff8000102adfb4)
Location: include/linux/cpuset.h:130
Inline: True
```
```
In mm/page_alloc.c (ffff800010318194)
Location: include/linux/cpuset.h:130
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
```
```
In mm/hugetlb.c (ffff80001032d87c)
Location: include/linux/cpuset.h:130
Inline: True
Inline callers:
  - mm/hugetlb.c:dequeue_huge_page_nodemask
```
```
In mm/slub.c (ffff800010347b10)
Location: include/linux/cpuset.h:130
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
In mm/page_alloc.c (c0532704)
Location: include/linux/cpuset.h:130
Inline: True
Inline callers:
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
In mm/filemap.c (c000000000363094)
Location: include/linux/cpuset.h:130
Inline: True
```
```
In mm/page_alloc.c (c0000000003ea860)
Location: include/linux/cpuset.h:130
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
```
```
In mm/hugetlb.c (c000000000405ebc)
Location: include/linux/cpuset.h:130
Inline: True
Inline callers:
  - mm/hugetlb.c:dequeue_huge_page_nodemask
```
```
In mm/slub.c (c000000000425ec4)
Location: include/linux/cpuset.h:130
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
In mm/page_alloc.c (ffffffe00021dfde)
Location: include/linux/cpuset.h:130
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
```
```
In mm/hugetlb.c (ffffffe00022c060)
Location: include/linux/cpuset.h:130
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
In mm/filemap.c (ffffffff8121993e)
Location: include/linux/cpuset.h:130
Inline: True
```
```
In mm/page_alloc.c (ffffffff81278899)
Location: include/linux/cpuset.h:130
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
```
```
In mm/hugetlb.c (ffffffff8128935d)
Location: include/linux/cpuset.h:130
Inline: True
Inline callers:
  - mm/hugetlb.c:dequeue_huge_page_nodemask
```
```
In mm/slub.c (ffffffff8129eddb)
Location: include/linux/cpuset.h:130
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
In mm/filemap.c (ffffffff8120cb4e)
Location: include/linux/cpuset.h:130
Inline: True
```
```
In mm/page_alloc.c (ffffffff8126a789)
Location: include/linux/cpuset.h:130
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
```
```
In mm/hugetlb.c (ffffffff8127b1fd)
Location: include/linux/cpuset.h:130
Inline: True
Inline callers:
  - mm/hugetlb.c:dequeue_huge_page_nodemask
```
```
In mm/slub.c (ffffffff8129091b)
Location: include/linux/cpuset.h:130
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
In mm/filemap.c (ffffffff812176de)
Location: include/linux/cpuset.h:130
Inline: True
```
```
In mm/page_alloc.c (ffffffff81276639)
Location: include/linux/cpuset.h:130
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
```
```
In mm/hugetlb.c (ffffffff8128716d)
Location: include/linux/cpuset.h:130
Inline: True
Inline callers:
  - mm/hugetlb.c:dequeue_huge_page_nodemask
```
```
In mm/slub.c (ffffffff8129cbeb)
Location: include/linux/cpuset.h:130
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
In mm/filemap.c (ffffffff8122678e)
Location: include/linux/cpuset.h:130
Inline: True
```
```
In mm/page_alloc.c (ffffffff812861f9)
Location: include/linux/cpuset.h:130
Inline: True
Inline callers:
  - mm/page_alloc.c:__alloc_pages_slowpath
```
```
In mm/hugetlb.c (ffffffff812978ed)
Location: include/linux/cpuset.h:130
Inline: True
Inline callers:
  - mm/hugetlb.c:dequeue_huge_page_nodemask
```
```
In mm/slub.c (ffffffff812acc4f)
Location: include/linux/cpuset.h:130
Inline: True
Inline callers:
  - mm/slub.c:___slab_alloc
```
</details>
</li>
</ul>

## Differences
