# Function: <code>set_compound_page_dtor</code>

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
In mm/page_alloc.c (ffffffff8119294f)
Location: include/linux/mm.h:540
Inline: True
Inline callers:
  - mm/page_alloc.c:get_page_from_freelist
```
```
In mm/hugetlb.c (ffffffff811da1aa)
Location: include/linux/mm.h:540
Inline: True
Inline callers:
  - mm/hugetlb.c:prep_new_huge_page
  - mm/hugetlb.c:update_and_free_page
  - mm/hugetlb.c:__alloc_buddy_huge_page
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
In mm/page_alloc.c (ffffffff811a9952)
Location: include/linux/mm.h:587
Inline: True
Inline callers:
  - mm/page_alloc.c:get_page_from_freelist
```
```
In mm/hugetlb.c (ffffffff811f9004)
Location: include/linux/mm.h:587
Inline: True
Inline callers:
  - mm/hugetlb.c:__alloc_buddy_huge_page
  - mm/hugetlb.c:prep_new_huge_page
  - mm/hugetlb.c:update_and_free_page
```
```
In mm/huge_memory.c (ffffffff81216d16)
Location: include/linux/mm.h:587
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
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
In mm/page_alloc.c (ffffffff811b9eb6)
Location: include/linux/mm.h:574
Inline: True
Inline callers:
  - mm/page_alloc.c:get_page_from_freelist
```
```
In mm/hugetlb.c (ffffffff81209bf4)
Location: include/linux/mm.h:574
Inline: True
Inline callers:
  - mm/hugetlb.c:__alloc_buddy_huge_page
  - mm/hugetlb.c:prep_new_huge_page
  - mm/hugetlb.c:update_and_free_page
```
```
In mm/huge_memory.c (ffffffff812292c4)
Location: include/linux/mm.h:574
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
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
In mm/page_alloc.c (ffffffff811c2410)
Location: include/linux/mm.h:630
Inline: True
Inline callers:
  - mm/page_alloc.c:get_page_from_freelist
```
```
In mm/hugetlb.c (ffffffff8121436e)
Location: include/linux/mm.h:630
Inline: True
Inline callers:
  - mm/hugetlb.c:__alloc_buddy_huge_page
  - mm/hugetlb.c:prep_new_huge_page
  - mm/hugetlb.c:update_and_free_page
```
```
In mm/huge_memory.c (ffffffff812350f7)
Location: include/linux/mm.h:630
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
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
In mm/page_alloc.c (ffffffff811d6dc1)
Location: include/linux/mm.h:647
Inline: True
Inline callers:
  - mm/page_alloc.c:get_page_from_freelist
```
```
In mm/hugetlb.c (ffffffff8122ef2e)
Location: include/linux/mm.h:647
Inline: True
Inline callers:
  - mm/hugetlb.c:__alloc_buddy_huge_page
  - mm/hugetlb.c:prep_new_huge_page
  - mm/hugetlb.c:update_and_free_page
```
```
In mm/huge_memory.c (ffffffff812534da)
Location: include/linux/mm.h:647
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
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
In mm/page_alloc.c (ffffffff811f86e1)
Location: include/linux/mm.h:689
Inline: True
Inline callers:
  - mm/page_alloc.c:get_page_from_freelist
```
```
In mm/hugetlb.c (ffffffff8125248a)
Location: include/linux/mm.h:689
Inline: True
Inline callers:
  - mm/hugetlb.c:prep_new_huge_page
  - mm/hugetlb.c:update_and_free_page
```
```
In mm/huge_memory.c (ffffffff81277b0a)
Location: include/linux/mm.h:689
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
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
In mm/page_alloc.c (ffffffff8120ad14)
Location: include/linux/mm.h:717
Inline: True
Inline callers:
  - mm/page_alloc.c:get_page_from_freelist
```
```
In mm/hugetlb.c (ffffffff812666ea)
Location: include/linux/mm.h:717
Inline: True
Inline callers:
  - mm/hugetlb.c:prep_new_huge_page
  - mm/hugetlb.c:update_and_free_page
