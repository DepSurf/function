# Function: <code>set_compound_head</code>

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
In mm/page_alloc.c (ffffffff81192982)
Location: include/linux/page-flags.h:403
Inline: True
Inline callers:
  - mm/page_alloc.c:get_page_from_freelist
```
```
In mm/hugetlb.c (ffffffff811db046)
Location: include/linux/page-flags.h:403
Inline: True
Inline callers:
  - mm/hugetlb.c:prep_compound_gigantic_page
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
In mm/page_alloc.c (ffffffff811a999b)
Location: include/linux/page-flags.h:475
Inline: True
Inline callers:
  - mm/page_alloc.c:get_page_from_freelist
```
```
In mm/hugetlb.c (ffffffff811f91b6)
Location: include/linux/page-flags.h:475
Inline: True
Inline callers:
  - mm/hugetlb.c:prep_compound_gigantic_page
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
In mm/page_alloc.c (ffffffff811b9eff)
Location: include/linux/page-flags.h:491
Inline: True
Inline callers:
  - mm/page_alloc.c:get_page_from_freelist
```
```
In mm/hugetlb.c (ffffffff81209d84)
Location: include/linux/page-flags.h:491
Inline: True
Inline callers:
  - mm/hugetlb.c:prep_compound_gigantic_page
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
In mm/page_alloc.c (ffffffff811c2459)
Location: include/linux/page-flags.h:494
Inline: True
Inline callers:
  - mm/page_alloc.c:get_page_from_freelist
```
```
In mm/hugetlb.c (ffffffff81215314)
Location: include/linux/page-flags.h:494
Inline: True
Inline callers:
  - mm/hugetlb.c:prep_compound_gigantic_page
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
In mm/page_alloc.c (ffffffff811d6e0d)
Location: include/linux/page-flags.h:495
Inline: True
Inline callers:
  - mm/page_alloc.c:get_page_from_freelist
```
```
In mm/hugetlb.c (ffffffff8122fe57)
Location: include/linux/page-flags.h:495
Inline: True
Inline callers:
  - mm/hugetlb.c:prep_compound_gigantic_page
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
In mm/page_alloc.c (ffffffff811f872e)
Location: include/linux/page-flags.h:502
Inline: True
Inline callers:
  - mm/page_alloc.c:get_page_from_freelist
```
```
In mm/hugetlb.c (ffffffff812522bb)
Location: include/linux/page-flags.h:502
Inline: True
Inline callers:
  - mm/hugetlb.c:prep_compound_gigantic_page
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
In mm/page_alloc.c (ffffffff8120ad5b)
Location: include/linux/page-flags.h:519
Inline: True
Inline callers:
  - mm/page_alloc.c:get_page_from_freelist
```
```
In mm/hugetlb.c (ffffffff81266529)
Location: include/linux/page-flags.h:519
Inline: True
Inline callers:
  - mm/hugetlb.c:prep_compound_gigantic_page
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
In mm/page_alloc.c (ffffffff8126d471)
Location: include/linux/page-flags.h:552
Inline: True
Inline callers:
  - mm/page_alloc.c:prep_new_page
```
```
In mm/hugetlb.c (ffffffff812817c5)
Location: include/linux/page-flags.h:552
Inline: True
Inline callers:
  - mm/hugetlb.c:prep_compound_gigantic_page
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
In mm/page_alloc.c (ffffffff8127bfb1)
Location: include/linux/page-flags.h:552
Inline: True
Inline callers:
  - mm/page_alloc.c:prep_new_page
```
```
In mm/hugetlb.c (ffffffff81290b25)
Location: include/linux/page-flags.h:552
Inline: True
Inline callers:
  - mm/hugetlb.c:prep_compound_gigantic_page
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
In mm/page_alloc.c (ffffffff812af6e4)
Location: include/linux/page-flags.h:568
Inline: True
Inline callers:
  - mm/page_alloc.c:prep_compound_page
```
```
In mm/hugetlb.c (ffffffff812c3c69)
Location: include/linux/page-flags.h:568
Inline: True
Inline callers:
  - mm/hugetlb.c:prep_compound_gigantic_page
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
In mm/page_alloc.c (ffffffff812bb30c)
Location: include/linux/page-flags.h:572
Inline: True
Inline callers:
  - mm/page_alloc.c:prep_compound_page
```
```
In mm/hugetlb.c (ffffffff812cf8b2)
Location: include/linux/page-flags.h:572
Inline: True
Inline callers:
  - mm/hugetlb.c:prep_compound_gigantic_page
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
In mm/page_alloc.c (ffffffff812c045f)
Location: include/linux/page-flags.h:572
Inline: True
Inline callers:
  - mm/page_alloc.c:prep_compound_page
```
```
In mm/hugetlb.c (ffffffff812d6102)
Location: include/linux/page-flags.h:572
Inline: True
Inline callers:
  - mm/hugetlb.c:prep_compound_gigantic_page
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
In mm/page_alloc.c (ffffffff813031f2)
Location: include/linux/page-flags.h:592
Inline: True
Inline callers:
  - mm/page_alloc.c:prep_compound_page