```
```
In mm/huge_memory.c (ffffffff8128c127)
Location: include/linux/mm.h:717
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
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
In mm/page_alloc.c (ffffffff8126d42b)
Location: include/linux/mm.h:783
Inline: True
Inline callers:
  - mm/page_alloc.c:prep_new_page
```
```
In mm/hugetlb.c (ffffffff828d84cf)
Location: include/linux/mm.h:783
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:alloc_fresh_huge_page
  - mm/hugetlb.c:update_and_free_page
```
```
In mm/huge_memory.c (ffffffff812a6d22)
Location: include/linux/mm.h:783
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
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
In mm/page_alloc.c (ffffffff8127bf6b)
Location: include/linux/mm.h:778
Inline: True
Inline callers:
  - mm/page_alloc.c:prep_new_page
```
```
In mm/hugetlb.c (ffffffff828e096c)
Location: include/linux/mm.h:778
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:alloc_fresh_huge_page
  - mm/hugetlb.c:update_and_free_page
```
```
In mm/huge_memory.c (ffffffff812b81cd)
Location: include/linux/mm.h:778
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
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
In mm/page_alloc.c (ffffffff812af6a3)
Location: include/linux/mm.h:873
Inline: True
Inline callers:
  - mm/page_alloc.c:prep_compound_page
```
```
In mm/hugetlb.c (ffffffff812c47fa)
Location: include/linux/mm.h:873
Inline: True
Inline callers:
  - mm/hugetlb.c:prep_new_huge_page
  - mm/hugetlb.c:update_and_free_page
```
```
In mm/huge_memory.c (ffffffff812ea92a)
Location: include/linux/mm.h:873
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
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
In mm/page_alloc.c (ffffffff812bb315)
Location: include/linux/mm.h:906
Inline: True
Inline callers:
  - mm/page_alloc.c:prep_compound_page
```
```
In mm/hugetlb.c (ffffffff812d0493)
Location: include/linux/mm.h:906
Inline: True
Inline callers:
  - mm/hugetlb.c:prep_new_huge_page
  - mm/hugetlb.c:update_and_free_page
```
```
In mm/huge_memory.c (ffffffff812f5db9)
Location: include/linux/mm.h:906
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
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
In mm/page_alloc.c (ffffffff812c0468)
Location: include/linux/mm.h:929
Inline: True
Inline callers:
  - mm/page_alloc.c:prep_compound_page
```
```
In mm/hugetlb.c (ffffffff812d6632)
Location: include/linux/mm.h:929
Inline: True
Inline callers:
  - mm/hugetlb.c:__prep_new_huge_page
  - mm/hugetlb.c:remove_hugetlb_page
```
```
In mm/huge_memory.c (ffffffff812fc1cb)
Location: include/linux/mm.h:929
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
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
In mm/page_alloc.c (ffffffff813031ff)
Location: include/linux/mm.h:933
Inline: True
Inline callers:
  - mm/page_alloc.c:prep_compound_page
```
```
In mm/hugetlb.c (ffffffff8131c442)
Location: include/linux/mm.h:933
Inline: True
Inline callers:
  - mm/hugetlb.c:__prep_new_huge_page
  - mm/hugetlb.c:add_hugetlb_page
```
```
In mm/huge_memory.c (ffffffff81346027)
Location: include/linux/mm.h:933
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
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
In mm/page_alloc.c (ffffffff81f1a59a)
Location: include/linux/mm.h:888
Inline: True
Inline callers:
  - mm/page_alloc.c:memmap_init_compound
  - mm/page_alloc.c:prep_compound_page
```
```
In mm/hugetlb.c (ffffffff81393e55)
Location: include/linux/mm.h:888
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_and_dissolve_huge_page
  - mm/hugetlb.c:prep_new_huge_page
  - mm/hugetlb.c:add_hugetlb_page