```
```
In mm/hugetlb.c (ffffffff8131ca2b)
Location: include/linux/page-flags.h:592
Inline: True
Inline callers:
  - mm/hugetlb.c:prep_compound_gigantic_page
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
In mm/page_alloc.c (ffffffff81f1a58d)
Location: include/linux/page-flags.h:807
Inline: True
Inline callers:
  - mm/page_alloc.c:memmap_init_compound
  - mm/page_alloc.c:prep_compound_page
```
```
In mm/hugetlb.c (ffffffff813883b1)
Location: include/linux/page-flags.h:807
Inline: True
Inline callers:
  - mm/hugetlb.c:__prep_compound_gigantic_page
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
In mm/page_alloc.c (ffffffff820c23de)
Location: include/linux/page-flags.h:804
Inline: True
Inline callers:
  - mm/page_alloc.c:memmap_init_compound
  - mm/page_alloc.c:prep_compound_page
```
```
In mm/hugetlb.c (ffffffff81405908)
Location: include/linux/page-flags.h:804
Inline: True
Inline callers:
  - mm/hugetlb.c:__prep_compound_gigantic_folio
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
In mm/mm_init.c (ffffffff82145ef5)
Location: include/linux/page-flags.h:793
Inline: True
```
```
In mm/page_alloc.c (ffffffff8141c072)
Location: include/linux/page-flags.h:793
Inline: True
Inline callers:
  - mm/page_alloc.c:prep_compound_page
```
```
In mm/hugetlb.c (ffffffff81438e0a)
Location: include/linux/page-flags.h:793
Inline: True
Inline callers:
  - mm/hugetlb.c:__prep_compound_gigantic_folio
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
In mm/mm_init.c (ffffffff82228615)
Location: include/linux/page-flags.h:809
Inline: True
```
```
In mm/page_alloc.c (ffffffff81448be2)
Location: include/linux/page-flags.h:809
Inline: True
Inline callers:
  - mm/page_alloc.c:prep_compound_page
```
```
In mm/hugetlb.c (ffffffff8391aa2f)
Location: include/linux/page-flags.h:809
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_folio_init_tail_vmemmap
  - mm/hugetlb.c:__prep_compound_gigantic_folio
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
In mm/page_alloc.c (ffff800010313534)
Location: include/linux/page-flags.h:552
Inline: True
Inline callers:
  - mm/page_alloc.c:prep_new_page
```
```
In mm/hugetlb.c (ffff80001032e1bc)
Location: include/linux/page-flags.h:552
Inline: True
Inline callers:
  - mm/hugetlb.c:prep_compound_gigantic_page
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
In mm/page_alloc.c (c052e3c8)
Location: include/linux/page-flags.h:552
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
In mm/page_alloc.c (c0000000003e51ac)
Location: include/linux/page-flags.h:552
Inline: True
Inline callers:
  - mm/page_alloc.c:prep_new_page
```
```
In mm/hugetlb.c (c000000000406bf0)
Location: include/linux/page-flags.h:552
Inline: True
Inline callers:
  - mm/hugetlb.c:prep_compound_gigantic_page
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
In mm/page_alloc.c (ffffffe00021a8d6)
Location: include/linux/page-flags.h:552
Inline: True
Inline callers:
  - mm/page_alloc.c:prep_new_page
```
```
In mm/hugetlb.c (ffffffe00022c448)
Location: include/linux/page-flags.h:552
Inline: True
Inline callers:
  - mm/hugetlb.c:prep_compound_gigantic_page
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
In mm/page_alloc.c (ffffffff81274601)
Location: include/linux/page-flags.h:552
Inline: True
Inline callers:
  - mm/page_alloc.c:prep_new_page
```
```
In mm/hugetlb.c (ffffffff81289105)
Location: include/linux/page-flags.h:552
Inline: True
Inline callers:
  - mm/hugetlb.c:prep_compound_gigantic_page
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
In mm/page_alloc.c (ffffffff81266571)
Location: include/linux/page-flags.h:552
Inline: True
Inline callers:
  - mm/page_alloc.c:prep_new_page
```
```
In mm/hugetlb.c (ffffffff8127afa5)
Location: include/linux/page-flags.h:552
Inline: True
Inline callers:
  - mm/hugetlb.c:prep_compound_gigantic_page
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
In mm/page_alloc.c (ffffffff812723a1)
Location: include/linux/page-flags.h:552
Inline: True
Inline callers:
  - mm/page_alloc.c:prep_new_page
```
```
In mm/hugetlb.c (ffffffff81286f15)
Location: include/linux/page-flags.h:552
Inline: True
Inline callers:
  - mm/hugetlb.c:prep_compound_gigantic_page
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
In mm/page_alloc.c (ffffffff812821d1)
Location: include/linux/page-flags.h:552
Inline: True
Inline callers:
  - mm/page_alloc.c:prep_new_page
```
```
In mm/hugetlb.c (ffffffff812975e5)
Location: include/linux/page-flags.h:552
Inline: True
Inline callers:
  - mm/hugetlb.c:prep_compound_gigantic_page
```
</details>
</li>
</ul>

## Differences