```
```
In mm/huge_memory.c (ffffffff813bc032)
Location: include/linux/mm.h:888
Inline: True
Inline callers:
  - mm/huge_memory.c:prep_transhuge_page
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
In mm/page_alloc.c (ffffffff820c23f7)
Location: include/linux/mm.h:999
Inline: True
Inline callers:
  - mm/page_alloc.c:memmap_init_compound
  - mm/page_alloc.c:prep_compound_page
```
```
In mm/huge_memory.c (ffffffff8143e5c2)
Location: include/linux/mm.h:999
Inline: True
Inline callers:
  - mm/huge_memory.c:prep_transhuge_page
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
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffff8000103134f0)
Location: include/linux/mm.h:778
Inline: True
Inline callers:
  - mm/page_alloc.c:prep_new_page
```
```
In mm/hugetlb.c (ffff80001032ed88)
Location: include/linux/mm.h:778
Inline: True
Inline callers:
  - mm/hugetlb.c:prep_new_huge_page
  - mm/hugetlb.c:update_and_free_page
```
```
In mm/huge_memory.c (ffff8000103587f4)
Location: include/linux/mm.h:778
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
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
In mm/page_alloc.c (c052e384)
Location: include/linux/mm.h:778
Inline: True
Inline callers:
  - mm/page_alloc.c:prep_new_page
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
In mm/page_alloc.c (c0000000003e5144)
Location: include/linux/mm.h:778
Inline: True
Inline callers:
  - mm/page_alloc.c:prep_new_page
```
```
In mm/hugetlb.c (c000000000407488)
Location: include/linux/mm.h:778
Inline: True
Inline callers:
  - mm/hugetlb.c:prep_new_huge_page
```
```
In mm/huge_memory.c (c000000000441578)
Location: include/linux/mm.h:778
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
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
In mm/page_alloc.c (ffffffe00021a89e)
Location: include/linux/mm.h:778
Inline: True
Inline callers:
  - mm/page_alloc.c:prep_new_page
```
```
In mm/hugetlb.c (ffffffe000018016)
Location: include/linux/mm.h:778
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:alloc_fresh_huge_page
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
In mm/page_alloc.c (ffffffff812745bb)
Location: include/linux/mm.h:778
Inline: True
Inline callers:
  - mm/page_alloc.c:prep_new_page
```
```
In mm/hugetlb.c (ffffffff828c9820)
Location: include/linux/mm.h:778
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:alloc_fresh_huge_page
  - mm/hugetlb.c:update_and_free_page
```
```
In mm/huge_memory.c (ffffffff812b07ad)
Location: include/linux/mm.h:778
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
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
In mm/page_alloc.c (ffffffff8126652b)
Location: include/linux/mm.h:778
Inline: True
Inline callers:
  - mm/page_alloc.c:prep_new_page
```
```
In mm/hugetlb.c (ffffffff828c1f45)
Location: include/linux/mm.h:778
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:alloc_fresh_huge_page
  - mm/hugetlb.c:update_and_free_page
```
```
In mm/huge_memory.c (ffffffff812a1a3f)
Location: include/linux/mm.h:778
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
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
In mm/page_alloc.c (ffffffff8127235b)
Location: include/linux/mm.h:778
Inline: True
Inline callers:
  - mm/page_alloc.c:prep_new_page
```
```
In mm/hugetlb.c (ffffffff828dc5a0)
Location: include/linux/mm.h:778
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:alloc_fresh_huge_page
  - mm/hugetlb.c:update_and_free_page
```
```
In mm/huge_memory.c (ffffffff812ae5bd)
Location: include/linux/mm.h:778
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
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
In mm/page_alloc.c (ffffffff8128218b)
Location: include/linux/mm.h:778
Inline: True
Inline callers:
  - mm/page_alloc.c:prep_new_page
```
```
In mm/hugetlb.c (ffffffff828e19bc)
Location: include/linux/mm.h:778
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:alloc_fresh_huge_page
  - mm/hugetlb.c:update_and_free_page
```
```
In mm/huge_memory.c (ffffffff812be91a)
Location: include/linux/mm.h:778
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
</details>
</li>
</ul>

## Differences
